---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/project-resources.html"
breadcrumb-title: ''
description: Accedi alle risorse del progetto e alla documentazione tecnica di Substance 3D Painter per migliorare il tuo flusso di lavoro e la risoluzione dei problemi.
helpx_creative_field: ""
helpx_description: Substance 3D Painter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Risorse progetto
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---


# Risorse e impostazioni del progetto

La gestione delle risorse del progetto può contribuire a gettare buone basi per le prestazioni del progetto in Painter.

+++Riduci mappa con baking
A volte non tutte le mappe con baking devono avere risoluzioni 2k o 4k. Non esitate a eseguire i baking un batch a 2k, quindi ripetete l&#39;operazione a una risoluzione inferiore per vedere se c&#39;è una differenza visiva.

+++

+++Gestire le bitmap importate
Le immagini importate possono influire notevolmente sulle prestazioni, quindi è importante prestare attenzione a ciò che viene importato. Se i set di texture sono impostati su 2k e non verranno esportati ad una risoluzione più elevata, l’utilizzo di un’immagine 8k non avrà alcun impatto positivo: la qualità sarà limitata a 2k, poiché si tratta della risoluzione del set di texture.

Anche il formato è importante: EXR, HDR e persino PNG sono molto più pesanti di un JPG-e non tutte le immagini possono richiedere il livello di qualità di un EXR (ad esempio, come Colore di base rispetto ai dettagli del Height).

+++

+++Regolare le impostazioni dello shader
La qualità dello Specular su Ultra fornisce risultati più precisi, ma l&#39;impostazione è costosa. Più effetti sono attivati contemporaneamente nello shader, più pesante è il calcolo. Se possibile, dividete i materiali complessi in un altro insieme di texture con uno shader separato. Se è abilitato lo spostamento, prestare attenzione al parametro di tassellatura.

+++

+++Opzioni di regolazione dei file
Utilizza <b>File > Salva > Salva e riduci file</b> <b>dimensioni </b>per scaricare i dati non necessari e utilizzare <b>Rimuovi risorse inutilizzate</b> per eliminare i file importati nel progetto che non vengono utilizzati in alcun punto del progetto.

+++
