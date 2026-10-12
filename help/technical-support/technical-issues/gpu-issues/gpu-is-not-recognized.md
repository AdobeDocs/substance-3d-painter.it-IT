---
breadcrumb-title: ""
description: Scoprite come correggere i problemi di riconoscimento GPU in Substance 3D Painter per consentire prestazioni e accelerazione hardware corrette.
title: GPU non riconosciuta
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '79'
ht-degree: 0%
---

# GPU non riconosciuta

![](../../../assets/not-recognized-gpu.png){width="500px"}

Alcuni utenti di **NVIDIA Optimus** possono riscontrare problemi nell’esecuzione di Substance 3D Painter con la GPU corretta. Una soluzione alternativa consiste nell’impostare le seguenti chiavi nel Registro di sistema di Windows su 0:

* HKEY\_LOCAL\_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows\RequireSignedAppInit
* HKEY\_LOCAL\_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows NT\CurrentVersion\Windows\RequireSignedAppInit
