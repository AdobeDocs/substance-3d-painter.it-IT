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
* &amp;lbrack;Cage Painting&amp;rbrack; Creazione di un&#39;interfaccia utente di base per la Pittura della gabbia
* &amp;lbrack;Cage Painting&amp;rbrack; Nuove opzioni di visualizzazione della gabbia
* &amp;lbrack;Cage Painting&amp;rbrack; Strumento Selezione/Riempimento Modificabile
* &amp;lbrack;Cage Painting&amp;rbrack; Mostra modalità Fusione nella barra degli strumenti
* &amp;lbrack;Cage Painting&amp;brack; modifiche interfaccia utente del cursore HDR
* &amp;lbrack;Cage Painting&amp;rbrack; shader di visualizzazione
* &amp;lbrack;Cage Painting&amp;rbrack; Ripristina opzioni pila
* Miglioramenti dello strumento Riempimento poligono
* &amp;lbrack;Polygon Fill&amp;brack; Aggiungi patch poligonale
* &amp;lbrack;Polygon Fill&amp;brack; Aggiungi loop poligonale
* &amp;lbrack;Polygon Fill&amp;rbrack; supporto Simmetria con loop/Patch
* &amp;lbrack;Polygon Fill&amp;rbrack; Simmetria anteprima bordi
* &amp;lbrack;Polygon Fill&amp;brack; Rimuovi triangoli con loop e loop parziali
* &amp;lbrack;Polygon Fill&amp;rbrack; Wireframe visibile solo per il set di texture attivo
* &amp;lbrack;Riempimento poligonale&amp;rbrack; evidenziazione dei bordi rossi su triangoli non selezionabili
* &amp;lbrack;Riempimento poligonale; Non disabilitare le opzioni della modalità di riempimento
* &amp;lbrack;Riempimento poligono&amp;rbrack; Consenti di impostare tutte le proprietà del canale con Riempimento poligono
* &amp;blocca;Riempimento poligono&amp;nna; Riprendi tratto precedente funziona con Riempimento poligonale
* &amp;lbrack;Riempimento poligonale; Mostra cursore non consentito su set di texture non attivi
* &amp;blocco;Riempimento poligono&amp;rnco; Anteprima istantanea ALT
* &amp;lbrack;Polygon Fill&amp;rbrack; Scelta rapida da tastiera per il passaggio temporaneo a Polyloop (MAIUSC+A)
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Mostra set di texture/Porzione UV selezione evidenziata
* &amp;lbrack;Viewport&amp;rbrack; Aggiungi il supporto per Trasparenza indipendente dall&#39;ordine nella finestra della vista in tempo reale
* &amp;lbrack;Impostazioni di visualizzazione&amp;rbrack; riorganizza le impostazioni di visualizzazione in nuovi gruppi
* &amp;lbrack;Strumento&amp;rbrack; Aggiungi il supporto per la fusione additiva con tratti pennello
* &amp;lbrack;Strumento&amp;rbrack; Aggiungi supporto per fusione additiva con Riempimento poligonale
* &amp;lbrack;USD&amp;rbrack; L&#39;USD esportato con mappa di opacità rende tutto trasparente in Arnold
* &amp;lbrack;Nvidia&amp;rbrack; Aggiungi avviso sui driver Nvidia più recenti (da 616.56 a 617.14)
* Aggiungi nuovo input mappa motore &quot;mesh_uv_next&quot;
* Aggiornare i baker alla versione 3.23.0
* Aggiornamento del motore di Substance alla versione 9.6.1

**Corretto:**

* &amp;lbrack;Esegui i baking&amp;rbrack; Occlusione ambientale L&#39;opzione Ignora backface per nome trama non funziona
* &amp;lbrack;Esegue i baking&amp;rbrack; &amp;lbrack;AMD&amp;rbrack; Dispositivo perso durante la esegue i baking con trame pesanti e ad alto polio
* &amp;lbrack;Performance&amp;rbrack; Painter nasconde l&#39;utilizzo dell&#39;VRAM
* &amp;lbrack;Viewport&amp;rbrack; texture mancanti all’apertura di progetti su schermi HDPI
* &amp;lbrack;Strumento&amp;rbrack; Il metodo di fusione è disattivato quando si disegna in una maschera
* Cartelle temporanee non eliminate dopo l’esportazione in rete
* &amp;lbrack;USD&amp;rbrack; La geometria USD esportata viene divisa lungo i bordi UV
* &amp;lbrack;USD&amp;rbrack; Blocco durante il caricamento di USDz in formato non valido

### 12.1.5

Data di pubblicazione: **2026/09/15**

Riepilogo: **Versione secondaria**

**Corretto:**

* L’esportazione di un’immagine dallo scaffale a una rete non funziona più
* &amp;lbrack;Generator&amp;rbrack; L&#39;impostazione di &quot;usa texture&quot; su false non disattiva l&#39;uso dell&#39;input della texture
* Il riquadro di visualizzazione si blocca durante il salvataggio durante la modifica della proiezione 3D
* La risoluzione dei livelli del materiale è troppo bassa

### 12.1.4

Data di pubblicazione: **2026/09/04**

Riepilogo: **Versione secondaria**

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; Arresto anomalo durante l&#39;importazione o l&#39;esportazione di file i cui nomi contengono caratteri non ASCII

### 12.1.3

Data di pubblicazione: **2026/08/26**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* Aggiornamento del motore di Substance alla versione 9.4.6

**Corretto:**

* &amp;blocco;Selettore scala di grigi&amp;rbrack; rimane aperto dopo la modifica dello strumento
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; La correzione dell&#39;inclinazione si interrompe quando si disegna e si annulla
* &amp;lbrack;Strumento di proiezione&amp;rbrack; l&#39;interazione del riquadro di visualizzazione viene bloccata dallo strumento di proiezione
* &amp;lbrack;Dynamic Stroke&amp;brack; parametri Dynamic Stroke mancanti nelle proprietà del pennello
* L’esportazione in rete non funziona più

### 12.1.2

Data di pubblicazione: **2026/08/03**

Riepilogo: **Versione secondaria**

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; Alcune Substance possono generare un arresto anomalo durante il rendering
* &amp;lbrack;Arresto anomalo&amp;rbrack; reimporta trama in modalità eseguita i baking
* &amp;lbrack;Arresto anomalo&amp;rbrack; se non si inizializza la visualizzazione grafica, può verificarsi un arresto anomalo
* &amp;lbrack;Arresto anomalo&amp;rbrack; in alcuni casi durante l&#39;aggiornamento del registro può verificarsi un arresto anomalo dell&#39;esportazione della texture
* &amp;lbrack;Arresto anomalo&amp;rbrack; Arresto anomalo in modalità eseguita i baking in alcuni casi durante il caricamento/aggiornamento della mappa dell&#39;ambiente
* &amp;lbrack;Eseguite i baking&amp;rbrack; Il eseguo i baking di riavvio dopo la modifica del file di poly alto può provocare un blocco
* &amp;lbrack;Invia a Photoshop&amp;rbrack; non riesce a esportare la maschera del livello
* &amp;lbrack;Engine&amp;rbrack; Il risultato del punto di ancoraggio non esegue il rendering tra una maschera e un canale di colore

### 12.1.1

Data di pubblicazione: **2026/07/09**

Riepilogo: versione secondaria

Aggiunto:

* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Esposizione inclina base Modalità normale: trama o per-triangolo
* &amp;lbrack;Properties&amp;rbrack; Imposta sempre i colori uniformi sul valore predefinito del canale
* &amp;lbrack;OpenPBR&amp;rbrack; raggruppa i canali per categorie nella finestra Esporta Texture per la creazione di modelli di output
* Aggiornamento del motore di Substance alla versione 9.4.5

Fisso:

* &amp;lbrack;Project&amp;rbrack; L&#39;apertura e il salvataggio di alcuni progetti può richiedere più tempo del solito
* &amp;lbrack;Arresto anomalo&amp;rbrack; Ricarica più trame può generare un arresto anomalo
* &amp;lbrack;Arresto anomalo&amp;rbrack; l&#39;eliminazione di un canale durante la modalità di visualizzazione maschera genera un arresto anomalo
* &amp;lbrack;Arresto anomalo&amp;rbrack; Alcune Substance possono generare un arresto anomalo durante il rendering
* &amp;lbrack;Pittura inclina&amp;rbrack; lo strumento selezionato in pittura inclina rimane selezionato dopo il passaggio alla modalità di disegno
* &amp;lbrack;Esegue i baking impostazioni comuni&amp;rbrack; le impostazioni di distanza gabbia non aggiornano la visualizzazione di wireframe e shader
* &amp;lbrack;Engine&amp;rbrack; La modalità &quot;Vicina spazio 3D&quot; del riempimento UV non funziona correttamente sui triangoli sottili
* &amp;lbrack;Engine&amp;rbrack; Il risultato del punto di ancoraggio non esegue il rendering tra una maschera e un canale di colore

### 12.1.0

Data di pubblicazione: **2026/06/23**

Riepilogo: **Questo aggiornamento è una versione principale e contiene miglioramenti a livello di baker con il nuovo stato predefinito dell’interfaccia utente eseguito i baking, la mappa di inclinazione del colore, il rebake automatico, la nuova opzione per lo srotolamento UV automatico per trame e OpenPBR hardsurface. Per ulteriori dettagli, vedere le note sulla versione complete.**

**Aggiunto**:

* &amp;lbrack;Inclina &amp;eseguo i baking; Inclina strumenti di pittura
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Aggiungi shader anteprima inclina e immagini vettoriali della direzione di inclinazione quando si disegna la mappa di inclinazione
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Aggiungi protezione bordi opzione
* &amp;lbrack;Inclina eseguo i baking&amp;rbrack; Ripetizione automatica
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Rielabora interfaccia utente mappa trama
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Dividi mappa trama / Impostazioni comuni di Esegue i baking + Sposta impostazioni comuni fuori dall&#39;elenco mappa trama solo colore di base o maschera
* &amp;lbrack;Inclina &amp;Eseguo i baking; Cambia pulsanti della barra degli strumenti della finestra della vista
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Mostra interruttore Simmetria per il pennello nella barra degli strumenti superiore
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Rinomina opzioni nel menu Sincronizzazione elenco mappa trama
* &amp;lbrack;Inclina &amp;Eseguo i baking; Aggiorna finestre di dialogo per sincronizzazione e stato selezionato
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Crea variante del selettore colore in scala di grigi
* &amp;lbrack;Inclina Eseguo i baking&amp;rbrack; Aggiorna icona modalità eseguo i baking
* &amp;lbrack;Auto Unwrap&amp;rbrack; opzione Integra superficie rigida
* &amp;lbrack;OpenPBR&amp;rbrack; Aggiungi supporto per OpenPBR 1.1
* &amp;lbrack;OpenPBR&amp;rbrack; Imposta l&#39;OpenPBR come flusso di lavoro e shader predefiniti
* &amp;lbrack;OpenPBR&amp;rbrack; Importa materiali e texture OpenPBR tramite USD
* &amp;lbrack;OpenPBR&amp;rbrack; Esporta OpenPBR e texture tramite USD
* &amp;lbrack;OpenPBR&amp;rbrack; Aggiorna la finestra Texture di esportazione per mostrare la convenzione di denominazione dell&#39;OpenPBR
* &amp;lbrack;OpenPBR&amp;rbrack; Aggiungi documentazione sulle modifiche all&#39;OpenPBR di supporto
* &amp;lbrack;OpenPBR&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; Aggiungi un nuovo MDL per supportare l&#39;OpenPBR 1.1 in Iray
* Diversi miglioramenti minori nelle esportazioni USD
* &amp;lbrack;UI&amp;rbrack; Aggiungi un avviso nella finestra della vista quando si tenta di eseguire la pittura su un altro set di texture
* &amp;lbrack;Appiattisci&amp;rbrack; Consenti di appiattire tutti i livelli istantanei tra set di texture
* &amp;lbrack;Impostazioni set di texture&amp;rbrack; Consenti di selezionare più canali contemporaneamente tramite una nuova finestra
* &amp;lbrack;History&amp;rbrack; Aggiorna il &quot;valore&quot; della voce Annulla per riflettere il nome del parametro
* &amp;lbrack;Pila livelli&amp;rbrack; Rende gli effetti di riempimento nelle maschere predefiniti sul bianco (1.0)
* &amp;lbrack;Substance&amp;rbrack; Aggiungi nuovo input mappa motore &quot;mesh_hard_edges_triangle&quot;
* &amp;lbrack;Substance&amp;rbrack; Aggiungi nuovo input mappa motore &quot;mesh_hard_edges&quot;
* &amp;lbrack;Shader&amp;rbrack; impedisce alle istanze shader di condividere gli stessi nomi
* &amp;lbrack;Shader&amp;rbrack; utilizza lo shader del modello di progetto durante l&#39;importazione di un file USD o GLTF
* Aggiornamento dell&#39;Adobe Color Engine alla versione 7.0
* Aggiornamento della versione minima MacOSX alla versione 13.0 (Ventura)
* &amp;lbrack;Content&amp;rbrack; Nuovi modelli di progetto per l&#39;OpenPBR
* &amp;lbrack;Content&amp;rbrack; aggiorna i progetti di esempio per utilizzare il nuovo shader di OpenPBR
* &amp;lbrack;Python&amp;rbrack; Espandi l’API maschera geometria per consentire le modalità di inclusione ed esclusione, come nell’interfaccia utente

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Mesh Maps Settings&amp;rbrack; Applica le impostazioni ad altri set di texture
* &amp;lbrack;Arresto anomalo&amp;rbrack; Quando si esegue i baking la curvatura da una mappa senza spazio mondo normale
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Esegue i baking&amp;rbrack; Esegue i baking con gabbia personalizzata abilitata ma nessun file selezionato arresti anomali
* &amp;lbrack;Arresto anomalo&amp;rbrack; annullamento della esegue i baking di AO
* &amp;lbrack;Auto-Cage&amp;rbrack; Caricamento infinito quando il percorso del file poli è alto non è valido
* &amp;lbrack;Linux&amp;rbrack;&amp;lbrack;Windows&amp;rbrack; Il selettore colore a volte può essere completamente nero o non essere visualizzato
* &amp;lbrack;Strumento Riempimento poligonale&amp;rbrack; Lo strumento non funziona con file non PBR
* &amp;lbrack;&amp;lbrack;Pittura&amp;rbrack; l&#39;eliminazione del canale del colore di base non elimina il colore colorato in precedenza
* &amp;lbrack;USD&amp;rbrack; Istanze shader non tutte correttamente rilevate
* &amp;lbrack;Substance&amp;rbrack; viene considerato solo il primo utilizzo di un nodo di input/output
* &amp;lbrack;Shader&amp;rbrack; l&#39;Occlusione ambientale viene applicata due volte con i set di texture utilizzando diversi metodi di miscelazione
* &amp;lbrack;Engine&amp;rbrack; La texture normale con canale blu vuoto (nero) può produrre risultati di fusione errati
* &amp;lbrack;GLTF Import&amp;rbrack; La fusione alfa è abilitata su ogni set di texture
* &amp;lbrack;GLTF Export&amp;rbrack; Fusione alfa è sempre abilitata all&#39;esportazione
* &amp;lbrack;Export&amp;rbrack; La geometria a due lati è sempre disattivata durante l&#39;importazione di un file GLTF
* &amp;lbrack;Javascript&amp;rbrack; La modifica delle impostazioni degli shader non contribuisce alla cancellazione della cronologia
* &amp;lbrack;Samples&amp;rbrack; Subsurface scattering non è abilitato in Impostazioni di visualizzazione per Riunione

### 12.0.3

Data di pubblicazione: **2026/05/05**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* Aggiornare i baker alla versione 3.22.2
* Aggiornamento del motore di Substance alla versione 9.4.3
* &amp;lbrack;Python&amp;rbrack; Salvare un materiale avanzato in una posizione specifica

**Corretto:**

* &amp;lbrack;Ubuntu&amp;rbrack; Arresto anomalo durante la selezione del materiale
* &amp;lbrack;Mac&amp;rbrack; Viene visualizzata una finestra a comparsa ricorrente per chiedere l&#39;accesso ai dati di altre app
* &amp;lbrack;Esegui i baking&amp;rbrack; Gli artefatti possono essere visualizzati sulla mappa curvatura
* &amp;lbrack;Esegue i baking&amp;rbrack; Esegue i baking più lenta in alcuni casi
* &amp;lbrack;Altera a geometria&amp;rbrack; In alcuni casi l&#39;opzione Altera a geometria viene disattivata
* &amp;lbrack;Porzione UV&amp;rbrack; Alfa estratto del punto di ancoraggio ignorato da altre porzioni
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;Mac&amp;rbrack; Eccezioni nella console Python con SSL
* &amp;lbrack;Python&amp;rbrack; arresto anomalo Painter all&#39;uscita con widget Qt rimanenti

### 12.0.2

Data di pubblicazione: **2026/04/07**

Riepilogo: **Versione secondaria**

**Aggiunto:**

* &amp;lbrack;Color management&amp;rbrack; Aggiungi nuovo OCIO per specificare lo spazio colore predefinito del selettore colore
* &amp;lbrack;Python&amp;rbrack; Esporre le impostazioni di annullamento automatico del wrapping nell&#39;API Python

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; Il salvataggio con spazio su disco insufficiente può causare l&#39;arresto anomalo o il danneggiamento dei progetti
* &amp;lbrack;Arresto anomalo&amp;rbrack; &amp;lbrack;Ribbon&amp;rbrack; L&#39;utilizzo della barra multifunzione può causare arresti anomali per alcuni progetti
* &amp;lbrack;Arresto anomalo&amp;rbrack; &amp;lbrack;Esegui i baking&amp;rbrack; arresto anomalo in cui non è possibile scrivere il file .assbin nella cartella
* &amp;lbrack;Import&amp;rbrack; le trame OBJ da Stager possono non riuscire durante la creazione del progetto
* &amp;lbrack;Import&amp;rbrack; in alcuni casi all&#39;OBJ manca il volto
* &amp;lbrack;Import&amp;rbrack; la trama USD senza materiale assegnato può essere arresto anomalo durante l&#39;importazione
* &amp;lbrack;Filled Path&amp;rbrack; non influenzato dalla simmetria
* &amp;lbrack;Stencil&amp;rbrack; L&#39;anteprima ha una risoluzione inferiore rispetto al risultato disegnato
* &amp;lbrack;UI&amp;rbrack; &#39;isola uv&#39; è ancora menzionato nella descrizione comando origine colore mappa ID
* &amp;lbrack;Display&amp;rbrack; Le ombre appaiono invertite
* &amp;lbrack;Viewport&amp;rbrack; Il Trasforma di proiezione dell&#39;alterazione rimane dopo il passaggio alla modalità di esegue i baking
* &amp;lbrack;Altera&amp;rbrack; la griglia scompare quando la scala è impostata su 0 sull&#39;asse Z con l&#39;opzione Altera alla geometria abilitata
* &amp;lbrack;Python&amp;rbrack; errore imprevisto durante l&#39;aggiunta di un canale con modifica dell&#39;ambito

### 12.0.1

Data di pubblicazione: **2026/03/18**

Riepilogo: **Versione secondaria**

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Freeze&amp;rbrack; Esporta da progetti specifici

### 12.0.0

Data di pubblicazione: **2026/03/09** Riepilogo: **Si tratta di una versione principale. Questa versione contiene le funzioni che appiattiscono i livelli, altera la geometria, nuovi effetti post, miglioramenti alla nuova finestra del progetto e altri miglioramenti.**

**Aggiunto**:

* &amp;lbrack;Appiattisci livelli&amp;rbrack; Appiattisci i livelli all’interno della Pila livelli
* &amp;lbrack;Unisci livelli&amp;rbrack; Esporta livelli uniti su disco
* &amp;lbrack;Altera a geometria&amp;rbrack; Aggiungi nuova funzionalità di alterazione automatica alle proiezioni di alterazione
* &amp;lbrack;Post-effects&amp;rbrack; Sostituisci gli effetti post con altri nuovi
* &amp;lbrack;Post-effects&amp;rbrack; Aggiorna mappatura toni
* &amp;lbrack;Post-effects&amp;rbrack; Aggiungi nuovo utilizzo per le risorse Post-effetti
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Post-effects&amp;rbrack; Integra le risorse predefinite per i post-effetti nella libreria
* &amp;lbrack;Nuovo progetto&amp;rbrack; Migliora l&#39;interfaccia utente per la creazione del progetto
* &amp;lbrack;Nuovo progetto&amp;rbrack; modifiche alla funzionalità di reimportazione della trama
* &amp;lbrack;Nuovo progetto&amp;rbrack; consente l&#39;apertura dei file \*.geo.usd
* &amp;lbrack;Configurazione progetto&amp;rbrack; Migliora interfaccia utente per la configurazione del progetto
* Aggiornamento della libreria USD alla versione 25.05
* Aggiornamento della Substance Engine alla versione 9.3.4
* Aumenta i driver minimi a 25.3.1/25.Q2 per le GPU AMD
* Aggiornamento di Qt alla versione 6.8.6
* &amp;lbrack;Scripting&amp;rbrack; Aggiornamento dell&#39;API JavaScript alla versione 1.1.20
* Aggiorna Python alla versione 3.13

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; La modifica dell&#39;output di un canale di materiale in una maschera può arresto anomalo
* &amp;lbrack;Import&amp;rbrack; le texture EXR vengono forzate in sRGB anziché in modo lineare durante l&#39;importazione dei file USD
* &amp;lbrack;Porzione UV&amp;rbrack; La sequenza di immagini con una singola immagine riempie anche altre Porzioni UV
* &amp;lbrack;Eseguite i baking&amp;rbrack; AO è diverso tra la CPU e la GPU eseguite i baking
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;MacOS&amp;rbrack; Viewport BaseColor non corrisponde a colorpicker
* &amp;lbrack;USD&amp;rbrack; In alcuni casi i valori uniformi non vengono importati

## Versione 11

### 11.1.3

Data di pubblicazione: **2026/02/12** Riepilogo: **Versione secondaria**

**Risolto**:

* &amp;lbrack;Pitture&amp;rbrack; In alcuni casi, stencil e simmetria non funzionano
* &amp;blocco;Tracciato&amp;rbrack; nessun aggiornamento quando si modifica il cursore dell&#39;opacità del tratto sfumino
* &amp;lbrack;Project&amp;rbrack; impossibile eseguire la pittura su alcune geometrie
* &amp;lbrack;Ribbon&amp;rbrack; il percorso istanziato scompare quando si modifica la risoluzione del set di texture
* &amp;lbrack;UI&amp;rbrack; il selettore colore può ridursi e in alcuni casi scomparire

### 11.1.2

Data di pubblicazione: **2026/01/13** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &amp;lbrack;Esegui i baking&amp;rbrack; migliora il tempo di eseguita i baking per il progetto Porzione UV con il salvataggio asincrono
* &amp;lbrack;Shaders&amp;rbrack; Citazione nelle modifiche apportate al registro modifiche API shader in seguito alla migrazione Vulkan
* Aggiornamento dell’OpenEXR alla versione 3.4.4

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack; Arresto anomalo durante l&#39;avvio su Nvidia GTX 10xx series
* &amp;lbrack;Arresto anomalo&amp;rbrack; L&#39;uso del selettore colore su set di texture diversi può produrre un arresto anomalo quando si esce dall&#39;applicazione
* &amp;lbrack;Prestazioni&amp;rbrack; problema di prestazioni quando si disegna in un progetto con molti livelli
* &amp;lbrack;Performance&amp;brack; Ritardo quando si disegna con la penna grafica
* &amp;lbrack;UI&amp;rbrack; Le impostazioni della fotocamera rimangono disattivate in modalità rendering (Iray)
* &amp;lbrack;Barra multifunzione&amp;rbrack; In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* &amp;lbrack;Ribbon&amp;rbrack; problema di prestazioni con la Porzione UV
* &amp;lbrack;Substance&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Gli input dell&#39;immagine scompaiono se compressi
* &amp;lbrack;Substance&amp;rbrack;&amp;lbrack;UI&amp;rbrack; I gruppi nidificati possono rimanere anche se visibili se li nasconde
* &amp;lbrack;Eseguite i baking&amp;rbrack;&amp;lbrack;UI&amp;rbrack; impossibile impostare il raggio di campionamento della curvatura oltre 0,01
* &amp;lbrack;Eseguite i baking&amp;rbrack;&amp;lbrack;UI&amp;rbrack; impossibile impostare la distanza massima di occlusione oltre 1
* &amp;lbrack;Esegui i baking&amp;rbrack; L’impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e esegue i baking bassa come alta
* &amp;lbrack;Esegue i baking&amp;rbrack; La mappa ID non esegue i baking i colori dei vertici dall&#39;FBX in modalità Bassa come Alta
* &amp;lbrack;Content&amp;rbrack; Highpass filter genera colori sbiaditi nei canali con gestione del colore

### 11.1.1

Data di pubblicazione: **2025/12/09** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &amp;lbrack;Prestazioni&amp;rbrack; Migliora le prestazioni Porzioni UV durante l&#39;elaborazione di texture parziali
* &amp;lbrack;Baker&amp;rbrack; Aggiornamento alla versione 3.15.4

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;MacOS&amp;rbrack; Salvataggio del progetto dalla versione precedente sempre arresto anomalo
* &amp;lbrack;Arresto anomalo&amp;rbrack; La chiusura di un progetto può talvolta generare un arresto anomalo
* &amp;lbrack;Project&amp;rbrack; Errore &quot;conteggio membri non corrispondente&quot; durante l&#39;apertura di un progetto creato nella versione precedente
* &amp;lbrack;Eseguire i baking&amp;rbrack; le Porzioni UV non sono combinate con i risultati della esegue i baking precedente, se presenti
* &amp;lbrack;Eseguite i baking&amp;rbrack; Dispositivo perso anche con raytracing disattivato sulla serie Nvidia GTX 10XX
* &amp;lbrack;Esegui i baking&amp;rbrack; AO con normale ha artefatti ai bordi perché nessuna spaziatura interna
* &amp;lbrack;Eseguite i baking&amp;rbrack; L&#39;impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e l&#39;opzione &quot;corrispondenza per nome&quot; viene attivata
* &amp;lbrack;Esegui i baking&amp;rbrack; La mappa ID è completamente nera se mancano i colori dei vertici in qualsiasi trama di poli alta
* &amp;lbrack;Ribbon&amp;rbrack; la descrizione comando per il metodo di fusione Alfa indica il metodo di fusione Schermo anziché Scherma lineare
* &amp;lbrack;Path&amp;brack; Le tangenti creano un ciclo inatteso quando il punto viene spostato vicino alle estremità del tracciato
* &amp;lbrack;Strumento&amp;rbrack; L&#39;anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
* &amp;blocca;Motore&amp;brack; disegnare piccoli tratti può causare artefatti a blocchi
* &amp;lbrack;Shader&amp;rbrack; l&#39;annullamento della creazione dell&#39;istanza shader non la rimuove correttamente
* &amp;lbrack;Export&amp;rbrack; La modalità di Alpha per l&#39;esportazione GLTF è sempre impostata su MASK
* &amp;lbrack;Python&amp;rbrack; errore imprevisto durante la modifica della Pila livelli all&#39;esterno del blocco di modifica con ambito

**Problemi noti**:

* &amp;lbrack;Ribbon&amp;rbrack; problema di prestazioni con la Porzione UV
* &amp;lbrack;Barra multifunzione&amp;rbrack; In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Ribbon&amp;rbrack; creazione di testi molto lunghi nella barra multifunzione può essere un arresto anomalo
* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.1.0

Data di pubblicazione: **2025/11/18** Riepilogo: **Questo aggiornamento è una versione principale, contiene il nuovo strumento barra multifunzione con nuovi contenuti dedicati, supporto simmetria per livelli di riempimento, parametro dimensioni fisiche per lo spostamento, prestazioni migliorate tramite i baker aggiornati, supporto completo di Vulkan per Windows e Linux e altri miglioramenti.**

**Aggiunto**:

* Nuovo strumento barra multifunzione
* &amp;blocca;Strumento &amp;Barra multifunzione; Aggiungi nuovo strumento Barra multifunzione per creare tracciati senza interruzioni
* &amp;blocco;Barra multifunzione&amp;rbrack; Aggiungi scelte rapide da tastiera per i predefiniti della barra multifunzione nella finestra Proprietà
* &amp;lbrack;Barra multifunzione&amp;rbrack; consente di modificare l&#39;opacità della barra multifunzione per vertice sul tracciato
* &amp;lbrack;Barra multifunzione&amp;rbrack; Consente di modificare le dimensioni della barra multifunzione per vertice sul tracciato
* &amp;lbrack;Barra multifunzione&amp;rbrack; Rimuovi inizio/fine definiti in una Substance quando i tracciati vengono chiusi
* &amp;lbrack;Ribbon&amp;rbrack; Rimuovi anteprima tracciato/materiale nella finestra delle proprietà per gli strumenti tracciato Pittura/Gomma/Sfumino
* &amp;lbrack;Ribbon&amp;rbrack; Aggiungi metodi di fusione per l&#39;alfa e alcuni canali quando si sovrappongono
* Riempi simmetria
* &amp;lbrack;Fill&amp;rbrack; Aggiungere il supporto per simmetria su livelli di riempimento ed effetti
* &amp;lbrack;Fill&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Esporre le impostazioni della simmetria nella finestra delle proprietà per il livello di riempimento e gli effetti
* &amp;lbrack;Fill&amp;rbrack; Rielaborare l&#39;interfaccia utente delle impostazioni della simmetria sia nel menu della finestra della vista che nella finestra delle proprietà
* &amp;lbrack;Fill&amp;rbrack; Riorientare correttamente la texture normale durante la proiezione in modalità di alterazione
* Dimensioni fisiche spostamento
* &amp;lbrack;Spostamento&amp;rbrack; Usa dimensioni fisiche come unità di spostamento
* Miglioramento delle prestazioni
* &amp;lbrack;Prestazioni&amp;rbrack; Migliora il rendering dei tratti pennello piccoli su triangoli grandi
* &amp;lbrack;Performance&amp;rbrack; Migliora i tempi di compilazione degli Shader
* &amp;lbrack;Performance&amp;rbrack; supporto completo di Vulkan per Windows e Linux
* &amp;lbrack;Performance&amp;rbrack; baker aggiornati con rendering GPU più veloce e supporto di AMD raytracing
* &amp;lbrack;UI&amp;rbrack; riorganizza le proprietà degli strumenti in gruppi e comprimi alcuni per impostazione predefinita
* &amp;lbrack;Engine&amp;rbrack; Aggiorna Substance Engine alla versione 9.2.5
* &amp;lbrack;Substance&amp;rbrack; Esponi sostituzione risoluzione per le risorse Substance in Strumenti e riempimenti
* &amp;lbrack;Esporta&amp;rbrack; Aggiorna il predefinito di esportazione delle mappe trama per esportare texture in scala di grigio
* Python
* &amp;lbrack;Eseguite i baking&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Indica nel registro modifiche che interrompono l&#39;aggiornamento dei baker successivi
* &amp;lbrack;Python&amp;rbrack; Esporre le impostazioni delle simmetrie di riempimento in Python
* Contenuto e nuovo contenuto
* &amp;lbrack;Content&amp;rbrack; Aggiungi 75 nuovi strumenti predefiniti per lo strumento barra multifunzione
* &amp;blocco;Content&amp;rbrack; aggiorna la risorsa di creazione delle sfumature per renderla compatibile con la barra multifunzione

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack; Il caricamento di un altro progetto mentre l&#39;aggancio del percorso è abilitato può comportare l&#39;arresto anomalo
* &amp;lbrack;Arresto anomalo&amp;rbrack; è possibile eseguire l&#39;arresto anomalo facendo clic con il pulsante destro del mouse nel pannello Tracciato con le informazioni di un&#39;altra sessione negli Appunti
* &amp;lbrack;UI&amp;rbrack; L&#39;interfaccia scorre verso l&#39;alto nelle proprietà dello strumento durante la creazione di un tracciato
* &amp;lbrack;UI&amp;rbrack; Il cursore del mouse scompare quando la visualizzazione della finestra della vista del percorso è nascosta
* &amp;blocco;Tracciato&amp;rbrack; copiare/incollare diverse proprietà dello strumento nel pannello Tracciato causa proprietà instabili
* &amp;Lbrack;Strumento &amp;Rbrack; I predefiniti degli strumenti Gomma e Sfumino non sempre aggiornano la selezione del canale
* &amp;lbrack;Strumento&amp;rbrack; il valore Dipinto è grigio ma l&#39;interfaccia utente viene visualizzata in bianco dopo il caricamento del predefinito dello strumento colorato nella maschera
* &amp;lbrack;Strumento&amp;rbrack; predefinito creato dalla maschera mantiene i valori dei canali caricati da un altro predefinito
* &amp;lbrack;Substance&amp;rbrack; L&#39;override dello spazio colore normale definito nel grafico non viene considerato
* &amp;lbrack;Content&amp;rbrack; la risorsa forma pennello predefinita utilizza una Substance obsoleta

**Problemi noti**:

* Cronologia Istanze shader non monitorata correttamente
* &amp;lbrack;Ribbon&amp;rbrack; problema di prestazioni con la Porzione UV
* &amp;lbrack;Barra multifunzione&amp;rbrack; In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
* &amp;lbrack;Ribbon&amp;rbrack; le tangenti creano un ciclo indesiderato quando il punto viene spostato vicino alle estremità del tracciato
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Ribbon&amp;rbrack; creazione di testi molto lunghi nella barra multifunzione può essere un arresto anomalo
* &amp;lbrack;Strumento&amp;rbrack; L&#39;anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
* &amp;lbrack;Eseguite i baking&amp;rbrack; L&#39;impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e l&#39;opzione &quot;corrispondenza per nome&quot; è abilitata
* &amp;lbrack;Esegui i baking&amp;rbrack; AO con normale presenta artefatti ai bordi a causa della mancanza di spaziatura interna
* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.3

Data di pubblicazione: **2025/08/05** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &amp;lbrack;Substance 3D Assets&amp;rbrack; Aggiungi un punto di notifica al pannello Risorse 3D
* &amp;lbrack;VFX Platform 2025&amp;rbrack; aggiunta della configurazione ACE 2.0 nelle impostazioni di gestione del colore
* &amp;lbrack;VFX Platform 2025&amp;rbrack; Aggiornamento OCIO alla versione 2.4.2
* Aggiornamento di Iray alla versione 2024.10
* &amp;lbrack;Engine&amp;rbrack; Aggiornamento a Substance Engine v.9.2.3
* &amp;lbrack;Nvidia&amp;rbrack; aumenta la versione minima dei driver Nvidia a 572.60 (Win) e 570.169 (Linux)

**Risolto**:

* &amp;lbrack;Python&amp;rbrack; La modifica con ambito non viene visualizzata nella finestra Cronologia

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.2

Data di pubblicazione: **2025/06/10** Riepilogo: **Versione secondaria**

**Aggiunto**:

* &amp;lbrack;Mac&amp;rbrack; Aggiungi avviso per una versione specifica del sistema operativo che causa artefatti
* &amp;lbrack;Auto-update&amp;rbrack; miglioramenti minori UX al registro errori Risorse
* &amp;lbrack;Srotolamenti automatici&amp;rbrack; Aggiornamento alla versione 1.3.2 con miglioramenti per la giunzione
* &amp;lbrack;USD&amp;rbrack;&amp;lbrack;FBX&amp;rbrack; Aggiungi supporto per più set UV con dati sparsi
* &amp;lbrack;Export&amp;rbrack; Nelle trame esportate come FBX mancano gli eventuali set UV aggiuntivi presenti durante l&#39;importazione

**Risolto**:

* &amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;Linux&amp;rbrack; Arresto anomalo durante il salvataggio sull&#39;unità di rete
* &amp;lbrack;Win&amp;rbrack;&amp;lbrack;Tablet&amp;rbrack; Sfarfallio durante il panning
* &amp;lbrack;SpaceMouse&amp;rbrack; Problema durante l&#39;utilizzo dello strumento tracciato
* &amp;lbrack;Auto-cage&amp;rbrack; Impossibile eseguire i baking dopo un ricaricamento della trama
* &amp;lbrack;Auto-update&amp;rbrack; La sequenza di immagini non viene ricaricata se manca la prima porzione
* &amp;lbrack;Tracciato&amp;rbrack; la tangente personalizzata può influire su un&#39;altra tangente
* &amp;lbrack;Tracciato&amp;rbrack; il tracciato non viene visualizzato sull&#39;insieme di texture se il primo punto si trova su un altro insieme di texture
* &amp;lbrack;UI&amp;rbrack; Alcuni menu sono sempre disattivati dopo l’apertura di un progetto (ad esempio: simmetria)
* &amp;lbrack;Properties&amp;rbrack; Impossibile utilizzare/caricare strumenti predefiniti con lo strumento tracciato pieno
* &amp;lbrack;USD&amp;rbrack; più set UV non vengono riconosciuti in uno shader personalizzato quando si utilizzano file USD
* &amp;lbrack;USD&amp;rbrack; Le videocamere con gli stessi nomi vengono sostituite
* &amp;lbrack;Esporta&amp;rbrack; Invia a Photoshop genera uno spazio colore errato per i risultati a colori e in scala di grigi
* &amp;lbrack;Esporta&amp;rbrack; i canali in scala di grigi con alfa vengono esportati come colore invece che come scala di grigi con formato PNG
* &amp;lbrack;Esporta&amp;rbrack; l&#39;esportazione del canale in scala di grigi come PSD genera un file non valido/troncato
* &amp;lbrack;Content&amp;rbrack; Il filtro Altera in modalità multidirezionale non funziona
* &amp;lbrack;Python&amp;rbrack; Impossibile allocare l&#39;errore dell&#39;elenco durante la ricerca per indicizzazione dei nodi Pila livelli

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.1

Data di pubblicazione: **2025/04/10** Riepilogo: **Versione secondaria**

Nota: **La versione del CCD Linux verrà posticipata al 29 aprile**

**Aggiunto:**

* Aggiornamento a Qt 6.5.8
* &amp;lbrack;Substance&amp;rbrack; Aggiungi messaggio di registro per i filtri quando più input di immagine condividono lo stesso utilizzo
* &amp;lbrack;Nvidia&amp;rbrack; Aggiungi avviso sui driver Nvidia più recenti (572.47)

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; quando si trascina e rilascia un sbsar con un utilizzo in uno slot per un singolo canale
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Path&amp;rbrack; L&#39;opzione Cambia tipo di tracciato non è disattivata quando non si fa clic su un tracciato specifico
* &amp;lbrack;Riempi tracciato&amp;rbrack; Non dovrebbe essere in grado di selezionare il materiale Substance
* &amp;lbrack;Engine&amp;brack; artefatti lungo i tratti pennello
* &amp;lbrack;Motore&amp;rbrack; I tracciati possono essere interrotti con impostazioni specifiche
* Problema con il menu a discesa per lo spazio colore del contagocce
* &amp;lbrack;Auto-update&amp;rbrack; &amp;lbrack;Python&amp;rbrack; Messaggio di errore errato quando si utilizza ResourceID senza versione
* &amp;lbrack;Shader&amp;rbrack; Arresto anomalo durante l&#39;apertura di alcuni progetti

**Problemi noti:**

* &amp;lbrack;SpaceMouse&amp;rbrack; Problema durante l&#39;utilizzo dello strumento tracciato
* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante

### 11.0.0

Data di pubblicazione: **2025/03/11** Riepilogo: **Versione principale, nuova funzione di aggiornamento automatico, strumento Tracciato riempito e altri miglioramenti del percorso, oltre a nuovi filtri e una generazione sperimentale di gabbia automatica per eseguire i baking**

**Aggiunto**:

* Aggiornamento automatico
* &amp;lbrack;Auto-update&amp;rbrack; aggiorna automaticamente le risorse modificate nel pannello Risorse
* &amp;lbrack;Auto-update&amp;rbrack; aggiorna automaticamente le risorse modificate nel progetto
* &amp;lbrack;Auto-update&amp;rbrack; Mantiene disattivato l&#39;aggiornamento automatico per impostazione predefinita
* &amp;lbrack;Auto-update&amp;rbrack; Rende facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono (.sbsar, .glsl, .ai, .svg)
* &amp;lbrack;Auto-update&amp;rbrack; Aggiungi variabile di ambiente per disabilitare la funzione di aggiornamento automatico
* &amp;lbrack;Auto-update&amp;rbrack;&amp;lbrack;SBSAR&amp;rbrack; Rende facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono
* Tracciato pieno
* &amp;lbrack;Tracciato&amp;rbrack;&amp;lbrack;Riempi&amp;rbrack; Aggiungi nuovo strumento per creare tracciati pieni
* Miglioramenti al tracciato
* &amp;lbrack;Path&amp;rbrack; Crea un tracciato che si aggancia ai poligoni
* &amp;lbrack;Path&amp;rbrack; Consenti di cambiare i tipi di percorso
* &amp;lbrack;Path&amp;brack; Consenti di copiare e incollare i dati dei vertici del tracciato tra contenuto e maschera
* &amp;lbrack;Path&amp;rbrack; Consenti di vincolare l&#39;angolo durante la creazione di un nuovo punto
* &amp;lbrack;Path&amp;rbrack; Consenti di vincolare la creazione di punti a una linea
* &amp;blocco;Tracciato&amp;rbrack; Chiudi forma con un solo clic
* &amp;lbrack;Path&amp;rbrack; Visualizza informazioni sul percorso
* &amp;blocco;Tracciato&amp;rbrack; Consenti di ridimensionare e ruotare i vertici del tracciato
* &amp;lbrack;Path&amp;rbrack;&amp;lbrack;UX&amp;rbrack; Semplificare l&#39;accesso ai gizmo di trasformazione
* &amp;blocco;Tracciato&amp;rbrack; Aggiungi anteprima tracciato
* &amp;blocca;Tracciato&amp;rbrack; disattiva l&#39;anteprima del tracciato con Maiusc + P
* &amp;lbrack;Path&amp;rbrack; Migliora l&#39;edizione tangente dalla vista laterale
* &amp;lbrack;Tracciato&amp;rbrack; Consenti di concentrarsi su un tracciato 3D
* &amp;lbrack;Path&amp;brack; I vertici devono mantenere lo stato di selezione quando si attiva e disattiva l&#39;interfaccia utente
* &amp;lbrack;Path&amp;rbrack; Consente di eliminare il percorso utilizzando Backspace
* &amp;lbrack;Path&amp;rbrack; Mantieni aperto l&#39;elenco dei percorsi se l&#39;utente lo espande
* &amp;lbrack;Path&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; rinominare correttamente i duplicati quando si copia o incolla
* &amp;lbrack;Path&amp;brack; miglioramenti all&#39;interfaccia utente e alla descrizione comandi
* Prestazioni
* &amp;lbrack;Prestazioni&amp;rbrack; Migliora le prestazioni della finestra della vista quando si utilizza un livello di tassellatura elevato
* &amp;lbrack;Prestazioni&amp;rbrack; Abilita solo il primo canale sui nuovi livelli di riempimento/effetti
* &amp;lbrack;Prestazioni&amp;rbrack; Calcolo del tratto pennello in parallelo
* Baking
* &amp;lbrack;Esegue i baking&amp;rbrack; Aggiungi nuova opzione di generazione gabbie completamente automatica per eseguire i baking con trame ad alto poli (sperimentale)
* Contenuti
* &amp;lbrack;Content&amp;rbrack; Aggiungi 6 nuovi filtri: stilizzazione, quantizzazione, kuwahara anisotropo, smusso uniforme, distanza direzionale, conversione scala di grigi
* &amp;lbrack;Content&amp;rbrack; aggiorna Disturbi e Grunge alla versione più recente di Designer (con il nuovo Voronoi 2D)
* &amp;lbrack;Content&amp;rbrack; Aggiungi 3 nuovi generatori di texture (Affianca casuale, Triangle Grid, Generatore Scratches)
* &amp;lbrack;Content&amp;rbrack; Rinomina il modello di motore originale ed esporta i predefiniti
* Python
* &amp;lbrack;Shelf&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Salva materiale avanzato o maschera avanzata su disco da Python
* &amp;lbrack;Python&amp;rbrack; Aggiungi gabbia automatica eseguente i baking all&#39;API Python
* &amp;lbrack;Python&amp;rbrack; Consente di modificare i nomi e le descrizioni di set di texture/Porzioni UV
* &amp;lbrack;Python&amp;rbrack; Condivisione delle impostazioni di risoluzione su sorgenti vettoriali e di font
* &amp;lbrack;Auto-update&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Esposizione delle funzionalità di aggiornamento automatico del progetto in Python
* Varie
* &amp;lbrack;Esporta&amp;rbrack; Semplifica l’accesso alle opzioni di invio con un nuovo pannello
* &amp;lbrack;Nvidia&amp;rbrack; Aggiungi avviso sui driver Nvidia più recenti (572.16)
* L’aggancio dell’angolo deve essere influenzato dalla selezione dello spazio Oggetto/Mondo
* &amp;lbrack;Elenco set di texture&amp;rbrack; consente di aggiungere un nome personalizzato alle Porzioni UV e di utilizzarle all&#39;esportazione
* Mac
* &amp;lbrack;Mac&amp;rbrack; Utilizzare Metal invece di OpenGL per il rendering grafico
* &amp;lbrack;Mac&amp;rbrack; Elimina supporto Mac

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack; Elimina input immagine
* Impossibile aggiungere smart mat tramite il pulsante Pila livelli
* &amp;lbrack;Python&amp;rbrack; Impossibile trovare gli effetti su GroupLayerNode

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;MacOS Intel&amp;rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante
* &amp;blocco;RedHat&amp;rbrack; problemi relativi al selettore colore

## Versione 10

### 10.1.2

Data di pubblicazione: **2024/12/3** Riepilogo: **Versione secondaria, correzioni di bug**

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack; Elimina input immagine
* Impossibile aggiungere smart mat tramite il pulsante Pila livelli
* &amp;lbrack;Python&amp;rbrack; Impossibile trovare gli effetti su GroupLayerNode

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;MacOS Intel&amp;rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante
* &amp;blocco;RedHat&amp;rbrack; problemi relativi al selettore colore

### 10.1.1

Data di pubblicazione: **2024/11/5** Riepilogo: **Versione secondaria, correzioni di bug**

**Aggiunto**:

* &amp;blocco;Progetto&amp;rbrack; mantieni aperto il progetto corrente fino a quando la nuova selezione del progetto non viene convalidata
* &amp;lbrack;Srotolamento automatico&amp;rbrack; densità texel consente di dividere meglio le Isole UV in UDIM
* &amp;lbrack;Eseguite i baking&amp;rbrack; Correggi copia ambigua nel menu di scelta rapida delle Mappe trama
* &amp;lbrack;Altera&amp;rbrack; rimuove il ridimensionamento nella finestra della vista per l&#39;asse Z (profondità)
* &amp;lbrack;Import/Export&amp;brack; Rimuovi il supporto per i formati di file immagine inutilizzati
* Aggiornamento della Substance Engine alla versione 9.1.4

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack; dopo il trasferimento della risorsa in Risorse e il salvataggio del progetto
* &amp;lbrack;Arresto anomalo&amp;rbrack; Problemi con la libreria aiserver
* &amp;lbrack;Arresto anomalo&amp;rbrack; arresto anomalo del server Illustrator in alcuni rari casi
* &amp;lbrack;Arresto anomalo&amp;rbrack; Quando si esce dall&#39;applicazione in alcuni rari casi
* Impossibile inviare report di arresto anomalo su alcuni computer
* &amp;lbrack;Esegui i baking&amp;rbrack; Il colore del vertice non viene letto correttamente
* &amp;blocco;UI&amp;rbrack; la posizione delle finestre e le novità all&#39;avvio vengono spostate
* &amp;lbrack;Assimp&amp;rbrack; StandardSurface di Maya non riconosciuto nella esegue i baking di ID
* &amp;lbrack;Python&amp;rbrack; La libreria SSL mancante genera un errore
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;Win&amp;rbrack; Errore durante la chiamata di QColorConstants.Transparent
* &amp;lbrack;Python&amp;rbrack; Le miniature dei livelli create tramite Python non si aggiornano finché non si fa clic all&#39;interno della Pila livelli
* &amp;lbrack;Shader&amp;rbrack; collegamento interrotto nel registro modifiche API shader
* &amp;lbrack;Risorse 3D&amp;rbrack; Usa le impostazioni proxy del sistema operativo per accedere alle Risorse 3D

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regressione&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;MacOS Intel&amp;rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget che sembra eliminato tramite uno script funziona ancora
* &amp;blocco;RedHat&amp;rbrack; problemi relativi al selettore colore

### 10.1.0

Data di pubblicazione: **2024/09/17** Riepilogo: **Rilascio principale, nuovo contenuto: maschera area di riempimento/filtro colore, filtro decalcomania ricamo e sei filtri Substance generici, importazione di USD con proprietà di materiali e shader, miglioramento delle prestazioni, conformità della piattaforma VFX 2024 e migrazione a Linux RedHat**

**Aggiunto**:

* &amp;blocco;Contenuto&amp;rbrack; Aggiungi nuova maschera area di riempimento/filtro colore
* &amp;lbrack;Content&amp;rbrack; Aggiungi nuovo filtro decalcomania ricamo
* &amp;lbrack;Content&amp;rbrack; Aggiungi 6 nuovi filtri Substance generici (FXAA, pixelate, highpass, posterize, smoothstep, threshold)
* &amp;lbrack;USD&amp;rbrack; Esporta il livello USD con un materiale ASM definito
* &amp;lbrack;USD&amp;rbrack; Importa USD con proprietà di materiale e shader
* &amp;lbrack;Prestazioni&amp;rbrack; Abilita miniature Pila livelli ottimizzate per impostazione predefinita
* &amp;lbrack;Prestazioni&amp;rbrack; Riduci il tempo di apertura dei file di progetto e il consumo di memoria (decodifica dei dati)
* Conforme alla piattaforma VFX 2024
* &amp;lbrack;VFX Platform 2024&amp;rbrack; aggiornamento a Python 3.11
* &amp;lbrack;VFX Platform 2024&amp;rbrack; aggiornamento all&#39;OpenEXR 3.2
* &amp;lbrack;VFX Platform 2024&amp;rbrack; &amp;lbrack;USD&amp;rbrack; aggiornamento OpenSubdiv 3.6.0
* &amp;lbrack;VFX Platform 2024&amp;rbrack;&amp;lbrack;Color Management&amp;rbrack; Aggiornamento a OCIO 2.3.2
* &amp;lbrack;Linux&amp;rbrack; Migrazione a Linux RedHat
* &amp;lbrack;Linux&amp;rbrack; aggiornamento della versione minima del driver Nvidia a 535.171.04
* &amp;lbrack;Import&amp;rbrack; Aggiungi un&#39;opzione per capovolgere la mappa normale durante l&#39;importazione di una trama GLTF
* &amp;lbrack;UI&amp;rbrack; Utilizza il valore predefinito del sistema operativo per la distanza di rilevamento eventi trascinamento
* &amp;lbrack;Substance Engine&amp;rbrack; Aggiungi funzione di striscia di chiamata per rimuovere i simboli dall&#39;eseguibile
* &amp;lbrack;Schermata iniziale&amp;rbrack; Aggiornamento al nuovo formato della schermata iniziale
* Aggiornamento della Substance Engine alla versione 9.1.3
* &amp;lbrack;Python&amp;rbrack; Mostra collegamento agli esempi nel menu Pila livelli documentazione
* &amp;lbrack;JavaScript&amp;rbrack; Sposta i plug-in Javascript nella sottocartella javascript/plugins

**Risolto**:

* &amp;lbrack;Illustrator&amp;rbrack; Arresto anomalo di esportazione di una Porzione UV con grafica .ai in casi specifici
* &amp;lbrack;Tratti dinamici&amp;rbrack;&amp;lbrack;Path&amp;rbrack; Casuale per tratto non funziona su un tracciato
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Properties&amp;rbrack; Il blocco è attivato quando l&#39;Affiancamento non è uniforme
* Il file TXT di debug viene creato quando si fa doppio clic su un progetto Painter
* &amp;lbrack;USD&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Alcune texture potrebbero essere mancanti
* &amp;lbrack;ASM&amp;rbrack; il canale colore di dispersione ignora l&#39;effetto metallico
* &amp;lbrack;Content&amp;rbrack; Il filtro Sfocatura non funziona nello spazio colore &quot;di lavoro&quot;
* &amp;lbrack;Contenuto&amp;rbrack; Il filtro Regolazione Height modifica anche l&#39;alfa del livello

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Win&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; &amp;lbrack;ACE&amp;rbrack; Non si utilizza lo spazio cromatico sRGB ICE per la Trasforma di visualizzazione
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;MacOS Intel&amp;rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &amp;lbrack;Arresto anomalo&amp;rbrack; riposiziona risorsa e salva progetto
* &amp;lbrack;Engine&amp;rbrack; Colorazione con lo strumento Clona /Clone in colori di scorrimento canale normale non corretta
* &amp;lbrack;Python&amp;rbrack; Il widget fantasma viene eliminato da script ancora funzionante
* &amp;blocco;RedHat&amp;rbrack; problemi relativi al selettore colore

### 10.0.1

Data di pubblicazione: **2024/06/11** Riepilogo: **Versione secondaria, correzioni di bug**

**Aggiunto:**

* &amp;lbrack;Libreria&amp;rbrack; Converte i font Substance in normali file di font
* &amp;lbrack;Illustrator&amp;rbrack;&amp;lbrack;SVG&amp;rbrack; Assegna alle miniature nella selezione dell&#39;ambito uno sfondo grigio chiaro
* &amp;lbrack;Python&amp;rbrack; Aggiungi funzione sull&#39;origine bitmap per elencare gli spazi colore disponibili

**Risolto**:

* &amp;lbrack;Pila livelli&amp;rbrack; cartella sempre chiusa quando viene spostata all&#39;interno o all&#39;esterno di altre cartelle
* &amp;lbrack;Salva&amp;rbrack; Il file di progetto viene perso quando &quot;salva come copia&quot; o il salvataggio automatico non riesce in casi specifici
* &amp;lbrack;Import&amp;rbrack; Risorse con lo stesso nome ma estensioni diverse vengono sostituite
* &amp;lbrack;Properties&amp;rbrack; Impostazioni mancanti quando si utilizza un punto di ancoraggio negli input dell&#39;immagine
* &amp;lbrack;Illustrator&amp;rbrack; Impossibile importare i file Illustrator dopo l&#39;arresto anomalo del server senza riavviare Painter
* &amp;lbrack;Python&amp;rbrack; Impossibile impostare l&#39;istanza padre con il tipo &quot;properties&quot;
* &amp;lbrack;Python&amp;rbrack; Se si imposta il poly alto come parametro eseguente i baking, il poly alto non viene caricato
* &amp;lbrack;Python&amp;rbrack; Messaggio di errore per set_color_space() troppo generico
* &amp;lbrack;Python&amp;rbrack; Le origini di riferimento consentono di creare cicli

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;MacOS Intel&amp;rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &amp;lbrack;Illustrator&amp;rbrack; Arresto anomalo di esportazione di una Porzione UV con grafica .ai in casi specifici
* &amp;lbrack;Tratti dinamici&amp;rbrack;&amp;lbrack;Path&amp;rbrack; Casuale per tratto non funziona su un tracciato

### 10.0.0

Data di pubblicazione: **2024/05/16** Riepilogo: **Versione principale, edizione di Pila livelli con API Python, lettura dei file nativi di Illustrator, integrazione di Risorse 3D e nuova risorsa di testo**

**Aggiunto**:

* &amp;lbrack;Illustrator&amp;rbrack; Utilizzo dei file Illustrator con le tavole da disegno in Painter
* &amp;lbrack;Illustrator&amp;rbrack;&amp;lbrack;SVG&amp;rbrack; Aggiungi anteprime nella selezione dell&#39;ambito
* &amp;lbrack;Substance 3D Assets&amp;rbrack; Sfoglia, seleziona e scarica risorse 3D direttamente in Painter
* &amp;lbrack;Substance 3D Assets&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo pannello
* &amp;lbrack;Substance 3D Assets&amp;rbrack; Supporta mappe e materiali dell&#39;ambiente
* &amp;lbrack;Substance 3D Assets&amp;rbrack; Consenti di ricaricare, spostarsi e aprire la cartella della posizione nel nuovo pannello Substance 3D Assets
* &amp;lbrack;Substance 3D Assets&amp;rbrack; aggiunta di un gestore di download
* &amp;laback;Text Resource&amp;brack; Consenti l&#39;utilizzo di font incorporabili
* &amp;blocco;Risorsa di testo&amp;rbrack; Consenti il rendering di un font/testo su una trama
* &amp;lbrack;Text Resource&amp;rbrack; visualizza i font dell&#39;utente e di altri tracciati condivisi nel pannello Risorse con una nuova categoria
* &amp;lbrack;Text Resource&amp;rbrack;&amp;lbrack;Properties&amp;rbrack; Aggiungi il supporto per le proprietà avanzate dei font
* &amp;lbrack;Text Resource&amp;rbrack; Consenti di cercare/visualizzare i font nei mini-scaffali
* &amp;lbrack;Text Resource&amp;rbrack; Aggiungi messaggio/finestra di dialogo di errore durante l&#39;importazione di un font incompatibile
* Varie
* &amp;lbrack;Riempi proiezione&amp;rbrack; Migliora il comportamento del manipolatore Scala quando si utilizzano valori di piccole dimensioni
* &amp;lbrack;Manipolatori&amp;rbrack; Aggiungi nuova modalità precisa quando si preme la scelta rapida da tastiera CTRL
* &amp;lbrack;Manipolatore&amp;rbrack; Migliora la stabilità del manipolatore di superfici durante la traduzione
* &amp;lbrack;Export&amp;rbrack; Aggiungi nome spazio colore negli output SBSAR
* &amp;lbrack;Prestazioni&amp;rbrack; Migliora il tempo di individuazione delle librerie delle risorse su disco
* &amp;lbrack;Substance&amp;rbrack; aggiornamento al motore di Substance versione 9.1.2
* &amp;lbrack;Drag and Drop&amp;brack; Allinea la rotazione della decalcomania alla videocamera quando viene rilasciata nella finestra della vista
* &amp;lbrack;Python&amp;rbrack; edizione della Pila livelli
* &amp;lbrack;Python&amp;rbrack; Consenti di selezionare livello, effetto, maschera, maschera geografica nell&#39;interfaccia utente
* &amp;lbrack;Python&amp;rbrack; Consenti di ottenere/impostare i metodi di fusione dei livelli
* &amp;lbrack;Python&amp;rbrack; Consenti di ottenere/impostare le impostazioni di proiezione del livello di riempimento
* &amp;lbrack;Python&amp;rbrack; Consenti di eseguire query sul colore del materiale della Substance da un livello di riempimento
* &amp;lbrack;Python&amp;rbrack; Consenti di eseguire query e impostare colori uniformi e risorse in livelli ed effetti
* &amp;lbrack;Python&amp;rbrack; Consenti di creare e modificare risorse di testo in Pila livelli
* &amp;lbrack;Python&amp;rbrack; Consente di modificare i canali attivi su livelli ed effetti
* &amp;lbrack;Python&amp;rbrack; Consenti alle azioni in batch di avere un singolo annullamento/ripetizione
* &amp;lbrack;Python&amp;rbrack; consente di caricare/modificare i parametri di origine vettoriale
* &amp;lbrack;Python&amp;rbrack; Consente di modificare le proprietà dei colori dei livelli e degli effetti con la gestione del colore
* &amp;lbrack;Python&amp;rbrack; Consenti di eseguire query e creare livelli istanziati
* &amp;lbrack;Python&amp;rbrack; Consenti di aggiungere l&#39;effetto di selezione colore
* &amp;lbrack;Python&amp;rbrack; Consenti di controllare la gestione del colore dell&#39;immagine bitmap
* &amp;lbrack;Python&amp;rbrack; consente di mettere in pausa/rimettere in pausa il motore
* &amp;lbrack;Python&amp;rbrack; Consenti di passare ai nodi di pari livello e padre
* &amp;lbrack;Python&amp;rbrack; Consente di creare un effetto filtro/generatore
* &amp;lbrack;Python&amp;rbrack; Consenti di aggiungere effetto livello
* &amp;lbrack;Python&amp;rbrack; Consenti di aggiungere maschera avanzata a un livello
* &amp;lbrack;Python&amp;rbrack; consente di creare/modificare punti di ancoraggio
* &amp;lbrack;Python&amp;rbrack; Consenti di ottenere/impostare la maschera sui livelli
* &amp;lbrack;Python&amp;rbrack; Consente di creare un effetto maschera di confronto
* &amp;lbrack;Python&amp;rbrack; Consenti di eseguire query e utilizzare i predefiniti dalle risorse Substance
* &amp;lbrack;Python&amp;rbrack; Consenti di elencare i predefiniti e i relativi valori tramite la funzione internal_properties per le risorse Substance
* &amp;lbrack;Python&amp;rbrack; Consenti di elencare i predefiniti di esportazione predefiniti
* &amp;lbrack;Python&amp;rbrack; Consenti di elencare i predefiniti di esportazione disponibili nella libreria
* &amp;lbrack;Python&amp;rbrack; Consente di recuperare il contenuto dei predefiniti di esportazione

**Risolto**:

* &amp;lbrack;Arresto anomalo&amp;rbrack; annullamento di &quot;Rimuovi istanza shader&quot; con Ctrl-Z
* &amp;lbrack;Arresto anomalo&amp;rbrack; Crea un livello su una pila vuota se l&#39;ultima selezione era un effetto
* &amp;lbrack;SVG&amp;rbrack; Problema con il valore personalizzato dell&#39;area ritagliata
* &amp;lbrack;Srotolamento automatico&amp;rbrack; se si ricalcola solo l&#39;impacchettamento senza modificare l&#39;orientamento UV, si verifica l&#39;arresto anomalo
* &amp;lbrack;Drag&amp;drop&amp;brack; Il ritardo dovuto alle risorse esterne viene precaricato più volte
* &amp;lbrack;UI&amp;rbrack; se si trascina la miniatura della risorsa, il messaggio di avviso nella Pila livelli può essere nascosto
* &amp;lbrack;Performance&amp;brack; I riquadri UV mascherati sono ancora calcolati
* &amp;lbrack;USD&amp;rbrack; Evidenziazione errata per selezione ambito
* &amp;lbrack;Risorsa&amp;rbrack; L&#39;immagine bitmap viene danneggiata dopo aver colorato nel canale normale e salvato il progetto
* &amp;lbrack;USD&amp;rbrack; supporta l&#39;ordinamento dei vertici mancini
* &amp;lbrack;Substance&amp;rbrack; Ripristina valori predefiniti torna sempre a zero per il widget Angolo
* &amp;lbrack;Engine&amp;rbrack; Colorare con un SVG in uno stencil non funziona
* &amp;lbrack;Motore&amp;rbrack; Mappa normale interruzione tratti pennello dopo un annullamento
* &amp;lbrack;Content&amp;rbrack; La fusione alfa e lo spazio cromatico dell&#39;elemento grafico nel Filtro materiale non sono corretti
* &amp;lbrack;Content&amp;rbrack; I metodi di fusione sul Tile Generator non funzionano
* &amp;lbrack;Content&amp;rbrack; Il filtro di scansione Istogramma produce in alcuni casi bande
* &amp;lbrack;Content&amp;rbrack; illuminazione Eseguita i baking stilizzata non tiene conto del height dipinto
* &amp;lbrack;Python&amp;rbrack; errore imprevisto durante il recupero delle informazioni sui livelli istanziati dopo la modifica dello shader
* &amp;lbrack;Salva&amp;rbrack; Il file di progetto viene perso quando &quot;salva con nome&quot; non riesce in casi specifici

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Linux&amp;rbrack;&amp;lbrack;AMD&amp;rbrack; Trascinamento delle risorse in Pila livelli su Wayland OS
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent
* &amp;lbrack;Save&amp;rbrack; Il file di progetto Spp viene perso quando l&#39;operazione &quot;Salva come copia&quot; non riesce in casi specifici
* &amp;lbrack;MacOS Intel&amp;rbrack; Arresto anomalo durante l&#39;importazione di alcuni predefiniti
* &amp;lbrack;Illustrator&amp;rbrack; Impossibile importare i file Ai dopo l&#39;arresto anomalo del server senza riavviare Painter
* &amp;lbrack;Import&amp;rbrack; Risorse con lo stesso nome ma estensioni diverse vengono sostituite

## Versione 9

### 9.1.2

Data di pubblicazione: **2024/01/30** Riepilogo: **Versione secondaria, correzioni di bug**

**Aggiunto**:

* &amp;lbrack;Prestazioni&amp;rbrack; Migliora il tempo di creazione del primo livello di riempimento nei nuovi progetti
* &amp;lbrack;Performance&amp;rbrack; Riduci il tempo di caricamento di mappe dell&#39;ambiente pesanti
* &amp;lbrack;Substance&amp;rbrack; consente di salvare/chiudere i progetti anche quando vengono generate miniature

**Risolto**:

* Il salvataggio non riesce sui progetti della versione precedente quando la finestra della vista viene modificata
* &amp;lbrack;Arresto anomalo&amp;rbrack; reimportazione della trama quando si utilizza la gestione personalizzata degli oggetti AO e del colore
* &amp;lbrack;Riempi proiezione&amp;rbrack; Facendo clic sul manipolatore Scala viene visualizzato il messaggio &quot;non colorabile&quot;
* &amp;lbrack;Brush&amp;brack; se si utilizza l&#39;allineamento UV si verificano artefatti
* &amp;lbrack;Pila livelli&amp;rbrack; La ridenominazione del livello è lenta quando la pila è molto lunga
* &amp;lbrack;Pila livelli&amp;rbrack; Messaggio di errore non corretto quando si utilizza un filtro incompatibile nella maschera
* &amp;lbrack;Pila livelli&amp;rbrack; dopo l&#39;eliminazione, la selezione torna al livello superiore
* &amp;lbrack;Export&amp;rbrack; La texture normale generata è sempre in modalità di riempimento Vicina spazio 3D
* &amp;lbrack;Esporta&amp;rbrack; Texture alfa non viene generato con il predefinito di esportazione vista 2D
* &amp;lbrack;Export&amp;rbrack; L&#39;esportazione SBSAR presenta utilizzi errati con mappe convertite
* &amp;lbrack;Shader&amp;rbrack; Il registro modifiche API shader non è aggiornato con le ultime modifiche ASM

**Problemi noti**:

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Linux&amp;rbrack;&amp;lbrack;AMD&amp;rbrack; Trascinamento delle risorse in Pila livelli su Wayland OS
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sugli schermi HD
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Python&amp;rbrack; esportazione USD attivata da TextureStateEvent

### 9.1.1

Data di pubblicazione: **2023/12/05** Riepilogo: **Versione secondaria, correzioni di bug e invio alla funzionalità After Effects**

**Aggiunto:**

* &amp;lbrack;Interop&amp;rbrack; Consenti di inviare una trama con texture ad After Effects (Ae 24.1)

**Corretto:**

* &amp;lbrack;Fill&amp;rbrack; UV impostato sulla proiezione del set UV non legge più di 2 set UV
* &amp;lbrack;Arresto anomalo&amp;rbrack; Utilizzo della mappa dell&#39;ambiente a 16 K
* &amp;lbrack;Arresto anomalo&amp;rbrack; Exr utilizzato come input dell&#39;immagine
* &amp;lbrack;Arresto anomalo&amp;rbrack; Copia e incolla percorsi tra progetti
* &amp;lbrack;QoL&amp;rbrack; con trascinamento della risorsa Alpha in modalità decalcomania si crea Proiezione UV nella maschera
* &amp;lbrack;Path&amp;rbrack; La copia dei vertici dei tracciati rinomina anche il tracciato di destinazione alla riapertura del progetto
* &amp;lbrack;Linux&amp;rbrack; La selezione del colore può essere interrotta con più schermate
* &amp;lbrack;Auto Unwrap&amp;rbrack; problema dell&#39;interfaccia utente per il controllo della densità del testo
* &amp;lbrack;Color Management&amp;rbrack; Il feedback dell&#39;interfaccia utente è appropriato per le esigenze, ma il motore non lo è
* &amp;lbrack;Gestione colore&amp;rbrack; selezione errata dello spazio colore nella maschera con override dei dati utente

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Linux&amp;rbrack; con Linux Wayland su AMD quando si trascina e si rilascia la risorsa nella Pila livelli
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Mac&amp;rbrack; Modifica del valore di filtro anisotropo nel sistema operativo Monterey
* &amp;lbrack;Regressione&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sullo schermo hd
* &amp;lbrack;Python&amp;rbrack; Arresto anomalo di esportazione dell&#39;USD attivata da TextureStateEvent

### 9.1.0

Data di pubblicazione: **2023/11/07** Riepilogo: **Versione principale che introduce il supporto per SVG e trasparenza, oltre a miglioramenti dello strumento di trascinamento della selezione**

**Aggiunto:**

* &amp;lbrack;SVG&amp;rbrack; Consenti importazione file vettoriali (SVG)
* &amp;lbrack;SVG&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Aggiungi il supporto per le proprietà specifiche dei SVG
* &amp;lbrack;SVG&amp;rbrack; Aggiungi un&#39;opzione per mantenere facilmente le proporzioni originali dell&#39;immagine
* &amp;lbrack;SVG&amp;rbrack; Consenti l&#39;utilizzo automatico dell&#39;alfa di SVG con trasparenza
* &amp;lbrack;Interop&amp;rbrack; Consenti di inviare una trama con texture ad After Effects (Ae 24.1 beta)
* &amp;lbrack;Interop&amp;rbrack; Aggiungi impostazioni per Invia a After Effects
* &amp;lbrack;QoL&amp;rbrack;&amp;lbrack;Assets&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Importa automaticamente risorsa durante il trascinamento nello slot dell&#39;interfaccia utente
* &amp;lbrack;QoL&amp;rbrack; Consenti di trascinare e rilasciare risorse esterne nella Pila livelli
* &amp;lbrack;QoL&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Trascina la texture dal pannello Risorse alla Pila livelli
* &amp;lbrack;QoL&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Consente di trascinare e rilasciare il generatore, filtri sulla trama
* &amp;lbrack;QoL&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Consenti di rilasciare le risorse esterne nella trama
* &amp;lbrack;QoL&amp;rbrack;&amp;lbrack;Projection&amp;rbrack; Aggiungi un nuovo set UV alla modalità di proiezione con impostazione UV
* &amp;lbrack;QoL&amp;rbrack; Trascina la Maschera avanzata come nuovi livelli nella finestra della vista e nella Pila livelli
* &amp;lbrack;QoL&amp;rbrack; Aggiungi selettore per i generatori con più output quando utilizzati nella maschera
* &amp;lbrack;QoL&amp;rbrack; Consente di trascinare e rilasciare immagini di un singolo canale su un effetto di riempimento
* &amp;lbrack;QoL&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Utilizzare i modificatori CTRL/ALT con trascinamento per specificare dove/come creare effetti/livello
* &amp;blocco;Tracciato&amp;rbrack; Attiva/disattiva la visibilità dei tracciati singolarmente nel pannello Tracciato
* &amp;lbrack;Path&amp;rbrack; Consenti l&#39;utilizzo di manipolatori di trasformazione per i punti di tracciato
* &amp;lbrack;Path&amp;rbrack; Consenti di controllare manualmente le tangenti per vertice
* &amp;blocca;Tracciato&amp;rbrack; copia/incolla proprietà tracciato
* &amp;lbrack;Path&amp;rbrack; Introduce una scelta rapida da tastiera vuota per il pulsante Tangente di interruzione
* &amp;lbrack;Shader&amp;rbrack; Aggiungi il supporto per Opacità e Traslucidità in shader ASM
* &amp;lbrack;Shader&amp;rbrack; Aggiungi supporto per il canale di Colore di assorbimento con shader ASM
* &amp;lbrack;Shader&amp;rbrack; suggerimenti per migliorare i parametri di shader ASM
* &amp;lbrack;Shader&amp;rbrack; Cambia il colore predefinito del canale della Traslucidità in nero
* &amp;lbrack;Impostazioni di visualizzazione&amp;rbrack; Attiva Anti-alias temporale per impostazione predefinita
* &amp;lbrack;Impostazioni di visualizzazione&amp;rbrack; Attiva impostazione di dispersione sotto superficie per impostazione predefinita
* &amp;lbrack;Substance&amp;rbrack; Aggiungi il supporto per la proprietà ColorSpace dall’input/output del grafico
* &amp;lbrack;Substance&amp;rbrack; Aggiorna il motore di Substance alla versione 9.0.3
* &amp;lbrack;UI&amp;rbrack; Rendi accessibile il pulsante contestuale della barra degli strumenti anche se la finestra dell&#39;app è piccola
* &amp;lbrack;Auto Unwrap&amp;rbrack; controlla il numero di Porzione UV con densità texel
* &amp;lbrack;Eseguite i baking&amp;rbrack; Disattiva Raytracing GPU su GPU AMD per impostazione predefinita
* &amp;lbrack;Performance&amp;rbrack; Applica la compressione senza perdita di dati alle immagini a 16 bit per ridurre l&#39;ingombro del progetto
* &amp;lbrack;Python&amp;rbrack; Consente di manipolare la videocamera predefinita in vista 3D
* &amp;lbrack;Python&amp;rbrack; Esporta la possibilità di esportare trama tramite script
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Samples&amp;rbrack; Aggiungi nuovo progetto di esempio &quot;French Restaurant Table&quot;
* &amp;lbrack;Content&amp;rbrack; Aggiorna Substance logo alfa alla nuova versione
* &amp;lbrack;Content&amp;rbrack; Aggiungi tre filtri di materiale focalizzati sulle SVG (Adesivo personalizzato, Spruzzo personalizzato e Grafica su materiale)

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; modifica delle dimensioni del manipolatore quando non si utilizza lo strumento simmetria
* &amp;lbrack;Arresto anomalo&amp;rbrack; &amp;lbrack;Pila livelli&amp;rbrack; Creazione del livello quando non è selezionato nulla
* &amp;lbrack;Project&amp;rbrack; Le mappe trama possono essere danneggiate dopo la rimozione di risorse inutilizzate
* &amp;lbrack;Project&amp;rbrack; danneggiamento delle risorse dopo la reimportazione o la esegue i baking dell&#39;immagine
* &amp;lbrack;Assets&amp;rbrack; Il ricaricamento di una risorsa la rimuove dai Preferiti
* &amp;lbrack;Import&amp;rbrack; Impossibile importare risorse quando nel pannello delle risorse è presente l&#39;indicazione &quot;Nessun risultato trovato&quot;
* &amp;lbrack;UI&amp;rbrack; In alcuni casi la freccia contestuale della barra degli strumenti non viene visualizzata
* &amp;lbrack;Substance&amp;rbrack; Il pulsante affiancato per i valori booleani non è supportato
* &amp;lbrack;Level&amp;brack; etichetta di canale errata quando utilizzato nella maschera
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;glTF&amp;rbrack; i file glTF/GLB esportati da Painter non hanno un&#39;unità di dimensioni fisiche
* &amp;lbrack;Content&amp;rbrack; l&#39;intensità del filtro Sfocatura è bloccata su 16
* &amp;lbrack;Content&amp;rbrack; l&#39;input dell&#39;immagine &quot;colore di destinazione&quot; del filtro Corrispondenza colori non è visibile

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Linux&amp;rbrack; con Linux Wayland su AMD quando si trascina e si rilascia la risorsa nella Pila livelli
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Mac&amp;rbrack; Modifica del valore di filtro anisotropo nel sistema operativo Monterey
* &amp;lbrack;Arresto anomalo&amp;rbrack; Exr utilizzato come input dell&#39;immagine
* &amp;lbrack;Arresto anomalo&amp;rbrack; Utilizzo della mappa dell&#39;ambiente a 16 K
* &amp;lbrack;Auto Unwrap&amp;rbrack; problema dell&#39;interfaccia utente per il controllo della densità del testo
* &amp;lbrack;Regressione&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Il menu di scelta rapida è troppo piccolo sullo schermo hd
* &amp;lbrack;Python&amp;rbrack; Arresto anomalo di esportazione dell&#39;USD attivata da TextureStateEvent
* &amp;lbrack;QoL&amp;rbrack; con trascinamento della risorsa Alpha in modalità decalcomania si crea Proiezione UV nella maschera

### 9.0.1

Data di pubblicazione: **2023/09/19** Riepilogo: **Versione del bug minore con diversi miglioramenti**

**Aggiunto:**

* &amp;lbrack;Import&amp;rbrack; Imposta posizione di importazione predefinita nella finestra di importazione
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Consenti di ripristinare i parametri ai valori predefiniti
* &amp;lbrack;Esegui i baking&amp;rbrack; Imposta la risoluzione della esegue i baking su pittura durante la creazione di un progetto
* &amp;lbrack;Simmetrie&amp;rbrack; Rimuovi associazione manipolatore specifico della simmetria dalla scelta rapida da tastiera Q
* &amp;lbrack;Menu&amp;rbrack; Aggiungi l’opzione &quot;mostra registro&quot; nel menu Aiuto
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Migliora la velocità di rendering delle ombre
* &amp;lbrack;Substance&amp;rbrack; Aggiorna il motore alla versione 9.0.1
* &amp;lbrack;Color Management&amp;rbrack; Il file di configurazione OCIO può avere qualsiasi tipo di estensione
* &amp;lbrack;Assets&amp;rbrack; La risorsa Sbsar con utilizzo &quot;decalcomania&quot; deve essere impostata automaticamente su altera proiezione
* &amp;lbrack;Path&amp;brack; Visualizza un messaggio quando tenti di interagire con lo strumento Tracciato mentre interfaccia utente e Gizmo sono nascosti

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; Alt + trascinamento sul pannello Tracciato
* &amp;lbrack;Importa risorse&amp;rbrack; arresto anomalo casuale durante la rimozione delle risorse da importare
* Arresto anomalo durante l&#39;importazione di un file GLB compresso
* Problema durante la pittura su trame che condividono UV
* Flash di trama nero durante il ricalcolo o il caricamento della cache
* &amp;lbrack;Proprietà&amp;rbrack; Il menu di scelta rapida per reimpostare i parametri non viene visualizzato nei menu a discesa
* &amp;lbrack;Level&amp;brack; cursori di input bloccati dal livello precedente
* &amp;lbrack;AMD&amp;rbrack;&amp;lbrack;Sparse&amp;rbrack; opzione SVT se attivata genera artefatti
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Arresto anomalo quando si fa doppio clic sui vertici
* &amp;lbrack;Path&amp;rbrack; interfaccia utente e percorso visibili in modalità di esegue i baking
* &amp;lbrack;AMD&amp;rbrack; Texture persa durante la riproduzione con visibilità
* &amp;lbrack;Sparse&amp;rbrack; Risoluzione troppo bassa quando si ruota la trama

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

### 9.0.0

Data di pubblicazione: **2023/06/20** Riepilogo: **Versione principale con Pittura lungo il percorso che consente curve 3D, nuovi materiali di base e la pulizia dei materiali legacy e nuovi predefiniti per curve 3D**

**Aggiunto:**

* &amp;lbrack;Path&amp;rbrack; Aggiungi nuova Pittura lungo il tracciato, strumento
* &amp;lbrack;Path&amp;rbrack; Aggiungi una scelta rapida da tastiera vuota per lo strumento tracciato
* &amp;lbrack;Path&amp;brack; Consenti di aggiungere nuovi punti a un percorso esistente
* &amp;lbrack;Path&amp;rbrack; Aggiungi scelta rapida da tastiera per uscire dalla creazione del percorso corrente
* &amp;lbrack;Tracciato&amp;rbrack; Consente di modificare le proprietà del pennello per i tracciati
* &amp;lbrack;Tracciato&amp;rbrack; Regola automaticamente le tangenti durante il posizionamento di un punto
* &amp;lbrack;Path&amp;brack; Ricalcola tangenti quando si sposta un punto
* &amp;lbrack;Tracciato&amp;rbrack; aggancia i punti appena creati alla superficie di una trama
* &amp;lbrack;Path&amp;rbrack; Consenti modifica pressione per vertice
* &amp;lbrack;Tracciato&amp;rbrack; Regola la pressione del punto appena creato dai punti vicini
* &amp;lbrack;Tracciato&amp;rbrack; Consenti di convertire i punti in punti morbidi/d&#39;angolo (interruzione tangente)
* &amp;blocco;Tracciato&amp;rbrack; Consenti di spostare immediatamente un punto appena aggiunto
* &amp;lbrack;Path&amp;rbrack; consente di rimuovere punti dal percorso esistente
* &amp;lbrack;Tracciato&amp;rbrack; Consenti di invertire la direzione di un tracciato
* &amp;lbrack;Path&amp;rbrack; Consenti di selezionare un percorso nella finestra della vista
* &amp;lbrack;Tracciato&amp;rbrack; Consenti di selezionare punti di tracciato con selezione
* &amp;lbrack;Tracciato&amp;rbrack; Introduce le scelte rapide CTRL-A per selezionare tutti i punti di un tracciato
* &amp;lbrack;Path&amp;rbrack; Consenti di chiudere il percorso
* &amp;lbrack;Path&amp;rbrack; Consenti di specificare l&#39;asse del tracciato in Proprietà
* &amp;lbrack;Path&amp;brack; Aggiungi un menu di controllo dei vertici alla barra degli strumenti contestuale
* &amp;lbrack;Path&amp;rbrack; Introdurre le modalità pittura/Cancella/Sfumino allo strumento tracciato
* &amp;lbrack;Path&amp;brack; Crea un feedback visivo per i tracciati nella finestra della vista
* &amp;lbrack;Path&amp;brack; Aggiungi un indicatore visivo per la direzione del tracciato
* &amp;lbrack;Path&amp;rbrack; Aggiungi thickness di linee alle impostazioni di visualizzazione del tracciato
* &amp;lbrack;Path&amp;brack; Consenti di nascondere l&#39;interfaccia utente dei percorsi
* &amp;lbrack;Path&amp;brack; Aggiungi pannello Tracciato per elencare i tracciati del livello attualmente selezionato
* &amp;blocco;Tracciato&amp;rbrack; Aggiungi feedback visivo quando si passa il cursore su un tracciato nel pannello Tracciato
* &amp;lbrack;Tracciato&amp;rbrack; Visualizza il pannello dei tracciati ogni volta che è selezionato lo strumento Tracciato
* &amp;blocco;Tracciato&amp;rbrack; consente di rinominare, eliminare, copiare, tagliare, duplicare il tracciato nel pannello Tracciato
* &amp;lbrack;Path&amp;rbrack; Visualizza il messaggio quando si tenta di interagire nella finestra della vista 2D con lo strumento Tracciato
* &amp;lbrack;Libreria&amp;rbrack; Integrazione di nuovo contenuto (strumenti e materiali di base di tracciati)
* &amp;lbrack;Tratti dinamici&amp;rbrack; Aggiungi proprietà distanza per tratti dinamici
* &amp;lbrack;Tratti dinamici&amp;rbrack; Aggiungi proprietà di dimensione e spaziatura ai tratti dinamici
* &amp;lbrack;Tratti dinamici&amp;rbrack; Aggiungi proprietà inizio/centro/fine per tratti dinamici
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Esposizione dei parametri di configurazione del progetto per il formato USD
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Esposizione dei parametri di creazione del progetto per il formato USD
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Aggiungi informazioni sul percorso del progetto all&#39;interno del file USD esportato
* &amp;lbrack;GLTF&amp;rbrack; Aggiorna texture nella libreria durante il ricaricamento di un file GLTF
* &amp;lbrack;Shader&amp;rbrack; Riduci artefatti di giuntura per Isole UV con orientamento diverso
* &amp;lbrack;Engine&amp;rbrack; Aggiornamento al motore di Substance versione 9.0

**Corretto:**

* &amp;lbrack;Import&amp;rbrack; Alcuni GLB con texture non ottengono texture in Painter
* &amp;lbrack;AMD&amp;rbrack; artefatti sui bordi per tutti i riempimenti di proiezione 3D
* &amp;lbrack;Engine&amp;rbrack; Texture interrotta quando si attiva o disattiva la visibilità del livello
* &amp;lbrack;Engine&amp;rbrack; Le Texture sono vuote in alcuni punti durante la modifica del metodo di fusione
* &amp;lbrack;Engine&amp;rbrack; Texture/Proiezione in alcuni casi è la modalità di alterazione vuota
* &amp;lbrack;Iray&amp;rbrack; Iterazione reimpostata su 0 durante il salvataggio del rendering
* &amp;lbrack;Log&amp;rbrack; messaggio di errore USD quando si esegue File > Nuovo

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Pila livelli&amp;rbrack; sorgente di input non salvata per livello

## Versione 8

### 8.3.1

Data di pubblicazione: **2023/04/27**

**Aggiunto:**

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi scelta rapida da tastiera (vuota) per mostrare/nascondere la visualizzazione della finestra della vista
* &amp;lbrack;Modalità Eseguita i baking&amp;rbrack; Mostra sempre Low Poly quando si utilizza il pulsante &quot;Nascondi trame eseguite i baking&quot;
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Mostra suffisso per corrispondenza per nome in base al set di texture corrente
* &amp;lbrack;Import&amp;rbrack; Aggiungi supporto per file binari GLTF (glb)
* &amp;lbrack;Elenco set di texture&amp;rbrack; Aggiungi menu per selezionare o creare istanze shader
* &amp;lbrack;Elenco set di texture&amp;rbrack; consente di modificare rapidamente il set di texture e la risoluzione delle Porzioni UV
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Migliora il comportamento del manipolatore quando si utilizza dimensioni fisiche in Proiezione UV
* &amp;lbrack;UI&amp;rbrack; Ripristina &quot;Salva con nome&quot; nel menu File principale
* &amp;lbrack;UI&amp;rbrack; Salva selezione visualizzazione (solo 2D, solo 3D, entrambi) nel layout dell&#39;interfaccia utente
* &amp;lbrack;USD&amp;rbrack; Messaggio di errore meno vago durante la creazione del progetto con forme USD non supportate
* &amp;lbrack;Python&amp;rbrack; Aggiungi eventi di eseguita i baking per seguire l&#39;avanzamento della Esegue i baking
* &amp;lbrack;Python&amp;rbrack; Consenti di annullare un eseguo i baking
* &amp;lbrack;Python&amp;rbrack; Esposizione &quot;In base al modello di output&quot; per Tipo di file e Profondità di bit nell&#39;esportazione
* &amp;lbrack;Python&amp;rbrack; tempo di aggiornamento espositivo per TextureStateEvent.Update

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; arresto anomalo raro alla chiusura di un progetto
* &amp;lbrack;Arresto anomalo&amp;rbrack; &amp;lbrack;Esegui i baking&amp;rbrack; Attiva la sincronizzazione della mappa trama con il Height o la curvatura in un progetto specifico
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Scripting&amp;rbrack; Arresto anomalo durante l&#39;aggiunta di un materiale dopo la creazione dell&#39;istanza shader
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; L&#39;intensità di AO nel materiale neutro non ha effetto
* &amp;lbrack;Modalità Esegue i baking&amp;rbrack; Arresto anomalo quando si passa alla modalità esegue i baking prima che il modello venga caricato
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Messaggio di errore mancante nella scheda Esegue i baking processo
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; le impostazioni dei materiali neutri non hanno effetto dopo la reimportazione di una trama
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; il separatore del riquadro di visualizzazione viene salvato globalmente e non per modalità
* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Problema di visualizzazione: la normale media non modifica la superficie della gabbia
* &amp;lbrack;Color Management&amp;rbrack; l&#39;impostazione Rileva automaticamente spazio colore è disattivata quando è presente OCIO env var
* &amp;lbrack;Content&amp;rbrack; Il filtro Contorno maschera ha un artefatto con input height
* &amp;lbrack;Content&amp;rbrack; il cursore intensità filtro sfocatura Pendenza è bloccato su 1,0
* &amp;lbrack;Interop&amp;rbrack; impossibile creare il progetto con GLTF da Sampler
* &amp;lbrack;Pila livelli&amp;rbrack; Il valore dell&#39;Affiancamento di proiezione non viene aggiornato correttamente con manipolatore
* &amp;lbrack;Linux&amp;rbrack; scostamento tra la penna grafica del tablet e il cursore con HDPI superiore al 100%
* &amp;lbrack;Python&amp;rbrack; Arresto anomalo durante la reimportazione di una trama dopo la creazione di un progetto
* &amp;lbrack;Substance&amp;rbrack; i rumori 3D vengono interrotti dopo la reimportazione di una trama
* &amp;lbrack;Porzione UV&amp;rbrack; L&#39;offset per la Proiezione UV è bloccato su 1
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Il feedback visivo delle linee rette non è più visibile
* &amp;lbrack;WhatsNew&amp;rbrack; restituzione di riga non corretta per i titoli delle caratteristiche

**Problemi noti:**

* &amp;lbrack;Import&amp;rbrack; Alcuni GLB con texture non ottengono texture in Painter

### 8.3.0

*(Rilasciato: 10 gennaio 2023*)Riepilogo: **Versione principale con nuova modalità di esegue i baking, nuova importazione ed esportazione di file USD e supporto di dimensioni fisiche per Proiezione UV**

**Aggiunto:**

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Nuova modalità di esegue i baking dedicata alla esegue i baking

* &amp;lbrack;Modalità Eseguita i baking&amp;rbrack; Imposta la scelta rapida da tastiera per passare alla modalità eseguita i baking su F8

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; pulsante Aggiungi inizio e Annulla esegue i baking nella finestra della vista

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi selezione eseguita i baking nell&#39;elenco Set di texture

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi nuova finestra Baker mappa trama per selezionare i baker

* &amp;lbrack;Modalità Esegue i baking&amp;rbrack; Aggiungi nuova finestra Impostazioni mappa trama per modificare le impostazioni di esegue i baking

* &amp;lbrack;Modalità Esegue i baking&amp;rbrack; Aggiungi nuova finestra Registro Esegue i baking per seguire la procedura di esegue i baking

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi parametri di esegue i baking e annulla azioni alla finestra della cronologia

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi breadcrumbs nelle impostazioni della mappa trama

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi miniature di mappe trama nella finestra Baker mappe trama

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi impostazioni di visualizzazione menu comprimibile nella finestra della vista 3D

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama High-Poly

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama della gabbia e il wireframe

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama a basso poli

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi impostazione di visualizzazione per mostrare i bordi netti senza giunture UV come errori

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; informa nella finestra della vista della trama e esegue i baking gli errori se Esegue i baking registro non è visibile

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi azione per sincronizzare le impostazioni del baker tra tutti i set di texture

  Nella finestra Baker mappa trama, è possibile sincronizzare ciascun baker (e le impostazioni comuni) tra set di texture facendo clic sull’icona di collegamento accanto al nome del gruppo. Questa azione consente di aprire una finestra che consente di selezionare quali set di texture condivideranno gli stessi parametri.

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi azioni per copiare e incollare le impostazioni del baker

  Nella finestra Baker mappa trama sono disponibili le azioni per copiare e superare le impostazioni di ciascun baker nei set di texture, tramite il menu dedicato nella parte superiore della finestra o il menu di scelta rapida (clic con il pulsante destro del mouse).

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Pulsante Aggiungi in Esegue i baking registro per passare da un errore alle impostazioni corrette

  Quando un baker si guasta o una trama non viene caricata correttamente, nel Registro di Esegue i baking viene visualizzato un messaggio di errore. Un pulsante accanto al messaggio consente di modificare la finestra Baker mappa trama e Impostazioni mappa trama per visualizzare le relative impostazioni. In questo modo è possibile isolare più facilmente la fonte di un problema per poterlo risolvere.

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi menu per gestire set di texture e selezioni di Baker

  Sia nella finestra &quot;Elenco set texture&quot; che nella finestra &quot;Baker mappa trama&quot; sono stati aggiunti un piccolo menu di azioni che consente di copiare e invertire le selezioni.

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Dividi elenco selezioni baker per set di texture

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Dividi le impostazioni comuni per set di texture

* &amp;lbrack;modalità di Esegue i baking&amp;rbrack; Carica mesh di poligoni alti e gabbia senza bloccare l&#39;interfaccia

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Utilizzare la barra di avanzamento della finestra della vista per visualizzare il caricamento della trama

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Aggiungi stato di caricamento mesh nel registro di Esegue i baking

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Consenti di ruotare la trama nella finestra della vista durante la esegue i baking

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Imposta l&#39;ordine di esegue i baking in base alla visibilità della finestra della vista della trama corrente

* &amp;lbrack;Modalità Esegue i baking&amp;rbrack; Visualizza gabbia eseguita i baking implicita nella finestra della vista

  Quando non si utilizza un file di mesh di gabbia personalizzato, viene generata e visualizzata una mesh di gabbia automatica nella finestra della vista. Le sue dimensioni si basano sul parametro Distanza frontale massima dalle impostazioni comuni eseguite i baking. La maglia della gabbia viene utilizzata per indicare la distanza di corrispondenza tra il poly basso e alto.

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Mostra elenco corrispondente di nomi di trama per corrispondenza per nome nel registro di Esegue i baking

* &amp;lbrack;Modalità Esegue i baking&amp;rbrack; Usa materiale neutro per visualizzare il modello 3D nella finestra della vista

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Disattiva il calcolo del motore in modalità di esegue i baking

* &amp;lbrack;Modalità di Esegue i baking&amp;rbrack; Visualizza un avviso quando si esce dall&#39;app mentre è in corso un eseguo i baking

* &amp;lbrack;Baker&amp;rbrack; aggiornare le etichette delle impostazioni di antialiasing

  I valori delle impostazioni di antialiasing sono stati rinominati &quot;Supersampling&quot; e con un numero moltiplicatore esplicito per chiarirne il comportamento.

* &amp;lbrack;Baker&amp;rbrack; Aggiorna i baker alla versione 2.5.7.

* &amp;lbrack;USD&amp;rbrack; Importa ed esporta file di Universal Scene Description (USD)

* &amp;lbrack;USD&amp;rbrack; Aggiungere le opzioni USD alla finestra Nuovo progetto quando si seleziona un file USD

* &amp;lbrack;USD&amp;rbrack; Aggiungi nuova finestra di selezione Ambito e Varianti

  Quando si importa un file USD, facendo clic sul pulsante di modifica nella finestra Nuovo progetto o Configurazione progetto è possibile selezionare la parte e le varianti di un file USD da importare.

* &amp;lbrack;USD&amp;rbrack; Aggiungi livelli di suddivisioni, opzione

  Quando si crea un nuovo progetto con un file mesh USD che contiene suddivisioni, è possibile selezionare il livello di suddivisioni utilizzando un cursore. Il progetto verrà creato con la trama suddivisa. Il livello può essere modificatore tramite Configurazione progetto.

* &amp;lbrack;USD&amp;rbrack; Importa mesh con skin USD in un fotogramma specifico

  Quando si crea un nuovo progetto con un file mesh USD che contiene animazioni, è possibile selezionare il fotogramma utilizzando un cursore che riflette la sequenza temporale incorporata. Il fotogramma può essere modificatore tramite Configurazione progetto.

* &amp;lbrack;USD&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Aggiungi un&#39;opzione per esportare i file USD

  Nuova casella di controllo Esporta USD aggiunta alla finestra Esporta texture. Quando è selezionato, consente di esportare file USD e mappe texture utilizzando qualsiasi modello.

* &amp;lbrack;USD&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Aggiungere il formato di file USD all&#39;esportazione mesh

* &amp;lbrack;USD&amp;rbrack; Rinomina il predefinito di esportazione &quot;Rugosità metallo USD PBR&quot; esistente in modo che sia più esplicito

  Il modello di esportazione USD precedentemente noto come &#39;Rugosità metallo USD PBR&#39; è ancora accessibile tramite Esporta texture > Modello di output > USDz (Apple AR).

* &amp;lbrack;Auto Unwrap&amp;rbrack; Aggiungi orientamento Blocco per impacchettamento

  Nuova opzione per lo scorrimento automatico delle impostazioni che consente di mantenere l’orientamento delle Isole UV esistenti quando si utilizza la funzione di impacchettamento. È possibile accedervi da Nuovo progetto > Opzioni Srotolamento automatico > Isola UV orientamento.

* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Aggiungi impostazione per utilizzare automaticamente la Dimensioni fisiche nell&#39;effetto/livello di riempimento

  È stata aggiunta una nuova opzione che consente di passare automaticamente alla scala dimensioni fisiche quando si utilizza un materiale con dimensioni fisiche incorporata. Può essere attivato per ogni progetto tramite Nuovo progetto o tramite Modifica > Configurazione progetto > Dimensioni fisiche > Converti il ridimensionamento del livello di riempimento in Dimensioni fisiche quando si assegnano i materiali.

* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Esposizione dimensioni fisiche per Proiezione UV

  Il ridimensionamento delle dimensioni fisiche è ora disponibile per le Proiezioni UV: consente di ridimensionare automaticamente un materiale in base alla dimensioni fisiche di una trama. Può essere selezionata da Scala > Dimensioni fisiche nel livello di riempimento o nella finestra Proprietà effetti.

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di eseguire query sulla versione dell&#39;applicazione

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; Aggiorna l’API in base ai nuovi parametri di esegue i baking

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; modulo di Esegue i baking: modifica parametri di esegue i baking

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; modulo di Esegue i baking: avvia/annulla esegue i baking

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; modulo di Esegue i baking: selezione metodo curvatura

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; modulo di Esegue i baking: selezione di baker/porzioni uv

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; modulo di Esegue i baking: sincronizzare le impostazioni del baker tra tutti i set di texture

* &amp;lbrack;SVT&amp;rbrack; abilita il supporto hardware di tipo sparse sulle GPU AMD

  L’accelerazione hardware per il sistema Sparse Virtual Textures può ora essere abilitata con le GPU AMD. Questa impostazione viene attivata automaticamente nelle preferenze generali.

* &amp;lbrack;Proiezione&amp;rbrack; Rinomina i parametri della proiezione cilindrica

  Il parametro &quot;Cylinder Culling&quot; è stato rinominato &quot;Backface Culling&quot; per rappresentarne meglio l’azione. La descrizione associata è stata modificata di conseguenza.

* &amp;lbrack;Project&amp;rbrack; Salva la versione dell&#39;applicazione nel progetto e recuperala tramite script

  A partire dalla versione 8.2, la versione dell’applicazione viene ora memorizzata nel file spp durante il salvataggio. Questo numero di versione può essere recuperato con la funzione last_saved_substance_painter_version() nel modulo di progetto dell’API Python. Per i progetti realizzati prima della versione 8.2, il valore restituito sarà null.

* &amp;lbrack;Import&amp;rbrack; Migliora il tempo di importazione generale dei modelli 3D

  Abbiamo migliorato il tempo generale di importazione delle trame. Ad esempio, la riduzione del tempo di attesa durante il caricamento di trame a poli elevato per la esegue i baking. Questa ottimizzazione si applica in particolare al caricamento dei file OBJ.

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; modifica dei canali sul filtro con una pila specifica

* &amp;lbrack;Mac&amp;rbrack;&amp;lbrack;M1&amp;rbrack; Arresto anomalo durante la creazione di un livello di riempimento e l&#39;uscita dalla Pila livelli

  Questo problema può essere risolto eseguendo l’aggiornamento a Mac OS 13 (Ventura).

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Arresto anomalo quando si utilizza ui.add_dock_widget() con il tipo errato

* &amp;lbrack;Eseguite i baking&amp;rbrack; Messaggio di errore incompleto nel registro quando un eseguo i baking non riesce

* &amp;lbrack;Esegui i baking&amp;rbrack; La memoria non viene liberata al termine della esegue i baking

* &amp;lbrack;Engine&amp;rbrack; La cache della Texture non si aggiorna quando si modifica la visibilità degli effetti

* &amp;lbrack;Export&amp;rbrack; vista 2D esporta una mappa uniformata casualmente

* &amp;lbrack;Project&amp;rbrack; errore di allocazione della memoria durante il salvataggio del progetto con trama grande

* &amp;lbrack;Viewport&amp;rbrack; In alcuni casi, l&#39;accesso automatico al contenuto causa artefatti durante il disegno

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Pila livelli&amp;rbrack; sorgente di input non salvata per livello

### 8.2.0

*(Versione: 06 ottobre 2022*)Riepilogo: **Versione principale con nuovi pannelli di onboarding (nuovo pannello di benvenuto e novità), esportazione in SBSAR, effetti per la cartella, diversi miglioramenti per la qualità della vita e correzioni di bug.**

**Aggiunto:**

* &amp;lbrack;Onboarding&amp;brack; pannello Onboarding per accogliere nuovi utenti

  È stata aggiunta una nuova schermata introduttiva quando i nuovi utenti CC aprono Painter per la prima volta.

* &amp;lbrack;Onboarding&amp;rbrack; pannello Novità per migliorare la ricerca di nuove funzioni

  È stata aggiunta una nuova schermata Novità che mostra le principali nuove funzioni. Viene visualizzato automaticamente la prima volta che Painter viene aperto dopo un aggiornamento importante ed è nuovamente accessibile da Aiuto > Novità.

* &amp;lbrack;Onboarding&amp;rbrack; rinomina il vecchio benvenuto in &quot;Schermata Home&quot;

  La vecchia schermata introduttiva è stata rinominata Schermata iniziale per evitare confusione con la nuova schermata introduttiva.

* &amp;lbrack;UI&amp;rbrack; Risolvi i problemi di ridimensionamento per schermi ad alto DPI

  È stato migliorato l’adattamento dell’interfaccia utente di Painter su schermi ad alta definizione con ridimensionamento personalizzato.

* &amp;lbrack;UI&amp;rbrack; Evita messaggi di errore persistenti nell&#39;interfaccia utente

  I messaggi di errore dei progetti precedenti sono stati rimossi dalla barra di stato inferiore.

* &amp;lbrack;UI&amp;rbrack; Rielabora menu Salva

  Le opzioni di salvataggio aggiuntive sono ora raggruppate in un sottomenu e alcune sono state rinominate per coerenza.

* &amp;blocca;UI&amp;rbrack; Salva ed esporta/condividi layout interfaccia utente

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

* &amp;lbrack;Assets panel&amp;rbrack; risorse preferite del &quot;Segnaposto&quot; da visualizzare sopra il pannello delle risorse

  È stata aggiunta una nuova opzione di clic con il pulsante destro del mouse sulle risorse della libreria che consente di raggrupparle come segnaposti preferiti nella parte superiore del pannello. Puoi anche visualizzare tutte le tue risorse preferite tramite Ricerche salvate.

* &amp;lbrack;Pannello Risorse; Elimina, ricarica e rinomina le risorse

  Sono state aggiunte le opzioni del menu di scelta rapida per eliminare, ricaricare e rinominare le risorse nella libreria utente. Vengono eliminati direttamente dal percorso della libreria sul disco e ricaricati dal percorso originale. Le risorse che fanno parte di un pacchetto come .abr o .sbsar non possono essere modificate singolarmente.

* &amp;lbrack;Color Selection&amp;rbrack; Aggiungi metodi di fusione all&#39;effetto Selezione colore

* &amp;lbrack;Pila livelli&amp;rbrack; Aggiungi metodo di fusione e opacità sui filtri

* &amp;lbrack;Pila livelli&amp;rbrack; Consenti valori Affiancamenti maggiori di 128 per livello di riempimento/effetti

* &amp;lbrack;Pila livelli&amp;rbrack; tappi cilindrici per la proiezione cilindrica nel livello/effetto di riempimento

  La proiezione cilindrica nelle proprietà del livello Riempimento ora ha l&#39;opzione per rimuovere le estremità dei cilindri.

* &amp;lbrack;Log&amp;rbrack; Mostra un messaggio di errore se la parte mesh si trova in uno spazio negativo durante il tentativo di creazione di un progetto Porzione UV

  È stato aggiunto un messaggio di errore più chiaro quando non si crea un progetto di Porzione UV perché le parti UV vengono trovate in spazi negativi.

* &amp;lbrack;Project&amp;rbrack; indica la versione nel messaggio di errore &quot;dati troppo recenti&quot; durante l&#39;apertura di un progetto

  Quando si apre un progetto troppo recente per l’applicazione, il messaggio di errore indica ora la versione del progetto per facilitare l’identificazione della versione corretta dell’applicazione.

* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Consenti di illuminare la trama da sotto

  È stato aggiunto un nuovo parametro di Allineamento ambiente in Impostazioni visualizzazione > Fotocamera > Impostazioni ambiente per allineare l’illuminazione della mappa ambiente alla videocamera quando è impostata su &quot;Locale&quot;.

* &amp;lbrack;Viewport&amp;rbrack; Visualizza R, G, B e Alpha nella finestra della vista (modalità visualizzazione solo)

  In Impostazioni schermo > Impostazioni finestra vista > Visualizzazione canali è disponibile una nuova impostazione Canali colore che consente di visualizzare solo il componente R, G, B o Alpha di un canale quando è attiva la modalità di visualizzazione singola.

* &amp;lbrack;Shader&amp;rbrack; Consenti di impostare i canali utente come RGBA nei livelli di materiale

  Quando si imposta la configurazione dei canali dell’insieme di texture all’interno di uno shader per la creazione di livelli di materiale, è ora possibile specificare il formato del canale da deviare dal valore di default. In particolare, è possibile richiedere canali utente a colori invece che solo in scala di grigi.

* &amp;lbrack;Esporta&amp;rbrack; consente di esportare texture come SBSAR

  Quando si esporta una texture tramite la finestra File > Esporta Texture, si può scegliere il formato di file SBSAR (Substance Archivio) per raggrupparla. Il contenuto del SBSAR dipende dal modello di output utilizzato. Il formato del file SBSAR può essere impostato anche nei predefiniti di esportazione. Quando si utilizza la configurazione ibrida (SBSAR + Altro formato), le texture che hanno come destinazione un SBSAR vengono raggruppate mentre le altre vengono esportate insieme.

* &amp;lbrack;Export&amp;rbrack; Exposé 16bit, opzione per il formato di file EXR

  Quando si esportano file di texture EXR, ora è possibile scegliere tra 16f bit (Mezza Virgola mobile) o 32f bit (Virgola mobile) nella finestra Esporta Texture (sia per le impostazioni di esportazione che per i predefiniti di esportazione). I vecchi progetti e i vecchi predefiniti di esportazione verranno impostati per impostazione predefinita su 16 f bit per riflettere il vecchio comportamento.

* &amp;lbrack;Python&amp;rbrack; Aggiungi evento per sapere quando modificare i set di texture

  Il nuovo &quot;substance_painter.event.TextureStateEvent&quot; consente di sapere quando un insieme di texture è stato modificato a causa di un tratto pittura, di un nuovo canale aggiunto o di un canale rimosso.

* &amp;lbrack;Python&amp;rbrack; Consenti di ottenere e impostare le risorse Mesh Map nelle impostazioni del set di texture

  Nel modulo &quot;substance_painter.project&quot; sono state aggiunte nuove funzioni per ottenere e impostare le risorse delle mappe mesh. Queste funzioni possono essere utilizzate per aggiornare le mappe di trama a cui fanno riferimento le impostazioni del set di texture.

* &amp;lbrack;Plugin&amp;rbrack; Rimuovi l&#39;opzione per ottenere altri plug-in JS

  È stata rimossa l’opzione per ottenere i plug-in JavaScript poiché erano ospitati nel sito Web di condivisione obsoleto.

* &amp;blocco;Content&amp;rbrack; Aggiungi nuovo modello Roblox ed esporta predefinito

  Sono stati aggiunti un nuovo modello di progetto Roblox &quot;Material Variant&quot; e &quot;Surface Appearance&quot; e un predefinito di esportazione per facilitare l’esportazione di texture PBR in Roblox. È possibile accedere al modello dalla finestra File > Nuovo progetto.

* Aggiornamento della Substance Engine alla versione più recente (8.6.3)

* &amp;lbrack;Steam&amp;rbrack; build ottimizzata per chipset Apple Silicon (Apple M1 / M2)

**Corretto:**

* Arresto anomalo quando si utilizza exr 16k

* &amp;lbrack;Arresto anomalo&amp;rbrack; Ctrl Z Dopo l&#39;eliminazione di un&#39;istanza shader

* &amp;lbrack;Iray&amp;rbrack; IoR è bloccato su 1 per alcuni shader

* &amp;lbrack;Win&amp;rbrack;&amp;lbrack;Esegui i baking&amp;rbrack; Alcuni alti poli non vengono caricati

* &amp;lbrack;Gestione colore&amp;rbrack; nome dello spazio colore non corretto nell&#39;interfaccia utente con filtri

* &amp;lbrack;Python&amp;rbrack; Gli oggetti risorsa restituiti dalla funzione di importazione non hanno un tipo

  Quando si importava un pacchetto di Substance in Python, la funzione restituiva il pacchetto invece dei relativi grafici. Il modulo delle risorse ora fornisce funzioni e parametri per recuperare i grafici di un pacchetto di Substance.

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Pila livelli&amp;rbrack; sorgente di input non salvata per livello
* &amp;lbrack;Painting&amp;rbrack; L&#39;antialiasing temporale causa artefatti quando si disegna in alcuni casi
* &amp;lbrack;Export&amp;rbrack; vista 2D esporta una mappa uniformata casualmente

### 8.1.3

*(Rilasciato: 25 agosto 2022*)Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

* Aggiornamento a Iray SDK 1.6

**Corretto:**

* &amp;lbrack;Shader&amp;rbrack; Arresto anomalo con vecchio shader difettoso
* &amp;lbrack;Material Layering&amp;brack; I materiali possono scomparire quando si riapre un progetto

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Pila livelli&amp;rbrack; sorgente di input non salvata per livello
* &amp;lbrack;Arresto anomalo&amp;rbrack; Ctrl Z Dopo l&#39;eliminazione di un&#39;istanza shader
* &amp;lbrack;Iray&amp;rbrack; IoR è bloccato su 1 per alcuni shader

### 8.1.2

*(Rilasciato: 19 luglio 2022*)Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

* &amp;lbrack;Auto Unwrap&amp;rbrack; Nuova opzione &quot;Ottimizza per trame organiche&quot; per selezionare l&#39;algoritmo di segmentazione
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Esposizione delle opzioni delle unità in Nuovo progetto e Configurazione progetto
* &amp;lbrack;Color Management&amp;rbrack; Usa visualizzazione monitor per impostazione predefinita quando si utilizza ACE
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Durante la creazione del progetto, tenere conto del file predefinito ACE env-var
* &amp;lbrack;Color Management&amp;rbrack; Reimposta le impostazioni di Color Management nella finestra Nuovo progetto quando la configurazione cambia
* &amp;lbrack;Gestione colore&amp;rbrack; Disattiva accesso alle impostazioni OCIO in presenza di env-var
* &amp;lbrack;Color Management&amp;rbrack; aggiorna in modo sicuro le impostazioni ACE quando un parametro non esiste più
* Aggiornamento della Substance Engine alla versione 8.6.0
* &amp;lbrack;Export&amp;rbrack; Aggiungi nuovo predefinito di esportazione GLTF con supporto Spostamento
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Recupero delle informazioni sulle risorse (inclusi i metadati personalizzati)
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Aggiungi funzione all&#39;elenco di query dei nomi di trama per set di texture
* &amp;lbrack;Content&amp;rbrack; Aggiungi nuovo modello di fusione ed esporta predefinito

**Corretto:**

* &amp;lbrack;MacOS&amp;rbrack; Arresto anomalo all&#39;avvio di Iray in alcuni casi
* &amp;lbrack;Thumbnails&amp;rbrack; Le miniature dello shelf non vengono caricate correttamente
* Più canali UV vengono ignorati
* &amp;lbrack;Auto Unwrap&amp;rbrack; calcolo non necessario durante la divisione di isole lunghe
* &amp;lbrack;Auto Unwrap&amp;rbrack; Opzione per evitare isole allungate non considerata
* &amp;lbrack;Auto Unwrap&amp;rbrack; perdita di dati aggiuntivi (colori dei vertici) durante il reinserimento degli UV
* &amp;lbrack;UI&amp;rbrack; Barra di scorrimento orizzontale nella finestra delle proprietà quando Gestione colore è attivato
* &amp;lbrack;Color Management&amp;rbrack; nelle configurazioni OCIO manca il ruolo substance_3d_painter_standard_srgb
* &amp;lbrack;Generator&amp;rbrack; Utilizzo errato dei dati utente &quot;disabilitato&quot;
* &amp;lbrack;Gestione colore&amp;rbrack; Il menu a discesa Spazio colore &quot;Non compatibile&quot; non deve essere selezionabile
* &amp;lbrack;Gestione colore&amp;rbrack;&amp;lbrack;Shader&amp;rbrack; sRGB override define non funziona più
* &amp;lbrack;Generator&amp;rbrack; Utilizzo errato dei dati utente &quot;disabilitato&quot;
* &amp;lbrack;Pila livelli&amp;rbrack; anteprime interrotte con progetti Porzioni UV
* &amp;lbrack;Shader&amp;rbrack; La documentazione delle API non è completamente aggiornata con la Normali incurvate
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Interoperability&amp;rbrack; Impossibile inviare a Stager con caratteri speciali
* &amp;blocca;Contenuto&amp;Raccoglitore; alcune miniature dei pennelli predefiniti sono vuote o troppo scure

**Problemi noti:**

* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
* &amp;lbrack;Pila livelli&amp;rbrack; La sorgente di input non viene salvata per livello
* &amp;lbrack;Arresto anomalo&amp;rbrack; Ctrl Z Dopo l&#39;eliminazione di un&#39;istanza shader
* &amp;lbrack;Iray&amp;rbrack; IoR è bloccato su 1 per alcuni shader
* &amp;lbrack;Shader&amp;rbrack; Arresto anomalo con vecchio shader difettoso

### 8.1.1

*(Rilasciato: 28 giugno 2022*)Riepilogo: **Hotfix per le versioni secondarie**

**Aggiunto:**

* &amp;lbrack;Pila livelli&amp;rbrack; se si fa clic su Alt sulla maschera, gli effetti non vengono più deselezionati

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack; apertura del vecchio progetto salvata in modalità di visualizzazione Solo
* &amp;lbrack;Arresto anomalo&amp;rbrack; Elimina un generatore nelle proprietà
* &amp;lbrack;Impostazioni set di texture&amp;rbrack; missaggio normale/Occlusione ambientale e height ai metodi normali non funzionano
* &amp;lbrack;Export&amp;rbrack; Esporta texture utilizzando il riempimento diffusione esegue il rendering delle mappe nere

**Problemi noti:**

* &amp;lbrack;MacOS&amp;rbrack; Arresto anomalo all&#39;avvio di Iray su Monterey
* &amp;lbrack;Anteprima miniatura&amp;rbrack; le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

### 8.1.0

*(Rilasciato il 7 giugno 2022*)Riepilogo: **Versione principale con supporto ICC, ridimensionamento del materiale in base ai dati della dimensioni fisiche, nuovi baker, miglioramenti del contagocce colore e una serie di contenuti aggiuntivi**

**Aggiunto:**

* &amp;lbrack;Color Management&amp;rbrack; Aggiungi supporto per profili ICC con Adobe Color Engine (ACE)
* &amp;lbrack;Color Management&amp;rbrack; Aggiungi il supporto per &quot;Adobe 98 RGB&quot; come spazio cromatico di lavoro per ICC
* &amp;lbrack;Color Management&amp;rbrack; Consenti di configurare le impostazioni ACE/ICC tramite un file di configurazione
* &amp;lbrack;Gestione colore&amp;rbrack; Consenti di inserire valori di colore lineari nel Selettore colore con la modalità Legacy
* &amp;lbrack;Gestione colore&amp;rbrack; Consenti di specificare il profilo colore utilizzato per la selezione del colore al di fuori dell&#39;interfaccia utente
* &amp;lbrack;Color Management&amp;rbrack; Ricorda l&#39;ultimo valore di visualizzazione scelto nella finestra della vista
* &amp;lbrack;Gestione colore&amp;rbrack;&amp;lbrack;Substance&amp;rbrack; Fare in modo che i generatori/filtri funzionino correttamente con Gestione colore
* &amp;lbrack;Gestione colore&amp;rbrack;&amp;lbrack;Substance&amp;rbrack; Aggiungi nuove parole chiave di esclusione dello spazio colore $working e $standardsrgb
* &amp;lbrack;Dimensioni fisiche&amp;rbrack;&amp;lbrack;Engine&amp;rbrack; Estrai informazioni sulla dimensioni fisiche dalla trama
* &amp;lbrack;Dimensioni fisiche&amp;rbrack;&amp;lbrack;Engine&amp;rbrack; calcolo Dimensioni fisiche
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Esporre le opzioni per l&#39;utilizzo della dimensioni fisiche nell&#39;interfaccia utente
* &amp;lbrack;Dimensioni fisiche&amp;rbrack; Aggiungi helper visivi nella finestra della vista
* &amp;lbrack;Esegui i baking&amp;rbrack; Aggiungi baker Height
* &amp;lbrack;Esegui i baking&amp;rbrack; Aggiungi baker Normali incurvate
* &amp;lbrack;Esegui i baking&amp;rbrack; Aggiungi baker opacità
* &amp;lbrack;Contagocce&amp;rbrack; Nuova anteprima del contagocce colore accanto al mouse e al colore gestito
* &amp;lbrack;Contagocce&amp;rbrack; il pannello Selettore colore riappare nella sua ultima posizione quando viene riaperto
* &amp;lbrack;Contagocce&amp;rbrack; Una nuova icona per il selettore materiale
* &amp;lbrack;Contagocce&amp;rbrack; Gestione del colore per l&#39;anteprima dei canali del selettore colore
* &amp;blocca;Contagocce&amp;rbrack; Aggiungi funzionalità di selezione al contagocce
* &amp;lbrack;Contagocce&amp;rbrack; il selettore di materiali non attiva più i canali non attivi
* &amp;lbrack;Contagocce&amp;rbrack; Consenti l&#39;utilizzo del contagocce con una scelta rapida da tastiera
* &amp;lbrack;Contagocce&amp;rbrack; il contagocce preleva il canale pertinente, se applicabile
* &amp;lbrack;Contagocce&amp;rbrack; quando si entra in modalità Selettore colore, vengono disattivate tutte le scelte rapide
* &amp;lbrack;Contagocce&amp;rbrack; Rimuovi selezione automatica del campo esadecimale
* &amp;lbrack;Contagocce&amp;rbrack; Non chiudere il pannello quando si utilizza il selettore di materiali
* &amp;lbrack;Contagocce&amp;rbrack; Nuovo stato disabilitato quando il canale non è disponibile per la selezione
* &amp;lbrack;Export&amp;rbrack; Aggiungi attributo tangente all&#39;esportazione glTF
* Aggiorna Substance Engine alla versione 8.4
* Aggiorna Scorrimento automatico a 0.9.0
* Esegui l’aggiornamento a Qt 5.15.8
* Aggiornamento a Python 3.9
* &amp;lbrack;Shader&amp;rbrack; Aggiungi supporto per ombreggiatura Normali incurvate
* &amp;lbrack;MacOS&amp;rbrack; supporto di 3DConnection SpaceMouse
* &amp;lbrack;Python&amp;rbrack; Documenta la versione Python utilizzata nell&#39;API
* &amp;lbrack;Content&amp;rbrack; Aggiungi 6 nuovi rumori 3D con 105 predefiniti
* &amp;lbrack;Content&amp;rbrack; 20 nuove mappe di grungi e 2 motivi di pieghe in tessuto
* &amp;lbrack;Content&amp;rbrack; Aggiornare il predefinito di esportazione &quot;Mesh maps&quot; per utilizzare nuovi baker
* &amp;lbrack;Content&amp;rbrack; Pendenza sfocatura e filtro alterazione dipendono dalla risoluzione dell’insieme di texture
* &amp;lbrack;Content&amp;rbrack; aggiorna i progetti di esempio per utilizzare i 3 nuovi baker

**Corretto:**

* &amp;lbrack;glTF&amp;rbrack; impossibile aprire glTF con carattere speciale
* &amp;lbrack;Engine&amp;rbrack; artefatti con anisotropia e SVT disattivati
* &amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;M1&amp;rbrack; Materiali avanzati non visualizzati correttamente
* &amp;lbrack;Mesh Processing&amp;brack; Impossibile importare trame da Modeler
* &amp;lbrack;UI&amp;rbrack; Barra di scorrimento orizzontale nella nuova finestra del progetto con la Gestione colore attivata
* &amp;lbrack;Gestione colore&amp;rbrack; Valore spazio di lavoro mancante nel selettore colore con alcune configurazioni OCIO
* &amp;lbrack;Gestione colore&amp;rbrack; L&#39;anteprima del pennello nella finestra della vista non è sottoposta alla gestione del colore
* &amp;lbrack;SpaceMouse&amp;rbrack; Il pivot non viene aggiornato immediatamente con la modifica dello stato attivo e a volte fuori dal modello
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; I file USD esportati hanno una struttura errata
* &amp;lbrack;USD&amp;rbrack; problema di Occlusione ambientale durante l&#39;esportazione
* &amp;lbrack;Content&amp;rbrack; aggiorna la trama della miniatura in modo che corrisponda al progetto di esempio Preview Sphere

**Problemi noti:**

* Esportare texture utilizzando il riempimento diffusione esegue il rendering delle mappe nere
* Il missaggio normale/Occlusione ambientale è interrotto
* &amp;lbrack;MacOS&amp;rbrack; Arresto anomalo all&#39;avvio di Iray in alcuni rari casi
* &amp;lbrack;Anteprima miniatura&amp;rbrack; Le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
* &amp;lbrack;Color Management&amp;rbrack; le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

## Versione 7

### 7.4.3

*(Rilasciato: 11 aprile 2022*)Riepilogo: **Bugfix con supporto di 3Dconnection SpaceMouse nel viewport 2D**

**Aggiunto:**

* &amp;lbrack;SpaceMouse&amp;rbrack; supporto di 3DConnection SpaceMouse in 2D Viewport

**Corretto:**

* &amp;lbrack;Selettore colore&amp;rbrack; Impossibile scrivere in un campo esadecimale
* &amp;lbrack;Gestione colore&amp;rbrack; le risorse utilizzate in modalità di proiezione non sono gestite dal colore nella sovrapposizione
* &amp;lbrack;Gestione colore&amp;rbrack; Gli errori non vengono segnalati nel registro
* &amp;lbrack;SpaceMouse&amp;rbrack; Rimuovi il messaggio di errore generico se l&#39;utente non dispone di SpaceMouse
* &amp;lbrack;SpaceMouse&amp;rbrack; Quando si carica un progetto, il punto fulcro è sempre nascosto
* &amp;lbrack;Baker&amp;rbrack; l&#39;impostazione &quot;Media normali&quot; non ha effetto nei progetti di Porzione UV
* &amp;lbrack;Porzione UV&amp;rbrack; le sovrapposizioni dei riquadri uv inattivi scompaiono quando si ricarica la trama con riquadri diversi
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Lo scripting remoto è interrotto
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Non è possibile eseguire query su diversi canali dall’API e questo genera un errore
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Arresto anomalo quando si utilizza l&#39;evento ProjectEditionEntered
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Arresto anomalo durante la chiamata di get_active_stack()

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* &amp;lbrack;UI&amp;rbrack; barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella finestra di un nuovo progetto
* &amp;lbrack;Mac M1&amp;rbrack; i Materiali avanzati non vengono visualizzati correttamente

### 7.4.2

*(Rilasciato: 08 marzo 2022*)Riepilogo: **Bugfix con supporto di 3Dconnection SpaceMouse e miglioramenti alla gestione del colore (OCIO)**

**Aggiunto:**

* &amp;lbrack;SpaceMouse&amp;rbrack;&amp;lbrack;Windows&amp;rbrack; supporto di 3Dconnection SpaceMouse nel riquadro di visualizzazione 3D per la navigazione
* &amp;lbrack;SpaceMouse&amp;rbrack;&amp;lbrack;Windows&amp;rbrack; scelte rapide da tastiera e tasti di base per i modelli Pro ed Enterprise SpaceMouse nella finestra della vista 3D
* &amp;lbrack;SpaceMouse&amp;rbrack;&amp;lbrack;Windows&amp;rbrack; icona del centro di rotazione dedicato nel riquadro di visualizzazione 3D
* &amp;lbrack;Color Management&amp;rbrack; Utilizzare i ruoli della configurazione OCIO per modificare le impostazioni predefinite
* &amp;lbrack;Gestione colore&amp;rbrack; Gestione colore gestisce la finestra delle proprietà per i widget colore
* &amp;lbrack;Gestione colore&amp;rbrack; Gestione colore gestisce la finestra delle proprietà per l&#39;anteprima del materiale
* &amp;lbrack;Gestione colore&amp;rbrack; Gestione colore gestisce i campioni nel selettore colore
* &amp;lbrack;Gestione colore&amp;rbrack; Aggiungi un&#39;impostazione per definire lo spazio colore sRGB standard
* &amp;lbrack;Gestione colore&amp;rbrack; Aggiungi lo spazio colore sRGB standard dalla configurazione OCIO nel selettore colore Elenco selettori visualizzazione
* &amp;lbrack;Gestione colore&amp;rbrack; Miglioramenti per il menu di esclusione dello spazio colore
* &amp;lbrack;Gestione colore&amp;rbrack; Consenti di ignorare lo spazio cromatico della mappa dell&#39;ambiente in Impostazioni visualizzazione
* &amp;lbrack;Gestione colore&amp;rbrack; Disegna sfumature selettore colore in base alla visualizzazione corrente
* &amp;lbrack;Color Management&amp;rbrack; Blocca valori HDR per impostazione predefinita nell&#39;editor colori
* &amp;lbrack;Gestione colore&amp;rbrack; Usa passthrough (senza spazio colore) per i filtri in modalità Legacy
* &amp;lbrack;Gestione colore&amp;rbrack; Limita la visualizzazione delle sfumature nell&#39;editor colori in base all&#39;intervallo &amp;lbrack;0-1&amp;rbrack;
* &amp;lbrack;Gestione colore&amp;rbrack; Nascondi selettore visualizzazione nel selettore colore in modalità Legacy
* &amp;lbrack;Gestione colore&amp;rbrack; Imposta il selettore colore come campo esadecimale sempre nello spazio colore sRGB
* &amp;lbrack;Gestione colore&amp;rbrack; Disattiva il selettore colore Visualizza il menu a discesa per i canali dati
* &amp;lbrack;Optimization&amp;rbrack; la griglia di alterazione ricalcola solo i riquadri UV coperti
* &amp;lbrack;Esporta&amp;rbrack; consente di esportare progetti di Porzione UV per Sketchfab, USD e glTF
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di modificare la funzione di mappatura tonale

**Corretto:**

* &amp;lbrack;Sketchfab&amp;rbrack; l&#39;aggiornamento del modello esistente comporta la creazione di un nuovo modello
* &amp;lbrack;Sketchfab&amp;rbrack; Arresto anomalo durante la ricerca di un modello aggiornato in precedenza
* Arresto anomalo durante l’esportazione nell’USD
* Arresto anomalo durante la creazione di una nuova istanza shader nella maschera di geometria o quando la geometria è nascosta
* &amp;lbrack;Importa finestra cespite&amp;rbrack; Arresto anomalo quando si modifica il tipo di risorse importate
* Le mappe con trama normale vengono invertite se utilizzate in Pila livelli
* &amp;lbrack;Substance&amp;rbrack; il metodo di fusione dei dati utente non viene considerato
* &amp;lbrack;Color Management&amp;rbrack; Le bitmap con spazio cromatico nel nome del file vengono importate come sequenze di Porzioni UV
* &amp;lbrack;Color Management&amp;rbrack; Gli output con gestione del colore del grafico a Substance si trovano in uno spazio cromatico errato
* &amp;lbrack;Gestione colore&amp;rbrack; lo strumento Riempimento poligonale visualizza il colore errato
* &amp;lbrack;Color Management&amp;rbrack; Il tonemapper ACE viene applicato ai canali in modalità Solo
* &amp;lbrack;Gestione colore&amp;rbrack; L&#39;illuminazione della sfera dell&#39;anteprima dello strumento non è gestita dal colore
* &amp;lbrack;Color management&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Le mappe convertite applicano una conversione errata
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack;&amp;lbrack;Color Management&amp;rbrack; I progetti creati con la variabile di ambiente template &amp; OCIO sono in modalità Legacy
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Impossibile utilizzare la funzione di valutazione JavaScript all&#39;avvio
* &amp;lbrack;3D Adobe Offer&amp;rbrack; Impossibile avviare Painter quando si utilizzano impostazioni internazionali con lingue non supportate per impostazione predefinita

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* &amp;lbrack;UI&amp;rbrack; barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella finestra di un nuovo progetto
* &amp;lbrack;Baker&amp;rbrack; l&#39;impostazione &quot;Media normali&quot; non ha effetto nei progetti di Porzione UV
* &amp;lbrack;Mac M1&amp;rbrack; Materiali avanzati non visualizzati correttamente
* &amp;lbrack;Gestione colore&amp;rbrack; le risorse utilizzate in modalità di proiezione non sono gestite dal colore nella sovrapposizione
* &amp;lbrack;Selettore colore&amp;rbrack; Impossibile scrivere in un campo esadecimale

### 7.4.1

*(Rilasciato: 14 dicembre 2021*)Riepilogo: **Correzione rapida con miglioramenti nella gestione del colore**

**Aggiunto:**

* &amp;lbrack;Gestione colore&amp;rbrack; Usa ruolo dati nei nomi file esportati
* &amp;lbrack;Color Management&amp;rbrack; Espandere la sezione Color Management (Gestione colore) per impostazione predefinita, quando nelle finestre Nuovo progetto e Impostazioni progetto è selezionato OCIO
* &amp;lbrack;Color Management&amp;rbrack; Aggiungi tonemapper ACE in modalità legacy
* &amp;lbrack;Gestione colore&amp;rbrack; Regolare le impostazioni di configurazione predefinite
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Fill $colorSpace nei nomi dei file per i canali dati
* &amp;lbrack;Esporta&amp;rbrack; Esporta progetto Porzione UV in Stager
* &amp;lbrack;Interoperability&amp;rbrack; non disponibile per le edizioni Steam e Substance
* &amp;lbrack;Interoperabilità&amp;rbrack; Consente di inviare un progetto di Porzione UV a Stager

**Corretto:**

* &amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; Painter non inizia con Catalina
* &amp;lbrack;Gestione colore&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; arresto anomalo casuale durante la riproduzione con la gestione del tipo di dati/colore sul canale utente
* &amp;lbrack;Gestione colore&amp;rbrack; Risorse utilizzate come scala di grigi nel nuovo menu per la visualizzazione dello spazio colore della maschera
* &amp;lbrack;Gestione colore&amp;rbrack; il canale utente è più scuro nella finestra della vista in modalità legacy + vista solo
* &amp;lbrack;Color Management&amp;rbrack; La mappa Env è sempre lineare se utilizzata in iRay
* &amp;lbrack;Color Management&amp;rbrack; Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* &amp;lbrack;Color management&amp;rbrack; Il selettore colore non funziona all’interno di una Substance in modalità legacy
* &amp;lbrack;Gestione colore&amp;rbrack; il passaggio tra le viste dei singoli canali nella finestra della vista viene visualizzato con lo spazio cromatico corretto quando si utilizza il menu a discesa
* &amp;lbrack;Gestione colore&amp;rbrack; Esporta applica la conversione errata sui canali utente con gestione del colore in modalità legacy
* I tratti creati nella maschera di visualizzazione Solo non vengono visualizzati quando si ritorna alla vista Materiale
* &amp;lbrack;Esporta&amp;rbrack; le mappe convertite non vengono esportate come canali con gestione del colore
* &amp;lbrack;Texture Set&amp;brack; La descrizione con il nome originale non è presente nei canali utente rinominati
* &amp;lbrack;Steam&amp;rbrack; File mancanti durante la verifica dell&#39;integrità del file con Steam

**Problemi noti:**

* &amp;lbrack;Mac M1&amp;rbrack; Materiali avanzati non visualizzati correttamente

### 7.4.0

*(Rilasciato: 24 novembre 2021*)Riepilogo: **Versione principale. Introduzione della prima versione della gestione del colore, disancoraggio della vista 2D o 3D, nuova opzione per lo srotolamento automatico degli UV per evitare isole allungate, chiamata delle funzioni JavaScript dall&#39;API Python e nuovo contenuto**

**Aggiunto:**

* &amp;lbrack;Color Management&amp;rbrack; supporto della gestione colore OpenColorIO versione 2
* &amp;lbrack;Gestione colore&amp;rbrack; Aggiungi impostazioni di gestione colore alle impostazioni del progetto
* &amp;lbrack;Color Management&amp;rbrack; finestra di avvertenza sulle modifiche alla configurazione di Color Management all&#39;apertura di un progetto
* &amp;lbrack;Color Management&amp;rbrack; Visualizza un messaggio di errore se viene selezionato un file di configurazione OCIO non valido
* &amp;lbrack;Color Management&amp;rbrack; consente di ignorare la configurazione con la variabile di ambiente OCIO
* &amp;lbrack;Color Management&amp;rbrack; più configurazioni OCIO integrate per impostazione predefinita con l&#39;applicazione
* &amp;lbrack;Gestione colore&amp;rbrack; Estrai il nome dello spazio colore dal nome del file bitmap importato
* &amp;lbrack;Gestione colore&amp;rbrack; Consenti di ignorare lo spazio colore con uno spazio colore dalla configurazione nella finestra Proprietà
* &amp;lbrack;Gestione colore&amp;rbrack; Aggiungere opzioni di gestione colore nelle impostazioni del set di texture
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Consenti di gestire separatamente i colori delle viste 2D e 3D
* &amp;lbrack;Color Management&amp;rbrack; Carica e converti la mappa dell&#39;ambiente nello spazio cromatico di lavoro
* &amp;lbrack;Gestione colore&amp;rbrack; Regola il selettore colore e l&#39;editor con lo spazio colore corrente
* &amp;lbrack;Gestione colore&amp;rbrack; Consenti di selezionare lo spazio colore Trasforma della visualizzazione nella finestra della vista con un nuovo menu a discesa
* &amp;lbrack;Color Management&amp;rbrack; Applica la Trasforma di visualizzazione con i risultati del rendering dei raggi
* &amp;lbrack;Gestione colore&amp;rbrack; Esporta texture con diversi spazi colore
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Applica le impostazioni di gestione del colore dalla variabile di ambiente (OCIO) ai nuovi progetti
* &amp;lbrack;Viewport&amp;rbrack; Consenti di disancorare la finestra della vista 2D o 3D
* &amp;lbrack;Auto Unwrap&amp;rbrack; Nuova opzione per evitare isole allungate
* &amp;lbrack;Scripting Python&amp;rbrack; Chiama funzioni JavaScript dall&#39;API Python
* &amp;lbrack;Finestra nuovo progetto&amp;rbrack; Rende comprimibile la sezione delle mappe importate
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;brack; Consenti di nascondere le normali come opzione nelle impostazioni di Altera
* &amp;lbrack;Content&amp;rbrack; 11 nuove mappe grungi
* &amp;lbrack;Content&amp;rbrack; 8 nuovi strumenti predefiniti (cerniera, cavo di serraggio, glitter)
* &amp;lbrack;Content&amp;rbrack; 8 nuovi materiali (cicatrice, tasca, ...)
* &amp;lbrack;Content&amp;rbrack; 1 nuovo generatore (inflate shrinkwarp)

**Problemi noti:**

* &amp;lbrack;Mac M1&amp;rbrack; Materiali avanzati non visualizzati correttamente
* &amp;lbrack;Gestione colore&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; arresto anomalo casuale durante la riproduzione con la gestione del tipo di dati/colore sul canale utente
* &amp;lbrack;Color Management&amp;rbrack; Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* &amp;lbrack;Color management&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; Il salvataggio del rendering in EXR o TIFF durante l’attivazione di Color Management nella finestra della vista consente di risparmiare sempre in modalità lineare
* &amp;lbrack;Gestione colore&amp;rbrack; Le risorse utilizzate come scala di grigi nella maschera visualizzano il menu Spazio colore errato
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; La mappa Env è sempre lineare quando viene utilizzata in Iray
* &amp;lbrack;Gestione colore&amp;rbrack;&amp;lbrack;Esporta&amp;rbrack; Le mappe convertite non vengono esportate come canali con gestione del colore
* &amp;lbrack;Color Management&amp;rbrack;&amp;lbrack;Export&amp;brack; Esporta ignora se il canale utente è gestito dal colore o meno in modalità legacy

### 7.3.1

*(Rilasciato: 24 Novembre 2021*)Riepilogo: **Bugfix**

**Aggiunto:**

* &amp;lbrack;Proiezione&amp;rbrack; Il ridimensionamento dovrebbe funzionare solo nello spazio oggetto

**Corretto:**

* &amp;lbrack;Mac M1&amp;rbrack; il livellamento dei materiali non funziona
* &amp;lbrack;Mac M1&amp;rbrack;&amp;lbrack;Projection&amp;rbrack; Warp non funziona
* I micro dettagli non vengono visualizzati correttamente
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; Passaggio alla modalità di alterazione con un livello creato con una versione precedente
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
* &amp;lbrack;Projection&amp;rbrack;&amp;lbrack;Warp&amp;rbrack; Split rimane selezionata al termine della divisione
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;UV&amp;rbrack; Il punto pivot viene reimpostato quando si capovolge la proiezione
* &amp;lbrack;Filter&amp;rbrack; L&#39;ambiente Esegue i baking illuminazione cambia quando si ricarica o si modifica un parametro
* &amp;lbrack;Interoperability&amp;rbrack; non disponibile per le edizioni Steam e Substance
* &amp;lbrack;Interoperability&amp;rbrack; Il pulsante &quot;Sfoglia risorse 3D nel Marketplace&quot; dovrebbe sempre aprire CCD nella scheda 3D di Stock e Marketplace

**Problemi noti:**

* &amp;lbrack;Mac M1&amp;rbrack; Materiali avanzati non visualizzati correttamente

### 7.3.0

*(Rilasciato: 13 ottobre 2021*)Riepilogo: **Versione principale. Contiene una nuova proiezione di alterazione 3D, una nuova proiezione cilindrica, miglioramenti del selettore colore, nuove funzioni nell&#39;API Python e correzioni di bug**

**Aggiunto:**

* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Esposizione dell’alterazione 3D come nuova modalità di proiezione
* &amp;lbrack;Projection&amp;rbrack;&amp;lbrack;Warp&amp;rbrack; Consenti la modalità decalcomania per Alpha, Texture e procedure con trascinamento nella finestra della vista
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Usa proiezione alterazione con decalcomania (ALT)
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack;&amp;lbrack;Barra&amp;rbrack; Trasforma alterazione come intero o per vertici
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack;&amp;lbrack;Barra degli strumenti&amp;rbrack; Aggiungi punti della griglia con opzioni Dividi alterazione a croce, in orizzontale o in verticale
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack;&amp;lbrack;Barra degli strumenti&amp;rbrack; Menu dedicato per le azioni di ripristino
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack;&amp;lbrack;Barra degli strumenti&amp;rbrack; Opzione per regolare automaticamente le tangenti quando si spostano i punti
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack;&amp;lbrack;Barra degli strumenti&amp;rbrack; Menu dedicato per l&#39;edizione della griglia (dimensioni, reimpostazione, colore e dimensione della maniglia)
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Nuova scelta rapida da tastiera da tastiera per cambiare la modalità edizione alterazione vertici interi (MAIUSC+V)
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Fare clic+Ctrl per passare dallo strumento superficie ad altri strumenti
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Cilindrico&amp;rbrack; Esposizione della modalità di proiezione cilindrica
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Barra degli strumenti&amp;rbrack; Impostazioni manipolatore di gruppi (dimensioni, passaggi griglia, passaggi angolo)
* &amp;lbrack;Selettore colore&amp;rbrack; Nuova interfaccia utente del selettore colore
* &amp;lbrack;Selettore colore&amp;rbrack; Usa valori sRGB nei widget del selettore colore
* &amp;lbrack;Selettore colore&amp;rbrack; Consenti di salvare ed eliminare campioni colore
* &amp;lbrack;Selettore colore&amp;rbrack; Contagocce accessibile da slot normali e di colore
* &amp;lbrack;Selettore colore&amp;rbrack; Consente di modificare il colore dinamico tra i valori 0 e 255
* &amp;lbrack;Selettore colore&amp;rbrack; Rendi lo stato HSV/RGB comune in tutta l&#39;app
* &amp;lbrack;Selettore colore&amp;rbrack; La finestra del selettore colore è semi-persistente
* &amp;lbrack;Selettore colore&amp;rbrack; Premendo Esc si chiude la finestra del selettore colore
* Miglioramento delle prestazioni per l’interazione dell’interfaccia utente e durante la pittura
* &amp;lbrack;Engine&amp;rbrack; Aggiornamento alla nuova versione del motore di Substance (8.3.0)
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consente di ricaricare la trama del progetto corrente
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di aggiornare le risorse nei progetti
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di impostare ed eseguire query sulla risoluzione delle Porzioni UV
* &amp;lbrack;Interoperability&amp;rbrack; non disponibile per le edizioni Steam e Substance
* &amp;lbrack;Interoperability&amp;rbrack; Ricezione di più risorse da Bridge

**Corretto:**

* Il selettore colore non visualizza il colore corretto
* &amp;lbrack;Eseguite i baking&amp;rbrack; L&#39;elenco dei set di texture non è ordinato correttamente
* &amp;lbrack;FBX import&amp;rbrack; 3ds Le trasformazioni pivot del gruppo Max non vengono considerate
* &amp;lbrack;Substance Engine&amp;rbrack; Arresto anomalo con importazione di SBSAR danneggiati
* &amp;lbrack;MacOS&amp;rbrack; l&#39;opzione di configurazione del progetto in lingue diverse non è presente
* I salvati automaticamente possono bloccare Painter durante processi lunghi

**Problemi noti:**

* &amp;lbrack;Projection&amp;rbrack;&amp;lbrack;Warp&amp;rbrack; Split rimane selezionata al termine della divisione
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;Altera&amp;rbrack; Linee artefatto tra le patch in alcuni rari casi
* &amp;lbrack;Proiezione&amp;rbrack;&amp;lbrack;UV&amp;rbrack; Il punto pivot viene reimpostato quando si capovolge la proiezione
* &amp;lbrack;Mac M1&amp;rbrack; Materiali avanzati non visualizzati correttamente
* &amp;lbrack;M1&amp;rbrack;&amp;lbrack;Regressione&amp;rbrack; Il livellamento dei materiali non funziona

### 7.2.3

*(Rilasciato: 24 agosto 2021*)Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

* &amp;lbrack;Librerie&amp;rbrack; Aggiungi un modo per escludere i file indesiderati dalla ricerca per indicizzazione

**Corretto:**

* &amp;lbrack;Win&amp;rbrack; più schermi e problemi di sospensione
* &amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; Commutazione dello shader quando si utilizzano gli effetti
* &amp;lbrack;Viewport&amp;rbrack; la modalità di anteprima completa non mostra più il cursore del pennello senza canale alfa
* &amp;lbrack;UI&amp;rbrack; il widget Angolo non funziona correttamente
* &amp;lbrack;Pila livelli&amp;rbrack; molte sottocartelle causano un blocco molto lungo
* &amp;lbrack;Iray&amp;rbrack; viste diverse in Iray e OpenGL: visibile se non funziona
* &amp;lbrack;Iray&amp;rbrack; Indice di rifrazione non preso in considerazione e non viene visualizzato nelle proprietà mdl
* &amp;lbrack;JavaScript&amp;rbrack; ShowExportDialog() non restituisce mai true
* Impossibile leggere mtl da Adobe Stock

### 7.2.2

*(Rilasciato: 27 luglio 2021*)Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

* Aggiornamento della versione dei requisiti del driver AMD

**Corretto:**

* &amp;lbrack;Mac M1&amp;rbrack; rilevamento memoria errata
* &amp;lbrack;Export&amp;rbrack; I tracciati molto lunghi non vengono visualizzati correttamente

**Problemi noti:**

* &amp;nero;Contenuto&amp;nero; Ombreggiature obsolete dei campioni

### 7.2.1

*(Rilasciato: 2 luglio 2021*)Riepilogo: **Rilascio secondario, Hotfix**

**Aggiunto:**

* &amp;lbrack;Interop&amp;rbrack; Aggiungi descrizione per informare che l’invio di progetti Porzione UV a Stager non è ancora supportato
* &amp;lbrack;Plugin&amp;brack;&amp;lbrack;UI&amp;rbrack; aggiornamento dell&#39;icona di collegamento dinamico

**Corretto:**

* &amp;lbrack;Nvidia&amp;rbrack; La versione del driver che inizia con 30 è considerata obsoleta
* &amp;blocco;Librerie&amp;rbrack; lo stato del pannello Risorse non viene salvato a meno che un progetto non sia aperto
* &amp;lbrack;Librerie&amp;rbrack; la nuova ricerca salvata mantiene la parola chiave della vecchia ricerca salvata
* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;UVTiles&amp;rbrack; Anche le mappe ID per meshID prendono in considerazione le Porzioni UV
* &amp;lbrack;Export&amp;rbrack; gLTF non importa il colore dei vertici
* &amp;lbrack;Iray&amp;brack; mancano alcune descrizioni comandi
* &amp;lbrack;Interop&amp;rbrack; Invia a Stager non è sempre disabilitato quando Stager non viene rilevato
* &amp;lbrack;Resource Updater&amp;rbrack; impossibile aggiornare il creatore di pennelli di Photoshop
* &amp;lbrack;Content&amp;rbrack; Il generatore di usura dei bordi in fibra di vetro è rotto

### 7.2.0

*(Rilasciato: 23 giugno 2021*)Riepilogo: **Versione principale, fornisce un aggiornamento al pannello delle risorse, un nuovo shader con accesso a nuovi canali e parametri, un aggiornamento complessivo dell’interfaccia utente, alcuni miglioramenti delle prestazioni molto richiesti, supporto linguistico esteso e altro ancora.**

**Aggiunto:**

* &amp;blocco;Librerie&amp;rbrack; Nuovo pannello Risorse per sostituire lo scaffale
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo layout pannello Risorse
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Cambiare l&#39;orientamento e l&#39;interfaccia utente predefiniti del pannello Risorse
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Introduce un&#39;opzione di visualizzazione elenco alla libreria
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo percorso di navigazione nel pannello Risorse
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Selezionare &quot;Tutte le librerie&quot; quando si seleziona una ricerca salvata
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Seleziona &quot;Tutte le librerie&quot; quando tutte le cartelle sono deselezionate
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo tag per i pennelli particelle
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Sostituito da &quot;shelf&quot; con &quot;Tutte le librerie&quot; nell&#39;app
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Consenti di nascondere le cartelle vuote
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; La libreria utente predefinita dovrebbe essere visibile anche se vuota
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo metodo di filtraggio tramite le icone dei tipi di risorsa
* &amp;lbrack;Libraries&amp;rbrack; Scelta rapida da tastiera &quot;CTRL&quot; per selezionare più tipi di risorse
* &amp;lbrack;Libraries&amp;rbrack; Nuova variabile di ambiente per controllare il budget della memoria di anteprima della risorsa
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Content&amp;rbrack; Mappe nuovo ambiente
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Content&amp;rbrack;&amp;lbrack;UI&amp;rbrack; spostamento di rendering nei materiali predefiniti
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Content&amp;rbrack; Imposta lo shader dell&#39;Adobe Standard Material (ASM) come predefinito per la generazione delle anteprime
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Content&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; Nuovi modelli di progetto per il nuovo shader ASM
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Thumbnail&amp;rbrack; Use new Studio 6 environment map
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Thumbnail&amp;rbrack; Leggi la miniatura nella risorsa invece di generarla
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Thumbnail&amp;rbrack; Aggiungi spostamento alla generazione delle miniature
* &amp;lbrack;Impostazioni set di texture&amp;rbrack;
* &amp;lbrack;Impostazioni set di texture&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Esposizione del nuovo height al metodo di conversione normale
* &amp;lbrack;Texture Set Settings&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Rielaborazione dell&#39;organizzazione dell&#39;interfaccia utente dei canali
* &amp;lbrack;Texture Set Settings&amp;rbrack; limite canali utente elevato a 16 canali
* &amp;lbrack;Texture Set Settings&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Indica i canali compatibili con lo shader selezionato
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; Nuovo shader Adobe Standard Material
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; Supporto aggiunto per Anisotropia, Cancella pelo, Dispersione sottosuperficie, Specular edge color e Brillantezza
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; modifica i valori di colore dei canali predefiniti
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Modello di esportazione aggiornato Adobe Dimension in Adobe Substance 3D Stager
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; etichette e descrizioni comandi aggiunte per i parametri shader e MDL
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; Rende visibile il colore della Dispersione in vista 2D anche se SSS non è supportato
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; Supporto dello shader ASM in Iray con la nuova MDL
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; Scattering sottosuperficie aggiornato in lucido e patinato specifiche PBR legacy
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack;&amp;lbrack;Content&amp;rbrack; ha modificato il tipo SSS predefinito per gli esempi
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; Documentazione aggiunta per l&#39;API ASM
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;ASM&amp;rbrack; Ottimizza gli ombreggiatori per ignorare i canali inutilizzati
* &amp;lbrack;Shader&amp;rbrack; Esposizione dei nuovi canali degli insiemi di texture
* &amp;lbrack;Shader&amp;rbrack; Dispersione sottosuperficie migliorata
* &amp;lbrack;Shader&amp;rbrack; nuovi parametri di shader nascosti per alcuni ombreggiatori
* &amp;lbrack;Shader&amp;rbrack; Visibile se per i parametri di shader
* &amp;lbrack;Performance&amp;rbrack;
* &amp;lbrack;Librerie&amp;rbrack; Anteprima risorse: caricamento tempo e prestazioni di calcolo migliorate
* &amp;lbrack;Engine&amp;rbrack; Miglioramento delle prestazioni di pittura
* &amp;lbrack;Auto Unwrap&amp;rbrack;
* &amp;lbrack;Auto Unwrap&amp;rbrack; miglioramenti alle prestazioni Impacchettamenti
* &amp;lbrack;Auto Unwrap&amp;rbrack; Auto unwrap compatibile con il flusso di lavoro Porzione UV
* &amp;lbrack;Srotolamento automatico&amp;rbrack; Nuova opzione per posizionare gli UV in base all&#39;orientamento della trama
* &amp;blocco;Altro&amp;blocco;
* &amp;lbrack;Impostazioni&amp;rbrack; direzione di zoom predefinita modificata
* &amp;lbrack;UI&amp;rbrack; aggiornamento generale dell&#39;interfaccia utente
* &amp;lbrack;UI&amp;rbrack; Rielaborazione del menu?
* &amp;lbrack;UI&amp;rbrack; Sostituisci icona inversa
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Plugin&amp;rbrack; Sostituisci icona per il collegamento dcc del plug-in
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;AMD&amp;rbrack; Aggiorna la versione minima richiesta e il messaggio popup
* &amp;lbrack;Pila livelli&amp;rbrack; Crea nuovo livello all&#39;interno della cartella vuota selezionata
* Aggiornamento della documentazione Python
* &amp;lbrack;Branding&amp;rbrack;
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nome applicazione aggiornato in Adobe Substance 3D Painter
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Versione standalone aggiornata a &#39;Substance edition&#39;
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nome eseguibile dell&#39;applicazione aggiornato, percorso di installazione, pacchetto e icone
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Libreria e percorso predefiniti rinominati
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Aggiornamento della finestra Informazioni su
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Schermata introduttiva aggiornata
* &amp;lbrack;Branding&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Rimosso il numero di versione basato sull&#39;anno
* &amp;lbrack;Localization&amp;rbrack; Nuove traduzioni in tedesco, francese e cinese semplificato
* &amp;lbrack;Interoperability&amp;rbrack; non disponibile per le edizioni Steam e Substance
* &amp;lbrack;Interoperabilità&amp;rbrack; Interoperabilità con l&#39;ecosistema Adobe: Designer, Sampler, Stager e Bridge
* &amp;lbrack;Interoperability&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Ricevi e aggiorna la risorsa da Designer
* &amp;lbrack;Interoperability&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Ricevi risorsa da Sampler
* &amp;lbrack;Interoperability&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Invia risorsa a Stager
* &amp;lbrack;Interoperability&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Mostra in Adobe Bridge
* &amp;lbrack;Interoperability&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Consenti di accedere rapidamente a Risorse Adobe 3D
* &amp;lbrack;Interoperability&amp;rbrack; Nuovi tag di utilizzo di sbsar
* &amp;lbrack;Interoperabilità&amp;rbrack; Handle ricevuto tipi di risorse
* &amp;lbrack;Interoperability&amp;rbrack; Le risorse ricevute da Adobe Substance 3D Designer o Adobe Substance 3D Sampler sono archiviate nella libreria scelta di default dall&#39;utente
* &amp;lbrack;Interoperability&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova icona nella barra degli strumenti a sinistra da inviare a Stager o Photoshop

**Corretto:**

* &amp;lbrack;Tablet&amp;rbrack; prestazioni ridotte durante la pittura con pressione
* &amp;lbrack;Tablet&amp;rbrack; Problema con i tablet con controlli del cursore
* &amp;lbrack;Arresto anomalo&amp;rbrack; nome non corrispondente tra l&#39;elenco e l&#39;Esportazione del set di texture
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Libraries&amp;rbrack; Fare doppio clic su una libreria secondaria
* &amp;lbrack;Libraries&amp;rbrack; Problema durante la ricerca per indicizzazione delle directory della libreria
* &amp;lbrack;Libraries&amp;rbrack; La riga di comando Forza generazione anteprima non funziona come previsto
* &amp;lbrack;Libraries&amp;rbrack;&amp;lbrack;Content&amp;rbrack; Il filtro Ambiente luce Eseguito i baking è nero per impostazione predefinita
* &amp;lbrack;Linux&amp;rbrack;&amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;Esporta mesh&amp;rbrack; Impossibile importare glTF creato su Linux/MacOS
* &amp;lbrack;Linux&amp;rbrack; Se si trascina un file nel pannello Risorse, si può verificare un arresto anomalo
* &amp;lbrack;Srotolamenti automatici&amp;rbrack; Lo Srotolamento automatico è disponibile anche se non è stata selezionata una trama per il ricaricamento
* &amp;lbrack;Particelle&amp;rbrack; comportamento particella errato con gravità
* &amp;lbrack;Pila livelli&amp;rbrack; L&#39;istogramma dei livelli può utilizzare la luminanza solo con alcuni canali
* &amp;blocca;Maschera geometria; Il menu di scelta rapida di una cartella quando si modifica la maschera di geometria non funziona
* &amp;lbrack;Proiezione&amp;rbrack; giuntura con proiezione sferica e filtro bilineare
* &amp;lbrack;Porzione UV&amp;rbrack; Esporta maschera in file esporta solo la porzione 0, 0
* &amp;lbrack;Esporta trama&amp;rbrack; l&#39;esportazione della trama FBX è vuota
* &amp;lbrack;Iray&amp;rbrack; La Mappa normale non viene considerata nei nuovi progetti durante il rendering
* &amp;lbrack;Salva&amp;rbrack; Salva problemi su unità condivise
* &amp;lbrack;Eseguite i baking&amp;rbrack; Se si rigenera una trama con parametri modificati, viene visualizzato un avviso
* &amp;lbrack;Esegui i baking&amp;rbrack;&amp;lbrack;Regressione&amp;rbrack; Risultato errato quando il rettangolo di selezione globale di trame di poli superiori non include l&#39;origine della scena
* &amp;lbrack;Python&amp;rbrack; Le librerie utente personalizzate non vengono considerate

**Problemi noti:**

* &amp;lbrack;Librerie&amp;rbrack; ricerche salvate non salvate se non è aperto alcun progetto
* &amp;lbrack;NVIDIA&amp;rbrack; Messaggio per driver obsoleto anche se aggiornato

### 7.1.1 (2021.1.1)

*(Rilasciato: 23 marzo 2021*)Riepilogo: **Versione secondaria, Bugfix con possibilità di immettere valori esadecimali nel selettore colore**

**Aggiunto:**

* &amp;lbrack;Log&amp;brack; Avvisa gli utenti in caso di driver GPU AMD incompatibili
* &amp;lbrack;Selettore colore&amp;rbrack; Consente di digitare valori esadecimali

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack; Prestazioni esterne
* &amp;lbrack;Geometry mask&amp;rbrack; se si fa clic sul nome della trama tenendo premuto il tasto Alt, si potrebbe verificare un arresto anomalo
* &amp;lbrack;Engine&amp;rbrack; Il disegno non aggiorna l&#39;intera visualizzazione quando necessario
* &amp;lbrack;Pila livelli&amp;rbrack; la selezione si blocca dopo la modifica dello shader
* &amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;Selettore colore&amp;rbrack; Il colore è leggermente diverso da quello selezionato
* &amp;lbrack;Export&amp;rbrack; L&#39;utilizzo del formato di file PSD non genera un file per Porzione UV
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Javascript&amp;rbrack; alg.mapexport.getPathsExportDocumentMaps() non restituisce tutti i valori
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; I plug-in disattivati vengono nuovamente attivati alla riapertura di Painter

### 7.1.0 (2021.1.0)

*(Rilasciato: 28 gennaio 2021*)Riepilogo: **Versione principale, nuova maschera di geometria che consente di selezionare e pittura parti della geometria, copiare/incollare effetti nella Pila livelli, miglioramento del flusso di lavoro della Porzione UV, aggiornamento di Iray, Baker, Substance Engine e nuovo contenuto**

**Aggiunto:**

* Nuova maschera di geometria e pittura parti selezionate della geometria
* &amp;lbrack;Geometry Mask&amp;rbrack; Consenti di pittura le parti selezionate della geometria in base ai nomi della trama
* &amp;lbrack;Geometry Mask&amp;rbrack; selezione rettangolare in entrambe le finestre
* &amp;blocco;Maschera geometria&amp;rbrack; Consenti di nascondere/ignorare la geometria esclusa su qualsiasi livello
* &amp;lbrack;Geometry Mask&amp;rbrack;&amp;lbrack;Properties&amp;rbrack; Selezione rapida delle caselle di controllo con clic e trascinamento
* &amp;lbrack;Geometry Mask&amp;rbrack;&amp;lbrack;Properties&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Includi/Escludi tutto con un menu a discesa nella finestra Proprietà
* &amp;lbrack;Geometry Mask&amp;rbrack;&amp;lbrack;Properties&amp;rbrack; Consenti di selezionare rapidamente una voce in un elenco con ALT+CLIC SINISTRO
* &amp;lbrack;Geometry Mask&amp;rbrack;&amp;lbrack;Properties&amp;rbrack; Sovrapposizione nelle finestre delle viste quando si passa con il mouse sui nomi delle trame o sulle Porzioni UV nella finestra Proprietà
* &amp;lbrack;Geometry Mask&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Aggiungi opzioni Copia/Incolla alla maschera di geometria
* &amp;blocca;Maschera geometria&amp;rbrack; icona Nuova per il pulsante Nascondi/Ignora geometria esclusa
* &amp;lbrack;Geometry Mask&amp;rbrack; Nuovo tooltip per Nascondi/Ignora geometria esclusa
* &amp;lbrack;Geometry Mask&amp;rbrack; scelta rapida da tastiera da tastiera ALT+H per attivare/disattivare il pulsante &quot;Ignora geometria esclusa&quot;
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Nuova miniatura di anteprima della sfera del livello di riempimento per la Porzione UV e la modalità semplificata
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Consente di uscire facilmente dalla maschera Porzione UV
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Texture Set List&amp;rbrack; Consenti di fornire una descrizione per Porzione UV
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Texture Set Settings&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Due nuovi titoli di sezione nel menu a discesa per modificare la risoluzione delle Porzioni UV
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Finestra&amp;vista; Esci da Porzione UV maschera quando si trascina un materiale nella finestra della vista
* &amp;blocco;Pila livelli&amp;rbrack; Aggiungi opzioni di copia/incolla per gli effetti
* &amp;lbrack;Pila livelli&amp;rbrack; consente di copiare/incollare gli effetti da un set di texture a un altro
* &amp;lbrack;Pila livelli&amp;rbrack; Consenti selezione multipla di effetti
* &amp;blocco;Pila livelli&amp;rbrack; Aggiungi opzioni di copia/incolla come scelte rapide per gli effetti di livello
* &amp;lbrack;Pila livelli&amp;rbrack; Passa automaticamente tra maschera e contenuto quando si trascinano gli effetti in un altro livello
* &amp;lbrack;Pila livelli&amp;rbrack; crea automaticamente una maschera quando si incolla una maschera da un altro livello
* &amp;lbrack;Pila livelli&amp;rbrack; Aggiungi azioni effetto di spostamento all&#39;interno del menu contestuale di scelta rapida degli effetti
* &amp;lbrack;Pila livelli&amp;rbrack; Consenti di trascinare gli effetti da un livello all&#39;altro
* &amp;lbrack;Pila livelli&amp;rbrack; trascinando gli elementi in una cartella, questi vengono posizionati nella parte superiore della cartella
* Aggiornamento di Iray alla versione 2020.1.0
* &amp;lbrack;Baker&amp;rbrack; Aggiorna i Baker alla versione 2.5.4
* &amp;lbrack;Baker&amp;rbrack; Visualizza le singole Porzioni UV nella finestra di avanzamento eseguita i baking
* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Consente di eseguire i baking rapidamente il set di texture corrente con un nuovo pulsante
* &amp;lbrack;Baker&amp;rbrack; Consente all&#39;utente di selezionare rapidamente uno dei baker con ALT+CLIC SINISTRO
* Aggiorna Substance Engine alla versione 8.0.8
* &amp;lbrack;Substance Engine&amp;rbrack; supporta il colore predefinito nei nuovi file .sbsar
* &amp;lbrack;Auto Unwrap&amp;rbrack; miglioramento delle prestazioni
* &amp;lbrack;Export&amp;rbrack; Aggiungi un feedback visivo per indicare quale risoluzione di Porzione UV differisce da quella predefinita del progetto
* &amp;lbrack;Export&amp;rbrack; Aggiungi fattore dimensioni scena nel file json shader esportato
* &amp;lbrack;Lingua&amp;rbrack; Aggiungi traduzione giapponese
* &amp;lbrack;UI&amp;rbrack; Aggiorna informazioni su finestra con controllo delle versioni delle dipendenze interne
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di gestire le risorse degli scaffali
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di sapere quando un progetto è pronto per essere eseguito i baking ed esportato
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di sapere quando uno scaffale ha terminato la ricerca per indicizzazione delle risorse sul disco
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di eseguire query sull&#39;elenco di porzioni UV per set di texture
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di assegnare l&#39;anteprima personalizzata alle risorse Shelf
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di gestire scaffali personalizzati
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Aggiungi un indice di metodo in ogni sottomodulo della documentazione
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Nuovo stile per la documentazione
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Miglioramento delle risorse e della documentazione dello scaffale
* &amp;lbrack;Content&amp;rbrack; Tre nuovi strumenti predefiniti per creare punti
* &amp;lbrack;Shelf&amp;rbrack; Rimuovi temporaneamente &quot;Esporta in Substance share&quot; durante la transizione alla nuova piattaforma di Substance share

**Corretto:**

* Arresto anomalo di utilizzo di monitor con risoluzioni diverse
* Arresto anomalo in Substance Engine con alcuni progetti rari
* L’aggiornamento della finestra della vista non riesce con Nascondi/Ignora geometria esclusa quando si cambia livello
* &amp;lbrack;vista 2D&amp;rbrack; il riquadro di visualizzazione 2D potrebbe non essere presente in alcuni progetti
* &amp;lbrack;Eseguire i baking&amp;rbrack; &quot;Corrispondenza per nome trama&quot; ignora parti dell&#39;oggetto
* &amp;lbrack;Pila livelli&amp;rbrack; se si fa clic su un effetto di livello, viene aperta la cartella
* &amp;lbrack;Geometry Mask&amp;rbrack; La Porzione UV viene comunque conteggiata nella maschera anche quando si reimporta la trama senza di essa
* &amp;lbrack;Geometry Mask&amp;rbrack; Il menu di scelta rapida nella finestra della vista non fornisce gli strumenti corretti
* &amp;lbrack;Engine&amp;rbrack; Segnali di ritardo gravi su progetti specifici
* &amp;lbrack;Scripting&amp;rbrack; latenza elevata con richieste JSON POST remote in Windows
* &amp;lbrack;Linux&amp;rbrack; La quantità di Vram non viene rilevata correttamente con specifiche GPU integrate
* &amp;lbrack;Auto Unwrap&amp;rbrack; Arresti anomali o tempi lunghi per l&#39;annullamento del wrapping su alcuni progetti

## Versione 6

### 6.2.2 (2020.2.2)

*(Rilasciato: 28 settembre 2020*)Riepilogo: **Versione secondaria, Bugfix con alcune funzioni nell&#39;API Python**

**Aggiunto:**

* &amp;lbrack;Performance&amp;rbrack; Non calcolare tutte le Porzioni UV quando si utilizza la selezione ID colore
* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Visualizza le descrizioni del set di texture
* &amp;lbrack;Baker&amp;rbrack; Consenti di salvare le impostazioni di esegue i baking
* &amp;lbrack;Baker&amp;rbrack; Aggiungi comprimi tutte/espandi tutte le opzioni alla scheda Selezione
* &amp;lbrack;Texture Set List&amp;rbrack; Nascondi descrizione se vuoto
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Texture Set List&amp;rbrack; Fare clic su Porzione UV per espandere/comprimere l&#39;elenco
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Consente di ridimensionare il pannello Elenco set di texture in orizzontale
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Testo coerente delle descrizioni per il flusso di lavoro Porzione UV e Set di texture con texture non selezionata
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di utilizzare i predefiniti di esportazione per esportare la texture
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Aggiungi un registro modifiche nella documentazione
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti di eseguire una query su tutti i canali disponibili in un determinato stack
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; miglioramenti dell&#39;interfaccia utente della console

**Corretto:**

* &amp;lbrack;AMD&amp;rbrack; Rilevamento non corretto della versione del driver obsoleta
* Arresto anomalo di reimportazione di una trama con layout di Porzione UV diverso in alcuni casi
* Arresto anomalo quando si utilizzano particelle con UDIM su trame molto pesanti
* &amp;lbrack;Porzione UV&amp;rbrack; Arresto anomalo durante l&#39;esportazione di una trama con informazioni di spostamento in alcuni casi
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Arresto anomalo&amp;rbrack; L&#39;esportazione di Vista 2D in formato psd può causare un arresto anomalo
* L’importazione di immagini come sequenze durante la creazione di un progetto non funziona
* Motore bloccato in un ciclo continuo
* &amp;lbrack;Scelta rapida da tastiera&amp;rbrack; la fotocamera ruota sempre in modalità snap quando si modificano le scelte rapide della modalità snap
* Le trame vengono sempre annullate automaticamente quando vengono reimportate, anche se l’opzione è disattivata
* &amp;lbrack;Texture Set List&amp;rbrack; Il campo di testo Descrizione a volte non è completamente visibile durante l&#39;edizione
* &amp;lbrack;Elenco&amp;rbrack set di texture; Il menu a discesa per nascondere/mostrare i set di texture non è completamente visibile
* &amp;lbrack;Elenco set di texture&amp;rbrack; se si fa clic sull&#39;icona occhio, non deve essere immesso il nome &quot;Modifica set di texture&quot;
* &amp;lbrack;Impostazioni set di texture&amp;rbrack; la rimozione di un canale rimuove anche il canale sottostante
* &amp;lbrack;Export&amp;rbrack; Includi tutto e Reimposta tutto non prende in considerazione le Porzioni UV
* &amp;lbrack;Baker&amp;rbrack; durante la esegue i baking vengono visualizzati i baker deselezionati
* L’aggiornamento della risoluzione non viene considerato per le mappe con baking utilizzate come input
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; 3D Viewport si blocca quando si aggiunge un Materiale avanzato dopo l&#39;altro con la maschera Porzione UV selezionata
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Il Wireframe è ancora visibile per le porzioni nascoste con la modalità pittura passante
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Sketchfab&amp;rbrack; Problemi con il tipo di abbonamento &quot;più&quot;
* &amp;lbrack;Sketchfab&amp;rbrack; la casella di controllo &quot;Questa risorsa è privata&quot; non viene visualizzata dopo il cambio di account
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Contenuto&amp;rbrack; I predefiniti &quot;Deformazioni in movimento&quot; del pennello possono causare problemi di prestazioni
* &amp;lbrack;Plugin Photoshop&amp;rbrack; Messaggio nel registro: non compatibile con il flusso di lavoro Porzione UV
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; PYTHONPATH env var impedisce l&#39;avvio dell&#39;applicazione
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Typo nella documentazione Python

### 6.2.1 (2020.2.1)

*(Rilasciato: 29 luglio 2020*)Riepilogo: **Versione secondaria, Hotfix**

**Aggiunto:**

* Aggiungere la variabile di ambiente &quot;SUBSTANCE_PAINTER_VRAM_BUDGET&quot; per ignorare la quantità VRam della GPU
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Prestazioni&amp;rbrack; Non calcolare tutte le porzioni UV quando si utilizza lo strumento Riempimento poligonale

**Corretto:**

* &amp;lbrack;Iray&amp;brack; Salva rendering restituisce un errore e restituisce un&#39;immagine nera
* &amp;lbrack;Linux&amp;rbrack; Arresto anomalo dopo la schermata iniziale su CentOS 7.3
* &amp;lbrack;Linux&amp;rbrack; La quantità di Vram non viene rilevata correttamente con configurazioni specifiche
* &amp;lbrack;Arresto anomalo&amp;rbrack; apertura di un progetto con il nome di un set di texture duplicato
* &amp;lbrack;Engine&amp;rbrack; Problema di invalidamento della cache durante la modifica di una maschera
* &amp;lbrack;Elenco set di texture&amp;rbrack; Effetto font errato quando il set di texture è disattivato

**Problemi noti:**

* &amp;lbrack;Texture Set List&amp;rbrack; Impossibile nascondere la descrizione
* Problemi dell&#39;interfaccia utente di &amp;lbrack;Texture Set List&amp;rbrack;
* &amp;lbrack;Iray&amp;rbrack; il rendering PSD non si apre
* &amp;lbrack;Plugin Photoshop&amp;rbrack; non compatibile con il flusso di lavoro Porzione UV

### 6.2.0 (2020.2.0)

*(Rilasciato: 23 luglio 2020*)Riepilogo: **Versione principale con nuovo flusso di lavoro Porzione UV, pittura tra Porzioni UV e miglioramento delle prestazioni**

**Aggiunto:**

* Porzioni UV (UDIM)
* &amp;lbrack;Porzione UV&amp;rbrack; Pittura tra porzioni UV
* &amp;lbrack;Porzione UV&amp;rbrack; consente di scegliere tra flusso di lavoro nuovo e legacy per la Porzione UV
* &amp;lbrack;Porzione UV&amp;rbrack; Importa UDIM/Porzione UV sequenze di immagini come risorsa
* &amp;lbrack;Porzioni UV&amp;rbrack; Aggiungi elenco di Porzioni UV per set di texture nella finestra Elenco set di texture
* &amp;lbrack;Porzione UV&amp;rbrack; consente di modificare contemporaneamente la risoluzione di più Porzioni UV nelle impostazioni del set di texture
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;vista 2D&amp;rbrack; Visualizza la Porzione UV come griglia
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;vista 2D&amp;rbrack; pulsante Nuova finestra per visualizzare o nascondere le informazioni sulla Porzione UV
* &amp;lbrack;Porzione UV&amp;rbrack; per impostazione predefinita, per i progetti di Porzione UV imposta lo strumento di pittura su un singolo canale
* &amp;lbrack;Porzione UV&amp;rbrack; Nuovo pulsante nella barra degli strumenti contestuale per ignorare la Porzione UV mascherata durante il disegno
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; nuove icone Pila livelli per migliorare le prestazioni
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Migliorare le icone di Pittura e riempimento nella barra degli strumenti
* &amp;lbrack;Porzione UV maschera&amp;rbrack;&amp;lbrack;vista 2D&amp;rbrack; Consente di includere o escludere più Porzioni UV contemporaneamente (clic sinistro, CTRL+clic sinistro)
* &amp;lbrack;Maschera Porzione UV&amp;rbrack; Nuova maschera Porzione UV da includere, esclude le porzioni per livello con una nuova icona
* &amp;lbrack;Porzione UV maschera&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Visualizza il numero di Porzioni UV nell&#39;icona della maschera Porzione UV quando non tutte sono incluse
* &amp;lbrack;Porzione UV maschera&amp;rbrack;&amp;lbrack;2D/vista 3D&amp;rbrack; Aggiungi effetto al passaggio del mouse per visualizzare le Porzioni UV sotto il cursore
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Consente di selezionare e eseguire i baking Porzioni UV specifiche
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Aggiungi opzioni di selezione per set di texture/Porzione UV
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Opzione del menu di scelta rapida per selezionare le Porzioni UV di un set di texture
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Consenti selezione rapida in Set di texture/Porzioni UV mediante trascinamento
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Sostituire i pulsanti &quot;Tutto&quot; e &quot;Nessuno&quot; nelle mappe trama con opzioni di selezione più esplicite
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Visualizza il numero di texture da eseguire i baking
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Esporta&amp;rbrack; Consente di selezionare ed esportare Porzione UV specifica
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Esporta&amp;rbrack; Consenti selezione rapida di Porzione UV mediante trascinamento
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Aggiungi opzioni del menu a discesa per la Porzione UV
* &amp;lbrack;Porzioni UV&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Rende non disponibili alcuni predefiniti di esportazione se non funzionano con la Porzione UV (Adobe Dimension, Sketchfab, glTF, USD)
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Content&amp;rbrack; Aggiorna i predefiniti di esportazione per utilizzare il nuovo tag $udim
* &amp;lbrack;Porzione UV&amp;rbrack; migliora la segnalazione degli errori durante l&#39;importazione di trame con Isole UV sovrapposte
* &amp;lbrack;Porzione UV&amp;rbrack; Porzione UV compatibile in Iray
* &amp;lbrack;Porzione UV&amp;rbrack;&amp;lbrack;Scripting&amp;rbrack; Aggiungi la documentazione di esportazione delle Porzioni UV al documento Python
* Prestazioni
* &amp;lbrack;Prestazioni&amp;rbrack; Nuovo pulsante nella barra degli strumenti contestuale per sospendere il calcolo del motore durante il lavoro (MAIUSC+ESC)
* &amp;lbrack;Performance&amp;rbrack; Apertura più rapida del progetto ritardando il calcolo della cache del set di texture
* &amp;lbrack;Prestazioni&amp;rbrack; Non attendere il caricamento delle mappe mesh all&#39;apertura del progetto
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;2D/vista 3D&amp;rbrack; Non calcolare il canale maschera nella finestra della vista quando non viene utilizzato
* &amp;lbrack;Performance&amp;rbrack; Non bloccare l&#39;applicazione durante il caricamento delle mappe mesh visualizzate nelle finestre delle viste
* &amp;lbrack;Prestazioni&amp;rbrack; Migliora la velocità di salvataggio incrementale durante il salvataggio di un progetto
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Modificare le impostazioni di dilatazione predefinite per migliorare il risparmio di tempo e le dimensioni del progetto
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;Baker&amp;rbrack; Passa a scala di grigi su Baker specifici per migliorare il tempo di salvataggio e la dimensione del progetto
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Migliora le prestazioni del motore per esportare texture più velocemente
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Migliora la reattività quando si apre la finestra di dialogo di esportazione con molti set di texture
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Migliora le prestazioni quando si passa alla scheda &quot;Elenco esportazioni&quot;
* &amp;lbrack;Performance&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; Ridurre il tempo di avvio di Iray
* Altro
* &amp;lbrack;Baker&amp;rbrack; Aggiungi opzioni di selezione per set di texture
* Sposta la gestione delle istanze shader nelle impostazioni del set di texture
* &amp;lbrack;2D/vista 3D&amp;rbrack; Aggiungi un messaggio nella parte inferiore della finestra della vista per indicare il tipo di maschera modificato
* &amp;lbrack;Pila livelli&amp;rbrack; Nuova opzione nelle impostazioni per passare dalla miniatura precedente a quella nuova
* &amp;lbrack;Pila livelli&amp;rbrack; Aggiungi un feedback visivo per indicare lo stato di caricamento delle miniature
* &amp;lbrack;Proj&amp;rbrack; Nuova modalità di proiezione &quot;Riempi (come per porzione UV)&quot; per caricare le sequenze di immagini
* &amp;lbrack;Proj&amp;rbrack; Modifica la modalità di proiezione dei livelli di riempimento su &quot;Riempi (come per porzione UV)&quot; in casi specifici
* &amp;lbrack;Content&amp;rbrack; Ottimizza i predefiniti del pennello Carboncino per migliorare le prestazioni
* Aggiornamento di Iray alla versione 2020.0.0
* &amp;blocco;Esporta&amp;rbrack; Disattiva elenco delle esportazioni quando non è selezionato nulla
* Annulla contornamento automatico
* &amp;lbrack;Auto Unwrap&amp;rbrack; migliora la percentuale di successo del processo di annullamento automatico del wrapping
* &amp;lbrack;Auto Unwrap&amp;rbrack; parametrizzazione migliorata per aumentare velocità e stabilità

**Corretto:**

* &amp;lbrack;Alembic&amp;rbrack; I set di facce vengono ignorati durante l&#39;importazione dei file
* &amp;lbrack;Alembic&amp;rbrack; Tempo di caricamento infinito con file specifici
* &amp;lbrack;Import&amp;rbrack; Quando solo l&#39;estensione del file è diversa, viene importata una sequenza di immagini UDIM errata
* &amp;lbrack;Arresto anomalo&amp;rbrack; Se si tenta di aprire un progetto bloccato da un altro processo, viene generato un arresto anomalo
* &amp;lbrack;Proiezione&amp;rbrack; Artefatti sulla trama duplicata quando si utilizza la proiezione triplanare
* &amp;lbrack;Export&amp;rbrack; Il canale Emissivo non viene esportato con il formato USD
* &amp;lbrack;Content&amp;rbrack; Il Materiale avanzato &quot;Carboncino&quot; contiene tratti di pittura

**Problemi noti:**

* &amp;lbrack;Texture Set List&amp;rbrack; Impossibile nascondere la descrizione
* Problemi dell&#39;interfaccia utente di &amp;lbrack;Texture Set List&amp;rbrack;

### 6.1.3 (2020.1.3)

*(Rilasciato: 16 Giugno 2020*)Riepilogo: **Bugfix**

**Aggiunto:**

* &amp;lbrack;Export&amp;rbrack; Aggiungi impostazioni di spostamento nel file json dei parametri di Shader

**Corretto:**

* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Engine&amp;rbrack; Arresto anomalo durante il tentativo di cancellare e sostituire i canali esistenti
* &amp;lbrack;Arresto anomalo&amp;rbrack; Modifica dello shader dopo aver colorato una maschera in livelli di materiale
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Engine&amp;rbrack; Arresti anomali con alcuni progetti pesanti
* &amp;lbrack;Baker&amp;rbrack; La corrispondenza per nome non funziona con l&#39;OBJ esportato da zBrush
* &amp;lbrack;Spostamento&amp;rbrack;&amp;lbrack;SVT&amp;rbrack; le Texture non vengono visualizzate all&#39;apertura del progetto quando lo spostamento è attivo
* &amp;lbrack;Export&amp;rbrack; Alcune texture vengono esportate in grigio uniforme
* &amp;lbrack;Export&amp;rbrack; I set di texture disabilitati non devono essere esportati per i predefiniti di esportazione Dimension e Sketchfab
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; Arresto anomalo durante l&#39;utilizzo dell&#39;API JavaScript per accedere alla configurazione di esportazione nell&#39;evento onProjectOpened
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Javascript&amp;rbrack; onExportFinished() non viene chiamato dopo un&#39;esportazione

### 6.1.2 (2020.1.2)

*(Rilasciato: 28 maggio 2020*)Riepilogo: **Aggiornamento di Substance Engine e Baker**

**Aggiunto:**

* &amp;lbrack;Baker&amp;rbrack; Aggiornamento alla versione più recente
* &amp;lbrack;Baker&amp;rbrack; Nuovo metodo di campionamento in Occlusione ambientale, Curvatura, baker Thickness
* Aggiornamento alla versione di Substance Engine più recente
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consente la creazione di ResourceID per le risorse del progetto
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Consenti query sulle informazioni del canale
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; Aggiunta di funzioni di esecuzione e richiamata per simulare l&#39;esportazione di texture

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack; Normali non corrette nel baker World Space Normals che utilizza una Mappa normale tangente in casi specifici
* &amp;lbrack;Baker&amp;rbrack; Errore durante il eseguo i baking dell&#39;Occlusione ambientale con Optix quando non è presente un poly alto
* &amp;lbrack;Tratti dinamici&amp;rbrack; Ritardo durante il caricamento di un set di texture specifico
* &amp;lbrack;Export&amp;rbrack; Non deve esportare i set di texture disabilitati per USD, glTF
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; Impossibile modificare le nuove impostazioni del baker di curvatura
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; alg.texturesets.addChannel() in alcuni casi non restituisce un errore
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; Typo nella documentazione delle API Javascript per setProjectExportOptions()
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; esporta sempre tutti i set di texture
* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;Python&amp;rbrack; sys.eseguibile restituisce un percorso a python.exe anziché a Substance Painter
* Cache texture non compatibile tra i sistemi operativi Mac e Windows/Linux
* &amp;lbrack;Livelink UE4&amp;rbrack; per tutti gli insiemi di texture in una trama combinata viene utilizzato solo l&#39;ultimo materiale

**Problemi noti:**

* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Dimension&amp;rbrack;&amp;lbrack;Skecthfab&amp;rbrack; Non deve esportare i set di texture disattivati
* &amp;lbrack;Arresto anomalo&amp;rbrack; Cambia shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.1 (2020.1.1)

*(Rilasciato: 05 Maggio 2020*)Riepilogo: **Hotfix**

**Aggiunto:**

* &amp;lbrack;Export&amp;rbrack; Override stato del feedback visivo su TextureSet

**Corretto:**

* &amp;lbrack;Export&amp;rbrack; dimensione della finestra di Esportazione troppo grande per il monitor con risoluzione speciale e non ridimensionabile
* &amp;lbrack;Esporta&amp;rbrack; Le opzioni non vengono salvate dopo l&#39;esportazione
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo o impossibile esportare con il predefinito di esportazione &quot;dalla cache&quot;
* &amp;lbrack;Esporta&amp;rbrack; se si annulla l&#39;esportazione, viene generata una mappa vuota aggiuntiva imprevista
* &amp;lbrack;Esporta&amp;rbrack; Correggi impostazioni predefinite esportazione virtuale
* &amp;lbrack;Python&amp;rbrack; PYTHONPATH env var non viene considerato
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;Export&amp;rbrack; L’annullamento dell’esportazione tramite Python restituisce un errore di eccezione
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;Export&amp;rbrack; export_project_texture un risultato errato con il formato di file psd
* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo su Linux con Raytracing GPU

**Problemi noti:**

* &amp;lbrack;JavaScript&amp;rbrack; Impossibile modificare le nuove impostazioni del baker di curvatura
* &amp;lbrack;JavaScript&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Esporta sempre tutti i set di texture
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Non deve esportare i set di texture disabilitati
* &amp;lbrack;Arresto anomalo&amp;rbrack; Cambia shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.0 (2020.1.0)

*(Rilasciato: 22 aprile 2020*)Riepilogo: **Versione principale con nuova esportazione di texture e trama (con spostamento e tassellatura), srotolamento UV aggiornato con più controlli, nuovi baker, nuova API per il pitone di scripting, migliore esperienza utente per la proiezione di decalcomanie e nuovi contenuti**

**Aggiunto:**

* Nuova esportazione di texture e trama
* &amp;lbrack;Export&amp;rbrack; Nuova interfaccia di esportazione
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Esporta tab&amp;rbrack; Consenti la selezione dei canali delle mappe da esportare per set di texture
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Esporta tab&amp;rbrack; Consenti la modifica delle dimensioni del set di texture per tutti i set di texture in un&#39;unica azione
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Export tab&amp;rbrack; Consente un modello diverso per set di texture (eccetto USD, glTF, Sketchfab e Dimension)
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Esporta tab&amp;rbrack; Attivazione e disattivazione rapida di mappe e set di texture
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Export tab&amp;rbrack; Risoluzione di esportazione 8192x8192 non più sperimentale
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Export tab&amp;rbrack; Consenti modifica del formato e della profondità di bit del file per mappa
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Esporta tab&amp;rbrack; Consenti di ripristinare i valori dei parametri predefiniti
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Export tab&amp;rbrack; Consente di salvare le impostazioni senza esportarle
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;Modelli di output tab&amp;rbrack; Rinomina la scheda &quot;Configurazione&quot; in &quot;Modelli di output&quot;
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Modelli di output tab&amp;rbrack; Consenti definizione di formato file e profondità di bit per mappa predefinita
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Elenco di esportazioni tab&amp;rbrack; Nuova scheda di anteprima per riepilogare e visualizzare il processo di esportazione
* &amp;lbrack;Importa/esporta mesh&amp;brack; Importa/esporta ottimizzazione prestazioni tempo
* &amp;lbrack;Esporta trama&amp;rbrack; Esporta trama in FBX
* &amp;lbrack;Esporta trama&amp;rbrack; Esporta trama con spostamento e tassellatura
* &amp;lbrack;Esporta mesh&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuove impostazioni per il ricalcolo del vertice normale, applica la triangolazione
* &amp;lbrack;Esporta mesh&amp;brack; Esporta topologia mesh originale con nuovi UV generati dallo srotolamento automatico
* Aggiornamento dello srotolamento UV automatico con più controlli
* &amp;lbrack;UV Unwrapping&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Aggiungi impostazione per attivare lo srotolamento UV automatico nella nuova finestra del progetto
* &amp;lbrack;UV Unwrapping&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuove opzioni per controllare i passaggi di unwrapping (cuciture, unwrapping, impacchettamento)
* &amp;lbrack;UV Unwrapping&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Consenti la conservazione di cuciture/unwrapping/impacchettamento di unwrapping esistenti
* &amp;lbrack;UV Unwrapping&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuove opzioni per ricalcolare completamente i passaggi di unwrapping
* &amp;lbrack;UV Unwrapping&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova opzione per controllare le dimensioni del margine (nessuno, piccolo, medio e grande)
* Nuovi Baker
* &amp;lbrack;Baker&amp;rbrack; Sostituisce la vecchia curvatura con la nuova curvatura dalla trama
* &amp;lbrack;Baker&amp;rbrack; Aggiungi corrispondenza per nome, opzione per ignorare il backface nel baker &quot;Occlusione ambientale&quot;
* &amp;lbrack;Baker&amp;rbrack; Aggiungi opzione piano terreno nel baker &quot;Occlusione ambientale&quot;
* Nuova API Python per scripting (3.7.6)
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo menu di script per Python
* &amp;lbrack;Python&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova documentazione Python nel menu Aiuto
* &amp;lbrack;Python&amp;rbrack; Esposizione moduli pitone Substance Painter: substance_painter, alg, display, project.setting, project, texturesets, ui
* &amp;lbrack;Python&amp;rbrack; Esposizione del nuovo modulo Python &quot;substance_painter&quot;
* &amp;lbrack;Python&amp;rbrack; Esposizione del nuovo sottomodulo Python: alg, display, log, project, resource, texturesets, ui
* &amp;lbrack;Python&amp;rbrack; Listener per le modifiche al progetto
* &amp;lbrack;Python&amp;rbrack; Nuovi esempi nella documentazione Python
* &amp;lbrack;JavaScript&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Plugin sostituito da JavaScript
* &amp;lbrack;Viewport&amp;rbrack; consente di creare una proiezione decalcomania &quot;trascinando/rilasciando + ALT&quot; una risorsa dallo scaffale
* Nuovo contenuto
* &amp;lbrack;Content&amp;rbrack; 5 nuovi materiali decalcomanie da Substance Source
* &amp;laback;Content&amp;brack; Aggiungi nuovi modelli di progetto ed esporta predefiniti per il modulo di rendering Maxwell
* &amp;lbrack;Content&amp;rbrack; Aggiungi modello di progetto per esportazione Keyshot 9
* &amp;lbrack;Content&amp;rbrack; Aggiorna il predefinito di esportazione Keyshot 9 per supportare spostamento e emissivo
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Esportazione&amp;rbrack; Aggiornamento di tutti i predefiniti di esportazione in base alle versioni più recenti dei motori di gioco e dei moduli di rendering
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Esportazione&amp;rbrack; Aggiorna i file dei predefiniti di esportazione per utilizzare le nuove impostazioni di formato e dithering
* &amp;lbrack;Content&amp;rbrack; nuovi modelli e shader per il supporto del materiale VRay (VRayMtl)
* &amp;lbrack;Pila livelli&amp;rbrack; Consente l&#39;eliminazione degli effetti di livello utilizzando l&#39;icona del cestino o la scelta rapida da tastiera della tastiera Elimina
* Rimuovere la Substance Source del plug-in (utilizzare il modulo di avvio con la funzionalità &quot;Invia a&quot;)
* &amp;lbrack;Windows&amp;rbrack; Non visualizzare l&#39;avviso TDR sulle GPU di fascia alta

**Corretto:**

* Problemi di traduzione nella finestra di dialogo Nuovo file di progetto
* &amp;lbrack;Baker&amp;rbrack; L’impostazione &quot;Salva file di scena preelaborato&quot; non funziona più
* &amp;lbrack;Proiezione Planari&amp;rbrack; Proiezione non funziona su trame con UV ripetuti
* &amp;lbrack;Decal&amp;rbrack; differenza di comportamento nel canale normale quando si utilizzano diverse modalità di proiezione del livello di riempimento
* &amp;lbrack;Sfumino&amp;rbrack;&amp;lbrack;Clona /Clone&amp;rbrack; Può apparire un artefatto quando si disegna in una maschera
* &amp;lbrack;Engine&amp;rbrack; Arresto anomalo con contenuto livello specifico
* &amp;lbrack;Engine&amp;rbrack; arresto anomalo casuale quando si disegna in alcuni casi
* &amp;lbrack;Punto di ancoraggio&amp;rbrack; il riferimento a una maschera vuota restituisce sempre il bianco
* &amp;lbrack;Export&amp;rbrack; Livello non preso in considerazione in alcune particolari configurazioni dello stack
* &amp;lbrack;Esporta mesh&amp;rbrack; Impossibile esportare con un percorso contenente caratteri speciali
* &amp;lbrack;Esporta mesh&amp;rbrack; Impossibile leggere i file glTF quando esportati da Linux o MacOS
* &amp;lbrack;Importa mesh&amp;rbrack; La reimportazione di DAE, PLY o glTF non funziona come previsto

**Problemi noti:**

* &amp;lbrack;Scripting&amp;rbrack;&amp;lbrack;JavaScript&amp;rbrack; Impossibile modificare le nuove impostazioni del baker di curvatura
* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo su Linux con Raytracing GPU
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Non deve esportare i set di texture disabilitati
* &amp;lbrack;Arresto anomalo&amp;rbrack; Cambia shader dopo aver dipinto una maschera in livelli di materiale

## Versione 5

### 5.3.3 (2019.3.3)

*(Rilasciato: 06 febbraio 2020*)Riepilogo: **Bugfix con aggiornamento a Iray 2019.3**

**Aggiunto:**

* Aggiornamento a Iray 2019.3
* &amp;lbrack;Log&amp;rbrack; indica un BIOS obsoleto per la CPU Ryzen che causa arresto anomalo durante la esegue i baking
* &amp;lbrack;ABR&amp;rbrack; Estrai alfa ABR da riporre

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack; la Esegue i baking non riesce se la trama High-poly non include UV
* &amp;lbrack;Linux&amp;rbrack; Le scelte rapide personalizzate del mouse non vengono salvate
* &amp;blocca;Pennello&amp;sfoglia; Il contorno scompare con alcune forme alfa
* &amp;lbrack;Tablet&amp;rbrack; rilevamento errato durante lo spostamento dei cursori
* &amp;lbrack;Shortcuts&amp;rbrack; Impossibile impostare una scelta rapida da tastiera con &quot;Ctrl+Alt+MouseClick&quot;
* &amp;lbrack;Shelf&amp;rbrack; Impossibile visualizzare la descrizione comandi della risorsa quando si utilizza una tavoletta a penna
* &amp;lbrack;vista 2D&amp;rbrack;&amp;lbrack;Export&amp;rbrack; il predefinito non tiene conto delle informazioni normali
* Si verifica un blocco con quando si disegna in allineamento UV con determinati pennelli
* Colorare sotto un filtro crea un artefatto sul tratto in corso
* &amp;lbrack;Viewport&amp;rbrack; cache di texture errata nella finestra della vista dopo la reimportazione di una trama
* &amp;lbrack;Arresto anomalo&amp;rbrack; errore durante il salvataggio dopo l&#39;esportazione in Photoshop
* &amp;lbrack;Arresto anomalo&amp;rbrack; scrittura di simboli speciali nel prefisso durante l&#39;importazione delle risorse
* &amp;lbrack;Arresto anomalo&amp;rbrack; Fare clic sul riferimento in Proprietà punto di ancoraggio
* &amp;lbrack;Punti di ancoraggio&amp;rbrack; Il canale non si aggiorna quando è presente un filtro tra punto di ancoraggio e riferimento
* Il collegamento dell’URL del raggio nel menu Aiuto non funziona

**Problemi noti:**

* &amp;lbrack;UV Unwrapping&amp;rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &amp;lbrack;UV Unwrapping&amp;rbrack; Vertici con le stesse coordinate vengono uniti
* &amp;lbrack;UV Unwrapping&amp;rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme tra set di texture
* &amp;lbrack;UV Unwrapping&amp;rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &amp;lbrack;UV Unwrapping&amp;rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped

### 5.3.2 (2019.3.2)

*(Rilasciato: 21 Gennaio 2020*)Riepilogo: **Bugfix**

**Corretto:**

* L’apertura di un progetto che è stato salvato in modalità solo canale non visualizza la trama
* Il riquadro di visualizzazione non viene sempre aggiornato quando si disegna sotto il livello utilizzando lo strumento Clona

**Problemi noti:**

* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo relativo al multithreading su CPU Ryzen
* &amp;lbrack;UV Unwrapping&amp;rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &amp;lbrack;UV Unwrapping&amp;rbrack; Vertici con le stesse coordinate vengono uniti
* &amp;lbrack;UV Unwrapping&amp;rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme tra set di texture
* &amp;lbrack;UV Unwrapping&amp;rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &amp;lbrack;UV Unwrapping&amp;rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped

### 5.3.1 (2019.3.1)

*(Rilasciato: 20 Dicembre 2019*)Riepilogo: **Hotfix**

**Corretto:**

* Arresto anomalo quando si lavora su trame con Proiezioni UV specifiche
* &amp;lbrack;ABR&amp;rbrack; Arresto anomalo quando si passa da un predefinito Photoshop a un altro
* &amp;lbrack;Linux&amp;rbrack; Impossibile avviare la Substance Painter su CentOS 7.4 a causa di un problema di dipendenza libGLX
* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo durante la esegue i baking dopo aver utilizzato File > Pulisci
* &amp;lbrack;Baker&amp;rbrack; Esegue i baking la finestra di dialogo di avanzamento si blocca dopo l&#39;annullamento
* &amp;lbrack;Baker&amp;rbrack; Eseguire i baking la trama dopo l&#39;esportazione della texture non funziona
* &amp;lbrack;Baker&amp;rbrack; Utilizzo di risultati &quot;Corrispondenza per nome&quot; con Mappe trama nere
* &amp;lbrack;Baker&amp;rbrack; Cage non viene considerato
* &amp;lbrack;Shelf&amp;rbrack; l&#39;importazione di file PSD genera immagini interrotte
* &amp;lbrack;Sample&amp;rbrack; Il progetto di esempio &quot;Mat&quot; ha videocamere danneggiate e un predefinito di esportazione errato

**Problemi noti:**

* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo relativo al multithreading su CPU Ryzen
* &amp;lbrack;UV Unwrapping&amp;rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &amp;lbrack;UV Unwrapping&amp;rbrack; Vertici con le stesse coordinate vengono uniti
* &amp;lbrack;UV Unwrapping&amp;rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme tra set di texture
* &amp;lbrack;UV Unwrapping&amp;rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &amp;lbrack;UV Unwrapping&amp;rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped

### 5.3.0 (2019.3.0)

*(Rilasciato: 17 dicembre 2019*)Riepilogo: **Versione principale con miglioramento dell’esperienza utente di pittura a mano, utilizzo dei tablet, srotolamento automatico degli UV nella versione beta (0.3.0) e diversi nuovi contenuti per la pittura a mano**

**Aggiunto:**

* Integrazione dello srotolamento UV automatico della versione 0.3.0 in Substance Painter
* &amp;lbrack;UV unwrapping&amp;rbrack; srotolamento UV automatico nella Substance Painter quando non sono presenti UV o UV parziali
* &amp;lbrack;UV unwrapping&amp;rbrack; un&#39;impostazione globale per attivarla e disattivarla
* &amp;lbrack;UV unwrapping&amp;rbrack; Versione riportata nel file di registro
* &amp;lbrack;UV unwrapping&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Indica l&#39;avanzamento dello srotolamento UV
* &amp;lbrack;UI&amp;rbrack; Nuove impostazioni nella barra degli strumenti contestuale per selezionare l&#39;anteprima del pennello: Anteprima completa, Contorno pennello e mirino
* &amp;lbrack;Strumento&amp;rbrack; Nuovo metodo di fusione avanzato nella sezione alfa: Schiarisci (massimo) oltre a Normale
* &amp;lbrack;Pila livelli&amp;rbrack; opzione di correzione gamma per livello per alfa o maschera (menu di scelta rapida)
* &amp;lbrack;Pila livelli&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Aggiungi l’icona &quot;i&quot; quando un livello alfa è corretto da gamma
* &amp;lbrack;Tablet&amp;rbrack;&amp;lbrack;Tool&amp;rbrack; Esposizione della pressione minima per dimensioni e flusso
* &amp;lbrack;Tablet&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova impostazione nella barra degli strumenti contestuale per selezionare la pressione della curva: lineare, facile da inserire e facile da eliminare
* &amp;lbrack;Tablet&amp;rbrack;&amp;lbrack;UX&amp;rbrack; Aggiungi Ctrl+Alt+clic per scorrere
* Importare pennelli predefiniti di Photoshop (formato ABR)
* &amp;lbrack;ABR&amp;rbrack; Supporta i parametri Shape
* &amp;lbrack;ABR&amp;rbrack; supporta i parametri della dinamica delle forme
* &amp;lbrack;ABR&amp;rbrack; supporta parametri di trasferimento
* &amp;lbrack;ABR&amp;rbrack; supporta i parametri di dispersione
* &amp;lbrack;ABR&amp;rbrack;&amp;lbrack;Tratti dinamici&amp;rbrack; Supporto di rotondità e capovolgimento
* &amp;lbrack;ABR&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Esporre la struttura di cartelle dei pennelli nell&#39;Editor filtri
* &amp;lbrack;ABR&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Aggiungi icona Photoshop nelle miniature
* &amp;lbrack;ABR&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Aggiungi elenco di parametri non supportati nella miniatura dettagliata ABR
* &amp;lbrack;Tool&amp;rbrack;&amp;lbrack;Tratti dinamici&amp;rbrack; Nuova impostazione del tratto dinamico per controllare il numero di valori di inizializzazione casuali da generare
* &amp;lbrack;Tool&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Aggiungi nuove impostazioni di distribuzione e asse per la variazione di dispersione
* &amp;lbrack;Scelta rapida da tastiera&amp;rbrack; Aggiungi Ctrl+Maiusc+B per aprire la finestra di Esegue i baking
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Menu&amp;rbrack; Aggiungi voce nel menu &quot;Modifica&quot; per aprire la finestra di Esegue i baking
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Settings&amp;rbrack; Miglioramento dell&#39;allineamento dell&#39;elenco delle scelte rapide
* &amp;blocco;UI&amp;rbrack; Sostituisce le icone dei controlli di pressione (dimensioni e flusso) con pulsanti di attivazione/disattivazione
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Consenti di mettere a fuoco separatamente i riquadri di visualizzazione 2D e 3D
* Aggiornamento a QT 5.12.5
* &amp;lbrack;UI&amp;rbrack; Indica l&#39;avanzamento del caricamento della trama
* &amp;lbrack;Substance&amp;rbrack; Aggiungi il supporto per l&#39;intervallo non bloccato e morbido con i cursori
* &amp;lbrack;Substance&amp;rbrack; Aumenta la precisione dei parametri della Substance fino a 6 decimali
* &amp;lbrack;Substance&amp;rbrack; tiene conto del passo definito da un parametro
* &amp;lbrack;Substance&amp;rbrack; Ottimizza la generazione di tratti dinamici con il supporto delle condizioni nei dati utente
* &amp;lbrack;Substance&amp;rbrack; Consenti di designare un output del grafico come maschera per tutti i canali tramite userdata
* &amp;lbrack;Content&amp;rbrack; Aggiorna il progetto di esempio &quot;Mat&quot; con topologia descrittiva per lo spostamento, nuova mappa ID e nuove fotocamere
* &amp;lbrack;Content&amp;rbrack; Integra 3 nuovi filtri (MatFx): fumetto, acquerello, Pittura a olio (ispirato al lavoro di Emrecan Cubukcu)
* &amp;lbrack;Content&amp;rbrack; Integra 102 pennelli predefiniti di Photoshop dai pacchetti di Kyle T. Webster
* &amp;lbrack;Content&amp;rbrack; Integra 18 nuovi pennelli predefiniti: Pittura freccia a rullo, Pittura testo avviso rullo, Carboncino fine e altri ancora
* &amp;lbrack;Content&amp;rbrack; Integra 9 nuove alfa: Rullo Pittura di Brush Maker, Photoshop di Brush Maker, Pattern di pennelli e altro ancora
* &amp;lbrack;Content&amp;rbrack; Integra 2 nuovi strumenti predefiniti: Gouache Dense e Gouache Faded
* &amp;lbrack;Content&amp;rbrack; Integra 1 nuovo generatore : Controllo UV (Isole UV evidenziazione e cuciture)
* &amp;lbrack;Content&amp;rbrack; Integra 2 nuovo predefinito di esportazione: Keyshot 9+ e Spark AR Studio
* &amp;lbrack;Content&amp;rbrack; Integra 1 nuovo modello di progetto: Spark AR Studio (Facebook)

**Corretto:**

* &amp;blocco;Tablet&amp;brack; Annullamento dei tratti dello stilo (CTRL+Z) è più lento dell&#39;annullamento dei tratti del mouse
* &amp;lbrack;Tablet&amp;rbrack; pressione iniziale e finale non considerate quando si disegna una linea retta
* &amp;blocco;Tablet&amp;rbrack; Il primo timbro viene disegnato due volte quando si utilizza una linea retta
* &amp;lbrack;Tablet&amp;rbrack; Migliora il supporto per le scelte rapide da tastiera per tablet Huion
* &amp;lbrack;Tablet&amp;rbrack; supporto migliorato per i pulsanti penna Huion
* &amp;lbrack;Tablet&amp;brack; scostamento tra l&#39;anteprima del pennello e il timbro disegnato
* &amp;lbrack;Tablet&amp;brack; Le scelte rapide per modificare i pennelli con penna conducono in rari casi a prestazioni ridotte
* &amp;lbrack;Tablet&amp;rbrack; ritardo durante la pittura su un livello specifico
* In rari casi, quando si cambia finestra, possono verificarsi texture sfocate
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Substance&amp;rbrack; Gli input dell&#39;immagine non vengono sempre visualizzati
* L’opzione Pulisci non rimuove dal ripiano i predefiniti importati in un progetto
* &amp;lbrack;Tool&amp;rbrack;&amp;lbrack;Dynamic Stroke&amp;rbrack; Problema di prestazioni durante l&#39;ottimizzazione del conteggio dei cicli del timbro
* In rari casi, problemi di aggiornamento durante l’uso della modalità finestra vista 3D/2D
* Colorare un tratto molto lungo può portare a un blocco
* &amp;lbrack;Strumento&amp;rbrack; problema di prestazioni quando si disegna con tratti dinamici specifici
* &amp;lbrack;UI&amp;rbrack; la barra degli strumenti contestuale visualizza ancora le proprietà del pennello quando si seleziona una cartella
* I valori dell&#39;asse delle simmetrie non vengono ripristinati
* L’importazione di texture EXR con valori a virgola mobile è completamente nera
* Alt + clic su un canale per isolare non funziona per filtro e generatore
* &amp;lbrack;Export&amp;rbrack; arresti anomali di progetto specifici all&#39;esportazione
* &amp;lbrack;Substance&amp;rbrack; Valore predefinito errato nel menu a discesa se il parametro è nascosto da Visibile se
* &amp;lbrack;Shader&amp;rbrack; i canali definiti tramite la creazione di livelli di materiale non sono ordinati allo stesso modo nell&#39;interfaccia utente
* &amp;lbrack;Shelf&amp;rbrack; I metadati dei predefiniti non vengono salvati sul disco

**Problemi noti:**

* &amp;lbrack;UV Unwrapping&amp;rbrack; L&#39;elaborazione di trame poly elevate può richiedere molto tempo
* &amp;lbrack;UV Unwrapping&amp;rbrack; Vertici con le stesse coordinate vengono uniti
* &amp;lbrack;UV Unwrapping&amp;rbrack; La generazione UV potrebbe non riuscire su alcune parti mesh in alcuni rari casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* &amp;lbrack;UV Unwrapping&amp;rbrack; rapporto testuale non uniforme tra set di texture
* &amp;lbrack;UV Unwrapping&amp;rbrack; l&#39;Isola UV generata può essere molto allungata e in alcuni casi non può essere contenuta nello spazio UV
* &amp;lbrack;UV Unwrapping&amp;rbrack; le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV unwrapped
* L’esempio di riunione presenta alcuni problemi con le videocamere importate

### 5.2.3 (2019.2.3)

*(Rilasciato: 23 ottobre 2019*)Riepilogo: **Versione Bugfix**

**Aggiunto:**

* &amp;lbrack;Texture Set List&amp;rbrack; Pulsante Aggiungi per attivare/disattivare rapidamente la modalità di attivazione
* &amp;lbrack;Log&amp;rbrack; Aggiungi il numero di versione di Windows 10 nel file di registro
* Aggiornamento alla versione più recente di Substance Engine
* &amp;lbrack;MacOS&amp;rbrack; ha autenticato il software per soddisfare i nuovi requisiti di distribuzione di MacOS Catalina

**Corretto:**

* &amp;lbrack;Plugin&amp;brack; L&#39;origine del plug-in non funziona
* &amp;lbrack;MacOS&amp;rbrack;&amp;lbrack;Shader&amp;rbrack; Mac OS 10.14.5 e AMD: la creazione di livelli di materiale non funziona come previsto

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.2 (2019.2.2)

*(Rilasciato: 20 settembre 2019*)Riepilogo: **Versione Bugfix**

**Corretto:**

* L&#39;importazione di risorse tramite script può provocare un arresto anomalo
* &amp;lbrack;Plugin&amp;rbrack; Il download di materiale dall&#39;origine può provocare un arresto anomalo

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.1 (2019.2.1)

*(Rilasciato: 17 settembre 2019*)Riepilogo: **Versione Bugfix**

**Corretto:**

* &amp;lbrack;Mac&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Impossibile aprire i file USDZ esportati da MacOS
* &amp;lbrack;Set di texture&amp;rbrack; impossibile isolare un set di texture con il modificatore ALT
* &amp;lbrack;Shelf&amp;rbrack; I predefiniti, i Materiali avanzati e le Maschere avanzate vengono sempre modificati quando si esce dall&#39;applicazione
* &amp;lbrack;Pila livelli&amp;rbrack; Impossibile selezionare l&#39;effetto dopo aver eliminato un altro effetto
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

* &amp;lbrack;Baker&amp;rbrack; Supporto aggiunto per Raytracing GPU con DXR e OptiX (Occlusione ambientale, Thickness)
* &amp;lbrack;Baker&amp;rbrack; ottimizzazioni e accelerazioni per il Raytracing CPU
* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;Modalità Vis&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova modalità visualizzazione eseguita i baking nella finestra della vista
* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;Preferenze&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova opzione di esegue i baking per abilitare-disabilitare il Raytracing GPU
* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Rielaborazione della finestra di dialogo della barra di avanzamento
* &amp;lbrack;Baker&amp;rbrack; miglioramento dei messaggi di avviso e di errore
* &amp;lbrack;Baker&amp;rbrack; Consente l&#39;annullamento più reattivo del eseguo i baking
* &amp;lbrack;Baker&amp;rbrack; riapri la finestra di esegue i baking dopo aver fatto clic su annulla
* &amp;lbrack;Proj&amp;rbrack;&amp;lbrack;UX&amp;rbrack; Miglioramento della usabilità del manipolatore di rotazione
* &amp;lbrack;Settings&amp;brack; Opzione per migliorare le prestazioni riducendo la risoluzione della finestra della vista per gli schermi HDPI
* &amp;lbrack;Scripting&amp;rbrack; Cambia la risoluzione del set di texture
* &amp;lbrack;Scripting&amp;rbrack; Ottieni set di texture selezionato
* &amp;lbrack;Scripting&amp;rbrack; Consente all&#39;utente di selezionare un set di texture
* &amp;lbrack;Scripting&amp;rbrack; Funzione per sapere quando è stata modificata la selezione del set di texture
* &amp;lbrack;Shelf&amp;rbrack; aggiunti 40 nuovi materiali avanzati
* &amp;lbrack;Shelf&amp;rbrack; aggiunta di 20 nuove maschere avanzate

**Corretto:**

* &amp;lbrack;Pila livelli&amp;rbrack; Blocco dell&#39;interfaccia utente durante la selezione multipla dei livelli
* &amp;lbrack;Pila livelli&amp;rbrack; il raggruppamento di numerosi livelli blocca l’interfaccia utente per un tempo più lungo del solito
* &amp;lbrack;Pila livelli&amp;rbrack; In alcuni casi è possibile selezionare contemporaneamente un livello e un effetto
* I grafici delle Substance utilizzati negli strumenti di pittura non vengono generati alla risoluzione giusta
* &amp;lbrack;Baker&amp;rbrack; il pulsante &quot;Esegue i baking tutti i set di texture&quot; non è disattivato quando non è selezionato alcun baker
* &amp;lbrack;MacOS&amp;rbrack; Disattiva il messaggio di avviso sulla tassellatura
* Lo strumento Proiezione non ha un’anteprima quando viene utilizzato con una maschera
* Arresti anomali e progetti danneggiati durante il tentativo di salvataggio con spazio su disco insufficiente
* &amp;lbrack;Shelf&amp;rbrack; Arresto anomalo durante l&#39;importazione di una risorsa su disco tramite shelf con spazio insufficiente
* &amp;lbrack;Shelf&amp;rbrack; Arresto anomalo durante il ripristino del predefinito di sessione
* &amp;lbrack;Shelf&amp;rbrack; L&#39;importazione di un predefinito con un nome che termina con uno spazio genera un arresto anomalo
* &amp;lbrack;Shelf&amp;rbrack; L&#39;importazione di una risorsa con un prefisso che termina con uno spazio vuoto genera un arresto anomalo

**Problemi noti:**

* Impossibile importare file alembici con suddivisioni
* Arresti anomali rari durante l’importazione di alcuni file Alembic
* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.1.3 (2019.1.3)

*(Rilasciato: 01 luglio 2019*)Riepilogo: **Bugfix con 2 nuove funzioni**

**Aggiunto:**

* Consente di specificare il budget VRam con una riga di comando (ad esempio: budget vram 4096)
* &amp;lbrack;QML&amp;rbrack; Esposizione delle proprietà wrapMode ed elide dei pulsanti e delle caselle di controllo QML

**Corretto:**

* &quot;Segui tracciato&quot; non funziona sempre
* La mappatura dei canali non funziona con SBSAR utilizzato negli slot a canale singolo
* &amp;lbrack;Pila livelli&amp;rbrack; prestazioni ridotte durante lo scorrimento con livelli nascosti
* &amp;lbrack;TextureSet&amp;rbrack; Arresto anomalo quando si fa clic tra le maschere
* &amp;lbrack;SVT&amp;rbrack; Spostamento non visualizzato correttamente e in alcuni casi sfarfalla
* &amp;lbrack;Alembic&amp;rbrack; Arresto anomalo con trama che utilizza le normali dei punti invece delle normali dei vertici
* &amp;lbrack;Alembic&amp;rbrack;&amp;lbrack;Log&amp;rbrack; Segnala un errore nel registro se il file Alembic non è supportato durante l&#39;importazione

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

* &amp;lbrack;Substance&amp;rbrack; Visibile Se non viene preso in considerazione per le Immagini di input
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Engine&amp;rbrack; La modifica della risoluzione del set di texture in alcuni casi genera un arresto anomalo
* &amp;lbrack;Engine&amp;rbrack; In alcuni casi vengono visualizzate texture nere casuali
* &amp;lbrack;Pila livelli&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente
* &amp;lbrack;Pila livelli&amp;rbrack; l&#39;opacità non ha effetto sull&#39;effetto Pittura con il metodo di fusione Attraversa
* &amp;lbrack;Pila livelli&amp;rbrack; L&#39;input del filtro Height al normale non si aggiorna correttamente con il tratto del pennello gomma
* &amp;lbrack;LayersStack&amp;rbrack; Arresto anomalo quando si annulla l&#39;eliminazione di una maschera avanzata
* Sfarfallio del wireframe con ombre e anti-alias temporale attivati
* &amp;lbrack;Spostamento&amp;rbrack; ritardo su AMD con alcune trame pesanti
* &amp;lbrack;Windows&amp;rbrack; Arresto anomalo durante l&#39;apertura di alcuni progetti tramite Esplora file
* &amp;lbrack;Istogramma&amp;rbrack; Arresto anomalo durante la rimozione di una maschera con punto di ancoraggio in alcuni casi
* Arresto anomalo di generazione dell’anteprima in alcuni rari casi
* &amp;lbrack;Arresto anomalo&amp;rbrack; Impossibile riaprire un progetto con troppi strumenti di clonazione e sfumino
* Nessuna trama visualizzata in modalità materiale dopo il salvataggio in alcuni casi
* &amp;lbrack;Scripting&amp;rbrack; alg.mapexport.documentStructure() restituisce valori errati per le cartelle

**Problemi noti:**

* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione

### 5.1.0 (2019.1.0)

*(Rilasciato: 23 aprile 2019*)Riepilogo: **Tratto dinamico con nuovi contenuti dedicati, Spostamento e tassellatura in tempo reale e raggi X, effetto Maschera di confronto, simmetria radiale, Planari e Proiezione sferica**

**Aggiunto:**

* &amp;lbrack;Strumento&amp;rbrack; tratto dinamico: Substance la variazione accanto a un tratto pennello
* &amp;lbrack;Dynamic stroke&amp;rbrack; esporre il nuovo parametro dell&#39;indice del timbro con le opzioni
* &amp;lbrack;Dynamic stroke&amp;brack; tiene conto del parametro $time
* &amp;lbrack;Dynamic stroke&amp;brack; genera un nuovo parametro $randomseed per tratto e per timbro
* &amp;blocco;Traccia dinamica&amp;rbrack; Avvia un indice di traccia dinamica da un numero casuale
* &amp;lbrack;Dynamic stroke&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Aiuta a trovare una risorsa traccia dinamica con l&#39;icona dedicata
* Spostamento e tassellatura nella finestra della vista in tempo reale
* Spostamento e tassellatura in Iray
* &amp;lbrack;Shader impostazioni&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova scheda per il controllo dello spostamento e della tassellatura
* &amp;lbrack;Pila livelli&amp;rbrack; Nuovo effetto Confronta maschera: genera una maschera confrontando due canali
* &amp;lbrack;Pila livelli&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuova voce nel menu di scelta rapida &quot;Aggiungi maschera con combinazione di height&quot; per inserire un effetto CompareMask
* &amp;lbrack;Simmetria&amp;rbrack; Nuova modalità simmetria: pittura radiale
* &amp;lbrack;Simmetria impostazioni&amp;rbrack; Espandi entrambe le sezioni &quot;Impostazioni&quot; e &quot;Schermo&quot;
* &amp;lbrack;Simmetria impostazioni&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Anteprima per pittura radiale
* Esporre due nuove modalità di proiezione: planare e sferica
* &amp;lbrack;Proj&amp;rbrack; Nuova modalità di ritaglio forma per tutte le proiezioni
* &amp;lbrack;Proj&amp;rbrack; modalità Planari con il nuovo manipolatore: strumento superficie
* &amp;lbrack;Proj&amp;rbrack;&amp;lbrack;Scelta rapida da tastiera&amp;rbrack; Scelta rapida da tastiera MAIUSC+W per lo strumento superficie
* &amp;lbrack;Proj&amp;rbrack; Planare maschera di proiezione con sfoltimento profondità e taglio dello sfondo
* &amp;lbrack;Manipolatore&amp;rbrack; miglioramento del manipolatore di rotazione su tutti e tre gli assi per il triplanare
* &amp;lbrack;Tool&amp;rbrack;&amp;lbrack;UX&amp;rbrack; Se si fa clic con il tasto Alt su un canale, questo viene attivato o disattivato
* &amp;lbrack;Engine&amp;rbrack; Aggiornamento alla versione più recente di Substance Engine
* &amp;lbrack;Set&amp;rbrack texture; selezione multipla e modifica della risoluzione
* &amp;lbrack;Set di texture&amp;rbrack; Attivazione e disattivazione rapida dei set di texture
* &amp;lbrack;Set di texture&amp;rbrack; Combina solo e tutte le opzioni in un nuovo menu
* &amp;lbrack;Texture set&amp;rbrack;&amp;lbrack;Pila livelli&amp;rbrack; Nuova icona per attivazione e disattivazione
* &amp;lbrack;Pila livelli&amp;rbrack;&amp;lbrack;UX&amp;rbrack; Inserisci effetti sopra a quelli già selezionati
* &amp;lbrack;Pila livelli&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Rielabora stile di selezione visualizzazione Pila livelli
* &amp;lbrack;Pila livelli&amp;rbrack; Il metodo di fusione per i livelli istantanei è ora in modalità Attraversa per impostazione predefinita
* &amp;lbrack;Esporta&amp;rbrack; Opzione per attivare e disattivare il dithering
* &amp;lbrack;Plugin&amp;brack; supporta il modificatore di precisione per i cursori (MAIUSC)
* &amp;lbrack;Plugin&amp;brack;&amp;lbrack;UI&amp;rbrack; Nuova icona per il salvataggio automatico
* &amp;lbrack;Scripting&amp;rbrack; Elenca il contenuto di una cartella
* &amp;blocco;Scripting&amp;rbrack; Consenti eliminazione file
* &amp;lbrack;Scripting&amp;rbrack; Leggi tutte le informazioni sullo stack, incluse le risorse utilizzate
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Dynamic stroke&amp;rbrack; Nuovi strumenti e pennelli predefiniti
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Dynamic stroke&amp;rbrack; Due nuove sfumature procedurali: Tonalità sfumatura e Generatore sfumatura
* &amp;lbrack;Content&amp;rbrack; 11 nuovi filtri: MatFx Peeling Pitture, MatFx Water Drops e altro ancora
* &amp;lbrack;Content&amp;rbrack; 7 nuovi generatori: Cucitrice automatica, Colore casuale UV, Densità texel UV e altro ancora
* &amp;lbrack;Content&amp;rbrack; 93 nuove alfa: nuovi testi, frecce e varie altre forme
* &amp;lbrack;Content&amp;rbrack; 2 nuove procedure: Tonalità sfumatura, Generatore sfumatura e altre ancora
* &amp;lbrack;Content&amp;rbrack; 21 nuovi strumenti e pennelli predefiniti per Tratti dinamici: ciottoli, impronte, spray e altro
* &amp;lbrack;Content&amp;rbrack; 2 nuovi HDR: terreno di Canopus e foresta autunnale
* &amp;lbrack;Content&amp;rbrack; Aggiorna il contenuto con la selezione del valore di inizializzazione casuale nello scaffale
* &amp;lbrack;Content&amp;rbrack; Nuova icona con parametro di inizializzazione casuale esposto nello scaffale

**Corretto:**

* &amp;lbrack;Pila livelli&amp;rbrack; La Pila livelli continua a trascinare per sempre
* &amp;lbrack;Mac&amp;rbrack; &quot;Mostra nel Finder&quot; può portare al blocco
* &amp;lbrack;Scripting&amp;rbrack; Le impostazioni salvate tramite l&#39;interfaccia utente personalizzata vengono perse se si sposta il file di shader
* &amp;lbrack;Scripting&amp;rbrack; Il numero di versione dell&#39;API non è corretto e non è aggiornato
* &amp;lbrack;Effetto&amp;rbrack; Il contenuto dell&#39;istogramma non viene visualizzato correttamente
* &amp;lbrack;Effetto&amp;rbrack; In alcuni casi l’effetto istogramma non si aggiorna
* &amp;lbrack;Shelf&amp;rbrack; I punti non sono allineati correttamente sul materiale &quot;Plastic Fabric Pyramid&quot;

**Problemi noti:**

* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione
* &amp;lbrack;Pila livelli&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente

## Versione 4

### 4.3.3 (2018.3.3)

*(Rilasciato: 7 marzo 2019*)Riepilogo: **bugfix**

**Aggiunto:**

* &amp;lbrack;Content&amp;rbrack; Integra il nuovo modello di progetto: &quot;PBR - Rugosità metallica fusione Alpha&quot;
* L&#39;ordine di ricerca delle librerie dinamiche Linux è stato modificato per assegnare priorità alle librerie nella directory di installazione prima di ciò che è installato sul sistema

**Corretto:**

* La trama a volte scompare dalla finestra della vista 3D (premete F per reimpostare la videocamera)
* Aggiornate Substance Painter caricatore Sketchfab con i nuovi tipi di licenza Sketchfab
* &amp;lbrack;Import&amp;rbrack;&amp;lbrack;glTF&amp;rbrack; Gestione errata della modulazione della texture di input come definita nei file glTF
* &amp;lbrack;Import&amp;rbrack;&amp;lbrack;glTF&amp;rbrack; Il piano terreno viene visualizzato in modo errato in alcuni casi con l&#39;importazione glTF
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;USD&amp;rbrack; L&#39;opacità non funziona in Arkit
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; arresti anomali di esportazione USDz in alcuni casi
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Esporta in USD senza salvare porta all&#39;arresto anomalo
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Modalità di Affiancamento errata per texture, modalità di suddivisione per trame e tipi di output per ombreggiatori
* &amp;lbrack;Export&amp;rbrack;&amp;lbrack;USD&amp;rbrack; Esporta solo alcuni set di texture con tutta la geometria
* &amp;lbrack;Instance&amp;rbrack; Arresto anomalo quando si tenta di eliminare un livello di istanza interrotto
* &amp;lbrack;Regression&amp;rbrack;&amp;lbrack;Export&amp;rbrack; Alcune mappe non vengono esportate nella profondità di bit scelta
* &amp;lbrack;Linux&amp;rbrack; Problema con la libreria libtbb.so.2

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.2 (2018.3.2)

*(Rilasciato: 24 gennaio 2019*)Riepilogo: **Hotfix con nuove funzionalità (esportazione USDZ e filtro Texture nella finestra della vista)**

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; Consenti esportazione in USDZ
* &amp;lbrack;Viewport&amp;rbrack; Consenti di controllare la qualità della texture nelle impostazioni di visualizzazione
* &amp;lbrack;Viewport&amp;rbrack; aggiunta dell&#39;impostazione di polarizzazione mip nelle impostazioni di visualizzazione
* &amp;lbrack;Viewport&amp;rbrack; Filtro anisotropo aggiunto nelle impostazioni di visualizzazione
* &amp;lbrack;plugins&amp;rbrack; Aggiorna i plug-in ufficiali per utilizzare lo stile di Substance Painter 2018
* &amp;lbrack;License&amp;rbrack; Installa la licenza per impostazione predefinita in una cartella utente

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
* &amp;lbrack;Scripting&amp;rbrack; creazione del percorso del file non forzata durante il salvataggio di un progetto
* &amp;lbrack;Scripting&amp;rbrack; La richiamata &quot;onProjectAboutToSave()&quot; non funziona più
* Collegamenti al forum interrotti nella finestra di segnalazione dei bug

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.1 (2018.3.1)

*(Rilasciato: 06 Dicembre 2018*)Riepilogo: **Hotfix**

**Aggiunto:**

* &amp;lbrack;Simmetrie&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Il disegno della Simmetria nel Vista 2D è indietro e ora presenta un&#39;anteprima del pennello clone corretta

**Corretto:**

* &amp;lbrack;Esporta&amp;rbrack; Vista 2D esporta in alcuni casi una texture nera
* &amp;lbrack;Iray&amp;rbrack; le informazioni normali diventano errate in Iray dopo aver creato un&#39;istanza di un livello di materiale
* Gli insiemi di texture non quadrate possono portare in alcuni casi all&#39;arresto anomalo
* &amp;lbrack;Annulla&amp;rbrack; in alcuni casi, diversi CTRL+Z possono causare l&#39;arresto anomalo casuale
* &amp;lbrack;QML&amp;rbrack; In alcuni casi, AlgScrollView può creare un avviso nel registro (cicli di associazione)

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.3.0 (2018.3.0)

*(Rilasciato: 20 novembre 2018*)Riepilogo: **Aggiornamenti del viewport, corretta esportazione dei Vista 2D, nuovi helper dell&#39;interfaccia utente, uno strumento di simmetria migliorato, nuovi contenuti e prestazioni notevolmente migliorate**

**Aggiunto:**

* &amp;lbrack;Anti-aliasing&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Nuova anti-alias temporale di filtro per la finestra della vista 3D (tramite Impostazioni schermo)
* &amp;lbrack;Export&amp;rbrack; Esporta il contenuto della finestra della vista 2D come texture singola
* &amp;lbrack;Esporta&amp;rbrack;&amp;lbrack;Dithering&amp;rbrack; Esporta dithering all&#39;esportazione
* &amp;lbrack;Pila livelli&amp;rbrack; colori su livelli e cartelle
* &amp;lbrack;Pila livelli&amp;rbrack; Attivazione e disattivazione rapida di più livelli ed effetti
* &amp;lbrack;Pila livelli&amp;rbrack; Navigazione più semplice per metodi di fusione con tasti su e scorrimento del mouse
* &amp;lbrack;Proj&amp;rbrack;&amp;lbrack;UI&amp;rbrack; manipolatore di rotazione aggiuntivo su tutti e tre gli assi per triplanare
* &amp;lbrack;Proj&amp;rbrack;&amp;lbrack;Shorcuts&amp;rbrack; - e + per modificare le dimensioni del manipolatore di Proiezioni UV
* &amp;lbrack;Shader&amp;rbrack; controlla i parametri dei livelli rivestiti con canali nello shader rivestito con PBR
* &amp;lbrack;Substance&amp;rbrack; Esposizione di nuovi input di texture basati su trama per filtri e generatori
* &amp;lbrack;Simmetria&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack;&amp;lbrack;UI&amp;rbrack; controllare lo scostamento della simmetria con i manipolatori
* &amp;lbrack;Simmetrie&amp;rbrack;&amp;lbrack;Contextual toolbar&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Nuovo pannello simmetria con opzioni
* &amp;lbrack;Simmetria&amp;rbrack; Nuova modalità di intersezione linee simmetrie
* &amp;lbrack;Simmetria&amp;rbrack; nuovo cursore clone simmetria
* &amp;lbrack;Simmetria&amp;rbrack;&amp;lbrack;Shortcuts&amp;rbrack; Q to hide and -, + to change size and shift to snap
* &amp;lbrack;Log&amp;rbrack; migliora i messaggi di errore quando non è possibile esportare texture
* &amp;lbrack;Scripting&amp;rbrack; Consenti modifica o aggiornamento delle risorse in Impostazioni di visualizzazione
* &amp;lbrack;Scripting&amp;rbrack; Consente di creare o rimuovere canali nei set di texture
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Shaders&amp;rbrack; Aggiunta del supporto per l&#39;anisotropia con uno shader dedicato (pbr-metal-rough-anisotropia-angle)
* &amp;lbrack;Content&amp;rbrack; aggiornamento della sfera di anteprima con anisotropia e angolo modificato
* &amp;lbrack;Content&amp;rbrack; Shutline matFx aggiornato
* &amp;lbrack;Content&amp;rbrack; Nuova texturing.XYZ scansione del volto senza interruzioni
* &amp;lbrack;Content&amp;rbrack; Nuove procedure anisotrope
* &amp;lbrack;Content&amp;rbrack; Nuovo filtro: baked lighting environment
* &amp;lbrack;Content&amp;rbrack; Mappa del nuovo ambiente: studio automotive neutral
* &amp;lbrack;Content&amp;rbrack; Nuovo modello di progetto: PBR - Angolo di anisotropia rugosità metallica (con canali di anisotropia)
* &amp;lbrack;Content&amp;rbrack; Nuovo modello di progetto: PBR - rugosità metallica Coated
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Engine&amp;rbrack; Sparse Virtual Textures (SVT)
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Preferenze&amp;rbrack;&amp;lbrack;UI&amp;rbrack; opzione di accelerazione per il supporto hardware SVT
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Log&amp;rbrack; informazioni aggiuntive per la funzionalità di creazione di texture virtuali sparse (ad esempio, disco di dimensioni)
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;UI&amp;rbrack; finestra dei messaggi all&#39;inizio se le dimensioni del disco sono troppo basse per la cache
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Preferenze&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Substance Painter posizione cache globale
* &amp;lbrack;SVT&amp;rbrack; Nuova variabile di ambiente per specificare il percorso della cache della Substance Painter
* &amp;lbrack;SVT&amp;rbrack; Nuova variabile di ambiente per attivare l&#39;accelerazione del supporto hardware SVT
* &amp;lbrack;SVT&amp;rbrack; Rileva supporto sparse per hardware
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Hardware Sparse&amp;rbrack; Aumentare la versione minima del driver per la GPU Nvidia
* &amp;lbrack;SVT&amp;rbrack;&amp;lbrack;Shader&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack;&amp;lbrack;UI&amp;rbrack; Avvisa l&#39;utente se all&#39;apertura del progetto sono presenti artefatti con texture virtuale sparsa

**Corretto:**

* &amp;lbrack;Selettore colore&amp;rbrack; Viene visualizzato il cursore di disegno quando si tenta di scegliere un colore
* Arresto anomalo selezionando o deselezionando i livelli in un ordine specifico può provocare arresto anomalo
* Arresto anomalo quando si incolla come istanza un livello con una maschera
* &amp;lbrack;Canale utente&amp;rbrack;&amp;lbrack;Regressione&amp;rbrack; Arresto anomalo durante la ridenominazione del canale utente
* &amp;lbrack;Canale utente&amp;rbrack; Anteprima pennello in grigio
* &amp;lbrack;Alembic&amp;rbrack; Un solo set di texture da diversi materiali dopo l&#39;importazione
* &amp;lbrack;Engine&amp;rbrack; La texture esportata è diversa dalla finestra della vista per i timbri del pennello
* &amp;lbrack;Engine&amp;rbrack; L&#39;inversione con un effetto livello non influisce completamente su una texture
* Il selettore materiale sta applicando un tratto di pennello durante il prelievo
* Il passaggio a una risoluzione di 128x128px genera un arresto anomalo
* I collegamenti delle mappe trama non vengono aggiornati correttamente quando si ridefiniscono o si creano istanze dei livelli
* &amp;lbrack;Substance&amp;rbrack; UserData ColorSpace non funziona con la trama Eseguita i baking Normale richiesta come input
* Associazione MDL non corrispondente quando si utilizzano più istanze di shader
* &amp;lbrack;Simmetria&amp;rbrack;&amp;lbrack;Riempi livello&amp;rbrack; piano della Simmetria e il relativo manipolatore attivo nel livello di riempimento
* &amp;lbrack;Viewport&amp;rbrack; punto pivot per la traduzione non sempre aggiornato dopo il clic
* &amp;lbrack;UI&amp;rbrack; icone fisse e rimozione dei segnaposto per i monitor HDPI

**Problemi noti:**

* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.2.3 (2018.2.3)

*(Rilasciato il 25 settembre 2018)*

**Corretto:**

* &amp;lbrack;vista 2D&amp;rbrack; vista 2D interrotto con alcune trame durante la creazione di un nuovo progetto
* &amp;lbrack;Arresto anomalo&amp;rbrack; il passaggio da Proiezione UV a proiezione triplanare genera un arresto anomalo
* &amp;lbrack;RayCollider&amp;rbrack; più arresti anomali dovuti a &quot;RayCollider&quot;
* &amp;lbrack;Strumento&amp;rbrack; se si cambia livello, vengono perse le proprietà del pennello modificate
* Le impostazioni del pennello vengono ripristinate quando si passa alla gomma

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.2 (2018.2.2)

*(Rilasciato l&#39;11 settembre 2018*)Riepilogo: **Hotfix con aggiornamento del contenuto, nuove funzionalità di scripting e possibilità di disabilitare l&#39;aggiornamento automatico**

**Aggiunto:**

* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Aggiungi un predefinito Ripiano incarnato
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;shelf&amp;rbrack; Conversione di 19 normali di incarnato in materiali per la dispersione del sottosuolo
* &amp;lbrack;Scripting&amp;rbrack; Crea un modello di progetto da un progetto aperto
* &amp;lbrack;Scripting&amp;rbrack; Recupera/Imposta le impostazioni di esportazione di un progetto aperto
* &amp;lbrack;Updates&amp;rbrack; Consente di disabilitare la finestra a comparsa di aggiornamento automatico da impostazioni e variabile di ambiente
* &amp;lbrack;Updates&amp;rbrack; Non viene visualizzato fino alla versione successiva nella finestra a comparsa Manutenzione obsoleta

**Corretto:**

* &amp;blocco;Camera&amp;rbrack; zoom errato passando da ortografica a Prospettiva
* &amp;lbrack;Display&amp;rbrack; Alcune mappe vengono visualizzate in modalità lineare anziché sRGB
* &amp;lbrack;Viewports&amp;rbrack; Lo stato attivo della trama non si comporta correttamente
* &amp;lbrack;vista 2D&amp;rbrack; Il progetto con la fotocamera rotta ha sparito UVs Gusci
* &amp;lbrack;SSS&amp;rbrack;&amp;lbrack;Tooltip&amp;rbrack; subsurface scattering suggerimenti visualizzati nel registro
* Alcuni progetti non possono essere aperti in 2018.2 e il messaggio di errore non può salvare un pacchetto substance null
* &amp;lbrack;Mask&amp;rbrack; Il colore dello strumento Pittura può bloccarsi in alcuni casi quando si lavora in una maschera
* &amp;lbrack;Material&amp;rbrack; Mappe non visualizzate in situazioni specifiche
* &amp;lbrack;Proj&amp;rbrack;&amp;lbrack;Tools&amp;rbrack; Manipolatore attivo con un generatore
* &amp;lbrack;Substance&amp;rbrack; Substance di parametri mancanti
* &amp;lbrack;Scripting&amp;rbrack; nome software errato nella documentazione
* &amp;lbrack;UDIM&amp;rbrack; nessuna informazione nel registro sulle shell UV su più porzioni UV

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

* &amp;lbrack;SSS&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; dispersione generica sottosuperficie
* &amp;lbrack;SSS&amp;rbrack; Sincronizza i parametri MDL e di dispersione sottosuperficie
* &amp;lbrack;SSS&amp;rbrack; ha aggiunto un nuovo canale in scala di grigi denominato Dispersione
* &amp;lbrack;SSS&amp;rbrack;&amp;lbrack;Impostazioni Shader&amp;rbrack; parametro del tipo di dispersione per la dispersione del sottosuolo (incarnato o traslucido)
* &amp;lbrack;SSS&amp;rbrack;&amp;lbrack;Impostazioni Shader&amp;rbrack; parametro della scala di dispersione per la dispersione del sottosuolo
* &amp;lbrack;SSS&amp;rbrack;&amp;lbrack;Impostazioni Shader&amp;rbrack; Parametro colore di dispersione per la dispersione del sottosuolo
* &amp;lbrack;SSS&amp;rbrack;&amp;lbrack;Impostazioni di visualizzazione&amp;rbrack; Conteggio campioni diffusione per dispersione sottosuperficie
* &amp;lbrack;Shader&amp;rbrack;&amp;lbrack;Iray&amp;rbrack; Integra MDL di dispersione sottosuperficiale per Iray
* &amp;lbrack;Shader&amp;rbrack; aggiornamento di Shader tramite il programma di aggiornamento delle risorse
* &amp;lbrack;Shader&amp;rbrack; Aggiorna API e documentazione del log delle modifiche
* &amp;lbrack;Tool Properties&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; Nuovi parametri per la proiezione triplanare
* &amp;lbrack;Viewport&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; Controlla le proprietà dei livelli di riempimento nella vista 3D direttamente con i manipolatori (proiezione triplanare)
* &amp;lbrack;Shortcuts&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; Nuove scelte rapide Q, W, E, R, T per manipolatori di proiezione triplanari
* &amp;lbrack;Viewport&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; Controlla le proprietà dei livelli di riempimento direttamente nei Vista 2D (Proiezione UV)
* &amp;lbrack;Shortcuts&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; Nuova scelta rapida da tastiera Q per manipolatori Proiezione UV
* &amp;lbrack;Contextual Toolbar&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; Controlla manipolatori di proiezione triplanari
* &amp;lbrack;Contextual Toolbar&amp;rbrack;&amp;lbrack;Proj&amp;rbrack; manipolatori di Proiezioni UV di controllo
* &amp;lbrack;Proprietà strumento&amp;rbrack; Disattiva Affiancamento texture con lo strumento Proiezione e Stencil
* &amp;lbrack;Stencil&amp;rbrack; Usa immagini non quadrate con lo strumento di proiezione/stencil
* &amp;lbrack;Stencil&amp;rbrack; Consenti il controllo della modalità Affiancamento nella finestra Proprietà
* &amp;lbrack;Stencil&amp;rbrack; Lo zoom non è centrato su uno stencil non Affiancamento
* &amp;lbrack;Fotocamere&amp;rbrack; Importa fotocamere da Maya, Max, Blender, Modo, DAE
* &amp;lbrack;Cameras&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Selezionare e controllare le fotocamere importate nella finestra della vista
* &amp;lbrack;Camera&amp;rbrack;&amp;lbrack;Iray&amp;brack; Selezionare e controllare le fotocamere importate in Iray
* &amp;lbrack;Cameras&amp;rbrack;&amp;lbrack;UI&amp;rbrack;&amp;lbrack;New project&amp;rbrack;&amp;lbrack;Project configuration&amp;rbrack; Import cameras is checked per impostazione predefinita
* &amp;lbrack;Cameras&amp;rbrack;&amp;lbrack;Shortcuts&amp;rbrack; Aggiungi scelte rapide per passare da una fotocamera all’altra
* &amp;lbrack;Cameras&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Aggiungi fotogramma nella finestra della vista
* &amp;lbrack;Cameras&amp;rbrack;&amp;lbrack;Viewport Settings&amp;rbrack; Controllo dell&#39;opacità del fotogramma
* &amp;lbrack;Camera&amp;rbrack;&amp;lbrack;Impostazioni fotocamera&amp;rbrack; lunghezza focale massima a 500 mm
* &amp;lbrack;Fotocamere&amp;rbrack;&amp;lbrack;Impostazioni fotocamera&amp;rbrack; Rapporto di esposizione
* &amp;lbrack;Camera&amp;rbrack;&amp;lbrack;Impostazioni fotocamera&amp;rbrack; Aggiungi opzione di blocco
* &amp;lbrack;Camera&amp;rbrack;&amp;lbrack;Impostazioni fotocamera&amp;rbrack; Aggiungi un&#39;opzione di ripristino
* &amp;lbrack;Cameras&amp;rbrack;&amp;lbrack;Impostazioni fotocamera&amp;rbrack; Aggiungi attributo distanza focale
* &amp;lbrack;glTF&amp;rbrack; importazione di un file glTF
* &amp;lbrack;glTF&amp;rbrack; Importa mapping occlusione ambientale
* &amp;lbrack;Alembic&amp;rbrack; Importa fotogramma Alembic 1 con geometria statica
* &amp;lbrack;Shelf&amp;rbrack; Trascina i materiali direttamente sulla trama utilizzando mappe ID con un modificatore (CTRL/Comando)
* &amp;lbrack;Pila livelli&amp;rbrack; creazione automatica della maschera ID con trascinamento dei materiali sulla trama con mappe ID
* &amp;lbrack;Pila livelli&amp;rbrack; scorrimento automatico dei livelli con trascinamento sulla Pila livelli
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Tool Properties&amp;rbrack; Exposé preset di Substance
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Menu della Guida&amp;rbrack; miglioramento del menu della Guida
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;New Project&amp;rbrack;&amp;lbrack;Project Configuration&amp;rbrack; Riorganizzazione della finestra
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;New Project&amp;rbrack;&amp;lbrack;Project Configuration&amp;rbrack; Sostituisci termine trama con file
* &amp;lbrack;UI&amp;rbrack;&amp;lbrack;Substance&amp;rbrack; Visualizza gli attributi della Substance nell&#39;interfaccia utente
* &amp;lbrack;Shortcuts&amp;rbrack; F4 passa dalla vista 2D a quella 3D e viceversa
* &amp;lbrack;Scelte rapide&amp;rbrack; Nuove scelte rapide per Attiva/Disattiva stencil N e maschera veloce U
* &amp;lbrack;Substance integration&amp;rbrack; tiene conto delle istruzioni &#39;visible if&#39; nei parametri della Substance
* &amp;lbrack;Viewport&amp;rbrack; Ombre non obbligate a essere calcolate dopo lo spostamento della videocamera
* &amp;lbrack;Content&amp;rbrack; Aggiorna MeetMat con le fotocamere importate
* &amp;lbrack;Content&amp;rbrack; Aggiungi un campione con la dispersione sottosuperficie abilitata - JadeToad
* &amp;lbrack;Content&amp;rbrack; Aggiungi un nuovo modello di progetto PBR con la dispersione sottosuperficie attivata
* &amp;lbrack;Content&amp;rbrack; predefiniti di esportazione aggiornati per aggiungere un nuovo canale di diffusione
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Supporto per la dispersione sottosuperficiale aggiunto per: pbr-metal-rough, pbr-metal-rough-alpha-test, pbr-coated, pbr-spec-gloss
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; Canale di dispersione aggiunto a 5 materiali avanzati (pallini e pelli)
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; 1 nuovo materiale giada
* &amp;lbrack;Content&amp;rbrack;&amp;lbrack;Shelf&amp;rbrack; 1 nuovo materiale cerato

**Corretto:**

* &amp;lbrack;CMD&amp;rbrack; risultati diversi utilizzando la stessa riga di comando con versioni diverse
* &amp;lbrack;TDR&amp;rbrack; Se TdrLevel è impostato, non ci sono errori nel registro
* &amp;lbrack;Baker&amp;rbrack; mappa di Occlusione ambientale capovolta
* &amp;lbrack;ID Map&amp;rbrack; Arresto anomalo durante il prelievo al di fuori dell&#39;intervallo 0-1
* &amp;lbrack;Iray&amp;rbrack; Arresto anomalo quando si cambia set di texture e si torna alla modalità Pittura
* &amp;lbrack;Viewport&amp;rbrack; sincronizza le aree di rilascio tra le finestre per il trascinamento
* &amp;lbrack;Engine&amp;rbrack; artefatto di Moire quando si disegnano livelli di riempimento Affiancamenti o si disegna un piccolo pennello
* &amp;lbrack;License&amp;rbrack; Controllo versione software non valida del servizio licenze
* &amp;lbrack;License&amp;rbrack; rielaborare il modo in cui gestiamo l&#39;autenticazione
* &amp;lbrack;API&amp;rbrack; richiama l&#39;evento API di scripting onNewProjectCreated anche durante la creazione con un modello
* &amp;lbrack;Shader&amp;rbrack; Lo shader compilato non viene caricato dalla cache se non viene compilato il file di shader
* &amp;lbrack;Shelf&amp;rbrack; l&#39;esportazione del file HDR dallo shelf genererà un file con valori bloccati
* &amp;lbrack;Export&amp;rbrack; l&#39;esportazione EXR blocca i valori dei colori RGB tra 0 e 1
* &amp;lbrack;Contenuto&amp;rbrack; Disturbo Procedurale Perlin 3D Frattale è pixelato

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.1.3 (2018.1.3)

*(Rilasciato il 28 giugno 2018)*

**Aggiunto:**

* &amp;lbrack;Preferenze&amp;rbrack; Proponi di salvare il progetto al riavvio di Painter

**Corretto:**

* &amp;lbrack;Plugin&amp;rbrack; Substance Source di ricerca non funziona
* &amp;lbrack;Materiali avanzati&amp;rbrack; L&#39;importazione di Materiali avanzati in alcuni casi genera un arresto anomalo
* &amp;lbrack;Materiali avanzati&amp;rbrack; l&#39;eliminazione di Materiali avanzati in alcuni casi genera un arresto anomalo
* &amp;lbrack;Save&amp;rbrack; Il salvataggio genera un arresto anomalo in alcuni rari casi
* &amp;lbrack;Shelf&amp;rbrack; Inverti non funziona su Celle 2 e Celle 3
* &amp;lbrack;Shelf&amp;rbrack; Typo in alcuni Alpha
* &amp;lbrack;Shelf&amp;rbrack; Alcuni materiali Substance non vengono renderizzati correttamente

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.2 (2018.1.2)

*(Rilasciato: 12 giugno 2018*)Riepilogo: **Velocità di Esegue i baking migliorata, Sistema di salvataggio migliorato, Cursori aggiornati, API di plug-in aggiornata, Traduzione cinese, Riempimento migliorato ora facoltativo**

**Aggiunto:**

* &amp;lbrack;Baker&amp;rbrack; miglioramento delle prestazioni con la nuova versione del baker
* Forzare la finestra di dialogo di visualizzazione con la GPU incompatibile
* &amp;lbrack;Salva&amp;rbrack; Esposizione nuova funzionalità di progetto compatto (modalità di salvataggio completa/compatta)
* &amp;lbrack;Salva&amp;rbrack; Informa l&#39;utente in caso di errore di salvataggio
* &amp;lbrack;Clean&amp;brack; salvataggio successivo in modalità completa/compatta
* &amp;lbrack;Cursori&amp;rbrack; miglioramento della precisione delle barre e dei cursori di colore/scala di grigi
* &amp;blocco;Cursori&amp;sblocco; aggiunta dei controlli freccia Su/Giù
* &amp;lbrack;Cursori&amp;rbrack; stessa zona di rilevamento per i cursori a barre a colori e in scala di grigi
* &amp;lbrack;Plugin&amp;brack; Salvataggio automatico sempre in modalità incrementale
* &amp;lbrack;Plugin&amp;brack; Opzione per passare dai plug-in al nuovo stile di interfaccia
* &amp;lbrack;Lingua&amp;rbrack; Aggiungi traduzione cinese
* &amp;lbrack;Padding&amp;rbrack; Opzione per passare dalla spaziatura UV a quella 3D adiacente per set di texture in Impostazioni set di texture
* &amp;lbrack;Script&amp;rbrack; modalità di salvataggio esposizione: completa/compatta o incrementale
* &amp;lbrack;Script&amp;rbrack; Aggiornamento della documentazione di script/QML
* &amp;lbrack;Log&amp;rbrack; indica la modalità di salvataggio nel log (completa/compatta o incrementale)

**Corretto:**

* &amp;lbrack;Strumento&amp;rbrack; Lo slot del canale Trasforma in uno slot di materiale su riempimenti a canale singolo
* Arresto anomalo durante il caricamento di una trama (FBX) con alcune facce non assegnate da un materiale
* Arresto anomalo in Iray con NVIDIA GRID 5.2 sulla macchina virtuale
* Arresto anomalo quando si annulla un&#39;eliminazione di un predefinito di materiale
* Arresto anomalo durante il caricamento di alcuni progetti
* &amp;lbrack;Riga di comando&amp;rbrack; Nuova riga di comando per le trame UDIM suddivise per dim
* &amp;lbrack;Toolbar&amp;rbrack; Riduzione della barra degli strumenti
* &amp;lbrack;Instancing&amp;rbrack; Impossibile creare un&#39;istanza di bitmap su più set di texture
* &amp;lbrack;Viewport&amp;rbrack; L&#39;aggiornamento non è completo quando si disegna su trama con UV affiancati
* &amp;lbrack;Iray&amp;rbrack; La Mappa normale viene applicata due volte per i dielettrici
* &amp;lbrack;Shelf&amp;rbrack; Composizione tipografica in alcuni parametri di Substance (alfa, procedure e matfx)
* &amp;lbrack;Shelf&amp;rbrack; Errore di battitura per la bitmap &quot;Solo personale autorizzato&quot;
* &amp;lbrack;Script&amp;rbrack; Function alg.shaders.materials() non funziona più

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.1 (2018.1.1)

*(Rilasciato il 3 aprile 2018)*

**Corretto:**

* &amp;lbrack;Tablet&amp;rbrack; Problema durante la modifica delle scelte di interazione predefinite
* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo con libreria Assimp
* &amp;lbrack;Baker&amp;rbrack; regressione sulle prestazioni con mappa OA
* &amp;lbrack;Iray&amp;rbrack; La Distorsione obiettivo non viene applicata al Canale alfa
* &amp;lbrack;Driver&amp;rbrack; aggiornamento dei requisiti minimi dei driver
* &amp;lbrack;3Dview&amp;rbrack; Normali non generate correttamente sulle trame UDIM senza informazioni sulle normali
* &amp;lbrack;Intel&amp;rbrack; Arresto anomalo con Substance Painter 2018.1.0
* &amp;lbrack;Intel&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Problema con la spaziatura interna (artefatti neri)

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.0 (2018.1.0)

*(Rilasciato il 15 marzo 2018)*

**Aggiunto:**

* Nuovo stile generale (icone, colore, comportamento)
* Nuovo layout predefinito
* &amp;lbrack;Tablet&amp;rbrack; miglioramento dell&#39;esperienza utente durante l&#39;uso
* &amp;lbrack;Menu principale&amp;rbrack; ordina prima gli elementi nativi nelle visualizzazioni e nelle barre degli strumenti
* &amp;lbrack;Menu principale&amp;rbrack; Sposta le azioni maschera veloce nella sezione viewport
* &amp;lbrack;Menu principale&amp;rbrack; sposta le azioni del clic con il pulsante destro del mouse nella sezione della finestra della vista
* &amp;lbrack;Menu principale&amp;rbrack; Rinomina il menu &quot;Visualizza&quot; in &quot;Finestra&quot;
* &amp;lbrack;Menu rapido&amp;rbrack; Nuove proprietà dello strumento con clic destro nella finestra della vista
* &amp;blocco;Ancoraggio widget&amp;rbrack; Nuova barra degli strumenti Ancoraggio per ridurre/richiamare rapidamente
* &amp;lbrack;Impostazioni di visualizzazione&amp;rbrack; finestra Impostazioni fotocamera e visualizzatore unite
* &amp;lbrack;Pila livelli&amp;rbrack; menu di scelta rapida contestuale
* &amp;lbrack;Pila livelli&amp;rbrack; Trascina e rilascia per spostare qualsiasi effetto all’interno dello stesso livello
* &amp;lbrack;Toolbar&amp;rbrack; riorganizzazione della barra degli strumenti e nuova barra degli strumenti contestuale
* &amp;blocca;Strumenti barra degli strumenti&amp;rbrack; dividi lo strumento clone in due strumenti separati
* &amp;lbrack;Strumenti proprietà&amp;rbrack; valore più chiaro della scala di grigi dello sfondo nell&#39;anteprima
* &amp;lbrack;Strumenti proprietà&amp;rbrack; Organizzazione nelle schede (riempimento e strumenti)
* &amp;lbrack;Strumento&amp;rbrack; il risultato del disegno corrisponde allo stencil
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; nuovo cursore per il livello di riempimento
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; navigazione e pittura più fluidi (frequenza fotogrammi più elevata)
* &amp;lbrack;Viewport&amp;rbrack; casella combinata di selezione Materiale/Canale/Mappa nella finestra della vista
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Riduci sfarfallio durante la rotazione (con ombreggiatura)
* &amp;lbrack;Shelf&amp;rbrack; Visualizza i materiali per impostazione predefinita all&#39;apertura di Painter
* &amp;lbrack;Shelf&amp;rbrack; miglioramento del tempo di caricamento di texture e materiali per Substance (da 2 a 6 volte più veloce)
* &amp;lbrack;Shelf&amp;rbrack; Riorganizza le cartelle dei materiali per adattarle alla struttura della Substance Source
* &amp;lbrack;Shelf&amp;rbrack; Trascina i materiali direttamente sulla trama nella finestra della vista
* &amp;lbrack;Shelf&amp;rbrack; Nuovi rumori 3D (Perlin, Perlin Fractal, Simplex e Worley)
* &amp;lbrack;Shelf&amp;rbrack; Nuovo generatore di maschere con posizione trama
* &amp;lbrack;Shelf&amp;rbrack; Disturbi di base aggiornati per supportare il non square expansion
* &amp;lbrack;Shelf&amp;rbrack; Aggiunto nuovo modello ed esporta predefinito per Lens Studio (applicazione Snap)
* &amp;lbrack;Shelf&amp;rbrack; Materiali avanzati e Maschere avanzate aggiornati per utilizzare la versione più recente dell&#39;Editor maschera (micro dettagli)
* &amp;lbrack;Shelf&amp;rbrack; Nuovo progetto di esempio &quot;TilingMaterial&quot; per creare materiali in Affiancamento senza interruzioni
* &amp;lbrack;Shelf&amp;rbrack; Nuovi pennelli predefiniti (Calligrafia, Bagnato, Tratteggio e così via)
* &amp;blocco;Cursori&amp;sbarra; nuovi cursori e stile e comportamento delle barre di colore/scala di grigio
* &amp;lbrack;Baker&amp;rbrack; Consenti l&#39;uso del rettangolo di selezione completo della scena per calcolare la mappa di posizione
* &amp;lbrack;Shader&amp;rbrack; rimuove il parametro di forza height dai parametri di shader predefiniti
* &amp;lbrack;Engine&amp;rbrack; motore di Substance aggiornato
* &amp;lbrack;Engine&amp;rbrack; Nessuna o meno discontinuità tra i blocchi UV
* &amp;lbrack;Plugin&amp;rbrack; Importa più rapidamente i materiali scaricati da Substance Source
* &amp;lbrack;Plugin&amp;brack; Aggiorna tutti i plug-in in base al nuovo stile generale
* &amp;lbrack;Preferenze&amp;rbrack; l&#39;anteprima del colore di sfondo cambia automaticamente
* &amp;lbrack;Clean&amp;rbrack; Riduzione del rischio di danneggiamento del progetto
* &amp;lbrack;Open&amp;rbrack; apertura miglioramento tempo progetto
* &amp;lbrack;Nuovo progetto&amp;rbrack; Nuovo progetto - Miglioramento del tempo di aggiornamento mesh
* &amp;lbrack;Salva&amp;rbrack; Salvataggio miglioramento tempo progetto
* &amp;lbrack;Log&amp;rbrack; tipo di licenza segnalato nel log
* &amp;lbrack;TextureSet&amp;rbrack; Rinomina il pulsante &quot;Esegue i baking Texture&quot; in &quot;Esegue i baking mappe trama&quot;
* Rinominare &quot;Mappe aggiuntive&quot; come &quot;Mesh maps&quot;

**Corretto:**

* &amp;lbrack;Viewport&amp;rbrack; Prestazioni errate con trame contenenti numerosi sottooggetti
* &amp;lbrack;Strumenti proprietà&amp;rbrack; Canale disattivato quando si trascina un&#39;immagine nello slot del materiale
* &amp;lbrack;Strumenti proprietà&amp;rbrack; L&#39;anteprima del pennello non funziona con gli strumenti sfumino e clone
* &amp;lbrack;Texture set&amp;rbrack; L&#39;ordine dei canali non è corretto quando si utilizzano i modelli
* &amp;lbrack;Shelf&amp;rbrack; icona mancante per il generatore di Conversioni in scala di grigi
* &amp;lbrack;Shelf&amp;rbrack; il numero alfa del cerchio di firma è interrotto (font mancante)
* Rilevamento errato delle GPU integrate all’avvio
* &amp;lbrack;Arresto anomalo&amp;rbrack; Trascina una risorsa importata denominata con un carattere #
* &amp;lbrack;Engine&amp;rbrack; Problema di rilevamento Vram nella GPU integrata
* &amp;lbrack;Engine&amp;rbrack; Sono stati corretti numerosi arresti anomali in Substance Engine Linker
* &amp;lbrack;Engine&amp;rbrack; artefatti quadrati durante la modifica della risoluzione
* &amp;lbrack;Effetti post&amp;rbrack; il ridimensionamento dell&#39;interfaccia è lento quando gli effetti post sono attivi
* &amp;lbrack;Baker&amp;rbrack; L&#39;unità della scena non viene rispettata correttamente per i valori di Distanza raggio
* &amp;lbrack;Baker&amp;rbrack; AO da mesh La distanza di occlusione è bloccata a 1 indipendentemente dal valore di input
* &amp;lbrack;Baker&amp;rbrack; Corrispondenza per nome ignora alcune trame con nomi specifici
* &amp;lbrack;Baker&amp;rbrack; L&#39;impostazione dei colori da mesh Polygroup e Submesh ID restituisce sempre un&#39;immagine nera
* &amp;lbrack;Baker&amp;rbrack; La Esegue i baking dell&#39;ID non riesce con trame FBX binarie da Blender
* &amp;lbrack;Shader&amp;rbrack; Disturbo nel vista 2D con dota-2 e non-pbr-spec-gloss
* &amp;lbrack;Linux&amp;rbrack; durante la esegue i baking viene utilizzato un solo thread CPU
* &amp;lbrack;MacOS&amp;rbrack; Arresto anomalo con il cursore del pennello che si sposta sulla finestra della vista

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Processo di post-distorsione non preso in considerazione durante l&#39;esportazione in IRay (alfa)

## Versione 3

### 3.4.2 (2017.4.2)

*(Rilasciato il 24 gennaio 2018)*

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; Ottiene lo stato di un&#39;esportazione con avanzamento passaggio
* &amp;lbrack;Esporta&amp;rbrack; Consenti l&#39;annullamento di un&#39;esportazione
* &amp;lbrack;Esporta&amp;rbrack; Esporta texture in Sketchfab senza perdere la qualità delle mappe normali
* &amp;lbrack;Esporta&amp;rbrack; Esporta in formato binario (glb) glTF
* &amp;lbrack;Esporta&amp;rbrack; Consenti ridimensionamento colonne nella scheda di configurazione della finestra di esportazione
* &amp;lbrack;Shader&amp;rbrack; Aggiungi un registro modifiche per l&#39;API shader
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi funzioni di richiamata prima e dopo quando si esportano texture
* &amp;lbrack;Iray&amp;rbrack; Aggiornamento a SDK 2017.1 (supporto di GPU Volta)

**Corretto:**

* Arresto anomalo di chiusura dell&#39;applicazione prima della visualizzazione della finestra principale
* &amp;lbrack;MAC&amp;rbrack; Arresto anomalo durante il caricamento di mappe in scala di grigio con IRAY
* &amp;lbrack;MAC&amp;rbrack; rilevamento VRAM non corretto con il nuovo sistema operativo High Sierra
* &amp;lbrack;Plugin&amp;rbrack; Il download delle risorse da Substance Source non funziona più
* &amp;lbrack;Scripting&amp;rbrack; Rilevamento minimo della versione del plug-in non corretto
* &amp;lbrack;Export&amp;rbrack; Impossibile salvare il predefinito di esportazione dopo l&#39;esportazione della texture
* &amp;lbrack;Istanza&amp;rbrack; problema con i generatori di cui viene creata un&#39;istanza in un TextureSet senza mappature aggiuntive
* &amp;lbrack;Viewport&amp;rbrack; Il dithering non funziona con una risoluzione superiore a 4k
* &amp;lbrack;Viewport&amp;rbrack; la visualizzazione del materiale vista 2D è coperta da rumore
* &amp;lbrack;Shelf&amp;rbrack; Migliora il tempo di caricamento per i predefiniti shelf
* &amp;lbrack;Engine&amp;rbrack; Fusione errata quando si disegna sotto la selezione colore

### 3.4.1 (2017.4.1)

*(Rilasciato il 15 dicembre 2017)*

**Aggiunto:**

* &amp;lbrack;Scripting&amp;rbrack; Esporta trama tramite l’API di scripting
* &amp;lbrack;Import&amp;rbrack; disabilita l&#39;importazione di un formato di file mesh non supportato (consenti solo obj, fbx, dae, ply)
* &amp;lbrack;Log&amp;rbrack; Indica con maggiore precisione il problema TDR nel file di registro

**Corretto:**

* Arresto anomalo se l&#39;applicazione viene chiusa prima del termine della ricerca per indicizzazione delle risorse
* Arresto anomalo durante l’apertura di progetti con lo strumento Sfumino/Clona /Clone
* Arresto anomalo quando si utilizza Ripeti dopo un annullamento della modifica dello Shader in Impostazioni visualizzatore
* &amp;lbrack;Engine&amp;rbrack; La creazione di texture differisce tra Painter 2017.2 e 2017.4
* &amp;lbrack;Viewport&amp;rbrack; selezione su una mappa ID da un&#39;istanza campiona il colore errato
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l&#39;esportazione di una texture normale o di occlusione non valida
* &amp;lbrack;Export&amp;rbrack; I gruppi dei file PSD vengono bloccati quando vengono aperti in Photoshop CS6
* &amp;lbrack;Plugin&amp;brack; il plug-in Photoshop ignora la selezione del canale ed esporta sempre tutto
* &amp;lbrack;Livelli&amp;rbrack; Gli ancoraggi si interrompono quando vengono copiati/incollati tra set di texture
* &amp;lbrack;Layers&amp;rbrack; alcuni riferimenti di ancoraggio non possono essere ripristinati se danneggiati
* &amp;lbrack;Shader&amp;rbrack; il parametro di rugosità secondaria rivestita in pbr è interrotto
* &amp;lbrack;Steam&amp;rbrack; La finestra a comparsa Controllo versione non dovrebbe essere visibile all&#39;avvio

**Problemi noti:**

* &amp;lbrack;AMD&amp;rbrack; Arresti anomali/Si blocca quando si tenta di pittura su una trama. Può essere risolto con un aggiornamento del driver GPU.

### 3.4.0 (2017.4.0)

*(Rilasciato il 23 novembre 2017)*

**Aggiunto:**

* &amp;lbrack;Istanza&amp;rbrack; Consenti di creare un&#39;istanza dei parametri tra i livelli
* &amp;lbrack;Istanza&amp;rbrack; Consente di passare da un livello di origine a un&#39;istanza e viceversa
* &amp;lbrack;Istanza&amp;rbrack; Aggiungi un&#39;azione &quot;crea istanza tra set di texture&quot;
* &amp;lbrack;Instancing&amp;rbrack; Indicare nella Pila livelli le istanze di rientro (cicli)
* &amp;lbrack;Instancing&amp;rbrack; Elimina le istanze quando viene rimossa un&#39;origine
* &amp;lbrack;Istanza&amp;rbrack; Non consentire riferimenti di ancoraggio dall&#39;esterno di una cartella istanza
* &amp;lbrack;UI&amp;rbrack; sposta lo stack di annullamento nella relativa finestra denominata &quot;History&quot;
* &amp;lbrack;Plugin&amp;brack; Integrazione del plug-in DCC Live-Link
* &amp;lbrack;Motore&amp;rbrack; migliora le prestazioni di pittura con pittura sparsa
* &amp;lbrack;Esporta&amp;rbrack; Aggiungi le opzioni di bozza e riesportazione all&#39;esportazione Sketchfab
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi controllo &quot;flip&quot; per le sostanze font
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi 20 nuovi materiali procedurali
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi 40 nuove mappe di grunge (basate su bitmap e procedurali)
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Attiva le collisioni di anteprima pennello su altri set di texture visibili
* Aggiornamento dei requisiti minimi dei driver della GPU AMD

**Corretto:**

* Arresto anomalo quando si elaborano Substance a risoluzioni eccessive
* Arresto anomalo quando si dipinge intensamente con particelle
* &amp;lbrack;Viewport&amp;rbrack; riflesso di specular errato nel Vista 2D con trame specifiche
* &amp;lbrack;UI&amp;rbrack; alcune azioni indesiderate vengono visualizzate nella finestra Cronologia

**Problemi noti:**

* &amp;lbrack;Layers&amp;rbrack; alcuni riferimenti di ancoraggio non possono essere ripristinati se danneggiati
* Arresto anomalo quando si utilizza Ripeti dopo un annullamento della modifica dello Shader in Impostazioni visualizzatore

### 3.3.3 (2017.3.3)

*(Rilasciato il 1° dicembre 2017)*

**Corretto:**

* &amp;lbrack;Steam&amp;rbrack; La finestra a comparsa Controllo versione non dovrebbe essere visibile all&#39;avvio
* &amp;lbrack;Export&amp;rbrack; I gruppi dei file PSD vengono bloccati quando vengono aperti in Photoshop CS6

### 3.3.2 (2017.3.2)

*(Rilasciato il 20 novembre 2017)*

**Aggiunto:**

* &amp;lbrack;UI&amp;rbrack; Finestra di dialogo Migliora nuova versione e aggiungi registro modifiche
* &amp;lbrack;UI&amp;rbrack; Indica se la manutenzione è scaduta nella finestra di dialogo per la nuova versione
* &amp;lbrack;License&amp;rbrack; Aggiorna il sistema di licenze per gestire le date di manutenzione
* &amp;lbrack;Esporta&amp;rbrack; Rinomina l&#39;Adobe Standard Material in Adobe Dimension

**Corretto:**

* &amp;lbrack;Mac&amp;rbrack; Il disegno genera quadrati neri e texture danneggiamenti
* &amp;lbrack;Engine&amp;rbrack; La cache a volte può scomparire nel riquadro di visualizzazione
* &amp;lbrack;Engine&amp;rbrack; Vengono visualizzati artefatti Bloccati quando viene attivato il comando di compressione della memoria
* &amp;lbrack;Esegui i baking&amp;rbrack; strani messaggi di errore quando si eseguono i baking trame specifiche
* &amp;lbrack;Export&amp;rbrack; PSD non sono scritti correttamente e non vengono riconosciuti correttamente da Photoshop
* &amp;blocca;Livelli&amp;rbrack; non dovrebbe essere possibile copiare/incollare i livelli in più progetti
* &amp;lbrack;Substance&amp;rbrack; in alcuni casi lo spazio colore UserData per l&#39;input Normale viene capovolto
* &amp;lbrack;Shelf&amp;rbrack; micro-normale nei generatori genera curvatura invertita
* &amp;lbrack;Shelf&amp;rbrack; il filtro HSL influisce anche sul canale alfa
* &amp;lbrack;Linux&amp;rbrack; l&#39;installazione su Centos non riesce a causa di dipendenze mancanti
* In alcuni casi, il programma di installazione non rimuove tutte le risorse dall&#39;installazione precedente

### 3.3.1 (2017.3.1)

*(Rilasciato il 26 ottobre 2017)*

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; Consente di esportare la trama da un progetto
* &amp;lbrack;Shelf&amp;rbrack; Rimuovi &quot;Sub-Shelf&quot; dai titoli delle schede
* Salvare le impostazioni di post-elaborazione nei modelli
* Rendere il messaggio TDR più comprensibile
* Finestra Migliora impostazioni per la segnalazione degli errori

**Corretto:**

* Arresto anomalo quando si eliminano più scaffali secondari
* Arresto anomalo quando si passa da un livello a qualcos&#39;altro durante il calcolo di un motore
* &amp;lbrack;Mac&amp;rbrack; Arresto anomalo sulla GPU Intel durante il calcolo del motore
* &amp;lbrack;Mac&amp;rbrack;&amp;lbrack;Viewport&amp;rbrack; Prestazioni errate quando è attivato il dithering
* &amp;lbrack;Mac&amp;rbrack; MacOS 10.13 viene riconosciuto come &quot;Versione sconosciuta&quot; nel file di registro
* &amp;lbrack;Baker&amp;rbrack; Eseguire i baking con una gabbia non funziona più
* &amp;lbrack;Layers&amp;rbrack; Ctrl + C scelta rapida da tastiera (azione copia) non funziona più
* &amp;lbrack;Layers&amp;rbrack; Incollare i livelli non aggiorna l&#39;interfaccia utente con i riferimenti dell&#39;ancoraggio
* &amp;lbrack;Ancoraggio&amp;rbrack; collegamenti per duplicare o copiare/incollare il livello con riferimenti
* &amp;lbrack;Export&amp;rbrack; 8K export can arresto anomalo or deadlock application in alcuni casi
* &amp;lbrack;Export&amp;rbrack; Più problemi nel formato di file glTF generato
* &amp;lbrack;Import&amp;rbrack; La reimportazione di una trama con lo stesso nome file non funziona più
* &amp;lbrack;Plugin&amp;brack; La finestra Salvataggio automatico viene sempre visualizzata sopra ogni elemento
* &amp;lbrack;UI&amp;rbrack; ciclo infinito quando si preme &quot;Esc&quot; nella finestra di dialogo TDR
* &amp;lbrack;UI&amp;rbrack; Reimposta interfaccia utente visualizza una seconda barra del titolo nella finestra scaffale

### 3.3.0 (2017.3.0)

*(Rilasciato il 28 settembre 2017)*

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; consente di esportare trama e texture per il progetto Felix di Adobe
* &amp;lbrack;Esporta&amp;rbrack; Consenti esportazione in formato file glTF
* &amp;lbrack;Engine&amp;rbrack; Ottimizza le dimensioni della texture nell&#39;VRAM utilizzando la compressione dei blocchi
* &amp;lbrack;Finestra di visualizzazione&amp;rbrack; possibilità di trascinare una trama o un progetto nella finestra della vista
* &amp;lbrack;UI&amp;rbrack; Migliora il messaggio di avviso relativo a TDR.
* &amp;lbrack;UI&amp;rbrack; Il registro deve essere visualizzato solo su richiesta
* &amp;lbrack;UI&amp;rbrack; Consenti di cancellare il contenuto della finestra del registro
* &amp;lbrack;UI&amp;rbrack; Visualizza avvisi ed errori nella barra di stato
* &amp;lbrack;UI&amp;rbrack; Visualizza le schede in alto come nei browser Web
* &amp;lbrack;UI&amp;rbrack; Migliora il contesto e i messaggi &quot;non colorabili&quot;
* &amp;lbrack;UI&amp;rbrack; Aggiungi un&#39;azione &quot;Salva come copia&quot; nel menu del file
* &amp;lbrack;Layer&amp;rbrack; Imposta l&#39;Affiancamento predefinito su 1 per impostazione predefinita
* &amp;lbrack;Shelf&amp;rbrack; filtro sfumatura migliorato per supportare 10 colori dinamici
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi uno spazio nella query predefinita del mini-shelf
* &amp;lbrack;Shelf&amp;rbrack; Aggiungere un&#39;azione &quot;Apri in Esplora risorse&quot; per le risorse locali nello scaffale
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi modello e shader per Adobe Material Standard (Project Felix)
* &amp;lbrack;Shelf&amp;rbrack; Aumenta l&#39;Affiancamento massimo a 128 nei livelli di materiale
* &amp;lbrack;Shelf&amp;rbrack; Curvatura sobel aggiunta per micro-dettagli dei Generatori di maschere
* &amp;lbrack;Plugin&amp;brack; Aggiungi plug-in di salvataggio automatico con intervallo di tempo personalizzabile
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi una funzione &quot;Salva come copia&quot;

**Corretto:**

* &amp;lbrack;UI&amp;rbrack; il layout non funziona al primo avvio
* &amp;lbrack;Export&amp;rbrack; PSD generato durante l&#39;esportazione presenta errori di formato
* &amp;lbrack;Export&amp;rbrack; EXR esporta sempre la mappa dell&#39;altezza a 8 bit
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo durante l&#39;esportazione di mappe aggiuntive danneggiate
* &amp;lbrack;Import&amp;rbrack; In alcuni casi i bordi netti non vengono mantenuti su trame poly basse
* &amp;lbrack;Import&amp;rbrack; messaggi di errore migliorati durante l&#39;importazione di trame con problemi
* &amp;lbrack;Baker&amp;rbrack; Il Eseguo i baking della mappa ID non riesce con l&#39;opzione Corrispondenza per nome attivata
* &amp;lbrack;Viewport&amp;rbrack; lo spazio tangente non è sincronizzato con i baker
* &amp;blocco;Effetto&amp;rbrack; Lo spostamento indietro di un livello non ripristina il riferimento di un ancoraggio
* &amp;lbrack;Effetto&amp;rbrack; Problema di aggiornamento durante la creazione di un collegamento tra due maschere con ancoraggi
* &amp;lbrack;Effetto&amp;rbrack; Le maschere con ancoraggi sopra la maschera non devono essere elencate
* &amp;lbrack;Effetto&amp;rbrack; L&#39;impostazione Estrai Alpha da Ancoraggi non funziona
* &amp;lbrack;Engine&amp;brack; La maschera si inverte dopo il primo tratto del pennello
* &amp;lbrack;Engine&amp;rbrack; Arresto anomalo quando si cambia set di texture in un progetto specifico
* &amp;lbrack;Shelf&amp;rbrack; Arresto anomalo quando si elimina un predefinito che si trova in un progetto
* &amp;lbrack;Shelf&amp;rbrack; Typo nel filtro avanzato Tri-Planari
* &amp;lbrack;Shelf&amp;rbrack; MG Mask Builder AO Noise Scale non funziona correttamente
* &amp;lbrack;Shelf&amp;rbrack; MG Mask Builder ha parametri di curvatura invertiti
* &amp;lbrack;Shelf&amp;rbrack; Le alfa importate generano un&#39;anteprima sfera di materiale invece di un&#39;anteprima piatta

### 3.2.0 (2017.2.0)

*(Rilasciato il 27 luglio 2017)*

**Aggiunto:**

* Punti di ancoraggio - Sistema di riferimento livello e maschera
* &amp;lbrack;Livelli&amp;rbrack; possibilità di rinominare effetti di riempimento e Pittura
* &amp;lbrack;Plugin&amp;rbrack; Plug-in Substance Source aggiornato
* &amp;lbrack;Scripting&amp;rbrack; Consenti di eseguire query sulla risoluzione del set di texture
* &amp;lbrack;Scripting&amp;rbrack; Consenti di ottenere lo stato del motore di pittura
* &amp;lbrack;Prestazioni&amp;rbrack; ottimizzazioni migliorate per il caricamento del progetto e la stampa del pennello

**Corretto:**

* &amp;lbrack;Tool&amp;rbrack; Problemi di prestazioni durante l&#39;ottimizzazione dei parametri del materiale
* &amp;lbrack;Motore&amp;rbrack; Scomparsa dei tratti del pennello durante la modifica della risoluzione (4K>2K)
* &amp;lbrack;vista 3D&amp;rbrack; lo spazio tangente non è sincronizzato con i baker
* &amp;lbrack;Shelf&amp;rbrack; Il percorso dello shelf nei documenti utente non viene creato automaticamente
* &amp;lbrack;Shelf&amp;rbrack; Rendi i predefiniti compatibili con le versioni precedenti dopo un aggiornamento
* &amp;lbrack;Shader&amp;rbrack; Lo shader non PBR non funziona più
* &amp;lbrack;Baker&amp;rbrack; Il Eseguo i baking della mappa ID non riesce con l&#39;opzione Corrispondenza per nome attivata
* &amp;lbrack;Sample&amp;rbrack; Incontra mascherino: i nomi dei set di texture di esempio del progetto non sono corretti
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura

### 3.1.0 (2017.1.0)

*(Rilasciato il 20 giugno 2017)*

**Aggiunto:**

* &amp;lbrack;Plugin&amp;rbrack; Nuovo plug-in Substance Source (consente di scaricare risorse nello scaffale)
* &amp;lbrack;Shelf&amp;rbrack; 4 nuovi font (giapponese + cinese semplificato, macchina da scrivere, segmento)
* &amp;lbrack;Shelf&amp;rbrack; 230 Nuovi Alpha (combinazione di pattern, pennelli e scansioni di impronte digitali)
* &amp;lbrack;Shelf&amp;rbrack; 50 Nuovi Procedurals (Modelli di tessuto di abbigliamento medievale e contemporaneo)
* &amp;lbrack;Shelf&amp;rbrack; 2 Nuove mappe ambientali (Mondarrain e Villa Nova Street)
* &amp;lbrack;Shelf&amp;rbrack; 9 Nuovi filtri (Edge Wear dettagli MatFx, Blocca, HBAO, ecc.)
* &amp;lbrack;Shelf&amp;rbrack; Mappa ambiente Panorama predefinita migliorata
* &amp;lbrack;Shelf&amp;rbrack; Nuovi predefiniti di esportazione Arnold 5
* &amp;lbrack;Scripting&amp;rbrack; Consenti importazione della risorsa nello scaffale

**Problemi noti:**

* &amp;lbrack;Esporta&amp;rbrack; La modifica di un predefinito di esportazione è molto lenta

## Versione 2

### 2.6.2

*(Rilasciato il 20 ottobre 2017)*

**Aggiunto:**

* &amp;lbrack;Set di texture&amp;rbrack; Consente di eliminare i set di texture disabilitati
* &amp;lbrack;Shelf&amp;rbrack; Consenti a più utenti di scrivere nella stessa cartella dello scaffale
* &amp;lbrack;Scripting&amp;rbrack; è possibile ricaricare la cartella dei plug-in
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi una versione API minima richiesta nei metadati del plug-in per garantire la compatibilità
* &amp;lbrack;IRay&amp;rbrack; finestra di dialogo Esporta immagine migliorata

**Corretto:**

* &amp;lbrack;Engine&amp;rbrack; Scomparsa dei tratti problema durante la modifica della risoluzione (4K>2K)
* &amp;lbrack;Baker&amp;rbrack; Il Eseguo i baking della mappa ID non riesce con l&#39;opzione Corrispondenza per nome attivata
* &amp;lbrack;Baker&amp;rbrack; I messaggi di errore non sono sufficientemente espliciti
* &amp;lbrack;vista 3D&amp;rbrack; lo spazio tangente non è sincronizzato con i baker
* &amp;lbrack;Strumento&amp;rbrack; artefatti di colore nero quando si utilizza lo strumento sfumino
* &amp;lbrack;Shader&amp;rbrack; Lo shader non PBR non funziona più
* &amp;lbrack;Shader&amp;rbrack; &quot;pbr-coated&quot; è interrotto
* &amp;lbrack;Shader&amp;rbrack; La rugosità dello shader &quot;pbr-coated&quot; non ha più alcun impatto
* &amp;lbrack;Shader&amp;rbrack; Lo shader lucido della specifica non corrisponde a Iray e SD
* &amp;lbrack;Shelf&amp;rbrack; Arresto anomalo durante il caricamento di due file con lo stesso nome ma estensioni diverse
* &amp;lbrack;Shelf&amp;rbrack; Impossibile modificare il predefinito negli scaffali
* &amp;lbrack;Shelf&amp;rbrack; Impossibile impostare un&#39;anteprima personalizzata per le risorse importate nello shelf
* Le risorse caricate dalla cache perdono il loro utilizzo
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura
* Salvataggio del progetto errato se il nome del file contiene due punti
* Importazione di file con più punti (.) nel nome del file causa problemi

### 2.6.1

*(Rilasciato il 12 maggio 2017)*

**Aggiunto:**

* &amp;lbrack;TextureSet&amp;rbrack; Non consentire la riassegnazione dei materiali mesh a nulla

**Corretto:**

* Arresto anomalo quando si cambia TextureSet dopo la sostituzione della mappa con baking
* Arresto anomalo quando si esegue &quot;Annulla e ripeti&quot; dopo aver modificato il metodo di fusione del livello
* Arresto anomalo o blocco quando si utilizza l&#39;effetto &quot;selezione colore&quot; con mappa ID grande
* &amp;lbrack;Export&amp;rbrack; I set di texture rinominati non sono ordinati alfabeticamente nella finestra di esportazione
* &amp;lbrack;TextureSet&amp;rbrack; Il ripristino del nome predefinito non controlla l&#39;unicità
* &amp;lbrack;TextureSet&amp;rbrack; Il set di texture rinominato diventa disattivato dopo la riapertura del progetto
* &amp;lbrack;Shelf&amp;rbrack; contenuto modelli predefiniti mancante
* &amp;lbrack;Shelf&amp;rbrack; le texture non quadrate vengono visualizzate come quadrate
* &amp;lbrack;Shader&amp;rbrack; una volta disattivato un set di texture, lo shader associato viene eliminato
* &amp;lbrack;Scripting&amp;rbrack; alg.eseguite i baking.setTextureSetBakingParameters() non funziona più
* &amp;lbrack;Scripting&amp;rbrack; Errore di battitura nell&#39;esercitazione websocket
* &amp;lbrack;Scripting&amp;rbrack; Vari problemi in AlgWidgets
* &amp;lbrack;Log&amp;rbrack; In alcuni casi, rilevamento non corretto della memoria virtuale disponibile

### 2.6.0

*(Rilasciato il 27 aprile 2017)*

**Aggiunto:**

* Aggiungi nuovo progetto di esempio &quot;Meet Mat&quot;
* &amp;lbrack;Plugin&amp;brack; Nuovo plug-in &quot;Resources Updater&quot;
* &amp;lbrack;TextureSet&amp;rbrack; consente di rinominare e aggiungere una descrizione ai set di texture
* &amp;lbrack;TextureSet&amp;rbrack; Consente di riassegnare i materiali
* &amp;lbrack;TextureSet&amp;rbrack; Aggiungi un pulsante di impostazione nella finestra dell’elenco di set di texture
* &amp;lbrack;TextureSet&amp;rbrack; Mostra i set di texture &quot;disabilitati&quot; nella parte inferiore dell’elenco
* &amp;lbrack;Substance&amp;rbrack; Utilizza mappe aggiuntive alla risoluzione corrente del set di texture per migliorare le prestazioni
* &amp;lbrack;Scripting&amp;rbrack; Consenti di aggiornare una risorsa utilizzata in un progetto (materiale, generatore, ecc.)
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi un modo per aggiungere/rimuovere uno scaffale
* &amp;lbrack;Scripting&amp;rbrack; Consenti di eseguire query sulle informazioni dalla risorsa nei progetti
* &amp;lbrack;Scripting&amp;rbrack; Consenti di recuperare un elenco di scaffali disponibili
* &amp;lbrack;Scripting&amp;rbrack; Esercitazione per migliorare la miniatura di AlgWidget
* &amp;lbrack;Esporta&amp;rbrack; Disattiva/Attiva profondità di bit in base al supporto del formato di file
* &amp;lbrack;Log&amp;rbrack; Aggiungi nome plug-in per la stampa nella console
* &amp;lbrack;Log&amp;brack; Rimuovi errore sui set di texture nascosti
* Aggiornate la &quot;Schermata introduttiva&quot; con nuove icone e testo per gli esempi

**Corretto:**

* Arresto anomalo durante l’aggiornamento di una trama in progetti specifici
* &amp;lbrack;Viewport&amp;rbrack; il colore interno del piano della Simmetria non è più visibile
* &amp;lbrack;Finestra di vista&amp;rbrack; Alcuni effetti di post-elaborazione sono attivati quando si utilizza la vista Solo
* &amp;lbrack;Shaders&amp;rbrack; la fusione &quot;over_premium&quot; non funziona correttamente
* &amp;lbrack;Shaders&amp;rbrack; Avvertenza sul test alfa con lo shader predefinito
* &amp;lbrack;Shelf&amp;rbrack; Analisi errata dei tag dalle Substance
* &amp;lbrack;Shelf&amp;rbrack; MatFX La misurazione tempo Ruggine non funziona correttamente
* &amp;lbrack;Shelf&amp;rbrack; il filtro HSL è attivato sui canali errati per impostazione predefinita
* &amp;lbrack;Shelf&amp;rbrack; Nitidezza è abilitato per impostazione predefinita sul canale Height/Normale
* &amp;lbrack;Export&amp;rbrack; I predefiniti di esportazione Vray non utilizzano una mappa normale OpenGL
* &amp;lbrack;Strumento&amp;rbrack; problemi di imprecisione con lo strumento clone/sfumino crea artefatti

### 2.5.3

*(Rilasciato il 15 marzo 2017)*

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo quando si esegue i baking con trame specifiche

**Problemi noti:**

* &amp;lbrack;Mac&amp;rbrack; Le particelle possono causare il danneggiamento delle texture in alcuni casi

### 2.5.2

*(Rilasciato il 14 marzo 2017)*

**Corretto:**

* &amp;lbrack;Tool&amp;rbrack; I tablet Wacom non funzionano su Linux
* &amp;lbrack;Strumento&amp;rbrack; artefatti di colore nero quando si utilizza lo strumento sfumino
* &amp;lbrack;Baker&amp;rbrack; Eseguita i baking non riuscita se si utilizza Corrispondenza per nome con una gabbia
* &amp;lbrack;Baker&amp;rbrack; Occlusione ambientale interrotta quando si esegue i baking solo con Mappa normale
* &amp;lbrack;Shelf&amp;rbrack; I filtri generici non gestiscono correttamente il canale alfa (Contrasto/Luminosità, Passa alto, ecc.)
* &amp;lbrack;Viewport&amp;rbrack; problema di prestazioni durante il caricamento di un progetto con le ombre attivate
* &amp;lbrack;Viewport&amp;rbrack; problema di dithering in vista 3D su MacOS
* &amp;lbrack;Viewport&amp;rbrack; Anteprime particelle visualizzate in modo errato quando il profilo colore è attivato
* &amp;lbrack;Iray&amp;rbrack; Arresto anomalo quando si ripristina il progetto in OpenGL se l’inizializzazione di Iray non è riuscita
* &amp;lbrack;IRay&amp;rbrack; La Lucentezza viene ignorata durante il rendering di SpecGloss shader/mdl
* &amp;lbrack;Shader&amp;rbrack; Spec/Gloss shader non corrisponde a Iray e SD
* &amp;lbrack;Shader&amp;rbrack; conversione sRGB diversa dalla conversione LUT lineare in sRGB
* &amp;lbrack;Shader&amp;rbrack; Rendering non corretto durante il caricamento di un progetto con ombreggiature obsolete
* &amp;lbrack;Shader&amp;rbrack; lo shader &quot;pbr-coated&quot; non funziona più
* &amp;lbrack;Esporta&amp;rbrack; alcuni canali vengono comunque esportati anche se non presenti nel set di texture
* &amp;lbrack;Layers&amp;rbrack; Il metodo di fusione &quot;mappa normale dettagli invertiti&quot; non funziona sui canali in scala di grigio
* &amp;lbrack;UI&amp;rbrack; Problema nella &quot;Finestra di selezione colore&quot; con monitor HDPI e zoom dello schermo al 150%

**Problemi noti:**

* &amp;lbrack;Mac&amp;rbrack; Le particelle possono causare il danneggiamento delle texture in alcuni casi

### 2.5.1

*(Rilasciato il 27 febbraio 2017)*

**Corretto:**

* &amp;lbrack;Mac&amp;rbrack; input tablet Wacom interrotto in 3D e Vista 2D
* &amp;lbrack;Baker&amp;rbrack; La corrispondenza per nome non funziona più
* &amp;lbrack;Baker&amp;rbrack; l&#39;impostazione &quot;Media normali&quot; non funziona più
* &amp;lbrack;Iray&amp;rbrack; rendering non corretto con mappa normale eseguita i baking mancante
* &amp;lbrack;Iray&amp;brack; i profili colore si comportano in modo diverso rispetto al modulo di rendering OpenGL
* &amp;lbrack;Iray&amp;brack; L&#39;esportazione del rendering come bitmap non include la correzione del profilo colore
* &amp;lbrack;Substance&amp;rbrack; i Filtri materiali non funzionano più
* &amp;lbrack;Strumento&amp;brack; L&#39;opacità del tratto non viene memorizzata nei predefiniti del pennello
* &amp;lbrack;Strumento&amp;rbrack; Allineamento UV pennello Clona /Clone non funziona più
* &amp;lbrack;Export&amp;rbrack; Il canale di Spostamento deve essere centrato in 0,5 quando si esporta in numero intero
* &amp;lbrack;Template&amp;rbrack; il percorso assoluto viene memorizzato in Modelli
* &amp;lbrack;TextureSet&amp;rbrack; La texture dei canali persiste dopo la rimozione del canale

**Problemi noti:**

* &amp;lbrack;Linux&amp;rbrack; Gli input dei tablet Wacom non funzionano in 3D e Vista 2D
* &amp;lbrack;Mac&amp;rbrack; Le particelle possono causare il danneggiamento delle texture in alcuni casi
* &amp;lbrack;Export&amp;brack; In casi molto rari, i rettangoli neri possono apparire sulle GPU AMD

### 2.5.0

*(Rilasciato il 21 febbraio 2017)*

**Aggiunto:**

* Aggiunta del supporto per le GPU AMD Radeon Pro e AMD FirePro
* &amp;blocca;Strumento&amp;Raccoglitore; Aggiungi il supporto per l&#39;opacità del tratto
* &amp;lbrack;Strumento&amp;rbrack; Aggiungi un modificatore che consenta di continuare l’ultimo tratto del pennello
* &amp;lbrack;Iray&amp;brack; Aggiornamento per supportare le GPU Pascal
* &amp;lbrack;Viewport&amp;rbrack; Aggiungi supporto per profili colore (LUT)
* &amp;lbrack;Substance&amp;rbrack; Integrazione del nuovo framework (motore SD6)
* &amp;lbrack;UI&amp;rbrack; Aumenta elenco dimensioni &quot;file recenti&quot; nel menu File
* &amp;lbrack;Import&amp;rbrack; Utilizza la categoria da sostanze per riempire il prefisso nella finestra di dialogo di importazione
* &amp;lbrack;Baker&amp;rbrack; Consenti di eseguire i baking texture 8K
* &amp;lbrack;Baker&amp;rbrack; Consente di eseguire i baking risoluzioni non quadrate
* &amp;lbrack;Baker&amp;rbrack; migliora il consumo di memoria quando si eseguono i baking trame pesanti a elevato polio
* &amp;lbrack;Shelf&amp;rbrack; Blocca ripiani (e progetti) per impedire modifiche simultanee ed evitare danneggiamenti
* &amp;lbrack;Shelf&amp;rbrack; Leggi la categoria e le parole chiave dalle sostanze per utilizzarle per filtrare
* &amp;lbrack;Shelf&amp;rbrack; Consente di escludere le risorse dal risultato di una query di ricerca
* &amp;lbrack;Shelf&amp;rbrack; Miniature migliorate nel calcolo del tempo
* &amp;lbrack;Shelf&amp;rbrack; Consenti di incorporare predefiniti nei progetti
* &amp;lbrack;Shelf&amp;rbrack; Consenti di comprimere/espandere rapidamente la visualizzazione struttura con MAIUSC
* &amp;lbrack;Shelf&amp;rbrack; Consente di salvare le miniature quando le risorse sono di sola lettura (cache locale)
* &amp;lbrack;Shelf&amp;rbrack; Nuovo contenuto : nuovi filtri (Trasforma, mirror, tri-planari, ecc.)
* &amp;lbrack;Shelf&amp;rbrack; Nuovo contenuto : nuovi profili LUT (classici e artistici, ad esempio Film Noir, Vintage e così via)
* &amp;lbrack;Shelf&amp;rbrack; Nuovo contenuto: 10 nuove Substance di font per generare rapidamente testi personalizzati
* &amp;lbrack;Shelf&amp;rbrack; Nuovi modelli: Unity 5 e Unreal Engine 4
* &amp;lbrack;Shelf&amp;rbrack; Filtro HSL migliorato per semplificare l&#39;uso degli artisti
* &amp;lbrack;Shader&amp;rbrack; Aggiungi supporto per canale di specular level negli shader PBR
* &amp;lbrack;Shader&amp;rbrack; Aggiungi il supporto per il dithering nello shader di test Alpha
* &amp;lbrack;Shader&amp;rbrack; Aggiungi il supporto per la mappatura delle occlusioni parallasse negli shader PBR
* &amp;lbrack;Shader&amp;rbrack; Consente di definire un&#39;interfaccia utente personalizzata per i parametri di shader
* &amp;lbrack;MatLayering&amp;rbrack; Crea un nuovo canale maschera per il flusso di lavoro per la creazione di livelli di materiale
* &amp;lbrack;Scripting&amp;rbrack; Consenti la scrittura di metadati in un progetto SP
* &amp;lbrack;Scripting&amp;rbrack; Consente di esportare con un predefinito di esportazione specifico
* &amp;lbrack;Scripting&amp;rbrack; consente di recuperare i parametri di shader come JSON
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi supporto per connessioni WebSocket
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi la possibilità di caricare istanze shader
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi la possibilità di creare un nuovo progetto
* &amp;lbrack;Scripting&amp;rbrack; Consente di recuperare l&#39;URL della trama importata in un progetto
* &amp;lbrack;Scripting&amp;rbrack; Consenti esegue i baking non quadrata
* &amp;lbrack;Scripting&amp;rbrack; Segnala errori durante l’impostazione dei dati tramite API di scripting
* &amp;lbrack;Substance&amp;rbrack; Aggiungi tag utente-dati per specificare il formato mappa normale

**Corretto:**

* Arresto anomalo di selezione del colore con le sostanze
* Arresto anomalo durante il caricamento di un&#39;immagine non RGBA32f come mappa dell&#39;ambiente
* Arresto anomalo relativo alla pittura su GPU AMD
* &amp;lbrack;Mesh&amp;brack; l&#39;importazione OBJ non riconosce i materiali senza file mtl
* &amp;lbrack;Mesh&amp;rbrack; La generazione del nome del set di texture UDIM può non essere corretta su alcune trame
* &amp;lbrack;UI&amp;rbrack; pulsante Annulla/Ripeti nel visualizzatore Impostazione dello stato attivo e interruzione dello scorrimento del mouse
* &amp;lbrack;UI&amp;rbrack; alcune etichette vengono ritagliate in modo errato con valori DPI alti
* &amp;lbrack;Layer&amp;rbrack; La modalità Sostituisci per l&#39;effetto pittura ha un comportamento errato su Maschera
* &amp;lbrack;Layer&amp;rbrack; il metodo di fusione Sottrai ha un comportamento errato con il canale alfa
* &amp;lbrack;Strumento&amp;rbrack; la dimensione del pennello diventa enorme in vista 2D quando si disegna sui bordi UV
* &amp;lbrack;Tool&amp;rbrack; La linea retta agganciata ha un comportamento irregolare con DPI alto
* &amp;lbrack;Tool&amp;rbrack; La risoluzione dello stencil a volte non è corretta
* &amp;lbrack;Baker&amp;rbrack; i valori di &quot;Distanza max occlusione&quot; sono bloccati se &quot;relativa al rettangolo di selezione&quot; è &quot;Disattivato&quot;
* &amp;lbrack;Shader&amp;rbrack; Le definizioni dei canali Stack e Param automatico non corrispondono
* &amp;lbrack;vista 3D&amp;rbrack; Visualizzazione incoerente del canale normale a seconda dell&#39;impostazione del progetto
* &amp;lbrack;Viewport&amp;rbrack; Alcune mappe normali hanno valori bloccati che appaiono come artefatti
* &amp;lbrack;Viewport&amp;rbrack; Gli effetti successivi sono sempre disattivati per impostazione predefinita
* &amp;lbrack;Export&amp;rbrack; L&#39;impostazione di miscelazione normale non è corretta se manca il canale normale
* &amp;lbrack;Export&amp;rbrack; Generazione errata di texture in alcuni casi su GPU AMD
* &amp;lbrack;Export&amp;rbrack; I parametri di Shader non vengono esportati correttamente se sono inclusi in un gruppo
* &amp;lbrack;Export&amp;rbrack; Modifica di un predefinito di esportazione in uno scaffale personalizzato genera un errore di registro
* &amp;lbrack;Shelf&amp;rbrack; Il filtro della visualizzazione a struttura non corrisponde esattamente al nome della cartella
* &amp;lbrack;Shelf&amp;rbrack; Ridenominare uno shelf predefinito è difficile da leggere
* &amp;lbrack;Shelf&amp;rbrack; la risorsa Shader importata nello scaffale non viene mantenuta dopo il riavvio
* &amp;lbrack;Shelf&amp;rbrack; Contenuto: Predefinito strumento saldatura mancante
* &amp;lbrack;Shelf&amp;rbrack; Contenuto: il Tile Generator non funziona correttamente
* &amp;lbrack;Shelf&amp;rbrack; Contenuto : Corretta la maschera errata sul materiale avanzato sporco di gomma
* &amp;lbrack;Shelf&amp;rbrack; Contenuto : Corretto il nome del gruppo errato nel materiale del sacchetto in pelle
* &amp;lbrack;Iray&amp;rbrack; metà delle trame non è presente in Iray
* &amp;lbrack;Linux&amp;rbrack; Arresto anomalo quando si trascina una risorsa sopra il vista 3D
* &amp;lbrack;Mac&amp;rbrack; Le preferenze vengono reimpostate a ogni avvio su Sierra

**Problemi noti:**

* &amp;lbrack;Export&amp;brack; In casi molto rari, i rettangoli neri possono apparire sulle GPU AMD
* &amp;lbrack;Iray&amp;rbrack; a volte i profili colore possono comportarsi in modo strano

### 2.4.1

*(Rilasciato il 28 ottobre 2016)*

**Corretto:**

* Arresto anomalo di creazione di un progetto con un modello
* Arresto anomalo di chiusura della finestra di dialogo di esportazione durante un’esportazione
* &amp;lbrack;Mac&amp;rbrack; Errori durante il salvataggio del progetto (impossibile salvare il predefinito di esportazione)
* &amp;lbrack;Shelf&amp;rbrack; La creazione di un nuovo predefinito lo visualizzerà due volte
* &amp;lbrack;Shelf&amp;rbrack; I predefiniti non possono essere caricati in modalità di sola lettura senza diritti di amministratore

### 2.4.0

*(Rilasciato il 27 ottobre 2016)*

**Aggiunto:**

* &amp;lbrack;Shelf&amp;rbrack; Nuova interfaccia per sfogliare le risorse (vista struttura, filtri e così via)
* &amp;lbrack;Shelf&amp;rbrack; Consenti di salvare una ricerca come predefinito
* &amp;lbrack;Shelf&amp;rbrack; Consenti di creare una nuova finestra da un predefinito
* &amp;lbrack;Shelf&amp;rbrack; Nuova interfaccia per l&#39;importazione delle risorse
* &amp;lbrack;Shelf&amp;rbrack; Non copiare lo scaffale allegorico predefinito nella cartella Documenti
* &amp;lbrack;Shelf&amp;rbrack; Nuovi predefiniti particelle: Circuito elettrico, Linee elettriche, Rococò, Vene piccole
* &amp;lbrack;Shelf&amp;rbrack; Migliorati i vecchi predefiniti particelle per essere più facili da usare (come &quot;Rain&quot;)
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi nuove informazioni nel menu di scelta rapida della risorsa
* &amp;lbrack;Viewport&amp;rbrack; migliora le prestazioni durante il caricamento delle mappe dell&#39;ambiente
* &amp;lbrack;Viewport&amp;rbrack; Aggiungi supporto per mappe di ambiente che non sono alimentate da due

**Corretto:**

* Arresto anomalo durante la rimozione di una maschera
* Arresto anomalo quando si disegna dopo aver salvato un predefinito
* Arresto anomalo con sfocatura dell’ambiente su alcune GPU
* Arresto anomalo durante l&#39;assegnazione di una risorsa errata con lo scaffale inferiore
* &amp;lbrack;Shelf&amp;rbrack; Pulisci + Salva rimuovi tag e metadati per le risorse nel progetto
* &amp;lbrack;Shelf&amp;rbrack; l&#39;importazione di un predefinito ne visualizzerà le risorse nello scaffale
* &amp;lbrack;Export&amp;rbrack; La Mappa normale generata dal canale del height ha un’intensità bassa
* &amp;lbrack;Export&amp;rbrack; Normale da trama non è sempre presente nella mappa normale finale
* &amp;lbrack;Export&amp;rbrack; A volte la dilatazione con trasparenza può risultare senza trasparenza
* &amp;lbrack;Scripting&amp;rbrack; &quot;alg.plugin_root_directory&quot; può restituire un percorso di rete troncato
* &amp;lbrack;TextureSet&amp;rbrack; Il pulsante Blocca è attivato quando si riaprono progetti non quadrati

### 2.3.1

*(Rilasciato il 7 ottobre 2016)*

**Aggiunto:**

* &amp;lbrack;Plugin&amp;rbrack;&amp;lbrack;Photoshop&amp;rbrack; Consenti di specificare il materiale/stack/canali da esportare
* &amp;lbrack;Scripting&amp;rbrack; I nomi delle funzioni presentano alcune incongruenze

**Corretto:**

* &amp;lbrack;Export&amp;rbrack; L&#39;Alpha può essere eliminato nei predefiniti di esportazione personalizzati
* &amp;lbrack;Export&amp;rbrack; Alpha ottiene una conversione gamma errata sui canali sRGB
* &amp;lbrack;Esporta&amp;rbrack; i documenti non quadrati vengono esportati come quadrati
* &amp;lbrack;Export&amp;rbrack; Impossibile esportare mappe aggiuntive se ne manca una
* &amp;lbrack;Iray&amp;rbrack; Alcuni parametri (come Intensità emissivo) non hanno effetto
* &amp;lbrack;NVIDIA&amp;rbrack; Arresto anomalo all&#39;avvio con NVIDIA Quadro K2200/GTX 750/760
* &amp;lbrack;AMD&amp;rbrack; set di colori non corretto per miniature e anteprime
* &amp;lbrack;AMD&amp;rbrack; si blocca e si verifica un errore del driver all&#39;apertura di un nuovo file
* &amp;lbrack;Log&amp;rbrack; &quot;software-version&quot; non è presente nel file di log

### 2.3.0

*(Rilasciato il 15 settembre 2016)*

**Aggiunto:**

* &amp;lbrack;Plugin&amp;rbrack; Nuovo plug-in &quot;Esporta in Photoshop&quot; (esportazione Pila livelli completa)
* &amp;lbrack;Esporta&amp;rbrack; Consenti di specificare la larghezza della spaziatura interna (in pixel o infinito)
* &amp;lbrack;Esporta&amp;rbrack; Consenti di impostare il tipo di sfondo al di fuori degli UV
* &amp;lbrack;Shelf&amp;rbrack; Nuovo shader di stratificazione del materiale per fondere 10 materiali
* &amp;lbrack;Shelf&amp;rbrack; Nuovo shader argilla per visualizzare i dettagli con il canale height/normale
* &amp;lbrack;Shelf&amp;rbrack; Nuovo filtro di illuminazione eseguito i baking con input ambiente
* &amp;lbrack;Shelf&amp;rbrack; aggiornato alcuni generatori di maschere per aggiungere trasformazioni non quadrate
* &amp;lbrack;Viewport&amp;rbrack; Aggiungi mappa normale composta (normale+height+esegue i baking) alla modalità Solo
* &amp;lbrack;Scripting&amp;rbrack; Consente di esportare mappe aggiuntive
* &amp;lbrack;Scripting&amp;rbrack; Consenti di eseguire query sulle mappe aggiuntive disponibili per set di texture
* &amp;lbrack;Scripting&amp;rbrack; Consenti di recuperare il formato del canale
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi esempi nella documentazione di esegue i baking
* &amp;lbrack;Scripting&amp;rbrack; Consenti di eseguire query sulla visibilità di un livello
* &amp;lbrack;Scripting&amp;rbrack; Consenti di eseguire query sul metodo di fusione e sull&#39;opacità del livello
* &amp;lbrack;Scripting&amp;rbrack; Consente di esportare le mappe convertite (mappa normale finale, AO misto e così via)
* &amp;lbrack;Substance&amp;rbrack; lettura e connessione degli usi personalizzati
* &amp;blocca;Scelte rapide&amp;rbrack; Aggiungi tasto modificatore (MAIUSC) per tornare alla modalità Solo
* &amp;lbrack;Esporta&amp;rbrack; Predefinito di esportazione predefinito aggiornato per disabilitare il canale alfa
* &amp;lbrack;UI&amp;rbrack; Le miniature ora vengono calcolate solo se il motore è disponibile
* &amp;lbrack;UI&amp;rbrack; visualizza una menzione quando le miniature sono in fase di elaborazione

**Corretto:**

* Arresto anomalo con alcuni vecchi progetti all’apertura
* Arresto anomalo con cache canali texture danneggiata
* Arresto anomalo quando si fondono più di 4 materiali con il flusso di lavoro Livelli di materiale
* &amp;lbrack;UI&amp;rbrack; Le scelte rapide dello strumento non funzionano se la barra degli strumenti è nascosta
* &amp;lbrack;UI&amp;rbrack; La barra degli strumenti Iray è denominata &quot;Senza titolo&quot; nel menu Visualizza
* &amp;lbrack;UI&amp;rbrack; Le barre degli strumenti Plugin sono denominate &quot;Untilted&quot; nel menu Visualizza
* &amp;lbrack;Baker&amp;rbrack; premendo Invio durante la modifica di un&#39;impostazione di esegue i baking si avvia la esegue i baking
* &amp;lbrack;Baker&amp;rbrack; Intervalli non corretti per alcuni parametri
* &amp;lbrack;Import&amp;rbrack; impossibile importare trame OBJ a causa dei numeri molto grandi
* &amp;lbrack;Import&amp;rbrack; Alcuni file OBJ vengono importati con troppi sottooggetti
* &amp;nero;Esporta&amp;rbrack; lo sfondo del canale viene riempito con il nero invece del colore predefinito al momento dell&#39;esportazione
* &amp;lbrack;Tool&amp;rbrack; Le particelle non funzionano correttamente se il valore FOV è troppo basso
* &amp;lbrack;Strumento&amp;rbrack; Il colore di anteprima del pennello non è corretto con le maschere nei sottoinsiemi
* &amp;lbrack;Viewport&amp;rbrack; Quando il pennello passa in aree vuote nel Vista 2D, diventa gigantesco
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Anteprima pennello vuoto quando si disegna texture normale
* &amp;lbrack;Scripting&amp;rbrack; Documentazione non corretta: &quot;ao&quot; è elencato invece di &quot;ambientocclusion&quot;
* &amp;lbrack;Scripting&amp;rbrack; Il processo avviato con subprocess() viene interrotto alla chiusura di Painter
* &amp;lbrack;Shelf&amp;rbrack; il filtro di illuminazione Eseguito i baking utilizza un input AO errato
* &amp;lbrack;MacOS&amp;rbrack; Rimosso progetto idrante (incompatibile)
* Il progetto predefinito viene aperto quando si carica un file \*.spt (anziché \*.spp)

**Problemi noti:**

* &amp;lbrack;Plugin&amp;rbrack; A causa di Photoshop, il height e il canale normale non possono essere tradotti così com&#39;è

### 2.2.0

*(Rilasciato il 22 luglio 2016)*

**Aggiunto:**

* &amp;lbrack;Shelf&amp;rbrack; Migliorare il sistema di ricerca e le query
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi campo di ricerca per i mini-scaffali
* &amp;lbrack;Shader&amp;rbrack; Consenti di definire la precisione dei passi per i cursori
* &amp;lbrack;Shader&amp;rbrack; Aggiungi un pulsante Annulla/Ripeti per i parametri degli shader
* &amp;lbrack;Shader&amp;rbrack; Il ricaricamento di uno shader non deve reimpostare i relativi parametri
* &amp;lbrack;MatLayering&amp;rbrack; Aggiungi il supporto per Stratificazioni dinamiche del materiale e sottopile
* &amp;lbrack;MatLayering&amp;rbrack; Consenti di importare il file json per configurare le impostazioni di shader
* &amp;lbrack;MatLayering&amp;rbrack; Sblocca il limite dei campionatori texture (passa a texture senza binding)
* &amp;lbrack;Scripting&amp;rbrack; Consenti di impostare le impostazioni dei baker e di avviarne il calcolo
* &amp;lbrack;Substance&amp;rbrack; Utilizza &quot;utilizzo&quot; per connessioni di input/output oltre agli identificatori
* &amp;lbrack;Strumento&amp;rbrack; Consenti di selezionare il canale di anteprima nella finestra della vista per lo strumento Proiezione

**Corretto:**

* Arresto anomalo all&#39;avvio se le sostanze si trovano in una cartella errata
* Il report di Arresto anomalo a volte non funziona a causa di un file di registro errato
* &amp;lbrack;Iray&amp;rbrack; Effetti post non vengono aggiornati quando Iray è in pausa
* &amp;lbrack;Iray&amp;rbrack; L&#39;attivazione automatica della scelta rapida da tastiera non funziona più
* &amp;lbrack;Iray&amp;rbrack; Il comportamento del cursore Apertura cambia a seconda delle dimensioni della risorsa
* &amp;lbrack;Livelli&amp;rbrack; Il primo canale di materiale non è attivato per impostazione predefinita se è disattivato
* &amp;lbrack;Shader&amp;rbrack; Se un &quot;parametro automatico&quot; non è corretto, non viene stampato alcun errore

**Problemi noti:**

* &amp;lbrack;Mac&amp;rbrack; il limite di campioni di Texture è bloccato a 16 (problema con il driver della GPU)

### 2.1.1

*(Rilasciato il 1° luglio 2016)*

**Aggiunto:**

* &amp;lbrack;License&amp;rbrack; Possibilità di modificare il percorso del file di licenza
* &amp;lbrack;Viewport&amp;rbrack; Aggiungi una scelta rapida da tastiera &quot;B&quot; per passare da una mappa all&#39;altra
* &amp;lbrack;Import&amp;rbrack; Consenti di importare correttamente FBX 2016/2017
* &amp;lbrack;Strumento&amp;rbrack; Rimuovi i controlli quando si utilizza la maschera veloce
* &amp;lbrack;Iray&amp;brack; Aggiungi informazioni sulle dimensioni della scena
* &amp;lbrack;Iray&amp;rbrack; Consenti di aumentare il numero massimo di campioni e il tempo di rendering
* &amp;lbrack;UI&amp;rbrack; Aggiorna immediatamente il risultato quando si utilizza il pulsante +/- sui cursori
* &amp;lbrack;UI&amp;rbrack; Consente una maggiore precisione per i cursori in scala di grigi
* &amp;lbrack;Esporta&amp;rbrack; Non esportare un canale alfa per texture che sono solo RGB
* &amp;lbrack;Export&amp;rbrack; Aggiorna predefinito di esportazione Dota 2
* &amp;lbrack;Shelf&amp;rbrack; Nuovo pattern &quot;Esagono porzioni&quot;
* &amp;lbrack;Shelf&amp;rbrack; nuovo strumento &quot;Saldatura&quot;
* &amp;lbrack;Shelf&amp;rbrack; Filtri di fine aggiornati per fornire controlli di direzione

**Corretto:**

* &amp;lbrack;Export&amp;rbrack; Impossibile esportare file PSD in 8 bit
* &amp;lbrack;Export&amp;rbrack; 8K export non è disponibile in alcune configurazioni hardware
* &amp;lbrack;Export&amp;rbrack; La finestra Sketchfab è ritagliata
* &amp;lbrack;Esporta&amp;rbrack; Mapping di rugosità errato nel predefinito di esportazione Spec/Gloss
* &amp;lbrack;UI&amp;rbrack; La digitazione nei cursori in scala di grigi non funziona più
* &amp;lbrack;UI&amp;rbrack; impossibile inserire filtri negli input di substance (come Generatori)
* &amp;lbrack;UI&amp;rbrack; Alcuni cursori hanno comportamenti dispari
* &amp;lbrack;UI&amp;rbrack; il passaggio DeltaTime +/- per le particelle è troppo grande
* &amp;lbrack;Iray&amp;brack; Alcuni progetti bloccano l&#39;applicazione quando si passa a Iray
* &amp;lbrack;Iray&amp;rbrack; Arresto anomalo durante il rilevamento dell&#39;hardware
* &amp;lbrack;Strumento&amp;rbrack; Il colore di anteprima del pennello non è corretto in modalità Maschera
* &amp;lbrack;Strumento&amp;rbrack; il selettore materiale può essere utilizzato con strumenti incompatibili
* &amp;lbrack;Strumento&amp;rbrack; L&#39;anteprima di proiezione non passa a Diffusa con flusso di lavoro Spec/Gloss
* &amp;lbrack;Shelf&amp;rbrack; La modifica dello shader predefinito interrompe le anteprime smart mats/maschera avanzata
* &amp;lbrack;Shelf&amp;rbrack; Alcuni materiali avanzati hanno nomi errati
* &amp;lbrack;Shelf&amp;rbrack; altre forme alfa sono danneggiate e non verranno caricate
* &amp;lbrack;Viewport&amp;rbrack; Passare alla modalità &quot;Mappa aggiuntiva&quot; e visualizzare prima &quot;altro&quot;
* &amp;lbrack;Viewport&amp;rbrack; Il viewport torna a &quot;other&quot; quando non esiste una mappa aggiuntiva
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Linux&amp;rbrack; Il report Arresto anomalo non funziona su Ubuntu (Steam)
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Linux&amp;rbrack; I collegamenti agli URL Web non funzionano su Ubuntu (Steam)
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Windows&amp;rbrack; Rimuovi &quot;crashwatcher&quot; quando Substance painter non viene più eseguito
* &amp;lbrack;Arresto anomalo&amp;rbrack;&amp;lbrack;Mac&amp;rbrack; Arresto anomalo del report non funziona correttamente
* &amp;lbrack;Arresto anomalo&amp;rbrack; importazione di una trama durante l&#39;importazione di una trama porta a un arresto anomalo
* Set di texture scelta rapida da tastiera di prelievo reimpostato su niente dopo un riavvio

### 2.1.0

*(Rilasciato il 2 giugno 2016)*

**Aggiunto:**

* &amp;lbrack;UDIM&amp;rbrack; Importa porzioni UDIM da una trama come set di texture
* &amp;lbrack;Linux&amp;rbrack; Supporto aggiunto per CentOS 6.6 e Ubuntu 12.4
* &amp;lbrack;Export&amp;rbrack; Aggiungi risoluzione 8K (sperimentale)
* &amp;lbrack;Esporta&amp;rbrack; Consenti di scegliere la profondità di bit durante l&#39;esportazione
* &amp;lbrack;Baker&amp;rbrack; Consenti di eseguire i baking più set di texture contemporaneamente
* Supporto di monitor ad alta risoluzione (ridimensionamento DPI elevato)
* &amp;lbrack;Scripting&amp;rbrack; impostare una risoluzione e un riempimento personalizzati per texture al momento dell&#39;esportazione
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; consente di passare da un set di texture all&#39;altro facendo clic sulla trama (tramite Ctrl+Alt+Clic)
* &amp;lbrack;Viewport&amp;rbrack; andare dove si trova il cursore del mouse quando si esegue lo zoom con la rotellina del mouse
* &amp;lbrack;UI&amp;rbrack; aggiorna il colore di sfondo predefinito e la visualizzazione della mappa dell&#39;ambiente
* &amp;lbrack;UI&amp;rbrack; Aggiungi descrizioni comandi con nomi originali per i canali utente
* &amp;lbrack;UI&amp;rbrack; Cambia il colore di sfondo per i canali che non possono essere rinominati
* &amp;lbrack;Strumento&amp;rbrack; Rimuovi i controlli quando si utilizza la maschera veloce
* &amp;lbrack;Shader&amp;rbrack; Consente di definire i gruppi per i parametri e i materiali/le maschere di shader
* &amp;lbrack;Engine&amp;rbrack; ottimizzazione della stampa di piccole dimensioni
* &amp;lbrack;Stencil&amp;rbrack; Aggiungi &quot;W&quot; come scelta rapida da tastiera per attivare/disattivare temporaneamente la maschera
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi un pulsante x per cancellare il campo di ricerca
* &amp;lbrack;Shelf&amp;rbrack; Carica Alpha con un solo clic
* &amp;lbrack;Shelf&amp;rbrack; Nuovo predefinito di esportazione: Vray UDIM, Arnold UDIM, Spec/Gloss da Metal/Rough
* &amp;lbrack;Shelf&amp;rbrack; Nuove alfa: forme, vene e segni geometrici
* Aggiungi nome e versione nelle proprietà dell&#39;eseguibile Substance Painter

**Corretto:**

* &amp;lbrack;Substance&amp;rbrack; impossibile utilizzare contemporaneamente il canale normale e la mappa aggiuntiva
* &amp;lbrack;Iray&amp;rbrack; rifrazione MDL e impostazione assorbimento non funzionano
* &amp;lbrack;Iray&amp;rbrack; La scala della scena originale non viene mantenuta
* &amp;lbrack;Shelf&amp;rbrack; il modello di Specular/Lucentezza utilizza uno shader errato
* &amp;lbrack;Esporta&amp;rbrack; il predefinito di esportazione predefinito non esporta alcune mappe (come AO)
* &amp;lbrack;Viewport&amp;rbrack; Il punto pivot non si aggiorna quando si fa clic all&#39;esterno degli UV nel vista 2D
* &amp;lbrack;UI&amp;rbrack; I valori del cursore sono arrotondati
* &amp;lbrack;UI&amp;rbrack; A volte, quando si modificano i valori dei cursori, lo spazio libero è molto ridotto
* &amp;lbrack;Nuovo progetto&amp;rbrack; L&#39;elenco a discesa Modello non è aggiornato correttamente (da 1.x a 2.x)
* &amp;lbrack;Scripting&amp;rbrack; Corretto il comportamento al passaggio del mouse sui pulsanti personalizzati
* &amp;lbrack;Mac&amp;rbrack; Annullando su un progetto vuoto, la videocamera si blocca

**Problemi noti:**

* Il report di Arresto anomalo non è disponibile su Ubuntu
* Alcuni pulsanti URL potrebbero non funzionare. Consulta le domande frequenti per una soluzione alternativa.

### 2.0.5

*(Rilasciato il 29 aprile 2016)*

**Aggiunto:**

* &amp;lbrack;Shelf&amp;rbrack; aggiunto/aggiornato modello non pbr, shader ed esportazione predefinito
* &amp;lbrack;Shelf&amp;rbrack; Predefinito di esportazione UE4 aggiornato per includere l&#39;Occlusione ambientale

**Corretto:**

* Arresto anomalo durante l&#39;apertura e il salvataggio di alcuni progetti con risorse danneggiate
* &amp;lbrack;Viewport&amp;rbrack; il Wireframe appare interrotto nel Vista 2D
* &amp;lbrack;Shelf&amp;rbrack; Prestazioni migliorate di alcune mappe dell&#39;ambiente di studio
* &amp;lbrack;Shelf&amp;rbrack; Alcune mappe dell&#39;ambiente di studio sono duplicate
* &amp;lbrack;Shelf&amp;rbrack; &quot;Materiale di illuminazione Eseguito i baking&quot; mancante
* &amp;lbrack;Shelf&amp;rbrack; generatore &quot;Conversione scala di grigi&quot; mancante

### 2.0.4

*(Rilasciato il 26 aprile 2016)*

**Aggiunto:**

* Migliorare le collisioni di trama e ottimizzare il rendering dei wireframi
* Migliorare le prestazioni e la gestione della memoria con i grandi progetti
* Migliorare la precisione del cursore e i passaggi
* &amp;lbrack;UI&amp;rbrack; Aggiorna il motore solo quando si convalida un cursore (non quando si immette un valore)
* &amp;lbrack;UI&amp;rbrack; Sposta lo switch Iray in un pulsante dedicato nella barra degli strumenti principale (e cambiane la scelta rapida da tastiera)
* &amp;lbrack;Strumento&amp;rbrack; Aggiungi impostazione per il comportamento posizione origine strumento clone
* &amp;lbrack;Shader&amp;rbrack; consente di leggere i colori dei vertici della trama negli ombreggiatori personalizzati
* &amp;lbrack;Scripting&amp;rbrack; Consente di recuperare l’elenco di set di texture, canali e livelli
* &amp;lbrack;Scripting&amp;rbrack; Aggiungi funzioni di supporto (URL al percorso, ottieni percorso di esportazione dal progetto)
* &amp;lbrack;Mac&amp;rbrack; Rileva la versione &quot;El Capitan&quot; del sistema operativo Mac nel file di registro

**Corretto:**

* Arresto anomalo dopo la seconda esportazione nel Substance share
* Arresto anomalo quando si copia un livello tra set di texture con dati di Maschera veloce.
* Alcuni progetti hanno un programma di aggiornamento molto lungo che richiede molta memoria
* &amp;lbrack;Strumento&amp;rbrack; Arresto anomalo durante la selezione di un predefinito di particella con lo strumento clone/sfumino
* &amp;lbrack;Baker&amp;rbrack; Il caricamento dei file FBX richiede troppo tempo per trame pesanti
* &amp;lbrack;Viewport&amp;rbrack; mappa dell&#39;ambiente Allungamento in alcuni computer
* &amp;lbrack;Viewport&amp;rbrack; Conversione gamma errata dell&#39;alfa del pennello
* &amp;lbrack;Export&amp;rbrack; Alpha memorizzato come trasparenza anziché come canale separato con file Tiff.
* &amp;lbrack;Export&amp;rbrack; Il canale normale viene sempre esportato come OpenGL
* &amp;lbrack;Iray&amp;rbrack; Nomi dei cursori mancanti per le impostazioni di Iray
* &amp;lbrack;Iray&amp;brack; Il rendering viene eseguito con una risoluzione errata su Retina/DPI alto
* &amp;lbrack;Iray&amp;rbrack; Arresto anomalo durante il ridimensionamento dell&#39;interfaccia in modalità Iray
* &amp;lbrack;Iray&amp;brack; rallentamento delle prestazioni quando il rendering viene eseguito a risoluzioni basse
* &amp;lbrack;Iray&amp;rbrack; Pausa non funziona (Iray continua a calcolare in background)
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

* &amp;lbrack;Iray&amp;rbrack; aggiorna il modello e lo shader di specifiche/lucidi per renderli compatibili con Iray
* &amp;lbrack;Esporta&amp;rbrack; Consente di esportare le schermate in ArtStation
* &amp;lbrack;Scripting&amp;rbrack; Supporto dell&#39;esecuzione dalla directory dei plug-in
* &amp;lbrack;Scripting&amp;rbrack; Consenti &quot;Salva con nome&quot;
* &amp;lbrack;UI&amp;rbrack; consente di fare doppio clic su un cursore per modificarne il valore
* Sposta il campione della Vela nel Substance share
* Nuovo progetto di esempio: Sphere Preview
* Avvisa gli utenti in caso di conflitto di estensione della shell

**Corretto:**

* Il programma di installazione sovrascrive l&#39;installazione di Substance Painter 1.x
* &amp;lbrack;UI&amp;rbrack; il layout dell&#39;elenco dei canali non funziona con i filtri
* &amp;lbrack;UI&amp;rbrack; i parametri di Shader non vengono visualizzati
* &amp;lbrack;UI&amp;rbrack; Il ridimensionamento della finestra del livello ritaglia in modo errato il contenuto
* &amp;lbrack;Strumento&amp;rbrack; Il canale Opacità non viene sempre utilizzato correttamente
* &amp;lbrack;Strumento&amp;rbrack; Sfumino/Clona /Clone non funziona con Simmetria
* &amp;lbrack;Strumento&amp;rbrack; L&#39;opacità dell&#39;anteprima del pennello non è corretta con alcuni canali
* &amp;lbrack;Iray&amp;rbrack; Arresto anomalo quando si utilizza Iray mentre non è ancora stato creato
* &amp;lbrack;Iray&amp;rbrack; Impossibile caricare i dati delle impostazioni di iray dal progetto
* &amp;lbrack;Iray&amp;rbrack; Iray non si occupa della modifica delle impostazioni dopo una pausa
* &amp;lbrack;Shelf&amp;rbrack; L&#39;importazione di un materiale sullo scaffale non funziona
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
* &amp;Sfumino;Strumento &amp;Sfumino; Nuovo strumento Sfumino per la fusione e la diffusione dei colori
* &amp;lbrack;Strumento&amp;rbrack; Nuovo strumento Clona /Clone per copiare parte della texture
* &amp;lbrack;Strumento&amp;rbrack; Consenti di selezionare i canali per lo strumento Sfumino, Clona /Clone e Gomma
* &amp;lbrack;Layer&amp;rbrack; Aggiungi nome Substance per nome effetto di riempimento
* &amp;blocco;Livello&amp;rbrack; Consenti di esportare la maschera negli Appunti
* &amp;lbrack;Viewport&amp;rbrack; Passa dalla modalità Prospettiva a quella ortografica e viceversa
* &amp;lbrack;Viewport&amp;rbrack; Consenti di controllare il campo di visualizzazione in modalità Prospettiva
* &amp;lbrack;Viewport&amp;rbrack; Consenti di impostare la Profondità della distanza del campo con CTRL+clic centrale
* &amp;lbrack;Viewport&amp;rbrack; Consente di trascinare e rilasciare le mappe dell&#39;ambiente nel vista 3D.
* &amp;lbrack;Viewport&amp;rbrack; feedback migliorato quando il motore esegue calcoli complessi
* &amp;lbrack;Esporta&amp;rbrack; Consenti di esportare i parametri di shader in un file json
* &amp;lbrack;UI&amp;rbrack; Aggiorna l&#39;interfaccia con nuove icone, colori e layout
* &amp;lbrack;UI&amp;rbrack; Aggiungi i nomi delle risorse ai mini scaffali
* &amp;lbrack;UI&amp;rbrack; comprimi &quot;mappatura canali&quot; per impostazione predefinita
* &amp;lbrack;Shader&amp;rbrack; Scegliere un colore personalizzato per i parametri della texture di shader
* &amp;blocco;Shelf&amp;rbrack; Chiedi dove importare i file quando trascini le risorse
* &amp;lbrack;Shelf&amp;rbrack; Nuova sfera di anteprima per Materiali avanzati e generatori
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi shader Specular
* &amp;blocca;Raccoglitore&amp;zione; nuove forme superficie rigida
* &amp;lbrack;Shelf&amp;rbrack; Nuovi Alpha, texture e forme
* &amp;lbrack;Shelf&amp;rbrack; Nuove texture incarnato
* &amp;lbrack;Shelf&amp;rbrack; nuovi materiali basati su scansione e materiali avanzati
* &amp;lbrack;Shelf&amp;rbrack; Nuovi materiali avanzati e supporto delle specifiche/lucidità dei vecchi
* &amp;lbrack;Shelf&amp;rbrack; Nuovi filtri Finitura per simulazione superficie metallica
* &amp;lbrack;Shelf&amp;rbrack; Nuovo potente generatore di maschere &quot;Editor maschera&quot;
* &amp;lbrack;Shelf&amp;rbrack; vecchi materiali rilavorati e puliti
* Nuovo progetto di esempio &quot;Vela&quot;

**Corretto:**

* &amp;lbrack;Settings&amp;rbrack; Rotazione e velocità di zoom della fotocamera sostituite dal progetto
* &amp;lbrack;Viewport&amp;rbrack; il problema di precisione nella texture normale predefinita genera riflessi errati
* &amp;lbrack;Viewport&amp;rbrack; Vignettatura attivata per impostazione predefinita
* &amp;lbrack;Viewport&amp;rbrack; Gli artefatti vengono visualizzati ai bordi della mappa dell&#39;ambiente (GPU Nvidia)
* &amp;lbrack;Viewport&amp;rbrack; La miniatura in modalità proiezione/stencil è molto lunga da caricare
* &amp;lbrack;Baker&amp;rbrack; Memorizza le texture eseguite i baking in un numero intero a 16 bit anziché a 32 bit
* &amp;lbrack;Layer&amp;brack; Le sostanze obsolete vengono visualizzate in modo errato nella pila
* Il colore e la profondità di bit predefiniti per alcuni canali non sono corretti (ad esempio: Specular, Lucentezza)
* È stato corretto il comportamento della gomma per disabilitare la fusione in modalità passthrough.

**Problemi noti:**

* Simmetria non funziona con lo strumento Sfumino e Clona /Clone
* Esportazione ArtStation mancante

## Versione 1

### 1.7.3

*(Rilasciato il 1° marzo 2016)*

**Aggiunto:**

* &amp;lbrack;Esporta&amp;rbrack; Aggiungi un&#39;opzione per disabilitare il riempimento
* &amp;lbrack;Shelf&amp;rbrack; supporta la gerarchia di scaffali secondari all&#39;interno di una cartella di scaffali

**Corretto:**

* Arresto anomalo di salvataggio su un file di sola lettura precedente
* Arresto anomalo all’apertura di un secondo progetto
* Arresto anomalo durante il caricamento di alcune miniature (scaffale, livelli o descrizioni comandi)
* La disattivazione di &quot;Mantieni posizioni dei tratti sulla trama&quot; non funziona
* &amp;lbrack;Export&amp;rbrack; L&#39;ingrandimento delle bitmap viene eseguito con il filtro più vicino
* &amp;lbrack;Shelf&amp;rbrack; L&#39;individuazione delle risorse è molto lenta
* &amp;lbrack;Shelf&amp;rbrack; I filtri Sfocatura non sono compatibili a 16 bit
* &amp;lbrack;Strumento&amp;rbrack; Simmetria non funziona se si carica un vecchio strumento predefinito
* La finestra di dialogo Colore per il canale Specular non esegue una conversione dello spazio colore

### 1.7.2

*(Rilasciato il 13 gennaio 2016)*

**Aggiunto:**

* &amp;lbrack;Livelli&amp;rbrack; Consenti di specificare la lavorazione predefinita per i livelli di riempimento

**Corretto:**

* &amp;lbrack;Esporta&amp;rbrack; l&#39;esportazione Sketchfab non funziona più
* &amp;lbrack;Livello&amp;rbrack; Il filtro bilineare viene applicato anche su Riempimento senza alcuna trasformazione
* &amp;lbrack;Tool&amp;rbrack; Scarse prestazioni con substance con input immagine in modalità proiezione
* &amp;lbrack;Strumento&amp;rbrack; selettore materiale interrotto

### 1.7.1

*(Rilasciato il 18 dicembre 2015)*

**Corretto:**

* Arresto anomalo quando si cambia set di texture
* Prestazioni rallentate durante la pittura

### 1.7.0

*(Rilasciato il 17 dicembre 2015)*

**Aggiunto:**

* &amp;lbrack;Performance&amp;brack; Calcola contemporaneamente il contenuto dei livelli e le relative miniature
* &amp;lbrack;Esporta&amp;rbrack; Salva il percorso di esportazione come relativo quando è accanto al progetto
* &amp;lbrack;Layers&amp;rbrack; Aggiunto nuovo metodo di fusione: subtract and add/sub
* &amp;lbrack;Layers&amp;rbrack; Nuovo filtro HQ bilineare per i livelli di riempimento
* &amp;lbrack;Shader&amp;rbrack; Impostare uno shader predefinito per la generazione delle miniature nelle preferenze.
* &amp;lbrack;Shader&amp;rbrack; Consenti di specificare uno shader per set di texture
* &amp;lbrack;Shader&amp;rbrack; Consenti di campionare texture dallo scaffale
* &amp;lbrack;Strumento&amp;rbrack; Nuovo comportamento del pennello &quot;a capo&quot; per la pittura
* &amp;lbrack;Strumento&amp;rbrack; Filtro e aliasing ridotti migliorati durante la pittura
* &amp;lbrack;Strumento&amp;rbrack; Qualità pittura dei sub-pixel migliorata
* &amp;lbrack;Strumento&amp;rbrack; è stata rimossa la visualizzazione &quot;base&quot; per le impostazioni del pennello e migliorata l’icona di apertura/chiusura del fotogramma
* &amp;lbrack;Menu&amp;rbrack; Aggiungere icone degli effetti nel menu di scelta rapida
* Creazione di modelli da progetti
* &amp;lbrack;Shelf&amp;rbrack; Nuovi modelli: PBR, Dota 2
* &amp;lbrack;Shelf&amp;rbrack; Nuovo predefinito di esportazione: Dota 2
* &amp;lbrack;Shelf&amp;rbrack; Nuovi shader: Dota 2, pittura per auto PBR, PBR Coated, Velluto PBR
* &amp;lbrack;Shelf&amp;rbrack; Nuovo materiale: ruggine e usura in acciaio, illuminazione stilizzata
* &amp;lbrack;Shelf&amp;rbrack; Nuovi filtri: Sfocatura direzionale, illuminazione stilizzata
* &amp;lbrack;Shelf&amp;rbrack; Nuovo pennello : predefinito morbido e predefinito rigido con un nuovo alfa per un migliore controllo della durezza
* &amp;lbrack;Shelf&amp;rbrack; Nuovi generatori: 3D Distanza e Luce
* &amp;lbrack;Shelf&amp;rbrack; pennelli aggiornati con proiezione a capo e culling sfondo (attivato per impostazione predefinita)
* &amp;lbrack;Shelf&amp;rbrack; disturbo bianco aggiornato con versione elaboratore pixel per un calcolo più veloce

**Corretto:**

* &amp;lbrack;Schermata di benvenuto&amp;rbrack; Tutorials collegamento invia a video precedenti
* &amp;lbrack;Channels&amp;rbrack; Dire &quot;no&quot; per riempire la creazione del livello con AO crea ancora il livello
* &amp;lbrack;Canali&amp;rbrack; I nomi dei canali UserX non si propagano nell&#39;interfaccia
* &amp;lbrack;Viewport&amp;rbrack; La voce Maschera è vuota nell&#39;elenco dei canali singoli
* &amp;lbrack;Condividi&amp;brack; L&#39;esportazione di un file alfa da condividere da SP crea un file .image illeggibile
* &amp;lbrack;License&amp;rbrack; Correggere l&#39;attivazione per i nomi utente con caratteri non ASCII
* &amp;lbrack;Shader&amp;rbrack; La finestra di dialogo dei parametri colore scompare quando si sceglie un colore
* &amp;lbrack;Shelf&amp;rbrack; Le miniature non vengono scaricate dalla memoria se non utilizzate
* &amp;lbrack;Shelf&amp;rbrack; filtro sfumatura fissa
* &amp;lbrack;Strumento&amp;rbrack; Simmetria non funziona con stencil/proiezione
* &amp;lbrack;Strumento&amp;rbrack; nome errato durante la creazione di un nuovo pennello predefinito
* L’impostazione Mantieni tratto rimane disattivata anche durante la reimportazione di una trama
* Reimpostazione del driver (TDR) quando si calcolano particelle di grandi dimensioni.

### 1.6.1

*(Rilasciato il 9 novembre 2015)*

**Corretto:**

* Arresto anomalo durante l’apertura di un progetto se Vista 2D è visibile
* Arresto anomalo durante la creazione di un nuovo predefinito di esportazione se lo scaffale corrente non esiste
* &amp;blocca;Strumento&amp;Segnale; l&#39;icona del selettore di materiale può rimanere visualizzata
* &amp;blocca;Strumento&amp;Segno di interruzione; Il selettore di materiale nasconde il cursore del mouse quando si disegna allo stesso tempo
* &amp;lbrack;Shelf&amp;rbrack; I metadati vengono scritti sul disco dopo ogni uscita

### 1.6.0

*(Rilasciato il 29 ottobre 2015)*

**Aggiunto:**

* Supporto ufficiale per Windows 10
* &amp;lbrack;Substance&amp;rbrack; comprime i gruppi di parametri Substance per impostazione predefinita
* &amp;lbrack;Substance&amp;rbrack; Aggiungi nuovo framework (Migliora le prestazioni degli Elaboratori pixel)
* &amp;lbrack;Viewport&amp;rbrack; Consente di disattivare la visualizzazione del piano della simmetria in modalità simmetria.
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; migliorare il rendering e le prestazioni delle ombre
* &amp;lbrack;Riquadro di visualizzazione&amp;rbrack; Sospende il calcolo dell&#39;ombreggiatura durante la pittura
* &amp;lbrack;Viewport&amp;rbrack; Migliora le prestazioni di rendering dei wireframi
* &amp;lbrack;Engine&amp;rbrack; Migliora la gestione della memoria Vram per ridurne l&#39;ingombro
* &amp;lbrack;Engine&amp;rbrack; Migliora l&#39;aggiornamento della texture sulle GPU AMD per prestazioni migliori
* &amp;lbrack;Engine&amp;rbrack; Disattiva l’impostazione di ottimizzazione concatenata sulle GPU NVIDIA per prestazioni migliori
* &amp;lbrack;Effect&amp;rbrack; Aggiungi un tag per richiedere l&#39;input dell&#39;immagine &quot;imbottita&quot;
* &amp;lbrack;Livello&amp;rbrack; Aumenta la precisione dell&#39;Offset UV/scala nel riempimento
* &amp;lbrack;Livello&amp;rbrack; Rende il cursore della scala esponenziale nel riempimento
* &amp;lbrack;Layer&amp;rbrack; Consente di trascinare i materiali direttamente nella Pila livelli.
* &amp;lbrack;Layer&amp;rbrack; Consenti di trascinare i filtri direttamente nella Pila livelli
* &amp;lbrack;Livello&amp;brack; regola il colore del pennello maschera con il colore maschera appena creato
* &amp;lbrack;Shader&amp;rbrack; Esposizione di più parole
* &amp;lbrack;Shader&amp;rbrack; Esposizione funzione gamma/tonemapping per consentire funzioni personalizzate
* &amp;lbrack;Baker&amp;rbrack; modifica le impostazioni predefinite del baker di posizioni per l&#39;utilizzo triplo
* &amp;lbrack;Tool&amp;rbrack; Rinomina &quot;Geometry Decal&quot; in &quot;Polygon Fill&quot;
* &amp;lbrack;Shelf&amp;rbrack; Aggiorna i generatori per supportare TriPlanar : MG Metal edge wear, MG Mask builder, MG Fibre Glass, MG Dirt
* &amp;lbrack;Shelf&amp;rbrack; aggiorna i materiali con le nuove impostazioni e i materiali inutilizzati rimossi
* &amp;lbrack;Shelf&amp;rbrack; 22 nuovi materiali avanzati (plastica, ferro, tessuto, acciaio e altro)
* &amp;lbrack;Shelf&amp;rbrack; Aggiorna i filtri Nitidezza, Sfocatura e Altera con input immagine imbottita per evitare giunture
* &amp;lbrack;Shelf&amp;rbrack; migliorare le impostazioni di alterazione per un utilizzo più semplice
* &amp;lbrack;Shelf&amp;rbrack; 2 Nuovi rumori procedurali: disturbo Perlin 3D e disturbo Worley 3D

**Corretto:**

* &amp;lbrack;Engine&amp;rbrack; Il rilevamento della quantità di Vram per la GPU dedicata non è corretto in Mac
* &amp;lbrack;Engine&amp;rbrack; Texture la versione più scura nella finestra della vista
* &amp;lbrack;Engine&amp;rbrack; Pessime prestazioni quando si disegna al di sotto di più livelli
* &amp;lbrack;Engine&amp;rbrack; I livelli calcolati all’apertura del progetto sono diversi dalla versione memorizzata nella cache
* &amp;lbrack;Substance&amp;rbrack; risultati errati in 4K su Mac
* &amp;lbrack;Substance&amp;rbrack; I parametri sono nell&#39;ordine errato
* &amp;lbrack;Shader&amp;rbrack; Gli shader Toon e Pixelated sono completamente neri
* &amp;lbrack;Shader&amp;rbrack; I parametri scompaiono dopo aver modificato env-map
* &amp;lbrack;Shelf&amp;rbrack; Arresto anomalo durante l&#39;inserimento di file png nella cartella generator
* &amp;lbrack;Shelf&amp;rbrack; Le miniature vengono generate con una bassa rugosità
* &amp;lbrack;Strumento&amp;rbrack; Arresto anomalo quando si utilizza una bitmap nel pennello alfa su windows
* &amp;lbrack;Esporta&amp;rbrack; Predefinito di esportazione mappa aggiuntivo ora esporta una mappa RGB per Posizione

### 1.5.7

*(Rilasciato il 24 settembre 2015)*

**Corretto:**

* Il report di Arresto anomalo non funziona più

### 1.5.6

*(Rilasciato il 21 settembre 2015)*

**Aggiunto:**

* &amp;lbrack;Shelf&amp;rbrack; Migliorare la qualità di rendering delle miniature (utilizzare texture da 1.000 rpm)

**Corretto:**

* &amp;lbrack;Condividi&amp;rbrack; impossibile firmare con un altro account
* &amp;lbrack;Shelf&amp;rbrack; le miniature sono troppo pesanti sul disco
* &amp;lbrack;Shelf&amp;rbrack; Il caricamento dei Materiali avanzati è molto lento
* &amp;lbrack;Windows&amp;rbrack; Correggi installazione servizio licenze
* &amp;lbrack;Channels&amp;rbrack; Trasmissivi map viene creata come G8 per impostazione predefinita

### 1.5.5

*(Rilasciato il 15 settembre 2015)*

**Aggiunto:**

* &amp;lbrack;Shelf&amp;rbrack; Esporta risorse in Substance share
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi nuova anteprima sfera per Materiali
* &amp;lbrack;Shelf&amp;rbrack; Utilizzare la mappa di invidiabilità &quot;Glazed patio&quot; per generare miniature
* &amp;lbrack;Shelf&amp;rbrack; Aumenta la risoluzione delle dimensioni della miniatura a 512x512 pixel
* &amp;lbrack;vista 3D&amp;rbrack; Esposizione del valore di rotazione dell&#39;ambiente
* &amp;lbrack;Windows&amp;rbrack; firma l&#39;applicazione

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack; risultati errati quando si eseguono i baking mappe contemporaneamente
* &amp;lbrack;vista 3D&amp;rbrack; La mappa env viene visualizzata quando nessun progetto è aperto
* &amp;lbrack;Livelli&amp;rbrack; i Generatori di maschere non funzionano sul contenuto del livello
* &amp;lbrack;Livelli&amp;rbrack; è possibile eseguire la pittura sui livelli nascosti
* &amp;lbrack;Shelf&amp;rbrack; Dirt_5 e Dirt_6 sono identici
* &amp;lbrack;Shelf&amp;rbrack; Alcuni generatori di maschere sono pixelati o di bassa qualità
* &amp;lbrack;Strumento&amp;rbrack; Rotazione gizmo errata su determinate angolazioni.
* &amp;lbrack;Strumento&amp;rbrack; troppi canali causano il ritaglio dei pulsanti dei canali
* &amp;lbrack;Strumento&amp;rbrack; Inverti scelta rapida da tastiera maschera per Maschera veloce non funziona
* &amp;lbrack;Export&amp;rbrack; Sketchfab: pulsante Annulla non considerato correttamente
* &amp;lbrack;License&amp;rbrack; Attivazione non riuscita quando non è possibile copiare la licenza
* Il limitatore di cadenza fotogrammi non funziona più nell&#39;interfaccia utente

### 1.5.0

*(Rilasciato il 20 agosto 2015)*

**Aggiunto:**

* &amp;lbrack;Shader&amp;rbrack; Aggiungi numero di riga nei messaggi di errore di compilazione di Shader
* &amp;lbrack;Shelf&amp;rbrack; Migliorare la qualità delle miniature di anteprima
* &amp;lbrack;Shelf&amp;rbrack; Generazione automatica delle miniature per i Materiali avanzati
* &amp;lbrack;Strumento&amp;rbrack; Scelta rapida da tastiera per controllare l&#39;impostazione della durezza nella sostanza
* &amp;lbrack;Strumento&amp;rbrack; Usa widget scala di grigi per decalcomanie geometriche quando si trova sopra una maschera
* &amp;lbrack;Strumento&amp;rbrack; Scelta rapida da tastiera per invertire il colore della pittura mentre si disegna su una mappa in scala di grigio
* &amp;lbrack;Viewport&amp;rbrack; Consenti di visualizzare il wireframe e modificarne il colore
* &amp;lbrack;Viewport&amp;rbrack; Sfoca lo sfondo dell&#39;ambiente
* &amp;blocca;Controlli&amp;rbrack; Aggiungi rotazione alle scelte rapide del mouse per i pennelli
* &amp;lbrack;Esporta&amp;rbrack; Esporta in Sketchfab
* &amp;lbrack;Esporta&amp;rbrack; Crea predefiniti di esportazione per i moduli di rendering
* &amp;lbrack;Export&amp;rbrack; Aggiungi riflessione mappa convertita, F0 e 1/IOR
* &amp;lbrack;UI&amp;rbrack; Aggiungi schermata introduttiva
* &amp;lbrack;UI&amp;rbrack; Aggiorna layout predefinito
* &amp;lbrack;UI&amp;rbrack; Aggiungi descrizioni comandi mancanti e rinomina una voce di menu
* &amp;lbrack;Layers&amp;rbrack; Esporta la maschera attualmente selezionata come bitmap
* &amp;lbrack;Layers&amp;rbrack; Aggiungi azione &quot;inverti maschera&quot; nel menu di scelta rapida

**Corretto:**

* &amp;lbrack;Project&amp;rbrack; Se le trame pivot sono diverse nell&#39;FBX, le trame vengono esplose durante l&#39;importazione
* &amp;lbrack;Substance&amp;rbrack; le Substance utilizzate negli strumenti di proiezione sono bloccate in 256\*256
* &amp;lbrack;Layers&amp;rbrack; Arresto anomalo quando si utilizza Cancella maschera
* &amp;lbrack;Esporta&amp;rbrack; Conversione gamma non corretta su texture molto scure
* &amp;lbrack;Export&amp;rbrack; La mappa di posizione può essere utilizzata solo nei predefiniti di esportazione come mappa in scala di grigio
* &amp;lbrack;Strumento&amp;rbrack; il colore iniziale della decalcomania Geometria è nero se utilizzato su una maschera
* &amp;lbrack;Strumento&amp;rbrack; La scelta rapida da tastiera Rotazione non funziona se non è presente durezza nell&#39;alfa

### 1.4.2

*(Rilasciato il 15 luglio 2015)*

**Corretto:**

* &amp;lbrack;Strumento&amp;rbrack; Arresto anomalo quando si utilizza la decalcomania geometrica con maschera veloce
* L’aggiornamento del progetto da 1.4.0 a 1.4.1 utilizza tutta la memoria del computer
* Importazione del vecchio formato di progetto non corretta
* Gli scaffali personalizzati analizzano l&#39;intera gerarchia e duplicano le risorse ovunque

### 1.4.1

*(Rilasciato il 23 giugno 2015)*

**Aggiunto:**

* &amp;blocca;Riquadro di visualizzazione&amp;rbrack; consente di ancorare i pannelli uno accanto all&#39;altro
* &amp;blocco;Effetto&amp;rbrack; Aggiungi uno sfondo e un righello per l&#39;effetto livello
* &amp;lbrack;Effetto&amp;rbrack; Aggiungi un effetto Pittura che consenta di lavorare su altri effetti

**Corretto:**

* &amp;lbrack;Shelf&amp;rbrack; La generazione delle miniature non funziona se non è aperto alcun progetto
* &amp;lbrack;Shelf&amp;rbrack; impossibile generare l&#39;anteprima del predefinito del materiale
* &amp;lbrack;Shelf&amp;rbrack; Le anteprime dei materiali vengono generate su una trama con normali invertite
* &amp;lbrack;Shelf&amp;rbrack; Le miniature vengono sempre ricalcolate a causa di una funzione hash errata
* &amp;blocca;Raccoglitore&amp;zione; Se si fa clic su un materiale Substance, non vengono collegate ulteriori mappe
* &amp;lbrack;Strumento&amp;rbrack; valore non corretto campionato con il selettore materiale
* &amp;lbrack;Strumento&amp;rbrack; Selettore colore seleziona il colore del cursore della finestra della vista
* &amp;lbrack;vista 2D&amp;rbrack; Velocità fotogrammi/prestazioni molto basse
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo quando si apre la finestra di esportazione con predefiniti di esportazione troppo recenti.
* &amp;lbrack;Export&amp;rbrack; il canale Height su Mappa normale viene convertito nello spazio errato
* &amp;lbrack;Mac&amp;rbrack; BaseColor dagli effetti substance viene visualizzato come lineare
* &amp;lbrack;Mac&amp;rbrack; Il widget Linee rette viene disegnato in modo errato su Retina
* Le linee rette possono rimanere attivate anche con le scelte rapide da tastiera rilasciate.
* Le linee rette del guizmo scompaiono dopo aver ruotato la mappa dell&#39;ambiente
* Gli output di Occlusione ambientale da sostanze non vengono collegati automaticamente al canale AO
* Risolvere il problema di copia della licenza su Windows con carattere speciale nel nome utente

### 1.4.0

*(Rilasciato il 10 giugno 2015)*

**Aggiunto:**

* &amp;lbrack;Export&amp;rbrack; Aggiungi altre mappe nell&#39;elenco delle mappe di input disponibili
* &amp;lbrack;Shelf&amp;rbrack; Utilizza i materiali sbsar come predefiniti di materiale
* &amp;lbrack;Shelf&amp;rbrack; Consenti l&#39;utilizzo di percorsi libreria personalizzati
* &amp;lbrack;Shelf&amp;rbrack; Modificare le dimensioni minime
* &amp;lbrack;Shelf&amp;rbrack; Nuovo contenuto: 20 nuovi materiali avanzati
* &amp;lbrack;Shelf&amp;rbrack; Nuovo contenuto: nuova sostanza procedurale (trama, trama)
* &amp;lbrack;Shelf&amp;rbrack; Filtro Sfocatura aggiornato
* Disegnare linee rette utilizzando un tasto modificatore
* Aggiungere il canale di Occlusione ambientale e rielaborare il comportamento AO/Normale in Pila livelli
* Lettura del colore predefinito da Input immagine definito in Substance dati utente
* Consente di esportare il registro dal menu Aiuto

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;Mac&amp;rbrack; Arresto anomalo con baker normale da trama
* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo se nel file della gabbia non sono presenti UV
* &amp;lbrack;Baker&amp;rbrack; La corrispondenza per nomi non funziona con l&#39;OBJ esportato da zBrush
* &amp;lbrack;Baker&amp;rbrack; Esegue i baking con una gabbia sovrascrive il eseguo i baking se si utilizzano più set di texture e UV sovrapposti
* &amp;lbrack;Baker&amp;rbrack; file OBJ specifici generano texture nere
* &amp;lbrack;Shelf&amp;rbrack; Impossibile leggere le risorse se impostato su sola lettura
* &amp;lbrack;Shelf&amp;rbrack; I file delle risorse vengono scritti in Painter se sono stati utilizzati nel progetto.
* &amp;lbrack;Shelf&amp;rbrack; Il ricaricamento delle sostanze aggiorna anche il livello
* &amp;lbrack;Export&amp;rbrack; Tiff esporta immagini a 32 bit che non possono essere lette correttamente da Photoshop o motori grafici
* &amp;lbrack;Esporta&amp;rbrack; i canali predefiniti preimpostati esportano sempre come RGB
* &amp;lbrack;Material&amp;rbrack; il canale della Diffusa sovrascrive il mapping BaseColor con le sostanze
* &amp;lbrack;vista 3D&amp;rbrack; illuminazione Diffusa errata con mappe di ambiente specifiche
* &amp;lbrack;Strumento&amp;rbrack; impossibile ruotare un pennello in un angolo specifico
* Il riquadro di visualizzazione diventa attivo quando si passa il cursore del mouse mentre si digita in un campo di testo
* Arresto anomalo con predefiniti troppo recenti per la versione corrente dello scaffale
* Arresto anomalo dopo la sostituzione della trama
* Arresto anomalo quando si ricarica una sostanza con un diverso numero di input
* Trame FBX da Cinema4D importate con nomi di materiale errati

### 1.3.5

*(Rilasciato il 29 maggio 2015)*

**Aggiunto:**

* &amp;lbrack;License&amp;rbrack; Problema di attivazione quando è presente un file di licenza esistente
* &amp;lbrack;Mac&amp;rbrack; Arresto anomalo durante il caricamento di file FBX specifici
* &amp;lbrack;Mac&amp;rbrack;&amp;lbrack;vista 3D&amp;rbrack; Riflesso errato per la GPU integrata
* &amp;lbrack;vista 3D&amp;rbrack; font di Maschera veloce interrotto
* &amp;lbrack;vista 3D&amp;rbrack; Il selettore materiale rende la finestra della vista completamente nera
* Arresto anomalo dopo l’apertura dei progetti creati nella versione 1.3.3
* L&#39;anteprima del materiale è vuota quando si utilizzano ombreggiature con canale alfa
* Il disegno smette di funzionare su trame specifiche
* Le prestazioni diminuiscono notevolmente con le maglie specifiche dell&#39;OBJ
* I canali utente non sono mappati quando si utilizzano gli effetti
* Le cartelle temporanee non vengono pulite all&#39;avvio

**Corretto:**

* Miglioramenti dei tempi di calcolo nel progetto estremamente lungo da caricare
* Modificare la finestra &quot;Risoluzione dei problemi GPU&quot; per renderla più comprensibile
* &amp;lbrack;Layers&amp;rbrack; Salva lo stato del blocco delle proporzioni per i livelli di riempimento e attivalo per impostazione predefinita
* &amp;lbrack;Baker&amp;rbrack; La corrispondenza per nome ora utilizza il suffisso come separatore

### 1.3.4

*(Rilasciato il 27 aprile 2015)*

**Aggiunto:**

* &amp;lbrack;Mac&amp;rbrack; Arresto anomalo con Mac OS X Yosemite (10.10)
* &amp;lbrack;Mac&amp;rbrack; impossibile uscire dalla modalità a schermo intero
* &amp;lbrack;Baker&amp;rbrack; l&#39;opzione Esegue i baking corrispondenza per nome non funziona
* &amp;lbrack;Baker&amp;rbrack; Lo spazio tangente Mikk utilizzato in SP non funziona con UE4
* &amp;lbrack;Baker&amp;rbrack; Il baker di ID non può eseguire i baking colori ID materiale
* &amp;lbrack;vista 2D&amp;rbrack; Il Wireframe non viene visualizzato quando si utilizza lo strumento decalcomania Geometria
* &amp;lbrack;Strumento&amp;rbrack; Il canale alfa di pennelli viene visualizzato come controllo anziché come trasparenza con i materiali
* &amp;lbrack;Strumento&amp;rbrack; Arresto anomalo con decalcomania geometria
* &amp;lbrack;Layers&amp;rbrack; Lo slot dei materiali è compresso per impostazione predefinita sul livello Riempimento
* &amp;lbrack;Export&amp;rbrack; Arresto anomalo quando si esportano con dimensioni superiori alla risoluzione impostata per le texture
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
* &amp;lbrack;Shelf&amp;rbrack; Aggiungi nuove mappe ambiente: Corsica beach, studio 05, studio Tornoco e altro
* &amp;lbrack;Shelf&amp;rbrack; Aggiorna MG Mask Builder con i nuovi parametri
* &amp;lbrack;Shelf&amp;rbrack; aggiornare e calibrare le mappe vecchio ambiente

**Corretto:**

* Arresto anomalo all’apertura della finestra di esportazione
* Impossibile trascinare il widget dell&#39;interfaccia utente quando non è ancorato
* &quot;Ricerca aggiornamenti&quot; non funziona
* &amp;blocca;Livelli&amp;rbrack; non selezionare la maschera quando si fa clic su di essa tenendo premuto ALT
* &amp;lbrack;Strumento&amp;rbrack; Tri-planari non funziona con il canale Normale
* &amp;lbrack;vista 3D&amp;rbrack; l&#39;illuminazione della Diffusa dalla mappa env non è corretta
* &amp;lbrack;vista 3D&amp;rbrack; Il calcolo dell&#39;esposizione è diverso da Designer
* &amp;lbrack;vista 3D&amp;rbrack; Le ombre non devono essere visibili su una superficie metallica al 100%
* &amp;lbrack;vista 3D&amp;rbrack; La trama con UV specchiati ha capovolto tangente/binomio
* &amp;lbrack;vista 3D&amp;rbrack; Le ombre producono risultati errati su determinate trame
* &amp;lbrack;Baker&amp;rbrack; Rimuovi la cartella &quot;.alg_meta&quot; creata dai file assbin
* &amp;lbrack;Baker&amp;rbrack; Arresto anomalo quando si esegue i baking se Painter ricalcola contemporaneamente un TextureSet
* &amp;lbrack;Mac&amp;rbrack; errore interfaccia utente del riquadro bianco all&#39;avvio dell&#39;applicazione

### 1.3.2

*(Rilasciato il 6 marzo 2015)*

**Corretto:**

* &amp;lbrack;vista 3D&amp;rbrack; impossibile ricaricare una mappa env salvata con il progetto

### 1.3.1

*(Rilasciato il 5 marzo 2015)*

**Aggiunto:**

* &amp;lbrack;Baker&amp;rbrack; Aggiungi una versione memorizzata nella cache delle trame High-Poly per accelerare il calcolo
* &amp;lbrack;Baker&amp;rbrack; Aggiungi un&#39;icona di avviso se non viene caricata alcuna trama High-Poly
* &amp;lbrack;Baker&amp;rbrack; Se non viene caricata alcuna trama High-Poly, utilizza invece la trama del progetto

**Corretto:**

* &amp;lbrack;Baker&amp;rbrack; premere &quot;invio&quot; quando si modifica il valore di un cursore per chiudere la finestra
* &amp;lbrack;Baker&amp;rbrack; Anche l&#39;attivazione/disattivazione di un baker attiverà il pulsante
* &amp;lbrack;Baker&amp;rbrack; impossibile da eseguire i baking se si utilizza il pulsante &quot;all/none&quot;
* &amp;lbrack;Baker&amp;rbrack; L&#39;ordinamento dei pulsanti di baker non è corretto
* &amp;lbrack;Baker&amp;rbrack; La casella di controllo viene ignorata e tutti i baker vengono sempre elaborati
* &amp;lbrack;Baker&amp;rbrack; stato barra di avanzamento corretto

### 1.3.0

*(Rilasciato il 4 marzo 2015)*

**Aggiunto:**

* &amp;lbrack;Baker&amp;rbrack;&amp;lbrack;vista 3D&amp;rbrack; Usa calcolo spazio tangente Mikkt se non vengono trovate tangenti/binormali
* &amp;lbrack;Baker&amp;rbrack; Aggiunti nuovi baker: Normale, ID, Occlusione, Curvatura, Thickness, Posizione
* &amp;lbrack;Effetti&amp;rbrack; La pila di effetti è ora invertita e visualizzata dall’alto verso il basso (come i livelli)
* &amp;blocco;Effetti&amp;rbrack; Aggiungi nuove icone alla pila di effetti
* &amp;lbrack;Effetti&amp;rbrack; Aggiungi metodo di fusione tra le azioni di riempimento nella pila effetti
* &amp;lbrack;Effetti&amp;rbrack; Rinomina effetti (effetto sostanza = filtro, ecc.)
* Aggiungere un file &quot;lock&quot; durante il processo di salvataggio
* &amp;blocco;Effetti&amp;rbrack; Aggiungi azione Riempimento nella pila effetti
* Aggiunta nuova risorsa: Materiali avanzati
* &amp;blocca;Livelli&amp;rbrack; Consenti di riordinare gli effetti di livello
* &amp;lbrack;Strumento&amp;rbrack; Aggiungi proiezione tripla Planari
* &amp;lbrack;vista 3D&amp;rbrack; Aggiungi supporto per ombre
* &amp;lbrack;vista 3D&amp;rbrack; possibilità di impostare gli stati OpenGL richiesti in shader personalizzati
* &amp;lbrack;vista 3D&amp;rbrack; supporto per alfa tramite nuovi shader
* &amp;lbrack;vista 3D&amp;rbrack; Gli ombreggiatori sono ora provvisti di versione e completamente salvati in un progetto
* &amp;lbrack;vista 3D&amp;rbrack; Avvisa l&#39;utente se lo shader non viene più compilato

**Corretto:**

* &amp;lbrack;Layers&amp;rbrack; correggere l&#39;eliminazione in una cartella compressa
* &amp;lbrack;Shelf&amp;rbrack; Correggere il filtro contenuto nei mini-scaffali
* &amp;lbrack;Shelf&amp;rbrack; Rinominare le categorie e riorganizzare le schede

### 1.2.1

*(Rilasciato il 12 febbraio 2015)*

**Aggiunto:**

* I file \*.spp possono ora essere aperti con un doppio clic in Esplora risorse
* &amp;lbrack;Export&amp;rbrack; Nuovo tag &quot;$project&quot; per i predefiniti di esportazione
* &amp;lbrack;Esporta&amp;rbrack; Aggiungi elenco mappe (con nomenclatura) sotto ogni set di texture
* &amp;blocca;Esporta&amp;blocca; Aggiungi un pulsante Tutto/Nessuno per selezionare i set di texture
* &amp;lbrack;Esporta&amp;rbrack; le mappe vuote vengono eliminate durante l&#39;esportazione

**Corretto:**

* &amp;lbrack;Export&amp;rbrack; i predefiniti Unity5 hanno mappe invertite
* &amp;lbrack;Esporta&amp;rbrack; L&#39;aggiunta di una barra in avanti nel nome del predefinito crea una cartella danneggiata
* &amp;lbrack;Export&amp;rbrack; il canale di Height esportato in formati a 32 bit è bloccato in modo errato
* &amp;lbrack;Export&amp;rbrack; L&#39;elenco dei set di texture non è ordinato come nel progetto
* &amp;lbrack;Tool&amp;rbrack; Il taglio del backface non funziona più
* Il comando Salva non funziona con i caratteri speciali nel tracciato

### 1.2.0

*(Rilasciato il 28 gennaio 2015)*

**Aggiunto:**

* Nuovo canale Normale per la pittura dei dati della mappa normale e la combinazione dei risultati
* &amp;lbrack;Export&amp;rbrack; Nuova finestra di esportazione con la possibilità di creare impacchettamenti personalizzati e impostare nomi personalizzati
* Il formato del file di progetto ora è un singolo file anziché delle cartelle
* &amp;lbrack;Esporta&amp;rbrack; supporta diversi formati normali (DirectX, OpenGL)
* &amp;lbrack;Export&amp;rbrack; Crea un file &quot;lock&quot; temporaneo durante l&#39;esportazione
* &amp;lbrack;Layers&amp;rbrack; Maiusc+LeftPer attivare/disattivare una maschera è possibile fare clic con il pulsante sinistro del mouse
* &amp;lbrack;Parametri&amp;rbrack; Esposizione dello spazio colore nella parte inferiore dell&#39;input di un&#39;immagine
* &amp;lbrack;Shelf&amp;rbrack; Effetto &quot;MG Mask Builder&quot; ha ora nuove impostazioni
* &amp;lbrack;vista 3D&amp;rbrack; la mappa di Occlusione ambientale ora occlude il contributo alla diffusione, non lo specular

**Corretto:**

* L&#39;anteprima del materiale di proiezione/stencil non viene visualizzata correttamente nella finestra della vista
* &amp;lbrack;vista 3D&amp;rbrack; descrizione comando Scelta rapida da tastiera non visualizzata quando si utilizza la scelta rapida da tastiera &quot;S&quot; (stencil)
* &amp;lbrack;Shelf&amp;rbrack; Effetto &quot;MatFx Skin Scale&quot; offre ora prestazioni migliori a bassa risoluzione
* &amp;lbrack;Export&amp;rbrack; Le Texture esportate vengono solo ingrandite quando si specifica un documento di dimensioni maggiori

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

* &amp;blocca;Livello&amp;traccia; seleziona il livello sopra all’apertura di un set di texture di progetto/cambio
* Velocità di salvataggio e salvataggio con nome migliorate con il nuovo algoritmo di compressione
* Visualizzare un errore en durante l’apertura di un progetto troppo recente per Painter

**Corretto:**

* &amp;lbrack;Strumento&amp;rbrack; La decalcomania della geometria genera danni alla memoria
* &amp;lbrack;Brush&amp;rbrack; impossibile immettere manualmente valori mobili inferiori a 1 per la dimensione del pennello
* &amp;lbrack;Livello&amp;rbrack; la creazione di un effetto di selezione colore non lo aggiunge nella Pila livelli
* &amp;blocco;Livello&amp;rbrack; se si sposta il mouse sui livelli, Painter sfarfalla nella barra delle applicazioni
* &amp;lbrack;Layer&amp;rbrack; L&#39;aggiunta di una bitmap come maschera può provocare un arresto anomalo
* La GUI per la modalità Solo con il canale del Height non è corretta
* &quot;Salva progetto&quot; può non riuscire e danneggiare un progetto
* Arresto anomalo quando si apre un progetto dopo averne caricato un altro con uno shader obsoleto

### 1.1.0

*(Rilasciato il 16 dicembre 2014)*

**Aggiunto:**

* &amp;blocco;Effetto&amp;rbrack; nuovo creatore maschera ID materiale
* Nuova linea bianca/nera punteggiata per il gizmo del pennello
* Nuovo parametro segui angolo
* Nuovo parametro di taglio backface
* Nuovo parametro Mouse lento
* &amp;lbrack;Livelli&amp;rbrack; supporto per più selezioni e gestione
* &amp;blocca;Livelli&amp;rbrack; Copia e incolla da un set di texture all&#39;altro
* &amp;lbrack;Export&amp;rbrack; formato PSD di Adobe Photoshop
* &amp;lbrack;Shelf&amp;rbrack; Nuovo strumento: pelliccia, punti metallici e cerniera
* &amp;lbrack;Shelf&amp;rbrack; Nuovo pennello: stampo, matita, linea affilata e punto
* &amp;lbrack;Shelf&amp;rbrack; New alpha : Disturbo gaussiano, linea nitida, stampo, penna, schizzo, punto, cerniera
* Le prestazioni di pittura sono migliorate aggiornando solo le parti delle texture necessarie

**Corretto:**

* &amp;lbrack;Shelf&amp;rbrack; impossibile caricare una sostanza con un grafico con etichette identiche
* &amp;lbrack;Livelli&amp;rbrack; Il metodo di fusione Attraversa non funziona con le maschere
* &amp;lbrack;Stencil&amp;rbrack; Scala interrotta nel Vista 2D
* Problemi e arresto anomalo su Mac OS Yosemite

### 1.0.2

*(Rilasciato il 9 novembre 2014)*

**Aggiunto:**

* Prestazioni migliorate nell’anteprima del materiale con le sostanze
* Prestazioni migliorate con l’anteprima del tratto pennello durante l’aggiornamento del documento
* Prestazioni migliorate nella finestra della vista con una frequenza di aggiornamento inferiore per l’area non di lavoro
* &amp;lbrack;Effetti post&amp;rbrack; interfaccia utente migliorata per la gestione delle impostazioni
* &amp;lbrack;Effetti post&amp;rbrack; ripristina i valori predefiniti
* Substance effetti e operazioni sui livelli nel menu di scelta rapida
* Supporto per input/output premoltiplicato nelle sostanze

**Corretto:**

* &amp;lbrack;vista 3D&amp;rbrack; I parametri di shader personalizzati sono separati da uno spazio grande
* &amp;lbrack;Export&amp;rbrack; Conversione sRGB mancante per il predefinito Unity4
* Possibile Arresto anomalo durante il caricamento delle maglie fbx
* Arresto anomalo a volte durante il caricamento di semplici trame obj
* La barra di elaborazione rimane bloccata al 100% durante il caricamento
* Quando si ricarica una sostanza, la si inserisce in ogni categoria
* Switch DirectX/OpenGL interrotto

### 1.0.1

*(Rilasciato il 27 ottobre 2014)*

**Aggiunto:**

* &amp;lbrack;Tool&amp;rbrack; utilizzo dei parametri dei materiali migliorato
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
* &amp;lbrack;Export&amp;rbrack; Aggiungi una passata di dilatazione prima del postprocesso di diffusione
* Argomenti della riga di comando in SP per operazioni semplici
* Nuovi materiali ed effetti
* Anteprima strumento (anteprima del materiale in tempo reale separata e area di prova del tratto)
* Non creare un documento predefinito all&#39;avvio di Painter
* &amp;lbrack;Tool&amp;rbrack; Aggiungi la possibilità di modificare manualmente un valore in scala di grigio
* Vari miglioramenti per gli stencil (Aggancia, Reimposta)
* Le particelle sono ora dei sottostrumenti degli strumenti Pennello artistico, Gomma e Proiezione
* &amp;lbrack;vista 3D&amp;rbrack; Usa AO eseguito i baking nel rendering della finestra della vista
* Dividere i controlli degli stencil tra la vista 2D e 3D
* Modifiche di piccole dimensioni del pollice nella libreria
* I campi di ricerca sono specifici di ogni finestra
* Interfaccia utente modificata

**Corretto:**

* &amp;lbrack;Substance&amp;brack; Switch non funziona
* &amp;lbrack;Finestra di dialogo Colore&amp;rbrack; sfumatura tonalità non aggiornata
* Impossibile aggiornare una trama se il nome del file è identico
* Lo strumento non è visibile nelle visualizzazioni quando è troppo piccolo
* Lo strumento decalcomania sullo schermo Retina non funziona correttamente
* &amp;lbrack;Substance&amp;rbrack; Int1 viene visualizzato come float1
* &amp;lbrack;Substance&amp;rbrack; input/output basecolor non riconosciuti
* &amp;lbrack;Substance&amp;rbrack; filtri non possono essere ricaricati
* &amp;lbrack;Strumento&amp;rbrack; il widget scala di grigi è sempre compresso

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
* Scelte rapide di &amp;lbrack; e &amp;rbrack; per Dimensione pennello
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
