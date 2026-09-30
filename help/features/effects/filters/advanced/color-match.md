---
title: Corrispondenza colori
description: Scoprite come utilizzare il filtro Corrispondenza colore in Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 1%
---

# Corrispondenza colori

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="./Resources/icon_color_match.png" alt="Icona Corrispondenza colori" title="Corrispondenza colori"/><br><strong>Ingresso:</strong> effetti/regolazioni</td>
    <td style="border: 0;" valign="top">Descrizione<br>Il filtro Corrispondenza colori fa corrispondere un intervallo di colori di origine definito a un intervallo di colori di destinazione, con supporto per gli slot di input per definire sia i valori di origine che quelli di destinazione. La corrispondenza colore consente di conservare i dettagli cambiando il colore di una superficie e di controllare come vengono gestiti Tonalità, Crominanza e Luma.<br>La corrispondenza colore viene utilizzata su un livello di riempimento per apportare regolazioni di colore precise.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Colore di origine:** | Slot di input per il colore di origine. Usate una mappa colore personale o un punto di ancoraggio. |
| **Colore di destinazione:** | Slot di input per il colore di destinazione. Usate una mappa colore personale o un punto di ancoraggio. |

## Parametri

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Metodo colore sorgente:</strong></td>
    <td>Selezionate l’origine del colore di origine.<br><ul><li><strong>Media</strong>: usate il colore del materiale esistente come colore di origine. Nota: questo richiede che il metodo di fusione del livello sia impostato su <strong>Passthrough</strong>.</li><li><strong>Parametro</strong>: impostare il colore di origine utilizzando un parametro.</li><li><strong>Input</strong>: impostare il colore di origine con un input di immagine.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Colore di origine:</strong></td>
    <td>Regolare il colore di origine quando <strong>Metodo colore di origine</strong> è impostato su <strong>Parametro</strong>.</td>
  </tr>
  <tr>
    <td><strong>Metodo colore di destinazione:</strong></td>
    <td>Selezionate l’origine del colore di destinazione.<br><ul><li><strong>Parametro</strong>: impostare il colore di destinazione utilizzando un parametro.</li><li><strong>Input</strong>: impostare il colore di destinazione con un input di immagine.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Colore di destinazione:</strong></td>
    <td>Regolare il colore di destinazione quando <strong>Metodo colore di destinazione</strong> è impostato su <strong>Parametro</strong>.</td>
  </tr>
  <tr>
    <td><strong>Variazione colore personale:</strong></td>
    <td>Attiva/disattiva i controlli personalizzati di tonalità, crominanza e variazione della luminanza.</td>
  </tr>
  <tr>
    <td><strong>Tonalità:</strong></td>
    <td>Regolate la variazione della tonalità applicata al risultato.</td>
  </tr>
  <tr>
    <td><strong>Crominanza:</strong></td>
    <td>Regola la variazione di crominanza applicata al risultato.</td>
  </tr>
  <tr>
    <td><strong>Luma:</strong></td>
    <td>Regolate la variazione della luminanza applicata al risultato.</td>
  </tr>
</table>