---
title: Distanza 3D
description: Scopri come utilizzare il generatore di distanza 3D di Substance 3D Painter.
source-git-commit: b095b9b437f75bbb3a3b85ee84a6850026c3bf98
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 1%

---


# Distanza 3D

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_3d_distance.webp" alt=""/><br><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di distanza 3D definisce un punto nello spazio 3D (punto di origine) e visualizza la distanza da tale punto con una sfumatura monocromatica. Le aree della superficie della trama più vicine al punto sono più scure e le aree più lontane sono più chiare (per impostazione predefinita).<br><br>È necessaria una mappa di posizione eseguita i baking come input dell'immagine. <a href="../../../baking/baking.md">Ulteriori informazioni su come eseguire i baking qui</a>.<br><br>Con Distanza 3D viene generata una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere che creano una sfumatura lontano da una determinata posizione.<br><br></td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Posizione** | Utilizza la mappa Posizione eseguita i baking per calcolare la distanza. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la sfumatura. |
| **Posizione X** | Trasforma il punto sorgente lungo l&#39;asse x. |
| **Posizione Y** | Trasforma il punto sorgente lungo l’asse y. |
| **Posizione Z** | Trasforma il punto sorgente lungo l’asse z. |
| **Raggio** | Regolate le dimensioni del decadimento della distanza. |
| **Scostamento** | Spostate le posizioni iniziale e finale della sfumatura verso o lontano dal punto sorgente. Se ci si allontana dal punto sorgente (aumentando lo scostamento), si ottiene un’area scura più grande vicino al punto sorgente. Se ci si avvicina al punto sorgente, la sfumatura viene schiarita e potenzialmente la si rimuove completamente se **Scostamento** è impostato su 0. |
| **Contrasto** | Regolate il contrasto della sfumatura sferica. |
