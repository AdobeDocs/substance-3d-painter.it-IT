---
title: Gocce d’acqua MatFX
description: Scopri come utilizzare il filtro Gocce d’acqua MatFX di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 3%
---

# Gocce d’acqua MatFX

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Gocce d&#39;acqua MatFX](./Resources/icon_matfx_water_drops.png "Gocce d&#39;acqua MatFX")

<b>Ingresso:</b> Effetti/sfocatura, scala di grigi

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Gocce d’acqua MatFX crea effetti di gocce d’acqua e deflusso su un materiale.

Viene utilizzato su strati di texture o pile di materiale per aggiungere goccioline, striature direzionali e variazione della superficie bagnata.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Occlusione ambientale:</b> Scala di grigi | Usa la mappa di occlusione ambientale eseguita i baking. |
| <b>Normali spazio globale:</b> colore | Usate la mappa eseguita i baking delle normali spaziali mondiali. |
| <b>Posizione:</b> colore | Utilizzare la mappa di posizione eseguita i baking. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Quantità di cadute:</b> | Regolate la quantità di gocce d’acqua. |
| <b>Scala cadute X:</b> | Regola la scala X delle gocce. |
| <b>Ridimensionamento Gocce Y:</b> | Regolate la scala Y delle gocce. |
| <b>Scala delle gocce casuale:</b> | Regola l’entità della variazione casuale della scala nelle gocce. |
| <b>Intensità direzione salti:</b> | Regolate l’intensità direzionale delle gocce. |

### Posizione

| Nome parametro | Descrizione |
| --- | --- |
| <b>Influenza X:</b> | Regola l’influenza X dell’input della posizione. |
| <b>Influenza Y:</b> | Regola l’influenza Y dell’input della posizione. |
| <b>Influenza Z:</b> | Regola l’influenza Z dell’input della posizione. |

### Accumulo di acqua

| Nome parametro | Descrizione |
| --- | --- |
| <b>Intensità:</b> | Regolare l’intensità dell’accumulo di acqua. |
| <b>Pagine affiancate:</b> | Regolare la diffusione dell&#39;accumulo di acqua. |
| <b>Intensità basata su AO:</b> | Regolare la quantità di occlusione ambientale che influenza l’accumulo di acqua. |

### Spazio globale

| Nome parametro | Descrizione |
| --- | --- |
| <b>Intensità mascheratura:</b> | Regolate l&#39;intensità della maschera World-Space. |
| <b>Intensità massima:</b> | Regolate l’intensità delle gocce nelle aree rivolte verso l’alto. |
| <b>Intensità inferiore:</b> | Regolate l’intensità delle gocce nelle aree rivolte verso il basso. |
| <b>Intensità anteriore:</b> | Regolate l’intensità delle gocce sulle aree rivolte in avanti. |
| <b>Intensità retro:</b> | Regolate l’intensità delle gocce sulle aree rivolte in secondo piano. |
| <b>Intensità destra:</b> | Regola l’intensità delle gocce nelle aree rivolte a destra. |
| <b>Intensità sinistra:</b> | Regolate l’intensità delle gocce sulle aree rivolte a sinistra. |

### Materiale

| Nome parametro | Descrizione |
| --- | --- |
| <b>Rilascia l&#39;intensità dell&#39;alterazione del Colore di base:</b> | Regolate l’intensità di alterazione applicata al colore di base sotto le gocce. |
| <b>Moltiplicatore mappa vettoriale rotazione salti:</b> | Regola il moltiplicatore applicato alla mappa del vettore di rotazione esterna. |
| <b>Rilascia Intensità Height:</b> | Regolate l’intensità dell’effetto height. |
| <b>Rugosità gocce:</b> | Regolate la rugosità delle gocce. |
| <b>Fusione rugosità gocce:</b> | Regolate il modo in cui la rugosità della goccia si fonde con il materiale. |
| <b>Gocce metalliche:</b> | Regolate il valore metallico delle gocce. |
| <b>Rilascia fusione metallizzata:</b> | Regolate il modo in cui il valore del metallo di rilascio si fonde con il materiale. |
| <b>Intensità normale:</b> | Regolate l’intensità dell’effetto normale. |
