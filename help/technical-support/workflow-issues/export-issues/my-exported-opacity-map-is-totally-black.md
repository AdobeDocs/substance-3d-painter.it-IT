---
breadcrumb-title: ""
description: Scopri come correggere le mappe di opacità esportate che appaiono completamente nere in Substance 3D Painter per una corretta esportazione della trasparenza.
title: La mappa di opacità esportata è completamente nera
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '117'
ht-degree: 0%
---

# La mappa di opacità esportata è completamente nera

Quando create un nuovo progetto, il colore predefinito viene dallo shader e non dalle texture. Di conseguenza, quando si esportano tutte le parti che non sono state pitture, queste diventeranno nere con un valore alfa impostato su 0 (poiché su queste parti non esistono dati).

Il modo più semplice per correggere questo problema è mettere un livello di riempimento nella parte inferiore della Pila livelli: riempirà tutti gli UV con un colore predefinito, che è identico al colore predefinito dello shader.
