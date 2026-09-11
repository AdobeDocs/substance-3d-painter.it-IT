---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/workflow-issues/shelf-issues/font-import.html"
breadcrumb-title: ''
description: Scoprite come correggere i problemi di importazione dei file dei font in Substance 3D Painter per importare e utilizzare correttamente le risorse dei font.
helpx_creative_field: ""
helpx_description: Substance 3D Painter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impossibile importare il file dei font
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Impossibile importare il file dei font

Con l&#39;introduzione della [risorsa di testo](../../../painting/text-resource.md), i file dei font vengono raccolti automaticamente all&#39;avvio. I file dei font possono anche essere importati manualmente.

In questi casi possono comparire alcuni messaggi di errore:

* Quando trascini un file nell’interfaccia di Painter.
* Quando Painter rileva i font sul disco (ricerca per indicizzazione della libreria).

## Come risolvere il problema

Se viene generato un messaggio di errore relativo a un <b>file danneggiato</b>, provare a trovare una versione alternativa del file e Painter potrebbe essere in grado di caricarlo. Sono supportati solo i formati <b>.ttf</b> e <b>.otf</b>.

Se viene generato un messaggio di errore relativo a un <b>problema di licenza</b>, il font non è semplicemente compatibile con Painter e non può essere importato.

### Panoramica sui messaggi

|  |  |
| --- | --- |
| <b>Messaggio di errore</b> | <b>Spiegazione</b> |
| Ci sono problemi nella libreria &quot;LIBRARYNAME&quot; che riguardano 4 file di font: FONTNAME, FONTNAME, FONTNAME,... | Questo messaggio contiene un breve elenco di nomi di file di font che sono stati identificati e che non possono essere importati in Painter. Questi file verranno ignorati e non verranno visualizzati nella finestra Risorse. |
| Problemi di font trovati. Per i dettagli, visitare il sito https://... | Messaggio generico che indica che è stato rilevato un problema con i font. |
| Impossibile importare FONTNAME a causa delle restrizioni di licenza. Per i dettagli, visitare il sito https://... | Per poterli utilizzare, Painter deve essere in grado di incorporare i font nel file di progetto. I font non consentiti (specificati nei metadati) non possono quindi essere importati. |
| Impossibile importare FONTNAME perché il file è danneggiato o un tipo non supportato. Per i dettagli, visitare il sito https://... | Painter non è in grado di leggere il file di font fornito. |
