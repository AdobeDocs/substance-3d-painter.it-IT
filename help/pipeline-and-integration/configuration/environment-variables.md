---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/pipeline-and-integration/configuration/environment-variables.html"
breadcrumb-title: ''
description: Scopri come utilizzare le variabili di ambiente in Substance 3D Painter per configurare il comportamento dell'applicazione e l'integrazione della pipeline.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Configuration > Environment variables
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Variabili di ambiente
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '513'
ht-degree: 3%

---


# Variabili di ambiente

Questa pagina elenca le variabili di ambiente che possono essere utilizzate per ignorare il comportamento predefinito dell&#39;applicazione.

| Variabile | Descrizione | Versione |
| --- | --- | --- |
| **SUBSTANCE\_PAINTER\_LICENSE** | Valore: percorso diretto a un file di licenza stesso.Consente di ignorare il percorso predefinito del file di licenza. Esempio: se il file di licenza si trova in **H:/allegorithmic/licenses/substance\_painter.key**, i dati della variabile devono essere **&quot;H:/allegorithmic/licenses/substance\_painter.key&quot;**.  **Nota:** utilizzare SUBSTANCE\_PAINTER\_2\_LICENSE per versioni precedenti a 3.x (2017.x). | <ol data-preserve-html="true"><li data-preserve-html="true">1</li></ol> |
| **ALLEGO\_LICENSE\_IDLE\_DELAY** | Valore: 7200Specifica il tempo in secondi prima di rilasciare una postazione di licenza in caso di configurazione multiutente. Il valore predefinito è 2 ore (7.200). | <ol data-preserve-html="true"><li data-preserve-html="true">1</li></ol> |
| **ALG\_PAINTER\_SKIP\_CHECK\_FOR\_UPDATES** | Valore : 0 o 1 (1 = Disattiva controllo aggiornamento)Consente di ignorare il controllo aggiornamento all&#39;avvio dell&#39;applicazione. Disattiva il pannello Novità. | <ol data-preserve-html="true"><li data-preserve-html="true">2.2</li></ol> |
| **SUBSTANCE\_PAINTER\_SVT\_HARDWARE\_ACCELERATION** | Valore: 0 o 1 (1 = Abilitato)Utilizza la funzione Sparse nella GPU. Se non supportata dalla GPU o dal sistema operativo, l&#39;impostazione verrà ignorata. Per informazioni sulle configurazioni hardware compatibili, consultare la documentazione: [Texture virtuali sparse](../../features/sparse-virtual-textures.md)Questa variabile sostituisce il parametro disponibile nella finestra [Impostazioni](../../interface/settings/settings.md). | <ol data-preserve-html="true"><li data-preserve-html="true">3</li></ol> |
| **SUBSTANCE\_PAINTER\_TEMP\_LOCATION** | Valore: percorso diretto a una cartellaDefinisce il percorso in cui Substance Painter deve scrivere i file temporanei, inclusa la cache SVT. Questa variabile sostituisce il parametro disponibile nella finestra [Impostazioni](../../interface/settings/settings.md). | <ol data-preserve-html="true"><li data-preserve-html="true">3</li></ol> |
| **SUBSTANCE\_PAINTER\_PREVIEWS\_MEMORY\_BUDGET** | Valore: 500Definisce la quantità di memoria (Ram) che l&#39;applicazione può utilizzare per caricare e memorizzare anteprime temporanee dalla finestra Risorse. Quando il limite del budget viene raggiunto, le anteprime precedenti vengono scaricate. Questo valore controlla solo la visualizzazione delle anteprime nella finestra Risorse.Il valore è definito in megabyte. Il valore predefinito è 500 MB. | <ol data-preserve-html="true"><li data-preserve-html="true">2</li></ol> |
| **SUBSTANCE\_PAINTER\_PLUGINS\_PATH** | Posizione dei plug-in Python aggiuntivi. | 6.1 |
| **PERCORSO PITTONE** | Moduli Python aggiuntivi da caricare con l’integrazione Python dell’applicazione. Per ulteriori informazioni, vedere [Caricamento di moduli Python esterni](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/loading-external-python-modules-205363420.html). | <ol data-preserve-html="true"><li data-preserve-html="true">1</li></ol> |
| **OCIO** | Percorso di un file **config.ocio** che verrà utilizzato per gestire le impostazioni di [Gestione colore](../../features/color-management/color-management.md) con OpenColorIO.  **Nota:** questa variabile di ambiente ha la priorità sulla variabile **PAINTER\_ACE\_CONFIG**. | <ol data-preserve-html="true"><li data-preserve-html="true">4</li></ol> |
| **PAINTER\_ACE\_CONFIG** | Percorso di un file json che verrà utilizzato per gestire le impostazioni di [Gestione colore](../../features/color-management/color-management.md) con Adobe. | <ol data-preserve-html="true"><li data-preserve-html="true">1</li></ol> |
| **SUBSTANCE\_DISABLE\_SPECIFIC\_FEATURES** | Disattiva diverse funzionalità all&#39;interno delle applicazioni:<ul data-preserve-html="true"><li data-preserve-html="true">Collegamenti a risorse esterne (Guida, pagine Web, esempi, ecc.)</li><li data-preserve-html="true">Disabilita controlli per aggiornamenti</li><li data-preserve-html="true">Disabilita l&#39;invio di statistiche di utilizzo</li><li data-preserve-html="true">Disabilita esportazione in Substance share</li><li data-preserve-html="true">Disattiva i pannelli Benvenuti e Novità</li></ul> | <ol data-preserve-html="true"><li data-preserve-html="true">1</li></ol> |
| **ALG\_PAINTER\_DEBUG\_FPS** | Visualizza nella finestra della vista un contatore che indica quanti fotogrammi al secondo vengono sottoposti a rendering dalla finestra della vista. | <ol data-preserve-html="true"><li data-preserve-html="true">1</li></ol> |
| **SUBSTANCE\_PAINTER\_VRAM\_BUDGET** | Specificate la quantità di memoria GPU utilizzabile da Painter. Definisce un budget globale in MB. Ad esempio, per definire un limite di 4 GB, utilizzare il valore 4000. Per eseguire la stessa azione è possibile utilizzare anche un argomento della riga di comando. Vedere [Righe di comando](command-lines.md). | <ol data-preserve-html="true"><li data-preserve-html="true">2.1</li></ol> |
