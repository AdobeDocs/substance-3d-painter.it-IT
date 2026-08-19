---
description: Scopri come utilizzare il generatore World Space Normals di Substance 3D Painter.
title: Normali spazio globale
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '567'
ht-degree: 4%

---


# Normali spazio globale

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_world_space_normals.png" alt=""/><br><strong>Ingresso:</strong> maschera, generatore, scala di grigi, fusione</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore Normale spazio mondo utilizza la mappa normale dello spazio mondo cotta per colorare il modello o applicare effetti in base alla direzione verso cui ogni superficie è rivolta nello spazio 3D. Ad esempio, dall’alto verso il basso.<br><br>Il generatore World Space Normals genera una texture monocromatica (bianco e nero). Di conseguenza, è utile generare le maschere per applicare vari effetti come dirt, dust, neve o ruggine in base alle direzioni del volto.<br><br>Per l'input dell'immagine sono necessarie mappe normali della posizione e dello spazio globale. <a href="../../../baking/baking.md">Ulteriori informazioni sulla cottura</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Texture** | Usate una texture personalizzata o un punto di ancoraggio. |
| Colore **Normali spazio globale** | Utilizzate la mappa standard di World Space. |
| Colore **Sfumatura posizione** | Utilizzate la mappa di posizione al forno. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inversione globale** | Invertite il risultato finale dopo aver combinato tutti gli effetti. |
| **Sfocatura globale** | Ammorbidite la maschera finale in modo uniforme dopo aver combinato tutti gli effetti. |
| **Saldo globale** | Dopo aver combinato tutti gli effetti con il bianco o il nero, spostate il bilanciamento della maschera finale, ad esempio regolando la luminosità. |
| **Contrasto globale** | Dopo aver combinato tutti gli effetti, regolate il contrasto della maschera finale. |
| **Usa texture** | Attivate o disattivate l’utilizzo di una mappa texture personalizzata. |

### Mappa spazio mondiale

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite solo le normali dello spazio mondiale. |
| **Sfocatura** | Smussate solo le normali spaziali mondiali. |
| **Saldo** | Regola solo il bilanciamento delle normali dello spazio mondo, spostando il punto medio verso il bianco o il nero come un controllo della luminosità. |
| **Contrasto** | Regolate solo il contrasto/decadimento delle normali nello spazio mondo. |
| **Luminosità** | Regolate la luminosità solo delle normali dello spazio mondo. |
| **Da destra a sinistra** | Regolate l’applicazione dell’effetto da sinistra a destra attraverso la trama. |
| **Dall&#39;alto verso il basso** | Regolate l’applicazione dell’effetto dall’alto verso il basso attraverso la trama. |
| **Da sopra a sotto** | Regola il modo in cui l’effetto viene applicato dalla parte anteriore a quella posteriore della trama. |

#### Spazio globale normale/da destra a sinistra

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione della sfumatura da destra a sinistra. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |

#### Spazio mondo normale/Dall’alto verso il basso

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione del gradiente dall’alto verso il basso. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |

#### Spazio globale normale/da sopra a sotto

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Invertite la direzione della sfumatura da davanti a dietro. |
| **Metodo fusione** | Seleziona il [metodo di fusione](../../../interface/layer-stack/blending-modes.md) da utilizzare per il livello corrente. |

### Texture

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Opacità texture</strong></td>
    <td>Regolate la visibilità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite solo la texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Conversione in scala di grigi</strong></td>
    <td>Imposta il metodo usato per convertire dal colore completo al grigio. Il generatore di conversione <a href="grayscale-conversion.md">scala di grigi fornisce ulteriori informazioni sul funzionamento di ciascun metodo</a>.</td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Regolate l'operazione di fusione da utilizzare. Consultate la pagina dedicata ai metodi di fusione.</td>
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
    <td>Quando Triplanare è attivato, la texture viene proiettata da tre direzioni (assi X, Y, Z) invece di fare affidamento solo sugli UV.<br><ul><li>Senza triplanare, la texture segue il layout UV.</li><li>Con triplanare, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto triplanare</strong></td>
    <td>Regolate l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. In questo modo si regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
</table>
