---
title: Gonfia contornamento
description: Scopri come utilizzare il generatore di ritiro gonfiato di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 3%

---


# Gonfia contornamento

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_inflate_shrinkwrap.webp" alt=""/><br><strong>Ingresso:</strong> ritiro, gonfiaggio, generatore, casuale</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore Gonfiamento Ritaglia aggiunge rughe che simulano l'effetto di un materiale sottile allungamento sulla superficie della trama.<br><br>Il generatore di ritorno a capo automatico Gonfiamento genera una texture monocromatica (bianco e nero). Di conseguenza, è utile per generare maschere che creano l’effetto contorno stretto. Tuttavia, può anche essere posizionato direttamente su un livello di riempimento per aggiungere rughe ai canali height e normale.<br><br>È necessaria una mappa di curvatura eseguita i baking come input dell'immagine. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura eseguita i baking. |

## Parametri

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Predefinito</strong></td>
    <td>Passa da predefiniti gonfiati, a vuoto tirato e a predefiniti stretti.</td>
  </tr>
  <tr>
    <td><strong>Seed</strong></td>
    <td>Impostate il valore di inizializzazione utilizzato per generare la texture di dirt. <br><ul><li>Fate clic su Casuale per passare a un altro valore di inizializzazione casuale.</li><li>Fate clic sulla matita per visualizzare il valore iniziale corrente e immettete un valore specifico.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Gonfiamento o ritiro</strong></td>
    <td>Passate dalla modalità gonfia a quella Riduci a capo.</td>
  </tr>
  <tr>
    <td><strong>Intensità giuntura</strong></td>
    <td>Regolate l’intensità dei bordi.</td>
  </tr>
  <tr>
    <td><strong>Larghezza bordo in rilievo</strong></td>
    <td>Regolate il rigonfiamento dei bordi.</td>
  </tr>
  <tr>
    <td><strong>Intensità bordo rialzato</strong></td>
    <td>Regolate l’intensità dell’effetto del bordo in rilievo.</td>
  </tr>
  <tr>
    <td><strong>Densità delle pieghe</strong></td>
    <td>Regolate il numero di rughe.</td>
  </tr>
  <tr>
    <td><strong>Rugosità</strong></td>
    <td>Regolate l’intensità delle rughe sui bordi UV.</td>
  </tr>
  <tr>
    <td><strong>Intervallo rughe</strong></td>
    <td>Regolate la distanza delle rughe dai bordi UV.</td>
  </tr>
  <tr>
    <td><strong>Scala rughe</strong></td>
    <td>Regolate la dimensione delle rughe.</td>
  </tr>
</table>

### Parametri tecnici

| Nome parametro | Descrizione |
| --- | --- |
| **Intervallo Height** | Imposta l’intervallo height. |
| **Posizione Height** | Regolate il height verso il nero (0) o il bianco (1). |
| **Dimensioni superficie (cm)** | Impostate la dimensioni fisiche della superficie. |
| **Profondità di superficie (cm)** | Impostate la profondità fisica della superficie. |
