---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/fill-projections/spherical-projection.html"
breadcrumb-title: ''
description: Usate proiezione sferica in Substance 3D Painter per proiettare le texture da una sfera per disporre le texture attorno agli oggetti.
helpx_creative_field: ""
helpx_description: Painter > Painting > Fill projections > Spherical projection
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Proiezione sferica
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '855'
ht-degree: 2%

---


# Proiezione sferica

![](../../assets/spherical-proj.jpg)

La Proiezione sferica di riempimento consente di proiettare immagini e pattern attorno a un oggetto. Può essere utile proiettare su oggetti rotondi o distorcere la texture in pattern circolari.

## Proprietà

| Impostazione | Descrizione |
| --- | --- |
| **Filtraggio** | Controlla il modo in cui la texture o il materiale verranno filtrati. Questa impostazione può influire sull’aspetto della texture quando viene ripetuta più volte. Con valori di ridimensionamento elevati, l’utilizzo di un filtro diverso da quello predefinito può produrre risultati migliori. Impostazioni correnti disponibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Bilineare | HQ</strong> (impostazione predefinita): filtro bilineare avanzato che tenta di migliorare la qualità della texture quando i valori di suddivisione in porzioni sono elevati.</li><li data-preserve-html="true"><strong>Bilineare | Nitidezza</strong>: filtro bilineare semplice che ammorbidisce leggermente la texture, ma tenta di mantenere i dettagli.</li><li data-preserve-html="true"><strong>Più vicino</strong>: nessun filtro utile se il filtro bilineare produce un risultato sfocato e interrompe i dettagli più fini. Può introdurre l’alias nella texture.</li></ul> |
| **Involucro UV** | Controllate la modalità di ripetizione della texture all’interno della proiezione. I valori possibili sono:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Nessuno</strong>: la texture non viene ripetuta. Tutto ciò che si trova al di fuori della texture è nero/trasparente.</li><li data-preserve-html="true"><strong>Ripetizione orizzontale</strong>: la texture si ripete solo orizzontalmente.</li><li data-preserve-html="true"><strong>Ripeti verticalmente</strong>: la texture si ripete solo verticalmente.</li><li data-preserve-html="true"><strong>Ripetizione</strong> (impostazione predefinita): la texture si ripete su entrambi gli assi.</li></ul> <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/spherical-repeat.jpg" width="500px"/></div> |
| **Ritaglio forma** | Definite se la texture proiettata deve essere visibile all&#39;esterno dell&#39;area di proiezione. I valori possibili sono:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Progetto ritagliato in forma</strong>: la proiezione è limitata all&#39;interno dell&#39;area di proiezione.</li><li data-preserve-html="true"><strong>La proiezione si estende oltre la forma</strong> (impostazione predefinita): la proiezione continua oltre l&#39;area di proiezione.</li></ul> <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r3-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/spherical-shape-crop.jpg" width="500px"/></div> |

### Trasformazione UV

Le impostazioni di trasformazione UV controllano la texture all’interno della proiezione.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Scala** | Definite quante volte la texture verrà ripetuta all’interno della proiezione. |
| **Rotazione** | Controllate l’angolo della texture applicata alla proiezione. |
| **Scostamento** | Controllate l’origine della texture proiettata. Il valore di default indica che la texture si trova al centro della proiezione. |

### Impostazioni progetto 3D

Le impostazioni di proiezione 3D controllano la trasformazione della proiezione nello spazio 3D.

| Impostazione | Descrizione |
| --- | --- |
| **Scostamento** | Posizione dell&#39;origine della proiezione nello spazio 3D. Le unità si basano sul rettangolo di selezione dell’intera scena. 0 è il centro di questa casella. |
| **Rotazione** | Angoli in gradi per ruotare l’intera proiezione su ciascun asse. |
| **Scala** | Dimensione dell&#39;intera proiezione su ciascun asse. |

## Barra degli strumenti contestuale

Nella [barra degli strumenti contestuale](../../interface/toolbars.md) che si trova nella parte superiore della finestra della vista, sono disponibili varie impostazioni e strumenti che consentono di controllare il manipolatore e la proiezione:

| Icona | Nome | Descrizione |
| --- | --- | --- |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r1-column-c0_image" src="../../assets/icon-hide-manipulator.png" width="50px"/></div> | Mostra/nascondi il manipolatore | Se questa opzione è attivata, il manipolatore è visibile e controllabile nella finestra della vista. |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r2-column-c0_image" src="../../assets/icon-manipulator-settings.png" width="50px"/></div> | Impostazioni manipolatore | Questo menu contiene tre impostazioni:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Dimensione manipolatore</strong>: controlla la dimensione del manipolatore nella finestra della vista.</li><li data-preserve-html="true"><strong>Passaggi griglia</strong>: definisci la dimensione del passaggio durante la traduzione con un vincolo.</li><li data-preserve-html="true"><strong>Passaggi angolari</strong>: definisci l&#39;angolo del passo quando si ruota con un vincolo.</li></ul> |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r3-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-translate.png" width="50px"/></div> | Manipolatore di traduzione | Consente di spostare la proiezione nella scena lungo gli assi principali (X, Y, Z). |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r4-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-rotate.png" width="50px"/></div> | Manipolatore di rotazione | Consente di ruotare la proiezione nella scena lungo gli assi principali (X, Y, Z). |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r5-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-scale.png" width="50px"/></div> | Manipolatore scala | Consente di ridimensionare la proiezione nella scena lungo gli assi principali (X, Y, Z). |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r6-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-surface.png" width="50px"/></div> | manipolatore di superficie | Consente di spostare la proiezione agganciandola sulla superficie del modello 3D.  **Nota:** questo manipolatore è disponibile solo con i tipi di proiezione Planar e Warp. |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r7-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-space.png" width="50px"/></div> | Spazio manipolatore | Definisce lo spazio in cui viene eseguita la trasformazione. I valori possibili sono:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Spazio locale</strong>: gli assi sono allineati alla trasformazione corrente.</li><li data-preserve-html="true"><strong>Spazio globale</strong>: gli assi sono allineati alla scena.</li></ul> |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r8-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-flip-x.png" width="50px"/></div> | Speculare su X | Invertite la trasformazione sull&#39;asse X. |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r9-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-flip-y.png" width="50px"/></div> | Speculare su Y | Invertite la trasformazione sull&#39;asse Y. |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r10-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-flip-z.png" width="50px"/></div> | Speculare su Z | Invertite la trasformazione sull&#39;asse Z. |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r11-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-reset.png" width="50px"/></div> | Reimposta la trasformazione | Ripristina lo stato predefinito della trasformazione di proiezione. |

## Manipolatore

Questo manipolatore di proiezione è disponibile solo nella [finestra della vista 3D](../../interface/viewport/3d-view.md).

| Azione | Scelta rapida | Descrizione |
| --- | --- | --- |
| **Traduzione** | Clic del mouse | Con il manipolatore Traslazione (Translation), fate clic sugli assi per spostare la proiezione:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Un asse</strong>: spostarsi solo in una direzione della proiezione.</li><li data-preserve-html="true"><strong>Due assi</strong>: spostate la proiezione sui piani allineati agli assi.</li><li data-preserve-html="true"><strong>Tre assi</strong>: spostate la proiezione nello spazio della fotocamera (piano rivolto verso di essa).</li></ul>   <table> <tr style="border: 0;"> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r1-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/3d-translate.gif" width="200px"/></div>  </td> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r1-column-c2_dynamic_grid_items_grid-cell1_position-par_image" src="../../assets/3d-translate-2axes.gif" width="200px"/></div>  </td> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r1-column-c2_dynamic_grid_items_grid-cell2_position-par_image" src="../../assets/3d-translate-3axes.gif" width="200px"/></div>  </td> </tr> </table> |
| **Traduzione vincolata** | MAIUSC+clic del mouse | Con il manipolatore Traslazione (Translation), spostate la proiezione lungo gli assi selezionati, ma solo a intervalli specifici (stepping). La dimensione dell&#39;intervallo viene definita tramite le impostazioni del manipolatore. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r2-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/3d-translate-step.gif" width="200px"/></div> |
| **Rotazione** | Clic del mouse | Con il manipolatore Rotazione, facendo clic su un asse si ruota la proiezione. Fate clic tra gli assi per consentire la rotazione di tutti gli assi contemporaneamente.   <table> <tr style="border: 0;"> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r3-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/3d-rotate.gif" width="200px"/></div>  </td> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r3-column-c2_dynamic_grid_items_grid-cell1_position-par_image" src="../../assets/3d-rotate-3axes.gif" width="200px"/></div>  </td> </tr> </table> |
| **Rotazione vincolata** | MAIUSC+clic del mouse | Con il manipolatore Rotazione, fare clic su un asse per ruotare la proiezione solo a intervalli specifici. Il passo viene definito da un angolo tramite le impostazioni del manipolatore. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r4-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/3d-rotate-step.gif" width="200px"/></div> |
| **Scala** | Clic del mouse | Con il manipolatore Scala, facendo clic su una maniglia dell&#39;asse potete ridimensionare la proiezione lungo l&#39;asse specificato.   <table> <tr style="border: 0;"> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r5-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/scale-one-axis.gif" width="200px"/></div>  </td> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r5-column-c2_dynamic_grid_items_grid-cell1_position-par_image" src="../../assets/scale-two-axis.gif" width="200px"/></div>  </td> <td style="border: 0;" valign="top">  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r5-column-c2_dynamic_grid_items_grid-cell2_position-par_image" src="../../assets/scale-3-axes.gif" width="200px"/></div>  </td> </tr> </table> |
| **Scala vincolata** | MAIUSC+clic del mouse | Con il manipolatore Scala (Scale), facendo clic su una maniglia dell&#39;asse mantenendo la scelta rapida da tastiera, la proiezione viene ridimensionata gradualmente. La dimensione del passo è uguale a quella del manipolatore di traslazione. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r6-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/scale-1-axis-constrained.gif" width="200px"/></div> |
| **Superficie** | Clic del mouse | Con il manipolatore Superficie (Surface), fate clic e trascinate sul modello 3D per eseguirne lo snap sulla superficie. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r7-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/surface.gif" width="200px"/></div> **Nota:** questo manipolatore è disponibile solo con i tipi di proiezione **Planar** e **Warp**. |
