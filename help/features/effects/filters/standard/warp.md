---
title: Ordito
description: Scoprite come utilizzare il filtro Altera di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '261'
ht-degree: 2%
---

# Ordito

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Altera](./Resources/icon_warp.png "Altera")

<b>Ingresso:</b> effetti/scala di grigi

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Altera viene utilizzato per vari effetti di deformazione. Il filtro Altera consente di accedere all’alterazione regolare, a un’alterazione direzionale che si altera in una direzione specifica e a un’alterazione multidirezionale che agevola le variazioni.

Altera viene utilizzato su un livello texture o all’interno di una maschera (output in bianco e nero) per deformare materiali, forme, maschere, contorni, ecc.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Disturbo personalizzato</b> | Utilizza una texture personalizzata come mappa di input del disturbo. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Valore di inizializzazione:</b> | Assegna un valore casuale per creare una variazione diversa senza modificare le impostazioni generali. |
| <b>Modalità alterazione:</b> | Selezionate la modalità di alterazione. |
| <b>Intensità:</b> | Regolate l’intensità dell’alterazione. |
| <b>Divisore intensità:</b> | Selezionate la modalità di divisione dell’intensità dell’alterazione. |
| <b>Angolo:</b> | Regolate l’angolo di alterazione. |
| <b>Metodo fusione:</b> | Selezionate il metodo di fusione utilizzato dall’alterazione. |
| <b>Indicazioni:</b> | Selezionate il numero di direzioni di alterazione. |

### Parametri di origine

<table>
<tr>
<td><b>Modalità sorgente:</b></td>
<td>Determina la modalità di origine.<br><br> - Disturbo predefinito: utilizza il disturbo predefinito per l'effetto di alterazione.<br> - Input precedente: utilizza l’input precedente per l’effetto di alterazione. Quando a un livello di riempimento è applicato uno specifico pattern di disturbo, l'utilizzo di un effetto di alterazione nella modalità "Input precedente" farà sì che l'effetto utilizzi lo stesso pattern di disturbo del livello di riempimento.<br> - Disturbo personalizzato: utilizza l’input di disturbo personalizzato per l’effetto di alterazione.</td>
</tr>
<tr>
<td><b>Sfocatura sorgente:</b></td>
<td>Sfoca il disturbo sorgente.</td>
</tr>
<tr>
<td><b>Saldo origine:</b></td>
<td>Regola il bilanciamento del disturbo sorgente, spostando il punto medio verso il bianco o il nero come un controllo della luminosità.</td>
</tr>
<tr>
<td><b>Contrasto sorgente:</b></td>
<td>Modifica il contrasto del disturbo sorgente.</td>
</tr>
<tr>
<td><b>Lavorazione origine:</b></td>
<td>Controlla l’Affiancamento del disturbo sorgente.</td>
</tr>
</table>
