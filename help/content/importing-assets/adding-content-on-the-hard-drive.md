---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/content/importing-assets/adding-content-on-the-hard-drive.html"
breadcrumb-title: ''
description: Scoprite come aggiungere contenuto dal disco rigido a Substance 3D Painter per espandere la libreria di risorse con i file locali.
helpx_creative_field: ""
helpx_description: Painter > Content > Importing assets > Adding content on the hard drive
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Aggiunta di contenuto sul disco rigido
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '488'
ht-degree: 2%

---


# Aggiunta di contenuto sul disco rigido

È possibile aggiungere risorse alle librerie inserendo nuovi contenuti direttamente sul disco rigido nella posizione corretta.

Per impostazione predefinita, viene fornita una cartella predefinita per le risorse utente in cui è possibile aggiungere il nuovo contenuto tramite l’interfaccia dell’applicazione o rilasciandolo manualmente nel seguente percorso. Questa libreria predefinita viene utilizzata anche per la creazione di nuovi predefiniti quali pennelli, strumenti, materiali avanzati e così via. Per ulteriori informazioni, consultate la documentazione [Predefiniti](../../painting/presets/presets.md).

## Dove mettere le risorse?

Di seguito sono riportati i percorsi della libreria predefinita **Le tue risorse** in cui vengono creati i tuoi contenuti personalizzati per impostazione predefinita:

<table data-preserve-html="true" style="width: 100.0%;"><colgroup> <col style="width: 15.0%;"/> <col style="width: 15.0%;"/> <col style="width: 70.0%;"/> </colgroup><tbody><tr><th>Piattaforma</th><th>Versione</th><th>Tracciato</th></tr><tr><td rowspan="2"><strong>Windows</strong></td><td><strong>7.2</strong> o versioni successive</td><td colspan="1">C:\Users\username\Documents\Adobe\Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Precedente</td><td colspan="1">C:\Users\username\Documents\Allegorithmic\Substance Painter</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="1">/Utenti/nome utente/Documenti/Adobe/Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Precedente</td><td colspan="1">/Utenti/nomeutente/Documenti/Allegorithmic/Substance Painter</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="1">/home/nomeutente/Documenti/Adobe/Adobe Substance 3D Painter</td></tr><tr><td>Precedente</td><td colspan="1">/home/nomeutente/Documenti/Allegorithmic/Substance Painter</td></tr></tbody></table>

>[!WARNING]
>
> Le **risorse Starter** fornite con l&#39;applicazione si trovano nella cartella di installazione e vengono sostituite in ogni nuova versione. Si consiglia di non inserire contenuti personali in questo percorso, poiché verranno **cancellati con ogni aggiornamento** e potrebbero verificarsi problemi di autorizzazione in lettura/scrittura.\
> È preferibile utilizzare il percorso **Le tue risorse** o un altro percorso personalizzato. Per ulteriori informazioni su come aggiungere un percorso libreria personalizzato, vedere [Aggiunta di una nuova libreria](../../interface/assets/adding-a-new-library.md).

## Formati di file e utilizzi

Puoi importare diversi tipi di file nella libreria Substance 3D Painter. Inserirli nelle cartelle designate (ad esempio *alfa*, *colorluts*, *effetti*...) assegnerà un tipo di utilizzo alla risorsa, quindi è importante scegliere la cartella corretta quando si aggiunge nuovo contenuto. Si noti che se si aggiunge un percorso di libreria personalizzato, verranno automaticamente create le cartelle appropriate in tale percorso.

| *Formato file* | *Utilizzo* | *Cartella* |
| --- | --- | --- |
| **SBSAR** | Materiale di Substance | risorse / Materiali |
| **SBSAR** | Filtri | risorse/Effetti |
| **SBSAR** | Generatori | risorse / Generatori |
| **PNG, TGA, JPEG e così via** | TEXTURE o ALPHA | risorse/Texture **o** Scaffale/Alpha |
| **HDR, EXR** | Ambiente o Lut colori | risorse/ambienti **o** Shelf/Colorlut |
| **GLSL** | Shader | risorse/Shader |
| **SPPR** | Pennello predefinito | risorse / Predefiniti / Pennello |
| **SPPR** | Predefinito Particle | risorse / Predefinito / Particelle |
| **SPPR** | Predefinito materiale | risorse / Predefiniti / Materiali **o** risorse / Materiali |
| **SPPR** | Strumento predefinito | risorse / Predefinito / Strumenti |
| **SPSM** | Materiale avanzato | risorse/Smart-materials |
| **SPMSK** | Maschera intelligente | risorse/Maschere intelligenti |
| **SPEXP** | Esporta predefinito | Shelf/Export-presets |

>[!NOTE]
>
> A partire dalla versione 7.2.0, le cartelle e le categorie personalizzate possono essere utilizzate in una libreria. Saranno accessibili nella finestra Risorse tramite [Filtra per percorso](../../interface/assets/filter-by-path.md) o [Breadcrumbs](https://helpx.adobe.com/it/substance-3d/unlisted/documentation/spdoc/navigating-in-the-shelf-147095659.html).

>[!WARNING]
>
> I file **SBS** (non SBSAR) non possono essere utilizzati direttamente, devono essere esportati come SBSAR da Substance 3D Designer.
