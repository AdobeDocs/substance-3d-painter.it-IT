---
helpx_url: 'https://helpx.adobe.com/substance-3d-painter/release-notes/all-changes.html'
breadcrumb-title: ''
description: Esamina tutte le modifiche e gli aggiornamenti nelle versioni di Substance 3D Painter per tenere traccia dell’evoluzione delle funzioni e dei miglioramenti nel tempo.
helpx_creative_field: ''
helpx_description: Painter > Release notes > All Changes
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Tutte le modifiche
user-guide-description: ''
user-guide-title: ''
hold: false
source-git-commit: 9bb3d9d70fb00c8817a11c2938292aa337279b74
workflow-type: tm+mt
source-wordcount: '33992'
ht-degree: 0%

---


# Tutte le modifiche

Questa pagina contiene le note sulla versione per tutte le versioni precedenti di Substance 3D Painter, ordinate dalla più recente alla meno recente.

>[!NOTE]
>
> Per visualizzare i problemi noti che possono influire su Painter, consulta la [pagina dedicata alla documentazione](known-issues.md).

## Versione 12

### 12.1.3

Data di pubblicazione: **2026/08/26**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* Aggiornamento del motore di Substance alla versione 9.4.6

**Corretto:**

* [Il selettore scala di grigi] rimane aperto dopo aver modificato lo strumento
* [Inclina al forno] La correzione dell’inclinazione si interrompe quando si disegna e si annulla
* [L&#39;interazione dello strumento di proiezione] nella finestra della vista è bloccata dallo strumento di proiezione
* [Traccia dinamica] Parametri di traccia dinamica mancanti nelle proprietà del pennello
* L’esportazione in rete non funziona più

### 12.1.2

Data di pubblicazione: **2026/08/03**

Riepilogo: **Versione secondaria**

**Corretto:**

* \[Arresto anomalo\] Alcune Substance possono causare un arresto anomalo durante il rendering
* \[Arresto anomalo\] Reimporta trama in modalità cottura al forno
* \[Arresto anomalo\] Un errore di inizializzazione della visualizzazione della grafica può causare un arresto anomalo
* \[Arresto anomalo\] Durante l’aggiornamento del registro, in alcuni casi l’esportazione delle texture può bloccarsi
* \[Arresto anomalo\] Arresto anomalo in modalità cottura in alcuni casi durante il caricamento/aggiornamento della mappa dell&#39;ambiente
* \[Baking\] Il riavvio di bake dopo la modifica del file di poly elevato può provocare un blocco
* \[Invia a Photoshop\] Non riesce a esportare la maschera di livello
* Il risultato del punto di ancoraggio \[Motore\] non viene visualizzato tra una maschera e un canale di colore

### 12.1.1

Data di pubblicazione: <b>2026/07/09</b>

Riepilogo: versione secondaria

Aggiunto:

* [Inclina al forno] Modo normale base di inclinazione esposta: mesh o per triangle
* [Proprietà] Rendi i colori uniformi sempre ripristinati al valore predefinito del canale
* [OpenPBR] Raggruppare i canali per categorie nella finestra Esporta texture per la creazione di modelli di output
* Aggiornamento del motore di Substance alla versione 9.4.5

Fisso:

* [Il progetto] L&#39;apertura e il salvataggio di alcuni progetti può richiedere più tempo del solito
* [Arresto anomalo] Il ricaricamento di più trame può causare un arresto anomalo
* [Arresto anomalo] L’eliminazione di un canale in modalità di visualizzazione maschera causa un arresto anomalo
* [Arresto anomalo] Alcune Substance possono causare un arresto anomalo durante il rendering
* [Inclina inclinazione] lo strumento selezionato in inclina rimane selezionato dopo il passaggio alla modalità di disegno
* [Impostazioni comuni di cottura] Le impostazioni della distanza di gabbia non aggiornano la visualizzazione di cage wireframe e shader
* La modalità &quot;Vicina spazio 3D&quot; del riempimento UV del [Motore] non funziona correttamente su triangoli sottili
* Il risultato del punto di ancoraggio [del motore] non viene visualizzato tra una maschera e un canale di colore

### 12.1.0

Data di pubblicazione: <b>2026/06/23</b>

Riepilogo: <b>Questo aggiornamento è una versione principale e contiene miglioramenti dei forni con il nuovo stato dell&#39;interfaccia utente predefinito di cottura al forno, la mappa di inclinazione del disegno, il rebake automatico, la nuova opzione per lo srotolamento UV automatico per trame e OpenPBR su superfici dure. Per ulteriori dettagli, vedere le note sulla versione complete.</b>

<b>Aggiunto</b>:

* [Inclina al forno] Inclina strumenti di pittura
* [Inclina al forno] Aggiungete effetti visivi vettoriali dell&#39;ombreggiatura dell&#39;anteprima dell&#39;inclinazione e della direzione dell&#39;inclinazione quando colorate la mappa dell&#39;inclinazione
* [Skew Baking] Aggiungi opzione protezione bordi
* [Inclina al forno] Ripetizione automatica
* [Skew Baking] Rielaborare l&#39;interfaccia utente dell&#39;elenco mappa trama
* [Inclina in forno] Dividi mappa trama / Impostazioni comuni di cottura + Sposta impostazioni comuni fuori dall&#39;elenco mappa trama solo colore di base o maschera
* [Skew Baking] Cambiare i pulsanti della barra degli strumenti della finestra della vista
* [Skew Baking] Mostra/Nascondi simmetria per il pennello nella barra degli strumenti superiore
* [Skew Baking] Opzioni di ridenominazione nel menu di sincronizzazione della mappa mesh
* [Inclina baking] Aggiornare le finestre di dialogo Sincronizza e Stato controllato
* [Inclina cottura] Crea variante del selettore colore in scala di grigio
* [Skew Baking] Icona Aggiorna modalità di cottura
* [Auto Unwrap] Opzione Integra superficie dura (Integrate Hard Surface)
* [OpenPBR] Aggiungi il supporto per l’OpenPBR 1.1
* [OpenPBR] Rendi OpenPBR il flusso di lavoro e lo shader predefiniti
* [OpenPBR] Importa materiali e texture OpenPBR tramite USD
* [OpenPBR] Esportare materiali e texture di OpenPBR tramite USD
* [OpenPBR] Aggiornare la finestra Esporta texture per visualizzare la convenzione di denominazione dell&#39;OpenPBR
* [OpenPBR] Aggiungi documentazione sulle modifiche all’OpenPBR di supporto
* [OpenPBR]&#x200B;[Iray] Aggiungi un nuovo MDL per supportare l&#39;OpenPBR 1.1 in Iray
* Diversi miglioramenti minori delle esportazioni in USD
* [UI] Aggiungete un avviso nella finestra della vista quando tentate di colorare su un altro set di texture
* [Appiattisci] Consenti di appiattire tutti i livelli istanziati tra set di texture
* [Impostazioni set texture] Consente di selezionare più canali contemporaneamente tramite una nuova finestra
* [History] Aggiornare il &quot;valore&quot; della voce Annulla per riflettere il nome del parametro
* [Pila di livelli] Rendi gli effetti di riempimento nelle maschere predefiniti sul bianco (1,0)
* [Substance] Aggiungi nuovo input mappa motore &quot;mesh_hard_edges_triangle&quot;
* [Substance] Aggiungi nuovo input mappa motore &quot;mesh_hard_edges&quot;
* [Shader] Impedire alle istanze dello shader di condividere gli stessi nomi
* [Shader] Utilizza lo shader dal modello di progetto quando importi un file USD o GLTF
* Aggiornamento dell&#39;Adobe Color Engine alla versione 7.0
* Aggiornamento della versione minima MacOSX alla versione 13.0 (Ventura)
* [Content] Nuovi modelli di progetto per l&#39;OpenPBR
* [Content] Aggiorna i progetti di esempio per utilizzare il nuovo OpenPBR shader
* [Python] Espandi l’API maschera geometria per consentire le modalità di inclusione ed esclusione, come nell’interfaccia utente

<b>Risolto</b>:

* [Arresto anomalo]&#x200B;[Impostazioni mappe trama] Applica le impostazioni ad altri set di texture
* [Arresto anomalo] Quando si cuoce la curvatura dalla mappa senza spazio mondo normale
* [Arresto anomalo]&#x200B;[Baking] Il baking con una gabbia personalizzata abilitata ma nessun file selezionato si arresta in modo anomalo
* [Arresto anomalo] Annullamento della cottura automatica
* [Auto-Cage] Caricamento infinito quando il percorso del file di tipo High Poly non è valido
* [Linux]&#x200B;[Windows] Il selettore colore a volte può essere completamente nero o non apparire
* [Strumento Riempimento poligonale] Lo strumento non funziona con file non PBR
* &lbrack;[Paint] L’eliminazione del canale del colore di base non elimina il colore colorato precedentemente
* [USD] Le istanze dello shader non vengono tutte rilevate correttamente
* [Substance] Viene preso in considerazione solo il primo utilizzo di un nodo di input/output
* [Shader] L’Occlusione Ambiente viene applicata due volte con gli insiemi di texture, utilizzando diversi metodi di miscelazione
* [Engine] Le texture normali con canale blu vuoto (nero) possono produrre risultati di fusione errati
* [Importazione GLTF] La fusione di Alpha è abilitata su ogni set di texture
* [Esportazione GLTF] La fusione di Alpha è sempre abilitata all&#39;esportazione
* [Esporta] La geometria a due lati è sempre disattivata durante l&#39;importazione di un file GLTF
* [Javascript] La modifica delle impostazioni degli shader non contribuisce alla cronologia di annullamento
* [Esempi] La dispersione sotto la superficie non è attivata in Impostazioni schermo per Riunione

### 12.0.3

Data di pubblicazione: **2026/05/05**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* Aggiorna i forni alla versione 3.22.2
* Aggiornamento del motore di Substance alla versione 9.4.3
* \[Python\] Salvare un materiale avanzato in una posizione specifica

**Corretto:**

* \[Ubuntu\] Arresto anomalo durante la selezione del materiale
* Viene visualizzata la finestra a comparsa \[Mac\] Ricorrente per chiedere l’accesso ai dati di altre app
* Gli artefatti di [Baking] possono essere visualizzati sulla mappa di curvatura
* \[Cottura al forno\] In alcuni casi la cottura è più lenta
* \[Altera a geometria\] In alcuni casi l’opzione Altera a geometria viene disattivata
* \[Porzione UV\] Alfa estratto del punto di ancoraggio ignorato da altre porzioni
* \[Python\]\[Mac\] Eccezioni nella console Python con SSL
* \[Python\] Arresto anomalo di Painter all’uscita con widget Qt rimanenti

### 12.0.2

Data di pubblicazione: **2026/04/07**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* [Gestione colore] Aggiungi un nuovo OCIO per specificare lo spazio colore predefinito del selettore colore
* [Python] Esporre le impostazioni di annullamento automatico del wrapping nell’API Python

**Corretto:**

* [Arresto anomalo] Il salvataggio con spazio su disco insufficiente può causare l’arresto anomalo o il danneggiamento dei progetti
* [Arresto anomalo] [Barra multifunzione] L&#39;utilizzo della barra multifunzione può causare arresti anomali per alcuni progetti
* [Arresto anomalo] [Baking] arresto anomalo quando non è possibile scrivere il file .assbin nella cartella
* [Importazione] Le trame OBJ da Stager possono non riuscire durante la creazione del progetto
* [Import] In alcuni casi, OBJ ha un volto mancante
* [Importa] La trama USD senza materiale assegnato può arrestarsi in modo anomalo durante l&#39;importazione
* [Tracciato pieno] Non influenzato dalla simmetria
* [Stencil] L&#39;anteprima ha una risoluzione inferiore rispetto al risultato disegnato
* [UI] &quot;uv island&quot; è ancora menzionato nella descrizione comandi dell&#39;origine colore della mappa ID
* [Display] Le ombre appaiono invertite
* [Finestra vista] La trasformazione della proiezione di alterazione rimane dopo il passaggio alla modalità cottura
* [Altera] La griglia scompare quando la scala è impostata su 0 sull’asse Z con l’opzione Altera alla geometria attivata
* [Python] Errore imprevisto durante l&#39;aggiunta di un canale con modifica dell&#39;ambito

### 12.0.1

Data di pubblicazione: **2026/03/18**

Riepilogo: **Versione secondaria**

**Corretto:**

* \[Arresto anomalo\]\[Blocca\] Esporta da progetti specifici

### 12.0.0

Data di pubblicazione: <b>2026/03/09</b>
Riepilogo: <b>Questa è una versione principale. Questa versione contiene le funzioni per la conversione dei livelli, l&#39;alterazione della geometria, i nuovi effetti di postproduzione, i miglioramenti apportati alla nuova finestra del progetto e altri miglioramenti.</b>

<b>Aggiunto</b>:

* [Appiattisci livelli] Appiattisci i livelli all’interno del gruppo di livelli
* [Unico livello] Esportare su disco i livelli uniti
* [Altera a geometria] Aggiunge una nuova funzionalità di alterazione automatica alle proiezioni di alterazione
* [Post-effetti] Sostituisci i post-effetti con l’aggiunta di nuovi
* [Post-effects] Aggiornare la mappatura toni
* [Post-effetti] Aggiungi nuovo utilizzo per le risorse Post-effetti
* [Content]&#x200B;[Post-effects] Integra le risorse predefinite per i post-effetti nella libreria
* [Nuovo progetto] Miglioramento dell’interfaccia utente per la creazione di progetti
* [Nuovo progetto] Modifiche alla funzionalità di reimportazione della trama
* [Nuovo progetto] Consenti apertura file \*.geo.usd
* [Configurazione progetto] Miglioramento dell&#39;interfaccia utente per la configurazione del progetto
* Aggiornamento della libreria USD alla versione 25.05
* Aggiornamento della Substance Engine alla versione 9.3.4
* Aumenta i driver minimi a 25.3.1/25.Q2 per le GPU AMD
* Aggiornamento di Qt alla versione 6.8.6
* [Scripting] Aggiornamento dell’API JavaScript alla versione 1.1.20
* Aggiorna Python alla versione 3.13

<b>Corretto:</b>

* [Arresto anomalo] La modifica dell’output di un canale di materiale in una maschera può causare l’arresto anomalo
* [Import] Le texture EXR vengono forzate in sRGB invece che in lineare durante l’importazione di file USD
* [Porzioni UV] La sequenza di immagini con una singola immagine riempie anche altre porzioni UV
* [Baking] L&#39;AO è diverso tra il baking della CPU e quello della GPU
* [Color Management]&#x200B;[MacOS] La finestra di visualizzazione BaseColor non corrisponde al selettore colore
* [USD] In alcuni casi non vengono importati valori uniformi

## Versione 11

### 11.1.3

Data di pubblicazione: <b>2026/02/12</b>
Riepilogo: <b>Versione secondaria</b>

<b>Risolto</b>:

* [Disegno] In alcuni casi lo stencil e la simmetria non funzionano
* [Path] Nessun aggiornamento quando si modifica il cursore dell&#39;opacità del tratto sfumino
* [Progetto] Impossibile colorare su alcune geometrie
* [Barra multifunzione] Il tracciato istanziato scompare quando si modifica la risoluzione dell’insieme di texture
* [UI] Il selettore colore può ridursi e scomparire in alcuni casi

### 11.1.2

Data di pubblicazione: <b>2026/01/13</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

* [Baking] Migliora il tempo di cottura per il progetto UV Tiles con salvataggio asincrono
* [Ombreggiatori] Citazione nelle modifiche apportate al registro delle modifiche delle API shader in seguito alla migrazione Vulkan
* Aggiornamento dell’OpenEXR alla versione 3.4.4

<b>Risolto</b>:

* [Arresto anomalo] Arresto anomalo all’avvio su Nvidia GTX 10xx series
* [Arresto anomalo] L’utilizzo del selettore colore su set di texture diversi può causare un arresto anomalo quando si esce dall’applicazione
* [Prestazioni] Problema di prestazioni quando si disegna in un progetto con più livelli
* [Prestazioni] Ritardo quando si disegna con la penna grafica
* [UI] Le impostazioni della fotocamera rimangono disattivate in modalità di rendering (Iray)
* [Barra multifunzione] In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* [Barra multifunzione] Problema di prestazioni con i riquadri UV
* [Substance]&#x200B;[UI] Gli input dell’immagine scompaiono quando compressi
* [Substance]&#x200B;[UI] I gruppi nidificati possono rimanere visibili anche se li nascondono.
* [Baking]&#x200B;[UI] Impossibile impostare il raggio di campionamento della curvatura oltre 0,01
* [Baking]&#x200B;[UI] Impossibile impostare la distanza massima di occlusione oltre 1
* [Baking] L’impostazione &quot;Occlusione autonoma&quot; dell’opzione AO viene ignorata con diversi set di texture e Bassa come baking elevato
* [Baking] La mappa ID non esegue il baking dei colori dei vertici da FBX in modalità Bassa come Alta
* [Content] Il filtro Highpass genera colori sbiaditi nei canali con gestione del colore

### 11.1.1

Data di pubblicazione: <b>2025/12/09</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

* [Prestazioni] Miglioramento delle prestazioni dei riquadri UV durante l&#39;elaborazione di texture parziali
* [Bakers] Aggiornamento alla versione 3.15.4

<b>Risolto</b>:

* [Arresto anomalo]&#x200B;[MacOS] Il salvataggio di un progetto da una versione precedente si arresta sempre in modo anomalo
* [Arresto anomalo] La chiusura di un progetto può talvolta causare un arresto anomalo
* [Progetto] Errore &quot;numero di membri non corrispondente&quot; durante l’apertura di un progetto creato nella versione precedente
* [Baking] Le porzioni UV non sono combinate con i risultati di bake precedenti, se presenti
* [Baking] Dispositivo perso anche con il ray tracing disattivato su Nvidia GTX 10XX Series
* [Baking] AO con normale presenta artefatti ai bordi perché nessuna imbottitura
* [Baking] L’impostazione &quot;Occlusione autonoma&quot; di AO viene ignorata con diversi set di texture e &quot;corrispondenza per nome&quot; attivata
* [Baking] La mappa ID è completamente nera se mancano i colori dei vertici in qualsiasi trama di poli superiore
* [Barra multifunzione] La descrizione comando per il metodo di fusione Alpha indica il metodo di fusione Schermo anziché Scherma lineare
* [Path] Le tangenti creano un ciclo inatteso quando il punto viene spostato vicino alle estremità del tracciato
* [Strumento] L’anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
* [Engine] Colorare piccoli tratti può causare artefatti a blocchi
* [Shader] L’annullamento della creazione dell’istanza dello shader non ne comporta la rimozione corretta
* [Esporta] La modalità di Alpha per l&#39;esportazione GLTF è sempre impostata su MASK
* [Python] Errore imprevisto durante la modifica dello stack di livelli all&#39;esterno del blocco di modifica con ambito

<b>Problemi noti</b>:

* [Barra multifunzione] Problema di prestazioni con i riquadri UV
* [Barra multifunzione] In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* [Arresto anomalo]&#x200B;[Barra multifunzione] La creazione di testi molto lunghi nella barra multifunzione può causare l&#39;arresto anomalo
* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.1.0

Data di pubblicazione: <b>2025/11/18</b>
Riepilogo: <b>Questo aggiornamento è una versione principale e contiene il nuovo strumento barra multifunzione con nuovi contenuti dedicati, supporto di simmetria per i livelli di riempimento, parametri di dimensioni fisiche per lo spostamento, prestazioni migliorate tramite i forni aggiornati, supporto completo di Vulkan per Windows e Linux e altri miglioramenti.</b>

<b>Aggiunto</b>:

* Nuovo strumento barra multifunzione
* [Strumento] Aggiungi un nuovo strumento barra multifunzione per creare tracciati uniformi
* [Barra multifunzione] Aggiungi scelte rapide da tastiera per i predefiniti della barra multifunzione nella finestra Proprietà
* [Barra multifunzione] Consente di modificare l&#39;opacità della barra multifunzione per vertice sul tracciato
* [Barra multifunzione] Consente di modificare le dimensioni della barra multifunzione per vertice sul tracciato
* [Barra multifunzione] Rimuovi inizio/fine definiti in una Substance quando i percorsi vengono chiusi
* [Barra multifunzione] Rimuovi anteprima tracciato/materiale nella finestra delle proprietà per gli strumenti tracciato Disegno/Gomma/Sfumino
* [Barra multifunzione] Aggiungi metodi di fusione per l&#39;alfa e alcuni canali quando si sovrappongono automaticamente
* Simmetria riempimento
* [Riempimento] Aggiungi il supporto per la simmetria su livelli di riempimento ed effetti
* [Fill]&#x200B;[UI] Mostra le impostazioni di simmetria nella finestra delle proprietà per il livello di riempimento e gli effetti
* [Fill] Rielaborare l&#39;interfaccia utente delle impostazioni di simmetria sia nel menu della finestra della vista che nella finestra delle proprietà
* [Riempimento] Riorientare correttamente le texture normali durante la proiezione in modalità di alterazione
* Dimensioni fisiche spostamento
* [Spostamento] Usa dimensioni fisiche come unità di spostamento
* Miglioramento delle prestazioni
* [Prestazioni] Migliorare il rendering dei tratti di pennello piccoli su triangoli grandi
* [Prestazioni] Miglioramento del tempo di compilazione dello shader
* [Prestazioni] Supporto Vulkan completo per Windows e Linux
* [Prestazioni] Pannelli aggiornati con rendering GPU più veloce e supporto del ray tracing AMD
* [UI] Riorganizza le proprietà degli strumenti in gruppi e comprimi alcuni per impostazione predefinita
* [Engine] Aggiorna Substance Engine alla versione 9.2.5
* [Substance] Esporre la sostituzione della risoluzione per le risorse Substance in Strumenti e riempimenti
* [Esporta] Aggiorna il predefinito di esportazione delle mappe trama per esportare le texture in scala di grigio
* Python
* [Baking]&#x200B;[Python] Indicare in changelog le modifiche di interruzione dopo l&#39;aggiornamento di bakers
* [Python] Esposizione delle impostazioni di simmetria riempimento in Python
* Contenuto e nuovo contenuto
* [Content] Aggiungi 75 nuovi strumenti predefiniti per lo strumento Barra multifunzione
* [Contenuto] Aggiorna la risorsa di creazione sfumature per renderla compatibile con la barra multifunzione

<b>Risolto</b>:

* [Arresto anomalo] Il caricamento di un altro progetto mentre l’aggancio del percorso è abilitato può causare l’arresto anomalo
* [Arresto anomalo] Se si fa clic con il pulsante destro del mouse nel pannello Tracciato con le informazioni di un’altra sessione negli Appunti si può verificare un arresto anomalo
* [UI] L’interfaccia scorre verso l’alto nelle proprietà dello strumento quando si crea un tracciato
* [UI] Il cursore del mouse scompare quando la visualizzazione del riquadro di visualizzazione del percorso è nascosta
* [Tracciato] Copiare/incollare diverse proprietà dello strumento nel pannello Tracciato causa proprietà instabili
* I predefiniti dello strumento [Strumento] Gomma e Sfumino non aggiornano sempre la selezione del canale
* [Tool] Il valore Dipinto è grigio ma l’interfaccia utente viene visualizzata in bianco dopo il caricamento del predefinito dello strumento colorato nella maschera
* [Strumento] Il predefinito creato dalla maschera mantiene i valori dei canali caricati da un altro predefinito
* [Substance] L&#39;override dello spazio colore normale definito nel grafico non viene considerato
* [Content] La risorsa forma pennello predefinita utilizza una Substance obsoleta

<b>Problemi noti</b>:

* Cronologia dell&#39;istanza dello shader non rilevata correttamente
* [Barra multifunzione] Problema di prestazioni con i riquadri UV
* [Barra multifunzione] In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* [Barra multifunzione] Le tangenti creano un ciclo indesiderato quando il punto viene spostato vicino alle estremità del tracciato
* [Arresto anomalo]&#x200B;[Barra multifunzione] La creazione di testi molto lunghi nella barra multifunzione può causare l&#39;arresto anomalo
* [Strumento] L’anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
* [Baking] L’impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e &quot;corrispondenza per nome&quot; abilitato
* [Baking] AO con normale presenta artefatti ai bordi a causa della mancanza di riempimento
* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.3

Data di pubblicazione: <b>2025/08/05</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

* [Substance 3D Assets] Aggiungi un punto di notifica al pannello Risorse 3D
* [VFX Platform 2025] Aggiunta della configurazione ACES 2.0 nelle impostazioni di gestione del colore
* [VFX Platform 2025] Aggiornamento di OCIO alla versione 2.4.2
* Aggiornamento di Iray alla versione 2024.10
* [Engine] Aggiornamento a Substance Engine v.9.2.3
* [Nvidia] Aumenta la versione dei driver minimi Nvidia a 572.60 (Win) e 570.169 (Linux)

<b>Risolto</b>:

* [Python] La modifica con ambito non viene visualizzata nella finestra Cronologia

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.2

Data di pubblicazione: <b>2025/06/10</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

* [Mac] Aggiungi un avviso relativo a una versione specifica del sistema operativo che causa artefatti
* [Aggiornamento automatico] Miglioramenti minori UX al registro degli errori Risorse
* [Annullamento automatico] Aggiornamento alla versione 1.3.2 con miglioramenti per la giuntura
* [USD]&#x200B;[FBX] Aggiungi il supporto per più set UV con dati sparsi
* [Esporta] Nelle trame esportate come FBX mancano i loro set UV aggiuntivi se presenti al momento dell’importazione

<b>Risolto</b>:

* [MacOS]&#x200B;[Linux] Arresto anomalo durante il salvataggio sull&#39;unità di rete
* [Win]&#x200B;[Tablet] Sfarfallio durante il panning
* [SpaceMouse] Problema durante l&#39;utilizzo dello strumento Tracciato
* [Gabbia automatica] Impossibile eseguire il baking dopo un ricaricamento della trama
* [Aggiornamento automatico] La sequenza di immagini non viene ricaricata se manca la prima sezione
* [Path] La tangente personalizzata può influire su un&#39;altra tangente
* [Path] Il percorso non viene visualizzato in un set di texture se il primo punto si trova in un altro set di texture
* [UI] Alcuni menu sono sempre disattivati dopo l’apertura di un progetto (es.: simmetria)
* [Properties] Impossibile utilizzare/caricare strumenti predefiniti con lo strumento Filled path
* [USD] Più set UV non vengono riconosciuti nello shader personalizzato quando si utilizzano file USD
* [USD] Le videocamere con gli stessi nomi vengono sostituite
* [Esporta] Invia a Photoshop genera uno spazio colore errato per i risultati a colori e in scala di grigi
* [Esportazione] I canali in scala di grigio con alfa vengono esportati come colore invece che in scala di grigio con il formato PNG
* [Esportazione] L’esportazione del canale in scala di grigio come PSD genera un file non valido/troncato
* [Contenuto] Il filtro Altera in modalità multidirezionale non funziona
* [Python] Impossibile allocare l&#39;errore dell&#39;elenco durante la ricerca per indicizzazione dei nodi dello stack di livelli

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.1

Data di pubblicazione: <b>2025/04/10</b>
Riepilogo: <b>Versione secondaria</b>

Nota: <b>La versione del CCD Linux verrà posticipata al 29 aprile</b>

<b>Aggiunto:</b>

* Aggiornamento a Qt 6.5.8
* [Substance] Aggiungi un messaggio di registro per i filtri quando più input di immagine condividono lo stesso utilizzo
* [Nvidia] Aggiungi un avviso sui driver Nvidia più recenti (572.47)

<b>Corretto:</b>

* [Arresto anomalo] Quando trascini e rilasci una barra secondaria con un utilizzo in uno slot per un singolo canale
* [Arresto anomalo]&#x200B;[Tracciato] L’opzione Cambia tipo di tracciato non è disattivata quando non si fa clic su un tracciato specifico
* [Percorso di riempimento] Non dovrebbe essere in grado di selezionare il materiale Substance
* [Motore] Artefatti lungo tratti pennello
* [Engine] I tracciati possono essere interrotti con impostazioni specifiche
* Problema con il menu a discesa per lo spazio colore del contagocce
* [Aggiornamento automatico] [Python] Messaggio di errore errato quando si utilizza ResourceID senza versione
* [Shader] Arresto anomalo all’apertura di alcuni progetti

<b>Problemi noti:</b>

* [SpaceMouse] Problema durante l&#39;utilizzo dello strumento Tracciato
* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.0

Data di pubblicazione: <b>2025/03/11</b>
Riepilogo: <b>Versione principale, nuova funzione Aggiornamento automatico, strumento Tracciato riempito e altri miglioramenti al tracciato, nuovi filtri e una generazione sperimentale di gabbia automatica per la cottura al forno</b>

<b>Aggiunto</b>:

* Aggiornamento automatico
* [Aggiornamento automatico] Aggiornamento automatico delle risorse modificate nel pannello Risorse
* [Aggiornamento automatico] Aggiorna automaticamente le risorse modificate nel progetto
* [Aggiornamento automatico] Disattiva l&#39;aggiornamento automatico per impostazione predefinita
* [Aggiornamento automatico] Rendi facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono (.sbsar, .glsl, .ai, .svg)
* [Aggiornamento automatico] Aggiungi variabile di ambiente per disabilitare la funzione di aggiornamento automatico
* [Aggiornamento automatico]&#x200B;[SBSAR] Rendi facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono
* Tracciato pieno
* [Tracciato]&#x200B;[Riempimento] Aggiungi nuovo strumento per creare tracciati pieni
* Miglioramenti al tracciato
* [Path] Crea un tracciato che si aggancia ai poligoni
* [Path] Consente di cambiare i tipi di percorso
* [Path] Consente di copiare e incollare i dati dei vertici del tracciato tra contenuto e maschera
* [Path] Consente di vincolare l&#39;angolo durante la creazione di un nuovo punto
* [Path] Consenti di vincolare la creazione di punti a una linea
* [Tracciato] Chiudi la forma con un solo clic
* [Path] Visualizza informazioni sul percorso
* [Tracciato] Consente di ridimensionare e ruotare i vertici del tracciato
* [Path]&#x200B;[UX] Semplificare l&#39;accesso ai gizmo di trasformazione
* [Path] Aggiungi anteprima percorso
* [Tracciato] Disattiva l&#39;anteprima del tracciato con Maiusc + P
* [Path] Migliorare l&#39;edizione tangente dalla vista laterale
* [Tracciato] Consenti di concentrarsi su un tracciato 3D
* [Path] I vertici devono mantenere lo stato di selezione quando si attiva e disattiva l&#39;interfaccia utente
* [Path] Consente di eliminare il percorso utilizzando Backspace
* [Path] Mantieni l&#39;elenco dei percorsi aperto se l&#39;utente lo espande
* [Path]&#x200B;[Pila di livelli] Rinomina correttamente i duplicati quando si copia o incolla
* Miglioramenti all&#39;interfaccia utente di [Path] e alle descrizioni comandi
* Prestazioni
* [Prestazioni] Migliorare le prestazioni della finestra di visualizzazione quando si utilizza un livello di tassellatura elevato
* [Prestazioni] Abilita solo il primo canale su nuovi livelli di riempimento/effetti
* [Prestazioni] Calcolo del tratto del pennello in parallelo
* Baking
* [Baking] Aggiungi nuova opzione di generazione gabbie completamente automatica per la cottura al forno con trame ad alto poli (sperimentale)
* Contenuto
* [Content] Aggiungi 6 nuovi filtri: stilizzazione, quantizzazione, kuwahara anisotropo, smusso uniforme, distanza direzionale, conversione in scala di grigi
* [Content] Aggiornate Noises and Grunges alla versione più recente di Designer (con il nuovo Voronoi 2D)
* [Content] Aggiungi 3 nuovi generatori di texture (Tile Random, Triangle Grid, Generatore di Scratches)
* [Content] Rinomina il modello di motore originale ed esporta i predefiniti
* Python
* [Shelf]&#x200B;[Python] Salva materiale intelligente o maschera avanzata su disco da Python
* [Python] Aggiungi gabbia automatica di cottura all’API Python
* [Python] Consente di modificare i nomi e le descrizioni dei set di texture/porzioni UV
* [Python] Condivisione delle impostazioni di risoluzione su sorgenti vettoriali e di font
* [Auto-update]&#x200B;[Python] Esporre le funzionalità di aggiornamento automatico del progetto in Python
* Varie
* [Esporta] Semplificare l’accesso alle opzioni di invio con un nuovo pannello
* [Nvidia] Aggiungi un avviso sui driver Nvidia più recenti (572.16)
* L’aggancio dell’angolo deve essere influenzato dalla selezione dello spazio Oggetto/Mondo
* [Elenco set di texture] Consente di aggiungere un nome personalizzato ai riquadri UV e di utilizzarli al momento dell’esportazione
* Mac
* [Mac] Usare Metal invece di OpenGL per il rendering grafico
* [Mac] Elimina il supporto Mac Intel

<b>Risolto</b>:

* [Arresto anomalo] Elimina input immagine
* Impossibile aggiungere smart mat tramite il pulsante stack di livelli
* [Python] Impossibile trovare gli effetti in GroupLayerNode

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione
* [RedHat] Problemi con il selettore colore

## Versione 10

### 10.1.2

Data di pubblicazione: <b>2024/12/3</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Risolto</b>:

* [Arresto anomalo] Elimina input immagine
* Impossibile aggiungere smart mat tramite il pulsante stack di livelli
* [Python] Impossibile trovare gli effetti in GroupLayerNode

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione
* [RedHat] Problemi con il selettore colore

### 10.1.1

Data di pubblicazione: <b>2024/11/5</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Aggiunto</b>:

* [Progetto] Mantieni aperto il progetto corrente fino alla convalida della nuova selezione del progetto
* [Srotolamento automatico] La densità di texel consente di suddividere meglio le Isole UV in UDIM
* [Baking] Correggere una copia ambigua nel menu di scelta rapida delle mappe trama
* [Altera] Rimuovi il ridimensionamento nella finestra della vista per l’asse Z (profondità)
* [Importa/Esporta] Rimuovi il supporto per i formati di file immagine inutilizzati
* Aggiornamento della Substance Engine alla versione 9.1.4

<b>Risolto</b>:

* [Arresto anomalo] Dopo il trasferimento della risorsa in Risorse e il salvataggio del progetto
* [Arresto anomalo] Problemi con la libreria aiserver
* [Arresto anomalo] Arresto anomalo del server Illustrator in alcuni rari casi
* [Arresto anomalo] Quando si esce dall’applicazione in alcuni rari casi
* Impossibile inviare report di arresto anomalo su alcuni computer
* [Baking] Il colore del vertice non viene letto correttamente
* [UI] La posizione delle finestre e le novità all’avvio sono state spostate
* [Assimp] StandardSurface di Maya non riconosciuto nella preparazione di ID
* [Python] La libreria SSL mancante genera un errore
* [Python]&#x200B;[Win] Errore durante la chiamata di QColorConstants.Transparent
* [Python] Le miniature dei livelli create tramite Python non si aggiornano finché non si fa clic all’interno della pila di livelli
* [Shader] Collegamento interrotto nel registro delle modifiche API shader
* [Risorse 3D] Utilizza le impostazioni proxy del sistema operativo per accedere alle Risorse 3D

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget che sembra eliminato tramite script funziona ancora
* [RedHat] Problemi con il selettore colore

### 10.1.0

Data di pubblicazione: <b>2024/09/17</b>
Riepilogo: <b>Versione principale, nuovo contenuto: filtro area di riempimento/colore, filtro decalcomania ricamo e sei filtri Substance generici, importa USD con proprietà materiale e shader, miglioramento delle prestazioni, conforme alla piattaforma VFX 2024 e migrazione a Linux RedHat</b>

<b>Aggiunto</b>:

* [Contenuto] Aggiungi nuova maschera area di riempimento/filtro colore
* [Content] Aggiungi nuovo filtro Ricamo decalcomania
* [Content] Aggiungi 6 nuovi filtri Substance generici (FXAA, pixelate, highpass, posterize, smoothstep, threshold)
* [USD] Esporta il livello USD con un materiale ASM definito
* [USD] Importa USD con proprietà del materiale e dello shader
* [Prestazioni] Abilita miniature stack di livelli ottimizzate per impostazione predefinita
* [Prestazioni] Riduzione del tempo di apertura dei file di progetto e del consumo di memoria (decodifica dei dati)
* Conforme alla piattaforma VFX 2024
* [VFX Platform 2024] Aggiornamento a Python 3.11
* [Piattaforma VFX 2024] Aggiornamento all&#39;OpenEXR 3.2
* [VFX Platform 2024] [USD] Aggiornamento OpenSubdiv 3.6.0
* [VFX Platform 2024]&#x200B;[Color Management] Aggiornamento a OCIO 2.3.2
* [Linux] Migrazione a Linux RedHat
* [Linux] Aggiorna la versione min del driver Nvidia a 535.171.04
* [Import] Aggiungi un&#39;opzione per capovolgere la mappa normale durante l&#39;importazione di una trama GLTF
* [UI] Utilizza il valore predefinito del sistema operativo per la distanza di rilevamento degli eventi di trascinamento
* [Substance Engine] Aggiungi la funzione di striscia delle chiamate per rimuovere i simboli dall&#39;eseguibile
* [Schermata iniziale] Aggiornamento al nuovo formato della schermata iniziale
* Aggiornamento della Substance Engine alla versione 9.1.3
* [Python] Mostra collegamento agli esempi nel menu della documentazione dello stack di livelli
* [JavaScript] Spostare i plug-in Javascript nella sottocartella javascript/plugins

<b>Risolto</b>:

* [Illustrator] Arresto anomalo durante l&#39;esportazione di un riquadro UV con grafica .ai in casi specifici
* [Tratti dinamici]&#x200B;[Tracciato] Casuale per tratto non funziona su un tracciato
* [UI]&#x200B;[Proprietà] Il blocco è attivato quando la suddivisione in porzioni è non uniforme
* Il file TXT di debug viene creato quando si fa doppio clic su un progetto Painter
* [USD]&#x200B;[Esporta] Alcune texture potrebbero essere mancanti
* [ASM] La dispersione del canale del colore ignora l&#39;effetto metallizzato
* [Contenuto] Il filtro Sfocatura non funziona nello spazio colore &quot;di lavoro&quot;
* [Contenuto] Il filtro Regolazione Height modifica anche il canale alfa del livello

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Win]&#x200B;[Arresto anomalo] [ACE] Non utilizza lo spazio colore ICE sRGB per la trasformazione dello schermo
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
* [Arresto anomalo] Riposiziona risorsa e salva progetto
* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione
* [RedHat] Problemi con il selettore colore

### 10.0.1

Data di pubblicazione: <b>2024/06/11</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Aggiunto:</b>

* [Library] Convertire i font di Substance in normali file di font
* [Illustrator]&#x200B;[SVG] Dai alle miniature nella selezione dell&#39;ambito uno sfondo grigio chiaro
* [Python] Aggiungi la funzione sull&#39;origine bitmap per elencare gli spazi colore disponibili

<b>Risolto</b>:

* [Serie di livelli] Cartella sempre chiusa quando viene spostata all’interno o all’esterno di altre cartelle
* [Salva] Il file di progetto viene perso quando &quot;salva come copia&quot; o il salvataggio automatico non riesce in casi specifici
* [Importa] Le risorse con lo stesso nome ma estensioni diverse vengono sostituite
* [Proprietà] Impostazioni mancanti quando si utilizza un punto di ancoraggio negli input dell’immagine
* [Illustrator] Impossibile importare file Illustrator dopo l&#39;arresto del server senza riavviare Painter
* [Python] Impossibile impostare l&#39;istanza padre con il tipo &quot;properties&quot;
* [Python] L&#39;impostazione del poly alto come parametro di cottura non carica il poly alto
* [Python] Messaggio di errore per set\_color\_space() troppo generico
* [Python] Le sorgenti di riferimento consentono di creare cicli

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
* [Illustrator] Arresto anomalo durante l&#39;esportazione di un riquadro UV con grafica .ai in casi specifici
* [Tratti dinamici]&#x200B;[Tracciato] Casuale per tratto non funziona su un tracciato

### 10.0.0

Data di pubblicazione: <b>2024/05/16</b>
Riepilogo: <b>Versione principale, edizione dello stack di livelli con API Python, lettura dei file nativi di Illustrator, integrazione di risorse 3D e nuova risorsa di testo</b>

<b>Aggiunto</b>:

* [Illustrator] Utilizzare i file Illustrator con le tavole da disegno in Painter
* [Illustrator]&#x200B;[SVG] Aggiungere anteprime nella selezione dell’ambito
* [Substance 3D Assets] Sfoglia, seleziona e scarica Risorse 3D direttamente in Painter
* [Substance 3D Assets]&#x200B;[UI] Nuovo pannello
* [Substance 3D Assets] Supporto di mappe e materiali ambientali
* [Substance 3D Assets] Consenti di ricaricare, navigare e aprire la cartella della posizione nel nuovo pannello di Substance 3D Assets
* [Substance 3D Assets] Aggiunta di un gestore di download
* [Risorsa testo] Consenti l&#39;utilizzo di font incorporabili
* [Risorsa testo] Consenti il rendering di un font o testo su una trama
* [Risorsa di testo] Visualizza i font dell&#39;utente e di altri tracciati condivisi nel pannello Risorse con una nuova categoria
* [Text Resource]&#x200B;[Properties] Aggiungi il supporto per le proprietà avanzate dei font
* [Risorsa di testo] Consenti di cercare/visualizzare i font nei mini-scaffali
* [Risorsa testo] Aggiungi messaggio di errore/finestra di dialogo durante l’importazione di un font incompatibile
* Varie
* [Proiezione riempimento] Migliora il comportamento del manipolatore di scala quando si utilizzano valori piccoli
* [Manipolatori] Aggiungi una nuova modalità precisa quando si preme CTRL
* [Manipolatori] Miglioramento della stabilità del manipolatore di superficie durante la traslazione
* [Esporta] Aggiungi nome spazio colore negli output SBSAR
* [Prestazioni] Miglioramento dei tempi di individuazione delle librerie delle risorse su disco
* [Substance] Aggiornamento al motore di Substance versione 9.1.2
* [Drag and Drop] Allinea la rotazione della decalcomania alla videocamera quando viene rilasciata nella finestra della vista
* [Python] Edizione dello stack di livelli
* [Python] Consenti di selezionare livello, effetto, maschera e maschera geografica nell&#39;interfaccia utente
* [Python] Consenti di ottenere/impostare i metodi di fusione dei livelli
* [Python] Consenti di ottenere/impostare le impostazioni di proiezione del livello di riempimento
* [Python] Consente di interrogare il colore del materiale della Substance da un livello di riempimento
* [Python] Consenti di eseguire query e impostare colori e risorse uniformi nei livelli e negli effetti
* [Python] Consenti di creare e modificare risorse di testo in una pila di livelli
* [Python] Consente di modificare i canali attivi su livelli ed effetti
* [Python] Consenti alle azioni in batch di avere un singolo annullamento/ripristino
* [Python] Consente di caricare/modificare i parametri di origine vettoriale
* [Python] Consente di modificare le proprietà dei colori dei livelli e degli effetti con la gestione del colore
* [Python] Consenti di eseguire query e creare livelli istanziati
* [Python] Consenti di aggiungere un effetto di selezione colore
* [Python] Consente di controllare la gestione del colore dell&#39;immagine bitmap
* [Python] Consente di mettere in pausa/rimettere in pausa il motore
* [Python] Consenti di passare a nodi di pari livello e nodi padre
* [Python] Consente di creare un effetto filtro/generatore
* [Python] Consente di aggiungere un effetto livello
* [Python] Consenti di aggiungere una maschera avanzata a un livello
* [Python] Consenti di creare/modificare punti di ancoraggio
* [Python] Consenti di ottenere/impostare la maschera sui livelli
* [Python] Consente di creare un effetto maschera di confronto
* [Python] Consenti di eseguire query e utilizzare i predefiniti dalle risorse Substance
* [Python] Consenti di elencare i predefiniti e i relativi valori tramite la funzione internal\_properties per le risorse Substance
* [Python] Consenti di elencare i predefiniti di esportazione predefiniti
* [Python] Consenti di elencare i predefiniti di esportazione disponibili nella libreria
* [Python] Consenti di recuperare il contenuto dei predefiniti di esportazione

<b>Risolto</b>:

* [Arresto anomalo] Annullamento di &quot;Rimuovi istanza shader&quot; con Ctrl+Z
* [Arresto anomalo] Crea un livello su una pila vuota se l’ultima selezione era un effetto
* [SVG] Problema con il valore dell’area ritagliata personalizzato
* [Annullamento automatico] Il ricalcolo del solo impacchettamento senza alcuna modifica dell’orientamento UV provoca l’arresto anomalo
* [Drag and drop] Il ritardo dovuto alle risorse esterne viene precaricato più volte
* [UI] Trascinate la miniatura della risorsa per nascondere il messaggio di avviso nello stack di livelli
* [Prestazioni] I riquadri UV mascherati vengono ancora calcolati
* [USD] Evidenziazione errata per la selezione dell’ambito
* [Risorsa] L&#39;immagine bitmap viene danneggiata dopo aver colorato nel canale normale e salvato il progetto
* [USD] Supporta l’ordine dei vertici mancini
* [Substance] Ripristina predefiniti torna sempre a zero per il widget Angolo
* [Engine] Colorare con un SVG in uno stencil non funziona
* [Motore] I tratti del pennello mappa normale si interrompono dopo un annullamento
* [Contenuto] Il filtro Da grafica a materiale presenta una fusione alfa e uno spazio cromatico errati
* [Content] I metodi di fusione sul Tile Generator non funzionano
* [Contenuto] In alcuni casi, il filtro di scansione dell’istogramma genera bande
* [Contenuto] L’illuminazione al forno stilizzata non tiene conto del height dipinto
* [Python] Errore imprevisto durante il recupero delle informazioni sui livelli istanziati dopo la modifica dello shader
* [Salva] Il file di progetto viene perso quando &quot;salva con nome&quot; non riesce in casi specifici

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Crash]&#x200B;[Linux]&#x200B;[AMD] Trascinamento di risorse nello stack di livelli sul sistema operativo Wayland
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo per gli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
* [Salva] Il file di progetto Spp viene perso quando &quot;salva come copia&quot; non riesce in casi specifici
* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
* [Illustrator] Impossibile importare file Ai dopo l&#39;arresto del server senza riavviare Painter
* [Importa] Le risorse con lo stesso nome ma estensioni diverse vengono sostituite

## Versione 9

### 9.1.2

Data di pubblicazione: <b>2024/01/30</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Aggiunto</b>:

* [Prestazioni] Migliorare il tempo di creazione del primo livello di riempimento nei nuovi progetti
* [Prestazioni] Riduzione del tempo di caricamento delle mappe dell&#39;ambiente più complesse
* [Substance] Consenti di salvare/chiudere i progetti anche quando vengono generate miniature

<b>Risolto</b>:

* Il salvataggio non riesce sui progetti della versione precedente quando la finestra della vista viene modificata
* [Arresto anomalo] Reimportazione della trama quando si utilizza la gestione dei colori e degli oggetti AO personalizzati
* [Proiezione riempimento] Facendo clic sul manipolatore Scala viene visualizzato il messaggio &quot;non colorabile&quot;
* [Pennello] Colorare con allineamento UV provoca artefatti
* [Stack di livelli] La ridenominazione del livello è lenta quando lo stack è molto lungo
* [Serie di livelli] Messaggio di errore non corretto quando si utilizza un filtro incompatibile nella maschera
* [Serie di livelli] La selezione torna al livello superiore dopo l’eliminazione
* [Esporta] La texture normale generata è sempre in modalità di spaziatura interna 3D
* [Esporta] La texture alfa non viene generata con il predefinito di esportazione Vista 2D
* [Export] L’esportazione SBSAR contiene utilizzi errati con mappe convertite
* [Shader] Il registro delle modifiche delle API shader non è aggiornato con le ultime modifiche ASM

<b>Problemi noti</b>:

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Crash]&#x200B;[Linux]&#x200B;[AMD] Trascinamento di risorse nello stack di livelli sul sistema operativo Wayland
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo per gli schermi HD
* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent

### 9.1.1

Data di pubblicazione: <b>2023/12/05</b>
Riepilogo: <b>Versione secondaria, correzioni di bug e invio alle funzionalità After Effects</b>

<b>Aggiunto:</b>

* [Interoperabilità] Consente di inviare una trama con texture ad After Effects (Ae 24.1)

<b>Corretto:</b>

* [Riempimento] L&#39;impostazione UV sulla proiezione del set UV non legge più di 2 set UV
* [Arresto anomalo] Utilizzo di una mappa dell&#39;ambiente a 16 K
* [Arresto anomalo] Esr utilizzato come input dell’immagine
* [Arresto anomalo] Copiare e incollare tracciati tra progetti
* [QoL] Se si trascina una risorsa Alpha in modalità decalcomania, viene creata una Proiezione UV nella maschera
* [Path] Quando si copiano i vertici di un tracciato, anche il tracciato di destinazione viene rinominato alla riapertura del progetto
* [Linux] La selezione del colore può essere interrotta con più schermi
* [Annullamento automatico] Problema di interfaccia utente per il controllo della densità del testo
* [Gestione colore] Il feedback dell&#39;interfaccia utente è appropriato per i casi, ma il motore non lo è
* [Gestione colore] Selezione dello spazio colore errata nella maschera con override dei dati utente

<b>Problemi noti:</b>

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Crash]&#x200B;[Linux] con Linux Wayland su AMD quando si trascina e si rilascia una risorsa nello stack di livelli
* [Arresto anomalo]&#x200B;[Mac] Modifica del valore di filtro anisotropo nel sistema operativo Monterey
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sullo schermo hd
* [Python] Arresto anomalo durante l’esportazione di USD attivato da TextureStateEvent

### 9.1.0

Data di pubblicazione: <b>2023/11/07</b>
Riepilogo: <b>Versione principale che introduce il supporto per SVG e trasparenza, oltre a miglioramenti dello strumento di trascinamento della selezione</b>

<b>Aggiunto:</b>

* [SVG] Consenti l’importazione di file vettoriali (SVG)
* [SVG]&#x200B;[UI] Aggiungi il supporto per le proprietà specifiche dei SVG
* [SVG] Aggiungete un’opzione per mantenere facilmente le proporzioni originali dell’immagine
* [SVG] Consenti l&#39;utilizzo automatico del canale alfa di SVG con trasparenza
* [Interoperabilità] Consente di inviare una trama con texture ad After Effects (Ae 24.1 beta)
* [Interoperabilità] Aggiungere impostazioni per Invia a After Effects
* [QoL]&#x200B;[Assets]&#x200B;[UI] Importa automaticamente risorsa durante il trascinamento nello slot dell&#39;interfaccia utente
* [QoL] Consente di trascinare e rilasciare risorse esterne nella pila di livelli
* [QoL]&#x200B;[Serie di livelli] Trascina le texture dal pannello Risorse alla serie di livelli
* [QoL]&#x200B;[Viewport] Consente di trascinare e rilasciare il generatore, filtri sulla trama
* [QoL]&#x200B;[Finestra vista] Consente di rilasciare risorse esterne sulla trama
* [QoL]&#x200B;[Proiezione] Aggiungi un nuovo set UV alla modalità di proiezione del set UV
* [QoL] Trascinate le maschere avanzate come nuovi livelli nella finestra della vista e nella pila di livelli
* [QoL] Aggiungi selettore per i generatori con più output quando utilizzati nella maschera
* [QoL] Consente di trascinare e rilasciare immagini a canale singolo su un effetto di riempimento
* [QoL]&#x200B;[Serie di livelli] Utilizzate i modificatori CTRL/ALT con il trascinamento per specificare dove/come creare effetti/livello
* [Tracciato] Attiva/disattiva la visibilità dei tracciati singolarmente nel pannello Tracciato
* [Tracciato] Consenti l&#39;utilizzo di manipolatori di trasformazione per i punti di tracciato
* [Path] Consente di controllare manualmente le tangenti per vertice
* [Path] Copiare/incollare le proprietà del percorso
* [Tracciato] Introduci una scelta rapida vuota per il pulsante Tangente di interruzione
* [Shader] Aggiungere il supporto per Opacità e Traslucenza nello shader ASM
* [Shader] Aggiungere il supporto per il canale di Colore di assorbimento con lo shader ASM
* [Shader] Suggerimenti per migliorare i parametri dello shader ASM
* [Shader] Imposta il colore predefinito del canale di trasparenza su nero
* [Impostazioni schermo] Abilita Anti-alias temporale per impostazione predefinita
* [Impostazioni schermo] Abilita impostazione di dispersione sotto la superficie per impostazione predefinita
* [Substance] Aggiungi il supporto per la proprietà ColorSpace dall’input/output del grafico
* [Substance] Aggiorna il motore di Substance alla versione 9.0.3
* [UI] Rendi accessibile il pulsante contestuale della barra degli strumenti anche se la finestra dell&#39;app è piccola
* [Annullamento automatico] Controlla il numero di porzioni UV con densità texel
* [Baking] Disattiva Raytracing GPU su GPU AMD per impostazione predefinita
* [Prestazioni] Applicate la compressione senza perdita di dati alle immagini a 16 bit per ridurre l’ingombro del progetto
* [Python] Consenti di manipolare la videocamera predefinita nella vista 3D
* [Python] Esporta la possibilità di esportare trama tramite scripting
* [Content]&#x200B;[Samples] Aggiungi un nuovo progetto di esempio &quot;French Restaurant Table&quot;
* [Content] Aggiorna Substance logo alpha alla nuova versione
* [Contenuto] Aggiungi tre filtri di materiale focalizzati sui SVG (Adesivo personalizzato, Spruzzo personalizzato e Grafica su materiale)

<b>Corretto:</b>

* [Arresto anomalo] Modifica delle dimensioni del manipolatore quando non si utilizza lo strumento di simmetria
* [Arresto anomalo] [Serie di livelli] Creazione di un livello quando non è selezionato nulla
* [Progetto] Le mappe trama possono essere danneggiate dopo la rimozione di risorse inutilizzate
* [Progetto] Danneggiamento delle risorse dopo la reimportazione o la rigenerazione dell&#39;immagine
* [Risorse] Quando si ricarica una risorsa, questa viene rimossa dai Preferiti
* [Importa] Impossibile importare risorse quando nel pannello delle risorse è presente l’indicazione &quot;Nessun risultato trovato&quot;
* [UI] In alcuni casi la freccia contestuale della barra degli strumenti non viene visualizzata
* [Substance] Il pulsante affiancato per i valori booleani non è supportato
* [Level] Etichetta del canale errata quando utilizzata nella maschera
* [Export]&#x200B;[glTF] i file glTF/GLB esportati da Painter non dispongono di un&#39;unità di dimensioni fisiche
* [Content] L’intensità del filtro Sfocatura è bloccata su 16
* [Content] L&#39;input dell&#39;immagine &quot;colore di destinazione&quot; del filtro Corrispondenza colori non è visibile

<b>Problemi noti:</b>

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Crash]&#x200B;[Linux] con Linux Wayland su AMD quando si trascina e si rilascia una risorsa nello stack di livelli
* [Arresto anomalo]&#x200B;[Mac] Modifica del valore di filtro anisotropo nel sistema operativo Monterey
* [Arresto anomalo] Esr utilizzato come input dell’immagine
* [Arresto anomalo] Utilizzo di una mappa dell&#39;ambiente a 16 K
* [Annullamento automatico] Problema di interfaccia utente per il controllo della densità del testo
* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sullo schermo hd
* [Python] Arresto anomalo durante l’esportazione di USD attivato da TextureStateEvent
* [QoL] Se si trascina una risorsa Alpha in modalità decalcomania, viene creata una Proiezione UV nella maschera

### 9.0.1

Data di pubblicazione: <b>2023/09/19</b>
Riepilogo: <b>Versione del bug minore con diversi miglioramenti</b>

<b>Aggiunto:</b>

* [Import] Impostare la posizione di importazione predefinita nella finestra di importazione
* [Modalità cottura] Consente di ripristinare i valori predefiniti dei parametri
* [Baking] Impostate il baking sulla risoluzione del colore durante la creazione di un progetto
* [Simmetria] Separa manipolatore specifico della simmetria dalla scelta rapida Q
* [Menu] Aggiungi l&#39;opzione &quot;show log&quot; nel menu della Guida
* [Finestra di visualizzazione] Miglioramento della velocità di rendering delle ombre
* [Substance] Aggiorna il motore alla versione 9.0.1
* [Gestione colore] Il file di configurazione OCIO può avere qualsiasi tipo di estensione
* [Assets] La risorsa Sbsar con utilizzo &quot;decalcomania&quot; deve essere impostata automaticamente su proiezione alterazione
* [Tracciato] Visualizza un messaggio quando tenti di interagire con lo strumento Tracciato mentre l&#39;interfaccia utente e il widget sono nascosti

<b>Corretto:</b>

* [Arresto anomalo] Alt + trascinamento nel pannello Tracciato
* [Importa risorse] Arresto anomalo casuale durante la rimozione delle risorse da importare
* Arresto anomalo durante l’importazione di un file GLB compresso
* Problema durante la pittura su trame che condividono UV
* Flash di trama nero durante il ricalcolo o il caricamento della cache
* [Proprietà] Il menu di scelta rapida, accessibile facendo clic con il pulsante destro del mouse per reimpostare i parametri, non viene visualizzato nei menu a discesa
* [Level] Cursori di input bloccati dal livello precedente
* [AMD]&#x200B;[Sparse] Opzione SVT se attivata genera artefatti
* [Proiezione]&#x200B;[Altera] Arresto anomalo quando si fa doppio clic sui vertici
* [Path] Interfaccia utente e percorso visibili in modalità cottura al forno
* [AMD] Texture persa quando si gioca con visibilità
* [Sparsa] Risoluzione troppo bassa quando si ruota la trama

<b>Problemi noti:</b>

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati

### 9.0.0

Data di pubblicazione: <b>2023/06/20</b>
Riepilogo: <b>Versione principale con Pittura lungo il percorso che consente curve 3D, nuovi materiali di base e pulizia dei materiali legacy e nuovi predefiniti per curve 3D</b>

<b>Aggiunto:</b>

* [Tracciato] Strumento Aggiungi nuovo disegno lungo tracciato
* [Tracciato] Aggiungi una scelta rapida vuota per lo strumento tracciato
* [Path] Consente di aggiungere nuovi punti a un percorso esistente
* [Path] Aggiungi collegamento per uscire dalla creazione del percorso corrente
* [Tracciato] Consente di modificare le proprietà del pennello per i tracciati
* [Tracciato] Regolare automaticamente le tangenti durante il posizionamento di un punto
* [Path] Ricalcolare le tangenti quando si sposta un punto
* [Tracciato] Agganciare i punti appena creati alla superficie di una trama
* [Path] Consente di modificare la pressione per vertice
* [Path] Regola la pressione del punto appena creato dai punti vicini
* [Tracciato] Consenti di convertire i punti in punti morbidi/d&#39;angolo (interruzione tangente)
* [Path] Consente di spostare immediatamente un punto appena aggiunto
* [Path] Consente di rimuovere punti dal percorso esistente
* [Tracciato] Consente di invertire la direzione di un tracciato
* [Path] Consente di selezionare un percorso nella finestra della vista
* [Tracciato] Consente di selezionare punti di tracciato con selezione
* [Path] Introduci le scelte rapide da tastiera CTRL-A per selezionare tutti i punti di un tracciato
* [Path] Consenti di chiudere il percorso
* [Path] Consenti di specificare l&#39;asse del tracciato verso l&#39;alto in Proprietà
* [Path] Aggiungere un menu di controllo dei vertici alla barra degli strumenti contestuale
* [Tracciato] Introdurre le modalità di disegno/cancellazione/sfumino allo strumento tracciato
* [Path] Crea un feedback visivo per i tracciati nella finestra della vista
* [Path] Aggiungi un indicatore visivo per la direzione del tracciato
* [Path] Aggiungere un thickness di linee alle impostazioni di visualizzazione del percorso
* [Path] Consenti di nascondere l&#39;interfaccia utente dei percorsi
* [Tracciato] Aggiungi il pannello Tracciato per elencare i tracciati del livello attualmente selezionato
* [Tracciato] Aggiungi un feedback visivo quando si passa il cursore su un tracciato nel pannello Tracciato
* [Tracciato] Visualizza il pannello dei tracciati ogni volta che è selezionato lo strumento Tracciato
* [Tracciato] Consente di rinominare, eliminare, copiare, tagliare, duplicare il tracciato nel pannello Tracciato
* [Path] Visualizza un messaggio quando si tenta di interagire nella finestra della vista 2D con lo strumento Tracciato
* [Library] Integrazione di nuovi contenuti (strumenti e materiali di base di percorso)
* [Tratti dinamici] Aggiungi proprietà distanza per tratti dinamici
* [Tratti dinamici] Aggiungere dimensioni e proprietà di spaziatura ai tratti dinamici
* [Tratti dinamici] Aggiungi proprietà inizio/metà/fine per tratti dinamici
* [Python]&#x200B;[USD] Esporre i parametri di configurazione del progetto per il formato USD
* [Python]&#x200B;[USD] Esporre i parametri di creazione del progetto per il formato USD
* [Esporta]&#x200B;[USD] Aggiungi le informazioni sul percorso del progetto nel file USD esportato
* [GLTF] Aggiorna le texture nella libreria durante il ricaricamento di un file GLTF
* [Shader] Riduci gli artefatti di giuntura per Isole UV con orientamento diverso
* [Engine] Aggiornamento alla versione 9.0 del motore di Substance

<b>Corretto:</b>

* [Importa] Alcuni GLB con texture non ottengono texture in Painter
* [AMD] Artefatti sui bordi per tutti i riempimenti di proiezione 3D
* [Engine] Le texture si interrompono quando si attiva o disattiva la visibilità del livello
* [Engine] Le texture sono vuote in alcuni punti quando si cambia il metodo di fusione
* [Motore] In alcuni casi, Texture/Proiezione è la modalità di alterazione vuota
* [Iray] Iterazione reimpostata su 0 durante il salvataggio del rendering
* [Log] Messaggio di errore USD quando si esegue File > Nuovo

<b>Problemi noti:</b>

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Serie di livelli] Origine di input non salvata per livello

## Versione 8

### 8.3.1

Data di pubblicazione: <b>2023/04/27</b>

<b>Aggiunto:</b>

* [Modalità cottura] Aggiungi collegamento (vuoto) per mostrare/nascondere la visualizzazione della finestra della vista
* [Modalità cottura] Mostra sempre Low Poly quando si utilizza il pulsante &quot;Nascondi mesh di cottura&quot;
* [Modalità cottura] Mostra suffisso per corrispondenza per nome in base al set di texture corrente
* [Import] Aggiungi supporto per file binari GLTF (glb)
* [Elenco Set di texture] Menu Aggiungi per selezionare o creare istanze dello shader
* [Elenco set di texture] Consente di modificare rapidamente il set di texture e la risoluzione delle porzioni UV
* [Dimensioni fisiche] Migliorare il comportamento del manipolatore quando si utilizza dimensioni fisiche in Proiezione UV
* [UI] Riporta &quot;Salva con nome&quot; nel menu principale File
* [UI] Salva selezione vista (solo 2D, solo 3D, entrambi) nel layout dell&#39;interfaccia utente
* [USD] Messaggio di errore meno vago alla creazione del progetto con forme USD non supportate
* [Python] Aggiungi eventi di cottura per seguire i progressi della cottura al forno
* [Python] Consenti di annullare una cottura al forno
* [Python] Esporta &quot;In base al modello di output&quot; per il tipo di file e la profondità di bit nell&#39;esportazione
* [Python] Tempo di aggiornamento di Exposé per TextureStateEvent.Update

<b>Corretto:</b>

* [Arresto anomalo] Raro arresto anomalo quando si chiude un progetto
* [Crash] [Baking] Attiva la sincronizzazione della mappa mesh con il Height o la curvatura su un progetto specifico
* [Arresto anomalo]&#x200B;[Scripting] Arresto anomalo durante l’aggiunta di materiale dopo la creazione dell’istanza dello shader
* [Modalità cottura] L’intensità di AO in materiale neutro non ha effetto
* [Modalità cottura] Arresto anomalo quando si passa alla modalità cottura prima che il modello venga caricato
* [Modalità di cottura] Messaggio di errore mancante nella scheda Processo di cottura
* [Modalità cottura] Le impostazioni del materiale neutro non hanno effetto dopo la reimportazione di una trama
* [Modalità cottura] Il separatore della finestra della vista viene salvato globalmente e non per modalità
* [Modalità cottura] Problema di visualizzazione: la normale media non modifica la superficie della gabbia
* [Gestione colore] L&#39;impostazione Rileva automaticamente spazio colore è disattivata quando è presente l&#39;env OCIO var
* [Contenuto] Il filtro Contorno maschera contiene artefatto con input height
* [Contenuto] Il cursore dell’intensità del filtro sfocatura Pendenza è bloccato su 1,0
* [Interop] Impossibile creare il progetto con GLTF da Sampler
* [Serie di livelli] Il valore di suddivisione della proiezione non viene aggiornato correttamente con il manipolatore
* [Linux] Scostamento tra la penna grafica del tablet e il cursore con HDPI superiore al 100%
* [Python] Arresto anomalo quando si reimporta una trama dopo aver creato un progetto
* [Substance] I rumori 3D vengono interrotti dopo la reimportazione di una trama
* [Riquadri UV] L&#39;offset per la Proiezione UV è bloccato su 1
* [Finestra vista] Il feedback visivo delle linee rette non è più visibile
* [Novità] Ritorno riga errato sui titoli delle funzioni

<b>Problemi noti:</b>

* [Importa] Alcuni GLB con texture non ottengono texture in Painter

### 8.3.0

*(Rilasciato: 10 gennaio 2023)*
Riepilogo: <b>Versione principale con nuova modalità di cottura, nuova importazione ed esportazione di file USD e supporto di dimensioni fisiche per Proiezione UV</b>

<b>Aggiunto:</b>

* [Modalità cottura] Nuova modalità di cottura dedicata al processo di cottura al forno
* [Modalità cottura] Imposta la scelta rapida per passare alla modalità di cottura su F8
* [Modalità cottura] Aggiungere i pulsanti Avvia e Annulla cottura nella finestra della vista
* [Modalità cottura] Aggiungete la selezione di cottura al forno nell&#39;elenco Set di texture
* [Modalità cottura] Aggiungere una nuova finestra Pannelli mappa trama per selezionare panettieri
* [Modalità cottura] Aggiungere una nuova finestra Impostazioni mappa trama per modificare le impostazioni di cottura
* [Modalità cottura] Aggiungere una nuova finestra Registro cottura per seguire il processo di cottura
* [Modalità cottura] Aggiungere parametri di cottura e annullare le azioni alla finestra della cronologia
* [Modalità cottura] Aggiungere breadcrumbs in Impostazioni mappa trama
* [Modalità cottura] Aggiungere miniature di mappe trama nella finestra Pannelli mappe trama
* [Modalità cottura] Aggiungere il menu comprimibile delle impostazioni di visualizzazione nella finestra della vista 3D
* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama High-Poly
* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama della gabbia e il wireframe
* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama a basso poli
* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare bordi netti senza giunture UV come errori
* [Modalità cottura] Informate nella finestra della vista sugli errori di mesh e di cottura se il registro di cottura non è visibile
* [Modalità cottura] Aggiungi azione per sincronizzare le impostazioni del fornaio tra tutti i set di texture

  Nella finestra Pannelli mappa trama, ogni panettiere (così come le impostazioni comuni) può essere sincronizzato tra set di texture facendo clic sull&#39;icona di collegamento accanto al nome. Questa azione consente di aprire una finestra che consente di selezionare quali set di texture condivideranno gli stessi parametri.

* [Modalità cottura] Aggiungere azioni per copiare e incollare le impostazioni del fornaio

  Nella finestra Pannelli mappa trama sono disponibili le azioni per copiare e superare le impostazioni di ogni panettiera tra i set di texture, tramite il menu dedicato nella parte superiore della finestra o il menu contestuale, accessibile facendo clic con il pulsante destro del mouse.

* [Modalità di cottura] Pulsante Aggiungi nel registro di cottura per passare da un errore alle impostazioni corrette

  Quando un fornaio non va a buon fine o una trama non viene caricata correttamente, nel Registro forni viene visualizzato un messaggio di errore. Un pulsante accanto al messaggio consente di modificare la finestra Impostazioni cassette e mappe trama per visualizzare le relative impostazioni. In questo modo è possibile isolare più facilmente la fonte di un problema per poterlo risolvere.

* [Modalità cottura] Aggiungete menu per gestire set di texture e selezioni di forni

  Nelle finestre &quot;Set di texture&quot; e &quot;Mesh Map Bakers&quot; è stato aggiunto un menu di azioni che permette di copiare e invertire le selezioni.

* [Modalità cottura] Dividi elenco di selezione forni per set di texture
* [Modalità cottura] Dividere le impostazioni comuni per set di texture
* [Modalità cottura] Carica maglie ad alto poligono e gabbia senza bloccare l&#39;interfaccia
* [Modalità cottura] Utilizzare la barra di avanzamento della finestra della vista per visualizzare il caricamento della trama
* [Modalità di cottura] Aggiungere lo stato di caricamento della trama nel registro di cottura
* [Modalità cottura] Consente di ruotare la trama nella finestra della vista durante la cottura
* [Modalità cottura] Imposta l&#39;ordine di cottura in base alla visibilità della finestra della trama corrente
* [Modalità cottura] Visualizza gabbia di cottura implicita nella finestra della vista

  Quando non si utilizza un file di mesh di gabbia personalizzato, viene generata e visualizzata una mesh di gabbia automatica nella finestra della vista. Le sue dimensioni saranno basate sul parametro Distanza frontale massima dalle impostazioni comuni di cottura al forno. La maglia della gabbia viene utilizzata per indicare la distanza di corrispondenza tra il poly basso e alto.

* [Modalità di cottura] Mostra elenco corrispondente di nomi di mesh per corrispondenza per nome nel registro di cottura
* [Modalità cottura] Usate materiale neutro per visualizzare il modello 3D nella finestra della vista
* [Modalità cottura] Disattiva il calcolo del motore in modalità cottura
* [Modalità cottura] Visualizza un avviso quando si esce dall’app mentre è in corso una cottura
* [Bakers] Aggiornamento delle etichette delle impostazioni di antialiasing

  I valori delle impostazioni di antialiasing sono stati rinominati &quot;Supersampling&quot; e con un numero moltiplicatore esplicito per chiarirne il comportamento.

* [Bakers] Aggiornate bakers alla versione 2.5.7.
* [USD] Importare ed esportare file Universal Scene Description (USD)
* [USD] Aggiungere le opzioni USD alla finestra Nuovo progetto quando si seleziona un file USD
* [USD] Aggiungi nuova finestra di selezione Ambito e Varianti

  Quando si importa un file USD, facendo clic sul pulsante Modifica nella finestra Nuovo progetto o Configurazione progetto è possibile selezionare la parte e le varianti di un file USD da importare.

* [USD] Opzione Aggiungi livelli di suddivisioni

  Quando create un nuovo progetto con un file di trama USD che contiene suddivisioni, è possibile selezionare il livello di suddivisioni utilizzando un cursore. Il progetto verrà creato con la trama suddivisa. Il livello può essere modificatore tramite Configurazione progetto.

* [USD] Importa mesh con skin USD in un fotogramma specifico

  Quando crei un nuovo progetto con un file di trama USD che contiene animazioni, è possibile selezionare il fotogramma utilizzando un cursore che riflette la sequenza temporale incorporata. Il fotogramma può essere modificatore tramite Configurazione progetto.

* [USD]&#x200B;[Esporta] Aggiungi un’opzione per esportare i file USD

  Nuova casella di controllo Esporta USD aggiunta alla finestra Esporta texture. Quando è selezionato, consente di esportare file USD e mappe texture utilizzando qualsiasi modello.

* [USD]&#x200B;[Esporta] Aggiungi il formato di file USD all’esportazione con trama
* [USD] Rinomina il predefinito di esportazione &quot;Rugosità metallo USD PBR&quot; esistente per renderlo più esplicito

  Il modello di esportazione USD precedentemente noto come &quot;Rugosità metallo USD PBR&quot; è ancora accessibile tramite Esporta texture > Modello di output > USDz (Apple AR).

* [Annullamento automatico] Aggiungi orientamento blocco per impacchettamento

  Nuova opzione per lo scorrimento automatico delle impostazioni che consente di mantenere l’orientamento delle Isole UV esistenti quando si utilizza la funzione di impacchettamento. È possibile accedervi da Nuovo progetto > Opzioni di annullamento automatico > Isola UV orientamento.

* [Dimensioni fisiche] Aggiungi impostazione per utilizzare automaticamente la Dimensioni fisiche nell’effetto/livello di riempimento

  È stata aggiunta una nuova opzione che consente di passare automaticamente alla scala dimensioni fisiche quando si utilizza un materiale con dimensioni fisiche incorporata. Può essere attivato per ogni progetto tramite Nuovo progetto o tramite Modifica > Configurazione progetto > Dimensioni fisiche > Converti il ridimensionamento del livello di riempimento in Dimensioni fisiche quando si assegnano i materiali.

* [Dimensioni fisiche] Esposizione dimensioni fisiche per Proiezione UV

  Il ridimensionamento delle dimensioni fisiche è ora disponibile per le Proiezioni UV: consente di ridimensionare automaticamente un materiale in base alla dimensioni fisiche di una trama. Può essere selezionata da Scala > Dimensioni fisiche nel livello di riempimento o nella finestra Proprietà effetti.

* [Scripting]&#x200B;[Python] Consenti di eseguire query sulla versione dell’applicazione
* [Scripting]&#x200B;[JavaScript] Aggiorna l’API in base ai nuovi parametri di baking
* [Scripting]&#x200B;[Python] Modulo Baking: modificare i parametri di baking
* [Scripting]&#x200B;[Python] Modulo Baking: avvia/annulla baking
* [Scripting]&#x200B;[Python] Modulo Baking: selezionare il metodo di curvatura
* [Scripting]&#x200B;[Python] Modulo Baking: selezione di panettieri/piastrelle uv
* [Scripting]&#x200B;[Python] Modulo Baking: sincronizzare le impostazioni baker su tutti i set di texture
* [SVT] Abilitazione del supporto hardware di tipo sparse sulle GPU AMD

  L’accelerazione hardware per il sistema Sparse Virtual Textures può ora essere abilitata con le GPU AMD. Questa impostazione viene attivata automaticamente nelle preferenze generali.

* [Proiezione] Rinomina parametri proiezione cilindrica

  Il parametro &quot;Cylinder Culling&quot; è stato rinominato &quot;Backface Culling&quot; per rappresentarne meglio l’azione. La descrizione associata è stata modificata di conseguenza.

* [Project] Salva la versione dell&#39;applicazione nel progetto e recuperala tramite script

  A partire dalla versione 8.2, la versione dell’applicazione viene ora memorizzata nel file spp durante il salvataggio.
  Questo numero di versione può essere recuperato con la funzione last\_saved\_substance\_painter\_version() nel modulo di progetto dell’API Python.
  Per i progetti realizzati prima della versione 8.2, il valore restituito sarà null.

* [Import] Migliorare i tempi generali di importazione dei modelli 3D

  Abbiamo migliorato il tempo generale di importazione delle trame. Ad esempio, la riduzione del tempo di attesa durante il caricamento di trame ad alto poli per la cottura al forno. Questa ottimizzazione si applica in particolare al caricamento di file OBJ.

<b>Corretto:</b>

* [Arresto anomalo] Modifica dei canali su un filtro con uno stack specifico
* [Mac]&#x200B;[M1] Arresto anomalo durante la creazione di un livello di riempimento e l&#39;uscita dal gruppo di livelli

  Questo problema può essere risolto eseguendo l’aggiornamento a Mac OS 13 (Ventura).

* [Scripting]&#x200B;[Python] Arresto anomalo quando si utilizza ui.add\_dock\_widget() con tipo errato
* [Baking] Messaggio di errore incompleto nel registro quando un baking non riesce
* [Baking] La memoria non viene liberata al termine della cottura
* [Engine] La cache delle texture non si aggiorna quando si modifica la visibilità degli effetti
* [Esporta] La vista 2D esporta una mappa casualmente uniforme
* [Progetto] Errore di allocazione della memoria durante il salvataggio del progetto con trama grande
* [Riquadro di visualizzazione] In alcuni casi, l’accesso automatico al contenuto causa artefatti durante l’uso del colore

<b>Problemi noti:</b>

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Serie di livelli] Origine di input non salvata per livello

### 8.2.0

*(Rilasciato il 6 ottobre 2022)*
Riepilogo: **Versione principale con nuovi pannelli di onboarding (nuovo pannello di benvenuto e novità), esportazione in SBSAR, effetti per cartella, diversi miglioramenti per la qualità della vita e correzioni di bug.**

**Aggiunto:**

* [Onboarding] Pannello Onboarding per accogliere nuovi utenti

  È stata aggiunta una nuova schermata introduttiva quando i nuovi utenti CC aprono Painter per la prima volta.

* [Onboarding] Novità del pannello per migliorare la ricerca di nuove funzioni

  È stata aggiunta una nuova schermata Novità che mostra le principali nuove funzioni. Viene visualizzato automaticamente la prima volta che Painter viene aperto dopo un aggiornamento importante ed è nuovamente accessibile da Aiuto > Novità.

* [Onboarding] Rinomina il vecchio benvenuto in &quot;Schermata Home&quot;

  La vecchia schermata introduttiva è stata rinominata Schermata iniziale per evitare confusione con la nuova schermata introduttiva.

* [UI] Risoluzione dei problemi di ridimensionamento per schermi ad alto DPI

  È stato migliorato l’adattamento dell’interfaccia utente di Painter su schermi ad alta definizione con ridimensionamento personalizzato.

* [UI] Evitare messaggi di errore persistenti nell&#39;interfaccia utente

  I messaggi di errore dei progetti precedenti sono stati rimossi dalla barra di stato inferiore.

* [UI] Rielaborare il menu di salvataggio

  Le opzioni di salvataggio aggiuntive sono ora raggruppate in un sottomenu e alcune sono state rinominate per coerenza.

* [UI] Salvare ed esportare/condividere i layout dell’interfaccia utente

  Nel menu Finestra sono disponibili nuove azioni per salvare il layout dell&#39;interfaccia utente nei file e ricaricarli. I layout di disegno e rendering vengono salvati separatamente.
  A &quot;substance\_painter.ui&quot; sono state aggiunte varie funzioni per salvare, reimpostare e caricare anche i layout dell&#39;interfaccia utente.

* Aggiungere azioni di copia/incolla per i metodi di fusione/opacità di un livello

  È stata aggiunta la nuova voce &quot;Opzioni di fusione&quot; al menu di scelta rapida dei livelli. Consente di copiare e incollare il metodo di fusione e l’opacità di tutti i canali da un livello all’altro.

* Applicare il metodo di fusione/opacità a tutti i canali di un livello

  È stata aggiunta una funzionalità di clic con il pulsante destro del mouse al metodo di fusione e all’opacità dei livelli che consente di applicare a tutti i canali l’impostazione su cui si fa clic.

* Ricarica trama con una scelta rapida da tastiera (CTRL+MAIUSC+R)

  È stata aggiunta una scelta rapida modificabile per ricaricare il file mesh con le ultime impostazioni disponibili. È possibile accedere a questa opzione anche da Modifica > Reimporta trama.

* Ripristina i parametri predefiniti di Substance

  È stato aggiunto un nuovo pulsante nelle proprietà nella parte inferiore delle risorse .sbsar che consente di ripristinare le impostazioni predefinite della risorsa.

* Ripristina pennello artistico ai valori predefiniti

  È stato aggiunto un nuovo menu nella sezione Pennello in Proprietà che consente di ripristinare il pennello di base predefinito.

* Fare clic con il pulsante destro del mouse per ripristinare i singoli parametri di Substance ai valori predefiniti

  È stata aggiunta la possibilità di ripristinare singoli parametri all&#39;interno di una risorsa .sbsar tramite clic con il pulsante destro del mouse.

* [Pannello Risorse] &quot;Blocca&quot; le risorse preferite da visualizzare sopra il pannello Risorse

  È stata aggiunta una nuova opzione di clic con il pulsante destro del mouse sulle risorse della libreria che consente di bloccarle come preferite nella parte superiore del pannello. Puoi anche visualizzare tutte le tue risorse preferite tramite Ricerche salvate.

* [Pannello Risorse] Elimina, ricarica e rinomina le risorse

  Sono state aggiunte le opzioni del menu di scelta rapida per eliminare, ricaricare e rinominare le risorse nella libreria utente. Vengono eliminati direttamente dal percorso della libreria sul disco e ricaricati dal percorso originale. Le risorse che fanno parte di un pacchetto come .abr o .sbsar non possono essere modificate singolarmente.

* [Selezione colore] Aggiungere metodi di fusione all’effetto Selezione colore
* [Serie di livelli] Aggiungi metodo di fusione e opacità ai filtri
* [Serie di livelli] Consenti valori di suddivisione in porzioni superiori a 128 per livelli di riempimento/effetti
* [Serie di livelli] Estremità cilindriche per la proiezione cilindrica nel livello di riempimento/effetto

  La proiezione cilindrica nelle proprietà del livello Riempimento ora ha l&#39;opzione per rimuovere le estremità dei cilindri.

* [Log] Visualizza un messaggio di errore se la parte mesh si trova in uno spazio negativo quando si tenta di creare un progetto di porzione UV

  È stato aggiunto un messaggio di errore più chiaro quando non è possibile creare un progetto di porzioni UV perché le parti UV si trovano in spazi negativi.

* [Progetto] Indica la versione nel messaggio di errore &quot;dati troppo recenti&quot; quando si apre un progetto

  Quando si apre un progetto troppo recente per l’applicazione, il messaggio di errore indica ora la versione del progetto per facilitare l’identificazione della versione corretta dell’applicazione.

* [Finestra vista] Consente di illuminare la trama da sotto

  È stato aggiunto un nuovo parametro di Allineamento ambiente in Impostazioni visualizzazione > Fotocamera > Impostazioni ambiente per allineare l’illuminazione della mappa ambiente alla videocamera quando è impostata su &quot;Locale&quot;.

* [Finestra vista] Visualizza R, G, B e Alpha nella finestra vista (modalità di visualizzazione solo)

  In Impostazioni schermo > Impostazioni finestra vista > Visualizzazione canali è disponibile una nuova impostazione Canali colore che consente di visualizzare solo il componente R, G, B o Alpha di un canale quando è attiva la modalità di visualizzazione singola.

* [Shader] Consenti di impostare i canali utente come RGBA negli shader di livello materiale

  Quando si imposta la configurazione dei canali dell’insieme di texture all’interno di uno shader per la creazione di livelli di materiale, è ora possibile specificare il formato del canale da deviare dal valore di default. In particolare, è possibile richiedere canali utente a colori invece che solo in scala di grigi.

* [Esporta] Consente di esportare le texture come SBSAR

  Quando si esportano le texture tramite la finestra File > Esporta texture, è possibile scegliere il formato di file SBSAR (Substance archivio) per raggrupparle nuovamente. Il contenuto del SBSAR dipende dal modello di output utilizzato.
  Il formato del file SBSAR può essere impostato anche nei predefiniti di esportazione. Quando utilizzate la configurazione ibrida (SBSAR + Altro formato), le texture che hanno come destinazione un SBSAR vengono raggruppate, mentre il resto viene esportato insieme.

* [Esporta] Opzione Esporta 16 bit per il formato di file EXR

  Quando si esportano i file di texture EXR, ora è possibile scegliere tra 16f bit (Half-Float) o 32f bit (Float) nella finestra Esporta texture (sia per le impostazioni di esportazione che per i predefiniti di esportazione). I vecchi progetti e i vecchi predefiniti di esportazione verranno impostati per impostazione predefinita su 16 f bit per riflettere il vecchio comportamento.

* [Python] Aggiungi evento per sapere quando vengono modificati i set di texture

  Il nuovo &quot;substance\_painter.event.TextureStateEvent&quot; consente di sapere quando un insieme di texture è stato modificato a causa di un tratto pennello, di un nuovo canale aggiunto o di un canale rimosso.

* [Python] Consenti di ottenere e impostare le risorse Mesh Map nelle impostazioni Texture Set

  Nel modulo &quot;substance\_painter.project&quot; sono state aggiunte nuove funzioni per ottenere e impostare le risorse per le mappe mesh. Queste funzioni possono essere utilizzate per aggiornare le mappe di trama a cui fanno riferimento le impostazioni del set di texture.

* [Plugin] Rimuovi l&#39;opzione per ottenere altri plug-in JS

  È stata rimossa l’opzione per ottenere i plug-in JavaScript poiché erano ospitati nel sito Web di condivisione obsoleto.

* [Content] Aggiungi nuovo modello Roblox ed esporta predefinito

  Sono stati aggiunti un nuovo modello di progetto Roblox &quot;Variante materiale&quot; e &quot;Aspetto superficie&quot; e un predefinito di esportazione per facilitare l’esportazione di texture PBR in Roblox. È possibile accedere al modello dalla finestra File > Nuovo progetto.

* Aggiornamento della Substance Engine alla versione più recente (8.6.3)
* [Steam] Versione ottimizzata per chipset Apple Silicon (Apple M1 / M2)

**Corretto:**

* Arresto anomalo quando si utilizza exr 16.000
* [Arresto anomalo] Ctrl Z Dopo l’eliminazione di un’istanza dello shader
* [Iray] IoR è bloccato su 1 per alcuni shader
* [Win]&#x200B;[Baking] Alcuni High-Poly non vengono caricati
* [Gestione colore] Nome dello spazio colore non corretto nell&#39;interfaccia utente con filtri
* [Python] Gli oggetti risorsa restituiti dalla funzione di importazione non hanno un tipo

  Quando si importava un pacchetto di Substance in Python, la funzione restituiva il pacchetto invece dei relativi grafici. Il modulo delle risorse ora fornisce funzioni e parametri per recuperare i grafici di un pacchetto di Substance.

**Problemi noti:**

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Serie di livelli] Origine di input non salvata per livello
* [Pittura] L’anti-alias temporale provoca artefatti quando si dipinge in alcuni casi
* [Esporta] La vista 2D esporta una mappa casualmente uniforme

### 8.1.3

*(Rilasciato: 25 Agosto 2022)*
Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

* Aggiornamento a Iray SDK 1.6

**Corretto:**

* [Shader] Arresto anomalo con il vecchio shader difettoso
* [Livelli di materiale] I materiali possono scomparire quando si riapre un progetto

**Problemi noti:**

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Serie di livelli] Origine di input non salvata per livello
* [Arresto anomalo] Ctrl Z Dopo l’eliminazione di un’istanza dello shader
* [Iray] IoR è bloccato su 1 per alcuni shader

### 8.1.2

*(Rilasciato: 19 luglio 2022)*
Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

* [Auto Unwrap] Nuova opzione &quot;Ottimizza per trame organiche&quot; per selezionare l&#39;algoritmo di segmentazione
* [Dimensioni fisiche] Opzioni di esposizione dell&#39;unità in Nuovo progetto e Configurazione progetto
* [Gestione colore] Usa visualizzazione monitor per impostazione predefinita quando si utilizza ACE
* [Gestione colore]&#x200B;[Python] Durante la creazione del progetto, prendi in considerazione il file predefinito ACE env-var
* [Gestione colore] Reimposta le impostazioni di Gestione colore nella finestra Nuovo progetto quando la configurazione cambia
* [Gestione colore] Disattiva accesso alle impostazioni OCIO quando è presente env-var
* [Gestione colore] Aggiorna in modo sicuro le impostazioni ACE quando un parametro non esiste più
* Aggiornamento della Substance Engine alla versione 8.6.0
* [Esporta] Aggiungi nuovo predefinito di esportazione GLTF con supporto Spostamento
* [Scripting]&#x200B;[Python] Recupero delle informazioni sulle risorse (inclusi i metadati personalizzati)
* [Scripting]&#x200B;[Python] Aggiungi funzione all’elenco di query dei nomi mesh per set di texture
* [Content] Aggiungi un nuovo modello di fusione ed esporta predefinito

**Corretto:**

* [MacOS] Arresto anomalo all&#39;avvio di Iray in alcuni casi
* [Miniature] Le miniature dello shelf non vengono caricate correttamente
* Più canali UV vengono ignorati
* [Annullamento automatico] Calcolo non necessario durante la divisione di isole lunghe
* [Srotolamento automatico] Opzione per evitare isole allungate non considerata
* [Annullamento automatico] Perdita di dati aggiuntivi (colori dei vertici) durante il reinserimento degli UV
* [UI] Barra di scorrimento orizzontale nella finestra delle proprietà quando Gestione colore è abilitato
* [Gestione colore] Le configurazioni OCIO mancano del ruolo substance\_3d\_painter\_standard\_srgb
* [Generator] Utilizzo errato dei dati utente &quot;disabilitato&quot;
* [Gestione colore] Il menu a discesa Spazio colore &quot;Non compatibile&quot; non deve essere selezionabile
* [Gestione colore]&#x200B;[Shader] L’esclusione di sRGB definisce non funziona più
* [Generator] Utilizzo errato dei dati utente &quot;disabilitato&quot;
* [Serie di livelli] Anteprime interrotte con progetti con porzioni UV
* La documentazione API di [Shader] non è completamente aggiornata con Bent Normals
* [Export]&#x200B;[Interoperability] Impossibile inviare a Stager con caratteri speciali
* [Contenuto] Alcune miniature dei pennelli predefiniti sono vuote o troppo scure

**Problemi noti:**

* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
* [Serie di livelli] La sorgente di input non viene salvata per livello
* [Arresto anomalo] Ctrl Z Dopo l’eliminazione di un’istanza dello shader
* [Iray] IoR è bloccato su 1 per alcuni shader
* [Shader] Arresto anomalo con il vecchio shader difettoso

### 8.1.1

*(Rilasciato il 28 giugno 2022)*
Riepilogo: **Hotfix per le versioni secondarie**

**Aggiunto:**

* [Pila di livelli] Quando si fa clic con il tasto Alt su una maschera, gli effetti non vengono più deselezionati

**Corretto:**

* [Arresto anomalo] Apertura di un vecchio progetto salvato in modalità di visualizzazione Solo
* [Arresto anomalo] Eliminare un Generatore nelle proprietà
* [Texture Set Settings] Il mixaggio delle Occlusioni normali/ambientali e il height ai metodi normali non funzionano
* [Esporta] Esporta le texture utilizzando l’imbottitura di diffusione esegue il rendering delle mappe nere

**Problemi noti:**

* [MacOS] Arresto anomalo all’avvio di Iray su Monterey
* [Anteprima miniatura] Le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati

### 8.1.0

*(Rilasciato il 7 giugno 2022)*
Riepilogo: **Versione principale con supporto ICC, ridimensionamento del materiale in base ai dati della dimensioni fisiche, nuovi forni, miglioramenti del contagocce colore e una serie di contenuti aggiuntivi**

**Aggiunto:**

* [Gestione colore] Aggiungi il supporto per i profili ICC con Adobe Color Engine (ACE)
* [Gestione colore] Aggiungi il supporto per &quot;Adobe 98 RGB&quot; come spazio colore di lavoro per ICC
* [Gestione colore] Consente di configurare le impostazioni ACE/ICC tramite un file di configurazione
* [Gestione colore] Consente di inserire valori di colore lineari nel Selettore colore con la modalità Legacy
* [Gestione colore] Consente di specificare il profilo colore utilizzato per la selezione del colore al di fuori dell&#39;interfaccia utente
* [Gestione colore] Ricordare l&#39;ultimo valore di visualizzazione scelto nella finestra della vista
* [Gestione colore]&#x200B;[Substance] Fate funzionare correttamente i generatori/filtri con la Gestione colore
* [Gestione colore]&#x200B;[Substance] Aggiungi nuove parole chiave di esclusione dello spazio colore $working e $standardsrgb
* [Dimensioni fisiche]&#x200B;[Engine] Estrai informazioni dimensioni fisiche dalla trama
* Calcolo Dimensioni fisiche [Dimensioni fisiche]&#x200B;[Engine]
* [Dimensioni fisiche] Esporre le opzioni per utilizzare dimensioni fisiche nell&#39;interfaccia utente
* [Dimensioni fisiche] Aggiungere gli helper visivi nella finestra della vista
* [Baking] Aggiungere Height
* [Baking] Aggiungere il fornaio normale piegato
* [Baking] Aggiungi panettiere opacità
* [Contagocce] Nuova anteprima del contagocce colore accanto al mouse e al colore gestito
* [Contagocce] Il pannello Selettore colore riappare nell&#39;ultima posizione quando viene riaperto
* [Contagocce] Una nuova icona per il Selettore materiale
* [Contagocce] Il colore gestisce l&#39;anteprima del canale del selettore colore
* [Contagocce] Aggiungete al contagocce la funzionalità clic per selezionare
* [Contagocce] Il selettore di materiali non attiva più i canali non attivi
* [Contagocce] Consenti di utilizzare il contagocce con una scelta rapida
* [Contagocce] Il contagocce preleva il canale pertinente, se applicabile
* [Contagocce] Quando si entra in modalità Selettore colore, tutte le scelte rapide vengono disattivate
* [Contagocce] Rimuovi la selezione automatica del campo esadecimale
* [Contagocce] Non chiudere il pannello quando si utilizza il selettore di materiale
* [Contagocce] Nuovo stato disabilitato quando il canale non è disponibile per la selezione
* [Esporta] Aggiungi attributo tangente all&#39;esportazione glTF
* Aggiorna Substance Engine alla versione 8.4
* Aggiorna Scorrimento automatico a 0.9.0
* Esegui l’aggiornamento a Qt 5.15.8
* Aggiornamento a Python 3.9
* [Shader] Aggiungere il supporto per l&#39;ombreggiatura Normali piegati
* [MacOS] Supporto di 3DConnection SpaceMouse
* [Python] Documentazione della versione Python utilizzata nell’API
* [Content] Aggiungi 6 nuovi rumori 3D con 105 predefiniti
* [Content] 20 nuove mappe di grunge e 2 modelli di pieghe di tessuto
* [Content] Aggiorna il predefinito di esportazione &quot;Mesh maps&quot; per utilizzare nuovi forni
* [Contenuto] I filtri Sfoca Pendenza e Altera dipendono dalla risoluzione del set di texture
* [Content] Aggiorna i progetti di esempio per utilizzare i tre nuovi panettieri

**Corretto:**

* [glTF] Impossibile aprire glTF con carattere speciale
* [Engine] Artefatti con anisotropia e SVT disattivati
* [MacOS]&#x200B;[M1] I materiali avanzati non vengono visualizzati correttamente
* [Elaborazione trama] Impossibile importare trame da Modeler
* [UI] Barra di scorrimento orizzontale nella nuova finestra del progetto con la Gestione colore attivata
* [Gestione colore] Valore dello spazio di lavoro mancante nel selettore colore con alcune configurazioni OCIO
* [Gestione colore] L’anteprima del pennello nella finestra della vista non è sottoposta alla gestione del colore
* [SpaceMouse] Il pivot non viene aggiornato immediatamente con la modifica dello stato attivo e a volte fuori dal modello
* [Export]&#x200B;[USD] I file USD esportati hanno una struttura errata
* [USD] Problema di Occlusione ambientale durante l’esportazione
* [Content] Aggiorna la trama della miniatura in modo che corrisponda al progetto di esempio Preview Sphere

**Problemi noti:**

* Esporta le texture utilizzando il riempimento di diffusione esegue il rendering delle mappe nere
* Il mixaggio delle Occlusioni normali/ambientali è interrotto
* [MacOS] Arresto anomalo all&#39;avvio di Iray in alcuni rari casi
* [Anteprima miniatura] Le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati

## Versione 7

### 7.4.3

*(Rilasciato: 11 aprile 2022)*
Riepilogo: **Bugfix con supporto di 3Dconnection SpaceMouse nel viewport 2D**

**Aggiunto:**

* [SpaceMouse] Supporto di 3DConnection SpaceMouse nel viewport 2D

**Corretto:**

* [Selettore colore] Impossibile scrivere in un campo esadecimale
* [Gestione colore] Le risorse utilizzate in modalità di proiezione non sono sottoposte alla gestione del colore nella sovrapposizione
* [Gestione colore] Gli errori non vengono segnalati nel registro
* [SpaceMouse] Rimuovere un messaggio di errore generico se l&#39;utente non dispone di un oggetto SpaceMouse
* [SpaceMouse] Quando si carica un progetto, il punto fulcro è sempre nascosto
* [Panettieri] L&#39;impostazione &quot;Normali medi&quot; non ha effetto nei progetti per le porzioni UV
* [Piastrella UV] Le sovrapposizioni dei riquadri UV inattivi scompaiono quando si ricarica la trama con riquadri diversi
* [Scripting]&#x200B;[Python] Lo scripting remoto è interrotto
* [Scripting]&#x200B;[Python] Diversi canali non possono essere interrogati dall’API e si verifica un errore
* [Scripting]&#x200B;[Python] Arresto anomalo quando si utilizza l&#39;evento ProjectEditionEntered
* [Scripting]&#x200B;[Python] Arresto anomalo durante la chiamata di get\_active\_stack()

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* [UI] Barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella nuova finestra del progetto
* [Mac M1] I materiali avanzati non vengono visualizzati correttamente

### 7.4.2

*(Rilasciato: 8 marzo 2022)*
Riepilogo: **Correzione rapida con supporto di 3Dconnection SpaceMouse e miglioramenti OCIO (Color Management)**

**Aggiunto:**

* [SpaceMouse]&#x200B;[Windows] Supporto di 3Dconnection SpaceMouse nel riquadro di visualizzazione 3D per la navigazione
* [SpaceMouse]&#x200B;[Windows] Scelte rapide/tasti di base per i modelli Pro ed Enterprise di SpaceMouse nella finestra della vista 3D
* [SpaceMouse]&#x200B;[Windows] Icona del centro di rotazione dedicato nella finestra della vista 3D
* [Gestione colore] Utilizzare i ruoli dalla configurazione OCIO per modificare le impostazioni predefinite
* [Gestione colore] Gestione colore gestisce la finestra delle proprietà per i widget colore
* [Gestione colore] Gestione colore gestisce la finestra delle proprietà per l’anteprima del materiale
* [Gestione colore] Campioni di gestione colore nel selettore colore
* [Gestione colore] Aggiungi un’impostazione per definire lo spazio colore sRGB standard
* [Gestione colore] Aggiungi lo spazio cromatico sRGB standard dalla configurazione OCIO nel selettore colore. Elenco selettori visualizzazione
* [Gestione colore] Miglioramenti per il menu di esclusione dello spazio colore
* [Gestione colore] Consente di ignorare lo spazio colore della mappa dell&#39;ambiente in Impostazioni schermo
* [Gestione colore] Disegna sfumature selettore colore in base alla visualizzazione corrente
* [Gestione colore] Blocca valori HDR per impostazione predefinita nell&#39;editor colori
* [Gestione colore] Usa passthrough (senza spazio colore) per i filtri in modalità Legacy
* [Gestione colore] Limita la visualizzazione delle sfumature nell&#39;editor colori in base all&#39;intervallo [0-1]
* [Gestione colore] Nascondi selettore visualizzazione nel selettore colore in modalità Legacy
* [Gestione colore] Rendi il selettore colore un campo esadecimale sempre nello spazio colore sRGB
* [Gestione colore] Disattiva il selettore colore Visualizza il menu a discesa per i canali dati
* [Ottimizzazione] La griglia di alterazione ricalcola solo le porzioni UV coperte
* [Esportazione] Consente di esportare i progetti di porzioni UV per Sketchfab, USD e glTF
* [Scripting]&#x200B;[Python] Consente di modificare la funzione di mappatura tonale

**Corretto:**

* [Sketchfab] L&#39;aggiornamento del modello esistente comporta la creazione di un nuovo modello
* [Sketchfab] Arresto anomalo durante la ricerca di un modello aggiornato in precedenza
* Arresto anomalo durante l’esportazione in USD
* Arresto anomalo durante la creazione di una nuova istanza dello shader nella maschera di geometria o quando la geometria è nascosta
* [Finestra Importa risorsa] Arresto anomalo quando si modifica il tipo di risorse importate
* Le mappe mesh normali vengono invertite quando vengono utilizzate nella pila di livelli
* [Substance] Metodo di fusione dei dati utente non preso in considerazione
* [Gestione colore] Le bitmap con spazio colore nel nome del file vengono importate come sequenze di porzioni UV
* [Gestione colore] Gli output con gestione del colore del grafico a Substance si trovano in uno spazio colore errato
* [Gestione colore] Lo strumento Riempimento poligonale visualizza il colore errato
* [Gestione colore] Il tonemapper ACES viene applicato ai canali in modalità Solo
* [Gestione colore] L’illuminazione della sfera di anteprima dello strumento non è gestita dal colore
* [Gestione colore]&#x200B;[Esporta] Le mappe convertite applicano una conversione errata
* [Scripting]&#x200B;[Python]&#x200B;[Gestione colore] I progetti creati con la variabile di ambiente template e OCIO sono in modalità Legacy
* [Scripting]&#x200B;[Python] Impossibile utilizzare la funzione di valutazione JavaScript all&#39;avvio
* [Offerta Adobe 3D] Impossibile avviare Painter quando si utilizzano impostazioni internazionali con lingue non supportate per impostazione predefinita

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* [UI] Barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella nuova finestra del progetto
* [Panettieri] L&#39;impostazione &quot;Normali medi&quot; non ha effetto nei progetti per le porzioni UV
* [Mac M1] I materiali avanzati non vengono visualizzati correttamente
* [Gestione colore] Le risorse utilizzate in modalità di proiezione non sono sottoposte alla gestione del colore nella sovrapposizione
* [Selettore colore] Impossibile scrivere in un campo esadecimale

### 7.4.1

*(Rilasciato: 14 dicembre 2021)*
Riepilogo: **Correzione rapida con miglioramenti alla gestione del colore**

**Aggiunto:**

* [Gestione colore] Usa ruolo dati nei nomi file esportati
* [Gestione colore] Per impostazione predefinita, espandi la sezione Gestione colore quando OCIO è selezionato nelle finestre Nuovo progetto e Impostazioni progetto
* [Gestione colore] Aggiungere il tonemapper ACES in modalità legacy
* [Gestione colore] Regolare le impostazioni di configurazione predefinite
* [Gestione colore]&#x200B;[Esporta] Riempi $colorSpace nei nomi dei file per i canali dati
* [Esporta] Esporta progetto porzione UV in Stager
* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
* [Interoperabilità] Consente di inviare un progetto UV Tile a Stager

**Corretto:**

* [MacOS]&#x200B;[Arresto anomalo] Painter non inizia con Catalina
* [Gestione colore]&#x200B;[Arresto anomalo] Arresto anomalo casuale durante la riproduzione con tipo di dati/gestione colore sul canale utente
* [Gestione colore] Le risorse utilizzate come scala di grigio nello spazio colore della maschera visualizzano il nuovo menu
* [Gestione colore] Il canale utente è più scuro nella finestra della vista in modalità legacy + visualizzazione solo
* [Gestione colore] La mappa Env è sempre lineare quando utilizzata in iRay
* [Gestione colore] Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* [Gestione colore] Il selettore colore non funziona all’interno di una Substance in modalità legacy
* [Gestione colore] Il passaggio tra le viste dei singoli canali nella finestra della vista viene visualizzato con lo spazio cromatico corretto quando si utilizza il menu a discesa
* [Gestione colore] L’esportazione applica la conversione errata ai canali utente con gestione del colore in modalità legacy
* I tratti creati nella maschera di visualizzazione Solo non vengono visualizzati quando si ritorna alla vista Materiale
* [Esportazione] Le mappe convertite non vengono esportate come canali con gestione del colore
* [Set di texture] Descrizione comando con nome originale mancante nei canali utente rinominati
* [Steam] File mancanti durante la verifica dell&#39;integrità del file con Steam

**Problemi noti:**

* [Mac M1] I materiali avanzati non vengono visualizzati correttamente

### 7.4.0

*(Rilasciato il 24 novembre 2021)*
Riepilogo: **Versione principale. Introduzione della prima versione della gestione del colore, disancoraggio della vista 2D o 3D, nuova opzione per lo srotolamento automatico degli UV per evitare isole allungate, chiamata delle funzioni JavaScript dall&#39;API Python e nuovo contenuto**

**Aggiunto:**

* [Gestione colore] Supporto della gestione colore OpenColorIO versione 2
* [Gestione colore] Aggiungere impostazioni di gestione del colore alle impostazioni del progetto
* [Gestione colore] Finestra di avvertenza sulle modifiche alla configurazione di Gestione colore all’apertura di un progetto
* [Gestione colore] Visualizza un messaggio di errore se è selezionato un file di configurazione OCIO non valido
* [Gestione colore] Consente di ignorare la configurazione con la variabile di ambiente OCIO
* [Gestione colore] Più configurazioni OCIO integrate per impostazione predefinita con l&#39;applicazione
* [Gestione colore] Estrai il nome dello spazio colore dal nome del file bitmap importato
* [Gestione colore] Consente di ignorare lo spazio colore con uno spazio colore dalla configurazione nella finestra Proprietà
* [Gestione colore] Aggiungere opzioni di gestione del colore nelle impostazioni del set di texture
* [Gestione colore]&#x200B;[Finestra vista] Consente di gestire separatamente i colori delle viste 2D e 3D
* [Gestione colore] Caricare e convertire la mappa dell&#39;ambiente nello spazio colore di lavoro
* [Gestione colore] Regola il selettore colore e l&#39;editor con lo spazio colore corrente
* [Gestione colore] Consente di selezionare lo spazio colore di trasformazione della visualizzazione nella finestra della vista con un nuovo menu a discesa
* [Gestione colore] Applicare la trasformazione della visualizzazione con i risultati del rendering dei raggi
* [Gestione colore] Esportare texture con diversi spazi colore
* [Gestione colore]&#x200B;[Python] Applicazione delle impostazioni di gestione del colore dalla variabile di ambiente (OCIO) ai nuovi progetti
* [Finestra vista] Consente di disancorare la finestra della vista 2D o 3D
* [Annullamento automatico] Nuova opzione per evitare isole allungate
* [Scripting Python] Chiama funzioni JavaScript dall’API Python
* [Finestra Nuovo progetto] Rende comprimibile la sezione delle mappe importate
* [Proiezione]&#x200B;[Altera] Consenti di nascondere le normali come opzione nelle impostazioni di Altera
* [Content] 11 nuove mappe grungi
* [Content] 8 nuovi strumenti predefiniti (cerniera, cavo di serraggio, scintillio)
* [Contenuto] 8 nuovi materiali (cicatrice, tasca, ...)
* [Contenuto] 1 nuovo generatore (gonfia shrinkwarp)

**Problemi noti:**

* [Mac M1] I materiali avanzati non vengono visualizzati correttamente
* [Gestione colore]&#x200B;[Arresto anomalo] Arresto anomalo casuale durante la riproduzione con tipo di dati/gestione colore sul canale utente
* [Gestione colore] Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* [Gestione colore]&#x200B;[Iray] Il salvataggio del rendering in EXR o TIFF durante l’attivazione della Gestione colore nella finestra della vista consente di salvare sempre in modalità lineare
* [Gestione colore] Le risorse utilizzate come scala di grigio nella maschera visualizzano il menu Spazio colore errato
* [Color Management]&#x200B;[Iray] La mappa Env è sempre lineare se utilizzata in Iray
* [Gestione colore]&#x200B;[Esporta] Le mappe convertite non vengono esportate come canali di gestione del colore
* [Gestione colore]&#x200B;[Esporta] L&#39;esportazione ignora se il canale utente è sottoposto alla gestione del colore o meno in modalità legacy

### 7.3.1

*(Rilasciato il 24 novembre 2021)*
Riepilogo: **Bugfix**

**Aggiunto:**

* [Proiezione] Il ridimensionamento deve funzionare solo nello spazio oggetto

**Corretto:**

* [Mac M1] La creazione di livelli di materiale non funziona
* [Mac M1]&#x200B;[Proiezione] L’alterazione non funziona
* I micro dettagli non vengono visualizzati correttamente
* [Proiezione]&#x200B;[Arresto anomalo] Passaggio alla modalità di alterazione con un livello creato con una versione precedente
* [Proiezione]&#x200B;[Altera] L’opzione Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
* [Proiezione]&#x200B;[Altera] L’opzione Dividi rimane selezionata al termine della divisione
* [Proiezione]&#x200B;[UV] Il punto pivot viene reimpostato quando si capovolge la proiezione
* [Filter] L’ambiente Bake Lighting cambia quando si ricarica o si modifica un parametro
* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
* [Interoperabilità] Il pulsante &quot;Sfoglia risorse 3D nel Marketplace&quot; dovrebbe sempre aprire CCD nella scheda 3D di Stock e Marketplace

**Problemi noti:**

* [Mac M1] I materiali avanzati non vengono visualizzati correttamente

### 7.3.0

*(Rilasciato il 13 ottobre 2021)*
Riepilogo: **Versione principale. Contiene una nuova proiezione di alterazione 3D, una nuova proiezione cilindrica, miglioramenti del selettore colore, nuove funzioni nell&#39;API Python e correzioni di bug**

**Aggiunto:**

* [Proiezione]&#x200B;[Altera] Esporre l’alterazione 3D come nuova modalità di proiezione
* [Proiezione]&#x200B;[Altera] Consente la modalità decalcomania per Alpha, texture e procedurali con trascinamento nella finestra della vista
* [Proiezione]&#x200B;[Altera] Usa proiezione alterazione con scelta rapida decalcomania (ALT)
* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Trasforma l’alterazione nel suo insieme o per vertici
* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Aggiungi punti della griglia con opzioni Dividi alterazione a croce, in orizzontale o verticale
* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Menu dedicato per le azioni di ripristino
* Opzione [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] per regolare automaticamente le tangenti quando si spostano i punti
* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Menu dedicato per l&#39;edizione della griglia (dimensioni, reimpostazione, colore e dimensione della maniglia)
* [Proiezione]&#x200B;[Altera] Nuova scelta rapida da tastiera per cambiare la modalità edizione alterazione vertici interi (MAIUSC+V)
* [Proiezione]&#x200B;[Altera] Con clic+Ctrl è possibile passare dallo strumento superficie ad altri strumenti
* [Proiezione]&#x200B;[Cilindrica] Esposizione della modalità di proiezione cilindrica
* [Proiezione]&#x200B;[Barra degli strumenti] Impostazioni manipolatore gruppo (dimensioni, passaggi griglia, passaggi angolo)
* [Selettore colore] Nuova interfaccia utente del selettore colore
* [Selettore colore] Usare i valori sRGB nei widget del selettore colore
* [Selettore colore] Consente di salvare ed eliminare i campioni di colore
* [Selettore colore] Contagocce accessibile da slot per colori e normali
* [Selettore colore] Consente di modificare il colore dinamico tra i valori 0 e 255
* [Selettore colore] Rendi lo stato HSV/RGB comune in tutta l’app
* [Selettore colore] La finestra del selettore colore è semi-persistente
* [Selettore colore] Premendo Esc si chiude la finestra del selettore colore
* Miglioramento delle prestazioni per l’interazione dell’interfaccia utente e durante la pittura
* [Engine] Aggiornamento alla nuova versione del motore di Substance (8.3.0)
* [Scripting]&#x200B;[Python] Consente di ricaricare la trama del progetto corrente
* [Scripting]&#x200B;[Python] Consente di aggiornare le risorse nei progetti
* [Scripting]&#x200B;[Python] Consenti di impostare ed eseguire query sulla risoluzione dei riquadri UV
* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
* [Interoperabilità] Ricezione di più risorse da Bridge

**Corretto:**

* Il selettore colore non visualizza il colore corretto
* [Baking] L&#39;elenco dei set di texture non è ordinato correttamente
* [Importazione FBX] Le trasformazioni pivot del gruppo 3ds Max non vengono considerate
* [Substance Engine] Arresto anomalo con importazione di SBSAR danneggiati
* [MacOS] L’opzione di configurazione del progetto in lingue diverse non è presente
* I salvati automaticamente possono bloccare Painter durante processi lunghi

**Problemi noti:**

* [Proiezione]&#x200B;[Altera] L’opzione Dividi rimane selezionata al termine della divisione
* [Proiezione]&#x200B;[Altera] L’opzione Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
* [Proiezione]&#x200B;[Altera] Linee di artefatto tra le patch in alcuni rari casi
* [Proiezione]&#x200B;[UV] Il punto pivot viene reimpostato quando si capovolge la proiezione
* [Mac M1] I materiali avanzati non vengono visualizzati correttamente
* [M1]&#x200B;[Regressione] Livelli di materiale non funzionanti

### 7.2.3

*(Rilasciato il 24 agosto 2021)*
Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

* [Librerie] Aggiungere un metodo per escludere dalla ricerca per indicizzazione i file indesiderati

**Corretto:**

* [Win] Schermi multipli e problemi di sospensione
* [MacOS]&#x200B;[Arresto anomalo] Cambio dello shader quando si utilizzano gli effetti
* [Riquadro di visualizzazione] La modalità di anteprima completa non mostra più il cursore del pennello senza canale alfa
* [UI] Il widget Angolo cambia direzione
* [Stack di livelli] Molte sottocartelle creano un blocco molto lungo
* [Iray] Viste diverse in Iray e OpenGL: visibile se non funziona
* [Iray] Indice di rifrazione non preso in considerazione e non visualizzato nelle proprietà mdl
* [JavaScript] ShowExportDialog() non restituisce mai true
* Impossibile leggere mtl da Adobe Stock

### 7.2.2

*(Rilasciato: 27 luglio 2021)*
Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

* Aggiornamento della versione dei requisiti del driver AMD

**Corretto:**

* [Mac M1] Rilevamento memoria errato
* [Esporta] I tracciati molto lunghi non vengono visualizzati correttamente

**Problemi noti:**

* [Content] Ombreggiature obsolete dei campioni

### 7.2.1

*(Rilasciato il 2 luglio 2021)*
Riepilogo: **Versione secondaria, aggiornamento rapido**

**Aggiunto:**

* [Interoperabilità] Aggiungi una descrizione per informare che l’invio di progetti per le porzioni UV a Stager non è ancora supportato
* [Plugin]&#x200B;[UI] Aggiornamento dell&#39;icona Livelink

**Corretto:**

* [Nvidia] La versione del driver che inizia con 30 è considerata obsoleta
* [Librerie] Lo stato del pannello Risorse non viene salvato a meno che un progetto non sia aperto
* [Librerie] La nuova ricerca salvata mantiene la parola chiave della vecchia ricerca salvata
* [Bakers]&#x200B;[UVTiles] Anche le mappe ID per meshID prendono in considerazione i riquadri UV
* [Esporta] I file gLTF non importano il colore dei vertici
* [Iray] Mancano alcune descrizioni comandi
* [Interoperabilità] L&#39;opzione Invia a Stager non è sempre disattivata quando non viene rilevato Stager
* [Resource Updater] Impossibile aggiornare il creatore di pennelli di Photoshop
* [Contenuto] Il generatore di usura dei bordi in fibra di vetro è rotto

### 7.2.0

*(Rilasciato il 23 giugno 2021)*
Riepilogo: **Versione principale, fornisce un aggiornamento del pannello delle risorse, un nuovo shader con accesso a nuovi canali e parametri, un aggiornamento complessivo dell’interfaccia utente, alcuni miglioramenti delle prestazioni molto richiesti, supporto linguistico esteso e altro ancora.**

**Aggiunto:**

* [Librerie] Nuovo pannello Risorse per sostituire lo scaffale
* [Libraries]&#x200B;[UI] Nuovo layout del pannello Risorse
* [Libraries]&#x200B;[UI] Modifica l&#39;orientamento e l&#39;interfaccia utente predefiniti del pannello Risorse
* [Libraries]&#x200B;[UI] Introduce un&#39;opzione di visualizzazione elenco alla libreria
* [Libraries]&#x200B;[UI] Nuovo percorso di navigazione nel pannello Risorse
* [Libraries]&#x200B;[UI] Seleziona &quot;Tutte le librerie&quot; quando selezioni una ricerca salvata
* [Libraries]&#x200B;[UI] Seleziona &quot;Tutte le librerie&quot; quando tutte le cartelle sono deselezionate
* [Libraries]&#x200B;[UI] Nuovo tag per i pennelli particelle
* [Libraries]&#x200B;[UI] Sostituito &quot;shelf&quot; da &quot;Tutte le librerie&quot; in tutta l&#39;app
* [Libraries]&#x200B;[UI] Consente di nascondere le cartelle vuote
* [Libraries]&#x200B;[UI] La libreria utente predefinita dovrebbe essere visibile anche se vuota
* [Libraries]&#x200B;[UI] Nuovo metodo di filtraggio tramite le icone del tipo di risorsa
* [Libraries] Scelta rapida &quot;CTRL&quot; per selezionare più tipi di risorse
* [Libraries] Nuova variabile di ambiente per controllare il budget della memoria di anteprima delle risorse
* [Libraries]&#x200B;[Content] Mappe del nuovo ambiente
* [Libraries]&#x200B;[Content]&#x200B;[UI] spostamento di rendering sui materiali predefiniti
* [Libraries]&#x200B;[Contenuto] Impostate lo shader Adobe Standard Material (ASM) come predefinito per la generazione delle anteprime
* [Libraries]&#x200B;[Content]&#x200B;[ASM] Nuovi modelli di progetto per il nuovo shader ASM
* [Libraries]&#x200B;[Thumbnail] Utilizza la nuova mappa dell&#39;ambiente Studio 6
* [Libraries]&#x200B;[Thumbnail] Leggi la miniatura nella risorsa invece di generarla
* [Libraries]&#x200B;[Thumbnail] Aggiungi spostamento alla generazione di miniature
* [Impostazioni set di texture]
* [Texture Set Settings]&#x200B;[UI] Esporta il nuovo height al metodo di conversione normale
* [Impostazioni set di texture]&#x200B;[UI] Rielaborazione dell&#39;organizzazione dell&#39;interfaccia utente dei canali
* [Impostazioni set texture] Limite canali utente aumentato a 16 canali
* [Texture Set Settings]&#x200B;[UI] Indica quali canali sono compatibili con lo shader attualmente selezionato
* [Shader]&#x200B;[ASM] Nuovo shader materiale standard Adobe
* [Shader]&#x200B;[ASM] Aggiunto il supporto per Anisotropia, Cancella rivestimento, Dispersione sottosuperficie, Specular edge color e Brillantezza
* [Shader]&#x200B;[ASM] Modifica i valori di colore dei canali predefiniti
* [Shader]&#x200B;[ASM]&#x200B;[Esporta] Modello di esportazione aggiornato da Adobe Dimension a Adobe Substance 3D Stager
* [Shader]&#x200B;[ASM] Etichette e descrizioni comandi aggiunte per i parametri shader e MDL
* [Shader]&#x200B;[ASM] Rendete visibile il colore della Dispersione nella vista 2D anche se SSS non è supportato
* [Shader]&#x200B;[ASM]&#x200B;[Iray] Supporta lo shader ASM in Iray con la nuova MDL
* [Shader]&#x200B;[ASM]&#x200B;[Iray] Scattering sottosuperficie aggiornato in lucido e patinato delle specifiche PBR legacy
* [Shader]&#x200B;[ASM]&#x200B;[Content] Ha modificato il tipo SSS predefinito per i campioni
* [Shader]&#x200B;[ASM] Documentazione aggiunta per l&#39;API ASM
* [Shader]&#x200B;[ASM] Ottimizzate gli shader per ignorare i canali non utilizzati
* [Shader] Esporre i nuovi canali del set di texture
* [Shader] Dispersione sottosuperficie migliorata
* [Shader] Nuovi parametri dello shader nascosti per alcuni shader
* [Shader] Visibile se per i parametri dello shader
* [Prestazioni]
* [Librerie] Anteprima risorse: miglioramenti a livello di tempo di caricamento e prestazioni di calcolo
* [Engine] Miglioramenti delle prestazioni di pittura
* [Annullamento automatico]
* [Annullamento automatico] Miglioramenti delle prestazioni di Impacchettamento
* [Rimozione automatica] Rimozione automatica dell’involucro compatibile con il flusso di lavoro Porzione UV
* [Auto-Unwrap] Nuova opzione per posizionare gli UV in base all&#39;orientamento della trama
* [Altro]
* [Impostazioni] Cambiata direzione zoom predefinita
* [UI] Aggiornamento complessivo dell’interfaccia utente
* [UI] Rielaborazione del menu Aiuto
* [UI] Sostituisci l&#39;icona Inverti
* [UI]&#x200B;[Plugin] Icona Sostituisci per il collegamento dcc del plug-in
* [UI]&#x200B;[AMD] Aggiorna la versione minima richiesta e il messaggio a comparsa
* [Serie di livelli] Crea un nuovo livello all’interno della cartella vuota selezionata
* Aggiornamento della documentazione Python
* Branding
* [Branding]&#x200B;[UI] Nome dell’applicazione aggiornato in Adobe Substance 3D Painter
* [Branding]&#x200B;[UI] Versione autonoma aggiornata a &quot;Substance edition&quot;
* [Branding]&#x200B;[UI] Nome eseguibile dell&#39;applicazione aggiornato, percorso di installazione, pacchetto e icone
* [Branding]&#x200B;[UI] Libreria e percorso predefiniti rinominati
* [Branding]&#x200B;[UI] Aggiornamento della finestra Informazioni su
* [Branding]&#x200B;[UI] Schermata introduttiva aggiornata
* [Branding]&#x200B;[UI] Rimosso il numero di versione basato sull&#39;anno
* [Localizzazione] Nuove traduzioni in tedesco, francese e cinese semplificato
* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
* [Interoperabilità] Interoperabilità con l&#39;ecosistema Adobe: Designer, Sampler, Stager e Bridge
* [Interoperabilità]&#x200B;[UI] Ricevi e aggiorna la risorsa da Designer
* [Interoperabilità]&#x200B;[UI] Ricevi risorsa da Sampler
* [Interoperabilità]&#x200B;[UI] Invia risorsa a Stager
* [Interoperabilità]&#x200B;[UI] Mostra in Adobe Bridge
* [Interoperabilità]&#x200B;[UI] Consente di accedere rapidamente alle risorse 3D di Adobe
* [Interoperabilità] Nuovi tag di utilizzo di sbsar
* [Interoperabilità] Gestire i tipi di risorse ricevute
* [Interoperabilità] Le risorse ricevute da Adobe Substance 3D Designer o Adobe Substance 3D Sampler vengono archiviate nella libreria predefinita scelta dall&#39;utente
* [Interoperabilità]&#x200B;[UI] Nuova icona nella barra degli strumenti a sinistra da inviare a Stager o Photoshop

**Corretto:**

* [Tablet] Prestazioni ridotte quando si esegue il disegno a pressione
* [Tablet] Problema con i tablet con controlli del cursore
* [Arresto anomalo] Mancata corrispondenza del nome tra l’elenco Set di texture e il modulo di esportazione
* [Arresto anomalo]&#x200B;[Librerie] Fai doppio clic su una libreria secondaria
* [Libraries] Problema durante la ricerca per indicizzazione delle directory della libreria
* [Libraries] La riga di comando Forza generazione anteprima non funziona come previsto
* [Libraries]&#x200B;[Contenuto] Il filtro Baked Light Environment è nero per impostazione predefinita
* [Linux]&#x200B;[MacOS]&#x200B;[Esporta mesh] Impossibile importare glTF creato su Linux/MacOS
* [Linux] Il trascinamento di un file nel pannello Risorse può causare un arresto anomalo
* [Auto-Unwrap] L’opzione Auto-Unwrap è disponibile anche se una trama non è stata selezionata per il ricaricamento
* [Particelle] Comportamento errato delle particelle con gravità
* [Serie di livelli] L’istogramma a livelli può utilizzare la luminanza solo con alcuni canali
* [Maschera geometria] Il menu di scelta rapida di una cartella quando si modifica la maschera di geometria non funziona
* [Proiezione] Cucitura con proiezione sferica e filtro bilineare
* [Riquadri UV] Esporta maschera solo in file esporta solo il riquadro 0, 0
* [Trama di esportazione] L&#39;esportazione della trama FBX è vuota
* [Iray] La mappa normale non viene considerata nei nuovi progetti durante il rendering
* [Salva] Salva problemi su unità condivise
* [Baking] Se si esegue il rebaking di una trama con parametri modificati, viene visualizzato un avviso
* [Baking]&#x200B;[Regressione] Risultato errato quando il rettangolo di selezione globale di High Poly Meshes non include l&#39;origine della scena
* [Python] Le librerie utente personalizzate non sono considerate

**Problemi noti:**

* [Librerie] Ricerche salvate non salvate se non è aperto alcun progetto
* [NVIDIA] Messaggio per driver obsoleto anche se aggiornato

### 7.1.1 (2021.1.1)

*(Rilasciato: 23 marzo 2021)*
Riepilogo: **Versione secondaria, correzione rapida con possibilità di immettere valori esadecimali nel selettore colore**

**Aggiunto:**

* [Log] Avvisa gli utenti in caso di driver GPU AMD incompatibili
* [Selettore colore] Consente di digitare valori esadecimali

**Corretto:**

* [Baker] Prestazioni ridotte
* [Maschera Geometria] Se si fa clic con il tasto Alt sul nome della trama, si può verificare un arresto anomalo
* [Engine] Il disegno non aggiorna l’intera vista quando necessario
* [Serie di livelli] La selezione si blocca dopo la modifica dello shader
* [MacOS]&#x200B;[Selettore colore] Il colore è leggermente diverso da quello selezionato
* [Esporta] L’uso del formato di file PSD non genera un file per porzione UV
* [Scripting]&#x200B;[Javascript] alg.mapexport.getPathsExportDocumentMaps() non restituisce tutti i valori
* [Scripting]&#x200B;[Python] I plug-in disabilitati vengono nuovamente abilitati alla riapertura di Painter

### 7.1.0 (2021.1.0)

*(Rilasciato: 28 gennaio 2021)*
Riepilogo: **Versione principale, nuova maschera di geometria che consente di selezionare e colorare parti della geometria, copiare/incollare effetti nella pila di livelli, miglioramento del flusso di lavoro delle porzioni UV, aggiornamento di Iray, forni, Substance Engine e nuovi contenuti**

**Aggiunto:**

* Nuova maschera di geometria e colorazione di parti selezionate della geometria
* [Maschera geometria] Consente di colorare parti selezionate della geometria in base ai nomi della trama
* [Maschera di geometria] Selezione rettangolare in entrambe le viste
* [Maschera geometria] Consente di nascondere/ignorare la geometria esclusa su qualsiasi livello
* [Maschera geometria]&#x200B;[Proprietà] Selezione rapida delle caselle di controllo con clic e trascinamento
* [Geometry Mask]&#x200B;[Proprietà]&#x200B;[UI] Includi/Escludi tutto con un menu a discesa nella finestra Proprietà
* [Maschera geometria]&#x200B;[Proprietà] Consente di selezionare rapidamente una voce in un elenco con ALT+CLIC SINISTRO
* [Maschera geometria]&#x200B;[Proprietà] Sovrapposizione nelle finestre delle viste quando si passa il cursore su Nomi trama/Porzioni UV nella finestra Proprietà
* [Geometry Mask]&#x200B;[Pila di livelli] Aggiunge le opzioni Copia/Incolla alla maschera di geometria
* [Maschera geometria] Icona Nuova per il pulsante Nascondi/Ignora geometria esclusa
* [Maschera geometria] Nuova descrizione comando per nascondere/ignorare la geometria esclusa
* [Maschera geometria] Scelta rapida da tastiera ALT+H per attivare/disattivare il pulsante &quot;Nascondi geometria esclusa&quot;
* [Porzioni UV]&#x200B;[Pila di livelli] Nuova miniatura di anteprima della sfera del livello di riempimento per le porzioni UV e la modalità semplificata
* [Porzioni UV]&#x200B;[Serie di livelli] Consente di uscire facilmente dalla maschera Porzioni UV
* [Riquadri UV]&#x200B;[Elenco set texture] Consente di fornire una descrizione per riquadro UV
* [Porzioni UV]&#x200B;[Impostazioni set texture]&#x200B;[UI] Due nuovi titoli di sezione nel menu a discesa per modificare la risoluzione delle porzioni UV
* [Riquadri UV]&#x200B;[Finestra vista] Esci dalla maschera per riquadri UV quando si trascina un materiale nella finestra della vista
* [Pila di livelli] Aggiungi opzioni di copia/incolla per gli effetti
* [Serie di livelli] Consente di copiare/incollare effetti da un set di texture a un altro
* [Serie di livelli] Consente la selezione multipla di effetti
* [Pila di livelli] Aggiungi opzioni di copia/incolla come scelte rapide per gli effetti di livello
* [Serie di livelli] Passa automaticamente tra maschera e contenuto quando trascini gli effetti su un altro livello
* [Pila di livelli] Crea automaticamente una maschera quando si incolla una maschera da un altro livello
* [Serie di livelli] Aggiungi azioni effetto di spostamento nel menu contestuale di scelta rapida degli effetti
* [Pila di livelli] Consente di trascinare gli effetti da un livello all’altro
* [Pila di livelli] Quando si trascinano degli elementi in una cartella, questi vengono inseriti sopra la cartella
* Aggiornamento di Iray alla versione 2020.1.0
* [Bakers] Aggiornate Bakers alla versione 2.5.4
* [Panettieri] Visualizzare le singole porzioni UV nella finestra di avanzamento della cottura
* [Bakers]&#x200B;[UI] Consenti di eseguire rapidamente il set di texture corrente con un nuovo pulsante
* [Panettieri] Consente all&#39;utente di selezionare rapidamente uno dei panettieri con ALT+CLIC SINISTRO
* Aggiorna Substance Engine alla versione 8.0.8
* [Substance Engine] Supporto del colore predefinito nei nuovi file .sbsar
* [Annullamento automatico] Miglioramento delle prestazioni
* [Esporta] Aggiungi un feedback visivo per indicare quale risoluzione delle porzioni UV differisce da quella predefinita del progetto
* [Esporta] Aggiungere il fattore dimensione scena nel file json shader esportato
* [Lingua] Aggiungi traduzione giapponese
* [UI] Finestra Aggiorna informazioni con controllo delle versioni delle dipendenze interne
* [Scripting]&#x200B;[Python] Consente di gestire le risorse degli scaffali
* [Scripting]&#x200B;[Python] Consenti di sapere quando un progetto è pronto per la cottura al forno e l’esportazione
* [Scripting]&#x200B;[Python] Consenti di sapere quando uno scaffale ha terminato la ricerca per indicizzazione delle risorse sul disco
* [Scripting]&#x200B;[Python] Consenti di eseguire query sull’elenco di porzioni UV per set di texture
* [Scripting]&#x200B;[Python] Consente di assegnare un’anteprima personalizzata alle risorse dello shelf
* [Scripting]&#x200B;[Python] Consenti di gestire scaffali personalizzati
* [Scripting]&#x200B;[Python] Aggiunge un indice di metodo in ogni sottomodulo della documentazione
* [Scripting]&#x200B;[Python] Nuovo stile per la documentazione
* [Scripting]&#x200B;[Python] Miglioramento delle risorse e della documentazione dello scaffale
* [Content] Tre nuovi strumenti predefiniti per creare punti
* [Shelf] Rimuovi temporaneamente &quot;Esporta in Substance share&quot; durante la transizione alla nuova piattaforma di Substance share

**Corretto:**

* Arresto anomalo quando si utilizzano monitor con risoluzioni diverse
* Arresto anomalo della Substance Engine con alcuni progetti rari
* L’aggiornamento della finestra della vista non riesce con Nascondi/Ignora geometria esclusa quando si cambia livello
* [Vista 2D] Il riquadro di visualizzazione 2D potrebbe non essere presente in alcuni progetti
* [Baking] L&#39;opzione &quot;Corrispondenza per nome trama&quot; ignora parti dell&#39;oggetto
* [Pila di livelli] Quando si fa clic su un effetto di livello, viene aperta la cartella
* [Maschera geometria] Il riquadro UV viene ancora conteggiato nella maschera anche quando si reimporta la trama senza di essa
* [Maschera geometria] Il menu di scelta rapida nella finestra della vista non fornisce gli strumenti corretti
* [Engine] Segnali di ritardo gravi su progetti specifici
* [Scripting] Latenza elevata con richieste JSON POST remote su Windows
* [Linux] La quantità di Vram non viene rilevata correttamente con specifiche GPU integrate
* [Annullamento automatico] Arresto anomalo o annullamento dell’operazione a lungo termine in alcuni progetti

## Versione 6

### 6.2.2 (2020.2.2)

*(Rilasciato il 28 settembre 2020)*
Riepilogo: **Versione secondaria, correzione rapida con alcune funzioni nell’API Python**

**Aggiunto:**

* [Prestazioni] Non calcolare tutte le porzioni UV quando si utilizza la selezione dell&#39;ID colore
* [Bakers]&#x200B;[UI] Visualizza le descrizioni dei set di texture
* [Panettieri] Consenti di salvare le impostazioni del forno
* [Panettieri] Aggiungi le opzioni Comprimi tutto/Espandi tutto alla scheda Selezione
* [Elenco set di texture] Nascondi descrizione se vuoto
* [Riquadri UV]&#x200B;[Elenco set texture] Se si fa clic su Riquadro UV, l&#39;elenco dovrebbe espandersi/comprimere
* [Esporta]&#x200B;[UI] Consente di ridimensionare il pannello Elenco set di texture in orizzontale
* [Esporta]&#x200B;[UI] Testo coerente della descrizione per il flusso di lavoro Texture Set e Tessere UV con texture non selezionate
* [Scripting]&#x200B;[Python] Consente di utilizzare i predefiniti di esportazione per esportare le texture
* [Scripting]&#x200B;[Python] Aggiungere un registro delle modifiche nella documentazione
* [Scripting]&#x200B;[Python] Consente di eseguire query su tutti i canali disponibili in un determinato stack
* [Scripting]&#x200B;[Python] Miglioramenti dell’interfaccia utente della console

**Corretto:**

* [AMD] Rilevamento non corretto della versione del driver obsoleta
* Arresto anomalo durante la reimportazione di una trama con layout UV Tiles diverso in alcuni casi
* Arresto anomalo quando si utilizzano particelle con UDIM su trame molto pesanti
* [Riquadri UV] Arresto anomalo durante l’esportazione di una trama con informazioni di spostamento in alcuni casi
* [Esportazione]&#x200B;[Arresto anomalo] L’esportazione di una vista 2D in formato psd può causare un arresto anomalo
* L’importazione di immagini come sequenze durante la creazione di un progetto non funziona
* Motore bloccato in un ciclo continuo
* [Scelta rapida] La fotocamera ruota sempre in modalità snap quando si modificano le scelte rapide della modalità snap
* Le trame vengono sempre annullate automaticamente quando vengono reimportate, anche se l’opzione è disattivata
* [Elenco set di texture] Il campo di testo Descrizione a volte non è completamente visibile durante l&#39;edizione
* Il menu a discesa [Elenco set di texture] per nascondere/mostrare i set di texture non è completamente visibile
* [Elenco set di texture] Facendo clic sull’icona occhio non si dovrebbe inserire il nome &quot;Modifica set di texture&quot;
* [Impostazioni set texture] La rimozione di un canale rimuove anche il canale sottostante
* [Esporta] Includi tutto e Reimposta tutto non prende in considerazione i riquadri UV
* [Panettieri] I panettieri deselezionati compaiono durante la cottura
* L’aggiornamento della risoluzione non viene considerato per le mappe con baking utilizzate come input
* [UV Tiles]&#x200B;[Viewport] Il viewport 3D si blocca quando si aggiunge materiale avanzato dopo la cartella con la maschera UV Tile selezionata
* [UV Tiles]&#x200B;[Viewport] Il Wireframe è ancora visibile per le porzioni nascoste con la modalità pittura passante
* [Esportazione]&#x200B;[Sketchfab] Problemi con il tipo di abbonamento &quot;più&quot;
* [Sketchfab] La casella di controllo &quot;Questa risorsa è privata&quot; non viene visualizzata dopo il cambio di account
* I predefiniti per i pennelli &quot;Deformazioni&quot; [Esporta]&#x200B;[Contenuto] possono causare problemi di prestazioni
* [Plugin Photoshop] Messaggio nel registro: non compatibile con il flusso di lavoro UV Tile
* [Scripting]&#x200B;[Python] L’opzione var PYTHONPATH impedisce l’avvio dell’applicazione
* [Scripting]&#x200B;[Python] Errore nella documentazione Python

### 6.2.1 (2020.2.1)

*(Rilasciato: 29 luglio 2020)*
Riepilogo: **Versione secondaria, aggiornamento rapido**

**Aggiunto:**

* Aggiungere la variabile di ambiente &quot;SUBSTANCE\_PAINTER\_VRAM\_BUDGET&quot; per ignorare la quantità di VRam della GPU
* [Riquadri UV]&#x200B;[Prestazioni] Non calcolare tutti i riquadri UV quando si utilizza lo strumento Riempimento poligonale

**Corretto:**

* [Iray] Il comando Salva rendering restituisce un errore e restituisce un’immagine nera
* [Linux] Arresto anomalo dopo la schermata iniziale su CentOS 7.3
* [Linux] La quantità di Vram non viene rilevata correttamente con configurazioni specifiche
* [Arresto anomalo] Apertura di un progetto con il nome di un set di texture duplicato
* [Engine] Problema di inconvalida della cache durante la modifica di una maschera
* [Elenco set di texture] Effetto di font errato quando il set di texture è disattivato

**Problemi noti:**

* [Elenco set di texture] Impossibile nascondere la descrizione
* Problemi dell&#39;interfaccia utente di [Texture Set List]
* [Iray] Il rendering di PSD non si apre
* [Plugin Photoshop] Non compatibile con il flusso di lavoro dei riquadri UV

### 6.2.0 (2020.2.0)

*(Rilasciato: 23 luglio 2020)*
Riepilogo: **Versione principale con il nuovo flusso di lavoro Porzioni UV, applicazione della pittura su porzioni UV e miglioramento delle prestazioni**

**Aggiunto:**

* Riquadri UV (UDIM)
* [Porzioni UV] Dipingi su porzioni UV
* [Riquadri UV] Consente di scegliere tra il flusso di lavoro nuovo e precedente per i riquadri UV
* [Riquadri UV] Importa sequenze di immagini UDIM/Riquadro UV come risorsa
* [Riquadri UV] Aggiungi elenco di riquadri UV per set di texture nella finestra Elenco set di texture
* [Porzioni UV] Consenti di modificare contemporaneamente la risoluzione di più porzioni UV nelle impostazioni del set di texture
* [Porzioni UV]&#x200B;[Vista 2D] Visualizza le porzioni UV come griglia
* [Riquadri UV]&#x200B;[Vista 2D] Pulsante Nuova finestra della vista per visualizzare o nascondere le informazioni sui riquadri UV
* [Porzioni UV] Per impostazione predefinita, imposta lo strumento di pittura su un singolo canale per i progetti con porzioni UV
* [Riquadri UV] Nuovo pulsante nella barra degli strumenti contestuale per ignorare i riquadri UV mascherati durante il disegno
* [Porzioni UV]&#x200B;[Serie di livelli] Icone nuove serie di livelli per migliorare le prestazioni
* [Riquadri UV]&#x200B;[Pila di livelli] Migliorare le icone di disegno e riempimento nella barra degli strumenti
* [Maschera porzione UV]&#x200B;[Vista 2D] Consente di includere o escludere più porzioni UV contemporaneamente (clic sinistro, CTRL+clic sinistro)
* [Maschera porzione UV] Nuova maschera porzione UV da includere, escludere porzioni per livello con una nuova icona
* [Maschera porzione UV]&#x200B;[Pila di livelli] Visualizza il numero di porzioni UV nell&#39;icona della maschera Porzioni UV quando non tutte sono incluse
* [Maschera porzione UV]&#x200B;[Vista 2D/3D] Aggiungi effetto al passaggio del mouse per visualizzare le porzioni UV sotto il cursore
* [Porzioni UV]&#x200B;[Pannelli] Consenti di selezionare e cuocere porzioni UV specifiche
* [Porzioni UV]&#x200B;[Pannelli] Aggiungete opzioni di selezione per set di texture/porzioni UV
* [Porzioni UV]&#x200B;[Pannelli] Opzione del menu di scelta rapida per selezionare Porzioni UV all&#39;interno di un set di texture
* [Porzioni UV]&#x200B;[Pannelli] Consente la selezione rapida in Set di texture/Porzioni UV trascinando
* [Porzioni UV]&#x200B;[Pannelli] Sostituite i pulsanti &quot;Tutto&quot; e &quot;Nessuno&quot; nelle mappe trama con opzioni di selezione più esplicite
* [Riquadri UV]&#x200B;[Pannelli] Visualizza il numero di texture da produrre
* [Porzioni UV]&#x200B;[Esporta] Consente di selezionare ed esportare porzioni UV specifiche
* [Porzioni UV]&#x200B;[Esporta] Consente la selezione rapida di porzioni UV mediante trascinamento
* [Porzioni UV]&#x200B;[Esporta] Aggiungi opzioni del menu a discesa per le porzioni UV
* [Riquadri UV]&#x200B;[Esporta] Rendi non disponibili alcuni predefiniti di esportazione se non funzionano con i riquadri UV (Adobe Dimension, Sketchfab, glTF, USD)
* [Porzioni UV]&#x200B;[Contenuto] Aggiornate i predefiniti di esportazione per utilizzare il nuovo tag $udim
* [Riquadri UV] Miglioramento della segnalazione degli errori durante l’importazione di trame con Isole UV sovrapposte
* [Riquadri UV] Riquadri UV compatibili in Iray
* [UV Tiles]&#x200B;[Scripting] Aggiungere la documentazione di esportazione delle porzioni UV al documento Python
* Prestazioni
* [Prestazioni] Nuovo pulsante nella barra degli strumenti contestuale per sospendere il calcolo del motore durante il lavoro (MAIUSC+ESC)
* [Prestazioni] Apertura più rapida del progetto ritardando il calcolo della cache del set di texture
* [Prestazioni] Non aspettare che le mappe mesh vengano caricate all’apertura del progetto
* [Prestazioni]&#x200B;[Vista 2D/3D] Non calcolare il canale maschera nella finestra della vista quando non viene utilizzato
* [Prestazioni] Non bloccare l&#39;applicazione durante il caricamento delle mappe mesh visualizzate nelle finestre delle viste
* [Prestazioni] Migliorare la velocità di salvataggio incrementale durante il salvataggio di un progetto
* [Prestazioni]&#x200B;[Panettieri] Modifica le impostazioni di dilatazione predefinite per migliorare il risparmio di tempo e dimensioni del progetto
* [Performance]&#x200B;[Panettieri] Passa alla scala di grigi su panettieri specifici per risparmiare tempo e dimensioni del progetto
* [Prestazioni]&#x200B;[Esporta] Migliora le prestazioni del motore per esportare le texture più velocemente
* [Prestazioni]&#x200B;[Esporta] Migliora la reattività quando si apre la finestra di dialogo di esportazione con molti set di texture
* [Prestazioni]&#x200B;[Esporta] Migliora le prestazioni quando si passa alla scheda &quot;Elenco esportazioni&quot;
* [Performance]&#x200B;[Iray] Ridurre il tempo di avvio di Iray
* Altro
* [Panettieri] Aggiungere opzioni di selezione per i set di texture
* Sposta la gestione dell’istanza dello shader nelle impostazioni del set di texture
* [Vista 2D/3D] Aggiungere un messaggio nella parte inferiore della finestra della vista per indicare il tipo di maschera modificato
* [Serie di livelli] Nuova opzione nelle impostazioni per passare dalla miniatura precedente a quella nuova
* [Serie di livelli] Aggiungi un feedback visivo per indicare lo stato di caricamento delle miniature
* [Proj] Nuova modalità di proiezione &quot;Riempimento (Corrispondenza per porzione UV)&quot; per caricare le sequenze di immagini
* [Proj] Modifica la modalità di proiezione dei livelli di riempimento su &quot;Riempi (come per porzione UV)&quot; in casi specifici
* [Contenuto] Ottimizzare i predefiniti per i pennelli Carboncino per migliorare le prestazioni
* Aggiornamento di Iray alla versione 2020.0.0
* [Esporta] Disattiva la scheda Elenco esportazioni se non è selezionato nulla
* Annulla contornamento automatico
* [Annullamento automatico] Migliora la percentuale di successo del processo di annullamento automatico del contornamento
* [Auto Unwrap] Parametrizzazione migliorata per aumentare la velocità e la stabilità

**Corretto:**

* [Alembic] Gli insiemi di facce vengono ignorati durante l&#39;importazione dei file
* [Alembic] Tempo di caricamento infinito con file specifici
* [Importa] Una sequenza di immagini UDIM errata viene importata quando differisce solo l’estensione del file
* [Arresto anomalo] Il tentativo di aprire il progetto bloccato da un altro processo causa un arresto anomalo
* [Proiezione] Artefatti sulla trama duplicata quando si utilizza la proiezione triplanare
* [Esporta] Il canale di espulsione non viene esportato con il formato USD
* [Content] Il materiale avanzato &quot;Carboncino&quot; contiene tratti pennello

**Problemi noti:**

* [Elenco set di texture] Impossibile nascondere la descrizione
* Problemi dell&#39;interfaccia utente di [Texture Set List]

### 6.1.3 (2020.1.3)

*(Rilasciato il 16 giugno 2020)*
Riepilogo: **Bugfix**

**Aggiunto:**

* [Esporta] Aggiungere le impostazioni di spostamento nel file json dei parametri Shader

**Corretto:**

* [Crash]&#x200B;[Engine] Arresto anomalo quando si tenta di cancellare e sostituire i canali esistenti
* [Arresto anomalo] Modifica dello shader dopo aver colorato una maschera in livelli di materiale
* [Crash]&#x200B;[Engine] Si arresta in modo anomalo con alcuni progetti pesanti
* [Bakers] La corrispondenza per nome non funziona con gli oggetti esportati da zBrush
* [Spostamento]&#x200B;[SVT] Le texture non vengono visualizzate all’apertura del progetto quando lo spostamento è attivo
* [Esporta] Alcune texture vengono esportate in grigio uniforme
* [Esporta] I set di texture disabilitati non devono essere esportati per i predefiniti di esportazione Dimension e Sketchfab
* [Scripting]&#x200B;[JavaScript] Arresto anomalo durante l’utilizzo dell’API JavaScript per accedere alla configurazione di esportazione nell’evento onProjectOpened
* [Scripting]&#x200B;[Javascript] onExportFinished() non viene chiamato dopo un&#39;esportazione

### 6.1.2 (2020.1.2)

*(Rilasciato il 28 maggio 2020)*
Riepilogo: **Aggiornamento di Bugfix con Substance Engine e Bakers**

**Aggiunto:**

* [Bakers] Esegui l’aggiornamento alla versione più recente
* [Panettieri] Nuovo metodo di campionamento in Occlusione ambiente, curvatura, panettieri Thickness
* Aggiornamento alla versione di Substance Engine più recente
* [Scripting]&#x200B;[Python] Consente la creazione di ResourceID per le risorse del progetto
* [Scripting]&#x200B;[Python] Consenti query sulle informazioni del canale
* [Scripting]&#x200B;[Python] Aggiungi le funzioni di esecuzione a secco e di richiamata per simulare l’esportazione di texture

**Corretto:**

* [Panettieri] Normali non corrette in World Space Normals panettiere utilizzando una mappa normale tangente in casi specifici
* [Bakers] Errore di baking Occlusione ambiente con Optix quando non si verifica un poly elevato
* [Tratti dinamici] Ritardo durante il caricamento di un set di texture specifico
* [Export] Non deve esportare i set di texture disabilitati per USD, glTF
* [Scripting]&#x200B;[JavaScript] Impossibile modificare le nuove impostazioni di Curvature Baker
* [Scripting]&#x200B;[JavaScript] alg.texturesets.addChannel() in alcuni casi non restituisce un errore
* [Scripting]&#x200B;[JavaScript] Errore di battitura nella documentazione delle API Javascript per setProjectExportOptions()
* [Scripting]&#x200B;[JavaScript] Esporta sempre tutti i set di texture
* [Scripting]&#x200B;[Python] l&#39;eseguibile sys.restituisce un percorso a python.exe anziché a Substance Painter
* Cache delle texture non compatibile tra i sistemi operativi Mac e Windows/Linux
* [Livelink UE4] Solo l&#39;ultimo materiale viene utilizzato per tutti i set di texture in una trama combinata

**Problemi noti:**

* [Export]&#x200B;[Dimension]&#x200B;[Skecthfab] Non deve esportare i set di texture disattivati
* [Arresto anomalo] Cambia lo shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.1 (2020.1.1)

*(Rilasciato il 5 maggio 2020)*
Riepilogo: **Hotfix**

**Aggiunto:**

* [Esporta] Feedback visivo sullo stato sostituito su TextureSet

**Corretto:**

* [Esporta] La dimensione della finestra del modulo di esportazione è troppo grande su un monitor con risoluzione speciale e non può essere ridimensionata
* Opzioni di esportazione non salvate dopo l’esportazione
* [Esporta] Arresto anomalo o impossibile esportare con il predefinito di esportazione &quot;dalla cache&quot;
* [Esportazione] L’annullamento dell’esportazione genera un’ulteriore mappa vuota imprevista
* [Esporta] Correggere le impostazioni predefinite di esportazione virtuale
* [Python] PYTHONPATH env var non è considerato
* [Python]&#x200B;[Export] Se si annulla l’esportazione tramite Python, viene restituito un errore di eccezione
* [Python]&#x200B;[Export] export\_project\_textures risultato errato con formato file psd
* [Bakers] Arresto anomalo di Linux con Raytracing GPU

**Problemi noti:**

* [JavaScript] Impossibile modificare le nuove impostazioni di Curvature Baker
* [JavaScript]&#x200B;[Esporta] Esporta sempre tutti i set di texture
* [Export]&#x200B;[USD] Non deve esportare i set di texture disattivati
* [Arresto anomalo] Cambia lo shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.0 (2020.1.0)

*(Rilasciato il 22 aprile 2020)*
Riepilogo: **Versione principale con esportazione di nuove texture e trame (con spostamento e tassellatura), apertura UV aggiornata con più controlli, nuovi forni, nuova API di scripting python, migliore esperienza utente per la proiezione di decalcomanie e nuovi contenuti**

**Aggiunto:**

* Nuovo modulo di esportazione texture e trama
* [Esporta] Nuova interfaccia di esportazione
* [Esportazione]&#x200B;[Scheda Esportazione] Consente di selezionare i canali di mappe da esportare per set di texture
* [Esporta]&#x200B;[Scheda Esporta] Consenti di modificare le dimensioni del set di texture per tutti i set di texture con un&#39;unica azione
* [Esportazione]&#x200B;[Scheda Esportazione] Consente un modello diverso per set di texture (tranne USD, glTF, Sketchfab e Dimension)
* [Esportazione]&#x200B;[Scheda Esportazione] Attivazione e disattivazione rapida di mappe e set di texture
* [Export]&#x200B;[Export tab] La risoluzione di esportazione 8192x8192 non è più sperimentale
* [Export]&#x200B;[Scheda Esportazione] Consente la modifica del formato del file e della profondità di bit per mappa
* [Esporta]&#x200B;[Scheda Esporta] Consente di ripristinare i valori dei parametri predefiniti
* [Esporta]&#x200B;[Scheda Esportazione] Consente di salvare le impostazioni senza esportare
* [Esporta]&#x200B;[scheda Modelli di output] Rinomina la scheda &quot;Configurazione&quot; in &quot;Modelli di output&quot;
* [Esporta]&#x200B;[scheda Modelli di output] Consenti la definizione del formato del file e della profondità di bit per mappa predefinita
* [Export]&#x200B;[Scheda Elenco esportazioni] Nuova scheda di anteprima per riepilogare e visualizzare il processo di esportazione
* [Importa/Esporta trama] Ottimizzazione delle prestazioni in termini di tempo di importazione/esportazione
* [Trama di esportazione] Trama di esportazione in FBX
* [Esporta trama] Esporta trama con spostamento e tassellatura
* [Esporta trama]&#x200B;[UI] Nuove impostazioni per il ricalcolo del vertice normale, applica la triangolazione
* [Esporta trama] Esporta la topologia di trama originale con i nuovi UV generati dallo srotolamento automatico
* Aggiornamento dello srotolamento UV automatico con più controlli
* [Srotolamento UV]&#x200B;[UI] Aggiungi impostazione per attivare lo srotolamento UV automatico nella nuova finestra del progetto
* [Srotolamento UV]&#x200B;[UI] Nuove opzioni per controllare i passaggi di srotolamento (cuciture, srotolamento, impacchettamento)
* [Srotolamento UV]&#x200B;[UI] Consente la conservazione delle giunture di srotolamento esistenti/srotolamento/impacchettamento
* [Srotolamento UV]&#x200B;[UI] Nuove opzioni per ricalcolare completamente i passaggi di srotolamento
* [Srotolamento UV]&#x200B;[UI] Nuova opzione per controllare le dimensioni del margine (nessuno, piccolo, medio e grande)
* Nuovi fornai
* [Pannelli] Sostituisci la vecchia curvatura con la nuova curvatura dalla trama
* [Panettieri] Aggiungi l&#39;opzione Corrispondenza per nome per ignorare il backface nel panettiere &quot;Occlusione ambientale&quot;
* [Panettieri] Aggiungi opzione piano terreno nel fornaio &quot;Occlusione ambiente&quot;
* Nuova API Python per scripting (3.7.6)
* [Python]&#x200B;[UI] Nuovo menu di script per Python
* [Python]&#x200B;[UI] Nuova documentazione Python nel menu Aiuto
* [Python] Esposizione dei moduli pitone delle Substance Painter: substance\_painter, alg, display, project.setting, project, texturesets, ui
* [Python] Esporre il nuovo modulo Python &quot;substance\_painter&quot;
* [Python] Esporre il nuovo sottomodulo Python: alg, display, log, project, resource, texturesets, ui
* [Python] Listener per modifiche al progetto
* [Python] Nuovi esempi nella documentazione Python
* Menu dei plug-in [JavaScript]&#x200B;[UI] sostituito da JavaScript
* [Finestra vista] Consente la creazione di una proiezione decalcomania &quot;trascinando/rilasciando + ALT&quot; una risorsa dallo scaffale
* Nuovo contenuto
* [Content] 5 nuovi materiali decalcomanie da Substance Source
* [Content] Aggiungi nuovi modelli di progetto ed esporta predefiniti per il modulo di rendering Maxwell
* [Content] Aggiungi modello di progetto per esportazione Keyshot 9
* [Content] Aggiorna il predefinito di esportazione Keyshot 9 per supportare lo spostamento e l&#39;emissione
* [Content]&#x200B;[Exporter] Aggiornamento di tutti i predefiniti di esportazione in base alle versioni più recenti dei motori grafici e dei moduli di rendering per giochi
* [Content]&#x200B;[Exporter] Aggiorna i file dei predefiniti di esportazione per utilizzare il nuovo formato e le nuove impostazioni di dithering
* [Content] Nuovi modelli e shader per supportare il materiale VRay (VRayMtl)
* [Serie di livelli] Consente l’eliminazione degli effetti di livello mediante l’icona del cestino o la scelta rapida da tastiera Elimina
* Rimuovere la Substance Source del plug-in (utilizzare il modulo di avvio con la funzionalità &quot;Invia a&quot;)
* [Windows] Non visualizzare l&#39;avviso TDR sulle GPU di fascia alta

**Corretto:**

* Problemi di traduzione nella finestra di dialogo Nuovo file di progetto
* [Bakers] L’impostazione &quot;Salva file di scena preelaborato&quot; non funziona più
* [Proiezione planare] La proiezione non funziona su trame con UV ripetuti
* [Decal] Differenza di comportamento nel canale normale quando si utilizzano diverse modalità di proiezione del livello di riempimento
* [Sfumino]&#x200B;[Clona] È possibile che si verifichi un artefatto quando si disegna in una maschera
* [Engine] Arresto anomalo con contenuti di livello specifici
* [Engine] Arresto anomalo casuale quando si disegna in alcuni casi
* [Punto di ancoraggio] Il riferimento a una maschera vuota restituisce sempre il bianco
* [Esporta] Livello non preso in considerazione in alcune particolari configurazioni dello stack
* [Trama di esportazione] Impossibile esportare con un percorso contenente caratteri speciali
* [Esporta mesh] Impossibile leggere i file glTF quando esportati da Linux o MacOS
* [Importa trama] La reimportazione di DAE, PLY o glTF non funziona come previsto

**Problemi noti:**

* [Scripting]&#x200B;[JavaScript] Impossibile modificare le nuove impostazioni di Curvature Baker
* [Bakers] Arresto anomalo di Linux con Raytracing GPU
* [Export]&#x200B;[USD] Non deve esportare i set di texture disattivati
* [Arresto anomalo] Cambia lo shader dopo aver dipinto una maschera in livelli di materiale

## Versione 5

### 5.3.3 (2019.3.3)

*(Rilasciato il 6 febbraio 2020)*
Riepilogo: **Correzione rapida con aggiornamento a Iray 2019.3**

**Aggiunto:**

* Aggiornamento a Iray 2019.3
* [Log] Indica bios obsoleto per la CPU Ryzen che causa l&#39;arresto anomalo durante la cottura
* [ABR] Estrarre ABR alfa allo scaffale

**Corretto:**

* [Baker] La cottura non riesce se la rete High-Poly non ha UV
* [Linux] Le scelte rapide personalizzate del mouse non vengono salvate
* [Pennello] Il contorno scompare con alcune forme alfa
* [Tablet] Rilevamento errato durante lo spostamento dei cursori
* [Shortcuts] Impossibile impostare qualsiasi scelta rapida con &quot;Ctrl+Alt+MouseClick&quot;
* [Shelf] Impossibile visualizzare la descrizione comando della risorsa quando si utilizza una tavoletta a penna
* [Vista 2D]&#x200B;[Esporta] Il predefinito Vista 2D non tiene conto delle informazioni normali
* Si verifica un blocco con quando si disegna in allineamento UV con determinati pennelli
* Colorare sotto un filtro crea un artefatto sul tratto in corso
* [Finestra vista] Cache delle texture errata nella finestra della vista dopo la reimportazione di una trama
* [Arresto anomalo] Errore durante il salvataggio dopo l’esportazione in Photoshop
* [Arresto anomalo] Scrittura di simboli speciali nel prefisso durante l’importazione delle risorse
* [Arresto anomalo] Fai clic sul riferimento in Proprietà punto di ancoraggio
* [Punti di ancoraggio] Il canale non si aggiorna quando è presente un filtro tra il punto di ancoraggio e il riferimento
* Il collegamento dell’URL del raggio nel menu Aiuto non funziona

**Problemi noti:**

* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV

### 5.3.2 (2019.3.2)

*(Rilasciato: 21 gennaio 2020)*
Riepilogo: **Bugfix**

**Corretto:**

* L’apertura di un progetto che è stato salvato in modalità solo canale non visualizza la trama
* Il riquadro di visualizzazione non viene sempre aggiornato quando si disegna sotto il livello utilizzando lo strumento Clona

**Problemi noti:**

* [Baker] Arresto anomalo relativo al multithreading su CPU Ryzen
* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV

### 5.3.1 (2019.3.1)

*(Rilasciato: 20 dicembre 2019)*
Riepilogo: **Hotfix**

**Corretto:**

* Arresto anomalo quando si lavora su trame con Proiezioni UV specifiche
* [ABR] Arresto anomalo quando si passa da un predefinito Photoshop a un altro
* [Linux] Impossibile avviare Substance Painter su CentOS 7.4 a causa di un problema di dipendenza libGLX
* [Bakers] Arresto anomalo durante la cottura al forno dopo aver utilizzato File > Pulisci
* [Bakers] La finestra di dialogo di avanzamento della cottura si blocca dopo l&#39;annullamento
* [fornai] La mesh di cottura al forno dopo l’esportazione delle texture non funziona
* [Panettieri] Utilizzo dei risultati &quot;Corrispondenza per nome&quot; con mappe trama nere
* [Panettieri] Gabbia non presa in considerazione
* [Shelf] L’importazione di file PSD genera immagini danneggiate
* [Sample] Il progetto di esempio &quot;Mat&quot; ha videocamere danneggiate e un predefinito di esportazione errato

**Problemi noti:**

* [Baker] Arresto anomalo relativo al multithreading su CPU Ryzen
* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV

### 5.3.0 (2019.3.0)

*(Rilasciato: 17 dicembre 2019)*
Riepilogo: **Versione principale con miglioramento dell’esperienza utente di pittura a mano, utilizzo dei tablet, srotolamento automatico degli UV nella versione beta (0.3.0) e diversi nuovi contenuti per la pittura a mano**

**Aggiunto:**

* Integrazione dello srotolamento UV automatico della versione 0.3.0 in Substance Painter
* [Srotolamento UV] Srotolamento UV automatico nella Substance Painter quando non sono presenti UV o UV parziali
* [Srotolamento UV] Un&#39;impostazione globale per attivarla e disattivarla
* [Annullamento del wrapping UV] Versione riportata nel file di log
* [Annullamento UV]&#x200B;[UI] Indica l&#39;avanzamento dello srotolamento UV
* [UI] Nuove impostazioni nella barra degli strumenti contestuale per selezionare l&#39;anteprima del pennello: anteprima completa, contorno del pennello e mirino
* [Tool] Nuovo metodo di fusione avanzato nella sezione alfa: Schiarisci (Massimo) oltre a Normale
* [Serie di livelli] Opzione di correzione gamma per livello per canale alfa o maschera (menu di scelta rapida)
* [Layer Stack]&#x200B;[UI] Aggiungi icona &quot;i&quot; quando un livello alfa è corretto dal gamma
* [Tablet]&#x200B;[Strumento] Esporre la pressione minima per le dimensioni e il flusso
* [Tablet]&#x200B;[UI] Nuova impostazione nella barra degli strumenti contestuale per selezionare la pressione della curva: lineare, intuitivo, intuitivo
* [Tablet]&#x200B;[UX] Aggiungi Ctrl+Alt+clic per scorrere
* Importare pennelli predefiniti di Photoshop (formato ABR)
* [ABR] Supporta i parametri Shape
* [ABR] Supporta i parametri della dinamica delle forme
* [ABR] Parametri di trasferimento del supporto
* [ABR] Supporta i parametri di dispersione
* [ABR]&#x200B;[Tratti dinamici] Supporta rotondità e capovolgimento
* [ABR]&#x200B;[Shelf] Esporre la struttura di cartelle dei pennelli nell&#39;Editor filtri
* [ABR]&#x200B;[Ripiano] Aggiungere l’icona di Photoshop nelle miniature
* [ABR]&#x200B;[Shelf] Aggiungi un elenco di parametri non supportati nella miniatura dettagliata ABR
* [Strumento]&#x200B;[Tratti dinamici] Nuova impostazione del tratto dinamico per controllare il numero di inizializzazione casuale da generare
* [Tool]&#x200B;[UI] Aggiungi nuove impostazioni di distribuzione e asse per la variazione di dispersione
* [Scelta rapida] Aggiungi Ctrl+Maiusc+B per aprire la finestra Baking
* [UI]&#x200B;[Menu] Aggiungi voce nel menu &quot;Modifica&quot; per aprire la finestra Baking
* [UI]&#x200B;[Impostazioni] Miglioramento dell’allineamento dell’elenco delle scelte rapide
* [UI] Sostituire le icone dei controlli pressione (dimensioni e flusso) con i pulsanti di attivazione/disattivazione
* [Riquadro di visualizzazione] Consente di mettere a fuoco separatamente il riquadro di visualizzazione 2D e 3D
* Aggiornamento a QT 5.12.5
* [UI] Indica l&#39;avanzamento del caricamento della trama
* [Substance] Aggiungi il supporto per l&#39;intervallo non bloccato e morbido con i cursori
* [Substance] Aumenta la precisione dei parametri della Substance fino a 6 decimali
* [Substance] Tenere conto della fase definita da un parametro
* [Substance] Ottimizzazione della generazione di tratti dinamici con supporto delle condizioni nei dati utente
* [Substance] Consenti di designare un output del grafico come maschera per tutti i canali tramite dati utente
* [Content] Aggiorna il progetto di esempio &quot;Mat&quot; con topologia descrittiva per lo spostamento, nuova mappa ID e nuove fotocamere
* [Content] Integrare 3 nuovi filtri (MatFx): fumetto, acquerello, Dipinto a olio (ispirato al lavoro di Emrecan Cubukcu)
* [Contenuto] Integra 102 pennelli predefiniti di Photoshop dai pacchetti di Kyle T. Webster
* [Content] Integrate 18 nuovi predefiniti per i pennelli: Freccia del rullo di pittura, Testo di avvertenza del rullo di pittura, Carboncino fine e altri ancora
* [Contenuto] Integrazione di 9 nuove alfa: rullo di pittura del creatore di pennelli, Photoshop del creatore di pennelli, pattern di pennelli e altro ancora
* [Content] Integrate 2 nuovi strumenti predefiniti: Gouache Dense e Gouache Faded
* [Content] Integra 1 nuovo generatore : Controllo UV (Isole UV di evidenziazione e cuciture)
* [Content] Integra 2 nuovo predefinito di esportazione: Keyshot 9+ e Spark AR Studio
* [Content] Integra 1 nuovo modello di progetto : Spark AR Studio (Facebook)

**Corretto:**

* [Tablet] L&#39;annullamento dei tratti dello stilo (CTRL+Z) è più lento dell&#39;annullamento dei tratti del mouse
* [Tablet] Pressione iniziale e finale non considerate quando si disegna una linea retta
* [Tablet] Il primo timbro viene disegnato due volte quando si utilizza una linea retta
* [Tablet] Supporto migliorato per le scelte rapide da tastiera per Huion
* [Tablet] Supporto migliorato per i pulsanti penna Huion
* [Tablet] Scostamento tra l&#39;anteprima del pennello e il timbro disegnato
* [Tablet] In rari casi, le scelte rapide per modificare i pennelli a penna comportano prestazioni ridotte
* [Tablet] Ritardo quando si disegna su un livello specifico
* In rari casi, quando si cambia finestra, possono verificarsi texture sfocate
* [UI]&#x200B;[Substance] Gli input dell’immagine non vengono sempre visualizzati
* L’opzione Pulisci non rimuove dal ripiano i predefiniti importati in un progetto
* [Strumento]&#x200B;[Tratto dinamico] Problema di prestazioni durante l&#39;ottimizzazione del conteggio dei cicli del timbro
* In rari casi, problemi di aggiornamento durante l’uso della modalità finestra vista 3D/2D
* Colorare un tratto molto lungo può portare a un blocco
* [Tool] Problema di prestazioni quando si disegna con tratti dinamici specifici
* [UI] Nella barra degli strumenti contestuale vengono ancora visualizzate le proprietà del pennello durante la selezione di una cartella
* I valori dell&#39;asse di simmetria non vengono reimpostati
* L’importazione di texture EXR con valori a virgola mobile è completamente nera
* Alt + clic su un canale per isolare non funziona per filtro e generatore
* [Esporta] Il progetto specifico si arresta in modo anomalo durante l’esportazione
* [Substance] Valore predefinito errato nel menu a discesa se il parametro è nascosto da Visible If
* [Shader] I canali definiti tramite la creazione di livelli di materiale non sono ordinati allo stesso modo nell’interfaccia utente
* [Shelf] I metadati dei predefiniti non vengono salvati sul disco

**Problemi noti:**

* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV
* L’esempio di riunione presenta alcuni problemi con le videocamere importate

### 5.2.3 (2019.2.3)

*(Rilasciato il 23 ottobre 2019)*
Riepilogo: **Versione Bugfix**

**Aggiunto:**

* Pulsante Aggiungi [Texture Set List] per attivare/disattivare rapidamente la modalità di attivazione
* [Log] Aggiungere il numero di versione di Windows 10 nel file di log
* Aggiornamento alla versione più recente di Substance Engine
* [MacOS] Ha autenticato il software per soddisfare i nuovi requisiti di distribuzione di MacOS Catalina

**Corretto:**

* [Plugin] L&#39;origine del plug-in non funziona
* [MacOS]&#x200B;[Shader] Mac OS 10.14.5 e AMD: la creazione di livelli di materiale non funziona come previsto

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Rari arresti anomali durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde durante la cottura in forno con DXR su GPU Pascal

### 5.2.2 (2019.2.2)

*(Rilasciato il 20 settembre 2019)*
Riepilogo: **Versione Bugfix**

**Corretto:**

* L’importazione di risorse tramite script può causare un arresto anomalo
* [Plugin] Il download di materiale dall’origine può causare un arresto anomalo

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Rari arresti anomali durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde durante la cottura in forno con DXR su GPU Pascal

### 5.2.1 (2019.2.1)

*(Rilasciato: 17 settembre 2019)*
Riepilogo: **Versione Bugfix**

**Corretto:**

* [Mac]&#x200B;[USD] Impossibile aprire i file USDZ esportati da MacOS
* [Set di texture] Impossibile isolare un set di texture con il modificatore ALT
* [Shelf] I predefiniti, i materiali avanzati e le maschere intelligenti vengono sempre modificati quando si esce dall’applicazione
* [Serie di livelli] Impossibile selezionare l’effetto dopo aver eliminato un altro effetto
* Sfarfallio quando si utilizza un cursore all’interno del pannello delle proprietà dello strumento
* Arresto anomalo durante l’esportazione dei predefiniti nello scaffale
* Arresto anomalo durante l’esportazione di un predefinito con spazio insufficiente
* Arresto anomalo durante la creazione di un predefinito con spazio insufficiente

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Rari arresti anomali durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde durante la cottura in forno con DXR su GPU Pascal

### 5.2.0 (2019.2.0)

*(Rilasciato: 25 luglio 2019)*
Riepilogo: **Versione principale con aggiornamenti dei forni in termini di prestazioni e una nuova modalità di previsualizzazione + nuovi contenuti**

**Aggiunto:**

* [Bakers] Aggiunto il supporto per Raytracing GPU con DXR e OptiX (Occlusione ambientale, Thickness)
* [Baker] Ottimizzazioni e accelerazioni per il Raytracing della CPU
* [Bakers]&#x200B;[Vis mode]&#x200B;[UI] Nuova modalità di visualizzazione baking nella finestra della vista
* [Bakers]&#x200B;[Preferenze]&#x200B;[UI] Nuova opzione baking per abilitare-disabilitare Raytracing GPU
* [Pannelli]&#x200B;[UI] Rielaborazione della finestra di dialogo barra di avanzamento
* [Bakers] Miglioramento dei messaggi di avviso e di errore
* [Panettieri] Consenti una cancellazione più reattiva del processo di cottura al forno
* [Bakers] Riapri la finestra del bake dopo aver fatto clic su Annulla
* [Proj]&#x200B;[UX] Miglioramento dell&#39;usabilità del manipolatore di rotazione
* [Settings] Opzione per migliorare le prestazioni riducendo la risoluzione del viewport per schermi HDPI
* [Scripting] Modificare la risoluzione del set di texture
* [Scripting] Ottieni set di texture selezionato
* [Scripting] Consente di selezionare un set di texture
* [Scripting] Funzione per sapere quando la selezione del set di texture è stata modificata
* [Shelf] Aggiunti 40 nuovi materiali intelligenti
* [Shelf] Aggiunte 20 nuove maschere avanzate

**Corretto:**

* [Serie di livelli] Blocco dell’interfaccia utente durante la selezione multipla dei livelli
* [Serie di livelli] Il raggruppamento di numerosi livelli blocca l’interfaccia utente per un tempo più lungo del solito
* [Pila di livelli] In alcuni casi è possibile selezionare contemporaneamente un livello e un effetto
* I grafici delle Substance utilizzati negli strumenti di pittura non vengono generati alla risoluzione giusta
* [Baker] Il pulsante &quot;Crea in forno tutti i set di texture&quot; non è disattivato quando non è selezionato alcun panettiere
* [MacOS] Disattiva il messaggio di avviso sulla tassellatura
* Lo strumento Proiezione non ha un’anteprima quando viene utilizzato con una maschera
* Arresto anomalo e danneggiamento dei progetti durante il tentativo di salvataggio con spazio su disco insufficiente
* [Shelf] Arresto anomalo durante l&#39;importazione di una risorsa su disco tramite shelf con spazio insufficiente
* [Shelf] Arresto anomalo durante il ripristino del predefinito di sessione
* [Shelf] L’importazione di un predefinito con un nome che termina con uno spazio causa un arresto anomalo
* [Shelf] L&#39;importazione di una risorsa con un prefisso che termina con uno spazio vuoto provoca un arresto anomalo

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Rari arresti anomali durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde durante la cottura in forno con DXR su GPU Pascal

### 5.1.3 (2019.1.3)

*(Rilasciato: 1 luglio 2019)*
Riepilogo: **Correzione rapida con 2 nuove funzioni**

**Aggiunto:**

* Consente di specificare il budget VRam con una riga di comando (ad esempio: budget vram 4096)
* [QML] Esporre le proprietà wrapMode ed elide dei pulsanti e delle caselle di controllo QML

**Corretto:**

* &quot;Segui tracciato&quot; non funziona sempre
* La mappatura dei canali non funziona con SBSAR utilizzato negli slot a canale singolo
* [Serie di livelli] Prestazioni ridotte durante lo scorrimento con livelli nascosti
* Arresto anomalo di [TextureSet] quando si fa clic tra le maschere
* Lo Spostamento [SVT] non viene visualizzato correttamente e in alcuni casi sfarfalla
* [Alembic] Arresto anomalo con trama che utilizza le normali dei punti invece delle normali dei vertici
* [Alembic]&#x200B;[Log] Segnala un errore nel log se il file Alembic non è supportato durante l&#39;importazione

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Rari arresti anomali durante l’importazione di alcuni file Alembic

### 5.1.2 (2019.1.2)

*(Rilasciato il 21 maggio 2019)*
Riepilogo: **Hotfix**

**Corretto:**

* Arresto anomalo quando si selezionano due risorse con un input di immagine

### 5.1.1 (2019.1.1)

*(Rilasciato il 20 maggio 2019)*
Riepilogo: **Hotfix**

**Aggiunto:**

* Aggiornamento alla versione più recente di Substance Engine con l’ultima versione di Substance Designer 2019.1

**Corretto:**

* [Substance] Visibile se non viene preso in considerazione per le immagini di input
* [SVT]&#x200B;[Engine] La modifica della risoluzione del set di texture in alcuni casi causa un arresto anomalo
* [Engine] In alcuni casi vengono visualizzate texture di nero casuale
* [Serie di livelli]&#x200B;[UI] Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente
* [Serie di livelli] L’opacità non ha effetto sull’effetto Disegno con metodo di fusione Attraversa
* [Serie di livelli] L’input del filtro Da Height a normale non si aggiorna correttamente con il tratto del pennello gomma
* [LayersStack] Arresto anomalo quando si annulla la rilascio di una maschera avanzata
* Sfarfallio del wireframe con ombre e anti-alias temporale attivati
* [Spostamento] Ritardo su AMD con alcune trame pesanti
* [Windows] Arresto anomalo all&#39;apertura di alcuni progetti tramite Esplora file
* [Istogramma] Arresto anomalo durante la rimozione di una maschera con punto di ancoraggio in alcuni casi
* Arresto anomalo nella generazione dell’anteprima in alcuni rari casi
* [Arresto anomalo] Impossibile riaprire un progetto con troppi strumenti di clonazione e sfumino
* Nessuna trama visualizzata in modalità materiale dopo il salvataggio in alcuni casi
* [Scripting] alg.mapexport.documentStructure() restituisce valori errati per le cartelle

**Problemi noti:**

* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione

### 5.1.0 (2019.1.0)

*(Rilasciato il 23 aprile 2019)*
Riepilogo: **Traccia dinamica con nuovi contenuti dedicati, Spostamento e tassellatura in tempo reale e irraggiamento, effetto maschera di confronto, simmetria radiale, planare e Proiezione sferica**

**Aggiunto:**

* [Strumento] Tratto dinamico: Substance la variazione lungo il tratto di un pennello
* [Tratto dinamico] Esposizione del nuovo parametro indice del timbro con le opzioni
* [Tratto dinamico] Tieni conto del parametro $time
* [Tratto dinamico] Genera un nuovo parametro $randomseed per tratto e per timbro
* [Tratto dinamico] Avvia un indice di tratto dinamico da un numero casuale
* [Tratto dinamico]&#x200B;[Scaffale] Aiuta a trovare una risorsa tratto dinamico con una nuova icona dedicata
* Spostamento e tassellatura nella finestra della vista in tempo reale
* Spostamento e tassellatura in Iray
* [Impostazioni shader]&#x200B;[UI] Nuova scheda per il controllo dello spostamento e della tassellatura
* [Serie di livelli] Nuovo effetto Confronta maschera: genera una maschera confrontando due canali
* [Stack di livelli]&#x200B;[UI] Nuova voce nel menu di scelta rapida &quot;Aggiungi maschera con combinazione di height&quot; per inserire un effetto CompareMask
* [Simmetria] Nuova modalità simmetria: pittura radiale
* [Impostazioni simmetria] Espandere entrambe le sezioni &quot;Impostazioni&quot; e &quot;Visualizzazione&quot;
* [Impostazioni simmetria]&#x200B;[UI] Anteprima per pittura radiale
* Esporre due nuove modalità di proiezione: piana e sferica
* [Proj] Nuova modalità di ritaglio forma per tutte le proiezioni
* [Proj] Modalità Planare con nuovo manipolatore: strumento Superficie
* [Proj]&#x200B;[Scelta rapida] Scelta rapida MAIUSC+W per lo strumento Superficie
* [Proj] Maschera di proiezione planare con taglio a sfoltimento profondità e sfondo
* [Manipolatore] Miglioramento del manipolatore di rotazione su tutti e tre gli assi per triplanare
* [Tool]&#x200B;[UX] Se si fa clic su un canale tenendo premuto il tasto Alt, tale canale viene attivato o disattivato
* [Engine] Aggiornamento alla versione più recente di Substance Engine
* [Set di texture] Selezione multipla e modifica della risoluzione
* [Set di texture] Attivazione e disattivazione rapida dei set di texture
* [Set di texture] Combina solo e tutte le opzioni in un nuovo menu
* [Set di texture]&#x200B;[Layer stack] Icona Nuova per attivazione e disattivazione
* [Layer stack]&#x200B;[UX] Inserisci effetti sopra quelli già selezionati
* [Serie di livelli]&#x200B;[UI] Rielaborare lo stile di selezione della visualizzazione della serie di livelli
* [Serie di livelli] Per impostazione predefinita, il metodo di fusione per i livelli istanziati è ora impostato sul metodo Attraversa
* Opzione [Esporta] per attivare e disattivare il dithering
* [Plugin] Supporta il modificatore di precisione per i cursori (SHIFT)
* [Plugin]&#x200B;[UI] Nuova icona per il salvataggio automatico
* [Scripting] Elenca il contenuto di una cartella
* [Scripting] Consente l’eliminazione dei file
* [Scripting] Leggi tutte le informazioni sullo stack, incluse le risorse utilizzate
* [Contenuto]&#x200B;[Tratto dinamico] Nuovi strumenti e pennelli predefiniti
* [Contenuto]&#x200B;[Tratto dinamico] Due nuove sfumature procedurali: Tonalità sfumatura e Generatore sfumatura
* [Contenuto] 11 nuovi filtri: MatFx Peeling Paint, MatFx Water Drops e altro ancora
* [Content] 7 nuovi generatori: Cucitrice automatica, Colore casuale UV, Densità texel UV e altro ancora
* [Contenuto] 93 nuove alfa: nuovi testi, frecce e varie altre forme
* [Content] 2 nuove procedure: Tonalità sfumatura, Generatore sfumatura e altro ancora
* [Contenuto] 21 nuovi strumenti e pennelli predefiniti per Tratti dinamici : Ciottoli, Impronte, Spruzzo e altro ancora
* [Content] 2 Nuove HDR: terreno di Canopus e foresta autunnale
* [Content] Aggiorna il contenuto con la cura del seme casuale nello scaffale
* [Content] Nuova icona con parametro di inizializzazione casuale esposto nello scaffale

**Corretto:**

* [Pila livelli] La pila di livelli continua a trascinare per sempre
* [Mac] &quot;Mostra nel Finder&quot; può portare al blocco
* [Scripting] Le impostazioni salvate tramite l’interfaccia utente personalizzata vengono perse se il file dello shader viene spostato
* [Scripting] Il numero di versione dell’API non è corretto e non aggiornato
* [Effetto] Il contenuto dell’istogramma non viene visualizzato correttamente
* [Effetto] In alcuni casi l’effetto Istogramma non si aggiorna
* [Ripiano] I punti non sono allineati correttamente sul materiale &quot;Plastic Fabric Pyramid&quot;

**Problemi noti:**

* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione
* [Serie di livelli]&#x200B;[UI] Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente

## Versione 4

### 4.3.3 (2018.3.3)

*(Rilasciato il 7 marzo 2019)*
Riepilogo: **bugfix**

**Aggiunto:**

* [Content] Integrazione del nuovo modello di progetto: &quot;PBR - fusione Alpha rugosità metallica&quot;
* L&#39;ordine di ricerca delle librerie dinamiche Linux è stato modificato per assegnare priorità alle librerie nella directory di installazione prima di ciò che è installato sul sistema

**Corretto:**

* La trama a volte scompare dalla finestra della vista 3D (premete F per reimpostare la videocamera)
* Aggiornate Substance Painter caricatore Sketchfab con i nuovi tipi di licenza Sketchfab
* [Import]&#x200B;[glTF] Gestione errata della modulazione della texture di input come definita nei file glTF
* [Import]&#x200B;[glTF] In alcuni casi il piano terreno viene visualizzato in modo errato con l&#39;importazione glTF
* [Esporta]&#x200B;[USD] L’opacità non funziona in Arkit
* [Export]&lbrack;USDz export si blocca in alcuni casi
* [Export]&#x200B;[USD] L’esportazione in USD senza salvare causa l’arresto anomalo
* [Esporta]&#x200B;[USD] Modalità di suddivisione errata per le texture, modalità di suddivisione per trame e tipi di output per gli ombreggiatori
* [Esporta]&#x200B;[USD] Esportazioni sparse solo di alcuni set di texture con tutta la geometria
* [Istanza] Arresto anomalo quando si tenta di eliminare un livello di istanza interrotto
* [Regressione]&#x200B;[Esporta] Alcune mappe non vengono esportate nella profondità di bit scelta
* [Linux] Problema con la libreria libtbb.so.2

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.2 (2018.3.2)

*(Rilasciato il 24 gennaio 2019)*
Riepilogo: **Correzione rapida con nuove funzioni (esportazione USDZ e filtro Texture nella finestra della vista)**

**Aggiunto:**

* [Esporta] Consente l’esportazione in USDZ
* [Finestra vista] Consenti di controllare la qualità della texture in Impostazioni schermo
* [Finestra vista] È stata aggiunta l&#39;impostazione di polarizzazione mip in Impostazioni schermo
* [Finestra vista] È stato aggiunto il filtro anisotropo in Impostazioni schermo
* [plug-in] Aggiorna i plug-in ufficiali per utilizzare lo stile di Substance Painter 2018
* [Licenza] Per impostazione predefinita, installa la licenza in una cartella utente

**Corretto:**

* Arresto anomalo collegato alla decompressione
* Aggiungi TAA sul materiale da solo
* Disturbo con ombreggiatura, prova di sensibilità TAA e alfa con dithering
* Rimuovere il dithering specular per tutti gli shader PBR classici
* In alcuni casi, arresto anomalo nelle impostazioni dello shader
* L’attivazione della dispersione non è sincronizzata tra i rendering OpenGL e Iray
* Gli strumenti Sfumino e Clona non funzionano più su trame specifiche
* Alcuni set di texture non possono essere visualizzati nel rendering dei raggi
* I set di texture rinominati non vengono salvati dopo la chiusura del progetto
* Wireframe gli artefatti durante il trascinamento dei materiali sulle mappe ID
* [Scripting] Creazione del percorso del file non forzata durante il salvataggio di un progetto
* [Scripting] Il callback &quot;onProjectAboutToSave()&quot; non funziona più
* Collegamenti al forum interrotti nella finestra di segnalazione dei bug

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.1 (2018.3.1)

*(Rilasciato il 6 dicembre 2018)*
Riepilogo: **Hotfix**

**Aggiunto:**

* [Simmetria]&#x200B;[Finestra vista] La simmetria nella vista 2D è tornata ed ora presenta un&#39;anteprima del pennello clone fissa

**Corretto:**

* [Esporta] In alcuni casi, l’esportazione in vista 2D genera una texture nera
* [Iray] Le informazioni normali diventano errate in Iray dopo aver creato un&#39;istanza di un livello di materiale
* Gli insiemi di texture non quadrate possono causare in alcuni casi l’arresto anomalo
* [Annulla] Diversi Ctrl+Z possono causare in alcuni casi l&#39;arresto anomalo
* [QML] In alcuni casi AlgScrollView può creare un avviso nel registro (cicli di associazione)

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.3.0 (2018.3.0)

*(Rilasciato il 20 novembre 2018)*
Riepilogo: <b>Aggiornamenti del viewport, corretta esportazione della vista 2D, nuovi helper dell&#39;interfaccia utente, uno strumento di simmetria migliorato, nuovi contenuti e un enorme miglioramento delle prestazioni</b>

<b>Aggiunto:</b>

* [Anti-alias]&#x200B;[Finestra vista] Nuova anti-alias temporale di filtro per la finestra della vista 3D (tramite Impostazioni schermo)
* [Esporta] Esporta il contenuto della finestra della vista 2D come texture singola
* [Export]&#x200B;[Dithering] Esporta dithering all’esportazione
* [Serie di livelli] Colori su livelli e cartelle
* [Serie di livelli] Attivazione e disattivazione rapida di più livelli ed effetti
* [Serie di livelli] Navigazione più semplice per i metodi di fusione con i tasti Su e Scorrimento del mouse
* [Proj]&#x200B;[UI] Manipolatore di rotazione aggiuntivo su tutti e tre gli assi per triplanare
* [Proj]&#x200B;[Scelte rapide] - e + per modificare le dimensioni del manipolatore Proiezione UV
* [Shader] Controlla i parametri dei livelli rivestiti con canali nello shader rivestito in PBR
* [Substance] Esporre nuovi input di texture basati su mesh per filtri e generatori
* [Symmetry]&#x200B;[Viewport]&#x200B;[UI] Controlla lo scostamento della simmetria con i manipolatori
* [Symmetry]&#x200B;[barra degli strumenti contestuale]&#x200B;[UI] Nuovo pannello di simmetria con opzioni
* [Symmetry] Nuova modalità di intersezione delle linee di simmetria
* [Simmetria] Nuovo cursore clone simmetria
* [Simmetria]&#x200B;[Scelte rapide] Q per nascondere e -, + per modificare le dimensioni e spostare per agganciare
* [Log] Migliora i messaggi di errore quando non è possibile esportare le texture
* [Scripting] Consente di modificare o aggiornare le risorse in Impostazioni di visualizzazione
* [Scripting] Consente di creare o rimuovere i canali nei set di texture
* [Content]&#x200B;[Shaders] Aggiungi il supporto per l&#39;anisotropia con uno shader dedicato (pbr-metal-rough-anisotropia-angle)
* [Contenuto] Aggiornamento della sfera di anteprima con anisotropia e angolo modificato
* [Content] Shutline matFx aggiornato
* [Content] Nuova creazione di texture.Scansione del volto senza interruzioni in XYZ
* [Contenuto] Nuove procedure anisotrope
* [Content] Nuovo filtro: baked lighting environment
* [Content] Mappa del nuovo ambiente: studio automobilistico neutro
* [Content] Nuovo modello di progetto: PBR - angolo di Anisotropia rugosità metallica (con canali di anisotropia)
* [Content] Nuovo modello di progetto: PBR - rugosità metallica patinata
* [SVT]&#x200B;[Engine]: Texture virtuali sparse (SVT)
* [SVT]&#x200B;[Preferenze]&#x200B;[UI] Opzione di accelerazione del supporto hardware SVT
* [SVT]&#x200B;[Registro] Ulteriori informazioni sulla funzionalità di creazione di texture virtuali sparse (ad esempio, disco di dimensioni)
* [SVT]&#x200B;[UI] Finestra del messaggio all&#39;avvio se le dimensioni del disco sono troppo basse per la cache
* [SVT]&#x200B;[Preferenze]&#x200B;[UI] Substance Painter posizione cache globale
* [SVT] Nuova variabile di ambiente per specificare il percorso della cache della Substance Painter
* [SVT] Nuova variabile di ambiente per attivare l&#39;accelerazione del supporto hardware SVT
* [SVT] Rileva supporto sparse per hardware
* [SVT]&#x200B;[Hardware Sparse] Aumento della versione minima del driver per la GPU Nvidia
* [SVT]&#x200B;[Shader]&#x200B;[Viewport]&#x200B;[UI] Avvisa l&#39;utente se all&#39;apertura del progetto sono presenti artefatti con texture virtuale sparsa

<b>Corretto:</b>

* [Selettore colore] Viene visualizzato il cursore di disegno quando si tenta di selezionare un colore
* L’arresto anomalo quando si selezionano o deselezionano i livelli in un ordine specifico può causare l’arresto anomalo
* Arresto anomalo quando si incolla come istanza un livello con una maschera
* [Canale utente]&#x200B;[Regressione] Arresto anomalo durante la ridenominazione del canale utente
* [Canale utente] Anteprima pennello grigio
* [Alembic] Una sola texture impostata da diversi materiali dopo l’importazione
* [Engine] La texture esportata è diversa dalla finestra della vista per i timbri a pennello
* [Motore] L’inversione con un effetto livello non influisce completamente su una texture
* Il selettore materiale sta applicando un tratto di pennello durante il prelievo
* Il passaggio a una risoluzione di 128x128px causa un arresto anomalo
* I collegamenti delle mappe trama non vengono aggiornati correttamente quando si ridefiniscono o si creano istanze dei livelli
* [Substance] UserData ColorSpace non funziona su Baked Mesh Normal richiesto come input
* Associazione MDL non corrispondente quando si utilizzano più istanze di shader
* [Simmetria]&#x200B;[Livello riempimento] Piano di simmetria e relativo manipolatore attivo nel livello di riempimento
* [Viewport] Il punto pivot per la traduzione non viene sempre aggiornato dopo aver fatto clic su
* [UI] Icone fisse e rimozione dei segnaposto per i monitor HDPI

<b>Problemi noti:</b>

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.2.3 (2018.2.3)

*(Rilasciato il 25 settembre 2018)*

**Corretto:**

* [Vista 2D] La vista 2D è interrotta con alcune trame durante la creazione di un nuovo progetto
* [Arresto anomalo] Il passaggio dalla proiezione Proiezione UV a quella triplanare causa un arresto anomalo
* [RayCollider] Arresti anomali multipli dovuti a &quot;RayCollider&quot;
* [Strumento] Quando si cambia livello, le proprietà del pennello modificate vengono perse
* Le impostazioni del pennello vengono ripristinate quando si passa alla gomma

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.2 (2018.2.2)

*(Rilasciato: 11 settembre 2018)*
Riepilogo: **Correzione rapida con aggiornamento dei contenuti, nuove funzionalità di scripting e possibilità di disattivare l&#39;aggiornamento automatico**

**Aggiunto:**

* [Content]&#x200B;[Shelf] Aggiungi un predefinito Ripiano incarnato
* [Content]&#x200B;[shelf] Conversione di 19 normali cutanee in materiali per la dispersione sottosuperficiale
* [Scripting] Crea un modello di progetto da un progetto aperto
* [Scripting] Ottenere/impostare le impostazioni di esportazione di un progetto aperto
* [Updates] Consente di disattivare la finestra a comparsa Aggiornamento automatico da impostazioni e variabile di ambiente
* [Aggiornamenti] Non visualizzare fino alla versione successiva nella finestra a comparsa con aggiornamenti per la manutenzione

**Corretto:**

* [Fotocamera] Zoom errato passando da ortogonale a prospettico
* [Display] Alcune mappe vengono visualizzate in modalità lineare anziché sRGB
* [Finestre di visualizzazione] Lo stato attivo della trama non funziona correttamente
* [2D View] Progetto con fotocamera rotta ha sparito UVs Gusci
* [SSS]&#x200B;[Tooltip] nel registro vengono visualizzate le descrizioni degli strumenti per la dispersione delle superfici
* Alcuni progetti non possono essere aperti in 2018.2 e il messaggio di errore non può salvare un pacchetto substance null
* [Maschera] Il colore dello strumento di pittura può bloccarsi in alcuni casi quando si lavora su una maschera
* [Materiale] Mappe non visualizzate in situazioni specifiche
* [Proj]&#x200B;[Strumenti] Manipolatore attivo con un generatore
* [Substance] Gruppi di parametri Substance mancanti
* [Scripting] Nome software errato nella documentazione
* [UDIM] Nessuna informazione nel registro sui gusci UV su più riquadri UV

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.1 (2018.2.1)

*(Rilasciato il 3 agosto 2018)*

**Corretto:**

* Parametri shader di dispersione sottosuperficie mancanti da progetti di aggiornamento

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.0 (2018.2.0)

*(Rilasciato il 2 agosto 2018)*
Riepilogo: **Versione estate, supporto per la dispersione sottosuperficiale, miglioramenti a livello di proiezione e riempimento, importazione e selezione della fotocamera, supporto di Alembic e glTF, trascinamento sulla mappa ID, supporto migliorato del formato di Substance e nuovi contenuti**

**Aggiunto:**

* [SSS]&#x200B;[Viewport]&#x200B;[Iray] Dispersione sottosuperficie generica
* [SSS] Sincronizza i parametri di dispersione MDL e subsuperficiale
* [SSS] È stato aggiunto un nuovo canale in scala di grigi denominato Dispersione
* [SSS]&#x200B;[Impostazioni shader] Parametro del tipo di dispersione per la dispersione del sottosuolo (incarnato o traslucido)
* [SSS]&#x200B;[Impostazioni shader] Parametro della scala di dispersione per la dispersione sotto la superficie
* [SSS]&#x200B;[Impostazioni shader] Parametro colore di dispersione per dispersione sottosuperficie
* [SSS]&#x200B;[Impostazioni schermo] Conteggio dei campioni di dispersione per la dispersione sotto la superficie
* [Shader]&#x200B;[Iray] Integrazione di MDL di dispersione sottosuperficiale per Iray
* [Shader] Aggiornamento di Shader tramite il programma di aggiornamento delle risorse
* [Shader] Aggiornamento dell&#39;API del log delle modifiche e della documentazione
* [Proprietà utensile]&#x200B;[Proj] Nuovi parametri per la proiezione triplanare
* [Finestra vista]&#x200B;[Proj] Controlla le proprietà del livello di riempimento nella vista 3D direttamente con i manipolatori (proiezione triplanare)
* [Shortcuts]&#x200B;[Proj] Nuove scelte rapide Q, W, E, R, T per manipolatori di proiezione triplanari
* [Finestra vista]&#x200B;[Proj] Controlla le proprietà del livello di riempimento nella vista 2D direttamente con i manipolatori (Proiezione UV)
* [Shortcuts]&#x200B;[Proj] Nuova scelta rapida Q per i manipolatori di Proiezione UV
* [Barra degli strumenti contestuale]&#x200B;[Proj] Controlla i manipolatori di proiezione triplanari
* [Barra degli strumenti contestuale]&#x200B;[Proj] Manipolatori Proiezione UV di controllo
* [Proprietà strumento] Disattiva l&#39;affiancamento della texture con lo strumento proiezione e stencil
* [Stencil] Utilizzare immagini non quadrate con lo strumento di proiezione/stencil
* [Stencil] Consenti il controllo della modalità di suddivisione in porzioni nella finestra Proprietà
* [Stencil] Lo zoom non è centrato su uno stencil non affiancato
* [Fotocamere] Importa fotocamere da Maya, Max, Blender, Modo, DAE
* [Fotocamere]&#x200B;[Finestra vista] Selezionare e controllare le videocamere importate nella finestra della vista
* [Fotocamere]&#x200B;[Iray] Seleziona e controlla le videocamere importate in Iray
* [Fotocamere]&#x200B;[UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] L’opzione di importazione delle fotocamere è selezionata per impostazione predefinita
* [Fotocamere]&#x200B;[Scelte rapide] Aggiungi scelte rapide per passare da una videocamera all’altra
* [Fotocamere]&#x200B;[Finestra vista] Aggiungi fotogramma nella finestra della vista
* [Fotocamere]&#x200B;[Impostazioni finestra di visualizzazione] Controllo dell&#39;opacità dei fotogrammi
* [Fotocamere]&#x200B;[Impostazioni fotocamera] lunghezza focale massima a 500 mm
* [Fotocamere]&#x200B;[Impostazioni videocamera] Rapporto di esposizione
* [Fotocamere]&#x200B;[Impostazioni fotocamera] Aggiungi un&#39;opzione di blocco
* [Fotocamere]&#x200B;[Impostazioni fotocamera] Aggiungi un&#39;opzione di ripristino
* [Cameras]&#x200B;[Impostazioni fotocamera] Aggiungi attributo distanza focale
* [glTF] Importazione di un file glTF
* [glTF] Importa mappa occlusione ambiente
* [Alembic] Importa fotogramma Alembic 1 con geometria statica
* [Ripiano] Trascina i materiali direttamente sulla trama utilizzando mappe ID con un modificatore (CTRL/Comando)
* [Pila di livelli] Creazione automatica di maschere ID con trascinamento di materiali sulla trama con mappe ID
* [Pila di livelli] Scorrimento automatico dei livelli con trascinamento sulla pila di livelli
* [UI]&#x200B;[Proprietà strumento] Predefinito di Esposizione Substance
* [UI]&#x200B;[Menu?] Miglioramento del menu?
* [UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] Riorganizzazione della finestra
* [UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] Sostituisci termine trama con file
* [UI]&#x200B;[Substance] Visualizza gli attributi della Substance nell&#39;interfaccia utente
* [Scelte rapide] F4 alterna la vista 2D e 3D
* [Scelte rapide] Nuove scelte rapide per Attiva/Disattiva stencil N e maschera rapida U
* [Integrazione Substance] Considera le istruzioni &#39;visible if&#39; nei parametri di Substance
* [Riquadro di visualizzazione] Le ombre non vengono calcolate dopo lo spostamento della videocamera
* [Content] Aggiorna MeetMat con le fotocamere importate
* [Content] Aggiungi un campione con la dispersione sottosuperficiale attivata - JadeToad
* [Content] Aggiungi un nuovo modello di progetto PBR con la dispersione sottosuperficie attivata
* [Content] Predefiniti di esportazione aggiornati per aggiungere un nuovo canale di diffusione
* [Content]&#x200B;[Shelf] Aggiunto supporto per la dispersione sottosuperficiale per: pbr-metal-rough, pbr-metal-rough-alpha-test, pbr-coated, pbr-spec-gloss
* [Content]&#x200B;[Shelf] Canale di dispersione aggiunto a 5 materiali intelligenti (marmi e pelli)
* [Content]&#x200B;[Shelf] 1 nuovo materiale giada
* [Content]&#x200B;[Shelf] 1 nuovo materiale cera

**Corretto:**

* [CMD] Risultati diversi utilizzando la stessa riga di comando con versioni diverse
* [TDR] Se TdrLevel è impostato, non ci sono errori nel registro
* [Baker] La mappa di occlusione ambientale è capovolta
* [ID Map] Arresto anomalo durante il prelievo al di fuori dell’intervallo 0-1
* [Iray] Arresto anomalo quando si cambia set di texture e si torna alla modalità Disegno
* [Finestra vista] Sincronizza le aree di rilascio tra le finestre della vista per il trascinamento
* [Motore] Artefatto moire quando si sovrappongono i livelli di riempimento o si dipinge un piccolo pennello
* [Licenza] Verifica versione software non valida del servizio di licenza
* [Licenza] Rielabora il modo in cui gestiamo l&#39;autenticazione
* [API] Chiama l’evento API di scripting onNewProjectCreated anche durante la creazione con un modello
* [Shader] Lo shader compilato non viene caricato dalla cache quando il file shader non viene compilato
* [Shelf] L’esportazione di file HDR dallo shelf genera un file con valori bloccati
* [Esporta] L’esportazione EXR blocca i valori di colore RGB tra 0 e 1
* [Contenuto] Disturbo procedurale 3D Perlin Disturbo Frattale è pixelato

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.1.3 (2018.1.3)

*(Rilasciato il 28 giugno 2018)*

**Aggiunto:**

* [Preferenze] Proponi di salvare il progetto al riavvio di Painter

**Corretto:**

* [Plugin] La Substance Source di ricerca non funziona
* [Materiali intelligenti] L’importazione di materiali intelligenti in alcuni casi provoca un arresto anomalo
* [Materiali avanzati] L’eliminazione di materiali intelligenti causa in alcuni casi un arresto anomalo
* [Salva] Il salvataggio causa un arresto anomalo in alcuni rari casi
* [Shelf] Inverti non funziona su Celle 2 e Celle 3
* [Shelf] Errore di battitura in alcuni Alpha
* [Ripiano] Alcuni materiali Substance non vengono riprodotti correttamente

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.2 (2018.1.2)

*(Rilasciato il 12 giugno 2018)*
Riepilogo: **Velocità di cottura migliorata, sistema di salvataggio migliorato, cursori aggiornati, API di plug-in aggiornata, traduzione cinese, spaziatura interna migliorata ora facoltativa**

**Aggiunto:**

* [Panettieri] Miglioramento delle prestazioni con la nuova versione per panettieri
* Forzare la finestra di dialogo di visualizzazione con la GPU incompatibile
* [Salva] Scopri la nuova funzionalità di progetto compatto (modalità di salvataggio completa/compatta)
* [Salva] Informa l&#39;utente in caso di errore di salvataggio
* [Clean] Salvataggio successivo in modalità completa/compatta
* [Cursori] Miglioramento della precisione delle barre e dei cursori dei colori/della scala di grigi
* [Cursori] Aggiunta di controlli freccia Su/Giù
* [Cursori] Stessa zona di rilevamento per i cursori a barre a colori e in scala di grigio
* [Plugin] Salvataggio automatico sempre in modalità incrementale
* [Plugin] Opzione per passare dai plug-in al nuovo stile di interfaccia
* [Lingua] Aggiungi traduzione cinese
* [Spaziatura interna] Opzione per passare dalla spaziatura UV a quella 3D adiacente per set di texture nelle impostazioni set di texture
* [Script] Modalità di salvataggio esposizione: completa/compatta o incrementale
* [Script] Aggiornamento della documentazione di scripting/QML
* [Registro] Indica la modalità di salvataggio nel registro (completo/compatto o incrementale)

**Corretto:**

* [Strumento] Lo slot del canale si trasforma in uno slot materiale su riempimenti a canale singolo
* Arresto anomalo durante il caricamento di una trama (FBX) con alcune facce non assegnate da un materiale
* Arresto anomalo di Iray con NVIDIA GRID 5.2 sulla macchina virtuale
* Arresto anomalo quando si annulla un&#39;eliminazione di materiali predefiniti
* Arresto anomalo durante il caricamento di alcuni progetti
* [Riga di comando] Nuova riga di comando per le trame UDIM suddivise per dim
* [Toolbar] Riduzione della barra degli strumenti
* [Istanza] Impossibile creare un&#39;istanza delle bitmap su più set di texture
* [Finestra vista] L’aggiornamento non è completo quando si dipinge su trama con UV in porzioni
* [Iray] La mappa normale viene applicata due volte per i dielettrici
* [Shelf] Errori di battitura in alcuni parametri di Substance (alpha, procedure e matfx)
* [Shelf] Errore ortografico per la bitmap &quot;Authorized Personnel Only&quot;
* [Script] La funzione alg.shaders.materials() non funziona più

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.1 (2018.1.1)

*(Rilasciato il 3 aprile 2018)*

**Corretto:**

* [Tablet] Problema durante la modifica delle scelte di interazione predefinite
* [Baker] Arresto anomalo con la libreria Assimp
* [Bakers] Regressione sulle prestazioni con A.O. map
* [Iray] La Distorsione obiettivo non viene applicata al canale Alpha
* [Driver] Aggiornamento dei requisiti minimi dei driver
* [3Dview] Normali non generate correttamente sulle trame UDIM senza informazioni sulle normali
* [Intel] Arresto anomalo con Substance Painter 2018.1.0
* [Intel]&#x200B;[Viewport] Problema con la spaziatura interna (artefatti neri)

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.0 (2018.1.0)

*(Rilasciato il 15 marzo 2018)*

**Aggiunto:**

* Nuovo stile generale (icone, colore, comportamento)
* Nuovo layout predefinito
* [Tablet] Miglioramento dell&#39;esperienza utente durante la pittura
* [Menu principale] Ordinare prima gli elementi nativi nelle visualizzazioni e nelle barre degli strumenti
* [Menu principale] Spostare le azioni rapide della maschera nella sezione viewport
* [Menu principale] Spostare le azioni del clic con il pulsante destro del mouse nella sezione della finestra della vista
* [Menu principale] Rinominare &quot;Visualizza&quot; come &quot;Finestra&quot;
* [Menu rapido] Nuove proprietà dello strumento facendo clic con il pulsante destro del mouse nella finestra della vista
* [Widget dock] Nuova barra degli strumenti dock per ridurre/richiamare rapidamente
* [Impostazioni di visualizzazione] Finestra Impostazioni videocamera e visualizzatore unita
* [Serie di livelli] Menu contestuale di scelta rapida
* [Pila di livelli] Trascina e rilascia per spostare qualsiasi effetto all’interno dello stesso livello
* [Toolbar] Riorganizzazione della barra degli strumenti e nuova barra degli strumenti contestuale
* [Barra degli strumenti] Dividere lo strumento Clona in due strumenti separati
* [Proprietà Tools] Valore più chiaro della scala di grigi dello sfondo nell&#39;anteprima
* [Strumenti proprietà] Organizzazione nelle schede (riempimento e strumenti)
* [Strumento] Il risultato del disegno corrisponde allo stencil
* [Finestra vista] Nuovo cursore per il livello di riempimento
* [Finestra vista] Navigazione e pittura più fluida (frequenza fotogrammi più elevata)
* [Finestra vista] Casella combinata di selezione Materiale/Canale/Mappa nella finestra della vista
* [Riquadro di visualizzazione] Ridurre lo sfarfallio durante la rotazione (ombra attivata)
* [Shelf] Visualizza i materiali per impostazione predefinita all’apertura di Painter
* [Shelf] Miglioramento del tempo di caricamento di texture e materiali Substance (da 2 a 6 volte più veloce)
* [Shelf] Riorganizzare le cartelle dei materiali per adattarle alla struttura della Substance Source
* [Shelf] Trascina i materiali direttamente sulla trama nella finestra della vista
* [Shelf] Nuovi rumori 3D (Perlin, Perlin Fractal, Simplex e Worley)
* [Shelf] Nuovo generatore maschera 3D linear gradient con posizione mesh
* [Shelf] Disturbi di base aggiornati per supportare il non square expansion
* [Shelf] Aggiunto un nuovo modello ed esporta il predefinito per Lens Studio (applicazione Snap)
* [Shelf] Materiali avanzati e maschere intelligenti aggiornati per utilizzare la versione più recente di Editor maschera (micro dettagli)
* [Shelf] Nuovo progetto di esempio &quot;TilingMaterial&quot; per creare materiali per piastrelle senza giunture
* [Shelf] Nuovi predefiniti per i pennelli (Calligrafia, Bagnato, Tratteggio e così via)
* [Cursori] Nuovi cursori e stile e comportamento delle barre di grigio/colore
* [Baker] Consenti l&#39;uso del rettangolo di selezione della scena per calcolare la mappa di posizione
* [Shader] Rimuove il parametro della forza del height dai parametri dello shader di default
* Motore di Substance [Engine] aggiornato
* [Motore] Nessuna o meno discontinuità tra i blocchi UV
* [Plugin] Importa più rapidamente i materiali scaricati da Substance Source
* [Plug-in] Aggiorna tutti i plug-in in base al nuovo stile generale
* [Preferenze] L’anteprima del colore di sfondo cambia automaticamente
* [Clean] Riduzione del rischio di danneggiamento dei progetti
* [Aperto] Apertura del progetto - Miglioramento orario
* [Nuovo progetto] Nuovo progetto - Miglioramento del tempo di aggiornamento mesh
* [Salva] Salvataggio del tempo del progetto migliorato
* [Log] Tipo di licenza segnalato nel log
* [TextureSet] Rinomina il pulsante &quot;Crea texture&quot; in &quot;Crea mappe trama&quot;
* Rinominare &quot;Mappe aggiuntive&quot; come &quot;Mesh maps&quot;

**Corretto:**

* [Finestra vista] Prestazioni errate con trame contenenti molti sottooggetti
* [Strumenti proprietà] Canale disattivato quando si trascina un’immagine nello slot del materiale
* [Proprietà Tools] L’anteprima del pennello non funziona con gli strumenti sfumino e clone
* [Set di texture] L’ordine dei canali non è corretto quando si utilizzano i modelli
* [Shelf] Icona mancante per il generatore di conversione in scala di grigi
* [Shelf] Sign Circle Number alpha è interrotto (font mancante)
* Rilevamento errato delle GPU integrate all’avvio
* [Arresto anomalo] Trascina una risorsa importata denominata con un carattere #
* [Engine] Problema di rilevamento Vram sulla GPU integrata
* [Engine] Risolti numerosi arresti anomali in Substance Engine Linker
* [Engine] Artefatti quadrati quando si modifica la risoluzione
* [Post Effects] Il ridimensionamento dell’interfaccia è lento quando gli effetti post sono attivi
* [Bakers] L’unità della scena non viene rispettata correttamente per i valori di distanza dei raggi
* [Panettieri] AO dalla distanza di occlusione della trama è fissato a 1 indipendentemente dal valore di input
* [Bakers] La corrispondenza per nome ignora alcune trame con nomi specifici
* [Pannelli] L’impostazione Colore da trama Poligruppo e ID trama restituisce sempre un’immagine nera
* [Bakers] ID Baking non riesce con trame FBX binarie da Blender
* [Shader] Disturbo nella vista 2D con dota-2 e non-pbr-spec-gloss
* [Linux] Durante il baking viene utilizzato un solo thread CPU
* [MacOS] Arresto anomalo con il cursore del pennello che si sposta sulla finestra della vista

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Processo di post-distorsione non preso in considerazione durante l&#39;esportazione in IRay (alfa)

## Versione 3

### 3.4.2 (2017.4.2)

*(Rilasciato il 24 gennaio 2018)*

**Aggiunto:**

* [Esportazione] Ottieni lo stato di un’esportazione con avanzamento passaggio
* [Esportazione] Consenti l’annullamento di un’esportazione
* [Esporta] Esporta le texture in Sketchfab senza perdere la qualità della mappa normale
* [Esportazione] Esportazione in formato binario (glb) glTF
* [Esporta] Consente il ridimensionamento delle colonne nella scheda di configurazione della finestra di esportazione
* [Shader] Aggiungere un registro delle modifiche per l&#39;API shader
* [Scripting] Aggiungere le funzioni di richiamata prima e dopo l’esportazione delle texture
* [Iray] Aggiornamento a SDK 2017.1 (supporto di GPU Volta)

**Corretto:**

* Arresto anomalo quando si esce dall’applicazione prima della visualizzazione della finestra principale
* [MAC] Arresto anomalo durante il caricamento di mappe in scala di grigio con IRAY
* [MAC] Il rilevamento VRAM non è corretto con il nuovo sistema operativo High Sierra
* [Plugin] Il download delle risorse da Substance Source non funziona più
* [Scripting] Rilevamento minimo della versione del plug-in non corretto
* [Esporta] Impossibile salvare il predefinito di esportazione dopo l’esportazione delle texture
* [Istanza] Problema relativo ai generatori di cui è stata creata un’istanza in un TextureSet senza mappe aggiuntive
* [Finestra vista] Il dithering non funziona con una risoluzione superiore a 4k
* [Riquadro di visualizzazione] La visualizzazione del materiale 2D View è coperta da rumore
* [Shelf] Migliorare il tempo di caricamento per i predefiniti shelf
* [Motore] Fusione errata durante il disegno sotto la selezione colore

### 3.4.1 (2017.4.1)

*(Rilasciato il 15 dicembre 2017)*

**Aggiunto:**

* [Scripting] Esporta trama tramite API di scripting
* [Import] Disabilita l&#39;importazione di un formato di file mesh non supportato (consenti solo obj, fbx, dae, ply)
* [Log] Indica con maggiore precisione il problema TDR nel file di log

**Corretto:**

* Arresto anomalo se l&#39;applicazione viene chiusa prima del termine della ricerca per indicizzazione delle risorse
* Arresto anomalo all’apertura di progetti con lo strumento Sfumino/Clone
* Arresto anomalo quando si utilizza Ripeti dopo un annullamento di una modifica dello shader in Impostazioni visualizzatore
* [Engine] La creazione di texture differisce tra Painter 2017.2 e 2017.4
* [Finestra vista] Il prelievo su una mappa ID da un&#39;istanza consente di campionare il colore errato
* [Esporta] Arresto anomalo durante l’esportazione di una texture normale o di occlusione non valida
* I gruppi dei file PSD di [Esportazione] sono bloccati all’apertura in Photoshop CS6
* [Plugin] Il plug-in Photoshop ignora la selezione del canale ed esporta sempre tutto
* [Livelli] Gli ancoraggi si interrompono quando vengono copiati/incollati su set di texture
* [Livelli] Alcuni riferimenti di ancoraggio non possono essere ripristinati se sono interrotti
* [Shader] Il parametro di rugosità secondaria rivestita con pbr è interrotto
* [Steam] La finestra a comparsa Controllo versione non deve essere visibile all’avvio

**Problemi noti:**

* [AMD] Si arresta in modo anomalo/si blocca quando si tenta di dipingere su una trama. Può essere risolto con un aggiornamento del driver GPU.

### 3.4.0 (2017.4.0)

*(Rilasciato il 23 novembre 2017)*

**Aggiunto:**

* [Creazione istanza] Consente di creare un&#39;istanza dei parametri tra i livelli
* [Istanza] Consente di passare da un livello di origine a un&#39;istanza e viceversa
* [Creazione di istanze] Aggiungi un’azione &quot;Crea istanza tra set di texture&quot;
* [Istanza] Indica nello stack di livelli istanze di rientro (cicli)
* [Istanza] Elimina le istanze quando viene rimossa un&#39;origine
* [Istanza] Non consentire riferimenti di ancoraggio dall&#39;esterno di una cartella istanza
* [UI] Sposta lo stack di annullamento nella propria finestra denominata &quot;History&quot;
* [Plugin] Integrazione del plug-in DCC live-link
* [Engine] Migliora le prestazioni di pittura con Pittura sparsa
* [Esporta] Aggiungi le opzioni di bozza e riesportazione al modulo di esportazione Sketchfab
* [Shelf] Aggiungi il controllo &quot;flip&quot; per le sostanze Font
* [Shelf] Aggiungi 20 nuovi materiali per le procedure
* [Shelf] Aggiungi 40 nuove mappe grunge (basate su bitmap e procedurali)
* [Finestra di visualizzazione] Attivare le collisioni di anteprima pennello su altri set di texture visibili
* Aggiornamento dei requisiti minimi dei driver della GPU AMD

**Corretto:**

* Arresto anomalo durante l’elaborazione di Substance con risoluzioni eccessive
* Arresto anomalo quando si dipingono intensamente con particelle
* [Finestra vista] Riflesso di specular errato nella vista 2D con trame specifiche
* [UI] Alcune azioni indesiderate vengono visualizzate nella finestra Cronologia

**Problemi noti:**

* [Livelli] Alcuni riferimenti di ancoraggio non possono essere ripristinati se sono interrotti
* Arresto anomalo quando si utilizza Ripeti dopo un annullamento di una modifica dello shader in Impostazioni visualizzatore

### 3.3.3 (2017.3.3)

*(Rilasciato il 1° dicembre 2017)*

**Corretto:**

* [Steam] La finestra a comparsa Controllo versione non deve essere visibile all’avvio
* I gruppi dei file PSD di [Esportazione] sono bloccati all’apertura in Photoshop CS6

### 3.3.2 (2017.3.2)

*(Rilasciato il 20 novembre 2017)*

**Aggiunto:**

* [UI] Migliora la finestra di dialogo per la nuova versione e aggiungi il registro modifiche
* [UI] Indica se la manutenzione è scaduta nella finestra di dialogo per una nuova versione
* [Licenza] Aggiornare il sistema di licenze per gestire le date di manutenzione
* [Esporta] Rinomina materiale standard Adobe in Adobe Dimension

**Corretto:**

* [Mac] La pittura causa la corruzione dei quadrati neri e delle texture
* La cache di [Engine] a volte può scomparire nella finestra della vista
* [Engine] Vengono visualizzati artefatti di tipo Blocky quando si attiva la compressione della memoria
* [Baking] Strani messaggi di errore durante la cottura di trame specifiche
* [Export] PSD non sono scritti correttamente e non vengono riconosciuti correttamente da Photoshop
* [Livelli] Non dovrebbe essere possibile copiare/incollare i livelli in più progetti
* [Substance] In alcuni casi, lo spazio colore UserData per l’input Normale viene capovolto
* [Shelf] Micro-normale nei generatori produce una curvatura invertita
* [Shelf] Il filtro HSL influisce anche sul canale alfa
* [Linux] L&#39;installazione su Centos non riesce a causa di dipendenze mancanti
* In alcuni casi, il programma di installazione non rimuove tutte le risorse dall&#39;installazione precedente

### 3.3.1 (2017.3.1)

*(Rilasciato il 26 ottobre 2017)*

**Aggiunto:**

* [Esporta] Consente di esportare la trama da un progetto
* [Shelf] Rimuovere &quot;Sub-Shelf&quot; dai titoli delle schede
* Salvare le impostazioni di post-elaborazione nei modelli
* Rendere il messaggio TDR più comprensibile
* Finestra Migliora impostazioni per la segnalazione degli errori

**Corretto:**

* Arresto anomalo quando si eliminano più scaffali secondari
* Arresto anomalo durante il passaggio da un livello a un altro durante il calcolo di un motore
* [Mac] Arresto anomalo della GPU Intel durante il calcolo del motore
* [Mac]&#x200B;[Finestra vista] Prestazioni errate quando è attivato il dithering
* [Mac] MacOS 10.13 viene riconosciuto come &quot;Versione sconosciuta&quot; nel file di registro
* [Baker] Cucinare in gabbia non funziona più
* [Livelli] La scelta rapida Ctrl + C (azione copia) non funziona più
* [Livelli] Incollare i livelli non aggiorna l’interfaccia utente con i riferimenti dell’ancoraggio
* [Ancoraggio] Quando si duplica o si copia/incolla un livello con riferimenti, i collegamenti vengono interrotti
* [Esportazione] L’esportazione 8K può causare l’arresto anomalo o il blocco dell’applicazione in alcuni casi
* [Esporta] Più problemi nel formato di file glTF generato
* [Import] La reimportazione di una trama con lo stesso nome di file non funziona più
* [Plugin] La finestra di salvataggio automatico viene sempre visualizzata sopra ogni elemento
* [UI] Ciclo infinito quando si preme &quot;Esc&quot; nella finestra di dialogo TDR
* [UI] Reimposta interfaccia utente visualizza una seconda barra del titolo nella finestra scaffale

### 3.3.0 (2017.3.0)

*(Rilasciato il 28 settembre 2017)*

**Aggiunto:**

* [Esporta] Consente di esportare trame e trame per Adobe Project Felix
* [Esporta] Consente di esportare nel formato di file glTF
* [Engine] Ottimizza le dimensioni delle texture in VRAM utilizzando la compressione dei blocchi
* [Finestra vista] Consente di trascinare una trama o un progetto nella finestra della vista
* [UI] Migliora il messaggio di avviso relativo al TDR.
* [UI] Il registro deve essere visualizzato solo su richiesta
* [UI] Consenti di cancellare il contenuto della finestra di registro
* [UI] Visualizza avvisi ed errori nella barra di stato
* [UI] Visualizza le schede in alto come nei browser Web
* [UI] Migliorare il contesto e i messaggi &quot;non colorabili&quot;
* [UI] Aggiungi un’azione &quot;Salva come copia&quot; nel menu del file
* [Livello] Per impostazione predefinita, imposta l’impostazione predefinita per la porzione su 1
* [Ripiano] Filtro sfumatura migliorato per supportare 10 colori dinamici
* [Shelf] Aggiungi uno spazio nella query predefinita del mini-shelf
* [Shelf] Aggiungi un&#39;azione &quot;Apri in Esplora risorse&quot; per le risorse locali nello shelf
* [Shelf] Aggiungi modello e shader per Adobe Material Standard (Project Felix)
* [Ripiano] Aumenta l’affiancatura fino a 128 nelle ombreggiature a strati di materiale
* [Ripiano] Curvatura sobel aggiunta per micro-dettagli dei generatori maschera
* [Plugin] Aggiungi plug-in di salvataggio automatico con intervallo di tempo personalizzabile
* [Scripting] Aggiungere una funzione &quot;Salva come copia&quot;

**Corretto:**

* [UI] Il layout non funziona al primo avvio
* [Esportazione] Il PSD generato durante l’esportazione contiene errori di formato
* [Esporta] EXR esporta sempre mappa height a 8 bit
* [Esporta] Arresto anomalo durante l’esportazione di mappe aggiuntive danneggiate
* [Importazione] In alcuni casi i bordi netti non vengono mantenuti su trame poly basse
* [Import] Messaggi di errore migliorati durante l&#39;importazione di trame con problemi
* [Bakers] La mappatura degli ID non riesce con l&#39;opzione Corrispondenza per nome abilitata
* [Riquadro di visualizzazione] Lo spazio tangente non è sincronizzato con i forni
* [Effetto] Spostandosi indietro di un livello non si ripristina il riferimento di un ancoraggio
* [Effetto] Problema di aggiornamento quando si crea un collegamento tra due maschere con ancoraggi
* [Effetto] I punti di ancoraggio delle maschere sopra la maschera non devono essere elencati
* [Effetto] L’impostazione Estrai Alpha da Ancoraggi non funziona
* [Motore] La maschera si inverte dopo il primo tratto del pennello
* [Engine] Arresto anomalo quando si cambia set di texture in un progetto specifico
* [Shelf] Arresto anomalo quando si elimina un predefinito presente in un progetto
* [Shelf] Errore di battitura nel filtro triplanare avanzato
* [Shelf] MG Mask Builder AO Noise Scale non funziona correttamente
* [Shelf] MG Mask Builder ha parametri di curvatura invertiti
* [Scaffale] Le alfa importate generano un&#39;anteprima della sfera di materiale anziché una di forma piatta

### 3.2.0 (2017.2.0)

*(Rilasciato il 27 luglio 2017)*

**Aggiunto:**

* Punti di ancoraggio - Sistema di riferimento livello e maschera
* [Livelli] Possibilità di rinominare gli effetti di riempimento e disegno
* [Plugin] Plug-in Substance Source aggiornato
* [Scripting] Consente di eseguire query sulla risoluzione del set di texture
* [Scripting] Consenti di ottenere lo stato del motore di pittura
* [Prestazioni] Ottimizzazione migliorata del caricamento del progetto e della timbratura del pennello

**Corretto:**

* [Tool] Problemi di prestazioni durante la modifica dei parametri del materiale
* [Motore] Scomparsa dei tratti di pennello durante la modifica della risoluzione (4K>2K)
* [Vista 3D] Lo spazio tangente non è sincronizzato con i forni
* [Shelf] Il percorso dello scaffale nei documenti utente non viene creato automaticamente
* [Shelf] Rendete i predefiniti compatibili con le versioni precedenti dopo un aggiornamento
* [Shader] Lo shader non PBR non funziona più
* [Bakers] La mappatura degli ID non riesce con l&#39;opzione Corrispondenza per nome abilitata
* [Sample] I nomi dei set di texture del progetto di esempio Meet Mat non sono corretti
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura

### 3.1.0 (2017.1.0)

*(Rilasciato il 20 giugno 2017)*

**Aggiunto:**

* [Plugin] Nuovo plug-in Substance Source (consente di scaricare risorse nello scaffale)
* [Scaffale] 4 Nuovi Font (Giapponese + Cinese Semplificato, Macchina Da Scrivere, Segmento)
* [Shelf] 230 Nuovi Alpha (Mix di pattern, pennelli e scansioni di impronte digitali)
* [Scaffale] 50 Nuovi Procedurali (Tessuti di abbigliamento medievale e contemporaneo)
* [Scaffale] 2 Nuove mappe ambientali (Mondarrain e Villa Nova Street)
* [Shelf] 9 Nuovi filtri (MatFx Detail Edge Wear, Clamp, HBAO, ecc.)
* [Shelf] Mappa ambiente Panorama predefinita migliorata
* [Shelf] Nuovi predefiniti di esportazione Arnold 5
* [Scripting] Consente di importare la risorsa nello scaffale

**Problemi noti:**

* [Esportazione] La modifica di un predefinito di esportazione è molto lenta

## Versione 2

### 2.6.2

*(Rilasciato il 20 ottobre 2017)*

<b>Aggiunto:</b>

* [Set di texture] Consente di eliminare i set di texture disattivati
* [Shelf] Consenti a più utenti di scrivere nella stessa cartella shelf
* [Scripting] Possibilità di ricaricare la cartella dei plug-in
* [Scripting] Aggiungi una versione API minima richiesta nei metadati del plug-in per garantire la compatibilità
* [IRay] Miglioramenti alla finestra di dialogo Esporta immagine

<b>Corretto:</b>

* [Engine] Problema di scomparsa dei tratti quando si modifica la risoluzione (4K>2K)
* [Bakers] La mappatura degli ID non riesce con l&#39;opzione Corrispondenza per nome abilitata
* [Bakers] I messaggi di errore non sono sufficientemente espliciti
* [Vista 3D] Lo spazio tangente non è sincronizzato con i forni
* [Strumento] Artefatti di nero quando si utilizza lo strumento sfumino
* [Shader] Lo shader non PBR non funziona più
* [Shader] &quot;pbr-coated&quot; è rotto
* [Shader] La rugosità del rivestimento dello shader &quot;pbr-coated&quot; non ha più alcun impatto
* [Shader] Lo shader lucido della specifica non corrisponde a Iray e SD
* [Shelf] Arresto anomalo durante il caricamento di due file con lo stesso nome ma estensioni diverse
* [Shelf] Impossibile modificare il predefinito negli scaffali
* [Shelf] Impossibile impostare un&#39;anteprima personalizzata per le risorse importate nello shelf
* Le risorse caricate dalla cache perdono il loro utilizzo
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura
* Salvataggio del progetto errato se il nome del file contiene due punti
* Importazione di file con più punti (.) nel nome del file causa problemi

### 2.6.1

*(Rilasciato il 12 maggio 2017)*

**Aggiunto:**

* [TextureSet] Non consentire la riassegnazione di materiali mesh a nulla

**Corretto:**

* Arresto anomalo quando si cambia TextureSet dopo la sostituzione della mappa con baking
* Arresto anomalo quando si esegue &quot;Annulla e ripeti&quot; dopo aver modificato il metodo di fusione del livello
* Arresto anomalo o blocco quando si utilizza l’effetto &quot;Selezione colore&quot; con mappa ID grande
* [Esporta] I set di texture rinominati non sono ordinati alfabeticamente nella finestra di esportazione
* [TextureSet] Il ripristino del nome predefinito non verifica la presenza di unicità
* [TextureSet] Il set di texture rinominato viene disattivato dopo la riapertura del progetto
* [Shelf] Contenuto modelli predefiniti mancante
* [Ripiano] Le texture non quadrate vengono visualizzate come quadrate
* [Shader] Una volta disattivato un set di texture, lo shader associato viene eliminato
* [Script] alg.baking.setTextureSetBakingParameters() non funziona più
* [Scripting] Errore di battitura nell’esercitazione websocket
* [Scripting] Vari problemi in AlgWidgets
* [Log] Rilevamento errato della memoria virtuale disponibile in alcuni casi

### 2.6.0

*(Rilasciato il 27 aprile 2017)*

**Aggiunto:**

* Aggiungi nuovo progetto di esempio &quot;Meet Mat&quot;
* [Plugin] Nuovo plug-in &quot;Resources Updater&quot;
* [TextureSet] Consente di rinominare e aggiungere una descrizione ai set di texture
* [TextureSet] Consente di riassegnare i materiali
* [TextureSet] Pulsante Aggiungi impostazione nella finestra elenco set di texture
* [TextureSet] Mostra i set di texture &quot;disabilitati&quot; nella parte inferiore dell’elenco
* [Substance] Utilizzate mappe aggiuntive con la risoluzione del set di texture corrente per migliorare le prestazioni
* [Scripting] Consente di aggiornare una risorsa utilizzata in un progetto (materiale, generatore, ecc.)
* [Scripting] Aggiungere un modo per aggiungere/rimuovere uno scaffale
* [Scripting] Consente di eseguire query sulle informazioni dalla risorsa nei progetti
* [Scripting] Consente di recuperare un elenco di scaffali disponibili
* [Scripting] Esercitazione per migliorare la miniatura di AlgWidget
* [Esporta] Disattiva/attiva profondità di bit in base al supporto del formato di file
* [Log] Aggiungi il nome del plug-in per la stampa nella console
* [Log] Rimuovi errore sui set di texture nascosti
* Aggiornate la &quot;Schermata introduttiva&quot; con nuove icone e testo per gli esempi

**Corretto:**

* Arresto anomalo durante l’aggiornamento di una trama in progetti specifici
* [Finestra vista] Il colore interno del piano di simmetria non è più visibile
* [Riquadro di visualizzazione] Alcuni effetti di post-elaborazione sono attivati quando si utilizza la vista Solo
* [Ombreggiature] La fusione &quot;sopra\_predefinito&quot; non funziona correttamente
* [Shader] Avvertenza sul test alfa con lo shader predefinito
* [Shelf] Analisi errata dei tag dalle Substance
* [Shelf] MatFX Ruggine Weathering non funziona correttamente
* [Shelf] Per impostazione predefinita, il filtro HSL è attivato sui canali errati
* [Shelf] Per impostazione predefinita, l’opzione Nitidezza è abilitata nel canale Height/Normale
* [Esporta] I predefiniti di esportazione Vray non utilizzano una mappa normale OpenGL
* [Tool] Problemi di imprecisione con lo strumento Clona/Sfumino per creare artefatti

### 2.5.3

*(Rilasciato il 15 marzo 2017)*

**Corretto:**

* [Baker] Arresto anomalo durante la cottura al forno con trame specifiche

**Problemi noti:**

* [Mac] In alcuni casi, le particelle possono danneggiare le texture

### 2.5.2

*(Rilasciato il 14 marzo 2017)*

**Corretto:**

* [Tool] I tablet Wacom non funzionano su Linux
* [Strumento] Artefatti di nero quando si utilizza lo strumento sfumino
* [Panettieri] La cottura non riesce se si utilizza Corrispondenza per nome con una gabbia
* [Panettieri] Occlusione ambiente interrotta durante la cottura al forno solo con carta normale
* [Shelf] I filtri generici non gestiscono correttamente il canale alfa (Contrasto/Luminosità, Passa alto, ecc.)
* [Riquadro di visualizzazione] Problema di prestazioni durante il caricamento di un progetto con le ombre attivate
* [Riquadro di visualizzazione] Problema di dithering nella vista 3D su MacOS
* [Finestra vista] Le anteprime delle particelle non vengono visualizzate correttamente quando il profilo colore è attivato
* [Iray] Arresto anomalo quando si ritorna al progetto OpenGL se l’inizializzazione di Iray non riesce
* [IRay] La luminosità viene ignorata durante il rendering dello shader SpecGloss/mdl
* [Shader] Lo shader Spec/Gloss non corrisponde a Iray e SD
* [Shader] Conversione sRGB diversa dalla conversione LUT lineare in sRGB
* [Shader] Rendering errato durante il caricamento di un progetto con ombreggiature obsolete
* [Shader] Lo shader &quot;pbr-coated&quot; non funziona più
* [Esportazione] Alcuni canali vengono comunque esportati anche se non presenti nel set di texture
* [Livelli] Il metodo di fusione &quot;mappa normale, inverti dettagli&quot; non funziona sui canali in scala di grigio
* [UI] Problema nella &quot;Finestra di selezione del colore&quot; con monitor HDPI e zoom dello schermo al 150%

**Problemi noti:**

* [Mac] In alcuni casi, le particelle possono danneggiare le texture

### 2.5.1

*(Rilasciato il 27 febbraio 2017)*

**Corretto:**

* [Mac] Input del tablet Wacom interrotto nella vista 3D e 2D
* [Panettieri] La corrispondenza per nome non funziona più
* [Panettieri] L’impostazione &quot;Normali medi&quot; non funziona più
* [Iray] Rendering non corretto con mappa normale inattiva
* [Iray] I profili colore si comportano in modo diverso rispetto al modulo di rendering OpenGL
* [Iray] L’esportazione del rendering come bitmap non include la correzione del profilo colore
* [Substance] I filtri del materiale non funzionano più
* [Strumento] L&#39;opacità del tratto non viene memorizzata nei predefiniti del pennello
* [Strumento] L’allineamento UV del pennello clone non funziona più
* [Esporta] Il canale di Spostamento deve essere centrato in 0,5 quando si esporta in numeri interi
* [Template] Il percorso assoluto è memorizzato in Templates
* [TextureSet] La texture del canale persiste dopo la rimozione del canale

**Problemi noti:**

* [Linux] Gli input dei tablet Wacom non funzionano nella vista 3D e 2D
* [Mac] In alcuni casi, le particelle possono danneggiare le texture
* [Esportazione] In casi molto rari, possono apparire rettangoli neri sulle GPU AMD

### 2.5.0

*(Rilasciato il 21 febbraio 2017)*

**Aggiunto:**

* Aggiunta del supporto per le GPU AMD Radeon Pro e AMD FirePro
* [Tool] Aggiungi il supporto per l’opacità del tratto
* [Tool] Aggiungi un modificatore che consenta di continuare l’ultimo tratto del pennello
* [Iray] Aggiornamento per supportare le GPU Pascal
* [Finestra vista] Aggiungere il supporto per i profili colore (LUT)
* [Substance] Integrazione del nuovo framework (motore SD6)
* [UI] Aumenta l’elenco dei file recenti nel menu File
* [Importa] Utilizza la categoria da sostanze per riempire il prefisso nella finestra di dialogo di importazione
* [Panettieri] Consenti di cuocere texture 8K
* [Panettieri] Consenti di produrre risoluzioni non quadrate
* [Pannelli] Migliora il consumo di memoria durante la cottura di trame pesanti ad alto polio
* [Shelf] Bloccare gli scaffali (e i progetti) per impedire la modifica simultanea ed evitare corruzioni
* [Shelf] Leggi la categoria e le parole chiave delle sostanze per utilizzarle per filtrare
* [Shelf] Consente di escludere le risorse dal risultato di una query di ricerca
* [Shelf] Calcolo temporale delle miniature migliorato
* [Shelf] Consenti di incorporare predefiniti nei progetti
* [Shelf] Consente di comprimere/espandere rapidamente la vista struttura con MAIUSC
* [Shelf] Consente di salvare le miniature quando le risorse sono di sola lettura (cache locale)
* [Scaffale] Nuovo contenuto : nuovi filtri (trasformazione, specchio, triplanare, ecc.)
* [Shelf] Nuovo contenuto : nuovi profili LUT (classici e artistici, come Film Noir, Vintage, ecc.)
* [Shelf] Nuovo contenuto : 10 nuove Substance di font per generare rapidamente testi personalizzati
* [Shelf] Nuovi modelli: Unità 5 e motore irreale 4
* [Shelf] Il filtro HSL è stato migliorato per semplificare maggiormente l&#39;uso degli artisti
* [Shader] Aggiungi il supporto per il canale di specular level negli shader PBR
* [Shader] Aggiungere il supporto per il dithering nello shader di test di Alpha
* [Shader] Aggiungi il supporto per la mappatura delle occlusioni parallasse negli shader PBR
* [Shader] Consente di definire un&#39;interfaccia utente personalizzata per i parametri dello shader
* [MatLayering] Crea un nuovo canale maschera per il flusso di lavoro per la creazione di livelli di materiale
* [Scripting] Consenti la scrittura di metadati in un progetto SP
* [Scripting] Consente di esportare con un predefinito di esportazione specifico
* [Scripting] Consente di recuperare i parametri dello shader come JSON.
* [Scripting] Aggiunta del supporto per le connessioni WebSocket
* [Scripting] Aggiungi la possibilità di caricare istanze dello shader
* [Scripting] Aggiungi la possibilità di creare un nuovo progetto
* [Scripting] Consente di recuperare l’URL della trama importata in un progetto
* [Scripting] Consenti cottura al forno non quadrata
* [Scripting] Segnala errori durante l’impostazione dei dati tramite API di scripting
* [Substance] Aggiungi tag utente-dati per specificare il formato mappa normale

**Corretto:**

* Arresto anomalo durante la selezione del colore con le sostanze
* Arresto anomalo durante il caricamento di un&#39;immagine non RGBA32f come mappa dell&#39;ambiente
* Arresto anomalo relativo all’uso di colori su GPU AMD
* [Trama] L&#39;importazione OBJ non riconosce i materiali senza file mtl
* [Trama] La generazione del nome del set di texture UDIM può non essere corretta su alcune trame
* [UI] Pulsante Annulla/Ripeti nel visualizzatore Impostazione dello stato attivo e interruzione dello scorrimento del mouse
* [UI] Alcune etichette sono ritagliate in modo errato in High-DPI
* [Livello] La modalità Sostituisci per l’effetto disegno ha un comportamento errato su Maschera
* [Livello] Il metodo di fusione Sottrai ha un comportamento errato con il canale alfa
* [Strumento] La dimensione del pennello diventa enorme nella vista 2D quando si disegna sui bordi UV
* [Tool] La linea retta agganciata ha un comportamento irregolare con DPI alto
* [Strumento] La risoluzione dello stencil a volte non è corretta
* [Pannelli] I valori di &quot;Distanza max occlusione&quot; sono bloccati se &quot;relativa al rettangolo di selezione&quot; è &quot;Disattivato&quot;
* [Shader] Le definizioni di canale di stack e parametro automatico non corrispondono
* [Vista 3D] Visualizzazione incoerente del canale normale a seconda dell&#39;impostazione del progetto
* [Riquadro di visualizzazione] Alcune mappe normali presentano valori bloccati che appaiono come artefatti
* [Riquadro di visualizzazione] Gli effetti a posteriori sono sempre disattivati per impostazione predefinita
* [Esporta] L’impostazione di miscelazione normale non è corretta se manca il canale normale
* [Esportazione] Generazione di texture errata in alcuni casi su GPU AMD
* [Esporta] I parametri dello shader non vengono esportati correttamente se si trovano in un gruppo
* [Export] La modifica di un predefinito di esportazione in uno scaffale personalizzato genera un errore di registro
* [Shelf] Il filtro della visualizzazione a struttura non corrisponde esattamente al nome della cartella
* [Shelf] Ridenominare un predefinito di shelf è difficile da leggere
* [Shelf] La risorsa Shader importata nello Shelf non viene mantenuta dopo il riavvio
* [Shelf] Contenuto : Predefinito strumento saldatura mancante
* [Shelf] Contenuto: il Tile Generator non funziona correttamente
* [Scaffale] Contenuto : Corretta maschera errata su materiale intelligente sporco di gomma
* [Shelf] Contenuto : Corretto il nome del gruppo errato sul materiale del sacchetto in pelle
* [Iray] Metà delle maglie è mancante in Iray
* [Linux] Arresto anomalo quando si trascina una risorsa sopra la vista 3D
* [Mac] Le preferenze vengono reimpostate a ogni avvio su Sierra

**Problemi noti:**

* [Esportazione] In casi molto rari, possono apparire rettangoli neri sulle GPU AMD
* [Iray] I profili colore a volte possono comportarsi in modo strano

### 2.4.1

*(Rilasciato il 28 ottobre 2016)*

**Corretto:**

* Arresto anomalo durante la creazione di un progetto con un modello
* Arresto anomalo quando si chiude la finestra di dialogo di esportazione durante un’esportazione
* [Mac] Errori durante il salvataggio del progetto (impossibile salvare il predefinito di esportazione)
* [Shelf] Quando si crea un nuovo predefinito, questo viene visualizzato due volte
* [Shelf] I predefiniti non possono essere caricati in modalità di sola lettura senza diritti di amministratore

### 2.4.0

*(Rilasciato il 27 ottobre 2016)*

**Aggiunto:**

* [Shelf] Nuova interfaccia per sfogliare le risorse (vista struttura, filtri e così via)
* [Shelf] Consente di salvare una ricerca come predefinito
* [Shelf] Consente di creare una nuova finestra da un predefinito
* [Shelf] Nuova interfaccia per l&#39;importazione delle risorse
* [Shelf] Non copiare lo scaffale allegorico predefinito nella cartella Documenti
* [Shelf] Nuovi predefiniti particelle : Circuito elettrico, Linee elettriche, Rococò, Vene piccole
* [Shelf] Migliorati i vecchi predefiniti particelle per essere più facili da usare (come &quot;Rain&quot;)
* [Shelf] Aggiungi nuove informazioni nel menu contestuale della risorsa
* [Finestra di visualizzazione] Miglioramento delle prestazioni durante il caricamento delle mappe dell&#39;ambiente
* [Finestra vista] Aggiungi il supporto per mappe di ambiente che non sono alimentate da due

**Corretto:**

* Arresto anomalo durante la rimozione di una maschera
* Arresto anomalo quando si disegna dopo aver salvato un predefinito
* Arresto anomalo con sfocatura dell’ambiente su alcune GPU
* Arresto anomalo durante l’assegnazione di una risorsa errata al mini scaffale
* [Shelf] Pulisci e salva rimuovi tag e metadati per le risorse nel progetto
* [Shelf] l’importazione di un predefinito ne mostra le risorse nello shelf
* [Esporta] La mappa normale generata dal canale del height ha un’intensità bassa
* [Esporta] Normale da trama non è sempre presente nella mappa normale finale
* [Esportazione] Talvolta può verificarsi una dilatazione con trasparenza senza alcuna trasparenza
* [Scripting] &quot;alg.plugin\_root\_directory&quot; può restituire un percorso di rete troncato
* Il pulsante [TextureSet] Lock (Blocca texture) è attivato quando si riaprono progetti non quadrati

### 2.3.1

*(Rilasciato il 7 ottobre 2016)*

**Aggiunto:**

* [Plugin]&#x200B;[Photoshop] Consente di specificare quale materiale/stack/canale esportare
* [Scripting] I nomi delle funzioni presentano alcune incongruenze

**Corretto:**

* L’Alpha [Esporta] può essere eliminato nei predefiniti di esportazione personalizzati
* [Export] L’Alpha ottiene una conversione gamma errata sui canali sRGB
* [Esporta] I documenti non quadrati vengono esportati come quadrati
* [Esporta] Impossibile esportare mappe aggiuntive se ne manca una
* [Iray] Alcuni parametri (come Intensità emissiva) non hanno alcun effetto
* [NVIDIA] Arresto anomalo all&#39;avvio con NVIDIA Quadro K2200/GTX 750/760
* [AMD] Set di colori non corretto per miniature e anteprime
* [AMD] Si blocca e si verifica un errore del driver all&#39;apertura di un nuovo file
* [Log] &quot;versione-software&quot; mancante nel file di log

### 2.3.0

*(Rilasciato il 15 settembre 2016)*

**Aggiunto:**

* [Plugin] Nuovo plug-in &quot;Esporta in Photoshop&quot; (esportazione dello stack di livelli completo)
* [Esporta] Consente di specificare la larghezza della spaziatura interna (in pixel o infinito)
* [Esporta] Consente di impostare il tipo di sfondo esterno agli UV
* [Shelf] Nuovo shader di stratificazione del materiale per fondere 10 materiali
* [Shelf] Nuovo shader argilla per visualizzare i dettagli con il canale height/normale
* [Shelf] Nuovo filtro di illuminazione cotta con input ambientale
* [Shelf] Sono stati aggiornati alcuni generatori di maschere per aggiungere trasformazioni non quadrate
* [Finestra vista] Aggiungere la mappa normale composta (normale+height+bake) alla modalità Solo
* [Scripting] Consente di esportare mappe aggiuntive
* [Scripting] Consente di eseguire query sulle mappe aggiuntive disponibili per set di texture
* [Scripting] Consente di recuperare il formato del canale
* [Scripting] Aggiungere esempi nella documentazione di cottura
* [Scripting] Consente di interrogare la visibilità di un livello
* [Scripting] Consente di interrogare il metodo di fusione e l’opacità del livello
* [Scripting] Consente di esportare le mappe convertite (mappe normali finali, AO misti, ecc.)
* [Substance] Lettura e connessione di utilizzi personalizzati
* [Scelte rapide] Aggiungi il tasto modificatore (MAIUSC) per tornare alla modalità Solo
* [Esporta] Predefinito di esportazione predefinito aggiornato per disattivare il canale alfa
* [UI] Le miniature ora vengono calcolate solo se il motore è disponibile
* [UI] Visualizza una menzione quando le miniature sono elaborate

**Corretto:**

* Arresto anomalo con alcuni vecchi progetti all’apertura
* Arresto anomalo con cache dei canali delle texture danneggiata
* Arresto anomalo durante la fusione di più di 4 materiali con il flusso di lavoro Livelli di materiale
* [UI] Le scelte rapide degli strumenti non funzionano se la barra degli strumenti è nascosta
* [UI] La barra degli strumenti Iray è etichettata &quot;Senza titolo&quot; nel menu Visualizza
* [UI] Le barre degli strumenti plug-in sono denominate &quot;Untilted&quot; nel menu Visualizza
* [Baker] Premendo Invio durante la modifica di un&#39;impostazione bake viene avviato il processo bake
* [Baker] Intervalli errati per alcuni parametri
* [Import] Impossibile importare mesh OBJ a causa di numeri molto grandi
* [Import] Alcuni file OBJ vengono importati con troppi sottooggetti
* Lo sfondo del canale [Esporta] viene riempito di nero al posto del colore predefinito al momento dell’esportazione
* [Strumento] Le particelle non funzionano correttamente se il valore FOV è troppo basso
* [Strumento] Il colore di anteprima del pennello non è corretto con le maschere nei sottoinsiemi
* [Finestra vista] Quando il pennello entra in aree vuote nella vista 2D, diventa gigantesco
* [Riquadro di visualizzazione] Anteprima pennello vuoto quando si colorano texture normali
* [Scripting] Documentazione errata: &quot;ao&quot; elencato invece di &quot;ambientocclusion&quot;
* [Scripting] Il processo avviato con subprocess() viene interrotto alla chiusura di Painter
* [Shelf] Il filtro per l&#39;illuminazione al forno utilizza un input AO errato
* [MacOS] Progetto rimosso dell&#39;idrante (incompatibile)
* Il progetto predefinito viene aperto quando si carica un file \*.spt (anziché \*.spp)

**Problemi noti:**

* [Plugin] A causa di Photoshop, il height e il canale normale non possono essere tradotti così com’è

### 2.2.0

*(Rilasciato il 22 luglio 2016)*

**Aggiunto:**

* [Shelf] Miglioramento del sistema di ricerca e delle query
* [Shelf] Aggiungi campo di ricerca per i mini-scaffali
* [Shader] Consente di definire la precisione dei passi per i cursori
* [Shader] Aggiungere un pulsante Annulla/Ripeti per i parametri dello shader
* [Shader] Il ricaricamento di uno shader non deve reimpostarne i parametri
* [MatLayering] Aggiungi il supporto per Stratificazioni dinamiche del materiale e sottopile
* [MatLayering] Consenti di importare un file json per configurare le impostazioni dello shader
* [MatLayering] Limite sblocca i campionatori texture (passa a texture senza binding)
* [Scripting] Consenti di impostare le impostazioni dei panettieri e avviare il loro calcolo
* [Substance] Utilizzare &quot;utilizzo&quot; per connessioni di input/output oltre agli identificatori
* [Tool] Consente di selezionare il canale di anteprima nella finestra della vista per lo strumento di proiezione

**Corretto:**

* Arresto anomalo all&#39;avvio se le sostanze si trovano in una cartella errata
* Il rapporto sugli arresti anomali a volte non funziona a causa di un file di registro errato
* [Iray] Gli effetti post non si aggiornano quando Iray è in pausa
* [Iray] La scelta rapida per l&#39;attivazione automatica non funziona più
* [Iray] Il comportamento del cursore Apertura varia a seconda delle dimensioni della risorsa
* [Livelli] Il primo canale di materiale non è attivato per impostazione predefinita se è disattivato
* [Shader] Se un &quot;param auto&quot; non è corretto, non vengono stampati errori

**Problemi noti:**

* [Mac] Il limite di campioni di texture è bloccato su 16 (problema con il driver della GPU)

### 2.1.1

*(Rilasciato il 1° luglio 2016)*

**Aggiunto:**

* [Licenza] Possibilità di modificare il percorso del file di licenza
* [Finestra vista] Aggiungi una scelta rapida &quot;B&quot; per passare da una mappa all’altra
* [Importazione] Consente di importare correttamente FBX 2016/2017
* [Strumento] Rimuovi i controlli quando si utilizza la maschera veloce
* [Iray] Aggiungere informazioni sulle dimensioni della scena
* [Iray] Consente di aumentare il numero massimo di campioni e il tempo di rendering
* [UI] Aggiorna immediatamente i risultati quando si utilizza il pulsante +/- sui cursori
* [UI] Consente una maggiore precisione per i cursori in scala di grigi
* [Esporta] Non esportare un canale alfa per texture che sono solo RGB
* [Esporta] Aggiorna predefinito di esportazione Dota 2
* [Shelf] Nuovo pattern &quot;Esagono piastrelle&quot;
* [Shelf] Nuovo strumento &quot;Saldatura&quot;
* [Shelf] Filtri di finitura aggiornati per fornire controlli di direzione

**Corretto:**

* [Esportazione] Impossibile esportare file PSD in 8 bit
* [Esportazione] L&#39;esportazione 8K non è disponibile in alcune configurazioni hardware
* [Esporta] La finestra Sketchfab è ritagliata
* [Esporta] Mapping di rugosità errato nel predefinito di esportazione Spec/Gloss
* [UI] La digitazione nei cursori in scala di grigio non funziona più
* [UI] Impossibile inserire filtri negli input di substance (come Generatori)
* [UI] Alcuni cursori hanno comportamenti insoliti
* [UI] Il passaggio DeltaTime +/- per le particelle è troppo grande
* [Iray] Alcuni progetti bloccano l&#39;applicazione quando si passa a Iray
* [Iray] Arresto anomalo durante il rilevamento dell&#39;hardware
* [Strumento] Il colore di anteprima del pennello non è corretto in modalità Maschera
* [Tool] Il selettore di materiali può essere utilizzato con strumenti incompatibili
* [Tool] L’anteprima della proiezione non passa al flusso di lavoro Diffusione con specifiche/lucido
* [Shelf] La modifica dello shader predefinito interrompe le anteprime degli smart mats/smart masks
* [Shelf] Alcuni materiali intelligenti hanno nomi errati
* [Ripiano] Altre forme alfa sono danneggiate e non vengono caricate
* [Finestra della vista] Passare alla modalità &quot;Mappa aggiuntiva&quot; e visualizzare prima &quot;Altro&quot;
* [Viewport] Il viewport torna a &quot;other&quot; quando non esiste una mappa aggiuntiva
* [Crash]&#x200B;[Linux] Il report di arresto anomalo non funziona su Ubuntu (Steam)
* [Crash]&#x200B;[Linux] I collegamenti agli URL Web non funzionano su Ubuntu (Steam)
* [Arresto anomalo]&#x200B;[Windows] Rimuovi &quot;crashwatcher&quot; quando Substance Painter non viene più eseguito
* [Arresto anomalo]&#x200B;[Mac] Il sistema di segnalazione degli arresti anomali non funziona correttamente
* [Arresto anomalo] L’importazione di una trama durante l’importazione di una trama causa di un arresto anomalo
* La scelta rapida per il prelievo del set di texture viene reimpostata su niente dopo un riavvio

### 2.1.0

*(Rilasciato il 2 giugno 2016)*

**Aggiunto:**

* [UDIM] Importa porzioni UDIM da una trama come set di texture
* [Linux] È stato aggiunto il supporto per CentOS 6.6 e Ubuntu 12.4
* [Esportazione] Aggiungi risoluzione 8K (sperimentale)
* [Esporta] Consenti di scegliere la profondità di bit durante l’esportazione
* [Baker] Consenti di eseguire il baking di più set di texture contemporaneamente
* Supporto di monitor ad alta risoluzione (ridimensionamento DPI elevato)
* [Scripting] Impostate la risoluzione e il riempimento personalizzati per texture al momento dell’esportazione
* [Riquadro di visualizzazione] Consente di passare da un set di texture all’altro facendo clic sulla trama (tramite Ctrl+Alt+Clic)
* [Finestra vista] Posizionare il cursore del mouse quando si esegue lo zoom con la rotellina del mouse
* [UI] Aggiorna la visualizzazione predefinita del colore di sfondo e della mappa dell&#39;ambiente
* [UI] Aggiungi descrizioni comandi con nomi originali per i canali utente
* [UI] Modifica il colore di sfondo per i canali che non possono essere rinominati
* [Strumento] Rimuovi i controlli quando si utilizza la maschera veloce
* [Shader] Consente di definire i gruppi per i parametri dello shader e i materiali/le maschere
* [Motore] Ottimizzazione della stampa di piccole dimensioni
* [Stencil] Aggiungi &quot;W&quot; come scelta rapida per attivare/disattivare temporaneamente la maschera
* [Shelf] Aggiungi un pulsante x per cancellare il campo di ricerca
* [Shelf] Caricare l&#39;Alpha con un solo clic
* [Shelf] Nuovo predefinito di esportazione: Vray UDIM, Arnold UDIM, Spec/Gloss da Metal/Rough
* [Scaffale] Nuove alfa: forme geometriche, vene e insegne
* Aggiungi nome e versione nelle proprietà dell&#39;eseguibile Substance Painter

**Corretto:**

* [Substance] Impossibile utilizzare contemporaneamente il canale normale e la mappa aggiuntiva
* [Iray] La rifrazione MDL e l&#39;impostazione assorbimento non funzionano
* [Iray] La scala della scena originale non viene mantenuta
* [Shelf] Il modello Specular/lucidità utilizza uno shader errato
* [Esporta] Il predefinito di esportazione predefinito non esporta alcune mappe (come AO)
* [Riquadro di visualizzazione] Il punto pivot non si aggiorna quando si fa clic al di fuori degli UV nella vista 2D
* [UI] I valori del cursore sono arrotondati
* [UI] A volte quando si modificano i valori dei cursori, lo spazio libero è molto ridotto
* [Nuovo progetto] L’elenco a discesa del modello non è aggiornato correttamente (da 1.x a 2.x)
* [Scripting] Corretto il comportamento al passaggio del mouse sui pulsanti personalizzati
* [Mac] L’annullamento su un progetto vuoto blocca la videocamera

**Problemi noti:**

* Il rapporto sugli arresti anomali non è disponibile su Ubuntu
* Alcuni pulsanti URL potrebbero non funzionare. Consulta le domande frequenti per una soluzione alternativa.

### 2.0.5

*(Rilasciato il 29 aprile 2016)*

**Aggiunto:**

* [Shelf] Modello non pbr, shader ed esportazione predefiniti aggiunti/aggiornati
* [Shelf] Predefinito di esportazione UE4 aggiornato per includere l&#39;Occlusione ambientale

**Corretto:**

* Arresto anomalo all’apertura e al salvataggio di alcuni progetti con risorse danneggiate
* [Finestra vista] Il Wireframe appare interrotto nella vista 2D
* [Shelf] Prestazioni migliorate di alcune mappe dell&#39;ambiente di studio
* [Shelf] Alcune mappe dell&#39;ambiente di studio sono duplicate
* [Ripiano] &quot;Materiale di illuminazione cotto&quot; mancante
* [Shelf] Generatore &quot;Conversione in scala di grigi&quot; mancante

### 2.0.4

*(Rilasciato il 26 aprile 2016)*

**Aggiunto:**

* Migliorare le collisioni di trama e ottimizzare il rendering dei wireframi
* Migliorare le prestazioni e la gestione della memoria con i grandi progetti
* Migliorare la precisione del cursore e i passaggi
* [UI] Aggiorna il motore solo quando si convalida un cursore (non quando si immette un valore)
* [UI] Sposta lo switch Iray in un pulsante dedicato nella barra degli strumenti principale (e modifica la relativa scelta rapida)
* [Tool] Aggiungi impostazione per il comportamento di posizione della sorgente dello strumento Clone
* [Shader] Consente di leggere i colori dei vertici della trama negli shader personalizzati
* [Scripting] Consente di recuperare l’elenco di set di texture, canali e livelli
* [Scripting] Aggiunta di funzioni di supporto (URL del percorso, recupero del percorso di esportazione dal progetto)
* [Mac] Rileva la versione &quot;El Capitan&quot; del sistema operativo Mac nel file di registro

**Corretto:**

* Arresto anomalo dopo la seconda esportazione nel Substance share
* Arresto anomalo durante la copia di un livello tra set di texture con dati maschera rapidi.
* Alcuni progetti hanno un programma di aggiornamento molto lungo che richiede molta memoria
* [Strumento] Arresto anomalo quando si seleziona un predefinito di particella con lo strumento clone/sfumino
* [Baker] Il caricamento dei file FBX richiede troppo tempo per le trame pesanti
* [Viewport] Mapping di ambiente esteso in alcuni computer
* [Finestra vista] Conversione gamma errata dell’alfa del pennello
* L&#39;Alpha [Esporta] viene memorizzato come trasparenza anziché come canale separato con file Tiff.
* [Export] Il canale normale viene sempre esportato come OpenGL
* [Iray] Nomi dei cursori mancanti per le impostazioni Iray
* [Iray] Il rendering viene eseguito con una risoluzione errata su Retina/High DPI
* [Iray] Arresto anomalo durante il ridimensionamento dell’interfaccia in modalità Iray
* [Iray] Enorme rallentamento delle prestazioni durante il rendering a risoluzioni basse
* [Iray] La pausa non funziona (Iray continua a elaborare in background)
* Il canale normale a volte presenta artefatti quadrati neri
* Il canale normale viene invertito dai filtri in scala di grigio
* Il canale normale non si fonde correttamente se la pila ha del canale alfa
* Il progetto viene modificato sul disco quando si apre un progetto, anche se non è stato ancora salvato
* La reimportazione di una trama su alcuni progetti dà prestazioni GPU molto cattive
* L’orientamento del pennello non è corretto quando non si tocca una trama
* Il logo del substance share non è presente nella schermata iniziale

### 2.0.2

*(Rilasciato il 25 marzo 2016)*

**Aggiunto:**

* [Iray] Aggiornate il modello Spec/Gloss e lo shader per garantire la compatibilità con Iray
* [Esporta] Possibilità di esportare le schermate in ArtStation
* [Scripting] Supporto dell&#39;esecuzione dalla directory dei plug-in
* [Scripting] Consenti di &quot;Salva con nome&quot;
* [UI] Consenti di fare doppio clic su un cursore per modificarne il valore
* Sposta il campione della Vela nel Substance share
* Nuovo progetto di esempio: Sphere Preview
* Avvisa gli utenti in caso di conflitto di estensione della shell

**Corretto:**

* Il programma di installazione sovrascrive l&#39;installazione di Substance Painter 1.x
* [UI] Il layout dell&#39;elenco dei canali è interrotto con i filtri
* [UI] I parametri dello shader non vengono visualizzati
* [UI] Quando si ridimensiona la finestra del livello, il contenuto viene ritagliato in modo errato
* [Tool] Il canale di opacità non viene sempre utilizzato correttamente
* [Tool] Sfumino/Clone non funziona con simmetria
* [Tool] L’opacità dell’anteprima del pennello non è corretta in alcuni canali
* [Iray] Arresto anomalo quando si utilizza Iray quando non è ancora stato creato
* [Iray] Impossibile caricare i dati delle impostazioni di iray dal progetto
* [Iray] Iray non si occupa della modifica delle impostazioni dopo una pausa
* [Scaffale] L&#39;importazione di un materiale sullo scaffale non funziona
* Lo stencil non funziona con il canale Normale
* Arresto anomalo quando si dipinge su alcuni progetti
* Arresto anomalo durante il disegno con particelle su alcuni progetti
* Arresto anomalo del processore Pixel durante alcuni calcoli

### 2.0.0

*(Rilasciato il 16 marzo 2016)*

**Aggiunto:**

* Collegamento a Substance Store nella barra degli strumenti principale
* Rendering di immagini con modalità di visualizzazione ed esportazione di schermate
* Supporto per la creazione e l’utilizzo di &quot;Maschere intelligenti&quot;
* Supporto per il flusso di lavoro PBR Specular/lucidi (con nuovo canale di diffusione)
* Concatenamento di Substance (per collegare le sostanze agli input dell&#39;immagine substance)
* Supporto dello scripting con i plug-in personalizzati
* Migliorare la conversione da Height a Normale utilizzando un filtro Sobel
* Passa la risoluzione dell&#39;anteprima Stencil/Proiezione a 2K
* Aggiungere un canale normale per impostazione predefinita per i nuovi progetti
* Lettura del tag dati utente dal nodo di output per abilitare/disabilitare i canali di una sostanza per impostazione predefinita
* Esporre la fusione Normale/AO nelle impostazioni TextureSet
* [Tool] Nuovo strumento Sfumino per fondere e diffondere i colori
* [Strumento] Nuovo strumento Clona per copiare parte delle texture
* [Strumento] Consenti di selezionare i canali per lo strumento Sfumino, Clona e Gomma
* [Livello] Aggiungi nome Substance per nome effetto di riempimento
* [Livello] Consente di esportare la maschera negli Appunti
* [Riquadro di visualizzazione] Consente di passare dalla modalità prospettiva alla modalità ortogonale
* [Riquadro di visualizzazione] Consente di controllare il campo di visualizzazione in modalità prospettiva
* [Finestra vista] Consente di impostare la Profondità della distanza del campo con CTRL+clic centrale
* [Finestra vista] Consente di trascinare e rilasciare le mappe dell&#39;ambiente nella vista 3D.
* [Finestra di visualizzazione] Feedback migliorato quando il motore esegue calcoli complessi
* [Esporta] Consente di esportare i parametri dello shader in un file json
* [UI] Aggiorna l&#39;interfaccia con nuove icone, colori e layout
* [UI] Aggiungi i nomi delle risorse ai mini scaffali
* [UI] Comprimi &quot;Mappatura canali&quot; per impostazione predefinita
* [Shader] Scegliete un colore personale per i parametri della texture dello shader
* [Shelf] Chiedi dove importare i file quando trascini le risorse
* [Shelf] Nuova sfera di anteprima per materiali intelligenti e generatori
* [Shelf] Aggiungi shader Specular lucidità
* [Shelf] Nuove forme superficie rigida
* [Ripiano] Nuovi Alpha di texture e forme
* [Shelf] Nuove texture incarnato
* [Shelf] Nuovi materiali basati su scansione e materiali intelligenti
* [Shelf] Nuovi materiali intelligenti e supporto di specifiche/lucidità dei vecchi
* [Shelf] Nuovi filtri di finitura per simulazione di superficie metallica
* [Shelf] Nuovo potente generatore di maschere &quot;Mask Editor&quot;
* [Scaffale] Vecchi materiali rilavorati e puliti
* Nuovo progetto di esempio &quot;Vela&quot;

**Corretto:**

* [Impostazioni] La rotazione della videocamera e la velocità dello zoom vengono sostituite dal progetto
* [Finestra vista] Un problema di precisione nella texture normale predefinita genera riflessi errati
* [Finestra vista] La vignettatura è attivata per impostazione predefinita
* [Viewport] Gli artefatti vengono visualizzati ai bordi della mappa dell&#39;ambiente (GPU Nvidia)
* [Viewport] La miniatura in modalità di proiezione/stencil è molto lunga da caricare
* [Baker] Memorizza le texture cotte in un numero intero di 16 bit anziché di 32 bit
* [Livello] Le sostanze obsolete vengono visualizzate in modo errato nella pila
* Il colore e la profondità di bit predefiniti per alcuni canali non sono corretti (ad esempio: Specular, lucidità)
* È stato corretto il comportamento della gomma per disabilitare la fusione in modalità passthrough.

**Problemi noti:**

* La simmetria non funziona con lo strumento Sfumino e Clona
* Esportazione ArtStation mancante

## Versione 1

### 1.7.3

*(Rilasciato il 1° marzo 2016)*

**Aggiunto:**

* [Esporta] Aggiungi un’opzione per disabilitare il riempimento
* [Shelf] Supporta la gerarchia di scaffali secondari all&#39;interno di una cartella di scaffali

**Corretto:**

* Arresto anomalo durante il salvataggio su un file di sola lettura precedente
* Arresto anomalo all’apertura di un secondo progetto
* Arresto anomalo durante il caricamento di alcune miniature (shelf, livelli o descrizioni comandi)
* La disattivazione di &quot;Mantieni posizioni dei tratti sulla trama&quot; non funziona
* [Export] L’ingrandimento delle bitmap viene eseguito con il filtro più vicino
* [Shelf] L&#39;individuazione delle risorse è molto lenta
* [Shelf] I filtri Sfocatura non sono compatibili con 16 bit
* [Strumento] La simmetria non funziona se caricate un vecchio strumento predefinito
* La finestra di dialogo Colore per il canale Specular non esegue una conversione dello spazio colore

### 1.7.2

*(Rilasciato il 13 gennaio 2016)*

**Aggiunto:**

* [Livelli] Consente di specificare la lavorazione predefinita per i livelli di riempimento

**Corretto:**

* [Esporta] L&#39;esportazione Sketchfab non funziona più
* [Livello] Il filtro bilineare viene applicato anche a Riempimento senza alcuna trasformazione
* [Tool] Prestazioni mediocri con l’utilizzo di substance con input di immagine in modalità di proiezione
* [Tool] Il selettore del materiale è interrotto

### 1.7.1

*(Rilasciato il 18 dicembre 2015)*

**Corretto:**

* Arresto anomalo quando si cambia set di texture
* Prestazioni rallentate durante la pittura

### 1.7.0

*(Rilasciato il 17 dicembre 2015)*

**Aggiunto:**

* [Prestazioni] Calcola contemporaneamente il contenuto dei livelli e le relative miniature
* [Export] Salva il percorso di esportazione come relativo quando è accanto al progetto
* [Layers] Aggiunto un nuovo metodo di fusione : Sottrai e Aggiungi/Sottometti
* [Layers] Nuovo filtro HQ bilineare per i livelli di riempimento
* [Shader] Impostate uno shader predefinito per la generazione delle miniature nelle preferenze.
* [Shader] Consente di specificare uno shader per set di texture
* [Shader] Consente di campionare le texture dallo scaffale
* [Strumento] Nuovo comportamento del pennello &quot;a capo&quot; per la pittura
* [Tool] Miglioramento del filtro e riduzione dell’aliasing durante la pittura
* [Tool] Qualità di pittura dei sottopixel migliorata
* [Tool] Rimosso il display &quot;basic&quot; per le impostazioni del pennello e migliorata l’icona di apertura/chiusura del fotogramma
* [Menu] Aggiungere icone degli effetti nel menu di scelta rapida
* Creazione di modelli da progetti
* [Shelf] Nuovi modelli : PBR, Dota 2
* [Shelf] Nuovo predefinito di esportazione : Dota 2
* [Shelf] Nuovi shader : Dota 2, PBR Vernice per auto, PBR rivestito, Velluto PBR
* [Scaffale] Nuovo materiale: ruggine e usura in acciaio, illuminazione stilizzata
* [Shelf] Nuovi filtri : Sfocatura direzione, illuminazione stilizzata
* [Shelf] Nuovo pennello : predefinito morbido e predefinito rigido con un nuovo alfa per un migliore controllo della durezza
* [Shelf] Nuovi generatori : 3D Distanza e Luce
* [Ripiano] Pennelli aggiornati con proiezione a capo e taglio del carattere di sfondo (attivato per impostazione predefinita)
* [Shelf] Rumore bianco aggiornato con la versione del processore pixel per un calcolo più veloce

**Corretto:**

* [Schermata introduttiva] Tutorials collegamento invia a vecchi video
* [Canali] Dicendo &quot;no&quot; per riempire la creazione del livello con AO si crea ancora il livello
* [Canali] I nomi dei canali UserX non si propagano nell’interfaccia
* [Finestra della vista] La voce Maschera è vuota nell’elenco dei canali singoli
* [Condividi] L’esportazione di un file alfa per la condivisione da SP crea un file .image illeggibile
* [Licenza] Correggere l&#39;attivazione per i nomi utente con caratteri non ASCII
* [Shader] La finestra di dialogo dei parametri colore scompare quando si sceglie un colore
* [Shelf] Le miniature non vengono scaricate dalla memoria se non utilizzate
* [Ripiano] Filtro sfumatura fissa
* [Strumento] La simmetria non funziona con stencil/proiezione
* [Strumento] Nome errato durante la creazione di un nuovo pennello predefinito
* L’impostazione Mantieni tratto rimane disattivata anche durante la reimportazione di una trama
* Reimpostazione del driver (TDR) quando si calcolano particelle di grandi dimensioni.

### 1.6.1

*(Rilasciato il 9 novembre 2015)*

**Corretto:**

* Arresto anomalo all’apertura di un progetto se è visibile la vista 2D
* Arresto anomalo durante la creazione di un nuovo predefinito di esportazione se lo scaffale corrente non esiste
* [Tool] L’icona del selettore di materiali può rimanere visualizzata
* [Strumento] Il selettore materiale nasconde il cursore del mouse quando si disegna allo stesso tempo
* [Shelf] I metadati vengono scritti sul disco dopo ogni uscita

### 1.6.0

*(Rilasciato il 29 ottobre 2015)*

**Aggiunto:**

* Supporto ufficiale per Windows 10
* [Substance] Comprimi gruppi di parametri della sostanza per impostazione predefinita
* [Substance] Aggiungere un nuovo framework (migliorare le prestazioni del processore pixel)
* [Finestra vista] Consente di disattivare la visualizzazione del piano di simmetria in modalità simmetria.
* [Finestra di visualizzazione] Migliorare il rendering e le prestazioni delle ombre
* [Finestra vista] Mette in pausa il calcolo dell’ombra durante il disegno
* [Finestra di visualizzazione] Miglioramento delle prestazioni di rendering dei wireframi
* [Engine] Miglioramento della gestione della memoria Vram per ridurre l&#39;ingombro
* [Engine] Migliora l&#39;aggiornamento delle texture sulle GPU AMD per prestazioni migliori
* [Engine] Disattiva l’impostazione di ottimizzazione concatenata sulle GPU NVIDIA per prestazioni migliori
* [Effect] Aggiungi un tag per richiedere l&#39;input di un&#39;immagine &quot;imbottita&quot;
* [Livello] Aumenta la precisione dell’Offset UV/scala nel riempimento
* [Layer] Rendi il cursore della scala esponenziale nel riempimento
* [Livello] Consente di trascinare e rilasciare i materiali direttamente nella pila di livelli.
* [Livello] Consente di trascinare i filtri direttamente nella pila di livelli
* [Livello] Regola il colore del pennello maschera sul colore maschera appena creato
* [Shader] Esporre più parole chiave
* [Shader] Funzione di esposizione gamma/tonemapping per consentire funzioni personalizzate
* [Bakers] Modificare le impostazioni predefinite di Position Baker per l&#39;utilizzo triplo
* [Tool] Rinomina &quot;Geometry Decal&quot; in &quot;Polygon Fill&quot;
* [Shelf] Aggiornare i generatori per supportare TriPlanar : MG Metal edge usura, MG Mask builder, MG Fibre di vetro, MG Dirt
* [Shelf] Aggiorna i materiali con le nuove impostazioni e i materiali non utilizzati rimossi
* [Scaffale] 22 Nuovi materiali intelligenti (plastica, ferro, tessuto, acciaio e altro)
* [Shelf] Aggiorna i filtri Nitidezza, Sfocatura e Altera con l&#39;input dell&#39;immagine imbottita per evitare giunture
* [Shelf] Migliorare le impostazioni di Alterazione per un utilizzo più semplice
* [Shelf] 2 Nuovi rumori procedurali : 3D Perlin e 3D Worley

**Corretto:**

* [Engine] Il rilevamento della quantità di Vram per la GPU dedicata non è corretto su Mac
* [Engine] Le texture diventano una versione più scura nella finestra della vista
* [Motore] Prestazioni insoddisfacenti quando si disegna al di sotto di più livelli
* [Engine] I livelli calcolati all’apertura del progetto sono diversi dalla versione memorizzata nella cache
* [Substance] Risultati errati in 4K su Mac
* [Substance] I parametri sono nell&#39;ordine errato
* [Shader] Gli shader Toon e Pixelated sono completamente neri
* [Shader] I parametri scompaiono dopo aver modificato env-map
* [Shelf] Arresto anomalo durante l&#39;inserimento di file png nella cartella generator
* [Shelf] Le miniature vengono generate con una bassa rugosità
* [Strumento] Arresto anomalo quando si utilizza una bitmap nel pennello alfa su Windows
* [Esporta] Un predefinito di esportazione mappa aggiuntivo ora esporta una mappa RGB per Posizione

### 1.5.7

*(Rilasciato il 24 settembre 2015)*

**Corretto:**

* Il rapporto sugli arresti anomali non funziona più

### 1.5.6

*(Rilasciato il 21 settembre 2015)*

**Aggiunto:**

* [Shelf] Migliorare la qualità di rendering delle miniature (utilizzare texture 1K)

**Corretto:**

* [Condividi] Impossibile firmare con un altro account
* [Shelf] Le miniature sono troppo pesanti sul disco
* [Shelf] I materiali intelligenti sono molto lenti da caricare
* [Windows] Correggere l&#39;installazione del servizio licenze
* [Canali] La mappa di trasmissione viene creata come G8 per impostazione predefinita

### 1.5.5

*(Rilasciato il 15 settembre 2015)*

**Aggiunto:**

* [Shelf] Esportare risorse in Substance share
* [Shelf] Aggiungi nuova anteprima sfera per Materiali
* [Shelf] Utilizza la mappa di invidiabilità &quot;Glazed patio&quot; per generare le miniature
* [Shelf] Aumenta la risoluzione delle dimensioni delle miniature a 512x512 pixel
* [Vista 3D] Esposizione del valore di rotazione dell&#39;ambiente
* [Windows] Firma l’applicazione

**Corretto:**

* [Panettieri] Risultati errati durante la cottura di mappe allo stesso tempo
* [Vista 3D] La mappa di invidiabilità viene visualizzata quando non è aperto alcun progetto
* [Livelli] I generatori di maschere non funzionano sul contenuto del livello
* [Livelli] Potete disegnare su livelli nascosti
* [Shelf] Il rumore di Dirt\_5 e di Dirt\_6 sono identici
* [Shelf] Alcuni generatori di maschere sono pixelati o di bassa qualità
* [Tool] Rotazione del gizmo errata su alcuni angoli.
* [Tool] Troppi canali causano il ritaglio dei pulsanti dei canali
* [Strumento] La scelta rapida Inverti maschera per Maschera rapida non funziona
* [Esporta] Sketchfab: il pulsante Annulla non è stato considerato correttamente
* [Licenza] Attivazione non riuscita quando non è possibile copiare la licenza
* Il limitatore di cadenza fotogrammi non funziona più nell&#39;interfaccia utente

### 1.5.0

*(Rilasciato il 20 agosto 2015)*

<b>Aggiunto:</b>

* [Shader] Aggiungi il numero di riga in Shader per la compilazione dei messaggi di errore
* [Shelf] Migliorare la qualità delle anteprime delle miniature
* [Shelf] Generazione automatizzata di miniature per Smart Materials
* [Tool] Scelta rapida per controllare l&#39;impostazione della durezza nella sostanza
* [Strumento] Usa widget in scala di grigio per decalcomanie geometriche quando si sovrappone una maschera
* [Strumento] Scelta rapida per invertire il colore del disegno su una mappa in scala di grigio
* [Finestra vista] Consente di visualizzare il wireframe e di modificarne il colore
* [Riquadro di visualizzazione] Sfocatura dello sfondo dell’ambiente
* [Controls] Aggiungi rotazione alle scelte rapide del mouse per il pennello
* [Esporta] Esporta in Sketchfab
* [Esporta] Creare predefiniti di esportazione per i moduli di rendering
* [Esporta] Aggiungi riflessione mappa convertita, F0 e 1/IOR
* [UI] Aggiungi schermata introduttiva
* [UI] Aggiorna layout predefinito
* [UI] Aggiungi descrizioni comandi mancanti e rinomina una voce di menu
* [Livelli] Esporta la maschera attualmente selezionata come bitmap
* [Layers] Aggiungi l’azione &quot;inverti maschera&quot; nel menu di scelta rapida

<b>Corretto:</b>

* [Progetto] Se i perni mesh sono diversi in FBX, le mesh vengono esplose durante l&#39;importazione
* [Substance] Le Substance utilizzate negli strumenti di proiezione sono bloccate in 256\*256
* [Livelli] Arresto anomalo quando si utilizza Cancella maschera
* [Esporta] Conversione gamma errata su texture molto scure
* [Esporta] La mappa di posizione può essere utilizzata solo nei predefiniti di esportazione come mappa in scala di grigio
* [Strumento] Il colore iniziale della decalcomania Geometria è nero se utilizzato su una maschera
* [Strumento] La scelta rapida per la rotazione non funziona se non è presente durezza nell&#39;alfa

### 1.4.2

*(Rilasciato il 15 luglio 2015)*

**Corretto:**

* [Tool] Arresto anomalo quando si utilizza la decalcomania geometrica con la maschera veloce
* L’aggiornamento del progetto da 1.4.0 a 1.4.1 utilizza tutta la memoria del computer
* Importazione del vecchio formato di progetto non corretta
* Gli scaffali personalizzati analizzano l&#39;intera gerarchia e duplicano le risorse ovunque

### 1.4.1

*(Rilasciato il 23 giugno 2015)*

**Aggiunto:**

* [Finestra vista] Consente di ancorare i pannelli uno accanto all’altro
* [Effetto] Aggiungete uno sfondo e un righello per l’effetto livello
* [Effetto] Aggiungi un effetto Disegno che consenta di lavorare su altri effetti

**Corretto:**

* [Shelf] La generazione delle miniature è interrotta se non è aperto alcun progetto
* [Shelf] Impossibile generare l&#39;anteprima del materiale predefinito
* [Shelf] Le anteprime dei materiali vengono generate su una trama con normali invertite
* [Shelf] Le miniature vengono sempre ricalcolate a causa di una funzione hash errata
* [Ripiano] Facendo clic su un materiale di una sostanza non si collegano mappe aggiuntive
* [Strumento] Valore non corretto campionato con il selettore Materiale
* [Strumento] Selettore colore seleziona il colore del cursore della finestra della vista
* [Vista 2D] Velocità fotogrammi/prestazioni molto basse
* [Esporta] Arresto anomalo quando si apre la finestra di esportazione con predefiniti di esportazione troppo recenti.
* [Esporta] Il canale di Height nella mappa Normale viene convertito nello spazio errato
* [Mac] BaseColor dagli effetti substance viene visualizzato come Lineare
* [Mac] Il widget Linee rette è stato disegnato in modo errato su Retina
* Le linee rette possono rimanere attivate anche con la scelta rapida rilasciata.
* Le linee rette del guizmo scompaiono dopo aver ruotato la mappa dell&#39;ambiente
* Gli output delle occlusioni ambientali da sostanze non vengono collegati automaticamente al canale AO
* Risolvere il problema di copia della licenza su Windows con carattere speciale nel nome utente

### 1.4.0

*(Rilasciato il 10 giugno 2015)*

**Aggiunto:**

* [Esporta] Aggiungi mappe aggiuntive nell&#39;elenco delle mappe di input disponibili
* [Shelf] Utilizza i materiali sbsar come materiali predefiniti
* [Shelf] Consenti l&#39;utilizzo di percorsi libreria personalizzati
* [Shelf] Modificare le dimensioni minime
* [Shelf] Nuovo contenuto : 20 nuovi materiali intelligenti
* [Scaffale] Nuovo contenuto : nuova sostanza procedurale (tessitura, trama)
* [Shelf] Filtro Sfocatura aggiornato
* Disegnare linee rette utilizzando un tasto modificatore
* Aggiungere il canale di Occlusione ambiente e rielaborare il comportamento AO/Normale nella pila di livelli
* Lettura del colore predefinito da Input immagine definito in Substance dati utente
* Consente di esportare il registro dal menu Aiuto

**Corretto:**

* [Baker]&#x200B;[Mac] Arresto anomalo con Normale da Baker mesh
* [Baker] Arresto anomalo se nel file della gabbia non sono presenti UV
* [Baker] La corrispondenza per nomi non funziona con gli oggetti esportati da zBrush
* [Baker] La cottura con gabbia sovrascrive la cottura se si utilizzano più set di texture e UV sovrapposti
* [Baker] File OBJ specifici producono texture nere
* [Shelf] Impossibile leggere le risorse se impostato su sola lettura
* [Shelf] I file delle risorse vengono scritti in Painter se sono stati utilizzati nel progetto.
* [Ripiano] Il ricaricamento delle sostanze aggiorna anche lo strato
* [Esportazione] Tiff esporta immagini a 32 bit che non possono essere lette correttamente da Photoshop o motori grafici
* [Esporta] Il predefinito dei canali predefiniti esporta sempre come RGB
* [Material] Sovrascrivi canale diffuso mappatura BaseColor con sostanze
* [Vista 3D] Illuminazione diffusa errata con mappe di ambiente specifiche
* [Strumento] Impossibile ruotare un pennello in un angolo specifico
* Il riquadro di visualizzazione diventa attivo quando si passa il cursore del mouse mentre si digita in un campo di testo
* Arresto anomalo con predefiniti troppo recenti per la versione corrente dello scaffale
* Arresto anomalo dopo la sostituzione della trama
* Arresto anomalo durante il ricaricamento di una sostanza con un numero diverso di input
* Trame FBX da Cinema4D importate con nomi di materiale errati

### 1.3.5

*(Rilasciato il 29 maggio 2015)*

**Aggiunto:**

* [Licenza] Problema di attivazione quando è presente un file di licenza esistente
* [Mac] Arresto anomalo durante il caricamento di file FBX specifici
* [Mac]&#x200B;[Vista 3D] Riflesso errato per la GPU integrata
* [Vista 3D] Il font Maschera veloce è interrotto
* [Vista 3D] Il selettore di materiali rende la finestra della vista completamente nera
* Arresto anomalo dopo l’apertura dei progetti creati nella versione 1.3.3
* L&#39;anteprima del materiale è vuota quando si utilizzano ombreggiature con canale alfa
* Il disegno smette di funzionare su trame specifiche
* Le prestazioni diminuiscono notevolmente con trame OBJ specifiche
* I canali utente non sono mappati quando si utilizzano gli effetti
* Le cartelle temporanee non vengono pulite all&#39;avvio

**Corretto:**

* Miglioramenti dei tempi di calcolo nel progetto estremamente lungo da caricare
* Modificare la finestra &quot;Risoluzione dei problemi GPU&quot; per renderla più comprensibile
* [Livelli] Salva lo stato del blocco delle proporzioni per i livelli di riempimento e attivalo per impostazione predefinita
* [Panettieri] La corrispondenza per nome ora utilizza il suffisso come separatore

### 1.3.4

*(Rilasciato il 27 aprile 2015)*

**Aggiunto:**

* [Mac] Arresto anomalo con Mac OS X Yosemite (10.10)
* [Mac] Impossibile uscire dalla modalità a schermo intero
* [Panettieri] L’opzione Baking Match by name non funziona
* [Bakers] Lo spazio tangente Mikk utilizzato in SP non funziona con UE4
* [Panettieri] Il fornaio di ID non può cuocere i colori ID del materiale
* [Vista 2D] Il Wireframe non viene visualizzato quando si utilizza lo strumento decalcomania Geometria
* [Strumento] Il canale alfa del pennello viene visualizzato come controllo anziché come trasparenza con i materiali
* [Tool] Arresto anomalo con decalcomania geometrica
* [Livelli] Lo slot del materiale è compresso per impostazione predefinita sul livello di riempimento
* [Esporta] Arresto anomalo durante l’esportazione con dimensioni superiori alla risoluzione impostata per la texture
* Canale Specular non riconosciuto nei filtri.
* Clean + save non toglie correttamente le risorse dall&#39;archivio delle specie
* Non memorizzare la trasformazione low-poly nel file assbin high-poly
* Il file FBX viene importato con troppi set di texture

**Corretto:**

* Effetti: Blocco livelli dovrebbe essere attivato per impostazione predefinita per simulare i livelli &quot;classici&quot;
* Livelli: modificare il livello minimo e massimo di fresatura nell’azione Riempi
* Livelli: salvare e ripristinare lo stato della pila
* Panettieri: AO Baker tiene conto della mappa normale se non viene specificato HP
* Panettieri: aggiunte descrizioni e informazioni aggiuntive nella finestra di cottura
* Creare un file di backup durante il salvataggio di un progetto

### 1.3.3

*(Rilasciato: 01 aprile 2015)*

**Aggiunto:**

* Aggiungere la versione del software e il nome del progetto nella barra del titolo
* Rimuovi informazioni riservate dai nomi dei set di texture e dei materiali avanzati
* Aggiornamento del motore di Substance alla versione 5
* [Shelf] Aggiungi nuove mappe dell&#39;ambiente: spiaggia di Corsica, studio 05, studio di Tornoco e altro
* [Shelf] Aggiorna MG Mask Builder con i nuovi parametri
* [Shelf] Aggiorna e calibra le mappe dell&#39;ambiente precedente

**Corretto:**

* Arresto anomalo all’apertura della finestra di esportazione
* Impossibile trascinare il widget dell&#39;interfaccia utente quando non è ancorato
* &quot;Ricerca aggiornamenti&quot; non funziona
* [Livelli] Non selezionare la maschera quando si fa clic su di essa tenendo premuto ALT
* [Tool] Il triplo non funziona con il canale Normale
* [Vista 3D] L&#39;illuminazione diffusa dalla mappa env non è corretta
* [Vista 3D] Il calcolo dell&#39;esposizione è diverso da Designer
* [Vista 3D] Le ombre non devono essere visibili su una superficie metallica al 100%
* [Vista 3D] La trama con UV specchiati ha capovolto tangente/binomio
* [Vista 3D] Le ombre producono risultati errati su determinate trame
* [Bakers] Rimuovi la cartella &quot;.alg\_meta&quot; creata dai file assbin
* [Bakers] Arresto anomalo durante la cottura se Painter ricalcola contemporaneamente un TextureSet
* [Mac] Problema di interfaccia utente del riquadro bianco all’avvio dell’applicazione

### 1.3.2

*(Rilasciato il 6 marzo 2015)*

**Corretto:**

* [Vista 3D] Impossibile ricaricare una mappa INVIV salvata con il progetto

### 1.3.1

*(Rilasciato il 5 marzo 2015)*

**Aggiunto:**

* [Bakers] Aggiungi una versione memorizzata nella cache di mesh high-poly per accelerare il calcolo
* [Pannelli] Se non è caricata alcuna trama ad alto poli, aggiungi un’icona di avvertenza
* [Pannelli] Se non viene caricata alcuna trama ad alto poli, utilizza invece la trama del progetto

**Corretto:**

* [Pannelli] Premendo &quot;Invio&quot; quando si modifica il valore di un cursore si chiude la finestra
* [Pannelli] Anche l’attivazione/disattivazione di un panettiere attiva il pulsante
* [Panettieri] Impossibile cuocere se si utilizza il pulsante &quot;tutto/nessuno&quot;
* [Panettieri] L&#39;ordinamento dei pulsanti non è corretto
* [Panettieri] La casella di controllo viene ignorata e tutti i panettieri vengono sempre elaborati
* [Panifici] Stato barra di avanzamento corretto

### 1.3.0

*(Rilasciato il 4 marzo 2015)*

**Aggiunto:**

* [Bakers]&#x200B;[Vista 3D] Usa calcolo spazio tangente Mikkt se non vengono trovate tangenti/binormali
* [Panettieri] Aggiunti nuovi panettieri : Normale, ID, Occlusione, Curvatura, Thickness, Posizione
* [Effetti] La serie di effetti è ora invertita e visualizzata dall’alto verso il basso (come i livelli)
* [Effects] Aggiungere nuove icone alla serie di effetti
* [Effetti] Aggiungi metodo di fusione tra le azioni di riempimento nella pila degli effetti
* [Effetti] Rinominare gli effetti (effetto sostanza = filtro, ecc.)
* Aggiungere un file &quot;lock&quot; durante il processo di salvataggio
* [Effects] Aggiungi azione Riempimento nella serie di effetti
* Aggiunta nuova risorsa: materiali avanzati
* [Livelli] Consente di riordinare gli effetti di livello
* [Tool] Aggiungi proiezione triplanare
* [Vista 3D] Aggiungere il supporto per le ombre
* [Vista 3D] Possibilità di impostare gli stati OpenGL richiesti in shader personalizzati
* [Vista 3D] Supporto per alfa tramite nuovi shader
* [Vista 3D] Gli ombreggiatori sono ora provvisti di versione e completamente salvati in un progetto
* [Vista 3D] Avvisa l&#39;utente se lo shader non viene più compilato

**Corretto:**

* [Livelli] correggi l’inserimento in una cartella compressa
* [Shelf] Correggere il filtraggio dei contenuti nei mini-shelf
* [Shelf] Rinominare le categorie e riorganizzare le schede

### 1.2.1

*(Rilasciato il 12 febbraio 2015)*

**Aggiunto:**

* I file \*.spp possono ora essere aperti con un doppio clic in Esplora risorse
* [Esporta] Nuovo tag &quot;$project&quot; per i predefiniti di esportazione
* [Esporta] Aggiungete un elenco di mappe (con nomenclatura) sotto ogni set di texture
* [Esporta] Aggiungi un pulsante Tutto/Nessuno per selezionare i set di texture
* [Esporta] Le mappe vuote vengono eliminate durante l’esportazione

**Corretto:**

* [Esporta] I predefiniti Unity5 hanno mappe invertite
* [Esportazione] L’aggiunta di una barra in avanti nel nome di un predefinito crea una cartella danneggiata
* [Esportazione] Il canale di Height esportato in formati a 32 bit viene bloccato in modo errato
* [Esporta] L’elenco dei set di texture non è ordinato come nel progetto
* [Tool] L’eliminazione dei volti sullo sfondo non funziona più
* Il comando Salva non funziona con i caratteri speciali nel tracciato

### 1.2.0

*(Rilasciato il 28 gennaio 2015)*

**Aggiunto:**

* Nuovo canale Normale per colorare i dati delle mappe normali e combinare i risultati
* [Export] Nuova finestra di esportazione con la possibilità di creare impacchettamenti personalizzati e impostare nomi personalizzati
* Il formato del file di progetto ora è un singolo file anziché delle cartelle
* [Esportazione] Supporto di diversi formati normali (DirectX, OpenGL)
* [Export] Crea un file &quot;lock&quot; temporaneo durante l’esportazione
* [Livelli] Per alternare una maschera è possibile utilizzare Maiusc+clic sinistro del mouse
* [Parametri] Esporre lo spazio colore nella parte inferiore dell’input di un’immagine
* [Shelf] L&#39;effetto &quot;MG Mask Builder&quot; ha ora nuove impostazioni
* [Vista 3D] La mappa dell&#39;Occlusione ambientale ora oscura il contributo diffuso, non lo specular

**Corretto:**

* L&#39;anteprima del materiale di proiezione/stencil non viene visualizzata correttamente nella finestra della vista
* [Vista 3D] Descrizione comando scelta rapida non visualizzata quando si utilizza la scelta rapida &quot;S&quot; (stencil)
* [Shelf] L&#39;effetto &quot;MatFx Skin Scale&quot; offre ora prestazioni migliori a bassa risoluzione
* [Esportazione] Le texture esportate vengono solo ingrandite quando si specifica un documento di dimensioni maggiori

### 1.1.2

*(Rilasciato il 15 gennaio 2015)*

**Aggiunto:**

* Aggiunte: nuove impostazioni Trasla, Ruota e Scala nel livello Riempimento
* Filtro ottimizzato per pennelli e livelli di riempimento
* La versione di prova è ora completamente disponibile (può essere esportata) ma è limitata nel tempo.

**Corretto:**

* Impossibile importare mesh OBJ con precisione molto piccola
* Problema durante l&#39;attivazione di una licenza su Windows 7 e 8
* Arresto anomalo durante il salvataggio con nome di un progetto
* Arresto anomalo quando si elimina l’ultimo canale di un set di texture
* Arresto anomalo quando si elimina un livello in un contesto specifico

### 1.1.1

*(Rilasciato il 25 dicembre 2014)*

**Aggiunto:**

* [Livello] Seleziona il livello in alto quando si apre un progetto o si cambia set di texture
* Velocità di salvataggio e salvataggio con nome migliorate con il nuovo algoritmo di compressione
* Visualizzare un errore en durante l’apertura di un progetto troppo recente per Painter

**Corretto:**

* [Strumento] La decalcomania della geometria genera danni alla memoria
* [Pennello] Impossibile inserire manualmente valori mobili inferiori a 1 per la dimensione del pennello
* [Livello] La creazione di un effetto di selezione colore non lo aggiunge nella pila dei livelli
* [Livello] Quando si sposta il mouse sui livelli, Painter scorre rapidamente nella barra delle applicazioni
* [Livello] L’aggiunta di una bitmap come maschera può provocare un arresto anomalo
* La GUI per la modalità Solo con il canale del Height non è corretta
* &quot;Salva progetto&quot; può non riuscire e danneggiare un progetto
* Arresto anomalo quando si apre un progetto dopo averne caricato un altro con uno shader obsoleto

### 1.1.0

*(Rilasciato il 16 dicembre 2014)*

**Aggiunto:**

* [Effetto] Nuovo creatore maschera ID materiale
* Nuova linea bianca/nera punteggiata per il gizmo del pennello
* Nuovo parametro segui angolo
* Nuovo parametro di taglio backface
* Nuovo parametro per il mouse Lazy
* [Livelli] Supporto per più selezioni e gestione
* [Livelli] Copiare e incollare da un set di texture all’altro
* [Esporta] Formato PSD di Adobe Photoshop
* [Scaffale] Nuovo strumento: pelliccia, punti metallici e cerniera
* [Ripiano] Nuovo pennello : stampo, matita, linea affilata e punto
* [Ripiano] Nuovo alfa: disturbo gaussiano, linea affilata, stampo, penna, schizzo, punto, cerniera
* Le prestazioni di pittura sono migliorate aggiornando solo le parti delle texture necessarie

**Corretto:**

* [Scaffale] Impossibile caricare una sostanza con un grafico con etichette identiche
* [Livelli] Il metodo di fusione Attraversa non funziona con le maschere
* [Stencil] La scala non funziona nella vista 2D
* Problemi e arresto anomalo su Mac OS Yosemite

### 1.0.2

*(Rilasciato il 9 novembre 2014)*

**Aggiunto:**

* Prestazioni migliorate nell’anteprima del materiale con le sostanze
* Prestazioni migliorate con l’anteprima del tratto pennello durante l’aggiornamento del documento
* Prestazioni migliorate nella finestra della vista con una frequenza di aggiornamento inferiore per l’area non di lavoro
* [Post Effects] Interfaccia utente migliorata per la gestione delle impostazioni
* [Post Effects] Ripristina i valori predefiniti
* Substance effetti e operazioni sui livelli nel menu di scelta rapida
* Supporto per input/output premoltiplicato nelle sostanze

**Corretto:**

* [Vista 3D] I parametri shader personalizzati sono separati da uno spazio grande
* [Esporta] Conversione sRGB mancante per il predefinito Unity4
* Possibile arresto anomalo durante il caricamento di trame fbx
* A volte si verificano arresti anomali durante il caricamento di semplici trame obj
* La barra di elaborazione rimane bloccata al 100% durante il caricamento
* Quando si ricarica una sostanza, la si inserisce in ogni categoria
* Switch DirectX/OpenGL interrotto

### 1.0.1

*(Rilasciato il 27 ottobre 2014)*

**Aggiunto:**

* [Tool] Utilizzo dei parametri del materiale migliorato
* Nuovo collegamento al sito Web di UserVoice nel menu?
* Vari miglioramenti delle prestazioni del motore

**Corretto:**

* I valori dei parametri sono limitati a 2 decimali per Particelle
* La Substance caricata dalla cache non viene visualizzata nell’interfaccia utente come obsoleta
* Arresto anomalo durante il caricamento di una trama da un URL di rete
* Painter è ora riconosciuto come firmato su Mac OS X

### 1.0.0

*(Rilasciato il 15 ottobre 2014)*

**Aggiunto:**

* Supporto shader personalizzato
* Supporto della risoluzione 4k
* Progetti carattere di esempio
* Visualizza barra di avanzamento per lunghi tempi di calcolo
* [Esporta] Aggiungere una passata di dilatazione prima del postprocesso di diffusione
* Argomenti della riga di comando in SP per operazioni semplici
* Nuovi materiali ed effetti
* Anteprima strumento (anteprima del materiale in tempo reale separata e area di prova del tratto)
* Non creare un documento predefinito all&#39;avvio di Painter
* [Strumento] Aggiungete la possibilità di modificare manualmente un valore in scala di grigio
* Vari miglioramenti per gli stencil (Aggancia, Reimposta)
* Le particelle sono ora dei sottostrumenti degli strumenti Pennello artistico, Gomma e Proiezione
* [Vista 3D] Usa l’audio caricato al forno nel rendering della finestra della vista
* Dividere i controlli degli stencil tra la vista 2D e 3D
* Modifiche di piccole dimensioni del pollice nella libreria
* I campi di ricerca sono specifici di ogni finestra
* Interfaccia utente modificata

**Corretto:**

* [Substance] L&#39;opzione non funziona
* [Finestra di dialogo Colore] Sfumatura tonalità non aggiornata
* Impossibile aggiornare una trama se il nome del file è identico
* Lo strumento non è visibile nelle visualizzazioni quando è troppo piccolo
* Lo strumento decalcomania sullo schermo Retina non funziona correttamente
* [Substance] Int1 viene visualizzato come float1
* [Substance] input/output basecolor non riconosciuti
* Impossibile ricaricare i filtri di [Substance]
* [Tool] il widget della scala di grigi è sempre compresso

## Beta

### 0.12.1-beta

*(Rilasciato il 18 settembre 2014)*

**Aggiunto:**

* Predefinito di esportazione Unity 5

**Corretto:**

* PBR Shader, la qualità del rendering dovrebbe migliorare notevolmente
* La funzione di messa a fuoco è interrotta e le trame vengono ritagliate per impostazione predefinita

### 0.12.0-beta

*(Rilasciato il 17 settembre 2014)*

**Aggiunto:**

* Strumento Contagocce
* Opzione &quot;Mantieni posizione tratto&quot; aggiunta alla reimportazione della trama per quando il rettangolo di selezione cambia.
* Mappa normale per trama predefinita Cymourai
* Migliorare l&#39;interfaccia della vista strumenti (i colori sono wip)
* Spostare il menu &quot;Aiuto->Impostazioni&quot; in &quot;Modifica->Impostazioni&quot;
* Salvare il percorso di esportazione nella finestra &quot;Esporta tutti i canali&quot;
* Interfaccia grafica dei nuovi livelli con visualizzazione dell&#39;istogramma
* Migliore gestione delle risorse (trascinamento, ricaricamento di risorse, eliminazione di elementi inutilizzati)
* Passare da &quot;diffusione&quot; a &quot;colore di base&quot;
* Cursori per la modifica delle regolazioni: consenti punti oltre a virgole
* Livello di riempimento: aumenta il valore massimo di affiancamento
* Mappa ambiente predefinita

**Corretto:**

* Artefatti di riflesso su angoli estremi
* Esportazione specular/lucentezza interrotta
* I collegamenti nella finestra &quot;Informazioni su&quot; di Painter non funzionano
* Arresto anomalo con OSX Yosemite
* Le trame vengono salvate in triangolo
* La scelta rapida per i colori della finestra degli strumenti viene inviata all’emittente anziché alla scala di grigi
* Il selettore colore rimane aperto quando si passa da un livello all’altro
* Impossibile salvare il materiale da un livello di riempimento
* Abilita il ridimensionamento delle tre aree dello scaffale

### 0.11.0-beta

*(Rilasciato il 4 settembre 2014)*

**Aggiunto:**

* Aggiungere una barra di divisione tra le viste 3D e 2D
* Utilizzare uno sfondo sfumato nelle viste 2D/3D
* Interfaccia per l’istogramma Livelli
* Unisci scaffale e libreria
* Nessuna azione di salvataggio richiesta per la creazione o l’aggiornamento di un predefinito
* Importare le risorse nello scaffale tramite trascinamento della selezione

**Corretto:**

* Il nome dei pulsanti viene visualizzato nella barra degli strumenti principale

### 0.10.2-beta

*(Rilasciato il 28 agosto 2014)*

**Corretto:**

* L’esportazione di tutti i canali genera risultati errati

### 0.10.1-beta

*(Rilasciato il 26 agosto 2014)*

**Corretto:**

* L’ombreggiatore restituisce un risultato nero con bassa ruvidità
* Controllo GPU: gestisce le schede &quot;Quadro&quot;, rileva tutti i dispositivi e adatta di conseguenza il messaggio dell&#39;utente
* La maggior parte dei materiali Substance è limitata a 256 in Beta 9
* Il height viene bloccato quando viene esportato come bitmap
* L’anteprima del pennello è diversa dalla sovrapposizione di proiezione su Mac
* L&#39;utilizzo dello strumento Geometria per creare una maschera non viene visualizzato nelle finestre delle viste
* Maschera veloce danneggiata
* Risolvere il problema di fusione sui vecchi mac pro

### 0.10.0-beta

*(Rilasciato il 7 agosto 2014)*

**Aggiunto:**

* Maschere stencil

**Corretto:**

* Supporto per schede Quadro
* L’ombreggiatore restituisce un risultato nero con bassa ruvidità
* I materiali Substance hanno un limite di 256
* L’esportazione di mappe normali elimina il canale verde

### 0.9.0-beta

*(Rilasciato il 17 luglio 2014)*

**Aggiunto:**

* Post-elaborazione Yebis 2
* La Creazione guidata nuovo progetto consente di importare mappe di input (AO, Curvatura, ecc.)
* Collega automaticamente le mappe di input (AO, Curvatura, ecc.) Substance effetti
* Controllo in scala sui materiali applicato ai livelli di riempimento

### 0,8,2-beta

*(Rilasciato l&#39;11 luglio 2014)*

**Corretto:**

* Il cursore Tonalità ha come impostazione predefinita il bianco
* Progetto reimpostato se il nome del materiale contiene caratteri speciali
* La modifica del nome del materiale per un singolo oggetto materiale non deve invalidare il progetto.
* Gli UV vengono danneggiati dopo il salvataggio del progetto e la riapertura

### 0,8,1-beta

*(Rilasciato il 4 luglio 2014)*

**Corretto:**

* Arresti anomali multipli della GPU
* Arresto anomalo durante l’esportazione dei canali

### 0.8.0-beta

*(Rilasciato il 28 giugno 2014)*

**Aggiunto:**

* Multi-materiale: ora puoi dipingere su più materiali nello stesso documento
* Simmetria
* Tutti i metodi di fusione sono ora disponibili

**Corretto:**

* Arresti anomali multipli della GPU
* Progetto reimpostato se il nome del materiale contiene caratteri speciali
* Gli UV vengono incasinati dopo il salvataggio del progetto e riaperti con più UV

### 0.7.0-beta

*(Rilasciato il 18 giugno 2014)*

**Aggiunto:**

* Effetti di livello
* Nuovi materiali per stencil Substance
* Annulla la maschera
* Consenti di copiare/incollare livelli/maschere
* Consenti di duplicare il livello
* Strumento Modifica durante la modifica della maschera di livello
* La Substance è ora basata su GPU

**Corretto:**

* La pittura con mappe di height non dipinge valori negativi.
* La visualizzazione Selettore materiale non deve tenere conto della mappa normale campionata
* Determinismo delle particelle rotto
* Matrice stencil nella vista 2D
* Ngon nei file obj
* Vari arresti anomali

### 0.6.0-beta

*(Rilasciato il 4 giugno 2014)*

**Aggiunto:**

* Nuova opzione di esportazione per esportare una mappa di Specular da una composizione dei canali metallici e di rugosità

**Corretto:**

* Compatibilità con Windows Vista
* La mappa del height non colorerà i valori negativi

### 0.5.0-beta

*(Rilasciato il 7 maggio 2014)*

**Aggiunto:**

* Switch di visualizzazione 3D/2D
* Strumento di selezione del blocco UV
* Lo strumento cambia automaticamente quando si disegna su maschere.
* La risoluzione della Substance dipende dal

**Corretto:**

* Arresto anomalo all’avvio
* Arresto anomalo con trame ASCII
* Matrice stencil fissa nella vista 2D
* Arresto anomalo con gomma

### 0.4.0-beta

*(Rilasciato il 17 aprile 2014)*

**Aggiunto:**

* Visualizzazione 2D uniforme
* Maschere di livello bitmap
* Controllo dell&#39;esposizione ambientale
* Riempi livelli ora usa le finestre Strumenti per impostare le proprietà
* I materiali possono essere applicati ai livelli di riempimento
* Aggiunti altri stencil nella libreria degli stencil
* Predefiniti Particelle aggiornati per un calcolo più veloce
* Ottimizzazione dello shader PBR e miglioramento della qualità per impostazioni di qualità inferiore

**Corretto:**

* Le miniature dei livelli sono collegate al canale attualmente selezionato
* Molti arresti anomali

### 0.3.0-beta

*(Rilasciato il 4 aprile 2014)*

**Aggiunto:**

* Consenti valori negativi nel selettore colore per il disegno della mappa del height
* Mostra anteprima del materiale/colore selezionato
* Aggiungere scelte rapide per gli strumenti nella barra degli strumenti (1,2,3,4)
* Passare al formato Normale (OpenGL e DirectX) a livello globale su un progetto
* Creazione guidata nuovo progetto
* Il cursore di spaziatura non è più bloccato
* Stile cursori aggiornati
* Rendi il selettore colore non modale
* Selezionando un materiale nella libreria, impostate di conseguenza il tipo di utensile

**Corretto:**

* Fisso: l’importazione del tracciato trama non viene mantenuta
* Fisso: generazione di texture errata
* Corretto: arresto anomalo all’avvio

### 0.2.0-beta

*(Rilasciato il 17 marzo 2014)*

**Aggiunto:**

* Contagocce materiale (scelta rapida P)
* Miniature nell’anteprima dello strumento 3D
* Sistema di licenza per versioni autonome
* Scelte rapide da tastiera [ e ] per Dimensione pennello
* Riempimento su mappe esportate
* Stile finestra strumenti aggiornato
* Stile cursori aggiornati
* Ambiente HDR predefinito aggiornato

**Corretto:**

* Stencil: modifica valore di flusso nella vista 3D interrompe a 52
* Ciclo infinito nel motore quando l&#39;aggiunta di tasti di pressione 0 al tratto è fissa
* Strumento: la variazione angolo non restituisce valori superiori a +/- 90%
* Modifica della visualizzazione della vista 3D quando viene selezionata una maschera di livello
* Zoom invertito

### 0.1.0-beta

*(Rilasciato il 2 marzo 2014)*

**Aggiunto:**

* Nuova gestione libreria
* Nuovo contenuto Pennelli e particelle
* Anteprima pennello 3D
* Stile finestra strumenti aggiornato
* Stile cursori aggiornati
* Prestazioni cache aggiornate

**Corretto:**

* Controlli videocamera
* Rotazione pennello
