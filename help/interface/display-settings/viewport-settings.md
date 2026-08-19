---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/display-settings/viewport-settings.html"
breadcrumb-title: ''
description: Scopri come configurare le impostazioni della finestra della vista in Substance 3D Painter per personalizzare le opzioni di visualizzazione e la qualità del rendering.
helpx_creative_field: ""
helpx_description: Painter > Interface > Display settings > Viewport settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni dell'area di visualizzazione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '734'
ht-degree: 2%

---


# Impostazioni dell&#39;area di visualizzazione

Questa sezione delle **Impostazioni di visualizzazione** controlla varie impostazioni relative alla visualizzazione della finestra della vista, quali il filtro delle texture e il wireframe della trama.

## Filtro Texture

![](../../assets/texture-filtering.png)

Il filtro anisotropo e il bias MipMap consentono di controllare la visualizzazione delle texture nella finestra della vista. Queste impostazioni non influiscono direttamente sulle texture e non verranno applicate al momento dell’esportazione, ma solo perfezionano il processo di rendering nella finestra della vista. L’impostazione Compensazione MipMap consente di forzare l’uso di texture molto nitide per pixel lontani o ad angoli obliqui, ma in alcuni casi può creare pattern Moiré o tremolii.

Le impostazioni predefinite compromettono la qualità e le prestazioni e devono essere modificate solo in caso di reale necessità.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Filtro Anisotropo** | Il filtro anisotropo migliora la qualità della texture quando la visualizzazione avviene ad angoli obliqui. Valori di alta qualità offrono un filtro migliore ma possono causare una perdita di prestazioni. Questa impostazione controlla la quantità di campioni per pixel (spp) utilizzati per il filtraggio:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Disabilitato</strong>: nessun filtro</li><li data-preserve-html="true"><strong>Bassa</strong> (2spp)</li><li data-preserve-html="true"><strong>Media</strong> (4spp): valore predefinito</li><li data-preserve-html="true"><strong>Alto</strong> (8spp)</li><li data-preserve-html="true"><strong>Molto alto</strong> (16spp)</li></ul> <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/quality-anisotropic-filtering.jpg"/></div> |
| **Distinzione MipMap** | Scostate il Livello mipmap di dettagli per migliorare la qualità della texture. I valori netti possono causare la perdita di prestazioni e texture scalettate.<ul data-preserve-html="true"><li data-preserve-html="true"><strong>0 - Soft</strong> (prestazioni leggere): valore predefinito</li><li data-preserve-html="true"><strong>1 - Medio morbido</strong></li><li data-preserve-html="true"><strong>2 - Nitido</strong></li><li data-preserve-html="true"><strong>3 - Molto Nitido</strong> (Prestazioni Intensive)</li></ul>(Da 0 a -3) |

## Telaio della fotocamera

![](../../assets/camera-frame.png)

Per ulteriori informazioni sulla gestione della fotocamera, vedere: [Gestione fotocamera](../viewport/camera-management.md)

## Visualizzazione degli strumenti

![](../../assets/viewport-tool.png)

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Nascondi stencil durante il disegno** | Quando si utilizza uno stencil (vedere le proprietà dello strumento di disegno), questa impostazione consente di nasconderlo temporaneamente quando si disegna sulla trama. |
| **Opacità visualizzazione stencil** | Controlla la visibilità dello stencil sul rendering della finestra della vista quando non si disegna. |
| **Canale di anteprima proiezione** | Controlla il canale del materiale da visualizzare quando si utilizza lo strumento di proiezione. |

## Wireframe trama

![](../../assets/viewport-mesh.png)

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Mostra wireframe trama** | Attivate o disattivate la visualizzazione del wireframe della trama nella finestra della vista. |
| **Colore Wireframe** | Controlla il colore usato per disegnare il wireframe della trama. |
| **Opacità Wireframe** | Controlla di quanto sarà visibile il wireframe quando verrà disegnato sopra la trama. |

## Visualizzazione dei canali

![](../../assets/viewport-channel.png)

>[!NOTE]
>
> Le impostazioni di visualizzazione dei canali sono disponibili solo quando si utilizza la modalità di visualizzazione **canale singolo**.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Visualizzazione solo senza illuminazione** | Quando si visualizza in modalità a canale singolo, l’attivazione di questa impostazione rimuove l’illuminazione e mostra il canale come colori piatti. Se è disattivata, verrà applicata un’ombreggiatura al bordo della trama. |
| **Scala valori HDR** | Quando si visualizza in modalità canale singolo una texture **HDR** (ad esempio il height), questa impostazione ridimensiona i valori totali. Questa funzione è utile per visualizzare i valori superiori a 1 o inferiori a -1. Il risultato è uguale a **Canale immerso per scala**.Con l’esempio seguente, il canale di height ha valori fino a 3. Tuttavia, per impostazione predefinita, non possono essere visualizzati a meno che non venga modificato il valore di scala: <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/scale-hdr.jpg"/></div> |
| **Usa colore +/- per valori HDR** | Questa impostazione consente di visualizzare più facilmente la texture HDR sostituendo i valori positivi del primo colore e i valori negativi del secondo colore. I valori neutri (0) sono neri.Esempio: <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r3-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/colored-hdr.jpg"/></div> |
| **Canali di colore** | Modificate la modalità di visualizzazione della finestra della vista in modo da visualizzare solo singolarmente il componente R, G, B o Alpha del canale corrente. Questa impostazione non è disponibile nella modalità di visualizzazione dei materiali. Quando questa opzione è attivata, il nome del canale di colore selezionato viene visualizzato nella finestra della vista:  <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r4-column-c1_image" src="../../assets/color-channel.png"/></div>  Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>RGBA</strong> (impostazione predefinita): nei canali colore, visualizza tutti i componenti con la trasparenza.</li><li data-preserve-html="true"><strong>Scala di grigi+Alpha</strong> (impostazione predefinita): nel canale Scala di grigi, visualizza i valori in scala di grigi con la trasparenza.</li><li data-preserve-html="true"><strong>R</strong>: nei canali dei colori, viene visualizzato solo il componente rosso.</li><li data-preserve-html="true"><strong>G</strong>: nei canali di colore viene visualizzato solo il componente verde.</li><li data-preserve-html="true"><strong>B</strong>: nei canali colore viene visualizzato solo il componente blu.</li><li data-preserve-html="true"><strong>Alpha</strong>: su qualsiasi canale, viene visualizzata solo la trasparenza della texture.</li></ul> |

## Griglia

![](../../assets/display-settings-grid.png)

Le impostazioni della griglia consentono di visualizzare e controllare il disegno di una griglia 3D all&#39;interno della finestra della vista 3D.

Le divisioni della griglia sono automatiche in base al livello di zoom e angolo della videocamera corrente. L&#39;unità della griglia corrente viene visualizzata in basso a sinistra nella finestra della vista.

| Impostazione | Descrizione |
| --- | --- |
| **Mostra griglia** | Se attivata, rendete visibile la griglia nella finestra della vista 3D. |
| **Asse** | Definire lungo quale asse la griglia è visibile nella finestra della vista. Il valore predefinito è Y poiché si tratta dell&#39;asse superiore dell&#39;applicazione. |
| **Colore griglia** | Colore della griglia quando viene disegnata nella finestra della vista. |
| **Opacità griglia** | Opacità della griglia nella finestra della vista. |
