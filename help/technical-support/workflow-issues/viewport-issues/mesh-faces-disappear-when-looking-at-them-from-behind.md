---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/workflow-issues/viewport-issues/mesh-faces-disappear-when-looking-at-them-from-behind.html"
breadcrumb-title: ''
description: Scoprite come correggere le facce con trama che scompaiono quando vengono visualizzate da dietro nella finestra di visualizzazione di Substance 3D Painter per una corretta visibilità della trama.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Viewport Issues > Mesh faces disappear when looking at them from behind
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Le facce della trama scompaiono guardandole da dietro
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '86'
ht-degree: 0%

---


# Le facce della trama scompaiono guardandole da dietro

Per impostazione predefinita, le trame nella finestra della vista potrebbero non visualizzare il retro dei poligoni della trama (superficie posteriore). Questo perché vengono eliminati dallo shader corrente.

Per visualizzare il retro delle facce, è sufficiente modificare lo shader corrente in **pbr-metal-rough-alpha-test** nelle [impostazioni shader](../../../interface/shader-settings/shader-settings.md).
