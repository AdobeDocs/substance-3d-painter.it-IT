---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/release-notes/old-versions/version-2017-3.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Painter versione 2017.3 per scoprire le nuove funzioni, i miglioramenti e le correzioni di bug.
helpx_creative_field: ""
helpx_description: Painter > Release notes > Old versions > Version 2017.3
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 2017.3
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '1588'
ht-degree: 0%

---


# Versione 2017.3

**Substance Painter 2017.3** si concentra sul nuovo predefinito di esportazione avanzato con il supporto di **Adobe Project Felix** e il formato aperto **glTF**. Questa nuova versione si concentra anche sull&#39;esperienza utente migliorando l&#39;interfaccia e aggiungendo un plug-in di salvataggio automatico.

Data di pubblicazione: *28 settembre 2017*

## Caratteristiche principali

### Predefinito di esportazione Adobe Standard Material

![](../../assets/adobe-dimension-meetmat.jpg)

Una delle nuove esportazioni incluse in questa versione è il supporto dell’Adobe Standard Material, da utilizzare con Adobe Dimension (in precedenza Project Felix dell’Adobe). Ti permettiamo di esportare la trama della scena e le sue texture per importarle nel Progetto Felix con un solo clic. Per accedervi, è sufficiente scegliere &quot;**Adobe Standard Material**&quot; nella finestra Esporta texture. Per ulteriori informazioni, vedere: [http://www.adobe.com/products/dimension.html](https://www.adobe.com/products/dimension.html)

Puoi anche consultare il post del blog su questo argomento: <https://www.allegorithmic.com/blog/new-dimension-substance-ecosystem>

### Predefinito di esportazione glTF 2.0

![](../../assets/gltf-export.jpg)

Abbiamo aggiunto anche il supporto per il formato di file **glTF**, con l&#39;esportazione della **trama della scena** e delle **texture PBR** (metalliche/rugosità). Per accedervi, è sufficiente scegliere &quot;**glTF PBR Metal Roughness**&quot; nella finestra Esporta texture. **glTF** è un formato di file open source diretto dal gruppo Khronos. Puoi visualizzare il file glTF da **Windows 10** o utilizzare semplicemente un visualizzatore WebGL come [**Babylon**](http://sandbox.babylonjs.com/).

Per ulteriori informazioni, vedere: <https://github.com/KhronosGroup/glTF>

### Plug-in di salvataggio automatico

![](../../assets/autosave-details.png)

In questa versione è stato incluso anche un nuovo plug-in che ha la possibilità di **creare backup** del progetto attualmente aperto. Crea un file di backup sul lato del progetto aperto.\
Per questo motivo, abbiamo aggiunto una voce &quot;**Salva come copia**&quot; nel menu File. È possibile arrestare il **salvataggio automatico** disattivando il plug-in stesso, le relative **impostazioni** sono accessibili **tramite il pannello di configurazione**. Una volta raggiunto il ritardo del tempo di avviso, viene visualizzata una **barra di avanzamento** sotto il pulsante nella barra degli strumenti principale, che consente di nasconderla per alcuni minuti, se necessario (utile se si desidera terminare qualcosa prima del backup).

Se viene creato un backup ma il progetto non è stato salvato (ovvero Untilted), il backup verrà archiviato nella cartella **Documents/Allegorithmic/Substance Painter/autosave**. In caso contrario, il backup sarà accanto al progetto stesso (a meno che il percorso non venga ignorato dal pannello di configurazione).

### Filtro sfumatura migliorato

![](../../assets/gradient-rust.jpg)

Il **filtro sfumatura** è stato completamente rinnovato. Agire in modo molto più simile al nodo **mappa sfumatura** disponibile nel **Substance Designer**. Ora supporta fino a **10 colori diversi**, con la possibilità di specificare **dove si trova il colore all&#39;interno** della sfumatura ****, aprendo molte nuove porte. Ciò consente di creare più&#x200B;**pattern di colore avanzati**, ma anche **mappe di altezza rimasterizzate**e di creare **nuove forme**.

Il cursore principale (quantità di colore) definisce il numero di colori totali utilizzati per creare la sfumatura. Il pulsante appena sotto definisce il metodo di fusione del colore (sRGB o lineare). Questo è importante se desiderate ottenere una fusione corretta tra i colori. Ad esempio, la fusione di un rosso puro e di un verde puro dovrebbe dare un bel giallo nel mezzo. Questo non è il caso se il pulsante è disattivato (darà invece un marrone scuro). Quando si modifica il height o qualsiasi altro canale in scala di grigio, questo pulsante deve essere disattivato per evitare la conversione di gamma.

Il pulsante in alto consente di sostituire il risultato del filtro con la sfumatura stessa, per visualizzare la sfumatura nel Vista 2D.

![](../../assets/gradient-height-demo.jpg)

### Miglioramenti a livello di interfaccia e comportamento

![](../../assets/tabs-top.png)

In questa versione, le **schede** dei diversi dock dell&#39;applicazione si trovano ora **nella parte superiore anziché nella parte inferiore** delle rispettive finestre. Questa scelta è stata fatta per migliorare la leggibilità dell&#39;interfaccia ma anche per essere più coerente con altre applicazioni. A seguito di questa modifica è stata introdotta la **piccola croce** accanto al titolo della scheda per **chiuderla facilmente**. È inoltre possibile **fare clic con il pulsante destro del mouse** sulla scheda per visualizzare un **menu di scelta rapida** (che consente di chiudere o disancorare la finestra). Per disancorare la finestra, una scelta rapida da tastiera deve semplicemente trascinare e rilasciare la linguetta all’esterno dell’area della finestra.

Ora è anche possibile **aprire i progetti** semplicemente trascinandoli **nella finestra della vista** da Esplora file. Funziona anche con i file **mesh**: se si trascina un file mesh in una **finestra di visualizzazione vuota**, verrà aperta la **finestra del nuovo progetto**, ma se si esegue questa operazione su un **progetto già aperto** verrà aperta la **finestra di dialogo di configurazione del progetto**, consentendo di **aggiornare rapidamente una mesh**.

**Nota**: in caso di problemi con il trascinamento della selezione,[consultate le domande frequenti sull&#39;argomento](../../technical-support/technical-issues/miscellaneous-issues/impossible-to-drag-and-drop-files-into-the-shelf.md).

### Miglioramenti delle prestazioni

Questa versione di Substance Painter include anche un nuovo e forte miglioramento delle prestazioni relativo al modo in cui gestiamo la memoria GPU (VRam). I colori uniformi (come i livelli di riempimento) vengono ora compressi in texture più piccole, accelerano il loro trasferimento tra la memoria principale e la memoria GPU, ma riducono anche l’ingombro della memoria e il tempo di calcolo. Questo dovrebbe essere particolarmente visibile quando si aprono progetti di grandi dimensioni e quando si raggiungono i limiti della memoria GPU.

## Note sulla versione

### 2017.3.3

(Pubblicato il 1° dicembre 2017)

**Risolto:**

* [Steam] La finestra a comparsa Controllo versione non deve essere visibile all’avvio
* I gruppi dei file PSD di [Esportazione] sono bloccati all’apertura in Photoshop CS6

### 2017.3.2

(Pubblicato il 20 novembre 2017)

**Aggiunto:**

* [UI] Migliora la finestra di dialogo per la nuova versione e aggiungi il registro modifiche
* [UI] Indica se la manutenzione è scaduta nella finestra di dialogo per una nuova versione
* [Licenza] Aggiornare il sistema di licenze per gestire le date di manutenzione
* [Esporta] Rinomina materiale standard Adobe in Adobe Dimension

**Risolto:**

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

### 2017.3.1

(Pubblicato il 26 ottobre 2017)

**Aggiunto:**

* [Esporta] Consente di esportare la trama da un progetto
* [Shelf] Rimuovere &quot;Sub-Shelf&quot; dai titoli delle schede
* Salvare le impostazioni di post-elaborazione nei modelli
* Rendere il messaggio TDR più comprensibile
* Finestra Migliora impostazioni per la segnalazione degli errori

**Risolto:**

* Arresto anomalo quando si eliminano più scaffali secondari
* Arresto anomalo quando si passa da un livello a qualcos&#39;altro durante il calcolo di un motore
* [Mac] Arresto anomalo sulla GPU Intel durante il calcolo del motore
* [Mac][Finestra vista] Prestazioni errate quando è attivato il dithering
* [Mac] MacOS 10.13 viene riconosciuto come &quot;Versione sconosciuta&quot; nel file di registro
* [Baker] Eseguire i baking con una gabbia non funziona più
* [Livelli] Ctrl + C scelta rapida da tastiera (azione copia) non funziona più
* [Livelli] Incollare i livelli non aggiorna l’interfaccia utente con i riferimenti dell’ancoraggio
* [Ancoraggio] Quando si duplica o si copia/incolla un livello con riferimenti, i collegamenti vengono interrotti
* [Esportazione] L&#39;esportazione 8K può causare l&#39;arresto anomalo o il blocco dell&#39;applicazione in alcuni casi
* [Esporta] Più problemi nel formato di file glTF generato
* [Import] La reimportazione di una trama con lo stesso nome di file non funziona più
* [Plugin] La finestra di salvataggio automatico viene sempre visualizzata sopra ogni elemento
* [UI] Ciclo infinito quando si preme &quot;Esc&quot; nella finestra di dialogo TDR
* [UI] Reimposta interfaccia utente visualizza una seconda barra del titolo nella finestra scaffale

### 2017.3

(Pubblicato il 28 settembre 2017)

**Aggiunto:**

* [Esporta] Consente di esportare trama e texture per il progetto Felix di Adobe
* [Esporta] Consente di esportare nel formato di file glTF
* [Engine] Ottimizza le dimensioni della texture nell&#39;VRAM utilizzando la compressione dei blocchi
* [Finestra vista] Consente di trascinare una trama o un progetto nella finestra della vista
* [UI] Migliora il messaggio di avviso relativo al TDR.
* [UI] Il registro deve essere visualizzato solo su richiesta
* [UI] Consenti di cancellare il contenuto della finestra di registro
* [UI] Visualizza avvisi ed errori nella barra di stato
* [UI] Visualizza le schede in alto come nei browser Web
* [UI] Migliorare il contesto e i messaggi &quot;non colorabili&quot;
* [UI] Aggiungi un’azione &quot;Salva come copia&quot; nel menu del file
* [Layer] Imposta l&#39;Affiancamento predefinito su 1 per impostazione predefinita
* [Ripiano] Filtro sfumatura migliorato per supportare 10 colori dinamici
* [Shelf] Aggiungi uno spazio nella query predefinita del mini-shelf
* [Shelf] Aggiungere un&#39;azione &#39;Apri in Esplora risorse&#39; per le risorse locali nello shelf
* [Scaffale] Aggiungi modello e shader per Adobe Material Standard (Project Felix)
* [Scaffale] Aumenta l’Affiancamento massimo a 128 negli ombreggiatori a strati di materiale
* [Ripiano] Curvatura sobel aggiunta per microdettagli dei Generatori di maschere
* [Plugin] Aggiungi plug-in di salvataggio automatico con intervallo di tempo personalizzabile
* [Scripting] Aggiungere una funzione &quot;Salva come copia&quot;

**Risolto:**

* [UI] Il layout non funziona al primo avvio
* [Esportazione] Il PSD generato durante l’esportazione contiene errori di formato
* [Esporta] L’EXR esporta sempre la mappa con altezza di 8 bit
* [Esporta] Arresto anomalo durante l’esportazione di mappe aggiuntive danneggiate
* [Importazione] In alcuni casi i bordi netti non vengono mantenuti su trame poly basse
* [Import] Messaggi di errore migliorati durante l&#39;importazione di trame con problemi
* [Baker] La Esegue i baking della mappa ID non riesce con l’opzione Corrispondenza per nome attivata
* [Finestra vista] Lo spazio tangente non è sincronizzato con i baker
* [Effetto] Spostandosi indietro di un livello non si ripristina il riferimento di un ancoraggio
* [Effetto] Problema di aggiornamento quando si crea un collegamento tra due maschere con ancoraggi
* [Effetto] I punti di ancoraggio delle maschere sopra la maschera non devono essere elencati
* [Effetto] L’impostazione Estrai Alpha da Ancoraggi non funziona
* [Motore] La maschera si inverte dopo il primo tratto del pennello
* [Engine] Arresto anomalo quando si cambia set di texture in un progetto specifico
* [Shelf] Arresto anomalo quando si elimina un predefinito che si trova in un progetto
* [Shelf] Tipo nel filtro avanzato Tri-Planari
* [Shelf] MG Mask Builder AO Noise Scale non funziona correttamente
* [Shelf] MG Mask Builder ha parametri di curvatura invertiti
* [Scaffale] Le alfa importate generano un&#39;anteprima della sfera di materiale anziché una di forma piatta
