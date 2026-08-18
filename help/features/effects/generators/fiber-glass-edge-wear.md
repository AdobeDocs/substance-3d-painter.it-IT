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
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di Edge Wear in fibra di vetro aggiunge un'usura realistica dei bordi in fibra di vetro e dettagli di sfilacciamento basati su mappe curvatura cotte e Occlusione ambientale. Facoltativamente, è anche possibile utilizzare le mappe Micro Height e Micro Normal per ulteriori dettagli.<br><br>Il generatore di Edge Wear in fibra di vetro genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere per aggiungere dettagli di usura dei bordi in fibra di vetro a un livello.<br><br>Per l'input dell'immagine sono necessarie mappe normali di posizione, curvatura, occlusione ambientale e spazio globale. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **grunge personalizzata** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura. |
| **Occlusione ambiente** Scala di grigi | Utilizzate la mappa di Occlusione ambiente cotta. |
| Colore **Spazio globale normale** | Utilizzate la mappa standard di World Space. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |
| Colore **Micro-Normale** | Usate una texture normale personalizzata o un punto di ancoraggio. |
| Colore **Micro Height** | Usate una texture personalizzata o un punto di ancoraggio. |

## Parametri

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Seed</strong></td>
    <td>Impostate il valore di partenza utilizzato per generare la texture del dirt. <br><ul><li>Fate clic su Casuale per passare a un altro valore di inizializzazione casuale.</li><li>Fate clic sulla matita per visualizzare il valore iniziale corrente e immettete un valore specifico.</li></ul></td>
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
    <td>Quando l’opzione <strong>Usa triplanare </strong> è abilitata, la texture viene proiettata da tre direzioni (assi X, Y, Z) anziché dipendere solo dagli UV. <br><ul><li>Senza l’opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l’opzione triplanare attivata, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto fusione triplanare</strong></td>
    <td>Regolate l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
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
    <td><strong>Mascheratura Occlusione ambientale</strong></td>
    <td>Regola l'influenza della mappa di occlusione ambiente sul risultato.</td>
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
    <td>Attivare o disattivare l'utilizzo di una mappa di Micro Height personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Micro Normale</strong></td>
    <td>Attivare o disattivare l'utilizzo di una mappa Micro Normal personalizzata.</td>
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
    <td>Regola il raggio (intervallo) dell'Occlusione Ambiente nei micro dettagli.</td>
  </tr>
  <tr>
    <td><strong>PROFONDITÀ AO</strong></td>
    <td>Regola la profondità (intensità) dell'Occlusione ambiente nei micro dettagli.</td>
  </tr>
</table>
