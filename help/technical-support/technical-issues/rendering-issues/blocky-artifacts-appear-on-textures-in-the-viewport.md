---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/rendering-issues/blocky-artifacts-appear-on-textures-in-the-viewport.html"
breadcrumb-title: ''
description: Scopri come correggere gli artefatti a blocchi che appaiono sulla texture nella finestra della vista di Substance 3D Painter per una qualità visiva pulita.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Rendering Issues > Blocky artifacts appear on textures in the viewport
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Gli artefatti a blocchi vengono visualizzati sulle texture nella finestra della vista
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---


# Gli artefatti a blocchi vengono visualizzati sulle texture nella finestra della vista

A partire dalla versione 2018.3.0, nella finestra della vista possono essere visualizzati i seguenti tipi di artefatti:

![](../../../assets/viewport-artifacts.jpg){width="400px"}

Questi artefatti sono relativi a problemi con i driver GPU Nvidia.\
Per evitare gli artefatti, è necessario disattivare il supporto hardware Texture virtuali sparse.

I **driver 440.97** GeForce hanno ora **risolto il problema**. Si consiglia di eseguire l&#39;aggiornamento a questi driver e di mantenere l&#39;SVT abilitato per ottenere buone prestazioni.

Nuovi driver disponibili sul sito Web Nvidia: <https://www.nvidia.com/Download/index.aspx>

## Disabilitazione dell&#39;accelerazione hardware delle texture virtuali sparse

### 1 - Avviate Substance 3D Painter e aprite le impostazioni

![](../../../assets/settings-34.png)

Apri le Impostazioni principali da Modifica > Impostazioni.

### 2 - Trovate la sezione &quot;Texture virtuali sparse&quot;

![](../../../assets/svt-subsection.png)

Nella sezione &quot;Generale&quot;, scorri verso il basso e trova la sottosezione denominata &quot;Texture virtuali sparse&quot;

### 3 - Deselezionare l’impostazione

![](../../../assets/uncheck-hardware.png)

Deselezionare l&#39;impostazione &quot;Accelerazione supporto hardware&quot; per disattivarla.

### 4 - Convalidare e riavviare Substance 3D Painter

![](../../../assets/validate-1.png)

Per convalidare la modifica, fare clic sul pulsante &quot;OK&quot;.

![](../../../assets/restart-3.png)

Riavviate Substance 3D Painter facendo clic sul pulsante &quot;Sì&quot; per applicare la modifica.
