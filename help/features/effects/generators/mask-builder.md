---
title: Generatore maschera
description: Scoprite come utilizzare il generatore generatore Mask Builder di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '1146'
ht-degree: 2%

---


# Generatore maschera

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_mask_builder_dark.png" alt=""/><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di Generatore maschera è una versione precedente del generatore di Editor maschera. È un generatore di maschere multifunzione che consente di combinare Grunge, AO, Curvatura, Sfumatura, Spazio normale, Scratches, Dispersione e Micro Dettagli in un'unica maschera.<br><br>Il generatore di generatori di maschere è molto flessibile, ma a causa della sua complessità, può influire sulle prestazioni più della maggior parte dei generatori.<br><br>Il generatore del generatore di generatori di maschere genera una texture monocromatica (in bianco e nero). Di conseguenza, è utile per generare maschere basate sulle varie mappe con baking. <br><br>Sono necessarie mappe Eseguite i baking di posizione, curvatura, occlusione ambientale e spazio globale come input dell'immagine. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Spazio globale normale** colore | Utilizzare la mappa eseguita i baking World Space Normals. |
| **grunge personalizzata 1** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| **grunge personalizzata 2** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| **Input Dispersione** Scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |
| **Curvatura** Scala Di Grigi | Utilizzate la mappa di curvatura eseguita i baking. |
| **Occlusione ambientale** Scala di grigi | Usa la mappa di Occlusione ambientale eseguita i baking. |
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
    <td>Impostate il valore di partenza utilizzato per generare la texture del dirt. <br><ul><li>Fate clic su Casuale per passare a un altro valore di inizializzazione casuale.</li><li>Fate clic sulla matita per visualizzare il valore iniziale corrente e immettete un valore specifico.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Valore tonale</strong></td>
    <td>Regolate il livello del punto medio della maschera finale dopo che tutti gli effetti sono stati combinati in bianco o nero, come avviene con la regolazione della luminosità.</td>
  </tr>
  <tr>
    <td><strong>Contrasto</strong></td>
    <td>Regolate il contrasto/decadimento della maschera finale.</td>
  </tr>
  <tr>
    <td><strong>Inverti</strong></td>
    <td>Invertite il risultato finale della maschera combinata.</td>
  </tr>
  <tr>
    <td><strong>Usa triplanare</strong></td>
    <td>Quando l'opzione <strong>Usa triplanare </strong> è abilitata, la texture viene proiettata da tre direzioni (assi X, Y, Z) anziché basarsi solo sugli UV. <br><ul><li>Senza l'opzione triplanare attivata, la texture segue il layout UV.</li><li>Con l'opzione triplanare attivata, la texture viene proiettata da più angolazioni e fusa.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Contrasto fusione triplanare</strong></td>
    <td>Regola l’uniformità con cui una texture si fonde quando viene proiettata utilizzando la mappatura triplanare. Regola la morbidezza della fusione tra le proiezioni da ogni direzione.</td>
  </tr>
  <tr>
    <td><strong>Grunge</strong></td>
    <td>Regolate l’impatto delle impostazioni Grunge sul risultato finale della maschera.</td>
  </tr>
  <tr>
    <td><strong>AO</strong></td>
    <td>Regolate l’impatto delle impostazioni AO (Occlusione ambientale) sul risultato finale della maschera.</td>
  </tr>
  <tr>
    <td><strong>Curvatura</strong></td>
    <td>Regolate l’impatto delle impostazioni di curvatura sul risultato finale della maschera.</td>
  </tr>
  <tr>
    <td><strong>Sfumatura superiore/inferiore</strong></td>
    <td>Regolate l’impatto della Sfumatura superiore/inferiore sul risultato finale della maschera.</td>
  </tr>
  <tr>
    <td><strong>Mappa spazio mondiale</strong></td>
    <td>Regolate in che modo le impostazioni di Spazio globale normale influiscono sul risultato finale della maschera.</td>
  </tr>
  <tr>
    <td><strong>Graffi</strong></td>
    <td>Regolate l’effetto delle impostazioni di Scratches sul risultato finale della maschera. Affinché gli Scratches siano visibili, Grunge, AO o Curvatura devono essere superiori a 0.</td>
  </tr>
  <tr>
    <td><strong>A dispersione</strong></td>
    <td>Modifica l’effetto della Dispersione sulla maschera.</td>
  </tr>
</table>

### Grunge

| Nome parametro | Descrizione |
| --- | --- |
| **Scala** | Regolate le dimensioni della texture di grunge. |
| **Usa Grunge personalizzata** | Attivare o disattivare l&#39;utilizzo di una mappa Grunge personalizzata. È solo la visibilità della Grunge personalizzata 1. Per controllare la visibilità della Grunge personalizzata 2, regolate il cursore Grunge personalizzata secondaria. |
| **Grunge personalizzata secondaria** | Regolate la visibilità della texture Grunge personalizzata 2. |
| **Inverti** | Invertite le mappe delle grungi. |

### Occlusione ambientale

| Nome parametro | Descrizione |
| --- | --- |
| **Intervallo** | Regolate l’intervallo della maschera AO. |
| **Contrasto** | Regolate il contrasto/decadimento della maschera AO. |
| **Disturbo** | Aggiungete del disturbo al risultato AO, riducendo efficacemente la luminosità della maschera. |
| **Inverti** | Invertite la maschera AO. |

### Curvatura

| Nome parametro | Descrizione |
| --- | --- |
| **Intervallo convesso** | Regolate l’angolo convesso minimo che la maschera deve evidenziare. |
| **Contrasto convesso** | Regolate il contrasto della maschera convessa. |
| **Inversione convessa** | Inverte la maschera convessa. |
| **Intervallo concavo** | Regolate l’angolo concavo minimo che la maschera deve evidenziare. |
| **Contrasto concavo** | Regolate il contrasto della maschera concava. |
| **Inversione concava** | Invertite la maschera concava. |
| **Smoothness** | Regolate la fusione tra le aree chiare e scure della maschera Curvatura. |
| **Incremento livello** | Utilizzate questa opzione per estendere l’intervallo dell’area mascherata. Questo comportamento è analogo a un moltiplicatore per i parametri **Intervallo convesso** e **Intervallo concavo**. |
| **Disturbo** | Aggiungete disturbo al risultato Curvatura, riducendo efficacemente la luminosità della maschera. |

### Sfumatura

La posizione della sfumatura si basa sulla mappa Posizione che può essere eseguita i baking con la scala Scena completa o Con la scala di normalizzazione Per materiale. Se il materiale viene visualizzato solo in una piccola area della scena, ma la mappa di posizione viene creata con una scala di normalizzazione completa della scena, potrebbe essere difficile regolare l’Intervallo sfumatura per ottenere il risultato desiderato.

| Nome parametro | Descrizione |
| --- | --- |
| **Intervallo** | Regolate l’intervallo della sfumatura. |
| **Contrasto** | Modifica il contrasto della sfumatura. |
| **Inverti** | Inverte la sfumatura. |

### Mappa spazio mondiale

I valori **anteriore**, **posteriore**, **sinistro** e **destro** potrebbero non corrispondere ai lati anteriore, posteriore, sinistro e destro della trama. Per impostazione predefinita, **Anteriore** corrisponde all&#39;asse X positivo, mentre Destra corrisponde all&#39;asse Z positivo.

| Nome parametro | Descrizione |
| --- | --- |
| **Intensità massima** | Regolate l’intervallo (intensità) della sfumatura top-down. |
| **Intensità inferiore** | Regolate l’intervallo (intensità) della sfumatura dal basso verso l’alto. |
| **Intensità anteriore** | Regolate l’intervallo (intensità) della sfumatura anteriore posteriore. |
| **Intensità retro** | Regolate l’intervallo (intensità) della sfumatura anteriore posteriore. |
| **Intensità destra** | Regolate l’intervallo (intensità) della sfumatura a destra a sinistra. |
| **Intensità sinistra** | Regolate l’intervallo (intensità) della sfumatura destra sinistra. |

### Graffi

| Nome parametro | Descrizione |
| --- | --- |
| **Importo** | Regolate la densità dei graffi. |
| **Scala** | Regolate la dimensione dei graffi. |

### A dispersione

| Nome parametro | Descrizione |
| --- | --- |
| **Scala** | Regolate le dimensioni dell’effetto dispersione. Una scala più alta genera un numero maggiore di timbri più piccoli, mentre una scala più bassa aumenta le dimensioni dei singoli timbri con un numero minore di timbri visibili. |
| **Densità** | Regola il numero dei timbri sparsi. |
| **Dimensioni** | Regola la dimensione dei timbri sparsi. |
| **Variazione dimensioni** | Regola la casualità delle dimensioni di ogni occorrenza del timbro diffuso. Una variazione di dimensione più elevata riduce casualmente le dimensioni dei timbri, pertanto l’aumento della variazione di dimensione può comportare anche la necessità di aumentare il valore Dimensione per mantenere le stesse dimensioni medie. |
| **Variazione opacità** | Regola la casualità dell’opacità di ogni occorrenza del timbro a dispersione. |

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
    <td>Impostate il tipo di curvatura. <br><ul><li><strong>Standard</strong>: consente di ottenere risultati abbastanza netti, ma possono mancare dettagli più ampi.</li><li><strong>Sobel</strong>: produce risultati simili a quelli standard, ma leggermente più sfocati perché valuta la mappa normale utilizzando un filtro Sobel.</li><li><strong>Uniforme</strong>: genera diversi livelli di sfocatura (come mipmap) per accumulare informazioni. In questo modo, di solito, si ottengono curve più uniformi, ma i dettagli possono andare perduti.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Intensità curvatura</strong></td>
    <td>Regolate l'intensità della curvatura in <strong>Modalità curvatura standard </strong>e <strong>Sobel </strong>.</td>
  </tr>
  <tr>
    <td><strong>Intensità dettagli height</strong></td>
    <td>Regolate l'intensità dei dettagli del Micro Height.</td>
  </tr>
  <tr>
    <td><strong>Raggio AO</strong></td>
    <td>Regolate il raggio (intervallo) dell’Occlusione ambientale nei micro dettagli.</td>
  </tr>
  <tr>
    <td><strong>PROFONDITÀ AO</strong></td>
    <td>Regola la profondità (intensità) dell'Occlusione ambiente nei micro dettagli.</td>
  </tr>
</table>
