---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/tool-list/eraser.html"
breadcrumb-title: ''
description: Utilizza lo strumento Gomma di Substance 3D Painter per rimuovere pittura e texture dai modelli 3D con controllo di precisione.
helpx_creative_field: ""
helpx_description: Painter > Painting > Tool list > Eraser
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Gomma
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 1%

---


# Gomma

La Gomma è uno strumento pittura che cancella/nasconde ciò che è stato precedentemente disegnato da altri strumenti. Questo strumento agisce solo su un livello alla volta.

La Gomma condivide parametri e comportamenti comuni con lo strumento Pittura. Per ulteriori informazioni sui controlli pennello, alfa e stencil, vedere la [pagina dello strumento Pittura](paint-brush.md).

>[!NOTE]
>
> Tecnicamente, **la gomma non rimuove effettivamente le informazioni**. È sufficiente impostare nuovamente il livello alfa su zero per cancellare/nascondere le informazioni di pittura precedenti. Ciò significa che:
> 
> * Eventuali pennellate precedenti colorate vengono comunque calcolate quando un progetto viene riaperto prima che vengano applicate le pennellate con la gomma.
> * Un filtro Substance può recuperare le informazioni sulla pittura se ignora le informazioni alfa
> 
> Ecco perché a volte si consiglia di **eliminare un livello e ricrearlo**, invece di utilizzare la gomma, in quanto può migliorare le prestazioni.

## Materiale

Quando si cancellano le informazioni, è possibile agire solo su canali specifici.

>[!NOTE]
>
> A differenza dello strumento Pittura, la Gomma consente solo di definire i canali interessati. Non è possibile caricare una risorsa dallo scaffale per influire su ciascun canale.

* Se tutti i canali sono attivati, la gomma rimuoverà le informazioni all&#39;interno di tutti i canali:

  ![](../../assets/eraser-all-channels-selection.png)

  ![](../../assets/erase-all-channel-optim.gif){width="325px"}
* Se sono selezionati canali specifici, la gomma rimuoverà le informazioni solo da tali canali:

  ![](../../assets/eraser-one-channel-selection.png)

  ![](../../assets/erase-one-channel-optim.gif){width="325px"}
