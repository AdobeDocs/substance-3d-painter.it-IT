---
title: PBR Validata
description: Scopri come utilizzare il filtro PBR Validata di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '117'
ht-degree: 2%
---

# PBR Validata

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![icona PBR Validata](./Resources/icon_pbr_validate.png "PBR Validata")

<b>Ingresso:</b> effetti/pbr, metallici, rugosità

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro PBR Validata convalida i dati PBR controllando i valori scuri di albedo e gli intervalli di riflettanza del metallo.

Viene utilizzato su un livello di riempimento per verificare che i valori del materiale rimangano entro gli intervalli PBR previsti. PBR Validata non deve essere attivato durante l’esportazione dei materiali.

</td>
</tr>
</table>

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Modalità di convalida:</b> | Seleziona se convalidare l’albedo, la riflettenza metallica o entrambi. |
| <b>Albedo soglia intervallo scuro:</b> | Selezionare la soglia minima consentita per la convalida dell&#39;albedo. |
| <b>Intervallo di riflessione Metal:</b> | Selezionare l&#39;intervallo di riflettanza utilizzato per convalidare i valori metallici. |
| <b>Mappa sovrapposizione:</b> | Attiva/disattiva la sovrapposizione di convalida sui dati della mappa. |

