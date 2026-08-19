---
title: Edge Wear metallico
description: Scopri come utilizzare il generatore di Edge Wear Metal di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '541'
ht-degree: 1%

---


# Edge Wear metallico

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_metal_edge_wear.webp" alt=""/><br><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di Edge Wear metallico dà l'impressione di danneggiare e consumare le aree della trama che potrebbero essere urtate o graffiate.<br><br>Il generatore di Edge Wear Metal genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere per aggiungere dettagli di usura dei bordi a un livello.<br><br>Per l'input dell'immagine sono necessarie mappe di posizione, curvatura, occlusione ambientale e spazio globale normale. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Spazio globale normale** colore | Utilizzate la mappa Normale di World Space. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |
| **grunge personalizzata** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura. |
| **Occlusione ambiente** Scala di grigi | Utilizzate la mappa di Occlusione ambiente cotta. |
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
    <td>Invertite la maschera di usura dei bordi in metallo.</td>
  </tr>
  <tr>
    <td><strong>Livello usura</strong></td>
    <td>Impostare la quantità totale di usura.</td>
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
    <td>Regolate la quantità dei dettagli della grunge.</td>
  </tr>
  <tr>
    <td><strong>Scala grungi</strong></td>
    <td>Regolate la scala dei dettagli della grunge.</td>
  </tr>
  <tr>
    <td><strong>Usa Grunge personalizzata</strong></td>
    <td>Attivare o disattivare l'utilizzo di una mappa grunge personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Smoothness bordi</strong></td>
    <td>Regolate lo smoothness dei bordi complessivi.</td>
  </tr>
  <tr>
    <td><strong>Mascheratura Occlusione ambientale</strong></td>
    <td>Utilizzate l’occlusione ambiente come maschera per evitare che le aree ostruite ricevano l’effetto dell’invecchiamento.</td>
  </tr>
  <tr>
    <td><strong>Spessore curvatura</strong></td>
    <td>Regolate in che misura la mappa di curvatura influisce sul risultato finale. La mappa di curvatura è ciò che il generatore utilizza per definire i bordi, quindi uno spessore di curvatura molto basso può rimuovere tutta l'usura dei bordi, lasciando solo le grungi.</td>
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
    <td>Impostate il tipo di curvatura. <br><ul><li><strong>Standard</strong>: consente di ottenere risultati abbastanza netti, ma possono mancare dettagli più ampi.</li><li><strong>Sobel</strong>: produce risultati simili a quelli standard, ma leggermente più sfocati perché valuta la mappa normale utilizzando un filtro Sobel.</li><li><strong>Uniforme</strong>: genera diversi livelli di sfocatura (come mipmap) per accumulare informazioni. In questo modo, di solito, si ottengono curve più uniformi, ma i dettagli possono andare perduti.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Intensità curvatura</strong></td>
    <td>Regolate l'intensità della curvatura in <strong>Modalità curvatura standard </strong>e <strong>Sobel </strong>.</td>
  </tr>
  <tr>
    <td><strong>Intensità dettagli height</strong></td>
    <td>Regola l’intensità dei dettagli del Micro Height.</td>
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
