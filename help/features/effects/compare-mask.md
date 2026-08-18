---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/effects/compare-mask.html"
breadcrumb-title: ''
description: Scoprite come utilizzare l’effetto Confronta maschera in Substance 3D Painter per creare maschere basate su operazioni di confronto delle texture.
helpx_creative_field: ""
helpx_description: Painter > Features > Effects > Compare Mask
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Confronta la maschera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '376'
ht-degree: 1%

---


# Confronta la maschera

![](../../assets/compare-mask.png)

Questo effetto consente di confrontare rapidamente e facilmente due canali e di produrre di conseguenza una maschera. Questo effetto è disponibile solo per Maschera sui livelli.

Di seguito sono riportate le impostazioni disponibili per questo effetto:

| Impostazione | Descrizione |
| --- | --- |
| **Canale** | Canale da confrontare tra la sorgente e la destinazione da cui creare una maschera. Questo elenco si basa sul canale disponibile nelle [impostazioni del set di texture](../../interface/texture-set/texture-set-settings.md). |
| **Confronta** | Qui sono disponibili tre parametri per scegliere come calcolare la maschera. Il menu a discesa al centro definisce l&#39;operazione di confronto (minore di, entro tolleranza, maggiore di). <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/compare-mode.png"/></div> Modalità di origine e di destinazione:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Livelli inferiori</strong>: tenete conto della versione convertita di tutti i livelli inferiori a quello corrente.</li><li data-preserve-html="true"><strong>Questo livello</strong>: considera solo questo livello.</li><li data-preserve-html="true"><strong>Questa maschera</strong>: tenete presente il contenuto esistente della maschera (ad esempio, se sono già presenti un effetto Riempimento o un effetto Generatore).</li><li data-preserve-html="true"><strong>Costante</strong>: valore uniforme.</li></ul>Le operazioni sono:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Minore di</strong>: se il menu a discesa Origine (a sinistra) contiene valori inferiori al menu a discesa Destinazione (a destra), nella maschera verranno generati valori bianchi.</li><li data-preserve-html="true"><strong>Entro tolleranza</strong>: se il menu a discesa Origine (a sinistra) ha valori simili a quelli del menu a discesa Destinazione (a destra), nella maschera verranno generati i valori bianchi.</li><li data-preserve-html="true"><strong>Maggiore di</strong>: se il menu a discesa Origine (a sinistra) contiene valori superiori a quelli del menu a discesa Destinazione (a destra), nella maschera verranno generati valori bianchi.</li></ul> |
| **Costante** | Valore da confrontare quando l&#39;impostazione di confronto è impostata su &quot;costante&quot;. |
| **Durezza** | Controlla lo smoothness e la durezza del confronto di maschere ottenuto. |
| **Istogramma dei canali sorgente** | Fornite una vista istogramma dell&#39;origine e della destinazione. È utile sapere se si sovrappongono o meno (se non si sovrappongono, la maschera risulterà vuota).Per ulteriori informazioni sul funzionamento dell&#39;istogramma, vedere: [Livelli](https://experienceleague.adobe.com/en/docs/substance-3d-designer/using/substance-graphs/nodes-reference-for-substance-graphs/atomic-nodes/levels). |

>[!NOTE]
>
> È possibile fare clic con il pulsante destro del mouse su un livello e scegliere la scelta rapida &quot;**Aggiungi maschera con combinazione di height**&quot; per aggiungere rapidamente questo nuovo effetto a un livello. Questa scelta rapida cambierà anche il canale di Height **metodo di fusione** in &quot;**Normale**&quot; anziché il valore predefinito &quot;**Scherma lineare (Aggiungi)**&quot;.\
> ![](../../assets/compare-shortcut.png)
