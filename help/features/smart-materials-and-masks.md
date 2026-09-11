---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/smart-materials-and-masks.html"
breadcrumb-title: ''
description: Scoprite come utilizzare materiali avanzati e maschere in Substance 3D Painter per creare texture di procedurali che si adattano alla geometria.
helpx_creative_field: ""
helpx_description: Painter > Features > Smart Materials and Masks
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Materiali avanzati e maschere
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '382'
ht-degree: 0%

---


# Materiali avanzati e maschere

Substance 3D Painter supporta l&#39;utilizzo di **predefiniti di livello** avanzati. Questi predefiniti possono essere utilizzati per **condividere rapidamente tra** set di texture o progetti in un **processo di texture simile** mantenendo i risultati diversi, **adattati alla topologia della trama** .

>[!NOTE]
>
> Una volta aggiunto nella pila di livelli, non è possibile recuperare il materiale avanzato utilizzato. Nel caso in cui un materiale avanzato debba essere aggiornato, il processo dovrà essere eseguito manualmente.\
> È tuttavia possibile aggiornare le singole risorse con [Resources Updater](plugins/resources-updater.md).

## Come si utilizzano Materiali avanzati/maschere?

I materiali avanzati possono essere utilizzati in qualsiasi punto della pila di livelli, mentre le maschere avanzate possono essere utilizzate solo nella pila di effetti.\
Per ulteriori informazioni sulle differenze, consultate: [Stack di livelli](../interface/layer-stack/layer-stack.md) e [Effetti](effects/effects.md)

### Aggiunta di un materiale avanzato

I materiali avanzati possono essere aggiunti in due modi diversi:

* Trascinando un materiale avanzato dallo scaffale alla Pila livelli:\
  ![](../assets/sm-drop.gif)
* Facendo clic sul pulsante Materiale avanzato per aprire un ripiano:\
  ![](../assets/sm-button.gif)

### Aggiunta di una Maschera avanzata

Poiché le Maschere avanzate sono predefiniti degli effetti, possono essere aggiunte solo alle serie di effetti (in modo specifico per la maschera).

* Per aggiungere una Maschera avanzata, è sufficiente **trascinarne** una dallo scaffale al livello **target**:\
  ![](../assets/smm-drop.gif)
* Se trascinate **più** maschere avanzate, queste verranno accumulate:\
  ![](../assets/smm-drop-accum.gif)
* È tuttavia possibile **sostituire** l&#39;intera serie di effetti premendo **CTRL** durante il trascinamento della selezione:\
  ![](../assets/smm-drop-replace.gif)

### Come si creano Materiali avanzati/maschere?

Per creare un Materiale avanzato, è necessaria una **cartella**.\
Il contenuto dei Materiali avanzati sarà contenuto nella cartella. Quindi fai clic con il pulsante destro del mouse sulla cartella e seleziona &quot; **Crea materiale avanzato** &quot;. Il Materiale avanzato verrà quindi aggiunto allo scaffale corrente e denominato in base alla cartella selezionata.

![](../assets/create-sm.png)

Per creare una Maschera avanzata, è sufficiente fare clic con il pulsante destro del mouse su un livello e scegliere &quot; **Crea maschera avanzata** &quot;.

![](../assets/create-smm.png)

## Come condividere/recuperare un materiale avanzato/una maschera?

I predefiniti sono salvati **sul disco** e possono essere recuperati dalla cartella dedicata.\
Per trovare il **percorso dello scaffale** , vedere: [Aggiunta di contenuto sul disco rigido](../content/importing-assets/adding-content-on-the-hard-drive.md) .

Chiunque può semplicemente **importare** il file nel proprio scaffale Substance 3D Painter per utilizzare il predefinito.
