---
source-git-commit: 0376fe6500551442b28831d5742ecbbc9363ab19
workflow-type: tm+mt
source-wordcount: '828'
ht-degree: 1%

---
# Generatore di problemi noti - Substance 3D Painter

Automatizza la generazione del documento markdown dei problemi noti per Substance 3D Painter, pubblicato su:
`https://helpx.adobe.com/it/substance-3d-painter/release-notes/know-issues.html`

I problemi derivano dall&#39;epic Jira `SBSFOUR-6267`. Lo script recupera tutti i problemi, filtra tutto ciò che è già stato risolto nella versione di destinazione e genera un file di markdown formattato pronto per il commit.

&#x200B;---

## Avvio rapido

Questi passaggi presuppongono che la configurazione singola seguente sia già stata completata.

1. Connetti a **VPN GlobalProtect**
2. Imposta `TARGET_VERSION` nel file `.env` sulla versione per cui stai generando documenti (ad esempio `12.0.3`)
3. Eseguire lo script dalla directory `scripts/known-issues-automation/`:

   ```
   python fetch_known_issues.py
   ```

4. Controllare il riepilogo dell&#39;output: riporta quanti problemi sono stati recuperati e quanti esclusi
5. Copia `known-issues.md` generato in `help/release-notes/known-issues.md`

> In caso di problemi mancanti o imprevisti, esaminare `raw_issues.json` per verificare esattamente cosa ha restituito Jira prima di applicare il filtro.

&#x200B;---

## Configurazione singola

### &#x200B;1. Dipendenze di installazione

```bash
pip install requests python-dotenv
```

### &#x200B;2. Crea il file `.env`

```bash
cp .env.example .env
```

### &#x200B;3. Ottieni un token di accesso personale Jira

1. Accedi a `https://jira.corp.adobe.com`
2. Vai al tuo profilo → **Token di accesso personale** nella barra laterale sinistra
3. Fai clic su **Crea token**, assegnagli un nome e copia il valore generato

> I PAT non scadono al termine della sessione del browser, rendendoli più affidabili dei cookie di sessione per l’accesso alle API con script.

### &#x200B;4. Compila il file `.env`

```
JIRA_PAT=your-personal-access-token
TARGET_VERSION=12.0.3
OUTPUT_FILE=known-issues.md
```

`TARGET_VERSION` è la versione di Substance 3D Painter per la quale stai generando la pagina dei problemi noti. Controlla quali problemi risolti sono esclusi. Vedere [Logica di filtro](#filtering-logic) di seguito.

&#x200B;---

## Struttura del repository

```
.
├── README.md                  # This file
├── fetch_known_issues.py      # Main script
├── .env.example               # Environment variable template (safe to commit)
├── .env                       # Your local credentials — never commit this
├── raw_issues.json            # Raw Jira dump from last run — gitignored
└── known-issues.md            # Generated output from last run — gitignored
```

&#x200B;---

## Riferimento Jira

| Campo | Valore |
|---|---|
| Istanza Jira | `https://jira.corp.adobe.com` |
| Chiave progetto | `SBSFOUR` |
| Problemi noti epici | `SBSFOUR-6267` |

Tutti i problemi noti devono essere collegati a questo epic per essere visualizzati nel documento generato. Se un problema deve essere aggiunto o rimosso dalla pagina, aggiorna l’epica in Jira anziché modificare manualmente il markdown.

&#x200B;---

## Funzionamento dello script

### Passaggio 1 - Recupero

Lo script esegue una query sull’API REST di Jira utilizzando JQL:

```
"Epic Link" = SBSFOUR-6267 ORDER BY created ASC
```

I risultati vengono impaginati a 50 problemi per pagina. Per ogni problema sono stati recuperati i seguenti campi: `summary`, `issuetype`, `status`, `affectedVersions`, `fixVersions`, `labels`.

L&#39;autenticazione utilizza un token Bearer da `JIRA_PAT`. L&#39;istanza Jira aziendale utilizza un certificato SSL interno, pertanto la verifica del certificato è disabilitata per queste richieste. Questo è il comportamento previsto sulla rete Adobe.

### Fase 2 — Doppiaggio raw

Prima di applicare filtri o formattazioni, lo script scrive `raw_issues.json`. Questa è un’istantanea semplificata di ogni problema restituito da Jira, ed è sempre generata indipendentemente da ciò che succede dopo. Se l&#39;output non viene visualizzato correttamente, esaminare prima questo file, in quanto mostra esattamente quali dati ha fornito Jira.

### Passaggio 3 — Filtro

I problemi vengono filtrati utilizzando due regole applicate contemporaneamente:

1. **Filtro stato** — solo `Backlog` e `Dev In Progress` problemi sono problemi noti attivi. I problemi con stato `Fixed` sono candidati all&#39;esclusione, soggetto alla verifica della versione seguente.

2. **Filtro versione**: un problema `Fixed` è escluso solo se una delle versioni corrette è minore o uguale a `TARGET_VERSION`. Se la versione della correzione è superiore a `TARGET_VERSION`, il problema è ancora incluso perché la correzione non è stata spedita per la versione documentata.

Questo gestisce il caso in cui due versioni sono in fase di sviluppo contemporaneamente: un problema risolto in `12.1.0` rimane un problema noto per `12.0.3`.

Vedere [Logica filtro](#filtering-logic) per la tabella delle decisioni completa.

### Passaggio 4 — Analisi delle categorie

Ogni riepilogo del problema viene analizzato per i tag di categoria all&#39;inizio della stringa:

- `[Shader] Some description` → categorie: `["Shader"]`, descrizione: `"Some description"`
- `[Crash][Engine] Some description` → categorie: `["Crash", "Engine"]`, descrizione: `"Some description"`
- `No brackets here` → nessuna categoria, trattata come non classificata

La **categoria primaria** è sempre il primo tag. Determina il raggruppamento e il posizionamento della sezione.

### Passaggio 5 — Raggruppamento e ordinamento

I problemi sono così organizzati:

- I problemi sono raggruppati per categoria principale
- I gruppi vengono ordinati in base al numero di problemi, decrescente (prima i gruppi più grandi).
- Nella parte superiore del documento vengono visualizzati i gruppi con più problemi
- I gruppi con un solo problema e gli eventuali problemi senza categoria vengono visualizzati dopo i gruppi con più problemi senza intestazione di sezione
- I problemi con `[Crash]` come categoria primaria vengono sempre inseriti per ultimi, in una sezione `## Stability`

### Passaggio 6 — Formattazione e scrittura

Lo script genera `known-issues.md` con:

- Frontespizio YAML (metadati helpx)
- Intestazione `# Known issues` con un paragrafo intro che indica la versione di destinazione
- Problemi formattati come: `` * `[Category]` Description ``
- Problemi con più categorie: `` * `[Category1]` `[Category2]` Description ``
- Righe vuote tra gruppi di categorie
- Una sezione `## Stability` alla fine per problemi di arresto anomalo

&#x200B;---

## Logica filtro

| Stato | Correggere il set di versioni? | Correggi versione e destinazione | Incluso? |
|---|---|---|---|
| `Backlog` | — | — | Sì |
| `Dev In Progress` | — | — | Sì |
| `Fixed` | No | — | No (escluso in modo conservativo) |
| `Fixed` | Sì | Correggi versione ≤ destinazione | No (già spedito) |
| `Fixed` | Sì | Correggi versione > destinazione | Sì (la correzione è in una versione futura) |

&#x200B;---

## Formato di output

```markdown
---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/release-notes/know-issues.html"
...
---

# Known issues

This page lists all the active known issues present in v12.0.3 of Substance 3D Painter:

* `[Engine]` Error when using Smart Materials if Texture Set has no tile 1001
* `[Engine]` Geometry mask shows artifacts at UV borders with instanced layers

* `[Shader]` user0 channel always can not be read as sRGB with specific shader

* `[Export]` GLTF exports at the wrong size
* `[Import]` Cannot import obj file with "nan" values

## Stability

* `[Crash]` Select "Export mesh" when mesh failed to load
```

**Nota di formattazione:** i tag di categoria utilizzano il ritorno a capo singolo — `` `[Category]` `` — non il doppio ritorno a capo. Il documento legacy gestito manualmente conteneva errori di doppio segno di spunta indietro; lo script produce sempre il formato corretto.

&#x200B;---

## Risoluzione dei problemi

**401 Non Autorizzato**
- Conferma connessione a **GlobalProtect VPN**
- Il tuo PAT potrebbe essere scaduto o essere stato revocato. Generane uno nuovo in `https://jira.corp.adobe.com/secure/ViewProfile.jspa` e aggiorna il tuo `.env`

Errore **`JIRA_PAT is not set`**
- Assicurati di aver creato un file `.env` da `.env.example` e compilato il token
- Conferma l&#39;esecuzione dello script dalla directory `scripts/known-issues-automation/` in modo che `python-dotenv` possa trovare il file `.env`

**Problemi mancanti nell&#39;output**
- Verifica `raw_issues.json`: se il problema non si verifica, significa che non è collegato all&#39;epic `SBSFOUR-6267` in Jira
- Se il problema si trova in `raw_issues.json` ma non nell&#39;output, è stato escluso dal filtro. Controllare lo stato e correggere la versione in base a `TARGET_VERSION`

Avviso **`TARGET_VERSION`in fase di esecuzione**
- Lo script verrà eseguito ma escluderà in modo conservativo tutti i problemi relativi a `Fixed` se `TARGET_VERSION` non è impostato. Impostalo sempre prima di generare il documento finale.
