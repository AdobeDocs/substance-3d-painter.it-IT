---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/gpu-issues/gpu-is-not-recognized.html"
breadcrumb-title: ''
description: Scoprite come correggere i problemi di riconoscimento GPU in Substance 3D Painter per consentire prestazioni e accelerazione hardware corrette.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > GPU Issues > GPU is not recognized
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: GPU non riconosciuta
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '79'
ht-degree: 0%

---


# GPU non riconosciuta

![](../../../assets/not-recognized-gpu.png){width="500px"}

Alcuni utenti di **NVIDIA Optimus** possono riscontrare problemi nell’esecuzione di Substance 3D Painter con la GPU corretta. Una soluzione alternativa consiste nell’impostare le seguenti chiavi nel Registro di sistema di Windows su 0:

* HKEY\_LOCAL\_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows\RequireSignedAppInit
* HKEY\_LOCAL\_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows NT\CurrentVersion\Windows\RequireSignedAppInit
