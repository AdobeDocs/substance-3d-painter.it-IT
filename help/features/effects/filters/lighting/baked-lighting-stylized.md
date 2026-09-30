---
title: Illuminazione eseguita i baking stilizzata
description: Scoprite come utilizzare il filtro Eseguito i baking Illuminazione stilizzata di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '651'
ht-degree: 1%
---

# Illuminazione eseguita i baking stilizzata

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Stilizzata illuminazione Eseguita i baking](./Resources/icon_baked_lighting_stylized.png "Icona Stilizzata illuminazione Eseguita i baking")

<b>Ingresso:</b> effetti/stilizzati, luce, colore

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Stilizzato illuminazione Eseguito i baking esegue i baking le informazioni sul materiale e sull’illuminazione nel canale di colore.

Viene utilizzato su un livello di pittura impostato sulla modalità passthrough e applicato a tutti i canali. È utile per flussi di lavoro stilizzati in cui non è richiesta un’illuminazione simulata accurata o quando le risorse sono limitate, ad esempio su progetti mobili o risorse che si basano solo su una mappa colore.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Occlusione ambientale:</b> Scala di grigi | Usa la mappa di Occlusione ambientale eseguita i baking. |
| <b>Curvatura:</b> Scala Di Grigi | Utilizzate la mappa di curvatura eseguita i baking. |
| <b>Normale:</b> colore | Utilizzate la Mappa normale eseguita i baking. |
| <b>Normali spazio globale:</b> colore | Utilizzare la mappa eseguita i baking World Space Normals. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Input:</b> | Selezionare il flusso di lavoro del materiale di input. |
| <b>Output:</b> | Selezionare la modalità di output. |
| <b>Riflettenza Dielettrica:</b> | Regolate la riflettanza dielettrica. |
| <b>Diffusa AO:</b> | Regolare il contributo dell&#39;occlusione ambientale all&#39;illuminazione diffusa. |
| <b>Cavità Diffusa:</b> | Regolare il contributo della cavità all&#39;illuminazione diffusa. |
| <b>Specular AO:</b> | Regola il contributo dell’occlusione ambientale all’illuminazione dello specular. |
| <b>Cavità Specular:</b> | Regolate il contributo della cavità all&#39;illuminazione dello specular. |
| <b>Smoothness cavità:</b> | Regolate lo smoothness dell&#39;effetto cavità. |
| <b>Intensità bordi:</b> | Regolate l’intensità dell’effetto del bordo. |
| <b>Smoothness bordi:</b> | Regolate lo smoothness dell’effetto del bordo. |
| <b>Tipo dettagli normali:</b> | Selezionare i dettagli normali utilizzati. |
| <b>Intensità da Height a normale:</b> | Regola l’intensità della conversione da height a normale. |
| <b>Intensità sole:</b> | Regolate l’intensità della luce del sole. |
| <b>Angolo orizzontale Sole:</b> | Regola l&#39;angolo orizzontale della luce del sole. |
| <b>Angolo verticale sole:</b> | Regola l&#39;angolo verticale della luce del sole. |
| <b>Colore Sole:</b> | Regolate il colore della luce del sole. |
| <b>Intensità cielo:</b> | Regolate l’intensità della luce del cielo. |
| <b>Colore cielo:</b> | Regolate il colore della luce del cielo. |
| <b>Colore orizzonte:</b> | Regola il colore della luce dell&#39;orizzonte. |
| <b>Colore terreno:</b> | Regolate il colore della luce del terreno. |
| <b>Angolo orizzontale:</b> | Regola l’angolo orizzontale della luce aggiuntiva. |
| <b>Angolo verticale:</b> | Regolate l’angolo verticale della luce aggiuntiva. |
| <b>Intensità:</b> | Regolate l’intensità della luce aggiuntiva. |
| <b>Colore:</b> | Regolate il colore della luce aggiuntiva. |
| <b>Angolo orizzontale:</b> | Regolate l’angolo orizzontale della seconda luce aggiuntiva. |
| <b>Angolo verticale:</b> | Regolate l’angolo verticale della seconda luce aggiuntiva. |
| <b>Intensità:</b> | Regolate l’intensità della seconda luce aggiuntiva. |
| <b>Colore:</b> | Regolate il colore della seconda luce aggiuntiva. |

### Materiale

<table>
<tr>
<td><b>Riflettenza Dielettrica:</b></td>
<td>Impostate la quantità di riflettanza dielettrica.</td>
</tr>
<tr>
<td><b>Diffusa AO:</b></td>
<td>Controllate l’entità dell’occlusione ambientale che influenza i dettagli della diffusione.</td>
</tr>
<tr>
<td><b>Cavità Diffusa:</b></td>
<td>Controllate la misura in cui le aree della cavità influenzano i dettagli diffusi.</td>
</tr>
<tr>
<td><b>Specular AO:</b></td>
<td>Controllate l’entità dell’influenza dell’occlusione ambientale sui dettagli degli specular.</td>
</tr>
<tr>
<td><b>Cavità Specular:</b></td>
<td>Regolate il grado di influenza delle aree di cavità sui dettagli dello specular.</td>
</tr>
<tr>
<td><b>Smoothness cavità:</b></td>
<td>Regolate l’aspetto uniforme delle aree della cavità.</td>
</tr>
<tr>
<td><b>Intensità bordi:</b></td>
<td>Impostate l'intensità dei dettagli del bordo.</td>
</tr>
<tr>
<td><b>Smoothness bordi:</b></td>
<td>Regolate lo smoothness delle aree dei bordi.</td>
</tr>
<tr>
<td><b>Tipo di dettagli normali:</b></td>
<td>Selezionate i dettagli da usare per le normali: Solo trama o Trama + Height + Normale.</td>
</tr>
<tr>
<td><b>Intensità da height a normale:</b></td>
<td>Regolate l’intensità dei dettagli normali generati.</td>
</tr>
</table>

### Sole e cielo

<table>
<tr>
<td><b>Intensità sole:</b></td>
<td>Controllate la forza del sole.</td>
</tr>
<tr>
<td><b>Angolo orizzontale sole:</b></td>
<td>Regolate l'angolo orizzontale del sole.</td>
</tr>
<tr>
<td><b>Angolo verticale sole:</b></td>
<td>Regolate l'angolo verticale del sole.</td>
</tr>
<tr>
<td><b>Colore sole:</b></td>
<td>Controllate il colore del sole.</td>
</tr>
<tr>
<td><b>Intensità cielo:</b></td>
<td>Regolate la forza del cielo.</td>
</tr>
<tr>
<td><b>Colore cielo:</b></td>
<td>Imposta il colore del cielo.</td>
</tr>
<tr>
<td><b>Colore orizzonte:</b></td>
<td>Regolate il colore dell'orizzonte.</td>
</tr>
<tr>
<td><b>Colore terreno:</b></td>
<td>Impostate il colore del terreno.</td>
</tr>
</table>

### Chiaro 1

<table>
<tr>
<td><b>Angolo orizzontale:</b></td>
<td>Regola l’angolo orizzontale della luce aggiuntiva.</td>
</tr>
<tr>
<td><b>Angolo verticale:</b></td>
<td>Regolate l’angolo verticale della luce aggiuntiva.</td>
</tr>
<tr>
<td><b>Intensità</b></td>
<td>Regolate l’intensità della luce aggiuntiva.</td>
</tr>
<tr>
<td><b>Colore:</b></td>
<td>Impostate il colore della luce aggiuntiva.</td>
</tr>
</table>

### Chiaro 2

<table>
<tr>
<td><b>Angolo orizzontale:</b></td>
<td>Regolate l’angolo orizzontale della seconda luce aggiuntiva.</td>
</tr>
<tr>
<td><b>Angolo verticale:</b></td>
<td>Regolate l’angolo verticale della seconda luce aggiuntiva.</td>
</tr>
<tr>
<td><b>Intensità</b></td>
<td>Regolate l’intensità della seconda luce aggiuntiva.</td>
</tr>
<tr>
<td><b>Colore:</b></td>
<td>Impostate il colore della seconda luce aggiuntiva.</td>
</tr>
</table>
