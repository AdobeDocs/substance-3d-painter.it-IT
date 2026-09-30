---
title: Illuminazione eseguita i baking stilizzata
description: Scoprite come utilizzare il filtro Eseguito i baking Illuminazione stilizzata di Substance 3D Painter.
source-git-commit: 5078774d081555f586a50965b91d85f7c340ef13
workflow-type: tm+mt
source-wordcount: '662'
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
| <b>Angolo orizzontale:</b> | Regolate l’intensità della luce aggiuntiva. |
| <b>Angolo verticale:</b> | Regolate l’angolo verticale della luce aggiuntiva. |
| <b>Intensità:</b> | Regolate l’intensità della luce aggiuntiva. |
| <b>Colore:</b> | Regolate il colore della luce aggiuntiva. |
| <b>Angolo orizzontale:</b> | Regolate l’angolo orizzontale della seconda luce aggiuntiva. |
| <b>Angolo verticale:</b> | Regolate l’angolo verticale della seconda luce aggiuntiva. |
| <b>Intensità:</b> | Regolate l’intensità della seconda luce aggiuntiva. |
| <b>Colore:</b> | Regolate il colore della seconda luce aggiuntiva. |

### Materiale

| Nome parametro | Descrizione |
| --- | --- |
| **Riflettenza Dielettrica:** | Impostate la quantità di riflettanza dielettrica. |
| **Diffusa AO:** | Controllate l’entità dell’occlusione ambientale che influenza i dettagli della diffusione. |
| **Cavità Diffusa:** | Controllate la misura in cui le aree della cavità influenzano i dettagli diffusi. |
| **Specular AO:** | Controllate l’entità dell’influenza dell’occlusione ambientale sui dettagli degli specular. |
| **Cavità Specular:** | Regolate il grado di influenza delle aree di cavità sui dettagli dello specular. |
| **Smoothness cavità:** | Regolate l’aspetto uniforme delle aree della cavità. |
| **Intensità bordi:** | Impostate l&#39;intensità dei dettagli del bordo. |
| **Smoothness bordi:** | Regolate lo smoothness delle aree dei bordi. |
| **Tipo dettagli normali:** | Selezionate i dettagli da usare per le normali: Solo trama o Trama + Height + Normale. |
| **Intensità da Height a normale:** | Regolate l’intensità dei dettagli normali generati. |

### Sole e cielo

| Nome parametro | Descrizione |
| --- | --- |
| **Intensità sole:** | Controllate la forza del sole. |
| **Angolo orizzontale Sole:** | Regolate l&#39;angolo orizzontale del sole. |
| **Angolo verticale sole:** | Regolate l&#39;angolo verticale del sole. |
| **Colore Sole:** | Controllate il colore del sole. |
| **Intensità cielo:** | Regolate la forza del cielo. |
| **Colore cielo:** | Imposta il colore del cielo. |
| **Colore orizzonte:** | Regolate il colore dell&#39;orizzonte. |
| **Colore terreno:** | Impostate il colore del terreno. |

### Chiaro 1

| Nome parametro | Descrizione |
| --- | --- |
| **Angolo orizzontale:** | Regola l’angolo orizzontale della luce aggiuntiva. |
| **Angolo verticale:** | Regolate l’angolo verticale della luce aggiuntiva. |
| **Intensità:** | Regolate l’intensità della luce aggiuntiva. |
| **Colore:** | Impostate il colore della luce aggiuntiva. |

### Chiaro 2

| Nome parametro | Descrizione |
| --- | --- |
| **Angolo orizzontale:** | Regolate l’angolo orizzontale della seconda luce aggiuntiva. |
| **Angolo verticale:** | Regolate l’angolo verticale della seconda luce aggiuntiva. |
| **Intensità:** | Regolate l’intensità della seconda luce aggiuntiva. |
| **Colore:** | Impostate il colore della seconda luce aggiuntiva. |
