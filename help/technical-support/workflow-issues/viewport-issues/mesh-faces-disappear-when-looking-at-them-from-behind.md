---
breadcrumb-title: ""
description: Scoprite come correggere le facce con trama che scompaiono quando vengono visualizzate da dietro nella finestra di visualizzazione di Substance 3D Painter per una corretta visibilità della trama.
title: Le facce della trama scompaiono guardandole da dietro
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '86'
ht-degree: 0%
---

# Le facce della trama scompaiono guardandole da dietro

Per impostazione predefinita, le trame nella finestra della vista potrebbero non visualizzare il retro dei poligoni della trama (superficie posteriore). Questo perché sono soppressi dallo shader attuale.

Per visualizzare il retro delle facce, è sufficiente modificare lo shader corrente in **pbr-metal-rough-alpha-test** nelle [impostazioni Shader](../../../interface/shader-settings/shader-settings.md).
