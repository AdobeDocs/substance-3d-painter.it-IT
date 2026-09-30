---
title: Kuwahara Anisotropo
description: Scopri come utilizzare il filtro Anisotropo Kuwahara di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '258'
ht-degree: 1%
---

# Kuwahara Anisotropo

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona anisotropa del Kuwahara](./Resources/icon_anisotropic_kuwahara.png "Icona anisotropa del Kuwahara")

<b>Ingresso:</b> Effetti/scala di grigi, kuwahara, anisotropi, stilizzati

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Kuwahara anisotropo crea effetti di stilizzazione pittorica preservando al contempo forti caratteristiche direzionali.

Viene utilizzato su un livello texture o all’interno di una maschera (output in bianco e nero) per creare un aspetto stilizzato per materiali completi, rumori e maschere.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Mappa raggio:</b> scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |
| <b>Input personalizzato: </b> colore | Usate una texture personalizzata o un punto di ancoraggio. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Direzione estrazione:</b> | Selezionate il modo in cui il filtro deriva la direzione della sfocatura. |
| <b>Raggio:</b> | Regolate il raggio di sfocatura. Più alti sono i valori, maggiore sarà l’effetto di sfocatura. Il valore massimo è 32. |
| <b>Smoothness:</b> | Regola la quantità di colori che si fondono lungo la direzione calcolata. A 0, i colori vengono spostati principalmente in quella direzione con una fusione minima. |
| <b>Nitidezza:</b> | Regolate il contrasto nelle aree sfocate per renderle più piatte e definite. |
| <b>Smoothness del tensore:</b> | Regolate la quantità di sfocatura applicata alle direzioni calcolate dall’immagine e memorizzate nella mappa direzionale. Valori più alti producono un risultato più uniforme quando l’immagine contiene molti dettagli ad alta frequenza. |
| <b>Anisotropia:</b> | Regolate l’entità dell’influenza della mappa direzionale sulla sfocatura. La mappa direzionale e i relativi modificatori influiscono ancora sul risultato anche quando questo valore è 0, perché la mappa viene utilizzata nel kernel del filtro Kuwahara. |
| <b>Angolo di anisotropia:</b> | Regolate a turno la rotazione applicata alla mappa direzionale. Questa rotazione viene aggiunta al valore dall&#39;input Mappa Angolo di anisotropia. |

