---
title: Fisso
description: Scopri come utilizzare il filtro di Blocca di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 2%
---

# Fisso

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Blocca](./Resources/icon_clamp.png "Blocca")

<b>Ingresso:</b> effetti/regolazioni

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Blocca blocca i valori ai limiti definiti.

Viene utilizzato direttamente su un livello di riempimento per limitare aspetti specifici di un materiale oppure su una maschera per vincolare i valori a un determinato intervallo.

</td>
</tr>
</table>

>[!NOTE]
>
> Quando viene utilizzato su un livello di riempimento o come passthrough per le informazioni sul colore, il morsetto agisce su ciascun canale di colore singolarmente. Quindi, se un determinato pixel ha un colore di (R 0, G 0,5, B 1,0) ed è fissato a 0,5, il colore risultante di quel pixel sarà (R 0, G 0,5, B 0,5). Questo perché il canale Blu aveva un valore abbastanza alto da poter essere bloccato, mentre gli altri canali no. Questo significa che il filtro di Blocca può modificare la tonalità dei contenuti colorati.
>
>Se non desideri modificare la tonalità, potrebbe essere preferibile utilizzare altri filtri, ad esempio Livelli.

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Min:</b> | Regolate il valore minimo. |
| <b>Massimo:</b> | Regolate il valore massimo. |
