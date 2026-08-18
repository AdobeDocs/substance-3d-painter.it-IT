---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/rendering-issues/some-hdpi-scaling-values-are-not-working.html"
breadcrumb-title: ''
description: Scoprite come correggere i problemi relativi al valore di ridimensionamento HDPI in Substance 3D Painter per un corretto supporto dello schermo ad alta risoluzione.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Rendering Issues > Some HDPI scaling values are not working
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Alcuni valori di ridimensionamento HDPI non funzionano
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Alcuni valori di ridimensionamento HDPI non funzionano

In Windows, alcuni valori di scala HDPI (utilizzati per ridimensionare l’interfaccia su monitor con risoluzioni elevate) potrebbero non funzionare correttamente.\
Questo perché il nostro framework di finestre (Qt) non li supporta. Non è possibile risolverlo finché non viene effettivamente gestito dai fornitori del framework stesso.

Ecco quindi il comportamento che potresti incontrare a seconda delle tue impostazioni:

* 120 DPI (**125%** ridimensionamento) - renderizzato come 96 DPI (**100%** ridimensionamento)
* 144 DPI (**150%** ridimensionamento) - renderizzato come 192 DPI (**200%** ridimensionamento)
* 168 DPI (**175%** ridimensionamento) - renderizzato come 192 DPI (**200%** ridimensionamento)

Per ulteriori dettagli, vedere: <https://bugreports.qt.io/browse/QTBUG-55654>
