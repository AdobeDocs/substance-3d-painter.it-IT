---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/pipeline-and-integration/installation-and-preferences/automated-installation.html"
breadcrumb-title: ''
description: Scopri come automatizzare l’installazione di Substance 3D Painter per i flussi di lavoro di distribuzione aziendale e integrazione delle pipeline.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Installation and preferences > Automated installation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Installazione automatica
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---


# Installazione automatica

Quando si utilizza il programma di installazione autonomo di Substance 3D, è possibile installare l&#39;applicazione in modalità non presidiata per semplificare la distribuzione.

Stiamo utilizzando **InnoSetup** per generare il programma di installazione. L&#39;intero set di parametri utilizzabili con il programma di installazione è [disponibile qui](http://www.jrsoftware.org/ishelp/index.php?topic=setupcmdline).

## Installazione in modalità non interattiva tramite la riga di comando

Il flag da utilizzare per eseguire un&#39;installazione invisibile è **/SILENT**. È inoltre possibile utilizzare il flag **/NCRC** per ignorare il CRC (verifica) del pacchetto per velocizzare il processo.

Esempio:

```
SubstancePainter_Installer.exe /NCRC /SILENT /DIR="C:InstallationFolder"
```


>[!NOTE]
>
> Il percorso di installazione deve utilizzare un singolo carattere barra rovesciata per separare le cartelle, altrimenti il programma di installazione non riconoscerà il percorso.
