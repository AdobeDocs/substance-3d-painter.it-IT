---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/gpu-issues/multi-bi-gpu.html"
breadcrumb-title: ''
description: Scopri come configurare Substance 3D Painter per sistemi con più GPU e due GPU per ottimizzare le prestazioni di rendering.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > GPU Issues > MultiBi-GPU
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: MultiBi-GPU
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '93'
ht-degree: 0%

---


# Multi/Bi-GPU

Alcune configurazioni GPU e/o modelli GPU non sono compatibili con Substance 3D Painter e causeranno instabilità e arresti anomali. Di seguito è riportato un elenco delle configurazioni incompatibili:

| ***Configurazione*** | ***Soluzione*** |
| --- | --- |
| **Nvidia SLI/AMD Crossfire** (bridge di schede grafiche) | Disattivate SLI o il fuoco incrociato nelle impostazioni del driver GPU. |
| **Bi-GPU** (due chipset GPU su una scheda grafica) | Disattivate l&#39;uso dei due chipset GPU nelle impostazioni dei driver per un solo chipset. |
