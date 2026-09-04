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
source-git-commit: fc154cd38e23b0e598c15bfbfee8a263d5770592
workflow-type: tm+mt
source-wordcount: '34015'
ht-degree: 0%

---


# Tutte le modifiche

Questa pagina contiene le note sulla versione per tutte le versioni precedenti di Substance 3D Painter, ordinate dalla più recente alla meno recente.

>[!NOTE]
>
> Per visualizzare i problemi noti che possono influire su Painter, consulta la [pagina dedicata alla documentazione](known-issues.md).

## Versione 12

### 12.1.4

Data di pubblicazione: **2026/09/04**

Riepilogo: **Versione secondaria**

**Corretto:**

- \[Arresto anomalo\] Arresto anomalo durante l&#39;importazione o l&#39;esportazione di file i cui nomi contengono caratteri non ASCII

### 12.1.3

Data di pubblicazione: **2026/08/26**

Riepilogo: **Versione secondaria**

**Aggiunto:**

&#x200B;* Aggiornamento del motore di Substance alla versione 9.4.6

**Corretto:**

&#x200B;* [Il selettore scala di grigi] rimane aperto dopo aver modificato lo strumento
&#x200B;* [Inclina Eseguita i baking] La correzione dell’inclinazione si interrompe quando si disegna e si annulla
&#x200B;* [L&#39;interazione dello strumento di proiezione] nella finestra della vista è bloccata dallo strumento di proiezione
&#x200B;* [Traccia dinamica] Parametri di traccia dinamica mancanti nelle proprietà del pennello
&#x200B;* L’esportazione in rete non funziona più

### 12.1.2

Data di pubblicazione: **2026/08/03**

Riepilogo: **Versione secondaria**

**Corretto:**

&#x200B;* \[Arresto anomalo\] Alcune Substance possono generare un arresto anomalo durante il rendering
&#x200B;* \[Arresto anomalo\] Reimporta trama in modalità di esegue i baking
&#x200B;* \[Arresto anomalo\] Un errore di inizializzazione della visualizzazione della grafica può causare un arresto anomalo
&#x200B;* \[Arresto anomalo\] Durante l’aggiornamento del registro, in alcuni casi l’esportazione delle texture può bloccarsi
&#x200B;* \[Arresto anomalo\] Arresto anomalo in modalità cottura in alcuni casi durante il caricamento/aggiornamento della mappa dell&#39;ambiente
&#x200B;* \[Baking\] Il riavvio di bake dopo la modifica del file di poly elevato può provocare un blocco
&#x200B;* \[Invia a Photoshop\] Non riesce a esportare la maschera di livello
&#x200B;* Il risultato del punto di ancoraggio \[Motore\] non viene visualizzato tra una maschera e un canale di colore

### 12.1.1

Data di pubblicazione: <b>2026/07/09</b>

Riepilogo: versione secondaria

Aggiunto:

&#x200B;* [Inclina al forno] Modo normale base di inclinazione esposta: mesh o per triangle
&#x200B;* [Proprietà] Rendi i colori uniformi sempre ripristinati al valore predefinito del canale
&#x200B;* [OpenPBR] Raggruppare i canali per categorie nella finestra Esporta texture per la creazione di modelli di output
&#x200B;* Aggiornamento del motore di Substance alla versione 9.4.5

Fisso:

&#x200B;* [Il progetto] L&#39;apertura e il salvataggio di alcuni progetti può richiedere più tempo del solito
&#x200B;* [Arresto anomalo] Il ricaricamento di più trame può causare un arresto anomalo
&#x200B;* [Arresto anomalo] L’eliminazione di un canale in modalità di visualizzazione maschera causa un arresto anomalo
&#x200B;* [Arresto anomalo] Alcune Substance possono causare un arresto anomalo durante il rendering
&#x200B;* [Inclina inclinazione] lo strumento selezionato in inclina rimane selezionato dopo il passaggio alla modalità di disegno
&#x200B;* [Impostazioni comuni di cottura] Le impostazioni della distanza di gabbia non aggiornano la visualizzazione di cage wireframe e shader
&#x200B;* La modalità &quot;Vicina spazio 3D&quot; del riempimento UV del [Motore] non funziona correttamente su triangoli sottili
&#x200B;* Il risultato del punto di ancoraggio [del motore] non viene visualizzato tra una maschera e un canale di colore

### 12.1.0

Data di pubblicazione: <b>2026/06/23</b>

Riepilogo: <b>Questo aggiornamento è una versione principale e contiene miglioramenti dei forni con il nuovo stato dell&#39;interfaccia utente predefinito di cottura al forno, la mappa di inclinazione del disegno, il rebake automatico, la nuova opzione per lo srotolamento UV automatico per trame e OpenPBR su superfici dure. Per ulteriori dettagli, vedere le note sulla versione complete.</b>

<b>Aggiunto</b>:

&#x200B;* [Inclina eseguendo i baking] Inclina strumenti di pittura
&#x200B;* [Inclina in Eseguita i baking] Aggiungete immagini vettoriali di shader e direzione di inclinazione dell&#39;anteprima dell&#39;inclinazione quando disegnate la mappa di inclinazione
&#x200B;* [Inclina in Eseguita i baking] Opzione Aggiungi protezione bordi
&#x200B;* [Inclina in eseguita i baking] Ripetizione automatica
&#x200B;* [Inclina in Eseguita i baking] Rielaborare l&#39;interfaccia utente dell&#39;elenco delle mappe della trama
&#x200B;* [Inclina in Eseguita i baking] Dividi mappa trama / Impostazioni comuni di Esegue i baking + Sposta impostazioni comuni fuori dall&#39;elenco mappa trama solo colore di base o maschera
&#x200B;* [Inclina Eseguo i baking] Cambiare i pulsanti della barra degli strumenti della finestra della vista
&#x200B;* [Inclina in Eseguita i baking] Mostra/Nascondi Simmetria per il pennello nella barra degli strumenti superiore
&#x200B;* [Inclina in Eseguita i baking] Opzioni di ridenominazione nel menu Sincronizzazione mappa trama
&#x200B;* [Inclina in Eseguita i baking] Finestre di dialogo Aggiorna stato sincronizzato e controllato
&#x200B;* [Inclina in Eseguita i baking] Variante del selettore colore Crea scala di grigi
&#x200B;* [Inclina in Eseguita i baking] Aggiorna l’icona della modalità di esegue i baking
&#x200B;* [Auto Unwrap] Opzione Integra superficie dura (Integrate Hard Surface)
&#x200B;* [OpenPBR] Aggiungi il supporto per l’OpenPBR 1.1
&#x200B;* [OpenPBR] Imposta OpenPBR come flusso di lavoro e shader predefiniti
&#x200B;* [OpenPBR] Importare materiali e texture OpenPBR tramite USD
&#x200B;* [OpenPBR] Esportazione di materiali e texture OpenPBR tramite USD
&#x200B;* [OpenPBR] Aggiorna la finestra Esporta Texture per mostrare la convenzione di denominazione delle OpenPBR
&#x200B;* [OpenPBR] Aggiungi documentazione sulle modifiche all’OpenPBR di supporto
&#x200B;* [OpenPBR]&#x200B;[Iray] Aggiungi un nuovo MDL per supportare l&#39;OpenPBR 1.1 in Iray
&#x200B;* Diversi miglioramenti minori nelle esportazioni USD
&#x200B;* [UI] Aggiungete un avviso nella finestra della vista quando tentate di eseguire la pittura su un altro set di texture
&#x200B;* [Appiattisci] Consenti di appiattire tutti i livelli istanziati tra set di texture
&#x200B;* [Impostazioni set texture] Consente di selezionare più canali contemporaneamente tramite una nuova finestra
&#x200B;* [History] Aggiornare il &quot;valore&quot; della voce Annulla per riflettere il nome del parametro
&#x200B;* [Pila livelli] Rendi gli effetti di riempimento nelle maschere predefiniti sul bianco (1,0)
&#x200B;* [Substance] Aggiungi nuovo input mappa motore &quot;mesh_hard_edges_triangle&quot;
&#x200B;* [Substance] Aggiungi nuovo input mappa motore &quot;mesh_hard_edges&quot;
&#x200B;* [Shader] Impedisci la condivisione degli stessi nomi da parte delle istanze shader
&#x200B;* [Shader] Utilizza lo shader del modello di progetto durante l&#39;importazione di un file USD o GLTF
&#x200B;* Aggiornamento dell&#39;Adobe Color Engine alla versione 7.0
&#x200B;* Aggiornamento della versione minima MacOSX alla versione 13.0 (Ventura)
&#x200B;* [Content] Nuovi modelli di progetto per l&#39;OpenPBR
&#x200B;* [Content] Aggiorna i progetti di esempio per utilizzare il nuovo shader di OpenPBR
&#x200B;* [Python] Espandi l’API maschera geometria per consentire le modalità di inclusione ed esclusione, come nell’interfaccia utente

<b>Risolto</b>:

&#x200B;* [Arresto anomalo]&#x200B;[Impostazioni mappe trama] Applica le impostazioni ad altri set di texture
&#x200B;* [Arresto anomalo] Quando si esegue i baking la curvatura da una mappa senza spazio mondo normale
&#x200B;* [Arresto anomalo]&#x200B;[Esegue i baking] Esegue i baking con gabbia personalizzata abilitata ma nessun file selezionato arresti anomali
&#x200B;* [Arresto anomalo] Annullamento della esegue i baking di AO
&#x200B;* [Auto-Cage] Caricamento infinito quando il percorso del file di tipo High Poly non è valido
&#x200B;* [Linux]&#x200B;[Windows] Il selettore colore a volte può essere completamente nero o non apparire
&#x200B;* [Strumento Riempimento poligonale] Lo strumento non funziona con file non PBR
&#x200B;* &lbrack;[Pittura] L’eliminazione del canale del colore di base non elimina il colore colorato in precedenza
&#x200B;* [USD] Le Istanze shader non vengono tutte rilevate correttamente
&#x200B;* [Substance] Viene preso in considerazione solo il primo utilizzo di un nodo di input/output
&#x200B;* L’Occlusione ambientale [Shader] viene applicata due volte con gli insiemi di texture, utilizzando diversi metodi di miscelazione
&#x200B;* [Engine] Una texture normale con canale blu vuoto (nero) può produrre risultati di fusione errati
&#x200B;* [Importazione GLTF] La fusione alfa è abilitata su ogni set di texture
&#x200B;* [Esportazione GLTF] La fusione alfa è sempre abilitata all&#39;esportazione
&#x200B;* [Esporta] La geometria a due lati è sempre disattivata durante l&#39;importazione di un file GLTF
&#x200B;* [Javascript] La modifica delle impostazioni degli shader non contribuisce alla cronologia di annullamento
&#x200B;* [Esempi] La dispersione sotto la superficie non è attivata in Impostazioni schermo per Riunione

### 12.0.3

Data di pubblicazione: **2026/05/05**

Riepilogo: **Versione secondaria**

**Aggiunto:**

&#x200B;* Aggiornare i baker alla versione 3.22.2
&#x200B;* Aggiornamento del motore di Substance alla versione 9.4.3
&#x200B;* \[Python\] Salvare un materiale avanzato in un percorso specifico

**Corretto:**

&#x200B;* \[Ubuntu\] Arresto anomalo durante la selezione del materiale
&#x200B;* Viene visualizzata la finestra a comparsa \[Mac\] Ricorrente per chiedere l’accesso ai dati di altre app
&#x200B;* Gli artefatti \[Eseguente i baking\] possono essere visualizzati sulla mappa di curvatura
&#x200B;* \[Esegue i baking\] La Esegue i baking è in alcuni casi più lenta
&#x200B;* \[Altera a geometria\] In alcuni casi l’opzione Altera a geometria viene disattivata
&#x200B;* \[Porzione UV\] Alfa estratto del punto di ancoraggio ignorato da altre porzioni
&#x200B;* \[Python\]\[Mac\] Eccezioni nella console Python con SSL
&#x200B;* \[Python\] arresto anomalo Painter all&#39;uscita con widget Qt rimanenti

### 12.0.2

Data di pubblicazione: **2026/04/07**

Riepilogo: **Versione secondaria**

**Aggiunto:**

&#x200B;* [Gestione colore] Aggiungi un nuovo OCIO per specificare lo spazio colore predefinito del selettore colore
&#x200B;* [Python] Esporre le impostazioni di annullamento automatico del wrapping nell’API Python

**Corretto:**

&#x200B;* [Arresto anomalo] Il salvataggio con spazio su disco insufficiente può causare l’arresto anomalo o il danneggiamento dei progetti
&#x200B;* [Arresto anomalo] [Barra multifunzione] L&#39;utilizzo della barra multifunzione può causare arresti anomali per alcuni progetti
&#x200B;* [Arresto anomalo] [Baking] arresto anomalo quando non è possibile scrivere il file .assbin nella cartella
&#x200B;* [Importazione] Le trame OBJ da Stager possono non riuscire durante la creazione del progetto
&#x200B;* [Import] In alcuni casi, OBJ ha un volto mancante
&#x200B;* [Importa] La trama USD senza materiale assegnato può arrestarsi in modo anomalo durante l&#39;importazione
&#x200B;* [Tracciato pieno] Non influenzato dalla simmetria
&#x200B;* [Stencil] L&#39;anteprima ha una risoluzione inferiore rispetto al risultato disegnato
&#x200B;* [UI] &quot;uv island&quot; è ancora menzionato nella descrizione comandi dell&#39;origine colore della mappa ID
&#x200B;* [Display] Le ombre appaiono invertite
&#x200B;* [Finestra vista] La trasformazione della proiezione di alterazione rimane dopo il passaggio alla modalità cottura
&#x200B;* [Altera] La griglia scompare quando la scala è impostata su 0 sull’asse Z con l’opzione Altera alla geometria attivata
&#x200B;* [Python] Errore imprevisto durante l&#39;aggiunta di un canale con modifica dell&#39;ambito

### 12.0.1

Data di pubblicazione: **2026/03/18**

Riepilogo: **Versione secondaria**

**Corretto:**

&#x200B;* \[Arresto anomalo\]\[Blocca\] Esporta da progetti specifici

### 12.0.0

Data di pubblicazione: <b>2026/03/09</b>
Riepilogo: <b>Questa è una versione principale. Questa versione contiene le funzioni per la conversione dei livelli, l&#39;alterazione della geometria, i nuovi effetti di postproduzione, i miglioramenti apportati alla nuova finestra del progetto e altri miglioramenti.</b>

<b>Aggiunto</b>:

&#x200B;* [Appiattisci livelli] Appiattisci i livelli all’interno del gruppo di livelli
&#x200B;* [Unico livello] Esportare su disco i livelli uniti
&#x200B;* [Altera a geometria] Aggiunge una nuova funzionalità di alterazione automatica alle proiezioni di alterazione
&#x200B;* [Post-effetti] Sostituisci i post-effetti con l’aggiunta di nuovi
&#x200B;* [Post-effects] Aggiornare la mappatura toni
&#x200B;* [Post-effetti] Aggiungi nuovo utilizzo per le risorse Post-effetti
&#x200B;* [Content]&#x200B;[Post-effects] Integra le risorse predefinite per i post-effetti nella libreria
&#x200B;* [Nuovo progetto] Miglioramento dell’interfaccia utente per la creazione di progetti
&#x200B;* [Nuovo progetto] Modifiche alla funzionalità di reimportazione della trama
&#x200B;* [Nuovo progetto] Consenti apertura file \*.geo.usd
&#x200B;* [Configurazione progetto] Miglioramento dell&#39;interfaccia utente per la configurazione del progetto
&#x200B;* Aggiornamento della libreria USD alla versione 25.05
&#x200B;* Aggiornamento della Substance Engine alla versione 9.3.4
&#x200B;* Aumenta i driver minimi a 25.3.1/25.Q2 per le GPU AMD
&#x200B;* Aggiornamento di Qt alla versione 6.8.6
&#x200B;* [Scripting] Aggiornamento dell’API JavaScript alla versione 1.1.20
&#x200B;* Aggiorna Python alla versione 3.13

<b>Corretto:</b>

&#x200B;* [Arresto anomalo] La modifica dell’output di un canale di materiale in una maschera può causare l’arresto anomalo
&#x200B;* [Import] Le texture EXR vengono forzate in sRGB invece che lineari durante l&#39;importazione dei file USD
&#x200B;* [Porzione UV] Una sequenza di immagini con una sola immagine riempie anche altre Porzioni UV
&#x200B;* [Esegue i baking] L’AO varia tra esegue i baking su CPU e GPU
&#x200B;* [Color Management]&#x200B;[MacOS] La finestra di visualizzazione BaseColor non corrisponde al selettore colore
&#x200B;* [USD] In alcuni casi non vengono importati valori uniformi

## Versione 11

### 11.1.3

Data di pubblicazione: <b>2026/02/12</b>
Riepilogo: <b>Versione secondaria</b>

<b>Risolto</b>:

&#x200B;* [Pittura] In alcuni casi, Stencil e simmetria non funzionano
&#x200B;* [Path] Nessun aggiornamento quando si modifica il cursore dell&#39;opacità del tratto sfumino
&#x200B;* [Progetto] Impossibile eseguire la pittura su una geometria
&#x200B;* [Barra multifunzione] Il tracciato istanziato scompare quando si modifica la risoluzione dell’insieme di texture
&#x200B;* [UI] Il selettore colore può ridursi e scomparire in alcuni casi

### 11.1.2

Data di pubblicazione: <b>2026/01/13</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

&#x200B;* [Eseguire i baking] Migliorare il tempo di eseguita i baking per il progetto Porzione UV con il salvataggio asincrono
&#x200B;* [Ombreggiatori] Citazione nelle modifiche apportate al registro delle modifiche delle API shader in seguito alla migrazione Vulkan
&#x200B;* Aggiornamento dell’OpenEXR alla versione 3.4.4

<b>Risolto</b>:

&#x200B;* [Arresto anomalo] Arresto anomalo durante l&#39;avvio su Nvidia GTX 10xx series
&#x200B;* [Arresto anomalo] L’uso del selettore colore su diversi set di texture può produrre un arresto anomalo quando si esce dall’applicazione
&#x200B;* [Prestazioni] Problema di prestazioni quando si disegna in un progetto con più livelli
&#x200B;* [Prestazioni] Ritardo quando si disegna con la penna grafica
&#x200B;* [UI] Le impostazioni della fotocamera rimangono disattivate in modalità di rendering (Iray)
&#x200B;* [Barra multifunzione] In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
&#x200B;* [Barra multifunzione] Problema di prestazioni con la Porzione UV
&#x200B;* [Substance]&#x200B;[UI] Gli input dell’immagine scompaiono quando compressi
&#x200B;* [Substance]&#x200B;[UI] I gruppi nidificati possono rimanere visibili anche se li nascondono.
&#x200B;* [Eseguita i baking]&#x200B;[UI] Impossibile impostare il raggio di campionamento della curvatura oltre 0,01
&#x200B;* [Eseguita i baking]&#x200B;[UI] Impossibile impostare la distanza massima di occlusione oltre 1
&#x200B;* [Eseguita i baking] L’impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e Bassa come eseguita i baking alta
&#x200B;* [Eseguente i baking] La mappa ID non esegue i baking i colori dei vertici dall’FBX in modalità Bassa come Alta
&#x200B;* [Content] Il filtro Highpass genera colori sbiaditi nei canali con gestione del colore

### 11.1.1

Data di pubblicazione: <b>2025/12/09</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

&#x200B;* [Prestazioni] Miglioramento delle prestazioni Porzioni UV durante l&#39;elaborazione di texture parziali
&#x200B;* [Baker] Aggiornamento alla versione 3.15.4

<b>Risolto</b>:

&#x200B;* [Arresto anomalo]&#x200B;[MacOS] Salvataggio del progetto da una versione precedente sempre arresto anomalo
&#x200B;* [Arresto anomalo] La chiusura di un progetto può talvolta generare un arresto anomalo
&#x200B;* [Progetto] Errore &quot;numero di membri non corrispondente&quot; durante l’apertura di un progetto creato nella versione precedente
&#x200B;* Le Porzioni UV [Eseguente i baking] non sono combinate con i risultati di esegue i baking precedenti, se presenti
&#x200B;* [Eseguente i baking] Dispositivo perso anche con raytracing disattivato sulla serie Nvidia GTX 10XX
&#x200B;* [Eseguo i baking] AO con normale presenta artefatti ai bordi perché nessuna spaziatura interna
&#x200B;* [Eseguo i baking] L’impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e &quot;corrispondenza per nome&quot; attivata
&#x200B;* [Eseguente i baking] ID Map è completamente nero se mancano i colori dei vertici in qualsiasi trama di poli alta
&#x200B;* [Barra multifunzione] Il suggerimento per il metodo di fusione Alfa indica il metodo di fusione Schermo anziché Scherma lineare
&#x200B;* [Path] Le tangenti creano un ciclo inatteso quando il punto viene spostato vicino alle estremità del tracciato
&#x200B;* [Strumento] L’anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
&#x200B;* [Engine] Colorare piccoli tratti può causare artefatti a blocchi
&#x200B;* [Shader] L’annullamento della creazione dell’istanza shader non rimuove correttamente l’elemento
&#x200B;* [Esporta] La modalità di Alpha per l&#39;esportazione GLTF è sempre impostata su MASK
&#x200B;* [Python] Errore imprevisto durante la modifica della Pila livelli all&#39;esterno del blocco di modifica con ambito

<b>Problemi noti</b>:

&#x200B;* [Barra multifunzione] Problema di prestazioni con la Porzione UV
&#x200B;* [Barra multifunzione] In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
&#x200B;* [Arresto anomalo]&#x200B;[Barra multifunzione] La creazione di testi molto lunghi nella barra multifunzione può dare l&#39;arresto anomalo
&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.1.0

Data di pubblicazione: <b>2025/11/18</b>
Riepilogo: <b>Questo aggiornamento è una versione principale e contiene il nuovo strumento Barra multifunzione con nuovi contenuti dedicati, supporto simmetria per livelli di riempimento, parametro dimensioni fisiche per lo spostamento, prestazioni migliorate tramite i baker aggiornati, supporto Vulkan completo per Windows e Linux e altri miglioramenti.</b>

<b>Aggiunto</b>:

&#x200B;* Nuovo strumento barra multifunzione
&#x200B;* [Strumento] Aggiungi un nuovo strumento barra multifunzione per creare tracciati uniformi
&#x200B;* [Barra multifunzione] Aggiungi scelte rapide da tastiera per i predefiniti della barra multifunzione nella finestra Proprietà
&#x200B;* [Barra multifunzione] Consente di modificare l&#39;opacità della barra multifunzione per vertice sul tracciato
&#x200B;* [Barra multifunzione] Consente di modificare le dimensioni della barra multifunzione per vertice sul tracciato
&#x200B;* [Barra multifunzione] Rimuovi inizio/fine definiti in una Substance quando i percorsi vengono chiusi
&#x200B;* [Barra multifunzione] Rimuovi anteprima tracciato/materiale nella finestra delle proprietà per gli strumenti tracciato Disegno/Gomma/Sfumino
&#x200B;* [Barra multifunzione] Aggiungi metodi di fusione per l&#39;alfa e alcuni canali quando si sovrappongono automaticamente
&#x200B;* Simmetria riempimento
&#x200B;* [Riempimento] Aggiungi il supporto per simmetria su livelli di riempimento ed effetti
&#x200B;* [Fill]&#x200B;[UI] Mostra le impostazioni di simmetria nella finestra delle proprietà per il livello di riempimento e gli effetti
&#x200B;* [Fill] Rielaborare l&#39;interfaccia utente delle impostazioni di simmetria sia nel menu della finestra della vista che nella finestra delle proprietà
&#x200B;* [Riempimento] Riorientare correttamente la texture normale durante la proiezione in modalità di alterazione
&#x200B;* Dimensioni fisiche spostamento
&#x200B;* [Spostamento] Usa dimensioni fisiche come unità di spostamento
&#x200B;* Miglioramento delle prestazioni
&#x200B;* [Prestazioni] Migliorare il rendering dei tratti di pennello piccoli su triangoli grandi
&#x200B;* [Prestazioni] Miglioramento dei tempi di compilazione degli Shader
&#x200B;* [Prestazioni] Supporto Vulkan completo per Windows e Linux
&#x200B;* [Prestazioni] baker aggiornati con rendering GPU più veloce e supporto di AMD raytracing
&#x200B;* [UI] Riorganizza le proprietà degli strumenti in gruppi e comprimi alcuni per impostazione predefinita
&#x200B;* [Engine] Aggiorna Substance Engine alla versione 9.2.5
&#x200B;* [Substance] Esporre la sostituzione della risoluzione per le risorse Substance in Strumenti e riempimenti
&#x200B;* [Esporta] Aggiorna il predefinito di esportazione delle mappe trama per esportare le texture in scala di grigio
&#x200B;* Python
&#x200B;* [Eseguita i baking]&#x200B;[Python] Indica nel registro delle modifiche interrotte dopo l&#39;aggiornamento dei baker
&#x200B;* [Python] Esporre le impostazioni della simmetria di riempimento in Python
&#x200B;* Contenuto e nuovo contenuto
&#x200B;* [Content] Aggiungi 75 nuovi strumenti predefiniti per lo strumento Barra multifunzione
&#x200B;* [Contenuto] Aggiorna la risorsa di creazione sfumature per renderla compatibile con la barra multifunzione

<b>Risolto</b>:

&#x200B;* [Arresto anomalo] Il caricamento di un altro progetto mentre l&#39;aggancio del percorso è abilitato può arresto anomalo
&#x200B;* [Arresto anomalo] Puoi eseguire l’arresto anomalo facendo clic con il pulsante destro del mouse nel pannello Tracciato con le informazioni di un’altra sessione negli Appunti
&#x200B;* [UI] L’interfaccia scorre verso l’alto nelle proprietà dello strumento quando si crea un tracciato
&#x200B;* [UI] Il cursore del mouse scompare quando la visualizzazione del riquadro di visualizzazione del percorso è nascosta
&#x200B;* [Tracciato] Copiare/incollare diverse proprietà dello strumento nel pannello Tracciato causa proprietà instabili
&#x200B;* I predefiniti dello strumento Gomma e Sfumino non aggiornano sempre la selezione del canale
&#x200B;* [Tool] Il valore Dipinto è grigio ma l’interfaccia utente viene visualizzata in bianco dopo il caricamento del predefinito dello strumento colorato nella maschera
&#x200B;* [Strumento] Il predefinito creato dalla maschera mantiene i valori dei canali caricati da un altro predefinito
&#x200B;* [Substance] L&#39;override dello spazio colore normale definito nel grafico non viene considerato
&#x200B;* [Content] La risorsa forma pennello predefinita utilizza una Substance obsoleta

<b>Problemi noti</b>:

&#x200B;* Cronologia Istanze shader non monitorata correttamente
&#x200B;* [Barra multifunzione] Problema di prestazioni con i riquadri UV
&#x200B;* [Barra multifunzione] In alcuni casi, il percorso può sovrapporsi in modo imprevisto dopo un angolo
&#x200B;* [Barra multifunzione] Le tangenti creano un ciclo indesiderato quando il punto viene spostato vicino alle estremità del tracciato
&#x200B;* [Arresto anomalo]&#x200B;[Barra multifunzione] La creazione di testi molto lunghi nella barra multifunzione può causare l&#39;arresto anomalo
&#x200B;* [Strumento] L’anteprima del materiale non funziona quando si utilizza la proiezione in una maschera
&#x200B;* [Baking] L’impostazione AO &quot;Occlusione autonoma&quot; viene ignorata con diversi set di texture e &quot;corrispondenza per nome&quot; abilitato
&#x200B;* [Baking] AO con normale presenta artefatti ai bordi a causa della mancanza di riempimento
&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.3

Data di pubblicazione: <b>2025/08/05</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

&#x200B;* [Substance 3D Assets] Aggiungi un punto di notifica al pannello Risorse 3D
&#x200B;* [VFX Platform 2025] Aggiunta della configurazione ACES 2.0 nelle impostazioni di gestione del colore
&#x200B;* [VFX Platform 2025] Aggiornamento di OCIO alla versione 2.4.2
&#x200B;* Aggiornamento di Iray alla versione 2024.10
&#x200B;* [Engine] Aggiornamento a Substance Engine v.9.2.3
&#x200B;* [Nvidia] Aumenta la versione dei driver minimi Nvidia a 572.60 (Win) e 570.169 (Linux)

<b>Risolto</b>:

&#x200B;* [Python] La modifica con ambito non viene visualizzata nella finestra Cronologia

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.2

Data di pubblicazione: <b>2025/06/10</b>
Riepilogo: <b>Versione secondaria</b>

<b>Aggiunto</b>:

&#x200B;* [Mac] Aggiungi un avviso relativo a una versione specifica del sistema operativo che causa artefatti
&#x200B;* [Aggiornamento automatico] Miglioramenti minori UX al registro degli errori Risorse
&#x200B;* [Annullamento automatico] Aggiornamento alla versione 1.3.2 con miglioramenti per la giuntura
&#x200B;* [USD]&#x200B;[FBX] Aggiungi il supporto per più set UV con dati sparsi
&#x200B;* [Esporta] Nelle trame esportate come FBX mancano i loro set UV aggiuntivi se presenti al momento dell’importazione

<b>Risolto</b>:

&#x200B;* [MacOS]&#x200B;[Linux] Arresto anomalo durante il salvataggio sull&#39;unità di rete
&#x200B;* [Win]&#x200B;[Tablet] Sfarfallio durante il panning
&#x200B;* [SpaceMouse] Problema durante l&#39;utilizzo dello strumento Tracciato
&#x200B;* [Gabbia automatica] Impossibile eseguire il baking dopo un ricaricamento della trama
&#x200B;* [Aggiornamento automatico] La sequenza di immagini non viene ricaricata se manca la prima sezione
&#x200B;* [Path] La tangente personalizzata può influire su un&#39;altra tangente
&#x200B;* [Path] Il percorso non viene visualizzato in un set di texture se il primo punto si trova in un altro set di texture
&#x200B;* [UI] Alcuni menu sono sempre disattivati dopo l’apertura di un progetto (es.: simmetria)
&#x200B;* [Properties] Impossibile utilizzare/caricare strumenti predefiniti con lo strumento Filled path
&#x200B;* [USD] Più set UV non vengono riconosciuti nello shader personalizzato quando si utilizzano file USD
&#x200B;* [USD] Le videocamere con gli stessi nomi vengono sostituite
&#x200B;* [Esporta] Invia a Photoshop genera uno spazio colore errato per i risultati a colori e in scala di grigi
&#x200B;* [Esportazione] I canali in scala di grigio con alfa vengono esportati come colore invece che in scala di grigio con il formato PNG
&#x200B;* [Esportazione] L’esportazione del canale in scala di grigio come PSD genera un file non valido/troncato
&#x200B;* [Contenuto] Il filtro Altera in modalità multidirezionale non funziona
&#x200B;* [Python] Impossibile allocare l&#39;errore dell&#39;elenco durante la ricerca per indicizzazione dei nodi dello stack di livelli

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.1

Data di pubblicazione: <b>2025/04/10</b>
Riepilogo: <b>Versione secondaria</b>

Nota: <b>La versione del CCD Linux verrà posticipata al 29 aprile</b>

<b>Aggiunto:</b>

&#x200B;* Aggiornamento a Qt 6.5.8
&#x200B;* [Substance] Aggiungi un messaggio di registro per i filtri quando più input di immagine condividono lo stesso utilizzo
&#x200B;* [Nvidia] Aggiungi un avviso sui driver Nvidia più recenti (572.47)

<b>Corretto:</b>

&#x200B;* [Arresto anomalo] Quando trascini e rilasci una barra secondaria con un utilizzo in uno slot per un singolo canale
&#x200B;* [Arresto anomalo]&#x200B;[Tracciato] L’opzione Cambia tipo di tracciato non è disattivata quando non si fa clic su un tracciato specifico
&#x200B;* [Percorso di riempimento] Non dovrebbe essere in grado di selezionare il materiale Substance
&#x200B;* [Motore] Artefatti lungo tratti pennello
&#x200B;* [Engine] I tracciati possono essere interrotti con impostazioni specifiche
&#x200B;* Problema con il menu a discesa per lo spazio colore del contagocce
&#x200B;* [Aggiornamento automatico] [Python] Messaggio di errore errato quando si utilizza ResourceID senza versione
&#x200B;* [Shader] Arresto anomalo all’apertura di alcuni progetti

<b>Problemi noti:</b>

&#x200B;* [SpaceMouse] Problema durante l&#39;utilizzo dello strumento Tracciato
&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione

### 11.0.0

Data di pubblicazione: <b>2025/03/11</b>
Riepilogo: <b>Versione principale, nuova funzione Aggiornamento automatico, strumento Tracciato riempito e altri miglioramenti al tracciato, nuovi filtri e una generazione sperimentale di gabbia automatica per la cottura al forno</b>

<b>Aggiunto</b>:

&#x200B;* Aggiornamento automatico
&#x200B;* [Aggiornamento automatico] Aggiornamento automatico delle risorse modificate nel pannello Risorse
&#x200B;* [Aggiornamento automatico] Aggiorna automaticamente le risorse modificate nel progetto
&#x200B;* [Aggiornamento automatico] Disattiva l&#39;aggiornamento automatico per impostazione predefinita
&#x200B;* [Aggiornamento automatico] Rendi facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono (.sbsar, .glsl, .ai, .svg)
&#x200B;* [Aggiornamento automatico] Aggiungi variabile di ambiente per disabilitare la funzione di aggiornamento automatico
&#x200B;* [Aggiornamento automatico]&#x200B;[SBSAR] Rendi facoltativo l&#39;aggiornamento se i parametri della risorsa non corrispondono
&#x200B;* Tracciato pieno
&#x200B;* [Tracciato]&#x200B;[Riempimento] Aggiungi nuovo strumento per creare tracciati pieni
&#x200B;* Miglioramenti al tracciato
&#x200B;* [Path] Crea un tracciato che si aggancia ai poligoni
&#x200B;* [Path] Consente di cambiare i tipi di percorso
&#x200B;* [Path] Consente di copiare e incollare i dati dei vertici del tracciato tra contenuto e maschera
&#x200B;* [Path] Consente di vincolare l&#39;angolo durante la creazione di un nuovo punto
&#x200B;* [Path] Consenti di vincolare la creazione di punti a una linea
&#x200B;* [Tracciato] Chiudi la forma con un solo clic
&#x200B;* [Path] Visualizza informazioni sul percorso
&#x200B;* [Tracciato] Consente di ridimensionare e ruotare i vertici del tracciato
&#x200B;* [Path]&#x200B;[UX] Semplificare l&#39;accesso ai gizmo di trasformazione
&#x200B;* [Path] Aggiungi anteprima percorso
&#x200B;* [Tracciato] Disattiva l&#39;anteprima del tracciato con Maiusc + P
&#x200B;* [Path] Migliorare l&#39;edizione tangente dalla vista laterale
&#x200B;* [Tracciato] Consenti di concentrarsi su un tracciato 3D
&#x200B;* [Path] I vertici devono mantenere lo stato di selezione quando si attiva e disattiva l&#39;interfaccia utente
&#x200B;* [Path] Consente di eliminare il percorso utilizzando Backspace
&#x200B;* [Path] Mantieni l&#39;elenco dei percorsi aperto se l&#39;utente lo espande
&#x200B;* [Path]&#x200B;[Pila livelli] Rinominare correttamente i duplicati quando si copia/incolla
&#x200B;* Miglioramenti all&#39;interfaccia utente di [Path] e alle descrizioni comandi
&#x200B;* Prestazioni
&#x200B;* [Prestazioni] Migliorare le prestazioni della finestra di visualizzazione quando si utilizza un livello di tassellatura elevato
&#x200B;* [Prestazioni] Abilita solo il primo canale su nuovi livelli di riempimento/effetti
&#x200B;* [Prestazioni] Calcolo del tratto del pennello in parallelo
&#x200B;* Baking
&#x200B;* [Eseguita i baking] Aggiungi nuova opzione di generazione completamente automatica delle gabbie per eseguire i baking con maglie ad alto polio (sperimentale)
&#x200B;* Contenuto
&#x200B;* [Content] Aggiungi 6 nuovi filtri: stilizzazione, quantizzazione, kuwahara anisotropo, smusso uniforme, distanza direzionale, conversione in scala di grigi
&#x200B;* [Content] Aggiornate Noises and Grunges alla versione più recente di Designer (con il nuovo Voronoi 2D)
&#x200B;* [Contenuto] Aggiungi 3 nuovi generatori di texture (Tile Random, Triangle Grid, Generatore di Scratches)
&#x200B;* [Content] Rinomina il modello di motore originale ed esporta i predefiniti
&#x200B;* Python
&#x200B;* [Shelf]&#x200B;[Python] Salvataggio del materiale avanzato o della maschera avanzata su disco da Python
&#x200B;* [Python] Aggiungi gabbia automatica eseguente i baking all’API Python
&#x200B;* [Python] Consente di modificare i nomi e le descrizioni di set di texture/Porzioni UV
&#x200B;* [Python] Condivisione delle impostazioni di risoluzione su sorgenti vettoriali e di font
&#x200B;* [Auto-update]&#x200B;[Python] Esporre le funzionalità di aggiornamento automatico del progetto in Python
&#x200B;* Varie
&#x200B;* [Esporta] Semplificare l’accesso alle opzioni di invio con un nuovo pannello
&#x200B;* [Nvidia] Aggiungi un avviso sui driver Nvidia più recenti (572.16)
&#x200B;* L’aggancio dell’angolo deve essere influenzato dalla selezione dello spazio Oggetto/Mondo
&#x200B;* [Elenco set di texture] Consente di aggiungere un nome personalizzato alle Porzioni UV e di utilizzarle all’esportazione
&#x200B;* Mac
&#x200B;* [Mac] Usare Metal invece di OpenGL per il rendering grafico
&#x200B;* [Mac] Elimina il supporto Mac Intel

<b>Risolto</b>:

&#x200B;* [Arresto anomalo] Elimina input immagine
&#x200B;* Impossibile aggiungere smart mat tramite il pulsante Pila livelli
&#x200B;* [Python] Impossibile trovare gli effetti in GroupLayerNode

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Arresto anomalo]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [MacOS Intel] Arresto anomalo durante l&#39;importazione di alcuni predefiniti
&#x200B;* [Engine] Colorare con lo strumento Clona /Clone in colori di scorrimento canale normale non correttamente
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione
&#x200B;* [RedHat] Problemi con il selettore colore

## Versione 10

### 10.1.2

Data di pubblicazione: <b>2024/12/3</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Risolto</b>:

&#x200B;* [Arresto anomalo] Elimina input immagine
&#x200B;* Impossibile aggiungere smart mat tramite il pulsante Pila livelli
&#x200B;* [Python] Impossibile trovare gli effetti in GroupLayerNode

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Arresto anomalo]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [MacOS Intel] Arresto anomalo durante l&#39;importazione di alcuni predefiniti
&#x200B;* [Engine] Colorare con lo strumento Clona /Clone in colori di scorrimento canale normale non correttamente
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione
&#x200B;* [RedHat] Problemi con il selettore colore

### 10.1.1

Data di pubblicazione: <b>2024/11/5</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Aggiunto</b>:

&#x200B;* [Progetto] Mantieni aperto il progetto corrente fino alla convalida della nuova selezione del progetto
&#x200B;* [Srotolamento automatico] La densità di Texel consente di dividere meglio le Isole UV in UDIM
&#x200B;* [Eseguire i baking] Correggere una copia ambigua nel menu di scelta rapida di Mesh Maps
&#x200B;* [Altera] Rimuovi il ridimensionamento nella finestra della vista per l’asse Z (profondità)
&#x200B;* [Importa/Esporta] Rimuovi il supporto per i formati di file immagine inutilizzati
&#x200B;* Aggiornamento della Substance Engine alla versione 9.1.4

<b>Risolto</b>:

&#x200B;* [Arresto anomalo] Dopo il trasferimento della risorsa in Risorse e il salvataggio del progetto
&#x200B;* [Arresto anomalo] Problemi con la libreria aiserver
&#x200B;* [Arresto anomalo] arresto anomalo del server Illustrator in alcuni rari casi
&#x200B;* [Arresto anomalo] Quando si esce dall’applicazione in alcuni rari casi
&#x200B;* Impossibile inviare report di arresto anomalo su alcuni computer
&#x200B;* [Esegue i baking] Il colore del vertice non viene letto correttamente
&#x200B;* [UI] La posizione delle finestre e le novità all’avvio sono state spostate
&#x200B;* [Assimp] StandardSurface di Maya non riconosciuto nella esegue i baking ID
&#x200B;* [Python] La libreria SSL mancante genera un errore
&#x200B;* [Python]&#x200B;[Win] Errore durante la chiamata di QColorConstants.Transparent
&#x200B;* [Python] Le miniature dei livelli create tramite Python non si aggiornano finché non si fa clic all’interno della Pila livelli
&#x200B;* [Shader] Collegamento interrotto nel registro delle modifiche delle API shader
&#x200B;* [Risorse 3D] Utilizza le impostazioni proxy del sistema operativo per accedere alle Risorse 3D

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Arresto anomalo]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [MacOS Intel] Arresto anomalo durante l&#39;importazione di alcuni predefiniti
&#x200B;* [Engine] Colorare con lo strumento Clona /Clone in colori di scorrimento canale normale non correttamente
&#x200B;* [Python] Il widget che sembra eliminato tramite script funziona ancora
&#x200B;* [RedHat] Problemi con il selettore colore

### 10.1.0

Data di pubblicazione: <b>2024/09/17</b>
Riepilogo: <b>Versione principale, nuovo contenuto: maschera area di riempimento/filtro colore, filtro decalcomania ricamo e sei filtri Substance generici, importazione di USD con proprietà di materiale e shader, miglioramento delle prestazioni, conformità alla piattaforma VFX 2024 e migrazione a Linux RedHat</b>

<b>Aggiunto</b>:

&#x200B;* [Contenuto] Aggiungi nuova maschera area di riempimento/filtro colore
&#x200B;* [Content] Aggiungi nuovo filtro Ricamo decalcomania
&#x200B;* [Content] Aggiungi 6 nuovi filtri Substance generici (FXAA, pixelate, highpass, posterize, smoothstep, threshold)
&#x200B;* [USD] Esporta il livello USD con un materiale ASM definito
&#x200B;* [USD] Importare USD con proprietà del materiale e dello shader
&#x200B;* [Prestazioni] Abilita miniature stack di livelli ottimizzate per impostazione predefinita
&#x200B;* [Prestazioni] Riduzione del tempo di apertura dei file di progetto e del consumo di memoria (decodifica dei dati)
&#x200B;* Conforme alla piattaforma VFX 2024
&#x200B;* [VFX Platform 2024] Aggiornamento a Python 3.11
&#x200B;* [Piattaforma VFX 2024] Aggiornamento all&#39;OpenEXR 3.2
&#x200B;* [VFX Platform 2024] [USD] Aggiornamento OpenSubdiv 3.6.0
&#x200B;* [VFX Platform 2024]&#x200B;[Color Management] Aggiornamento a OCIO 2.3.2
&#x200B;* [Linux] Migrazione a Linux RedHat
&#x200B;* [Linux] Aggiorna la versione min del driver Nvidia a 535.171.04
&#x200B;* [Import] Aggiungi un&#39;opzione per capovolgere la mappa normale durante l&#39;importazione di una trama GLTF
&#x200B;* [UI] Utilizza il valore predefinito del sistema operativo per la distanza di rilevamento degli eventi di trascinamento
&#x200B;* [Substance Engine] Aggiungi la funzione di striscia delle chiamate per rimuovere i simboli dall&#39;eseguibile
&#x200B;* [Schermata iniziale] Aggiornamento al nuovo formato della schermata iniziale
&#x200B;* Aggiornamento della Substance Engine alla versione 9.1.3
&#x200B;* [Python] Mostra collegamento agli esempi nel menu della documentazione dello stack di livelli
&#x200B;* [JavaScript] Spostare i plug-in Javascript nella sottocartella javascript/plugins

<b>Risolto</b>:

&#x200B;* [Illustrator] Arresto anomalo durante l&#39;esportazione di un riquadro UV con grafica .ai in casi specifici
&#x200B;* [Tratti dinamici]&#x200B;[Tracciato] Casuale per tratto non funziona su un tracciato
&#x200B;* [UI]&#x200B;[Proprietà] Il blocco è attivato quando la suddivisione in porzioni è non uniforme
&#x200B;* Il file TXT di debug viene creato quando si fa doppio clic su un progetto Painter
&#x200B;* [USD]&#x200B;[Esporta] Alcune texture potrebbero essere mancanti
&#x200B;* [ASM] La dispersione del canale del colore ignora l&#39;effetto metallizzato
&#x200B;* [Contenuto] Il filtro Sfocatura non funziona nello spazio colore &quot;di lavoro&quot;
&#x200B;* [Contenuto] Il filtro Regolazione Height modifica anche il canale alfa del livello

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Win]&#x200B;[Arresto anomalo] [ACE] Non utilizza lo spazio colore ICE sRGB per la trasformazione dello schermo
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
&#x200B;* [Arresto anomalo] Riposiziona risorsa e salva progetto
&#x200B;* [Engine] Colorare con lo strumento Clona in canali normali si sposta i colori in modo errato
&#x200B;* [Python] Il widget Ghost viene eliminato se lo script è ancora in funzione
&#x200B;* [RedHat] Problemi con il selettore colore

### 10.0.1

Data di pubblicazione: <b>2024/06/11</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Aggiunto:</b>

&#x200B;* [Library] Convertire i font di Substance in normali file di font
&#x200B;* [Illustrator]&#x200B;[SVG] Dai alle miniature nella selezione dell&#39;ambito uno sfondo grigio chiaro
&#x200B;* [Python] Aggiungi la funzione sull&#39;origine bitmap per elencare gli spazi colore disponibili

<b>Risolto</b>:

&#x200B;* [Serie di livelli] Cartella sempre chiusa quando viene spostata all’interno o all’esterno di altre cartelle
&#x200B;* [Salva] Il file di progetto viene perso quando &quot;salva come copia&quot; o il salvataggio automatico non riesce in casi specifici
&#x200B;* [Importa] Le risorse con lo stesso nome ma estensioni diverse vengono sostituite
&#x200B;* [Proprietà] Impostazioni mancanti quando si utilizza un punto di ancoraggio negli input dell’immagine
&#x200B;* [Illustrator] Impossibile importare file Illustrator dopo l&#39;arresto del server senza riavviare Painter
&#x200B;* [Python] Impossibile impostare l&#39;istanza padre con il tipo &quot;properties&quot;
&#x200B;* [Python] L&#39;impostazione del poly alto come parametro di cottura non carica il poly alto
&#x200B;* [Python] Messaggio di errore per set\_color\_space() troppo generico
&#x200B;* [Python] Le sorgenti di riferimento consentono di creare cicli

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sugli schermi HD
&#x200B;* [Crash]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [MacOS Intel] Arresto anomalo durante l’importazione di alcuni predefiniti
&#x200B;* [Illustrator] Arresto anomalo durante l&#39;esportazione di un riquadro UV con grafica .ai in casi specifici
&#x200B;* [Tratti dinamici]&#x200B;[Tracciato] Casuale per tratto non funziona su un tracciato

### 10.0.0

Data di pubblicazione: <b>2024/05/16</b>
Riepilogo: <b>Versione principale, edizione dello stack di livelli con API Python, lettura dei file nativi di Illustrator, integrazione di risorse 3D e nuova risorsa di testo</b>

<b>Aggiunto</b>:

&#x200B;* [Illustrator] Utilizzare i file Illustrator con le tavole da disegno in Painter
&#x200B;* [Illustrator]&#x200B;[SVG] Aggiungere anteprime nella selezione dell’ambito
&#x200B;* [Substance 3D Assets] Sfoglia, seleziona e scarica Risorse 3D direttamente in Painter
&#x200B;* [Substance 3D Assets]&#x200B;[UI] Nuovo pannello
&#x200B;* [Substance 3D Assets] Supporto di mappe e materiali ambientali
&#x200B;* [Substance 3D Assets] Consenti di ricaricare, navigare e aprire la cartella della posizione nel nuovo pannello di Substance 3D Assets
&#x200B;* [Substance 3D Assets] Aggiunta di un gestore di download
&#x200B;* [Risorsa testo] Consenti l&#39;utilizzo di font incorporabili
&#x200B;* [Risorsa testo] Consenti il rendering di un font o testo su una trama
&#x200B;* [Risorsa di testo] Visualizza i font dell&#39;utente e di altri tracciati condivisi nel pannello Risorse con una nuova categoria
&#x200B;* [Text Resource]&#x200B;[Properties] Aggiungi il supporto per le proprietà avanzate dei font
&#x200B;* [Risorsa di testo] Consenti di cercare/visualizzare i font nei mini-scaffali
&#x200B;* [Risorsa testo] Aggiungi messaggio di errore/finestra di dialogo durante l’importazione di un font incompatibile
&#x200B;* Varie
&#x200B;* [Proiezione riempimento] Migliora il comportamento del manipolatore di scala quando si utilizzano valori piccoli
&#x200B;* [Manipolatori] Aggiungi una nuova modalità precisa quando si preme CTRL
&#x200B;* [Manipolatori] Miglioramento della stabilità del manipolatore di superficie durante la traslazione
&#x200B;* [Esporta] Aggiungi nome spazio colore negli output SBSAR
&#x200B;* [Prestazioni] Miglioramento dei tempi di individuazione delle librerie delle risorse su disco
&#x200B;* [Substance] Aggiornamento al motore di Substance versione 9.1.2
&#x200B;* [Drag and Drop] Allinea la rotazione della decalcomania alla videocamera quando viene rilasciata nella finestra della vista
&#x200B;* [Python] Edizione dello stack di livelli
&#x200B;* [Python] Consenti di selezionare livello, effetto, maschera e maschera geografica nell&#39;interfaccia utente
&#x200B;* [Python] Consenti di ottenere/impostare i metodi di fusione dei livelli
&#x200B;* [Python] Consenti di ottenere/impostare le impostazioni di proiezione del livello di riempimento
&#x200B;* [Python] Consente di interrogare il colore del materiale della Substance da un livello di riempimento
&#x200B;* [Python] Consenti di eseguire query e impostare colori e risorse uniformi nei livelli e negli effetti
&#x200B;* [Python] Consenti di creare e modificare risorse di testo in una pila di livelli
&#x200B;* [Python] Consente di modificare i canali attivi su livelli ed effetti
&#x200B;* [Python] Consenti alle azioni in batch di avere un singolo annullamento/ripristino
&#x200B;* [Python] Consente di caricare/modificare i parametri di origine vettoriale
&#x200B;* [Python] Consente di modificare le proprietà dei colori dei livelli e degli effetti con la gestione del colore
&#x200B;* [Python] Consenti di eseguire query e creare livelli istanziati
&#x200B;* [Python] Consenti di aggiungere un effetto di selezione colore
&#x200B;* [Python] Consente di controllare la gestione del colore dell&#39;immagine bitmap
&#x200B;* [Python] Consente di mettere in pausa/rimettere in pausa il motore
&#x200B;* [Python] Consenti di passare a nodi di pari livello e nodi padre
&#x200B;* [Python] Consente di creare un effetto filtro/generatore
&#x200B;* [Python] Consente di aggiungere un effetto livello
&#x200B;* [Python] Consenti di aggiungere una maschera avanzata a un livello
&#x200B;* [Python] Consenti di creare/modificare punti di ancoraggio
&#x200B;* [Python] Consenti di ottenere/impostare la maschera sui livelli
&#x200B;* [Python] Consente di creare un effetto maschera di confronto
&#x200B;* [Python] Consenti di eseguire query e utilizzare i predefiniti dalle risorse Substance
&#x200B;* [Python] Consenti di elencare i predefiniti e i relativi valori tramite la funzione internal\_properties per le risorse Substance
&#x200B;* [Python] Consenti di elencare i predefiniti di esportazione predefiniti
&#x200B;* [Python] Consenti di elencare i predefiniti di esportazione disponibili nella libreria
&#x200B;* [Python] Consenti di recuperare il contenuto dei predefiniti di esportazione

<b>Risolto</b>:

&#x200B;* [Arresto anomalo] Annullamento di &quot;Rimuovi istanza shader&quot; con Ctrl+Z
&#x200B;* [Arresto anomalo] Crea un livello su una pila vuota se l’ultima selezione era un effetto
&#x200B;* [SVG] Problema con il valore dell’area ritagliata personalizzato
&#x200B;* [Annullamento automatico] Il ricalcolo del solo impacchettamento senza alcuna modifica dell’orientamento UV provoca l’arresto anomalo
&#x200B;* [Drag and drop] Il ritardo dovuto alle risorse esterne viene precaricato più volte
&#x200B;* [UI] Trascinate la miniatura della risorsa per nascondere il messaggio di avviso nello stack di livelli
&#x200B;* [Prestazioni] I riquadri UV mascherati vengono ancora calcolati
&#x200B;* [USD] Evidenziazione errata per la selezione dell’ambito
&#x200B;* [Risorsa] L&#39;immagine bitmap viene danneggiata dopo aver colorato nel canale normale e salvato il progetto
&#x200B;* [USD] Supporta l’ordine dei vertici mancini
&#x200B;* [Substance] Ripristina predefiniti torna sempre a zero per il widget Angolo
&#x200B;* [Engine] Colorare con un SVG in uno stencil non funziona
&#x200B;* [Motore] I tratti del pennello mappa normale si interrompono dopo un annullamento
&#x200B;* [Contenuto] Il filtro Da grafica a materiale presenta una fusione alfa e uno spazio cromatico errati
&#x200B;* [Content] I metodi di fusione sul Tile Generator non funzionano
&#x200B;* [Contenuto] In alcuni casi, il filtro di scansione dell’istogramma genera bande
&#x200B;* [Contenuto] L’illuminazione Eseguita i baking stilizzata non tiene conto del height dipinto
&#x200B;* [Python] Errore imprevisto durante il recupero delle informazioni sui livelli istanziati dopo la modifica dello shader
&#x200B;* [Salva] Il file di progetto viene perso quando &quot;salva con nome&quot; non riesce in casi specifici

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Arresto anomalo]&#x200B;[Linux]&#x200B;[AMD] Trascinamento di risorse in Pila livelli su Wayland OS
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo per gli schermi HD
&#x200B;* [Arresto anomalo]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent
&#x200B;* [Salva] Il file di progetto Spp viene perso quando &quot;salva come copia&quot; non riesce in casi specifici
&#x200B;* [MacOS Intel] Arresto anomalo durante l&#39;importazione di alcuni predefiniti
&#x200B;* [Illustrator] Impossibile importare i file Ai dopo l&#39;arresto anomalo del server senza riavviare Painter
&#x200B;* [Importa] Le risorse con lo stesso nome ma estensioni diverse vengono sostituite

## Versione 9

### 9.1.2

Data di pubblicazione: <b>2024/01/30</b>
Riepilogo: <b>Versione secondaria, correzioni di bug</b>

<b>Aggiunto</b>:

&#x200B;* [Prestazioni] Migliorare il tempo di creazione del primo livello di riempimento nei nuovi progetti
&#x200B;* [Prestazioni] Riduzione del tempo di caricamento delle mappe dell&#39;ambiente più complesse
&#x200B;* [Substance] Consenti di salvare/chiudere i progetti anche quando vengono generate miniature

<b>Risolto</b>:

&#x200B;* Il salvataggio non riesce sui progetti della versione precedente quando la finestra della vista viene modificata
&#x200B;* [Arresto anomalo] Reimportazione della trama quando si utilizza AO personalizzato e la gestione del colore
&#x200B;* [Proiezione riempimento] Facendo clic sul manipolatore Scala viene visualizzato il messaggio &quot;non colorabile&quot;
&#x200B;* [Pennello] Colorare con allineamento UV provoca artefatti
&#x200B;* [Pila livelli] La ridenominazione del livello è lenta quando la pila è molto lunga
&#x200B;* [Pila livelli] Messaggio di errore errato quando si utilizza un filtro incompatibile nella maschera
&#x200B;* [Pila livelli] La selezione torna al livello superiore dopo l’eliminazione
&#x200B;* [Esporta] La texture normale generata è sempre in modalità di riempimento Vicina spazio 3D
&#x200B;* [Esporta] La Texture alfa non viene generata con il predefinito di esportazione vista 2D
&#x200B;* [Export] L’esportazione SBSAR contiene utilizzi errati con mappe convertite
&#x200B;* [Shader] Il registro delle modifiche di API shader non è aggiornato con le ultime modifiche ASM

<b>Problemi noti</b>:

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Arresto anomalo]&#x200B;[Linux]&#x200B;[AMD] Trascinamento di risorse in Pila livelli su Wayland OS
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo per gli schermi HD
&#x200B;* [Arresto anomalo]&#x200B;[Python] Esportazione USD attivata da TextureStateEvent

### 9.1.1

Data di pubblicazione: <b>2023/12/05</b>
Riepilogo: <b>Versione secondaria, correzioni di bug e invio alle funzionalità After Effects</b>

<b>Aggiunto:</b>

&#x200B;* [Interoperabilità] Consente di inviare una trama con texture ad After Effects (Ae 24.1)

<b>Corretto:</b>

&#x200B;* [Riempimento] L&#39;impostazione UV sulla proiezione del set UV non legge più di 2 set UV
&#x200B;* [Arresto anomalo] Utilizzo di una mappa dell&#39;ambiente a 16 K
&#x200B;* [Arresto anomalo] Exr utilizzato come input dell&#39;immagine
&#x200B;* [Arresto anomalo] Copiare e incollare tracciati tra progetti
&#x200B;* [QoL] Se si trascina una risorsa Alpha in modalità decalcomania, viene creata una Proiezione UV nella maschera
&#x200B;* [Path] Quando si copiano i vertici di un tracciato, anche il tracciato di destinazione viene rinominato alla riapertura del progetto
&#x200B;* [Linux] La selezione del colore può essere interrotta con più schermi
&#x200B;* [Annullamento automatico] Problema di interfaccia utente per il controllo della densità del testo
&#x200B;* [Gestione colore] Il feedback dell&#39;interfaccia utente è appropriato per i casi, ma il motore non lo è
&#x200B;* [Gestione colore] Selezione dello spazio colore errata nella maschera con override dei dati utente

<b>Problemi noti:</b>

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Arresto anomalo]&#x200B;[Linux] con Linux Wayland su AMD quando si trascina e si rilascia la risorsa nella Pila livelli
&#x200B;* [Arresto anomalo]&#x200B;[Mac] Modifica del valore di filtro anisotropo nel sistema operativo Monterey
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sullo schermo hd
&#x200B;* [Python] Arresto anomalo di esportazione dell’USD attivato da TextureStateEvent

### 9.1.0

Data di pubblicazione: <b>2023/11/07</b>
Riepilogo: <b>Versione principale che introduce il supporto per SVG e trasparenza, oltre a miglioramenti dello strumento di trascinamento della selezione</b>

<b>Aggiunto:</b>

&#x200B;* [SVG] Consenti l’importazione di file vettoriali (SVG)
&#x200B;* [SVG]&#x200B;[UI] Aggiungi il supporto per le proprietà specifiche dei SVG
&#x200B;* [SVG] Aggiungete un’opzione per mantenere facilmente le proporzioni originali dell’immagine
&#x200B;* [SVG] Consenti l&#39;utilizzo automatico del canale alfa di SVG con trasparenza
&#x200B;* [Interoperabilità] Consente di inviare una trama con texture ad After Effects (Ae 24.1 beta)
&#x200B;* [Interoperabilità] Aggiungere impostazioni per Invia a After Effects
&#x200B;* [QoL]&#x200B;[Assets]&#x200B;[UI] Importa automaticamente risorsa durante il trascinamento nello slot dell&#39;interfaccia utente
&#x200B;* [QoL] Consente di trascinare e rilasciare risorse esterne nella Pila livelli
&#x200B;* [QoL]&#x200B;[Pila livelli] Trascina le texture dal pannello Risorse alla Pila livelli
&#x200B;* [QoL]&#x200B;[Viewport] Consente di trascinare e rilasciare il generatore, filtri sulla trama
&#x200B;* [QoL]&#x200B;[Finestra vista] Consente di rilasciare risorse esterne sulla trama
&#x200B;* [QoL]&#x200B;[Proiezione] Aggiungi un nuovo set UV alla modalità di proiezione del set UV
&#x200B;* [QoL] Trascina le Maschere avanzate come nuovi livelli nella finestra della vista e nella Pila livelli
&#x200B;* [QoL] Aggiungi selettore per i generatori con più output quando utilizzati nella maschera
&#x200B;* [QoL] Consente di trascinare e rilasciare immagini a canale singolo su un effetto di riempimento
&#x200B;* [QoL]&#x200B;[Pila livelli] Usate i modificatori CTRL/ALT con il trascinamento per specificare dove/come creare effetti/livello
&#x200B;* [Tracciato] Attiva/disattiva la visibilità dei tracciati singolarmente nel pannello Tracciato
&#x200B;* [Path] Consenti l&#39;utilizzo di manipolatori di trasformazione per i punti di tracciato
&#x200B;* [Path] Consente di controllare manualmente le tangenti per vertice
&#x200B;* [Path] Copiare/incollare le proprietà del percorso
&#x200B;* [Path] Introdurre una scelta rapida da tastiera vuota per il pulsante Tangente di interruzione
&#x200B;* [Shader] Aggiunta del supporto per Opacità e Traslucidità in shader ASM
&#x200B;* [Shader] Aggiunta del supporto per il canale del Colore di assorbimento con shader ASM
&#x200B;* [Shader] Suggerimenti per migliorare i parametri degli shader ASM
&#x200B;* [Shader] Imposta il colore predefinito del canale della Traslucidità su nero
&#x200B;* [Impostazioni schermo] Abilita Anti-alias temporale per impostazione predefinita
&#x200B;* [Impostazioni schermo] Abilita impostazione di dispersione sotto la superficie per impostazione predefinita
&#x200B;* [Substance] Aggiungi il supporto per la proprietà ColorSpace dall’input/output del grafico
&#x200B;* [Substance] Aggiorna il motore di Substance alla versione 9.0.3
&#x200B;* [UI] Rendi accessibile il pulsante contestuale della barra degli strumenti anche se la finestra dell&#39;app è piccola
&#x200B;* [Annullamento automatico] Controlla il numero di Porzione UV con densità texel
&#x200B;* [Eseguo i baking] Disattiva Raytracing GPU sulle GPU AMD per impostazione predefinita
&#x200B;* [Prestazioni] Applicate la compressione senza perdita di dati alle immagini a 16 bit per ridurre l’ingombro del progetto
&#x200B;* [Python] Consenti di manipolare la videocamera predefinita in vista 3D
&#x200B;* [Python] Esporta la possibilità di esportare trama tramite scripting
&#x200B;* [Content]&#x200B;[Samples] Aggiungi un nuovo progetto di esempio &quot;French Restaurant Table&quot;
&#x200B;* [Content] Aggiorna Substance logo alpha alla nuova versione
&#x200B;* [Contenuto] Aggiungi tre filtri di materiale focalizzati sui SVG (Adesivo personalizzato, Spruzzo personalizzato e Grafica su materiale)

<b>Corretto:</b>

&#x200B;* [Arresto anomalo] Modifica della dimensione del manipolatore quando non si utilizza lo strumento simmetria
&#x200B;* [Arresto anomalo] [Pila livelli] Creazione del livello quando non è selezionato nulla
&#x200B;* [Progetto] Le mappe trama possono essere danneggiate dopo la rimozione di risorse inutilizzate
&#x200B;* [Progetto] Danneggiamento delle risorse dopo la reimportazione o la esegue i baking di un&#39;immagine
&#x200B;* [Risorse] Quando si ricarica una risorsa, questa viene rimossa dai Preferiti
&#x200B;* [Importa] Impossibile importare risorse quando nel pannello delle risorse è presente l’indicazione &quot;Nessun risultato trovato&quot;
&#x200B;* [UI] In alcuni casi la freccia contestuale della barra degli strumenti non viene visualizzata
&#x200B;* [Substance] Il pulsante affiancato per i valori booleani non è supportato
&#x200B;* [Level] Etichetta del canale errata quando utilizzata nella maschera
&#x200B;* [Export]&#x200B;[glTF] i file glTF/GLB esportati da Painter non dispongono di un&#39;unità di dimensioni fisiche
&#x200B;* [Content] L’intensità del filtro Sfocatura è bloccata su 16
&#x200B;* [Content] L&#39;input dell&#39;immagine &quot;colore di destinazione&quot; del filtro Corrispondenza colori non è visibile

<b>Problemi noti:</b>

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Arresto anomalo]&#x200B;[Linux] con Linux Wayland su AMD quando si trascina e si rilascia la risorsa nella Pila livelli
&#x200B;* [Arresto anomalo]&#x200B;[Mac] Modifica del valore di filtro anisotropo nel sistema operativo Monterey
&#x200B;* [Arresto anomalo] Exr utilizzato come input dell&#39;immagine
&#x200B;* [Arresto anomalo] Utilizzo di una mappa dell&#39;ambiente a 16 K
&#x200B;* [Annullamento automatico] Problema di interfaccia utente per il controllo della densità del testo
&#x200B;* [Regressione]&#x200B;[UI] Il menu di scelta rapida è troppo piccolo sullo schermo hd
&#x200B;* [Python] Arresto anomalo di esportazione dell’USD attivato da TextureStateEvent
&#x200B;* [QoL] Se si trascina una risorsa Alpha in modalità decalcomania, viene creata una Proiezione UV nella maschera

### 9.0.1

Data di pubblicazione: <b>2023/09/19</b>
Riepilogo: <b>Versione del bug minore con diversi miglioramenti</b>

<b>Aggiunto:</b>

&#x200B;* [Import] Impostare la posizione di importazione predefinita nella finestra di importazione
&#x200B;* [Modalità di Esegue i baking] Consente di ripristinare i parametri ai valori predefiniti
&#x200B;* [Eseguo i baking] Imposta la risoluzione di eseguo i baking su pittura durante la creazione di un progetto
&#x200B;* [Simmetria] Separa il manipolatore specifico della simmetria dalla scelta rapida da tastiera Q
&#x200B;* [Menu] Aggiungi l&#39;opzione &quot;show log&quot; nel menu della Guida
&#x200B;* [Finestra di visualizzazione] Miglioramento della velocità di rendering delle ombre
&#x200B;* [Substance] Aggiorna il motore alla versione 9.0.1
&#x200B;* [Gestione colore] Il file di configurazione OCIO può avere qualsiasi tipo di estensione
&#x200B;* [Assets] La risorsa Sbsar con utilizzo &quot;decalcomania&quot; deve essere impostata automaticamente su proiezione alterazione
&#x200B;* [Tracciato] Visualizza un messaggio quando tenti di interagire con lo strumento Tracciato mentre l&#39;interfaccia utente e il widget sono nascosti

<b>Corretto:</b>

&#x200B;* [Arresto anomalo] Alt + trascinamento sul pannello Tracciato
&#x200B;* [Importa risorse] arresto anomalo casuale durante la rimozione delle risorse da importare
&#x200B;* Arresto anomalo durante l&#39;importazione di un file GLB compresso
&#x200B;* Problema durante la pittura su trame che condividono UV
&#x200B;* Flash di trama nero durante il ricalcolo o il caricamento della cache
&#x200B;* [Proprietà] Il menu di scelta rapida, accessibile facendo clic con il pulsante destro del mouse per reimpostare i parametri, non viene visualizzato nei menu a discesa
&#x200B;* [Level] Cursori di input bloccati dal livello precedente
&#x200B;* [AMD]&#x200B;[Sparse] Opzione SVT se attivata genera artefatti
&#x200B;* [Proiezione]&#x200B;[Altera] Arresto anomalo quando si fa doppio clic sui vertici
&#x200B;* [Path] Interfaccia utente e percorso visibili in modalità di esegue i baking
&#x200B;* [AMD] Texture persa durante la riproduzione con visibilità
&#x200B;* [Sparsa] Risoluzione troppo bassa quando si ruota la trama

<b>Problemi noti:</b>

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

### 9.0.0

Data di pubblicazione: <b>2023/06/20</b>
Riepilogo: <b>Versione principale con Pittura lungo il percorso che consente curve 3D, nuovi materiali di base e pulizia dei materiali legacy e nuovi predefiniti per curve 3D</b>

<b>Aggiunto:</b>

&#x200B;* [Tracciato] Strumento Aggiungi nuovo disegno lungo tracciato
&#x200B;* [Tracciato] Aggiungi una scelta rapida vuota per lo strumento tracciato
&#x200B;* [Path] Consente di aggiungere nuovi punti a un percorso esistente
&#x200B;* [Path] Aggiungi collegamento per uscire dalla creazione del percorso corrente
&#x200B;* [Tracciato] Consente di modificare le proprietà del pennello per i tracciati
&#x200B;* [Tracciato] Regolare automaticamente le tangenti durante il posizionamento di un punto
&#x200B;* [Path] Ricalcolare le tangenti quando si sposta un punto
&#x200B;* [Tracciato] Agganciare i punti appena creati alla superficie di una trama
&#x200B;* [Path] Consente di modificare la pressione per vertice
&#x200B;* [Path] Regola la pressione del punto appena creato dai punti vicini
&#x200B;* [Tracciato] Consenti di convertire i punti in punti morbidi/d&#39;angolo (interruzione tangente)
&#x200B;* [Path] Consente di spostare immediatamente un punto appena aggiunto
&#x200B;* [Path] Consente di rimuovere punti dal percorso esistente
&#x200B;* [Tracciato] Consente di invertire la direzione di un tracciato
&#x200B;* [Path] Consente di selezionare un percorso nella finestra della vista
&#x200B;* [Tracciato] Consente di selezionare punti di tracciato con selezione
&#x200B;* [Path] Introduci le scelte rapide da tastiera CTRL-A per selezionare tutti i punti di un tracciato
&#x200B;* [Path] Consenti di chiudere il percorso
&#x200B;* [Path] Consenti di specificare l&#39;asse del tracciato verso l&#39;alto in Proprietà
&#x200B;* [Path] Aggiungere un menu di controllo dei vertici alla barra degli strumenti contestuale
&#x200B;* [Tracciato] Introdurre le modalità di disegno/cancellazione/sfumino allo strumento tracciato
&#x200B;* [Path] Crea un feedback visivo per i tracciati nella finestra della vista
&#x200B;* [Path] Aggiungi un indicatore visivo per la direzione del tracciato
&#x200B;* [Path] Aggiungere un thickness di linee alle impostazioni di visualizzazione del percorso
&#x200B;* [Path] Consenti di nascondere l&#39;interfaccia utente dei percorsi
&#x200B;* [Tracciato] Aggiungi il pannello Tracciato per elencare i tracciati del livello attualmente selezionato
&#x200B;* [Tracciato] Aggiungi un feedback visivo quando si passa il cursore su un tracciato nel pannello Tracciato
&#x200B;* [Tracciato] Visualizza il pannello dei tracciati ogni volta che è selezionato lo strumento Tracciato
&#x200B;* [Tracciato] Consente di rinominare, eliminare, copiare, tagliare, duplicare il tracciato nel pannello Tracciato
&#x200B;* [Path] Visualizza un messaggio quando si tenta di interagire nella finestra della vista 2D con lo strumento Tracciato
&#x200B;* [Library] Integrazione di nuovi contenuti (strumenti e materiali di base di percorso)
&#x200B;* [Tratti dinamici] Aggiungi proprietà distanza per tratti dinamici
&#x200B;* [Tratti dinamici] Aggiungere dimensioni e proprietà di spaziatura ai tratti dinamici
&#x200B;* [Tratti dinamici] Aggiungi proprietà inizio/metà/fine per tratti dinamici
&#x200B;* [Python]&#x200B;[USD] Esposizione dei parametri di configurazione del progetto per il formato USD
&#x200B;* [Python]&#x200B;[USD] Esposizione dei parametri di creazione dei progetti per il formato USD
&#x200B;* [Export]&#x200B;[USD] Aggiungi le informazioni sul percorso del progetto all’interno del file USD esportato
&#x200B;* [GLTF] Aggiorna texture nella libreria durante il ricaricamento di un file GLTF
&#x200B;* [Shader] Ridurre gli artefatti di giuntura per Isole UV con orientamento diverso
&#x200B;* [Engine] Aggiornamento alla versione 9.0 del motore di Substance

<b>Corretto:</b>

&#x200B;* [Importa] Alcuni GLB con texture non ricevono texture in Painter
&#x200B;* [AMD] Artefatti sui bordi per tutti i riempimenti di proiezione 3D
&#x200B;* [Engine] Le Texture si interrompono quando si attiva o disattiva la visibilità del livello
&#x200B;* Le Texture di [Engine] sono vuote in alcuni punti quando si cambia il metodo di fusione
&#x200B;* [Motore] In alcuni casi, Texture/Proiezione è la modalità di alterazione vuota
&#x200B;* [Iray] Iterazione reimpostata su 0 durante il salvataggio del rendering
&#x200B;* [Registro] Messaggio di errore USD quando si esegue File > Nuovo

<b>Problemi noti:</b>

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Pila livelli] Sorgente di input non salvata per livello

## Versione 8

### 8.3.1

Data di pubblicazione: <b>2023/04/27</b>

<b>Aggiunto:</b>

&#x200B;* [Modalità di Esegue i baking] Aggiungi (vuota) una scelta rapida da tastiera per mostrare/nascondere la visualizzazione della finestra della vista
&#x200B;* [Modalità di Eseguita i baking] Mostra sempre Low Poly quando si utilizza il pulsante &quot;Nascondi trame eseguite i baking&quot;
&#x200B;* [Modalità di Esegue i baking] Mostra suffisso per corrispondenza per nome in base al set di texture corrente
&#x200B;* [Import] Aggiungi supporto per file binari GLTF (glb)
&#x200B;* [Elenco set di texture] Menu Aggiungi per selezionare o creare istanze shader
&#x200B;* [Elenco set di texture] Consente di modificare rapidamente il set di texture e la risoluzione delle Porzioni UV
&#x200B;* [Dimensioni fisiche] Migliorare il comportamento del manipolatore quando si utilizza dimensioni fisiche in Proiezione UV
&#x200B;* [UI] Riporta &quot;Salva con nome&quot; nel menu principale File
&#x200B;* [UI] Salva selezione vista (solo 2D, solo 3D, entrambi) nel layout dell&#39;interfaccia utente
&#x200B;* [USD] Messaggio di errore meno vago alla creazione del progetto con forme USD non supportate
&#x200B;* [Python] Aggiungi eventi di eseguita i baking per seguire lo stato di Eseguita i baking
&#x200B;* [Python] Consenti di annullare un eseguo i baking
&#x200B;* [Python] Esporta &quot;In base al modello di output&quot; per il tipo di file e la profondità di bit nell&#39;esportazione
&#x200B;* [Python] Tempo di aggiornamento di Exposé per TextureStateEvent.Update

<b>Corretto:</b>

&#x200B;* [Arresto anomalo] arresto anomalo raro alla chiusura di un progetto
&#x200B;* [Arresto anomalo] [Eseguo i baking] Attiva la sincronizzazione della mappa della trama con il Height o la curvatura su un progetto specifico
&#x200B;* [Arresto anomalo]&#x200B;[Scripting] Arresto anomalo quando si aggiunge un materiale dopo la creazione dell’istanza shader
&#x200B;* [Modalità di Eseguita i baking] L’intensità di AO in materiale neutro non ha effetto
&#x200B;* [Modalità cottura] Arresto anomalo quando si passa alla modalità cottura prima che il modello venga caricato
&#x200B;* [Modalità di cottura] Messaggio di errore mancante nella scheda Processo di cottura
&#x200B;* [Modalità cottura] Le impostazioni del materiale neutro non hanno effetto dopo la reimportazione di una trama
&#x200B;* [Modalità cottura] Il separatore della finestra della vista viene salvato globalmente e non per modalità
&#x200B;* [Modalità Eseguita i baking] Problema di visualizzazione: la normale media non modifica la superficie della gabbia
&#x200B;* [Gestione colore] L&#39;impostazione Rileva automaticamente spazio colore è disattivata quando è presente OCIO env var
&#x200B;* [Contenuto] Il filtro Contorno maschera contiene artefatto con input height
&#x200B;* [Contenuto] Il cursore dell’intensità del filtro sfocatura Pendenza è bloccato su 1,0
&#x200B;* [Interop] Impossibile creare il progetto con GLTF da Sampler
&#x200B;* [Pila livelli] Il valore dell&#39;Affiancamento di proiezione non viene aggiornato correttamente con manipolatore
&#x200B;* [Linux] Scostamento tra la penna grafica del tablet e il cursore con HDPI superiore al 100%
&#x200B;* [Python] Arresto anomalo di reimportazione di una trama dopo la creazione di un progetto
&#x200B;* [Substance] I rumori 3D vengono interrotti dopo la reimportazione di una trama
&#x200B;* [Porzioni UV] Lo scostamento per la Proiezione UV è bloccato su 1
&#x200B;* [Finestra vista] Il feedback visivo delle linee rette non è più visibile
&#x200B;* [Novità] Ritorno riga errato sui titoli delle funzioni

<b>Problemi noti:</b>

&#x200B;* [Importa] Alcuni GLB con texture non ottengono texture in Painter

### 8.3.0

*(Rilasciato: 10 gennaio 2023)*
Riepilogo: <b>Versione principale con nuova modalità di esegue i baking, nuova importazione ed esportazione di file USD e supporto di dimensioni fisiche per Proiezione UV</b>

<b>Aggiunto:</b>

&#x200B;* [Modalità cottura] Nuova modalità di cottura dedicata al processo di cottura al forno
&#x200B;* [Modalità cottura] Imposta la scelta rapida per passare alla modalità di cottura su F8
&#x200B;* [Modalità di Esegue i baking] Pulsante Aggiungi inizio e Annulla esegue i baking nella finestra della vista
&#x200B;* [Modalità cottura] Aggiungete la selezione di cottura al forno nell&#39;elenco Set di texture
&#x200B;* [Modalità di Esegue i baking] Aggiungere una nuova finestra Baker mappa trama per selezionare i baker
&#x200B;* [Modalità cottura] Aggiungere una nuova finestra Impostazioni mappa trama per modificare le impostazioni di cottura
&#x200B;* [Modalità di Esegue i baking] Aggiungere una nuova finestra Log di Esegue i baking per seguire la procedura di esegue i baking
&#x200B;* [Modalità cottura] Aggiungere parametri di cottura e annullare le azioni alla finestra della cronologia
&#x200B;* [Modalità cottura] Aggiungere breadcrumbs in Impostazioni mappa trama
&#x200B;* [Modalità cottura] Aggiungere miniature di mappe trama nella finestra Pannelli mappe trama
&#x200B;* [Modalità cottura] Aggiungere il menu comprimibile delle impostazioni di visualizzazione nella finestra della vista 3D
&#x200B;* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama High-Poly
&#x200B;* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama della gabbia e il wireframe
&#x200B;* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare/nascondere la trama a basso poli
&#x200B;* [Modalità cottura] Aggiungi impostazione di visualizzazione per mostrare bordi netti senza giunture UV come errori
&#x200B;* [Modalità cottura] Informate nella finestra della vista sugli errori di mesh e di cottura se il registro di cottura non è visibile
&#x200B;* [Modalità cottura] Aggiungi azione per sincronizzare le impostazioni del fornaio tra tutti i set di texture

  Nella finestra Pannelli mappa trama, ogni panettiere (così come le impostazioni comuni) può essere sincronizzato tra set di texture facendo clic sull&#39;icona di collegamento accanto al nome. Questa azione consente di aprire una finestra che consente di selezionare quali set di texture condivideranno gli stessi parametri.

&#x200B;* [Modalità cottura] Aggiungere azioni per copiare e incollare le impostazioni del fornaio

  Nella finestra Pannelli mappa trama sono disponibili le azioni per copiare e superare le impostazioni di ogni panettiera tra i set di texture, tramite il menu dedicato nella parte superiore della finestra o il menu contestuale, accessibile facendo clic con il pulsante destro del mouse.

&#x200B;* [Modalità di cottura] Pulsante Aggiungi nel registro di cottura per passare da un errore alle impostazioni corrette

  Quando un fornaio non va a buon fine o una trama non viene caricata correttamente, nel Registro forni viene visualizzato un messaggio di errore. Un pulsante accanto al messaggio consente di modificare la finestra Impostazioni cassette e mappe trama per visualizzare le relative impostazioni. In questo modo è possibile isolare più facilmente la fonte di un problema per poterlo risolvere.

&#x200B;* [Modalità cottura] Aggiungete menu per gestire set di texture e selezioni di forni

  Nelle finestre &quot;Set di texture&quot; e &quot;Mesh Map Bakers&quot; è stato aggiunto un menu di azioni che permette di copiare e invertire le selezioni.

&#x200B;* [Modalità cottura] Dividi elenco di selezione forni per set di texture
&#x200B;* [Modalità cottura] Dividere le impostazioni comuni per set di texture
&#x200B;* [Modalità cottura] Carica maglie ad alto poligono e gabbia senza bloccare l&#39;interfaccia
&#x200B;* [Modalità cottura] Utilizzare la barra di avanzamento della finestra della vista per visualizzare il caricamento della trama
&#x200B;* [Modalità di cottura] Aggiungere lo stato di caricamento della trama nel registro di cottura
&#x200B;* [Modalità cottura] Consente di ruotare la trama nella finestra della vista durante la cottura
&#x200B;* [Modalità cottura] Imposta l&#39;ordine di cottura in base alla visibilità della finestra della trama corrente
&#x200B;* [Modalità cottura] Visualizza gabbia di cottura implicita nella finestra della vista

  Quando non si utilizza un file di mesh di gabbia personalizzato, viene generata e visualizzata una mesh di gabbia automatica nella finestra della vista. Le sue dimensioni saranno basate sul parametro Distanza frontale massima dalle impostazioni comuni di cottura al forno. La maglia della gabbia viene utilizzata per indicare la distanza di corrispondenza tra il poly basso e alto.

&#x200B;* [Modalità di cottura] Mostra elenco corrispondente di nomi di mesh per corrispondenza per nome nel registro di cottura
&#x200B;* [Modalità cottura] Usate materiale neutro per visualizzare il modello 3D nella finestra della vista
&#x200B;* [Modalità cottura] Disattiva il calcolo del motore in modalità cottura
&#x200B;* [Modalità cottura] Visualizza un avviso quando si esce dall’app mentre è in corso una cottura
&#x200B;* [Bakers] Aggiornamento delle etichette delle impostazioni di antialiasing

  I valori delle impostazioni di antialiasing sono stati rinominati &quot;Supersampling&quot; e con un numero moltiplicatore esplicito per chiarirne il comportamento.

&#x200B;* [Bakers] Aggiornate bakers alla versione 2.5.7.
&#x200B;* [USD] Importare ed esportare file Universal Scene Description (USD)
&#x200B;* [USD] Aggiungere le opzioni USD alla finestra Nuovo progetto quando si seleziona un file USD
&#x200B;* [USD] Aggiungi nuova finestra di selezione Ambito e Varianti

  Quando si importa un file USD, facendo clic sul pulsante Modifica nella finestra Nuovo progetto o Configurazione progetto è possibile selezionare la parte e le varianti di un file USD da importare.

&#x200B;* [USD] Opzione Aggiungi livelli di suddivisioni

  Quando create un nuovo progetto con un file di trama USD che contiene suddivisioni, è possibile selezionare il livello di suddivisioni utilizzando un cursore. Il progetto verrà creato con la trama suddivisa. Il livello può essere modificatore tramite Configurazione progetto.

&#x200B;* [USD] Importa mesh con skin USD in un fotogramma specifico

  Quando crei un nuovo progetto con un file di trama USD che contiene animazioni, è possibile selezionare il fotogramma utilizzando un cursore che riflette la sequenza temporale incorporata. Il fotogramma può essere modificatore tramite Configurazione progetto.

&#x200B;* [USD]&#x200B;[Esporta] Aggiungi un’opzione per esportare i file USD

  Nuova casella di controllo Esporta USD aggiunta alla finestra Esporta texture. Quando è selezionato, consente di esportare file USD e mappe texture utilizzando qualsiasi modello.

&#x200B;* [USD]&#x200B;[Esporta] Aggiungi il formato di file USD all’esportazione con trama
&#x200B;* [USD] Rinomina il predefinito di esportazione &quot;Rugosità metallo USD PBR&quot; esistente per renderlo più esplicito

  Il modello di esportazione USD precedentemente noto come &quot;Rugosità metallo USD PBR&quot; è ancora accessibile tramite Esporta texture > Modello di output > USDz (Apple AR).

&#x200B;* [Annullamento automatico] Aggiungi orientamento blocco per impacchettamento

  Nuova opzione per lo scorrimento automatico delle impostazioni che consente di mantenere l’orientamento delle Isole UV esistenti quando si utilizza la funzione di impacchettamento. È possibile accedervi da Nuovo progetto > Opzioni di annullamento automatico > Isola UV orientamento.

&#x200B;* [Dimensioni fisiche] Aggiungi impostazione per utilizzare automaticamente la Dimensioni fisiche nell’effetto/livello di riempimento

  È stata aggiunta una nuova opzione che consente di passare automaticamente alla scala dimensioni fisiche quando si utilizza un materiale con dimensioni fisiche incorporata. Può essere attivato per ogni progetto tramite Nuovo progetto o tramite Modifica > Configurazione progetto > Dimensioni fisiche > Converti il ridimensionamento del livello di riempimento in Dimensioni fisiche quando si assegnano i materiali.

&#x200B;* [Dimensioni fisiche] Esposizione dimensioni fisiche per Proiezione UV

  Il ridimensionamento delle dimensioni fisiche è ora disponibile per le Proiezioni UV: consente di ridimensionare automaticamente un materiale in base alla dimensioni fisiche di una trama. Può essere selezionata da Scala > Dimensioni fisiche nel livello di riempimento o nella finestra Proprietà effetti.

&#x200B;* [Scripting]&#x200B;[Python] Consenti di eseguire query sulla versione dell’applicazione
&#x200B;* [Scripting]&#x200B;[JavaScript] Aggiorna l’API in base ai nuovi parametri di baking
&#x200B;* [Scripting]&#x200B;[Python] Modulo Baking: modificare i parametri di baking
&#x200B;* [Scripting]&#x200B;[Python] Modulo Baking: avvia/annulla baking
&#x200B;* [Scripting]&#x200B;[Python] Modulo Baking: selezionare il metodo di curvatura
&#x200B;* [Scripting]&#x200B;[Python] Modulo Baking: selezione di panettieri/piastrelle uv
&#x200B;* [Scripting]&#x200B;[Python] Modulo Baking: sincronizzare le impostazioni baker su tutti i set di texture
&#x200B;* [SVT] Abilitazione del supporto hardware di tipo sparse sulle GPU AMD

  L’accelerazione hardware per il sistema Sparse Virtual Textures può ora essere abilitata con le GPU AMD. Questa impostazione viene attivata automaticamente nelle preferenze generali.

&#x200B;* [Proiezione] Rinomina parametri proiezione cilindrica

  Il parametro &quot;Cylinder Culling&quot; è stato rinominato &quot;Backface Culling&quot; per rappresentarne meglio l’azione. La descrizione associata è stata modificata di conseguenza.

&#x200B;* [Project] Salva la versione dell&#39;applicazione nel progetto e recuperala tramite script

  A partire dalla versione 8.2, la versione dell’applicazione viene ora memorizzata nel file spp durante il salvataggio.
  Questo numero di versione può essere recuperato con la funzione last\_saved\_substance\_painter\_version() nel modulo di progetto dell’API Python.
  Per i progetti realizzati prima della versione 8.2, il valore restituito sarà null.

&#x200B;* [Import] Migliorare i tempi generali di importazione dei modelli 3D

  Abbiamo migliorato il tempo generale di importazione delle trame. Ad esempio, la riduzione del tempo di attesa durante il caricamento di trame ad alto poli per la cottura al forno. Questa ottimizzazione si applica in particolare al caricamento di file OBJ.

<b>Corretto:</b>

&#x200B;* [Arresto anomalo] Modifica dei canali su un filtro con uno stack specifico
&#x200B;* [Mac]&#x200B;[M1] Arresto anomalo durante la creazione di un livello di riempimento e l&#39;uscita dal gruppo di livelli

  Questo problema può essere risolto eseguendo l’aggiornamento a Mac OS 13 (Ventura).

&#x200B;* [Scripting]&#x200B;[Python] Arresto anomalo quando si utilizza ui.add\_dock\_widget() con tipo errato
&#x200B;* [Baking] Messaggio di errore incompleto nel registro quando un baking non riesce
&#x200B;* [Baking] La memoria non viene liberata al termine della cottura
&#x200B;* [Engine] La cache delle texture non si aggiorna quando si modifica la visibilità degli effetti
&#x200B;* [Esporta] La vista 2D esporta una mappa casualmente uniforme
&#x200B;* [Progetto] Errore di allocazione della memoria durante il salvataggio del progetto con trama grande
&#x200B;* [Riquadro di visualizzazione] In alcuni casi, l’accesso automatico al contenuto causa artefatti durante l’uso del colore

<b>Problemi noti:</b>

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Pila livelli] Sorgente di input non salvata per livello

### 8.2.0

*(Rilasciato il 6 ottobre 2022)*
Riepilogo: **Versione principale con nuovi pannelli di onboarding (nuovo pannello di benvenuto e novità), esportazione in SBSAR, effetti per cartella, diversi miglioramenti per la qualità della vita e correzioni di bug.**

**Aggiunto:**

&#x200B;* [Onboarding] Pannello Onboarding per accogliere nuovi utenti

  È stata aggiunta una nuova schermata introduttiva quando i nuovi utenti CC aprono Painter per la prima volta.

&#x200B;* [Onboarding] Novità del pannello per migliorare la ricerca di nuove funzioni

  È stata aggiunta una nuova schermata Novità che mostra le principali nuove funzioni. Viene visualizzato automaticamente la prima volta che Painter viene aperto dopo un aggiornamento importante ed è nuovamente accessibile da Aiuto > Novità.

&#x200B;* [Onboarding] Rinomina il vecchio benvenuto in &quot;Schermata Home&quot;

  La vecchia schermata introduttiva è stata rinominata Schermata iniziale per evitare confusione con la nuova schermata introduttiva.

&#x200B;* [UI] Risoluzione dei problemi di ridimensionamento per schermi ad alto DPI

  È stato migliorato l’adattamento dell’interfaccia utente di Painter su schermi ad alta definizione con ridimensionamento personalizzato.

&#x200B;* [UI] Evitare messaggi di errore persistenti nell&#39;interfaccia utente

  I messaggi di errore dei progetti precedenti sono stati rimossi dalla barra di stato inferiore.

&#x200B;* [UI] Rielaborare il menu di salvataggio

  Le opzioni di salvataggio aggiuntive sono ora raggruppate in un sottomenu e alcune sono state rinominate per coerenza.

&#x200B;* [UI] Salvare ed esportare/condividere i layout dell’interfaccia utente

  Nel menu Finestra sono disponibili nuove azioni per salvare il layout dell&#39;interfaccia utente nei file e ricaricarli. I layout di disegno e rendering vengono salvati separatamente.
  A &quot;substance\_painter.ui&quot; sono state aggiunte varie funzioni per salvare, reimpostare e caricare anche i layout dell&#39;interfaccia utente.

&#x200B;* Aggiungere azioni di copia/incolla per i metodi di fusione/opacità di un livello

  È stata aggiunta la nuova voce &quot;Opzioni di fusione&quot; al menu di scelta rapida dei livelli. Consente di copiare e incollare il metodo di fusione e l’opacità di tutti i canali da un livello all’altro.

&#x200B;* Applicare il metodo di fusione/opacità a tutti i canali di un livello

  È stata aggiunta una funzionalità di clic con il pulsante destro del mouse al metodo di fusione e all’opacità dei livelli che consente di applicare a tutti i canali l’impostazione su cui si fa clic.

&#x200B;* Ricarica trama con una scelta rapida da tastiera (CTRL+MAIUSC+R)

  È stata aggiunta una scelta rapida da tastiera modificabile per ricaricare il file mesh con le ultime impostazioni disponibili. È possibile accedere a questa opzione anche da Modifica > Reimporta trama.

&#x200B;* Ripristina i parametri predefiniti di Substance

  È stato aggiunto un nuovo pulsante nelle proprietà nella parte inferiore delle risorse .sbsar che consente di ripristinare le impostazioni predefinite della risorsa.

&#x200B;* Ripristina pennello artistico ai valori predefiniti

  È stato aggiunto un nuovo menu nella sezione Pennello in Proprietà che consente di ripristinare il pennello di base predefinito.

&#x200B;* Fare clic con il pulsante destro del mouse per ripristinare i singoli parametri di Substance ai valori predefiniti

  È stata aggiunta la possibilità di ripristinare singoli parametri all&#39;interno di una risorsa .sbsar tramite clic con il pulsante destro del mouse.

&#x200B;* [Pannello Risorse] &quot;Blocca&quot; le risorse preferite da visualizzare sopra il pannello Risorse

  È stata aggiunta una nuova opzione di clic con il pulsante destro del mouse sulle risorse della libreria che consente di bloccarle come preferite nella parte superiore del pannello. Puoi anche visualizzare tutte le tue risorse preferite tramite Ricerche salvate.

&#x200B;* [Pannello Risorse] Elimina, ricarica e rinomina le risorse

  Sono state aggiunte le opzioni del menu di scelta rapida per eliminare, ricaricare e rinominare le risorse nella libreria utente. Vengono eliminati direttamente dal percorso della libreria sul disco e ricaricati dal percorso originale. Le risorse che fanno parte di un pacchetto come .abr o .sbsar non possono essere modificate singolarmente.

&#x200B;* [Selezione colore] Aggiungere metodi di fusione all’effetto Selezione colore
&#x200B;* [Serie di livelli] Aggiungi metodo di fusione e opacità ai filtri
&#x200B;* [Serie di livelli] Consenti valori di suddivisione in porzioni superiori a 128 per livelli di riempimento/effetti
&#x200B;* [Serie di livelli] Estremità cilindriche per la proiezione cilindrica nel livello di riempimento/effetto

  La proiezione cilindrica nelle proprietà del livello Riempimento ora ha l&#39;opzione per rimuovere le estremità dei cilindri.

&#x200B;* [Log] Visualizza un messaggio di errore se la parte mesh si trova in uno spazio negativo quando si tenta di creare un progetto di porzione UV

  È stato aggiunto un messaggio di errore più chiaro quando non è possibile creare un progetto di porzioni UV perché le parti UV si trovano in spazi negativi.

&#x200B;* [Progetto] Indica la versione nel messaggio di errore &quot;dati troppo recenti&quot; quando si apre un progetto

  Quando si apre un progetto troppo recente per l’applicazione, il messaggio di errore indica ora la versione del progetto per facilitare l’identificazione della versione corretta dell’applicazione.

&#x200B;* [Finestra vista] Consente di illuminare la trama da sotto

  È stato aggiunto un nuovo parametro di Allineamento ambiente in Impostazioni visualizzazione > Fotocamera > Impostazioni ambiente per allineare l’illuminazione della mappa ambiente alla videocamera quando è impostata su &quot;Locale&quot;.

&#x200B;* [Finestra vista] Visualizza R, G, B e Alpha nella finestra vista (modalità di visualizzazione solo)

  In Impostazioni schermo > Impostazioni finestra vista > Visualizzazione canali è disponibile una nuova impostazione Canali colore che consente di visualizzare solo il componente R, G, B o Alpha di un canale quando è attiva la modalità di visualizzazione singola.

&#x200B;* [Shader] Consenti di impostare i canali utente come RGBA negli shader di livello materiale

  Quando si imposta la configurazione dei canali dell’insieme di texture all’interno di uno shader per la creazione di livelli di materiale, è ora possibile specificare il formato del canale da deviare dal valore di default. In particolare, è possibile richiedere canali utente a colori invece che solo in scala di grigi.

&#x200B;* [Esporta] Consente di esportare texture come SBSAR

  Quando si esporta una texture tramite la finestra File > Esporta Texture, si può scegliere il formato di file SBSAR (Substance Archivio) per raggrupparla. Il contenuto del SBSAR dipende dal modello di output utilizzato.
  Il formato del file SBSAR può essere impostato anche nei predefiniti di esportazione. Quando si utilizza la configurazione ibrida (SBSAR + Altro formato), le texture che hanno come destinazione un SBSAR vengono raggruppate mentre le altre vengono esportate insieme.

&#x200B;* [Esporta] Opzione Esporta 16 bit per il formato di file EXR

  Quando si esportano file di texture EXR, ora è possibile scegliere tra 16f bit (Mezza Virgola mobile) o 32f bit (Virgola mobile) nella finestra Esporta Texture (sia per le impostazioni di esportazione che per i predefiniti di esportazione). I vecchi progetti e i vecchi predefiniti di esportazione verranno impostati per impostazione predefinita su 16 f bit per riflettere il vecchio comportamento.

&#x200B;* [Python] Aggiungi evento per sapere quando vengono modificati i set di texture

  Il nuovo &quot;substance\_painter.event.TextureStateEvent&quot; consente di sapere quando un insieme di texture è stato modificato a causa di un tratto di pittura, di un nuovo canale aggiunto o di un canale rimosso.

&#x200B;* [Python] Consenti di ottenere e impostare le risorse Mesh Map nelle impostazioni Texture Set

  Nel modulo &quot;substance\_painter.project&quot; sono state aggiunte nuove funzioni per ottenere e impostare le risorse per le mappe mesh. Queste funzioni possono essere utilizzate per aggiornare le mappe di trama a cui fanno riferimento le impostazioni del set di texture.

&#x200B;* [Plugin] Rimuovi l&#39;opzione per ottenere altri plug-in JS

  È stata rimossa l’opzione per ottenere i plug-in JavaScript poiché erano ospitati nel sito Web di condivisione obsoleto.

&#x200B;* [Content] Aggiungi nuovo modello Roblox ed esporta predefinito

  Sono stati aggiunti un nuovo modello di progetto Roblox &quot;Variante materiale&quot; e &quot;Aspetto superficie&quot; e un predefinito di esportazione per facilitare l’esportazione di texture PBR in Roblox. È possibile accedere al modello dalla finestra File > Nuovo progetto.

&#x200B;* Aggiornamento della Substance Engine alla versione più recente (8.6.3)
&#x200B;* [Steam] Versione ottimizzata per chipset Apple Silicon (Apple M1 / M2)

**Corretto:**

&#x200B;* Arresto anomalo quando si utilizza exr 16.000
&#x200B;* [Arresto anomalo] Ctrl Z Dopo l’eliminazione di un’istanza dello shader
&#x200B;* [Iray] IoR è bloccato su 1 per alcuni shader
&#x200B;* [Win]&#x200B;[Baking] Alcuni High-Poly non vengono caricati
&#x200B;* [Gestione colore] Nome dello spazio colore non corretto nell&#39;interfaccia utente con filtri
&#x200B;* [Python] Gli oggetti risorsa restituiti dalla funzione di importazione non hanno un tipo

  Quando si importava un pacchetto di Substance in Python, la funzione restituiva il pacchetto invece dei relativi grafici. Il modulo delle risorse ora fornisce funzioni e parametri per recuperare i grafici di un pacchetto di Substance.

**Problemi noti:**

&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Serie di livelli] Origine di input non salvata per livello
&#x200B;* [Pittura] L’anti-alias temporale provoca artefatti quando si dipinge in alcuni casi
&#x200B;* [Esporta] La vista 2D esporta una mappa casualmente uniforme

### 8.1.3

*(Rilasciato: 25 Agosto 2022)*
Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

&#x200B;* Aggiornamento a Iray SDK 1.6

**Corretto:**

&#x200B;* [Shader] Arresto anomalo con il vecchio shader difettoso
&#x200B;* [Livelli di materiale] I materiali possono scomparire quando si riapre un progetto

**Problemi noti:**

&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati
&#x200B;* [Serie di livelli] Origine di input non salvata per livello
&#x200B;* [Arresto anomalo] Ctrl Z Dopo l’eliminazione di un’istanza dello shader
&#x200B;* [Iray] IoR è bloccato su 1 per alcuni shader

### 8.1.2

*(Rilasciato: 19 luglio 2022)*
Riepilogo: **Versione bugfix secondaria**

**Aggiunto:**

&#x200B;* [Auto Unwrap] Nuova opzione &quot;Ottimizza per trame organiche&quot; per selezionare l&#39;algoritmo di segmentazione
&#x200B;* [Dimensioni fisiche] Opzioni di esposizione dell&#39;unità in Nuovo progetto e Configurazione progetto
&#x200B;* [Gestione colore] Usa visualizzazione monitor per impostazione predefinita quando si utilizza ACE
&#x200B;* [Gestione colore]&#x200B;[Python] Durante la creazione del progetto, tieni presente il file di predefiniti ACE env-var
&#x200B;* [Gestione colore] Reimposta le impostazioni di Gestione colore nella finestra Nuovo progetto quando la configurazione cambia
&#x200B;* [Gestione colore] Disattiva accesso alle impostazioni OCIO quando è presente env-var
&#x200B;* [Gestione colore] Aggiorna in modo sicuro le impostazioni ACE quando un parametro non esiste più
&#x200B;* Aggiornamento della Substance Engine alla versione 8.6.0
&#x200B;* [Esporta] Aggiungi nuovo predefinito di esportazione GLTF con supporto Spostamento
&#x200B;* [Scripting]&#x200B;[Python] Recupero delle informazioni sulle risorse (inclusi i metadati personalizzati)
&#x200B;* [Scripting]&#x200B;[Python] Aggiungi funzione all’elenco di query dei nomi mesh per set di texture
&#x200B;* [Content] Aggiungi un nuovo modello di fusione ed esporta predefinito

**Corretto:**

&#x200B;* [MacOS] Arresto anomalo all&#39;avvio di Iray in alcuni casi
&#x200B;* [Miniature] Le miniature dello shelf non vengono caricate correttamente
&#x200B;* Più canali UV vengono ignorati
&#x200B;* [Annullamento automatico] Calcolo non necessario durante la divisione di isole lunghe
&#x200B;* [Srotolamento automatico] Opzione per evitare isole allungate non considerata
&#x200B;* [Annullamento automatico] Perdita di dati aggiuntivi (colori dei vertici) durante il reinserimento degli UV
&#x200B;* [UI] Barra di scorrimento orizzontale nella finestra delle proprietà quando Gestione colore è abilitato
&#x200B;* [Gestione colore] Nelle configurazioni OCIO manca il ruolo substance\_3d\_painter\_standard\_srgb
&#x200B;* [Generator] Utilizzo errato dei dati utente &quot;disabilitato&quot;
&#x200B;* [Gestione colore] Il menu a discesa Spazio colore &quot;Non compatibile&quot; non deve essere selezionabile
&#x200B;* [Gestione colore]&#x200B;[Shader] l&#39;override sRGB definisce non funziona più
&#x200B;* [Generator] Utilizzo errato dei dati utente &quot;disabilitato&quot;
&#x200B;* [Pila livelli] Anteprime interrotte con progetti di Porzione UV
&#x200B;* La documentazione API di [Shader] non è completamente aggiornata con le Normali incurvate
&#x200B;* [Export]&#x200B;[Interoperability] Impossibile inviare a Stager con caratteri speciali
&#x200B;* [Contenuto] Alcune miniature dei pennelli predefiniti sono vuote o troppo scure

**Problemi noti:**

&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati
&#x200B;* [Pila livelli] La sorgente di input non viene salvata per livello
&#x200B;* [Arresto anomalo] Ctrl Z Dopo l’eliminazione di un’istanza shader
&#x200B;* [Iray] IoR è bloccato su 1 per alcuni shader
&#x200B;* [Shader] Arresto anomalo con vecchio shader difettoso

### 8.1.1

*(Rilasciato il 28 giugno 2022)*
Riepilogo: **Hotfix per le versioni secondarie**

**Aggiunto:**

&#x200B;* [Pila livelli] Il clic Alt sulla maschera non deseleziona più gli effetti

**Corretto:**

&#x200B;* [Arresto anomalo] Apertura di un vecchio progetto salvato in modalità di visualizzazione Solo
&#x200B;* [Arresto anomalo] Eliminare un Generatore nelle proprietà
&#x200B;* [Impostazioni set di texture] Il mixaggio normale/Occlusione ambientale e il height ai metodi normali non funzionano
&#x200B;* [Esporta] Esporta texture utilizzando il riempimento diffusione esegue il rendering delle mappe nere

**Problemi noti:**

&#x200B;* [MacOS] Arresto anomalo all&#39;avvio di Iray su Monterey
&#x200B;* [Anteprima miniatura] Le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
&#x200B;* [Gestione colore] Le conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

### 8.1.0

*(Rilasciato il 7 giugno 2022)*
Riepilogo: **Versione principale con supporto ICC, ridimensionamento del materiale in base ai dati della dimensioni fisiche, nuovi baker, miglioramenti del contagocce colore e una serie di contenuti aggiuntivi**

**Aggiunto:**

&#x200B;* [Gestione colore] Aggiungi supporto per profili ICC con Adobe Color Engine (ACE)
&#x200B;* [Gestione colore] Aggiungi il supporto per &quot;Adobe 98 RGB&quot; come spazio colore di lavoro per ICC
&#x200B;* [Gestione colore] Consente di configurare le impostazioni ACE/ICC tramite un file di configurazione
&#x200B;* [Gestione colore] Consente di inserire valori di colore lineari nel Selettore colore con la modalità Legacy
&#x200B;* [Gestione colore] Consente di specificare il profilo colore utilizzato per la selezione del colore al di fuori dell&#39;interfaccia utente
&#x200B;* [Gestione colore] Ricordare l&#39;ultimo valore di visualizzazione scelto nella finestra della vista
&#x200B;* [Gestione colore]&#x200B;[Substance] Fate funzionare correttamente i generatori/filtri con la Gestione colore
&#x200B;* [Gestione colore]&#x200B;[Substance] Aggiungi nuove parole chiave di esclusione dello spazio colore $working e $standardsrgb
&#x200B;* [Dimensioni fisiche]&#x200B;[Engine] Estrai informazioni dimensioni fisiche dalla trama
&#x200B;* Calcolo Dimensioni fisiche [Dimensioni fisiche]&#x200B;[Engine]
&#x200B;* [Dimensioni fisiche] Esporre le opzioni per utilizzare dimensioni fisiche nell&#39;interfaccia utente
&#x200B;* [Dimensioni fisiche] Aggiungere gli helper visivi nella finestra della vista
&#x200B;* [Esegue i baking] Aggiungi baker di Height
&#x200B;* [Esegue i baking] Aggiungi baker di Normali incurvate
&#x200B;* [Esegue i baking] Aggiungi baker di opacità
&#x200B;* [Contagocce] Nuova anteprima del contagocce colore accanto al mouse e al colore gestito
&#x200B;* [Contagocce] Il pannello Selettore colore riappare nell&#39;ultima posizione quando viene riaperto
&#x200B;* [Contagocce] Una nuova icona per il Selettore materiale
&#x200B;* [Contagocce] Il colore gestisce l&#39;anteprima del canale del selettore colore
&#x200B;* [Contagocce] Aggiungete al contagocce la funzionalità clic per selezionare
&#x200B;* [Contagocce] Il selettore di materiali non attiva più i canali non attivi
&#x200B;* [Contagocce] Consenti l’uso del contagocce con una scelta rapida da tastiera
&#x200B;* [Contagocce] Il contagocce preleva il canale pertinente, se applicabile
&#x200B;* [Contagocce] Quando si entra in modalità Selettore colore, tutte le scelte rapide vengono disattivate
&#x200B;* [Contagocce] Rimuovi la selezione automatica del campo esadecimale
&#x200B;* [Contagocce] Non chiudere il pannello quando si utilizza il selettore di materiale
&#x200B;* [Contagocce] Nuovo stato disabilitato quando il canale non è disponibile per la selezione
&#x200B;* [Esporta] Aggiungi attributo tangente all&#39;esportazione glTF
&#x200B;* Aggiorna Substance Engine alla versione 8.4
&#x200B;* Aggiorna Scorrimento automatico a 0.9.0
&#x200B;* Esegui l’aggiornamento a Qt 5.15.8
&#x200B;* Aggiornamento a Python 3.9
&#x200B;* [Shader] Aggiunta del supporto per l&#39;ombreggiatura della Normali incurvate
&#x200B;* [MacOS] Supporto di 3DConnection SpaceMouse
&#x200B;* [Python] Documentazione della versione Python utilizzata nell’API
&#x200B;* [Content] Aggiungi 6 nuovi rumori 3D con 105 predefiniti
&#x200B;* [Content] 20 nuove mappe di grunge e 2 modelli di pieghe di tessuto
&#x200B;* [Content] Aggiornamento del predefinito di esportazione &quot;Mesh maps&quot; per utilizzare nuovi baker
&#x200B;* [Contenuto] I filtri Sfoca Pendenza e Altera dipendono dalla risoluzione del set di texture
&#x200B;* [Content] Aggiorna i progetti di esempio per utilizzare i tre nuovi baker

**Corretto:**

&#x200B;* [glTF] Impossibile aprire glTF con carattere speciale
&#x200B;* [Engine] Artefatti con anisotropia e SVT disattivati
&#x200B;* [MacOS]&#x200B;[M1] I materiali avanzati non vengono visualizzati correttamente
&#x200B;* [Elaborazione trama] Impossibile importare trame da Modeler
&#x200B;* [UI] Barra di scorrimento orizzontale nella nuova finestra del progetto con la Gestione colore attivata
&#x200B;* [Gestione colore] Valore dello spazio di lavoro mancante nel selettore colore con alcune configurazioni OCIO
&#x200B;* [Gestione colore] L’anteprima del pennello nella finestra della vista non è sottoposta alla gestione del colore
&#x200B;* [SpaceMouse] Il pivot non viene aggiornato immediatamente con la modifica dello stato attivo e a volte fuori dal modello
&#x200B;* [Export]&#x200B;[USD] I file USD esportati hanno una struttura errata
&#x200B;* [USD] Problema di Occlusione ambientale durante l’esportazione
&#x200B;* [Content] Aggiorna la trama della miniatura in modo che corrisponda al progetto di esempio Preview Sphere

**Problemi noti:**

&#x200B;* Esporta le texture utilizzando il riempimento di diffusione esegue il rendering delle mappe nere
&#x200B;* Il mixaggio delle Occlusioni normali/ambientali è interrotto
&#x200B;* [MacOS] Arresto anomalo all&#39;avvio di Iray in alcuni rari casi
&#x200B;* [Anteprima miniatura] Le miniature semplificate non vengono aggiornate quando si utilizza un ancoraggio
&#x200B;* [Gestione colore] Le conversioni dello spazio colore HDR con ACE su Linux producono colori bloccati

## Versione 7

### 7.4.3

*(Rilasciato: 11 aprile 2022)*
Riepilogo: **Bugfix con supporto di 3Dconnection SpaceMouse nel viewport 2D**

**Aggiunto:**

&#x200B;* [SpaceMouse] Supporto di 3DConnection SpaceMouse nel viewport 2D

**Corretto:**

&#x200B;* [Selettore colore] Impossibile scrivere in un campo esadecimale
&#x200B;* [Gestione colore] Le risorse utilizzate in modalità di proiezione non sono sottoposte alla gestione del colore nella sovrapposizione
&#x200B;* [Gestione colore] Gli errori non vengono segnalati nel registro
&#x200B;* [SpaceMouse] Rimuovere un messaggio di errore generico se l&#39;utente non dispone di un oggetto SpaceMouse
&#x200B;* [SpaceMouse] Quando si carica un progetto, il punto fulcro è sempre nascosto
&#x200B;* [Baker] L’impostazione &quot;Normali medi&quot; non ha effetto nei progetti di Porzione UV
&#x200B;* [Porzione UV] Le sovrapposizioni dei riquadri uv inattivi scompaiono quando si ricarica la trama con riquadri diversi
&#x200B;* [Scripting]&#x200B;[Python] Lo scripting remoto è interrotto
&#x200B;* [Scripting]&#x200B;[Python] Diversi canali non possono essere interrogati dall’API e si verifica un errore
&#x200B;* [Scripting]&#x200B;[Python] Arresto anomalo quando si utilizza l&#39;evento ProjectEditionEntered
&#x200B;* [Scripting]&#x200B;[Python] Arresto anomalo durante la chiamata di get\_active\_stack()

**Problemi noti:**

&#x200B;* 3Dconnection SpaceMouse non supportato su MacOS
&#x200B;* [UI] Barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella nuova finestra del progetto
&#x200B;* [Mac M1] I Materiali avanzati non vengono visualizzati correttamente

### 7.4.2

*(Rilasciato: 8 marzo 2022)*
Riepilogo: **Correzione rapida con supporto di 3Dconnection SpaceMouse e miglioramenti alla gestione del colore (OCIO)**

**Aggiunto:**

&#x200B;* [SpaceMouse]&#x200B;[Windows] Supporto di 3Dconnection SpaceMouse nel riquadro di visualizzazione 3D per la navigazione
&#x200B;* [SpaceMouse]&#x200B;[Windows] Scelte rapide/tasti di base per i modelli Pro ed Enterprise di SpaceMouse nella finestra della vista 3D
&#x200B;* [SpaceMouse]&#x200B;[Windows] Icona del centro di rotazione dedicato nella finestra della vista 3D
&#x200B;* [Gestione colore] Utilizzare i ruoli della configurazione OCIO per modificare le impostazioni predefinite
&#x200B;* [Gestione colore] Gestione colore gestisce la finestra delle proprietà per i widget colore
&#x200B;* [Gestione colore] Gestione colore gestisce la finestra delle proprietà per l’anteprima del materiale
&#x200B;* [Gestione colore] Campioni di gestione colore nel selettore colore
&#x200B;* [Gestione colore] Aggiungi un’impostazione per definire lo spazio colore sRGB standard
&#x200B;* [Gestione colore] Aggiungere lo spazio colore sRGB standard dalla configurazione OCIO nel selettore colore Elenco selettori visualizzazione
&#x200B;* [Gestione colore] Miglioramenti per il menu di esclusione dello spazio colore
&#x200B;* [Gestione colore] Consente di ignorare lo spazio colore della mappa dell&#39;ambiente in Impostazioni schermo
&#x200B;* [Gestione colore] Disegna sfumature selettore colore in base alla visualizzazione corrente
&#x200B;* [Gestione colore] Per impostazione predefinita, Blocca i valori HDR nell’editor colori
&#x200B;* [Gestione colore] Usa passthrough (senza spazio colore) per i filtri in modalità Legacy
&#x200B;* [Gestione colore] Limita la visualizzazione delle sfumature nell&#39;editor colori in base all&#39;intervallo [0-1]
&#x200B;* [Gestione colore] Nascondi selettore visualizzazione nel selettore colore in modalità Legacy
&#x200B;* [Gestione colore] Rendi il selettore colore un campo esadecimale sempre nello spazio colore sRGB
&#x200B;* [Gestione colore] Disattiva il selettore colore Visualizza il menu a discesa per i canali dati
&#x200B;* [Ottimizzazione] La griglia di alterazione ricalcola solo le porzioni UV coperte
&#x200B;* [Esporta] Consente di esportare progetti di Porzione UV per Sketchfab, USD e glTF
&#x200B;* [Scripting]&#x200B;[Python] Consente di modificare la funzione di mappatura tonale

**Corretto:**

&#x200B;* [Sketchfab] L&#39;aggiornamento del modello esistente comporta la creazione di un nuovo modello
&#x200B;* [Sketchfab] Arresto anomalo durante la ricerca di un modello aggiornato in precedenza
&#x200B;* Arresto anomalo durante l’esportazione nell’USD
&#x200B;* Arresto anomalo durante la creazione di una nuova istanza shader nella maschera di geometria o quando la geometria è nascosta
&#x200B;* arresto anomalo di [Finestra Importa risorsa] quando si modifica il tipo di risorse importate
&#x200B;* Le mappe con trama normale vengono invertite se utilizzate in Pila livelli
&#x200B;* [Substance] Metodo di fusione dei dati utente non preso in considerazione
&#x200B;* [Gestione colore] Le bitmap con spazio cromatico nel nome del file vengono importate come sequenze di Porzioni UV
&#x200B;* [Gestione colore] Gli output con gestione del colore del grafico a Substance si trovano in uno spazio colore errato
&#x200B;* [Gestione colore] Lo strumento Riempimento poligonale visualizza il colore errato
&#x200B;* [Gestione colore] Il tonemapper ACE viene applicato ai canali in modalità Solo
&#x200B;* [Gestione colore] L’illuminazione della sfera di anteprima dello strumento non è gestita dal colore
&#x200B;* [Gestione colore]&#x200B;[Esporta] Le mappe convertite applicano una conversione errata
&#x200B;* [Scripting]&#x200B;[Python]&#x200B;[Gestione colore] I progetti creati con la variabile di ambiente template &amp; OCIO sono in modalità Legacy
&#x200B;* [Scripting]&#x200B;[Python] Impossibile utilizzare la funzione di valutazione JavaScript all&#39;avvio
&#x200B;* [Offerta Adobe 3D] Impossibile avviare Painter quando si utilizzano impostazioni internazionali con lingue non supportate per impostazione predefinita

**Problemi noti:**

&#x200B;* 3Dconnection SpaceMouse non supportato su MacOS
&#x200B;* [UI] Barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella nuova finestra del progetto
&#x200B;* [Baker] L’impostazione &quot;Normali medi&quot; non ha effetto nei progetti di Porzione UV
&#x200B;* [Mac M1] I Materiali avanzati non vengono visualizzati correttamente
&#x200B;* [Gestione colore] Le risorse utilizzate in modalità di proiezione non sono sottoposte alla gestione del colore nella sovrapposizione
&#x200B;* [Selettore colore] Impossibile scrivere in un campo esadecimale

### 7.4.1

*(Rilasciato: 14 dicembre 2021)*
Riepilogo: **Correzione rapida con miglioramenti alla gestione del colore**

**Aggiunto:**

&#x200B;* [Gestione colore] Usa ruolo dati nei nomi file esportati
&#x200B;* [Gestione colore] Per impostazione predefinita, espandi la sezione Gestione colore quando nelle finestre Nuovo progetto e Impostazioni progetto è selezionato OCIO
&#x200B;* [Gestione colore] Aggiungere il tonemapper ACE in modalità legacy
&#x200B;* [Gestione colore] Regolare le impostazioni di configurazione predefinite
&#x200B;* [Gestione colore]&#x200B;[Esporta] Riempi $colorSpace nei nomi dei file per i canali dati
&#x200B;* [Esporta] Esporta progetto di Porzione UV in Stager
&#x200B;* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
&#x200B;* [Interoperabilità] Consente di inviare un progetto Porzione UV a Stager

**Corretto:**

&#x200B;* [MacOS]&#x200B;[Arresto anomalo] Painter non inizia con Catalina
&#x200B;* [Gestione colore]&#x200B;[Arresto anomalo] arresto anomalo casuale durante la riproduzione con tipo di dati/gestione colore sul canale utente
&#x200B;* [Gestione colore] Le risorse utilizzate come scala di grigio nello spazio colore della maschera visualizzano il nuovo menu
&#x200B;* [Gestione colore] Il canale utente è più scuro nella finestra della vista in modalità legacy + visualizzazione solo
&#x200B;* [Gestione colore] La mappa Env è sempre lineare quando utilizzata in iRay
&#x200B;* [Gestione colore] Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
&#x200B;* [Gestione colore] Il selettore colore non funziona all’interno di una Substance in modalità legacy
&#x200B;* [Gestione colore] Il passaggio tra le viste dei singoli canali nella finestra della vista viene visualizzato con lo spazio cromatico corretto quando si utilizza il menu a discesa
&#x200B;* [Gestione colore] L’esportazione applica la conversione errata ai canali utente con gestione del colore in modalità legacy
&#x200B;* I tratti creati nella maschera di visualizzazione Solo non vengono visualizzati quando si ritorna alla vista Materiale
&#x200B;* [Esportazione] Le mappe convertite non vengono esportate come canali con gestione del colore
&#x200B;* [Set di texture] Descrizione comando con nome originale mancante nei canali utente rinominati
&#x200B;* [Steam] File mancanti durante la verifica dell&#39;integrità del file con Steam

**Problemi noti:**

&#x200B;* [Mac M1] I materiali avanzati non vengono visualizzati correttamente

### 7.4.0

*(Rilasciato il 24 novembre 2021)*
Riepilogo: **Versione principale. Introduzione della prima versione della gestione del colore, disancoraggio della vista 2D o 3D, nuova opzione per lo srotolamento automatico degli UV per evitare isole allungate, chiamata delle funzioni JavaScript dall&#39;API Python e nuovo contenuto**

**Aggiunto:**

&#x200B;* [Gestione colore] Supporto della gestione colore OpenColorIO versione 2
&#x200B;* [Gestione colore] Aggiungere impostazioni di gestione del colore alle impostazioni del progetto
&#x200B;* [Gestione colore] Finestra di avvertenza sulle modifiche alla configurazione di Gestione colore all’apertura di un progetto
&#x200B;* [Gestione colore] Visualizza un messaggio di errore se è selezionato un file di configurazione OCIO non valido
&#x200B;* [Gestione colore] Consente di ignorare la configurazione con la variabile di ambiente OCIO
&#x200B;* [Gestione colore] Più configurazioni OCIO integrate per impostazione predefinita con l&#39;applicazione
&#x200B;* [Gestione colore] Estrai il nome dello spazio colore dal nome del file bitmap importato
&#x200B;* [Gestione colore] Consente di ignorare lo spazio colore con uno spazio colore dalla configurazione nella finestra Proprietà
&#x200B;* [Gestione colore] Aggiungere opzioni di gestione del colore nelle impostazioni del set di texture
&#x200B;* [Gestione colore]&#x200B;[Finestra vista] Consente di gestire separatamente i colori delle viste 2D e 3D
&#x200B;* [Gestione colore] Caricare e convertire la mappa dell&#39;ambiente nello spazio colore di lavoro
&#x200B;* [Gestione colore] Regola il selettore colore e l&#39;editor con lo spazio colore corrente
&#x200B;* [Gestione colore] Consente di selezionare lo spazio colore di trasformazione della visualizzazione nella finestra della vista con un nuovo menu a discesa
&#x200B;* [Gestione colore] Applicare la trasformazione della visualizzazione con i risultati del rendering dei raggi
&#x200B;* [Gestione colore] Esportare texture con diversi spazi colore
&#x200B;* [Gestione colore]&#x200B;[Python] Applicazione delle impostazioni di gestione del colore dalla variabile di ambiente (OCIO) ai nuovi progetti
&#x200B;* [Finestra vista] Consente di disancorare la finestra della vista 2D o 3D
&#x200B;* [Annullamento automatico] Nuova opzione per evitare isole allungate
&#x200B;* [Scripting Python] Chiama funzioni JavaScript dall’API Python
&#x200B;* [Finestra Nuovo progetto] Rende comprimibile la sezione delle mappe importate
&#x200B;* [Proiezione]&#x200B;[Altera] Consenti di nascondere le normali come opzione nelle impostazioni di Altera
&#x200B;* [Content] 11 nuove mappe grungi
&#x200B;* [Content] 8 nuovi strumenti predefiniti (cerniera, cavo di serraggio, scintillio)
&#x200B;* [Contenuto] 8 nuovi materiali (cicatrice, tasca, ...)
&#x200B;* [Contenuto] 1 nuovo generatore (gonfia shrinkwarp)

**Problemi noti:**

&#x200B;* [Mac M1] I materiali avanzati non vengono visualizzati correttamente
&#x200B;* [Gestione colore]&#x200B;[Arresto anomalo] Arresto anomalo casuale durante la riproduzione con tipo di dati/gestione colore sul canale utente
&#x200B;* [Gestione colore] Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
&#x200B;* [Gestione colore]&#x200B;[Iray] Il salvataggio del rendering in EXR o TIFF durante l’attivazione della Gestione colore nella finestra della vista consente di salvare sempre in modalità lineare
&#x200B;* [Gestione colore] Le risorse utilizzate come scala di grigio nella maschera visualizzano il menu Spazio colore errato
&#x200B;* [Color Management]&#x200B;[Iray] La mappa Env è sempre lineare se utilizzata in Iray
&#x200B;* [Gestione colore]&#x200B;[Esporta] Le mappe convertite non vengono esportate come canali di gestione del colore
&#x200B;* [Gestione colore]&#x200B;[Esporta] L&#39;esportazione ignora se il canale utente è sottoposto alla gestione del colore o meno in modalità legacy

### 7.3.1

*(Rilasciato il 24 novembre 2021)*
Riepilogo: **Bugfix**

**Aggiunto:**

&#x200B;* [Proiezione] Il ridimensionamento deve funzionare solo nello spazio oggetto

**Corretto:**

&#x200B;* [Mac M1] La creazione di livelli di materiale non funziona
&#x200B;* [Mac M1]&#x200B;[Proiezione] L’alterazione non funziona
&#x200B;* I micro dettagli non vengono visualizzati correttamente
&#x200B;* [Proiezione]&#x200B;[Arresto anomalo] Passaggio alla modalità di alterazione con un livello creato con una versione precedente
&#x200B;* [Proiezione]&#x200B;[Altera] L’opzione Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
&#x200B;* [Proiezione]&#x200B;[Altera] L’opzione Dividi rimane selezionata al termine della divisione
&#x200B;* [Proiezione]&#x200B;[UV] Il punto pivot viene reimpostato quando si capovolge la proiezione
&#x200B;* [Filtro] L’ambiente Esegue i baking illuminazione cambia quando si ricarica o si modifica un parametro
&#x200B;* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
&#x200B;* [Interoperabilità] Il pulsante &quot;Sfoglia risorse 3D nel Marketplace&quot; dovrebbe sempre aprire CCD nella scheda 3D di Stock e Marketplace

**Problemi noti:**

&#x200B;* [Mac M1] I Materiali avanzati non vengono visualizzati correttamente

### 7.3.0

*(Rilasciato il 13 ottobre 2021)*
Riepilogo: **Versione principale. Contiene una nuova proiezione di alterazione 3D, una nuova proiezione cilindrica, miglioramenti del selettore colore, nuove funzioni nell&#39;API Python e correzioni di bug**

**Aggiunto:**

&#x200B;* [Proiezione]&#x200B;[Altera] Esporre l’alterazione 3D come nuova modalità di proiezione
&#x200B;* [Proiezione]&#x200B;[Altera] Consente la modalità decalcomania per Alpha, Texture e procedure con trascinamento nella finestra della vista
&#x200B;* [Proiezione]&#x200B;[Altera] Usa proiezione alterazione con decalcomania (ALT)
&#x200B;* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Trasforma alterazione intera o per vertici
&#x200B;* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Aggiungi punti della griglia con opzioni Dividi alterazione a croce, in orizzontale o verticale
&#x200B;* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Menu dedicato per le azioni di ripristino
&#x200B;* Opzione [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] per regolare automaticamente le tangenti quando si spostano i punti
&#x200B;* [Proiezione]&#x200B;[Altera]&#x200B;[Barra degli strumenti] Menu dedicato per l&#39;edizione della griglia (dimensioni, reimpostazione, colore e dimensione della maniglia)
&#x200B;* [Proiezione]&#x200B;[Altera] Nuova scelta rapida da tastiera da tastiera per cambiare la modalità dell&#39;edizione di alterazione vertici interi (MAIUSC+V)
&#x200B;* [Proiezione]&#x200B;[Altera] Con clic+Ctrl è possibile passare dallo strumento superficie ad altri strumenti
&#x200B;* [Proiezione]&#x200B;[Cilindrica] Esposizione della modalità di proiezione cilindrica
&#x200B;* [Proiezione]&#x200B;[Barra degli strumenti] Impostazioni manipolatore di gruppi (dimensioni, passaggi griglia, passaggi angolo)
&#x200B;* [Selettore colore] Nuova interfaccia utente del selettore colore
&#x200B;* [Selettore colore] Usare i valori sRGB nei widget del selettore colore
&#x200B;* [Selettore colore] Consente di salvare ed eliminare i campioni di colore
&#x200B;* [Selettore colore] Contagocce accessibile da slot per colori e normali
&#x200B;* [Selettore colore] Consente di modificare il colore dinamico tra i valori 0 e 255
&#x200B;* [Selettore colore] Rendi lo stato HSV/RGB comune in tutta l’app
&#x200B;* [Selettore colore] La finestra del selettore colore è semi-persistente
&#x200B;* [Selettore colore] Premendo Esc si chiude la finestra del selettore colore
&#x200B;* Miglioramento delle prestazioni per l’interazione dell’interfaccia utente e durante la pittura
&#x200B;* [Engine] Aggiornamento alla nuova versione del motore di Substance (8.3.0)
&#x200B;* [Scripting]&#x200B;[Python] Consente di ricaricare la trama del progetto corrente
&#x200B;* [Scripting]&#x200B;[Python] Consente di aggiornare le risorse nei progetti
&#x200B;* [Scripting]&#x200B;[Python] Consenti di impostare ed eseguire query sulla risoluzione delle Porzioni UV
&#x200B;* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
&#x200B;* [Interoperabilità] Ricezione di più risorse da Bridge

**Corretto:**

&#x200B;* Il selettore colore non visualizza il colore corretto
&#x200B;* [Esegue i baking] L’elenco dei set di texture non è ordinato correttamente
&#x200B;* [Importazione FBX] Le trasformazioni pivot del gruppo 3ds Max non sono prese in considerazione
&#x200B;* [Substance Engine] Arresto anomalo con importazione di SBSAR danneggiati
&#x200B;* [MacOS] L’opzione di configurazione del progetto in lingue diverse non è presente
&#x200B;* I salvati automaticamente possono bloccare Painter durante processi lunghi

**Problemi noti:**

&#x200B;* [Proiezione]&#x200B;[Altera] L’opzione Dividi rimane selezionata al termine della divisione
&#x200B;* [Proiezione]&#x200B;[Altera] L’opzione Capovolgi non funziona quando la trasformazione è impostata sullo spazio mondo
&#x200B;* [Proiezione]&#x200B;[Altera] Linee di artefatto tra le patch in alcuni rari casi
&#x200B;* [Proiezione]&#x200B;[UV] Il punto pivot viene reimpostato quando si capovolge la proiezione
&#x200B;* [Mac M1] I Materiali avanzati non vengono visualizzati correttamente
&#x200B;* [M1]&#x200B;[Regressione] Livelli di materiale non funzionanti

### 7.2.3

*(Rilasciato il 24 agosto 2021)*
Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

&#x200B;* [Librerie] Aggiungere un metodo per escludere dalla ricerca per indicizzazione i file indesiderati

**Corretto:**

&#x200B;* [Win] Schermi multipli e problemi di sospensione
&#x200B;* [MacOS]&#x200B;[Arresto anomalo] Commutazione dello shader quando si utilizzano gli effetti
&#x200B;* [Riquadro di visualizzazione] La modalità di anteprima completa non mostra più il cursore del pennello senza canale alfa
&#x200B;* [UI] Il widget Angolo cambia direzione
&#x200B;* [Pila livelli] Molte sottocartelle causano un blocco molto lungo
&#x200B;* [Iray] Viste diverse in Iray e OpenGL: visibile se non funziona
&#x200B;* [Iray] Indice di rifrazione non preso in considerazione e non visualizzato nelle proprietà mdl
&#x200B;* [JavaScript] ShowExportDialog() non restituisce mai true
&#x200B;* Impossibile leggere mtl da Adobe Stock

### 7.2.2

*(Rilasciato: 27 luglio 2021)*
Riepilogo: **Versione secondaria, bugfix**

**Aggiunto:**

&#x200B;* Aggiornamento della versione dei requisiti del driver AMD

**Corretto:**

&#x200B;* [Mac M1] Rilevamento memoria errato
&#x200B;* [Esporta] I tracciati molto lunghi non vengono visualizzati correttamente

**Problemi noti:**

&#x200B;* [Content] Ombreggiature obsolete dei campioni

### 7.2.1

*(Rilasciato il 2 luglio 2021)*
Riepilogo: **Versione secondaria, aggiornamento rapido**

**Aggiunto:**

&#x200B;* [Interoperabilità] Aggiungi una descrizione per informare che l’invio di progetti Porzione UV a Stager non è ancora supportato
&#x200B;* [Plugin]&#x200B;[UI] Aggiornamento dell&#39;icona Livelink

**Corretto:**

&#x200B;* [Nvidia] La versione del driver che inizia con 30 è considerata obsoleta
&#x200B;* [Librerie] Lo stato del pannello Risorse non viene salvato a meno che un progetto non sia aperto
&#x200B;* [Librerie] La nuova ricerca salvata mantiene la parola chiave della vecchia ricerca salvata
&#x200B;* [Baker]&#x200B;[UVTiles] Anche le mappe ID per meshID prendono in considerazione le Porzioni UV
&#x200B;* [Esporta] I file gLTF non importano il colore dei vertici
&#x200B;* [Iray] Mancano alcune descrizioni comandi
&#x200B;* [Interoperabilità] L&#39;opzione Invia a Stager non è sempre disattivata quando non viene rilevato Stager
&#x200B;* [Resource Updater] Impossibile aggiornare il creatore di pennelli di Photoshop
&#x200B;* [Contenuto] Il generatore di usura dei bordi in fibra di vetro è rotto

### 7.2.0

*(Rilasciato il 23 giugno 2021)*
Riepilogo: **Versione principale, fornisce un aggiornamento del pannello delle risorse, un nuovo shader con accesso a nuovi canali e parametri, un aggiornamento complessivo dell’interfaccia utente, alcuni miglioramenti delle prestazioni molto richiesti, supporto linguistico esteso e altro ancora.**

**Aggiunto:**

&#x200B;* [Librerie] Nuovo pannello Risorse per sostituire lo scaffale
&#x200B;* [Libraries]&#x200B;[UI] Nuovo layout del pannello Risorse
&#x200B;* [Libraries]&#x200B;[UI] Modifica l&#39;orientamento e l&#39;interfaccia utente predefiniti del pannello Risorse
&#x200B;* [Libraries]&#x200B;[UI] Introduce un&#39;opzione di visualizzazione elenco alla libreria
&#x200B;* [Libraries]&#x200B;[UI] Nuovo percorso di navigazione nel pannello Risorse
&#x200B;* [Libraries]&#x200B;[UI] Seleziona &quot;Tutte le librerie&quot; quando selezioni una ricerca salvata
&#x200B;* [Libraries]&#x200B;[UI] Seleziona &quot;Tutte le librerie&quot; quando tutte le cartelle sono deselezionate
&#x200B;* [Libraries]&#x200B;[UI] Nuovo tag per i pennelli particelle
&#x200B;* [Libraries]&#x200B;[UI] Sostituito &quot;shelf&quot; da &quot;Tutte le librerie&quot; in tutta l&#39;app
&#x200B;* [Libraries]&#x200B;[UI] Consente di nascondere le cartelle vuote
&#x200B;* [Libraries]&#x200B;[UI] La libreria utente predefinita dovrebbe essere visibile anche se vuota
&#x200B;* [Libraries]&#x200B;[UI] Nuovo metodo di filtraggio tramite le icone del tipo di risorsa
&#x200B;* [Libraries] Scelta rapida da tastiera &quot;CTRL&quot; per selezionare più tipi di risorse
&#x200B;* [Libraries] Nuova variabile di ambiente per controllare il budget della memoria di anteprima delle risorse
&#x200B;* [Libraries]&#x200B;[Content] Mappe del nuovo ambiente
&#x200B;* [Libraries]&#x200B;[Content]&#x200B;[UI] spostamento di rendering sui materiali predefiniti
&#x200B;* [Libraries]&#x200B;[Contenuto] Imposta lo shader dell&#39;Adobe Standard Material (ASM) come predefinito per la generazione delle anteprime
&#x200B;* [Libraries]&#x200B;[Content]&#x200B;[ASM] Nuovi modelli di progetto per il nuovo shader ASM
&#x200B;* [Libraries]&#x200B;[Thumbnail] Utilizza la nuova mappa dell&#39;ambiente Studio 6
&#x200B;* [Libraries]&#x200B;[Thumbnail] Leggi la miniatura nella risorsa invece di generarla
&#x200B;* [Libraries]&#x200B;[Thumbnail] Aggiungi spostamento alla generazione di miniature
&#x200B;* [Impostazioni set di texture]
&#x200B;* [Texture Set Settings]&#x200B;[UI] Esporta il nuovo height al metodo di conversione normale
&#x200B;* [Impostazioni set di texture]&#x200B;[UI] Rielaborazione dell&#39;organizzazione dell&#39;interfaccia utente dei canali
&#x200B;* [Impostazioni set texture] Limite canali utente aumentato a 16 canali
&#x200B;* [Texture Set Settings]&#x200B;[UI] Indica quali canali sono compatibili con lo shader attualmente selezionato
&#x200B;* [Shader]&#x200B;[ASM] Nuovo shader materiale standard Adobe
&#x200B;* [Shader]&#x200B;[ASM] Aggiunto il supporto per Anisotropia, Cancella rivestimento, Dispersione sottosuperficie, Specular edge color e Brillantezza
&#x200B;* [Shader]&#x200B;[ASM] Modifica i valori di colore dei canali predefiniti
&#x200B;* [Shader]&#x200B;[ASM]&#x200B;[Esporta] Modello di esportazione aggiornato da Adobe Dimension a Adobe Substance 3D Stager
&#x200B;* [Shader]&#x200B;[ASM] Etichette e descrizioni comandi aggiunte per i parametri shader e MDL
&#x200B;* [Shader]&#x200B;[ASM] Rendete visibile il colore della Dispersione nella vista 2D anche se SSS non è supportato
&#x200B;* [Shader]&#x200B;[ASM]&#x200B;[Iray] Supporta lo shader ASM in Iray con la nuova MDL
&#x200B;* [Shader]&#x200B;[ASM]&#x200B;[Iray] Scattering sottosuperficie aggiornato in lucido e patinato delle specifiche PBR legacy
&#x200B;* [Shader]&#x200B;[ASM]&#x200B;[Content] Ha modificato il tipo SSS predefinito per i campioni
&#x200B;* [Shader]&#x200B;[ASM] Documentazione aggiunta per l&#39;API ASM
&#x200B;* [Shader]&#x200B;[ASM] Ottimizzate gli shader per ignorare i canali non utilizzati
&#x200B;* [Shader] Esporre i nuovi canali del set di texture
&#x200B;* [Shader] Dispersione sottosuperficie migliorata
&#x200B;* [Shader] Nuovi parametri dello shader nascosti per alcuni shader
&#x200B;* [Shader] Visibile se per i parametri dello shader
&#x200B;* [Prestazioni]
&#x200B;* [Librerie] Anteprima risorse: miglioramenti a livello di tempo di caricamento e prestazioni di calcolo
&#x200B;* [Engine] Miglioramenti delle prestazioni di pittura
&#x200B;* [Annullamento automatico]
&#x200B;* [Annullamento automatico] Miglioramenti delle prestazioni di Impacchettamento
&#x200B;* [Annullamento automatico] Annullamento automatico del wrapping compatibile con il flusso di lavoro Porzione UV
&#x200B;* [Srotolamento automatico] Nuova opzione per posizionare gli UV in base all&#39;orientamento della trama
&#x200B;* [Altro]
&#x200B;* [Impostazioni] Cambiata direzione zoom predefinita
&#x200B;* [UI] Aggiornamento complessivo dell’interfaccia utente
&#x200B;* [UI] Rielaborazione del menu Aiuto
&#x200B;* [UI] Sostituisci l&#39;icona Inverti
&#x200B;* [UI]&#x200B;[Plugin] Icona Sostituisci per il collegamento dcc del plug-in
&#x200B;* [UI]&#x200B;[AMD] Aggiorna la versione minima richiesta e il messaggio a comparsa
&#x200B;* [Pila livelli] Crea un nuovo livello nella cartella vuota selezionata
&#x200B;* Aggiornamento della documentazione Python
&#x200B;* Branding
&#x200B;* [Branding]&#x200B;[UI] Nome dell’applicazione aggiornato in Adobe Substance 3D Painter
&#x200B;* [Branding]&#x200B;[UI] Versione autonoma aggiornata a &quot;Substance edition&quot;
&#x200B;* [Branding]&#x200B;[UI] Nome eseguibile dell&#39;applicazione aggiornato, percorso di installazione, pacchetto e icone
&#x200B;* [Branding]&#x200B;[UI] Libreria e percorso predefiniti rinominati
&#x200B;* [Branding]&#x200B;[UI] Aggiornamento della finestra Informazioni su
&#x200B;* [Branding]&#x200B;[UI] Schermata introduttiva aggiornata
&#x200B;* [Branding]&#x200B;[UI] Rimosso il numero di versione basato sull&#39;anno
&#x200B;* [Localizzazione] Nuove traduzioni in tedesco, francese e cinese semplificato
&#x200B;* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
&#x200B;* [Interoperabilità] Interoperabilità con l&#39;ecosistema Adobe: Designer, Sampler, Stager e Bridge
&#x200B;* [Interoperabilità]&#x200B;[UI] Ricevi e aggiorna la risorsa da Designer
&#x200B;* [Interoperabilità]&#x200B;[UI] Ricevi risorsa da Sampler
&#x200B;* [Interoperabilità]&#x200B;[UI] Invia risorsa a Stager
&#x200B;* [Interoperabilità]&#x200B;[UI] Mostra in Adobe Bridge
&#x200B;* [Interoperabilità]&#x200B;[UI] Consente di accedere rapidamente alle risorse 3D di Adobe
&#x200B;* [Interoperabilità] Nuovi tag di utilizzo di sbsar
&#x200B;* [Interoperabilità] Gestire i tipi di risorse ricevute
&#x200B;* [Interoperabilità] Le risorse ricevute da Adobe Substance 3D Designer o Adobe Substance 3D Sampler vengono archiviate nella libreria predefinita scelta dall&#39;utente
&#x200B;* [Interoperabilità]&#x200B;[UI] Nuova icona nella barra degli strumenti a sinistra da inviare a Stager o Photoshop

**Corretto:**

&#x200B;* [Tablet] Prestazioni ridotte quando si esegue il disegno a pressione
&#x200B;* [Tablet] Problema con i tablet con controlli del cursore
&#x200B;* [Arresto anomalo] Mancata corrispondenza del nome tra l’elenco Set di texture e il modulo di esportazione
&#x200B;* [Arresto anomalo]&#x200B;[Librerie] Fai doppio clic su una libreria secondaria
&#x200B;* [Libraries] Problema durante la ricerca per indicizzazione delle directory della libreria
&#x200B;* [Libraries] La riga di comando Forza generazione anteprima non funziona come previsto
&#x200B;* [Libraries]&#x200B;[Contenuto] Il filtro Baked Light Environment è nero per impostazione predefinita
&#x200B;* [Linux]&#x200B;[MacOS]&#x200B;[Esporta mesh] Impossibile importare glTF creato su Linux/MacOS
&#x200B;* [Linux] Il trascinamento di un file nel pannello Risorse può causare un arresto anomalo
&#x200B;* [Auto-Unwrap] L’opzione Auto-Unwrap è disponibile anche se una trama non è stata selezionata per il ricaricamento
&#x200B;* [Particelle] Comportamento errato delle particelle con gravità
&#x200B;* [Serie di livelli] L’istogramma a livelli può utilizzare la luminanza solo con alcuni canali
&#x200B;* [Maschera geometria] Il menu di scelta rapida di una cartella quando si modifica la maschera di geometria non funziona
&#x200B;* [Proiezione] Cucitura con proiezione sferica e filtro bilineare
&#x200B;* [Riquadri UV] Esporta maschera solo in file esporta solo il riquadro 0, 0
&#x200B;* [Trama di esportazione] L&#39;esportazione della trama FBX è vuota
&#x200B;* [Iray] La mappa normale non viene considerata nei nuovi progetti durante il rendering
&#x200B;* [Salva] Salva problemi su unità condivise
&#x200B;* [Baking] Se si esegue il rebaking di una trama con parametri modificati, viene visualizzato un avviso
&#x200B;* [Baking]&#x200B;[Regressione] Risultato errato quando il rettangolo di selezione globale di High Poly Meshes non include l&#39;origine della scena
&#x200B;* [Python] Le librerie utente personalizzate non sono considerate

**Problemi noti:**

&#x200B;* [Librerie] Ricerche salvate non salvate se non è aperto alcun progetto
&#x200B;* [NVIDIA] Messaggio per driver obsoleto anche se aggiornato

### 7.1.1 (2021.1.1)

*(Rilasciato: 23 marzo 2021)*
Riepilogo: **Versione secondaria, correzione rapida con possibilità di immettere valori esadecimali nel selettore colore**

**Aggiunto:**

&#x200B;* [Log] Avvisa gli utenti in caso di driver GPU AMD incompatibili
&#x200B;* [Selettore colore] Consente di digitare valori esadecimali

**Corretto:**

&#x200B;* [Baker] Prestazioni ridotte
&#x200B;* [Maschera Geometria] Se si fa clic con il tasto Alt sul nome della trama, si può verificare un arresto anomalo
&#x200B;* [Engine] Il disegno non aggiorna l’intera vista quando necessario
&#x200B;* [Serie di livelli] La selezione si blocca dopo la modifica dello shader
&#x200B;* [MacOS]&#x200B;[Selettore colore] Il colore è leggermente diverso da quello selezionato
&#x200B;* [Esporta] L’uso del formato di file PSD non genera un file per porzione UV
&#x200B;* [Scripting]&#x200B;[Javascript] alg.mapexport.getPathsExportDocumentMaps() non restituisce tutti i valori
&#x200B;* [Scripting]&#x200B;[Python] I plug-in disabilitati vengono nuovamente abilitati alla riapertura di Painter

### 7.1.0 (2021.1.0)

*(Rilasciato: 28 gennaio 2021)*
Riepilogo: **Versione principale, nuova maschera di geometria che consente di selezionare e colorare parti della geometria, copiare/incollare effetti nella pila di livelli, miglioramento del flusso di lavoro delle porzioni UV, aggiornamento di Iray, forni, Substance Engine e nuovi contenuti**

**Aggiunto:**

&#x200B;* Nuova maschera di geometria e colorazione di parti selezionate della geometria
&#x200B;* [Maschera geometria] Consente di colorare parti selezionate della geometria in base ai nomi della trama
&#x200B;* [Maschera di geometria] Selezione rettangolare in entrambe le viste
&#x200B;* [Maschera geometria] Consente di nascondere/ignorare la geometria esclusa su qualsiasi livello
&#x200B;* [Maschera geometria]&#x200B;[Proprietà] Selezione rapida delle caselle di controllo con clic e trascinamento
&#x200B;* [Geometry Mask]&#x200B;[Proprietà]&#x200B;[UI] Includi/Escludi tutto con un menu a discesa nella finestra Proprietà
&#x200B;* [Maschera geometria]&#x200B;[Proprietà] Consente di selezionare rapidamente una voce in un elenco con ALT+CLIC SINISTRO
&#x200B;* [Maschera geometria]&#x200B;[Proprietà] Sovrapposizione nelle finestre delle viste quando si passa il cursore su nomi/Porzioni UV trama nella finestra Proprietà
&#x200B;* [Geometry Mask]&#x200B;[Pila livelli] Aggiunge le opzioni Copia/Incolla alla maschera della geometria
&#x200B;* [Maschera geometria] Icona Nuova per il pulsante Nascondi/Ignora geometria esclusa
&#x200B;* [Maschera geometria] Nuova descrizione comando per nascondere/ignorare la geometria esclusa
&#x200B;* [Geometry Mask] scelta rapida da tastiera da tastiera ALT+H per attivare/disattivare il pulsante &quot;nascondi geometria esclusa&quot;
&#x200B;* [Porzioni UV]&#x200B;[Pila livelli] Nuova miniatura di anteprima della sfera del livello di riempimento per la Porzione UV e la modalità semplificata
&#x200B;* [Porzioni UV]&#x200B;[Pila livelli] Consente di uscire facilmente dalla maschera della Porzione UV
&#x200B;* [Porzioni UV]&#x200B;[Elenco set di texture] Consente di fornire una descrizione per Porzione UV
&#x200B;* [Porzioni UV]&#x200B;[Impostazioni set di texture]&#x200B;[UI] Due nuovi titoli di sezione nel menu a discesa per modificare la risoluzione della Porzione UV
&#x200B;* [Porzioni UV]&#x200B;[Finestra vista] Esci dalla maschera Porzione UV quando si trascina un materiale nella finestra della vista
&#x200B;* [Pila livelli] Aggiungere opzioni di copia/incolla per gli effetti
&#x200B;* [Pila livelli] Consente di copiare/incollare effetti da un set di texture a un altro
&#x200B;* [Pila livelli] Consenti selezione multipla di effetti
&#x200B;* [Pila livelli] Aggiungi opzioni di copia/incolla come scelte rapide per gli effetti di livello
&#x200B;* [Pila livelli] Passa automaticamente tra maschera e contenuto quando trascini gli effetti su un altro livello
&#x200B;* [Pila livelli] Crea automaticamente una maschera quando si incolla una maschera da un altro livello
&#x200B;* [Pila livelli] Aggiungi azioni effetto di spostamento nel menu contestuale di scelta rapida degli effetti
&#x200B;* [Pila livelli] Consente di trascinare gli effetti da un livello all’altro
&#x200B;* [Pila livelli] Quando trascini degli elementi in una cartella, questi vengono posizionati sopra la cartella
&#x200B;* Aggiornamento di Iray alla versione 2020.1.0
&#x200B;* [Baker] Aggiorna i Baker alla versione 2.5.4
&#x200B;* [Baker] Visualizza le singole Porzioni UV nella finestra di avanzamento eseguita i baking
&#x200B;* [Baker]&#x200B;[UI] Consente di eseguire i baking rapidamente il set di texture corrente con un nuovo pulsante
&#x200B;* [Baker] Consente all&#39;utente di selezionare rapidamente uno dei baker con ALT+CLIC SINISTRO
&#x200B;* Aggiorna Substance Engine alla versione 8.0.8
&#x200B;* [Substance Engine] Supporto del colore predefinito nei nuovi file .sbsar
&#x200B;* [Annullamento automatico] Miglioramento delle prestazioni
&#x200B;* [Esporta] Aggiungi un feedback visivo per indicare quale risoluzione di Porzione UV differisce da quella predefinita del progetto
&#x200B;* [Esporta] Aggiungere il fattore dimensione scena nel file json shader esportato
&#x200B;* [Lingua] Aggiungi traduzione giapponese
&#x200B;* [UI] Finestra Aggiorna informazioni con controllo delle versioni delle dipendenze interne
&#x200B;* [Scripting]&#x200B;[Python] Consente di gestire le risorse degli scaffali
&#x200B;* [Scripting]&#x200B;[Python] Consenti di sapere quando un progetto è pronto per essere eseguito i baking ed esportato
&#x200B;* [Scripting]&#x200B;[Python] Consenti di sapere quando uno scaffale ha terminato la ricerca per indicizzazione delle risorse sul disco
&#x200B;* [Scripting]&#x200B;[Python] Consenti di eseguire query sull’elenco di porzioni UV per set di texture
&#x200B;* [Scripting]&#x200B;[Python] Consente di assegnare un’anteprima personalizzata alle risorse dello shelf
&#x200B;* [Scripting]&#x200B;[Python] Consenti di gestire scaffali personalizzati
&#x200B;* [Scripting]&#x200B;[Python] Aggiunge un indice di metodo in ogni sottomodulo della documentazione
&#x200B;* [Scripting]&#x200B;[Python] Nuovo stile per la documentazione
&#x200B;* [Scripting]&#x200B;[Python] Miglioramento delle risorse e della documentazione dello scaffale
&#x200B;* [Content] Tre nuovi strumenti predefiniti per creare punti
&#x200B;* [Shelf] Rimuovi temporaneamente &quot;Esporta in Substance share&quot; durante la transizione alla nuova piattaforma di Substance share

**Corretto:**

&#x200B;* Arresto anomalo di utilizzo di monitor con risoluzioni diverse
&#x200B;* Arresto anomalo in Substance Engine con alcuni progetti rari
&#x200B;* L’aggiornamento della finestra della vista non riesce con Nascondi/Ignora geometria esclusa quando si cambia livello
&#x200B;* [vista 2D] Il riquadro di visualizzazione 2D potrebbe non essere presente in alcuni progetti
&#x200B;* [Eseguendo i baking] &quot;Corrispondenza per nome trama&quot; ignora parti dell’oggetto
&#x200B;* [Pila livelli] Quando si fa clic su un effetto di livello, si apre una cartella
&#x200B;* [Maschera geometria] La Porzione UV viene comunque conteggiata nella maschera anche quando si reimporta la trama senza di essa
&#x200B;* [Maschera geometria] Il menu di scelta rapida nella finestra della vista non fornisce gli strumenti corretti
&#x200B;* [Engine] Segnali di ritardo gravi su progetti specifici
&#x200B;* [Scripting] Latenza elevata con richieste JSON POST remote su Windows
&#x200B;* [Linux] La quantità di Vram non viene rilevata correttamente con specifiche GPU integrate
&#x200B;* [Annullamento automatico] Arresti anomali o operazioni di annullamento dell’avvolgimento lunghe in alcuni progetti

## Versione 6

### 6.2.2 (2020.2.2)

*(Rilasciato il 28 settembre 2020)*
Riepilogo: **Versione secondaria, correzione rapida con alcune funzioni nell’API Python**

**Aggiunto:**

&#x200B;* [Prestazioni] Non calcolare tutte le Porzioni UV quando si utilizza la selezione ID colore
&#x200B;* [Baker]&#x200B;[UI] Visualizza le descrizioni dei set di texture
&#x200B;* [Baker] Consenti di salvare le impostazioni di esegue i baking
&#x200B;* [Baker] Aggiungi le opzioni comprimi tutto/espandi tutto alla scheda Selezione
&#x200B;* [Elenco set di texture] Nascondi descrizione se vuoto
&#x200B;* [Porzioni UV]&#x200B;[Elenco set di texture] Se si fa clic su una Porzione UV, l’elenco viene espanso o compresso
&#x200B;* [Esporta]&#x200B;[UI] Consente di ridimensionare il pannello Elenco set di texture in orizzontale
&#x200B;* [Esporta]&#x200B;[UI] Testo coerente delle descrizioni per il flusso di lavoro Porzione UV e Set di texture con texture non selezionata
&#x200B;* [Scripting]&#x200B;[Python] Consente di utilizzare i predefiniti di esportazione per esportare la texture
&#x200B;* [Scripting]&#x200B;[Python] Aggiungere un registro delle modifiche nella documentazione
&#x200B;* [Scripting]&#x200B;[Python] Consente di eseguire query su tutti i canali disponibili in un determinato stack
&#x200B;* [Scripting]&#x200B;[Python] Miglioramenti dell’interfaccia utente della console

**Corretto:**

&#x200B;* [AMD] Rilevamento non corretto della versione del driver obsoleta
&#x200B;* Arresto anomalo di reimportazione di una trama con layout di Porzione UV diverso in alcuni casi
&#x200B;* Arresto anomalo quando si utilizzano particelle con UDIM su trame molto pesanti
&#x200B;* [Porzioni UV] Arresto anomalo durante l’esportazione di una trama con informazioni di spostamento in alcuni casi
&#x200B;* [Export]&#x200B;[Arresto anomalo] L’esportazione di Vista 2D in formato psd può causare un arresto anomalo
&#x200B;* L’importazione di immagini come sequenze durante la creazione di un progetto non funziona
&#x200B;* Motore bloccato in un ciclo continuo
&#x200B;* [Scelta rapida da tastiera] La fotocamera ruota sempre in modalità snap quando si modificano le scelte rapide della modalità snap
&#x200B;* Le trame vengono sempre annullate automaticamente quando vengono reimportate, anche se l’opzione è disattivata
&#x200B;* [Elenco set di texture] Il campo di testo Descrizione a volte non è completamente visibile durante l&#39;edizione
&#x200B;* Il menu a discesa [Elenco set di texture] per nascondere/mostrare i set di texture non è completamente visibile
&#x200B;* [Elenco set di texture] Facendo clic sull’icona occhio non si dovrebbe inserire il nome &quot;Modifica set di texture&quot;
&#x200B;* [Impostazioni set texture] La rimozione di un canale rimuove anche il canale sottostante
&#x200B;* [Esporta] Includi tutto e Reimposta tutto non tiene conto delle Porzioni UV
&#x200B;* [Baker] Durante la esegue i baking vengono visualizzati i baker deselezionati
&#x200B;* L’aggiornamento della risoluzione non viene considerato per le mappe con baking utilizzate come input
&#x200B;* [Porzioni UV]&#x200B;[Finestra vista] Il riquadro di visualizzazione 3D si blocca quando si aggiunge un Materiale avanzato dopo l&#39;altro con la maschera Porzione UV selezionata
&#x200B;* [Porzioni UV]&#x200B;[Finestra vista] Il Wireframe è ancora visibile per le porzioni nascoste con la modalità pittura passante
&#x200B;* [Esportazione]&#x200B;[Sketchfab] Problemi con il tipo di abbonamento &quot;più&quot;
&#x200B;* [Sketchfab] La casella di controllo &quot;Questa risorsa è privata&quot; non viene visualizzata dopo il cambio di account
&#x200B;* I predefiniti per i pennelli &quot;Deformazioni&quot; [Esporta]&#x200B;[Contenuto] possono causare problemi di prestazioni
&#x200B;* [Plugin Photoshop] Messaggio nel registro: non compatibile con il flusso di lavoro Porzione UV
&#x200B;* [Scripting]&#x200B;[Python] L’opzione var PYTHONPATH impedisce l’avvio dell’applicazione
&#x200B;* [Scripting]&#x200B;[Python] Errore nella documentazione Python

### 6.2.1 (2020.2.1)

*(Rilasciato: 29 luglio 2020)*
Riepilogo: **Versione secondaria, aggiornamento rapido**

**Aggiunto:**

&#x200B;* Aggiungere la variabile di ambiente &quot;SUBSTANCE\_PAINTER\_VRAM\_BUDGET&quot; per ignorare la quantità di VRam della GPU
&#x200B;* [Porzione UV]&#x200B;[Prestazioni] Non calcolare tutti i riquadri UV quando si utilizza lo strumento Riempimento poligonale

**Corretto:**

&#x200B;* [Iray] Il comando Salva rendering restituisce un errore e restituisce un’immagine nera
&#x200B;* [Linux] Arresto anomalo dopo la schermata iniziale su CentOS 7.3
&#x200B;* [Linux] La quantità di Vram non viene rilevata correttamente con configurazioni specifiche
&#x200B;* [Arresto anomalo] Apertura di un progetto con il nome di un set di texture duplicato
&#x200B;* [Engine] Problema di inconvalida della cache durante la modifica di una maschera
&#x200B;* [Elenco set di texture] Effetto di font errato quando il set di texture è disattivato

**Problemi noti:**

&#x200B;* [Elenco set di texture] Impossibile nascondere la descrizione
&#x200B;* Problemi dell&#39;interfaccia utente di [Texture Set List]
&#x200B;* [Iray] Il rendering di PSD non si apre
&#x200B;* [Plugin Photoshop] Non compatibile con il flusso di lavoro Porzione UV

### 6.2.0 (2020.2.0)

*(Rilasciato: 23 luglio 2020)*
Riepilogo: **Versione principale con nuovo flusso di lavoro Porzione UV, pittura tra Porzioni UV e miglioramento delle prestazioni**

**Aggiunto:**

&#x200B;* Porzioni UV (UDIM)
&#x200B;* [Porzione UV] Pittura sui riquadri UV
&#x200B;* [Porzioni UV] Consente di scegliere tra flusso di lavoro nuovo e legacy per la Porzione UV
&#x200B;* [Porzioni UV] Importa UDIM/Porzione UV sequenze di immagini come risorsa
&#x200B;* [Riquadri UV] Aggiungi elenco di riquadri UV per set di texture nella finestra Elenco set di texture
&#x200B;* [Porzioni UV] Consenti di modificare contemporaneamente la risoluzione di più porzioni UV nelle impostazioni del set di texture
&#x200B;* [Porzioni UV]&#x200B;[Vista 2D] Visualizza le porzioni UV come griglia
&#x200B;* [Riquadri UV]&#x200B;[Vista 2D] Pulsante Nuova finestra della vista per visualizzare o nascondere le informazioni sui riquadri UV
&#x200B;* [Porzioni UV] Per impostazione predefinita, imposta lo strumento di pittura su un singolo canale per i progetti con porzioni UV
&#x200B;* [Riquadri UV] Nuovo pulsante nella barra degli strumenti contestuale per ignorare i riquadri UV mascherati durante il disegno
&#x200B;* [Porzioni UV]&#x200B;[Serie di livelli] Icone nuove serie di livelli per migliorare le prestazioni
&#x200B;* [Riquadri UV]&#x200B;[Pila di livelli] Migliorare le icone di disegno e riempimento nella barra degli strumenti
&#x200B;* [Maschera porzione UV]&#x200B;[Vista 2D] Consente di includere o escludere più porzioni UV contemporaneamente (clic sinistro, CTRL+clic sinistro)
&#x200B;* [Maschera porzione UV] Nuova maschera porzione UV da includere, escludere porzioni per livello con una nuova icona
&#x200B;* [Maschera porzione UV]&#x200B;[Pila di livelli] Visualizza il numero di porzioni UV nell&#39;icona della maschera Porzioni UV quando non tutte sono incluse
&#x200B;* [Maschera porzione UV]&#x200B;[Vista 2D/3D] Aggiungi effetto al passaggio del mouse per visualizzare le porzioni UV sotto il cursore
&#x200B;* [Porzioni UV]&#x200B;[Pannelli] Consenti di selezionare e cuocere porzioni UV specifiche
&#x200B;* [Porzioni UV]&#x200B;[Pannelli] Aggiungete opzioni di selezione per set di texture/porzioni UV
&#x200B;* [Porzioni UV]&#x200B;[Pannelli] Opzione del menu di scelta rapida per selezionare Porzioni UV all&#39;interno di un set di texture
&#x200B;* [Porzioni UV]&#x200B;[Pannelli] Consente la selezione rapida in Set di texture/Porzioni UV trascinando
&#x200B;* [Porzioni UV]&#x200B;[Pannelli] Sostituite i pulsanti &quot;Tutto&quot; e &quot;Nessuno&quot; nelle mappe trama con opzioni di selezione più esplicite
&#x200B;* [Riquadri UV]&#x200B;[Pannelli] Visualizza il numero di texture da produrre
&#x200B;* [Porzioni UV]&#x200B;[Esporta] Consente di selezionare ed esportare porzioni UV specifiche
&#x200B;* [Porzioni UV]&#x200B;[Esporta] Consente la selezione rapida di porzioni UV mediante trascinamento
&#x200B;* [Porzioni UV]&#x200B;[Esporta] Aggiungi opzioni del menu a discesa per le porzioni UV
&#x200B;* [Riquadri UV]&#x200B;[Esporta] Rendi non disponibili alcuni predefiniti di esportazione se non funzionano con i riquadri UV (Adobe Dimension, Sketchfab, glTF, USD)
&#x200B;* [Porzioni UV]&#x200B;[Contenuto] Aggiornate i predefiniti di esportazione per utilizzare il nuovo tag $udim
&#x200B;* [Riquadri UV] Miglioramento della segnalazione degli errori durante l’importazione di trame con Isole UV sovrapposte
&#x200B;* [Riquadri UV] Riquadri UV compatibili in Iray
&#x200B;* [UV Tiles]&#x200B;[Scripting] Aggiungere la documentazione di esportazione delle porzioni UV al documento Python
&#x200B;* Prestazioni
&#x200B;* [Prestazioni] Nuovo pulsante nella barra degli strumenti contestuale per sospendere il calcolo del motore durante il lavoro (MAIUSC+ESC)
&#x200B;* [Prestazioni] Apertura più rapida del progetto ritardando il calcolo della cache del set di texture
&#x200B;* [Prestazioni] Non aspettare che le mappe mesh vengano caricate all’apertura del progetto
&#x200B;* [Prestazioni]&#x200B;[Vista 2D/3D] Non calcolare il canale maschera nella finestra della vista quando non viene utilizzato
&#x200B;* [Prestazioni] Non bloccare l&#39;applicazione durante il caricamento delle mappe mesh visualizzate nelle finestre delle viste
&#x200B;* [Prestazioni] Migliorare la velocità di salvataggio incrementale durante il salvataggio di un progetto
&#x200B;* [Prestazioni]&#x200B;[Panettieri] Modifica le impostazioni di dilatazione predefinite per migliorare il risparmio di tempo e dimensioni del progetto
&#x200B;* [Performance]&#x200B;[Panettieri] Passa alla scala di grigi su panettieri specifici per risparmiare tempo e dimensioni del progetto
&#x200B;* [Prestazioni]&#x200B;[Esporta] Migliora le prestazioni del motore per esportare le texture più velocemente
&#x200B;* [Prestazioni]&#x200B;[Esporta] Migliora la reattività quando si apre la finestra di dialogo di esportazione con molti set di texture
&#x200B;* [Prestazioni]&#x200B;[Esporta] Migliora le prestazioni quando si passa alla scheda &quot;Elenco esportazioni&quot;
&#x200B;* [Performance]&#x200B;[Iray] Ridurre il tempo di avvio di Iray
&#x200B;* Altro
&#x200B;* [Panettieri] Aggiungere opzioni di selezione per i set di texture
&#x200B;* Sposta la gestione dell’istanza dello shader nelle impostazioni del set di texture
&#x200B;* [Vista 2D/3D] Aggiungere un messaggio nella parte inferiore della finestra della vista per indicare il tipo di maschera modificato
&#x200B;* [Serie di livelli] Nuova opzione nelle impostazioni per passare dalla miniatura precedente a quella nuova
&#x200B;* [Serie di livelli] Aggiungi un feedback visivo per indicare lo stato di caricamento delle miniature
&#x200B;* [Proj] Nuova modalità di proiezione &quot;Riempimento (Corrispondenza per porzione UV)&quot; per caricare le sequenze di immagini
&#x200B;* [Proj] Modifica la modalità di proiezione dei livelli di riempimento su &quot;Riempi (come per porzione UV)&quot; in casi specifici
&#x200B;* [Contenuto] Ottimizzare i predefiniti per i pennelli Carboncino per migliorare le prestazioni
&#x200B;* Aggiornamento di Iray alla versione 2020.0.0
&#x200B;* [Esporta] Disattiva la scheda Elenco esportazioni se non è selezionato nulla
&#x200B;* Annulla contornamento automatico
&#x200B;* [Annullamento automatico] Migliora la percentuale di successo del processo di annullamento automatico del contornamento
&#x200B;* [Auto Unwrap] Parametrizzazione migliorata per aumentare la velocità e la stabilità

**Corretto:**

&#x200B;* [Alembic] Gli insiemi di facce vengono ignorati durante l&#39;importazione dei file
&#x200B;* [Alembic] Tempo di caricamento infinito con file specifici
&#x200B;* [Importa] Una sequenza di immagini UDIM errata viene importata quando differisce solo l’estensione del file
&#x200B;* [Arresto anomalo] Il tentativo di aprire il progetto bloccato da un altro processo causa un arresto anomalo
&#x200B;* [Proiezione] Artefatti sulla trama duplicata quando si utilizza la proiezione triplanare
&#x200B;* [Esporta] Il canale di espulsione non viene esportato con il formato USD
&#x200B;* [Content] Il materiale avanzato &quot;Carboncino&quot; contiene tratti pennello

**Problemi noti:**

&#x200B;* [Elenco set di texture] Impossibile nascondere la descrizione
&#x200B;* Problemi dell&#39;interfaccia utente di [Texture Set List]

### 6.1.3 (2020.1.3)

*(Rilasciato il 16 giugno 2020)*
Riepilogo: **Bugfix**

**Aggiunto:**

&#x200B;* [Esporta] Aggiungere le impostazioni di spostamento nel file json dei parametri Shader

**Corretto:**

&#x200B;* [Crash]&#x200B;[Engine] Arresto anomalo quando si tenta di cancellare e sostituire i canali esistenti
&#x200B;* [Arresto anomalo] Modifica dello shader dopo aver colorato una maschera in livelli di materiale
&#x200B;* [Crash]&#x200B;[Engine] Si arresta in modo anomalo con alcuni progetti pesanti
&#x200B;* [Bakers] La corrispondenza per nome non funziona con gli oggetti esportati da zBrush
&#x200B;* [Spostamento]&#x200B;[SVT] Le texture non vengono visualizzate all’apertura del progetto quando lo spostamento è attivo
&#x200B;* [Esporta] Alcune texture vengono esportate in grigio uniforme
&#x200B;* [Esporta] I set di texture disabilitati non devono essere esportati per i predefiniti di esportazione Dimension e Sketchfab
&#x200B;* [Scripting]&#x200B;[JavaScript] Arresto anomalo durante l’utilizzo dell’API JavaScript per accedere alla configurazione di esportazione nell’evento onProjectOpened
&#x200B;* [Scripting]&#x200B;[Javascript] onExportFinished() non viene chiamato dopo un&#39;esportazione

### 6.1.2 (2020.1.2)

*(Rilasciato il 28 maggio 2020)*
Riepilogo: **Aggiornamento di Bugfix con Substance Engine e Bakers**

**Aggiunto:**

&#x200B;* [Bakers] Esegui l’aggiornamento alla versione più recente
&#x200B;* [Panettieri] Nuovo metodo di campionamento in Occlusione ambiente, curvatura, panettieri Thickness
&#x200B;* Aggiornamento alla versione di Substance Engine più recente
&#x200B;* [Scripting]&#x200B;[Python] Consente la creazione di ResourceID per le risorse del progetto
&#x200B;* [Scripting]&#x200B;[Python] Consenti query sulle informazioni del canale
&#x200B;* [Scripting]&#x200B;[Python] Aggiungi le funzioni di esecuzione a secco e di richiamata per simulare l’esportazione di texture

**Corretto:**

&#x200B;* [Panettieri] Normali non corrette in World Space Normals panettiere utilizzando una mappa normale tangente in casi specifici
&#x200B;* [Bakers] Errore di baking Occlusione ambiente con Optix quando non si verifica un poly elevato
&#x200B;* [Tratti dinamici] Ritardo durante il caricamento di un set di texture specifico
&#x200B;* [Export] Non deve esportare i set di texture disabilitati per USD, glTF
&#x200B;* [Scripting]&#x200B;[JavaScript] Impossibile modificare le nuove impostazioni di Curvature Baker
&#x200B;* [Scripting]&#x200B;[JavaScript] alg.texturesets.addChannel() in alcuni casi non restituisce un errore
&#x200B;* [Scripting]&#x200B;[JavaScript] Errore di battitura nella documentazione delle API Javascript per setProjectExportOptions()
&#x200B;* [Scripting]&#x200B;[JavaScript] Esporta sempre tutti i set di texture
&#x200B;* [Scripting]&#x200B;[Python] l&#39;eseguibile sys.restituisce un percorso a python.exe anziché a Substance Painter
&#x200B;* Cache delle texture non compatibile tra i sistemi operativi Mac e Windows/Linux
&#x200B;* [Livelink UE4] Solo l&#39;ultimo materiale viene utilizzato per tutti i set di texture in una trama combinata

**Problemi noti:**

&#x200B;* [Export]&#x200B;[Dimension]&#x200B;[Skecthfab] Non deve esportare i set di texture disattivati
&#x200B;* [Arresto anomalo] Cambia shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.1 (2020.1.1)

*(Rilasciato il 5 maggio 2020)*
Riepilogo: **Hotfix**

**Aggiunto:**

&#x200B;* [Esporta] Feedback visivo sullo stato sostituito su TextureSet

**Corretto:**

&#x200B;* [Esporta] La finestra di Esportazione è troppo grande per un monitor con risoluzione speciale e non può essere ridimensionata
&#x200B;* Opzioni di esportazione non salvate dopo l’esportazione
&#x200B;* [Esporta] Arresto anomalo o impossibile esportare con il predefinito di esportazione &quot;dalla cache&quot;
&#x200B;* [Esportazione] L’annullamento dell’esportazione genera un’ulteriore mappa vuota imprevista
&#x200B;* [Esporta] Correggere le impostazioni predefinite di esportazione virtuale
&#x200B;* [Python] PYTHONPATH env var non è considerato
&#x200B;* [Python]&#x200B;[Export] Se si annulla l’esportazione tramite Python, viene restituito un errore di eccezione
&#x200B;* [Python]&#x200B;[Export] export\_project\_texture un risultato errato con il formato di file psd
&#x200B;* [Baker] Arresto anomalo su Linux con Raytracing GPU

**Problemi noti:**

&#x200B;* [JavaScript] Impossibile modificare le nuove impostazioni del baker di curvatura
&#x200B;* [JavaScript]&#x200B;[Esporta] Esporta sempre tutti i set di texture
&#x200B;* [Export]&#x200B;[USD] Non deve esportare i set di texture disattivati
&#x200B;* [Arresto anomalo] Cambia shader dopo aver dipinto una maschera in livelli di materiale

### 6.1.0 (2020.1.0)

*(Rilasciato il 22 aprile 2020)*
Riepilogo: **Versione principale con nuova esportazione di texture e trama (con spostamento e tassellatura), srotolamento UV aggiornato con più controlli, nuovi baker, nuova API Python di scripting, migliore esperienza utente per la proiezione delle decalcomanie e nuovi contenuti**

**Aggiunto:**

&#x200B;* Nuova esportazione di texture e trama
&#x200B;* [Export] Nuova interfaccia di esportazione
&#x200B;* [Esportazione]&#x200B;[Scheda Esportazione] Consente di selezionare i canali di mappe da esportare per set di texture
&#x200B;* [Esporta]&#x200B;[Scheda Esporta] Consenti di modificare le dimensioni del set di texture per tutti i set di texture con un&#39;unica azione
&#x200B;* [Esportazione]&#x200B;[Scheda Esportazione] Consente un modello diverso per set di texture (tranne USD, glTF, Sketchfab e Dimension)
&#x200B;* [Esportazione]&#x200B;[Scheda Esportazione] Attivazione e disattivazione rapida di mappe e set di texture
&#x200B;* [Export]&#x200B;[Export tab] La risoluzione di esportazione 8192x8192 non è più sperimentale
&#x200B;* [Export]&#x200B;[Scheda Esportazione] Consente la modifica del formato del file e della profondità di bit per mappa
&#x200B;* [Esporta]&#x200B;[Scheda Esporta] Consente di ripristinare i valori dei parametri predefiniti
&#x200B;* [Esporta]&#x200B;[Scheda Esportazione] Consente di salvare le impostazioni senza esportare
&#x200B;* [Esporta]&#x200B;[scheda Modelli di output] Rinomina la scheda &quot;Configurazione&quot; in &quot;Modelli di output&quot;
&#x200B;* [Esporta]&#x200B;[scheda Modelli di output] Consenti la definizione del formato del file e della profondità di bit per mappa predefinita
&#x200B;* [Export]&#x200B;[Scheda Elenco esportazioni] Nuova scheda di anteprima per riepilogare e visualizzare il processo di esportazione
&#x200B;* [Importa/Esporta trama] Ottimizzazione delle prestazioni in termini di tempo di importazione/esportazione
&#x200B;* [Trama di esportazione] Trama di esportazione in FBX
&#x200B;* [Esporta trama] Esporta trama con spostamento e tassellatura
&#x200B;* [Esporta trama]&#x200B;[UI] Nuove impostazioni per il ricalcolo del vertice normale, applica la triangolazione
&#x200B;* [Esporta trama] Esporta la topologia di trama originale con i nuovi UV generati dallo srotolamento automatico
&#x200B;* Aggiornamento dello srotolamento UV automatico con più controlli
&#x200B;* [Srotolamento UV]&#x200B;[UI] Aggiungi impostazione per attivare lo srotolamento UV automatico nella nuova finestra del progetto
&#x200B;* [Srotolamento UV]&#x200B;[UI] Nuove opzioni per controllare i passaggi di srotolamento (cuciture, srotolamento, impacchettamento)
&#x200B;* [Srotolamento UV]&#x200B;[UI] Consente la conservazione delle giunture di srotolamento esistenti/srotolamento/impacchettamento
&#x200B;* [Srotolamento UV]&#x200B;[UI] Nuove opzioni per ricalcolare completamente i passaggi di srotolamento
&#x200B;* [Srotolamento UV]&#x200B;[UI] Nuova opzione per controllare le dimensioni del margine (nessuno, piccolo, medio e grande)
&#x200B;* Nuovi fornai
&#x200B;* [Pannelli] Sostituisci la vecchia curvatura con la nuova curvatura dalla trama
&#x200B;* [Panettieri] Aggiungi l&#39;opzione Corrispondenza per nome per ignorare il backface nel panettiere &quot;Occlusione ambientale&quot;
&#x200B;* [Baker] Aggiungi opzione piano terreno nel baker &quot;Occlusione ambientale&quot;
&#x200B;* Nuova API Python per scripting (3.7.6)
&#x200B;* [Python]&#x200B;[UI] Nuovo menu di script per Python
&#x200B;* [Python]&#x200B;[UI] Nuova documentazione Python nel menu Aiuto
&#x200B;* [Python] Esposizione dei moduli pitone delle Substance Painter: substance\_painter, alg, display, project.setting, project, texturesets, ui
&#x200B;* [Python] Esporre il nuovo modulo Python &quot;substance\_painter&quot;
&#x200B;* [Python] Esporre il nuovo sottomodulo Python: alg, display, log, project, resource, texturesets, ui
&#x200B;* [Python] Listener per modifiche al progetto
&#x200B;* [Python] Nuovi esempi nella documentazione Python
&#x200B;* Menu dei plug-in [JavaScript]&#x200B;[UI] sostituito da JavaScript
&#x200B;* [Finestra vista] Consente la creazione di una proiezione decalcomania &quot;trascinando/rilasciando + ALT&quot; una risorsa dallo scaffale
&#x200B;* Nuovo contenuto
&#x200B;* [Content] 5 nuovi materiali decalcomanie da Substance Source
&#x200B;* [Content] Aggiungi nuovi modelli di progetto ed esporta predefiniti per il modulo di rendering Maxwell
&#x200B;* [Content] Aggiungi modello di progetto per esportazione Keyshot 9
&#x200B;* [Content] Aggiorna il predefinito di esportazione Keyshot 9 per supportare spostamento e emissivo
&#x200B;* [Content]&#x200B;[Esportazione] Aggiornamento di tutti i predefiniti di esportazione in base alle versioni più recenti dei motori grafici e dei moduli di rendering per giochi
&#x200B;* [Content]&#x200B;[Esportazione] Aggiornate i file dei predefiniti di esportazione per utilizzare il nuovo formato e le impostazioni del dithering
&#x200B;* [Content] Nuovi modelli e shader per supportare il materiale VRay (VRayMtl)
&#x200B;* [Pila livelli] Consenti l&#39;eliminazione degli effetti di livello utilizzando l&#39;icona del cestino o la scelta rapida da tastiera della tastiera Elimina
&#x200B;* Rimuovere la Substance Source del plug-in (utilizzare il modulo di avvio con la funzionalità &quot;Invia a&quot;)
&#x200B;* [Windows] Non visualizzare l&#39;avviso TDR sulle GPU di fascia alta

**Corretto:**

&#x200B;* Problemi di traduzione nella finestra di dialogo Nuovo file di progetto
&#x200B;* [Baker] L’impostazione &quot;Salva file di scena preelaborato&quot; non funziona più
&#x200B;* [Proiezione planare] La proiezione non funziona su trame con UV ripetuti
&#x200B;* [Decal] Differenza di comportamento nel canale normale quando si utilizzano diverse modalità di proiezione del livello di riempimento
&#x200B;* [Sfumino]&#x200B;[Clona] È possibile che si verifichi un artefatto quando si disegna in una maschera
&#x200B;* [Engine] Arresto anomalo con contenuti di livello specifici
&#x200B;* [Engine] Arresto anomalo casuale quando si disegna in alcuni casi
&#x200B;* [Punto di ancoraggio] Il riferimento a una maschera vuota restituisce sempre il bianco
&#x200B;* [Esporta] Livello non preso in considerazione in alcune particolari configurazioni dello stack
&#x200B;* [Trama di esportazione] Impossibile esportare con un percorso contenente caratteri speciali
&#x200B;* [Esporta mesh] Impossibile leggere i file glTF quando esportati da Linux o MacOS
&#x200B;* [Importa trama] La reimportazione di DAE, PLY o glTF non funziona come previsto

**Problemi noti:**

&#x200B;* [Scripting]&#x200B;[JavaScript] Impossibile modificare le nuove impostazioni di Curvature Baker
&#x200B;* [Bakers] Arresto anomalo di Linux con Raytracing GPU
&#x200B;* [Export]&#x200B;[USD] Non deve esportare i set di texture disattivati
&#x200B;* [Arresto anomalo] Cambia lo shader dopo aver dipinto una maschera in livelli di materiale

## Versione 5

### 5.3.3 (2019.3.3)

*(Rilasciato il 6 febbraio 2020)*
Riepilogo: **Correzione rapida con aggiornamento a Iray 2019.3**

**Aggiunto:**

&#x200B;* Aggiornamento a Iray 2019.3
&#x200B;* [Log] Indica bios obsoleto per la CPU Ryzen che causa l&#39;arresto anomalo durante la cottura
&#x200B;* [ABR] Estrarre ABR alfa allo scaffale

**Corretto:**

&#x200B;* [Baker] La Esegue i baking non riesce se la trama High-Poly non ha UV
&#x200B;* [Linux] Le scelte rapide personalizzate del mouse non vengono salvate
&#x200B;* [Pennello] Il contorno scompare con alcune forme alfa
&#x200B;* [Tablet] Rilevamento errato durante lo spostamento dei cursori
&#x200B;* [Scelte rapide] Impossibile impostare una scelta rapida da tastiera con &quot;Ctrl+Alt+MouseClick&quot;
&#x200B;* [Shelf] Impossibile visualizzare la descrizione comando della risorsa quando si utilizza una tavoletta a penna
&#x200B;* [Vista 2D]&#x200B;[Esporta] Il predefinito Vista 2D non tiene conto delle informazioni normali
&#x200B;* Si verifica un blocco con quando si disegna in allineamento UV con determinati pennelli
&#x200B;* Colorare sotto un filtro crea un artefatto sul tratto in corso
&#x200B;* [Finestra vista] Cache delle texture errata nella finestra della vista dopo la reimportazione di una trama
&#x200B;* [Arresto anomalo] Errore durante il salvataggio dopo l’esportazione in Photoshop
&#x200B;* [Arresto anomalo] Scrittura di simboli speciali nel prefisso durante l’importazione delle risorse
&#x200B;* [Arresto anomalo] Fai clic sul riferimento in Proprietà punto di ancoraggio
&#x200B;* [Punti di ancoraggio] Il canale non si aggiorna quando è presente un filtro tra il punto di ancoraggio e il riferimento
&#x200B;* Il collegamento dell’URL del raggio nel menu Aiuto non funziona

**Problemi noti:**

&#x200B;* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
&#x200B;* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
&#x200B;* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
&#x200B;* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
&#x200B;* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
&#x200B;* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
&#x200B;* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV

### 5.3.2 (2019.3.2)

*(Rilasciato: 21 gennaio 2020)*
Riepilogo: **Bugfix**

**Corretto:**

&#x200B;* L’apertura di un progetto che è stato salvato in modalità solo canale non visualizza la trama
&#x200B;* Il riquadro di visualizzazione non viene sempre aggiornato quando si disegna sotto il livello utilizzando lo strumento Clona

**Problemi noti:**

&#x200B;* [Baker] Arresto anomalo relativo al multithreading su CPU Ryzen
&#x200B;* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
&#x200B;* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
&#x200B;* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
&#x200B;* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
&#x200B;* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
&#x200B;* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
&#x200B;* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV

### 5.3.1 (2019.3.1)

*(Rilasciato: 20 dicembre 2019)*
Riepilogo: **Hotfix**

**Corretto:**

&#x200B;* Arresto anomalo quando si lavora su trame con Proiezioni UV specifiche
&#x200B;* [ABR] Arresto anomalo quando si passa da un predefinito Photoshop a un altro
&#x200B;* [Linux] Impossibile avviare Substance Painter su CentOS 7.4 a causa di un problema di dipendenza libGLX
&#x200B;* [Baker] Arresto anomalo durante la esegue i baking dopo aver utilizzato File > Pulisci
&#x200B;* [Baker] La finestra di dialogo di avanzamento Eseguita i baking si blocca dopo l’annullamento
&#x200B;* [Baker] La Esegue i baking della trama dopo l’esportazione delle texture non funziona
&#x200B;* [Baker] L’uso dei risultati &quot;Corrispondenza per nome&quot; con le mappe trama nere
&#x200B;* [Baker] Gabbia non presa in considerazione
&#x200B;* [Shelf] L’importazione di file PSD genera immagini danneggiate
&#x200B;* [Sample] Il progetto di esempio &quot;Mat&quot; ha videocamere danneggiate e un predefinito di esportazione errato

**Problemi noti:**

&#x200B;* [Baker] Arresto anomalo relativo al multithreading su CPU Ryzen
&#x200B;* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
&#x200B;* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
&#x200B;* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
&#x200B;* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
&#x200B;* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
&#x200B;* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
&#x200B;* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV

### 5.3.0 (2019.3.0)

*(Rilasciato: 17 dicembre 2019)*
Riepilogo: **Versione principale con miglioramento dell’esperienza utente di pittura a mano, utilizzo dei tablet, srotolamento automatico degli UV nella versione beta (0.3.0) e diversi nuovi contenuti per la pittura a mano**

**Aggiunto:**

&#x200B;* Integrazione dello srotolamento UV automatico della versione 0.3.0 in Substance Painter
&#x200B;* [Srotolamento UV] Srotolamento UV automatico nella Substance Painter quando non sono presenti UV o UV parziali
&#x200B;* [Srotolamento UV] Un&#39;impostazione globale per attivarla e disattivarla
&#x200B;* [Annullamento del wrapping UV] Versione riportata nel file di log
&#x200B;* [Annullamento UV]&#x200B;[UI] Indica l&#39;avanzamento dello srotolamento UV
&#x200B;* [UI] Nuove impostazioni nella barra degli strumenti contestuale per selezionare l&#39;anteprima del pennello: anteprima completa, contorno del pennello e mirino
&#x200B;* [Tool] Nuovo metodo di fusione avanzato nella sezione alfa: Schiarisci (Massimo) oltre a Normale
&#x200B;* [Serie di livelli] Opzione di correzione gamma per livello per canale alfa o maschera (menu di scelta rapida)
&#x200B;* [Layer Stack]&#x200B;[UI] Aggiungi icona &quot;i&quot; quando un livello alfa è corretto dal gamma
&#x200B;* [Tablet]&#x200B;[Strumento] Esporre la pressione minima per le dimensioni e il flusso
&#x200B;* [Tablet]&#x200B;[UI] Nuova impostazione nella barra degli strumenti contestuale per selezionare la pressione della curva: lineare, intuitivo, intuitivo
&#x200B;* [Tablet]&#x200B;[UX] Aggiungi Ctrl+Alt+clic per scorrere
&#x200B;* Importare pennelli predefiniti di Photoshop (formato ABR)
&#x200B;* [ABR] Supporta i parametri Shape
&#x200B;* [ABR] Supporta i parametri della dinamica delle forme
&#x200B;* [ABR] Parametri di trasferimento del supporto
&#x200B;* [ABR] Supporta i parametri di dispersione
&#x200B;* [ABR]&#x200B;[Tratti dinamici] Supporta rotondità e capovolgimento
&#x200B;* [ABR]&#x200B;[Shelf] Esporre la struttura di cartelle dei pennelli nell&#39;Editor filtri
&#x200B;* [ABR]&#x200B;[Ripiano] Aggiungere l’icona di Photoshop nelle miniature
&#x200B;* [ABR]&#x200B;[Shelf] Aggiungi un elenco di parametri non supportati nella miniatura dettagliata ABR
&#x200B;* [Strumento]&#x200B;[Tratti dinamici] Nuova impostazione del tratto dinamico per controllare il numero di inizializzazione casuale da generare
&#x200B;* [Tool]&#x200B;[UI] Aggiungi nuove impostazioni di distribuzione e asse per la variazione di dispersione
&#x200B;* [Scelta rapida] Aggiungi Ctrl+Maiusc+B per aprire la finestra Baking
&#x200B;* [UI]&#x200B;[Menu] Aggiungi voce nel menu &quot;Modifica&quot; per aprire la finestra Baking
&#x200B;* [UI]&#x200B;[Impostazioni] Miglioramento dell’allineamento dell’elenco delle scelte rapide
&#x200B;* [UI] Sostituire le icone dei controlli pressione (dimensioni e flusso) con i pulsanti di attivazione/disattivazione
&#x200B;* [Riquadro di visualizzazione] Consente di mettere a fuoco separatamente il riquadro di visualizzazione 2D e 3D
&#x200B;* Aggiornamento a QT 5.12.5
&#x200B;* [UI] Indica l&#39;avanzamento del caricamento della trama
&#x200B;* [Substance] Aggiungi il supporto per l&#39;intervallo non bloccato e morbido con i cursori
&#x200B;* [Substance] Aumenta la precisione dei parametri della Substance fino a 6 decimali
&#x200B;* [Substance] Tenere conto della fase definita da un parametro
&#x200B;* [Substance] Ottimizzazione della generazione di tratti dinamici con supporto delle condizioni nei dati utente
&#x200B;* [Substance] Consenti di designare un output del grafico come maschera per tutti i canali tramite dati utente
&#x200B;* [Content] Aggiorna il progetto di esempio &quot;Mat&quot; con topologia descrittiva per lo spostamento, nuova mappa ID e nuove fotocamere
&#x200B;* [Content] Integrare 3 nuovi filtri (MatFx): fumetto, acquerello, Dipinto a olio (ispirato al lavoro di Emrecan Cubukcu)
&#x200B;* [Contenuto] Integra 102 pennelli predefiniti di Photoshop dai pacchetti di Kyle T. Webster
&#x200B;* [Content] Integrate 18 nuovi predefiniti per i pennelli: Freccia del rullo di pittura, Testo di avvertenza del rullo di pittura, Carboncino fine e altri ancora
&#x200B;* [Contenuto] Integrazione di 9 nuove alfa: rullo di pittura del creatore di pennelli, Photoshop del creatore di pennelli, pattern di pennelli e altro ancora
&#x200B;* [Content] Integrate 2 nuovi strumenti predefiniti: Gouache Dense e Gouache Faded
&#x200B;* [Content] Integra 1 nuovo generatore : Controllo UV (Isole UV di evidenziazione e cuciture)
&#x200B;* [Content] Integra 2 nuovo predefinito di esportazione: Keyshot 9+ e Spark AR Studio
&#x200B;* [Content] Integra 1 nuovo modello di progetto : Spark AR Studio (Facebook)

**Corretto:**

&#x200B;* [Tablet] L&#39;annullamento dei tratti dello stilo (CTRL+Z) è più lento dell&#39;annullamento dei tratti del mouse
&#x200B;* [Tablet] Pressione iniziale e finale non considerate quando si disegna una linea retta
&#x200B;* [Tablet] Il primo timbro viene disegnato due volte quando si utilizza una linea retta
&#x200B;* [Tablet] Supporto migliorato per le scelte rapide da tastiera per Huion
&#x200B;* [Tablet] Supporto migliorato per i pulsanti penna Huion
&#x200B;* [Tablet] Scostamento tra l&#39;anteprima del pennello e il timbro disegnato
&#x200B;* [Tablet] In rari casi, le scelte rapide per modificare i pennelli a penna comportano prestazioni ridotte
&#x200B;* [Tablet] Ritardo quando si disegna su un livello specifico
&#x200B;* In rari casi, quando si cambia finestra, possono verificarsi texture sfocate
&#x200B;* [UI]&#x200B;[Substance] Gli input dell’immagine non vengono sempre visualizzati
&#x200B;* L’opzione Pulisci non rimuove dal ripiano i predefiniti importati in un progetto
&#x200B;* [Strumento]&#x200B;[Tratto dinamico] Problema di prestazioni durante l&#39;ottimizzazione del conteggio dei cicli del timbro
&#x200B;* In rari casi, problemi di aggiornamento durante l’uso della modalità finestra vista 3D/2D
&#x200B;* Colorare un tratto molto lungo può portare a un blocco
&#x200B;* [Tool] Problema di prestazioni quando si disegna con tratti dinamici specifici
&#x200B;* [UI] Nella barra degli strumenti contestuale vengono ancora visualizzate le proprietà del pennello durante la selezione di una cartella
&#x200B;* I valori dell&#39;asse delle simmetrie non vengono ripristinati
&#x200B;* L’importazione di texture EXR con valori a virgola mobile è completamente nera
&#x200B;* Alt + clic su un canale per isolare non funziona per filtro e generatore
&#x200B;* [Esporta] arresti anomali di progetto specifici all’esportazione
&#x200B;* [Substance] Valore predefinito errato nel menu a discesa se il parametro è nascosto da Visible If
&#x200B;* [Shader] I canali definiti tramite la creazione di livelli di materiale non sono ordinati allo stesso modo nell’interfaccia utente
&#x200B;* [Shelf] I metadati dei predefiniti non vengono salvati sul disco

**Problemi noti:**

&#x200B;* [Srotolamento UV] L&#39;elaborazione di maglie poly elevate può richiedere molto tempo
&#x200B;* [Srotolamento UV] Vertici con le stesse coordinate vengono uniti
&#x200B;* [Srotolamento UV] La generazione UV potrebbe non riuscire su alcune parti della trama in alcuni rari casi
&#x200B;* [Srotolamento UV] Rapporto testello non uniforme o altamente distorto in una singola Isola UV in alcuni casi
&#x200B;* [Srotolamento UV] Rapporto di testo non uniforme tra set di texture
&#x200B;* [Srotolamento UV] L&#39;Isola UV generata può essere molto allungata e in alcuni casi non si adatta allo spazio UV
&#x200B;* [Srotolamento UV] Le facce degenerate o non triangolari con bordi piccoli o sovrapposti potrebbero non ottenere lo srotolamento UV
&#x200B;* L’esempio di riunione presenta alcuni problemi con le videocamere importate

### 5.2.3 (2019.2.3)

*(Rilasciato il 23 ottobre 2019)*
Riepilogo: **Versione Bugfix**

**Aggiunto:**

&#x200B;* Pulsante Aggiungi [Texture Set List] per attivare/disattivare rapidamente la modalità di attivazione
&#x200B;* [Log] Aggiungere il numero di versione di Windows 10 nel file di log
&#x200B;* Aggiornamento alla versione più recente di Substance Engine
&#x200B;* [MacOS] Ha autenticato il software per soddisfare i nuovi requisiti di distribuzione di MacOS Catalina

**Corretto:**

&#x200B;* [Plugin] L&#39;origine del plug-in non funziona
&#x200B;* [MacOS]&#x200B;[Shader] Mac OS 10.14.5 e AMD: la creazione di livelli di materiale non funziona come previsto

**Problemi noti:**

&#x200B;* Impossibile importare file alembici con suddivisioni
&#x200B;* Rari arresti anomali durante l’importazione di alcuni file Alembic
&#x200B;* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.2 (2019.2.2)

*(Rilasciato il 20 settembre 2019)*
Riepilogo: **Versione Bugfix**

**Corretto:**

&#x200B;* L&#39;importazione di risorse tramite script può provocare un arresto anomalo
&#x200B;* [Plugin] Il download di materiale dall’origine può provocare un arresto anomalo

**Problemi noti:**

&#x200B;* Impossibile importare file alembici con suddivisioni
&#x200B;* Arresti anomali rari durante l’importazione di alcuni file Alembic
&#x200B;* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.1 (2019.2.1)

*(Rilasciato: 17 settembre 2019)*
Riepilogo: **Versione Bugfix**

**Corretto:**

&#x200B;* [Mac]&#x200B;[USD] Impossibile aprire i file USDZ esportati da MacOS
&#x200B;* [Set di texture] Impossibile isolare un set di texture con il modificatore ALT
&#x200B;* [Shelf] I predefiniti, i Materiali avanzati e le Maschere avanzate vengono sempre modificati quando si esce dall’applicazione
&#x200B;* [Pila livelli] Impossibile selezionare l’effetto dopo aver eliminato un altro effetto
&#x200B;* Sfarfallio quando si utilizza un cursore all’interno del pannello delle proprietà dello strumento
&#x200B;* Arresto anomalo durante l’esportazione dei predefiniti nello scaffale
&#x200B;* Arresto anomalo quando si esporta un predefinito con spazio insufficiente
&#x200B;* Arresto anomalo durante la creazione di un predefinito con spazio insufficiente

**Problemi noti:**

&#x200B;* Impossibile importare file alembici con suddivisioni
&#x200B;* Arresti anomali rari durante l’importazione di alcuni file Alembic
&#x200B;* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.2.0 (2019.2.0)

*(Rilasciato: 25 luglio 2019)*
Riepilogo: **Versione principale con aggiornamenti dei baker in termini di prestazioni e una nuova modalità di previsualizzazione + nuovi contenuti**

**Aggiunto:**

&#x200B;* [Baker] È stato aggiunto il supporto per Raytracing GPU con DXR e OptiX (Occlusione ambientale, Thickness)
&#x200B;* [Baker] Ottimizzazioni e accelerazioni per il Raytracing CPU
&#x200B;* [Baker]&#x200B;[Modalità Vis]&#x200B;[UI] Nuova modalità di visualizzazione eseguita i baking nella finestra della vista
&#x200B;* [Baker]&#x200B;[Preferenze]&#x200B;[UI] Nuova opzione di esegue i baking per abilitare/disabilitare il Raytracing GPU
&#x200B;* [Baker]&#x200B;[UI] Rielaborazione della finestra di dialogo barra di avanzamento
&#x200B;* [Baker] Miglioramento dei messaggi di avviso e di errore
&#x200B;* [Baker] Consenti un annullamento più reattivo del processo di esegue i baking
&#x200B;* [Baker] Riapri la finestra di esegue i baking dopo aver fatto clic su Annulla
&#x200B;* [Proj]&#x200B;[UX] Miglioramento dell&#39;usabilità del manipolatore di rotazione
&#x200B;* [Settings] Opzione per migliorare le prestazioni riducendo la risoluzione del viewport per schermi HDPI
&#x200B;* [Scripting] Modificare la risoluzione del set di texture
&#x200B;* [Scripting] Ottieni set di texture selezionato
&#x200B;* [Scripting] Consente di selezionare un set di texture
&#x200B;* [Scripting] Funzione per sapere quando la selezione del set di texture è stata modificata
&#x200B;* [Shelf] Aggiunti 40 nuovi materiali avanzati
&#x200B;* [Shelf] Aggiunte 20 nuove maschere avanzate

**Corretto:**

&#x200B;* [Pila livelli] Blocco dell’interfaccia utente durante la selezione multipla dei livelli
&#x200B;* [Pila livelli] Il raggruppamento di numerosi livelli blocca l’interfaccia utente più a lungo del solito
&#x200B;* [Pila livelli] In alcuni casi è possibile selezionare contemporaneamente un livello e un effetto
&#x200B;* I grafici delle Substance utilizzati negli strumenti di pittura non vengono generati alla risoluzione giusta
&#x200B;* [Baker] Il pulsante &quot;Esegue i baking tutti i set di texture&quot; non è disattivato quando non è selezionato alcun baker
&#x200B;* [MacOS] Disattiva il messaggio di avviso sulla tassellatura
&#x200B;* Lo strumento Proiezione non ha un’anteprima quando viene utilizzato con una maschera
&#x200B;* Arresti anomali e progetti danneggiati durante il tentativo di salvataggio con spazio su disco insufficiente
&#x200B;* [Shelf] Arresto anomalo durante l&#39;importazione di una risorsa su disco tramite shelf con spazio insufficiente
&#x200B;* [Shelf] Arresto anomalo durante il ripristino del predefinito di sessione
&#x200B;* [Shelf] L’importazione di un predefinito con un nome che termina con uno spazio genera un arresto anomalo
&#x200B;* [Shelf] L&#39;importazione di una risorsa con un prefisso che termina con uno spazio vuoto genera un arresto anomalo

**Problemi noti:**

&#x200B;* Impossibile importare file alembici con suddivisioni
&#x200B;* Arresti anomali rari durante l’importazione di alcuni file Alembic
&#x200B;* L’interfaccia utente temporaneamente non risponde quando si esegue i baking con DXR su GPU Pascal

### 5.1.3 (2019.1.3)

*(Rilasciato: 1 luglio 2019)*
Riepilogo: **Correzione rapida con 2 nuove funzioni**

**Aggiunto:**

&#x200B;* Consente di specificare il budget VRam con una riga di comando (ad esempio: budget vram 4096)
&#x200B;* [QML] Esporre le proprietà wrapMode ed elide dei pulsanti e delle caselle di controllo QML

**Corretto:**

&#x200B;* &quot;Segui tracciato&quot; non funziona sempre
&#x200B;* La mappatura dei canali non funziona con SBSAR utilizzato negli slot a canale singolo
&#x200B;* [Pila livelli] Prestazioni ridotte durante lo scorrimento con livelli nascosti
&#x200B;* arresto anomalo di [TextureSet] quando si fa clic tra maschere diverse
&#x200B;* Lo Spostamento [SVT] non viene visualizzato correttamente e in alcuni casi sfarfalla
&#x200B;* [Alembico] Arresto anomalo con trama che utilizza le normali dei punti invece delle normali dei vertici
&#x200B;* [Alembic]&#x200B;[Log] Segnala un errore nel log se il file Alembic non è supportato durante l&#39;importazione

**Problemi noti:**

&#x200B;* Impossibile importare file alembici con suddivisioni
&#x200B;* Arresti anomali rari durante l’importazione di alcuni file Alembic

### 5.1.2 (2019.1.2)

*(Rilasciato il 21 maggio 2019)*
Riepilogo: **Hotfix**

**Corretto:**

&#x200B;* Arresto anomalo quando si selezionano due risorse con un input di immagine

### 5.1.1 (2019.1.1)

*(Rilasciato il 20 maggio 2019)*
Riepilogo: **Hotfix**

**Aggiunto:**

&#x200B;* Aggiornamento alla versione più recente di Substance Engine con l’ultima versione di Substance Designer 2019.1

**Corretto:**

&#x200B;* [Substance] Visibile se non viene preso in considerazione per le immagini di input
&#x200B;* [SVT]&#x200B;[Motore] La modifica della risoluzione del set di texture porta in alcuni casi a un arresto anomalo
&#x200B;* [Engine] In alcuni casi compaiono texture nere casuali
&#x200B;* [Pila livelli]&#x200B;[UI] Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente
&#x200B;* [Pila livelli] L’opacità non ha effetto sull’effetto Pittura con il metodo di fusione Attraversa
&#x200B;* [Pila livelli] L’input del filtro Da Height a normale non si aggiorna correttamente con il tratto del pennello gomma
&#x200B;* [LayersStack] Arresto anomalo quando si annulla la rilascio di una maschera avanzata
&#x200B;* Sfarfallio del wireframe con ombre e anti-alias temporale attivati
&#x200B;* [Spostamento] Ritardo su AMD con alcune trame pesanti
&#x200B;* [Windows] Arresto anomalo quando si aprono alcuni progetti tramite Esplora file
&#x200B;* [Istogramma] Arresto anomalo durante la rimozione di una maschera con punto di ancoraggio in alcuni casi
&#x200B;* Arresto anomalo di generazione dell’anteprima in alcuni rari casi
&#x200B;* [Arresto anomalo] Impossibile riaprire un progetto con troppi strumenti di clonazione e sfumino
&#x200B;* Nessuna trama visualizzata in modalità materiale dopo il salvataggio in alcuni casi
&#x200B;* [Scripting] alg.mapexport.documentStructure() restituisce valori errati per le cartelle

**Problemi noti:**

&#x200B;* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione

### 5.1.0 (2019.1.0)

*(Rilasciato il 23 aprile 2019)*
Riepilogo: **Traccia dinamica con nuovi contenuti dedicati, Spostamento e tassellatura in tempo reale e irraggiamento, effetto Maschera di confronto, simmetria radiale, Planari e Proiezione sferica**

**Aggiunto:**

&#x200B;* [Strumento] Tratto dinamico: Substance la variazione lungo il tratto di un pennello
&#x200B;* [Tratto dinamico] Esposizione del nuovo parametro indice del timbro con le opzioni
&#x200B;* [Tratto dinamico] Tieni conto del parametro $time
&#x200B;* [Tratto dinamico] Genera un nuovo parametro $randomseed per tratto e per timbro
&#x200B;* [Tratto dinamico] Avvia un indice di tratto dinamico da un numero casuale
&#x200B;* [Tratto dinamico]&#x200B;[Scaffale] Aiuta a trovare una risorsa tratto dinamico con una nuova icona dedicata
&#x200B;* Spostamento e tassellatura nella finestra della vista in tempo reale
&#x200B;* Spostamento e tassellatura in Iray
&#x200B;* [Shader impostazioni]&#x200B;[UI] Nuova scheda per il controllo dello spostamento e della tassellatura
&#x200B;* [Pila livelli] Nuovo effetto Confronta maschera: genera una maschera confrontando due canali
&#x200B;* [Pila livelli]&#x200B;[UI] Nuova voce nel menu di scelta rapida &quot;Aggiungi maschera con combinazione di height&quot; per inserire un effetto CompareMask
&#x200B;* [Simmetria] Nuova modalità simmetria: pittura radiale
&#x200B;* [Simmetria impostazioni] Espandere entrambe le sezioni &quot;Impostazioni&quot; e &quot;Schermo&quot;
&#x200B;* [Simmetria impostazioni]&#x200B;[UI] Anteprima per pittura radiale
&#x200B;* Esporre due nuove modalità di proiezione: planare e sferica
&#x200B;* [Proj] Nuova modalità di ritaglio forma per tutte le proiezioni
&#x200B;* [Proj] Modalità Planari con nuovo manipolatore: strumento Superficie
&#x200B;* [Proj]&#x200B;[Scelta rapida da tastiera] Maiusc Scelta rapida da tastiera+W per strumento superficie
&#x200B;* [Proj] Maschera di proiezione Planare con sfoltimento profondità e taglio della superficie posteriore
&#x200B;* [Manipolatore] Miglioramento del manipolatore di rotazione su tutti e tre gli assi per il triplanare
&#x200B;* [Tool]&#x200B;[UX] Se si fa clic su un canale tenendo premuto il tasto Alt, tale canale viene attivato o disattivato
&#x200B;* [Engine] Aggiornamento alla versione più recente di Substance Engine
&#x200B;* [Set di texture] Selezione multipla e modifica della risoluzione
&#x200B;* [Set di texture] Attivazione e disattivazione rapida dei set di texture
&#x200B;* [Set di texture] Combina solo e tutte le opzioni in un nuovo menu
&#x200B;* [Set di texture]&#x200B;[Pila livelli] Icona Nuova per attivazione e disattivazione
&#x200B;* [Pila livelli]&#x200B;[UX] Inserisci effetti al di sopra di quelli già selezionati
&#x200B;* [Pila livelli]&#x200B;[UI] Rielaborare lo stile di selezione della vista Pila livelli
&#x200B;* [Pila livelli] Per impostazione predefinita, il metodo di fusione per i livelli istanziati è ora impostato sul metodo Attraversa
&#x200B;* Opzione [Esporta] per attivare e disattivare il dithering
&#x200B;* [Plugin] Supporta il modificatore di precisione per i cursori (SHIFT)
&#x200B;* [Plugin]&#x200B;[UI] Nuova icona per il salvataggio automatico
&#x200B;* [Scripting] Elenca il contenuto di una cartella
&#x200B;* [Scripting] Consente l’eliminazione dei file
&#x200B;* [Scripting] Leggi tutte le informazioni sullo stack, incluse le risorse utilizzate
&#x200B;* [Contenuto]&#x200B;[Tratto dinamico] Nuovi strumenti e pennelli predefiniti
&#x200B;* [Contenuto]&#x200B;[Tratto dinamico] Due nuove sfumature procedurali: Tonalità sfumatura e Generatore sfumatura
&#x200B;* [Contenuto] 11 nuovi filtri: Pittura di pelatura MatFx, gocce d&#39;acqua MatFx e altro ancora
&#x200B;* [Content] 7 nuovi generatori: Cucitrice automatica, Colore casuale UV, Densità texel UV e altro ancora
&#x200B;* [Contenuto] 93 nuove alfa: nuovi testi, frecce e varie altre forme
&#x200B;* [Content] 2 nuove procedure: Tonalità sfumatura, Generatore sfumatura e altro ancora
&#x200B;* [Contenuto] 21 nuovi strumenti e pennelli predefiniti per Tratti dinamici : Ciottoli, Impronte, Spruzzo e altro ancora
&#x200B;* [Content] 2 Nuove HDR: terreno di Canopus e foresta autunnale
&#x200B;* [Content] Aggiorna il contenuto con la cura del seme casuale nello scaffale
&#x200B;* [Content] Nuova icona con parametro di inizializzazione casuale esposto nello scaffale

**Corretto:**

&#x200B;* La Pila livelli [serie di livelli] continua a trascinare per sempre
&#x200B;* [Mac] &quot;Mostra nel Finder&quot; può portare al blocco
&#x200B;* [Scripting] Le impostazioni salvate tramite l’interfaccia utente personalizzata vengono perse se il file di shader viene spostato
&#x200B;* [Scripting] Il numero di versione dell’API non è corretto e non aggiornato
&#x200B;* [Effetto] Il contenuto dell’istogramma non viene visualizzato correttamente
&#x200B;* [Effetto] In alcuni casi l’effetto Istogramma non si aggiorna
&#x200B;* [Ripiano] I punti non sono allineati correttamente sul materiale &quot;Plastic Fabric Pyramid&quot;

**Problemi noti:**

&#x200B;* Facendo doppio clic sul nome del set di texture, questo viene selezionato prima di passare alla modalità di ridenominazione
&#x200B;* [Pila livelli]&#x200B;[UI] Alternando una maschera con MAIUSC è possibile selezionare più livelli contemporaneamente

## Versione 4

### 4.3.3 (2018.3.3)

*(Rilasciato il 7 marzo 2019)*
Riepilogo: **bugfix**

**Aggiunto:**

&#x200B;* [Content] Integrazione del nuovo modello di progetto: &quot;PBR - Rugosità metallica fusione Alpha&quot;
&#x200B;* L&#39;ordine di ricerca delle librerie dinamiche Linux è stato modificato per assegnare priorità alle librerie nella directory di installazione prima di ciò che è installato sul sistema

**Corretto:**

&#x200B;* La trama a volte scompare dalla finestra della vista 3D (premete F per reimpostare la videocamera)
&#x200B;* Aggiornate Substance Painter caricatore Sketchfab con i nuovi tipi di licenza Sketchfab
&#x200B;* [Import]&#x200B;[glTF] Gestione errata della modulazione della texture di input come definita nei file glTF
&#x200B;* [Import]&#x200B;[glTF] In alcuni casi il piano terreno viene visualizzato in modo errato con l&#39;importazione glTF
&#x200B;* [Esporta]&#x200B;[USD] L’opacità non funziona in Arkit
&#x200B;* [Esportazione]&#x200B;[USD] arresti anomali di esportazione USDz in alcuni casi
&#x200B;* [Export]&#x200B;[USD] L’esportazione in USD senza salvare causa l’arresto anomalo
&#x200B;* [Esporta]&#x200B;[USD] Modalità di suddivisione errata per le texture, modalità di suddivisione per trame e tipi di output per gli ombreggiatori
&#x200B;* [Esporta]&#x200B;[USD] Esportazioni sparse solo di alcuni set di texture con tutta la geometria
&#x200B;* [Istanza] Arresto anomalo quando si tenta di eliminare un livello di istanza interrotto
&#x200B;* [Regressione]&#x200B;[Esporta] Alcune mappe non vengono esportate nella profondità di bit scelta
&#x200B;* [Linux] Problema con la libreria libtbb.so.2

**Problemi noti:**

&#x200B;* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.2 (2018.3.2)

*(Rilasciato il 24 gennaio 2019)*
Riepilogo: **Correzione rapida con nuove funzioni (esportazione USDZ e filtro Texture nella finestra della vista)**

**Aggiunto:**

&#x200B;* [Esporta] Consente l’esportazione in USDZ
&#x200B;* [Finestra vista] Consenti di controllare la qualità della texture in Impostazioni schermo
&#x200B;* [Finestra vista] È stata aggiunta l&#39;impostazione di polarizzazione mip in Impostazioni schermo
&#x200B;* [Finestra vista] È stato aggiunto il filtro anisotropo in Impostazioni schermo
&#x200B;* [plug-in] Aggiorna i plug-in ufficiali per utilizzare lo stile di Substance Painter 2018
&#x200B;* [Licenza] Per impostazione predefinita, installa la licenza in una cartella utente

**Corretto:**

&#x200B;* Arresto anomalo collegato alla decompressione
&#x200B;* Aggiungi TAA sul materiale da solo
&#x200B;* Disturbo con ombreggiatura, prova di sensibilità TAA e alfa con dithering
&#x200B;* Rimuovere il dithering specular per tutti gli shader PBR classici
&#x200B;* In alcuni casi, arresto anomalo nelle impostazioni dello shader
&#x200B;* L’attivazione della dispersione non è sincronizzata tra i rendering OpenGL e Iray
&#x200B;* Gli strumenti Sfumino e Clona non funzionano più su trame specifiche
&#x200B;* Alcuni set di texture non possono essere visualizzati nel rendering dei raggi
&#x200B;* I set di texture rinominati non vengono salvati dopo la chiusura del progetto
&#x200B;* Wireframe gli artefatti durante il trascinamento dei materiali sulle mappe ID
&#x200B;* [Scripting] Creazione del percorso del file non forzata durante il salvataggio di un progetto
&#x200B;* [Scripting] Il callback &quot;onProjectAboutToSave()&quot; non funziona più
&#x200B;* Collegamenti al forum interrotti nella finestra di segnalazione dei bug

**Problemi noti:**

&#x200B;* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.3.1 (2018.3.1)

*(Rilasciato il 6 dicembre 2018)*
Riepilogo: **Hotfix**

**Aggiunto:**

&#x200B;* [Simmetria]&#x200B;[Finestra vista] La simmetria nella vista 2D è tornata ed ora presenta un&#39;anteprima del pennello clone fissa

**Corretto:**

&#x200B;* [Esporta] In alcuni casi, l’esportazione in vista 2D genera una texture nera
&#x200B;* [Iray] Le informazioni normali diventano errate in Iray dopo aver creato un&#39;istanza di un livello di materiale
&#x200B;* Gli insiemi di texture non quadrate possono causare in alcuni casi l’arresto anomalo
&#x200B;* [Annulla] Diversi Ctrl+Z possono causare in alcuni casi l&#39;arresto anomalo
&#x200B;* [QML] In alcuni casi AlgScrollView può creare un avviso nel registro (cicli di associazione)

**Problemi noti:**

&#x200B;* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
&#x200B;* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.3.0 (2018.3.0)

*(Rilasciato il 20 novembre 2018)*
Riepilogo: <b>Aggiornamenti del viewport, corretta esportazione dei Vista 2D, nuovi helper dell&#39;interfaccia utente, uno strumento di simmetria migliorato, nuovi contenuti e un enorme miglioramento delle prestazioni</b>

<b>Aggiunto:</b>

&#x200B;* [Anti-alias]&#x200B;[Finestra vista] Nuova anti-alias temporale di filtro per la finestra della vista 3D (tramite Impostazioni schermo)
&#x200B;* [Esporta] Esporta il contenuto della finestra della vista 2D come una singola texture
&#x200B;* [Export]&#x200B;[Dithering] Esporta dithering all’esportazione
&#x200B;* [Pila livelli] Colori su livelli e cartelle
&#x200B;* [Pila livelli] Attivazione e disattivazione rapida di più livelli ed effetti
&#x200B;* [Pila livelli] Navigazione più semplice per i metodi di fusione con i tasti su e giù e lo scorrimento del mouse
&#x200B;* [Proj]&#x200B;[UI] manipolatore di rotazione aggiuntivo su tutti e tre gli assi per triplanare
&#x200B;* [Proj]&#x200B;[Scelte rapide] - e + per modificare le dimensioni del manipolatore della Proiezione UV
&#x200B;* [Shader] Controlla i parametri dei livelli rivestiti con canali nello shader rivestito con PBR
&#x200B;* [Substance] Esposizione di nuovi input di texture basati su mesh per filtri e generatori
&#x200B;* [Simmetrie]&#x200B;[Viewport]&#x200B;[UI] Controlla lo scostamento della simmetria con i manipolatori
&#x200B;* [Simmetrie]&#x200B;[Barra degli strumenti contestuale]&#x200B;[UI] Nuovo pannello simmetria con opzioni
&#x200B;* [Simmetria] Nuova modalità di intersezione linee simmetria
&#x200B;* [Simmetria] Nuovo cursore clone simmetria
&#x200B;* [Simmetria]&#x200B;[Scelte rapide] Q per nascondere e -, + per modificare le dimensioni e MAIUSC per agganciare
&#x200B;* [Log] Migliora i messaggi di errore quando non è possibile esportare texture
&#x200B;* [Scripting] Consente di modificare o aggiornare le risorse in Impostazioni di visualizzazione
&#x200B;* [Scripting] Consente di creare o rimuovere i canali nei set di texture
&#x200B;* [Content]&#x200B;[Shaders] Aggiungi il supporto per l&#39;anisotropia con uno shader dedicato (pbr-metal-rough-anisotropia-angle)
&#x200B;* [Contenuto] Aggiornamento della sfera di anteprima con anisotropia e angolo modificato
&#x200B;* [Content] Shutline matFx aggiornato
&#x200B;* [Content] Nuova creazione di texture.Scansione del volto senza interruzioni in XYZ
&#x200B;* [Contenuto] Nuove procedure anisotrope
&#x200B;* [Content] Nuovo filtro: baked lighting environment
&#x200B;* [Content] Mappa del nuovo ambiente: studio automobilistico neutro
&#x200B;* [Content] Nuovo modello di progetto: PBR - Angolo di anisotropia di rugosità metallica (con canali di anisotropia)
&#x200B;* [Contenuto] Nuovo modello di progetto: PBR - rugosità metallica Coated
&#x200B;* [SVT]&#x200B;[Engine]: Texture virtuali sparse (SVT)
&#x200B;* [SVT]&#x200B;[Preferenze]&#x200B;[UI] Opzione di accelerazione del supporto hardware SVT
&#x200B;* [SVT]&#x200B;[Registro] Ulteriori informazioni sulla funzionalità di creazione di texture virtuali sparse (ad esempio, disco di dimensioni)
&#x200B;* [SVT]&#x200B;[UI] Finestra del messaggio all&#39;avvio se le dimensioni del disco sono troppo basse per la cache
&#x200B;* [SVT]&#x200B;[Preferenze]&#x200B;[UI] Substance Painter posizione cache globale
&#x200B;* [SVT] Nuova variabile di ambiente per specificare il percorso della cache della Substance Painter
&#x200B;* [SVT] Nuova variabile di ambiente per attivare l&#39;accelerazione del supporto hardware SVT
&#x200B;* [SVT] Rileva supporto sparse per hardware
&#x200B;* [SVT]&#x200B;[Hardware Sparse] Aumento della versione minima del driver per la GPU Nvidia
&#x200B;* [SVT]&#x200B;[Shader]&#x200B;[Viewport]&#x200B;[UI] Avvisa l&#39;utente se all&#39;apertura del progetto sono presenti artefatti con texture virtuale sparsa

<b>Corretto:</b>

&#x200B;* [Selettore colore] Viene visualizzato il cursore di disegno quando si tenta di selezionare un colore
&#x200B;* Arresto anomalo selezionando o deselezionando i livelli in un ordine specifico può provocare arresto anomalo
&#x200B;* Arresto anomalo quando si incolla come istanza un livello con una maschera
&#x200B;* arresto anomalo [Canale utente]&#x200B;[Regressione] durante la ridenominazione del canale utente
&#x200B;* [Canale utente] Anteprima pennello grigio
&#x200B;* [Alembic] Una sola texture impostata da diversi materiali dopo l’importazione
&#x200B;* [Engine] La texture esportata è diversa dalla finestra della vista per i timbri a pennello
&#x200B;* [Motore] L’inversione con un effetto livello non influisce completamente su una texture
&#x200B;* Il selettore materiale sta applicando un tratto di pennello durante il prelievo
&#x200B;* Il passaggio a una risoluzione di 128x128px genera un arresto anomalo
&#x200B;* I collegamenti delle mappe trama non vengono aggiornati correttamente quando si ridefiniscono o si creano istanze dei livelli
&#x200B;* [Substance] UserData ColorSpace non funziona con la trama Eseguita i baking Normale richiesta come input
&#x200B;* Associazione MDL non corrispondente quando si utilizzano più istanze di shader
&#x200B;* Piano della Simmetria [Simmetria]&#x200B;[Livello di riempimento] e il relativo manipolatore attivo nel livello di riempimento
&#x200B;* [Viewport] Il punto pivot per la traduzione non viene sempre aggiornato dopo aver fatto clic su
&#x200B;* [UI] Icone fisse e rimozione dei segnaposto per i monitor HDPI

<b>Problemi noti:</b>

&#x200B;* In alcuni casi, il calcolo si blocca sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
&#x200B;* L’anti-alias e le ombre quando sono attivi insieme possono dare risultati imprevisti

### 4.2.3 (2018.2.3)

*(Rilasciato il 25 settembre 2018)*

**Corretto:**

&#x200B;* [vista 2D] Il vista 2D è interrotto con alcune trame durante la creazione di un nuovo progetto
&#x200B;* [Arresto anomalo] Il passaggio da Proiezione UV a proiezione triplanari porta a un arresto anomalo
&#x200B;* [RayCollider] Più arresti anomali dovuti a &quot;RayCollider&quot;
&#x200B;* [Strumento] Quando si cambia livello, le proprietà del pennello modificate vengono perse
&#x200B;* Le impostazioni del pennello vengono ripristinate quando si passa alla gomma

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.2 (2018.2.2)

*(Rilasciato: 11 settembre 2018)*
Riepilogo: **Correzione rapida con aggiornamento dei contenuti, nuove funzionalità di scripting e possibilità di disattivare l&#39;aggiornamento automatico**

**Aggiunto:**

&#x200B;* [Content]&#x200B;[Shelf] Aggiungi un predefinito Ripiano incarnato
&#x200B;* [Content]&#x200B;[shelf] Conversione di 19 normali cutanee in materiali per la dispersione sottosuperficiale
&#x200B;* [Scripting] Crea un modello di progetto da un progetto aperto
&#x200B;* [Scripting] Ottenere/impostare le impostazioni di esportazione di un progetto aperto
&#x200B;* [Updates] Consente di disattivare la finestra a comparsa Aggiornamento automatico da impostazioni e variabile di ambiente
&#x200B;* [Aggiornamenti] Non visualizzare fino alla versione successiva nella finestra a comparsa con aggiornamenti per la manutenzione

**Corretto:**

&#x200B;* [Fotocamera] Zoom errato passando da ortogonale a prospettico
&#x200B;* [Display] Alcune mappe vengono visualizzate in modalità lineare anziché sRGB
&#x200B;* [Finestre di visualizzazione] Lo stato attivo della trama non funziona correttamente
&#x200B;* [2D View] Progetto con fotocamera rotta ha sparito UVs Gusci
&#x200B;* [SSS]&#x200B;[Tooltip] nel registro vengono visualizzate le descrizioni degli strumenti per la dispersione delle superfici
&#x200B;* Alcuni progetti non possono essere aperti in 2018.2 e il messaggio di errore non può salvare un pacchetto substance null
&#x200B;* [Maschera] Il colore dello strumento di pittura può bloccarsi in alcuni casi quando si lavora su una maschera
&#x200B;* [Materiale] Mappe non visualizzate in situazioni specifiche
&#x200B;* [Proj]&#x200B;[Strumenti] Manipolatore attivo con un generatore
&#x200B;* [Substance] Gruppi di parametri Substance mancanti
&#x200B;* [Scripting] Nome software errato nella documentazione
&#x200B;* [UDIM] Nessuna informazione nel registro sui gusci UV su più riquadri UV

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.1 (2018.2.1)

*(Rilasciato il 3 agosto 2018)*

**Corretto:**

&#x200B;* Parametri shader di dispersione sottosuperficie mancanti da progetti di aggiornamento

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.2.0 (2018.2.0)

*(Rilasciato il 2 agosto 2018)*
Riepilogo: **Versione estate, supporto per la dispersione sottosuperficiale, miglioramenti a livello di proiezione e riempimento, importazione e selezione della fotocamera, supporto di Alembic e glTF, trascinamento sulla mappa ID, supporto migliorato del formato di Substance e nuovi contenuti**

**Aggiunto:**

&#x200B;* [SSS]&#x200B;[Viewport]&#x200B;[Iray] Dispersione sottosuperficie generica
&#x200B;* [SSS] Sincronizza i parametri di dispersione MDL e subsuperficiale
&#x200B;* [SSS] È stato aggiunto un nuovo canale in scala di grigi denominato Dispersione
&#x200B;* [SSS]&#x200B;[Impostazioni Shader] Parametro del tipo di dispersione per la dispersione del sottosuolo (incarnato o traslucido)
&#x200B;* [SSS]&#x200B;[Impostazioni Shader] Parametro della scala di dispersione per la dispersione del sottosuolo
&#x200B;* [SSS]&#x200B;[Impostazioni Shader] Parametro colore di dispersione per la dispersione del sottosuolo
&#x200B;* [SSS]&#x200B;[Impostazioni schermo] Conteggio dei campioni di dispersione per la dispersione sotto la superficie
&#x200B;* [Shader]&#x200B;[Iray] Integra MDL di dispersione sottosuperficiale per Iray
&#x200B;* [Shader] Aggiornamento di Shader tramite il programma di aggiornamento delle risorse
&#x200B;* [Shader] Aggiornamento dell&#39;API del log delle modifiche e della documentazione
&#x200B;* [Proprietà utensile]&#x200B;[Proj] Nuovi parametri per la proiezione triplanare
&#x200B;* [Finestra vista]&#x200B;[Proj] Controlla le proprietà del livello di riempimento nella vista 3D direttamente con i manipolatori (proiezione triplanare)
&#x200B;* [Shortcuts]&#x200B;[Proj] Nuove scelte rapide Q, W, E, R, T per manipolatori di proiezione triplanari
&#x200B;* [Riquadro di visualizzazione]&#x200B;[Proj] Controlla le proprietà del livello di riempimento direttamente nei Vista 2D con i manipolatori (Proiezione UV)
&#x200B;* [Shortcuts]&#x200B;[Proj] Nuova scelta rapida da tastiera Q per manipolatori Proiezione UV
&#x200B;* [Barra degli strumenti contestuale]&#x200B;[Proj] Controlla manipolatori di proiezione triplanari
&#x200B;* [Barra degli strumenti contestuale]&#x200B;[Proj] manipolatori di Proiezioni UV di controllo
&#x200B;* [Proprietà strumento] Disattiva Affiancamento texture con lo strumento proiezione e stencil
&#x200B;* [Stencil] Utilizzare immagini non quadrate con lo strumento di proiezione/stencil
&#x200B;* [Stencil] Consenti il controllo della modalità Affiancamento nella finestra Proprietà
&#x200B;* [Stencil] Lo zoom non è centrato su uno stencil non Affiancamento
&#x200B;* [Fotocamere] Importa fotocamere da Maya, Max, Blender, Modo, DAE
&#x200B;* [Fotocamere]&#x200B;[Finestra vista] Selezionare e controllare le videocamere importate nella finestra della vista
&#x200B;* [Fotocamere]&#x200B;[Iray] Seleziona e controlla le videocamere importate in Iray
&#x200B;* [Fotocamere]&#x200B;[UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] L’opzione di importazione delle fotocamere è selezionata per impostazione predefinita
&#x200B;* [Fotocamere]&#x200B;[Scelte rapide] Aggiungi scelte rapide per passare da una videocamera all’altra
&#x200B;* [Fotocamere]&#x200B;[Finestra vista] Aggiungi fotogramma nella finestra della vista
&#x200B;* [Fotocamere]&#x200B;[Impostazioni finestra di visualizzazione] Controllo dell&#39;opacità dei fotogrammi
&#x200B;* [Fotocamere]&#x200B;[Impostazioni fotocamera] lunghezza focale massima a 500 mm
&#x200B;* [Fotocamere]&#x200B;[Impostazioni videocamera] Rapporto di esposizione
&#x200B;* [Fotocamere]&#x200B;[Impostazioni fotocamera] Aggiungi un&#39;opzione di blocco
&#x200B;* [Fotocamere]&#x200B;[Impostazioni fotocamera] Aggiungi un&#39;opzione di ripristino
&#x200B;* [Cameras]&#x200B;[Impostazioni fotocamera] Aggiungi attributo distanza focale
&#x200B;* [glTF] Importazione di un file glTF
&#x200B;* [glTF] Importa mappa occlusione ambiente
&#x200B;* [Alembic] Importa fotogramma Alembic 1 con geometria statica
&#x200B;* [Ripiano] Trascina i materiali direttamente sulla trama utilizzando mappe ID con un modificatore (CTRL/Comando)
&#x200B;* [Pila di livelli] Creazione automatica di maschere ID con trascinamento di materiali sulla trama con mappe ID
&#x200B;* [Pila di livelli] Scorrimento automatico dei livelli con trascinamento sulla pila di livelli
&#x200B;* [UI]&#x200B;[Proprietà strumento] Predefinito di Esposizione Substance
&#x200B;* [UI]&#x200B;[Menu?] Miglioramento del menu?
&#x200B;* [UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] Riorganizzazione della finestra
&#x200B;* [UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] Sostituisci termine trama con file
&#x200B;* [UI]&#x200B;[Substance] Visualizza gli attributi della Substance nell&#39;interfaccia utente
&#x200B;* [Scelte rapide] F4 alterna la vista 2D e 3D
&#x200B;* [Scelte rapide] Nuove scelte rapide per Attiva/Disattiva stencil N e maschera rapida U
&#x200B;* [Integrazione Substance] Considera le istruzioni &#39;visible if&#39; nei parametri di Substance
&#x200B;* [Riquadro di visualizzazione] Le ombre non vengono calcolate dopo lo spostamento della videocamera
&#x200B;* [Content] Aggiorna MeetMat con le fotocamere importate
&#x200B;* [Content] Aggiungi un campione con la dispersione sottosuperficiale attivata - JadeToad
&#x200B;* [Content] Aggiungi un nuovo modello di progetto PBR con la dispersione sottosuperficie attivata
&#x200B;* [Content] Predefiniti di esportazione aggiornati per aggiungere un nuovo canale di diffusione
&#x200B;* [Content]&#x200B;[Shelf] Aggiunto supporto per la dispersione sottosuperficiale per: pbr-metal-rough, pbr-metal-rough-alpha-test, pbr-coated, pbr-spec-gloss
&#x200B;* [Content]&#x200B;[Shelf] Canale di dispersione aggiunto a 5 materiali intelligenti (marmi e pelli)
&#x200B;* [Content]&#x200B;[Shelf] 1 nuovo materiale giada
&#x200B;* [Content]&#x200B;[Shelf] 1 nuovo materiale cera

**Corretto:**

&#x200B;* [CMD] Risultati diversi utilizzando la stessa riga di comando con versioni diverse
&#x200B;* [TDR] Se TdrLevel è impostato, non ci sono errori nel registro
&#x200B;* [Baker] La mappa di occlusione ambientale è capovolta
&#x200B;* [ID Map] Arresto anomalo durante il prelievo al di fuori dell’intervallo 0-1
&#x200B;* [Iray] Arresto anomalo quando si cambia set di texture e si torna alla modalità Disegno
&#x200B;* [Finestra vista] Sincronizza le aree di rilascio tra le finestre della vista per il trascinamento
&#x200B;* [Motore] Artefatto moire quando si sovrappongono i livelli di riempimento o si dipinge un piccolo pennello
&#x200B;* [Licenza] Verifica versione software non valida del servizio di licenza
&#x200B;* [Licenza] Rielabora il modo in cui gestiamo l&#39;autenticazione
&#x200B;* [API] Chiama l’evento API di scripting onNewProjectCreated anche durante la creazione con un modello
&#x200B;* [Shader] Lo shader compilato non viene caricato dalla cache quando il file shader non viene compilato
&#x200B;* [Shelf] L’esportazione di file HDR dallo shelf genera un file con valori bloccati
&#x200B;* [Esporta] L’esportazione EXR blocca i valori di colore RGB tra 0 e 1
&#x200B;* [Contenuto] Disturbo procedurale 3D Perlin Disturbo Frattale è pixelato

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA
&#x200B;* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 4.1.3 (2018.1.3)

*(Rilasciato il 28 giugno 2018)*

**Aggiunto:**

&#x200B;* [Preferenze] Proponi di salvare il progetto al riavvio di Painter

**Corretto:**

&#x200B;* [Plugin] La Substance Source di ricerca non funziona
&#x200B;* [Materiali avanzati] In alcuni casi, l’importazione di Materiali avanzati genera un arresto anomalo
&#x200B;* [Materiali avanzati] In alcuni casi, l’eliminazione di Materiali avanzati genera un arresto anomalo
&#x200B;* [Salva] In alcuni rari casi, il salvataggio genera un arresto anomalo
&#x200B;* [Shelf] Inverti non funziona su Celle 2 e Celle 3
&#x200B;* [Shelf] Errore di battitura in alcuni Alpha
&#x200B;* [Ripiano] Alcuni materiali Substance non vengono riprodotti correttamente

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.2 (2018.1.2)

*(Rilasciato il 12 giugno 2018)*
Riepilogo: **Velocità di Esegue i baking migliorata, sistema di salvataggio migliorato, cursori aggiornati, API del plug-in aggiornata, traduzione cinese, spaziatura interna migliorata ora facoltativa**

**Aggiunto:**

&#x200B;* [Baker] Miglioramento delle prestazioni con la nuova versione del baker
&#x200B;* Forzare la finestra di dialogo di visualizzazione con la GPU incompatibile
&#x200B;* [Salva] Scopri la nuova funzionalità di progetto compatto (modalità di salvataggio completa/compatta)
&#x200B;* [Salva] Informa l&#39;utente in caso di errore di salvataggio
&#x200B;* [Clean] Salvataggio successivo in modalità completa/compatta
&#x200B;* [Cursori] Miglioramento della precisione delle barre e dei cursori dei colori/della scala di grigi
&#x200B;* [Cursori] Aggiunta di controlli freccia Su/Giù
&#x200B;* [Cursori] Stessa zona di rilevamento per i cursori a barre a colori e in scala di grigio
&#x200B;* [Plugin] Salvataggio automatico sempre in modalità incrementale
&#x200B;* [Plugin] Opzione per passare dai plug-in al nuovo stile di interfaccia
&#x200B;* [Lingua] Aggiungi traduzione cinese
&#x200B;* [Spaziatura interna] Opzione per passare dalla spaziatura UV a quella 3D adiacente per set di texture nelle impostazioni set di texture
&#x200B;* [Script] Modalità di salvataggio esposizione: completa/compatta o incrementale
&#x200B;* [Script] Aggiornamento della documentazione di scripting/QML
&#x200B;* [Registro] Indica la modalità di salvataggio nel registro (completo/compatto o incrementale)

**Corretto:**

&#x200B;* [Strumento] Lo slot del canale Trasforma in uno slot materiale su riempimenti a canale singolo
&#x200B;* Arresto anomalo durante il caricamento di una trama (FBX) con alcune facce non assegnate da un materiale
&#x200B;* Arresto anomalo in Iray con NVIDIA GRID 5.2 sulla macchina virtuale
&#x200B;* Arresto anomalo quando si annulla un&#39;eliminazione di un predefinito di materiale
&#x200B;* Arresto anomalo durante il caricamento di alcuni progetti
&#x200B;* [Riga di comando] Nuova riga di comando per le trame degli UDIM suddivise per dim
&#x200B;* [Toolbar] Riduzione della barra degli strumenti
&#x200B;* [Istanza] Impossibile creare un&#39;istanza delle bitmap su più set di texture
&#x200B;* [Finestra vista] L’aggiornamento non è completo quando si dipinge su trama con UV in porzioni
&#x200B;* La Mappa normale [Iray] viene applicata due volte per i dielettrici
&#x200B;* [Shelf] Errori di battitura in alcuni parametri di Substance (alpha, procedure e matfx)
&#x200B;* [Shelf] Errore ortografico per la bitmap &quot;Authorized Personnel Only&quot;
&#x200B;* [Script] La funzione alg.shaders.materials() non funziona più

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.1 (2018.1.1)

*(Rilasciato il 3 aprile 2018)*

**Corretto:**

&#x200B;* [Tablet] Problema durante la modifica delle scelte di interazione predefinite
&#x200B;* [Baker] Arresto anomalo con la libreria Assimp
&#x200B;* [Bakers] Regressione sulle prestazioni con A.O. map
&#x200B;* [Iray] La Distorsione obiettivo non viene applicata al canale Alpha
&#x200B;* [Driver] Aggiornamento dei requisiti minimi dei driver
&#x200B;* [3Dview] Normali non generate correttamente sulle trame UDIM senza informazioni sulle normali
&#x200B;* [Intel] Arresto anomalo con Substance Painter 2018.1.0
&#x200B;* [Intel]&#x200B;[Viewport] Problema con la spaziatura interna (artefatti neri)

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA

### 4.1.0 (2018.1.0)

*(Rilasciato il 15 marzo 2018)*

**Aggiunto:**

&#x200B;* Nuovo stile generale (icone, colore, comportamento)
&#x200B;* Nuovo layout predefinito
&#x200B;* [Tablet] Miglioramento dell&#39;esperienza utente durante la pittura
&#x200B;* [Menu principale] Ordinare prima gli elementi nativi nelle visualizzazioni e nelle barre degli strumenti
&#x200B;* [Menu principale] Spostare le azioni rapide della maschera nella sezione viewport
&#x200B;* [Menu principale] Spostare le azioni del clic con il pulsante destro del mouse nella sezione della finestra della vista
&#x200B;* [Menu principale] Rinominare &quot;Visualizza&quot; come &quot;Finestra&quot;
&#x200B;* [Menu rapido] Nuove proprietà dello strumento facendo clic con il pulsante destro del mouse nella finestra della vista
&#x200B;* [Widget dock] Nuova barra degli strumenti dock per ridurre/richiamare rapidamente
&#x200B;* [Impostazioni di visualizzazione] Finestra Impostazioni videocamera e visualizzatore unita
&#x200B;* [Serie di livelli] Menu contestuale di scelta rapida
&#x200B;* [Pila livelli] Trascinate e rilasciate per spostare qualsiasi effetto all’interno dello stesso livello
&#x200B;* [Toolbar] Riorganizzazione della barra degli strumenti e nuova barra degli strumenti contestuale
&#x200B;* [Barra degli strumenti] Dividere lo strumento Clona in due strumenti separati
&#x200B;* [Proprietà Tools] Valore più chiaro della scala di grigi dello sfondo nell&#39;anteprima
&#x200B;* [Strumenti proprietà] Organizzazione nelle schede (riempimento e strumenti)
&#x200B;* [Strumento] Il risultato del disegno corrisponde allo stencil
&#x200B;* [Finestra vista] Nuovo cursore per il livello di riempimento
&#x200B;* [Finestra vista] Navigazione e pittura più fluida (frequenza fotogrammi più elevata)
&#x200B;* [Finestra vista] Casella combinata di selezione Materiale/Canale/Mappa nella finestra della vista
&#x200B;* [Riquadro di visualizzazione] Ridurre lo sfarfallio durante la rotazione (ombra attivata)
&#x200B;* [Shelf] Visualizza i materiali per impostazione predefinita all’apertura di Painter
&#x200B;* [Shelf] Miglioramento del tempo di caricamento delle texture e dei materiali delle Substance (da 2 a 6 volte più veloce)
&#x200B;* [Shelf] Riorganizzare le cartelle dei materiali per adattarle alla struttura della Substance Source
&#x200B;* [Shelf] Trascina i materiali direttamente sulla trama nella finestra della vista
&#x200B;* [Shelf] Nuovi rumori 3D (Perlin, Perlin Fractal, Simplex e Worley)
&#x200B;* [Ripiano] Nuovo generatore di maschere con posizione mesh
&#x200B;* [Shelf] Disturbi di base aggiornati per supportare il non square expansion
&#x200B;* [Shelf] Aggiunto un nuovo modello ed esporta il predefinito per Lens Studio (applicazione Snap)
&#x200B;* [Shelf] Materiali avanzati e Maschere avanzate aggiornati per utilizzare la versione più recente di Editor maschera (micro dettagli)
&#x200B;* [Shelf] Nuovo progetto di esempio &quot;TilingMaterial&quot; per creare materiali in Affiancamento senza soluzione di continuità
&#x200B;* [Shelf] Nuovi predefiniti per i pennelli (Calligrafia, Bagnato, Tratteggio e così via)
&#x200B;* [Cursori] Nuovi cursori e stile e comportamento delle barre di grigio/colore
&#x200B;* [Baker] Consenti l’uso del rettangolo di selezione completo della scena per calcolare la mappa di posizione
&#x200B;* [Shader] Rimuovi il parametro della forza del height dai parametri di shader di default
&#x200B;* Motore di Substance [Engine] aggiornato
&#x200B;* [Motore] Nessuna o meno discontinuità tra i blocchi UV
&#x200B;* [Plugin] Importa più rapidamente i materiali scaricati da Substance Source
&#x200B;* [Plug-in] Aggiorna tutti i plug-in in base al nuovo stile generale
&#x200B;* [Preferenze] L’anteprima del colore di sfondo cambia automaticamente
&#x200B;* [Clean] Riduzione del rischio di danneggiamento dei progetti
&#x200B;* [Aperto] Apertura del progetto - Miglioramento orario
&#x200B;* [Nuovo progetto] Nuovo progetto - Miglioramento del tempo di aggiornamento mesh
&#x200B;* [Salva] Salvataggio del tempo del progetto migliorato
&#x200B;* [Log] Tipo di licenza segnalato nel log
&#x200B;* [TextureSet] Rinomina il pulsante &quot;Esegue i baking Texture&quot; in &quot;Esegue i baking mappe trama&quot;
&#x200B;* Rinominare &quot;Mappe aggiuntive&quot; come &quot;Mesh maps&quot;

**Corretto:**

&#x200B;* [Finestra vista] Prestazioni errate con trame contenenti molti sottooggetti
&#x200B;* [Strumenti proprietà] Canale disattivato quando si trascina un’immagine nello slot del materiale
&#x200B;* [Proprietà Tools] L’anteprima del pennello non funziona con gli strumenti sfumino e clone
&#x200B;* [Set di texture] L’ordine dei canali non è corretto quando si utilizzano i modelli
&#x200B;* [Shelf] Icona mancante per il generatore di Conversioni in scala di grigi
&#x200B;* [Shelf] Sign Circle Number alpha è interrotto (font mancante)
&#x200B;* Rilevamento errato delle GPU integrate all’avvio
&#x200B;* [Arresto anomalo] Trascina una risorsa importata denominata con un carattere #
&#x200B;* [Engine] Problema di rilevamento Vram sulla GPU integrata
&#x200B;* [Engine] Corretti numerosi arresti anomali in Substance Engine Linker
&#x200B;* [Engine] Artefatti quadrati quando si modifica la risoluzione
&#x200B;* [Effetti post] Il ridimensionamento dell’interfaccia è lento quando gli effetti post sono attivi
&#x200B;* [Baker] L’unità della scena non viene rispettata correttamente per i valori di distanza dei raggi
&#x200B;* [Panettieri] AO dalla distanza di occlusione della trama è fissato a 1 indipendentemente dal valore di input
&#x200B;* [Bakers] La corrispondenza per nome ignora alcune trame con nomi specifici
&#x200B;* [Pannelli] L’impostazione Colore da trama Poligruppo e ID trama restituisce sempre un’immagine nera
&#x200B;* [Bakers] ID Baking non riesce con trame FBX binarie da Blender
&#x200B;* [Shader] Disturbo nella vista 2D con dota-2 e non-pbr-spec-gloss
&#x200B;* [Linux] Durante il baking viene utilizzato un solo thread CPU
&#x200B;* [MacOS] Arresto anomalo con il cursore del pennello che si sposta sulla finestra della vista

**Problemi noti:**

&#x200B;* Blocco del calcolo sulle GPU AMD VEGA
&#x200B;* Processo di post-distorsione non preso in considerazione durante l&#39;esportazione in IRay (alfa)

## Versione 3

### 3.4.2 (2017.4.2)

*(Rilasciato il 24 gennaio 2018)*

**Aggiunto:**

&#x200B;* [Esportazione] Ottieni lo stato di un’esportazione con avanzamento passaggio
&#x200B;* [Esportazione] Consenti l’annullamento di un’esportazione
&#x200B;* [Esporta] Esporta le texture in Sketchfab senza perdere la qualità della mappa normale
&#x200B;* [Esportazione] Esportazione in formato binario (glb) glTF
&#x200B;* [Esporta] Consente il ridimensionamento delle colonne nella scheda di configurazione della finestra di esportazione
&#x200B;* [Shader] Aggiungere un registro delle modifiche per l&#39;API shader
&#x200B;* [Scripting] Aggiungere le funzioni di richiamata prima e dopo l’esportazione delle texture
&#x200B;* [Iray] Aggiornamento a SDK 2017.1 (supporto di GPU Volta)

**Corretto:**

&#x200B;* Arresto anomalo quando si esce dall’applicazione prima della visualizzazione della finestra principale
&#x200B;* [MAC] Arresto anomalo durante il caricamento di mappe in scala di grigio con IRAY
&#x200B;* [MAC] Il rilevamento VRAM non è corretto con il nuovo sistema operativo High Sierra
&#x200B;* [Plugin] Il download delle risorse da Substance Source non funziona più
&#x200B;* [Scripting] Rilevamento minimo della versione del plug-in non corretto
&#x200B;* [Esporta] Impossibile salvare il predefinito di esportazione dopo l’esportazione delle texture
&#x200B;* [Istanza] Problema relativo ai generatori di cui è stata creata un’istanza in un TextureSet senza mappe aggiuntive
&#x200B;* [Finestra vista] Il dithering non funziona con una risoluzione superiore a 4k
&#x200B;* [Riquadro di visualizzazione] La visualizzazione del materiale 2D View è coperta da rumore
&#x200B;* [Shelf] Migliorare il tempo di caricamento per i predefiniti shelf
&#x200B;* [Motore] Fusione errata durante il disegno sotto la selezione colore

### 3.4.1 (2017.4.1)

*(Rilasciato il 15 dicembre 2017)*

**Aggiunto:**

&#x200B;* [Scripting] Esporta trama tramite API di scripting
&#x200B;* [Import] Disabilita l&#39;importazione di un formato di file mesh non supportato (consenti solo obj, fbx, dae, ply)
&#x200B;* [Log] Indica con maggiore precisione il problema TDR nel file di log

**Corretto:**

&#x200B;* Arresto anomalo se l&#39;applicazione viene chiusa prima del termine della ricerca per indicizzazione delle risorse
&#x200B;* Arresto anomalo all’apertura di progetti con lo strumento Sfumino/Clone
&#x200B;* Arresto anomalo quando si utilizza Ripeti dopo un annullamento di una modifica dello shader in Impostazioni visualizzatore
&#x200B;* [Engine] La creazione di texture differisce tra Painter 2017.2 e 2017.4
&#x200B;* [Finestra vista] Il prelievo su una mappa ID da un&#39;istanza consente di campionare il colore errato
&#x200B;* [Esporta] Arresto anomalo durante l’esportazione di una texture normale o di occlusione non valida
&#x200B;* I gruppi dei file PSD di [Esportazione] sono bloccati all’apertura in Photoshop CS6
&#x200B;* [Plugin] Il plug-in Photoshop ignora la selezione del canale ed esporta sempre tutto
&#x200B;* [Livelli] Gli ancoraggi si interrompono quando vengono copiati/incollati su set di texture
&#x200B;* [Livelli] Alcuni riferimenti di ancoraggio non possono essere ripristinati se sono interrotti
&#x200B;* [Shader] Il parametro di rugosità secondaria rivestita con pbr è interrotto
&#x200B;* [Steam] La finestra a comparsa Controllo versione non deve essere visibile all’avvio

**Problemi noti:**

&#x200B;* [AMD] Arresti anomali/Blocchi quando si tenta di pittura su una trama. Può essere risolto con un aggiornamento del driver GPU.

### 3.4.0 (2017.4.0)

*(Rilasciato il 23 novembre 2017)*

**Aggiunto:**

&#x200B;* [Creazione istanza] Consente di creare un&#39;istanza dei parametri tra i livelli
&#x200B;* [Istanza] Consente di passare da un livello di origine a un&#39;istanza e viceversa
&#x200B;* [Creazione di istanze] Aggiungi un’azione &quot;Crea istanza tra set di texture&quot;
&#x200B;* [Istanza] Indica nella Pila livelli istanze di rientro (cicli)
&#x200B;* [Istanza] Elimina le istanze quando viene rimossa un&#39;origine
&#x200B;* [Istanza] Non consentire riferimenti di ancoraggio dall&#39;esterno di una cartella istanza
&#x200B;* [UI] Sposta lo stack di annullamento nella propria finestra denominata &quot;History&quot;
&#x200B;* [Plugin] Integrazione del plug-in DCC live-link
&#x200B;* [Engine] Migliora le prestazioni di pittura con Pittura sparsa
&#x200B;* [Esporta] Aggiungi le opzioni di bozza e riesporta in esportazione Sketchfab
&#x200B;* [Shelf] Aggiungi il controllo &quot;flip&quot; per le sostanze Font
&#x200B;* [Shelf] Aggiungi 20 nuovi materiali per le procedure
&#x200B;* [Shelf] Aggiungi 40 nuove mappe grunge (basate su bitmap e procedurali)
&#x200B;* [Finestra di visualizzazione] Attivare le collisioni di anteprima pennello su altri set di texture visibili
&#x200B;* Aggiornamento dei requisiti minimi dei driver della GPU AMD

**Corretto:**

&#x200B;* Arresto anomalo quando si elaborano Substance a risoluzioni eccessive
&#x200B;* Arresto anomalo quando si dipinge intensamente con particelle
&#x200B;* [Finestra vista] Riflesso di specular errato nella Vista 2D con trame specifiche
&#x200B;* [UI] Alcune azioni indesiderate vengono visualizzate nella finestra Cronologia

**Problemi noti:**

&#x200B;* [Livelli] Alcuni riferimenti di ancoraggio non possono essere ripristinati se sono interrotti
&#x200B;* Arresto anomalo quando si utilizza Ripeti dopo un annullamento della modifica dello Shader in Impostazioni visualizzatore

### 3.3.3 (2017.3.3)

*(Rilasciato il 1° dicembre 2017)*

**Corretto:**

&#x200B;* [Steam] La finestra a comparsa Controllo versione non deve essere visibile all’avvio
&#x200B;* I gruppi dei file PSD di [Esportazione] sono bloccati all’apertura in Photoshop CS6

### 3.3.2 (2017.3.2)

*(Rilasciato il 20 novembre 2017)*

**Aggiunto:**

&#x200B;* [UI] Migliora la finestra di dialogo per la nuova versione e aggiungi il registro modifiche
&#x200B;* [UI] Indica se la manutenzione è scaduta nella finestra di dialogo per una nuova versione
&#x200B;* [Licenza] Aggiornare il sistema di licenze per gestire le date di manutenzione
&#x200B;* [Esporta] Rinomina Adobe Standard Material in Adobe Dimension

**Corretto:**

&#x200B;* [Mac] Dipingere causa quadrati neri e texture di corruzione
&#x200B;* La cache di [Engine] a volte può scomparire nella finestra della vista
&#x200B;* [Engine] Vengono visualizzati artefatti di tipo Blocky quando si attiva la compressione della memoria
&#x200B;* [Eseguita i baking] Strani messaggi di errore durante la esegue i baking di trame specifiche
&#x200B;* [Export] PSD non sono scritti correttamente e non vengono riconosciuti correttamente da Photoshop
&#x200B;* [Livelli] Non dovrebbe essere possibile copiare/incollare i livelli in più progetti
&#x200B;* [Substance] In alcuni casi, lo spazio colore UserData per l’input Normale viene capovolto
&#x200B;* [Shelf] Micro-normale nei generatori produce una curvatura invertita
&#x200B;* [Shelf] Il filtro HSL influisce anche sul canale alfa
&#x200B;* [Linux] L&#39;installazione su Centos non riesce a causa di dipendenze mancanti
&#x200B;* In alcuni casi, il programma di installazione non rimuove tutte le risorse dall&#39;installazione precedente

### 3.3.1 (2017.3.1)

*(Rilasciato il 26 ottobre 2017)*

**Aggiunto:**

&#x200B;* [Esporta] Consente di esportare la trama da un progetto
&#x200B;* [Shelf] Rimuovere &quot;Sub-Shelf&quot; dai titoli delle schede
&#x200B;* Salvare le impostazioni di post-elaborazione nei modelli
&#x200B;* Rendere il messaggio TDR più comprensibile
&#x200B;* Finestra Migliora impostazioni per la segnalazione degli errori

**Corretto:**

&#x200B;* Arresto anomalo quando si eliminano più scaffali secondari
&#x200B;* Arresto anomalo quando si passa da un livello a qualcos&#39;altro durante il calcolo di un motore
&#x200B;* [Mac] Arresto anomalo sulla GPU Intel durante il calcolo del motore
&#x200B;* [Mac]&#x200B;[Finestra vista] Prestazioni errate quando è attivato il dithering
&#x200B;* [Mac] MacOS 10.13 viene riconosciuto come &quot;Versione sconosciuta&quot; nel file di registro
&#x200B;* [Baker] Eseguire i baking con una gabbia non funziona più
&#x200B;* [Livelli] Ctrl + C scelta rapida da tastiera (azione copia) non funziona più
&#x200B;* [Livelli] Incollare i livelli non aggiorna l’interfaccia utente con i riferimenti dell’ancoraggio
&#x200B;* [Ancoraggio] Quando si duplica o si copia/incolla un livello con riferimenti, i collegamenti vengono interrotti
&#x200B;* [Esportazione] L&#39;esportazione 8K può causare l&#39;arresto anomalo o il blocco dell&#39;applicazione in alcuni casi
&#x200B;* [Esporta] Più problemi nel formato di file glTF generato
&#x200B;* [Import] La reimportazione di una trama con lo stesso nome di file non funziona più
&#x200B;* [Plugin] La finestra di salvataggio automatico viene sempre visualizzata sopra ogni elemento
&#x200B;* [UI] Ciclo infinito quando si preme &quot;Esc&quot; nella finestra di dialogo TDR
&#x200B;* [UI] Reimposta interfaccia utente visualizza una seconda barra del titolo nella finestra scaffale

### 3.3.0 (2017.3.0)

*(Rilasciato il 28 settembre 2017)*

**Aggiunto:**

&#x200B;* [Esporta] Consente di esportare trame e trame per Adobe Project Felix
&#x200B;* [Esporta] Consente di esportare nel formato di file glTF
&#x200B;* [Engine] Ottimizza le dimensioni delle texture in VRAM utilizzando la compressione dei blocchi
&#x200B;* [Finestra vista] Consente di trascinare una trama o un progetto nella finestra della vista
&#x200B;* [UI] Migliora il messaggio di avviso relativo al TDR.
&#x200B;* [UI] Il registro deve essere visualizzato solo su richiesta
&#x200B;* [UI] Consenti di cancellare il contenuto della finestra di registro
&#x200B;* [UI] Visualizza avvisi ed errori nella barra di stato
&#x200B;* [UI] Visualizza le schede in alto come nei browser Web
&#x200B;* [UI] Migliorare il contesto e i messaggi &quot;non colorabili&quot;
&#x200B;* [UI] Aggiungi un’azione &quot;Salva come copia&quot; nel menu del file
&#x200B;* [Livello] Per impostazione predefinita, imposta l’impostazione predefinita per la porzione su 1
&#x200B;* [Ripiano] Filtro sfumatura migliorato per supportare 10 colori dinamici
&#x200B;* [Shelf] Aggiungi uno spazio nella query predefinita del mini-shelf
&#x200B;* [Shelf] Aggiungi un&#39;azione &quot;Apri in Esplora risorse&quot; per le risorse locali nello shelf
&#x200B;* [Shelf] Aggiungi modello e shader per Adobe Material Standard (Project Felix)
&#x200B;* [Ripiano] Aumenta l’affiancatura fino a 128 nelle ombreggiature a strati di materiale
&#x200B;* [Ripiano] Curvatura sobel aggiunta per micro-dettagli dei generatori maschera
&#x200B;* [Plugin] Aggiungi plug-in di salvataggio automatico con intervallo di tempo personalizzabile
&#x200B;* [Scripting] Aggiungere una funzione &quot;Salva come copia&quot;

**Corretto:**

&#x200B;* [UI] Il layout non funziona al primo avvio
&#x200B;* [Esportazione] Il PSD generato durante l’esportazione contiene errori di formato
&#x200B;* [Esporta] EXR esporta sempre mappa height a 8 bit
&#x200B;* [Esporta] Arresto anomalo durante l’esportazione di mappe aggiuntive danneggiate
&#x200B;* [Importazione] In alcuni casi i bordi netti non vengono mantenuti su trame poly basse
&#x200B;* [Import] Messaggi di errore migliorati durante l&#39;importazione di trame con problemi
&#x200B;* [Baker] La Esegue i baking della mappa ID non riesce con l’opzione Corrispondenza per nome attivata
&#x200B;* [Finestra vista] Lo spazio tangente non è sincronizzato con i baker
&#x200B;* [Effetto] Spostandosi indietro di un livello non si ripristina il riferimento di un ancoraggio
&#x200B;* [Effetto] Problema di aggiornamento quando si crea un collegamento tra due maschere con ancoraggi
&#x200B;* [Effetto] I punti di ancoraggio delle maschere sopra la maschera non devono essere elencati
&#x200B;* [Effetto] L’impostazione Estrai Alpha da Ancoraggi non funziona
&#x200B;* [Motore] La maschera si inverte dopo il primo tratto del pennello
&#x200B;* [Engine] Arresto anomalo quando si cambia set di texture in un progetto specifico
&#x200B;* [Shelf] Arresto anomalo quando si elimina un predefinito che si trova in un progetto
&#x200B;* [Shelf] Tipo nel filtro avanzato Tri-Planari
&#x200B;* [Shelf] MG Mask Builder AO Noise Scale non funziona correttamente
&#x200B;* [Shelf] MG Mask Builder ha parametri di curvatura invertiti
&#x200B;* [Scaffale] Le alfa importate generano un&#39;anteprima della sfera di materiale anziché una di forma piatta

### 3.2.0 (2017.2.0)

*(Rilasciato il 27 luglio 2017)*

**Aggiunto:**

&#x200B;* Punti di ancoraggio - Sistema di riferimento livello e maschera
&#x200B;* [Livelli] Possibilità di rinominare gli effetti di riempimento e Pittura
&#x200B;* [Plugin] Plug-in Substance Source aggiornato
&#x200B;* [Scripting] Consente di eseguire query sulla risoluzione del set di texture
&#x200B;* [Scripting] Consenti di ottenere lo stato del motore di pittura
&#x200B;* [Prestazioni] Ottimizzazione migliorata del caricamento del progetto e della timbratura del pennello

**Corretto:**

&#x200B;* [Tool] Problemi di prestazioni durante la modifica dei parametri del materiale
&#x200B;* [Motore] Scomparsa dei tratti di pennello durante la modifica della risoluzione (4K>2K)
&#x200B;* [Vista 3D] Lo spazio tangente non è sincronizzato con i forni
&#x200B;* [Shelf] Il percorso dello scaffale nei documenti utente non viene creato automaticamente
&#x200B;* [Shelf] Rendete i predefiniti compatibili con le versioni precedenti dopo un aggiornamento
&#x200B;* [Shader] Lo shader non PBR non funziona più
&#x200B;* [Bakers] La mappatura degli ID non riesce con l&#39;opzione Corrispondenza per nome abilitata
&#x200B;* [Sample] I nomi dei set di texture del progetto di esempio Meet Mat non sono corretti
&#x200B;* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura

### 3.1.0 (2017.1.0)

*(Rilasciato il 20 giugno 2017)*

**Aggiunto:**

&#x200B;* [Plugin] Nuovo plug-in Substance Source (consente di scaricare risorse nello scaffale)
&#x200B;* [Scaffale] 4 Nuovi Font (Giapponese + Cinese Semplificato, Macchina Da Scrivere, Segmento)
&#x200B;* [Shelf] 230 Nuovi Alpha (Mix di pattern, pennelli e scansioni di impronte digitali)
&#x200B;* [Scaffale] 50 Nuovi Procedurali (Tessuti di abbigliamento medievale e contemporaneo)
&#x200B;* [Scaffale] 2 Nuove mappe ambientali (Mondarrain e Villa Nova Street)
&#x200B;* [Shelf] 9 Nuovi filtri (MatFx Detail Edge Wear, Clamp, HBAO, ecc.)
&#x200B;* [Shelf] Mappa ambiente Panorama predefinita migliorata
&#x200B;* [Shelf] Nuovi predefiniti di esportazione Arnold 5
&#x200B;* [Scripting] Consente di importare la risorsa nello scaffale

**Problemi noti:**

&#x200B;* [Esportazione] La modifica di un predefinito di esportazione è molto lenta

## Versione 2

### 2.6.2

*(Rilasciato il 20 ottobre 2017)*

<b>Aggiunto:</b>

&#x200B;* [Set di texture] Consente di eliminare i set di texture disattivati
&#x200B;* [Shelf] Consenti a più utenti di scrivere nella stessa cartella shelf
&#x200B;* [Scripting] Possibilità di ricaricare la cartella dei plug-in
&#x200B;* [Scripting] Aggiungi una versione API minima richiesta nei metadati del plug-in per garantire la compatibilità
&#x200B;* [IRay] Miglioramenti alla finestra di dialogo Esporta immagine

<b>Corretto:</b>

&#x200B;* [Engine] Problema di scomparsa dei tratti quando si modifica la risoluzione (4K>2K)
&#x200B;* [Baker] La Esegue i baking della mappa ID non riesce con l’opzione Corrispondenza per nome attivata
&#x200B;* [Baker] I messaggi di errore non sono sufficientemente espliciti
&#x200B;* [vista 3D] Lo spazio tangente non è sincronizzato con i baker
&#x200B;* [Strumento] Artefatti di nero quando si utilizza lo strumento sfumino
&#x200B;* [Shader] Lo shader non PBR non funziona più
&#x200B;* [Shader] &quot;pbr-coated&quot; è rotto
&#x200B;* [Shader] La rugosità dello shader &quot;pbr-coated&quot; non ha più alcun impatto
&#x200B;* [Shader] Lo shader lucido delle specifiche non corrisponde a Iray e SD
&#x200B;* [Shelf] Arresto anomalo durante il caricamento di due file con lo stesso nome ma estensioni diverse
&#x200B;* [Shelf] Impossibile modificare il predefinito negli scaffali
&#x200B;* [Shelf] Impossibile impostare un&#39;anteprima personalizzata per le risorse importate nello shelf
&#x200B;* Le risorse caricate dalla cache perdono il loro utilizzo
&#x200B;* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura
&#x200B;* Salvataggio del progetto errato se il nome del file contiene due punti
&#x200B;* Importazione di file con più punti (.) nel nome del file causa problemi

### 2.6.1

*(Rilasciato il 12 maggio 2017)*

**Aggiunto:**

&#x200B;* [TextureSet] Non consentire la riassegnazione di materiali mesh a nulla

**Corretto:**

&#x200B;* Arresto anomalo quando si cambia TextureSet dopo la sostituzione della mappa con baking
&#x200B;* Arresto anomalo quando si esegue &quot;Annulla e ripeti&quot; dopo aver modificato il metodo di fusione del livello
&#x200B;* Arresto anomalo o blocco quando si utilizza l&#39;effetto &quot;selezione colore&quot; con mappa ID grande
&#x200B;* [Esporta] I set di texture rinominati non sono ordinati alfabeticamente nella finestra di esportazione
&#x200B;* [TextureSet] Il ripristino del nome predefinito non verifica la presenza di unicità
&#x200B;* [TextureSet] Il set di texture rinominato viene disattivato dopo la riapertura del progetto
&#x200B;* [Shelf] Contenuto modelli predefiniti mancante
&#x200B;* [Shelf] Le texture non quadrate vengono visualizzate come quadrate
&#x200B;* [Shader] Una volta disattivato un set di texture, lo shader associato viene eliminato
&#x200B;* [Scripting] alg.eseguite i baking.setTextureSetBakingParameters() non funziona più
&#x200B;* [Scripting] Errore di battitura nell’esercitazione websocket
&#x200B;* [Scripting] Vari problemi in AlgWidgets
&#x200B;* [Log] Rilevamento errato della memoria virtuale disponibile in alcuni casi

### 2.6.0

*(Rilasciato il 27 aprile 2017)*

**Aggiunto:**

&#x200B;* Aggiungi nuovo progetto di esempio &quot;Meet Mat&quot;
&#x200B;* [Plugin] Nuovo plug-in &quot;Resources Updater&quot;
&#x200B;* [TextureSet] Consente di rinominare e aggiungere una descrizione ai set di texture
&#x200B;* [TextureSet] Consente di riassegnare i materiali
&#x200B;* [TextureSet] Pulsante Aggiungi impostazione nella finestra elenco set di texture
&#x200B;* [TextureSet] Mostra i set di texture &quot;disabilitati&quot; nella parte inferiore dell’elenco
&#x200B;* [Substance] Utilizzate mappe aggiuntive con la risoluzione del set di texture corrente per migliorare le prestazioni
&#x200B;* [Scripting] Consente di aggiornare una risorsa utilizzata in un progetto (materiale, generatore, ecc.)
&#x200B;* [Scripting] Aggiungere un modo per aggiungere/rimuovere uno scaffale
&#x200B;* [Scripting] Consente di eseguire query sulle informazioni dalla risorsa nei progetti
&#x200B;* [Scripting] Consente di recuperare un elenco di scaffali disponibili
&#x200B;* [Scripting] Esercitazione per migliorare la miniatura di AlgWidget
&#x200B;* [Esporta] Disattiva/attiva profondità di bit in base al supporto del formato di file
&#x200B;* [Log] Aggiungi il nome del plug-in per la stampa nella console
&#x200B;* [Log] Rimuovi errore sui set di texture nascosti
&#x200B;* Aggiornate la &quot;Schermata introduttiva&quot; con nuove icone e testo per gli esempi

**Corretto:**

&#x200B;* Arresto anomalo durante l’aggiornamento di una trama in progetti specifici
&#x200B;* [Finestra vista] Il colore interno del piano di simmetria non è più visibile
&#x200B;* [Riquadro di visualizzazione] Alcuni effetti di post-elaborazione sono attivati quando si utilizza la vista Solo
&#x200B;* [Ombreggiature] La fusione &quot;sopra\_predefinito&quot; non funziona correttamente
&#x200B;* [Shader] Avvertenza sul test alfa con lo shader predefinito
&#x200B;* [Shelf] Analisi errata dei tag dalle Substance
&#x200B;* [Shelf] MatFX Ruggine Weathering non funziona correttamente
&#x200B;* [Shelf] Per impostazione predefinita, il filtro HSL è attivato sui canali errati
&#x200B;* [Shelf] Per impostazione predefinita, l’opzione Nitidezza è abilitata nel canale Height/Normale
&#x200B;* [Esporta] I predefiniti di esportazione Vray non utilizzano una mappa normale OpenGL
&#x200B;* [Tool] Problemi di imprecisione con lo strumento Clona/Sfumino per creare artefatti

### 2.5.3

*(Rilasciato il 15 marzo 2017)*

**Corretto:**

&#x200B;* [Baker] Arresto anomalo durante la cottura al forno con trame specifiche

**Problemi noti:**

&#x200B;* [Mac] In alcuni casi, le particelle possono danneggiare le texture

### 2.5.2

*(Rilasciato il 14 marzo 2017)*

**Corretto:**

&#x200B;* [Tool] I tablet Wacom non funzionano su Linux
&#x200B;* [Strumento] Artefatti di nero quando si utilizza lo strumento sfumino
&#x200B;* [Panettieri] La cottura non riesce se si utilizza Corrispondenza per nome con una gabbia
&#x200B;* [Panettieri] Occlusione ambiente interrotta durante la cottura al forno solo con carta normale
&#x200B;* [Shelf] I filtri generici non gestiscono correttamente il canale alfa (Contrasto/Luminosità, Passa alto, ecc.)
&#x200B;* [Riquadro di visualizzazione] Problema di prestazioni durante il caricamento di un progetto con le ombre attivate
&#x200B;* [Riquadro di visualizzazione] Problema di dithering nella vista 3D su MacOS
&#x200B;* [Finestra vista] Le anteprime delle particelle non vengono visualizzate correttamente quando il profilo colore è attivato
&#x200B;* [Iray] Arresto anomalo quando si ritorna al progetto OpenGL se l’inizializzazione di Iray non riesce
&#x200B;* [IRay] La luminosità viene ignorata durante il rendering dello shader SpecGloss/mdl
&#x200B;* [Shader] Lo shader Spec/Gloss non corrisponde a Iray e SD
&#x200B;* [Shader] Conversione sRGB diversa dalla conversione LUT lineare in sRGB
&#x200B;* [Shader] Rendering errato durante il caricamento di un progetto con ombreggiature obsolete
&#x200B;* [Shader] Lo shader &quot;pbr-coated&quot; non funziona più
&#x200B;* [Esportazione] Alcuni canali vengono comunque esportati anche se non presenti nel set di texture
&#x200B;* [Livelli] Il metodo di fusione &quot;mappa normale, inverti dettagli&quot; non funziona sui canali in scala di grigio
&#x200B;* [UI] Problema nella &quot;Finestra di selezione del colore&quot; con monitor HDPI e zoom dello schermo al 150%

**Problemi noti:**

&#x200B;* [Mac] In alcuni casi, le particelle possono danneggiare le texture

### 2.5.1

*(Rilasciato il 27 febbraio 2017)*

**Corretto:**

&#x200B;* [Mac] Input del tablet Wacom interrotto nella vista 3D e 2D
&#x200B;* [Panettieri] La corrispondenza per nome non funziona più
&#x200B;* [Panettieri] L’impostazione &quot;Normali medi&quot; non funziona più
&#x200B;* [Iray] Rendering non corretto con mappa normale inattiva
&#x200B;* [Iray] I profili colore si comportano in modo diverso rispetto al modulo di rendering OpenGL
&#x200B;* [Iray] L’esportazione del rendering come bitmap non include la correzione del profilo colore
&#x200B;* [Substance] I Filtri materiali non funzionano più
&#x200B;* [Strumento] L&#39;opacità del tratto non viene memorizzata nei predefiniti del pennello
&#x200B;* [Strumento] L’allineamento UV del pennello clone non funziona più
&#x200B;* [Esporta] Il canale di Spostamento deve essere centrato in 0,5 quando si esporta in numeri interi
&#x200B;* [Template] Il percorso assoluto è memorizzato in Templates
&#x200B;* [TextureSet] La texture del canale rimane inalterata dopo la rimozione del canale

**Problemi noti:**

&#x200B;* [Linux] Gli input dei tablet Wacom non funzionano in 3D e Vista 2D
&#x200B;* [Mac] In alcuni casi, le particelle possono danneggiare le texture
&#x200B;* [Esportazione] In casi molto rari, possono apparire rettangoli neri sulle GPU AMD

### 2.5.0

*(Rilasciato il 21 febbraio 2017)*

**Aggiunto:**

&#x200B;* Aggiunta del supporto per le GPU AMD Radeon Pro e AMD FirePro
&#x200B;* [Tool] Aggiungi il supporto per l’opacità del tratto
&#x200B;* [Tool] Aggiungi un modificatore che consenta di continuare l’ultimo tratto del pennello
&#x200B;* [Iray] Aggiornamento per supportare le GPU Pascal
&#x200B;* [Finestra vista] Aggiungere il supporto per i profili colore (LUT)
&#x200B;* [Substance] Integrazione del nuovo framework (motore SD6)
&#x200B;* [UI] Aumenta l’elenco dei file recenti nel menu File
&#x200B;* [Importa] Utilizza la categoria da sostanze per riempire il prefisso nella finestra di dialogo di importazione
&#x200B;* [Panettieri] Consenti di cuocere texture 8K
&#x200B;* [Baker] Consente di eseguire i baking risoluzioni non quadrate
&#x200B;* [Pannelli] Migliora il consumo di memoria durante la cottura di trame pesanti ad alto polio
&#x200B;* [Shelf] Bloccare gli scaffali (e i progetti) per impedire la modifica simultanea ed evitare corruzioni
&#x200B;* [Shelf] Leggi la categoria e le parole chiave delle sostanze per utilizzarle per filtrare
&#x200B;* [Shelf] Consente di escludere le risorse dal risultato di una query di ricerca
&#x200B;* [Shelf] Calcolo temporale delle miniature migliorato
&#x200B;* [Shelf] Consenti di incorporare predefiniti nei progetti
&#x200B;* [Shelf] Consente di comprimere/espandere rapidamente la vista struttura con MAIUSC
&#x200B;* [Shelf] Consente di salvare le miniature quando le risorse sono di sola lettura (cache locale)
&#x200B;* [Scaffale] Nuovo contenuto : nuovi filtri (trasformazione, specchio, triplanare, ecc.)
&#x200B;* [Shelf] Nuovo contenuto : nuovi profili LUT (classici e artistici, come Film Noir, Vintage, ecc.)
&#x200B;* [Shelf] Nuovo contenuto : 10 nuove Substance di font per generare rapidamente testi personalizzati
&#x200B;* [Shelf] Nuovi modelli: Unità 5 e motore irreale 4
&#x200B;* [Shelf] Il filtro HSL è stato migliorato per semplificare maggiormente l&#39;uso degli artisti
&#x200B;* [Shader] Aggiungi il supporto per il canale di specular level negli shader PBR
&#x200B;* [Shader] Aggiungere il supporto per il dithering nello shader di test di Alpha
&#x200B;* [Shader] Aggiungi il supporto per la mappatura delle occlusioni parallasse negli shader PBR
&#x200B;* [Shader] Consente di definire un&#39;interfaccia utente personalizzata per i parametri dello shader
&#x200B;* [MatLayering] Crea un nuovo canale maschera per il flusso di lavoro per la creazione di livelli di materiale
&#x200B;* [Scripting] Consenti la scrittura di metadati in un progetto SP
&#x200B;* [Scripting] Consente di esportare con un predefinito di esportazione specifico
&#x200B;* [Scripting] Consente di recuperare i parametri dello shader come JSON.
&#x200B;* [Scripting] Aggiunta del supporto per le connessioni WebSocket
&#x200B;* [Scripting] Aggiungi la possibilità di caricare istanze dello shader
&#x200B;* [Scripting] Aggiungi la possibilità di creare un nuovo progetto
&#x200B;* [Scripting] Consente di recuperare l’URL della trama importata in un progetto
&#x200B;* [Scripting] Consenti esegue i baking non quadrata
&#x200B;* [Scripting] Segnala errori durante l’impostazione dei dati tramite API di scripting
&#x200B;* [Substance] Aggiungi tag utente-dati per specificare il formato mappa normale

**Corretto:**

&#x200B;* Arresto anomalo di selezione del colore con le sostanze
&#x200B;* Arresto anomalo durante il caricamento di un&#39;immagine non RGBA32f come mappa dell&#39;ambiente
&#x200B;* Arresto anomalo relativo alla pittura su GPU AMD
&#x200B;* [Trama] L’importazione OBJ non riconosce i materiali senza file mtl
&#x200B;* [Trama] La generazione del nome del set di texture UDIM può non essere corretta su alcune trame
&#x200B;* [UI] Pulsante Annulla/Ripeti nel visualizzatore Impostazione dello stato attivo e interruzione dello scorrimento del mouse
&#x200B;* [UI] Alcune etichette sono ritagliate in modo errato in High-DPI
&#x200B;* [Livello] Il comportamento della modalità Sostituisci per l’effetto pittura non è corretto nella maschera
&#x200B;* [Layer] Il metodo di fusione Sottrai ha un comportamento errato con alfa
&#x200B;* [Strumento] La dimensione del pennello diventa enorme in vista 2D quando si dipinge sui bordi UV
&#x200B;* [Tool] La linea retta agganciata ha un comportamento irregolare con DPI alto
&#x200B;* [Strumento] La risoluzione dello stencil a volte non è corretta
&#x200B;* [Baker] I valori di &quot;Distanza max occlusione&quot; sono bloccati se &quot;relativa al rettangolo di selezione&quot; è &quot;Disattivato&quot;
&#x200B;* [Shader] Le definizioni dei canali di stack e di param automatico non corrispondono
&#x200B;* [vista 3D] Visualizzazione incoerente del canale normale a seconda dell&#39;impostazione del progetto
&#x200B;* [Riquadro di visualizzazione] Alcune mappe normali hanno valori bloccati che appaiono come artefatti
&#x200B;* [Riquadro di visualizzazione] Gli effetti a posteriori sono sempre disattivati per impostazione predefinita
&#x200B;* [Esporta] L’impostazione di miscelazione normale non è corretta se manca il canale normale
&#x200B;* [Esportazione] Generazione di texture errata in alcuni casi su GPU AMD
&#x200B;* [Esporta] I parametri degli Shader non vengono esportati correttamente se sono inclusi in un gruppo
&#x200B;* [Export] La modifica di un predefinito di esportazione in uno scaffale personalizzato genera un errore di registro
&#x200B;* [Shelf] Il filtro della visualizzazione a struttura non corrisponde esattamente al nome della cartella
&#x200B;* [Shelf] Ridenominare un predefinito di shelf è difficile da leggere
&#x200B;* [Shelf] La risorsa Shader importata nello Shelf non viene mantenuta dopo il riavvio
&#x200B;* [Shelf] Contenuto : Predefinito strumento saldatura mancante
&#x200B;* [Shelf] Contenuto: il Tile Generator non funziona correttamente
&#x200B;* [Scaffale] Contenuto : Corretta maschera errata su materiale intelligente sporco di gomma
&#x200B;* [Shelf] Contenuto : Corretto il nome del gruppo errato sul materiale del sacchetto in pelle
&#x200B;* [Iray] Metà delle maglie è mancante in Iray
&#x200B;* [Linux] Arresto anomalo quando si trascina una risorsa sopra la vista 3D
&#x200B;* [Mac] Le preferenze vengono reimpostate a ogni avvio su Sierra

**Problemi noti:**

&#x200B;* [Esportazione] In casi molto rari, possono apparire rettangoli neri sulle GPU AMD
&#x200B;* [Iray] I profili colore a volte possono comportarsi in modo strano

### 2.4.1

*(Rilasciato il 28 ottobre 2016)*

**Corretto:**

&#x200B;* Arresto anomalo durante la creazione di un progetto con un modello
&#x200B;* Arresto anomalo quando si chiude la finestra di dialogo di esportazione durante un’esportazione
&#x200B;* [Mac] Errori durante il salvataggio del progetto (impossibile salvare il predefinito di esportazione)
&#x200B;* [Shelf] Quando si crea un nuovo predefinito, questo viene visualizzato due volte
&#x200B;* [Shelf] I predefiniti non possono essere caricati in modalità di sola lettura senza diritti di amministratore

### 2.4.0

*(Rilasciato il 27 ottobre 2016)*

**Aggiunto:**

&#x200B;* [Shelf] Nuova interfaccia per sfogliare le risorse (vista struttura, filtri e così via)
&#x200B;* [Shelf] Consente di salvare una ricerca come predefinito
&#x200B;* [Shelf] Consente di creare una nuova finestra da un predefinito
&#x200B;* [Shelf] Nuova interfaccia per l&#39;importazione delle risorse
&#x200B;* [Shelf] Non copiare lo scaffale allegorico predefinito nella cartella Documenti
&#x200B;* [Shelf] Nuovi predefiniti particelle : Circuito elettrico, Linee elettriche, Rococò, Vene piccole
&#x200B;* [Shelf] Migliorati i vecchi predefiniti particelle per essere più facili da usare (come &quot;Rain&quot;)
&#x200B;* [Shelf] Aggiungi nuove informazioni nel menu contestuale della risorsa
&#x200B;* [Finestra di visualizzazione] Miglioramento delle prestazioni durante il caricamento delle mappe dell&#39;ambiente
&#x200B;* [Finestra vista] Aggiungi il supporto per mappe di ambiente che non sono alimentate da due

**Corretto:**

&#x200B;* Arresto anomalo durante la rimozione di una maschera
&#x200B;* Arresto anomalo quando si disegna dopo aver salvato un predefinito
&#x200B;* Arresto anomalo con sfocatura dell’ambiente su alcune GPU
&#x200B;* Arresto anomalo durante l’assegnazione di una risorsa errata al mini scaffale
&#x200B;* [Shelf] Pulisci e salva rimuovi tag e metadati per le risorse nel progetto
&#x200B;* [Shelf] l’importazione di un predefinito ne mostra le risorse nello shelf
&#x200B;* [Esporta] La mappa normale generata dal canale del height ha un’intensità bassa
&#x200B;* [Esporta] Normale da trama non è sempre presente nella mappa normale finale
&#x200B;* [Esportazione] Talvolta può verificarsi una dilatazione con trasparenza senza alcuna trasparenza
&#x200B;* [Scripting] &quot;alg.plugin\_root\_directory&quot; può restituire un percorso di rete troncato
&#x200B;* Il pulsante [TextureSet] Lock (Blocca texture) è attivato quando si riaprono progetti non quadrati

### 2.3.1

*(Rilasciato il 7 ottobre 2016)*

**Aggiunto:**

&#x200B;* [Plugin]&#x200B;[Photoshop] Consente di specificare quale materiale/stack/canale esportare
&#x200B;* [Scripting] I nomi delle funzioni presentano alcune incongruenze

**Corretto:**

&#x200B;* L’Alpha [Esporta] può essere eliminato nei predefiniti di esportazione personalizzati
&#x200B;* [Export] L’Alpha ottiene una conversione gamma errata sui canali sRGB
&#x200B;* [Esporta] I documenti non quadrati vengono esportati come quadrati
&#x200B;* [Esporta] Impossibile esportare mappe aggiuntive se ne manca una
&#x200B;* [Iray] Alcuni parametri (come Intensità emissiva) non hanno alcun effetto
&#x200B;* [NVIDIA] Arresto anomalo all&#39;avvio con NVIDIA Quadro K2200/GTX 750/760
&#x200B;* [AMD] Set di colori non corretto per miniature e anteprime
&#x200B;* [AMD] Si blocca e si verifica un errore del driver all&#39;apertura di un nuovo file
&#x200B;* [Log] &quot;versione-software&quot; mancante nel file di log

### 2.3.0

*(Rilasciato il 15 settembre 2016)*

**Aggiunto:**

&#x200B;* [Plugin] Nuovo plug-in &quot;Esporta in Photoshop&quot; (esportazione dello stack di livelli completo)
&#x200B;* [Esporta] Consente di specificare la larghezza della spaziatura interna (in pixel o infinito)
&#x200B;* [Esporta] Consente di impostare il tipo di sfondo esterno agli UV
&#x200B;* [Shelf] Nuovo shader di stratificazione del materiale per fondere 10 materiali
&#x200B;* [Shelf] Nuovo shader argilla per visualizzare i dettagli con il canale height/normale
&#x200B;* [Shelf] Nuovo filtro di illuminazione cotta con input ambientale
&#x200B;* [Shelf] Sono stati aggiornati alcuni generatori di maschere per aggiungere trasformazioni non quadrate
&#x200B;* [Finestra vista] Aggiungere la mappa normale composta (normale+height+bake) alla modalità Solo
&#x200B;* [Scripting] Consente di esportare mappe aggiuntive
&#x200B;* [Scripting] Consente di eseguire query sulle mappe aggiuntive disponibili per set di texture
&#x200B;* [Scripting] Consente di recuperare il formato del canale
&#x200B;* [Scripting] Aggiungere esempi nella documentazione di cottura
&#x200B;* [Scripting] Consente di interrogare la visibilità di un livello
&#x200B;* [Scripting] Consente di interrogare il metodo di fusione e l’opacità del livello
&#x200B;* [Scripting] Consente di esportare le mappe convertite (mappe normali finali, AO misti, ecc.)
&#x200B;* [Substance] Lettura e connessione di utilizzi personalizzati
&#x200B;* [Scelte rapide] Aggiungi il tasto modificatore (MAIUSC) per tornare alla modalità Solo
&#x200B;* [Esporta] Predefinito di esportazione predefinito aggiornato per disattivare il canale alfa
&#x200B;* [UI] Le miniature ora vengono calcolate solo se il motore è disponibile
&#x200B;* [UI] Visualizza una menzione quando le miniature sono elaborate

**Corretto:**

&#x200B;* Arresto anomalo con alcuni vecchi progetti all’apertura
&#x200B;* Arresto anomalo con cache canali texture danneggiata
&#x200B;* Arresto anomalo quando si fondono più di 4 materiali con il flusso di lavoro Livelli di materiale
&#x200B;* [UI] Le scelte rapide degli strumenti non funzionano se la barra degli strumenti è nascosta
&#x200B;* [UI] La barra degli strumenti Iray è etichettata &quot;Senza titolo&quot; nel menu Visualizza
&#x200B;* [UI] Le barre degli strumenti plug-in sono denominate &quot;Untilted&quot; nel menu Visualizza
&#x200B;* [Baker] Premendo Invio durante la modifica di un&#39;impostazione di esegue i baking si avvia la esegue i baking
&#x200B;* [Baker] Intervalli errati per alcuni parametri
&#x200B;* [Importa] Impossibile importare mesh OBJ a causa di numeri molto grandi
&#x200B;* [Importa] Alcuni file OBJ vengono importati con troppi sottooggetti
&#x200B;* Lo sfondo del canale [Esporta] viene riempito di nero al posto del colore predefinito al momento dell’esportazione
&#x200B;* [Strumento] Le particelle non funzionano correttamente se il valore FOV è troppo basso
&#x200B;* [Strumento] Il colore di anteprima del pennello non è corretto con le maschere nei sottoinsiemi
&#x200B;* [Finestra vista] Quando il pennello entra in aree vuote nel Vista 2D diventa gigantesco
&#x200B;* [Riquadro di visualizzazione] Anteprima pennello vuoto quando si disegna texture normale
&#x200B;* [Scripting] Documentazione errata: &quot;ao&quot; elencato invece di &quot;ambientocclusion&quot;
&#x200B;* [Scripting] Il processo avviato con subprocess() viene interrotto alla chiusura di Painter
&#x200B;* [Shelf] Il filtro di illuminazione Eseguito i baking utilizza un input AO errato
&#x200B;* [MacOS] Progetto rimosso dell&#39;idrante (incompatibile)
&#x200B;* Il progetto predefinito viene aperto quando si carica un file \*.spt (anziché \*.spp)

**Problemi noti:**

&#x200B;* [Plugin] A causa di Photoshop, il height e il canale normale non possono essere tradotti così com’è

### 2.2.0

*(Rilasciato il 22 luglio 2016)*

**Aggiunto:**

&#x200B;* [Shelf] Miglioramento del sistema di ricerca e delle query
&#x200B;* [Shelf] Aggiungi campo di ricerca per i mini-scaffali
&#x200B;* [Shader] Consente di definire la precisione dei passi per i cursori
&#x200B;* [Shader] Aggiungere un pulsante Annulla/Ripeti per i parametri dello shader
&#x200B;* [Shader] Il ricaricamento di uno shader non deve reimpostarne i parametri
&#x200B;* [MatLayering] Aggiungi il supporto per Stratificazioni dinamiche del materiale e sottopile
&#x200B;* [MatLayering] Consenti di importare un file json per configurare le impostazioni dello shader
&#x200B;* [MatLayering] Limite sblocca i campionatori texture (passa a texture senza binding)
&#x200B;* [Scripting] Consenti di impostare le impostazioni dei panettieri e avviare il loro calcolo
&#x200B;* [Substance] Utilizzare &quot;utilizzo&quot; per connessioni di input/output oltre agli identificatori
&#x200B;* [Tool] Consente di selezionare il canale di anteprima nella finestra della vista per lo strumento di proiezione

**Corretto:**

&#x200B;* Arresto anomalo all&#39;avvio se le sostanze si trovano in una cartella errata
&#x200B;* Il rapporto sugli arresti anomali a volte non funziona a causa di un file di registro errato
&#x200B;* [Iray] Gli effetti post non si aggiornano quando Iray è in pausa
&#x200B;* [Iray] La scelta rapida per l&#39;attivazione automatica non funziona più
&#x200B;* [Iray] Il comportamento del cursore Apertura varia a seconda delle dimensioni della risorsa
&#x200B;* [Livelli] Il primo canale di materiale non è attivato per impostazione predefinita se è disattivato
&#x200B;* [Shader] Se un &quot;param auto&quot; non è corretto, non vengono stampati errori

**Problemi noti:**

&#x200B;* [Mac] Il limite di campioni di texture è bloccato su 16 (problema con il driver della GPU)

### 2.1.1

*(Rilasciato il 1° luglio 2016)*

**Aggiunto:**

&#x200B;* [Licenza] Possibilità di modificare il percorso del file di licenza
&#x200B;* [Finestra vista] Aggiungi una scelta rapida &quot;B&quot; per passare da una mappa all’altra
&#x200B;* [Importazione] Consente di importare correttamente FBX 2016/2017
&#x200B;* [Strumento] Rimuovi i controlli quando si utilizza la maschera veloce
&#x200B;* [Iray] Aggiungere informazioni sulle dimensioni della scena
&#x200B;* [Iray] Consente di aumentare il numero massimo di campioni e il tempo di rendering
&#x200B;* [UI] Aggiorna immediatamente i risultati quando si utilizza il pulsante +/- sui cursori
&#x200B;* [UI] Consente una maggiore precisione per i cursori in scala di grigi
&#x200B;* [Esporta] Non esportare un canale alfa per texture che sono solo RGB
&#x200B;* [Esporta] Aggiorna predefinito di esportazione Dota 2
&#x200B;* [Shelf] Nuovo pattern &quot;Esagono piastrelle&quot;
&#x200B;* [Shelf] Nuovo strumento &quot;Saldatura&quot;
&#x200B;* [Shelf] Filtri di finitura aggiornati per fornire controlli di direzione

**Corretto:**

&#x200B;* [Esportazione] Impossibile esportare file PSD in 8 bit
&#x200B;* [Esportazione] L&#39;esportazione 8K non è disponibile in alcune configurazioni hardware
&#x200B;* [Esporta] La finestra Sketchfab è ritagliata
&#x200B;* [Esporta] Mapping di rugosità errato nel predefinito di esportazione Spec/Gloss
&#x200B;* [UI] La digitazione nei cursori in scala di grigio non funziona più
&#x200B;* [UI] Impossibile inserire filtri negli input di substance (come Generatori)
&#x200B;* [UI] Alcuni cursori hanno comportamenti insoliti
&#x200B;* [UI] Il passaggio DeltaTime +/- per le particelle è troppo grande
&#x200B;* [Iray] Alcuni progetti bloccano l&#39;applicazione quando si passa a Iray
&#x200B;* [Iray] Arresto anomalo durante il rilevamento dell&#39;hardware
&#x200B;* [Strumento] Il colore di anteprima del pennello non è corretto in modalità Maschera
&#x200B;* [Tool] Il selettore di materiali può essere utilizzato con strumenti incompatibili
&#x200B;* [Tool] L’anteprima della proiezione non passa alla Diffusa con il flusso di lavoro Specifiche/lucido
&#x200B;* [Shelf] La modifica dello shader predefinito interrompe gli smart mats/le anteprime delle maschere avanzate
&#x200B;* [Shelf] Alcuni materiali avanzati hanno nomi errati
&#x200B;* [Ripiano] Altre forme alfa sono danneggiate e non vengono caricate
&#x200B;* [Finestra della vista] Passare alla modalità &quot;Mappa aggiuntiva&quot; e visualizzare prima &quot;Altro&quot;
&#x200B;* [Viewport] Il viewport torna a &quot;other&quot; quando non esiste una mappa aggiuntiva
&#x200B;* [Arresto anomalo]&#x200B;[Linux] Il report di Arresto anomalo non funziona su Ubuntu (Steam)
&#x200B;* [Arresto anomalo]&#x200B;[Linux] I collegamenti agli URL Web non funzionano su Ubuntu (Steam)
&#x200B;* [Arresto anomalo]&#x200B;[Windows] Rimuovi &quot;crashwatcher&quot; quando Substance Painter non viene più eseguito
&#x200B;* [Arresto anomalo]&#x200B;[Mac] Il sistema di rapporti di Arresto anomalo non funziona correttamente
&#x200B;* [Arresto anomalo] L’importazione di una trama durante l’importazione di una trama porta a un arresto anomalo
&#x200B;* Set di texture scelta rapida da tastiera di prelievo reimpostato su niente dopo un riavvio

### 2.1.0

*(Rilasciato il 2 giugno 2016)*

**Aggiunto:**

&#x200B;* [UDIM] Importa porzioni UDIM da una trama come set di texture
&#x200B;* [Linux] È stato aggiunto il supporto per CentOS 6.6 e Ubuntu 12.4
&#x200B;* [Esportazione] Aggiungi risoluzione 8K (sperimentale)
&#x200B;* [Esporta] Consenti di scegliere la profondità di bit durante l’esportazione
&#x200B;* [Baker] Consenti di eseguire i baking più set di texture contemporaneamente
&#x200B;* Supporto di monitor ad alta risoluzione (ridimensionamento DPI elevato)
&#x200B;* [Scripting] Impostate la risoluzione e il riempimento personalizzati per texture al momento dell’esportazione
&#x200B;* [Riquadro di visualizzazione] Consente di passare da un set di texture all’altro facendo clic sulla trama (tramite Ctrl+Alt+Clic)
&#x200B;* [Finestra vista] Posizionare il cursore del mouse quando si esegue lo zoom con la rotellina del mouse
&#x200B;* [UI] Aggiorna la visualizzazione predefinita del colore di sfondo e della mappa dell&#39;ambiente
&#x200B;* [UI] Aggiungi descrizioni comandi con nomi originali per i canali utente
&#x200B;* [UI] Modifica il colore di sfondo per i canali che non possono essere rinominati
&#x200B;* [Strumento] Rimuovi i controlli quando si utilizza la maschera veloce
&#x200B;* [Shader] Consente di definire i gruppi per i parametri dello shader e i materiali/le maschere
&#x200B;* [Motore] Ottimizzazione della stampa di piccole dimensioni
&#x200B;* [Stencil] Aggiungi &quot;W&quot; come scelta rapida per attivare/disattivare temporaneamente la maschera
&#x200B;* [Shelf] Aggiungi un pulsante x per cancellare il campo di ricerca
&#x200B;* [Shelf] Caricare l&#39;Alpha con un solo clic
&#x200B;* [Shelf] Nuovo predefinito di esportazione: Vray UDIM, Arnold UDIM, Spec/Gloss da Metal/Rough
&#x200B;* [Scaffale] Nuove alfa: forme geometriche, vene e insegne
&#x200B;* Aggiungi nome e versione nelle proprietà dell&#39;eseguibile Substance Painter

**Corretto:**

&#x200B;* [Substance] Impossibile utilizzare contemporaneamente il canale normale e la mappa aggiuntiva
&#x200B;* [Iray] La rifrazione MDL e l&#39;impostazione assorbimento non funzionano
&#x200B;* [Iray] La scala della scena originale non viene mantenuta
&#x200B;* [Shelf] Il modello Specular/lucidità utilizza uno shader errato
&#x200B;* [Esporta] Il predefinito di esportazione predefinito non esporta alcune mappe (come AO)
&#x200B;* [Riquadro di visualizzazione] Il punto pivot non si aggiorna quando si fa clic al di fuori degli UV nella vista 2D
&#x200B;* [UI] I valori del cursore sono arrotondati
&#x200B;* [UI] A volte quando si modificano i valori dei cursori, lo spazio libero è molto ridotto
&#x200B;* [Nuovo progetto] L’elenco a discesa del modello non è aggiornato correttamente (da 1.x a 2.x)
&#x200B;* [Scripting] Corretto il comportamento al passaggio del mouse sui pulsanti personalizzati
&#x200B;* [Mac] L’annullamento su un progetto vuoto blocca la videocamera

**Problemi noti:**

&#x200B;* Il report di Arresto anomalo non è disponibile su Ubuntu
&#x200B;* Alcuni pulsanti URL potrebbero non funzionare. Consulta le domande frequenti per una soluzione alternativa.

### 2.0.5

*(Rilasciato il 29 aprile 2016)*

**Aggiunto:**

&#x200B;* [Shelf] Aggiunto/Aggiornato modello non pbr, shader ed esportazione predefinito
&#x200B;* [Shelf] Predefinito di esportazione UE4 aggiornato per includere l&#39;Occlusione ambientale

**Corretto:**

&#x200B;* Arresto anomalo durante l&#39;apertura e il salvataggio di alcuni progetti con risorse danneggiate
&#x200B;* [Finestra vista] Il Wireframe appare interrotto nel Vista 2D
&#x200B;* [Shelf] Prestazioni migliorate di alcune mappe dell&#39;ambiente di studio
&#x200B;* [Shelf] Alcune mappe dell&#39;ambiente di studio sono duplicate
&#x200B;* [Ripiano] &quot;Materiale di illuminazione Eseguito i baking&quot; mancante
&#x200B;* [Shelf] Generatore &quot;Conversione in scala di grigi&quot; mancante

### 2.0.4

*(Rilasciato il 26 aprile 2016)*

**Aggiunto:**

&#x200B;* Migliorare le collisioni di trama e ottimizzare il rendering dei wireframi
&#x200B;* Migliorare le prestazioni e la gestione della memoria con i grandi progetti
&#x200B;* Migliorare la precisione del cursore e i passaggi
&#x200B;* [UI] Aggiorna il motore solo quando si convalida un cursore (non quando si immette un valore)
&#x200B;* [UI] Sposta lo switch Iray in un pulsante dedicato nella barra degli strumenti principale (e cambiane la scelta rapida da tastiera)
&#x200B;* [Tool] Aggiungi impostazione per il comportamento di posizione della sorgente dello strumento Clone
&#x200B;* [Shader] Consente di leggere i colori dei vertici della trama negli ombreggiatori personalizzati
&#x200B;* [Scripting] Consente di recuperare l’elenco di set di texture, canali e livelli
&#x200B;* [Scripting] Aggiunta di funzioni di supporto (URL del percorso, recupero del percorso di esportazione dal progetto)
&#x200B;* [Mac] Rileva la versione &quot;El Capitan&quot; del sistema operativo Mac nel file di registro

**Corretto:**

&#x200B;* Arresto anomalo dopo la seconda esportazione nel Substance share
&#x200B;* Arresto anomalo durante la copia di un livello tra set di texture con dati maschera rapidi.
&#x200B;* Alcuni progetti hanno un programma di aggiornamento molto lungo che richiede molta memoria
&#x200B;* [Strumento] Arresto anomalo quando si seleziona un predefinito di particella con lo strumento clone/sfumino
&#x200B;* [Baker] Il caricamento dei file FBX richiede troppo tempo per le trame pesanti
&#x200B;* [Viewport] Mapping di ambiente esteso in alcuni computer
&#x200B;* [Finestra vista] Conversione gamma errata dell’alfa del pennello
&#x200B;* L&#39;Alpha [Esporta] viene memorizzato come trasparenza anziché come canale separato con file Tiff.
&#x200B;* [Export] Il canale normale viene sempre esportato come OpenGL
&#x200B;* [Iray] Nomi dei cursori mancanti per le impostazioni Iray
&#x200B;* [Iray] Il rendering viene eseguito con una risoluzione errata su Retina/High DPI
&#x200B;* [Iray] Arresto anomalo durante il ridimensionamento dell’interfaccia in modalità Iray
&#x200B;* [Iray] Enorme rallentamento delle prestazioni durante il rendering a risoluzioni basse
&#x200B;* [Iray] La pausa non funziona (Iray continua a elaborare in background)
&#x200B;* Il canale normale a volte presenta artefatti quadrati neri
&#x200B;* Il canale normale viene invertito dai filtri in scala di grigio
&#x200B;* Il canale normale non si fonde correttamente se la pila ha del canale alfa
&#x200B;* Il progetto viene modificato sul disco quando si apre un progetto, anche se non è stato ancora salvato
&#x200B;* La reimportazione di una trama su alcuni progetti dà prestazioni GPU molto cattive
&#x200B;* L’orientamento del pennello non è corretto quando non si tocca una trama
&#x200B;* Il logo del substance share non è presente nella schermata iniziale

### 2.0.2

*(Rilasciato il 25 marzo 2016)*

**Aggiunto:**

&#x200B;* [Iray] Aggiornate il modello Spec/Gloss e lo shader per garantire la compatibilità con Iray
&#x200B;* [Esporta] Possibilità di esportare le schermate in ArtStation
&#x200B;* [Scripting] Supporto dell&#39;esecuzione dalla directory dei plug-in
&#x200B;* [Scripting] Consenti di &quot;Salva con nome&quot;
&#x200B;* [UI] Consenti di fare doppio clic su un cursore per modificarne il valore
&#x200B;* Sposta il campione della Vela nel Substance share
&#x200B;* Nuovo progetto di esempio: Sphere Preview
&#x200B;* Avvisa gli utenti in caso di conflitto di estensione della shell

**Corretto:**

&#x200B;* Il programma di installazione sovrascrive l&#39;installazione di Substance Painter 1.x
&#x200B;* [UI] Il layout dell&#39;elenco dei canali è interrotto con i filtri
&#x200B;* [UI] I parametri di Shader non vengono visualizzati
&#x200B;* [UI] Quando si ridimensiona la finestra del livello, il contenuto viene ritagliato in modo errato
&#x200B;* [Tool] Il canale di opacità non viene sempre utilizzato correttamente
&#x200B;* [Strumento] Sfumino/Clona /Clone non funziona con Simmetria
&#x200B;* [Tool] L’opacità dell’anteprima del pennello non è corretta in alcuni canali
&#x200B;* [Iray] Arresto anomalo quando si utilizza Iray mentre non è ancora stato creato
&#x200B;* [Iray] Impossibile caricare i dati delle impostazioni di iray dal progetto
&#x200B;* [Iray] Iray non si occupa della modifica delle impostazioni dopo una pausa
&#x200B;* [Scaffale] L&#39;importazione di un materiale sullo scaffale non funziona
&#x200B;* Lo stencil non funziona con il canale Normale
&#x200B;* Arresto anomalo di disegno su alcuni progetti
&#x200B;* Arresto anomalo quando si dipinge con particelle su alcuni progetti
&#x200B;* Arresto anomalo con Elaboratore pixel durante alcuni calcoli

### 2.0.0

*(Rilasciato il 16 marzo 2016)*

**Aggiunto:**

&#x200B;* Scelta rapida da tastiera in Substance Archivia nella barra degli strumenti principale
&#x200B;* Rendering di immagini con modalità di visualizzazione ed esportazione di schermate
&#x200B;* Supporto per la creazione e l’utilizzo di &quot;Maschera avanzata&quot;
&#x200B;* Supporto per il flusso di lavoro PBR Specular/lucidi (con nuovo canale di diffusione)
&#x200B;* Concatenamento di Substance (per collegare le sostanze agli input dell&#39;immagine substance)
&#x200B;* Supporto dello scripting con i plug-in personalizzati
&#x200B;* Migliorare la conversione da Height a Normale utilizzando un filtro Sobel
&#x200B;* Passa la risoluzione dell&#39;anteprima Stencil/Proiezione a 2K
&#x200B;* Aggiungere un canale normale per impostazione predefinita per i nuovi progetti
&#x200B;* Lettura del tag dati utente dal nodo di output per abilitare/disabilitare i canali di una sostanza per impostazione predefinita
&#x200B;* Esporre la fusione Normale/AO nelle impostazioni TextureSet
&#x200B;* [Tool] Nuovo strumento Sfumino per fondere e diffondere i colori
&#x200B;* [Strumento] Nuovo strumento Clona /Clone per copiare una parte delle texture
&#x200B;* [Strumento] Consenti di selezionare i canali per lo strumento Sfumino, Clona /Clone e Gomma
&#x200B;* [Livello] Aggiungi nome Substance per nome effetto di riempimento
&#x200B;* [Livello] Consente di esportare la maschera negli Appunti
&#x200B;* [Finestra vista] Consente di passare dalla modalità Prospettiva alla modalità ortografica
&#x200B;* [Riquadro di visualizzazione] Consente di controllare il campo di visualizzazione in modalità Prospettiva
&#x200B;* [Finestra vista] Consente di impostare la Profondità della distanza del campo con CTRL+clic centrale
&#x200B;* [Finestra vista] Consente di trascinare e rilasciare le mappe dell&#39;ambiente nel vista 3D.
&#x200B;* [Finestra di visualizzazione] Feedback migliorato quando il motore esegue calcoli complessi
&#x200B;* [Esporta] Consente di esportare i parametri di shader in un file json
&#x200B;* [UI] Aggiorna l&#39;interfaccia con nuove icone, colori e layout
&#x200B;* [UI] Aggiungi i nomi delle risorse ai mini scaffali
&#x200B;* [UI] Comprimi &quot;Mappatura canali&quot; per impostazione predefinita
&#x200B;* [Shader] Scegliere un colore personalizzato per i parametri della texture di shader
&#x200B;* [Shelf] Chiedi dove importare i file quando trascini le risorse
&#x200B;* [Shelf] Nuova sfera di anteprima per Materiali avanzati e generatori
&#x200B;* [Shelf] Aggiungi shader Lucentezza Specular
&#x200B;* [Shelf] Nuove forme superficie rigida
&#x200B;* [Ripiano] Nuovi Alpha, texture e forme
&#x200B;* [Shelf] Nuove texture incarnato
&#x200B;* [Shelf] Nuovi materiali basati su scansione e materiali intelligenti
&#x200B;* [Shelf] Nuovi materiali avanzati e supporto per specifiche/lucidità dei vecchi
&#x200B;* [Shelf] Nuovi filtri di finitura per simulazione di superficie metallica
&#x200B;* [Shelf] Nuovo potente generatore di maschere &quot;Editor maschera&quot;
&#x200B;* [Scaffale] Vecchi materiali rilavorati e puliti
&#x200B;* Nuovo progetto di esempio &quot;Vela&quot;

**Corretto:**

&#x200B;* [Impostazioni] La rotazione della videocamera e la velocità dello zoom vengono sostituite dal progetto
&#x200B;* [Finestra vista] Un problema di precisione nella texture normale predefinita causa riflessi errati
&#x200B;* [Finestra vista] La vignettatura è attivata per impostazione predefinita
&#x200B;* [Viewport] Gli artefatti vengono visualizzati ai bordi della mappa dell&#39;ambiente (GPU Nvidia)
&#x200B;* [Viewport] La miniatura in modalità di proiezione/stencil è molto lunga da caricare
&#x200B;* [Baker] Memorizza le texture eseguite i baking in un numero intero a 16 bit anziché a 32 bit
&#x200B;* [Livello] Le sostanze obsolete vengono visualizzate in modo errato nella pila
&#x200B;* Il colore e la profondità di bit predefiniti per alcuni canali non sono corretti (ad esempio: Specular, Lucentezza)
&#x200B;* È stato corretto il comportamento della gomma per disabilitare la fusione in modalità passthrough.

**Problemi noti:**

&#x200B;* Simmetria non funziona con lo strumento Sfumino e Clona /Clone
&#x200B;* Esportazione ArtStation mancante

## Versione 1

### 1.7.3

*(Rilasciato il 1° marzo 2016)*

**Aggiunto:**

&#x200B;* [Esporta] Aggiungi un’opzione per disabilitare il riempimento
&#x200B;* [Shelf] Supporta la gerarchia di scaffali secondari all&#39;interno di una cartella di scaffali

**Corretto:**

&#x200B;* Arresto anomalo di salvataggio su un file di sola lettura precedente
&#x200B;* Arresto anomalo all’apertura di un secondo progetto
&#x200B;* Arresto anomalo durante il caricamento di alcune miniature (scaffale, livelli o descrizioni comandi)
&#x200B;* La disattivazione di &quot;Mantieni posizioni dei tratti sulla trama&quot; non funziona
&#x200B;* [Export] L’ingrandimento delle bitmap viene eseguito con il filtro più vicino
&#x200B;* [Shelf] L&#39;individuazione delle risorse è molto lenta
&#x200B;* [Shelf] I filtri Sfocatura non sono compatibili con 16 bit
&#x200B;* [Strumento] La Simmetria non funziona se caricate un vecchio strumento predefinito
&#x200B;* La finestra di dialogo Colore per il canale Specular non esegue una conversione dello spazio colore

### 1.7.2

*(Rilasciato il 13 gennaio 2016)*

**Aggiunto:**

&#x200B;* [Livelli] Consente di specificare la lavorazione predefinita per i livelli di riempimento

**Corretto:**

&#x200B;* [Esporta] L&#39;esportazione Sketchfab non funziona più
&#x200B;* [Livello] Il filtro bilineare viene applicato anche a Riempimento senza alcuna trasformazione
&#x200B;* [Tool] Prestazioni mediocri con l’utilizzo di substance con input di immagine in modalità di proiezione
&#x200B;* [Tool] Il selettore del materiale è interrotto

### 1.7.1

*(Rilasciato il 18 dicembre 2015)*

**Corretto:**

&#x200B;* Arresto anomalo quando si cambia set di texture
&#x200B;* Prestazioni rallentate durante la pittura

### 1.7.0

*(Rilasciato il 17 dicembre 2015)*

**Aggiunto:**

&#x200B;* [Prestazioni] Calcola contemporaneamente il contenuto dei livelli e le relative miniature
&#x200B;* [Export] Salva il percorso di esportazione come relativo quando è accanto al progetto
&#x200B;* [Layers] Aggiunto un nuovo metodo di fusione : Sottrai e Aggiungi/Sottometti
&#x200B;* [Layers] Nuovo filtro HQ bilineare per i livelli di riempimento
&#x200B;* [Shader] Impostate uno shader predefinito per la generazione delle miniature nelle preferenze.
&#x200B;* [Shader] Consente di specificare uno shader per set di texture
&#x200B;* [Shader] Consente di campionare texture dallo scaffale
&#x200B;* [Strumento] Nuovo comportamento del pennello &quot;a capo&quot; per la pittura
&#x200B;* [Tool] Miglioramento del filtro e riduzione dell’aliasing durante la pittura
&#x200B;* [Tool] Qualità di pittura dei sottopixel migliorata
&#x200B;* [Tool] Rimosso il display &quot;basic&quot; per le impostazioni del pennello e migliorata l’icona di apertura/chiusura del fotogramma
&#x200B;* [Menu] Aggiungere icone degli effetti nel menu di scelta rapida
&#x200B;* Creazione di modelli da progetti
&#x200B;* [Shelf] Nuovi modelli : PBR, Dota 2
&#x200B;* [Shelf] Nuovo predefinito di esportazione : Dota 2
&#x200B;* [Shelf] Nuovi shader : Dota 2, pittura auto PBR, PBR rivestito, Velluto PBR
&#x200B;* [Scaffale] Nuovo materiale: ruggine e usura in acciaio, illuminazione stilizzata
&#x200B;* [Shelf] Nuovi filtri : Sfocatura direzione, illuminazione stilizzata
&#x200B;* [Shelf] Nuovo pennello : predefinito morbido e predefinito rigido con un nuovo alfa per un migliore controllo della durezza
&#x200B;* [Shelf] Nuovi generatori : 3D Distanza e Luce
&#x200B;* [Ripiano] Pennelli aggiornati con proiezione a capo e taglio del carattere di sfondo (attivato per impostazione predefinita)
&#x200B;* [Shelf] Rumore bianco aggiornato con la versione del processore pixel per un calcolo più veloce

**Corretto:**

&#x200B;* [Schermata introduttiva] Tutorials collegamento invia a vecchi video
&#x200B;* [Canali] Dicendo &quot;no&quot; per riempire la creazione del livello con AO si crea ancora il livello
&#x200B;* [Canali] I nomi dei canali UserX non si propagano nell’interfaccia
&#x200B;* [Finestra della vista] La voce Maschera è vuota nell’elenco dei canali singoli
&#x200B;* [Condividi] L’esportazione di un file alfa per la condivisione da SP crea un file .image illeggibile
&#x200B;* [Licenza] Correggere l&#39;attivazione per i nomi utente con caratteri non ASCII
&#x200B;* [Shader] La finestra di dialogo dei parametri colore scompare quando si sceglie un colore
&#x200B;* [Shelf] Le miniature non vengono scaricate dalla memoria se non utilizzate
&#x200B;* [Ripiano] Filtro sfumatura fissa
&#x200B;* [Strumento] La simmetria non funziona con stencil/proiezione
&#x200B;* [Strumento] Nome errato durante la creazione di un nuovo pennello predefinito
&#x200B;* L’impostazione Mantieni tratto rimane disattivata anche durante la reimportazione di una trama
&#x200B;* Reimpostazione del driver (TDR) quando si calcolano particelle di grandi dimensioni.

### 1.6.1

*(Rilasciato il 9 novembre 2015)*

**Corretto:**

&#x200B;* Arresto anomalo all’apertura di un progetto se è visibile la vista 2D
&#x200B;* Arresto anomalo durante la creazione di un nuovo predefinito di esportazione se lo scaffale corrente non esiste
&#x200B;* [Tool] L’icona del selettore di materiali può rimanere visualizzata
&#x200B;* [Strumento] Il selettore materiale nasconde il cursore del mouse quando si disegna allo stesso tempo
&#x200B;* [Shelf] I metadati vengono scritti sul disco dopo ogni uscita

### 1.6.0

*(Rilasciato il 29 ottobre 2015)*

**Aggiunto:**

&#x200B;* Supporto ufficiale per Windows 10
&#x200B;* [Substance] Comprimi gruppi di parametri della sostanza per impostazione predefinita
&#x200B;* [Substance] Aggiungere un nuovo framework (migliorare le prestazioni del processore pixel)
&#x200B;* [Finestra vista] Consente di disattivare la visualizzazione del piano di simmetria in modalità simmetria.
&#x200B;* [Finestra di visualizzazione] Migliorare il rendering e le prestazioni delle ombre
&#x200B;* [Finestra vista] Mette in pausa il calcolo dell’ombra durante il disegno
&#x200B;* [Finestra di visualizzazione] Miglioramento delle prestazioni di rendering dei wireframi
&#x200B;* [Engine] Miglioramento della gestione della memoria Vram per ridurre l&#39;ingombro
&#x200B;* [Engine] Migliora l&#39;aggiornamento delle texture sulle GPU AMD per prestazioni migliori
&#x200B;* [Engine] Disattiva l’impostazione di ottimizzazione concatenata sulle GPU NVIDIA per prestazioni migliori
&#x200B;* [Effect] Aggiungi un tag per richiedere l&#39;input di un&#39;immagine &quot;imbottita&quot;
&#x200B;* [Livello] Aumenta la precisione dell’Offset UV/scala nel riempimento
&#x200B;* [Layer] Rendi il cursore della scala esponenziale nel riempimento
&#x200B;* [Livello] Consente di trascinare e rilasciare i materiali direttamente nella pila di livelli.
&#x200B;* [Livello] Consente di trascinare i filtri direttamente nella pila di livelli
&#x200B;* [Livello] Regola il colore del pennello maschera sul colore maschera appena creato
&#x200B;* [Shader] Esporre più parole chiave
&#x200B;* [Shader] Funzione di esposizione gamma/tonemapping per consentire funzioni personalizzate
&#x200B;* [Bakers] Modificare le impostazioni predefinite di Position Baker per l&#39;utilizzo triplo
&#x200B;* [Tool] Rinomina &quot;Geometry Decal&quot; in &quot;Polygon Fill&quot;
&#x200B;* [Shelf] Aggiornare i generatori per supportare TriPlanar : MG Metal edge usura, MG Mask builder, MG Fibre di vetro, MG Dirt
&#x200B;* [Shelf] Aggiorna i materiali con le nuove impostazioni e i materiali non utilizzati rimossi
&#x200B;* [Scaffale] 22 Nuovi materiali avanzati (Plastica, Ferro, Tessuto, Acciaio e altro)
&#x200B;* [Shelf] Aggiorna i filtri Nitidezza, Sfocatura e Altera con l&#39;input dell&#39;immagine imbottita per evitare giunture
&#x200B;* [Shelf] Migliorare le impostazioni di Alterazione per un utilizzo più semplice
&#x200B;* [Shelf] 2 Nuovi rumori procedurali : disturbo Perlin 3D e disturbo Worley 3D

**Corretto:**

&#x200B;* [Engine] Il rilevamento della quantità di Vram per la GPU dedicata non è corretto su Mac
&#x200B;* [Engine] Le Texture diventano una versione più scura nella finestra della vista
&#x200B;* [Motore] Prestazioni insoddisfacenti quando si disegna al di sotto di più livelli
&#x200B;* [Engine] I livelli calcolati all’apertura del progetto sono diversi dalla versione memorizzata nella cache
&#x200B;* [Substance] Risultati errati in 4K su Mac
&#x200B;* [Substance] I parametri sono nell&#39;ordine errato
&#x200B;* [Shader] Gli shader Toon e Pixelated sono completamente neri
&#x200B;* [Shader] I parametri scompaiono dopo aver modificato env-map
&#x200B;* [Shelf] Arresto anomalo durante l&#39;inserimento di file png nella cartella generator
&#x200B;* [Shelf] Le miniature vengono generate con una bassa rugosità
&#x200B;* [Strumento] Arresto anomalo di utilizzo di una bitmap nel pennello alfa su Windows
&#x200B;* [Esporta] Un predefinito di esportazione mappa aggiuntivo ora esporta una mappa RGB per Posizione

### 1.5.7

*(Rilasciato il 24 settembre 2015)*

**Corretto:**

&#x200B;* Il report di Arresto anomalo non funziona più

### 1.5.6

*(Rilasciato il 21 settembre 2015)*

**Aggiunto:**

&#x200B;* [Shelf] Migliorare la qualità di rendering delle miniature (utilizzare texture da 1K)

**Corretto:**

&#x200B;* [Condividi] Impossibile firmare con un altro account
&#x200B;* [Shelf] Le miniature sono troppo pesanti sul disco
&#x200B;* Il caricamento dei Materiali avanzati [Shelf] è molto lento
&#x200B;* [Windows] Correggere l&#39;installazione del servizio licenze
&#x200B;* [Canali] Per impostazione predefinita, la mappa dei Trasmissivi viene creata come G8

### 1.5.5

*(Rilasciato il 15 settembre 2015)*

**Aggiunto:**

&#x200B;* [Shelf] Esportare risorse in Substance share
&#x200B;* [Shelf] Aggiungi nuova anteprima sfera per Materiali
&#x200B;* [Shelf] Utilizza la mappa di invidiabilità &quot;Glazed patio&quot; per generare le miniature
&#x200B;* [Shelf] Aumenta la risoluzione delle dimensioni delle miniature a 512x512 pixel
&#x200B;* [vista 3D] Esposizione del valore di rotazione dell&#39;ambiente
&#x200B;* [Windows] Firma l’applicazione

**Corretto:**

&#x200B;* [Baker] Risultati errati quando si eseguono i baking le mappe allo stesso tempo
&#x200B;* [vista 3D] La mappa env viene visualizzata quando non è aperto alcun progetto
&#x200B;* [Livelli] I Generatori di maschere non funzionano sul contenuto del livello
&#x200B;* [Livelli] Puoi applicare la pittura ai livelli nascosti
&#x200B;* [Shelf] Il rumore di Dirt\_5 e di Dirt\_6 sono identici
&#x200B;* [Ripiano] Alcuni generatori di maschere sono pixelati o di bassa qualità
&#x200B;* [Tool] Rotazione del gizmo errata su alcuni angoli.
&#x200B;* [Tool] Troppi canali causano il ritaglio dei pulsanti dei canali
&#x200B;* [Strumento] Inverti scelta rapida da tastiera maschera per Maschera veloce non funziona
&#x200B;* [Esporta] Sketchfab: il pulsante Annulla non è stato considerato correttamente
&#x200B;* [Licenza] Attivazione non riuscita quando non è possibile copiare la licenza
&#x200B;* Il limitatore di cadenza fotogrammi non funziona più nell&#39;interfaccia utente

### 1.5.0

*(Rilasciato il 20 agosto 2015)*

<b>Aggiunto:</b>

&#x200B;* [Shader] Aggiungi il numero di riga in Shader per la compilazione dei messaggi di errore
&#x200B;* [Shelf] Migliorare la qualità delle anteprime delle miniature
&#x200B;* [Shelf] Generazione automatica delle miniature per i Materiali avanzati
&#x200B;* scelta rapida da tastiera [Tool] per controllare la regolazione della durezza nella sostanza
&#x200B;* [Strumento] Usa widget in scala di grigio per decalcomanie geometriche quando si sovrappone una maschera
&#x200B;* [Strumento] Scelta rapida da tastiera per invertire il colore della pittura mentre si dipinge su una mappa in scala di grigio
&#x200B;* [Finestra vista] Consente di visualizzare il wireframe e di modificarne il colore
&#x200B;* [Riquadro di visualizzazione] Sfocatura dello sfondo dell’ambiente
&#x200B;* [Controls] Aggiungi rotazione alle scelte rapide del mouse per il pennello
&#x200B;* [Esporta] Esporta in Sketchfab
&#x200B;* [Esporta] Creare predefiniti di esportazione per i moduli di rendering
&#x200B;* [Esporta] Aggiungi riflessione mappa convertita, F0 e 1/IOR
&#x200B;* [UI] Aggiungi schermata introduttiva
&#x200B;* [UI] Aggiorna layout predefinito
&#x200B;* [UI] Aggiungi descrizioni comandi mancanti e rinomina una voce di menu
&#x200B;* [Livelli] Esporta la maschera attualmente selezionata come bitmap
&#x200B;* [Layers] Aggiungi l’azione &quot;inverti maschera&quot; nel menu di scelta rapida

<b>Corretto:</b>

&#x200B;* [Progetto] Se i perni di mesh sono diversi nell&#39;FBX, le mesh vengono esplose durante l&#39;importazione
&#x200B;* [Substance] Le Substance utilizzate negli strumenti di proiezione sono bloccate in 256\*256
&#x200B;* [Livelli] Arresto anomalo quando si utilizza Cancella maschera
&#x200B;* [Esportazione] Conversione del gamma non corretta su texture molto scure
&#x200B;* [Esporta] La mappa di posizione può essere utilizzata solo nei predefiniti di esportazione come mappa in scala di grigio
&#x200B;* [Strumento] Il colore iniziale della decalcomania Geometria è nero se utilizzato su una maschera
&#x200B;* [Strumento] La scelta rapida da tastiera di rotazione non funziona se non c&#39;è durezza nell&#39;alfa

### 1.4.2

*(Rilasciato il 15 luglio 2015)*

**Corretto:**

&#x200B;* [Strumento] Arresto anomalo quando si utilizza la decalcomania geometrica con maschera veloce
&#x200B;* L’aggiornamento del progetto da 1.4.0 a 1.4.1 utilizza tutta la memoria del computer
&#x200B;* Importazione del vecchio formato di progetto non corretta
&#x200B;* Gli scaffali personalizzati analizzano l&#39;intera gerarchia e duplicano le risorse ovunque

### 1.4.1

*(Rilasciato il 23 giugno 2015)*

**Aggiunto:**

&#x200B;* [Finestra vista] Consente di ancorare i pannelli uno accanto all’altro
&#x200B;* [Effetto] Aggiungete uno sfondo e un righello per l’effetto livello
&#x200B;* [Effetto] Aggiungi un effetto Pittura che consenta di lavorare su altri effetti

**Corretto:**

&#x200B;* [Shelf] La generazione delle miniature è interrotta se non è aperto alcun progetto
&#x200B;* [Shelf] Impossibile generare l&#39;anteprima del materiale predefinito
&#x200B;* [Shelf] Le anteprime dei materiali vengono generate su una trama con normali invertite
&#x200B;* [Shelf] Le miniature vengono sempre ricalcolate a causa di una funzione hash errata
&#x200B;* [Ripiano] Facendo clic su un materiale di una sostanza non si collegano mappe aggiuntive
&#x200B;* [Strumento] Valore non corretto campionato con il selettore Materiale
&#x200B;* [Strumento] Selettore colore seleziona il colore del cursore della finestra della vista
&#x200B;* [vista 2D] Velocità fotogrammi/prestazioni molto basse
&#x200B;* [Esporta] Arresto anomalo quando si apre la finestra di esportazione con predefiniti di esportazione troppo recenti.
&#x200B;* [Esporta] Il canale di Height su Mappa normale viene convertito nello spazio errato
&#x200B;* [Mac] BaseColor dagli effetti substance viene visualizzato come Lineare
&#x200B;* [Mac] Il widget Linee rette è stato disegnato in modo errato su Retina
&#x200B;* Le linee rette possono rimanere attivate anche con le scelte rapide da tastiera rilasciate.
&#x200B;* Le linee rette del guizmo scompaiono dopo aver ruotato la mappa dell&#39;ambiente
&#x200B;* Gli output di Occlusione ambientale da sostanze non vengono collegati automaticamente al canale AO
&#x200B;* Risolvere il problema di copia della licenza su Windows con carattere speciale nel nome utente

### 1.4.0

*(Rilasciato il 10 giugno 2015)*

**Aggiunto:**

&#x200B;* [Esporta] Aggiungi mappe aggiuntive nell&#39;elenco delle mappe di input disponibili
&#x200B;* [Shelf] Utilizza i materiali sbsar come materiali predefiniti
&#x200B;* [Shelf] Consenti l&#39;utilizzo di percorsi libreria personalizzati
&#x200B;* [Shelf] Modificare le dimensioni minime
&#x200B;* [Shelf] Nuovo contenuto : 20 nuovi materiali avanzati
&#x200B;* [Scaffale] Nuovo contenuto: nuova sostanza procedurale (tessitura, trama)
&#x200B;* [Shelf] Filtro Sfocatura aggiornato
&#x200B;* Disegnare linee rette utilizzando un tasto modificatore
&#x200B;* Aggiungere il canale di Occlusione ambientale e rielaborare il comportamento AO/Normale in Pila livelli
&#x200B;* Lettura del colore predefinito da Input immagine definito in Substance dati utente
&#x200B;* Consente di esportare il registro dal menu Aiuto

**Corretto:**

&#x200B;* [Baker]&#x200B;[Mac] Arresto anomalo con normale da baker trama
&#x200B;* [Baker] Arresto anomalo in cui non sono presenti UV nel file della gabbia
&#x200B;* [Baker] La corrispondenza per nomi non funziona con l’OBJ esportato da zBrush
&#x200B;* [Baker] Eseguire i baking con una gabbia sovrascrive il eseguo i baking se si utilizzano più set di texture e UV sovrapposti
&#x200B;* [Baker] I file OBJ specifici generano texture nere
&#x200B;* [Shelf] Impossibile leggere le risorse se impostato su sola lettura
&#x200B;* [Shelf] I file delle risorse vengono scritti in Painter se sono stati utilizzati nel progetto.
&#x200B;* [Ripiano] Il ricaricamento delle sostanze aggiorna anche lo strato
&#x200B;* [Esportazione] Tiff esporta immagini a 32 bit che non possono essere lette correttamente da Photoshop o motori grafici
&#x200B;* [Esporta] Il predefinito dei canali predefiniti esporta sempre come RGB
&#x200B;* [Material] Il canale della Diffusa sostituisce la mappatura BaseColor con le sostanze
&#x200B;* [vista 3D] Illuminazione errata delle Diffuse con mappe ambientali specifiche
&#x200B;* [Strumento] Impossibile ruotare un pennello in un angolo specifico
&#x200B;* Il riquadro di visualizzazione diventa attivo quando si passa il cursore del mouse mentre si digita in un campo di testo
&#x200B;* Arresto anomalo con predefiniti troppo recenti per la versione corrente dello scaffale
&#x200B;* Arresto anomalo dopo la sostituzione della trama
&#x200B;* Arresto anomalo quando si ricarica una sostanza con un diverso numero di input
&#x200B;* Trame FBX da Cinema4D importate con nomi di materiale errati

### 1.3.5

*(Rilasciato il 29 maggio 2015)*

**Aggiunto:**

&#x200B;* [Licenza] Problema di attivazione quando è presente un file di licenza esistente
&#x200B;* [Mac] Arresto anomalo durante il caricamento di file FBX specifici
&#x200B;* [Mac]&#x200B;[vista 3D] Riflesso errato per la GPU integrata
&#x200B;* [vista 3D] Il font della Maschera veloce è interrotto
&#x200B;* [vista 3D] Il selettore di materiali rende la finestra della vista completamente nera
&#x200B;* Arresto anomalo dopo l’apertura dei progetti creati nella versione 1.3.3
&#x200B;* L&#39;anteprima del materiale è vuota quando si utilizzano ombreggiature con canale alfa
&#x200B;* Il disegno smette di funzionare su trame specifiche
&#x200B;* Le prestazioni diminuiscono notevolmente con le maglie specifiche dell&#39;OBJ
&#x200B;* I canali utente non sono mappati quando si utilizzano gli effetti
&#x200B;* Le cartelle temporanee non vengono pulite all&#39;avvio

**Corretto:**

&#x200B;* Miglioramenti dei tempi di calcolo nel progetto estremamente lungo da caricare
&#x200B;* Modificare la finestra &quot;Risoluzione dei problemi GPU&quot; per renderla più comprensibile
&#x200B;* [Livelli] Salva lo stato del blocco delle proporzioni per i livelli di riempimento e attivalo per impostazione predefinita
&#x200B;* [Panettieri] La corrispondenza per nome ora utilizza il suffisso come separatore

### 1.3.4

*(Rilasciato il 27 aprile 2015)*

**Aggiunto:**

&#x200B;* [Mac] Arresto anomalo con Mac OS X Yosemite (10.10)
&#x200B;* [Mac] Impossibile uscire dalla modalità a schermo intero
&#x200B;* [Panettieri] L’opzione Baking Match by name non funziona
&#x200B;* [Bakers] Lo spazio tangente Mikk utilizzato in SP non funziona con UE4
&#x200B;* [Panettieri] Il fornaio di ID non può cuocere i colori ID del materiale
&#x200B;* [Vista 2D] Il Wireframe non viene visualizzato quando si utilizza lo strumento decalcomania Geometria
&#x200B;* [Strumento] Il canale alfa del pennello viene visualizzato come controllo anziché come trasparenza con i materiali
&#x200B;* [Tool] Arresto anomalo con decalcomania geometrica
&#x200B;* [Livelli] Lo slot del materiale è compresso per impostazione predefinita sul livello di riempimento
&#x200B;* [Esporta] Arresto anomalo durante l’esportazione con dimensioni superiori alla risoluzione impostata per la texture
&#x200B;* Canale Specular non riconosciuto nei filtri.
&#x200B;* Clean + save non toglie correttamente le risorse dall&#39;archivio delle specie
&#x200B;* Non memorizzare la trasformazione low-poly nel file assbin high-poly
&#x200B;* Il file FBX viene importato con troppi set di texture

**Corretto:**

&#x200B;* Effetti: Blocco livelli dovrebbe essere attivato per impostazione predefinita per simulare i livelli &quot;classici&quot;
&#x200B;* Livelli: modificare il livello minimo e massimo di fresatura nell’azione Riempi
&#x200B;* Livelli: salvare e ripristinare lo stato della pila
&#x200B;* Baker: il Baker AO tiene conto della mappa normale se non viene specificato HP
&#x200B;* Baker: sono state aggiunte descrizioni e informazioni aggiuntive nella finestra di esegue i baking
&#x200B;* Creare un file di backup durante il salvataggio di un progetto

### 1.3.3

*(Rilasciato: 01 aprile 2015)*

**Aggiunto:**

&#x200B;* Aggiungere la versione del software e il nome del progetto nella barra del titolo
&#x200B;* Rimuovi informazioni riservate dai nomi dei set di texture e dei Materiali avanzati
&#x200B;* Aggiornamento del motore di Substance alla versione 5
&#x200B;* [Shelf] Aggiungi nuove mappe dell&#39;ambiente: spiaggia di Corsica, studio 05, studio di Tornoco e altro
&#x200B;* [Shelf] Aggiorna MG Mask Builder con i nuovi parametri
&#x200B;* [Shelf] Aggiorna e calibra le mappe dell&#39;ambiente precedente

**Corretto:**

&#x200B;* Arresto anomalo all’apertura della finestra di esportazione
&#x200B;* Impossibile trascinare il widget dell&#39;interfaccia utente quando non è ancorato
&#x200B;* &quot;Ricerca aggiornamenti&quot; non funziona
&#x200B;* [Livelli] Non selezionare la maschera quando si fa clic su di essa tenendo premuto ALT
&#x200B;* [Tool] La planari tripla non funziona con il canale Normale
&#x200B;* [vista 3D] L&#39;illuminazione della Diffusa da env map non è corretta
&#x200B;* [vista 3D] Il calcolo dell&#39;esposizione è diverso da Designer
&#x200B;* [vista 3D] Le ombre non devono essere visibili su una superficie metallica al 100%
&#x200B;* [vista 3D] Trama con UV specchiati tangente/binomiale capovolto
&#x200B;* [vista 3D] Le ombre producono risultati errati su determinate trame
&#x200B;* [Baker] Rimuovi la cartella &quot;.alg\_meta&quot; creata dai file assbin
&#x200B;* [Baker] Arresto anomalo quando si esegue i baking se Painter ricalcola contemporaneamente un TextureSet
&#x200B;* [Mac] Problema di interfaccia utente del riquadro bianco all’avvio dell’applicazione

### 1.3.2

*(Rilasciato il 6 marzo 2015)*

**Corretto:**

&#x200B;* [vista 3D] Impossibile ricaricare una mappa env salvata con il progetto

### 1.3.1

*(Rilasciato il 5 marzo 2015)*

**Aggiunto:**

&#x200B;* [Baker] Aggiungi una versione memorizzata nella cache di trame ad alto polio per accelerare il calcolo
&#x200B;* [Baker] Aggiungi un’icona di avviso se non è caricata alcuna trama high-poly
&#x200B;* [Baker] Se non viene caricata alcuna trama ad alto poli, utilizza invece la trama del progetto

**Corretto:**

&#x200B;* [Baker] Premendo &quot;Invio&quot; quando si modifica il valore di un cursore si chiude la finestra
&#x200B;* [Baker] Anche l’attivazione/disattivazione di un baker attiva il pulsante
&#x200B;* [Baker] Impossibile eseguire i baking se si utilizza il pulsante &quot;all/none&quot;
&#x200B;* [Baker] L&#39;ordinamento dei pulsanti di baker non è corretto
&#x200B;* [Baker] La casella di controllo viene ignorata e tutti i baker vengono sempre elaborati
&#x200B;* [Baker] Stato barra di avanzamento corretto

### 1.3.0

*(Rilasciato il 4 marzo 2015)*

**Aggiunto:**

&#x200B;* [Baker]&#x200B;[vista 3D] Usa calcolo spazio tangente Mikkt se non vengono trovate tangenti/binormali
&#x200B;* [Baker] Aggiunti nuovi baker: Normale, ID, Occlusione, Curvatura, Thickness, Posizione
&#x200B;* [Effetti] La serie di effetti è ora invertita e visualizzata dall’alto verso il basso (come i livelli)
&#x200B;* [Effects] Aggiungere nuove icone alla serie di effetti
&#x200B;* [Effetti] Aggiungi metodo di fusione tra le azioni di riempimento nella pila degli effetti
&#x200B;* [Effetti] Rinominare gli effetti (effetto sostanza = filtro, ecc.)
&#x200B;* Aggiungere un file &quot;lock&quot; durante il processo di salvataggio
&#x200B;* [Effects] Aggiungi azione Riempimento nella serie di effetti
&#x200B;* Aggiunta nuova risorsa: materiali avanzati
&#x200B;* [Livelli] Consente di riordinare gli effetti di livello
&#x200B;* [Tool] Aggiungi proiezione triplanare
&#x200B;* [Vista 3D] Aggiungere il supporto per le ombre
&#x200B;* [Vista 3D] Possibilità di impostare gli stati OpenGL richiesti in shader personalizzati
&#x200B;* [Vista 3D] Supporto per alfa tramite nuovi shader
&#x200B;* [Vista 3D] Gli ombreggiatori sono ora provvisti di versione e completamente salvati in un progetto
&#x200B;* [Vista 3D] Avvisa l&#39;utente se lo shader non viene più compilato

**Corretto:**

&#x200B;* [Livelli] correggi l’inserimento in una cartella compressa
&#x200B;* [Shelf] Correggere il filtraggio dei contenuti nei mini-shelf
&#x200B;* [Shelf] Rinominare le categorie e riorganizzare le schede

### 1.2.1

*(Rilasciato il 12 febbraio 2015)*

**Aggiunto:**

&#x200B;* I file \*.spp possono ora essere aperti con un doppio clic in Esplora risorse
&#x200B;* [Esporta] Nuovo tag &quot;$project&quot; per i predefiniti di esportazione
&#x200B;* [Esporta] Aggiungete un elenco di mappe (con nomenclatura) sotto ogni set di texture
&#x200B;* [Esporta] Aggiungi un pulsante Tutto/Nessuno per selezionare i set di texture
&#x200B;* [Esporta] Le mappe vuote vengono eliminate durante l’esportazione

**Corretto:**

&#x200B;* [Esporta] I predefiniti Unity5 hanno mappe invertite
&#x200B;* [Esportazione] L’aggiunta di una barra in avanti nel nome di un predefinito crea una cartella danneggiata
&#x200B;* [Esportazione] Il canale di Height esportato in formati a 32 bit viene bloccato in modo errato
&#x200B;* [Esporta] L’elenco dei set di texture non è ordinato come nel progetto
&#x200B;* [Tool] L’eliminazione dei volti sullo sfondo non funziona più
&#x200B;* Il comando Salva non funziona con i caratteri speciali nel tracciato

### 1.2.0

*(Rilasciato il 28 gennaio 2015)*

**Aggiunto:**

&#x200B;* Nuovo canale Normale per colorare i dati delle mappe normali e combinare i risultati
&#x200B;* [Export] Nuova finestra di esportazione con la possibilità di creare impacchettamenti personalizzati e impostare nomi personalizzati
&#x200B;* Il formato del file di progetto ora è un singolo file anziché delle cartelle
&#x200B;* [Esportazione] Supporto di diversi formati normali (DirectX, OpenGL)
&#x200B;* [Export] Crea un file &quot;lock&quot; temporaneo durante l’esportazione
&#x200B;* [Livelli] Per alternare una maschera è possibile utilizzare Maiusc+clic sinistro del mouse
&#x200B;* [Parametri] Esporre lo spazio colore nella parte inferiore dell’input di un’immagine
&#x200B;* [Shelf] L&#39;effetto &quot;MG Mask Builder&quot; ha ora nuove impostazioni
&#x200B;* [Vista 3D] La mappa dell&#39;Occlusione ambientale ora oscura il contributo diffuso, non lo specular

**Corretto:**

&#x200B;* L&#39;anteprima del materiale di proiezione/stencil non viene visualizzata correttamente nella finestra della vista
&#x200B;* [Vista 3D] Descrizione comando scelta rapida non visualizzata quando si utilizza la scelta rapida &quot;S&quot; (stencil)
&#x200B;* [Shelf] L&#39;effetto &quot;MatFx Skin Scale&quot; offre ora prestazioni migliori a bassa risoluzione
&#x200B;* [Esportazione] Le texture esportate vengono solo ingrandite quando si specifica un documento di dimensioni maggiori

### 1.1.2

*(Rilasciato il 15 gennaio 2015)*

**Aggiunto:**

&#x200B;* Aggiunte: nuove impostazioni Trasla, Ruota e Scala nel livello Riempimento
&#x200B;* Filtro ottimizzato per pennelli e livelli di riempimento
&#x200B;* La versione di prova è ora completamente disponibile (può essere esportata) ma è limitata nel tempo.

**Corretto:**

&#x200B;* Impossibile importare mesh OBJ con precisione molto piccola
&#x200B;* Problema durante l&#39;attivazione di una licenza su Windows 7 e 8
&#x200B;* Arresto anomalo durante il salvataggio con nome di un progetto
&#x200B;* Arresto anomalo quando si elimina l’ultimo canale di un set di texture
&#x200B;* Arresto anomalo quando si elimina un livello in un contesto specifico

### 1.1.1

*(Rilasciato il 25 dicembre 2014)*

**Aggiunto:**

&#x200B;* [Livello] Seleziona il livello in alto quando si apre un progetto o si cambia set di texture
&#x200B;* Velocità di salvataggio e salvataggio con nome migliorate con il nuovo algoritmo di compressione
&#x200B;* Visualizzare un errore en durante l’apertura di un progetto troppo recente per Painter

**Corretto:**

&#x200B;* [Strumento] La decalcomania della geometria genera danni alla memoria
&#x200B;* [Pennello] Impossibile inserire manualmente valori mobili inferiori a 1 per la dimensione del pennello
&#x200B;* [Livello] La creazione di un effetto di selezione colore non lo aggiunge nella pila dei livelli
&#x200B;* [Livello] Quando si sposta il mouse sui livelli, Painter scorre rapidamente nella barra delle applicazioni
&#x200B;* [Livello] L’aggiunta di una bitmap come maschera può provocare un arresto anomalo
&#x200B;* La GUI per la modalità Solo con il canale del Height non è corretta
&#x200B;* &quot;Salva progetto&quot; può non riuscire e danneggiare un progetto
&#x200B;* Arresto anomalo quando si apre un progetto dopo averne caricato un altro con uno shader obsoleto

### 1.1.0

*(Rilasciato il 16 dicembre 2014)*

**Aggiunto:**

&#x200B;* [Effetto] Nuovo creatore maschera ID materiale
&#x200B;* Nuova linea bianca/nera punteggiata per il gizmo del pennello
&#x200B;* Nuovo parametro segui angolo
&#x200B;* Nuovo parametro di taglio backface
&#x200B;* Nuovo parametro per il mouse Lazy
&#x200B;* [Livelli] Supporto per più selezioni e gestione
&#x200B;* [Livelli] Copiare e incollare da un set di texture all’altro
&#x200B;* [Esporta] Formato PSD di Adobe Photoshop
&#x200B;* [Scaffale] Nuovo strumento: pelliccia, punti metallici e cerniera
&#x200B;* [Ripiano] Nuovo pennello : stampo, matita, linea affilata e punto
&#x200B;* [Ripiano] Nuovo alfa: disturbo gaussiano, linea affilata, stampo, penna, schizzo, punto, cerniera
&#x200B;* Le prestazioni di pittura sono migliorate aggiornando solo le parti delle texture necessarie

**Corretto:**

&#x200B;* [Scaffale] Impossibile caricare una sostanza con un grafico con etichette identiche
&#x200B;* [Livelli] Il metodo di fusione Attraversa non funziona con le maschere
&#x200B;* [Stencil] La scala è interrotta nel Vista 2D
&#x200B;* Problemi e arresto anomalo su Mac OS Yosemite

### 1.0.2

*(Rilasciato il 9 novembre 2014)*

**Aggiunto:**

&#x200B;* Prestazioni migliorate nell’anteprima del materiale con le sostanze
&#x200B;* Prestazioni migliorate con l’anteprima del tratto pennello durante l’aggiornamento del documento
&#x200B;* Prestazioni migliorate nella finestra della vista con una frequenza di aggiornamento inferiore per l’area non di lavoro
&#x200B;* [Effetti post] Interfaccia utente migliorata per la gestione delle impostazioni
&#x200B;* [Effetti post] Ripristina i valori predefiniti
&#x200B;* Substance effetti e operazioni sui livelli nel menu di scelta rapida
&#x200B;* Supporto per input/output premoltiplicato nelle sostanze

**Corretto:**

&#x200B;* [vista 3D] I parametri di shader personalizzati sono separati da uno spazio grande
&#x200B;* [Esporta] Conversione sRGB mancante per il predefinito Unity4
&#x200B;* Possibile Arresto anomalo durante il caricamento delle maglie fbx
&#x200B;* Arresto anomalo a volte durante il caricamento di semplici trame obj
&#x200B;* La barra di elaborazione rimane bloccata al 100% durante il caricamento
&#x200B;* Quando si ricarica una sostanza, la si inserisce in ogni categoria
&#x200B;* Switch DirectX/OpenGL interrotto

### 1.0.1

*(Rilasciato il 27 ottobre 2014)*

**Aggiunto:**

&#x200B;* [Tool] Utilizzo dei parametri del materiale migliorato
&#x200B;* Nuova scelta rapida da tastiera al sito Web di uservoice nel menu Aiuto
&#x200B;* Vari miglioramenti delle prestazioni del motore

**Corretto:**

&#x200B;* I valori dei parametri sono limitati a 2 decimali per Particelle
&#x200B;* La Substance caricata dalla cache non viene visualizzata nell’interfaccia utente come obsoleta
&#x200B;* Arresto anomalo durante il caricamento di una trama da un url di rete
&#x200B;* Painter è ora riconosciuto come firmato su Mac OS X

### 1.0.0

*(Rilasciato il 15 ottobre 2014)*

**Aggiunto:**

&#x200B;* Supporto Shader personalizzato
&#x200B;* Supporto della risoluzione 4k
&#x200B;* Progetti carattere di esempio
&#x200B;* Visualizza barra di avanzamento per lunghi tempi di calcolo
&#x200B;* [Esporta] Aggiungere una passata di dilatazione prima del postprocesso di diffusione
&#x200B;* Argomenti della riga di comando in SP per operazioni semplici
&#x200B;* Nuovi materiali ed effetti
&#x200B;* Anteprima strumento (anteprima del materiale in tempo reale separata e area di prova del tratto)
&#x200B;* Non creare un documento predefinito all&#39;avvio di Painter
&#x200B;* [Strumento] Aggiungete la possibilità di modificare manualmente un valore in scala di grigio
&#x200B;* Vari miglioramenti per gli stencil (Aggancia, Reimposta)
&#x200B;* Le particelle sono ora dei sottostrumenti degli strumenti Pennello artistico, Gomma e Proiezione
&#x200B;* [Vista 3D] Usa l’audio caricato al forno nel rendering della finestra della vista
&#x200B;* Dividere i controlli degli stencil tra la vista 2D e 3D
&#x200B;* Modifiche di piccole dimensioni del pollice nella libreria
&#x200B;* I campi di ricerca sono specifici di ogni finestra
&#x200B;* Interfaccia utente modificata

**Corretto:**

&#x200B;* [Substance] L&#39;opzione non funziona
&#x200B;* [Finestra di dialogo Colore] Sfumatura tonalità non aggiornata
&#x200B;* Impossibile aggiornare una trama se il nome del file è identico
&#x200B;* Lo strumento non è visibile nelle visualizzazioni quando è troppo piccolo
&#x200B;* Lo strumento decalcomania sullo schermo Retina non funziona correttamente
&#x200B;* [Substance] Int1 viene visualizzato come float1
&#x200B;* [Substance] input/output basecolor non riconosciuti
&#x200B;* Impossibile ricaricare i filtri di [Substance]
&#x200B;* [Tool] il widget della scala di grigi è sempre compresso

## Beta

### 0.12.1-beta

*(Rilasciato il 18 settembre 2014)*

**Aggiunto:**

&#x200B;* Predefinito di esportazione Unity 5

**Corretto:**

&#x200B;* PBR Shader, la qualità del rendering dovrebbe migliorare notevolmente
&#x200B;* La funzione di messa a fuoco è interrotta e le trame vengono ritagliate per impostazione predefinita

### 0.12.0-beta

*(Rilasciato il 17 settembre 2014)*

**Aggiunto:**

&#x200B;* Strumento Contagocce
&#x200B;* Opzione &quot;Mantieni posizione tratto&quot; aggiunta alla reimportazione della trama per quando il rettangolo di selezione cambia.
&#x200B;* Mappa normale trama predefinita Cymourai
&#x200B;* Migliorare l&#39;interfaccia della vista strumenti (i colori sono wip)
&#x200B;* Spostare il menu &quot;Aiuto->Impostazioni&quot; in &quot;Modifica->Impostazioni&quot;
&#x200B;* Salvare il percorso di esportazione nella finestra &quot;Esporta tutti i canali&quot;
&#x200B;* Interfaccia grafica dei nuovi livelli con visualizzazione dell&#39;istogramma
&#x200B;* Migliore gestione delle risorse (trascinamento, ricaricamento di risorse, eliminazione di elementi inutilizzati)
&#x200B;* Passare da &quot;diffusione&quot; a &quot;colore di base&quot;
&#x200B;* Cursori per la modifica delle regolazioni: consenti punti oltre a virgole
&#x200B;* Livello di riempimento: aumenta il valore massimo di Affiancamento
&#x200B;* Mappa ambiente predefinita

**Corretto:**

&#x200B;* Artefatti di riflesso su angoli estremi
&#x200B;* Esportazione specular/lucentezza interrotta
&#x200B;* I collegamenti nella finestra &quot;Informazioni su&quot; di Painter non funzionano
&#x200B;* Arresto anomalo con OSX Yosemite
&#x200B;* Le trame vengono salvate in triangolo
&#x200B;* La scelta rapida da tastiera a colori della finestra degli strumenti viene inviata all&#39;emettitore invece che alla scala di grigi
&#x200B;* Il selettore colore rimane aperto quando si passa da un livello all’altro
&#x200B;* Impossibile salvare il materiale da un livello di riempimento
&#x200B;* Abilita il ridimensionamento delle tre aree dello scaffale

### 0.11.0-beta

*(Rilasciato il 4 settembre 2014)*

**Aggiunto:**

&#x200B;* Aggiungere una barra di divisione tra le viste 3D e 2D
&#x200B;* Utilizzare uno sfondo sfumato nelle viste 2D/3D
&#x200B;* Interfaccia per l’istogramma Livelli
&#x200B;* Unisci scaffale e libreria
&#x200B;* Nessuna azione di salvataggio richiesta per la creazione o l’aggiornamento di un predefinito
&#x200B;* Importare le risorse nello scaffale tramite trascinamento della selezione

**Corretto:**

&#x200B;* Il nome dei pulsanti viene visualizzato nella barra degli strumenti principale

### 0.10.2-beta

*(Rilasciato il 28 agosto 2014)*

**Corretto:**

&#x200B;* L’esportazione di tutti i canali genera risultati errati

### 0.10.1-beta

*(Rilasciato il 26 agosto 2014)*

**Corretto:**

&#x200B;* Gli Shader danno un risultato nero con bassa ruvidezza
&#x200B;* Controllo GPU: gestisce le schede &quot;Quadro&quot;, rileva tutti i dispositivi e adatta di conseguenza il messaggio dell&#39;utente
&#x200B;* La maggior parte dei materiali Substance è limitata a 256 in Beta 9
&#x200B;* Il height viene bloccato quando viene esportato come bitmap
&#x200B;* L’anteprima del pennello è diversa dalla sovrapposizione di proiezione su Mac
&#x200B;* L&#39;utilizzo dello strumento Geometria per creare una maschera non viene visualizzato nelle finestre delle viste
&#x200B;* La maschera veloce è rotta
&#x200B;* Risolvere il problema di fusione sui vecchi mac pro

### 0.10.0-beta

*(Rilasciato il 7 agosto 2014)*

**Aggiunto:**

&#x200B;* Maschere stencil

**Corretto:**

&#x200B;* Supporto per schede Quadro
&#x200B;* Gli Shader danno un risultato nero con bassa ruvidezza
&#x200B;* I materiali Substance hanno un limite di 256
&#x200B;* L’esportazione mappa normale elimina il canale verde

### 0.9.0-beta

*(Rilasciato il 17 luglio 2014)*

**Aggiunto:**

&#x200B;* Post-elaborazione Yebis 2
&#x200B;* La Creazione guidata nuovo progetto consente di importare mappe di input (AO, Curvatura, ecc.)
&#x200B;* Collega automaticamente le mappe di input (AO, Curvatura, ecc.) Substance effetti
&#x200B;* Controllo in scala sui materiali applicato ai livelli di riempimento

### 0,8,2-beta

*(Rilasciato l&#39;11 luglio 2014)*

**Corretto:**

&#x200B;* Il cursore Tonalità ha come impostazione predefinita il bianco
&#x200B;* Progetto reimpostato se il nome del materiale contiene caratteri speciali
&#x200B;* La modifica del nome del materiale per un singolo oggetto materiale non deve invalidare il progetto.
&#x200B;* Gli UV vengono danneggiati dopo il salvataggio del progetto e la riapertura

### 0,8,1-beta

*(Rilasciato il 4 luglio 2014)*

**Corretto:**

&#x200B;* Arresti anomali multipli della GPU
&#x200B;* Arresto anomalo durante l’esportazione dei canali

### 0.8.0-beta

*(Rilasciato il 28 giugno 2014)*

**Aggiunto:**

&#x200B;* Multi-materiale: ora puoi dipingere su più materiali nello stesso documento
&#x200B;* Simmetria
&#x200B;* Tutti i metodi di fusione sono ora disponibili

**Corretto:**

&#x200B;* Arresti anomali multipli della GPU
&#x200B;* Progetto reimpostato se il nome del materiale contiene caratteri speciali
&#x200B;* Gli UV vengono incasinati dopo il salvataggio del progetto e riaperti con più UV

### 0.7.0-beta

*(Rilasciato il 18 giugno 2014)*

**Aggiunto:**

&#x200B;* Effetti di livello
&#x200B;* Nuovi materiali per stencil Substance
&#x200B;* Annulla la maschera
&#x200B;* Consenti di copiare/incollare livelli/maschere
&#x200B;* Consenti di duplicare il livello
&#x200B;* Strumento Modifica durante la modifica della maschera di livello
&#x200B;* La Substance è ora basata su GPU

**Corretto:**

&#x200B;* La pittura con mappe di height non dipinge valori negativi.
&#x200B;* La visualizzazione Selettore materiale non deve tenere conto della mappa normale campionata
&#x200B;* Determinismo delle particelle rotto
&#x200B;* Matrice stencil nella vista 2D
&#x200B;* Ngon nei file obj
&#x200B;* Vari arresti anomali

### 0.6.0-beta

*(Rilasciato il 4 giugno 2014)*

**Aggiunto:**

&#x200B;* Nuova opzione di esportazione per esportare una mappa di Specular da una composizione dei canali metallici e di rugosità

**Corretto:**

&#x200B;* Compatibilità con Windows Vista
&#x200B;* La mappa del height non colorerà i valori negativi

### 0.5.0-beta

*(Rilasciato il 7 maggio 2014)*

**Aggiunto:**

&#x200B;* Switch di visualizzazione 3D/2D
&#x200B;* Strumento di selezione del blocco UV
&#x200B;* Lo strumento cambia automaticamente quando si disegna su maschere.
&#x200B;* La risoluzione della Substance dipende dal

**Corretto:**

&#x200B;* Arresto anomalo all’avvio
&#x200B;* Arresto anomalo con trame ASCII
&#x200B;* Matrice stencil fissa nella vista 2D
&#x200B;* Arresto anomalo con gomma

### 0.4.0-beta

*(Rilasciato il 17 aprile 2014)*

**Aggiunto:**

&#x200B;* Visualizzazione 2D uniforme
&#x200B;* Maschere di livello bitmap
&#x200B;* Controllo dell&#39;esposizione ambientale
&#x200B;* Riempi livelli ora usa le finestre Strumenti per impostare le proprietà
&#x200B;* I materiali possono essere applicati ai livelli di riempimento
&#x200B;* Aggiunti altri stencil nella libreria degli stencil
&#x200B;* Predefiniti Particelle aggiornati per un calcolo più veloce
&#x200B;* Ottimizzazione dello shader PBR e miglioramento della qualità per impostazioni di qualità inferiore

**Corretto:**

&#x200B;* Le miniature dei livelli sono collegate al canale attualmente selezionato
&#x200B;* Molti arresti anomali

### 0.3.0-beta

*(Rilasciato il 4 aprile 2014)*

**Aggiunto:**

&#x200B;* Consenti valori negativi nel selettore colore per il disegno della mappa del height
&#x200B;* Mostra anteprima del materiale/colore selezionato
&#x200B;* Aggiungere scelte rapide per gli strumenti nella barra degli strumenti (1,2,3,4)
&#x200B;* Passare al formato Normale (OpenGL e DirectX) a livello globale su un progetto
&#x200B;* Creazione guidata nuovo progetto
&#x200B;* Il cursore di spaziatura non è più bloccato
&#x200B;* Stile cursori aggiornati
&#x200B;* Rendi il selettore colore non modale
&#x200B;* Selezionando un materiale nella libreria, impostate di conseguenza il tipo di utensile

**Corretto:**

&#x200B;* Fisso: l’importazione del tracciato trama non viene mantenuta
&#x200B;* Corretto: generazione texture errata
&#x200B;* Corretto: Arresto anomalo all’avvio

### 0.2.0-beta

*(Rilasciato il 17 marzo 2014)*

**Aggiunto:**

&#x200B;* Contagocce materiale (scelta rapida da tastiera P)
&#x200B;* Miniature nell’anteprima dello strumento 3D
&#x200B;* Sistema di licenza per versioni autonome
&#x200B;* Scelte rapide da tastiera [ e ] per Dimensione pennello
&#x200B;* Riempimento su mappe esportate
&#x200B;* Stile finestra strumenti aggiornato
&#x200B;* Stile cursori aggiornati
&#x200B;* Ambiente HDR predefinito aggiornato

**Corretto:**

&#x200B;* Stencil: modifica il valore di flusso nel vista 3D si arresta a 52
&#x200B;* Ciclo infinito nel motore quando l&#39;aggiunta di tasti di pressione 0 al tratto è fissa
&#x200B;* Strumento: la variazione angolo non restituisce valori superiori a +/- 90%
&#x200B;* Modifica della visualizzazione vista 3D quando è selezionata una maschera di livello
&#x200B;* Zoom invertito

### 0.1.0-beta

*(Rilasciato il 2 marzo 2014)*

**Aggiunto:**

&#x200B;* Nuova gestione libreria
&#x200B;* Nuovo contenuto Pennelli e particelle
&#x200B;* Anteprima pennello 3D
&#x200B;* Stile finestra strumenti aggiornato
&#x200B;* Stile cursori aggiornati
&#x200B;* Prestazioni cache aggiornate

**Corretto:**

&#x200B;* Controlli videocamera
&#x200B;* Rotazione pennello
