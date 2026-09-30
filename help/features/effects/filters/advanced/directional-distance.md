---
title: Distanza direzionale
description: Scopri come utilizzare il filtro Distanza direzionale in Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 1%
---

# Distanza direzionale

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="./Resources/icon_directional_distance.png" alt="Distanza direzionale icona" title="Distanza direzionale"/><br><strong>Ingresso:</strong> effetti/colore, distanza, direzionale, perdita, pioggia</td>
    <td style="border: 0;" valign="top">Descrizione<br>Il filtro Distanza direzionale crea una sfumatura di distanza che si sposta nella direzione scelta.<br>Viene utilizzato su un livello texture per creare striature direzionali, perdite e altri effetti basati sulla distanza. Puoi anche usare il filtro Distanza direzionale come maschera del canale height per aggiungere dimensionalità al canale normale.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| **Mappa di distanza:** Scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Distanza:** | Regolate la distanza percorsa dalla sfumatura di distanza nello spazio dell’immagine normalizzato, dove 1 è la lunghezza del lato più corto dell’immagine di input. |
| **Angolo:** | Regolate la direzione della sfumatura di distanza in successione, dove 0 punti in orizzontale a destra o lungo un vettore (1,0). |
| **Contrasto:** | Regolate il contrasto o la dissolvenza del risultato. |
| **Moltiplicatore Mappa di distanza:** | Regolate l’effetto della Mappa di distanza sulla distanza massima. Questo parametro non ha effetto quando l&#39;input della Mappa di distanza non è connesso. |

## Esempi

Nell’esempio seguente, utilizziamo il filtro Distanza direzionale per far apparire il generatore Celle 2 tridimensionale.

![](../../../../assets/filters/directional-distance/3d.png)

Questo si ottiene creando un livello di riempimento con il canale height attivato e impostato su un valore di 1.

Quindi aggiungi una maschera nera al livello di riempimento e nella maschera aggiungi un riempimento con la scala di grigi impostata su **Cella 2**. In questo modo viene creata la seguente maschera.

>[!NOTE]
>
> Per visualizzare la maschera nel **Riquadro di visualizzazione**, tieni premuto Alt e fai clic sull’icona della maschera; in alternativa, con il livello di riempimento selezionato, usa il menu a discesa dei canali nel **Riquadro di visualizzazione** per selezionare **Maschera**.

![](../../../../assets/filters/directional-distance/cells2.png)

Quindi, aggiungete un filtro alla maschera e selezionate il filtro Distanza direzionale.

Regolate le impostazioni Filtro per ottenere il risultato desiderato, ma la maschera deve essere simile all’esempio seguente.

![](../../../../assets/filters/directional-distance/result.png)

Tornare alla vista del materiale per visualizzare l&#39;effetto nel riquadro di visualizzazione.
