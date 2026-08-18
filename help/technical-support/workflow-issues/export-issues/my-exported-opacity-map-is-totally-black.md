---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/workflow-issues/export-issues/my-exported-opacity-map-is-totally-black.html"
breadcrumb-title: ''
description: Scopri come correggere le mappe di opacità esportate che appaiono completamente nere in Substance 3D Painter per una corretta esportazione della trasparenza.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Export Issues > My exported opacity map is totally black
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: La mappa di opacità esportata è completamente nera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '117'
ht-degree: 0%

---


# La mappa di opacità esportata è completamente nera

Quando create un nuovo progetto, il colore predefinito viene dallo shader e non dalle texture. Di conseguenza, quando esportate tutte le parti che non avete colorato, saranno nere con un valore alfa impostato su 0 (poiché su queste parti non esistono dati).

Il modo più semplice per risolvere questo problema è mettere un livello di riempimento nella parte inferiore della pila di livelli: riempirà tutti gli UV con un colore predefinito, che è identico al colore predefinito dello shader.
