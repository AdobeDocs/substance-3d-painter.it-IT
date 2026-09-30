---
title: Pendenza sfocatura
description: Scoprite come utilizzare il filtro Pendenza sfocatura di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 2%
---

# Pendenza sfocatura

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Pendenza sfocatura](./Resources/icon_blur_slope.png "Pendenza sfocatura")

<b>Ingresso:</b> Effetti/sfocatura, scala di grigi

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Sfocatura Pendenza crea un effetto di macchie o dissolvenza, particolarmente evidente sui bordi ad alto contrasto tra i colori.

Viene utilizzato direttamente su un livello texture per sfocare materiali completi o texture specifiche o su una maschera per applicare l’effetto di striscio alla maschera. Può causare effetti come bordi scheggiati o usurati, dirt che perde o ruggine sbavata.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Disturbo personalizzato:</b> Scala di grigi | Usate una texture personalizzata o un punto di ancoraggio come disturbo personalizzato. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Valore di inizializzazione:</b> | Assegna un valore casuale per creare una variazione diversa senza modificare le impostazioni generali. |
| <b>Intensità:</b> | Regolate l’intensità della sfocatura. |
| <b>Divisore intensità:</b> | Selezionate la modalità di divisione dell’intensità della sfocatura. |
| <b>Metodo fusione:</b> | Selezionate il metodo di fusione utilizzato dalla sfocatura pendenza. |
| <b>Qualità:</b> | Regolate la qualità dell’effetto. |

### Parametri di origine

<table>
<tr>
<td><b>Tipo di origine:</b></td>
<td>Consente di specificare se la sorgente utilizza il disturbo predefinito, l’input precedente o un disturbo personalizzato.</td>
</tr>
<tr>
<td><b>Sfocatura:</b></td>
<td>Regolate l’intensità della sfocatura del disturbo o dell’input sorgente.</td>
</tr>
<tr>
<td><b>Posizione:</b></td>
<td>Regola il punto medio del disturbo o dell'input sorgente, in modo simile a un controllo della luminosità.</td>
</tr>
<tr>
<td><b>Contrasto:</b></td>
<td>Regola il contrasto del disturbo o dell'input sorgente.</td>
</tr>
<tr>
<td><b>Lavorazione origine:</b></td>
<td>Regola l'Affiancamento del disturbo o dell'input sorgente.</td>
</tr>
</table>
