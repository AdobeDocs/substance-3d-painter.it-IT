---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/rendering-issues/broken-viewport-ubuntu.html"
breadcrumb-title: ''
description: Scoprite come correggere i problemi di viewport interrotti o non reattivi su Ubuntu in Substance 3D Painter per il corretto rendering 3D.
helpx_creative_field: ""
helpx_description: Viewport appears broken or unresponsive on Ubuntu
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Il riquadro di visualizzazione appare interrotto o non risponde su Ubuntu
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 0%

---


# Il riquadro di visualizzazione appare interrotto o non risponde su Ubuntu

Quando si esegue Painter da Steam su Ubuntu a partire dalla versione 11.1, la finestra della vista può apparire interrotta o non risponde.

Ciò è dovuto al fatto che Painter non inizia con la GPU appropriata assegnata. Su Ubuntu è possibile selezionare la GPU integrata invece di quella discreta. Painter eredita questa configurazione tramite Steam, che può causare problemi.

Esistono alcune soluzioni:

1. Esegui Steam da un Terminale. Questo forzerà un contesto diverso e dovrebbe far funzionare Steam e Painter sulla GPU giusta.
1. Modifica la scelta rapida da tastiera Steam per disabilitare l&#39;impostazione <b>Esegui utilizzando una scheda grafica dedicata</b>. Quindi esegui Steam come al solito.

Per ulteriori informazioni, vedere [questo problema github](https://github.com/ValveSoftware/steam-for-linux/issues/9940).
