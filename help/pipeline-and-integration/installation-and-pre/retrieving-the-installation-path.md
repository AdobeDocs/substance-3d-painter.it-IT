---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/pipeline-and-integration/installation-and-preferences/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: Scopri come recuperare il percorso di installazione per Substance 3D Painter per scopi di scripting e integrazione della pipeline.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Installation and preferences > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Recupero del percorso di installazione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 22871eab2f25d09bd82f1292d8b3e5f8c4f1c2cf
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 5%

---


# Recupero del percorso di installazione

Questa pagina raggruppa le informazioni sui modi per recuperare il percorso di installazione dell&#39;applicazione a seconda della versione e della piattaforma.

## Windows

### Creative Cloud desktop

1. Apri l&#39;editor del Registro di sistema di Windows (**regedit**).
1. Accedi alla chiave del Registro di sistema: **&#x200B; HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App Percorsi\**
1. Apri la sottochiave **Adobe Substance 3D Painter.exe**
1. Il valore della chiave contiene il percorso del file eseguibile dell&#39;applicazione in cui è installato

>[!NOTE]
>
> Questa chiave del Registro di sistema è disponibile solo dalla versione 7.2.\
>  Per le versioni precedenti, il percorso di installazione può essere recuperato dalle associazioni di file in **HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts**.

### Substance 3D autonomo

1. Apri l&#39;editor del Registro di sistema di Windows (**regedit**).
1. Accedi alla chiave del Registro di sistema: **HKEY\_LOCAL\_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**
1. Trova la sottochiave corrispondente all’AppID della versione dell’applicazione (vedi tabella seguente)
1. Il valore della chiave contiene il percorso di installazione dell&#39;applicazione

| Versione | AppId |
| --- | --- |
| **Versione 1.x** | `{410F5B6E-A29C-4F43-9DE3-44A1357D6AF5}` |
| **Versione 2.x** | `{f42b7a996fa1d13a1d0a2e33eea2c0800bb5d1b8}` |
| Da **3.x (2017.x) a 7.1** | `{33C3E9E2-0675-4196-9019-28AB9C5E9BB0}` |
| **7.2 o versione successiva** | `{2a8bbb68-725b-477c-9194-60efc5ece348}` |

### Vapore

L&#39;applicazione è installata nella sottocartella **steamapps/common/** della cartella di installazione di Steam.

## Mac

In Mac l’applicazione viene installata nei seguenti casi:

| Versione | Tracciato |
| --- | --- |
| **7.2 o versione successiva** | **/Applicazioni/Adobe Substance 3D Painter.app** |
| **Precedente** | **/Applicazioni/Substance Painter.app** |

## Linux

Su Linux il pacchetto rpm è installato nel seguente percorso:

| Versione | Tracciato |
| --- | --- |
| **7.2 o versione successiva** | **/opt/Adobe/Adobe\_Substance\_3D\_Painter** |
| **Precedente** | **/opt/Allegorithmic/Substance\_Painter** |
