---
title: Posiz.
description: Scopri come utilizzare il generatore di posizione di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '537'
ht-degree: 3%

---


# Posizione

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_position.webp" alt=""/><br><strong>Entrata:</strong> mesh, uv, distanza</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore Posizione utilizza le mappe normali di posizione e spazio mondo eseguite i baking per creare una maschera sfumatura in base alla posizione del materiale nello spazio 3D (come dall’alto verso il basso o da un lato all’altro).<br><br>Il generatore Posizione genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere con sfumature basate sulla posizione nello spazio mondo.<br><br>Per l'input dell'immagine sono necessarie mappe normali di posizione Eseguita i baking e di spazio mondo. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Texture** | Usate una texture personalizzata o un punto di ancoraggio. |
| Colore **Sfumatura posizione** | Utilizzate la mappa di posizione al forno. |
| Colore **Normali spazio globale** | Utilizzare la mappa eseguita i baking World Space Normals. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inversione globale** | Invertite il risultato finale dopo aver combinato tutti gli effetti. |
| **Sfocatura globale** | Sfocate la maschera finale in modo uniforme dopo aver combinato tutte le sfumature. |
| **Saldo globale** | Regolate il bilanciamento della maschera finale dopo aver combinato tutte le sfumature tra il bianco e il nero, come avviene con una regolazione della luminosità. |
| **Contrasto globale** | Regolate il contrasto della maschera finale dopo aver combinato tutte le sfumature. |
| **Usa Texture** | Attivate o disattivate l’utilizzo di una mappa texture personalizzata. |

### Posizione sfumatura

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite solo la sfumatura della posizione. |
| **Saldo** | Regola il bilanciamento della sola sfumatura di posizione, spostando il punto medio verso il bianco o il nero come un controllo della luminosità. |
| **Contrasto** | Regolate il contrasto/decadimento solo della sfumatura di posizione. |
| **Luminosità** | Regolate la luminosità solo della sfumatura di posizione. |
| **Da destra a sinistra** | Regolate l’applicazione dell’effetto da sinistra a destra attraverso la trama. |
| **Dall&#39;alto verso il basso** | Regolate l’applicazione dell’effetto dall’alto verso il basso attraverso la trama. |
| **Da sopra a sotto** | Regola il modo in cui l’effetto viene applicato dalla parte anteriore a quella posteriore della trama. |

#### Posiziona sfumatura/Da destra a sinistra

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione della sfumatura da destra a sinistra. |
| **Metodo fusione** | Selezionare il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per la sfumatura da destra a sinistra. |

#### Posiziona sfumatura/Dall’alto verso il basso

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione del gradiente dall’alto verso il basso. |
| **Metodo fusione** | Selezionare il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per la sfumatura dall&#39;alto verso il basso. |

#### Posiziona sfumatura/Da davanti a dietro

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione della sfumatura da davanti a dietro. |
| **Metodo fusione** | Selezionare il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per la sfumatura anteriore-posteriore. |

### Texture

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Opacità texture</strong></td>
    <td>Regola la visibilità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertire la mappa texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Conversione in scala di grigi</strong></td>
    <td>Imposta il metodo usato per convertire dal colore completo al grigio. Il generatore di <a href="grayscale-conversion.md">Conversioni in scala di grigi contiene ulteriori informazioni sul funzionamento di ciascun metodo</a>.</td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Selezionare il <a href="../../../interface/layer-stack/blending-modes.md">metodo di fusione</a> da utilizzare.</td>
  </tr>
  <tr>
    <td><strong>Scala</strong></td>
    <td>Regolate le dimensioni della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Regola il contrasto/decadimento della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Luminosità</strong></td>
    <td>Regola la luminosità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Triplanare</strong></td>
    <td>Quando l'opzione <strong>Usa triplanare </strong> è abilitata, la texture viene proiettata da tre direzioni (assi X, Y, Z) anziché basarsi solo sugli UV. <br><ul><li>Senza l'opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l'opzione triplanare attivata, la texture viene proiettata da più angolazioni e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto triplanare</strong></td>
    <td>Regola l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
</table>
