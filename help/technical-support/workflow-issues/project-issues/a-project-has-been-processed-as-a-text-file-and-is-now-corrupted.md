---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/workflow-issues/project-issues/a-project-has-been-processed-as-a-text-file-and-is-now-corrupted.html"
breadcrumb-title: ''
description: Scopri come recuperare i file di progetto di Substance 3D Painter danneggiati che sono stati elaborati come file di testo.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Project Issues > Corrupted project file
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: File di progetto danneggiato
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '119'
ht-degree: 0%

---


# Un progetto è stato elaborato come file di testo ed è ora danneggiato

A volte, durante il caricamento di un progetto, può verificarsi il seguente errore:

```
[Hdf5Archive] Archive 'project.spp' appears to have been processed as a text file and is irremediably corrupted. 

[Project management] The selected project 'project.spp' isn't valid!
```


Questo errore indica che il progetto è stato modificato all&#39;esterno di Substance 3D Painter e **non può essere riletto correttamente**.\
Ciò si verifica in genere quando un software per il controllo delle versioni (ad esempio **Perforce** ) ha elaborato il progetto Substance 3D Painter **come file di testo anziché come file binario**. L&#39;unica soluzione consiste nell&#39;aggiungere una nuova regola/eccezione al software di controllo delle versioni per forzare l&#39;elaborazione di **file spp come file binari**. Per ulteriori informazioni con **Perforce**, consulta la documentazione dedicata: <https://www.perforce.com/perforce/r16.1/manuals/cmdref/p4_typemap.html>
