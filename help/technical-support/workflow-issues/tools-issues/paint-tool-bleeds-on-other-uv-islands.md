---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/workflow-issues/tools-issues/paint-tool-bleeds-on-other-uv-islands.html"
breadcrumb-title: ''
description: Scoprite come correggere la dispersione di colore tra le Isole UV in Substance 3D Painter per mantenere puliti i bordi della texture.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Tools Issues > Paint Tool bleeds on other UV islands
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Lo strumento Disegno smargina su altre Isole UV
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 0%

---


# Lo strumento Disegno smargina su altre Isole UV

Alcuni comportamenti predefiniti dello [strumento di pittura](../../../features/effects/paint.md) possono sembrare controintuitivi in alcune situazioni specifiche. Substance 3D Painter è un’applicazione che funziona principalmente in uno spazio 3D, e lo è anche per la pittura. L’impostazione predefinita del pennello artistico è quella di cercare di lavorare senza interruzioni sugli UV durante la pittura. Per questo motivo, quando si interagisce con la vista 2D, alcuni risultati possono apparire inaspettati.

Per evitare che altre Isole UV perdano colore quando colorate nella vista 2D, modificate semplicemente l&#39;impostazione **Allineamento** nei parametri dello strumento:

| *Modalità di allineamento* | *Anteprima* |
| --- | --- |
| **Contorna con tangente** | <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../../assets/paint-mode-tangent-optim.gif"/></div> |
| **UV** | <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../../assets/paint-mode-uv.gif" width="450px"/></div> |
