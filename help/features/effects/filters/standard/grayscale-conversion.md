---
title: Conversione in scala di grigi
description: Scopri come utilizzare il filtro Conversione in scala di grigi di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 4%
---

# Conversione in scala di grigi

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Conversione in scala di grigi](./Resources/icon_grayscale_conversion.png "Conversione in scala di grigi")

<b>Ingresso:</b> Effetti/colore, desaturazione, min, max

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Conversione in scala di grigi converte un’immagine canale/colore in scala di grigi pesando la luminanza di ciascun canale di colore. Sono disponibili numerose opzioni per modificare la conversione.

Viene utilizzato su un livello texture o su un livello maschera per convertire i canali in scala di grigio o per convertire un’immagine a colori in scala di grigio e utilizzarla come maschera.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Input personalizzato: </b> colore | Usate una texture personalizzata o un punto di ancoraggio. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Input canale:</b> | Seleziona l’input del canale utilizzato per la conversione. |
| <b>Inverti:</b> | Attiva/disattiva l’inversione del risultato. |
| <b>Saldo:</b> | Regola il bilanciamento del risultato tra bianco e nero, in modo simile a una regolazione della luminosità. |
| <b>Contrasto:</b> | Regolate il contrasto/decadimento del risultato. |
| <b>Modalità:</b> | Seleziona la modalità di conversione della scala di grigi. |
| <b>Rosso:</b> | Regola la ponderazione per il canale Rosso. Questa ponderazione viene utilizzata per calcolare il risultato in scala di grigi. |
| <b>Verde:</b> | Regola la ponderazione per il canale Verde. Questa ponderazione viene utilizzata per calcolare il risultato in scala di grigi. |
| <b>Blu:</b> | Regolate la ponderazione per il canale Blu. Questa ponderazione viene utilizzata per calcolare il risultato in scala di grigi. |
| <b>Alpha:</b> | Regola la ponderazione del Canale alfa. Questa ponderazione viene utilizzata per calcolare il risultato in scala di grigi. |

