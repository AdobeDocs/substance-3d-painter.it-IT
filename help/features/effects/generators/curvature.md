---
title: Curvatura
description: Scoprite come utilizzare il generatore di curvatura di Substance 3D Painter.
source-git-commit: b095b9b437f75bbb3a3b85ee84a6850026c3bf98
workflow-type: tm+mt
source-wordcount: '597'
ht-degree: 4%

---


# Curvatura

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_curvature.webp" alt=""/><br><strong>Ingresso:</strong> maschera, generatore, scala di grigi, fusione</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di curvatura crea una maschera basata sulla mappa di curvatura cotta con l'opzione per fondere una texture o micro dettagli nella maschera.<br><br>Il generatore di curvatura genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere anziché applicarle direttamente a un livello.<br><br>Per l'input è necessaria una mappa di posizione al forno. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Texture** | Usate una texture o un punto di ancoraggio personalizzato. |
| Colore **Micro-Normale** | Usate una texture normale personalizzata o un punto di ancoraggio. |
| Colore **Micro Height** | Usate una texture o un punto di ancoraggio personalizzato. |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura. |
| Colore **Normali spazio globale** | Utilizzate la mappa standard di World Space. |
| Colore **Sfumatura posizione** | Utilizzate la mappa di posizione al forno. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inversione globale** | Inverte il risultato finale dopo aver combinato tutti gli effetti. |
| **Sfocatura globale** | Ammorbidisce la maschera finale in modo uniforme dopo aver combinato tutti gli effetti. |
| **Saldo globale** | Consente di spostare il bilanciamento della maschera finale quando tutti gli effetti vengono combinati in bianco o nero, ad esempio con una regolazione della luminosità. |
| **Contrasto globale** | Regola il contrasto della maschera finale dopo aver combinato tutti gli effetti. |
| **Usa texture** | Attivate o disattivate l’utilizzo di una mappa texture personalizzata. |
| **Usa dettagli micro** | Attivare o disattivare l’utilizzo della mappa dei micro dettagli personalizzata. |

### Curvatura

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite la mappa di curvatura generata.</td>
  </tr>
  <tr>
    <td><strong>Modalità</strong></td>
    <td>Impostate la modalità Curvatura. <br><ul><li><strong>Bordi</strong>: maschera i bordi (aree convesse)</li><li><strong>Cavità</strong>: maschera le cavità (aree concave)</li><li><strong>Doppio</strong>: maschera aree concave e convesse.</li><li><strong>Non elaborato</strong>: maschera di curvatura normale.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Preciso</strong></td>
    <td>Regolate l'intensità dei dettagli di curvatura nitida.</td>
  </tr>
  <tr>
    <td><strong>Fine</strong></td>
    <td>Regolate l'intensità dei dettagli di curvatura più fini.</td>
  </tr>
  <tr>
    <td><strong>Morbido</strong></td>
    <td>Regolate l’intensità dei dettagli di curvatura morbidi.</td>
  </tr>
  <tr>
    <td><strong>Medio</strong></td>
    <td>Regolate l'intensità dei dettagli di curvatura media.</td>
  </tr>
  <tr>
    <td><strong>Grande</strong></td>
    <td>Regolate l'intensità dei dettagli di curvatura più grandi.</td>
  </tr>
  <tr>
    <td><strong>Grande</strong></td>
    <td>Regolate l'intensità dei dettagli di curvatura più grandi.</td>
  </tr>
  <tr>
    <td><strong>Enorme</strong></td>
    <td>Regolate l'intensità dei dettagli di curvatura enormi.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Regolate il contrasto/decadimento della curvatura.</td>
  </tr>
  <tr>
    <td><strong>Luminosità</strong></td>
    <td>Regolate la luminosità della curvatura.</td>
  </tr>
</table>

### Texture

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Opacità texture</strong></td>
    <td>Controllate la visibilità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite solo la texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Conversione in scala di grigi</strong></td>
    <td>Seleziona il metodo utilizzato per convertire l’input a colori in bianco e nero. </td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Impostate il metodo di fusione per la texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Scala</strong></td>
    <td>Regolate le dimensioni della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Impostate il contrasto/decadimento della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Luminosità</strong></td>
    <td>Impostate la luminosità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Triplanare</strong></td>
    <td>Quando Triplanare è attivato, la texture viene proiettata da tre direzioni (assi X, Y, Z) invece di fare affidamento solo sugli UV. <br><ul><li>Senza l’opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l’opzione triplanare attivata, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto triplanare</strong></td>
    <td>Regolate l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
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
    <td>Regolate l'intensità della curvatura nelle <strong>modalità di curvatura standard </strong> e <strong>Sobel </strong>.</td>
  </tr>
  <tr>
    <td><strong>Intensità dettagli height</strong></td>
    <td>Regolate l'intensità dei dettagli del Micro Height.</td>
  </tr>
</table>
