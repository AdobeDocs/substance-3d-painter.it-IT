---
breadcrumb-title: ""
description: Scopri come configurare Substance 3D Painter per sistemi con più GPU e due GPU per ottimizzare le prestazioni di rendering.
title: MultiBi-GPU
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
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
