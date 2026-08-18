---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/baking/baking-visualization-settings.html"
breadcrumb-title: ''
description: Scoprite come configurare le impostazioni di visualizzazione del baking in Substance 3D Painter per visualizzare in anteprima ed eseguire il debug dei risultati del baking della mappa mesh.
helpx_creative_field: ""
helpx_description: Painter > Baking > Baking visualization settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni di visualizzazione Baking
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '597'
ht-degree: 6%

---


# Impostazioni di visualizzazione Baking

![](../assets/viewport-vizu.png)

La visualizzazione Baking è un pannello all&#39;interno del riquadro di visualizzazione di Painter in modalità Baking. Consente di regolare le impostazioni relative alla visualizzazione delle trame nella finestra della vista.

## Impostazioni generali

| Impostazione | Descrizione |
| --- | --- |
| **Nascondi trame di cottura** | Se attivata, questa icona nasconderà il poly alto e la mesh della gabbia nella finestra della vista. <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../assets/hide-baking-meshes.png"/></div> |
| **Mostra solo per il set di texture selezionato** | Se questa opzione è attivata, nella finestra della vista saranno visibili solo la gabbia e le trame a poli più alti dell’insieme di texture attualmente attivo. |

### Trama ad alta definizione (HP)

| Impostazione | Descrizione |
| --- | --- |
| <b>Trama</b> | Se questa opzione è attivata, nella vista 3D vengono visualizzate le trame con elevato poli. Quando è disattivata, anche le trame ad alto poligono vengono scaricate dalla memoria e possono contribuire a migliorare le prestazioni. Usate l’opzione colore accanto a questa impostazione per controllare il colore della superficie della trama nella finestra della vista. |
| <b>Errore corrispondente</b> | Se questa opzione è attivata, visualizza le aree delle trame ad alto poli che si trovano all’esterno del guscio della trama della gabbia nel colore specificato. Questa impostazione consente di identificare le aree che non verranno rilevate durante il processo di cottura e che potrebbero causare la perdita di dettagli/informazioni. Utilizzare l&#39;opzione colore accanto a questa impostazione per controllare il colore delle aree intersecanti nella finestra della vista. |

### Gabbia

| Impostazione | Descrizione |
| --- | --- |
| <b>Superficie della gabbia</b> | Se questa opzione è attivata, la superficie della mesh della gabbia viene visualizzata nella vista 3D. La superficie della gabbia è definita dal pulsante colore accanto all&#39;impostazione. |
| <b>Opacità superficie gabbia</b> | Rendete la trama più o meno trasparente per gestire la visibilità dei dettagli nella trama sottostante. |
| <b>wireframe gabbia</b> | Se questa opzione è attivata, il wireframe della mesh della gabbia sarà visibile nella finestra della vista. Il colore wireframe può essere regolato con il pulsante colore accanto a questa impostazione. |
| <b>Opacità Cage wireframi</b> | Rendete il wireframe più o meno trasparente. |

### Giunture UV

| Impostazione | Descrizione |
| --- | --- |
| <b>Cuciture mancanti sui bordi rigidi</b> | Se attivata, gli spigoli netti sulla superficie della trama che non sono giunture UV verranno evidenziati con il colore definito dal pulsante accanto all&#39;impostazione. I bordi evidenziati sono visibili solo sulla gabbia e sulla trama a basso poli. I bordi sono visibili sia nella vista 2D che 3D. Questa impostazione consente di identificare gli spigoli che hanno normali vertici divisi senza una giuntura di srotolamento UV, che potrebbe causare problemi di cottura in un secondo momento. |

### Mesh progetto

<table data-preserve-html="true">
<colgroup><col/><col/><col/></colgroup><tbody><tr><th scope="col">Impostazione</th>
<th scope="col">Impostazione secondaria</th>
<th scope="col">Descrizione</th>
</tr><tr><td><b>Mesh progetto</b></td>
<td> </td>
<td><p>Se questa opzione è attivata, nel riquadro di visualizzazione saranno visibili le trame a basso poli su cui sono incise le trame a elevato poli. Se è abilitata l'opzione <b>Nascondi trame di cottura</b>, questa impostazione viene attivata automaticamente anche per evitare che la finestra della vista sia vuota.</p>
<p>Usa l’opzione colore accanto a questa impostazione per regolare il colore della trama del progetto.</p>
</td>
</tr><tr><td rowspan="7"><b>Materiale neutro</b></td>
<td><b>Qualità</b></td>
<td>Controlla la qualità del riflesso dello specular sulla superficie della trama a basso poli. Un valore elevato garantirà una maggiore fedeltà nelle riflessioni, ma può influire anche sulle prestazioni. Un valore basso può introdurre giunture nell’ombreggiatura con mappe normali (nota: questo è solo un problema di visualizzazione).</td>
</tr><tr><td><b>Ruvidità</b></td>
<td>Controlla la ruvidità del materiale con trama a basso poli nelle finestre delle viste.</td>
</tr><tr><td><b>Metallizzato</b></td>
<td>Controlla la metallicità del materiale mesh a basso poli nelle finestre delle viste.</td>
</tr><tr><td><b>Intensità OA</b></td>
<td>Controlla in che misura l’Occlusione Ambiente cotta contribuisce all’ombreggiatura della trama a basso poli nel Riquadro di visualizzazione.</td>
</tr><tr><td><b>Normale con curvatura</b></td>
<td>Se questa opzione è attivata, utilizzate le normali piegate per migliorare l’ombreggiatura della trama a basso poli nella finestra della vista.</td>
</tr><tr><td><b>Quantità curvatura diffuse della normal</b></td>
<td>Controlla l'entità dell'effetto delle normali piegate sull'ombreggiatura della diffusione.</td>
</tr><tr><td><b>Quantità curvatura della specular della normal</b></td>
<td>Controlla l’entità dell’effetto delle normali piegate sull’ombreggiatura dello specular.</td>
</tr></tbody></table>
