---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/features/iray-renderer/viewer-and-mdl-settings.html"
breadcrumb-title: ''
description: Scopri come configurare le impostazioni del visualizzatore e MDL per il modulo di rendering di raggi X in Substance 3D Painter per personalizzare il rendering dei materiali.
helpx_creative_field: ""
helpx_description: Painter > Features > Iray Renderer > Viewer and MDL Settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni visualizzatore e MDL
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '733'
ht-degree: 0%

---


# Impostazioni visualizzatore e MDL

![](../../assets/display-settings-iray.png){width="400px"}

## Ambiente

Analogamente alla normale finestra della vista, la mappa ambiente utilizzata in Iray controllerà l&#39;illuminazione.\
Per modificare la mappa dell’ambiente, fai clic sul pulsante o trascina una texture HDR al suo interno.

* **Esposizione ambiente**: controlla il livello di esposizione della mappa ambiente HDR.
* **Rotazione ambiente**: per spostare la texture dell&#39;ambiente e ruotare la luce attorno alla scena.

>[!NOTE]
>
> Poiché Iray è un modulo di rendering basato su impostazioni fisiche, la texture ambiente definirà notevolmente l’illuminazione e l’aspetto della scena.

## Cupola

La cupola è la forma sulla quale verrà proiettata la mappa ambientale sullo sfondo.\
Sono disponibili 3 tipi di cupola, da utilizzare a seconda della scena:

![](../../assets/dome-type.png)

* **Sfera infinita**: l&#39;ambiente è proiettato in background su una sfera per simulare l&#39;orizzonte, sempre lontano dalla scena
* **Sfera**: l&#39;ambiente è proiettato su una sfera regolare, che può essere ridimensionata
* **Sfera con suolo**: simile alla forma precedente, questa ha anche un controllo per appiattire la parte inferiore della sfera per simulare un pavimento.

>[!NOTE]
>
> La Sfera con terra ha un controllo per definire la dimensione/raggio del pavimento, tuttavia un grande raggio creerà distorsioni sull&#39;ambiente.\
>  A seconda del tipo scelto, l’illuminazione può essere influenzata.

Sono disponibili impostazioni aggiuntive:

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Raggio** | Dimensioni della sfera (se non infinite) |
| **Scala texture** | Indica quanto verrà estesa la texture per il tipo **Sphere con ground**. |
| **Cancella colore** | Se questa opzione è attivata, sostituisci l’immagine di sfondo della mappa ambiente con un colore uniforme. Questo influirà sull’illuminazione. |

### Impostazioni del terreno

Le impostazioni del terreno consentono di specificare dove si trova un pavimento.\
Per impostazione predefinita, il valore è impostato per correggere la parte inferiore del rettangolo di selezione della scena.

| ***Impostazione*** | ***Descrizione*** |
| --- | --- |
| **Valore X, Y, Z** | Definite la posizione del pavimento sui tre assi.   Il valore 0,0,0 corrisponde al centro del rettangolo di selezione della scena. |
| **Riflettività** | Definisce l’intensità e il colore del riflesso del terreno.   Un valore di luminosità del bianco indica che il terreno è 100% riflettente, mentre il nero indica per nulla non riflettente. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/reflectivity-optim.gif"/></div> |
| **Lucentezza** | Definisce il grado di lucidità (o irregolare) del riflesso. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r3-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/glossiness-optim.gif"/></div> |
| **Intensità ombra** | Questo parametro definisce l’opacità finale dell’ombra dopo il calcolo dell’illuminazione. |
| **Visibile dal basso** | Definisce se il terreno è visibile dal basso o meno. Se selezionata, significa che il terreno occluderà qualsiasi elemento sovrastante. |

## Parametri MDL e Shader

Iray utilizza MDL per definire i materiali utilizzati per il rendering di un oggetto. Per ulteriori informazioni, consulta la [pagina Nvidia ufficiale del formato](http://www.nvidia.com/object/material-definition-language.html) .

Per impostazione predefinita, in Substance 3D Painter un file MDL è associato a uno shader GLSL e consente di passare dalla normale finestra della vista a Iray senza dover configurare nulla.\
I parametri della MDL vengono quindi visualizzati nella parte inferiore delle impostazioni del visualizzatore. Di seguito sono riportati i parametri del file MDL predefinito (compatibile con lo shader metallizzato/rugosità PBR).

>[!NOTE]
>
> Per caricare MDL personalizzati, è necessario uno shader glsl personalizzato.\
>  Nello shader è possibile aggiungere alcuni metadati per specificare il percorso mdl:
> 
> //- Dichiarare il materiale mdl iray da utilizzare con questo shader. //: metadati { //: &quot;mdl&quot;:&quot;mdl::alg::materials::physical\_metallic\_roughness::physical\_metallic\_roughness&quot; //: }
> 
> * **mdl**: definire il materiale mdl di Iray da utilizzare con lo shader. La sintassi del percorso è la seguente: *mdl::folder1::folder2::mdl\_filename::material\_name* dove *cartella1::folder2::mdl\_filename* è il percorso all&#39;interno di una cartella dello scaffale *mdl* in un file mdl e *::material\_name* è il nome di un materiale dichiarato all&#39;interno di questo file mdl. (ad esempio: &quot;mdl&quot; : &quot;mdl::alg::materials::fisicamente\_metallico\_rugosità::fisicamente\_metallico\_rugosità&quot;)

>[!NOTE]
>
> Per ogni istanza di materiale in un progetto verrà impostato un MDL. Pertanto, per separare le proprietà dei materiali tra Set di texture, impostate una nuova istanza Materiali in modo da configurare separatamente i file MDL.

![](../../assets/mdl.png)

Il file MDL predefinito di Substance 3D Painter supporta le seguenti proprietà:

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Intensità di emissione** | Moltiplicatore del canale di emissione. Un valore alto comincerà a emettere luce. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/emissive-optim.gif"/></div> |
| **Rifrazione** | Controlla la quantità di rifrazione. |
| **IOR** | Definisce l&#39;indice di rifrazione del materiale.   Nota : Aria = 1,0, Acqua = 1,2, Vetro = 1,5. |
| **Dispersione** | Controlla la quantità di luce diffusa sulla superficie. |
| **Assorbimento** | Controlla la quantità di luce assorbita attraverso la superficie. |
| **Colore di assorbimento** | Simula gli spostamenti di colore quando la luce attraversa la superficie. |
