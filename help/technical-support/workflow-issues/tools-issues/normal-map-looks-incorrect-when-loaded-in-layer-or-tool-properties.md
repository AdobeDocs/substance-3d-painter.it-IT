---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/workflow-issues/tools-issues/normal-map-looks-incorrect-when-loaded-in-layer-or-tool-properties.html"
breadcrumb-title: ''
description: Scoprite come correggere i normali problemi di visualizzazione delle mappe nel livello di Substance 3D Painter e le proprietà degli strumenti per dettagli accurati della superficie.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Tools Issues > Normal map looks incorrect when loaded in layer or tool properties
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: La mappa normale non viene visualizzata correttamente quando viene caricata nelle proprietà del livello o dello strumento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 0%

---


# La mappa normale non viene visualizzata correttamente quando viene caricata nelle proprietà del livello o dello strumento

Quando si carica una normale nello strumento corrente del livello di riempimento, questa può apparire errata se è una mappa normale OpenGL.\
Il motivo è piuttosto semplice: il motore di Substance 3D Painter presuppone che la mappa normale caricata sia DirectX per impostazione predefinita.

Questo comportamento può essere facilmente modificato facendo clic sulla piccola freccia accanto al materiale Substance o al canale dedicato:

![](../../../assets/channel-format-override.png)
