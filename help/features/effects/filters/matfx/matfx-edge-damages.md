---
title: Danni ai bordi di MatFX
description: Scopri come utilizzare il filtro Substance 3D Painter MatFX Edge Damages.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 1%
---

# Danni ai bordi di MatFX

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Danni bordi MatFX](./Resources/icon_matfx_edge_damages.png "Danni bordi MatFX")

<b>Ingresso:</b> Effetti/sfocatura, scala di grigi

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Danni bordo MatFX crea dettagli del bordo ridotto o danneggiato. Danno bordo si comporta in modo diverso rispetto al filtro Edge Wear dettagli MatFX in quanto Danno bordo non modifica il colore dell’area danneggiata. Ciò significa che può essere più utile per simulare danni a materiali come plastica o resina, piuttosto che Edge Wear che è meglio utilizzato per materiali come metallo verniciato.

MatFX Edge Damages viene utilizzato su livelli di texture o pile di materiale per aggiungere dettagli del bordo usurati, graffiati e danneggiati.

</td>
</tr>
</table>

>[!NOTE]
>
> Affinché il filtro MatFX Edge Damages possa modificare il canale di height, è necessario che nel canale siano presenti dati di height esistenti. In altre parole, se sotto il livello del filtro non ci sono livelli con dati di height, il filtro non avrà un effetto osservabile sul canale del height.

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Intensità sfocatura:</b> | Regolate l’intensità dell’effetto di sfocatura. |
| <b>Contorna con sfocatura:</b> | Attivate/disattivate l’opzione di ritorno a capo automatico. Quando è attivato, l’effetto campiona i pixel dal lato opposto della texture. |
| <b>Livello:</b> | Regolare il livello di danno complessivo. |
| <b>Contrasto:</b> | Regolate il contrasto o la dissolvenza del risultato. |
| <b>Intensità Scratches:</b> | Regolate l’intensità dei graffi. |
| <b>Rugosità danni:</b> | Regolate la rugosità delle aree danneggiate. |
| <b>Profondità danni:</b> | Regolate la profondità delle aree danneggiate. |
