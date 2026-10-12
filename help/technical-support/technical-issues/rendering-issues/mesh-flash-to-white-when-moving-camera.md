---
breadcrumb-title: ""
description: Scoprite come correggere il lampeggiamento della trama in bianco quando si sposta la videocamera nella finestra della vista di Substance 3D Painter per un rendering stabile.
title: Trasformare il flash in bianco quando si sposta la fotocamera
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '140'
ht-degree: 0%
---

# Trasformare il flash in bianco quando si sposta la fotocamera

![](../../../assets/white-flash-svt-optim.gif){width="300px"}

Con i vecchi progetti, lo spostamento all’interno della videocamera nella finestra della vista può mostrare brevemente flash bianchi generati da texture bianca/vuota. Questo perché il sistema [Sparse Virtual Textures](https://substance3d.adobe.com/display/DRAFTPAINTER/Sparse+Virtual+Textures) (SVT) si basa su specifiche configurazioni di shader non utilizzate dagli shader meno recenti.

Per eliminare il flash bianco è sufficiente **aggiornare** lo **shader del progetto**:

* Per **shader predefiniti**: seguire la procedura dettagliata dalla pagina [Aggiornamento di uno shader](../../../interface/shader-settings/updating-a-shader.md).
* Per **shader personalizzati**: esaminare i messaggi di errore nel registro e nella pagina [API shader](https://helpx.adobe.com/it/substance-3d/unlisted/documentation/spdoc/custom-shader-api-89686018.html).
