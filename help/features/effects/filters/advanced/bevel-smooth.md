---
title: Smusso uniforme
description: Scopri come utilizzare il filtro Smusso uniforme di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 2%
---

# Smusso uniforme

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Smusso uniforme](./Resources/icon_bevel_smooth.png "Smusso uniforme")

<b>Ingresso:</b> effetti/smussatura, arrotondamento, distanza, scala di grigi

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Smusso uniforme disegna una sfumatura dai bordi di una maschera verso l’esterno, l’interno o entrambi.

Viene utilizzato su un livello texture o all’interno di una maschera (output in bianco e nero) per creare una sfumatura smussata uniforme dai bordi di una maschera.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Mappa di distanza:</b> Scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Direzione:</b> | Selezionate il lato del bordo della maschera da dilatare. |
| <b>Distanza:</b> | Regolate la distanza di dilatazione dello smusso. |
| <b>Arrotondamento:</b> | Regolate l’intensità dell’attenuazione applicata alla maschera. |
| <b>Scostamento curva:</b> | Regolate i bordi della maschera verso l’interno o l’esterno. |
| <b>Forma curva:</b> | Consente di specificare se la pendenza di smusso deve utilizzare una curva pizzicata o arrotondata. |
| <b>Soglia maschera:</b> | Regola il valore utilizzato per rilevare i bordi della maschera dall’input. |
| <b>Moltiplicatore Mappa di distanza:</b> | Regolate l&#39;impatto della Mappa di distanza sulla Distanza massima. |
| <b>Contorna con smusso:</b> | Attivate o disattivate la visualizzazione delle porzioni di smusso in orizzontale e verticale. |
