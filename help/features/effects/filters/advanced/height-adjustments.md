---
title: Regolazione height
description: Scopri come utilizzare il filtro Regolazione Height di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 1%
---

# Regolazione height

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Regolazione Height](./Resources/icon_height_adjust.png "Regolazione Height")

<b>Ingresso:</b> effetti/regolazioni, ridimensionamento, scostamento, inversione

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Regolazione Height inverte, sposta o moltiplica il canale del height per un valore scelto.

Viene utilizzato su un livello texture o all’interno di una maschera (output in bianco e nero) per regolare le informazioni del height in modo non distruttivo.

</td>
</tr>
</table>

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Inverti:</b> | Attiva/disattiva l’inversione del risultato. |
| <b>Scostamento:</b> | Regolate il valore height aggiungendo o sottraendo la quantità specificata. |
| <b>Moltiplica:</b> | Moltiplica i valori di height per questo valore. Come moltiplicatore, questo rende le aree più alte più alte e quelle più basse più basse. |

>[!NOTE]
>
> I parametri **Moltiplica** e **Scostamento** vengono impilati con Scostamento applicato per primo. Se lo scostamento produce un valore height pari a zero in un dato punto, la moltiplicazione si moltiplica per zero, il che significa che non causerà alcuna modifica in quel punto. Per moltiplicare e quindi spostare i valori moltiplicati, potete aggiungere un secondo filtro Regolazione Height.
