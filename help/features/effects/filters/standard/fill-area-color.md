---
title: Colore area di riempimento
description: Scopri come utilizzare il filtro Colore area di riempimento di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 1%
---

# Colore area di riempimento

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Colore area di riempimento](./Resources/icon_fill_area_color.png "Colore area di riempimento")

<b>Ingresso:</b> effetti/riempimento, forma, contorno, rgba, colore

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Colore area di riempimento converte i contorni in forme piene. Viene riempita qualsiasi area con un bordo continuo. La versione a colori usa il canale alfa per determinare i bordi dell’area.

Viene utilizzato su un livello di pittura (canale di colore) per riempire tratti chiusi dipinti.

</td>
</tr>
</table>

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Rilevamento area:</b> | Selezionate la modalità di identificazione dell’area da riempire. |
| <b>Soglia rilevamento area:</b> | Regolate la soglia di rilevamento dell&#39;area. |
| <b>Rilevamento area di debug:</b> | Attiva/disattiva la visualizzazione del contorno rilevato dall&#39;impostazione Rilevamento area. Questo può aiutare a identificare le aree che potrebbero non essere completamente chiuse. |
| <b>Comportamento bordo UV:</b> | Seleziona come gestire i bordi UV durante il riempimento dell&#39;area. |
| <b>Soglia bordo UV:</b> | Regolate la soglia utilizzata per ignorare le aree UV che potrebbero altrimenti essere riempite dal processo di rilevamento dell&#39;area. |
| <b>Modalità colore:</b> | Selezionate il metodo utilizzato per riempire l’interno dell’area. |
| <b>Colore riempimento:</b> | Regolate il colore di riempimento. |
| <b>Intensità sfocatura:</b> | Regolate l’intensità della sfocatura. |
| <b>Campioni sfocatura:</b> | Regolate il numero di campioni di sfocatura. |
| <b>Iterazioni diffusione:</b> | Regolate il numero di iterazioni di diffusione da eseguire. Valori più alti migliorano il risultato ma sono più lenti. I valori utili sono compresi nell&#39;intervallo [8, 48]. |
