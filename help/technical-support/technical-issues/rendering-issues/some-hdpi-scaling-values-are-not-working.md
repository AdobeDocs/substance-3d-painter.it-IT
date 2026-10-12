---
breadcrumb-title: ""
description: Scoprite come correggere i problemi relativi al valore di ridimensionamento HDPI in Substance 3D Painter per un corretto supporto dello schermo ad alta risoluzione.
title: Alcuni valori di ridimensionamento HDPI non funzionano
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
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
