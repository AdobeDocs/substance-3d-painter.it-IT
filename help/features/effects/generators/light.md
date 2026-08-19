---
title: Luce
description: Scopri come utilizzare il generatore di luce di Substance 3D Painter.
source-git-commit: b095b9b437f75bbb3a3b85ee84a6850026c3bf98
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 3%

---


# Chiaro

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_light.webp" alt=""/><br><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di luce simula una luce direzionale che illumina la trama, in base alle mappe World Space Normal e Position.<br><br>Il generatore di luce può essere utilizzato su un livello di riempimento o per creare una maschera. Quando viene utilizzato in un livello di riempimento, il generatore genera colore, metallizzazione, rugosità specular, canali normali e height che possono essere utilizzati in varie combinazioni per creare effetti diversi. Si consiglia di scorrere le viste dei canali nella finestra della vista per capire in che modo ogni canale viene influenzato dal generatore di luce.<br><br>Per l'input dell'immagine sono necessarie mappe normali della posizione e dello spazio globale. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Spazio globale normale** | Utilizzate la mappa standard di World Space. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Inverti la mappa dei colori di output. |
| **Angolo orizzontale** | Impostate l&#39;angolo orizzontale della luce falsa. |
| **Angolo verticale** | Impostate l&#39;angolo verticale della luce falsa. |
| **Luce lucidità** | Regolate la dissolvenza dell’area evidenziata. |
| **Livello evidenziazione** | Regolate il contrasto della luce. |
| **Attenuazione della luce** | Regolate la dissolvenza della luce. |
