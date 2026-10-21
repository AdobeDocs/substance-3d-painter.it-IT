---
breadcrumb-title: ''
description: Esamina tutte le modifiche e gli aggiornamenti nelle versioni di Substance 3D Painter per tenere traccia dell’evoluzione delle funzioni e dei miglioramenti nel tempo.
title: Tutte le modifiche
user-guide-description: ''
user-guide-title: ''
source-git-commit: 479eb327180dd223bbff362e3f200995565cbcfa
workflow-type: tm+mt
source-wordcount: '40713'
ht-degree: 0%
---

# Tutte le modifiche

Questa pagina contiene le note sulla versione per tutte le versioni precedenti di Substance 3D Painter, ordinate dalla più recente alla meno recente.

>[!NOTE]
>
> Per visualizzare i problemi noti che possono influire su Painter, consulta la [pagina dedicata alla documentazione](known-issues.md).

## Versione 12

### 12.2.0

Data di pubblicazione: **2026/10/21**

Riepilogo: **Questo aggiornamento è una versione principale, aggiunge una nuova funzionalità di pittura in gabbia per la esegue i baking e apporta miglioramenti alla funzionalità di riempimento poligono. Per ulteriori dettagli, vedere le note sulla versione complete.**

**Aggiunto:**

* Eseguo i baking, pittura a gabbia
* &lbrack;Cage Painting&rbrack; Creazione di un&#39;interfaccia utente di base per la Pittura della gabbia
* &lbrack;Cage Painting&rbrack; Nuove opzioni di visualizzazione della gabbia
* &lbrack;Cage Painting&rbrack; Strumento Selezione/Riempimento Modificabile
* &lbrack;Cage Painting&rbrack; Mostra modalità Fusione nella barra degli strumenti
* &lbrack;Cage Painting&brack; modifiche interfaccia utente del cursore HDR
* &lbrack;Cage Painting&rbrack; shader di visualizzazione
* &lbrack;Cage Painting&rbrack; Ripristina opzioni pila
* Miglioramenti dello strumento Riempimento poligono
* &lbrack;Polygon Fill&brack; Aggiungi patch poligonale
* &lbrack;Polygon Fill&brack; Aggiungi loop poligonale
* &lbrack;Polygon Fill&rbrack; supporto Simmetria con loop/Patch
* &lbrack;Polygon Fill&rbrack; Simmetria anteprima bordi
* &lbrack;Polygon Fill&brack; Rimuovi triangoli con loop e loop parziali
* &lbrack;Polygon Fill&rbrack; Wireframe visibile solo per il set di texture attivo
* &lbrack;Riempimento poligonale&rbrack; evidenziazione dei bordi rossi su triangoli non selezionabili
* &lbrack;Riempimento poligonale; Non disabilitare le opzioni della modalità di riempimento
* &lbrack;Riempimento poligono&rbrack; Consenti di impostare tutte le proprietà del canale con Riempimento poligono
* &blocca;Riempimento poligono&nna; Riprendi tratto precedente funziona con Riempimento poligonale
* &lbrack;Riempimento poligonale; Mostra cursore non consentito su set di texture non attivi
* &blocco;Riempimento poligono&rnco; Anteprima istantanea ALT
* &lbrack;Polygon Fill&rbrack; Scelta rapida da tastiera per il passaggio temporaneo a Polyloop (MAIUSC+A)
* &lbrack;Riquadro di visualizzazione&rbrack; Mostra set di texture/Porzione UV selezione evidenziata
* &lbrack;Viewport&rbrack; Aggiungi il supporto per Trasparenza indipendente dall&#39;ordine nella finestra della vista in tempo reale
* &lbrack;Impostazioni di visualizzazione&rbrack; riorganizza le impostazioni di visualizzazione in nuovi gruppi
* &lbrack;Strumento&rbrack; Aggiungi il supporto per la fusione additiva con tratti pennello
* &lbrack;Strumento&rbrack; Aggiungi supporto per fusione additiva con Riempimento poligonale
* &lbrack;USD&rbrack; L&#39;USD esportato con mappa di opacità rende tutto trasparente in Arnold
* &lbrack;Nvidia&rbrack; Aggiungi avviso sui driver Nvidia più recenti (da 616.56 a 617.14)
* Aggiungi nuovo input mappa motore &quot;mesh_uv_next&quot;
* Aggiornare i baker alla versione 3.23.0
* Aggiornamento del motore di Substance alla versione 9.6.1

**Corretto:**

* &lbrack;Esegui i baking&rbrack; Occlusione ambientale L&#39;opzione Ignora backface per nome trama non funziona
* &lbrack;Esegue i baking&rbrack; &lbrack;AMD&rbrack; Dispositivo perso durante la esegue i baking con trame pesanti e ad alto polio
* &lbrack;Performance&rbrack; Painter nasconde l&#39;utilizzo dell&#39;VRAM
* &lbrack;Viewport&rbrack; texture mancanti all’apertura di progetti su schermi HDPI
* &lbrack;Strumento&rbrack; Il metodo di fusione è disattivato quando si disegna in una maschera
* Cartelle temporanee non eliminate dopo l’esportazione in rete
* &lbrack;USD&rbrack; La geometria USD esportata viene divisa lungo i bordi UV
* &lbrack;USD&rbrack; Blocco durante il caricamento di USDz in formato non valido

### 12.1.5

Data di pubblicazione: **2026/09/15**

Riepilogo: **Versione secondaria**

**Corretto:**

* L’esportazione di un’immagine dallo scaffale a una rete non funziona più
* &lbrack;Generator&rbrack; L&#39;impostazione di &quot;usa texture&quot; su false non disattiva l&#39;uso dell&#39;input della texture
* Il riquadro di visualizzazione si blocca durante il salvataggio durante la modifica della proiezione 3D
* La risoluzione dei livelli del materiale è troppo bassa

### 12.1.4

Data di pubblicazione: **2026/09/04**

Riepilogo: **Versione secondaria**

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; Arresto anomalo durante l&#39;importazione o l&#39;esportazione di file i cui nomi contengono caratteri non ASCII

### 12.1.3

Data di pubblicazione: **2026/08/26**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* Aggiornamento del motore di Substance alla versione 9.4.6

**Corretto:**

* &blocco;Selettore scala di grigi&rbrack; rimane aperto dopo la modifica dello strumento
* &lbrack;Inclina Eseguo i baking&rbrack; La correzione dell&#39;inclinazione si interrompe quando si disegna e si annulla
* &lbrack;Strumento di proiezione&rbrack; l&#39;interazione del riquadro di visualizzazione viene bloccata dallo strumento di proiezione
* &lbrack;Dynamic Stroke&brack; parametri Dynamic Stroke mancanti nelle proprietà del pennello
* L’esportazione in rete non funziona più

### 12.1.2

Data di pubblicazione: **2026/08/03**

Riepilogo: **Versione secondaria**

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; Alcune Substance possono generare un arresto anomalo durante il rendering
* &lbrack;Arresto anomalo&rbrack; reimporta trama in modalità eseguita i baking
* &lbrack;Arresto anomalo&rbrack; se non si inizializza la visualizzazione grafica, può verificarsi un arresto anomalo
* &lbrack;Arresto anomalo&rbrack; in alcuni casi durante l&#39;aggiornamento del registro può verificarsi un arresto anomalo dell&#39;esportazione della texture
* &lbrack;Arresto anomalo&rbrack; Arresto anomalo in modalità eseguita i baking in alcuni casi durante il caricamento/aggiornamento della mappa dell&#39;ambiente
* &lbrack;Eseguite i baking&rbrack; Il eseguo i baking di riavvio dopo la modifica del file di poly alto può provocare un blocco
* &lbrack;Invia a Photoshop&rbrack; non riesce a esportare la maschera del livello
* &lbrack;Engine&rbrack; Il risultato del punto di ancoraggio non esegue il rendering tra una maschera e un canale di colore

### 12.1.1

Data di pubblicazione: **2026/07/09**

Riepilogo: versione secondaria

Aggiunto:

* &lbrack;Inclina Eseguo i baking&rbrack; Esposizione inclina base Modalità normale: trama o per-triangolo
* &lbrack;Properties&rbrack; Imposta sempre i colori uniformi sul valore predefinito del canale
* &lbrack;OpenPBR&rbrack; raggruppa i canali per categorie nella finestra Esporta Texture per la creazione di modelli di output
* Aggiornamento del motore di Substance alla versione 9.4.5

Fisso:

* &lbrack;Project&rbrack; L&#39;apertura e il salvataggio di alcuni progetti può richiedere più tempo del solito
* &lbrack;Arresto anomalo&rbrack; Ricarica più trame può generare un arresto anomalo
* &lbrack;Arresto anomalo&rbrack; l&#39;eliminazione di un canale durante la modalità di visualizzazione maschera genera un arresto anomalo
* &lbrack;Arresto anomalo&rbrack; Alcune Substance possono generare un arresto anomalo durante il rendering
* &lbrack;Pittura inclina&rbrack; lo strumento selezionato in pittura inclina rimane selezionato dopo il passaggio alla modalità di disegno
* &lbrack;Esegue i baking impostazioni comuni&rbrack; le impostazioni di distanza gabbia non aggiornano la visualizzazione di wireframe e shader
* &lbrack;Engine&rbrack; La modalità &quot;Vicina spazio 3D&quot; del riempimento UV non funziona correttamente sui triangoli sottili
* &lbrack;Engine&rbrack; Il risultato del punto di ancoraggio non esegue il rendering tra una maschera e un canale di colore

### 12.1.0

Data di pubblicazione: **2026/06/23**

Riepilogo: **Questo aggiornamento è una versione principale e contiene miglioramenti a livello di baker con il nuovo stato predefinito dell’interfaccia utente eseguito i baking, la mappa di inclinazione del colore, il rebake automatico, la nuova opzione per lo srotolamento UV automatico per trame e OpenPBR hardsurface. Per ulteriori dettagli, vedere le note sulla versione complete.**

**Aggiunto**:

* &lbrack;Inclina &amp;eseguo i baking; Inclina strumenti di pittura
* &lbrack;Inclina Eseguo i baking&rbrack; Aggiungi shader anteprima inclina e immagini vettoriali della direzione di inclinazione quando si disegna la mappa di inclinazione
* &lbrack;Inclina Eseguo i baking&rbrack; Aggiungi protezione bordi opzione
* &lbrack;Inclina eseguo i baking&rbrack; Ripetizione automatica
* &lbrack;Inclina Eseguo i baking&rbrack; Rielabora interfaccia utente mappa trama
* &lbrack;Inclina Eseguo i baking&rbrack; Dividi mappa trama / Impostazioni comuni di Esegue i baking + Sposta impostazioni comuni fuori dall&#39;elenco mappa trama solo colore di base o maschera
* &lbrack;Inclina &amp;Eseguo i baking; Cambia pulsanti della barra degli strumenti della finestra della vista
* &lbrack;Inclina Eseguo i baking&rbrack; Mostra interruttore Simmetria per il pennello nella barra degli strumenti superiore
* &lbrack;Inclina Eseguo i baking&rbrack; Rinomina opzioni nel menu Sincronizzazione elenco mappa trama
* &lbrack;Inclina &amp;Eseguo i baking; Aggiorna finestre di dialogo per sincronizzazione e stato selezionato
* &lbrack;Inclina Eseguo i baking&rbrack; Crea variante del selettore colore in scala di grigi
* &lbrack;Inclina Eseguo i baking&rbrack; Aggiorna icona modalità eseguo i baking
* &lbrack;Auto Unwrap&rbrack; opzione Integra superficie rigida
* &lbrack;OpenPBR&rbrack; Aggiungi supporto per OpenPBR 1.1
* &lbrack;OpenPBR&rbrack; Imposta l&#39;OpenPBR come flusso di lavoro e shader predefiniti
* &lbrack;OpenPBR&rbrack; Importa materiali e texture OpenPBR tramite USD
* &lbrack;OpenPBR&rbrack; Esporta OpenPBR e texture tramite USD
* &lbrack;OpenPBR&rbrack; Aggiorna la finestra Texture di esportazione per mostrare la convenzione di denominazione dell&#39;OpenPBR
* &lbrack;OpenPBR&rbrack; Aggiungi documentazione sulle modifiche all&#39;OpenPBR di supporto
* &lbrack;OpenPBR&rbrack;&lbrack;Iray&rbrack; Aggiungi un nuovo MDL per supportare l&#39;OpenPBR 1.1 in Iray
* Diversi miglioramenti minori nelle esportazioni USD
* &lbrack;UI&rbrack; Aggiungi un avviso nella finestra della vista quando si tenta di eseguire la pittura su un altro set di texture
* &lbrack;Appiattisci&rbrack; Consenti di appiattire tutti i livelli istantanei tra set di texture
* &lbrack;Impostazioni set di texture&rbrack; Consenti di selezionare più canali contemporaneamente tramite una nuova finestra
* &lbrack;History&rbrack; Aggiorna il &quot;valore&quot; della voce Annulla per riflettere il nome del parametro
* &lbrack;Pila livelli&rbrack; Rende gli effetti di riempimento nelle maschere predefiniti sul bianco (1.0)
* &lbrack;Substance&rbrack; Aggiungi nuovo input mappa motore &quot;mesh_hard_edges_triangle&quot;
* &lbrack;Substance&rbrack; Aggiungi nuovo input mappa motore &quot;mesh_hard_edges&quot;
* &lbrack;Shader&rbrack; impedisce alle istanze shader di condividere gli stessi nomi
* &lbrack;Shader&rbrack; utilizza lo shader del modello di progetto durante l&#39;importazione di un file USD o GLTF
* Aggiornamento dell&#39;Adobe Color Engine alla versione 7.0
* Aggiornamento della versione minima MacOSX alla versione 13.0 (Ventura)
* &lbrack;Content&rbrack; Nuovi modelli di progetto per l&#39;OpenPBR
* &lbrack;Content&rbrack; aggiorna i progetti di esempio per utilizzare il nuovo shader di OpenPBR
* &lbrack;Python&rbrack; Espandi l’API maschera geometria per consentire le modalità di inclusione ed esclusione, come nell’interfaccia utente

**Risolto**:

* &lbrack;Arresto anomalo&rbrack;&lbrack;Mesh Maps Settings&rbrack; Applica le impostazioni ad altri set di texture
* &lbrack;Arresto anomalo&rbrack; Quando si esegue i baking la curvatura da una mappa senza spazio mondo normale
* &lbrack;Arresto anomalo&rbrack;&lbrack;Esegue i baking&rbrack; Esegue i baking con gabbia personalizzata abilitata ma nessun file selezionato arresti anomali
* &lbrack;Arresto anomalo&rbrack; annullamento della esegue i baking di AO
* &lbrack;Auto-Cage&rbrack; Caricamento infinito quando il percorso del file poli è alto non è valido
* &lbrack;Linux&rbrack;&lbrack;Windows&rbrack; Il selettore colore a volte può essere completamente nero o non essere visualizzato
* &lbrack;Strumento Riempimento poligonale&rbrack; Lo strumento non funziona con file non PBR
* &lbrack;&lbrack;Pittura&rbrack; l&#39;eliminazione del canale del colore di base non elimina il colore colorato in precedenza
* &lbrack;USD&rbrack; Istanze shader non tutte correttamente rilevate
* &lbrack;Substance&rbrack; viene considerato solo il primo utilizzo di un nodo di input/output
* &lbrack;Shader&rbrack; l&#39;Occlusione ambientale viene applicata due volte con i set di texture utilizzando diversi metodi di miscelazione
* &lbrack;Engine&rbrack; La texture normale con canale blu vuoto (nero) può produrre risultati di fusione errati
* &lbrack;GLTF Import&rbrack; La fusione alfa è abilitata su ogni set di texture
* &lbrack;GLTF Export&rbrack; Fusione alfa è sempre abilitata all&#39;esportazione
* &lbrack;Export&rbrack; La geometria a due lati è sempre disattivata durante l&#39;importazione di un file GLTF
* &lbrack;Javascript&rbrack; La modifica delle impostazioni degli shader non contribuisce alla cancellazione della cronologia
* &lbrack;Samples&rbrack; Subsurface scattering non è abilitato in Impostazioni di visualizzazione per Riunione

### 12.0.3

Data di pubblicazione: **2026/05/05**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* Aggiornare i baker alla versione 3.22.2
* Aggiornamento del motore di Substance alla versione 9.4.3
* &lbrack;Python&rbrack; Salvare un materiale avanzato in una posizione specifica

**Corretto:**

* &lbrack;Ubuntu&rbrack; Arresto anomalo durante la selezione del materiale
* &lbrack;Mac&rbrack; Viene visualizzata una finestra a comparsa ricorrente per chiedere l&#39;accesso ai dati di altre app
* &lbrack;Esegui i baking&rbrack; Gli artefatti possono essere visualizzati sulla mappa curvatura
* &lbrack;Esegue i baking&rbrack; Esegue i baking più lenta in alcuni casi
* &lbrack;Altera a geometria&rbrack; In alcuni casi l&#39;opzione Altera a geometria viene disattivata
* &lbrack;Porzione UV&rbrack; Alfa estratto del punto di ancoraggio ignorato da altre porzioni
* &lbrack;Python&rbrack;&lbrack;Mac&rbrack; Eccezioni nella console Python con SSL
* &lbrack;Python&rbrack; arresto anomalo Painter all&#39;uscita con widget Qt rimanenti

### 12.0.2

Data di pubblicazione: **2026/04/07**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* &lbrack;Color management&rbrack; Aggiungi nuovo OCIO per specificare lo spazio colore predefinito del selettore colore
* &lbrack;Python&rbrack; Esporre le impostazioni di annullamento automatico del wrapping nell&#39;API Python

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; Il salvataggio con spazio su disco insufficiente può causare l&#39;arresto anomalo o il danneggiamento dei progetti
* &lbrack;Arresto anomalo&rbrack; &lbrack;Ribbon&rbrack; L&#39;utilizzo della barra multifunzione può causare arresti anomali per alcuni progetti
* &lbrack;Arresto anomalo&rbrack; &lbrack;Esegui i baking&rbrack; arresto anomalo in cui non è possibile scrivere il file .assbin nella cartella
* &lbrack;Import&rbrack; le trame OBJ da Stager possono non riuscire durante la creazione del progetto
* &lbrack;Import&rbrack; in alcuni casi all&#39;OBJ manca il volto
* &lbrack;Import&rbrack; la trama USD senza materiale assegnato può essere arresto anomalo durante l&#39;importazione
* &lbrack;Filled Path&rbrack; non influenzato dalla simmetria
* &lbrack;Stencil&rbrack; L&#39;anteprima ha una risoluzione inferiore rispetto al risultato disegnato
* &lbrack;UI&rbrack; &#39;isola uv&#39; è ancora menzionato nella descrizione comando origine colore mappa ID
* &lbrack;Display&rbrack; Le ombre appaiono invertite
* &lbrack;Viewport&rbrack; Il Trasforma di proiezione dell&#39;alterazione rimane dopo il passaggio alla modalità di esegue i baking
* &lbrack;Altera&rbrack; la griglia scompare quando la scala è impostata su 0 sull&#39;asse Z con l&#39;opzione Altera alla geometria abilitata
* &lbrack;Python&rbrack; errore imprevisto durante l&#39;aggiunta di un canale con modifica dell&#39;ambito

### 12.0.1

Data di pubblicazione: **2026/03/18**

Riepilogo: **Versione secondaria**

**Corretto:**

* &lbrack;Arresto anomalo&rbrack;&lbrack;Freeze&rbrack; Esporta da progetti specifici

### 12.0.0

Data di pubblicazione: **2026/03/09** Riepilogo: **Si tratta di una versione principale. Questa versione contiene le funzioni che appiattiscono i livelli, altera la geometria, nuovi effetti post, miglioramenti alla nuova finestra del progetto e altri miglioramenti.**

**Aggiunto**:

* &lbrack;Appiattisci livelli&rbrack; Appiattisci i livelli all’interno della Pila livelli
* &lbrack;Unisci livelli&rbrack; Esporta livelli uniti su disco
* &lbrack;Altera a geometria&rbrack; Aggiungi nuova funzionalità di alterazione automatica alle proiezioni di alterazione
* &lbrack;Post-effects&rbrack; Sostituisci gli effetti post con altri nuovi
* &lbrack;Post-effects&rbrack; Aggiorna mappatura toni
* &lbrack;Post-effects&rbrack; Aggiungi nuovo utilizzo per le risorse Post-effetti
* &lbrack;Content&rbrack;&lbrack;Post-effects&rbrack; Integra le risorse predefinite per i post-effetti nella libreria
* &lbrack;Nuovo progetto&rbrack; Migliora l&#39;interfaccia utente per la creazione del progetto
* &lbrack;Nuovo progetto&rbrack; modifiche alla funzionalità di reimportazione della trama
* &lbrack;Nuovo progetto&rbrack; consente l&#39;apertura dei file \*.geo.usd
* &lbrack;Configurazione progetto&rbrack; Migliora interfaccia utente per la configurazione del progetto
* Aggiornamento della libreria USD alla versione 25.05
* Aggiornamento della Substance Engine alla versione 9.3.4
* Aumenta i driver minimi a 25.3.1/25.Q2 per le GPU AMD
* Aggiornamento di Qt alla versione 6.8.6
* &lbrack;Scripting&rbrack; Aggiornamento dell&#39;API JavaScript alla versione 1.1.20
* Aggiorna Python alla versione 3.13

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; La modifica dell&#39;output di un canale di materiale in una maschera può arresto anomalo
* &lbrack;Import&rbrack; le texture EXR vengono forzate in sRGB anziché in modo lineare durante l&#39;importazione dei file USD
* &lbrack;Porzione UV&rbrack; La sequenza di immagini con una singola immagine riempie anche altre Porzioni UV
* &lbrack;Eseguite i baking&rbrack; AO è diverso tra la CPU e la GPU eseguite i baking
* &lbrack;Color Management&rbrack;&lbrack;MacOS&rbrack; Viewport BaseColor non corrisponde a colorpicker
* &lbrack;USD&rbrack; In alcuni casi i valori uniformi non vengono importati

## Versione 11

### 11.1.3

Data di pubblicazione: **2026/02/12** Riepilogo: **Versione secondaria**

**Risolto**:

* &lbrack;Pitture&rbrack; In alcuni casi, stencil e simmetria non funzionano
* &blocco;Tracciato&rbrack; nessun aggiornamento quando si modifica il cursore dell&#39;opacità del tratto sfumino
* &lbrack;Project&rbrack; impossibile eseguire la pittura su alcune geometrie
* &lbrack;Ribbon&rbrack; il percorso istanziato scompare quando si modifica la risoluzione del set di texture
* &lbrack;UI&rbrack; il selettore colore può ridursi e in alcuni casi scomparire

### 11.1.2

Data di pubblicazione: **2026/01/13** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &lbrack;Esegui i baking&rbrack; migliora il tempo di eseguita i baking per il progetto Porzione UV con il salvataggio asincrono
* &lbrack;Shaders&rbrack; Citazione nelle modifiche apportate al registro modifiche API shader in seguito alla migrazione Vulkan
* Aggiornamento dell’OpenEXR alla versione 3.4.4

**Risolto**:

* &lbrack;Arresto anomalo&rbrack; Arresto anomalo durante l&#39;avvio su Nvidia GTX 10xx series
* &lbrack;Arresto anomalo&rbrack; L&#39;uso del selettore colore su set di texture diversi può produrre un arresto anomalo quando si esce dall&#39;applicazione
* &lbrack;Prestazioni&rbrack; problema di prestazioni quando si disegna in un progetto con molti livelli
* &lbrack;Performance&brack; Ritardo quando si disegna con la penna grafica
* &lbrack;UI&rbrack; Le impostazioni della fotocamera rimangono disattivate in modalità rendering (Iray)
* &lbrack;Barra multifunzione&rbrack; In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* &lbrack;Ribbon&rbrack; problema di prestazioni con la Porzione UV
* &lbrack;Substance&rbrack;&lbrack;UI&rbrack; Gli input dell&#39;immagine scompaiono se compressi
* &lbrack;Substance&rbrack;&lbrack;UI&rbrack; I gruppi nidificati possono rimanere anche se visibili se li nasconde
* &lbrack;Eseguite i baking&rbrack;&lbrack;UI&rbrack; impossibile impostare il raggio di campionamento della curvatura oltre 0,01
* &lbrack;Eseguite i baking&rbrack;&lbrack;UI&rbrack; impossibile impostare la distanza massima di occlusione oltre 1
* &lbrack;Esegui i baking&rbrack; L’impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e esegue i baking bassa come alta
* &lbrack;Esegue i baking&rbrack; La mappa ID non esegue i baking i colori dei vertici dall&#39;FBX in modalità Bassa come Alta
* &lbrack;Content&rbrack; Highpass filter genera colori sbiaditi nei canali con gestione del colore

### 11.1.1

Data di pubblicazione: **2025/12/09** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &lbrack;Prestazioni&rbrack; Migliora le prestazioni Porzioni UV durante l&#39;elaborazione di texture parziali
* &lbrack;Baker&rbrack; Aggiornamento alla versione 3.15.4

**Risolto**:

* &lbrack;Arresto anomalo&rbrack;&lbrack;MacOS&rbrack; Salvataggio del progetto dalla versione precedente sempre arresto anomalo
* &lbrack;Arresto anomalo&rbrack; La chiusura di un progetto può talvolta generare un arresto anomalo
* &lbrack;Project&rbrack; Errore &quot;conteggio membri non corrispondente&quot; durante l&#39;apertura di un progetto creato nella versione precedente
* &lbrack;Eseguire i baking&rbrack; le Porzioni UV non sono combinate con i risultati della esegue i baking precedente, se presenti
* &lbrack;Eseguite i baking&rbrack; Dispositivo perso anche con raytracing disattivato sulla serie Nvidia GTX 10XX
* &lbrack;Esegui i baking&rbrack; AO con normale ha artefatti ai bordi perché nessuna spaziatura interna
* &lbrack;Eseguite i baking&rbrack; L&#39;impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e l&#39;opzione &quot;corrispondenza per nome&quot; viene attivata
* &lbrack;Esegui i baking&rbrack; La mappa ID è completamente nera se mancano i colori dei vertici in qualsiasi trama di poli alta
* &lbrack;Ribbon&rbrack; la descrizione comando per il metodo di fusione Alfa indica il metodo di fusione Schermo anziché Scherma lineare
* &lbrack;Path&brack; Le tangenti creano un ciclo inatteso quando il punto viene spostato vicino alle estremità del tracciato
* &lbrack;Strumento&rbrack; L&#39;anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
* &blocca;Motore&brack; disegnare piccoli tratti può causare artefatti a blocchi
* &lbrack;Shader&rbrack; l&#39;annullamento della creazione dell&#39;istanza shader non la rimuove correttamente
* &lbrack;Export&rbrack; La modalità di Alpha per l&#39;esportazione GLTF è sempre impostata su MASK
* &lbrack;Python&rbrack; errore imprevisto durante la modifica della Pila livelli all&#39;esterno del blocco di modifica con ambito

**Problemi noti**:

* &lbrack;Ribbon&rbrack; problema di prestazioni con la Porzione UV
* &lbrack;Barra multifunzione&rbrack; In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* &lbrack;Arresto anomalo&rbrack;&lbrack;Ribbon&rbrack; creazione di testi molto lunghi nella barra multifunzione può essere un arresto anomalo
* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.1.0

Data di pubblicazione: **2025/11/18** Riepilogo: **Questo aggiornamento è una versione principale, contiene il nuovo strumento barra multifunzione con nuovi contenuti dedicati, supporto simmetria per livelli di riempimento, parametro dimensioni fisiche per lo spostamento, prestazioni migliorate tramite i baker aggiornati, supporto completo di Vulkan per Windows e Linux e altri miglioramenti.**

**Aggiunto**:

* Nuovo strumento barra multifunzione
* &blocca;Strumento &amp;Barra multifunzione; Aggiungi nuovo strumento Barra multifunzione per creare tracciati senza interruzioni
* &blocco;Barra multifunzione&rbrack; Aggiungi scelte rapide da tastiera per i predefiniti della barra multifunzione nella finestra Proprietà
* &lbrack;Barra multifunzione&rbrack; consente di modificare l&#39;opacità della barra multifunzione per vertice sul tracciato
* &lbrack;Barra multifunzione&rbrack; Consente di modificare le dimensioni della barra multifunzione per vertice sul tracciato
* &lbrack;Barra multifunzione&rbrack; Rimuovi inizio/fine definiti in una Substance quando i tracciati vengono chiusi
* &lbrack;Ribbon&rbrack; Rimuovi anteprima tracciato/materiale nella finestra delle proprietà per gli strumenti tracciato Pittura/Gomma/Sfumino
* &lbrack;Ribbon&rbrack; Aggiungi metodi di fusione per l&#39;alfa e alcuni canali quando si sovrappongono
* Riempi simmetria
* &lbrack;Fill&rbrack; Aggiungere il supporto per simmetria su livelli di riempimento ed effetti
* &lbrack;Fill&rbrack;&lbrack;UI&rbrack; Esporre le impostazioni della simmetria nella finestra delle proprietà per il livello di riempimento e gli effetti
* &lbrack;Fill&rbrack; Rielaborare l&#39;interfaccia utente delle impostazioni della simmetria sia nel menu della finestra della vista che nella finestra delle proprietà
* &lbrack;Fill&rbrack; Riorientare correttamente la texture normale durante la proiezione in modalità di alterazione
* Dimensioni fisiche spostamento
* &lbrack;Spostamento&rbrack; Usa dimensioni fisiche come unità di spostamento
* Miglioramento delle prestazioni
* &lbrack;Prestazioni&rbrack; Migliora il rendering dei tratti pennello piccoli su triangoli grandi
* &lbrack;Performance&rbrack; Migliora i tempi di compilazione degli Shader
* &lbrack;Performance&rbrack; supporto completo di Vulkan per Windows e Linux
* &lbrack;Performance&rbrack; baker aggiornati con rendering GPU più veloce e supporto di AMD raytracing
* &lbrack;UI&rbrack; riorganizza le proprietà degli strumenti in gruppi e comprimi alcuni per impostazione predefinita
* &lbrack;Engine&rbrack; Aggiorna Substance Engine alla versione 9.2.5
* &lbrack;Substance&rbrack; Esponi sostituzione risoluzione per le risorse Substance in Strumenti e riempimenti
* &lbrack;Esporta&rbrack; Aggiorna il predefinito di esportazione delle mappe trama per esportare texture in scala di grigio
* Python
* &lbrack;Eseguite i baking&rbrack;&lbrack;Python&rbrack; Indica nel registro modifiche che interrompono l&#39;aggiornamento dei baker successivi
* &lbrack;Python&rbrack; Esporre le impostazioni delle simmetrie di riempimento in Python
* Contenuto e nuovo contenuto
* &lbrack;Content&rbrack; Aggiungi 75 nuovi strumenti predefiniti per lo strumento barra multifunzione
* &blocco;Content&rbrack; aggiorna la risorsa di creazione delle sfumature per renderla compatibile con la barra multifunzione

**Risolto**:

* &lbrack;Arresto anomalo&rbrack; Il caricamento di un altro progetto mentre l&#39;aggancio del percorso è abilitato può comportare l&#39;arresto anomalo
* &lbrack;Arresto anomalo&rbrack; è possibile eseguire l&#39;arresto anomalo facendo clic con il pulsante destro del mouse nel pannello Tracciato con le informazioni di un&#39;altra sessione negli Appunti
* &lbrack;UI&rbrack; L&#39;interfaccia scorre verso l&#39;alto nelle proprietà dello strumento durante la creazione di un tracciato
* &lbrack;UI&rbrack; Il cursore del mouse scompare quando la visualizzazione della finestra della vista del percorso è nascosta
* &blocco;Tracciato&rbrack; copiare/incollare diverse proprietà dello strumento nel pannello Tracciato causa proprietà instabili
* &Lbrack;Strumento &Rbrack; I predefiniti degli strumenti Gomma e Sfumino non sempre aggiornano la selezione del canale
* &lbrack;Strumento&rbrack; il valore Dipinto è grigio ma l&#39;interfaccia utente viene visualizzata in bianco dopo il caricamento del predefinito dello strumento colorato nella maschera
* &lbrack;Strumento&rbrack; predefinito creato dalla maschera mantiene i valori dei canali caricati da un altro predefinito
* &lbrack;Substance&rbrack; L&#39;override dello spazio colore normale definito nel grafico non viene considerato
* &lbrack;Content&rbrack; la risorsa forma pennello predefinita utilizza una Substance obsoleta

**Problemi noti**:

* Cronologia Istanze shader non monitorata correttamente
* &lbrack;Ribbon&rbrack; problema di prestazioni con la Porzione UV
* &lbrack;Barra multifunzione&rbrack; In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* &lbrack;Ribbon&rbrack; le tangenti creano un ciclo indesiderato quando il punto viene spostato vicino alle estremità del tracciato
* &lbrack;Arresto anomalo&rbrack;&lbrack;Ribbon&rbrack; creazione di testi molto lunghi nella barra multifunzione può essere un arresto anomalo
* &lbrack;Strumento&rbrack; L&#39;anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
* &lbrack;Eseguite i baking&rbrack; L&#39;impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e l&#39;opzione &quot;corrispondenza per nome&quot; è abilitata
* &lbrack;Esegui i baking&rbrack; AO con normale presenta artefatti ai bordi a causa della mancanza di spaziatura interna
* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.3

Data di pubblicazione: **2025/08/05** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &lbrack;Substance 3D Assets&rbrack; Aggiungi un punto di notifica al pannello Risorse 3D
* &lbrack;VFX Platform 2025&rbrack; aggiunta della configurazione ACE 2.0 nelle impostazioni di gestione del colore
* &lbrack;VFX Platform 2025&rbrack; Aggiornamento OCIO alla versione 2.4.2
* Aggiornamento di Iray alla versione 2024.10
* &lbrack;Engine&rbrack; Aggiornamento a Substance Engine v.9.2.3
* &lbrack;Nvidia&rbrack; aumenta la versione minima dei driver Nvidia a 572.60 (Win) e 570.169 (Linux)

**Risolto**:

* &lbrack;Python&rbrack; La modifica con ambito non viene visualizzata nella finestra Cronologia

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.2

Data di pubblicazione: **2025/06/10** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &lbrack;Mac&rbrack; Aggiungi avviso per una versione specifica del sistema operativo che causa artefatti
* &lbrack;Auto-update&rbrack; miglioramenti minori UX al registro errori Risorse
* &lbrack;Srotolamenti automatici&rbrack; Aggiornamento alla versione 1.3.2 con miglioramenti per la giunzione
* &lbrack;USD&rbrack;&lbrack;FBX&rbrack; Aggiungi supporto per più set UV con dati sparsi
* &lbrack;Export&rbrack; Nelle trame esportate come FBX mancano gli eventuali set UV aggiuntivi presenti durante l&#39;importazione

**Risolto**:

* &lbrack;MacOS&rbrack;&lbrack;Linux&rbrack; Arresto anomalo durante il salvataggio sull&#39;unità di rete
* &lbrack;Win&rbrack;&lbrack;Tablet&rbrack; Sfarfallio durante il panning
* &lbrack;SpaceMouse&rbrack; Problema durante l&#39;utilizzo dello strumento tracciato
* &lbrack;Auto-cage&rbrack; Impossibile eseguire i baking dopo un ricaricamento della trama
* &lbrack;Auto-update&rbrack; La sequenza di immagini non viene ricaricata se manca la prima porzione
* &lbrack;Tracciato&rbrack; la tangente personalizzata può influire su un&#39;altra tangente
* &lbrack;Tracciato&rbrack; il tracciato non viene visualizzato sull&#39;insieme di texture se il primo punto si trova su un altro insieme di texture
* &lbrack;UI&rbrack; Alcuni menu sono sempre disattivati dopo l’apertura di un progetto (ad esempio: simmetria)
* &lbrack;Properties&rbrack; Impossibile utilizzare/caricare strumenti predefiniti con lo strumento tracciato pieno
* &lbrack;USD&rbrack; più set UV non vengono riconosciuti in uno shader personalizzato quando si utilizzano file USD
* &lbrack;USD&rbrack; Le videocamere con gli stessi nomi vengono sostituite
* &lbrack;Esporta&rbrack; Invia a Photoshop genera uno spazio colore errato per i risultati a colori e in scala di grigi
* &lbrack;Esporta&rbrack; i canali in scala di grigi con alfa vengono esportati come colore invece che come scala di grigi con formato PNG
* &lbrack;Esporta&rbrack; l&#39;esportazione del canale in scala di grigi come PSD genera un file non valido/troncato
* &lbrack;Content&rbrack; Il filtro Altera in modalità multidirezionale non funziona
* &lbrack;Python&rbrack; Impossibile allocare l&#39;errore dell&#39;elenco durante la ricerca per indicizzazione dei nodi Pila livelli

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.1

Data di pubblicazione: **2025/04/10** Riepilogo: **Versione secondaria**

Nota: **La versione del CCD Linux verrà posticipata al 29 aprile**

**Aggiunto:**

* Aggiornamento a Qt 6.5.8
* &lbrack;Substance&rbrack; Aggiungi messaggio di registro per i filtri quando più input di immagine condividono lo stesso utilizzo
* &lbrack;Nvidia&rbrack; Aggiungi avviso sui driver Nvidia più recenti (572.47)

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; quando si trascina e rilascia un sbsar con un utilizzo in uno slot per un singolo canale
* &lbrack;Arresto anomalo&rbrack;&lbrack;Path&rbrack; L&#39;opzione Cambia tipo di tracciato non è disattivata quando non si fa clic su un tracciato specifico
* &lbrack;Riempi tracciato&rbrack; Non dovrebbe essere in grado di selezionare il materiale Substance
* &lbrack;Engine&brack; artefatti lungo i tratti pennello
* &lbrack;Motore&rbrack; I tracciati possono essere interrotti con impostazioni specifiche
* Problema con il menu a discesa per lo spazio colore del contagocce
* &lbrack;Auto-update&rbrack; &lbrack;Python&rbrack; Messaggio di errore errato quando si utilizza ResourceID senza versione
* &lbrack;Shader&rbrack; Arresto anomalo durante l&#39;apertura di alcuni progetti

**Problemi noti:**

* &lbrack;SpaceMouse&rbrack; Problema durante l&#39;utilizzo dello strumento tracciato
* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.0

Data di pubblicazione: **2025/03/11** Riepilogo: **Versione principale, nuova funzione di aggiornamento automatico, strumento Tracciato riempito e altri miglioramenti del percorso, oltre a nuovi filtri e una generazione sperimentale di gabbia automatica per eseguire i baking**

**Aggiunto**:

* Aggiornamento automatico
* &lbrack;Auto-update&rbrack; aggiorna automaticamente le risorse modificate nel pannello Risorse
* &lbrack;Auto-update&rbrack; aggiorna automaticamente le risorse modificate nel progetto
* &lbrack;Auto-update&rbrack; Mantiene disattivato l&#39;aggiornamento automatico per impostazione predefinita
* &lbrack;Auto-update&rbrack; Rende facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono (.sbsar, .glsl, .ai, .svg)
* &lbrack;Auto-update&rbrack; Aggiungi variabile di ambiente per disabilitare la funzione di aggiornamento automatico
* &lbrack;Auto-update&rbrack;&lbrack;SBSAR&rbrack; Rende facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono
* Tracciato pieno
* &lbrack;Tracciato&rbrack;&lbrack;Riempi&rbrack; Aggiungi nuovo strumento per creare tracciati pieni
* Miglioramenti al tracciato
* &lbrack;Path&rbrack; Crea un tracciato che si aggancia ai poligoni
* &lbrack;Path&rbrack; Consenti di cambiare i tipi di percorso
* &lbrack;Path&brack; Consenti di copiare e incollare i dati dei vertici del tracciato tra contenuto e maschera
* &lbrack;Path&rbrack; Consenti di vincolare l&#39;angolo durante la creazione di un nuovo punto
* &lbrack;Path&rbrack; Consenti di vincolare la creazione di punti a una linea
* &blocco;Tracciato&rbrack; Chiudi forma con un solo clic
* &lbrack;Path&rbrack; Visualizza informazioni sul percorso
* &blocco;Tracciato&rbrack; Consenti di ridimensionare e ruotare i vertici del tracciato
* &lbrack;Path&rbrack;&lbrack;UX&rbrack; Semplificare l&#39;accesso ai gizmo di trasformazione
* &blocco;Tracciato&rbrack; Aggiungi anteprima tracciato
* &blocca;Tracciato&rbrack; disattiva l&#39;anteprima del tracciato con Maiusc + P
* &lbrack;Path&rbrack; Migliora l&#39;edizione tangente dalla vista laterale
* &lbrack;Tracciato&rbrack; Consenti di concentrarsi su un tracciato 3D
* &lbrack;Path&brack; I vertici devono mantenere lo stato di selezione quando si attiva e disattiva l&#39;interfaccia utente
* &lbrack;Path&rbrack; Consente di eliminare il percorso utilizzando Backspace
* &lbrack;Path&rbrack; Mantieni aperto l&#39;elenco dei percorsi se l&#39;utente lo espande
* &lbrack;Path&rbrack;&lbrack;Pila livelli&rbrack; rinominare correttamente i duplicati quando si copia o incolla
* &lbrack;Path&brack; miglioramenti all&#39;interfaccia utente e alla descrizione comandi
* Prestazioni
* &lbrack;Prestazioni&rbrack; Migliora le prestazioni della finestra della vista quando si utilizza un livello di tassellatura elevato
* &lbrack;Prestazioni&rbrack; Abilita solo il primo canale sui nuovi livelli di riempimento/effetti
* &lbrack;Prestazioni&rbrack; Calcolo del tratto pennello in parallelo
* Baking
* &lbrack;Esegue i baking&rbrack; Aggiungi nuova opzione di generazione gabbie completamente automatica per eseguire i baking con trame ad alto poli (sperimentale)
* Contenuti
* &lbrack;Content&rbrack; Aggiungi 6 nuovi filtri: stilizzazione, quantizzazione, kuwahara anisotropo, smusso uniforme, distanza direzionale, conversione scala di grigi
* &lbrack;Content&rbrack; aggiorna Disturbi e Grunge alla versione più recente di Designer (con il nuovo Voronoi 2D)
* &lbrack;Content&rbrack; Aggiungi 3 nuovi generatori di texture (Affianca casuale, Triangle Grid, Generatore Scratches)
* &lbrack;Content&rbrack; Rinomina il modello di motore originale ed esporta i predefiniti
* Python
* &lbrack;Shelf&rbrack;&lbrack;Python&rbrack; Salva materiale avanzato o maschera avanzata su disco da Python
* &lbrack;Python&rbrack; Aggiungi gabbia automatica eseguente i baking all&#39;API Python
* &lbrack;Python&rbrack; Consente di modificare i nomi e le descrizioni di set di texture/Porzioni UV
* &lbrack;Python&rbrack; Condivisione delle impostazioni di risoluzione su sorgenti vettoriali e di font
* &lbrack;Auto-update&rbrack;&lbrack;Python&rbrack; Esposizione delle funzionalità di aggiornamento automatico del progetto in Python
* Varie
* &lbrack;Esporta&rbrack; Semplifica l’accesso alle opzioni di invio con un nuovo pannello
* &lbrack;Nvidia&rbrack; Aggiungi avviso sui driver Nvidia più recenti (572.16)
* L’aggancio dell’angolo deve essere influenzato dalla selezione dello spazio Oggetto/Mondo
* &lbrack;Elenco set di texture&rbrack; consente di aggiungere un nome personalizzato alle Porzioni UV e di utilizzarle all&#39;esportazione
* Mac
* &lbrack;Mac&rbrack; Utilizzare Metal invece di OpenGL per il rendering grafico
* &lbrack;Mac&rbrack; Elimina supporto Mac

**Risolto**:

* &lbrack;Arresto anomalo&rbrack; Elimina input immagine
* Impossibile aggiungere smart mat tramite il pulsante Pila livelli
* &lbrack;Python&rbrack; Impossibile trovare gli effetti su GroupLayerNode

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;MacOS Intel&rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante
* &blocco;RedHat&rbrack; problemi relativi al selettore colore

## Versione 10

### 10.1.2

Data di pubblicazione: **2024/12/3** Riepilogo: **Versione secondaria, correzioni di bug**

**Risolto**:

* &lbrack;Arresto anomalo&rbrack; Elimina input immagine
* Impossibile aggiungere smart mat tramite il pulsante Pila livelli
* &lbrack;Python&rbrack; Impossibile trovare gli effetti su GroupLayerNode

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;MacOS Intel&rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante
* &blocco;RedHat&rbrack; problemi relativi al selettore colore

### 10.1.1

Data di pubblicazione: **2024/11/5** Riepilogo: **Versione secondaria, correzioni di bug**

**Aggiunto**:

* &blocco;Progetto&rbrack; mantieni aperto il progetto corrente fino a quando la nuova selezione del progetto non viene convalidata
* &lbrack;Srotolamento automatico&rbrack; densità texel consente di dividere meglio le Isole UV in UDIM
* &lbrack;Eseguite i baking&rbrack; Correggi copia ambigua nel menu di scelta rapida delle Mappe trama
* &lbrack;Altera&rbrack; rimuove il ridimensionamento nella finestra della vista per l&#39;asse Z (profondità)
* &lbrack;Import/Export&brack; Rimuovi il supporto per i formati di file immagine inutilizzati
* Aggiornamento della Substance Engine alla versione 9.1.4

**Risolto**:

* &lbrack;Arresto anomalo&rbrack; dopo il trasferimento della risorsa in Risorse e il salvataggio del progetto
* &lbrack;Arresto anomalo&rbrack; Problemi con la libreria aiserver
* &lbrack;Arresto anomalo&rbrack; arresto anomalo del server Illustrator in alcuni rari casi
* &lbrack;Arresto anomalo&rbrack; Quando si esce dall&#39;applicazione in alcuni rari casi
* Impossibile inviare report di arresto anomalo su alcuni computer
* &lbrack;Esegui i baking&rbrack; Il colore del vertice non viene letto correttamente
* &blocco;UI&rbrack; la posizione delle finestre e le novità all&#39;avvio vengono spostate
* &lbrack;Assimp&rbrack; StandardSurface di Maya non riconosciuto nella esegue i baking di ID
* &lbrack;Python&rbrack; La libreria SSL mancante genera un errore
* &lbrack;Python&rbrack;&lbrack;Win&rbrack; Errore durante la chiamata di QColorConstants.Transparent
* &lbrack;Python&rbrack; Le miniature dei livelli create tramite Python non si aggiornano finché non si fa clic all&#39;interno della Pila livelli
* &lbrack;Shader&rbrack; collegamento interrotto nel registro modifiche API shader
* &lbrack;Risorse 3D&rbrack; Usa le impostazioni proxy del sistema operativo per accedere alle Risorse 3D

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regressione&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;MacOS Intel&rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget che sembra eliminato tramite uno script funziona ancora
* &blocco;RedHat&rbrack; problemi relativi al selettore colore

### 10.1.0

Data di pubblicazione: **2024/09/17** Riepilogo: **Rilascio principale, nuovo contenuto: maschera area di riempimento/filtro colore, filtro decalcomania ricamo e sei filtri Substance generici, importazione di USD con proprietà di materiali e shader, miglioramento delle prestazioni, conformità della piattaforma VFX 2024 e migrazione a Linux RedHat**

**Aggiunto**:

* &blocco;Contenuto&rbrack; Aggiungi nuova maschera area di riempimento/filtro colore
* &lbrack;Content&rbrack; Aggiungi nuovo filtro decalcomania ricamo
* &lbrack;Content&rbrack; Aggiungi 6 nuovi filtri Substance generici (FXAA, pixelate, highpass, posterize, smoothstep, threshold)
* &lbrack;USD&rbrack; Esporta il livello USD con un materiale ASM definito
* &lbrack;USD&rbrack; Importa USD con proprietà di materiale e shader
* &lbrack;Prestazioni&rbrack; Abilita miniature Pila livelli ottimizzate per impostazione predefinita
* &lbrack;Prestazioni&rbrack; Riduci il tempo di apertura dei file di progetto e il consumo di memoria (decodifica dei dati)
* Conforme alla piattaforma VFX 2024
* &lbrack;VFX Platform 2024&rbrack; aggiornamento a Python 3.11
* &lbrack;VFX Platform 2024&rbrack; aggiornamento all&#39;OpenEXR 3.2
* &lbrack;VFX Platform 2024&rbrack; &lbrack;USD&rbrack; aggiornamento OpenSubdiv 3.6.0
* &lbrack;VFX Platform 2024&rbrack;&lbrack;Color Management&rbrack; Aggiornamento a OCIO 2.3.2
* &lbrack;Linux&rbrack; Migrazione a Linux RedHat
* &lbrack;Linux&rbrack; aggiornamento della versione minima del driver Nvidia a 535.171.04
* &lbrack;Import&rbrack; Aggiungi un&#39;opzione per capovolgere la mappa normale durante l&#39;importazione di una trama GLTF
* &lbrack;UI&rbrack; Utilizza il valore predefinito del sistema operativo per la distanza di rilevamento eventi trascinamento
* &lbrack;Substance Engine&rbrack; Aggiungi funzione di striscia di chiamata per rimuovere i simboli dall&#39;eseguibile
* &lbrack;Schermata iniziale&rbrack; Aggiornamento al nuovo formato della schermata iniziale
* Aggiornamento della Substance Engine alla versione 9.1.3
* &lbrack;Python&rbrack; Mostra collegamento agli esempi nel menu Pila livelli documentazione
* &lbrack;JavaScript&rbrack; Sposta i plug-in Javascript nella sottocartella javascript/plugins

**Risolto**:

* &lbrack;Illustrator&rbrack; Arresto anomalo di esportazione di una Porzione UV con grafica .ai in casi specifici
* &lbrack;Tratti dinamici&rbrack;&lbrack;Path&rbrack; Casuale per tratto non funziona su un tracciato
* &lbrack;UI&rbrack;&lbrack;Properties&rbrack; Il blocco è attivato quando l&#39;Affiancamento non è uniforme
* Il file TXT di debug viene creato quando si fa doppio clic su un progetto Painter
* &lbrack;USD&rbrack;&lbrack;Export&rbrack; Alcune texture potrebbero essere mancanti
* &lbrack;ASM&rbrack; il canale colore di dispersione ignora l&#39;effetto metallico
* &lbrack;Content&rbrack; Il filtro Sfocatura non funziona nello spazio colore &quot;di lavoro&quot;
* &lbrack;Contenuto&rbrack; Il filtro Regolazione Height modifica anche l&#39;alfa del livello

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Win&rbrack;&lbrack;Arresto anomalo&rbrack; &lbrack;ACE&rbrack; Non si utilizza lo spazio cromatico sRGB ICE per la Trasforma di visualizzazione
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;MacOS Intel&rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &lbrack;Arresto anomalo&rbrack; riposiziona risorsa e salva progetto
* &lbrack;Engine&rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &lbrack;Python&rbrack; Il widget fantasma viene eliminato da script ancora funzionante
* &blocco;RedHat&rbrack; problemi relativi al selettore colore

### 10.0.1

Data di pubblicazione: **2024/06/11** Riepilogo: **Versione secondaria, correzioni di bug**

**Aggiunto:**

* &lbrack;Libreria&rbrack; Converte i font Substance in normali file di font
* &lbrack;Illustrator&rbrack;&lbrack;SVG&rbrack; Assegna alle miniature nella selezione dell&#39;ambito uno sfondo grigio chiaro
* &lbrack;Python&rbrack; Aggiungi funzione sull&#39;origine bitmap per elencare gli spazi colore disponibili

**Risolto**:

* &lbrack;Pila livelli&rbrack; cartella sempre chiusa quando viene spostata all&#39;interno o all&#39;esterno di altre cartelle
* &lbrack;Salva&rbrack; Il file di progetto viene perso quando &quot;salva come copia&quot; o il salvataggio automatico non riesce in casi specifici
* &lbrack;Import&rbrack; Risorse con lo stesso nome ma estensioni diverse vengono sostituite
* &lbrack;Properties&rbrack; Impostazioni mancanti quando si utilizza un punto di ancoraggio negli input dell&#39;immagine
* &lbrack;Illustrator&rbrack; Impossibile importare i file Illustrator dopo l&#39;arresto anomalo del server senza riavviare Painter
* &lbrack;Python&rbrack; Impossibile impostare l&#39;istanza padre con il tipo &quot;properties&quot;
* &lbrack;Python&rbrack; Se si imposta il poly alto come parametro eseguente i baking, il poly alto non viene caricato
* &lbrack;Python&rbrack; Messaggio di errore per set_color_space() troppo generico
* &lbrack;Python&rbrack; Le origini di riferimento consentono di creare cicli

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;MacOS Intel&rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &lbrack;Illustrator&rbrack; Arresto anomalo di esportazione di una Porzione UV con grafica .ai in casi specifici
* &lbrack;Tratti dinamici&rbrack;&lbrack;Path&rbrack; Casuale per tratto non funziona su un tracciato

### 10.0.0

Data di pubblicazione: **2024/05/16** Riepilogo: **Versione principale, edizione di Pila livelli con API Python, lettura dei file nativi di Illustrator, integrazione di Risorse 3D e nuova risorsa di testo**

**Aggiunto**:

* &lbrack;Illustrator&rbrack; Utilizzo dei file Illustrator con le tavole da disegno in Painter
* &lbrack;Illustrator&rbrack;&lbrack;SVG&rbrack; Aggiungi anteprime nella selezione dell&#39;ambito
* &lbrack;Substance 3D Assets&rbrack; Sfoglia, seleziona e scarica risorse 3D direttamente in Painter
* &lbrack;Substance 3D Assets&rbrack;&lbrack;UI&rbrack; Nuovo pannello
* &lbrack;Substance 3D Assets&rbrack; Supporta mappe e materiali dell&#39;ambiente
* &lbrack;Substance 3D Assets&rbrack; Consenti di ricaricare, spostarsi e aprire la cartella della posizione nel nuovo pannello Substance 3D Assets
* &lbrack;Substance 3D Assets&rbrack; aggiunta di un gestore di download
* &laback;Text Resource&brack; Consenti l&#39;utilizzo di font incorporabili
* &blocco;Risorsa di testo&rbrack; Consenti il rendering di un font/testo su una trama
* &lbrack;Text Resource&rbrack; visualizza i font dell&#39;utente e di altri tracciati condivisi nel pannello Risorse con una nuova categoria
* &lbrack;Text Resource&rbrack;&lbrack;Properties&rbrack; Aggiungi il supporto per le proprietà avanzate dei font
* &lbrack;Text Resource&rbrack; Consenti di cercare/visualizzare i font nei mini-scaffali
* &lbrack;Text Resource&rbrack; Aggiungi messaggio/finestra di dialogo di errore durante l&#39;importazione di un font incompatibile
* Varie
* &lbrack;Riempi proiezione&rbrack; Migliora il comportamento del manipolatore Scala quando si utilizzano valori di piccole dimensioni
* &lbrack;Manipolatori&rbrack; Aggiungi nuova modalità precisa quando si preme la scelta rapida da tastiera CTRL
* &lbrack;Manipolatore&rbrack; Migliora la stabilità del manipolatore di superfici durante la traduzione
* &lbrack;Export&rbrack; Aggiungi nome spazio colore negli output SBSAR
* &lbrack;Prestazioni&rbrack; Migliora il tempo di individuazione delle librerie delle risorse su disco
* &lbrack;Substance&rbrack; aggiornamento al motore di Substance versione 9.1.2
* &lbrack;Drag and Drop&brack; Allinea la rotazione della decalcomania alla videocamera quando viene rilasciata nella finestra della vista
* &lbrack;Python&rbrack; edizione della Pila livelli
* &lbrack;Python&rbrack; Consenti di selezionare livello, effetto, maschera, maschera geografica nell&#39;interfaccia utente
* &lbrack;Python&rbrack; Consenti di ottenere/impostare i metodi di fusione dei livelli
* &lbrack;Python&rbrack; Consenti di ottenere/impostare le impostazioni di proiezione del livello di riempimento
* &lbrack;Python&rbrack; Consenti di eseguire query sul colore del materiale della Substance da un livello di riempimento
* &lbrack;Python&rbrack; Consenti di eseguire query e impostare colori uniformi e risorse in livelli ed effetti
* &lbrack;Python&rbrack; Consenti di creare e modificare risorse di testo in Pila livelli
* &lbrack;Python&rbrack; Consente di modificare i canali attivi su livelli ed effetti
* &lbrack;Python&rbrack; Consenti alle azioni in batch di avere un singolo annullamento/ripetizione
* &lbrack;Python&rbrack; consente di caricare/modificare i parametri di origine vettoriale
* &lbrack;Python&rbrack; Consente di modificare le proprietà dei colori dei livelli e degli effetti con la gestione del colore
* &lbrack;Python&rbrack; Consenti di eseguire query e creare livelli istanziati
* &lbrack;Python&rbrack; Consenti di aggiungere l&#39;effetto di selezione colore
* &lbrack;Python&rbrack; Consenti di controllare la gestione del colore dell&#39;immagine bitmap
* &lbrack;Python&rbrack; consente di mettere in pausa/rimettere in pausa il motore
* &lbrack;Python&rbrack; Consenti di passare ai nodi di pari livello e padre
* &lbrack;Python&rbrack; Consente di creare un effetto filtro/generatore
* &lbrack;Python&rbrack; Consenti di aggiungere effetto livello
* &lbrack;Python&rbrack; Consenti di aggiungere maschera avanzata a un livello
* &lbrack;Python&rbrack; consente di creare/modificare punti di ancoraggio
* &lbrack;Python&rbrack; Consenti di ottenere/impostare la maschera sui livelli
* &lbrack;Python&rbrack; Consente di creare un effetto maschera di confronto
* &lbrack;Python&rbrack; Consenti di eseguire query e utilizzare i predefiniti dalle risorse Substance
* &lbrack;Python&rbrack; Consenti di elencare i predefiniti e i relativi valori tramite la funzione internal_properties per le risorse Substance
* &lbrack;Python&rbrack; Consenti di elencare i predefiniti di esportazione predefiniti
* &lbrack;Python&rbrack; Consenti di elencare i predefiniti di esportazione disponibili nella libreria
* &lbrack;Python&rbrack; Consente di recuperare il contenuto dei predefiniti di esportazione

**Risolto**:

* &lbrack;Arresto anomalo&rbrack; annullamento di &quot;Rimuovi istanza shader&quot; con Ctrl-Z
* &lbrack;Arresto anomalo&rbrack; Crea un livello su una pila vuota se l&#39;ultima selezione era un effetto
* &lbrack;SVG&rbrack; Problema con il valore personalizzato dell&#39;area ritagliata
* &lbrack;Srotolamento automatico&rbrack; se si ricalcola solo l&#39;impacchettamento senza modificare l&#39;orientamento UV, si verifica l&#39;arresto anomalo
* &lbrack;Drag&amp;drop&brack; Il ritardo dovuto alle risorse esterne viene precaricato più volte
* &lbrack;UI&rbrack; se si trascina la miniatura della risorsa, il messaggio di avviso nella Pila livelli può essere nascosto
* &lbrack;Performance&brack; I riquadri UV mascherati sono ancora calcolati
* &lbrack;USD&rbrack; Evidenziazione errata per selezione ambito
* &lbrack;Risorsa&rbrack; L&#39;immagine bitmap viene danneggiata dopo aver colorato nel canale normale e salvato il progetto
* &lbrack;USD&rbrack; supporta l&#39;ordinamento dei vertici mancini
* &lbrack;Substance&rbrack; Ripristina valori predefiniti torna sempre a zero per il widget Angolo
* &lbrack;Engine&rbrack; Colorare con un SVG in uno stencil non funziona
* &lbrack;Motore&rbrack; Mappa normale interruzione tratti pennello dopo un annullamento
* &lbrack;Content&rbrack; La fusione alfa e lo spazio cromatico dell&#39;elemento grafico nel Filtro materiale non sono corretti
* &lbrack;Content&rbrack; I metodi di fusione sul Tile Generator non funzionano
* &lbrack;Content&rbrack; Il filtro di scansione Istogramma produce in alcuni casi bande
* &lbrack;Content&rbrack; illuminazione Eseguita i baking stilizzata non tiene conto del height dipinto
* &lbrack;Python&rbrack; errore imprevisto durante il recupero delle informazioni sui livelli istanziati dopo la modifica dello shader
* &lbrack;Salva&rbrack; Il file di progetto viene perso quando &quot;salva con nome&quot; non riesce in casi specifici

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Arresto anomalo&rbrack;&lbrack;Linux&rbrack;&lbrack;AMD&rbrack; Trascinamento delle risorse in Pila livelli su Wayland OS
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent
* &lbrack;Save&rbrack; Il file di progetto Spp viene perso quando l&#39;operazione &quot;Salva come copia&quot; non riesce in casi specifici
* &lbrack;MacOS Intel&rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &lbrack;Illustrator&rbrack; Impossibile importare i file Ai dopo l&#39;arresto anomalo del server senza riavviare Painter
* &lbrack;Import&rbrack; Risorse con lo stesso nome ma estensioni diverse vengono sostituite

## Versione 9

### 9.1.2

Data di pubblicazione: **2024/01/30** Riepilogo: **Versione secondaria, correzioni di bug**

**Aggiunto**:

* &lbrack;Prestazioni&rbrack; Migliora il tempo di creazione del primo livello di riempimento nei nuovi progetti
* &lbrack;Performance&rbrack; Riduci il tempo di caricamento di mappe dell&#39;ambiente pesanti
* &lbrack;Substance&rbrack; consente di salvare/chiudere i progetti anche quando vengono generate miniature

**Risolto**:

* Il salvataggio non riesce sui progetti della versione precedente quando la finestra della vista viene modificata
* &lbrack;Arresto anomalo&rbrack; reimportazione della trama quando si utilizza la gestione personalizzata degli oggetti AO e del colore
* &lbrack;Riempi proiezione&rbrack; Facendo clic sul manipolatore Scala viene visualizzato il messaggio &quot;non colorabile&quot;
* &lbrack;Brush&brack; se si utilizza l&#39;allineamento UV si verificano artefatti
* &lbrack;Pila livelli&rbrack; La ridenominazione del livello è lenta quando la pila è molto lunga
* &lbrack;Pila livelli&rbrack; Messaggio di errore non corretto quando si utilizza un filtro incompatibile nella maschera
* &lbrack;Pila livelli&rbrack; dopo l&#39;eliminazione, la selezione torna al livello superiore
* &lbrack;Export&rbrack; La texture normale generata è sempre in modalità di riempimento Vicina spazio 3D
* &lbrack;Esporta&rbrack; Texture alfa non viene generato con il predefinito di esportazione vista 2D
* &lbrack;Export&rbrack; L&#39;esportazione SBSAR presenta utilizzi errati con mappe convertite
* &lbrack;Shader&rbrack; Il registro modifiche API shader non è aggiornato con le ultime modifiche ASM

**Problemi noti**:

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Arresto anomalo&rbrack;&lbrack;Linux&rbrack;&lbrack;AMD&rbrack; Trascinamento delle risorse in Pila livelli su Wayland OS
* &lbrack;Regression&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &lbrack;Arresto anomalo&rbrack;&lbrack;Python&rbrack; esportazione USD attivata da TextureStateEvent

### 9.1.1

Data di pubblicazione: **2023/12/05** Riepilogo: **Versione secondaria, correzioni di bug e invio alla funzionalità After Effects**

**Aggiunto:**

* &lbrack;Interop&rbrack; Consenti di inviare una trama con texture ad After Effects (Ae 24.1)

**Corretto:**

* &lbrack;Fill&rbrack; UV impostato sulla proiezione del set UV non legge più di 2 set UV
* &lbrack;Arresto anomalo&rbrack; Utilizzo della mappa dell&#39;ambiente a 16 K
* &lbrack;Arresto anomalo&rbrack; Exr utilizzato come input dell&#39;immagine
* &lbrack;Arresto anomalo&rbrack; Copia e incolla percorsi tra progetti
* &lbrack;QoL&rbrack; con trascinamento della risorsa Alpha in modalità decalcomania si crea Proiezione UV nella maschera
* &lbrack;Path&rbrack; La copia dei vertici dei tracciati rinomina anche il tracciato di destinazione alla riapertura del progetto
* &lbrack;Linux&rbrack; La selezione del colore può essere interrotta con più schermate
* &lbrack;Auto Unwrap&rbrack; problema dell&#39;interfaccia utente per il controllo della densità del testo
* &lbrack;Color Management&rbrack; Il feedback dell&#39;interfaccia utente è appropriato per le esigenze, ma il motore non lo è
* &lbrack;Gestione colore&rbrack; selezione errata dello spazio colore nella maschera con override dei dati utente

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Arresto anomalo&rbrack;&lbrack;Linux&rbrack; con Linux Wayland su AMD quando si trascina e si rilascia la risorsa nella Pila livelli
* &lbrack;Arresto anomalo&rbrack;&lbrack;Mac&rbrack; Modifica del valore di filtro anisotropo nel sistema operativo Monterey
* &lbrack;Regressione&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sullo schermo hd
* &lbrack;Python&rbrack; Arresto anomalo di esportazione dell&#39;USD attivata da TextureStateEvent

### 9.1.0

Data di pubblicazione: **2023/11/07** Riepilogo: **Versione principale che introduce il supporto per SVG e trasparenza, oltre a miglioramenti dello strumento di trascinamento della selezione**

**Aggiunto:**

* &lbrack;SVG&rbrack; Consenti importazione file vettoriali (SVG)
* &lbrack;SVG&rbrack;&lbrack;UI&rbrack; Aggiungi il supporto per le proprietà specifiche dei SVG
* &lbrack;SVG&rbrack; Aggiungi un&#39;opzione per mantenere facilmente le proporzioni originali dell&#39;immagine
* &lbrack;SVG&rbrack; Consenti l&#39;utilizzo automatico dell&#39;alfa di SVG con trasparenza
* &lbrack;Interop&rbrack; Consenti di inviare una trama con texture ad After Effects (Ae 24.1 beta)
* &lbrack;Interop&rbrack; Aggiungi impostazioni per Invia a After Effects
* &lbrack;QoL&rbrack;&lbrack;Assets&rbrack;&lbrack;UI&rbrack; Importa automaticamente risorsa durante il trascinamento nello slot dell&#39;interfaccia utente
* &lbrack;QoL&rbrack; Consenti di trascinare e rilasciare risorse esterne nella Pila livelli
* &lbrack;QoL&rbrack;&lbrack;Pila livelli&rbrack; Trascina la texture dal pannello Risorse alla Pila livelli
* &lbrack;QoL&rbrack;&lbrack;Viewport&rbrack; Consente di trascinare e rilasciare il generatore, filtri sulla trama
* &lbrack;QoL&rbrack;&lbrack;Viewport&rbrack; Consenti di rilasciare le risorse esterne nella trama
* &lbrack;QoL&rbrack;&lbrack;Projection&rbrack; Aggiungi un nuovo set UV alla modalità di proiezione con impostazione UV
* &lbrack;QoL&rbrack; Trascina la Maschera avanzata come nuovi livelli nella finestra della vista e nella Pila livelli
* &lbrack;QoL&rbrack; Aggiungi selettore per i generatori con più output quando utilizzati nella maschera
* &lbrack;QoL&rbrack; Consente di trascinare e rilasciare immagini di un singolo canale su un effetto di riempimento
* &lbrack;QoL&rbrack;&lbrack;Pila livelli&rbrack; Utilizzare i modificatori CTRL/ALT con trascinamento per specificare dove/come creare effetti/livello
* &blocco;Tracciato&rbrack; Attiva/disattiva la visibilità dei tracciati singolarmente nel pannello Tracciato
* &lbrack;Path&rbrack; Consenti l&#39;utilizzo di manipolatori di trasformazione per i punti di tracciato
* &lbrack;Path&rbrack; Consenti di controllare manualmente le tangenti per vertice
* &blocca;Tracciato&rbrack; copia/incolla proprietà tracciato
* &lbrack;Path&rbrack; Introduce una scelta rapida da tastiera vuota per il pulsante Tangente di interruzione
* &lbrack;Shader&rbrack; Aggiungi il supporto per Opacità e Traslucidità in shader ASM
* &lbrack;Shader&rbrack; Aggiungi supporto per il canale di Colore di assorbimento con shader ASM
* &lbrack;Shader&rbrack; suggerimenti per migliorare i parametri di shader ASM
* &lbrack;Shader&rbrack; Cambia il colore predefinito del canale della Traslucidità in nero
* &lbrack;Impostazioni di visualizzazione&rbrack; Attiva Anti-alias temporale per impostazione predefinita
* &lbrack;Impostazioni di visualizzazione&rbrack; Attiva impostazione di dispersione sotto superficie per impostazione predefinita
* &lbrack;Substance&rbrack; Aggiungi il supporto per la proprietà ColorSpace dall’input/output del grafico
* &lbrack;Substance&rbrack; Aggiorna il motore di Substance alla versione 9.0.3
* &lbrack;UI&rbrack; Rendi accessibile il pulsante contestuale della barra degli strumenti anche se la finestra dell&#39;app è piccola
* &lbrack;Auto Unwrap&rbrack; controlla il numero di Porzione UV con densità texel
* &lbrack;Eseguite i baking&rbrack; Disattiva Raytracing GPU su GPU AMD per impostazione predefinita
* &lbrack;Performance&rbrack; Applica la compressione senza perdita di dati alle immagini a 16 bit per ridurre l&#39;ingombro del progetto
* &lbrack;Python&rbrack; Consente di manipolare la videocamera predefinita in vista 3D
* &lbrack;Python&rbrack; Esporta la possibilità di esportare trama tramite script
* &lbrack;Content&rbrack;&lbrack;Samples&rbrack; Aggiungi nuovo progetto di esempio &quot;French Restaurant Table&quot;
* &lbrack;Content&rbrack; Aggiorna Substance logo alfa alla nuova versione
* &lbrack;Content&rbrack; Aggiungi tre filtri di materiale focalizzati sulle SVG (Adesivo personalizzato, Spruzzo personalizzato e Grafica su materiale)

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; modifica delle dimensioni del manipolatore quando non si utilizza lo strumento simmetria
* &lbrack;Arresto anomalo&rbrack; &lbrack;Pila livelli&rbrack; Creazione del livello quando non è selezionato nulla
* &lbrack;Project&rbrack; Le mappe trama possono essere danneggiate dopo la rimozione di risorse inutilizzate
* &lbrack;Project&rbrack; danneggiamento delle risorse dopo la reimportazione o la esegue i baking dell&#39;immagine
* &lbrack;Assets&rbrack; Il ricaricamento di una risorsa la rimuove dai Preferiti
* &lbrack;Import&rbrack; Impossibile importare risorse quando nel pannello delle risorse è presente l&#39;indicazione &quot;Nessun risultato trovato&quot;
* &lbrack;UI&rbrack; In alcuni casi la freccia contestuale della barra degli strumenti non viene visualizzata
* &lbrack;Substance&rbrack; Il pulsante affiancato per i valori booleani non è supportato
* &lbrack;Level&brack; etichetta di canale errata quando utilizzato nella maschera
* &lbrack;Export&rbrack;&lbrack;glTF&rbrack; i file glTF/GLB esportati da Painter non hanno un&#39;unità di dimensioni fisiche
* &lbrack;Content&rbrack; l&#39;intensità del filtro Sfocatura è bloccata su 16
* &lbrack;Content&rbrack; l&#39;input dell&#39;immagine &quot;colore di destinazione&quot; del filtro Corrispondenza colori non è visibile

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Arresto anomalo&rbrack;&lbrack;Linux&rbrack; con Linux Wayland su AMD quando si trascina e si rilascia la risorsa nella Pila livelli
* &lbrack;Arresto anomalo&rbrack;&lbrack;Mac&rbrack; Modifica del valore di filtro anisotropo nel sistema operativo Monterey
* &lbrack;Arresto anomalo&rbrack; Exr utilizzato come input dell&#39;immagine
* &lbrack;Arresto anomalo&rbrack; Utilizzo della mappa dell&#39;ambiente a 16 K
* &lbrack;Auto Unwrap&rbrack; problema dell&#39;interfaccia utente per il controllo della densità del testo
* &lbrack;Regressione&rbrack;&lbrack;UI&rbrack; Il menu di scelta rapida è troppo piccolo sullo schermo hd
* &lbrack;Python&rbrack; Arresto anomalo di esportazione dell&#39;USD attivata da TextureStateEvent
* &lbrack;QoL&rbrack; con trascinamento della risorsa Alpha in modalità decalcomania si crea Proiezione UV nella maschera

### 9.0.1

Data di pubblicazione: **2023/09/19** Riepilogo: **Versione del bug minore con diversi miglioramenti**

**Aggiunto:**

* &lbrack;Import&rbrack; Imposta posizione di importazione predefinita nella finestra di importazione
* &lbrack;Modalità di Esegue i baking&rbrack; Consenti di ripristinare i parametri ai valori predefiniti
* &lbrack;Esegui i baking&rbrack; Imposta la risoluzione della esegue i baking su pittura durante la creazione di un progetto
* &lbrack;Simmetrie&rbrack; Rimuovi associazione manipolatore specifico della simmetria dalla scelta rapida da tastiera Q
* &lbrack;Menu&rbrack; Aggiungi l’opzione &quot;mostra registro&quot; nel menu Aiuto
* &lbrack;Riquadro di visualizzazione&rbrack; Migliora la velocità di rendering delle ombre
* &lbrack;Substance&rbrack; Aggiorna il motore alla versione 9.0.1
* &lbrack;Color Management&rbrack; Il file di configurazione OCIO può avere qualsiasi tipo di estensione
* &lbrack;Assets&rbrack; La risorsa Sbsar con utilizzo &quot;decalcomania&quot; deve essere impostata automaticamente su altera proiezione
* &lbrack;Path&brack; Visualizza un messaggio quando tenti di interagire con lo strumento Tracciato mentre interfaccia utente e Gizmo sono nascosti

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; Alt + trascinamento sul pannello Tracciato
* &lbrack;Importa risorse&rbrack; arresto anomalo casuale durante la rimozione delle risorse da importare
* Arresto anomalo durante l&#39;importazione di un file GLB compresso
* Problema durante la pittura su trame che condividono UV
* Flash di trama nero durante il ricalcolo o il caricamento della cache
* &lbrack;Proprietà&rbrack; Il menu di scelta rapida per reimpostare i parametri non viene visualizzato nei menu a discesa
* &lbrack;Level&brack; cursori di input bloccati dal livello precedente
* &lbrack;AMD&rbrack;&lbrack;Sparse&rbrack; opzione SVT se attivata genera artefatti
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Arresto anomalo quando si fa doppio clic sui vertici
* &lbrack;Path&rbrack; interfaccia utente e percorso visibili in modalità di esegue i baking
* &lbrack;AMD&rbrack; Texture persa durante la riproduzione con visibilità
* &lbrack;Sparse&rbrack; Risoluzione troppo bassa quando si ruota la trama

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

### 9.0.0

Data di pubblicazione: **2023/06/20** Riepilogo: **Versione principale con Pittura lungo il percorso che consente curve 3D, nuovi materiali di base e la pulizia dei materiali legacy e nuovi predefiniti per curve 3D**

**Aggiunto:**

* &lbrack;Path&rbrack; Aggiungi nuova Pittura lungo il tracciato, strumento
* &lbrack;Path&rbrack; Aggiungi una scelta rapida da tastiera vuota per lo strumento tracciato
* &lbrack;Path&brack; Consenti di aggiungere nuovi punti a un percorso esistente
* &lbrack;Path&rbrack; Aggiungi scelta rapida da tastiera per uscire dalla creazione del percorso corrente
* &lbrack;Tracciato&rbrack; Consente di modificare le proprietà del pennello per i tracciati
* &lbrack;Tracciato&rbrack; Regola automaticamente le tangenti durante il posizionamento di un punto
* &lbrack;Path&brack; Ricalcola tangenti quando si sposta un punto
* &lbrack;Tracciato&rbrack; aggancia i punti appena creati alla superficie di una trama
* &lbrack;Path&rbrack; Consenti modifica pressione per vertice
* &lbrack;Tracciato&rbrack; Regola la pressione del punto appena creato dai punti vicini
* &lbrack;Tracciato&rbrack; Consenti di convertire i punti in punti morbidi/d&#39;angolo (interruzione tangente)
* &blocco;Tracciato&rbrack; Consenti di spostare immediatamente un punto appena aggiunto
* &lbrack;Path&rbrack; consente di rimuovere punti dal percorso esistente
* &lbrack;Tracciato&rbrack; Consenti di invertire la direzione di un tracciato
* &lbrack;Path&rbrack; Consenti di selezionare un percorso nella finestra della vista
* &lbrack;Tracciato&rbrack; Consenti di selezionare punti di tracciato con selezione
* &lbrack;Tracciato&rbrack; Introduce le scelte rapide CTRL-A per selezionare tutti i punti di un tracciato
* &lbrack;Path&rbrack; Consenti di chiudere il percorso
* &lbrack;Path&rbrack; Consenti di specificare l&#39;asse del tracciato in Proprietà
* &lbrack;Path&brack; Aggiungi un menu di controllo dei vertici alla barra degli strumenti contestuale
* &lbrack;Path&rbrack; Introdurre le modalità pittura/Cancella/Sfumino allo strumento tracciato
* &lbrack;Path&brack; Crea un feedback visivo per i tracciati nella finestra della vista
* &lbrack;Path&brack; Aggiungi un indicatore visivo per la direzione del tracciato
* &lbrack;Path&rbrack; Aggiungi thickness di linee alle impostazioni di visualizzazione del tracciato
* &lbrack;Path&brack; Consenti di nascondere l&#39;interfaccia utente dei percorsi
* &lbrack;Path&brack; Aggiungi pannello Tracciato per elencare i tracciati del livello attualmente selezionato
* &blocco;Tracciato&rbrack; Aggiungi feedback visivo quando si passa il cursore su un tracciato nel pannello Tracciato
* &lbrack;Tracciato&rbrack; Visualizza il pannello dei tracciati ogni volta che è selezionato lo strumento Tracciato
* &blocco;Tracciato&rbrack; consente di rinominare, eliminare, copiare, tagliare, duplicare il tracciato nel pannello Tracciato
* &lbrack;Path&rbrack; Visualizza il messaggio quando si tenta di interagire nella finestra della vista 2D con lo strumento Tracciato
* &lbrack;Libreria&rbrack; Integrazione di nuovo contenuto (strumenti e materiali di base di tracciati)
* &lbrack;Tratti dinamici&rbrack; Aggiungi proprietà distanza per tratti dinamici
* &lbrack;Tratti dinamici&rbrack; Aggiungi proprietà di dimensione e spaziatura ai tratti dinamici
* &lbrack;Tratti dinamici&rbrack; Aggiungi proprietà inizio/centro/fine per tratti dinamici
* &lbrack;Python&rbrack;&lbrack;USD&rbrack; Esposizione dei parametri di configurazione del progetto per il formato USD
* &lbrack;Python&rbrack;&lbrack;USD&rbrack; Esposizione dei parametri di creazione del progetto per il formato USD
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; Aggiungi informazioni sul percorso del progetto all&#39;interno del file USD esportato
* &lbrack;GLTF&rbrack; Aggiorna texture nella libreria durante il ricaricamento di un file GLTF
* &lbrack;Shader&rbrack; Riduci artefatti di giuntura per Isole UV con orientamento diverso
* &lbrack;Engine&rbrack; Aggiornamento al motore di Substance versione 9.0

**Corretto:**

* &lbrack;Import&rbrack; Alcuni GLB con texture non ottengono texture in Painter
* &lbrack;AMD&rbrack; artefatti sui bordi per tutti i riempimenti di proiezione 3D
* &lbrack;Engine&rbrack; Texture interrotta quando si attiva o disattiva la visibilità del livello
* &lbrack;Engine&rbrack; Le Texture sono vuote in alcuni punti durante la modifica del metodo di fusione
* &lbrack;Engine&rbrack; Texture/Proiezione in alcuni casi è la modalità di alterazione vuota
* &lbrack;Iray&rbrack; Iterazione reimpostata su 0 durante il salvataggio del rendering
* &lbrack;Log&rbrack; messaggio di errore USD quando si esegue File > Nuovo

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Pila livelli&rbrack; sorgente di input non salvata per livello

## Versione 8

### 8.3.1

Data di pubblicazione: **2023/04/27**

**Aggiunto:**

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi scelta rapida da tastiera (vuota) per mostrare/nascondere la visualizzazione della finestra della vista
* &lbrack;Modalità Eseguita i baking&rbrack; Mostra sempre Low Poly quando si utilizza il pulsante &quot;Nascondi trame eseguite i baking&quot;
* &lbrack;Modalità di Esegue i baking&rbrack; Mostra suffisso per corrispondenza per nome in base al set di texture corrente
* &lbrack;Import&rbrack; Aggiungi supporto per file binari GLTF (glb)
* &lbrack;Elenco set di texture&rbrack; Aggiungi menu per selezionare o creare istanze shader
* &lbrack;Elenco set di texture&rbrack; consente di modificare rapidamente il set di texture e la risoluzione delle Porzioni UV
* &lbrack;Dimensioni fisiche&rbrack; Migliora il comportamento del manipolatore quando si utilizza dimensioni fisiche in Proiezione UV
* &lbrack;UI&rbrack; Ripristina &quot;Salva con nome&quot; nel menu File principale
* &lbrack;UI&rbrack; Salva selezione visualizzazione (solo 2D, solo 3D, entrambi) nel layout dell&#39;interfaccia utente
* &lbrack;USD&rbrack; Messaggio di errore meno vago durante la creazione del progetto con forme USD non supportate
* &lbrack;Python&rbrack; Aggiungi eventi di eseguita i baking per seguire l&#39;avanzamento della Esegue i baking
* &lbrack;Python&rbrack; Consenti di annullare un eseguo i baking
* &lbrack;Python&rbrack; Esposizione &quot;In base al modello di output&quot; per Tipo di file e Profondità di bit nell&#39;esportazione
* &lbrack;Python&rbrack; tempo di aggiornamento espositivo per TextureStateEvent.Update

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; arresto anomalo raro alla chiusura di un progetto
* &lbrack;Arresto anomalo&rbrack; &lbrack;Esegui i baking&rbrack; Attiva la sincronizzazione della mappa trama con il Height o la curvatura in un progetto specifico
* &lbrack;Arresto anomalo&rbrack;&lbrack;Scripting&rbrack; Arresto anomalo durante l&#39;aggiunta di un materiale dopo la creazione dell&#39;istanza shader
* &lbrack;Modalità di Esegue i baking&rbrack; L&#39;intensità di AO nel materiale neutro non ha effetto
* &lbrack;Modalità Esegue i baking&rbrack; Arresto anomalo quando si passa alla modalità esegue i baking prima che il modello venga caricato
* &lbrack;Modalità di Esegue i baking&rbrack; Messaggio di errore mancante nella scheda Esegue i baking processo
* &lbrack;Modalità di Esegue i baking&rbrack; le impostazioni dei materiali neutri non hanno effetto dopo la reimportazione di una trama
* &lbrack;Modalità di Esegue i baking&rbrack; il separatore del riquadro di visualizzazione viene salvato globalmente e non per modalità
* &lbrack;Modalità di Esegue i baking&rbrack; Problema di visualizzazione: la normale media non modifica la superficie della gabbia
* &lbrack;Color Management&rbrack; l&#39;impostazione Rileva automaticamente spazio colore è disattivata quando è presente OCIO env var
* &lbrack;Content&rbrack; Il filtro Contorno maschera ha un artefatto con input height
* &lbrack;Content&rbrack; il cursore intensità filtro sfocatura Pendenza è bloccato su 1,0
* &lbrack;Interop&rbrack; impossibile creare il progetto con GLTF da Sampler
* &lbrack;Pila livelli&rbrack; Il valore dell&#39;Affiancamento di proiezione non viene aggiornato correttamente con manipolatore
* &lbrack;Linux&rbrack; scostamento tra la penna grafica del tablet e il cursore con HDPI superiore al 100%
* &lbrack;Python&rbrack; Arresto anomalo durante la reimportazione di una trama dopo la creazione di un progetto
* &lbrack;Substance&rbrack; i rumori 3D vengono interrotti dopo la reimportazione di una trama
* &lbrack;Porzione UV&rbrack; L&#39;offset per la Proiezione UV è bloccato su 1
* &lbrack;Riquadro di visualizzazione&rbrack; Il feedback visivo delle linee rette non è più visibile
* &lbrack;WhatsNew&rbrack; restituzione di riga non corretta per i titoli delle caratteristiche

**Problemi noti:**

* &lbrack;Import&rbrack; Alcuni GLB con texture non ottengono texture in Painter

### 8.3.0

*(Rilasciato: 10 gennaio 2023*)Riepilogo: **Versione principale con nuova modalità di esegue i baking, nuova importazione ed esportazione di file USD e supporto di dimensioni fisiche per Proiezione UV**

**Aggiunto:**

* &lbrack;Modalità di Esegue i baking&rbrack; Nuova modalità di esegue i baking dedicata alla esegue i baking

* &lbrack;Modalità Eseguita i baking&rbrack; Imposta la scelta rapida da tastiera per passare alla modalità eseguita i baking su F8

* &lbrack;Modalità di Esegue i baking&rbrack; pulsante Aggiungi inizio e Annulla esegue i baking nella finestra della vista

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi selezione eseguita i baking nell&#39;elenco Set di texture

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi nuova finestra Baker mappa trama per selezionare i baker

* &lbrack;Modalità Esegue i baking&rbrack; Aggiungi nuova finestra Impostazioni mappa trama per modificare le impostazioni di esegue i baking

* &lbrack;Modalità Esegue i baking&rbrack; Aggiungi nuova finestra Registro Esegue i baking per seguire la procedura di esegue i baking

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi parametri di esegue i baking e annulla azioni alla finestra della cronologia

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi breadcrumbs nelle impostazioni della mappa trama

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi miniature di mappe trama nella finestra Baker mappe trama

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi impostazioni di visualizzazione menu comprimibile nella finestra della vista 3D

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama High-Poly

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama della gabbia e il wireframe

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama a basso poli

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi impostazione di visualizzazione per mostrare i bordi netti senza giunture UV come errori

* &lbrack;Modalità di Esegue i baking&rbrack; informa nella finestra della vista della trama e esegue i baking gli errori se Esegue i baking registro non è visibile

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi azione per sincronizzare le impostazioni del baker tra tutti i set di texture

  Nella finestra Baker mappa trama, è possibile sincronizzare ciascun baker (e le impostazioni comuni) tra set di texture facendo clic sull’icona di collegamento accanto al nome del gruppo. Questa azione consente di aprire una finestra che consente di selezionare quali set di texture condivideranno gli stessi parametri.

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi azioni per copiare e incollare le impostazioni del baker

  Nella finestra Baker mappa trama sono disponibili le azioni per copiare e superare le impostazioni di ciascun baker nei set di texture, tramite il menu dedicato nella parte superiore della finestra o il menu di scelta rapida (clic con il pulsante destro del mouse).

* &lbrack;Modalità di Esegue i baking&rbrack; Pulsante Aggiungi in Esegue i baking registro per passare da un errore alle impostazioni corrette

  Quando un baker si guasta o una trama non viene caricata correttamente, nel Registro di Esegue i baking viene visualizzato un messaggio di errore. Un pulsante accanto al messaggio consente di modificare la finestra Baker mappa trama e Impostazioni mappa trama per visualizzare le relative impostazioni. In questo modo è possibile isolare più facilmente la fonte di un problema per poterlo risolvere.

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi menu per gestire set di texture e selezioni di Baker

  Sia nella finestra &quot;Elenco set texture&quot; che nella finestra &quot;Baker mappa trama&quot; sono stati aggiunti un piccolo menu di azioni che consente di copiare e invertire le selezioni.

* &lbrack;Modalità di Esegue i baking&rbrack; Dividi elenco selezioni baker per set di texture

* &lbrack;Modalità di Esegue i baking&rbrack; Dividi le impostazioni comuni per set di texture

* &lbrack;modalità di Esegue i baking&rbrack; Carica mesh di poligoni alti e gabbia senza bloccare l&#39;interfaccia

* &lbrack;Modalità di Esegue i baking&rbrack; Utilizzare la barra di avanzamento della finestra della vista per visualizzare il caricamento della trama

* &lbrack;Modalità di Esegue i baking&rbrack; Aggiungi stato di caricamento mesh nel registro di Esegue i baking

* &lbrack;Modalità di Esegue i baking&rbrack; Consenti di ruotare la trama nella finestra della vista durante la esegue i baking

* &lbrack;Modalità di Esegue i baking&rbrack; Imposta l&#39;ordine di esegue i baking in base alla visibilità della finestra della vista della trama corrente

* &lbrack;Modalità Esegue i baking&rbrack; Visualizza gabbia eseguita i baking implicita nella finestra della vista

  Quando non si utilizza un file di mesh di gabbia personalizzato, viene generata e visualizzata una mesh di gabbia automatica nella finestra della vista. Le sue dimensioni si basano sul parametro Distanza frontale massima dalle impostazioni comuni eseguite i baking. La maglia della gabbia viene utilizzata per indicare la distanza di corrispondenza tra il poly basso e alto.

* &lbrack;Modalità di Esegue i baking&rbrack; Mostra elenco corrispondente di nomi di trama per corrispondenza per nome nel registro di Esegue i baking

* &lbrack;Modalità Esegue i baking&rbrack; Usa materiale neutro per visualizzare il modello 3D nella finestra della vista

* &lbrack;Modalità di Esegue i baking&rbrack; Disattiva il calcolo del motore in modalità di esegue i baking

* &lbrack;Modalità di Esegue i baking&rbrack; Visualizza un avviso quando si esce dall&#39;app mentre è in corso un eseguo i baking

* &lbrack;Baker&rbrack; aggiornare le etichette delle impostazioni di antialiasing

  I valori delle impostazioni di antialiasing sono stati rinominati &quot;Supersampling&quot; e con un numero moltiplicatore esplicito per chiarirne il comportamento.

* &lbrack;Baker&rbrack; Aggiorna i baker alla versione 2.5.7.

* &lbrack;USD&rbrack; Importa ed esporta file di Universal Scene Description (USD)

* &lbrack;USD&rbrack; Aggiungere le opzioni USD alla finestra Nuovo progetto quando si seleziona un file USD

* &lbrack;USD&rbrack; Aggiungi nuova finestra di selezione Ambito e Varianti

  Quando si importa un file USD, facendo clic sul pulsante di modifica nella finestra Nuovo progetto o Configurazione progetto è possibile selezionare la parte e le varianti di un file USD da importare.

* &lbrack;USD&rbrack; Aggiungi livelli di suddivisioni, opzione

  Quando si crea un nuovo progetto con un file mesh USD che contiene suddivisioni, è possibile selezionare il livello di suddivisioni utilizzando un cursore. Il progetto verrà creato con la trama suddivisa. Il livello può essere modificatore tramite Configurazione progetto.

* &lbrack;USD&rbrack; Importa mesh con skin USD in un fotogramma specifico

  Quando si crea un nuovo progetto con un file mesh USD che contiene animazioni, è possibile selezionare il fotogramma utilizzando un cursore che riflette la sequenza temporale incorporata. Il fotogramma può essere modificatore tramite Configurazione progetto.

* &lbrack;USD&rbrack;&lbrack;Export&rbrack; Aggiungi un&#39;opzione per esportare i file USD

  Nuova casella di controllo Esporta USD aggiunta alla finestra Esporta texture. Quando è selezionato, consente di esportare file USD e mappe texture utilizzando qualsiasi modello.

* &lbrack;USD&rbrack;&lbrack;Export&rbrack; Aggiungere il formato di file USD all&#39;esportazione mesh

* &lbrack;USD&rbrack; Rinomina il predefinito di esportazione &quot;Rugosità metallo USD PBR&quot; esistente in modo che sia più esplicito

  Il modello di esportazione USD precedentemente noto come &#39;Rugosità metallo USD PBR&#39; è ancora accessibile tramite Esporta texture > Modello di output > USDz (Apple AR).

* &lbrack;Auto Unwrap&rbrack; Aggiungi orientamento Blocco per impacchettamento

  Nuova opzione per lo scorrimento automatico delle impostazioni che consente di mantenere l’orientamento delle Isole UV esistenti quando si utilizza la funzione di impacchettamento. È possibile accedervi da Nuovo progetto > Opzioni Srotolamento automatico > Isola UV orientamento.

* &lbrack;Dimensioni fisiche&rbrack; Aggiungi impostazione per utilizzare automaticamente la Dimensioni fisiche nell&#39;effetto/livello di riempimento

  È stata aggiunta una nuova opzione che consente di passare automaticamente alla scala dimensioni fisiche quando si utilizza un materiale con dimensioni fisiche incorporata. Può essere attivato per ogni progetto tramite Nuovo progetto o tramite Modifica > Configurazione progetto > Dimensioni fisiche > Converti il ridimensionamento del livello di riempimento in Dimensioni fisiche quando si assegnano i materiali.

* &lbrack;Dimensioni fisiche&rbrack; Esposizione dimensioni fisiche per Proiezione UV

  Il ridimensionamento delle dimensioni fisiche è ora disponibile per le Proiezioni UV: consente di ridimensionare automaticamente un materiale in base alla dimensioni fisiche di una trama. Può essere selezionata da Scala > Dimensioni fisiche nel livello di riempimento o nella finestra Proprietà effetti.

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di eseguire query sulla versione dell&#39;applicazione

* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; Aggiorna l’API in base ai nuovi parametri di esegue i baking

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; modulo di Esegue i baking: modifica parametri di esegue i baking

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; modulo di Esegue i baking: avvia/annulla esegue i baking

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; modulo di Esegue i baking: selezione metodo curvatura

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; modulo di Esegue i baking: selezione di baker/porzioni uv

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; modulo di Esegue i baking: sincronizzare le impostazioni del baker tra tutti i set di texture

* &lbrack;SVT&rbrack; abilita il supporto hardware di tipo sparse sulle GPU AMD

  L’accelerazione hardware per il sistema Sparse Virtual Textures può ora essere abilitata con le GPU AMD. Questa impostazione viene attivata automaticamente nelle preferenze generali.

* &lbrack;Proiezione&rbrack; Rinomina i parametri della proiezione cilindrica

  Il parametro &quot;Cylinder Culling&quot; è stato rinominato &quot;Backface Culling&quot; per rappresentarne meglio l’azione. La descrizione associata è stata modificata di conseguenza.

* &lbrack;Project&rbrack; Salva la versione dell&#39;applicazione nel progetto e recuperala tramite script

  A partire dalla versione 8.2, la versione dell’applicazione viene ora memorizzata nel file spp durante il salvataggio. Questo numero di versione può essere recuperato con la funzione last_saved_substance_painter_version() nel modulo di progetto dell’API Python. Per i progetti realizzati prima della versione 8.2, il valore restituito sarà null.

* &lbrack;Import&rbrack; Migliora il tempo di importazione generale dei modelli 3D

  Abbiamo migliorato il tempo generale di importazione delle trame. Ad esempio, la riduzione del tempo di attesa durante il caricamento di trame a poli elevato per la esegue i baking. Questa ottimizzazione si applica in particolare al caricamento dei file OBJ.

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; modifica dei canali sul filtro con una pila specifica

* &lbrack;Mac&rbrack;&lbrack;M1&rbrack; Arresto anomalo durante la creazione di un livello di riempimento e l&#39;uscita dalla Pila livelli

  Questo problema può essere risolto eseguendo l’aggiornamento a Mac OS 13 (Ventura).

* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Arresto anomalo quando si utilizza ui.add_dock_widget() con il tipo errato

* &lbrack;Eseguite i baking&rbrack; Messaggio di errore incompleto nel registro quando un eseguo i baking non riesce

* &lbrack;Esegui i baking&rbrack; La memoria non viene liberata al termine della esegue i baking

* &lbrack;Engine&rbrack; La cache della Texture non si aggiorna quando si modifica la visibilità degli effetti

* &lbrack;Export&rbrack; vista 2D esporta una mappa uniformata casualmente

* &lbrack;Project&rbrack; errore di allocazione della memoria durante il salvataggio del progetto con trama grande

* &lbrack;Viewport&rbrack; In alcuni casi, l&#39;accesso automatico al contenuto causa artefatti durante il disegno

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Pila livelli&rbrack; sorgente di input non salvata per livello

### 8.2.0

*(Versione: 06 ottobre 2022*)Riepilogo: **Versione principale con nuovi pannelli di onboarding (nuovo pannello di benvenuto e novità), esportazione in SBSAR, effetti per la cartella, diversi miglioramenti per la qualità della vita e correzioni di bug.**

**Aggiunto:**

* &lbrack;Onboarding&brack; pannello Onboarding per accogliere nuovi utenti

  È stata aggiunta una nuova schermata introduttiva quando i nuovi utenti CC aprono Painter per la prima volta.

* &lbrack;Onboarding&rbrack; pannello Novità per migliorare la ricerca di nuove funzioni

  È stata aggiunta una nuova schermata Novità che mostra le principali nuove funzioni. Viene visualizzato automaticamente la prima volta che Painter viene aperto dopo un aggiornamento importante ed è nuovamente accessibile da Aiuto > Novità.

* &lbrack;Onboarding&rbrack; rinomina il vecchio benvenuto in &quot;Schermata Home&quot;

  La vecchia schermata introduttiva è stata rinominata Schermata iniziale per evitare confusione con la nuova schermata introduttiva.

* &lbrack;UI&rbrack; Risolvi i problemi di ridimensionamento per schermi ad alto DPI

  È stato migliorato l’adattamento dell’interfaccia utente di Painter su schermi ad alta definizione con ridimensionamento personalizzato.

* &lbrack;UI&rbrack; Evita messaggi di errore persistenti nell&#39;interfaccia utente

  I messaggi di errore dei progetti precedenti sono stati rimossi dalla barra di stato inferiore.

* &lbrack;UI&rbrack; Rielabora menu Salva

  Le opzioni di salvataggio aggiuntive sono ora raggruppate in un sottomenu e alcune sono state rinominate per coerenza.

* &blocca;UI&rbrack; Salva ed esporta/condividi layout interfaccia utente

  Nel menu Finestra sono disponibili nuove azioni per salvare il layout dell&#39;interfaccia utente nei file e ricaricarli. I layout di disegno e rendering vengono salvati separatamente. A &quot;substance_painter.ui&quot; sono state aggiunte varie funzioni per salvare, reimpostare e caricare anche i layout dell’interfaccia utente.

* Aggiungere azioni di copia/incolla per i metodi di fusione/opacità di un livello

  È stata aggiunta la nuova voce &quot;Opzioni di fusione&quot; al menu di scelta rapida dei livelli. Consente di copiare e incollare il metodo di fusione e l’opacità di tutti i canali da un livello all’altro.

* Applicare il metodo di fusione/opacità a tutti i canali di un livello

  È stata aggiunta una funzionalità di clic con il pulsante destro del mouse al metodo di fusione e all’opacità dei livelli che consente di applicare a tutti i canali l’impostazione su cui si fa clic.

* Ricarica trama con una scelta rapida da tastiera da tastiera (CTRL+MAIUSC+R)

  È stata aggiunta una scelta rapida da tastiera modificabile per ricaricare il file mesh con le ultime impostazioni disponibili. È possibile accedere a questa opzione anche da Modifica > Reimporta trama.

* Ripristina i parametri predefiniti di Substance

  È stato aggiunto un nuovo pulsante nelle proprietà nella parte inferiore delle risorse .sbsar che consente di ripristinare le impostazioni predefinite della risorsa.

* Ripristina pittura pennello predefinito

  È stato aggiunto un nuovo menu nella sezione Pennello in Proprietà che consente di ripristinare il pennello di base predefinito.

* Fare clic con il pulsante destro del mouse per ripristinare i singoli parametri di Substance ai valori predefiniti

  È stata aggiunta la possibilità di ripristinare singoli parametri all&#39;interno di una risorsa .sbsar tramite clic con il pulsante destro del mouse.

* &lbrack;Assets panel&rbrack; risorse preferite del &quot;Segnaposto&quot; da visualizzare sopra il pannello delle risorse

  È stata aggiunta una nuova opzione di clic con il pulsante destro del mouse sulle risorse della libreria che consente di raggrupparle come segnaposti preferiti nella parte superiore del pannello. Puoi anche visualizzare tutte le tue risorse preferite tramite Ricerche salvate.

* &lbrack;Pannello Risorse; Elimina, ricarica e rinomina le risorse

  Sono state aggiunte le opzioni del menu di scelta rapida per eliminare, ricaricare e rinominare le risorse nella libreria utente. Vengono eliminati direttamente dal percorso della libreria sul disco e ricaricati dal percorso originale. Le risorse che fanno parte di un pacchetto come .abr o .sbsar non possono essere modificate singolarmente.

* &lbrack;Color Selection&rbrack; Aggiungi metodi di fusione all&#39;effetto Selezione colore

* &lbrack;Pila livelli&rbrack; Aggiungi metodo di fusione e opacità sui filtri

* &lbrack;Pila livelli&rbrack; Consenti valori Affiancamenti maggiori di 128 per livello di riempimento/effetti

* &lbrack;Pila livelli&rbrack; tappi cilindrici per la proiezione cilindrica nel livello/effetto di riempimento

  La proiezione cilindrica nelle proprietà del livello Riempimento ora ha l&#39;opzione per rimuovere le estremità dei cilindri.

* &lbrack;Log&rbrack; Mostra un messaggio di errore se la parte mesh si trova in uno spazio negativo durante il tentativo di creazione di un progetto Porzione UV

  È stato aggiunto un messaggio di errore più chiaro quando non si crea un progetto di Porzione UV perché le parti UV vengono trovate in spazi negativi.

* &lbrack;Project&rbrack; indica la versione nel messaggio di errore &quot;dati troppo recenti&quot; durante l&#39;apertura di un progetto

  Quando si apre un progetto troppo recente per l’applicazione, il messaggio di errore indica ora la versione del progetto per facilitare l’identificazione della versione corretta dell’applicazione.

* &lbrack;Riquadro di visualizzazione&rbrack; Consenti di illuminare la trama da sotto

  È stato aggiunto un nuovo parametro di Allineamento ambiente in Impostazioni visualizzazione > Fotocamera > Impostazioni ambiente per allineare l’illuminazione della mappa ambiente alla videocamera quando è impostata su &quot;Locale&quot;.

* &lbrack;Viewport&rbrack; Visualizza R, G, B e Alpha nella finestra della vista (modalità visualizzazione solo)

  In Impostazioni schermo > Impostazioni finestra vista > Visualizzazione canali è disponibile una nuova impostazione Canali colore che consente di visualizzare solo il componente R, G, B o Alpha di un canale quando è attiva la modalità di visualizzazione singola.

* &lbrack;Shader&rbrack; Consenti di impostare i canali utente come RGBA nei livelli di materiale

  Quando si imposta la configurazione dei canali dell’insieme di texture all’interno di uno shader per la creazione di livelli di materiale, è ora possibile specificare il formato del canale da deviare dal valore di default. In particolare, è possibile richiedere canali utente a colori invece che solo in scala di grigi.

* &lbrack;Esporta&rbrack; consente di esportare texture come SBSAR

  Quando si esporta una texture tramite la finestra File > Esporta Texture, si può scegliere il formato di file SBSAR (Substance Archivio) per raggrupparla. Il contenuto del SBSAR dipende dal modello di output utilizzato. Il formato del file SBSAR può essere impostato anche nei predefiniti di esportazione. Quando si utilizza la configurazione ibrida (SBSAR + Altro formato), le texture che hanno come destinazione un SBSAR vengono raggruppate mentre le altre vengono esportate insieme.

* &lbrack;Export&rbrack; Exposé 16bit, opzione per il formato di file EXR

  Quando si esportano file di texture EXR, ora è possibile scegliere tra 16f bit (Mezza Virgola mobile) o 32f bit (Virgola mobile) nella finestra Esporta Texture (sia per le impostazioni di esportazione che per i predefiniti di esportazione). I vecchi progetti e i vecchi predefiniti di esportazione verranno impostati per impostazione predefinita su 16 f bit per riflettere il vecchio comportamento.

* &lbrack;Python&rbrack; Aggiungi evento per sapere quando modificare i set di texture

  Il nuovo &quot;substance_painter.event.TextureStateEvent&quot; consente di sapere quando un insieme di texture è stato modificato a causa di un tratto pittura, di un nuovo canale aggiunto o di un canale rimosso.

* &lbrack;Python&rbrack; Consenti di ottenere e impostare le risorse Mesh Map nelle impostazioni del set di texture

  Nel modulo &quot;substance_painter.project&quot; sono state aggiunte nuove funzioni per ottenere e impostare le risorse delle mappe mesh. Queste funzioni possono essere utilizzate per aggiornare le mappe di trama a cui fanno riferimento le impostazioni del set di texture.

* &lbrack;Plugin&rbrack; Rimuovi l&#39;opzione per ottenere altri plug-in JS

  È stata rimossa l’opzione per ottenere i plug-in JavaScript poiché erano ospitati nel sito Web di condivisione obsoleto.

* &blocco;Content&rbrack; Aggiungi nuovo modello Roblox ed esporta predefinito

  Sono stati aggiunti un nuovo modello di progetto Roblox &quot;Material Variant&quot; e &quot;Surface Appearance&quot; e un predefinito di esportazione per facilitare l’esportazione di texture PBR in Roblox. È possibile accedere al modello dalla finestra File > Nuovo progetto.

* Aggiornamento della Substance Engine alla versione più recente (8.6.3)

* &lbrack;Steam&rbrack; build ottimizzata per chipset Apple Silicon (Apple M1 / M2)

**Corretto:**

* Arresto anomalo quando si utilizza exr 16k

* &lbrack;Arresto anomalo&rbrack; Ctrl Z Dopo l&#39;eliminazione di un&#39;istanza shader

* &lbrack;Iray&rbrack; IoR è bloccato su 1 per alcuni shader

* &lbrack;Win&rbrack;&lbrack;Esegui i baking&rbrack; Alcuni alti poli non vengono caricati

* &lbrack;Gestione colore&rbrack; nome dello spazio colore non corretto nell&#39;interfaccia utente con filtri

* &lbrack;Python&rbrack; Gli oggetti risorsa restituiti dalla funzione di importazione non hanno un tipo

  Quando si importava un pacchetto di Substance in Python, la funzione restituiva il pacchetto invece dei relativi grafici. Il modulo delle risorse ora fornisce funzioni e parametri per recuperare i grafici di un pacchetto di Substance.

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Pila livelli&rbrack; sorgente di input non salvata per livello
* &lbrack;Painting&rbrack; L&#39;antialiasing temporale causa artefatti quando si disegna in alcuni casi
* &lbrack;Export&rbrack; vista 2D esporta una mappa uniformata casualmente

### 8.1.3

*(Rilasciato: 25 agosto 2022*)Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

* Aggiornamento a Iray SDK 1.6

**Corretto:**

* &lbrack;Shader&rbrack; Arresto anomalo con vecchio shader difettoso
* &lbrack;Material Layering&brack; I materiali possono scomparire quando si riapre un progetto

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Pila livelli&rbrack; sorgente di input non salvata per livello
* &lbrack;Arresto anomalo&rbrack; Ctrl Z Dopo l&#39;eliminazione di un&#39;istanza shader
* &lbrack;Iray&rbrack; IoR è bloccato su 1 per alcuni shader

### 8.1.2

*(Rilasciato: 19 luglio 2022*)Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

* &lbrack;Auto Unwrap&rbrack; Nuova opzione &quot;Ottimizza per trame organiche&quot; per selezionare l&#39;algoritmo di segmentazione
* &lbrack;Dimensioni fisiche&rbrack; Esposizione delle opzioni delle unità in Nuovo progetto e Configurazione progetto
* &lbrack;Color Management&rbrack; Usa visualizzazione monitor per impostazione predefinita quando si utilizza ACE
* &lbrack;Color Management&rbrack;&lbrack;Python&rbrack; Durante la creazione del progetto, tenere conto del file predefinito ACE env-var
* &lbrack;Color Management&rbrack; Reimposta le impostazioni di Color Management nella finestra Nuovo progetto quando la configurazione cambia
* &lbrack;Gestione colore&rbrack; Disattiva accesso alle impostazioni OCIO in presenza di env-var
* &lbrack;Color Management&rbrack; aggiorna in modo sicuro le impostazioni ACE quando un parametro non esiste più
* Aggiornamento della Substance Engine alla versione 8.6.0
* &lbrack;Export&rbrack; Aggiungi nuovo predefinito di esportazione GLTF con supporto Spostamento
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Recupero delle informazioni sulle risorse (inclusi i metadati personalizzati)
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Aggiungi funzione all&#39;elenco di query dei nomi di trama per set di texture
* &lbrack;Content&rbrack; Aggiungi nuovo modello di fusione ed esporta predefinito

**Corretto:**

* &lbrack;MacOS&rbrack; Arresto anomalo all&#39;avvio di Iray in alcuni casi
* &lbrack;Thumbnails&rbrack; Le miniature dello shelf non vengono caricate correttamente
* Più canali UV vengono ignorati
* &lbrack;Auto Unwrap&rbrack; calcolo non necessario durante la divisione di isole lunghe
* &lbrack;Auto Unwrap&rbrack; Opzione per evitare isole allungate non considerata
* &lbrack;Auto Unwrap&rbrack; perdita di dati aggiuntivi (colori dei vertici) durante il reinserimento degli UV
* &lbrack;UI&rbrack; Barra di scorrimento orizzontale nella finestra delle proprietà quando Gestione colore è attivato
* &lbrack;Color Management&rbrack; nelle configurazioni OCIO manca il ruolo substance_3d_painter_standard_srgb
* &lbrack;Generator&rbrack; Utilizzo errato dei dati utente &quot;disabilitato&quot;
* &lbrack;Gestione colore&rbrack; Il menu a discesa Spazio colore &quot;Non compatibile&quot; non deve essere selezionabile
* &lbrack;Gestione colore&rbrack;&lbrack;Shader&rbrack; sRGB override define non funziona più
* &lbrack;Generator&rbrack; Utilizzo errato dei dati utente &quot;disabilitato&quot;
* &lbrack;Pila livelli&rbrack; anteprime interrotte con progetti Porzioni UV
* &lbrack;Shader&rbrack; La documentazione delle API non è completamente aggiornata con la Normali incurvate
* &lbrack;Export&rbrack;&lbrack;Interoperability&rbrack; Impossibile inviare a Stager con caratteri speciali
* &blocca;Contenuto&Raccoglitore; alcune miniature dei pennelli predefiniti sono vuote o troppo scure

**Problemi noti:**

* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &lbrack;Pila livelli&rbrack; La sorgente di input non viene salvata per livello
* &lbrack;Arresto anomalo&rbrack; Ctrl Z Dopo l&#39;eliminazione di un&#39;istanza shader
* &lbrack;Iray&rbrack; IoR è bloccato su 1 per alcuni shader
* &lbrack;Shader&rbrack; Arresto anomalo con vecchio shader difettoso

### 8.1.1

*(Rilasciato: 28 giugno 2022*)Riepilogo: **Hotfix per le versioni secondarie**

**Aggiunto:**

* &lbrack;Pila livelli&rbrack; se si fa clic su Alt sulla maschera, gli effetti non vengono più deselezionati

**Corretto:**

* &lbrack;Arresto anomalo&rbrack; apertura del vecchio progetto salvata in modalità di visualizzazione Solo
* &lbrack;Arresto anomalo&rbrack; Elimina un generatore nelle proprietà
* &lbrack;Impostazioni set di texture&rbrack; missaggio normale/Occlusione ambientale e height ai metodi normali non funzionano
* &lbrack;Export&rbrack; Esporta texture utilizzando il riempimento diffusione esegue il rendering delle mappe nere

**Problemi noti:**

* &lbrack;MacOS&rbrack; Arresto anomalo all&#39;avvio di Iray su Monterey
* &lbrack;Anteprima miniatura&rbrack; le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

### 8.1.0

*(Rilasciato il 7 giugno 2022*)Riepilogo: **Versione principale con supporto ICC, ridimensionamento del materiale in base ai dati della dimensioni fisiche, nuovi baker, miglioramenti del contagocce colore e una serie di contenuti aggiuntivi**

**Aggiunto:**

* &lbrack;Color Management&rbrack; Aggiungi supporto per profili ICC con Adobe Color Engine (ACE)
* &lbrack;Color Management&rbrack; Aggiungi il supporto per &quot;Adobe 98 RGB&quot; come spazio cromatico di lavoro per ICC
* &lbrack;Color Management&rbrack; Consenti di configurare le impostazioni ACE/ICC tramite un file di configurazione
* &lbrack;Gestione colore&rbrack; Consenti di inserire valori di colore lineari nel Selettore colore con la modalità Legacy
* &lbrack;Gestione colore&rbrack; Consenti di specificare il profilo colore utilizzato per la selezione del colore al di fuori dell&#39;interfaccia utente
* &lbrack;Color Management&rbrack; Ricorda l&#39;ultimo valore di visualizzazione scelto nella finestra della vista
* &lbrack;Gestione colore&rbrack;&lbrack;Substance&rbrack; Fare in modo che i generatori/filtri funzionino correttamente con Gestione colore
* &lbrack;Gestione colore&rbrack;&lbrack;Substance&rbrack; Aggiungi nuove parole chiave di esclusione dello spazio colore $working e $standardsrgb
* &lbrack;Dimensioni fisiche&rbrack;&lbrack;Engine&rbrack; Estrai informazioni sulla dimensioni fisiche dalla trama
* &lbrack;Dimensioni fisiche&rbrack;&lbrack;Engine&rbrack; calcolo Dimensioni fisiche
* &lbrack;Dimensioni fisiche&rbrack; Esporre le opzioni per l&#39;utilizzo della dimensioni fisiche nell&#39;interfaccia utente
* &lbrack;Dimensioni fisiche&rbrack; Aggiungi helper visivi nella finestra della vista
* &lbrack;Esegui i baking&rbrack; Aggiungi baker Height
* &lbrack;Esegui i baking&rbrack; Aggiungi baker Normali incurvate
* &lbrack;Esegui i baking&rbrack; Aggiungi baker opacità
* &lbrack;Contagocce&rbrack; Nuova anteprima del contagocce colore accanto al mouse e al colore gestito
* &lbrack;Contagocce&rbrack; il pannello Selettore colore riappare nella sua ultima posizione quando viene riaperto
* &lbrack;Contagocce&rbrack; Una nuova icona per il selettore materiale
* &lbrack;Contagocce&rbrack; Gestione del colore per l&#39;anteprima dei canali del selettore colore
* &blocca;Contagocce&rbrack; Aggiungi funzionalità di selezione al contagocce
* &lbrack;Contagocce&rbrack; il selettore di materiali non attiva più i canali non attivi
* &lbrack;Contagocce&rbrack; Consenti l&#39;utilizzo del contagocce con una scelta rapida da tastiera
* &lbrack;Contagocce&rbrack; il contagocce preleva il canale pertinente, se applicabile
* &lbrack;Contagocce&rbrack; quando si entra in modalità Selettore colore, vengono disattivate tutte le scelte rapide
* &lbrack;Contagocce&rbrack; Rimuovi selezione automatica del campo esadecimale
* &lbrack;Contagocce&rbrack; Non chiudere il pannello quando si utilizza il selettore di materiali
* &lbrack;Contagocce&rbrack; Nuovo stato disabilitato quando il canale non è disponibile per la selezione
* &lbrack;Export&rbrack; Aggiungi attributo tangente all&#39;esportazione glTF
* Aggiorna Substance Engine alla versione 8.4
* Aggiorna Scorrimento automatico a 0.9.0
* Esegui l’aggiornamento a Qt 5.15.8
* Aggiornamento a Python 3.9
* &lbrack;Shader&rbrack; Aggiungi supporto per ombreggiatura Normali incurvate
* &lbrack;MacOS&rbrack; supporto di 3DConnection SpaceMouse
* &lbrack;Python&rbrack; Documenta la versione Python utilizzata nell&#39;API
* &lbrack;Content&rbrack; Aggiungi 6 nuovi rumori 3D con 105 predefiniti
* &lbrack;Content&rbrack; 20 nuove mappe di grungi e 2 motivi di pieghe in tessuto
* &lbrack;Content&rbrack; Aggiornare il predefinito di esportazione &quot;Mesh maps&quot; per utilizzare nuovi baker
* &lbrack;Content&rbrack; Pendenza sfocatura e filtro alterazione dipendono dalla risoluzione dell’insieme di texture
* &lbrack;Content&rbrack; aggiorna i progetti di esempio per utilizzare i 3 nuovi baker

**Corretto:**

* &lbrack;glTF&rbrack; impossibile aprire glTF con carattere speciale
* &lbrack;Engine&rbrack; artefatti con anisotropia e SVT disattivati
* &lbrack;MacOS&rbrack;&lbrack;M1&rbrack; Materiali avanzati non visualizzati correttamente
* &lbrack;Mesh Processing&brack; Impossibile importare trame da Modeler
* &lbrack;UI&rbrack; Barra di scorrimento orizzontale nella nuova finestra del progetto con la Gestione colore attivata
* &lbrack;Gestione colore&rbrack; Valore spazio di lavoro mancante nel selettore colore con alcune configurazioni OCIO
* &lbrack;Gestione colore&rbrack; L&#39;anteprima del pennello nella finestra della vista non è sottoposta alla gestione del colore
* &lbrack;SpaceMouse&rbrack; Il pivot non viene aggiornato immediatamente con la modifica dello stato attivo e a volte fuori dal modello
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; I file USD esportati hanno una struttura errata
* &lbrack;USD&rbrack; problema di Occlusione ambientale durante l&#39;esportazione
* &lbrack;Content&rbrack; aggiorna la trama della miniatura in modo che corrisponda al progetto di esempio Preview Sphere

**Problemi noti:**

* Esportare texture utilizzando il riempimento diffusione esegue il rendering delle mappe nere
* Il missaggio normale/Occlusione ambientale è interrotto
* &lbrack;MacOS&rbrack; Arresto anomalo all&#39;avvio di Iray in alcuni rari casi
* &lbrack;Anteprima miniatura&rbrack; Le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
* &lbrack;Color Management&rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

## Versione 7

### 7.4.3

*(Rilasciato: 11 aprile 2022*)Riepilogo: **Bugfix con supporto di 3Dconnection SpaceMouse nel viewport 2D**

**Aggiunto:**

* &lbrack;SpaceMouse&rbrack; supporto di 3DConnection SpaceMouse in 2D Viewport

**Corretto:**

* &lbrack;Selettore colore&rbrack; Impossibile scrivere in un campo esadecimale
* &lbrack;Gestione colore&rbrack; le risorse utilizzate in modalità di proiezione non sono gestite dal colore nella sovrapposizione
* &lbrack;Gestione colore&rbrack; Gli errori non vengono segnalati nel registro
* &lbrack;SpaceMouse&rbrack; Rimuovi il messaggio di errore generico se l&#39;utente non dispone di SpaceMouse
* &lbrack;SpaceMouse&rbrack; Quando si carica un progetto, il punto fulcro è sempre nascosto
* &lbrack;Baker&rbrack; l&#39;impostazione &quot;Media normali&quot; non ha effetto nei progetti di Porzione UV
* &lbrack;Porzione UV&rbrack; le sovrapposizioni dei riquadri uv inattivi scompaiono quando si ricarica la trama con riquadri diversi
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Lo scripting remoto è interrotto
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Non è possibile eseguire query su diversi canali dall’API e questo genera un errore
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Arresto anomalo quando si utilizza l&#39;evento ProjectEditionEntered
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Arresto anomalo durante la chiamata di get_active_stack()

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* &lbrack;UI&rbrack; barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella finestra di un nuovo progetto
* &lbrack;Mac M1&rbrack; i Materiali avanzati non vengono visualizzati correttamente

### 7.4.2

*(Rilasciato: 08 marzo 2022*)Riepilogo: **Bugfix con supporto di 3Dconnection SpaceMouse e miglioramenti alla gestione del colore (OCIO)**

**Aggiunto:**

* &lbrack;SpaceMouse&rbrack;&lbrack;Windows&rbrack; supporto di 3Dconnection SpaceMouse nel riquadro di visualizzazione 3D per la navigazione
* &lbrack;SpaceMouse&rbrack;&lbrack;Windows&rbrack; scelte rapide da tastiera e tasti di base per i modelli Pro ed Enterprise SpaceMouse nella finestra della vista 3D
* &lbrack;SpaceMouse&rbrack;&lbrack;Windows&rbrack; icona del centro di rotazione dedicato nel riquadro di visualizzazione 3D
* &lbrack;Color Management&rbrack; Utilizzare i ruoli della configurazione OCIO per modificare le impostazioni predefinite
* &lbrack;Gestione colore&rbrack; Gestione colore gestisce la finestra delle proprietà per i widget colore
* &lbrack;Gestione colore&rbrack; Gestione colore gestisce la finestra delle proprietà per l&#39;anteprima del materiale
* &lbrack;Gestione colore&rbrack; Gestione colore gestisce i campioni nel selettore colore
* &lbrack;Gestione colore&rbrack; Aggiungi un&#39;impostazione per definire lo spazio colore sRGB standard
* &lbrack;Gestione colore&rbrack; Aggiungi lo spazio colore sRGB standard dalla configurazione OCIO nel selettore colore Elenco selettori visualizzazione
* &lbrack;Gestione colore&rbrack; Miglioramenti per il menu di esclusione dello spazio colore
* &lbrack;Gestione colore&rbrack; Consenti di ignorare lo spazio cromatico della mappa dell&#39;ambiente in Impostazioni visualizzazione
* &lbrack;Gestione colore&rbrack; Disegna sfumature selettore colore in base alla visualizzazione corrente
* &lbrack;Color Management&rbrack; Blocca valori HDR per impostazione predefinita nell&#39;editor colori
* &lbrack;Gestione colore&rbrack; Usa passthrough (senza spazio colore) per i filtri in modalità Legacy
* &lbrack;Gestione colore&rbrack; Limita la visualizzazione delle sfumature nell&#39;editor colori in base all&#39;intervallo &lbrack;0-1&rbrack;
* &lbrack;Gestione colore&rbrack; Nascondi selettore visualizzazione nel selettore colore in modalità Legacy
* &lbrack;Gestione colore&rbrack; Imposta il selettore colore come campo esadecimale sempre nello spazio colore sRGB
* &lbrack;Gestione colore&rbrack; Disattiva il selettore colore Visualizza il menu a discesa per i canali dati
* &lbrack;Optimization&rbrack; la griglia di alterazione ricalcola solo i riquadri UV coperti
* &lbrack;Esporta&rbrack; consente di esportare progetti di Porzione UV per Sketchfab, USD e glTF
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di modificare la funzione di mappatura tonale

**Corretto:**

* &lbrack;Sketchfab&rbrack; l&#39;aggiornamento del modello esistente comporta la creazione di un nuovo modello
* &lbrack;Sketchfab&rbrack; Arresto anomalo durante la ricerca di un modello aggiornato in precedenza
* Arresto anomalo durante l’esportazione nell’USD
* Arresto anomalo durante la creazione di una nuova istanza shader nella maschera di geometria o quando la geometria è nascosta
* &lbrack;Importa finestra cespite&rbrack; Arresto anomalo quando si modifica il tipo di risorse importate
* Le mappe con trama normale vengono invertite se utilizzate in Pila livelli
* &lbrack;Substance&rbrack; il metodo di fusione dei dati utente non viene considerato
* &lbrack;Color Management&rbrack; Le bitmap con spazio cromatico nel nome del file vengono importate come sequenze di Porzioni UV
* &lbrack;Color Management&rbrack; Gli output con gestione del colore del grafico a Substance si trovano in uno spazio cromatico errato
* &lbrack;Gestione colore&rbrack; lo strumento Riempimento poligonale visualizza il colore errato
* &lbrack;Color Management&rbrack; Il tonemapper ACE viene applicato ai canali in modalità Solo
* &lbrack;Gestione colore&rbrack; L&#39;illuminazione della sfera dell&#39;anteprima dello strumento non è gestita dal colore
* &lbrack;Color management&rbrack;&lbrack;Export&rbrack; Le mappe convertite applicano una conversione errata
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack;&lbrack;Color Management&rbrack; I progetti creati con la variabile di ambiente template &amp; OCIO sono in modalità Legacy
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Impossibile utilizzare la funzione di valutazione JavaScript all&#39;avvio
* &lbrack;3D Adobe Offer&rbrack; Impossibile avviare Painter quando si utilizzano impostazioni internazionali con lingue non supportate per impostazione predefinita

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* &lbrack;UI&rbrack; barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella finestra di un nuovo progetto
* &lbrack;Baker&rbrack; l&#39;impostazione &quot;Media normali&quot; non ha effetto nei progetti di Porzione UV
* &lbrack;Mac M1&rbrack; Materiali avanzati non visualizzati correttamente
* &lbrack;Gestione colore&rbrack; le risorse utilizzate in modalità di proiezione non sono gestite dal colore nella sovrapposizione
* &lbrack;Selettore colore&rbrack; Impossibile scrivere in un campo esadecimale

### 7.4.1

*(Rilasciato: 14 dicembre 2021*)Riepilogo: **Correzione rapida con miglioramenti nella gestione del colore**

**Aggiunto:**

* &lbrack;Gestione colore&rbrack; Usa ruolo dati nei nomi file esportati
* &lbrack;Color Management&rbrack; Espandere la sezione Color Management (Gestione colore) per impostazione predefinita, quando nelle finestre Nuovo progetto e Impostazioni progetto è selezionato OCIO
* &lbrack;Color Management&rbrack; Aggiungi tonemapper ACE in modalità legacy
* &lbrack;Gestione colore&rbrack; Regolare le impostazioni di configurazione predefinite
* &lbrack;Color Management&rbrack;&lbrack;Export&rbrack; Fill $colorSpace nei nomi dei file per i canali dati
* &lbrack;Esporta&rbrack; Esporta progetto Porzione UV in Stager
* &lbrack;Interoperability&rbrack; non disponibile per le edizioni Steam e Substance
* &lbrack;Interoperabilità&rbrack; Consente di inviare un progetto di Porzione UV a Stager

**Corretto:**

* &lbrack;MacOS&rbrack;&lbrack;Arresto anomalo&rbrack; Painter non inizia con Catalina
* &lbrack;Gestione colore&rbrack;&lbrack;Arresto anomalo&rbrack; arresto anomalo casuale durante la riproduzione con la gestione del tipo di dati/colore sul canale utente
* &lbrack;Gestione colore&rbrack; Risorse utilizzate come scala di grigi nel nuovo menu per la visualizzazione dello spazio colore della maschera
* &lbrack;Gestione colore&rbrack; il canale utente è più scuro nella finestra della vista in modalità legacy + vista solo
* &lbrack;Color Management&rbrack; La mappa Env è sempre lineare se utilizzata in iRay
* &lbrack;Color Management&rbrack; Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* &lbrack;Color management&rbrack; Il selettore colore non funziona all’interno di una Substance in modalità legacy
* &lbrack;Gestione colore&rbrack; il passaggio tra le viste dei singoli canali nella finestra della vista viene visualizzato con lo spazio cromatico corretto quando si utilizza il menu a discesa
* &lbrack;Gestione colore&rbrack; Esporta applica la conversione errata sui canali utente con gestione del colore in modalità legacy
* I tratti creati nella maschera di visualizzazione Solo non vengono visualizzati quando si ritorna alla vista Materiale
* &lbrack;Esporta&rbrack; le mappe convertite non vengono esportate come canali con gestione del colore
* &lbrack;Texture Set&brack; La descrizione con il nome originale non è presente nei canali utente rinominati
* &lbrack;Steam&rbrack; File mancanti durante la verifica dell&#39;integrità del file con Steam

**Problemi noti:**

* &lbrack;Mac M1&rbrack; Materiali avanzati non visualizzati correttamente

### 7.4.0

*(Rilasciato: 24 novembre 2021*)Riepilogo: **Versione principale. Introduzione della prima versione della gestione del colore, disancoraggio della vista 2D o 3D, nuova opzione per lo srotolamento automatico degli UV per evitare isole allungate, chiamata delle funzioni JavaScript dall&#39;API Python e nuovo contenuto**

**Aggiunto:**

* &lbrack;Color Management&rbrack; supporto della gestione colore OpenColorIO versione 2
* &lbrack;Gestione colore&rbrack; Aggiungi impostazioni di gestione colore alle impostazioni del progetto
* &lbrack;Color Management&rbrack; finestra di avvertenza sulle modifiche alla configurazione di Color Management all&#39;apertura di un progetto
* &lbrack;Color Management&rbrack; Visualizza un messaggio di errore se viene selezionato un file di configurazione OCIO non valido
* &lbrack;Color Management&rbrack; consente di ignorare la configurazione con la variabile di ambiente OCIO
* &lbrack;Color Management&rbrack; più configurazioni OCIO integrate per impostazione predefinita con l&#39;applicazione
* &lbrack;Gestione colore&rbrack; Estrai il nome dello spazio colore dal nome del file bitmap importato
* &lbrack;Gestione colore&rbrack; Consenti di ignorare lo spazio colore con uno spazio colore dalla configurazione nella finestra Proprietà
* &lbrack;Gestione colore&rbrack; Aggiungere opzioni di gestione colore nelle impostazioni del set di texture
* &lbrack;Color Management&rbrack;&lbrack;Viewport&rbrack; Consenti di gestire separatamente i colori delle viste 2D e 3D
* &lbrack;Color Management&rbrack; Carica e converti la mappa dell&#39;ambiente nello spazio cromatico di lavoro
* &lbrack;Gestione colore&rbrack; Regola il selettore colore e l&#39;editor con lo spazio colore corrente
* &lbrack;Gestione colore&rbrack; Consenti di selezionare lo spazio colore Trasforma della visualizzazione nella finestra della vista con un nuovo menu a discesa
* &lbrack;Color Management&rbrack; Applica la Trasforma di visualizzazione con i risultati del rendering dei raggi
* &lbrack;Gestione colore&rbrack; Esporta texture con diversi spazi colore
* &lbrack;Color Management&rbrack;&lbrack;Python&rbrack; Applica le impostazioni di gestione del colore dalla variabile di ambiente (OCIO) ai nuovi progetti
* &lbrack;Viewport&rbrack; Consenti di disancorare la finestra della vista 2D o 3D
* &lbrack;Auto Unwrap&rbrack; Nuova opzione per evitare isole allungate
* &lbrack;Scripting Python&rbrack; Chiama funzioni JavaScript dall&#39;API Python
* &lbrack;Finestra nuovo progetto&rbrack; Rende comprimibile la sezione delle mappe importate
* &lbrack;Proiezione&rbrack;&lbrack;Altera&brack; Consenti di nascondere le normali come opzione nelle impostazioni di Altera
* &lbrack;Content&rbrack; 11 nuove mappe grungi
* &lbrack;Content&rbrack; 8 nuovi strumenti predefiniti (cerniera, cavo di serraggio, glitter)
* &lbrack;Content&rbrack; 8 nuovi materiali (cicatrice, tasca, ...)
* &lbrack;Content&rbrack; 1 nuovo generatore (inflate shrinkwarp)

**Problemi noti:**

* &lbrack;Mac M1&rbrack; Materiali avanzati non visualizzati correttamente
* &lbrack;Gestione colore&rbrack;&lbrack;Arresto anomalo&rbrack; arresto anomalo casuale durante la riproduzione con la gestione del tipo di dati/colore sul canale utente
* &lbrack;Color Management&rbrack; Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* &lbrack;Color management&rbrack;&lbrack;Iray&rbrack; Il salvataggio del rendering in EXR o TIFF durante l’attivazione di Color Management nella finestra della vista consente di risparmiare sempre in modalità lineare
* &lbrack;Gestione colore&rbrack; Le risorse utilizzate come scala di grigi nella maschera visualizzano il menu Spazio colore errato
* &lbrack;Color Management&rbrack;&lbrack;Iray&rbrack; La mappa Env è sempre lineare quando viene utilizzata in Iray
* &lbrack;Gestione colore&rbrack;&lbrack;Esporta&rbrack; Le mappe convertite non vengono esportate come canali con gestione del colore
* &lbrack;Color Management&rbrack;&lbrack;Export&brack; Esporta ignora se il canale utente è gestito dal colore o meno in modalità legacy

### 7.3.1

*(Rilasciato: 24 Novembre 2021*)Riepilogo: **Bugfix**

**Aggiunto:**

* &lbrack;Proiezione&rbrack; Il ridimensionamento dovrebbe funzionare solo nello spazio oggetto

**Corretto:**

* &lbrack;Mac M1&rbrack; il livellamento dei materiali non funziona
* &lbrack;Mac M1&rbrack;&lbrack;Projection&rbrack; Warp non funziona
* I micro dettagli non vengono visualizzati correttamente
* &lbrack;Proiezione&rbrack;&lbrack;Arresto anomalo&rbrack; Passaggio alla modalità di alterazione con un livello creato con una versione precedente
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
* &lbrack;Projection&rbrack;&lbrack;Warp&rbrack; Split rimane selezionata al termine della divisione
* &lbrack;Proiezione&rbrack;&lbrack;UV&rbrack; Il punto pivot viene reimpostato quando si capovolge la proiezione
* &lbrack;Filter&rbrack; L&#39;ambiente Esegue i baking illuminazione cambia quando si ricarica o si modifica un parametro
* &lbrack;Interoperability&rbrack; non disponibile per le edizioni Steam e Substance
* &lbrack;Interoperability&rbrack; Il pulsante &quot;Sfoglia risorse 3D nel Marketplace&quot; dovrebbe sempre aprire CCD nella scheda 3D di Stock e Marketplace

**Problemi noti:**

* &lbrack;Mac M1&rbrack; Materiali avanzati non visualizzati correttamente

### 7.3.0

*(Rilasciato: 13 ottobre 2021*)Riepilogo: **Versione principale. Contiene una nuova proiezione di alterazione 3D, una nuova proiezione cilindrica, miglioramenti del selettore colore, nuove funzioni nell&#39;API Python e correzioni di bug**

**Aggiunto:**

* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Esposizione dell’alterazione 3D come nuova modalità di proiezione
* &lbrack;Projection&rbrack;&lbrack;Warp&rbrack; Consenti la modalità decalcomania per Alpha, Texture e procedure con trascinamento nella finestra della vista
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Usa proiezione alterazione con decalcomania (ALT)
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack;&lbrack;Barra&rbrack; Trasforma alterazione come intero o per vertici
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack;&lbrack;Barra degli strumenti&rbrack; Aggiungi punti della griglia con opzioni Dividi alterazione a croce, in orizzontale o in verticale
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack;&lbrack;Barra degli strumenti&rbrack; Menu dedicato per le azioni di ripristino
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack;&lbrack;Barra degli strumenti&rbrack; Opzione per regolare automaticamente le tangenti quando si spostano i punti
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack;&lbrack;Barra degli strumenti&rbrack; Menu dedicato per l&#39;edizione della griglia (dimensioni, reimpostazione, colore e dimensione della maniglia)
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Nuova scelta rapida da tastiera da tastiera per cambiare la modalità edizione alterazione vertici interi (MAIUSC+V)
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Fare clic+Ctrl per passare dallo strumento superficie ad altri strumenti
* &lbrack;Proiezione&rbrack;&lbrack;Cilindrico&rbrack; Esposizione della modalità di proiezione cilindrica
* &lbrack;Proiezione&rbrack;&lbrack;Barra degli strumenti&rbrack; Impostazioni manipolatore di gruppi (dimensioni, passaggi griglia, passaggi angolo)
* &lbrack;Selettore colore&rbrack; Nuova interfaccia utente del selettore colore
* &lbrack;Selettore colore&rbrack; Usa valori sRGB nei widget del selettore colore
* &lbrack;Selettore colore&rbrack; Consenti di salvare ed eliminare campioni colore
* &lbrack;Selettore colore&rbrack; Contagocce accessibile da slot normali e di colore
* &lbrack;Selettore colore&rbrack; Consente di modificare il colore dinamico tra i valori 0 e 255
* &lbrack;Selettore colore&rbrack; Rendi lo stato HSV/RGB comune in tutta l&#39;app
* &lbrack;Selettore colore&rbrack; La finestra del selettore colore è semi-persistente
* &lbrack;Selettore colore&rbrack; Premendo Esc si chiude la finestra del selettore colore
* Miglioramento delle prestazioni per l’interazione dell’interfaccia utente e durante la pittura
* &lbrack;Engine&rbrack; Aggiornamento alla nuova versione del motore di Substance (8.3.0)
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consente di ricaricare la trama del progetto corrente
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di aggiornare le risorse nei progetti
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di impostare ed eseguire query sulla risoluzione delle Porzioni UV
* &lbrack;Interoperability&rbrack; non disponibile per le edizioni Steam e Substance
* &lbrack;Interoperability&rbrack; Ricezione di più risorse da Bridge

**Corretto:**

* Il selettore colore non visualizza il colore corretto
* &lbrack;Eseguite i baking&rbrack; L&#39;elenco dei set di texture non è ordinato correttamente
* &lbrack;FBX import&rbrack; 3ds Le trasformazioni pivot del gruppo Max non vengono considerate
* &lbrack;Substance Engine&rbrack; Arresto anomalo con importazione di SBSAR danneggiati
* &lbrack;MacOS&rbrack; l&#39;opzione di configurazione del progetto in lingue diverse non è presente
* I salvati automaticamente possono bloccare Painter durante processi lunghi

**Problemi noti:**

* &lbrack;Projection&rbrack;&lbrack;Warp&rbrack; Split rimane selezionata al termine della divisione
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
* &lbrack;Proiezione&rbrack;&lbrack;Altera&rbrack; Linee artefatto tra le patch in alcuni rari casi
* &lbrack;Proiezione&rbrack;&lbrack;UV&rbrack; Il punto pivot viene reimpostato quando si capovolge la proiezione
* &lbrack;Mac M1&rbrack; Materiali avanzati non visualizzati correttamente
* &lbrack;M1&rbrack;&lbrack;Regressione&rbrack; Il livellamento dei materiali non funziona

### 7.2.3

*(Rilasciato: 24 agosto 2021*)Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

* &lbrack;Librerie&rbrack; Aggiungi un modo per escludere i file indesiderati dalla ricerca per indicizzazione

**Corretto:**

* &lbrack;Win&rbrack; più schermi e problemi di sospensione
* &lbrack;MacOS&rbrack;&lbrack;Arresto anomalo&rbrack; Commutazione dello shader quando si utilizzano gli effetti
* &lbrack;Viewport&rbrack; la modalità di anteprima completa non mostra più il cursore del pennello senza canale alfa
* &lbrack;UI&rbrack; il widget Angolo non funziona correttamente
* &lbrack;Pila livelli&rbrack; molte sottocartelle causano un blocco molto lungo
* &lbrack;Iray&rbrack; viste diverse in Iray e OpenGL: visibile se non funziona
* &lbrack;Iray&rbrack; Indice di rifrazione non preso in considerazione e non viene visualizzato nelle proprietà mdl
* &lbrack;JavaScript&rbrack; ShowExportDialog() non restituisce mai true
* Impossibile leggere mtl da Adobe Stock

### 7.2.2

*(Rilasciato: 27 luglio 2021*)Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

* Aggiornamento della versione dei requisiti del driver AMD

**Corretto:**

* &lbrack;Mac M1&rbrack; rilevamento memoria errata
* &lbrack;Export&rbrack; I tracciati molto lunghi non vengono visualizzati correttamente

**Problemi noti:**

* &nero;Contenuto&nero; Ombreggiature obsolete dei campioni

### 7.2.1

*(Rilasciato: 2 luglio 2021*)Riepilogo: **Rilascio secondario, Hotfix**

**Aggiunto:**

* &lbrack;Interop&rbrack; Aggiungi descrizione per informare che l’invio di progetti Porzione UV a Stager non è ancora supportato
* &lbrack;Plugin&brack;&lbrack;UI&rbrack; aggiornamento dell&#39;icona di collegamento dinamico

**Corretto:**

* &lbrack;Nvidia&rbrack; La versione del driver che inizia con 30 è considerata obsoleta
* &blocco;Librerie&rbrack; lo stato del pannello Risorse non viene salvato a meno che un progetto non sia aperto
* &lbrack;Librerie&rbrack; la nuova ricerca salvata mantiene la parola chiave della vecchia ricerca salvata
* &lbrack;Baker&rbrack;&lbrack;UVTiles&rbrack; Anche le mappe ID per meshID prendono in considerazione le Porzioni UV
* &lbrack;Export&rbrack; gLTF non importa il colore dei vertici
* &lbrack;Iray&brack; mancano alcune descrizioni comandi
* &lbrack;Interop&rbrack; Invia a Stager non è sempre disabilitato quando Stager non viene rilevato
* &lbrack;Resource Updater&rbrack; impossibile aggiornare il creatore di pennelli di Photoshop
* &lbrack;Content&rbrack; Il generatore di usura dei bordi in fibra di vetro è rotto

### 7.2.0

*(Rilasciato: 23 giugno 2021*)Riepilogo: **Versione principale, fornisce un aggiornamento al pannello delle risorse, un nuovo shader con accesso a nuovi canali e parametri, un aggiornamento complessivo dell’interfaccia utente, alcuni miglioramenti delle prestazioni molto richiesti, supporto linguistico esteso e altro ancora.**

**Aggiunto:**

* &blocco;Librerie&rbrack; Nuovo pannello Risorse per sostituire lo scaffale
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Nuovo layout pannello Risorse
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Cambiare l&#39;orientamento e l&#39;interfaccia utente predefiniti del pannello Risorse
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Introduce un&#39;opzione di visualizzazione elenco alla libreria
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Nuovo percorso di navigazione nel pannello Risorse
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Selezionare &quot;Tutte le librerie&quot; quando si seleziona una ricerca salvata
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Seleziona &quot;Tutte le librerie&quot; quando tutte le cartelle sono deselezionate
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Nuovo tag per i pennelli particelle
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Sostituito da &quot;shelf&quot; con &quot;Tutte le librerie&quot; nell&#39;app
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Consenti di nascondere le cartelle vuote
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; La libreria utente predefinita dovrebbe essere visibile anche se vuota
* &lbrack;Libraries&rbrack;&lbrack;UI&rbrack; Nuovo metodo di filtraggio tramite le icone dei tipi di risorsa
* &lbrack;Libraries&rbrack; Scelta rapida da tastiera &quot;CTRL&quot; per selezionare più tipi di risorse
* &lbrack;Libraries&rbrack; Nuova variabile di ambiente per controllare il budget della memoria di anteprima della risorsa
* &lbrack;Libraries&rbrack;&lbrack;Content&rbrack; Mappe nuovo ambiente
* &lbrack;Libraries&rbrack;&lbrack;Content&rbrack;&lbrack;UI&rbrack; spostamento di rendering nei materiali predefiniti
* &lbrack;Libraries&rbrack;&lbrack;Content&rbrack; Imposta lo shader dell&#39;Adobe Standard Material (ASM) come predefinito per la generazione delle anteprime
* &lbrack;Libraries&rbrack;&lbrack;Content&rbrack;&lbrack;ASM&rbrack; Nuovi modelli di progetto per il nuovo shader ASM
* &lbrack;Libraries&rbrack;&lbrack;Thumbnail&rbrack; Use new Studio 6 environment map
* &lbrack;Libraries&rbrack;&lbrack;Thumbnail&rbrack; Leggi la miniatura nella risorsa invece di generarla
* &lbrack;Libraries&rbrack;&lbrack;Thumbnail&rbrack; Aggiungi spostamento alla generazione delle miniature
* &lbrack;Impostazioni set di texture&rbrack;
* &lbrack;Impostazioni set di texture&rbrack;&lbrack;UI&rbrack; Esposizione del nuovo height al metodo di conversione normale
* &lbrack;Texture Set Settings&rbrack;&lbrack;UI&rbrack; Rielaborazione dell&#39;organizzazione dell&#39;interfaccia utente dei canali
* &lbrack;Texture Set Settings&rbrack; limite canali utente elevato a 16 canali
* &lbrack;Texture Set Settings&rbrack;&lbrack;UI&rbrack; Indica i canali compatibili con lo shader selezionato
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; Nuovo shader Adobe Standard Material
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; Supporto aggiunto per Anisotropia, Cancella pelo, Dispersione sottosuperficie, Specular edge color e Brillantezza
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; modifica i valori di colore dei canali predefiniti
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack;&lbrack;Export&rbrack; Modello di esportazione aggiornato Adobe Dimension in Adobe Substance 3D Stager
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; etichette e descrizioni comandi aggiunte per i parametri shader e MDL
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; Rende visibile il colore della Dispersione in vista 2D anche se SSS non è supportato
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack;&lbrack;Iray&rbrack; Supporto dello shader ASM in Iray con la nuova MDL
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack;&lbrack;Iray&rbrack; Scattering sottosuperficie aggiornato in lucido e patinato specifiche PBR legacy
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack;&lbrack;Content&rbrack; ha modificato il tipo SSS predefinito per gli esempi
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; Documentazione aggiunta per l&#39;API ASM
* &lbrack;Shader&rbrack;&lbrack;ASM&rbrack; Ottimizza gli ombreggiatori per ignorare i canali inutilizzati
* &lbrack;Shader&rbrack; Esposizione dei nuovi canali degli insiemi di texture
* &lbrack;Shader&rbrack; Dispersione sottosuperficie migliorata
* &lbrack;Shader&rbrack; nuovi parametri di shader nascosti per alcuni ombreggiatori
* &lbrack;Shader&rbrack; Visibile se per i parametri di shader
* &lbrack;Performance&rbrack;
* &lbrack;Librerie&rbrack; Anteprima risorse: caricamento tempo e prestazioni di calcolo migliorate
* &lbrack;Engine&rbrack; Miglioramento delle prestazioni di pittura
* &lbrack;Auto Unwrap&rbrack;
* &lbrack;Auto Unwrap&rbrack; miglioramenti alle prestazioni Impacchettamenti
* &lbrack;Auto Unwrap&rbrack; Auto unwrap compatibile con il flusso di lavoro Porzione UV
* &lbrack;Srotolamento automatico&rbrack; Nuova opzione per posizionare gli UV in base all&#39;orientamento della trama
* &blocco;Altro&blocco;
* &lbrack;Impostazioni&rbrack; direzione di zoom predefinita modificata
* &lbrack;UI&rbrack; aggiornamento generale dell&#39;interfaccia utente
* &lbrack;UI&rbrack; Rielaborazione del menu?
* &lbrack;UI&rbrack; Sostituisci icona inversa
* &lbrack;UI&rbrack;&lbrack;Plugin&rbrack; Sostituisci icona per il collegamento dcc del plug-in
* &lbrack;UI&rbrack;&lbrack;AMD&rbrack; Aggiorna la versione minima richiesta e il messaggio popup
* &lbrack;Pila livelli&rbrack; Crea nuovo livello all&#39;interno della cartella vuota selezionata
* Aggiornamento della documentazione Python
* &lbrack;Branding&rbrack;
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Nome applicazione aggiornato in Adobe Substance 3D Painter
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Versione standalone aggiornata a &#39;Substance edition&#39;
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Nome eseguibile dell&#39;applicazione aggiornato, percorso di installazione, pacchetto e icone
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Libreria e percorso predefiniti rinominati
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Aggiornamento della finestra Informazioni su
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Schermata introduttiva aggiornata
* &lbrack;Branding&rbrack;&lbrack;UI&rbrack; Rimosso il numero di versione basato sull&#39;anno
* &lbrack;Localization&rbrack; Nuove traduzioni in tedesco, francese e cinese semplificato
* &lbrack;Interoperability&rbrack; non disponibile per le edizioni Steam e Substance
* &lbrack;Interoperabilità&rbrack; Interoperabilità con l&#39;ecosistema Adobe: Designer, Sampler, Stager e Bridge
* &lbrack;Interoperability&rbrack;&lbrack;UI&rbrack; Ricevi e aggiorna la risorsa da Designer
* &lbrack;Interoperability&rbrack;&lbrack;UI&rbrack; Ricevi risorsa da Sampler
* &lbrack;Interoperability&rbrack;&lbrack;UI&rbrack; Invia risorsa a Stager
* &lbrack;Interoperability&rbrack;&lbrack;UI&rbrack; Mostra in Adobe Bridge
* &lbrack;Interoperability&rbrack;&lbrack;UI&rbrack; Consenti di accedere rapidamente a Risorse Adobe 3D
* &lbrack;Interoperability&rbrack; Nuovi tag di utilizzo di sbsar
* &lbrack;Interoperabilità&rbrack; Handle ricevuto tipi di risorse
* &lbrack;Interoperability&rbrack; Le risorse ricevute da Adobe Substance 3D Designer o Adobe Substance 3D Sampler sono archiviate nella libreria scelta di default dall&#39;utente
* &lbrack;Interoperability&rbrack;&lbrack;UI&rbrack; Nuova icona nella barra degli strumenti a sinistra da inviare a Stager o Photoshop

**Corretto:**

* &lbrack;Tablet&rbrack; prestazioni ridotte durante la pittura con pressione
* &lbrack;Tablet&rbrack; Problema con i tablet con controlli del cursore
* &lbrack;Arresto anomalo&rbrack; nome non corrispondente tra l&#39;elenco e l&#39;Esportazione del set di texture
* &lbrack;Arresto anomalo&rbrack;&lbrack;Libraries&rbrack; Fare doppio clic su una libreria secondaria
* &lbrack;Libraries&rbrack; Problema durante la ricerca per indicizzazione delle directory della libreria
* &lbrack;Libraries&rbrack; La riga di comando Forza generazione anteprima non funziona come previsto
* &lbrack;Libraries&rbrack;&lbrack;Content&rbrack; Il filtro Ambiente luce Eseguito i baking è nero per impostazione predefinita
* &lbrack;Linux&rbrack;&lbrack;MacOS&rbrack;&lbrack;Esporta mesh&rbrack; Impossibile importare glTF creato su Linux/MacOS
* &lbrack;Linux&rbrack; Se si trascina un file nel pannello Risorse, si può verificare un arresto anomalo
* &lbrack;Srotolamenti automatici&rbrack; Lo Srotolamento automatico è disponibile anche se non è stata selezionata una trama per il ricaricamento
* &lbrack;Particelle&rbrack; comportamento particella errato con gravità
* &lbrack;Pila livelli&rbrack; L&#39;istogramma dei livelli può utilizzare la luminanza solo con alcuni canali
* &blocca;Maschera geometria; Il menu di scelta rapida di una cartella quando si modifica la maschera di geometria non funziona
* &lbrack;Proiezione&rbrack; giuntura con proiezione sferica e filtro bilineare
* &lbrack;Porzione UV&rbrack; Esporta maschera in file esporta solo la porzione 0, 0
* &lbrack;Esporta trama&rbrack; l&#39;esportazione della trama FBX è vuota
* &lbrack;Iray&rbrack; La Mappa normale non viene considerata nei nuovi progetti durante il rendering
* &lbrack;Salva&rbrack; Salva problemi su unità condivise
* &lbrack;Eseguite i baking&rbrack; Se si rigenera una trama con parametri modificati, viene visualizzato un avviso
* &lbrack;Esegui i baking&rbrack;&lbrack;Regressione&rbrack; Risultato errato quando il rettangolo di selezione globale di trame di poli superiori non include l&#39;origine della scena
* &lbrack;Python&rbrack; Le librerie utente personalizzate non vengono considerate

**Problemi noti:**

* &lbrack;Librerie&rbrack; ricerche salvate non salvate se non è aperto alcun progetto
* &lbrack;NVIDIA&rbrack; Messaggio per driver obsoleto anche se aggiornato

### 7.1.1 (2021.1.1)

*(Rilasciato: 23 marzo 2021*)Riepilogo: **Versione secondaria, Bugfix con possibilità di immettere valori esadecimali nel selettore colore**

**Aggiunto:**

* &lbrack;Log&brack; Avvisa gli utenti in caso di driver GPU AMD incompatibili
* &lbrack;Selettore colore&rbrack; Consente di digitare valori esadecimali

**Corretto:**

* &lbrack;Baker&rbrack; Prestazioni esterne
* &lbrack;Geometry mask&rbrack; se si fa clic sul nome della trama tenendo premuto il tasto Alt, si potrebbe verificare un arresto anomalo
* &lbrack;Engine&rbrack; Il disegno non aggiorna l&#39;intera visualizzazione quando necessario
* &lbrack;Pila livelli&rbrack; la selezione si blocca dopo la modifica dello shader
* &lbrack;MacOS&rbrack;&lbrack;Selettore colore&rbrack; Il colore è leggermente diverso da quello selezionato
* &lbrack;Export&rbrack; L&#39;utilizzo del formato di file PSD non genera un file per Porzione UV
* &lbrack;Scripting&rbrack;&lbrack;Javascript&rbrack; alg.mapexport.getPathsExportDocumentMaps() non restituisce tutti i valori
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; I plug-in disattivati vengono nuovamente attivati alla riapertura di Painter

### 7.1.0 (2021.1.0)

*(Rilasciato: 28 gennaio 2021*)Riepilogo: **Versione principale, nuova maschera di geometria che consente di selezionare e pittura parti della geometria, copiare/incollare effetti nella Pila livelli, miglioramento del flusso di lavoro della Porzione UV, aggiornamento di Iray, Baker, Substance Engine e nuovo contenuto**

**Aggiunto:**

* Nuova maschera di geometria e pittura parti selezionate della geometria
* &lbrack;Geometry Mask&rbrack; Consenti di pittura le parti selezionate della geometria in base ai nomi della trama
* &lbrack;Geometry Mask&rbrack; selezione rettangolare in entrambe le finestre
* &blocco;Maschera geometria&rbrack; Consenti di nascondere/ignorare la geometria esclusa su qualsiasi livello
* &lbrack;Geometry Mask&rbrack;&lbrack;Properties&rbrack; Selezione rapida delle caselle di controllo con clic e trascinamento
* &lbrack;Geometry Mask&rbrack;&lbrack;Properties&rbrack;&lbrack;UI&rbrack; Includi/Escludi tutto con un menu a discesa nella finestra Proprietà
* &lbrack;Geometry Mask&rbrack;&lbrack;Properties&rbrack; Consenti di selezionare rapidamente una voce in un elenco con ALT+CLIC SINISTRO
* &lbrack;Geometry Mask&rbrack;&lbrack;Properties&rbrack; Sovrapposizione nelle finestre delle viste quando si passa con il mouse sui nomi delle trame o sulle Porzioni UV nella finestra Proprietà
* &lbrack;Geometry Mask&rbrack;&lbrack;Pila livelli&rbrack; Aggiungi opzioni Copia/Incolla alla maschera di geometria
* &blocca;Maschera geometria&rbrack; icona Nuova per il pulsante Nascondi/Ignora geometria esclusa
* &lbrack;Geometry Mask&rbrack; Nuovo tooltip per Nascondi/Ignora geometria esclusa
* &lbrack;Geometry Mask&rbrack; scelta rapida da tastiera da tastiera ALT+H per attivare/disattivare il pulsante &quot;Ignora geometria esclusa&quot;
* &lbrack;Porzione UV&rbrack;&lbrack;Pila livelli&rbrack; Nuova miniatura di anteprima della sfera del livello di riempimento per la Porzione UV e la modalità semplificata
* &lbrack;Porzione UV&rbrack;&lbrack;Pila livelli&rbrack; Consente di uscire facilmente dalla maschera Porzione UV
* &lbrack;Porzione UV&rbrack;&lbrack;Texture Set List&rbrack; Consenti di fornire una descrizione per Porzione UV
* &lbrack;Porzione UV&rbrack;&lbrack;Texture Set Settings&rbrack;&lbrack;UI&rbrack; Due nuovi titoli di sezione nel menu a discesa per modificare la risoluzione delle Porzioni UV
* &lbrack;Porzione UV&rbrack;&lbrack;Finestra&vista; Esci da Porzione UV maschera quando si trascina un materiale nella finestra della vista
* &blocco;Pila livelli&rbrack; Aggiungi opzioni di copia/incolla per gli effetti
* &lbrack;Pila livelli&rbrack; consente di copiare/incollare gli effetti da un set di texture a un altro
* &lbrack;Pila livelli&rbrack; Consenti selezione multipla di effetti
* &blocco;Pila livelli&rbrack; Aggiungi opzioni di copia/incolla come scelte rapide per gli effetti di livello
* &lbrack;Pila livelli&rbrack; Passa automaticamente tra maschera e contenuto quando si trascinano gli effetti in un altro livello
* &lbrack;Pila livelli&rbrack; crea automaticamente una maschera quando si incolla una maschera da un altro livello
* &lbrack;Pila livelli&rbrack; Aggiungi azioni effetto di spostamento all&#39;interno del menu contestuale di scelta rapida degli effetti
* &lbrack;Pila livelli&rbrack; Consenti di trascinare gli effetti da un livello all&#39;altro
* &lbrack;Pila livelli&rbrack; trascinando gli elementi in una cartella, questi vengono posizionati nella parte superiore della cartella
* Aggiornamento di Iray alla versione 2020.1.0
* &lbrack;Baker&rbrack; Aggiorna i Baker alla versione 2.5.4
* &lbrack;Baker&rbrack; Visualizza le singole Porzioni UV nella finestra di avanzamento eseguita i baking
* &lbrack;Baker&rbrack;&lbrack;UI&rbrack; Consente di eseguire i baking rapidamente il set di texture corrente con un nuovo pulsante
* &lbrack;Baker&rbrack; Consente all&#39;utente di selezionare rapidamente uno dei baker con ALT+CLIC SINISTRO
* Aggiorna Substance Engine alla versione 8.0.8
* &lbrack;Substance Engine&rbrack; supporta il colore predefinito nei nuovi file .sbsar
* &lbrack;Auto Unwrap&rbrack; miglioramento delle prestazioni
* &lbrack;Export&rbrack; Aggiungi un feedback visivo per indicare quale risoluzione di Porzione UV differisce da quella predefinita del progetto
* &lbrack;Export&rbrack; Aggiungi fattore dimensioni scena nel file json shader esportato
* &lbrack;Lingua&rbrack; Aggiungi traduzione giapponese
* &lbrack;UI&rbrack; Aggiorna informazioni su finestra con controllo delle versioni delle dipendenze interne
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di gestire le risorse degli scaffali
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di sapere quando un progetto è pronto per essere eseguito i baking ed esportato
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di sapere quando uno scaffale ha terminato la ricerca per indicizzazione delle risorse sul disco
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di eseguire query sull&#39;elenco di porzioni UV per set di texture
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di assegnare l&#39;anteprima personalizzata alle risorse Shelf
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di gestire scaffali personalizzati
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Aggiungi un indice di metodo in ogni sottomodulo della documentazione
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Nuovo stile per la documentazione
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Miglioramento delle risorse e della documentazione dello scaffale
* &lbrack;Content&rbrack; Tre nuovi strumenti predefiniti per creare punti
* &lbrack;Shelf&rbrack; Rimuovi temporaneamente &quot;Esporta in Substance share&quot; durante la transizione alla nuova piattaforma di Substance share

**Corretto:**

* Arresto anomalo di utilizzo di monitor con risoluzioni diverse
* Arresto anomalo in Substance Engine con alcuni progetti rari
* L’aggiornamento della finestra della vista non riesce con Nascondi/Ignora geometria esclusa quando si cambia livello
* &lbrack;vista 2D&rbrack; il riquadro di visualizzazione 2D potrebbe non essere presente in alcuni progetti
* &lbrack;Eseguire i baking&rbrack; &quot;Corrispondenza per nome trama&quot; ignora parti dell&#39;oggetto
* &lbrack;Pila livelli&rbrack; se si fa clic su un effetto di livello, viene aperta la cartella
* &lbrack;Geometry Mask&rbrack; La Porzione UV viene comunque conteggiata nella maschera anche quando si reimporta la trama senza di essa
* &lbrack;Geometry Mask&rbrack; Il menu di scelta rapida nella finestra della vista non fornisce gli strumenti corretti
* &lbrack;Engine&rbrack; Segnali di ritardo gravi su progetti specifici
* &lbrack;Scripting&rbrack; latenza elevata con richieste JSON POST remote in Windows
* &lbrack;Linux&rbrack; La quantità di Vram non viene rilevata correttamente con specifiche GPU integrate
* &lbrack;Auto Unwrap&rbrack; Arresti anomali o tempi lunghi per l&#39;annullamento del wrapping su alcuni progetti

## Versione 6

### 6.2.2 (2020.2.2)

*(Rilasciato: 28 settembre 2020*)Riepilogo: **Versione secondaria, Bugfix con alcune funzioni nell&#39;API Python**

**Aggiunto:**

* &lbrack;Performance&rbrack; Non calcolare tutte le Porzioni UV quando si utilizza la selezione ID colore
* &lbrack;Baker&rbrack;&lbrack;UI&rbrack; Visualizza le descrizioni del set di texture
* &lbrack;Baker&rbrack; Consenti di salvare le impostazioni di esegue i baking
* &lbrack;Baker&rbrack; Aggiungi comprimi tutte/espandi tutte le opzioni alla scheda Selezione
* &lbrack;Texture Set List&rbrack; Nascondi descrizione se vuoto
* &lbrack;Porzione UV&rbrack;&lbrack;Texture Set List&rbrack; Fare clic su Porzione UV per espandere/comprimere l&#39;elenco
* &lbrack;Export&rbrack;&lbrack;UI&rbrack; Consente di ridimensionare il pannello Elenco set di texture in orizzontale
* &lbrack;Export&rbrack;&lbrack;UI&rbrack; Testo coerente delle descrizioni per il flusso di lavoro Porzione UV e Set di texture con texture non selezionata
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di utilizzare i predefiniti di esportazione per esportare la texture
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Aggiungi un registro modifiche nella documentazione
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti di eseguire una query su tutti i canali disponibili in un determinato stack
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; miglioramenti dell&#39;interfaccia utente della console

**Corretto:**

* &lbrack;AMD&rbrack; Rilevamento non corretto della versione del driver obsoleta
* Arresto anomalo di reimportazione di una trama con layout di Porzione UV diverso in alcuni casi
* Arresto anomalo quando si utilizzano particelle con UDIM su trame molto pesanti
* &lbrack;Porzione UV&rbrack; Arresto anomalo durante l&#39;esportazione di una trama con informazioni di spostamento in alcuni casi
* &lbrack;Export&rbrack;&lbrack;Arresto anomalo&rbrack; L&#39;esportazione di Vista 2D in formato psd può causare un arresto anomalo
* L’importazione di immagini come sequenze durante la creazione di un progetto non funziona
* Motore bloccato in un ciclo continuo
* &lbrack;Scelta rapida da tastiera&rbrack; la fotocamera ruota sempre in modalità snap quando si modificano le scelte rapide della modalità snap
* Le trame vengono sempre annullate automaticamente quando vengono reimportate, anche se l’opzione è disattivata
* &lbrack;Texture Set List&rbrack; Il campo di testo Descrizione a volte non è completamente visibile durante l&#39;edizione
* &lbrack;Elenco&amp;rbrack set di texture; Il menu a discesa per nascondere/mostrare i set di texture non è completamente visibile
* &lbrack;Elenco set di texture&rbrack; se si fa clic sull&#39;icona occhio, non deve essere immesso il nome &quot;Modifica set di texture&quot;
* &lbrack;Impostazioni set di texture&rbrack; la rimozione di un canale rimuove anche il canale sottostante
* &lbrack;Export&rbrack; Includi tutto e Reimposta tutto non prende in considerazione le Porzioni UV
* &lbrack;Baker&rbrack; durante la esegue i baking vengono visualizzati i baker deselezionati
* L’aggiornamento della risoluzione non viene considerato per le mappe con baking utilizzate come input
* &lbrack;Porzioni UV&rbrack;&lbrack;Viewport&rbrack; 3D Viewport si blocca quando si aggiunge un Materiale avanzato dopo l&#39;altro con la maschera Porzione UV selezionata
* &lbrack;Porzione UV&rbrack;&lbrack;Viewport&rbrack; Il Wireframe è ancora visibile per le porzioni nascoste con la modalità pittura passante
* &lbrack;Export&rbrack;&lbrack;Sketchfab&rbrack; Problemi con il tipo di abbonamento &quot;più&quot;
* &lbrack;Sketchfab&rbrack; la casella di controllo &quot;Questa risorsa è privata&quot; non viene visualizzata dopo il cambio di account
* &lbrack;Esporta&rbrack;&lbrack;Contenuto&rbrack; I predefiniti &quot;Deformazioni in movimento&quot; del pennello possono causare problemi di prestazioni
* &lbrack;Plugin Photoshop&rbrack; Messaggio nel registro: non compatibile con il flusso di lavoro Porzione UV
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; PYTHONPATH env var impedisce l&#39;avvio dell&#39;applicazione
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Typo nella documentazione Python

### 6.2.1 (2020.2.1)

*(Rilasciato: 29 luglio 2020*)Riepilogo: **Versione secondaria, Hotfix**

**Aggiunto:**

* Aggiungere la variabile di ambiente &quot;SUBSTANCE_PAINTER_VRAM_BUDGET&quot; per ignorare la quantità VRam della GPU
* &lbrack;Porzione UV&rbrack;&lbrack;Prestazioni&rbrack; Non calcolare tutte le porzioni UV quando si utilizza lo strumento Riempimento poligonale

**Corretto:**

* &lbrack;Iray&brack; Salva rendering restituisce un errore e restituisce un&#39;immagine nera
* &lbrack;Linux&rbrack; Arresto anomalo dopo la schermata iniziale su CentOS 7.3
* &lbrack;Linux&rbrack; La quantità di Vram non viene rilevata correttamente con configurazioni specifiche
* &lbrack;Arresto anomalo&rbrack; apertura di un progetto con il nome di un set di texture duplicato
* &lbrack;Engine&rbrack; Problema di invalidamento della cache durante la modifica di una maschera
* &lbrack;Elenco set di texture&rbrack; Effetto font errato quando il set di texture è disattivato

**Problemi noti:**

* &lbrack;Texture Set List&rbrack; Impossibile nascondere la descrizione
* Problemi dell&#39;interfaccia utente di &lbrack;Texture Set List&rbrack;
* &lbrack;Iray&rbrack; il rendering PSD non si apre
* &lbrack;Plugin Photoshop&rbrack; non compatibile con il flusso di lavoro Porzione UV

### 6.2.0 (2020.2.0)

*(Rilasciato: 23 luglio 2020*)Riepilogo: **Versione principale con nuovo flusso di lavoro Porzione UV, pittura tra Porzioni UV e miglioramento delle prestazioni**

**Aggiunto:**

* Porzioni UV (UDIM)
* &lbrack;Porzione UV&rbrack; Pittura tra porzioni UV
* &lbrack;Porzione UV&rbrack; consente di scegliere tra flusso di lavoro nuovo e legacy per la Porzione UV
* &lbrack;Porzione UV&rbrack; Importa UDIM/Porzione UV sequenze di immagini come risorsa
* &lbrack;Porzioni UV&rbrack; Aggiungi elenco di Porzioni UV per set di texture nella finestra Elenco set di texture
* &lbrack;Porzione UV&rbrack; consente di modificare contemporaneamente la risoluzione di più Porzioni UV nelle impostazioni del set di texture
* &lbrack;Porzione UV&rbrack;&lbrack;vista 2D&rbrack; Visualizza la Porzione UV come griglia
* &lbrack;Porzione UV&rbrack;&lbrack;vista 2D&rbrack; pulsante Nuova finestra per visualizzare o nascondere le informazioni sulla Porzione UV
* &lbrack;Porzione UV&rbrack; per impostazione predefinita, per i progetti di Porzione UV imposta lo strumento di pittura su un singolo canale
* &lbrack;Porzione UV&rbrack; Nuovo pulsante nella barra degli strumenti contestuale per ignorare la Porzione UV mascherata durante il disegno
* &lbrack;Porzione UV&rbrack;&lbrack;Pila livelli&rbrack; nuove icone Pila livelli per migliorare le prestazioni
* &lbrack;Porzioni UV&rbrack;&lbrack;Pila livelli&rbrack; Migliorare le icone di Pittura e riempimento nella barra degli strumenti
* &lbrack;Porzione UV maschera&rbrack;&lbrack;vista 2D&rbrack; Consente di includere o escludere più Porzioni UV contemporaneamente (clic sinistro, CTRL+clic sinistro)
* &lbrack;Maschera Porzione UV&rbrack; Nuova maschera Porzione UV da includere, esclude le porzioni per livello con una nuova icona
* &lbrack;Porzione UV maschera&rbrack;&lbrack;Pila livelli&rbrack; Visualizza il numero di Porzioni UV nell&#39;icona della maschera Porzione UV quando non tutte sono incluse
* &lbrack;Porzione UV maschera&rbrack;&lbrack;2D/vista 3D&rbrack; Aggiungi effetto al passaggio del mouse per visualizzare le Porzioni UV sotto il cursore
* &lbrack;Porzioni UV&rbrack;&lbrack;Baker&rbrack; Consente di selezionare e eseguire i baking Porzioni UV specifiche
* &lbrack;Porzione UV&rbrack;&lbrack;Baker&rbrack; Aggiungi opzioni di selezione per set di texture/Porzione UV
* &lbrack;Porzione UV&rbrack;&lbrack;Baker&rbrack; Opzione del menu di scelta rapida per selezionare le Porzioni UV di un set di texture
* &lbrack;Porzione UV&rbrack;&lbrack;Baker&rbrack; Consenti selezione rapida in Set di texture/Porzioni UV mediante trascinamento
* &lbrack;Porzioni UV&rbrack;&lbrack;Baker&rbrack; Sostituire i pulsanti &quot;Tutto&quot; e &quot;Nessuno&quot; nelle mappe trama con opzioni di selezione più esplicite
* &lbrack;Porzioni UV&rbrack;&lbrack;Baker&rbrack; Visualizza il numero di texture da eseguire i baking
* &lbrack;Porzione UV&rbrack;&lbrack;Esporta&rbrack; Consente di selezionare ed esportare Porzione UV specifica
* &lbrack;Porzione UV&rbrack;&lbrack;Esporta&rbrack; Consenti selezione rapida di Porzione UV mediante trascinamento
* &lbrack;Porzioni UV&rbrack;&lbrack;Export&rbrack; Aggiungi opzioni del menu a discesa per la Porzione UV
* &lbrack;Porzioni UV&rbrack;&lbrack;Export&rbrack; Rende non disponibili alcuni predefiniti di esportazione se non funzionano con la Porzione UV (Adobe Dimension, Sketchfab, glTF, USD)
* &lbrack;Porzione UV&rbrack;&lbrack;Content&rbrack; Aggiorna i predefiniti di esportazione per utilizzare il nuovo tag $udim
* &lbrack;Porzione UV&rbrack; migliora la segnalazione degli errori durante l&#39;importazione di trame con Isole UV sovrapposte
* &lbrack;Porzione UV&rbrack; Porzione UV compatibile in Iray
* &lbrack;Porzione UV&rbrack;&lbrack;Scripting&rbrack; Aggiungi la documentazione di esportazione delle Porzioni UV al documento Python
* Prestazioni
* &lbrack;Prestazioni&rbrack; Nuovo pulsante nella barra degli strumenti contestuale per sospendere il calcolo del motore durante il lavoro (MAIUSC+ESC)
* &lbrack;Performance&rbrack; Apertura più rapida del progetto ritardando il calcolo della cache del set di texture
* &lbrack;Prestazioni&rbrack; Non attendere il caricamento delle mappe mesh all&#39;apertura del progetto
* &lbrack;Performance&rbrack;&lbrack;2D/vista 3D&rbrack; Non calcolare il canale maschera nella finestra della vista quando non viene utilizzato
* &lbrack;Performance&rbrack; Non bloccare l&#39;applicazione durante il caricamento delle mappe mesh visualizzate nelle finestre delle viste
* &lbrack;Prestazioni&rbrack; Migliora la velocità di salvataggio incrementale durante il salvataggio di un progetto
* &lbrack;Performance&rbrack;&lbrack;Baker&rbrack; Modificare le impostazioni di dilatazione predefinite per migliorare il risparmio di tempo e le dimensioni del progetto
* &lbrack;Performance&rbrack;&lbrack;Baker&rbrack; Passa a scala di grigi su Baker specifici per migliorare il tempo di salvataggio e la dimensione del progetto
* &lbrack;Performance&rbrack;&lbrack;Export&rbrack; Migliora le prestazioni del motore per esportare texture più velocemente
* &lbrack;Performance&rbrack;&lbrack;Export&rbrack; Migliora la reattività quando si apre la finestra di dialogo di esportazione con molti set di texture
* &lbrack;Performance&rbrack;&lbrack;Export&rbrack; Migliora le prestazioni quando si passa alla scheda &quot;Elenco esportazioni&quot;
* &lbrack;Performance&rbrack;&lbrack;Iray&rbrack; Ridurre il tempo di avvio di Iray
* Altro
* &lbrack;Baker&rbrack; Aggiungi opzioni di selezione per set di texture
* Sposta la gestione delle istanze shader nelle impostazioni del set di texture
* &lbrack;2D/vista 3D&rbrack; Aggiungi un messaggio nella parte inferiore della finestra della vista per indicare il tipo di maschera modificato
* &lbrack;Pila livelli&rbrack; Nuova opzione nelle impostazioni per passare dalla miniatura precedente a quella nuova
* &lbrack;Pila livelli&rbrack; Aggiungi un feedback visivo per indicare lo stato di caricamento delle miniature
* &lbrack;Proj&rbrack; Nuova modalità di proiezione &quot;Riempi (come per porzione UV)&quot; per caricare le sequenze di immagini
* &lbrack;Proj&rbrack; Modifica la modalità di proiezione dei livelli di riempimento su &quot;Riempi (come per porzione UV)&quot; in casi specifici
* &lbrack;Content&rbrack; Ottimizza i predefiniti del pennello Carboncino per migliorare le prestazioni
* Aggiornamento di Iray alla versione 2020.0.0
* &blocco;Esporta&rbrack; Disattiva elenco delle esportazioni quando non è selezionato nulla
* Annulla contornamento automatico
* &lbrack;Auto Unwrap&rbrack; migliora la percentuale di successo del processo di annullamento automatico del wrapping
* &lbrack;Auto Unwrap&rbrack; parametrizzazione migliorata per aumentare velocità e stabilità

**Corretto:**

* &lbrack;Alembic&rbrack; I set di facce vengono ignorati durante l&#39;importazione dei file
* &lbrack;Alembic&rbrack; Tempo di caricamento infinito con file specifici
* &lbrack;Import&rbrack; Quando solo l&#39;estensione del file è diversa, viene importata una sequenza di immagini UDIM errata
* &lbrack;Arresto anomalo&rbrack; Se si tenta di aprire un progetto bloccato da un altro processo, viene generato un arresto anomalo
* &lbrack;Proiezione&rbrack; Artefatti sulla trama duplicata quando si utilizza la proiezione triplanare
* &lbrack;Export&rbrack; Il canale Emissivo non viene esportato con il formato USD
* &lbrack;Content&rbrack; Il Materiale avanzato &quot;Carboncino&quot; contiene tratti di pittura

**Problemi noti:**

* &lbrack;Texture Set List&rbrack; Impossibile nascondere la descrizione
* Problemi dell&#39;interfaccia utente di &lbrack;Texture Set List&rbrack;

### 6.1.3 (2020.1.3)

*(Rilasciato: 16 Giugno 2020*)Riepilogo: **Bugfix**

**Aggiunto:**

* &lbrack;Export&rbrack; Aggiungi impostazioni di spostamento nel file json dei parametri di Shader

**Corretto:**

* &lbrack;Arresto anomalo&rbrack;&lbrack;Engine&rbrack; Arresto anomalo durante il tentativo di cancellare e sostituire i canali esistenti
* &lbrack;Arresto anomalo&rbrack; Modifica dello shader dopo aver colorato una maschera in livelli di materiale
* &lbrack;Arresto anomalo&rbrack;&lbrack;Engine&rbrack; Arresti anomali con alcuni progetti pesanti
* &lbrack;Baker&rbrack; La corrispondenza per nome non funziona con l&#39;OBJ esportato da zBrush
* &lbrack;Spostamento&rbrack;&lbrack;SVT&rbrack; le Texture non vengono visualizzate all&#39;apertura del progetto quando lo spostamento è attivo
* &lbrack;Export&rbrack; Alcune texture vengono esportate in grigio uniforme
* &lbrack;Export&rbrack; I set di texture disabilitati non devono essere esportati per i predefiniti di esportazione Dimension e Sketchfab
* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; Arresto anomalo durante l&#39;utilizzo dell&#39;API JavaScript per accedere alla configurazione di esportazione nell&#39;evento onProjectOpened
* &lbrack;Scripting&rbrack;&lbrack;Javascript&rbrack; onExportFinished() non viene chiamato dopo un&#39;esportazione

### 6.1.2 (2020.1.2)

*(Rilasciato: 28 maggio 2020*)Riepilogo: **Aggiornamento di Substance Engine e Baker**

**Aggiunto:**

* &lbrack;Baker&rbrack; Aggiornamento alla versione più recente
* &lbrack;Baker&rbrack; Nuovo metodo di campionamento in Occlusione ambientale, Curvatura, baker Thickness
* Aggiornamento alla versione di Substance Engine più recente
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consente la creazione di ResourceID per le risorse del progetto
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Consenti query sulle informazioni del canale
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; Aggiunta di funzioni di esecuzione e richiamata per simulare l&#39;esportazione di texture

**Corretto:**

* &lbrack;Baker&rbrack; Normali non corrette nel baker World Space Normals che utilizza una Mappa normale tangente in casi specifici
* &lbrack;Baker&rbrack; Errore durante il eseguo i baking dell&#39;Occlusione ambientale con Optix quando non è presente un poly alto
* &lbrack;Tratti dinamici&rbrack; Ritardo durante il caricamento di un set di texture specifico
* &lbrack;Export&rbrack; Non deve esportare i set di texture disabilitati per USD, glTF
* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; Impossibile modificare le nuove impostazioni del baker di curvatura
* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; alg.texturesets.addChannel() in alcuni casi non restituisce un errore
* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; Typo nella documentazione delle API Javascript per setProjectExportOptions()
* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; esporta sempre tutti i set di texture
* &lbrack;Scripting&rbrack;&lbrack;Python&rbrack; sys.eseguibile restituisce un percorso a python.exe anziché a Substance Painter
* Cache texture non compatibile tra i sistemi operativi Mac e Windows/Linux
* &lbrack;Livelink UE4&rbrack; per tutti gli insiemi di texture in una trama combinata viene utilizzato solo l&#39;ultimo materiale

**Problemi noti:**

* &lbrack;Export&rbrack;&lbrack;Dimension&rbrack;&lbrack;Skecthfab&rbrack; Non deve esportare i set di texture disattivati
* &lbrack;Arresto anomalo&rbrack; Cambia shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.1 (2020.1.1)

*(Rilasciato: 05 Maggio 2020*)Riepilogo: **Hotfix**

**Aggiunto:**

* &lbrack;Export&rbrack; Override stato del feedback visivo su TextureSet

**Corretto:**

* &lbrack;Export&rbrack; dimensione della finestra di Esportazione troppo grande per il monitor con risoluzione speciale e non ridimensionabile
* &lbrack;Esporta&rbrack; Le opzioni non vengono salvate dopo l&#39;esportazione
* &lbrack;Export&rbrack; Arresto anomalo o impossibile esportare con il predefinito di esportazione &quot;dalla cache&quot;
* &lbrack;Esporta&rbrack; se si annulla l&#39;esportazione, viene generata una mappa vuota aggiuntiva imprevista
* &lbrack;Esporta&rbrack; Correggi impostazioni predefinite esportazione virtuale
* &lbrack;Python&rbrack; PYTHONPATH env var non viene considerato
* &lbrack;Python&rbrack;&lbrack;Export&rbrack; L’annullamento dell’esportazione tramite Python restituisce un errore di eccezione
* &lbrack;Python&rbrack;&lbrack;Export&rbrack; export_project_texture un risultato errato con il formato di file psd
* &lbrack;Baker&rbrack; Arresto anomalo su Linux con Raytracing GPU

**Problemi noti:**

* &lbrack;JavaScript&rbrack; Impossibile modificare le nuove impostazioni del baker di curvatura
* &lbrack;JavaScript&rbrack;&lbrack;Export&rbrack; Esporta sempre tutti i set di texture
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; Non deve esportare i set di texture disabilitati
* &lbrack;Arresto anomalo&rbrack; Cambia shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.0 (2020.1.0)

*(Rilasciato: 22 aprile 2020*)Riepilogo: **Versione principale con nuova esportazione di texture e trama (con spostamento e tassellatura), srotolamento UV aggiornato con più controlli, nuovi baker, nuova API per il pitone di scripting, migliore esperienza utente per la proiezione di decalcomanie e nuovi contenuti**

**Aggiunto:**

* Nuova esportazione di texture e trama
* &lbrack;Export&rbrack; Nuova interfaccia di esportazione
* &lbrack;Esporta&rbrack;&lbrack;Esporta tab&rbrack; Consenti la selezione dei canali delle mappe da esportare per set di texture
* &lbrack;Esporta&rbrack;&lbrack;Esporta tab&rbrack; Consenti la modifica delle dimensioni del set di texture per tutti i set di texture in un&#39;unica azione
* &lbrack;Export&rbrack;&lbrack;Export tab&rbrack; Consente un modello diverso per set di texture (eccetto USD, glTF, Sketchfab e Dimension)
* &lbrack;Esporta&rbrack;&lbrack;Esporta tab&rbrack; Attivazione e disattivazione rapida di mappe e set di texture
* &lbrack;Export&rbrack;&lbrack;Export tab&rbrack; Risoluzione di esportazione 8192x8192 non più sperimentale
* &lbrack;Export&rbrack;&lbrack;Export tab&rbrack; Consenti modifica del formato e della profondità di bit del file per mappa
* &lbrack;Esporta&rbrack;&lbrack;Esporta tab&rbrack; Consenti di ripristinare i valori dei parametri predefiniti
* &lbrack;Export&rbrack;&lbrack;Export tab&rbrack; Consente di salvare le impostazioni senza esportarle
* &lbrack;Export&rbrack;&lbrack;Modelli di output tab&rbrack; Rinomina la scheda &quot;Configurazione&quot; in &quot;Modelli di output&quot;
* &lbrack;Esporta&rbrack;&lbrack;Modelli di output tab&rbrack; Consenti definizione di formato file e profondità di bit per mappa predefinita
* &lbrack;Esporta&rbrack;&lbrack;Elenco di esportazioni tab&rbrack; Nuova scheda di anteprima per riepilogare e visualizzare il processo di esportazione
* &lbrack;Importa/esporta mesh&brack; Importa/esporta ottimizzazione prestazioni tempo
* &lbrack;Esporta trama&rbrack; Esporta trama in FBX
* &lbrack;Esporta trama&rbrack; Esporta trama con spostamento e tassellatura
* &lbrack;Esporta mesh&rbrack;&lbrack;UI&rbrack; Nuove impostazioni per il ricalcolo del vertice normale, applica la triangolazione
* &lbrack;Esporta mesh&brack; Esporta topologia mesh originale con nuovi UV generati dallo srotolamento automatico
* Aggiornamento dello srotolamento UV automatico con più controlli
* &lbrack;UV Unwrapping&rbrack;&lbrack;UI&rbrack; Aggiungi impostazione per attivare lo srotolamento UV automatico nella nuova finestra del progetto
* &lbrack;UV Unwrapping&rbrack;&lbrack;UI&rbrack; Nuove opzioni per controllare i passaggi di unwrapping (cuciture, unwrapping, impacchettamento)
* &lbrack;UV Unwrapping&rbrack;&lbrack;UI&rbrack; Consenti la conservazione di cuciture/unwrapping/impacchettamento di unwrapping esistenti
* &lbrack;UV Unwrapping&rbrack;&lbrack;UI&rbrack; Nuove opzioni per ricalcolare completamente i passaggi di unwrapping
* &lbrack;UV Unwrapping&rbrack;&lbrack;UI&rbrack; Nuova opzione per controllare le dimensioni del margine (nessuno, piccolo, medio e grande)
* Nuovi Baker
* &lbrack;Baker&rbrack; Sostituisce la vecchia curvatura con la nuova curvatura dalla trama
* &lbrack;Baker&rbrack; Aggiungi corrispondenza per nome, opzione per ignorare il backface nel baker &quot;Occlusione ambientale&quot;
* &lbrack;Baker&rbrack; Aggiungi opzione piano terreno nel baker &quot;Occlusione ambientale&quot;
* Nuova API Python per scripting (3.7.6)
* &lbrack;Python&rbrack;&lbrack;UI&rbrack; Nuovo menu di script per Python
* &lbrack;Python&rbrack;&lbrack;UI&rbrack; Nuova documentazione Python nel menu Aiuto
* &lbrack;Python&rbrack; Esposizione moduli pitone Substance Painter: substance_painter, alg, display, project.setting, project, texturesets, ui
* &lbrack;Python&rbrack; Esposizione del nuovo modulo Python &quot;substance_painter&quot;
* &lbrack;Python&rbrack; Esposizione del nuovo sottomodulo Python: alg, display, log, project, resource, texturesets, ui
* &lbrack;Python&rbrack; Listener per le modifiche al progetto
* &lbrack;Python&rbrack; Nuovi esempi nella documentazione Python
* &lbrack;JavaScript&rbrack;&lbrack;UI&rbrack; Plugin sostituito da JavaScript
* &lbrack;Viewport&rbrack; consente di creare una proiezione decalcomania &quot;trascinando/rilasciando + ALT&quot; una risorsa dallo scaffale
* Nuovo contenuto
* &lbrack;Content&rbrack; 5 nuovi materiali decalcomanie da Substance Source
* &laback;Content&brack; Aggiungi nuovi modelli di progetto ed esporta predefiniti per il modulo di rendering Maxwell
* &lbrack;Content&rbrack; Aggiungi modello di progetto per esportazione Keyshot 9
* &lbrack;Content&rbrack; Aggiorna il predefinito di esportazione Keyshot 9 per supportare spostamento e emissivo
* &lbrack;Content&rbrack;&lbrack;Esportazione&rbrack; Aggiornamento di tutti i predefiniti di esportazione in base alle versioni più recenti dei motori di gioco e dei moduli di rendering
* &lbrack;Content&rbrack;&lbrack;Esportazione&rbrack; Aggiorna i file dei predefiniti di esportazione per utilizzare le nuove impostazioni di formato e dithering
* &lbrack;Content&rbrack; nuovi modelli e shader per il supporto del materiale VRay (VRayMtl)
* &lbrack;Pila livelli&rbrack; Consente l&#39;eliminazione degli effetti di livello utilizzando l&#39;icona del cestino o la scelta rapida da tastiera della tastiera Elimina
* Rimuovere la Substance Source del plug-in (utilizzare il modulo di avvio con la funzionalità &quot;Invia a&quot;)
* &lbrack;Windows&rbrack; Non visualizzare l&#39;avviso TDR sulle GPU di fascia alta

**Corretto:**

* Problemi di traduzione nella finestra di dialogo Nuovo file di progetto
* &lbrack;Baker&rbrack; L’impostazione &quot;Salva file di scena preelaborato&quot; non funziona più
* &lbrack;Proiezione Planari&rbrack; Proiezione non funziona su trame con UV ripetuti
* &lbrack;Decal&rbrack; differenza di comportamento nel canale normale quando si utilizzano diverse modalità di proiezione del livello di riempimento
* &lbrack;Sfumino&rbrack;&lbrack;Clona /Clone&rbrack; Può apparire un artefatto quando si disegna in una maschera
* &lbrack;Engine&rbrack; Arresto anomalo con contenuto livello specifico
* &lbrack;Engine&rbrack; arresto anomalo casuale quando si disegna in alcuni casi
* &lbrack;Punto di ancoraggio&rbrack; il riferimento a una maschera vuota restituisce sempre il bianco
* &lbrack;Export&rbrack; Livello non preso in considerazione in alcune particolari configurazioni dello stack
* &lbrack;Esporta mesh&rbrack; Impossibile esportare con un percorso contenente caratteri speciali
* &lbrack;Esporta mesh&rbrack; Impossibile leggere i file glTF quando esportati da Linux o MacOS
* &lbrack;Importa mesh&rbrack; La reimportazione di DAE, PLY o glTF non funziona come previsto

**Problemi noti:**

* &lbrack;Scripting&rbrack;&lbrack;JavaScript&rbrack; Impossibile modificare le nuove impostazioni del baker di curvatura
* &lbrack;Baker&rbrack; Arresto anomalo su Linux con Raytracing GPU
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; Non deve esportare i set di texture disabilitati
* &lbrack;Arresto anomalo&rbrack; Cambia shader dopo aver dipinto una maschera in livelli di materiale

## Versione 5

### 5.3.3 (2019.3.3)

*(Rilasciato: 06 febbraio 2020*)Riepilogo: **Bugfix con aggiornamento a Iray 2019.3**

**Aggiunto:**

* Aggiornamento a Iray 2019.3
* &lbrack;Log&rbrack; indica un BIOS obsoleto per la CPU Ryzen che causa arresto anomalo durante la esegue i baking
* &lbrack;ABR&rbrack; Estrai alfa ABR da riporre

**Corretto:**

* &lbrack;Baker&rbrack; la Esegue i baking non riesce se la trama High-poly non include UV
* &lbrack;Linux&rbrack; Le scelte rapide personalizzate del mouse non vengono salvate
* &blocca;Pennello&sfoglia; Il contorno scompare con alcune forme alfa
* &lbrack;Tablet&rbrack; rilevamento errato durante lo spostamento dei cursori
* &lbrack;Shortcuts&rbrack; Impossibile impostare una scelta rapida da tastiera con &quot;Ctrl+Alt+MouseClick&quot;
* &lbrack;Shelf&rbrack; Impossibile visualizzare la descrizione comandi della risorsa quando si utilizza una tavoletta a penna
* &lbrack;vista 2D&rbrack;&lbrack;Export&rbrack; il predefinito non tiene conto delle informazioni normali
* Si verifica un blocco con quando si disegna in allineamento UV con determinati pennelli
* Colorare sotto un filtro crea un artefatto sul tratto in corso
* &lbrack;Viewport&rbrack; cache di texture errata nella finestra della vista dopo la reimportazione di una trama
* &lbrack;Arresto anomalo&rbrack; errore durante il salvataggio dopo l&#39;esportazione in Photoshop
* &lbrack;Arresto anomalo&rbrack; scrittura di simboli speciali nel prefisso durante l&#39;importazione delle risorse
* &lbrack;Arresto anomalo&rbrack; Fare clic sul riferimento in Proprietà punto di ancoraggio
* &lbrack;Punti di ancoraggio&rbrack; Il canale non si aggiorna quando è presente un filtro tra punto di ancoraggio e riferimento
* Il collegamento dell’URL del raggio nel menu Aiuto non funziona

**Problemi noti:**

* &lbrack;UV Unwrapping&rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &lbrack;UV Unwrapping&rbrack; Vertici con le stesse coordinate vengono uniti
* &lbrack;UV Unwrapping&rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme tra set di texture
* &lbrack;UV Unwrapping&rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &lbrack;UV Unwrapping&rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped

### 5.3.2 (2019.3.2)

*(Rilasciato: 21 Gennaio 2020*)Riepilogo: **Bugfix**

**Corretto:**

* L’apertura di un progetto che è stato salvato in modalità solo canale non visualizza la trama
* Il riquadro di visualizzazione non viene sempre aggiornato quando si disegna sotto il livello utilizzando lo strumento Clona

**Problemi noti:**

* &lbrack;Baker&rbrack; Arresto anomalo relativo al multithreading su CPU Ryzen
* &lbrack;UV Unwrapping&rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &lbrack;UV Unwrapping&rbrack; Vertici con le stesse coordinate vengono uniti
* &lbrack;UV Unwrapping&rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme tra set di texture
* &lbrack;UV Unwrapping&rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &lbrack;UV Unwrapping&rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped

### 5.3.1 (2019.3.1)

*(Rilasciato: 20 Dicembre 2019*)Riepilogo: **Hotfix**

**Corretto:**

* Arresto anomalo quando si lavora su trame con Proiezioni UV specifiche
* &lbrack;ABR&rbrack; Arresto anomalo quando si passa da un predefinito Photoshop a un altro
* &lbrack;Linux&rbrack; Impossibile avviare la Substance Painter su CentOS 7.4 a causa di un problema di dipendenza libGLX
* &lbrack;Baker&rbrack; Arresto anomalo durante la esegue i baking dopo aver utilizzato File > Pulisci
* &lbrack;Baker&rbrack; Esegue i baking la finestra di dialogo di avanzamento si blocca dopo l&#39;annullamento
* &lbrack;Baker&rbrack; Eseguire i baking la trama dopo l&#39;esportazione della texture non funziona
* &lbrack;Baker&rbrack; Utilizzo di risultati &quot;Corrispondenza per nome&quot; con Mappe trama nere
* &lbrack;Baker&rbrack; Cage non viene considerato
* &lbrack;Shelf&rbrack; l&#39;importazione di file PSD genera immagini interrotte
* &lbrack;Sample&rbrack; Il progetto di esempio &quot;Mat&quot; ha videocamere danneggiate e un predefinito di esportazione errato

**Problemi noti:**

* &lbrack;Baker&rbrack; Arresto anomalo relativo al multithreading su CPU Ryzen
* &lbrack;UV Unwrapping&rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &lbrack;UV Unwrapping&rbrack; Vertici con le stesse coordinate vengono uniti
* &lbrack;UV Unwrapping&rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme tra set di texture
* &lbrack;UV Unwrapping&rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &lbrack;UV Unwrapping&rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped

### 5.3.0 (2019.3.0)

*(Rilasciato: 17 dicembre 2019*)Riepilogo: **Versione principale con miglioramento dell’esperienza utente di pittura a mano, utilizzo dei tablet, srotolamento automatico degli UV nella versione beta (0.3.0) e diversi nuovi contenuti per la pittura a mano**

**Aggiunto:**

* Integrazione dello srotolamento UV automatico della versione 0.3.0 in Substance Painter
* &lbrack;UV unwrapping&rbrack; srotolamento UV automatico nella Substance Painter quando non sono presenti UV o UV parziali
* &lbrack;UV unwrapping&rbrack; un&#39;impostazione globale per attivarla e disattivarla
* &lbrack;UV unwrapping&rbrack; Versione riportata nel file di registro
* &lbrack;UV unwrapping&rbrack;&lbrack;UI&rbrack; Indica l&#39;avanzamento dello srotolamento UV
* &lbrack;UI&rbrack; Nuove impostazioni nella barra degli strumenti contestuale per selezionare l&#39;anteprima del pennello: Anteprima completa, Contorno pennello e mirino
* &lbrack;Strumento&rbrack; Nuovo metodo di fusione avanzato nella sezione alfa: Schiarisci (massimo) oltre a Normale
* &lbrack;Pila livelli&rbrack; opzione di correzione gamma per livello per alfa o maschera (menu di scelta rapida)
* &lbrack;Pila livelli&rbrack;&lbrack;UI&rbrack; Aggiungi l’icona &quot;i&quot; quando un livello alfa è corretto da gamma
* &lbrack;Tablet&rbrack;&lbrack;Tool&rbrack; Esposizione della pressione minima per dimensioni e flusso
* &lbrack;Tablet&rbrack;&lbrack;UI&rbrack; Nuova impostazione nella barra degli strumenti contestuale per selezionare la pressione della curva: lineare, facile da inserire e facile da eliminare
* &lbrack;Tablet&rbrack;&lbrack;UX&rbrack; Aggiungi Ctrl+Alt+clic per scorrere
* Importare pennelli predefiniti di Photoshop (formato ABR)
* &lbrack;ABR&rbrack; Supporta i parametri Shape
* &lbrack;ABR&rbrack; supporta i parametri della dinamica delle forme
* &lbrack;ABR&rbrack; supporta parametri di trasferimento
* &lbrack;ABR&rbrack; supporta i parametri di dispersione
* &lbrack;ABR&rbrack;&lbrack;Tratti dinamici&rbrack; Supporto di rotondità e capovolgimento
* &lbrack;ABR&rbrack;&lbrack;Shelf&rbrack; Esporre la struttura di cartelle dei pennelli nell&#39;Editor filtri
* &lbrack;ABR&rbrack;&lbrack;Shelf&rbrack; Aggiungi icona Photoshop nelle miniature
* &lbrack;ABR&rbrack;&lbrack;Shelf&rbrack; Aggiungi elenco di parametri non supportati nella miniatura dettagliata ABR
* &lbrack;Tool&rbrack;&lbrack;Tratti dinamici&rbrack; Nuova impostazione del tratto dinamico per controllare il numero di valori di inizializzazione casuali da generare
* &lbrack;Tool&rbrack;&lbrack;UI&rbrack; Aggiungi nuove impostazioni di distribuzione e asse per la variazione di dispersione
* &lbrack;Scelta rapida da tastiera&rbrack; Aggiungi Ctrl+Maiusc+B per aprire la finestra di Esegue i baking
* &lbrack;UI&rbrack;&lbrack;Menu&rbrack; Aggiungi voce nel menu &quot;Modifica&quot; per aprire la finestra di Esegue i baking
* &lbrack;UI&rbrack;&lbrack;Settings&rbrack; Miglioramento dell&#39;allineamento dell&#39;elenco delle scelte rapide
* &blocco;UI&rbrack; Sostituisce le icone dei controlli di pressione (dimensioni e flusso) con pulsanti di attivazione/disattivazione
* &lbrack;Riquadro di visualizzazione&rbrack; Consenti di mettere a fuoco separatamente i riquadri di visualizzazione 2D e 3D
* Aggiornamento a QT 5.12.5
* &lbrack;UI&rbrack; Indica l&#39;avanzamento del caricamento della trama
* &lbrack;Substance&rbrack; Aggiungi il supporto per l&#39;intervallo non bloccato e morbido con i cursori
* &lbrack;Substance&rbrack; Aumenta la precisione dei parametri della Substance fino a 6 decimali
* &lbrack;Substance&rbrack; tiene conto del passo definito da un parametro
* &lbrack;Substance&rbrack; Ottimizza la generazione di tratti dinamici con il supporto delle condizioni nei dati utente
* &lbrack;Substance&rbrack; Consenti di designare un output del grafico come maschera per tutti i canali tramite userdata
* &lbrack;Content&rbrack; Aggiorna il progetto di esempio &quot;Mat&quot; con topologia descrittiva per lo spostamento, nuova mappa ID e nuove fotocamere
* &lbrack;Content&rbrack; Integra 3 nuovi filtri (MatFx): fumetto, acquerello, Pittura a olio (ispirato al lavoro di Emrecan Cubukcu)
* &lbrack;Content&rbrack; Integra 102 pennelli predefiniti di Photoshop dai pacchetti di Kyle T. Webster
* &lbrack;Content&rbrack; Integra 18 nuovi pennelli predefiniti: Pittura freccia a rullo, Pittura testo avviso rullo, Carboncino fine e altri ancora
* &lbrack;Content&rbrack; Integra 9 nuove alfa: Rullo Pittura di Brush Maker, Photoshop di Brush Maker, Pattern di pennelli e altro ancora
* &lbrack;Content&rbrack; Integra 2 nuovi strumenti predefiniti: Gouache Dense e Gouache Faded
* &lbrack;Content&rbrack; Integra 1 nuovo generatore : Controllo UV (Isole UV evidenziazione e cuciture)
* &lbrack;Content&rbrack; Integra 2 nuovo predefinito di esportazione: Keyshot 9+ e Spark AR Studio
* &lbrack;Content&rbrack; Integra 1 nuovo modello di progetto: Spark AR Studio (Facebook)

**Corretto:**

* &blocco;Tablet&brack; Annullamento dei tratti dello stilo (CTRL+Z) è più lento dell&#39;annullamento dei tratti del mouse
* &lbrack;Tablet&rbrack; pressione iniziale e finale non considerate quando si disegna una linea retta
* &blocco;Tablet&rbrack; Il primo timbro viene disegnato due volte quando si utilizza una linea retta
* &lbrack;Tablet&rbrack; Migliora il supporto per le scelte rapide da tastiera per tablet Huion
* &lbrack;Tablet&rbrack; supporto migliorato per i pulsanti penna Huion
* &lbrack;Tablet&brack; scostamento tra l&#39;anteprima del pennello e il timbro disegnato
* &lbrack;Tablet&brack; Le scelte rapide per modificare i pennelli con penna conducono in rari casi a prestazioni ridotte
* &lbrack;Tablet&rbrack; ritardo durante la pittura su un livello specifico
* In rari casi, quando si cambia finestra, possono verificarsi texture sfocate
* &lbrack;UI&rbrack;&lbrack;Substance&rbrack; Gli input dell&#39;immagine non vengono sempre visualizzati
* L’opzione Pulisci non rimuove dal ripiano i predefiniti importati in un progetto
* &lbrack;Tool&rbrack;&lbrack;Dynamic Stroke&rbrack; Problema di prestazioni durante l&#39;ottimizzazione del conteggio dei cicli del timbro
* In rari casi, problemi di aggiornamento durante l’uso della modalità finestra vista 3D/2D
* Colorare un tratto molto lungo può portare a un blocco
* &lbrack;Strumento&rbrack; problema di prestazioni quando si disegna con tratti dinamici specifici
* &lbrack;UI&rbrack; la barra degli strumenti contestuale visualizza ancora le proprietà del pennello quando si seleziona una cartella
* I valori dell&#39;asse delle simmetrie non vengono ripristinati
* L’importazione di texture EXR con valori a virgola mobile è completamente nera
* Alt + clic su un canale per isolare non funziona per filtro e generatore
* &lbrack;Export&rbrack; arresti anomali di progetto specifici all&#39;esportazione
* &lbrack;Substance&rbrack; Valore predefinito errato nel menu a discesa se il parametro è nascosto da Visibile se
* &lbrack;Shader&rbrack; i canali definiti tramite la creazione di livelli di materiale non sono ordinati allo stesso modo nell&#39;interfaccia utente
* &lbrack;Shelf&rbrack; I metadati dei predefiniti non vengono salvati sul disco

**Problemi noti:**

* &lbrack;UV Unwrapping&rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &lbrack;UV Unwrapping&rbrack; Vertici con le stesse coordinate vengono uniti
* &lbrack;UV Unwrapping&rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &lbrack;UV Unwrapping&rbrack; rapporto testuale non uniforme tra set di texture
* &lbrack;UV Unwrapping&rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &lbrack;UV Unwrapping&rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped
* L’esempio di riunione presenta alcuni problemi con le videocamere importate

### 5.2.3 (2019.2.3)

*(Rilasciato: 23 ottobre 2019*)Riepilogo: **Versione Bugfix**

**Aggiunto:**

* &lbrack;Texture Set List&rbrack; Pulsante Aggiungi per attivare/disattivare rapidamente la modalità di attivazione
* &lbrack;Log&rbrack; Aggiungi il numero di versione di Windows 10 nel file di registro
* Aggiornamento alla versione più recente di Substance Engine
* &lbrack;MacOS&rbrack; ha autenticato il software per soddisfare i nuovi requisiti di distribuzione di MacOS Catalina

**Corretto:**

* &lbrack;Plugin&brack; L&#39;origine del plug-in non funziona
* &lbrack;MacOS&rbrack;&lbrack;Shader&rbrack; Mac OS 10.14.5 e AMD: la creazione di livelli di materiale non funziona come previsto

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.2 (2019.2.2)

*(Rilasciato: 20 settembre 2019*)Riepilogo: **Versione Bugfix**

**Corretto:**

* L&#39;importazione di risorse tramite script può provocare un arresto anomalo
* &lbrack;Plugin&rbrack; Il download di materiale dall&#39;origine può provocare un arresto anomalo

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.1 (2019.2.1)

*(Rilasciato: 17 settembre 2019*)Riepilogo: **Versione Bugfix**

**Corretto:**

* &lbrack;Mac&rbrack;&lbrack;USD&rbrack; Impossibile aprire i file USDZ esportati da MacOS
* &lbrack;Set di texture&rbrack; impossibile isolare un set di texture con il modificatore ALT
* &lbrack;Shelf&rbrack; I predefiniti, i Materiali avanzati e le Maschere avanzate vengono sempre modificati quando si esce dall&#39;applicazione
* &lbrack;Pila livelli&rbrack; Impossibile selezionare l&#39;effetto dopo aver eliminato un altro effetto
* Sfarfallio quando si utilizza un cursore all’interno del pannello delle proprietà dello strumento
* Arresto anomalo durante l’esportazione dei predefiniti nello scaffale
* Arresto anomalo quando si esporta un predefinito con spazio insufficiente
* Arresto anomalo durante la creazione di un predefinito con spazio insufficiente

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.0 (2019.2.0)

*(Rilasciato: 25 luglio 2019*)Riepilogo: **Versione principale con aggiornamenti dei baker in termini di prestazioni e una nuova modalità di previsualizzazione + nuovi contenuti**

**Aggiunto:**

* &lbrack;Baker&rbrack; Supporto aggiunto per Raytracing GPU con DXR e OptiX (Occlusione ambientale, Thickness)
* &lbrack;Baker&rbrack; ottimizzazioni e accelerazioni per il Raytracing CPU
* &lbrack;Baker&rbrack;&lbrack;Modalità Vis&rbrack;&lbrack;UI&rbrack; Nuova modalità visualizzazione eseguita i baking nella finestra della vista
* &lbrack;Baker&rbrack;&lbrack;Preferenze&rbrack;&lbrack;UI&rbrack; Nuova opzione di esegue i baking per abilitare-disabilitare il Raytracing GPU
* &lbrack;Baker&rbrack;&lbrack;UI&rbrack; Rielaborazione della finestra di dialogo della barra di avanzamento
* &lbrack;Baker&rbrack; miglioramento dei messaggi di avviso e di errore
* &lbrack;Baker&rbrack; Consente l&#39;annullamento più reattivo del eseguo i baking
* &lbrack;Baker&rbrack; riapri la finestra di esegue i baking dopo aver fatto clic su annulla
* &lbrack;Proj&rbrack;&lbrack;UX&rbrack; Miglioramento della usabilità del manipolatore di rotazione
* &lbrack;Settings&brack; Opzione per migliorare le prestazioni riducendo la risoluzione della finestra della vista per gli schermi HDPI
* &lbrack;Scripting&rbrack; Cambia la risoluzione del set di texture
* &lbrack;Scripting&rbrack; Ottieni set di texture selezionato
* &lbrack;Scripting&rbrack; Consente all&#39;utente di selezionare un set di texture
* &lbrack;Scripting&rbrack; Funzione per sapere quando è stata modificata la selezione del set di texture
* &lbrack;Shelf&rbrack; aggiunti 40 nuovi materiali avanzati
* &lbrack;Shelf&rbrack; aggiunta di 20 nuove maschere avanzate

**Corretto:**

* &lbrack;Pila livelli&rbrack; Blocco dell&#39;interfaccia utente durante la selezione multipla dei livelli
* &lbrack;Pila livelli&rbrack; il raggruppamento di numerosi livelli blocca l’interfaccia utente per un tempo più lungo del solito
* &lbrack;Pila livelli&rbrack; In alcuni casi è possibile selezionare contemporaneamente un livello e un effetto
* I grafici delle Substance utilizzati negli strumenti di pittura non vengono generati alla risoluzione giusta
* &lbrack;Baker&rbrack; il pulsante &quot;Esegue i baking tutti i set di texture&quot; non è disattivato quando non è selezionato alcun baker
* &lbrack;MacOS&rbrack; Disattiva il messaggio di avviso sulla tassellatura
* Lo strumento Proiezione non ha un’anteprima quando viene utilizzato con una maschera
* Arresti anomali e progetti danneggiati durante il tentativo di salvataggio con spazio su disco insufficiente
* &lbrack;Shelf&rbrack; Arresto anomalo durante l&#39;importazione di una risorsa su disco tramite shelf con spazio insufficiente
* &lbrack;Shelf&rbrack; Arresto anomalo durante il ripristino del predefinito di sessione
* &lbrack;Shelf&rbrack; L&#39;importazione di un predefinito con un nome che termina con uno spazio genera un arresto anomalo
* &lbrack;Shelf&rbrack; L&#39;importazione di una risorsa con un prefisso che termina con uno spazio vuoto genera un arresto anomalo

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.1.3 (2019.1.3)

*(Rilasciato: 01 luglio 2019*)Riepilogo: **Bugfix con 2 nuove funzioni**

**Aggiunto:**

* Consente di specificare il budget VRam con una riga di comando (ad esempio: budget vram 4096)
* &lbrack;QML&rbrack; Esposizione delle proprietà wrapMode ed elide dei pulsanti e delle caselle di controllo QML

**Corretto:**

* &quot;Segui tracciato&quot; non funziona sempre
* La mappatura dei canali non funziona con SBSAR utilizzato negli slot a canale singolo
* &lbrack;Pila livelli&rbrack; prestazioni ridotte durante lo scorrimento con livelli nascosti
* &lbrack;TextureSet&rbrack; Arresto anomalo quando si fa clic tra le maschere
* &lbrack;SVT&rbrack; Spostamento non visualizzato correttamente e in alcuni casi sfarfalla
* &lbrack;Alembic&rbrack; Arresto anomalo con trama che utilizza le normali dei punti invece delle normali dei vertici
* &lbrack;Alembic&rbrack;&lbrack;Log&rbrack; Segnala un errore nel registro se il file Alembic non è supportato durante l&#39;importazione

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic

### 5.1.2 (2019.1.2)

*(Rilasciato: 21 Maggio 2019*)Riepilogo: **Hotfix**

**Corretto:**

* Arresto anomalo quando si selezionano due risorse con un input di immagine

### 5.1.1 (2019.1.1)

*(Rilasciato: 20 Maggio 2019*)Riepilogo: **Hotfix**

**Aggiunto:**

* Aggiornamento alla versione più recente di Substance Engine con l’ultima versione di Substance Designer 2019.1

**Corretto:**

* &lbrack;Substance&rbrack; Visibile Se non viene preso in considerazione per le Immagini di input
* &lbrack;SVT&rbrack;&lbrack;Engine&rbrack; La modifica della risoluzione del set di texture in alcuni casi genera un arresto anomalo
* &lbrack;Engine&rbrack; In alcuni casi vengono visualizzate texture nere casuali
* &lbrack;Pila livelli&rbrack;&lbrack;UI&rbrack; Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente
* &lbrack;Pila livelli&rbrack; l&#39;opacità non ha effetto sull&#39;effetto Pittura con il metodo di fusione Attraversa
* &lbrack;Pila livelli&rbrack; L&#39;input del filtro Height al normale non si aggiorna correttamente con il tratto del pennello gomma
* &lbrack;LayersStack&rbrack; Arresto anomalo quando si annulla l&#39;eliminazione di una maschera avanzata
* Sfarfallio del wireframe con ombre e anti-alias temporale attivati
* &lbrack;Spostamento&rbrack; ritardo su AMD con alcune trame pesanti
* &lbrack;Windows&rbrack; Arresto anomalo durante l&#39;apertura di alcuni progetti tramite Esplora file
* &lbrack;Istogramma&rbrack; Arresto anomalo durante la rimozione di una maschera con punto di ancoraggio in alcuni casi
* Arresto anomalo di generazione dell’anteprima in alcuni rari casi
* &lbrack;Arresto anomalo&rbrack; Impossibile riaprire un progetto con troppi strumenti di clonazione e sfumino
* Nessuna trama visualizzata in modalità materiale dopo il salvataggio in alcuni casi
* &lbrack;Scripting&rbrack; alg.mapexport.documentStructure() restituisce valori errati per le cartelle

**Problemi noti:**

* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione

### 5.1.0 (2019.1.0)

*(Rilasciato: 23 aprile 2019*)Riepilogo: **Tratto dinamico con nuovi contenuti dedicati, Spostamento e tassellatura in tempo reale e raggi X, effetto Maschera di confronto, simmetria radiale, Planari e Proiezione sferica**

**Aggiunto:**

* &lbrack;Strumento&rbrack; tratto dinamico: Substance la variazione accanto a un tratto pennello
* &lbrack;Dynamic stroke&rbrack; esporre il nuovo parametro dell&#39;indice del timbro con le opzioni
* &lbrack;Dynamic stroke&brack; tiene conto del parametro $time
* &lbrack;Dynamic stroke&brack; genera un nuovo parametro $randomseed per tratto e per timbro
* &blocco;Traccia dinamica&rbrack; Avvia un indice di traccia dinamica da un numero casuale
* &lbrack;Dynamic stroke&rbrack;&lbrack;Shelf&rbrack; Aiuta a trovare una risorsa traccia dinamica con l&#39;icona dedicata
* Spostamento e tassellatura nella finestra della vista in tempo reale
* Spostamento e tassellatura in Iray
* &lbrack;Shader impostazioni&rbrack;&lbrack;UI&rbrack; Nuova scheda per il controllo dello spostamento e della tassellatura
* &lbrack;Pila livelli&rbrack; Nuovo effetto Confronta maschera: genera una maschera confrontando due canali
* &lbrack;Pila livelli&rbrack;&lbrack;UI&rbrack; Nuova voce nel menu di scelta rapida &quot;Aggiungi maschera con combinazione di height&quot; per inserire un effetto CompareMask
* &lbrack;Simmetria&rbrack; Nuova modalità simmetria: pittura radiale
* &lbrack;Simmetria impostazioni&rbrack; Espandi entrambe le sezioni &quot;Impostazioni&quot; e &quot;Schermo&quot;
* &lbrack;Simmetria impostazioni&rbrack;&lbrack;UI&rbrack; Anteprima per pittura radiale
* Esporre due nuove modalità di proiezione: planare e sferica
* &lbrack;Proj&rbrack; Nuova modalità di ritaglio forma per tutte le proiezioni
* &lbrack;Proj&rbrack; modalità Planari con il nuovo manipolatore: strumento superficie
* &lbrack;Proj&rbrack;&lbrack;Scelta rapida da tastiera&rbrack; Scelta rapida da tastiera MAIUSC+W per lo strumento superficie
* &lbrack;Proj&rbrack; Planare maschera di proiezione con sfoltimento profondità e taglio dello sfondo
* &lbrack;Manipolatore&rbrack; miglioramento del manipolatore di rotazione su tutti e tre gli assi per il triplanare
* &lbrack;Tool&rbrack;&lbrack;UX&rbrack; Se si fa clic con il tasto Alt su un canale, questo viene attivato o disattivato
* &lbrack;Engine&rbrack; Aggiornamento alla versione più recente di Substance Engine
* &lbrack;Set&amp;rbrack texture; selezione multipla e modifica della risoluzione
* &lbrack;Set di texture&rbrack; Attivazione e disattivazione rapida dei set di texture
* &lbrack;Set di texture&rbrack; Combina solo e tutte le opzioni in un nuovo menu
* &lbrack;Texture set&rbrack;&lbrack;Pila livelli&rbrack; Nuova icona per attivazione e disattivazione
* &lbrack;Pila livelli&rbrack;&lbrack;UX&rbrack; Inserisci effetti sopra a quelli già selezionati
* &lbrack;Pila livelli&rbrack;&lbrack;UI&rbrack; Rielabora stile di selezione visualizzazione Pila livelli
* &lbrack;Pila livelli&rbrack; Il metodo di fusione per i livelli istantanei è ora in modalità Attraversa per impostazione predefinita
* &lbrack;Esporta&rbrack; Opzione per attivare e disattivare il dithering
* &lbrack;Plugin&brack; supporta il modificatore di precisione per i cursori (MAIUSC)
* &lbrack;Plugin&brack;&lbrack;UI&rbrack; Nuova icona per il salvataggio automatico
* &lbrack;Scripting&rbrack; Elenca il contenuto di una cartella
* &blocco;Scripting&rbrack; Consenti eliminazione file
* &lbrack;Scripting&rbrack; Leggi tutte le informazioni sullo stack, incluse le risorse utilizzate
* &lbrack;Content&rbrack;&lbrack;Dynamic stroke&rbrack; Nuovi strumenti e pennelli predefiniti
* &lbrack;Content&rbrack;&lbrack;Dynamic stroke&rbrack; Due nuove sfumature procedurali: Tonalità sfumatura e Generatore sfumatura
* &lbrack;Content&rbrack; 11 nuovi filtri: MatFx Peeling Pitture, MatFx Water Drops e altro ancora
* &lbrack;Content&rbrack; 7 nuovi generatori: Cucitrice automatica, Colore casuale UV, Densità texel UV e altro ancora
* &lbrack;Content&rbrack; 93 nuove alfa: nuovi testi, frecce e varie altre forme
* &lbrack;Content&rbrack; 2 nuove procedure: Tonalità sfumatura, Generatore sfumatura e altre ancora
* &lbrack;Content&rbrack; 21 nuovi strumenti e pennelli predefiniti per Tratti dinamici: ciottoli, impronte, spray e altro
* &lbrack;Content&rbrack; 2 nuovi HDR: terreno di Canopus e foresta autunnale
* &lbrack;Content&rbrack; Aggiorna il contenuto con la selezione del valore di inizializzazione casuale nello scaffale
* &lbrack;Content&rbrack; Nuova icona con parametro di inizializzazione casuale esposto nello scaffale

**Corretto:**

* &lbrack;Pila livelli&rbrack; La Pila livelli continua a trascinare per sempre
* &lbrack;Mac&rbrack; &quot;Mostra nel Finder&quot; può portare al blocco
* &lbrack;Scripting&rbrack; Le impostazioni salvate tramite l&#39;interfaccia utente personalizzata vengono perse se si sposta il file di shader
* &lbrack;Scripting&rbrack; Il numero di versione dell&#39;API non è corretto e non è aggiornato
* &lbrack;Effetto&rbrack; Il contenuto dell&#39;istogramma non viene visualizzato correttamente
* &lbrack;Effetto&rbrack; In alcuni casi l’effetto istogramma non si aggiorna
* &lbrack;Shelf&rbrack; I punti non sono allineati correttamente sul materiale &quot;Plastic Fabric Pyramid&quot;

**Problemi noti:**

* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione
* &lbrack;Pila livelli&rbrack;&lbrack;UI&rbrack; Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente

## Versione 4

### 4.3.3 (2018.3.3)

*(Rilasciato: 7 marzo 2019*)Riepilogo: **bugfix**

**Aggiunto:**

* &lbrack;Content&rbrack; Integra il nuovo modello di progetto: &quot;PBR - Rugosità metallica fusione Alpha&quot;
* L&#39;ordine di ricerca delle librerie dinamiche Linux è stato modificato per assegnare priorità alle librerie nella directory di installazione prima di ciò che è installato sul sistema

**Corretto:**

* La trama a volte scompare dalla finestra della vista 3D (premete F per reimpostare la videocamera)
* Aggiornate Substance Painter caricatore Sketchfab con i nuovi tipi di licenza Sketchfab
* &lbrack;Import&rbrack;&lbrack;glTF&rbrack; Gestione errata della modulazione della texture di input come definita nei file glTF
* &lbrack;Import&rbrack;&lbrack;glTF&rbrack; Il piano terreno viene visualizzato in modo errato in alcuni casi con l&#39;importazione glTF
* &lbrack;Esporta&rbrack;&lbrack;USD&rbrack; L&#39;opacità non funziona in Arkit
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; arresti anomali di esportazione USDz in alcuni casi
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; Esporta in USD senza salvare porta all&#39;arresto anomalo
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; Modalità di Affiancamento errata per texture, modalità di suddivisione per trame e tipi di output per ombreggiatori
* &lbrack;Export&rbrack;&lbrack;USD&rbrack; Esporta solo alcuni set di texture con tutta la geometria
* &lbrack;Instance&rbrack; Arresto anomalo quando si tenta di eliminare un livello di istanza interrotto
* &lbrack;Regression&rbrack;&lbrack;Export&rbrack; Alcune mappe non vengono esportate nella profondità di bit scelta
* &lbrack;Linux&rbrack; Problema con la libreria libtbb.so.2

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.2 (2018.3.2)

*(Rilasciato: 24 gennaio 2019*)Riepilogo: **Hotfix con nuove funzionalità (esportazione USDZ e filtro Texture nella finestra della vista)**

**Aggiunto:**

* &lbrack;Esporta&rbrack; Consenti esportazione in USDZ
* &lbrack;Viewport&rbrack; Consenti di controllare la qualità della texture nelle impostazioni di visualizzazione
* &lbrack;Viewport&rbrack; aggiunta dell&#39;impostazione di polarizzazione mip nelle impostazioni di visualizzazione
* &lbrack;Viewport&rbrack; Filtro anisotropo aggiunto nelle impostazioni di visualizzazione
* &lbrack;plugins&rbrack; Aggiorna i plug-in ufficiali per utilizzare lo stile di Substance Painter 2018
* &lbrack;License&rbrack; Installa la licenza per impostazione predefinita in una cartella utente

**Corretto:**

* Arresto anomalo collegato alla decompressione
* Aggiungi TAA sul materiale da solo
* Disturbo con ombra, shader di prova TAA e alfa con dithering
* Rimuovere il dithering specular per tutti gli shader PBR classici
* Arresto anomalo nelle impostazioni shader in alcuni casi
* L’attivazione della dispersione non è sincronizzata tra i rendering OpenGL e Iray
* Gli strumenti Sfumino e Clona non funzionano più su trame specifiche
* Alcuni set di texture non possono essere visualizzati nel rendering dei raggi
* I set di texture rinominati non vengono salvati dopo la chiusura del progetto
* Wireframe gli artefatti durante il trascinamento dei materiali sulle mappe ID
* &lbrack;Scripting&rbrack; creazione del percorso del file non forzata durante il salvataggio di un progetto
* &lbrack;Scripting&rbrack; La richiamata &quot;onProjectAboutToSave()&quot; non funziona più
* Collegamenti al forum interrotti nella finestra di segnalazione dei bug

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.1 (2018.3.1)

*(Rilasciato: 06 Dicembre 2018*)Riepilogo: **Hotfix**

**Aggiunto:**

* &lbrack;Simmetrie&rbrack;&lbrack;Viewport&rbrack; Il disegno della Simmetria nel Vista 2D è indietro e ora presenta un&#39;anteprima del pennello clone corretta

**Corretto:**

* &lbrack;Esporta&rbrack; Vista 2D esporta in alcuni casi una texture nera
* &lbrack;Iray&rbrack; le informazioni normali diventano errate in Iray dopo aver creato un&#39;istanza di un livello di materiale
* Gli insiemi di texture non quadrate possono portare in alcuni casi all&#39;arresto anomalo
* &lbrack;Annulla&rbrack; in alcuni casi, diversi CTRL+Z possono causare l&#39;arresto anomalo casuale
* &lbrack;QML&rbrack; In alcuni casi, AlgScrollView può creare un avviso nel registro (cicli di associazione)

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.3.0 (2018.3.0)

*(Rilasciato: 20 novembre 2018*)Riepilogo: **Aggiornamenti del viewport, corretta esportazione dei Vista 2D, nuovi helper dell&#39;interfaccia utente, uno strumento di simmetria migliorato, nuovi contenuti e prestazioni notevolmente migliorate**

**Aggiunto:**

* &lbrack;Anti-aliasing&rbrack;&lbrack;Viewport&rbrack; Nuova anti-alias temporale di filtro per la finestra della vista 3D (tramite Impostazioni schermo)
* &lbrack;Export&rbrack; Esporta il contenuto della finestra della vista 2D come texture singola
* &lbrack;Esporta&rbrack;&lbrack;Dithering&rbrack; Esporta dithering all&#39;esportazione
* &lbrack;Pila livelli&rbrack; colori su livelli e cartelle
* &lbrack;Pila livelli&rbrack; Attivazione e disattivazione rapida di più livelli ed effetti
* &lbrack;Pila livelli&rbrack; Navigazione più semplice per metodi di fusione con tasti su e scorrimento del mouse
* &lbrack;Proj&rbrack;&lbrack;UI&rbrack; manipolatore di rotazione aggiuntivo su tutti e tre gli assi per triplanare
* &lbrack;Proj&rbrack;&lbrack;Shorcuts&rbrack; - e + per modificare le dimensioni del manipolatore di Proiezioni UV
* &lbrack;Shader&rbrack; controlla i parametri dei livelli rivestiti con canali nello shader rivestito con PBR
* &lbrack;Substance&rbrack; Esposizione di nuovi input di texture basati su trama per filtri e generatori
* &lbrack;Simmetria&rbrack;&lbrack;Viewport&rbrack;&lbrack;UI&rbrack; controllare lo scostamento della simmetria con i manipolatori
* &lbrack;Simmetrie&rbrack;&lbrack;Contextual toolbar&rbrack;&lbrack;UI&rbrack; Nuovo pannello simmetria con opzioni
* &lbrack;Simmetria&rbrack; Nuova modalità di intersezione linee simmetrie
* &lbrack;Simmetria&rbrack; nuovo cursore clone simmetria
* &lbrack;Simmetria&rbrack;&lbrack;Shortcuts&rbrack; Q to hide and -, + to change size and shift to snap
* &lbrack;Log&rbrack; migliora i messaggi di errore quando non è possibile esportare texture
* &lbrack;Scripting&rbrack; Consenti modifica o aggiornamento delle risorse in Impostazioni di visualizzazione
* &lbrack;Scripting&rbrack; Consente di creare o rimuovere canali nei set di texture
* &lbrack;Content&rbrack;&lbrack;Shaders&rbrack; Aggiunta del supporto per l&#39;anisotropia con uno shader dedicato (pbr-metal-rough-anisotropia-angle)
* &lbrack;Content&rbrack; aggiornamento della sfera di anteprima con anisotropia e angolo modificato
* &lbrack;Content&rbrack; Shutline matFx aggiornato
* &lbrack;Content&rbrack; Nuova texturing.XYZ scansione del volto senza interruzioni
* &lbrack;Content&rbrack; Nuove procedure anisotrope
* &lbrack;Content&rbrack; Nuovo filtro: baked lighting environment
* &lbrack;Content&rbrack; Mappa del nuovo ambiente: studio automotive neutral
* &lbrack;Content&rbrack; Nuovo modello di progetto: PBR - Angolo di anisotropia rugosità metallica (con canali di anisotropia)
* &lbrack;Content&rbrack; Nuovo modello di progetto: PBR - rugosità metallica Coated
* &lbrack;SVT&rbrack;&lbrack;Engine&rbrack; Sparse Virtual Textures (SVT)
* &lbrack;SVT&rbrack;&lbrack;Preferenze&rbrack;&lbrack;UI&rbrack; opzione di accelerazione per il supporto hardware SVT
* &lbrack;SVT&rbrack;&lbrack;Log&rbrack; informazioni aggiuntive per la funzionalità di creazione di texture virtuali sparse (ad esempio, disco di dimensioni)
* &lbrack;SVT&rbrack;&lbrack;UI&rbrack; finestra dei messaggi all&#39;inizio se le dimensioni del disco sono troppo basse per la cache
* &lbrack;SVT&rbrack;&lbrack;Preferenze&rbrack;&lbrack;UI&rbrack; Substance Painter posizione cache globale
* &lbrack;SVT&rbrack; Nuova variabile di ambiente per specificare il percorso della cache della Substance Painter
* &lbrack;SVT&rbrack; Nuova variabile di ambiente per attivare l&#39;accelerazione del supporto hardware SVT
* &lbrack;SVT&rbrack; Rileva supporto sparse per hardware
* &lbrack;SVT&rbrack;&lbrack;Hardware Sparse&rbrack; Aumentare la versione minima del driver per la GPU Nvidia
* &lbrack;SVT&rbrack;&lbrack;Shader&rbrack;&lbrack;Viewport&rbrack;&lbrack;UI&rbrack; Avvisa l&#39;utente se all&#39;apertura del progetto sono presenti artefatti con texture virtuale sparsa

**Corretto:**

* &lbrack;Selettore colore&rbrack; Viene visualizzato il cursore di disegno quando si tenta di scegliere un colore
* Arresto anomalo selezionando o deselezionando i livelli in un ordine specifico può provocare arresto anomalo
* Arresto anomalo quando si incolla come istanza un livello con una maschera
* &lbrack;Canale utente&rbrack;&lbrack;Regressione&rbrack; Arresto anomalo durante la ridenominazione del canale utente
* &lbrack;Canale utente&rbrack; Anteprima pennello in grigio
* &lbrack;Alembic&rbrack; Un solo set di texture da diversi materiali dopo l&#39;importazione
* &lbrack;Engine&rbrack; La texture esportata è diversa dalla finestra della vista per i timbri del pennello
* &lbrack;Engine&rbrack; L&#39;inversione con un effetto livello non influisce completamente su una texture
* Il selettore materiale sta applicando un tratto di pennello durante il prelievo
* Il passaggio a una risoluzione di 128x128px genera un arresto anomalo
* I collegamenti delle mappe trama non vengono aggiornati correttamente quando si ridefiniscono o si creano istanze dei livelli
* &lbrack;Substance&rbrack; UserData ColorSpace non funziona con la trama Eseguita i baking Normale richiesta come input
* Associazione MDL non corrispondente quando si utilizzano più istanze di shader
* &lbrack;Simmetria&rbrack;&lbrack;Riempi livello&rbrack; piano della Simmetria e il relativo manipolatore attivo nel livello di riempimento
* &lbrack;Viewport&rbrack; punto pivot per la traduzione non sempre aggiornato dopo il clic
* &lbrack;UI&rbrack; icone fisse e rimozione dei segnaposto per i monitor HDPI

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.2.3 (2018.2.3)

*(Rilasciato il 25 settembre 2018)*

**Corretto:**

* &lbrack;vista 2D&rbrack; vista 2D interrotto con alcune trame durante la creazione di un nuovo progetto
* &lbrack;Arresto anomalo&rbrack; il passaggio da Proiezione UV a proiezione triplanare genera un arresto anomalo
* &lbrack;RayCollider&rbrack; più arresti anomali dovuti a &quot;RayCollider&quot;
* &lbrack;Strumento&rbrack; se si cambia livello, vengono perse le proprietà del pennello modificate
* Le impostazioni del pennello vengono ripristinate quando si passa alla gomma

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.2 (2018.2.2)

*(Rilasciato l&#39;11 settembre 2018*)Riepilogo: **Hotfix con aggiornamento del contenuto, nuove funzionalità di scripting e possibilità di disabilitare l&#39;aggiornamento automatico**

**Aggiunto:**

* &lbrack;Content&rbrack;&lbrack;Shelf&rbrack; Aggiungi un predefinito Ripiano incarnato
* &lbrack;Content&rbrack;&lbrack;shelf&rbrack; Conversione di 19 normali di incarnato in materiali per la dispersione del sottosuolo
* &lbrack;Scripting&rbrack; Crea un modello di progetto da un progetto aperto
* &lbrack;Scripting&rbrack; Recupera/Imposta le impostazioni di esportazione di un progetto aperto
* &lbrack;Updates&rbrack; Consente di disabilitare la finestra a comparsa di aggiornamento automatico da impostazioni e variabile di ambiente
* &lbrack;Updates&rbrack; Non viene visualizzato fino alla versione successiva nella finestra a comparsa Manutenzione obsoleta

**Corretto:**

* &blocco;Camera&rbrack; zoom errato passando da ortografica a Prospettiva
* &lbrack;Display&rbrack; Alcune mappe vengono visualizzate in modalità lineare anziché sRGB
* &lbrack;Viewports&rbrack; Lo stato attivo della trama non si comporta correttamente
* &lbrack;vista 2D&rbrack; Il progetto con la fotocamera rotta ha sparito UVs Gusci
* &lbrack;SSS&rbrack;&lbrack;Tooltip&rbrack; subsurface scattering suggerimenti visualizzati nel registro
* Alcuni progetti non possono essere aperti in 2018.2 e il messaggio di errore non può salvare un pacchetto substance null
* &lbrack;Mask&rbrack; Il colore dello strumento Pittura può bloccarsi in alcuni casi quando si lavora in una maschera
* &lbrack;Material&rbrack; Mappe non visualizzate in situazioni specifiche
* &lbrack;Proj&rbrack;&lbrack;Tools&rbrack; Manipolatore attivo con un generatore
* &lbrack;Substance&rbrack; Substance di parametri mancanti
* &lbrack;Scripting&rbrack; nome software errato nella documentazione
* &lbrack;UDIM&rbrack; nessuna informazione nel registro sulle shell UV su più porzioni UV

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

*(Rilasciato il 2 agosto 2018*)Riepilogo: **Versione estate, supporto per la dispersione sottosuperficiale, miglioramenti a livello di proiezione e riempimento, importazione e selezione della fotocamera, supporto per Alembic e glTF, trascinamento sulla mappa ID, supporto migliorato per il formato di Substance e nuovi contenuti**

**Aggiunto:**

* &lbrack;SSS&rbrack;&lbrack;Viewport&rbrack;&lbrack;Iray&rbrack; dispersione generica sottosuperficie
* &lbrack;SSS&rbrack; Sincronizza i parametri MDL e di dispersione sottosuperficie
* &lbrack;SSS&rbrack; ha aggiunto un nuovo canale in scala di grigi denominato Dispersione
* &lbrack;SSS&rbrack;&lbrack;Impostazioni Shader&rbrack; parametro del tipo di dispersione per la dispersione del sottosuolo (incarnato o traslucido)
* &lbrack;SSS&rbrack;&lbrack;Impostazioni Shader&rbrack; parametro della scala di dispersione per la dispersione del sottosuolo
* &lbrack;SSS&rbrack;&lbrack;Impostazioni Shader&rbrack; Parametro colore di dispersione per la dispersione del sottosuolo
* &lbrack;SSS&rbrack;&lbrack;Impostazioni di visualizzazione&rbrack; Conteggio campioni diffusione per dispersione sottosuperficie
* &lbrack;Shader&rbrack;&lbrack;Iray&rbrack; Integra MDL di dispersione sottosuperficiale per Iray
* &lbrack;Shader&rbrack; aggiornamento di Shader tramite il programma di aggiornamento delle risorse
* &lbrack;Shader&rbrack; Aggiorna API e documentazione del log delle modifiche
* &lbrack;Tool Properties&rbrack;&lbrack;Proj&rbrack; Nuovi parametri per la proiezione triplanare
* &lbrack;Viewport&rbrack;&lbrack;Proj&rbrack; Controlla le proprietà dei livelli di riempimento nella vista 3D direttamente con i manipolatori (proiezione triplanare)
* &lbrack;Shortcuts&rbrack;&lbrack;Proj&rbrack; Nuove scelte rapide Q, W, E, R, T per manipolatori di proiezione triplanari
* &lbrack;Viewport&rbrack;&lbrack;Proj&rbrack; Controlla le proprietà dei livelli di riempimento direttamente nei Vista 2D (Proiezione UV)
* &lbrack;Shortcuts&rbrack;&lbrack;Proj&rbrack; Nuova scelta rapida da tastiera Q per manipolatori Proiezione UV
* &lbrack;Contextual Toolbar&rbrack;&lbrack;Proj&rbrack; Controlla manipolatori di proiezione triplanari
* &lbrack;Contextual Toolbar&rbrack;&lbrack;Proj&rbrack; manipolatori di Proiezioni UV di controllo
* &lbrack;Proprietà strumento&rbrack; Disattiva Affiancamento texture con lo strumento Proiezione e Stencil
* &lbrack;Stencil&rbrack; Usa immagini non quadrate con lo strumento di proiezione/stencil
* &lbrack;Stencil&rbrack; Consenti il controllo della modalità Affiancamento nella finestra Proprietà
* &lbrack;Stencil&rbrack; Lo zoom non è centrato su uno stencil non Affiancamento
* &lbrack;Fotocamere&rbrack; Importa fotocamere da Maya, Max, Blender, Modo, DAE
* &lbrack;Cameras&rbrack;&lbrack;Viewport&rbrack; Selezionare e controllare le fotocamere importate nella finestra della vista
* &lbrack;Camera&rbrack;&lbrack;Iray&brack; Selezionare e controllare le fotocamere importate in Iray
* &lbrack;Cameras&rbrack;&lbrack;UI&rbrack;&lbrack;New project&rbrack;&lbrack;Project configuration&rbrack; Import cameras is checked per impostazione predefinita
* &lbrack;Cameras&rbrack;&lbrack;Shortcuts&rbrack; Aggiungi scelte rapide per passare da una fotocamera all’altra
* &lbrack;Cameras&rbrack;&lbrack;Viewport&rbrack; Aggiungi fotogramma nella finestra della vista
* &lbrack;Cameras&rbrack;&lbrack;Viewport Settings&rbrack; Controllo dell&#39;opacità del fotogramma
* &lbrack;Camera&rbrack;&lbrack;Impostazioni fotocamera&rbrack; lunghezza focale massima a 500 mm
* &lbrack;Fotocamere&rbrack;&lbrack;Impostazioni fotocamera&rbrack; Rapporto di esposizione
* &lbrack;Camera&rbrack;&lbrack;Impostazioni fotocamera&rbrack; Aggiungi opzione di blocco
* &lbrack;Camera&rbrack;&lbrack;Impostazioni fotocamera&rbrack; Aggiungi un&#39;opzione di ripristino
* &lbrack;Cameras&rbrack;&lbrack;Impostazioni fotocamera&rbrack; Aggiungi attributo distanza focale
* &lbrack;glTF&rbrack; importazione di un file glTF
* &lbrack;glTF&rbrack; Importa mapping occlusione ambientale
* &lbrack;Alembic&rbrack; Importa fotogramma Alembic 1 con geometria statica
* &lbrack;Shelf&rbrack; Trascina i materiali direttamente sulla trama utilizzando mappe ID con un modificatore (CTRL/Comando)
* &lbrack;Pila livelli&rbrack; creazione automatica della maschera ID con trascinamento dei materiali sulla trama con mappe ID
* &lbrack;Pila livelli&rbrack; scorrimento automatico dei livelli con trascinamento sulla Pila livelli
* &lbrack;UI&rbrack;&lbrack;Tool Properties&rbrack; Exposé preset di Substance
* &lbrack;UI&rbrack;&lbrack;Menu della Guida&rbrack; miglioramento del menu della Guida
* &lbrack;UI&rbrack;&lbrack;New Project&rbrack;&lbrack;Project Configuration&rbrack; Riorganizzazione della finestra
* &lbrack;UI&rbrack;&lbrack;New Project&rbrack;&lbrack;Project Configuration&rbrack; Sostituisci termine trama con file
* &lbrack;UI&rbrack;&lbrack;Substance&rbrack; Visualizza gli attributi della Substance nell&#39;interfaccia utente
* &lbrack;Shortcuts&rbrack; F4 passa dalla vista 2D a quella 3D e viceversa
* &lbrack;Scelte rapide&rbrack; Nuove scelte rapide per Attiva/Disattiva stencil N e maschera veloce U
* &lbrack;Substance integration&rbrack; tiene conto delle istruzioni &#39;visible if&#39; nei parametri della Substance
* &lbrack;Viewport&rbrack; Ombre non obbligate a essere calcolate dopo lo spostamento della videocamera
* &lbrack;Content&rbrack; Aggiorna MeetMat con le fotocamere importate
* &lbrack;Content&rbrack; Aggiungi un campione con la dispersione sottosuperficie abilitata - JadeToad
* &lbrack;Content&rbrack; Aggiungi un nuovo modello di progetto PBR con la dispersione sottosuperficie attivata
* &lbrack;Content&rbrack; predefiniti di esportazione aggiornati per aggiungere un nuovo canale di diffusione
* &lbrack;Content&rbrack;&lbrack;Shelf&rbrack; Supporto per la dispersione sottosuperficiale aggiunto per: pbr-metal-rough, pbr-metal-rough-alpha-test, pbr-coated, pbr-spec-gloss
* &lbrack;Content&rbrack;&lbrack;Shelf&rbrack; Canale di dispersione aggiunto a 5 materiali avanzati (pallini e pelli)
* &lbrack;Content&rbrack;&lbrack;Shelf&rbrack; 1 nuovo materiale giada
* &lbrack;Content&rbrack;&lbrack;Shelf&rbrack; 1 nuovo materiale cerato

**Corretto:**

* &lbrack;CMD&rbrack; risultati diversi utilizzando la stessa riga di comando con versioni diverse
* &lbrack;TDR&rbrack; Se TdrLevel è impostato, non ci sono errori nel registro
* &lbrack;Baker&rbrack; mappa di Occlusione ambientale capovolta
* &lbrack;ID Map&rbrack; Arresto anomalo durante il prelievo al di fuori dell&#39;intervallo 0-1
* &lbrack;Iray&rbrack; Arresto anomalo quando si cambia set di texture e si torna alla modalità Pittura
* &lbrack;Viewport&rbrack; sincronizza le aree di rilascio tra le finestre per il trascinamento
* &lbrack;Engine&rbrack; artefatto di Moire quando si disegnano livelli di riempimento Affiancamenti o si disegna un piccolo pennello
* &lbrack;License&rbrack; Controllo versione software non valida del servizio licenze
* &lbrack;License&rbrack; rielaborare il modo in cui gestiamo l&#39;autenticazione
* &lbrack;API&rbrack; richiama l&#39;evento API di scripting onNewProjectCreated anche durante la creazione con un modello
* &lbrack;Shader&rbrack; Lo shader compilato non viene caricato dalla cache se non viene compilato il file di shader
* &lbrack;Shelf&rbrack; l&#39;esportazione del file HDR dallo shelf genererà un file con valori bloccati
* &lbrack;Export&rbrack; l&#39;esportazione EXR blocca i valori dei colori RGB tra 0 e 1
* &lbrack;Contenuto&rbrack; Disturbo Procedurale Perlin 3D Frattale è pixelato

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.1.3 (2018.1.3)

*(Rilasciato il 28 giugno 2018)*

**Aggiunto:**

* &lbrack;Preferenze&rbrack; Proponi di salvare il progetto al riavvio di Painter

**Corretto:**

* &lbrack;Plugin&rbrack; Substance Source di ricerca non funziona
* &lbrack;Materiali avanzati&rbrack; L&#39;importazione di Materiali avanzati in alcuni casi genera un arresto anomalo
* &lbrack;Materiali avanzati&rbrack; l&#39;eliminazione di Materiali avanzati in alcuni casi genera un arresto anomalo
* &lbrack;Save&rbrack; Il salvataggio genera un arresto anomalo in alcuni rari casi
* &lbrack;Shelf&rbrack; Inverti non funziona su Celle 2 e Celle 3
* &lbrack;Shelf&rbrack; Typo in alcuni Alpha
* &lbrack;Shelf&rbrack; Alcuni materiali Substance non vengono renderizzati correttamente

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.2 (2018.1.2)

*(Rilasciato: 12 giugno 2018*)Riepilogo: **Velocità di Esegue i baking migliorata, Sistema di salvataggio migliorato, Cursori aggiornati, API di plug-in aggiornata, Traduzione cinese, Riempimento migliorato ora facoltativo**

**Aggiunto:**

* &lbrack;Baker&rbrack; miglioramento delle prestazioni con la nuova versione del baker
* Forzare la finestra di dialogo di visualizzazione con la GPU incompatibile
* &lbrack;Salva&rbrack; Esposizione nuova funzionalità di progetto compatto (modalità di salvataggio completa/compatta)
* &lbrack;Salva&rbrack; Informa l&#39;utente in caso di errore di salvataggio
* &lbrack;Clean&brack; salvataggio successivo in modalità completa/compatta
* &lbrack;Cursori&rbrack; miglioramento della precisione delle barre e dei cursori di colore/scala di grigi
* &blocco;Cursori&sblocco; aggiunta dei controlli freccia Su/Giù
* &lbrack;Cursori&rbrack; stessa zona di rilevamento per i cursori a barre a colori e in scala di grigi
* &lbrack;Plugin&brack; Salvataggio automatico sempre in modalità incrementale
* &lbrack;Plugin&brack; Opzione per passare dai plug-in al nuovo stile di interfaccia
* &lbrack;Lingua&rbrack; Aggiungi traduzione cinese
* &lbrack;Padding&rbrack; Opzione per passare dalla spaziatura UV a quella 3D adiacente per set di texture in Impostazioni set di texture
* &lbrack;Script&rbrack; modalità di salvataggio esposizione: completa/compatta o incrementale
* &lbrack;Script&rbrack; Aggiornamento della documentazione di script/QML
* &lbrack;Log&rbrack; indica la modalità di salvataggio nel log (completa/compatta o incrementale)

**Corretto:**

* &lbrack;Strumento&rbrack; Lo slot del canale Trasforma in uno slot di materiale su riempimenti a canale singolo
* Arresto anomalo durante il caricamento di una trama (FBX) con alcune facce non assegnate da un materiale
* Arresto anomalo in Iray con NVIDIA GRID 5.2 sulla macchina virtuale
* Arresto anomalo quando si annulla un&#39;eliminazione di un predefinito di materiale
* Arresto anomalo durante il caricamento di alcuni progetti
* &lbrack;Riga di comando&rbrack; Nuova riga di comando per le trame UDIM suddivise per dim
* &lbrack;Toolbar&rbrack; Riduzione della barra degli strumenti
* &lbrack;Instancing&rbrack; Impossibile creare un&#39;istanza di bitmap su più set di texture
* &lbrack;Viewport&rbrack; L&#39;aggiornamento non è completo quando si disegna su trama con UV affiancati
* &lbrack;Iray&rbrack; La Mappa normale viene applicata due volte per i dielettrici
* &lbrack;Shelf&rbrack; Composizione tipografica in alcuni parametri di Substance (alfa, procedure e matfx)
* &lbrack;Shelf&rbrack; Errore di battitura per la bitmap &quot;Solo personale autorizzato&quot;
* &lbrack;Script&rbrack; Function alg.shaders.materials() non funziona più

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.1 (2018.1.1)

*(Rilasciato il 3 aprile 2018)*

**Corretto:**

* &lbrack;Tablet&rbrack; Problema durante la modifica delle scelte di interazione predefinite
* &lbrack;Baker&rbrack; Arresto anomalo con libreria Assimp
* &lbrack;Baker&rbrack; regressione sulle prestazioni con mappa OA
* &lbrack;Iray&rbrack; La Distorsione obiettivo non viene applicata al Canale alfa
* &lbrack;Driver&rbrack; aggiornamento dei requisiti minimi dei driver
* &lbrack;3Dview&rbrack; Normali non generate correttamente sulle trame UDIM senza informazioni sulle normali
* &lbrack;Intel&rbrack; Arresto anomalo con Substance Painter 2018.1.0
* &lbrack;Intel&rbrack;&lbrack;Viewport&rbrack; Problema con la spaziatura interna (artefatti neri)

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.0 (2018.1.0)

*(Rilasciato il 15 marzo 2018)*

**Aggiunto:**

* Nuovo stile generale (icone, colore, comportamento)
* Nuovo layout predefinito
* &lbrack;Tablet&rbrack; miglioramento dell&#39;esperienza utente durante l&#39;uso
* &lbrack;Menu principale&rbrack; ordina prima gli elementi nativi nelle visualizzazioni e nelle barre degli strumenti
* &lbrack;Menu principale&rbrack; Sposta le azioni maschera veloce nella sezione viewport
* &lbrack;Menu principale&rbrack; sposta le azioni del clic con il pulsante destro del mouse nella sezione della finestra della vista
* &lbrack;Menu principale&rbrack; Rinomina il menu &quot;Visualizza&quot; in &quot;Finestra&quot;
* &lbrack;Menu rapido&rbrack; Nuove proprietà dello strumento con clic destro nella finestra della vista
* &blocco;Ancoraggio widget&rbrack; Nuova barra degli strumenti Ancoraggio per ridurre/richiamare rapidamente
* &lbrack;Impostazioni di visualizzazione&rbrack; finestra Impostazioni fotocamera e visualizzatore unite
* &lbrack;Pila livelli&rbrack; menu di scelta rapida contestuale
* &lbrack;Pila livelli&rbrack; Trascina e rilascia per spostare qualsiasi effetto all’interno dello stesso livello
* &lbrack;Toolbar&rbrack; riorganizzazione della barra degli strumenti e nuova barra degli strumenti contestuale
* &blocca;Strumenti barra degli strumenti&rbrack; dividi lo strumento clone in due strumenti separati
* &lbrack;Strumenti proprietà&rbrack; valore più chiaro della scala di grigi dello sfondo nell&#39;anteprima
* &lbrack;Strumenti proprietà&rbrack; Organizzazione nelle schede (riempimento e strumenti)
* &lbrack;Strumento&rbrack; il risultato del disegno corrisponde allo stencil
* &lbrack;Riquadro di visualizzazione&rbrack; nuovo cursore per il livello di riempimento
* &lbrack;Riquadro di visualizzazione&rbrack; navigazione e pittura più fluidi (frequenza fotogrammi più elevata)
* &lbrack;Viewport&rbrack; casella combinata di selezione Materiale/Canale/Mappa nella finestra della vista
* &lbrack;Riquadro di visualizzazione&rbrack; Riduci sfarfallio durante la rotazione (con ombreggiatura)
* &lbrack;Shelf&rbrack; Visualizza i materiali per impostazione predefinita all&#39;apertura di Painter
* &lbrack;Shelf&rbrack; miglioramento del tempo di caricamento di texture e materiali per Substance (da 2 a 6 volte più veloce)
* &lbrack;Shelf&rbrack; Riorganizza le cartelle dei materiali per adattarle alla struttura della Substance Source
* &lbrack;Shelf&rbrack; Trascina i materiali direttamente sulla trama nella finestra della vista
* &lbrack;Shelf&rbrack; Nuovi rumori 3D (Perlin, Perlin Fractal, Simplex e Worley)
* &lbrack;Shelf&rbrack; Nuovo generatore di maschere con posizione trama
* &lbrack;Shelf&rbrack; Disturbi di base aggiornati per supportare il non square expansion
* &lbrack;Shelf&rbrack; Aggiunto nuovo modello ed esporta predefinito per Lens Studio (applicazione Snap)
* &lbrack;Shelf&rbrack; Materiali avanzati e Maschere avanzate aggiornati per utilizzare la versione più recente dell&#39;Editor maschera (micro dettagli)
* &lbrack;Shelf&rbrack; Nuovo progetto di esempio &quot;TilingMaterial&quot; per creare materiali in Affiancamento senza interruzioni
* &lbrack;Shelf&rbrack; Nuovi pennelli predefiniti (Calligrafia, Bagnato, Tratteggio e così via)
* &blocco;Cursori&sbarra; nuovi cursori e stile e comportamento delle barre di colore/scala di grigio
* &lbrack;Baker&rbrack; Consenti l&#39;uso del rettangolo di selezione completo della scena per calcolare la mappa di posizione
* &lbrack;Shader&rbrack; rimuove il parametro di forza height dai parametri di shader predefiniti
* &lbrack;Engine&rbrack; motore di Substance aggiornato
* &lbrack;Engine&rbrack; Nessuna o meno discontinuità tra i blocchi UV
* &lbrack;Plugin&rbrack; Importa più rapidamente i materiali scaricati da Substance Source
* &lbrack;Plugin&brack; Aggiorna tutti i plug-in in base al nuovo stile generale
* &lbrack;Preferenze&rbrack; l&#39;anteprima del colore di sfondo cambia automaticamente
* &lbrack;Clean&rbrack; Riduzione del rischio di danneggiamento del progetto
* &lbrack;Open&rbrack; apertura miglioramento tempo progetto
* &lbrack;Nuovo progetto&rbrack; Nuovo progetto - Miglioramento del tempo di aggiornamento mesh
* &lbrack;Salva&rbrack; Salvataggio miglioramento tempo progetto
* &lbrack;Log&rbrack; tipo di licenza segnalato nel log
* &lbrack;TextureSet&rbrack; Rinomina il pulsante &quot;Esegue i baking Texture&quot; in &quot;Esegue i baking mappe trama&quot;
* Rinominare &quot;Mappe aggiuntive&quot; come &quot;Mesh maps&quot;

**Corretto:**

* &lbrack;Viewport&rbrack; Prestazioni errate con trame contenenti numerosi sottooggetti
* &lbrack;Strumenti proprietà&rbrack; Canale disattivato quando si trascina un&#39;immagine nello slot del materiale
* &lbrack;Strumenti proprietà&rbrack; L&#39;anteprima del pennello non funziona con gli strumenti sfumino e clone
* &lbrack;Texture set&rbrack; L&#39;ordine dei canali non è corretto quando si utilizzano i modelli
* &lbrack;Shelf&rbrack; icona mancante per il generatore di Conversioni in scala di grigi
* &lbrack;Shelf&rbrack; il numero alfa del cerchio di firma è interrotto (font mancante)
* Rilevamento errato delle GPU integrate all’avvio
* &lbrack;Arresto anomalo&rbrack; Trascina una risorsa importata denominata con un carattere #
* &lbrack;Engine&rbrack; Problema di rilevamento Vram nella GPU integrata
* &lbrack;Engine&rbrack; Sono stati corretti numerosi arresti anomali in Substance Engine Linker
* &lbrack;Engine&rbrack; artefatti quadrati durante la modifica della risoluzione
* &lbrack;Effetti post&rbrack; il ridimensionamento dell&#39;interfaccia è lento quando gli effetti post sono attivi
* &lbrack;Baker&rbrack; L&#39;unità della scena non viene rispettata correttamente per i valori di Distanza raggio
* &lbrack;Baker&rbrack; AO da mesh La distanza di occlusione è bloccata a 1 indipendentemente dal valore di input
* &lbrack;Baker&rbrack; Corrispondenza per nome ignora alcune trame con nomi specifici
* &lbrack;Baker&rbrack; L&#39;impostazione dei colori da mesh Polygroup e Submesh ID restituisce sempre un&#39;immagine nera
* &lbrack;Baker&rbrack; La Esegue i baking dell&#39;ID non riesce con trame FBX binarie da Blender
* &lbrack;Shader&rbrack; Disturbo nel vista 2D con dota-2 e non-pbr-spec-gloss
* &lbrack;Linux&rbrack; durante la esegue i baking viene utilizzato un solo thread CPU
* &lbrack;MacOS&rbrack; Arresto anomalo con il cursore del pennello che si sposta sulla finestra della vista

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Processo di post-distorsione non preso in considerazione durante l&#39;esportazione in IRay (alfa)

## Versione 3

### 3.4.2 (2017.4.2)

*(Rilasciato il 24 gennaio 2018)*

**Aggiunto:**

* &lbrack;Esporta&rbrack; Ottiene lo stato di un&#39;esportazione con avanzamento passaggio
* &lbrack;Esporta&rbrack; Consenti l&#39;annullamento di un&#39;esportazione
* &lbrack;Esporta&rbrack; Esporta texture in Sketchfab senza perdere la qualità delle mappe normali
* &lbrack;Esporta&rbrack; Esporta in formato binario (glb) glTF
* &lbrack;Esporta&rbrack; Consenti ridimensionamento colonne nella scheda di configurazione della finestra di esportazione
* &lbrack;Shader&rbrack; Aggiungi un registro modifiche per l&#39;API shader
* &lbrack;Scripting&rbrack; Aggiungi funzioni di richiamata prima e dopo quando si esportano texture
* &lbrack;Iray&rbrack; Aggiornamento a SDK 2017.1 (supporto di GPU Volta)

**Corretto:**

* Arresto anomalo di chiusura dell&#39;applicazione prima della visualizzazione della finestra principale
* &lbrack;MAC&rbrack; Arresto anomalo durante il caricamento di mappe in scala di grigio con IRAY
* &lbrack;MAC&rbrack; rilevamento VRAM non corretto con il nuovo sistema operativo High Sierra
* &lbrack;Plugin&rbrack; Il download delle risorse da Substance Source non funziona più
* &lbrack;Scripting&rbrack; Rilevamento minimo della versione del plug-in non corretto
* &lbrack;Export&rbrack; Impossibile salvare il predefinito di esportazione dopo l&#39;esportazione della texture
* &lbrack;Istanza&rbrack; problema con i generatori di cui viene creata un&#39;istanza in un TextureSet senza mappature aggiuntive
* &lbrack;Viewport&rbrack; Il dithering non funziona con una risoluzione superiore a 4k
* &lbrack;Viewport&rbrack; la visualizzazione del materiale vista 2D è coperta da rumore
* &lbrack;Shelf&rbrack; Migliora il tempo di caricamento per i predefiniti shelf
* &lbrack;Engine&rbrack; Fusione errata quando si disegna sotto la selezione colore

### 3.4.1 (2017.4.1)

*(Rilasciato il 15 dicembre 2017)*

**Aggiunto:**

* &lbrack;Scripting&rbrack; Esporta trama tramite l’API di scripting
* &lbrack;Import&rbrack; disabilita l&#39;importazione di un formato di file mesh non supportato (consenti solo obj, fbx, dae, ply)
* &lbrack;Log&rbrack; Indica con maggiore precisione il problema TDR nel file di registro

**Corretto:**

* Arresto anomalo se l&#39;applicazione viene chiusa prima del termine della ricerca per indicizzazione delle risorse
* Arresto anomalo durante l’apertura di progetti con lo strumento Sfumino/Clona /Clone
* Arresto anomalo quando si utilizza Ripeti dopo un annullamento della modifica dello Shader in Impostazioni visualizzatore
* &lbrack;Engine&rbrack; La creazione di texture differisce tra Painter 2017.2 e 2017.4
* &lbrack;Viewport&rbrack; selezione su una mappa ID da un&#39;istanza campiona il colore errato
* &lbrack;Export&rbrack; Arresto anomalo durante l&#39;esportazione di una texture normale o di occlusione non valida
* &lbrack;Export&rbrack; I gruppi dei file PSD vengono bloccati quando vengono aperti in Photoshop CS6
* &lbrack;Plugin&brack; il plug-in Photoshop ignora la selezione del canale ed esporta sempre tutto
* &lbrack;Livelli&rbrack; Gli ancoraggi si interrompono quando vengono copiati/incollati tra set di texture
* &lbrack;Layers&rbrack; alcuni riferimenti di ancoraggio non possono essere ripristinati se danneggiati
* &lbrack;Shader&rbrack; il parametro di rugosità secondaria rivestita in pbr è interrotto
* &lbrack;Steam&rbrack; La finestra a comparsa Controllo versione non dovrebbe essere visibile all&#39;avvio

**Problemi noti:**

* &lbrack;AMD&rbrack; Arresti anomali/Si blocca quando si tenta di pittura su una trama. Può essere risolto con un aggiornamento del driver GPU.

### 3.4.0 (2017.4.0)

*(Rilasciato il 23 novembre 2017)*

**Aggiunto:**

* &lbrack;Istanza&rbrack; Consenti di creare un&#39;istanza dei parametri tra i livelli
* &lbrack;Istanza&rbrack; Consente di passare da un livello di origine a un&#39;istanza e viceversa
* &lbrack;Istanza&rbrack; Aggiungi un&#39;azione &quot;crea istanza tra set di texture&quot;
* &lbrack;Instancing&rbrack; Indicare nella Pila livelli le istanze di rientro (cicli)
* &lbrack;Instancing&rbrack; Elimina le istanze quando viene rimossa un&#39;origine
* &lbrack;Istanza&rbrack; Non consentire riferimenti di ancoraggio dall&#39;esterno di una cartella istanza
* &lbrack;UI&rbrack; sposta lo stack di annullamento nella relativa finestra denominata &quot;History&quot;
* &lbrack;Plugin&brack; Integrazione del plug-in DCC Live-Link
* &lbrack;Motore&rbrack; migliora le prestazioni di pittura con pittura sparsa
* &lbrack;Esporta&rbrack; Aggiungi le opzioni di bozza e riesportazione all&#39;esportazione Sketchfab
* &lbrack;Shelf&rbrack; Aggiungi controllo &quot;flip&quot; per le sostanze font
* &lbrack;Shelf&rbrack; Aggiungi 20 nuovi materiali procedurali
* &lbrack;Shelf&rbrack; Aggiungi 40 nuove mappe di grunge (basate su bitmap e procedurali)
* &lbrack;Riquadro di visualizzazione&rbrack; Attiva le collisioni di anteprima pennello su altri set di texture visibili
* Aggiornamento dei requisiti minimi dei driver della GPU AMD

**Corretto:**

* Arresto anomalo quando si elaborano Substance a risoluzioni eccessive
* Arresto anomalo quando si dipinge intensamente con particelle
* &lbrack;Viewport&rbrack; riflesso di specular errato nel Vista 2D con trame specifiche
* &lbrack;UI&rbrack; alcune azioni indesiderate vengono visualizzate nella finestra Cronologia

**Problemi noti:**

* &lbrack;Layers&rbrack; alcuni riferimenti di ancoraggio non possono essere ripristinati se danneggiati
* Arresto anomalo quando si utilizza Ripeti dopo un annullamento della modifica dello Shader in Impostazioni visualizzatore

### 3.3.3 (2017.3.3)

*(Rilasciato il 1° dicembre 2017)*

**Corretto:**

* &lbrack;Steam&rbrack; La finestra a comparsa Controllo versione non dovrebbe essere visibile all&#39;avvio
* &lbrack;Export&rbrack; I gruppi dei file PSD vengono bloccati quando vengono aperti in Photoshop CS6

### 3.3.2 (2017.3.2)

*(Rilasciato il 20 novembre 2017)*

**Aggiunto:**

* &lbrack;UI&rbrack; Finestra di dialogo Migliora nuova versione e aggiungi registro modifiche
* &lbrack;UI&rbrack; Indica se la manutenzione è scaduta nella finestra di dialogo per la nuova versione
* &lbrack;License&rbrack; Aggiorna il sistema di licenze per gestire le date di manutenzione
* &lbrack;Esporta&rbrack; Rinomina l&#39;Adobe Standard Material in Adobe Dimension

**Corretto:**

* &lbrack;Mac&rbrack; Il disegno genera quadrati neri e texture danneggiamenti
* &lbrack;Engine&rbrack; La cache a volte può scomparire nel riquadro di visualizzazione
* &lbrack;Engine&rbrack; Vengono visualizzati artefatti Bloccati quando viene attivato il comando di compressione della memoria
* &lbrack;Esegui i baking&rbrack; strani messaggi di errore quando si eseguono i baking trame specifiche
* &lbrack;Export&rbrack; PSD non sono scritti correttamente e non vengono riconosciuti correttamente da Photoshop
* &blocca;Livelli&rbrack; non dovrebbe essere possibile copiare/incollare i livelli in più progetti
* &lbrack;Substance&rbrack; in alcuni casi lo spazio colore UserData per l&#39;input Normale viene capovolto
* &lbrack;Shelf&rbrack; micro-normale nei generatori genera curvatura invertita
* &lbrack;Shelf&rbrack; il filtro HSL influisce anche sul canale alfa
* &lbrack;Linux&rbrack; l&#39;installazione su Centos non riesce a causa di dipendenze mancanti
* In alcuni casi, il programma di installazione non rimuove tutte le risorse dall&#39;installazione precedente

### 3.3.1 (2017.3.1)

*(Rilasciato il 26 ottobre 2017)*

**Aggiunto:**

* &lbrack;Esporta&rbrack; Consente di esportare la trama da un progetto
* &lbrack;Shelf&rbrack; Rimuovi &quot;Sub-Shelf&quot; dai titoli delle schede
* Salvare le impostazioni di post-elaborazione nei modelli
* Rendere il messaggio TDR più comprensibile
* Finestra Migliora impostazioni per la segnalazione degli errori

**Corretto:**

* Arresto anomalo quando si eliminano più scaffali secondari
* Arresto anomalo quando si passa da un livello a qualcos&#39;altro durante il calcolo di un motore
* &lbrack;Mac&rbrack; Arresto anomalo sulla GPU Intel durante il calcolo del motore
* &lbrack;Mac&rbrack;&lbrack;Viewport&rbrack; Prestazioni errate quando è attivato il dithering
* &lbrack;Mac&rbrack; MacOS 10.13 viene riconosciuto come &quot;Versione sconosciuta&quot; nel file di registro
* &lbrack;Baker&rbrack; Eseguire i baking con una gabbia non funziona più
* &lbrack;Layers&rbrack; Ctrl + C scelta rapida da tastiera (azione copia) non funziona più
* &lbrack;Layers&rbrack; Incollare i livelli non aggiorna l&#39;interfaccia utente con i riferimenti dell&#39;ancoraggio
* &lbrack;Ancoraggio&rbrack; collegamenti per duplicare o copiare/incollare il livello con riferimenti
* &lbrack;Export&rbrack; 8K export can arresto anomalo or deadlock application in alcuni casi
* &lbrack;Export&rbrack; Più problemi nel formato di file glTF generato
* &lbrack;Import&rbrack; La reimportazione di una trama con lo stesso nome file non funziona più
* &lbrack;Plugin&brack; La finestra Salvataggio automatico viene sempre visualizzata sopra ogni elemento
* &lbrack;UI&rbrack; ciclo infinito quando si preme &quot;Esc&quot; nella finestra di dialogo TDR
* &lbrack;UI&rbrack; Reimposta interfaccia utente visualizza una seconda barra del titolo nella finestra scaffale

### 3.3.0 (2017.3.0)

*(Rilasciato il 28 settembre 2017)*

**Aggiunto:**

* &lbrack;Esporta&rbrack; consente di esportare trama e texture per il progetto Felix di Adobe
* &lbrack;Esporta&rbrack; Consenti esportazione in formato file glTF
* &lbrack;Engine&rbrack; Ottimizza le dimensioni della texture nell&#39;VRAM utilizzando la compressione dei blocchi
* &lbrack;Finestra di visualizzazione&rbrack; possibilità di trascinare una trama o un progetto nella finestra della vista
* &lbrack;UI&rbrack; Migliora il messaggio di avviso relativo a TDR.
* &lbrack;UI&rbrack; Il registro deve essere visualizzato solo su richiesta
* &lbrack;UI&rbrack; Consenti di cancellare il contenuto della finestra del registro
* &lbrack;UI&rbrack; Visualizza avvisi ed errori nella barra di stato
* &lbrack;UI&rbrack; Visualizza le schede in alto come nei browser Web
* &lbrack;UI&rbrack; Migliora il contesto e i messaggi &quot;non colorabili&quot;
* &lbrack;UI&rbrack; Aggiungi un&#39;azione &quot;Salva come copia&quot; nel menu del file
* &lbrack;Layer&rbrack; Imposta l&#39;Affiancamento predefinito su 1 per impostazione predefinita
* &lbrack;Shelf&rbrack; filtro sfumatura migliorato per supportare 10 colori dinamici
* &lbrack;Shelf&rbrack; Aggiungi uno spazio nella query predefinita del mini-shelf
* &lbrack;Shelf&rbrack; Aggiungere un&#39;azione &quot;Apri in Esplora risorse&quot; per le risorse locali nello scaffale
* &lbrack;Shelf&rbrack; Aggiungi modello e shader per Adobe Material Standard (Project Felix)
* &lbrack;Shelf&rbrack; Aumenta l&#39;Affiancamento massimo a 128 nei livelli di materiale
* &lbrack;Shelf&rbrack; Curvatura sobel aggiunta per micro-dettagli dei Generatori di maschere
* &lbrack;Plugin&brack; Aggiungi plug-in di salvataggio automatico con intervallo di tempo personalizzabile
* &lbrack;Scripting&rbrack; Aggiungi una funzione &quot;Salva come copia&quot;

**Corretto:**

* &lbrack;UI&rbrack; il layout non funziona al primo avvio
* &lbrack;Export&rbrack; PSD generato durante l&#39;esportazione presenta errori di formato
* &lbrack;Export&rbrack; EXR esporta sempre la mappa dell&#39;altezza a 8 bit
* &lbrack;Export&rbrack; Arresto anomalo durante l&#39;esportazione di mappe aggiuntive danneggiate
* &lbrack;Import&rbrack; In alcuni casi i bordi netti non vengono mantenuti su trame poly basse
* &lbrack;Import&rbrack; messaggi di errore migliorati durante l&#39;importazione di trame con problemi
* &lbrack;Baker&rbrack; Il Eseguo i baking della mappa ID non riesce con l&#39;opzione Corrispondenza per nome attivata
* &lbrack;Viewport&rbrack; lo spazio tangente non è sincronizzato con i baker
* &blocco;Effetto&rbrack; Lo spostamento indietro di un livello non ripristina il riferimento di un ancoraggio
* &lbrack;Effetto&rbrack; Problema di aggiornamento durante la creazione di un collegamento tra due maschere con ancoraggi
* &lbrack;Effetto&rbrack; Le maschere con ancoraggi sopra la maschera non devono essere elencate
* &lbrack;Effetto&rbrack; L&#39;impostazione Estrai Alpha da Ancoraggi non funziona
* &lbrack;Engine&brack; La maschera si inverte dopo il primo tratto del pennello
* &lbrack;Engine&rbrack; Arresto anomalo quando si cambia set di texture in un progetto specifico
* &lbrack;Shelf&rbrack; Arresto anomalo quando si elimina un predefinito che si trova in un progetto
* &lbrack;Shelf&rbrack; Typo nel filtro avanzato Tri-Planari
* &lbrack;Shelf&rbrack; MG Mask Builder AO Noise Scale non funziona correttamente
* &lbrack;Shelf&rbrack; MG Mask Builder ha parametri di curvatura invertiti
* &lbrack;Shelf&rbrack; Le alfa importate generano un&#39;anteprima sfera di materiale invece di un&#39;anteprima piatta

### 3.2.0 (2017.2.0)

*(Rilasciato il 27 luglio 2017)*

**Aggiunto:**

* Punti di ancoraggio - Sistema di riferimento livello e maschera
* &lbrack;Livelli&rbrack; possibilità di rinominare effetti di riempimento e Pittura
* &lbrack;Plugin&rbrack; Plug-in Substance Source aggiornato
* &lbrack;Scripting&rbrack; Consenti di eseguire query sulla risoluzione del set di texture
* &lbrack;Scripting&rbrack; Consenti di ottenere lo stato del motore di pittura
* &lbrack;Prestazioni&rbrack; ottimizzazioni migliorate per il caricamento del progetto e la stampa del pennello

**Corretto:**

* &lbrack;Tool&rbrack; Problemi di prestazioni durante l&#39;ottimizzazione dei parametri del materiale
* &lbrack;Motore&rbrack; Scomparsa dei tratti del pennello durante la modifica della risoluzione (4K>2K)
* &lbrack;vista 3D&rbrack; lo spazio tangente non è sincronizzato con i baker
* &lbrack;Shelf&rbrack; Il percorso dello shelf nei documenti utente non viene creato automaticamente
* &lbrack;Shelf&rbrack; Rendi i predefiniti compatibili con le versioni precedenti dopo un aggiornamento
* &lbrack;Shader&rbrack; Lo shader non PBR non funziona più
* &lbrack;Baker&rbrack; Il Eseguo i baking della mappa ID non riesce con l&#39;opzione Corrispondenza per nome attivata
* &lbrack;Sample&rbrack; Incontra mascherino: i nomi dei set di texture di esempio del progetto non sono corretti
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura

### 3.1.0 (2017.1.0)

*(Rilasciato il 20 giugno 2017)*

**Aggiunto:**

* &lbrack;Plugin&rbrack; Nuovo plug-in Substance Source (consente di scaricare risorse nello scaffale)
* &lbrack;Shelf&rbrack; 4 nuovi font (giapponese + cinese semplificato, macchina da scrivere, segmento)
* &lbrack;Shelf&rbrack; 230 Nuovi Alpha (combinazione di pattern, pennelli e scansioni di impronte digitali)
* &lbrack;Shelf&rbrack; 50 Nuovi Procedurals (Modelli di tessuto di abbigliamento medievale e contemporaneo)
* &lbrack;Shelf&rbrack; 2 Nuove mappe ambientali (Mondarrain e Villa Nova Street)
* &lbrack;Shelf&rbrack; 9 Nuovi filtri (Edge Wear dettagli MatFx, Blocca, HBAO, ecc.)
* &lbrack;Shelf&rbrack; Mappa ambiente Panorama predefinita migliorata
* &lbrack;Shelf&rbrack; Nuovi predefiniti di esportazione Arnold 5
* &lbrack;Scripting&rbrack; Consenti importazione della risorsa nello scaffale

**Problemi noti:**

* &lbrack;Esporta&rbrack; La modifica di un predefinito di esportazione è molto lenta

## Versione 2

### 2.6.2

*(Rilasciato il 20 ottobre 2017)*

**Aggiunto:**

* &lbrack;Set di texture&rbrack; Consente di eliminare i set di texture disabilitati
* &lbrack;Shelf&rbrack; Consenti a più utenti di scrivere nella stessa cartella dello scaffale
* &lbrack;Scripting&rbrack; è possibile ricaricare la cartella dei plug-in
* &lbrack;Scripting&rbrack; Aggiungi una versione API minima richiesta nei metadati del plug-in per garantire la compatibilità
* &lbrack;IRay&rbrack; finestra di dialogo Esporta immagine migliorata

**Corretto:**

* &lbrack;Engine&rbrack; Scomparsa dei tratti problema durante la modifica della risoluzione (4K>2K)
* &lbrack;Baker&rbrack; Il Eseguo i baking della mappa ID non riesce con l&#39;opzione Corrispondenza per nome attivata
* &lbrack;Baker&rbrack; I messaggi di errore non sono sufficientemente espliciti
* &lbrack;vista 3D&rbrack; lo spazio tangente non è sincronizzato con i baker
* &lbrack;Strumento&rbrack; artefatti di colore nero quando si utilizza lo strumento sfumino
* &lbrack;Shader&rbrack; Lo shader non PBR non funziona più
* &lbrack;Shader&rbrack; &quot;pbr-coated&quot; è interrotto
* &lbrack;Shader&rbrack; La rugosità dello shader &quot;pbr-coated&quot; non ha più alcun impatto
* &lbrack;Shader&rbrack; Lo shader lucido della specifica non corrisponde a Iray e SD
* &lbrack;Shelf&rbrack; Arresto anomalo durante il caricamento di due file con lo stesso nome ma estensioni diverse
* &lbrack;Shelf&rbrack; Impossibile modificare il predefinito negli scaffali
* &lbrack;Shelf&rbrack; Impossibile impostare un&#39;anteprima personalizzata per le risorse importate nello shelf
* Le risorse caricate dalla cache perdono il loro utilizzo
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura
* Salvataggio del progetto errato se il nome del file contiene due punti
* Importazione di file con più punti (.) nel nome del file causa problemi

### 2.6.1

*(Rilasciato il 12 maggio 2017)*

**Aggiunto:**

* &lbrack;TextureSet&rbrack; Non consentire la riassegnazione dei materiali mesh a nulla

**Corretto:**

* Arresto anomalo quando si cambia TextureSet dopo la sostituzione della mappa con baking
* Arresto anomalo quando si esegue &quot;Annulla e ripeti&quot; dopo aver modificato il metodo di fusione del livello
* Arresto anomalo o blocco quando si utilizza l&#39;effetto &quot;selezione colore&quot; con mappa ID grande
* &lbrack;Export&rbrack; I set di texture rinominati non sono ordinati alfabeticamente nella finestra di esportazione
* &lbrack;TextureSet&rbrack; Il ripristino del nome predefinito non controlla l&#39;unicità
* &lbrack;TextureSet&rbrack; Il set di texture rinominato diventa disattivato dopo la riapertura del progetto
* &lbrack;Shelf&rbrack; contenuto modelli predefiniti mancante
* &lbrack;Shelf&rbrack; le texture non quadrate vengono visualizzate come quadrate
* &lbrack;Shader&rbrack; una volta disattivato un set di texture, lo shader associato viene eliminato
* &lbrack;Scripting&rbrack; alg.eseguite i baking.setTextureSetBakingParameters() non funziona più
* &lbrack;Scripting&rbrack; Errore di battitura nell&#39;esercitazione websocket
* &lbrack;Scripting&rbrack; Vari problemi in AlgWidgets
* &lbrack;Log&rbrack; In alcuni casi, rilevamento non corretto della memoria virtuale disponibile

### 2.6.0

*(Rilasciato il 27 aprile 2017)*

**Aggiunto:**

* Aggiungi nuovo progetto di esempio &quot;Meet Mat&quot;
* &lbrack;Plugin&brack; Nuovo plug-in &quot;Resources Updater&quot;
* &lbrack;TextureSet&rbrack; consente di rinominare e aggiungere una descrizione ai set di texture
* &lbrack;TextureSet&rbrack; Consente di riassegnare i materiali
* &lbrack;TextureSet&rbrack; Aggiungi un pulsante di impostazione nella finestra dell’elenco di set di texture
* &lbrack;TextureSet&rbrack; Mostra i set di texture &quot;disabilitati&quot; nella parte inferiore dell’elenco
* &lbrack;Substance&rbrack; Utilizza mappe aggiuntive alla risoluzione corrente del set di texture per migliorare le prestazioni
* &lbrack;Scripting&rbrack; Consenti di aggiornare una risorsa utilizzata in un progetto (materiale, generatore, ecc.)
* &lbrack;Scripting&rbrack; Aggiungi un modo per aggiungere/rimuovere uno scaffale
* &lbrack;Scripting&rbrack; Consenti di eseguire query sulle informazioni dalla risorsa nei progetti
* &lbrack;Scripting&rbrack; Consenti di recuperare un elenco di scaffali disponibili
* &lbrack;Scripting&rbrack; Esercitazione per migliorare la miniatura di AlgWidget
* &lbrack;Esporta&rbrack; Disattiva/Attiva profondità di bit in base al supporto del formato di file
* &lbrack;Log&rbrack; Aggiungi nome plug-in per la stampa nella console
* &lbrack;Log&brack; Rimuovi errore sui set di texture nascosti
* Aggiornate la &quot;Schermata introduttiva&quot; con nuove icone e testo per gli esempi

**Corretto:**

* Arresto anomalo durante l’aggiornamento di una trama in progetti specifici
* &lbrack;Viewport&rbrack; il colore interno del piano della Simmetria non è più visibile
* &lbrack;Finestra di vista&rbrack; Alcuni effetti di post-elaborazione sono attivati quando si utilizza la vista Solo
* &lbrack;Shaders&rbrack; la fusione &quot;over_premium&quot; non funziona correttamente
* &lbrack;Shaders&rbrack; Avvertenza sul test alfa con lo shader predefinito
* &lbrack;Shelf&rbrack; Analisi errata dei tag dalle Substance
* &lbrack;Shelf&rbrack; MatFX La misurazione tempo Ruggine non funziona correttamente
* &lbrack;Shelf&rbrack; il filtro HSL è attivato sui canali errati per impostazione predefinita
* &lbrack;Shelf&rbrack; Nitidezza è abilitato per impostazione predefinita sul canale Height/Normale
* &lbrack;Export&rbrack; I predefiniti di esportazione Vray non utilizzano una mappa normale OpenGL
* &lbrack;Strumento&rbrack; problemi di imprecisione con lo strumento clone/sfumino crea artefatti

### 2.5.3

*(Rilasciato il 15 marzo 2017)*

**Corretto:**

* &lbrack;Baker&rbrack; Arresto anomalo quando si esegue i baking con trame specifiche

**Problemi noti:**

* &lbrack;Mac&rbrack; Le particelle possono causare il danneggiamento delle texture in alcuni casi

### 2.5.2

*(Rilasciato il 14 marzo 2017)*

**Corretto:**

* &lbrack;Tool&rbrack; I tablet Wacom non funzionano su Linux
* &lbrack;Strumento&rbrack; artefatti di colore nero quando si utilizza lo strumento sfumino
* &lbrack;Baker&rbrack; Eseguita i baking non riuscita se si utilizza Corrispondenza per nome con una gabbia
* &lbrack;Baker&rbrack; Occlusione ambientale interrotta quando si esegue i baking solo con Mappa normale
* &lbrack;Shelf&rbrack; I filtri generici non gestiscono correttamente il canale alfa (Contrasto/Luminosità, Passa alto, ecc.)
* &lbrack;Viewport&rbrack; problema di prestazioni durante il caricamento di un progetto con le ombre attivate
* &lbrack;Viewport&rbrack; problema di dithering in vista 3D su MacOS
* &lbrack;Viewport&rbrack; Anteprime particelle visualizzate in modo errato quando il profilo colore è attivato
* &lbrack;Iray&rbrack; Arresto anomalo quando si ripristina il progetto in OpenGL se l’inizializzazione di Iray non è riuscita
* &lbrack;IRay&rbrack; La Lucentezza viene ignorata durante il rendering di SpecGloss shader/mdl
* &lbrack;Shader&rbrack; Spec/Gloss shader non corrisponde a Iray e SD
* &lbrack;Shader&rbrack; conversione sRGB diversa dalla conversione LUT lineare in sRGB
* &lbrack;Shader&rbrack; Rendering non corretto durante il caricamento di un progetto con ombreggiature obsolete
* &lbrack;Shader&rbrack; lo shader &quot;pbr-coated&quot; non funziona più
* &lbrack;Esporta&rbrack; alcuni canali vengono comunque esportati anche se non presenti nel set di texture
* &lbrack;Layers&rbrack; Il metodo di fusione &quot;mappa normale dettagli invertiti&quot; non funziona sui canali in scala di grigio
* &lbrack;UI&rbrack; Problema nella &quot;Finestra di selezione colore&quot; con monitor HDPI e zoom dello schermo al 150%

**Problemi noti:**

* &lbrack;Mac&rbrack; Le particelle possono causare il danneggiamento delle texture in alcuni casi

### 2.5.1

*(Rilasciato il 27 febbraio 2017)*

**Corretto:**

* &lbrack;Mac&rbrack; input tablet Wacom interrotto in 3D e Vista 2D
* &lbrack;Baker&rbrack; La corrispondenza per nome non funziona più
* &lbrack;Baker&rbrack; l&#39;impostazione &quot;Media normali&quot; non funziona più
* &lbrack;Iray&rbrack; rendering non corretto con mappa normale eseguita i baking mancante
* &lbrack;Iray&brack; i profili colore si comportano in modo diverso rispetto al modulo di rendering OpenGL
* &lbrack;Iray&brack; L&#39;esportazione del rendering come bitmap non include la correzione del profilo colore
* &lbrack;Substance&rbrack; i Filtri materiali non funzionano più
* &lbrack;Strumento&brack; L&#39;opacità del tratto non viene memorizzata nei predefiniti del pennello
* &lbrack;Strumento&rbrack; Allineamento UV pennello Clona /Clone non funziona più
* &lbrack;Export&rbrack; Il canale di Spostamento deve essere centrato in 0,5 quando si esporta in numero intero
* &lbrack;Template&rbrack; il percorso assoluto viene memorizzato in Modelli
* &lbrack;TextureSet&rbrack; La texture dei canali persiste dopo la rimozione del canale

**Problemi noti:**

* &lbrack;Linux&rbrack; Gli input dei tablet Wacom non funzionano in 3D e Vista 2D
* &lbrack;Mac&rbrack; Le particelle possono causare il danneggiamento delle texture in alcuni casi
* &lbrack;Export&brack; In casi molto rari, i rettangoli neri possono apparire sulle GPU AMD

### 2.5.0

*(Rilasciato il 21 febbraio 2017)*

**Aggiunto:**

* Aggiunta del supporto per le GPU AMD Radeon Pro e AMD FirePro
* &blocca;Strumento&Raccoglitore; Aggiungi il supporto per l&#39;opacità del tratto
* &lbrack;Strumento&rbrack; Aggiungi un modificatore che consenta di continuare l’ultimo tratto del pennello
* &lbrack;Iray&brack; Aggiornamento per supportare le GPU Pascal
* &lbrack;Viewport&rbrack; Aggiungi supporto per profili colore (LUT)
* &lbrack;Substance&rbrack; Integrazione del nuovo framework (motore SD6)
* &lbrack;UI&rbrack; Aumenta elenco dimensioni &quot;file recenti&quot; nel menu File
* &lbrack;Import&rbrack; Utilizza la categoria da sostanze per riempire il prefisso nella finestra di dialogo di importazione
* &lbrack;Baker&rbrack; Consenti di eseguire i baking texture 8K
* &lbrack;Baker&rbrack; Consente di eseguire i baking risoluzioni non quadrate
* &lbrack;Baker&rbrack; migliora il consumo di memoria quando si eseguono i baking trame pesanti a elevato polio
* &lbrack;Shelf&rbrack; Blocca ripiani (e progetti) per impedire modifiche simultanee ed evitare danneggiamenti
* &lbrack;Shelf&rbrack; Leggi la categoria e le parole chiave dalle sostanze per utilizzarle per filtrare
* &lbrack;Shelf&rbrack; Consente di escludere le risorse dal risultato di una query di ricerca
* &lbrack;Shelf&rbrack; Miniature migliorate nel calcolo del tempo
* &lbrack;Shelf&rbrack; Consenti di incorporare predefiniti nei progetti
* &lbrack;Shelf&rbrack; Consenti di comprimere/espandere rapidamente la visualizzazione struttura con MAIUSC
* &lbrack;Shelf&rbrack; Consente di salvare le miniature quando le risorse sono di sola lettura (cache locale)
* &lbrack;Shelf&rbrack; Nuovo contenuto : nuovi filtri (Trasforma, mirror, tri-planari, ecc.)
* &lbrack;Shelf&rbrack; Nuovo contenuto : nuovi profili LUT (classici e artistici, ad esempio Film Noir, Vintage e così via)
* &lbrack;Shelf&rbrack; Nuovo contenuto: 10 nuove Substance di font per generare rapidamente testi personalizzati
* &lbrack;Shelf&rbrack; Nuovi modelli: Unity 5 e Unreal Engine 4
* &lbrack;Shelf&rbrack; Filtro HSL migliorato per semplificare l&#39;uso degli artisti
* &lbrack;Shader&rbrack; Aggiungi supporto per canale di specular level negli shader PBR
* &lbrack;Shader&rbrack; Aggiungi il supporto per il dithering nello shader di test Alpha
* &lbrack;Shader&rbrack; Aggiungi il supporto per la mappatura delle occlusioni parallasse negli shader PBR
* &lbrack;Shader&rbrack; Consente di definire un&#39;interfaccia utente personalizzata per i parametri di shader
* &lbrack;MatLayering&rbrack; Crea un nuovo canale maschera per il flusso di lavoro per la creazione di livelli di materiale
* &lbrack;Scripting&rbrack; Consenti la scrittura di metadati in un progetto SP
* &lbrack;Scripting&rbrack; Consente di esportare con un predefinito di esportazione specifico
* &lbrack;Scripting&rbrack; consente di recuperare i parametri di shader come JSON
* &lbrack;Scripting&rbrack; Aggiungi supporto per connessioni WebSocket
* &lbrack;Scripting&rbrack; Aggiungi la possibilità di caricare istanze shader
* &lbrack;Scripting&rbrack; Aggiungi la possibilità di creare un nuovo progetto
* &lbrack;Scripting&rbrack; Consente di recuperare l&#39;URL della trama importata in un progetto
* &lbrack;Scripting&rbrack; Consenti esegue i baking non quadrata
* &lbrack;Scripting&rbrack; Segnala errori durante l’impostazione dei dati tramite API di scripting
* &lbrack;Substance&rbrack; Aggiungi tag utente-dati per specificare il formato mappa normale

**Corretto:**

* Arresto anomalo di selezione del colore con le sostanze
* Arresto anomalo durante il caricamento di un&#39;immagine non RGBA32f come mappa dell&#39;ambiente
* Arresto anomalo relativo alla pittura su GPU AMD
* &lbrack;Mesh&brack; l&#39;importazione OBJ non riconosce i materiali senza file mtl
* &lbrack;Mesh&rbrack; La generazione del nome del set di texture UDIM può non essere corretta su alcune trame
* &lbrack;UI&rbrack; pulsante Annulla/Ripeti nel visualizzatore Impostazione dello stato attivo e interruzione dello scorrimento del mouse
* &lbrack;UI&rbrack; alcune etichette vengono ritagliate in modo errato con valori DPI alti
* &lbrack;Layer&rbrack; La modalità Sostituisci per l&#39;effetto pittura ha un comportamento errato su Maschera
* &lbrack;Layer&rbrack; il metodo di fusione Sottrai ha un comportamento errato con il canale alfa
* &lbrack;Strumento&rbrack; la dimensione del pennello diventa enorme in vista 2D quando si disegna sui bordi UV
* &lbrack;Tool&rbrack; La linea retta agganciata ha un comportamento irregolare con DPI alto
* &lbrack;Tool&rbrack; La risoluzione dello stencil a volte non è corretta
* &lbrack;Baker&rbrack; i valori di &quot;Distanza max occlusione&quot; sono bloccati se &quot;relativa al rettangolo di selezione&quot; è &quot;Disattivato&quot;
* &lbrack;Shader&rbrack; Le definizioni dei canali Stack e Param automatico non corrispondono
* &lbrack;vista 3D&rbrack; Visualizzazione incoerente del canale normale a seconda dell&#39;impostazione del progetto
* &lbrack;Viewport&rbrack; Alcune mappe normali hanno valori bloccati che appaiono come artefatti
* &lbrack;Viewport&rbrack; Gli effetti successivi sono sempre disattivati per impostazione predefinita
* &lbrack;Export&rbrack; L&#39;impostazione di miscelazione normale non è corretta se manca il canale normale
* &lbrack;Export&rbrack; Generazione errata di texture in alcuni casi su GPU AMD
* &lbrack;Export&rbrack; I parametri di Shader non vengono esportati correttamente se sono inclusi in un gruppo
* &lbrack;Export&rbrack; Modifica di un predefinito di esportazione in uno scaffale personalizzato genera un errore di registro
* &lbrack;Shelf&rbrack; Il filtro della visualizzazione a struttura non corrisponde esattamente al nome della cartella
* &lbrack;Shelf&rbrack; Ridenominare uno shelf predefinito è difficile da leggere
* &lbrack;Shelf&rbrack; la risorsa Shader importata nello scaffale non viene mantenuta dopo il riavvio
* &lbrack;Shelf&rbrack; Contenuto: Predefinito strumento saldatura mancante
* &lbrack;Shelf&rbrack; Contenuto: il Tile Generator non funziona correttamente
* &lbrack;Shelf&rbrack; Contenuto : Corretta la maschera errata sul materiale avanzato sporco di gomma
* &lbrack;Shelf&rbrack; Contenuto : Corretto il nome del gruppo errato nel materiale del sacchetto in pelle
* &lbrack;Iray&rbrack; metà delle trame non è presente in Iray
* &lbrack;Linux&rbrack; Arresto anomalo quando si trascina una risorsa sopra il vista 3D
* &lbrack;Mac&rbrack; Le preferenze vengono reimpostate a ogni avvio su Sierra

**Problemi noti:**

* &lbrack;Export&brack; In casi molto rari, i rettangoli neri possono apparire sulle GPU AMD
* &lbrack;Iray&rbrack; a volte i profili colore possono comportarsi in modo strano

### 2.4.1

*(Rilasciato il 28 ottobre 2016)*

**Corretto:**

* Arresto anomalo di creazione di un progetto con un modello
* Arresto anomalo di chiusura della finestra di dialogo di esportazione durante un’esportazione
* &lbrack;Mac&rbrack; Errori durante il salvataggio del progetto (impossibile salvare il predefinito di esportazione)
* &lbrack;Shelf&rbrack; La creazione di un nuovo predefinito lo visualizzerà due volte
* &lbrack;Shelf&rbrack; I predefiniti non possono essere caricati in modalità di sola lettura senza diritti di amministratore

### 2.4.0

*(Rilasciato il 27 ottobre 2016)*

**Aggiunto:**

* &lbrack;Shelf&rbrack; Nuova interfaccia per sfogliare le risorse (vista struttura, filtri e così via)
* &lbrack;Shelf&rbrack; Consenti di salvare una ricerca come predefinito
* &lbrack;Shelf&rbrack; Consenti di creare una nuova finestra da un predefinito
* &lbrack;Shelf&rbrack; Nuova interfaccia per l&#39;importazione delle risorse
* &lbrack;Shelf&rbrack; Non copiare lo scaffale allegorico predefinito nella cartella Documenti
* &lbrack;Shelf&rbrack; Nuovi predefiniti particelle: Circuito elettrico, Linee elettriche, Rococò, Vene piccole
* &lbrack;Shelf&rbrack; Migliorati i vecchi predefiniti particelle per essere più facili da usare (come &quot;Rain&quot;)
* &lbrack;Shelf&rbrack; Aggiungi nuove informazioni nel menu di scelta rapida della risorsa
* &lbrack;Viewport&rbrack; migliora le prestazioni durante il caricamento delle mappe dell&#39;ambiente
* &lbrack;Viewport&rbrack; Aggiungi supporto per mappe di ambiente che non sono alimentate da due

**Corretto:**

* Arresto anomalo durante la rimozione di una maschera
* Arresto anomalo quando si disegna dopo aver salvato un predefinito
* Arresto anomalo con sfocatura dell’ambiente su alcune GPU
* Arresto anomalo durante l&#39;assegnazione di una risorsa errata con lo scaffale inferiore
* &lbrack;Shelf&rbrack; Pulisci + Salva rimuovi tag e metadati per le risorse nel progetto
* &lbrack;Shelf&rbrack; l&#39;importazione di un predefinito ne visualizzerà le risorse nello scaffale
* &lbrack;Export&rbrack; La Mappa normale generata dal canale del height ha un’intensità bassa
* &lbrack;Export&rbrack; Normale da trama non è sempre presente nella mappa normale finale
* &lbrack;Export&rbrack; A volte la dilatazione con trasparenza può risultare senza trasparenza
* &lbrack;Scripting&rbrack; &quot;alg.plugin_root_directory&quot; può restituire un percorso di rete troncato
* &lbrack;TextureSet&rbrack; Il pulsante Blocca è attivato quando si riaprono progetti non quadrati

### 2.3.1

*(Rilasciato il 7 ottobre 2016)*

**Aggiunto:**

* &lbrack;Plugin&rbrack;&lbrack;Photoshop&rbrack; Consenti di specificare il materiale/stack/canali da esportare
* &lbrack;Scripting&rbrack; I nomi delle funzioni presentano alcune incongruenze

**Corretto:**

* &lbrack;Export&rbrack; L&#39;Alpha può essere eliminato nei predefiniti di esportazione personalizzati
* &lbrack;Export&rbrack; Alpha ottiene una conversione gamma errata sui canali sRGB
* &lbrack;Esporta&rbrack; i documenti non quadrati vengono esportati come quadrati
* &lbrack;Export&rbrack; Impossibile esportare mappe aggiuntive se ne manca una
* &lbrack;Iray&rbrack; Alcuni parametri (come Intensità emissivo) non hanno effetto
* &lbrack;NVIDIA&rbrack; Arresto anomalo all&#39;avvio con NVIDIA Quadro K2200/GTX 750/760
* &lbrack;AMD&rbrack; set di colori non corretto per miniature e anteprime
* &lbrack;AMD&rbrack; si blocca e si verifica un errore del driver all&#39;apertura di un nuovo file
* &lbrack;Log&rbrack; &quot;software-version&quot; non è presente nel file di log

### 2.3.0

*(Rilasciato il 15 settembre 2016)*

**Aggiunto:**

* &lbrack;Plugin&rbrack; Nuovo plug-in &quot;Esporta in Photoshop&quot; (esportazione Pila livelli completa)
* &lbrack;Esporta&rbrack; Consenti di specificare la larghezza della spaziatura interna (in pixel o infinito)
* &lbrack;Esporta&rbrack; Consenti di impostare il tipo di sfondo al di fuori degli UV
* &lbrack;Shelf&rbrack; Nuovo shader di stratificazione del materiale per fondere 10 materiali
* &lbrack;Shelf&rbrack; Nuovo shader argilla per visualizzare i dettagli con il canale height/normale
* &lbrack;Shelf&rbrack; Nuovo filtro di illuminazione eseguito i baking con input ambiente
* &lbrack;Shelf&rbrack; aggiornato alcuni generatori di maschere per aggiungere trasformazioni non quadrate
* &lbrack;Viewport&rbrack; Aggiungi mappa normale composta (normale+height+esegue i baking) alla modalità Solo
* &lbrack;Scripting&rbrack; Consente di esportare mappe aggiuntive
* &lbrack;Scripting&rbrack; Consenti di eseguire query sulle mappe aggiuntive disponibili per set di texture
* &lbrack;Scripting&rbrack; Consenti di recuperare il formato del canale
* &lbrack;Scripting&rbrack; Aggiungi esempi nella documentazione di esegue i baking
* &lbrack;Scripting&rbrack; Consenti di eseguire query sulla visibilità di un livello
* &lbrack;Scripting&rbrack; Consenti di eseguire query sul metodo di fusione e sull&#39;opacità del livello
* &lbrack;Scripting&rbrack; Consente di esportare le mappe convertite (mappa normale finale, AO misto e così via)
* &lbrack;Substance&rbrack; lettura e connessione degli usi personalizzati
* &blocca;Scelte rapide&rbrack; Aggiungi tasto modificatore (MAIUSC) per tornare alla modalità Solo
* &lbrack;Esporta&rbrack; Predefinito di esportazione predefinito aggiornato per disabilitare il canale alfa
* &lbrack;UI&rbrack; Le miniature ora vengono calcolate solo se il motore è disponibile
* &lbrack;UI&rbrack; visualizza una menzione quando le miniature sono in fase di elaborazione

**Corretto:**

* Arresto anomalo con alcuni vecchi progetti all’apertura
* Arresto anomalo con cache canali texture danneggiata
* Arresto anomalo quando si fondono più di 4 materiali con il flusso di lavoro Livelli di materiale
* &lbrack;UI&rbrack; Le scelte rapide dello strumento non funzionano se la barra degli strumenti è nascosta
* &lbrack;UI&rbrack; La barra degli strumenti Iray è denominata &quot;Senza titolo&quot; nel menu Visualizza
* &lbrack;UI&rbrack; Le barre degli strumenti Plugin sono denominate &quot;Untilted&quot; nel menu Visualizza
* &lbrack;Baker&rbrack; premendo Invio durante la modifica di un&#39;impostazione di esegue i baking si avvia la esegue i baking
* &lbrack;Baker&rbrack; Intervalli non corretti per alcuni parametri
* &lbrack;Import&rbrack; impossibile importare trame OBJ a causa dei numeri molto grandi
* &lbrack;Import&rbrack; Alcuni file OBJ vengono importati con troppi sottooggetti
* &nero;Esporta&rbrack; lo sfondo del canale viene riempito con il nero invece del colore predefinito al momento dell&#39;esportazione
* &lbrack;Tool&rbrack; Le particelle non funzionano correttamente se il valore FOV è troppo basso
* &lbrack;Strumento&rbrack; Il colore di anteprima del pennello non è corretto con le maschere nei sottoinsiemi
* &lbrack;Viewport&rbrack; Quando il pennello passa in aree vuote nel Vista 2D, diventa gigantesco
* &lbrack;Riquadro di visualizzazione&rbrack; Anteprima pennello vuoto quando si disegna texture normale
* &lbrack;Scripting&rbrack; Documentazione non corretta: &quot;ao&quot; è elencato invece di &quot;ambientocclusion&quot;
* &lbrack;Scripting&rbrack; Il processo avviato con subprocess() viene interrotto alla chiusura di Painter
* &lbrack;Shelf&rbrack; il filtro di illuminazione Eseguito i baking utilizza un input AO errato
* &lbrack;MacOS&rbrack; Rimosso progetto idrante (incompatibile)
* Il progetto predefinito viene aperto quando si carica un file \*.spt (anziché \*.spp)

**Problemi noti:**

* &lbrack;Plugin&rbrack; A causa di Photoshop, il height e il canale normale non possono essere tradotti così com&#39;è

### 2.2.0

*(Rilasciato il 22 luglio 2016)*

**Aggiunto:**

* &lbrack;Shelf&rbrack; Migliorare il sistema di ricerca e le query
* &lbrack;Shelf&rbrack; Aggiungi campo di ricerca per i mini-scaffali
* &lbrack;Shader&rbrack; Consenti di definire la precisione dei passi per i cursori
* &lbrack;Shader&rbrack; Aggiungi un pulsante Annulla/Ripeti per i parametri degli shader
* &lbrack;Shader&rbrack; Il ricaricamento di uno shader non deve reimpostare i relativi parametri
* &lbrack;MatLayering&rbrack; Aggiungi il supporto per Stratificazioni dinamiche del materiale e sottopile
* &lbrack;MatLayering&rbrack; Consenti di importare il file json per configurare le impostazioni di shader
* &lbrack;MatLayering&rbrack; Sblocca il limite dei campionatori texture (passa a texture senza binding)
* &lbrack;Scripting&rbrack; Consenti di impostare le impostazioni dei baker e di avviarne il calcolo
* &lbrack;Substance&rbrack; Utilizza &quot;utilizzo&quot; per connessioni di input/output oltre agli identificatori
* &lbrack;Strumento&rbrack; Consenti di selezionare il canale di anteprima nella finestra della vista per lo strumento Proiezione

**Corretto:**

* Arresto anomalo all&#39;avvio se le sostanze si trovano in una cartella errata
* Il report di Arresto anomalo a volte non funziona a causa di un file di registro errato
* &lbrack;Iray&rbrack; Effetti post non vengono aggiornati quando Iray è in pausa
* &lbrack;Iray&rbrack; L&#39;attivazione automatica della scelta rapida da tastiera non funziona più
* &lbrack;Iray&rbrack; Il comportamento del cursore Apertura cambia a seconda delle dimensioni della risorsa
* &lbrack;Livelli&rbrack; Il primo canale di materiale non è attivato per impostazione predefinita se è disattivato
* &lbrack;Shader&rbrack; Se un &quot;parametro automatico&quot; non è corretto, non viene stampato alcun errore

**Problemi noti:**

* &lbrack;Mac&rbrack; il limite di campioni di Texture è bloccato a 16 (problema con il driver della GPU)

### 2.1.1

*(Rilasciato il 1° luglio 2016)*

**Aggiunto:**

* &lbrack;License&rbrack; Possibilità di modificare il percorso del file di licenza
* &lbrack;Viewport&rbrack; Aggiungi una scelta rapida da tastiera &quot;B&quot; per passare da una mappa all&#39;altra
* &lbrack;Import&rbrack; Consenti di importare correttamente FBX 2016/2017
* &lbrack;Strumento&rbrack; Rimuovi i controlli quando si utilizza la maschera veloce
* &lbrack;Iray&brack; Aggiungi informazioni sulle dimensioni della scena
* &lbrack;Iray&rbrack; Consenti di aumentare il numero massimo di campioni e il tempo di rendering
* &lbrack;UI&rbrack; Aggiorna immediatamente il risultato quando si utilizza il pulsante +/- sui cursori
* &lbrack;UI&rbrack; Consente una maggiore precisione per i cursori in scala di grigi
* &lbrack;Esporta&rbrack; Non esportare un canale alfa per texture che sono solo RGB
* &lbrack;Export&rbrack; Aggiorna predefinito di esportazione Dota 2
* &lbrack;Shelf&rbrack; Nuovo pattern &quot;Esagono porzioni&quot;
* &lbrack;Shelf&rbrack; nuovo strumento &quot;Saldatura&quot;
* &lbrack;Shelf&rbrack; Filtri di fine aggiornati per fornire controlli di direzione

**Corretto:**

* &lbrack;Export&rbrack; Impossibile esportare file PSD in 8 bit
* &lbrack;Export&rbrack; 8K export non è disponibile in alcune configurazioni hardware
* &lbrack;Export&rbrack; La finestra Sketchfab è ritagliata
* &lbrack;Esporta&rbrack; Mapping di rugosità errato nel predefinito di esportazione Spec/Gloss
* &lbrack;UI&rbrack; La digitazione nei cursori in scala di grigi non funziona più
* &lbrack;UI&rbrack; impossibile inserire filtri negli input di substance (come Generatori)
* &lbrack;UI&rbrack; Alcuni cursori hanno comportamenti dispari
* &lbrack;UI&rbrack; il passaggio DeltaTime +/- per le particelle è troppo grande
* &lbrack;Iray&brack; Alcuni progetti bloccano l&#39;applicazione quando si passa a Iray
* &lbrack;Iray&rbrack; Arresto anomalo durante il rilevamento dell&#39;hardware
* &lbrack;Strumento&rbrack; Il colore di anteprima del pennello non è corretto in modalità Maschera
* &lbrack;Strumento&rbrack; il selettore materiale può essere utilizzato con strumenti incompatibili
* &lbrack;Strumento&rbrack; L&#39;anteprima di proiezione non passa a Diffusa con flusso di lavoro Spec/Gloss
* &lbrack;Shelf&rbrack; La modifica dello shader predefinito interrompe le anteprime smart mats/maschera avanzata
* &lbrack;Shelf&rbrack; Alcuni materiali avanzati hanno nomi errati
* &lbrack;Shelf&rbrack; altre forme alfa sono danneggiate e non verranno caricate
* &lbrack;Viewport&rbrack; Passare alla modalità &quot;Mappa aggiuntiva&quot; e visualizzare prima &quot;altro&quot;
* &lbrack;Viewport&rbrack; Il viewport torna a &quot;other&quot; quando non esiste una mappa aggiuntiva
* &lbrack;Arresto anomalo&rbrack;&lbrack;Linux&rbrack; Il report Arresto anomalo non funziona su Ubuntu (Steam)
* &lbrack;Arresto anomalo&rbrack;&lbrack;Linux&rbrack; I collegamenti agli URL Web non funzionano su Ubuntu (Steam)
* &lbrack;Arresto anomalo&rbrack;&lbrack;Windows&rbrack; Rimuovi &quot;crashwatcher&quot; quando Substance painter non viene più eseguito
* &lbrack;Arresto anomalo&rbrack;&lbrack;Mac&rbrack; Arresto anomalo del report non funziona correttamente
* &lbrack;Arresto anomalo&rbrack; importazione di una trama durante l&#39;importazione di una trama porta a un arresto anomalo
* Set di texture scelta rapida da tastiera di prelievo reimpostato su niente dopo un riavvio

### 2.1.0

*(Rilasciato il 2 giugno 2016)*

**Aggiunto:**

* &lbrack;UDIM&rbrack; Importa porzioni UDIM da una trama come set di texture
* &lbrack;Linux&rbrack; Supporto aggiunto per CentOS 6.6 e Ubuntu 12.4
* &lbrack;Export&rbrack; Aggiungi risoluzione 8K (sperimentale)
* &lbrack;Esporta&rbrack; Consenti di scegliere la profondità di bit durante l&#39;esportazione
* &lbrack;Baker&rbrack; Consenti di eseguire i baking più set di texture contemporaneamente
* Supporto di monitor ad alta risoluzione (ridimensionamento DPI elevato)
* &lbrack;Scripting&rbrack; impostare una risoluzione e un riempimento personalizzati per texture al momento dell&#39;esportazione
* &lbrack;Riquadro di visualizzazione&rbrack; consente di passare da un set di texture all&#39;altro facendo clic sulla trama (tramite Ctrl+Alt+Clic)
* &lbrack;Viewport&rbrack; andare dove si trova il cursore del mouse quando si esegue lo zoom con la rotellina del mouse
* &lbrack;UI&rbrack; aggiorna il colore di sfondo predefinito e la visualizzazione della mappa dell&#39;ambiente
* &lbrack;UI&rbrack; Aggiungi descrizioni comandi con nomi originali per i canali utente
* &lbrack;UI&rbrack; Cambia il colore di sfondo per i canali che non possono essere rinominati
* &lbrack;Strumento&rbrack; Rimuovi i controlli quando si utilizza la maschera veloce
* &lbrack;Shader&rbrack; Consente di definire i gruppi per i parametri e i materiali/le maschere di shader
* &lbrack;Engine&rbrack; ottimizzazione della stampa di piccole dimensioni
* &lbrack;Stencil&rbrack; Aggiungi &quot;W&quot; come scelta rapida da tastiera per attivare/disattivare temporaneamente la maschera
* &lbrack;Shelf&rbrack; Aggiungi un pulsante x per cancellare il campo di ricerca
* &lbrack;Shelf&rbrack; Carica Alpha con un solo clic
* &lbrack;Shelf&rbrack; Nuovo predefinito di esportazione: Vray UDIM, Arnold UDIM, Spec/Gloss da Metal/Rough
* &lbrack;Shelf&rbrack; Nuove alfa: forme, vene e segni geometrici
* Aggiungi nome e versione nelle proprietà dell&#39;eseguibile Substance Painter

**Corretto:**

* &lbrack;Substance&rbrack; impossibile utilizzare contemporaneamente il canale normale e la mappa aggiuntiva
* &lbrack;Iray&rbrack; rifrazione MDL e impostazione assorbimento non funzionano
* &lbrack;Iray&rbrack; La scala della scena originale non viene mantenuta
* &lbrack;Shelf&rbrack; il modello di Specular/Lucentezza utilizza uno shader errato
* &lbrack;Esporta&rbrack; il predefinito di esportazione predefinito non esporta alcune mappe (come AO)
* &lbrack;Viewport&rbrack; Il punto pivot non si aggiorna quando si fa clic all&#39;esterno degli UV nel vista 2D
* &lbrack;UI&rbrack; I valori del cursore sono arrotondati
* &lbrack;UI&rbrack; A volte, quando si modificano i valori dei cursori, lo spazio libero è molto ridotto
* &lbrack;Nuovo progetto&rbrack; L&#39;elenco a discesa Modello non è aggiornato correttamente (da 1.x a 2.x)
* &lbrack;Scripting&rbrack; Corretto il comportamento al passaggio del mouse sui pulsanti personalizzati
* &lbrack;Mac&rbrack; Annullando su un progetto vuoto, la videocamera si blocca

**Problemi noti:**

* Il report di Arresto anomalo non è disponibile su Ubuntu
* Alcuni pulsanti URL potrebbero non funzionare. Consulta le domande frequenti per una soluzione alternativa.

### 2.0.5

*(Rilasciato il 29 aprile 2016)*

**Aggiunto:**

* &lbrack;Shelf&rbrack; aggiunto/aggiornato modello non pbr, shader ed esportazione predefinito
* &lbrack;Shelf&rbrack; Predefinito di esportazione UE4 aggiornato per includere l&#39;Occlusione ambientale

**Corretto:**

* Arresto anomalo durante l&#39;apertura e il salvataggio di alcuni progetti con risorse danneggiate
* &lbrack;Viewport&rbrack; il Wireframe appare interrotto nel Vista 2D
* &lbrack;Shelf&rbrack; Prestazioni migliorate di alcune mappe dell&#39;ambiente di studio
* &lbrack;Shelf&rbrack; Alcune mappe dell&#39;ambiente di studio sono duplicate
* &lbrack;Shelf&rbrack; &quot;Materiale di illuminazione Eseguito i baking&quot; mancante
* &lbrack;Shelf&rbrack; generatore &quot;Conversione scala di grigi&quot; mancante

### 2.0.4

*(Rilasciato il 26 aprile 2016)*

**Aggiunto:**

* Migliorare le collisioni di trama e ottimizzare il rendering dei wireframi
* Migliorare le prestazioni e la gestione della memoria con i grandi progetti
* Migliorare la precisione del cursore e i passaggi
* &lbrack;UI&rbrack; Aggiorna il motore solo quando si convalida un cursore (non quando si immette un valore)
* &lbrack;UI&rbrack; Sposta lo switch Iray in un pulsante dedicato nella barra degli strumenti principale (e cambiane la scelta rapida da tastiera)
* &lbrack;Strumento&rbrack; Aggiungi impostazione per il comportamento posizione origine strumento clone
* &lbrack;Shader&rbrack; consente di leggere i colori dei vertici della trama negli ombreggiatori personalizzati
* &lbrack;Scripting&rbrack; Consente di recuperare l’elenco di set di texture, canali e livelli
* &lbrack;Scripting&rbrack; Aggiungi funzioni di supporto (URL al percorso, ottieni percorso di esportazione dal progetto)
* &lbrack;Mac&rbrack; Rileva la versione &quot;El Capitan&quot; del sistema operativo Mac nel file di registro

**Corretto:**

* Arresto anomalo dopo la seconda esportazione nel Substance share
* Arresto anomalo quando si copia un livello tra set di texture con dati di Maschera veloce.
* Alcuni progetti hanno un programma di aggiornamento molto lungo che richiede molta memoria
* &lbrack;Strumento&rbrack; Arresto anomalo durante la selezione di un predefinito di particella con lo strumento clone/sfumino
* &lbrack;Baker&rbrack; Il caricamento dei file FBX richiede troppo tempo per trame pesanti
* &lbrack;Viewport&rbrack; mappa dell&#39;ambiente Allungamento in alcuni computer
* &lbrack;Viewport&rbrack; Conversione gamma errata dell&#39;alfa del pennello
* &lbrack;Export&rbrack; Alpha memorizzato come trasparenza anziché come canale separato con file Tiff.
* &lbrack;Export&rbrack; Il canale normale viene sempre esportato come OpenGL
* &lbrack;Iray&rbrack; Nomi dei cursori mancanti per le impostazioni di Iray
* &lbrack;Iray&brack; Il rendering viene eseguito con una risoluzione errata su Retina/DPI alto
* &lbrack;Iray&rbrack; Arresto anomalo durante il ridimensionamento dell&#39;interfaccia in modalità Iray
* &lbrack;Iray&brack; rallentamento delle prestazioni quando il rendering viene eseguito a risoluzioni basse
* &lbrack;Iray&rbrack; Pausa non funziona (Iray continua a calcolare in background)
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

* &lbrack;Iray&rbrack; aggiorna il modello e lo shader di specifiche/lucidi per renderli compatibili con Iray
* &lbrack;Esporta&rbrack; Consente di esportare le schermate in ArtStation
* &lbrack;Scripting&rbrack; Supporto dell&#39;esecuzione dalla directory dei plug-in
* &lbrack;Scripting&rbrack; Consenti &quot;Salva con nome&quot;
* &lbrack;UI&rbrack; consente di fare doppio clic su un cursore per modificarne il valore
* Sposta il campione della Vela nel Substance share
* Nuovo progetto di esempio: Sphere Preview
* Avvisa gli utenti in caso di conflitto di estensione della shell

**Corretto:**

* Il programma di installazione sovrascrive l&#39;installazione di Substance Painter 1.x
* &lbrack;UI&rbrack; il layout dell&#39;elenco dei canali non funziona con i filtri
* &lbrack;UI&rbrack; i parametri di Shader non vengono visualizzati
* &lbrack;UI&rbrack; Il ridimensionamento della finestra del livello ritaglia in modo errato il contenuto
* &lbrack;Strumento&rbrack; Il canale Opacità non viene sempre utilizzato correttamente
* &lbrack;Strumento&rbrack; Sfumino/Clona /Clone non funziona con Simmetria
* &lbrack;Strumento&rbrack; L&#39;opacità dell&#39;anteprima del pennello non è corretta con alcuni canali
* &lbrack;Iray&rbrack; Arresto anomalo quando si utilizza Iray mentre non è ancora stato creato
* &lbrack;Iray&rbrack; Impossibile caricare i dati delle impostazioni di iray dal progetto
* &lbrack;Iray&rbrack; Iray non si occupa della modifica delle impostazioni dopo una pausa
* &lbrack;Shelf&rbrack; L&#39;importazione di un materiale sullo scaffale non funziona
* Lo stencil non funziona con il canale Normale
* Arresto anomalo di disegno su alcuni progetti
* Arresto anomalo quando si dipinge con particelle su alcuni progetti
* Arresto anomalo con Elaboratore pixel durante alcuni calcoli

### 2.0.0

*(Rilasciato il 16 marzo 2016)*

**Aggiunto:**

* Scelta rapida da tastiera in Substance Archivia nella barra degli strumenti principale
* Rendering di immagini con modalità di visualizzazione ed esportazione di schermate
* Supporto per la creazione e l’utilizzo di &quot;Maschera avanzata&quot;
* Supporto per il flusso di lavoro PBR Specular/lucidi (con nuovo canale di diffusione)
* Concatenamento di Substance (per collegare le sostanze agli input dell&#39;immagine substance)
* Supporto dello scripting con i plug-in personalizzati
* Migliorare la conversione da Height a Normale utilizzando un filtro Sobel
* Passa la risoluzione dell&#39;anteprima Stencil/Proiezione a 2K
* Aggiungere un canale normale per impostazione predefinita per i nuovi progetti
* Lettura del tag dati utente dal nodo di output per abilitare/disabilitare i canali di una sostanza per impostazione predefinita
* Esporre la fusione Normale/AO nelle impostazioni TextureSet
* &Sfumino;Strumento &Sfumino; Nuovo strumento Sfumino per la fusione e la diffusione dei colori
* &lbrack;Strumento&rbrack; Nuovo strumento Clona /Clone per copiare parte della texture
* &lbrack;Strumento&rbrack; Consenti di selezionare i canali per lo strumento Sfumino, Clona /Clone e Gomma
* &lbrack;Layer&rbrack; Aggiungi nome Substance per nome effetto di riempimento
* &blocco;Livello&rbrack; Consenti di esportare la maschera negli Appunti
* &lbrack;Viewport&rbrack; Passa dalla modalità Prospettiva a quella ortografica e viceversa
* &lbrack;Viewport&rbrack; Consenti di controllare il campo di visualizzazione in modalità Prospettiva
* &lbrack;Viewport&rbrack; Consenti di impostare la Profondità della distanza del campo con CTRL+clic centrale
* &lbrack;Viewport&rbrack; Consente di trascinare e rilasciare le mappe dell&#39;ambiente nel vista 3D.
* &lbrack;Viewport&rbrack; feedback migliorato quando il motore esegue calcoli complessi
* &lbrack;Esporta&rbrack; Consenti di esportare i parametri di shader in un file json
* &lbrack;UI&rbrack; Aggiorna l&#39;interfaccia con nuove icone, colori e layout
* &lbrack;UI&rbrack; Aggiungi i nomi delle risorse ai mini scaffali
* &lbrack;UI&rbrack; comprimi &quot;mappatura canali&quot; per impostazione predefinita
* &lbrack;Shader&rbrack; Scegliere un colore personalizzato per i parametri della texture di shader
* &blocco;Shelf&rbrack; Chiedi dove importare i file quando trascini le risorse
* &lbrack;Shelf&rbrack; Nuova sfera di anteprima per Materiali avanzati e generatori
* &lbrack;Shelf&rbrack; Aggiungi shader Specular
* &blocca;Raccoglitore&zione; nuove forme superficie rigida
* &lbrack;Shelf&rbrack; Nuovi Alpha, texture e forme
* &lbrack;Shelf&rbrack; Nuove texture incarnato
* &lbrack;Shelf&rbrack; nuovi materiali basati su scansione e materiali avanzati
* &lbrack;Shelf&rbrack; Nuovi materiali avanzati e supporto delle specifiche/lucidità dei vecchi
* &lbrack;Shelf&rbrack; Nuovi filtri Finitura per simulazione superficie metallica
* &lbrack;Shelf&rbrack; Nuovo potente generatore di maschere &quot;Editor maschera&quot;
* &lbrack;Shelf&rbrack; vecchi materiali rilavorati e puliti
* Nuovo progetto di esempio &quot;Vela&quot;

**Corretto:**

* &lbrack;Settings&rbrack; Rotazione e velocità di zoom della fotocamera sostituite dal progetto
* &lbrack;Viewport&rbrack; il problema di precisione nella texture normale predefinita genera riflessi errati
* &lbrack;Viewport&rbrack; Vignettatura attivata per impostazione predefinita
* &lbrack;Viewport&rbrack; Gli artefatti vengono visualizzati ai bordi della mappa dell&#39;ambiente (GPU Nvidia)
* &lbrack;Viewport&rbrack; La miniatura in modalità proiezione/stencil è molto lunga da caricare
* &lbrack;Baker&rbrack; Memorizza le texture eseguite i baking in un numero intero a 16 bit anziché a 32 bit
* &lbrack;Layer&brack; Le sostanze obsolete vengono visualizzate in modo errato nella pila
* Il colore e la profondità di bit predefiniti per alcuni canali non sono corretti (ad esempio: Specular, Lucentezza)
* È stato corretto il comportamento della gomma per disabilitare la fusione in modalità passthrough.

**Problemi noti:**

* Simmetria non funziona con lo strumento Sfumino e Clona /Clone
* Esportazione ArtStation mancante

## Versione 1

### 1.7.3

*(Rilasciato il 1° marzo 2016)*

**Aggiunto:**

* &lbrack;Esporta&rbrack; Aggiungi un&#39;opzione per disabilitare il riempimento
* &lbrack;Shelf&rbrack; supporta la gerarchia di scaffali secondari all&#39;interno di una cartella di scaffali

**Corretto:**

* Arresto anomalo di salvataggio su un file di sola lettura precedente
* Arresto anomalo all’apertura di un secondo progetto
* Arresto anomalo durante il caricamento di alcune miniature (scaffale, livelli o descrizioni comandi)
* La disattivazione di &quot;Mantieni posizioni dei tratti sulla trama&quot; non funziona
* &lbrack;Export&rbrack; L&#39;ingrandimento delle bitmap viene eseguito con il filtro più vicino
* &lbrack;Shelf&rbrack; L&#39;individuazione delle risorse è molto lenta
* &lbrack;Shelf&rbrack; I filtri Sfocatura non sono compatibili a 16 bit
* &lbrack;Strumento&rbrack; Simmetria non funziona se si carica un vecchio strumento predefinito
* La finestra di dialogo Colore per il canale Specular non esegue una conversione dello spazio colore

### 1.7.2

*(Rilasciato il 13 gennaio 2016)*

**Aggiunto:**

* &lbrack;Livelli&rbrack; Consenti di specificare la lavorazione predefinita per i livelli di riempimento

**Corretto:**

* &lbrack;Esporta&rbrack; l&#39;esportazione Sketchfab non funziona più
* &lbrack;Livello&rbrack; Il filtro bilineare viene applicato anche su Riempimento senza alcuna trasformazione
* &lbrack;Tool&rbrack; Scarse prestazioni con substance con input immagine in modalità proiezione
* &lbrack;Strumento&rbrack; selettore materiale interrotto

### 1.7.1

*(Rilasciato il 18 dicembre 2015)*

**Corretto:**

* Arresto anomalo quando si cambia set di texture
* Prestazioni rallentate durante la pittura

### 1.7.0

*(Rilasciato il 17 dicembre 2015)*

**Aggiunto:**

* &lbrack;Performance&brack; Calcola contemporaneamente il contenuto dei livelli e le relative miniature
* &lbrack;Esporta&rbrack; Salva il percorso di esportazione come relativo quando è accanto al progetto
* &lbrack;Layers&rbrack; Aggiunto nuovo metodo di fusione: subtract and add/sub
* &lbrack;Layers&rbrack; Nuovo filtro HQ bilineare per i livelli di riempimento
* &lbrack;Shader&rbrack; Impostare uno shader predefinito per la generazione delle miniature nelle preferenze.
* &lbrack;Shader&rbrack; Consenti di specificare uno shader per set di texture
* &lbrack;Shader&rbrack; Consenti di campionare texture dallo scaffale
* &lbrack;Strumento&rbrack; Nuovo comportamento del pennello &quot;a capo&quot; per la pittura
* &lbrack;Strumento&rbrack; Filtro e aliasing ridotti migliorati durante la pittura
* &lbrack;Strumento&rbrack; Qualità pittura dei sub-pixel migliorata
* &lbrack;Strumento&rbrack; è stata rimossa la visualizzazione &quot;base&quot; per le impostazioni del pennello e migliorata l’icona di apertura/chiusura del fotogramma
* &lbrack;Menu&rbrack; Aggiungere icone degli effetti nel menu di scelta rapida
* Creazione di modelli da progetti
* &lbrack;Shelf&rbrack; Nuovi modelli: PBR, Dota 2
* &lbrack;Shelf&rbrack; Nuovo predefinito di esportazione: Dota 2
* &lbrack;Shelf&rbrack; Nuovi shader: Dota 2, pittura per auto PBR, PBR Coated, Velluto PBR
* &lbrack;Shelf&rbrack; Nuovo materiale: ruggine e usura in acciaio, illuminazione stilizzata
* &lbrack;Shelf&rbrack; Nuovi filtri: Sfocatura direzionale, illuminazione stilizzata
* &lbrack;Shelf&rbrack; Nuovo pennello : predefinito morbido e predefinito rigido con un nuovo alfa per un migliore controllo della durezza
* &lbrack;Shelf&rbrack; Nuovi generatori: 3D Distanza e Luce
* &lbrack;Shelf&rbrack; pennelli aggiornati con proiezione a capo e culling sfondo (attivato per impostazione predefinita)
* &lbrack;Shelf&rbrack; disturbo bianco aggiornato con versione elaboratore pixel per un calcolo più veloce

**Corretto:**

* &lbrack;Schermata di benvenuto&rbrack; Tutorials collegamento invia a video precedenti
* &lbrack;Channels&rbrack; Dire &quot;no&quot; per riempire la creazione del livello con AO crea ancora il livello
* &lbrack;Canali&rbrack; I nomi dei canali UserX non si propagano nell&#39;interfaccia
* &lbrack;Viewport&rbrack; La voce Maschera è vuota nell&#39;elenco dei canali singoli
* &lbrack;Condividi&brack; L&#39;esportazione di un file alfa da condividere da SP crea un file .image illeggibile
* &lbrack;License&rbrack; Correggere l&#39;attivazione per i nomi utente con caratteri non ASCII
* &lbrack;Shader&rbrack; La finestra di dialogo dei parametri colore scompare quando si sceglie un colore
* &lbrack;Shelf&rbrack; Le miniature non vengono scaricate dalla memoria se non utilizzate
* &lbrack;Shelf&rbrack; filtro sfumatura fissa
* &lbrack;Strumento&rbrack; Simmetria non funziona con stencil/proiezione
* &lbrack;Strumento&rbrack; nome errato durante la creazione di un nuovo pennello predefinito
* L’impostazione Mantieni tratto rimane disattivata anche durante la reimportazione di una trama
* Reimpostazione del driver (TDR) quando si calcolano particelle di grandi dimensioni.

### 1.6.1

*(Rilasciato il 9 novembre 2015)*

**Corretto:**

* Arresto anomalo durante l’apertura di un progetto se Vista 2D è visibile
* Arresto anomalo durante la creazione di un nuovo predefinito di esportazione se lo scaffale corrente non esiste
* &blocca;Strumento&Segnale; l&#39;icona del selettore di materiale può rimanere visualizzata
* &blocca;Strumento&amp;Segno di interruzione; Il selettore di materiale nasconde il cursore del mouse quando si disegna allo stesso tempo
* &lbrack;Shelf&rbrack; I metadati vengono scritti sul disco dopo ogni uscita

### 1.6.0

*(Rilasciato il 29 ottobre 2015)*

**Aggiunto:**

* Supporto ufficiale per Windows 10
* &lbrack;Substance&rbrack; comprime i gruppi di parametri Substance per impostazione predefinita
* &lbrack;Substance&rbrack; Aggiungi nuovo framework (Migliora le prestazioni degli Elaboratori pixel)
* &lbrack;Viewport&rbrack; Consente di disattivare la visualizzazione del piano della simmetria in modalità simmetria.
* &lbrack;Riquadro di visualizzazione&rbrack; migliorare il rendering e le prestazioni delle ombre
* &lbrack;Riquadro di visualizzazione&rbrack; Sospende il calcolo dell&#39;ombreggiatura durante la pittura
* &lbrack;Viewport&rbrack; Migliora le prestazioni di rendering dei wireframi
* &lbrack;Engine&rbrack; Migliora la gestione della memoria Vram per ridurne l&#39;ingombro
* &lbrack;Engine&rbrack; Migliora l&#39;aggiornamento della texture sulle GPU AMD per prestazioni migliori
* &lbrack;Engine&rbrack; Disattiva l’impostazione di ottimizzazione concatenata sulle GPU NVIDIA per prestazioni migliori
* &lbrack;Effect&rbrack; Aggiungi un tag per richiedere l&#39;input dell&#39;immagine &quot;imbottita&quot;
* &lbrack;Livello&rbrack; Aumenta la precisione dell&#39;Offset UV/scala nel riempimento
* &lbrack;Livello&rbrack; Rende il cursore della scala esponenziale nel riempimento
* &lbrack;Layer&rbrack; Consente di trascinare i materiali direttamente nella Pila livelli.
* &lbrack;Layer&rbrack; Consenti di trascinare i filtri direttamente nella Pila livelli
* &lbrack;Livello&brack; regola il colore del pennello maschera con il colore maschera appena creato
* &lbrack;Shader&rbrack; Esposizione di più parole
* &lbrack;Shader&rbrack; Esposizione funzione gamma/tonemapping per consentire funzioni personalizzate
* &lbrack;Baker&rbrack; modifica le impostazioni predefinite del baker di posizioni per l&#39;utilizzo triplo
* &lbrack;Tool&rbrack; Rinomina &quot;Geometry Decal&quot; in &quot;Polygon Fill&quot;
* &lbrack;Shelf&rbrack; Aggiorna i generatori per supportare TriPlanar : MG Metal edge wear, MG Mask builder, MG Fibre Glass, MG Dirt
* &lbrack;Shelf&rbrack; aggiorna i materiali con le nuove impostazioni e i materiali inutilizzati rimossi
* &lbrack;Shelf&rbrack; 22 nuovi materiali avanzati (plastica, ferro, tessuto, acciaio e altro)
* &lbrack;Shelf&rbrack; Aggiorna i filtri Nitidezza, Sfocatura e Altera con input immagine imbottita per evitare giunture
* &lbrack;Shelf&rbrack; migliorare le impostazioni di alterazione per un utilizzo più semplice
* &lbrack;Shelf&rbrack; 2 Nuovi rumori procedurali: disturbo Perlin 3D e disturbo Worley 3D

**Corretto:**

* &lbrack;Engine&rbrack; Il rilevamento della quantità di Vram per la GPU dedicata non è corretto in Mac
* &lbrack;Engine&rbrack; Texture la versione più scura nella finestra della vista
* &lbrack;Engine&rbrack; Pessime prestazioni quando si disegna al di sotto di più livelli
* &lbrack;Engine&rbrack; I livelli calcolati all’apertura del progetto sono diversi dalla versione memorizzata nella cache
* &lbrack;Substance&rbrack; risultati errati in 4K su Mac
* &lbrack;Substance&rbrack; I parametri sono nell&#39;ordine errato
* &lbrack;Shader&rbrack; Gli shader Toon e Pixelated sono completamente neri
* &lbrack;Shader&rbrack; I parametri scompaiono dopo aver modificato env-map
* &lbrack;Shelf&rbrack; Arresto anomalo durante l&#39;inserimento di file png nella cartella generator
* &lbrack;Shelf&rbrack; Le miniature vengono generate con una bassa rugosità
* &lbrack;Strumento&rbrack; Arresto anomalo quando si utilizza una bitmap nel pennello alfa su windows
* &lbrack;Esporta&rbrack; Predefinito di esportazione mappa aggiuntivo ora esporta una mappa RGB per Posizione

### 1.5.7

*(Rilasciato il 24 settembre 2015)*

**Corretto:**

* Il report di Arresto anomalo non funziona più

### 1.5.6

*(Rilasciato il 21 settembre 2015)*

**Aggiunto:**

* &lbrack;Shelf&rbrack; Migliorare la qualità di rendering delle miniature (utilizzare texture da 1.000 rpm)

**Corretto:**

* &lbrack;Condividi&rbrack; impossibile firmare con un altro account
* &lbrack;Shelf&rbrack; le miniature sono troppo pesanti sul disco
* &lbrack;Shelf&rbrack; Il caricamento dei Materiali avanzati è molto lento
* &lbrack;Windows&rbrack; Correggi installazione servizio licenze
* &lbrack;Channels&rbrack; Trasmissivi map viene creata come G8 per impostazione predefinita

### 1.5.5

*(Rilasciato il 15 settembre 2015)*

**Aggiunto:**

* &lbrack;Shelf&rbrack; Esporta risorse in Substance share
* &lbrack;Shelf&rbrack; Aggiungi nuova anteprima sfera per Materiali
* &lbrack;Shelf&rbrack; Utilizzare la mappa di invidiabilità &quot;Glazed patio&quot; per generare miniature
* &lbrack;Shelf&rbrack; Aumenta la risoluzione delle dimensioni della miniatura a 512x512 pixel
* &lbrack;vista 3D&rbrack; Esposizione del valore di rotazione dell&#39;ambiente
* &lbrack;Windows&rbrack; firma l&#39;applicazione

**Corretto:**

* &lbrack;Baker&rbrack; risultati errati quando si eseguono i baking mappe contemporaneamente
* &lbrack;vista 3D&rbrack; La mappa env viene visualizzata quando nessun progetto è aperto
* &lbrack;Livelli&rbrack; i Generatori di maschere non funzionano sul contenuto del livello
* &lbrack;Livelli&rbrack; è possibile eseguire la pittura sui livelli nascosti
* &lbrack;Shelf&rbrack; Dirt_5 e Dirt_6 sono identici
* &lbrack;Shelf&rbrack; Alcuni generatori di maschere sono pixelati o di bassa qualità
* &lbrack;Strumento&rbrack; Rotazione gizmo errata su determinate angolazioni.
* &lbrack;Strumento&rbrack; troppi canali causano il ritaglio dei pulsanti dei canali
* &lbrack;Strumento&rbrack; Inverti scelta rapida da tastiera maschera per Maschera veloce non funziona
* &lbrack;Export&rbrack; Sketchfab: pulsante Annulla non considerato correttamente
* &lbrack;License&rbrack; Attivazione non riuscita quando non è possibile copiare la licenza
* Il limitatore di cadenza fotogrammi non funziona più nell&#39;interfaccia utente

### 1.5.0

*(Rilasciato il 20 agosto 2015)*

**Aggiunto:**

* &lbrack;Shader&rbrack; Aggiungi numero di riga nei messaggi di errore di compilazione di Shader
* &lbrack;Shelf&rbrack; Migliorare la qualità delle miniature di anteprima
* &lbrack;Shelf&rbrack; Generazione automatica delle miniature per i Materiali avanzati
* &lbrack;Strumento&rbrack; Scelta rapida da tastiera per controllare l&#39;impostazione della durezza nella sostanza
* &lbrack;Strumento&rbrack; Usa widget scala di grigi per decalcomanie geometriche quando si trova sopra una maschera
* &lbrack;Strumento&rbrack; Scelta rapida da tastiera per invertire il colore della pittura mentre si disegna su una mappa in scala di grigio
* &lbrack;Viewport&rbrack; Consenti di visualizzare il wireframe e modificarne il colore
* &lbrack;Viewport&rbrack; Sfoca lo sfondo dell&#39;ambiente
* &blocca;Controlli&rbrack; Aggiungi rotazione alle scelte rapide del mouse per i pennelli
* &lbrack;Esporta&rbrack; Esporta in Sketchfab
* &lbrack;Esporta&rbrack; Crea predefiniti di esportazione per i moduli di rendering
* &lbrack;Export&rbrack; Aggiungi riflessione mappa convertita, F0 e 1/IOR
* &lbrack;UI&rbrack; Aggiungi schermata introduttiva
* &lbrack;UI&rbrack; Aggiorna layout predefinito
* &lbrack;UI&rbrack; Aggiungi descrizioni comandi mancanti e rinomina una voce di menu
* &lbrack;Layers&rbrack; Esporta la maschera attualmente selezionata come bitmap
* &lbrack;Layers&rbrack; Aggiungi azione &quot;inverti maschera&quot; nel menu di scelta rapida

**Corretto:**

* &lbrack;Project&rbrack; Se le trame pivot sono diverse nell&#39;FBX, le trame vengono esplose durante l&#39;importazione
* &lbrack;Substance&rbrack; le Substance utilizzate negli strumenti di proiezione sono bloccate in 256\*256
* &lbrack;Layers&rbrack; Arresto anomalo quando si utilizza Cancella maschera
* &lbrack;Esporta&rbrack; Conversione gamma non corretta su texture molto scure
* &lbrack;Export&rbrack; La mappa di posizione può essere utilizzata solo nei predefiniti di esportazione come mappa in scala di grigio
* &lbrack;Strumento&rbrack; il colore iniziale della decalcomania Geometria è nero se utilizzato su una maschera
* &lbrack;Strumento&rbrack; La scelta rapida da tastiera Rotazione non funziona se non è presente durezza nell&#39;alfa

### 1.4.2

*(Rilasciato il 15 luglio 2015)*

**Corretto:**

* &lbrack;Strumento&rbrack; Arresto anomalo quando si utilizza la decalcomania geometrica con maschera veloce
* L’aggiornamento del progetto da 1.4.0 a 1.4.1 utilizza tutta la memoria del computer
* Importazione del vecchio formato di progetto non corretta
* Gli scaffali personalizzati analizzano l&#39;intera gerarchia e duplicano le risorse ovunque

### 1.4.1

*(Rilasciato il 23 giugno 2015)*

**Aggiunto:**

* &blocca;Riquadro di visualizzazione&rbrack; consente di ancorare i pannelli uno accanto all&#39;altro
* &blocco;Effetto&rbrack; Aggiungi uno sfondo e un righello per l&#39;effetto livello
* &lbrack;Effetto&rbrack; Aggiungi un effetto Pittura che consenta di lavorare su altri effetti

**Corretto:**

* &lbrack;Shelf&rbrack; La generazione delle miniature non funziona se non è aperto alcun progetto
* &lbrack;Shelf&rbrack; impossibile generare l&#39;anteprima del predefinito del materiale
* &lbrack;Shelf&rbrack; Le anteprime dei materiali vengono generate su una trama con normali invertite
* &lbrack;Shelf&rbrack; Le miniature vengono sempre ricalcolate a causa di una funzione hash errata
* &blocca;Raccoglitore&zione; Se si fa clic su un materiale Substance, non vengono collegate ulteriori mappe
* &lbrack;Strumento&rbrack; valore non corretto campionato con il selettore materiale
* &lbrack;Strumento&rbrack; Selettore colore seleziona il colore del cursore della finestra della vista
* &lbrack;vista 2D&rbrack; Velocità fotogrammi/prestazioni molto basse
* &lbrack;Export&rbrack; Arresto anomalo quando si apre la finestra di esportazione con predefiniti di esportazione troppo recenti.
* &lbrack;Export&rbrack; il canale Height su Mappa normale viene convertito nello spazio errato
* &lbrack;Mac&rbrack; BaseColor dagli effetti substance viene visualizzato come lineare
* &lbrack;Mac&rbrack; Il widget Linee rette viene disegnato in modo errato su Retina
* Le linee rette possono rimanere attivate anche con le scelte rapide da tastiera rilasciate.
* Le linee rette del guizmo scompaiono dopo aver ruotato la mappa dell&#39;ambiente
* Gli output di Occlusione ambientale da sostanze non vengono collegati automaticamente al canale AO
* Risolvere il problema di copia della licenza su Windows con carattere speciale nel nome utente

### 1.4.0

*(Rilasciato il 10 giugno 2015)*

**Aggiunto:**

* &lbrack;Export&rbrack; Aggiungi altre mappe nell&#39;elenco delle mappe di input disponibili
* &lbrack;Shelf&rbrack; Utilizza i materiali sbsar come predefiniti di materiale
* &lbrack;Shelf&rbrack; Consenti l&#39;utilizzo di percorsi libreria personalizzati
* &lbrack;Shelf&rbrack; Modificare le dimensioni minime
* &lbrack;Shelf&rbrack; Nuovo contenuto: 20 nuovi materiali avanzati
* &lbrack;Shelf&rbrack; Nuovo contenuto: nuova sostanza procedurale (trama, trama)
* &lbrack;Shelf&rbrack; Filtro Sfocatura aggiornato
* Disegnare linee rette utilizzando un tasto modificatore
* Aggiungere il canale di Occlusione ambientale e rielaborare il comportamento AO/Normale in Pila livelli
* Lettura del colore predefinito da Input immagine definito in Substance dati utente
* Consente di esportare il registro dal menu Aiuto

**Corretto:**

* &lbrack;Baker&rbrack;&lbrack;Mac&rbrack; Arresto anomalo con baker normale da trama
* &lbrack;Baker&rbrack; Arresto anomalo se nel file della gabbia non sono presenti UV
* &lbrack;Baker&rbrack; La corrispondenza per nomi non funziona con l&#39;OBJ esportato da zBrush
* &lbrack;Baker&rbrack; Esegue i baking con una gabbia sovrascrive il eseguo i baking se si utilizzano più set di texture e UV sovrapposti
* &lbrack;Baker&rbrack; file OBJ specifici generano texture nere
* &lbrack;Shelf&rbrack; Impossibile leggere le risorse se impostato su sola lettura
* &lbrack;Shelf&rbrack; I file delle risorse vengono scritti in Painter se sono stati utilizzati nel progetto.
* &lbrack;Shelf&rbrack; Il ricaricamento delle sostanze aggiorna anche il livello
* &lbrack;Export&rbrack; Tiff esporta immagini a 32 bit che non possono essere lette correttamente da Photoshop o motori grafici
* &lbrack;Esporta&rbrack; i canali predefiniti preimpostati esportano sempre come RGB
* &lbrack;Material&rbrack; il canale della Diffusa sovrascrive il mapping BaseColor con le sostanze
* &lbrack;vista 3D&rbrack; illuminazione Diffusa errata con mappe di ambiente specifiche
* &lbrack;Strumento&rbrack; impossibile ruotare un pennello in un angolo specifico
* Il riquadro di visualizzazione diventa attivo quando si passa il cursore del mouse mentre si digita in un campo di testo
* Arresto anomalo con predefiniti troppo recenti per la versione corrente dello scaffale
* Arresto anomalo dopo la sostituzione della trama
* Arresto anomalo quando si ricarica una sostanza con un diverso numero di input
* Trame FBX da Cinema4D importate con nomi di materiale errati

### 1.3.5

*(Rilasciato il 29 maggio 2015)*

**Aggiunto:**

* &lbrack;License&rbrack; Problema di attivazione quando è presente un file di licenza esistente
* &lbrack;Mac&rbrack; Arresto anomalo durante il caricamento di file FBX specifici
* &lbrack;Mac&rbrack;&lbrack;vista 3D&rbrack; Riflesso errato per la GPU integrata
* &lbrack;vista 3D&rbrack; font di Maschera veloce interrotto
* &lbrack;vista 3D&rbrack; Il selettore materiale rende la finestra della vista completamente nera
* Arresto anomalo dopo l’apertura dei progetti creati nella versione 1.3.3
* L&#39;anteprima del materiale è vuota quando si utilizzano ombreggiature con canale alfa
* Il disegno smette di funzionare su trame specifiche
* Le prestazioni diminuiscono notevolmente con le maglie specifiche dell&#39;OBJ
* I canali utente non sono mappati quando si utilizzano gli effetti
* Le cartelle temporanee non vengono pulite all&#39;avvio

**Corretto:**

* Miglioramenti dei tempi di calcolo nel progetto estremamente lungo da caricare
* Modificare la finestra &quot;Risoluzione dei problemi GPU&quot; per renderla più comprensibile
* &lbrack;Layers&rbrack; Salva lo stato del blocco delle proporzioni per i livelli di riempimento e attivalo per impostazione predefinita
* &lbrack;Baker&rbrack; La corrispondenza per nome ora utilizza il suffisso come separatore

### 1.3.4

*(Rilasciato il 27 aprile 2015)*

**Aggiunto:**

* &lbrack;Mac&rbrack; Arresto anomalo con Mac OS X Yosemite (10.10)
* &lbrack;Mac&rbrack; impossibile uscire dalla modalità a schermo intero
* &lbrack;Baker&rbrack; l&#39;opzione Esegue i baking corrispondenza per nome non funziona
* &lbrack;Baker&rbrack; Lo spazio tangente Mikk utilizzato in SP non funziona con UE4
* &lbrack;Baker&rbrack; Il baker di ID non può eseguire i baking colori ID materiale
* &lbrack;vista 2D&rbrack; Il Wireframe non viene visualizzato quando si utilizza lo strumento decalcomania Geometria
* &lbrack;Strumento&rbrack; Il canale alfa di pennelli viene visualizzato come controllo anziché come trasparenza con i materiali
* &lbrack;Strumento&rbrack; Arresto anomalo con decalcomania geometria
* &lbrack;Layers&rbrack; Lo slot dei materiali è compresso per impostazione predefinita sul livello Riempimento
* &lbrack;Export&rbrack; Arresto anomalo quando si esportano con dimensioni superiori alla risoluzione impostata per le texture
* Canale Specular non riconosciuto nei filtri.
* Clean + save non toglie correttamente le risorse dall&#39;archivio delle specie
* Non memorizzare la trasformazione low-poly nel file assbin high-poly
* Il file FBX viene importato con troppi set di texture

**Corretto:**

* Effetti: la Blocca Livelli dovrebbe essere attivata per impostazione predefinita per simulare i livelli &quot;classici&quot;
* Livelli: modificare il livello minimo e massimo di fresatura nell’azione Riempi
* Livelli: salvare e ripristinare lo stato della pila
* Baker: il Baker AO tiene conto della mappa normale se non viene specificato HP
* Baker: sono state aggiunte descrizioni e informazioni aggiuntive nella finestra di esegue i baking
* Creare un file di backup durante il salvataggio di un progetto

### 1.3.3

*(Rilasciato: 01 aprile 2015)*

**Aggiunto:**

* Aggiungere la versione del software e il nome del progetto nella barra del titolo
* Rimuovi informazioni riservate dai nomi dei set di texture e dei Materiali avanzati
* Aggiornamento del motore di Substance alla versione 5
* &lbrack;Shelf&rbrack; Aggiungi nuove mappe ambiente: Corsica beach, studio 05, studio Tornoco e altro
* &lbrack;Shelf&rbrack; Aggiorna MG Mask Builder con i nuovi parametri
* &lbrack;Shelf&rbrack; aggiornare e calibrare le mappe vecchio ambiente

**Corretto:**

* Arresto anomalo all’apertura della finestra di esportazione
* Impossibile trascinare il widget dell&#39;interfaccia utente quando non è ancorato
* &quot;Ricerca aggiornamenti&quot; non funziona
* &blocca;Livelli&rbrack; non selezionare la maschera quando si fa clic su di essa tenendo premuto ALT
* &lbrack;Strumento&rbrack; Tri-planari non funziona con il canale Normale
* &lbrack;vista 3D&rbrack; l&#39;illuminazione della Diffusa dalla mappa env non è corretta
* &lbrack;vista 3D&rbrack; Il calcolo dell&#39;esposizione è diverso da Designer
* &lbrack;vista 3D&rbrack; Le ombre non devono essere visibili su una superficie metallica al 100%
* &lbrack;vista 3D&rbrack; La trama con UV specchiati ha capovolto tangente/binomio
* &lbrack;vista 3D&rbrack; Le ombre producono risultati errati su determinate trame
* &lbrack;Baker&rbrack; Rimuovi la cartella &quot;.alg_meta&quot; creata dai file assbin
* &lbrack;Baker&rbrack; Arresto anomalo quando si esegue i baking se Painter ricalcola contemporaneamente un TextureSet
* &lbrack;Mac&rbrack; errore interfaccia utente del riquadro bianco all&#39;avvio dell&#39;applicazione

### 1.3.2

*(Rilasciato il 6 marzo 2015)*

**Corretto:**

* &lbrack;vista 3D&rbrack; impossibile ricaricare una mappa env salvata con il progetto

### 1.3.1

*(Rilasciato il 5 marzo 2015)*

**Aggiunto:**

* &lbrack;Baker&rbrack; Aggiungi una versione memorizzata nella cache delle trame High-Poly per accelerare il calcolo
* &lbrack;Baker&rbrack; Aggiungi un&#39;icona di avviso se non viene caricata alcuna trama High-Poly
* &lbrack;Baker&rbrack; Se non viene caricata alcuna trama High-Poly, utilizza invece la trama del progetto

**Corretto:**

* &lbrack;Baker&rbrack; premere &quot;invio&quot; quando si modifica il valore di un cursore per chiudere la finestra
* &lbrack;Baker&rbrack; Anche l&#39;attivazione/disattivazione di un baker attiverà il pulsante
* &lbrack;Baker&rbrack; impossibile da eseguire i baking se si utilizza il pulsante &quot;all/none&quot;
* &lbrack;Baker&rbrack; L&#39;ordinamento dei pulsanti di baker non è corretto
* &lbrack;Baker&rbrack; La casella di controllo viene ignorata e tutti i baker vengono sempre elaborati
* &lbrack;Baker&rbrack; stato barra di avanzamento corretto

### 1.3.0

*(Rilasciato il 4 marzo 2015)*

**Aggiunto:**

* &lbrack;Baker&rbrack;&lbrack;vista 3D&rbrack; Usa calcolo spazio tangente Mikkt se non vengono trovate tangenti/binormali
* &lbrack;Baker&rbrack; Aggiunti nuovi baker: Normale, ID, Occlusione, Curvatura, Thickness, Posizione
* &lbrack;Effetti&rbrack; La pila di effetti è ora invertita e visualizzata dall’alto verso il basso (come i livelli)
* &blocco;Effetti&rbrack; Aggiungi nuove icone alla pila di effetti
* &lbrack;Effetti&rbrack; Aggiungi metodo di fusione tra le azioni di riempimento nella pila effetti
* &lbrack;Effetti&rbrack; Rinomina effetti (effetto sostanza = filtro, ecc.)
* Aggiungere un file &quot;lock&quot; durante il processo di salvataggio
* &blocco;Effetti&rbrack; Aggiungi azione Riempimento nella pila effetti
* Aggiunta nuova risorsa: Materiali avanzati
* &blocca;Livelli&rbrack; Consenti di riordinare gli effetti di livello
* &lbrack;Strumento&rbrack; Aggiungi proiezione tripla Planari
* &lbrack;vista 3D&rbrack; Aggiungi supporto per ombre
* &lbrack;vista 3D&rbrack; possibilità di impostare gli stati OpenGL richiesti in shader personalizzati
* &lbrack;vista 3D&rbrack; supporto per alfa tramite nuovi shader
* &lbrack;vista 3D&rbrack; Gli ombreggiatori sono ora provvisti di versione e completamente salvati in un progetto
* &lbrack;vista 3D&rbrack; Avvisa l&#39;utente se lo shader non viene più compilato

**Corretto:**

* &lbrack;Layers&rbrack; correggere l&#39;eliminazione in una cartella compressa
* &lbrack;Shelf&rbrack; Correggere il filtro contenuto nei mini-scaffali
* &lbrack;Shelf&rbrack; Rinominare le categorie e riorganizzare le schede

### 1.2.1

*(Rilasciato il 12 febbraio 2015)*

**Aggiunto:**

* I file \*.spp possono ora essere aperti con un doppio clic in Esplora risorse
* &lbrack;Export&rbrack; Nuovo tag &quot;$project&quot; per i predefiniti di esportazione
* &lbrack;Esporta&rbrack; Aggiungi elenco mappe (con nomenclatura) sotto ogni set di texture
* &blocca;Esporta&blocca; Aggiungi un pulsante Tutto/Nessuno per selezionare i set di texture
* &lbrack;Esporta&rbrack; le mappe vuote vengono eliminate durante l&#39;esportazione

**Corretto:**

* &lbrack;Export&rbrack; i predefiniti Unity5 hanno mappe invertite
* &lbrack;Esporta&rbrack; L&#39;aggiunta di una barra in avanti nel nome del predefinito crea una cartella danneggiata
* &lbrack;Export&rbrack; il canale di Height esportato in formati a 32 bit è bloccato in modo errato
* &lbrack;Export&rbrack; L&#39;elenco dei set di texture non è ordinato come nel progetto
* &lbrack;Tool&rbrack; Il taglio del backface non funziona più
* Il comando Salva non funziona con i caratteri speciali nel tracciato

### 1.2.0

*(Rilasciato il 28 gennaio 2015)*

**Aggiunto:**

* Nuovo canale Normale per la pittura dei dati della mappa normale e la combinazione dei risultati
* &lbrack;Export&rbrack; Nuova finestra di esportazione con la possibilità di creare impacchettamenti personalizzati e impostare nomi personalizzati
* Il formato del file di progetto ora è un singolo file anziché delle cartelle
* &lbrack;Esporta&rbrack; supporta diversi formati normali (DirectX, OpenGL)
* &lbrack;Export&rbrack; Crea un file &quot;lock&quot; temporaneo durante l&#39;esportazione
* &lbrack;Layers&rbrack; Maiusc+LeftPer attivare/disattivare una maschera è possibile fare clic con il pulsante sinistro del mouse
* &lbrack;Parametri&rbrack; Esposizione dello spazio colore nella parte inferiore dell&#39;input di un&#39;immagine
* &lbrack;Shelf&rbrack; Effetto &quot;MG Mask Builder&quot; ha ora nuove impostazioni
* &lbrack;vista 3D&rbrack; la mappa di Occlusione ambientale ora occlude il contributo alla diffusione, non lo specular

**Corretto:**

* L&#39;anteprima del materiale di proiezione/stencil non viene visualizzata correttamente nella finestra della vista
* &lbrack;vista 3D&rbrack; descrizione comando Scelta rapida da tastiera non visualizzata quando si utilizza la scelta rapida da tastiera &quot;S&quot; (stencil)
* &lbrack;Shelf&rbrack; Effetto &quot;MatFx Skin Scale&quot; offre ora prestazioni migliori a bassa risoluzione
* &lbrack;Export&rbrack; Le Texture esportate vengono solo ingrandite quando si specifica un documento di dimensioni maggiori

### 1.1.2

*(Rilasciato il 15 gennaio 2015)*

**Aggiunto:**

* Aggiunte: nuove impostazioni Trasla, Ruota e Scala nel livello Riempimento
* Filtro ottimizzato per pennelli e livelli di riempimento
* La versione di prova è ora completamente disponibile (può essere esportata) ma è limitata nel tempo.

**Corretto:**

* Impossibile importare maglie OBJ con precisione molto ridotta
* Problema durante l&#39;attivazione di una licenza su Windows 7 e 8
* Arresto anomalo durante il salvataggio con nome di un progetto
* Arresto anomalo quando si elimina l’ultimo canale di un set di texture
* Arresto anomalo di eliminazione di un livello in un contesto specifico

### 1.1.1

*(Rilasciato il 25 dicembre 2014)*

**Aggiunto:**

* &blocca;Livello&traccia; seleziona il livello sopra all’apertura di un set di texture di progetto/cambio
* Velocità di salvataggio e salvataggio con nome migliorate con il nuovo algoritmo di compressione
* Visualizzare un errore en durante l’apertura di un progetto troppo recente per Painter

**Corretto:**

* &lbrack;Strumento&rbrack; La decalcomania della geometria genera danni alla memoria
* &lbrack;Brush&rbrack; impossibile immettere manualmente valori mobili inferiori a 1 per la dimensione del pennello
* &lbrack;Livello&rbrack; la creazione di un effetto di selezione colore non lo aggiunge nella Pila livelli
* &blocco;Livello&rbrack; se si sposta il mouse sui livelli, Painter sfarfalla nella barra delle applicazioni
* &lbrack;Layer&rbrack; L&#39;aggiunta di una bitmap come maschera può provocare un arresto anomalo
* La GUI per la modalità Solo con il canale del Height non è corretta
* &quot;Salva progetto&quot; può non riuscire e danneggiare un progetto
* Arresto anomalo quando si apre un progetto dopo averne caricato un altro con uno shader obsoleto

### 1.1.0

*(Rilasciato il 16 dicembre 2014)*

**Aggiunto:**

* &blocco;Effetto&rbrack; nuovo creatore maschera ID materiale
* Nuova linea bianca/nera punteggiata per il gizmo del pennello
* Nuovo parametro segui angolo
* Nuovo parametro di taglio backface
* Nuovo parametro Mouse lento
* &lbrack;Livelli&rbrack; supporto per più selezioni e gestione
* &blocca;Livelli&rbrack; Copia e incolla da un set di texture all&#39;altro
* &lbrack;Export&rbrack; formato PSD di Adobe Photoshop
* &lbrack;Shelf&rbrack; Nuovo strumento: pelliccia, punti metallici e cerniera
* &lbrack;Shelf&rbrack; Nuovo pennello: stampo, matita, linea affilata e punto
* &lbrack;Shelf&rbrack; New alpha : Disturbo gaussiano, linea nitida, stampo, penna, schizzo, punto, cerniera
* Le prestazioni di pittura sono migliorate aggiornando solo le parti delle texture necessarie

**Corretto:**

* &lbrack;Shelf&rbrack; impossibile caricare una sostanza con un grafico con etichette identiche
* &lbrack;Livelli&rbrack; Il metodo di fusione Attraversa non funziona con le maschere
* &lbrack;Stencil&rbrack; Scala interrotta nel Vista 2D
* Problemi e arresto anomalo su Mac OS Yosemite

### 1.0.2

*(Rilasciato il 9 novembre 2014)*

**Aggiunto:**

* Prestazioni migliorate nell’anteprima del materiale con le sostanze
* Prestazioni migliorate con l’anteprima del tratto pennello durante l’aggiornamento del documento
* Prestazioni migliorate nella finestra della vista con una frequenza di aggiornamento inferiore per l’area non di lavoro
* &lbrack;Effetti post&rbrack; interfaccia utente migliorata per la gestione delle impostazioni
* &lbrack;Effetti post&rbrack; ripristina i valori predefiniti
* Substance effetti e operazioni sui livelli nel menu di scelta rapida
* Supporto per input/output premoltiplicato nelle sostanze

**Corretto:**

* &lbrack;vista 3D&rbrack; I parametri di shader personalizzati sono separati da uno spazio grande
* &lbrack;Export&rbrack; Conversione sRGB mancante per il predefinito Unity4
* Possibile Arresto anomalo durante il caricamento delle maglie fbx
* Arresto anomalo a volte durante il caricamento di semplici trame obj
* La barra di elaborazione rimane bloccata al 100% durante il caricamento
* Quando si ricarica una sostanza, la si inserisce in ogni categoria
* Switch DirectX/OpenGL interrotto

### 1.0.1

*(Rilasciato il 27 ottobre 2014)*

**Aggiunto:**

* &lbrack;Tool&rbrack; utilizzo dei parametri dei materiali migliorato
* Nuova scelta rapida da tastiera al sito Web di uservoice nel menu Aiuto
* Vari miglioramenti delle prestazioni del motore

**Corretto:**

* I valori dei parametri sono limitati a 2 decimali per Particelle
* La Substance caricata dalla cache non viene visualizzata nell’interfaccia utente come obsoleta
* Arresto anomalo durante il caricamento di una trama da un url di rete
* Painter è ora riconosciuto come firmato su Mac OS X

### 1.0.0

*(Rilasciato il 15 ottobre 2014)*

**Aggiunto:**

* Supporto Shader personalizzato
* Supporto della risoluzione 4k
* Progetti carattere di esempio
* Visualizza barra di avanzamento per lunghi tempi di calcolo
* &lbrack;Export&rbrack; Aggiungi una passata di dilatazione prima del postprocesso di diffusione
* Argomenti della riga di comando in SP per operazioni semplici
* Nuovi materiali ed effetti
* Anteprima strumento (anteprima del materiale in tempo reale separata e area di prova del tratto)
* Non creare un documento predefinito all&#39;avvio di Painter
* &lbrack;Tool&rbrack; Aggiungi la possibilità di modificare manualmente un valore in scala di grigio
* Vari miglioramenti per gli stencil (Aggancia, Reimposta)
* Le particelle sono ora dei sottostrumenti degli strumenti Pennello artistico, Gomma e Proiezione
* &lbrack;vista 3D&rbrack; Usa AO eseguito i baking nel rendering della finestra della vista
* Dividere i controlli degli stencil tra la vista 2D e 3D
* Modifiche di piccole dimensioni del pollice nella libreria
* I campi di ricerca sono specifici di ogni finestra
* Interfaccia utente modificata

**Corretto:**

* &lbrack;Substance&brack; Switch non funziona
* &lbrack;Finestra di dialogo Colore&rbrack; sfumatura tonalità non aggiornata
* Impossibile aggiornare una trama se il nome del file è identico
* Lo strumento non è visibile nelle visualizzazioni quando è troppo piccolo
* Lo strumento decalcomania sullo schermo Retina non funziona correttamente
* &lbrack;Substance&rbrack; Int1 viene visualizzato come float1
* &lbrack;Substance&rbrack; input/output basecolor non riconosciuti
* &lbrack;Substance&rbrack; filtri non possono essere ricaricati
* &lbrack;Strumento&rbrack; il widget scala di grigi è sempre compresso

## Beta

### 0.12.1-beta

*(Rilasciato il 18 settembre 2014)*

**Aggiunto:**

* Predefinito di esportazione Unity 5

**Corretto:**

* Shader PBR, la qualità del rendering dovrebbe migliorare notevolmente
* La funzione di messa a fuoco è interrotta e le trame vengono ritagliate per impostazione predefinita

### 0.12.0-beta

*(Rilasciato il 17 settembre 2014)*

**Aggiunto:**

* Strumento Contagocce
* Opzione &quot;Mantieni posizione tratto&quot; aggiunta alla reimportazione della trama per quando il rettangolo di selezione cambia.
* Mappa normale trama predefinita Cymourai
* Migliorare l&#39;interfaccia della vista strumenti (i colori sono wip)
* Spostare il menu &quot;Aiuto->Impostazioni&quot; in &quot;Modifica->Impostazioni&quot;
* Salvare il percorso di esportazione nella finestra &quot;Esporta tutti i canali&quot;
* Interfaccia grafica dei nuovi livelli con visualizzazione dell&#39;istogramma
* Migliore gestione delle risorse (trascinamento, ricaricamento di risorse, eliminazione di elementi inutilizzati)
* Passare da &quot;diffusione&quot; a &quot;colore di base&quot;
* Cursori per la modifica delle regolazioni: consenti punti oltre a virgole
* Livello di riempimento: aumenta il valore massimo di Affiancamento
* Mappa ambiente predefinita

**Corretto:**

* Artefatti di riflesso su angoli estremi
* Esportazione specular/lucentezza interrotta
* I collegamenti nella finestra &quot;Informazioni su&quot; di Painter non funzionano
* Arresto anomalo con OSX Yosemite
* Le trame vengono salvate in triangolo
* La scelta rapida da tastiera a colori della finestra degli strumenti viene inviata all&#39;emettitore invece che alla scala di grigi
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

* Gli Shader danno un risultato nero con bassa ruvidezza
* Controllo GPU: gestisce le schede &quot;Quadro&quot;, rileva tutti i dispositivi e adatta di conseguenza il messaggio dell&#39;utente
* La maggior parte dei materiali Substance è limitata a 256 in Beta 9
* Il height viene bloccato quando viene esportato come bitmap
* L’anteprima del pennello è diversa dalla sovrapposizione di proiezione su Mac
* L&#39;utilizzo dello strumento Geometria per creare una maschera non viene visualizzato nelle finestre delle viste
* La maschera veloce è rotta
* Risolvere il problema di fusione sui vecchi mac pro

### 0.10.0-beta

*(Rilasciato il 7 agosto 2014)*

**Aggiunto:**

* Maschere stencil

**Corretto:**

* Supporto per schede Quadro
* Gli Shader danno un risultato nero con bassa ruvidezza
* I materiali Substance hanno un limite di 256
* L’esportazione mappa normale elimina il canale verde

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

* Più arresti anomali GPU
* Arresto anomalo durante l’esportazione dei canali

### 0.8.0-beta

*(Rilasciato il 28 giugno 2014)*

**Aggiunto:**

* Multi-materiale: ora puoi eseguire la pittura su più materiali nello stesso documento
* Simmetria pittura
* Tutti i metodi di fusione sono ora disponibili

**Corretto:**

* Più arresti anomali GPU
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

* Il disegno della mappa dell&#39;altezza non pittura valori negativi.
* La visualizzazione Selettore materiale non deve tenere conto della mappa normale campionata
* Determinismo delle particelle rotto
* Matrice stencil in Vista 2D
* Ngon nei file obj
* Vari arresti anomali

### 0.6.0-beta

*(Rilasciato il 4 giugno 2014)*

**Aggiunto:**

* Nuova opzione di esportazione per esportare una mappa di Specular da una composizione dei canali metallici e di rugosità

**Corretto:**

* Compatibilità con Windows Vista
* La mappa dell&#39;altezza non pittura valori negativi

### 0.5.0-beta

*(Rilasciato il 7 maggio 2014)*

**Aggiunto:**

* Switch 3D/Vista 2D
* Strumento di selezione del blocco UV
* Lo strumento cambia automaticamente quando si disegna su maschere.
* La risoluzione della Substance dipende dal

**Corretto:**

* Arresto anomalo all’avvio
* Arresto anomalo con trame ASCII
* Matrice stencil fissa nel Vista 2D
* Arresto anomalo con Gomma

### 0.4.0-beta

*(Rilasciato il 17 aprile 2014)*

**Aggiunto:**

* Vista 2D uniforme
* Maschere di livello bitmap
* Controllo dell&#39;esposizione ambientale
* Riempi livelli ora usa le finestre Strumenti per impostare le proprietà
* I materiali possono essere applicati ai livelli di riempimento
* Aggiunti altri stencil nella libreria degli stencil
* Predefiniti Particelle aggiornati per un calcolo più veloce
* Ottimizzazione degli shader PBR e miglioramento della qualità per impostazioni di qualità inferiore

**Corretto:**

* Le miniature dei livelli sono collegate al canale attualmente selezionato
* Molti arresti anomali

### 0.3.0-beta

*(Rilasciato il 4 aprile 2014)*

**Aggiunto:**

* Consenti valori negativi nel selettore colore per il disegno della mappa dell’altezza
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
* Corretto: generazione texture errata
* Corretto: Arresto anomalo all’avvio

### 0.2.0-beta

*(Rilasciato il 17 marzo 2014)*

**Aggiunto:**

* Contagocce materiale (scelta rapida da tastiera P)
* Miniature nell’anteprima dello strumento 3D
* Sistema di licenza per versioni autonome
* Scelte rapide di &lbrack; e &rbrack; per Dimensione pennello
* Riempimento su mappe esportate
* Stile finestra strumenti aggiornato
* Stile cursori aggiornati
* Ambiente HDR predefinito aggiornato

**Corretto:**

* Stencil: modifica il valore di flusso nel vista 3D si arresta a 52
* Ciclo infinito nel motore quando l&#39;aggiunta di tasti di pressione 0 al tratto è fissa
* Strumento: la variazione angolo non restituisce valori superiori a +/- 90%
* Modifica della visualizzazione vista 3D quando è selezionata una maschera di livello
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
