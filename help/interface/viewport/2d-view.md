---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/viewport/2d-view.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la vista 2D in Substance 3D Painter per visualizzare e modificare le texture nello spazio UV per una pittura precisa delle texture.
helpx_creative_field: ""
helpx_description: Painter > Interface > Viewport > 2D view
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Vista 2D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '285'
ht-degree: 0%

---


# Vista 2D

![](../../assets/2d-view.jpg){width="450px"}

La vista 2D mostra le Isole UV della trama del [set di texture](../texture-set/texture-set.md) attualmente selezionato. Consente di visualizzare le texture della pila di livelli ma anche di dipingere sulle Isole UV della trama.

## Modalità di visualizzazione

![](../../assets/display-mode-1.png)

In alto a destra nella finestra della vista si trova il menu a discesa della modalità di visualizzazione. Questo controllo consente di modificare le informazioni che devono essere visibili nella finestra della vista. Consente di visualizzare singoli canali, mappe mesh o il risultato finale del materiale con illuminazione.

## Informazioni asse

![](../../assets/2d-axis.png)

In basso a destra nella finestra della vista si trova **Informazioni asse**, che indica la direzione degli assi bidimensionali. Nel caso in cui la vista 2D gli assi sono U e V.

## Informazioni sulle porzioni UV

![](../../assets/2d-view-button.png)

Accanto alla **Modalità di visualizzazione** è disponibile il pulsante **Informazioni sull&#39;elemento UV** che consente di mostrare/nascondere informazioni relative all&#39;elemento UV Tiles. Questo pulsante non è visibile con i progetti normali.

## Flusso di lavoro progetto

A seconda del flusso di lavoro definito durante la creazione di un progetto, la vista 2D può essere visualizzata e comportarsi in modo diverso:

| *Flusso di lavoro progetto* | *Comportamenti* |
| --- | --- |
| **Progetto regolare** | Con il progetto normale, è possibile colorare solo l&#39;UV con l&#39;intervallo UV [0-1]. Tutto ciò che si trova al di fuori di questo intervallo sarà visibile, ma non sarà interattivo.In questo esempio è possibile colorare solo le Isole UV a sinistra (con lo sfondo grigio chiaro dietro). <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/2d-view-range-regular.jpg" width="500px"/></div> |
| **Progetto porzione UV** | Con il progetto Piastrella UV, ogni intervallo UV è un nuovo set di texture, che può essere dipinto su. Viene visualizzata la vista 2D e una griglia per vedere meglio come sono organizzate le singole porzioni. A ogni riquadro verrà assegnato un numero UDIM. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/2d-view-range-uvtiles.jpg" width="500px"/></div> |
