---
title: 3D linear gradient
description: Scopri come utilizzare il generatore di 3D linear gradient di Substance 3D Painter.
source-git-commit: b095b9b437f75bbb3a3b85ee84a6850026c3bf98
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 1%

---


# 3D linear gradient

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_3d_linear_gradient.webp" alt=""/><br><strong>Ingresso:</strong> sfumatura, scala di grigi</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di 3D linear gradient utilizza la mappa Posizione per creare una sfumatura tra due punti sulla trama. <br><br>Il 3D linear gradient genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile generare maschere per posizionare una sfumatura lineare in un'area specifica.<br><br>Come input dell'immagine è necessaria una mappa di posizione eseguita i baking. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.<br><br>La mappa Posizione assegna un colore a ogni punto della trama che corrisponde alla sua posizione compresa tra 0 e 1 lungo gli assi X, Y e Z. Ciò significa che ogni punto della trama ha un colore unico. Puoi impostare i punti iniziale e finale della sfumatura lineare selezionando il colore della mappa posizione nelle posizioni iniziale e finale.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Posizione** | Utilizzate la mappa di posizione al forno. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la sfumatura lineare. |
| **Saldo** | Spostate la posizione del punto medio della sfumatura lineare. |
| **Contrasto** | Regolate il contrasto della sfumatura lineare. |
| **Inizio posizione 3D** | Imposta il punto iniziale della sfumatura in base ai colori della mappa posizione. Per definire facilmente il punto iniziale, visualizzare la mappa di posizione sullo schermo nella finestra della vista e utilizzare il selettore colore per selezionare il punto iniziale. |
| **Fine posizione 3D** | Imposta il punto finale della sfumatura in base ai colori della mappa posizione. Per definire facilmente il punto finale, visualizzare la mappa di posizione sullo schermo nella finestra della vista e utilizzare il selettore colore per selezionare il punto finale. |
