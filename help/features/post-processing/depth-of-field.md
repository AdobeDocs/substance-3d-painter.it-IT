---
breadcrumb-title: ""
description: Scoprite come utilizzare la profondità della post-elaborazione sul campo in Substance 3D Painter per creare effetti di sfocatura di messa a fuoco della fotocamera realistici.
title: Profondità di campo
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '132'
ht-degree: 0%
---

# Profondità di campo

![](../../assets/dof-example.jpg)![](../../assets/dof.png)

La **Profondità del campo** (DOF) non ha parametri diretti. Se questa opzione è attivata, **sovrascriverà** il valore DOF da **Iray**.

Per controllare l&#39;aspetto del DOF nella finestra della vista, sono disponibili due impostazioni tramite la fotocamera:

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Distanza focale** | Definisce la distanza alla quale si trova il punto focale.  Questo punto viene utilizzato dall’effetto Profondità campo. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/focus-distance-optim.gif"/></div> **Nota:** la distanza focale può essere impostata automaticamente facendo clic su un punto della trama con il **tasto CTRL + pulsante centrale del mouse della scelta rapida da tastiera.** |
| **Apertura** | Definisce l’ampiezza della Profondità di Campo. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/dof-aperture-optim.gif"/></div> **Nota:** se Iray controlla questo parametro, modificandolo verrà riattivato un calcolo. |
