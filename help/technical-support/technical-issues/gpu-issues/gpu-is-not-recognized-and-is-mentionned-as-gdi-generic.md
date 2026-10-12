---
breadcrumb-title: ""
description: Scopri come correggere i problemi di riconoscimento della GPU che vengono visualizzati come generici GDI in Substance 3D Painter per una corretta accelerazione GPU.
title: La GPU non è riconosciuta ed è indicata come GDI Generico
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '134'
ht-degree: 0%
---

# La GPU non è riconosciuta ed è indicata come GDI Generico

Questo problema è un po’ complicato da monitorare e può essere causato da più sorgenti:

* Se utilizzi un computer con Nvidia Optimus, consulta il seguente collegamento: [La GPU non è riconosciuta](gpu-is-not-recognized.md)
* Verifica che il monitor sia collegato alla GPU principale (e che su Windows questo monitor sia impostato come display principale)
* Verificare che la profondità di bit dei colori del display principale sia impostata su 32 bit
* Se i problemi persistono, prova a reinstallare in modo pulito i driver della GPU (disinstallare completamente l&#39;applicazione pulendo le parti rimaste nel registro di Windows).
