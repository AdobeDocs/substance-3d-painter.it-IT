---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/getting-started/glossary.html"
breadcrumb-title: ''
description: Accedete al glossario di Substance 3D Painter per comprendere i termini e i concetti chiave usati nella documentazione.
helpx_creative_field: ""
helpx_description: Painter > Getting Started > Glossary
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Glossario
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '2131'
ht-degree: 6%

---


# Glossario

Substance 3D Painter è un&#39;applicazione 3D che si basa su molte tecniche e parole chiave tecniche che possono essere difficili da capire all&#39;inizio.\
In questa pagina sono elencate le parole chiave più comuni utilizzate dall’applicazione insieme a una breve spiegazione del relativo significato.

| *Parola chiave* | *Definizione* |
| --- | --- |
| **Allineamento** | L’allineamento indica il modo in cui il pennello sarà orientato verso la trama 3D durante il disegno. |
| **Alpha** | Un canale alfa è una maschera che può essere utilizzata per colorare dettagli o forme complesse, ad esempio un codice a barre o un logo. |
| **Bake** | Per &quot;infornata&quot; si intende l’azione di calcolare le informazioni da una trama 3D e salvarle in una texture basata sulle informazioni UV di una trama. |
| **Profondità di bit** | La profondità di bit è la quantità di informazioni che possono essere memorizzate in una texture (per colore). Maggiore è il numero, migliore è la precisione delle informazioni. Tuttavia le prestazioni diminuiscono con numeri elevati durante l&#39;esecuzione dei calcoli. |
| **Pennello** | Un pennello è uno strumento per colorare su una mesh. Un pennello è definito da più parametri che ne controllano il comportamento (ad esempio le dimensioni e l’opacità). |
| **Fotocamera** | La videocamera è l’oggetto che consente di controllare la posizione e la direzione della vista in una finestra 3D o 2D. |
| **Canale** | Un canale è una texture con un comportamento specifico. Alcuni canali vengono utilizzati per definire il colore di un materiale, altri per controllare il comportamento della luce su una superficie. |
| **Clona** | Il clone è uno strumento utilizzato per replicare parte del disegno/texture in un’altra posizione. |
| **Contenuto/Maschera** | Il contenuto e la maschera si riferiscono alle due proprietà principali di un livello. Il contenuto è il disegno effettivo memorizzato nei canali contenuti in un livello, mentre la maschera viene utilizzata per visualizzare/nascondere il contenuto. Una maschera nera equivale a un contenuto invisibile. |
| **Diffusione** | La diffusione è un modo per generare informazioni al di fuori dell&#39;Isola UV di una trama. Funziona disperdendo gli ultimi pixel vicino al bordo di un’isola UV, creando colori sfocati. |
| **Dilatazione/Spaziatura interna** | Sulla stessa idea della diffusione, la dilatazione è un modo di generare informazioni al di fuori dell&#39;Isola UV estendendo i colori dei pixel. |
| **Effetto** | Un effetto è un elemento che può essere aggiunto a un livello, sul contenuto o sulla maschera. Substance 3D Painter supporta vari tipi di effetti, ad esempio i filtri. |
| **Ambiente** | Un ambiente è un’immagine utilizzata per calcolare l’illuminazione di una scena; si tratta in genere di una texture HDR che rappresenta un’ampia gamma di informazioni sul colore. |
| **Esporta** | L’esportazione consente di generare texture appiattite dal dipinto realizzato all’interno dell’applicazione. Le texture create dall’esportazione possono essere utilizzate in altre applicazioni. |
| **FOV / Campo di visualizzazione** | Il FOV è l&#39;estensione del mondo osservabile dalla Camera. |
| **Riempi** | Riempimento è un’azione (che può essere un effetto o un livello) che può caricare un colore, una texture o persino un materiale sull’intera trama 3D. |
| **Filtro** | Un filtro è un effetto Substance in grado di modificare le informazioni precedenti. Ad esempio, un filtro di sfocatura attenua un’immagine precedente. I filtri possono anche essere più complessi e modificare un materiale completo. |
| **Filtraggio** | I filtri si riferiscono al modo in cui le texture vengono visualizzate all’interno di una finestra della vista 3D. I più comuni sono i più vicini (i pixel vengono letti così com’è, creando un’immagine apparentemente squadrata verso l’alto) e bilineari (i pixel vengono interpolati, creando un’immagine sfocata verso l’alto). |
| **GPU** | La GPU (Graphic Processing Unit) è la parte di un computer che esegue calcoli rapidi per la produzione di immagini. |
| **Generatore** | Un Generatore è una Substance che genera nuove informazioni/immagini in genere basate su texture aggiuntive. Ad esempio, alcuni generatori di maschere usano texture cotta per creare maschere complesse. |
| **Istogramma** | Un istogramma è una rappresentazione grafica della distribuzione dei valori cromatici. Viene utilizzato per visualizzare il modo in cui i colori vengono bilanciati all’interno di un’immagine tra ombre, mezzitoni e luci. |
| **Iray** | Iray è un modulo di rendering per tracciati creato da NVIDIA, utilizzato per proiettare un’illuminazione realistica sulla trama 3D. Trattandosi di un modulo di rendering avanzato, è stato progettato per creare immagini belle e non per essere utilizzato per lavori in tempo reale. |
| **Variazione** | La variazione è una proprietà del pennello che produce un comportamento casuale durante il disegno. |
| **Livello** | Un livello è un elemento che contiene più canali con proprietà aggiuntive come un metodo di fusione e un’opacità. |
| **Stack di livelli** | Una pila di livelli è un punto in cui i livelli possono essere gestiti e organizzati. I livelli sono organizzati dal basso verso l’alto. Il livello inferiore verrà disegnato per primo, quindi ogni livello superiore verrà aggiunto uno alla volta l&#39;uno sopra l&#39;altro. |
| **Mouse pigro** | Il mouse pigro è un comportamento dello strumento pennello. Rallenta il tracciato del pennello per migliorare la precisione durante il disegno e crea un ritardo/scostamento tra il cursore del mouse e il disegno effettivo. |
| **Livello** | Un livello è un effetto che consente di controllare un intervallo o le informazioni sul colore/scala di grigi tramite un istogramma. Può essere utilizzato ad esempio per invertire il colore o scurire/schiarire un colore. |
| **Registro** | Un registro è un file di testo in cui vengono scritte informazioni dal software, in genere correlate al computer che esegue l&#39;applicazione. |
| **Trama bassa/alta** | Una maglia poly bassa e una alta sono entrambe mesh 3D, una è con una bassa densità di poligoni, mentre l&#39;altra è con una maggiore quantità di politonio (spesso 100 volte più grande). Di solito le informazioni sulla trama alta sono incise sulla trama bassa. |
| **Materiale** | Un materiale definisce le proprietà per rappresentare un argomento specifico. Su una trama 3D, il materiale viene utilizzato anche per definire gruppi di facce poligonali. |
| **Trama** | Una trama è un oggetto 3D definito da più informazioni. In Substance 3D Painter una trama è definita da poligoni (in genere triangoli). È possibile creare una trama in un&#39;applicazione di modellazione 3D come **Blender** o **Autodesk Maya**. |
| **Mappa trama** | Una mappa di trama è una mappa ricavata da una trama che contiene informazioni relative alla trama stessa. Può essere un&#39;informazione di posizione o un&#39;informazione di occlusione, ad esempio. |
| **Mip-Map** | Mip-map è una texture pre-calcolata, di solito presente come sequenza di immagini ogni volta a una risoluzione inferiore rispetto alla texture originale. |
| **Modalità** | Una modalità si riferisce alla configurazione dell&#39;interfaccia che dà accesso a una serie specifica di strumenti e controlli a seconda della modalità. |
| **Disturbo** | Un disturbo è un’immagine procedurale e casuale, che di solito rappresenta forme organiche e valori di colore/scala di grigi. |
| **Normale** | Una normale è una texture speciale che deforma il modo in cui una luce si comporta sulla superficie di una trama 3D per simulare dettagli che non esistono nella geometria. |
| **OpenGL / DirectX** | OpenGL e DirectX sono entrambe API (Application Programming Interface) utilizzate per il rendering di informazioni 2D e 3D. Definiscono anche il formato mappa normale. |
| **Ortografico** | Una proiezione ortogonale è un mezzo per rappresentare oggetti tridimensionali in due dimensioni in cui tutte le linee di proiezione sono ortogonali al piano di proiezione. |
| **PBR / PBS** | Il Rendering fisicamente basato (PBR) o Ombreggiatura fisica (PBS) è un modello nella computergrafica che cerca di eseguire il rendering della grafica in modo da modellare più accuratamente il flusso di luce nel mondo reale. |
| **Impacchettamento** | L’impacchettamento è l’azione di memorizzare più immagini all’interno di una texture. Poiché le texture sono composte da canali separati Rosso, Verde e Blu, possono memorizzare informazioni diverse che possono essere lette in modo indipendente in un’altra applicazione. |
| **Particelle** | Le particelle sono un tipo di strumento che genera tratti di pennello basati su proprietà fisiche o altri comportamenti complessi. |
| **Prospettiva** | La prospettiva è una rappresentazione approssimativa di un oggetto o di una scena vista dall&#39;occhio umano su una superficie piana (come uno schermo). È una simulazione di profondità e scala. |
| **Pixel/Texel** | Un pixel è un punto di un’immagine; è il più piccolo elemento possibile che contiene informazioni sui colori. Maggiore è la risoluzione, maggiore è il numero di pixel disponibili, con una migliore definizione e maggiori dettagli. I testi sono pixel all’interno di una texture. |
| **Plug-in** | I plug-in sono funzioni di programmazione (spesso espresse tramite scripting) che possono essere aggiunte al software, estendendo le possibilità dell&#39;applicazione. |
| **Post-elaborazione** | Un post-processo è un effetto visivo applicato sullo schermo una volta che l’immagine 3D è stata sottoposta a rendering, spesso per simulare comportamenti speciali come la correzione del colore o la fioritura. |
| **Procedurale** | Procedural è un termine che descrive un processo generato da un computer in base a una serie di parametri. Può trattarsi semplicemente di risultati matematici come numeri o immagini complesse. |
| **Proiezione** | Una proiezione è l’azione di applicare da un punto di vista specifico (come la fotocamera) un’immagine/oggetto sulla superficie della trama 3D. |
| **Risoluzione (potenza di 2)** | La risoluzione definisce le dimensioni di una texture sugli assi X e Y (o larghezza e height). Spesso in una potenza di 2 scale (2, 4, 8, 16... 512, 1024, 2048...) perché è ottimizzato per i calcoli su una GPU. |
| **Scripting** | Lo scripting è l&#39;atto o l&#39;utilizzo di un comando specifico tramite un formato di file basato su testo per eseguire comportamenti specifici. |
| **Shader** | Uno shader definisce il comportamento di un materiale quando riceve informazioni di illuminazione. Alcuni shader possono essere semplici (come ombreggiatura toon) o più avanzati (come ombreggiatura della pelle che simula l’assorbimento di luce in una superficie). |
| **Scaffale** | Uno scaffale è la posizione nell&#39;applicazione in cui sono organizzate risorse di tipo multiplo. Può passare da immagini semplici a strumenti più complessi. |
| **Maschera avanzata** | Le maschere avanzate si comportano come materiali intelligenti, ma anziché essere livelli, sono effetti definiti per generare una maschera solo in base alla trama 3D corrente. |
| **Materiale avanzato** | Un materiale avanzato è un gruppo di livelli salvati come un unico file. I materiali intelligenti possono adattarsi a ciascun progetto in Substance 3D Painter, consentendo di creare materiali che cambieranno a seconda della trama 3D corrente. |
| **Sfumino** | Sfumino è uno strumento per sfumare, diffondere o miscelare i colori. Viene spesso utilizzato per ammorbidire i pixel. |
| **Stencil** | Uno stencil è un&#39;immagine allineata allo schermo e utilizzata con una proiezione della fotocamera per dipingere sulla trama 3D. |
| **Substance** | Una Substance è un formato di file che consente di generare texture in base a un insieme di parametri (che comportano calcoli procedurali). Questi parametri possono essere modificati per creare variazioni. |
| **Simmetria** | La simmetria è un&#39;opzione di uno strumento che consente di dipingere in due punti contemporaneamente in modo speculare. |
| **Modello** | Un modello è un insieme di opzioni predefinite utilizzate durante la creazione di un nuovo progetto. Ad esempio, può definire la risoluzione di default o l&#39;impostazione di baking di default. |
| **Proporzioni testo** | Il rapporto di testo è la regola che confronta la dimensione di un’Isola UV (2D) e la geometria della trama 3D ad essa correlata. Un buon rapporto di testo indica uno sviluppo uniforme della geometria in 2D. È importante mantenere coerenti l’aspetto e la qualità della pittura/texture sulla trama 3D. |
| **Texture** | Una texture è un file contenente pixel in 2 dimensioni definite da una risoluzione. I pixel possono essere in scala di grigio o colorati. Quando colorati, i pixel possono avere informazioni di trasparenza (se supportate dal formato del file). |
| **Set Di Texture** | In Substance 3D Painter un set di texture rappresenta una parte di una trama con UV specifici su cui colorare. Il Set di texture viene creato in base al materiale univoco rilevato durante l’importazione di una trama 3D. |
| **Lavorazione** | L’aratura è la ripetizione di una texture in cui le cuciture non sono visibili ai bordi, ma serve a simulare un piano infinito. Esempio: erba o marciapiedi. |
| **Strumento** | Uno strumento si riferisce a un’azione che consente di interagire con la trama 3D, spesso per dipingere o applicare effetti. |
| **Barra Degli Strumenti** | La barra degli strumenti è la posizione in cui sono disponibili tutte le scelte rapide da tastiera per gli strumenti. |
| **UDIM** | UDIM consente di dividere gli UV di una trama 3D su più intervalli per aumentare la risoluzione generale della texture. |
| **UV** | I raggi UV sono informazioni definite su una trama 3D che indicano come può essere dispiegata per diventare una forma piatta. Queste informazioni vengono utilizzate per proiettare una texture su una trama 3D. Substance 3D Painter consente di dipingere solo nell’intervallo 0-1, che rappresenta le dimensioni di una texture. Altri intervalli sono supportati solo tramite il sistema UDIM. |
| **VRam** | VRam è la memoria della GPU (scheda grafica), utilizzata per memorizzare informazioni e texture durante l’esecuzione dei calcoli. Maggiore è il valore VRam, migliore è la possibilità di lavorare con Substance 3D Painter. |
| **Viewport** | Il riquadro di visualizzazione è la sezione dello schermo in cui viene visualizzata la scena 3D o 2D. È anche l’area in cui è possibile interagire con gli strumenti e la mesh 3D controllando la fotocamera. |
