---
title: Quantizza
description: Scopri come utilizzare il filtro Quantizza di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 1%
---

# Quantizza

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Quantizza](./Resources/icon_quantize.png "Quantizza")

<b>Ingresso:</b> Effetti/quantizzazione, colore

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Quantizza riduce un’immagine a un set limitato di colori.

Viene utilizzato su un livello texture per creare aree di colore più piatte, posterizzate o stilizzate.

</td>
</tr>
</table>

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Quantità colore:</b> | Regolate il numero massimo di colori usati nell’immagine quantizzata. Questo valore determina anche la tavolozza estratta, anche se il conteggio effettivo può essere inferiore a seconda del metodo di quantizzazione. Controllate l’output Quantità colore tavolozza per il numero finale di colori estratti. |
| <b>Arrotondamento contorno:</b> | Regolate il raggio di arrotondamento applicato all&#39;immagine di input per semplificare il risultato quantizzato in forme più solide e coese. Valori più alti aumentano notevolmente il tempo di calcolo. |
| <b>Dithering:</b> | Regolate la quantità di dithering utilizzata per ricreare le sfumature e le fusioni di colore pur continuando a utilizzare solo i colori rimasti dopo la quantizzazione. Per ottenere l’effetto di dithering previsto, impostate il valore 0 su Uniforma contorno. |
| <b>Criterio dithering:</b> | Selezionate il pattern di dithering utilizzato per ricreare le sfumature e le fusioni di colore nell’immagine originale. |
| <b>Spazio colore distanza:</b> | Selezionate lo spazio colore usato per confrontare e distribuire i colori durante la quantizzazione. Usate Lab (Colore) per le immagini a colori percettivi e RGB (Dati) per i dati raw, ad esempio la mappa normale. |
| <b>Applica all&#39;Alpha:</b> | Attiva/disattiva la quantizzazione del canale alfa del livello. |
| <b>Soglia Alpha:</b> | Regolate la soglia alfa. |

