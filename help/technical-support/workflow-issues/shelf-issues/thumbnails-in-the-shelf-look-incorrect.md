---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/workflow-issues/shelf-issues/thumbnails-in-the-shelf-look-incorrect.html"
breadcrumb-title: ''
description: Scopri come correggere la visualizzazione errata delle miniature nello scaffale di Substance 3D Painter per garantire anteprime accurate delle risorse.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Shelf Issues > Thumbnails in the shelf look incorrect
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Le miniature sullo scaffale sembrano errate
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '131'
ht-degree: 0%

---


# Le miniature sullo scaffale sembrano errate

Se le miniature sullo scaffale sembrano essere diverse da quelle abituali, è possibile che il rendering delle anteprime venga eseguito con uno shader diverso.

| Miniature interrotte | Miniature normali |
| --- | --- |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../../assets/shelf-broken-preview.png"/></div> | <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../../assets/shelf-normal-preview.png" width="300px"/></div> |

## 1 - Aprire la finestra delle impostazioni principali

Vai a **Modifica** e fai clic su **Impostazioni**:

![](../../../assets/pref-menu.png)

## 2 - Rimuovere lo shader di anteprima Ripiano

Nella vista **Generale** scorrete verso il basso fino a visualizzare la sezione &quot;Opzioni anteprima&quot;.\
Fare clic sul pulsante **croce** davanti a &quot; **Shader di anteprime materiali** &quot; per rimuovere lo shader corrente specificato.

![](../../../assets/remove-preview-shader.png){width="450px"}

## 3 - Riavviare Substance 3D Painter

Per rigenerare le miniature e renderle visibili correttamente, è necessario riavviare Substance 3D Painter.
