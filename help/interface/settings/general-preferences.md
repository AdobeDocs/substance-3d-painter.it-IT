---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/settings/general-preferences.html"
breadcrumb-title: ''
description: Scopri come configurare le preferenze generali in Substance 3D Painter per personalizzare il comportamento dell’applicazione e l’esperienza utente.
helpx_creative_field: ""
helpx_description: Painter > Interface > Settings > General preferences
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Preferenze generali
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '764'
ht-degree: 2%

---


# Preferenze generali

![](../../assets/settings-general_1.png)

In questa pagina vengono illustrate le impostazioni principali dell&#39;applicazione.

## Opzioni di interfaccia

![](../../assets/settings-interface.png)

| Impostazione | Descrizione |
| --- | --- |
| **Lingua** | Definire la lingua utilizzata dall&#39;interfaccia nell&#39;applicazione. Per rendere effettiva questa impostazione è necessario riavviare l&#39;applicazione.Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Impostazione predefinita (lingua di sistema)</strong>: recupera la lingua compatibile dal sistema operativo</li><li data-preserve-html="true"><strong>Inglese</strong></li><li data-preserve-html="true"><strong>Tedesco</strong></li><li data-preserve-html="true"><strong>Francese</strong></li><li data-preserve-html="true"><strong>Giapponese</strong></li><li data-preserve-html="true"><strong>Cinese</strong> (semplificato)</li></ul> |
| **Mostra helper tastiera** | Se attivata, visualizza le scelte rapide da tastiera in basso a sinistra delle finestre della vista quando si preme un tasto (ad esempio CTRL o MAIUSC). |
| **Mostra assi globali** | Se questa opzione è attivata, mostra l’asse del mondo in basso a destra nella vista 3D. |
| **Colore di sfondo** | Consente di scegliere i colori utilizzati come sfondo per le finestre delle viste. Sono disponibili due colori per creare una sfumatura. |
| **Visualizza solo il materiale selezionato durante il disegno** | Se questa opzione è attivata, nella vista 3D viene visualizzato solo il set di texture attualmente selezionato quando si disegna (nascondendo temporaneamente gli altri set di texture).  **Nota:** si consiglia di mantenere disattivata questa impostazione poiché una modifica rapida della visibilità nella finestra della vista può influire sulle prestazioni delle [texture virtuali sparse](../../features/sparse-virtual-textures.md). |
| **Ridimensionamento del riquadro di visualizzazione** | Consente di ridurre la risoluzione del viewport per schermi HDPI/Retina al fine di migliorare le prestazioni.Valore possibile:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Nessuno</strong>: nessun ridimensionamento, viewport è renderizzato alla risoluzione nativa dello schermo.</li><li data-preserve-html="true"><strong>Automatico</strong>: divide la risoluzione dello schermo per due (solo su schermi HDPI).</li></ul> |

## Opzioni stack di livelli

![](../../assets/settings-layerstack.png)

| Impostazione | Descrizione |
| --- | --- |
| **Scala UV predefinita per i materiali** | Definisce il valore predefinito di affiancatura/ripetizione per i livelli di riempimento e l’effetto di riempimento nella pila di livelli quando applicate i materiali. |
| **Usare miniature semplificate** | Se questa opzione è attivata, lo stack di livelli visualizzerà solo icone anziché miniature. L’uso delle icone migliora le prestazioni. Questa impostazione non si applica ai progetti che utilizzano il flusso di lavoro per porzioni UV, in quanto visualizzeranno sempre le icone. |

## Opzioni videocamera

![](../../assets/settings-camera.png)

| Impostazione | Descrizione |
| --- | --- |
| **Velocità di rotazione** | Moltiplicatore della velocità di rotazione predefinita della videocamera nelle finestre delle viste. |
| **Velocità zoom** | Moltiplicatore della velocità di zoom predefinita della videocamera nelle finestre.La direzione inversa consente di invertire la direzione dello zoom in base al movimento del mouse. |
| **Velocità ruota** | Moltiplicatore per la velocità di zoom della rotellina del mouse.La direzione inversa consente di invertire la direzione dello zoom in base al movimento della ruota. |

## Opzioni di cottura

![](../../assets/settings-baking.png)

| Impostazione | Descrizione |
| --- | --- |
| **Salvare i file di scena pre-elaborati** | Se questa opzione è attivata, le trame a elevato poli pre-elaborate utilizzate dai fornai verranno salvate sul disco per essere riutilizzate in futuro. Questa impostazione consente di eseguire nuovamente la cottura in forno più rapidamente. |
| **Abilita processo di baking dell&#39;anteprima dal vivo** | Se questa opzione è attivata, nella finestra della vista 3D e 2D viene visualizzata la texture del fornaio corrente calcolata sulla trama. |
| **Abilita Raytracing GPU** | Se questa opzione è attivata, i Baker proveranno a utilizzare la GPU per eseguire il ray tracing anziché la CPU. In generale, questa funzione consente ai panettieri di offrire prestazioni più rapide.Questa opzione può essere attivata solo su hardware compatibile. Per ulteriori dettagli, vedere [Requisiti di sistema](../../getting-started/system-requirements.md). |

## Opzioni di anteprima

![](../../assets/settings-preview.png)

| Impostazione | Descrizione |
| --- | --- |
| **Directory cache locale** | Definire la posizione secondaria in cui si trovano le miniature delle risorse quando vengono generate.Questa impostazione è utile per calcolare e memorizzare le miniature delle risorse quando un percorso di risorsa è di sola lettura (come in un percorso di rete con accesso in sola lettura). In questo modo si evita di ricalcolare le miniature a ogni avvio perché altrimenti non verrebbero salvate sul disco. |
| **Budget cache locale (in MB)** | Definire le dimensioni massime della cache locale. |
| **Shader di anteprime materiali** | Definite uno shader da utilizzare per generare le miniature dei materiali negli scaffali. Ciò risulta utile se le risorse utilizzano un flusso di lavoro diverso da quello predefinito. Per rendere effettiva questa impostazione, è necessario riavviare l&#39;applicazione. |

## File temporanei

![](../../assets/settings-temp-1.png)

| Impostazione | Descrizione |
| --- | --- |
| **Directory cache** | Definisce la posizione in cui vengono scritti i file temporanei. Questo include la cache [Sparse Virtual Textures](../../features/sparse-virtual-textures.md). Questa impostazione può essere sostituita da [variabili di ambiente](../../pipeline-and-integration/configuration/environment-variables.md). |

## Texture virtuali sparse

![](../../assets/settings-sparse.png)

| Impostazione | Descrizione |
| --- | --- |
| **Accelerazione supporto hardware** | Se questa opzione è attivata, l’applicazione proverà a utilizzare le texture sparse con la GPU. Per ulteriori informazioni, vedere la pagina [Texture virtuali sparse](../../features/sparse-virtual-textures.md). Questa impostazione può essere sostituita da [variabili di ambiente](../../pipeline-and-integration/configuration/environment-variables.md). |

## Hardware Iray

![](../../assets/settings-iray.png)

In questa sezione sono elencati tutti i componenti hardware compatibili disponibili che possono essere utilizzati per il rendering con Iray.

L&#39;impostazione CPU è disponibile in tutti i computer. Se il computer dispone di una **GPU Nvidia** con una versione compatibile CUDA, verrà elencato qui.

>[!NOTE]
>
> Si consiglia di disattivare la CPU e mantenere abilitato solo l’hardware della GPU per garantire prestazioni di rendering ottimali. Se CPU e GPU sono attivate insieme, il tempo di rendering può aumentare.

## Privacy

![](../../assets/settings-privacy.png)

| Impostazione | Descrizione |
| --- | --- |
| **Invia automaticamente statistiche utilizzi** | Se l&#39;opzione è attivata, inviare informazioni anonime sulla configurazione hardware del computer insieme ad altri dati di utilizzo. Questi dati ci aiutano a sviluppare e migliorare il software. |
