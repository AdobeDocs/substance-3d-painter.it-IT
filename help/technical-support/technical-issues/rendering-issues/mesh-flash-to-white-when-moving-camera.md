---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/rendering-issues/mesh-flash-to-white-when-moving-camera.html"
breadcrumb-title: ''
description: Scoprite come correggere il lampeggiamento della trama in bianco quando si sposta la videocamera nella finestra della vista di Substance 3D Painter per un rendering stabile.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Rendering Issues > Mesh flash to white when moving camera
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Trasformare il flash in bianco quando si sposta la fotocamera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '140'
ht-degree: 0%

---


# Trasformare il flash in bianco quando si sposta la fotocamera

![](../../../assets/white-flash-svt-optim.gif){width="300px"}

Con i vecchi progetti, lo spostamento all’interno della videocamera nella finestra della vista può mostrare brevemente flash bianchi generati da texture bianca/vuota. Questo perché il sistema [Sparse Virtual Textures](https://substance3d.adobe.com/display/DRAFTPAINTER/Sparse+Virtual+Textures) (SVT) si basa su specifiche configurazioni dello shader non utilizzate dagli shader meno recenti.

Per eliminare il flash bianco è sufficiente **aggiornare** lo **shader del progetto**:

* Per **shader predefiniti**: seguire la procedura dettagliata dalla pagina [Aggiornamento di uno shader](../../../interface/shader-settings/updating-a-shader.md).
* Per **shader personalizzati**: esaminare i messaggi di errore nel registro e nella pagina [API shader](https://helpx.adobe.com/it/substance-3d/unlisted/documentation/spdoc/custom-shader-api-89686018.html).
