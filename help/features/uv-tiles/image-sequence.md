---
breadcrumb-title: ""
description: Scoprite come utilizzare le sequenze di immagini con i riquadri UV in Substance 3D Painter per flussi di lavoro di texture animata.
title: Sequenza di immagini
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 0%
---

# Sequenza di immagini

Le sequenze di immagini sono una raccolta di immagini raggruppate come singola risorsa nello scaffale. I nomi dei file delle immagini vengono raggruppati in base a uno schema specifico.

## Come importare immagini come sequenza

Quando si importa un file di immagine, se il nome del file corrisponde a un pattern specifico, verrà importato automaticamente come sequenza. Se accanto al file importato sono presenti altre immagini, queste verranno considerate. Non è quindi necessario importare manualmente tutti i file da una sequenza, è sufficiente selezionare il primo file.

Esempi di file corrispondenti:

I seguenti nomi di file importano correttamente una sequenza di immagini perché possono riconoscere che l’ultima parte del nome del file fa riferimento a un numero UDIM 1032:

* file\_22.1032.jpg
* file\_22-223.1032.jpg
* file\_22-223-1032.jpg
* file\_22-223\_1032.jpg

I seguenti nomi di file non verranno importati come sequenza di immagini perché non sono strutturati correttamente:

* file\_22-2232032.jpg
* file\_22-223PM2032.jpg
* file\_22-223-0032.jpg
* file\_22-223\_Rec2020.jpg

La corrispondenza del nome file si basa sulla seguente espressione regolare:

```
 ^(.+?)[\.\-\_](?
```


## Come utilizzare le sequenze di immagini

Le sequenze di immagini possono essere caricate in qualsiasi slot di risorse nell&#39;interfaccia come qualsiasi altra risorsa. Tuttavia, in alcuni casi potrebbero essere necessarie impostazioni aggiuntive per il corretto utilizzo.

In [Livelli di riempimento](../../painting/fill-projections/fill-projections.md) (ed effetti di riempimento), assicuratevi che la modalità di proiezione sia impostata su **Riempimento (corrispondente a Porzione UV)** per garantire che ogni immagine della sequenza sia assegnata alla [Porzione UV](uv-tiles.md) destra nel set di texture.
