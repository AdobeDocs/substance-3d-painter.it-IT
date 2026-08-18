---
title: Editor maschera
description: Scoprite come utilizzare il generatore Editor maschera di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '1494'
ht-degree: 3%

---


# Editor maschera

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_mask_editor_dark.png" alt=""/><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore dell’editor maschere è un generatore di maschere multifunzione che consente di combinare texture, Occlusione ambientale, curvatura, spazio normale, sfumatura, Thickness e micro dettagli in un’unica maschera.<br>Il generatore di generatori di maschere è molto flessibile, ma a causa della sua complessità, può influire sulle prestazioni più della maggior parte dei generatori.<br><br>Il generatore dell'editor maschere genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere basate sulle varie mappe con baking. <br><br>Per l'input dell'immagine sono necessarie mappe di posizione, thickness, curvatura, occlusione ambientale e spazio globale normale. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Texture** | Usate una texture personalizzata o un punto di ancoraggio. |
| Colore **Texture (secondaria)** | Usate una texture personalizzata o un punto di ancoraggio. |
| Colore **Normali spazio globale** | Utilizzate la mappa standard di World Space. |
| Colore **Sfumatura posizione** | Utilizzate la mappa di posizione al forno. |
| **Thickness** in scala di grigi | Usa la mappa del Thickness cotto. |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura. |
| **Occlusione ambiente** Scala di grigi | Utilizzate la mappa di Occlusione ambiente cotta. |
| Colore **Micro-Normale** | Usate una texture normale personalizzata o un punto di ancoraggio. |
| Colore **Micro Height** | Usate una texture personalizzata o un punto di ancoraggio. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inversione globale** | Inverti il risultato finale dopo aver combinato tutti i livelli. |
| **Sfocatura globale** | Sfoca la maschera finale in modo uniforme dopo aver combinato tutti i livelli. |
| **Saldo globale** | Regola il bilanciamento della maschera finale dopo che tutti i livelli sono stati combinati in bianco o nero, come avviene per la regolazione della luminosità. |
| **Contrasto globale** | Regola il contrasto della maschera finale dopo aver combinato tutti i livelli. |
| **Opacità texture** | Regolate la visibilità della texture personalizzata. |
| **Opacità Texture 2** | Regolate la visibilità della seconda texture personalizzata. |
| **Opacità Occlusione ambiente** | Regola la visibilità dei dettagli di occlusione dell&#39;ambiente. |
| **Opacità curvatura** | Regolate la visibilità dei dettagli di curvatura. |
| **Opacità normale spazio globale** | Regola la visibilità dei dettagli normali dello spazio mondo. |
| **Opacità sfumatura posizione** | Regola la visibilità dei dettagli della posizione. |
| **Opacità Thickness** | Regola la visibilità dei dettagli del thickness. |

### Texture

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Inverte la texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Conversione in scala di grigi</strong></td>
    <td>Imposta il metodo usato per convertire dal colore completo al grigio. Il generatore di conversione <a href="grayscale-conversion.md">scala di grigi fornisce ulteriori informazioni sul funzionamento di ciascun metodo</a>.</td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Seleziona il <a href="../../../interface/layer-stack/blending-modes.md">metodo di fusione</a> da utilizzare per il livello corrente.</td>
  </tr>
  <tr>
    <td><strong>Scala</strong></td>
    <td>Regolate le dimensioni della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Regolate il contrasto/decadimento della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Luminosità</strong></td>
    <td>Regola la luminosità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Triplanare</strong></td>
    <td>Quando l’opzione <strong>Usa triplanare </strong> è abilitata, la texture viene proiettata da tre direzioni (assi X, Y, Z) anziché dipendere solo dagli UV. <br><ul><li>Senza l’opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l’opzione triplanare attivata, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto triplanare</strong></td>
    <td>Regolate l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
  <tr>
    <td><strong>Affiancatura non quadrata</strong></td>
    <td>Attiva o disattiva l'affiancatura non quadrata.</td>
  </tr>
</table>

### Texture 2

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite la texture secondaria personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Conversione in scala di grigi</strong></td>
    <td>Imposta il metodo usato per convertire dal colore completo al grigio. Il generatore di conversione <a href="grayscale-conversion.md">scala di grigi fornisce ulteriori informazioni sul funzionamento di ciascun metodo</a>.</td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Seleziona il <a href="../../../interface/layer-stack/blending-modes.md">metodo di fusione</a> da utilizzare per il livello corrente.</td>
  </tr>
  <tr>
    <td><strong>Scala</strong></td>
    <td>Regolate le dimensioni della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Regolate il contrasto/decadimento della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Luminosità</strong></td>
    <td>Regola la luminosità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Triplanare</strong></td>
    <td>Quando l’opzione <strong>Usa triplanare </strong> è abilitata, la texture viene proiettata da tre direzioni (assi X, Y, Z) anziché dipendere solo dagli UV. <br><ul><li>Senza l’opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l’opzione triplanare attivata, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto triplanare</strong></td>
    <td>Regolate l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
  <tr>
    <td><strong>Affiancatura non quadrata</strong></td>
    <td>Attiva o disattiva l'affiancatura non quadrata.</td>
  </tr>
</table>

### Occlusione ambientale

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Inverti i livelli Occlusione ambiente e Dettagli micro. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |
| **Sfocatura** | Regolate l&#39;Occlusione ambiente e la morbidezza dei dettagli micro. |
| **Saldo** | Regola il bilanciamento dell&#39;Occlusione ambiente e dei micro dettagli, spostando il punto medio verso il bianco o il nero come un controllo della luminosità. |
| **Contrasto** | Regola il contrasto/decadimento dell&#39;Occlusione ambiente e i micro dettagli. |

### Curvatura

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite la curvatura.</td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Seleziona il <a href="../../../interface/layer-stack/blending-modes.md">metodo di fusione</a> da utilizzare per il livello corrente.</td>
  </tr>
  <tr>
    <td><strong>Modalità</strong></td>
    <td>Impostate la modalità Curvatura. <br><ul><li><strong>Bordi</strong>: maschera i bordi (aree convesse)</li><li><strong>Cavità</strong>: maschera le cavità (aree concave)</li><li><strong>Doppio</strong>: maschera aree concave e convesse.</li><li><strong>Non elaborato</strong>: maschera di curvatura normale.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Preciso</strong></td>
    <td>Regolate la visibilità dei dettagli di curvatura nitida.</td>
  </tr>
  <tr>
    <td><strong>Fine</strong></td>
    <td>Regolate la visibilità dei dettagli di curvatura più fini.</td>
  </tr>
  <tr>
    <td><strong>Morbido</strong></td>
    <td>Regolate la visibilità dei dettagli di curvatura morbida.</td>
  </tr>
  <tr>
    <td><strong>Medio</strong></td>
    <td>Regolate la visibilità dei dettagli di curvatura medi.</td>
  </tr>
  <tr>
    <td><strong>Grande</strong></td>
    <td>Regolate la visibilità dei dettagli di curvatura di grandi dimensioni.</td>
  </tr>
  <tr>
    <td><strong>Grande</strong></td>
    <td>Regolate la visibilità dei grandi dettagli di curvatura.</td>
  </tr>
  <tr>
    <td><strong>Enorme</strong></td>
    <td>Regolate la visibilità dei dettagli di curvatura enormi.</td>
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

### Mappa spazio mondiale

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite le normali spaziali mondiali. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |
| **Sfocatura** | Regola la morbidezza normale dello spazio mondo. |
| **Saldo** | Regola il bilanciamento delle normali dello spazio mondiale, spostando il punto medio verso il bianco o il nero come un controllo della luminosità. |
| **Contrasto** | Regolate il contrasto/decadimento delle normali spaziali mondiali. |
| **Luminosità** | Regolate la luminosità delle normali dello spazio mondo. |
| **Da destra a sinistra** | Regolate l’applicazione dell’effetto da sinistra a destra attraverso la trama. |
| **Dall&#39;alto verso il basso** | Regolate l’applicazione dell’effetto dall’alto verso il basso attraverso la trama. |
| **Da sopra a sotto** | Regola il modo in cui l’effetto viene applicato dalla parte anteriore a quella posteriore della trama. |

### Spazio globale normale/da destra a sinistra

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Inverte la direzione da destra a sinistra. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |

### Spazio mondo normale/Dall’alto verso il basso

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione dall’alto verso il basso. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |

### Spazio globale normale/da sopra a sotto

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertire la direzione da anteriore a posteriore. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |

### Posizione sfumatura

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite il livello della sfumatura della posizione. |
| **Saldo** | Regola il bilanciamento del livello sfumatura posizione, spostando il punto medio verso il bianco o il nero come un controllo della luminosità. |
| **Contrasto** | Regola il contrasto/decadimento del livello sfumatura posizione. |
| **Luminosità** | Regola la luminosità del livello sfumatura posizione. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |
| **Da destra a sinistra** | Regolate l’applicazione dell’effetto da sinistra a destra attraverso la trama. |
| **Dall&#39;alto verso il basso** | Regolate l’applicazione dell’effetto dall’alto verso il basso attraverso la trama. |
| **Da sopra a sotto** | Regola il modo in cui l’effetto viene applicato dalla parte anteriore a quella posteriore della trama. |

>[!TIP]
>
> La sfumatura Posizione è composta da un massimo di tre sfumature, da destra a sinistra, dall’alto verso il basso e dall’alto verso il retro. Ciascuna delle sfumature secondarie ha un proprio metodo di fusione che può essere utilizzato per creare effetti diversi o mascherare aree diverse del modello. I metodi di fusione per queste sfumature interagiscono solo tra di loro per creare un livello di sfumatura Posizione finale, ma non interagiscono direttamente con altri livelli nel generatore all’esterno della sfumatura posizione.

### Sfumatura posizione - Da destra a sinistra

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione della sfumatura da destra a sinistra. |
| **Metodo fusione** | Selezionare il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per la sfumatura da destra a sinistra. |

### Sfumatura posizione - Dall&#39;alto verso il basso

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione del gradiente dall’alto verso il basso. |
| **Metodo fusione** | Selezionare il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per la sfumatura dall&#39;alto verso il basso. |

### Sfumatura posizione - Da sopra a sotto

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione della sfumatura da davanti a dietro. |
| **Metodo fusione** | Selezionare il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per la sfumatura anteriore-posteriore. |

### Spessore

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite il thickness. |
| **Sfocatura** | Regola la morbidezza dei dettagli nel livello thickness. |
| **Contrasto** | Regola il contrasto/decadimento del livello thickness. |
| **Luminosità** | Regola la luminosità del livello thickness. |

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
    <td>Regolate l'intensità della curvatura in modalità <strong>Standard</strong> e <strong>Sobel </strong>Curvatura.</td>
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
