---
breadcrumb-title: ""
description: Scoprite come correggere i problemi di visualizzazione delle mappe normali nel livello di Substance 3D Painter e le proprietà dello strumento per dettagli accurati delle superfici.
title: L’aspetto della mappa normale non è corretto quando viene caricata nelle proprietà del livello o dello strumento
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 0%
---

# L’aspetto della mappa normale non è corretto quando viene caricata nelle proprietà del livello o dello strumento

Quando si carica una normale nello strumento corrente del livello di riempimento, questa può apparire errata se si tratta di una mappa normale OpenGL.\
Il motivo è piuttosto semplice: il motore di Substance 3D Painter presuppone che la mappa normale caricata sia di DirectX per impostazione predefinita.

Questo comportamento può essere facilmente modificato facendo clic sulla piccola freccia accanto al materiale Substance o al canale dedicato:

![](../../../assets/channel-format-override.png)
