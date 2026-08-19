---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/tool-list/clone-tool.html"
breadcrumb-title: ''
description: Utilizzate lo strumento Clona di Substance 3D Painter per copiare i dettagli della texture da un’area all’altra per una pittura uniforme della texture.
helpx_creative_field: ""
helpx_description: Painter > Painting > Tool list > Clone Tool
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Strumento clone
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 1%

---


# Strumento clone

Introdotto in Substance 3D Painter 2, lo strumento Clona condivide lo stesso tipo di parametri dello [strumento di disegno](https://support.allegorithmic.com/documentation/display/SPDOC/Paint+brush). Come suggerisce il nome, lo strumento Clona consente di duplicare il contenuto di un livello specifico o dell’intero gruppo di livelli da un punto all’altro.

![](../../assets/clone-01.gif)

## Utilizzo

Il modo più semplice per usare lo strumento Clona consiste nell’usarlo sul contenuto di un livello di pittura.

Questa operazione può essere eseguita in 2 passaggi:

* Selezionare la posizione di origine posizionando il mouse sul modello e premendo il tasto &quot; **V** &quot;.
* Quindi posizionate il mouse nel punto in cui verrà visualizzata l’area duplicata e iniziate a colorare.

È possibile aggiornare l&#39;origine in qualsiasi momento premendo nuovamente &quot; **V** &quot;.

![](../../assets/2018-06-12-18-11-59.png)

Per impostazione predefinita, quando colorate con lo strumento Clona, la posizione di origine segue e aggiorna la sua posizione una volta rilasciato il pennello. Disabilitando il pulsante utilizzato per il &quot; **comportamento di origine clone** &quot;, l&#39;origine tornerà al punto in cui era stata definita quando si preme &quot; **V** &quot;. Questo può essere utile quando colorate più volte con la stessa area sorgente.

Un modo più intelligente di utilizzare lo strumento Clona consiste nel creare un livello di pittura e impostare il metodo di fusione di tutti i canali su &quot;Attraversa&quot;. Ciò consentirà di duplicare qualsiasi informazione in modo non distruttivo da tutti i livelli che si trovano sotto il &quot;livello Clone&quot;. I livelli sottostanti rimangono intatti e tutte le modifiche applicate in seguito verranno prese in considerazione dal livello Clone:

![](../../assets/clone-02.gif)
