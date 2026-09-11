---
title: Occlusione ambientale
description: Scopri come utilizzare il generatore di Occlusioni ambientali di Substance 3D Painter.
source-git-commit: b095b9b437f75bbb3a3b85ee84a6850026c3bf98
workflow-type: tm+mt
source-wordcount: '542'
ht-degree: 4%

---


# Occlusione ambientale

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_ambient_occlusion.webp" alt=""/><br><strong>Ingresso:</strong> maschera, generatore, scala di grigi, fusione</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di Occlusioni ambientali crea una maschera basata sulla mappa di Occlusione ambientale eseguita i baking con l'opzione per fondere una texture o micro dettagli nella maschera.<br><br>Se utilizzi il generatore di Occlusioni ambientali per creare una maschera di livello, potresti dover invertire l’output delle Occlusioni ambientali. Per impostazione predefinita, il generatore emette le aree occluse come scure e quelle non occluse come chiare. Se utilizzato come maschera, il livello mascherato è visibile solo nelle aree non occluse. Invertendo l’output, il livello mascherato apparirà solo nelle aree occluse.<br><br>Come input dell'immagine sono necessarie mappe normali di posizione, occlusione ambientale e spazio globale Eseguite i baking. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Texture colore | Usate una texture personalizzata o un punto di ancoraggio. |
| Colore micro-normale | Utilizzate una texture normale personalizzata o un punto di ancoraggio. |
| Colore micro Height | Usate una texture personalizzata o un punto di ancoraggio. |
| Occlusione ambientale scala di grigi | Usa la mappa di Occlusione ambientale eseguita i baking. |
| Colore normali spazio globale | Utilizzare la mappa eseguita i baking World Space Normals. |
| Posiziona colore sfumatura | Usa la mappa Posizione eseguita i baking. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Inversione globale** | Invertite il risultato finale dopo aver combinato tutti gli effetti. |
| **Sfocatura globale** | Una volta combinati tutti gli effetti, uniformate la maschera finale. |
| **Saldo globale** | Dopo aver combinato tutti gli effetti con il bianco o il nero, spostate il bilanciamento della maschera finale, ad esempio regolando la luminosità. |
| **Contrasto globale** | Dopo aver combinato tutti gli effetti, regolate il contrasto della maschera finale. |
| **Usa Texture** | Attivate o disattivate l’utilizzo di una mappa texture personalizzata. |
| **Usa dettagli micro** | Attivate o disattivate l’utilizzo di micro dettagli personalizzati. |

### Occlusione ambientale

| Nome parametro | Descrizione |
| --- | --- |
| **Inverti** | Inverti solo Occlusione ambientale e micro dettagli. |
| **Sfocatura** | Occlusione ambientale uniforme e micro dettagli. |
| **Saldo** | Regola il bilanciamento solo dell’Occlusione ambientale e dei micro dettagli, spostando il punto medio verso il bianco o il nero come un controllo della luminosità. |
| **Contrasto** | Regola il contrasto/decadimento solo dell’Occlusione ambientale e dei micro dettagli. |

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
    <td>Inverti solo la texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Conversione in scala di grigi</strong></td>
    <td>Imposta il metodo usato per convertire dal colore completo al grigio. Il generatore di <a href="grayscale-conversion.md">Conversioni in scala di grigi contiene ulteriori informazioni sul funzionamento di ciascun metodo</a>.</td>
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
    <td>Regola il contrasto/decadimento della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Luminosità</strong></td>
    <td>Regola la luminosità della texture personalizzata.</td>
  </tr>
  <tr>
    <td><strong>Triplanare</strong></td>
    <td>Quando Triplanare è attivato, la texture viene proiettata da tre direzioni (assi X, Y, Z) invece di basarsi solo sugli UV.<br><ul><li>Senza triplanare, la texture segue il layout UV.</li><li>Con triplanare, la texture viene proiettata da più angoli e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto triplanare</strong></td>
    <td>Consente di controllare l’uniformità della fusione di una texture quando viene proiettata utilizzando la mappatura triplanare. Questa impostazione regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
</table>

### Dettagli micro

| Nome parametro | Descrizione |
| --- | --- |
| **Micro Height** | Attivare o disattivare l&#39;utilizzo di una mappa personalizzata dell&#39;altezza della micro. |
| **Micro normale** | Attivare o disattivare l&#39;utilizzo di una Micro Mappa normale personalizzata. |
| **Raggio AO** | Regolate il raggio (intervallo) dell’Occlusione ambientale nei micro dettagli. |
| **Profondità AO** | Regola la profondità (intensità) dell&#39;Occlusione ambiente nei micro dettagli. |
