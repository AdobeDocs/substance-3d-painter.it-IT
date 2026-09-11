---
title: Edge Wear in fibra di vetro
description: Scoprite come utilizzare il generatore di Edge Wear in fibra di vetro di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 1%

---


# Edge Wear in fibra di vetro

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_fiber_glass_edge_wear.webp" alt=""/><br><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di Edge Wear in fibra di vetro aggiunge un'usura realistica dei bordi in fibra di vetro e dettagli di sfilacciamento basati su mappe di curvatura e Occlusione ambientale eseguite i baking. Facoltativamente, per ulteriori dettagli è possibile utilizzare anche Micro Height e Micro Mappa normale.<br><br>Il generatore di Edge Wear in fibra di vetro genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere per aggiungere dettagli di usura dei bordi in fibra di vetro a un livello.<br><br>Sono necessarie mappe Eseguite i baking di posizione, curvatura, occlusione ambientale e spazio globale come input dell'immagine. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **grunge personalizzata** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura eseguita i baking. |
| **Occlusione ambientale** Scala di grigi | Usa la mappa di Occlusione ambientale eseguita i baking. |
| Colore **Spazio globale normale** | Utilizzare la mappa eseguita i baking World Space Normals. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |
| Colore **Micro-Normale** | Utilizzate una texture normale personalizzata o un punto di ancoraggio. |
| Colore **Micro Height** | Usate una texture personalizzata o un punto di ancoraggio. |

## Parametri

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Seed</strong></td>
    <td>Impostate il valore di inizializzazione utilizzato per generare la texture di dirt. <br><ul><li>Fate clic su Casuale per passare a un altro valore di inizializzazione casuale.</li><li>Fate clic sulla matita per visualizzare il valore iniziale corrente e immettete un valore specifico.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite mappe interne specifiche (ad esempio, Curvatura, AO) prima di combinarle nella maschera finale.</td>
  </tr>
  <tr>
    <td><strong>Livello usura</strong></td>
    <td>Regola la quantità totale di usura e la visibilità complessiva dell'effetto generatore.</td>
  </tr>
  <tr>
    <td><strong>Indossare il contrasto</strong></td>
    <td>Regolare il contrasto del risultato finale di usura.</td>
  </tr>
  <tr>
    <td><strong>Usa triplanare</strong></td>
    <td>Quando l'opzione <strong>Usa triplanare </strong> è abilitata, la texture viene proiettata da tre direzioni (assi X, Y, Z) anziché basarsi solo sugli UV. <br><ul><li>Senza l'opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l'opzione triplanare attivata, la texture viene proiettata da più angolazioni e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto fusione triplanare</strong></td>
    <td>Regola l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
  <tr>
    <td><strong>Quantità grungi</strong></td>
    <td>Regolate l’intensità dei dettagli delle grungi.</td>
  </tr>
  <tr>
    <td><strong>Usa Grunge personalizzata</strong></td>
    <td>Attivare o disattivare l'utilizzo di una mappa grunge personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Smoothness bordi</strong></td>
    <td>Regola la morbidezza dell'effetto usura bordi.</td>
  </tr>
  <tr>
    <td><strong>Mascheratura Occlusioni ambientali</strong></td>
    <td>Regola l’influenza della mappa di occlusione ambientale sul risultato.</td>
  </tr>
  <tr>
    <td><strong>Spessore curvatura</strong></td>
    <td>Regolate l’influenza della mappa di curvatura sul risultato.</td>
  </tr>
</table>

### Dettagli micro

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Micro Height</strong></td>
    <td>Attivare o disattivare l'utilizzo di una mappa personalizzata dell'altezza della micro.</td>
  </tr>
  <tr>
    <td><strong>Micro Normale</strong></td>
    <td>Attivare o disattivare l'utilizzo di una Micro Mappa normale personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Tipo curvatura</strong></td>
    <td>Determina il tipo di curvatura. <br><ul><li><strong>Standard</strong>: consente di ottenere risultati abbastanza netti, ma possono mancare dettagli più ampi.</li><li><strong>Sobel</strong>: produce risultati simili a quelli standard, ma leggermente più sfocati perché valuta la mappa normale utilizzando un filtro Sobel.</li><li><strong>Uniforme</strong>: genera diversi livelli di sfocatura (come mipmap) per accumulare informazioni. In questo modo, di solito, si ottengono curve più uniformi, ma i dettagli possono andare perduti.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Intensità curvatura</strong></td>
    <td>Regolate l’intensità della curvatura nelle modalità Curvatura standard e obel.</td>
  </tr>
  <tr>
    <td><strong>Intensità dettagli height</strong></td>
    <td>Regola la quantità dei dettagli del Micro Height.</td>
  </tr>
  <tr>
    <td><strong>Raggio AO</strong></td>
    <td>Regolate il raggio (intervallo) dell’Occlusione ambientale nei micro dettagli.</td>
  </tr>
  <tr>
    <td><strong>PROFONDITÀ AO</strong></td>
    <td>Regolate la profondità (intensità) dell’Occlusione ambientale nei micro dettagli.</td>
  </tr>
</table>
