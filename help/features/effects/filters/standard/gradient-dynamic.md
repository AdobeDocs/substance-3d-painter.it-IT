---
title: Sfumatura dinamica
description: Scoprite come utilizzare il filtro Dinamico sfumatura di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '117'
ht-degree: 4%
---

# Sfumatura dinamica

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona dinamica sfumatura](./Resources/icon_gradient_dynamic.png "Dinamica sfumatura")

<b>Ingresso:</b> effetti/sfumatura, scala di grigi, modifica

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro dinamico sfumatura rimappa i valori della scala di grigio di un’immagine su una sfumatura definita da colori posizionati in punti specifici lungo la sfumatura.

Viene utilizzato su un livello texture o all’interno di una maschera (output in bianco e nero) per rimappare i valori della scala di grigi con una sfumatura campionata da un’altra immagine.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Origine sfumatura: </b> colore | Usate una mappa colore personale o un punto di ancoraggio. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Orientamento sfumatura:</b> | Seleziona se la sorgente del gradiente deve essere campionata orizzontalmente o verticalmente. |
| <b>Posizione di input sfumatura:</b> | Regolate la posizione campionata dall’input della sfumatura. |
