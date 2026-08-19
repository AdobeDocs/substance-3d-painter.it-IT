---
title: Terra
description: Scopri come utilizzare il generatore di Dirt di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '528'
ht-degree: 1%

---


# Terra

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_dirt.webp" alt=""/><br><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di Dirt aggiunge un accumulo realistico di dirt e grunge in fessure, bordi e superfici piane in base alla curvatura e all'occlusione ambientale. Facoltativamente, puoi anche utilizzare le mappe Micro Height e Micro Normal per aggiungere più dettagli.<br><br>Il generatore di Dirt genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile generare delle maschere per aggiungere dettagli di dirt o grunge al modello.<br><br>Per l'input dell'immagine sono necessarie mappe normali di posizione, curvatura, occlusione ambientale e spazio globale. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

>[!NOTE]
>
> Il generatore di Dirt è uno strumento potente che consente di aggiungere rapidamente dirt alla trama. Per risultati ottimali, consigliamo di utilizzare maschere aggiuntive per controllare come viene applicato il dirt, tenendo sempre conto dell’ambiente e della cronologia della risorsa.

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura. |
| **Occlusione ambiente** Scala di grigi | Utilizzate la mappa di Occlusione ambiente cotta. |
| Colore **Spazio globale normale** | Utilizzate la mappa standard di World Space. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |
| **grunge personalizzata** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
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
    <td>Invertite la maschera del dirt.</td>
  </tr>
  <tr>
    <td><strong>Livello dirt</strong></td>
    <td>Regolate l’intensità dell’effetto dirt.</td>
  </tr>
  <tr>
    <td><strong>Contrasto dirt</strong></td>
    <td>Regolate il contrasto dell’effetto dirt.</td>
  </tr>
  <tr>
    <td><strong>Usa triplanare</strong></td>
    <td>Quando Triplanare è attivato, la texture viene proiettata da tre direzioni (assi X, Y, Z) invece di fare affidamento solo sugli UV. <br><ul><li>Senza l’opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l’opzione triplanare attivata, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto fusione triplanare</strong></td>
    <td>Regolate l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. Regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
  <tr>
    <td><strong>Quantità grungi</strong></td>
    <td>Regolate l’intensità dei dettagli delle grungi.</td>
  </tr>
  <tr>
    <td><strong>Scala grungi</strong></td>
    <td>Regolate le dimensioni dei dettagli della grunge.</td>
  </tr>
  <tr>
    <td><strong>Usa Grunge personalizzata</strong></td>
    <td>Attivare o disattivare l'utilizzo di una mappa grunge personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Mascheratura bordi</strong></td>
    <td>Regolate la mascheratura dei bordi in base alla mappa di curvatura.</td>
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
