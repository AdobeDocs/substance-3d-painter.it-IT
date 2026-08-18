---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/workflow-issues/project-issues/preserve-brush-strokes-setting-stays-disabled.html"
breadcrumb-title: ''
description: Scoprite come correggere l’impostazione Mantieni tratti pennello che rimane disattivata in Substance 3D Painter per mantenere correttamente i tratti del pennello.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Project Issues > Preserve brush strokes setting stays disabled
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: L’impostazione Mantieni tratti pennello rimane disattivata
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---


# L’impostazione Mantieni tratti pennello rimane disattivata

A causa di uno sfortunato bug introdotto in Substance 3D Painter 1.5 (parzialmente risolto nella versione 1.7) alcuni progetti hanno perso i metadati relativi alla trama. Questo bug rende pertanto disattivata l’impostazione &quot;Mantieni posizioni dei tratti sulla trama&quot; nella finestra [Configurazione del progetto](../../../interface/project-configuration.md).

Per risolvere il problema, è necessario seguire alcuni passaggi specifici:

* Apri il progetto con il problema in Substance 3D Painter 1.7 o versione successiva
* Seleziona Modifica > Configurazione progetto.
* Seleziona e reimporta la trama originale utilizzata nel progetto corrente (non la versione aggiornata)
* Convalida e consenti a Substance 3D Painter di calcolare i livelli: se si tratta della stessa trama, non dovrebbe cambiare nulla
* Vai nuovamente a Modifica > Configurazione progetto
* L’opzione &quot;Mantieni posizioni tratti sulla trama&quot; ora dovrebbe essere nuovamente abilitata e ti consentirà di importare la nuova trama
