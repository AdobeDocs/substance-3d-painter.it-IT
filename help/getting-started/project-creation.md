---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/getting-started/project-creation.html"
breadcrumb-title: ''
description: Scoprite come creare un nuovo progetto in Substance 3D Painter per iniziare a colorare le texture sui modelli 3D.
helpx_creative_field: ""
helpx_description: Painter > Getting Started > Project Creation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creazione del progetto
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '1157'
ht-degree: 1%

---


# Creazione del progetto

![](../assets/v12_banner_project_window.jpg)

La <b>finestra Nuovo progetto </b>consente di creare un file di progetto per memorizzare il modello 3D e le relative informazioni di texture.

Viene creato un nuovo [set di texture](../interface/texture-set/texture-set.md) per ogni definizione di materiale trovata nel modello 3D importato. Ciò significa che più oggetti possono essere importati tramite un singolo file (anche con UV sovrapposti) se hanno materiali diversi.

## Creazione di un nuovo progetto

Per creare un nuovo progetto, fai clic su <b>File > Nuovo</b> o utilizza la scelta rapida da tastiera <b>Ctrl + N</b>.

Di seguito è riportata una spiegazione di tutti i parametri disponibili nella finestra Nuovo progetto.

### Impostazioni di base

| *Parametro* | *Descrizione* |
| --- | --- |
| **File** | Fate clic sul pulsante &quot;Seleziona&quot; per specificare il file del modello 3D da caricare. [Un elenco dei formati di file supportati è disponibile qui.](https://experienceleague.adobe.com/en/docs/substance-3d/general-knowledge/ecosystem/import-and-export-formats) |
| **Modello** | Specificate un modello che definirà le impostazioni predefinite del progetto. Un modello contiene i seguenti parametri:<ul data-preserve-html="true"> <li data-preserve-html="true">Impostazioni del set di texture.</li> <li data-preserve-html="true">Impostazioni dello schermo.</li> <li data-preserve-html="true">Impostazioni di cottura.</li> <li data-preserve-html="true">Risorse shader (incluse le texture associate).</li> <li data-preserve-html="true">File mappa ambiente.</li> </ul>  **Nota:** i modelli sono file di <b>\*.spt</b> creati da un progetto esistente tramite il [menu File](../interface/main-menu/file-menu.md) e salvati all&#39;interno della cartella Risorse per essere facilmente condivisi con i membri del team. |
| <b>Risoluzione</b> | Definite la risoluzione predefinita della texture del progetto per ciascun set di texture. La risoluzione può arrivare fino a 4K (4096x4096 pixel) quando si lavora all&#39;interno dell&#39;applicazione e 8K (8192x8192 pixel) quando si esporta. La risoluzione può essere modificata in qualsiasi momento in seguito, tramite le [impostazioni del set di texture](../interface/texture-set/texture-set-settings.md).  **Nota:** l&#39;esportazione in 8K richiede almeno 2,5 GB di VRam nella GPU per essere disponibile. |

### Impostazioni specifiche per il tipo di file

Quando viene selezionato un file USD, diventano disponibili altre impostazioni specifiche per il tipo di file.

| *Parametro* | *Descrizione* |
| --- | --- |
| <b>Ambito e varianti</b> | Selezionare una parte specifica di un file USD. Per impostazione predefinita, questa opzione è impostata su &quot;Root&quot;, il che significa che per creare il progetto Painter verrà utilizzato l’intero file USD.  <b>Modifica...</b> apre una nuova finestra che visualizza il contenuto dell&#39;USD. Se vengono rilevate varianti, è possibile selezionare una variante specifica per la creazione del progetto. È possibile modificare l&#39;ambito e le varianti dopo la creazione del progetto nelle impostazioni [Configurazione del progetto](../interface/project-configuration.md). Si noti che -<ul data-preserve-html="true"> <li data-preserve-html="true">Solo la selezione della variante di modellazione avrà un impatto sul progetto.</li> <li data-preserve-html="true">Le varianti nidificate all&#39;interno delle varianti non vengono attualmente rilevate.</li> </ul> |
| <b>Livello di suddivisioni</b> | Per la geometria che deve essere suddivisa, questa impostazione consente di specificare di quanto si desidera suddividere la trama per la creazione di texture in Painter. Se la suddivisione è impostata in modo esplicito su &#39;none&#39; all&#39;interno del file USD, questa impostazione è disattivata.  La suddivisione viene applicata dopo lo srotolamento degli UV, in modo da non alterare la forma degli UV della trama. I livelli di suddivisioni possono essere modificati dopo la creazione del progetto nelle impostazioni [Configurazione del progetto](../interface/project-configuration.md). |
| <b>Fotogramma</b> | Per i file USD in cui vengono rilevate animazioni, questa impostazione consente di selezionare il fotogramma che verrà utilizzato per creare il progetto Painter. Se nel file USD selezionato non è presente alcuna animazione, questa impostazione è disattivata. È possibile modificare la cornice dopo la creazione del progetto nelle impostazioni [Configurazione del progetto](../interface/project-configuration.md). |

### Impostazioni AVANZATE

| *Parametro* | *Descrizione* |
| --- | --- |
| **Formato mappa normale** | Definisce il Formato mappa normale per il progetto, che può essere<ul data-preserve-html="true"><li data-preserve-html="true"><strong>DirectX</strong> (X+, Y-, Z+)</li><li data-preserve-html="true"><strong>OpenGL</strong> (X+, Y+, Z+)</li></ul>  **Nota:** come promemoria:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Il motore irreale</b> utilizza il DirectX per impostazione predefinita.</li> <li data-preserve-html="true"><b>Unità</b> utilizza OpenGL per impostazione predefinita.</li> </ul> |
| **Calcola spazio tangente per frammento** | Se questa opzione è attivata, i bitangenti vengono calcolati nello shader del frammento (pixel) anziché nel vertice shader. Questo parametro influisce sul modo in cui la mappa Normale viene decodificata dallo shader nella finestra della vista. La modifica di queste impostazioni richiederà la riattivazione della mappa Normale.  **Nota:** come promemoria:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Il motore irreale</b> richiede che questa impostazione sia abilitata.</li> <li data-preserve-html="true">Per <b>Unity</b> è necessario che questa impostazione sia disabilitata (o abilitata se si utilizza il flusso di lavoro HDRP)</li> </ul> |

### Impostazioni della porzione UV (UDIM)

>[!NOTE]
>
> Queste impostazioni non possono essere modificate una volta creato il progetto.

| *Parametro* | *Descrizione* |
| --- | --- |
| **Usa flusso di lavoro porzioni UV** | Se selezionata, la trama importata verrà elaborata in modo diverso per consentire la pittura al di fuori dell&#39;intervallo UV regolare (0-1). I progetti che utilizzano UDIM devono abilitare questa impostazione. L’elaborazione della trama può variare a seconda dell’impostazione.   Per ulteriori informazioni, consultate la [documentazione relativa ai riquadri UV](../features/uv-tiles/uv-tiles.md). |
| <b>Mantenere il layout delle porzioni UV per i materiali e abilitare la pittura su più porzioni</b> | Le porzioni UV (UDIM) vengono importate e raggruppate per assegnazione di materiale sulla trama. Ciò significa che un singolo set di texture può contenere più porzioni UV visibili l’una accanto all’altra nella vista 2D. Le porzioni UV che si trovano all&#39;interno dello stesso set di texture possono essere dipinte in modo uniforme.  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r2-column-c1_image_copy" src="../assets/uvtiles-paintacross.jpg" width="500px"/></div> |
| <b>Convertire porzioni UV in singoli set di texture (legacy)</b> | Le porzioni UV (UDIM) vengono separate in singoli insiemi di texture e rinominate, ignorando qualsiasi assegnazione di materiale. Ogni porzione UV viene spostata nell&#39;intervallo UV [0-1] per essere colorabile.  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r3-column-c1_image" src="../assets/uvtiles-legacy.jpg" width="500px"/></div> |

### Importa impostazioni

| ***Parametro*** | ***Descrizione*** |
| --- | --- |
| **Importa fotocamere** | Se le fotocamere sono presenti nel file con trama, verranno importate nel progetto e saranno accessibili come predefiniti per la visualizzazione.  **Nota:** Substance 3D Painter non supporta alcune fotocamere in determinate condizioni:<ul data-preserve-html="true"><li data-preserve-html="true">Fotocamere fisiche di 3DS Max.</li><li data-preserve-html="true">Fotocamere ortografiche memorizzate in file Alembic (&#42;.abc).</li></ul> |
| **Annullamento automatico del wrapping** | Se questa opzione è attivata, verranno generati UV mancanti sulla trama importata. L&#39;elaborazione potrebbe cambiare a seconda delle impostazioni selezionate tramite il pulsante **Opzioni**.Per ulteriori informazioni, consulta la [documentazione per lo srotolamento automatico degli UV](../features/automatic-uv-unwrapping.md). |

### Importa mappe con baking

Usate il pulsante <b>Aggiungi</b> per caricare i file di texture come mappe trama e assegnarli automaticamente nelle [impostazioni del set di texture](../interface/texture-set/texture-set-settings.md). È necessario seguire una convenzione di denominazione specifica affinché le mappe mesh vengano assegnate automaticamente ai rispettivi set di texture. Le mappe della trama possono anche essere cotte direttamente all&#39;interno dell&#39;applicazione; consultate la documentazione sulla cottura al forno.

Convenzione di denominazione:<b> TextureSetName\_MeshMapName</b>

Esempio: <b> DefaultMaterial\_ambient\_occlusioni.png </b>

Elenco delle mappe di trama supportate e loro denominazione:

| *Mappa trama* | *Convenzione per il nome file* |
| --- | --- |
| **occlusione ambiente** | ambiente\_occlusione |
| **Curvatura** | curvatura |
| **Normale** | normal\_base |
| **Spazio globale normale** | world\_space\_normals |
| **ID** | id |
| **Posizione** | posizione |
| **Thickness** | spessore |

### Dimensione fisica

Le impostazioni dimensioni fisiche consentono di regolare il modo in cui Painter determina la dimensioni fisiche della trama in unità reali. Ciò è utile per garantire che i materiali vengano applicati in scala realistica.

* Usa scala di unità interna del file mesh: la maggior parte dei tipi di file include informazioni sulla dimensioni fisiche dell’oggetto esportato dall’applicazione di modellazione 3D. Quando questa opzione è selezionata, Painter utilizzerà queste informazioni del file importato.
* Scala unità personalizzata: sovrascrivi la scala unità del file importato o, se non è inclusa alcuna scala unità, utilizza la casella di immissione personalizzata per regolare la dimensione di una singola &quot;unità&quot;.
* Imposta la scala dei livelli di riempimento su Dimensioni fisiche durante l’assegnazione dei materiali: se questa opzione è attivata, i materiali con informazioni sulla dimensioni fisiche possono regolarne la scala in modo che corrisponda alla dimensioni fisiche della superficie a cui vengono applicati.

### Gestione del colore

![](../assets/newproj-cm.png)

Questa sezione controlla le impostazioni di gestione del colore del progetto. Per impostazione predefinita, è impostato su Legacy (flusso di lavoro sRGB / lineare).

Consulta la documentazione sulla [gestione colore](../features/color-management/color-management.md) per ulteriori informazioni sull&#39;utilizzo di questo flusso di lavoro e sulle impostazioni.
