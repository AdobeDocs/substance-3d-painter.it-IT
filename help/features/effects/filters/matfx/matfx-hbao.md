---
title: MatFX HBAO
description: Scopri come utilizzare il filtro HBAO MatFX di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 2%
---

# MatFX HBAO

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona HBAO MatFX](./Resources/icon_matfx_hbao.png "HBAO MatFX")

<b>Ingresso:</b> effetti/occlusione ambientale, height, ombreggiatura

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro HBAO MatFX genera un’occlusione ambientale basata sull’orizzonte in base alle informazioni del height.

Viene utilizzato sui livelli texture o sulle maschere per aggiungere ombre di profondità e contatto in base al canale sorgente o alle informazioni sul height.

</td>
</tr>
</table>

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Intensità sfocatura:</b> | Regolate l’intensità di sfocatura del risultato. |
| <b>Contorna con sfocatura:</b> | Attivate/disattivate l’opzione di ritorno a capo automatico. Quando è attivato, l’effetto campiona i pixel dal lato opposto della texture. |
| <b>Origine canale:</b> | Selezionate la sorgente del canale usata per generare l’occlusione. |
| <b>Usa unità globali:</b> | Attivate/disattivate l’uso di unità spazio-mondo. |
| <b>Profondità Height:</b> | Regola la profondità percepita dell&#39;input del height. |
| <b>Raggio:</b> | Regolate il raggio di campionamento dell’effetto di occlusione. |
| <b>Intensità:</b> | Regolate l’intensità dell’occlusione. |
| <b>Saldo Rilievo:</b> | Regola il saldo del contributo del rilievo. |
