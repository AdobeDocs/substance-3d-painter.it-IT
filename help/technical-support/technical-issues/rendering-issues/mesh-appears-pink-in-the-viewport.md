---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/rendering-issues/mesh-appears-pink-in-the-viewport.html"
breadcrumb-title: ''
description: Scoprite come correggere l'aspetto della trama rosa nella finestra della vista di Substance 3D Painter per ripristinare il rendering corretto del materiale.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Rendering Issues > Mesh appears pink in the viewport
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: La trama appare rosa nella finestra della vista
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '125'
ht-degree: 0%

---


# La trama appare rosa nella finestra della vista

![](../../../assets/pink-mesh.jpg){width="400px"}

La trama può apparire **rosa** all&#39;interno della finestra della vista perché lo **shader** utilizzato per disegnarla **non viene più compilato** (come indicato dalla **finestra del registro** ). Ciò può essere causato da uno shader obsoleto che non supporta la versione più recente dell’API shader.

Ecco come risolvere il problema:

* Per **shader predefiniti**: seguire la procedura dettagliata dalla pagina [Aggiornamento di uno shader](../../../interface/shader-settings/updating-a-shader.md).
* Per **shader personalizzato**: esamina il messaggio di errore nella finestra del registro e la pagina [API shader](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/custom-shader-api-89686018.html).
