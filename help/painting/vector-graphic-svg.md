---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/vector-graphic-svg.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la grafica vettoriale (file SVG e AI) in Substance 3D Painter per aggiungere grafica vettoriale scalabile alle texture.
helpx_creative_field: ""
helpx_description: Substance 3D Painter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Grafica vettoriale (SVG)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '522'
ht-degree: 1%

---


# Grafica vettoriale (.svg e .ai)

![Immagine che mostra un file svg proiettato su una trama accanto a un elenco di parametri](../assets/svg_overview.png)

I file di grafica vettoriale (sia <b>.svg</b> che Illustrator <b>.ai</b>) possono essere importati come immagini normali in Painter. Sono disponibili alcune impostazioni per regolare l’aspetto dell’elemento grafico e adattarlo meglio al resto della texture.

* Per ulteriori informazioni sui file SVG, [vedere questa pagina](https://www.adobe.com/creativecloud/file-types/image/vector/svg-file.html).
* Per ulteriori informazioni sui file AI, [consulta questa pagina](https://www.adobe.com/ie/creativecloud/file-types/image/vector/ai-file.html).

I file SVG e AI vengono automaticamente convertiti in immagini pixel se utilizzati all’interno della [pila di livelli](../interface/layer-stack/layer-stack.md) (a seconda dell’impostazione selezionata). Si tratta di un processo non distruttivo, in quanto la modifica della risoluzione o l’aggiornamento del file sorgente aggiornerà il risultato finale di conseguenza.

## Proprietà

Dopo aver importato un file vettoriale e averlo caricato all&#39;interno di un livello o di proprietà dello strumento, sarà disponibile un set di parametri:

| Sezione | Impostazione | Descrizione |
| --- | --- | --- |
| <b>Tavola da disegno</b> | <b>Tavola da disegno</b> | Seleziona la tavola da disegno inclusa nel file.  **Nota:** questa impostazione è disponibile solo per i file Illustrator (.ai). |
| <b>Risoluzione</b> | Risoluzione | Definite le dimensioni con cui il file svg verrà convertito in un’immagine bitmap (pixel) quando viene utilizzata per la texture all’interno della serie di livelli.   Valori possibili:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Automatico</b>: la risoluzione è determinata dalla risoluzione del set di texture corrente (se utilizzato nel livello/effetto di riempimento) o a 512 pixel quando utilizzato in uno strumento pennello.<br/> </li> <li data-preserve-html="true"><b>Risorsa</b>: la risoluzione è determinata dalla dimensione in pixel definita all&#39;interno del file SVG stesso.<br/> </li> <li data-preserve-html="true"><b>Personalizzato</b>: la risoluzione è determinata dall&#39;impostazione di risoluzione appena sotto nell&#39;interfaccia.</li> </ul>  <div><img alt="impostazione risoluzione svg" class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_table_row-ad42696-column-7212622_image" src="../assets/svg_resolution_custom.png" title="impostazione risoluzione svg"/></div> |
|  |  |  |
| <b>Area di ritaglio</b> | Ritaglia a | Definite in che modo le forme SVG saranno limitate all’area sottoposta a rendering.   Valori possibili:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Limiti risorsa</b>: l&#39;area è definita dai limiti definiti all&#39;interno del file SVG.</li> <li data-preserve-html="true"><b>Personalizzata</b>: l&#39;area è definita da valori espliciti tramite le impostazioni dell&#39;interfaccia appena sotto.<br/> </li> </ul> |
|  | Proporzioni quadrate | Se l’area di ritaglio è definita da <b>Limiti risorsa</b>, questa impostazione garantisce il mantenimento delle proporzioni originali, evitando dilatazioni errate durante il rendering del SVG come immagine quadrata.   Questa impostazione può rendere alcuni elementi inaspettatamente visibili. Per evitare questo problema, disattivate questa impostazione e regolate invece manualmente le impostazioni UV quando si trova all&#39;interno di un livello/effetto di riempimento. |
|  | In alto a sinistra In basso a destra | Se il ritaglio è impostato su Area personalizzata, queste impostazioni consentono di definire l’area manualmente specificando gli angoli superiore sinistro e inferiore destro. |
|  |  |  |
| <b>Ambito</b> | Ambito | Definite gli elementi all’interno del file SVG da includere prima di eseguire il rendering.   Il valore predefinito è <b>Documento</b>, ovvero viene utilizzato tutto il contenuto del file SVG. Utilizza il pulsante <b>Modifica</b> per modificare gli elementi da includere. |

### Finestra Ambito

Quando si modifica l’ambito di un elemento di grafica vettoriale (vedere l’impostazione precedente), viene visualizzata una finestra con un elenco di elementi da selezionare per specificare cosa includere o escludere dall’immagine finale renderizzata.

Utilizzare la casella di controllo <b>Mostra miniature</b> per visualizzare un&#39;immagine per ogni elemento.

![](../assets/v10_ai_thumbs.jpg)
