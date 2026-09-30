---
title: Riempi area maschera
description: Scoprite come utilizzare il filtro Maschera area di riempimento di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 2%
---

# Riempi area maschera

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Riempi maschera di area](./Resources/icon_fill_area_mask.png "Riempi maschera di area")

<b>Ingresso:</b> effetti/riempimento, forma, contorno, scala di grigi

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Maschera area di riempimento converte i contorni in forme piene. Viene riempita qualsiasi area con un bordo continuo.

Viene utilizzato su un livello maschera (output in bianco e nero) dopo aver aggiunto un livello di pittura per riempire tratti dipinti chiusi.

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
| <b>Soglia rilevamento bordo UV:</b> | Regolate la soglia utilizzata per ignorare le aree UV che potrebbero altrimenti essere riempite dal processo di rilevamento dell&#39;area. |
