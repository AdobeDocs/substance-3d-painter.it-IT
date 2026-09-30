---
title: Baked lighting environment
description: Scopri come utilizzare il filtro Baked lighting environment di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 2%
---

# Baked lighting environment

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Baked lighting environment](./Resources/icon_baked_lighting_environment.png "Baked lighting environment")

<b>Ingresso:</b> effetti/illuminazione, esegue i baking, ambiente, PBR

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Baked lighting environment esegue i baking le informazioni di illuminazione dell&#39;ambiente e del materiale nel canale di colore.

Viene utilizzato su un livello di pittura impostato sulla modalità passthrough e applicato a tutti i canali. È utile per flussi di lavoro stilizzati in cui non è richiesta un’illuminazione simulata accurata o quando le risorse sono limitate, ad esempio su progetti mobili o risorse che si basano solo su una mappa colore.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Occlusione ambientale:</b> Scala di grigi | Usa la mappa di Occlusione ambientale eseguita i baking. |
| <b>Mappa ambiente:</b> scala di grigi | Utilizzare la mappa dell&#39;ambiente. |
| <b>Normale:</b> colore | Utilizzate la Mappa normale eseguita i baking. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Rotazione orizzontale:</b> | Regola la rotazione orizzontale dell’illuminazione ambiente. |
| <b>Rotazione verticale:</b> | Regola la rotazione verticale dell&#39;illuminazione ambiente. |
| <b>Esposizione:</b> | Regola l’esposizione del risultato eseguito i baking. |
| <b>Intensità Height:</b> | Regolate l’entità dell’influenza delle informazioni sul height sul risultato. |
| <b>Intensità Occlusione ambientale:</b> | Regolate l’intensità dell’occlusione ambientale nel eseguo i baking. |
| <b>Intensità Occlusione Specular:</b> | Regolate l’intensità dell’occlusione dello specular nel eseguo i baking. |
