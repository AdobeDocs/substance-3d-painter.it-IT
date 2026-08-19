---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/layer-stack/layer-instancing.html"
breadcrumb-title: ''
description: Scoprite come utilizzare l’istanza dei livelli in Substance 3D Painter per riutilizzare in modo efficiente i livelli su più set di texture.
helpx_creative_field: ""
helpx_description: Painter > Interface > Layer stack > Layer instancing
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Istanza dei livelli
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '631'
ht-degree: 0%

---


# Istanza dei livelli

L&#39;**Istanza dei livelli** consente di sincronizzare i parametri di livello tra più livelli e [set di texture](../texture-set/texture-set.md) pur continuando a generare un risultato dipendente dalla trama.

Quando viene creata un’istanza di livello, viene utilizzato il livello originale (o livello di origine) per replicare i parametri tra tutte le istanze esistenti. **È possibile modificare solo il livello di origine**.

>[!WARNING]
>
> Qualsiasi azione di disegno (tratti pennello, riempimento poligonale, ecc.) funzionerà solo sul set di texture in cui si trova il livello sorgente. Gli altri set di texture che presentano un’istanza di questo livello elimineranno semplicemente le azioni di disegno.

## Creazione di un’istanza di livello

Per creare un’istanza di livello:

1. Seleziona un livello esistente
1. Copia il livello (**CTRL+C**)
1. Incollare come istanza (utilizzare **CTRL+MAIUSC+V** oppure fare clic con il pulsante destro del mouse per aprire il menu di scelta rapida e scegliere **Incolla come istanza**)

![](../../assets/paste-as-layer-instance.png)

>[!NOTE]
>
> Le istanze possono essere create da qualsiasi livello, inclusi **gruppi**. L’istanza di una cartella può essere un modo semplice per replicare più livelli su vari set di texture. L’aggiunta di livelli all’interno di una cartella di istanze li replicherà anche nelle istanze esistenti.

Una volta creata un&#39;istanza, il livello di origine e quello di destinazione visualizzeranno una nuova icona. Questa icona è un pulsante che può essere utilizzato per navigare più facilmente tra un livello sorgente e le sue istanze, senza dover passare manualmente da un insieme di texture all’altro (vedi di seguito).

| Nome | Icona |
| --- | --- |
| **Livello senza istanza** | <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/non-instanced.png"/></div> |
| **Origine istanza** | <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/instance-source.png"/></div> |
| **Destinazione istanza** | <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r3-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/instance-target.png"/></div> |

## Creazione di un&#39;istanza tra set di texture

È possibile creare un’istanza di livello su più set di texture con un’unica azione, evitando di copiarla e incollarla manualmente.

Per creare un’istanza su più set di texture:

1. Seleziona un livello esistente
1. Fai clic con il pulsante destro del mouse sul livello per aprire il menu contestuale
1. Scegli **Crea istanza tra set di texture**
1. Nella nuova finestra, controllate quali set di texture devono ricevere un’istanza.
1. Fate clic su OK per convalidare e creare le istanze.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/instance-across-texture-sets.png)

</td>
<td style="border: 0;" valign="top">

![](../../assets/instance-across-texture-sets-dialog.png)

</td>
</tr>
</table>

>[!NOTE]
>
> Il punto esclamativo accanto al nome di un set di texture indica un canale **non corrispondente**. Ciò significa che se un’istanza viene creata in questi insiemi di texture, non verrà riprodotta correttamente perché manca un canale.

## Passaggio da un’istanza all’origine

Poiché un&#39;istanza può essere aggiornata **solo** **modificando l&#39;origine** (per motivi tecnici), è obbligatorio selezionare il livello di origine per modificarne le proprietà.\
A tale scopo, fai clic sul **pulsante delle proprietà dell’istanza** sul livello nel gruppo di livelli.

![](../../assets/instance-properties-optim.gif)

Facendo clic sul pulsante delle proprietà di un&#39;istanza, la **finestra delle proprietà** passa dallo strumento/livello corrente a **un elenco** che visualizza un livello di origine e le relative istanze.\
Facendo clic su **qualsiasi elemento** dell&#39;elenco per **passare automaticamente a questo livello**. Questa operazione **modificherà** automaticamente gli attuali **set di texture selezionati** anche a destra.

L&#39;utilizzo dell&#39;**albero delle istanze** è il modo migliore per **passare rapidamente** da un&#39;istanza alla relativa origine visualizzando contemporaneamente le **dipendenze**.

## Cicli di istanze (e come risolverli)

I cicli sono istanze utilizzate direttamente o indirettamente nel livello sorgente stesso. I cicli **non possono essere calcolati** dal motore di Substance 3D Painter e pertanto devono essere **disabilitati** finché non vengono corretti o rimossi.

Esempio:\
![](../../assets/instance-cycle-optim.gif)

In questo esempio, l’istanza del livello sorgente viene spostata al suo interno (perché si tratta di una cartella). L&#39;istanza viene interrotta perché per generare i relativi parametri è necessario eseguire una query sui parametri dall&#39;origine, che dipende dai parametri dell&#39;istanza. In questo modo viene creato un ciclo che non può essere risolto automaticamente. L&#39;istanza viene disabilitata.

L&#39;unico modo per correggere un ciclo è **spostare** l&#39;istanza all&#39;esterno della cartella o **eliminarla**.

Le istanze di livello possono essere utilizzate nei livelli sorgente, a condizione che l’istanza stessa faccia riferimento a un livello sorgente diverso.
