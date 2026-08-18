---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/interface/display-settings/camera-settings.html"
breadcrumb-title: ''
description: Scoprite come configurare le impostazioni della fotocamera in Substance 3D Painter per controllare il comportamento e la proiezione della fotocamera nella finestra della vista.
helpx_creative_field: ""
helpx_description: Painter > Interface > Display settings > Camera settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni della videocamera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 3%

---


# Impostazioni della videocamera

Questa sezione delle **Impostazioni schermo** controlla il comportamento della videocamera e l&#39;aspetto finale della finestra della vista.

## Fotocamera

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Campo di visualizzazione** | Consente di controllare il campo di visualizzazione della videocamera (in gradi) |
| **Distanza focale** | Definisce la distanza alla quale si trova il punto focale.  Questo punto viene utilizzato dall’effetto Profondità campo. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/focus-distance-optim.gif"/></div> **Nota:** la distanza focale può essere impostata automaticamente facendo clic su un punto della trama con la scelta rapida **CTRL + pulsante centrale del mouse** |
| **Apertura** | Definisce l’ampiezza della Profondità di Campo. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r3-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/dof-aperture-optim.gif"/></div> **Nota:** se Iray controlla questo parametro, modificandolo verrà riattivato un calcolo. |

## Effetti post

![](../../assets/post.png)

Per ulteriori informazioni, consulta la [pagina post-effetto](../../features/post-processing/post-processing.md).

## Anti-alias temporale

![](../../assets/taa.png)

Se abilitato, l&#39;**Anti-alias temporale** (**TAA**) rimuoverà i bordi scalettati nella finestra della vista.\
**Il TAA** funziona accumulando informazioni su più fotogrammi di rendering. Questo significa che l&#39;effetto è disabilitato fino a quando la videocamera non smette di muoversi o non viene eseguita un&#39;altra operazione.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Accumulazioni** | Definisce quanti fotogrammi verranno accumulati per ridurre l’effetto di aliasing.<ul data-preserve-html="true"> <li data-preserve-html="true">16: valore consigliato per la maggior parte dei casi</li> <li data-preserve-html="true">64: utile per eliminare i valori di contrasto elevato (come l’Alpha Test shader e dithering combinati)</li> </ul>  **Nota:** questa impostazione non ha alcun impatto sulle prestazioni; tuttavia, un valore elevato potrebbe richiedere più tempo per produrre risultati soddisfacenti. |

![](../../assets/temporal-anti-aliasing.gif){width="500px"}

L&#39;antialiasing può essere utilizzato anche per filtrare lo shader **Alpha-Test** se l&#39;impostazione &quot;**Dithering alfa**&quot; è abilitata:

![](../../assets/dithering-aa.gif){width="500px"}

## Dispersione sotto la superficie

![](../../assets/subscat.png)

Per ulteriori informazioni, vedere la pagina [Dispersione sottosuperficie](../../features/subsurface-scattering/subsurface-scattering.md).

## Profilo colore

![](../../assets/profile-13.png)

Per ulteriori informazioni, vedere la [pagina Profilo colore](../../features/post-processing/color-profile.md).

## Mappatura toni

| Impostazione | Descrizione |
| --- | --- |
| **Funzione** | Consente di specificare la funzione utilizzata per adattare i valori di colore che superano le capacità di visualizzazione del monitor (modifica dei valori HDR in un intervallo LDR).I valori possibili sono:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Lineare</strong> (impostazione predefinita): nessuna trasformazione. I valori superiori a 1,0 sono bloccati.</li><li data-preserve-html="true"><strong>ACE</strong>: utilizzate la curva di mappatura dei toni cinematografici di ACES.</li></ul> <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table2_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/linear-vs-aces.jpg" width="450px"/></div> **Nota:** alcuni motori di gioco e software di rendering utilizzano la mappatura toni ACES. L’attivazione di questa funzione consente di far corrispondere i colori tra le applicazioni ed evitare differenze. |
