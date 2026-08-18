---
title: Conversione in scala di grigi
description: Scopri come utilizzare il generatore di conversione della scala di grigi di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '229'
ht-degree: 5%

---


# Conversione in scala di grigi

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_grayscale_conversion.png" alt=""/><br><strong>Ingresso:</strong> generatore, scala di grigi, colore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di conversione della scala di grigi converte una texture o una mappa in valori di scala di grigi.<br><br>Il generatore di conversione della scala di grigi genera una texture monocromatica (bianco e nero). Di conseguenza, è utile per generare maschere da una mappa di input a colori completa.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Origine** | Usate una texture di colore personale o un punto di ancoraggio. |

## Parametri

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Testo in scala di grigi</strong></td>
    <td>Imposta il metodo di conversione della scala di grigi: <br><ul><li><strong>Desaturazione</strong>: utilizza il valore a metà strada tra il più forte e il più debole dei canali di RGB.</li><li><strong>Luma</strong>: utilizza coefficienti RGB ponderati che corrispondono alla luminosità percepita dall’occhio umano (preferendo il verde).</li><li><strong>Media</strong>: combina i canali rosso, verde e blu in quantità uguali.</li><li><strong>Max</strong>: utilizza il valore più alto dei canali RGB.</li><li><strong>Min</strong>: utilizza il valore più basso dei canali RGB.<ul><li>Canale rosso: utilizza solo il canale rosso.</li><li>Canale verde: utilizza solo il canale verde.</li><li>Canale blu: utilizza solo il canale blu.</li></ul></li></ul></td>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Inverte la maschera.</td>
  </tr>
  <tr>
    <td><strong>Bilanciamento</strong></td>
    <td>Regola il bilanciamento dell’immagine sorgente convertita, spostando il punto medio verso il bianco o il nero come un controllo della luminosità.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Definisce il contrasto/decadimento dell’immagine sorgente convertita.</td>
  </tr>
  <tr>
    <td><strong>Piastrella</strong></td>
    <td>Consente di impostare la suddivisione in porzioni dell’immagine sorgente convertita.</td>
  </tr>
  <tr>
    <td><strong>Rotazione</strong></td>
    <td>Modifica l’angolo dell’immagine sorgente convertita.</td>
  </tr>
  <tr>
    <td><strong>Rotazione sicura</strong></td>
    <td>Attiva o disattiva la modalità di rotazione sicura. Se è true, Rotazione sicura blocca la rotazione ad angoli di 45 gradi.</td>
  </tr>
</table>
