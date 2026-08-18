---
title: Densità texel UV
description: Scopri come utilizzare il generatore di densità UV Texel di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '204'
ht-degree: 0%

---


# Densità texel UV

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_uv_texel_density.png" alt=""/><br><strong>In:</strong> uv, dimensione, utilità</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore di densità texel UV visualizza la densità di texel di una trama applicando una sfumatura colorata da bassa a alta.<br>Il generatore di densità texture UV genera una texture a colori completa ed è ideale su un livello di riempimento per identificare una scala UV incoerente e garantire dettagli di texture uniformi in un modello.</td>
  </tr>
</table>

>[!NOTE]
>
> La densità del texel si riferisce al numero di texel (pixel della texture) in una determinata area di superficie del modello. Una densità di texel elevata consente di inserire molti dettagli in una piccola area del modello, in cui una densità di texel bassa potrebbe limitare la quantità di dettagli ma migliorare le prestazioni. In generale, indipendentemente dalla risoluzione dei materiali, si consiglia di mantenere una densità di testo uniforme nella trama, in quanto grandi differenze nella densità del testo sono spesso evidenti agli spettatori e possono rendere una risorsa di qualità inferiore o meno realistica.

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Colore basso** | Impostate il colore utilizzato per le aree con densità di texel **bassa**. |
| **Colore medio** | Impostate il colore utilizzato per le aree con densità di texel **media**. |
| **Colore alto** | Impostate il colore utilizzato per le aree con densità di texel **alta**. |
