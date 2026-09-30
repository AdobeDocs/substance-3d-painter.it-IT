---
title: Tri-Planari Advanced
description: Scopri come utilizzare il filtro Avanzate Tri-Planari di Substance 3D Painter.
source-git-commit: 5078774d081555f586a50965b91d85f7c340ef13
workflow-type: tm+mt
source-wordcount: '553'
ht-degree: 1%
---

# Tri-Planari Advanced

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Avanzate Tri-Planari](./Resources/icon_tri_planar_advanced_filter.png "Icona Avanzate Tri-Planari")

<b>Ingresso:</b> effetti/proiezione

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Avanzato Tri-Planari è la versione filtro del generatore Avanzato Tri-Planari, con controlli manuali per la proiezione completa. Consente di controllare la rotazione e i valori di offset per ciascun asse. A differenza del generatore, questo filtro agisce direttamente sul contenuto del livello, mentre il generatore richiede un input maschera personalizzato per la fusione.

Viene utilizzato su un livello texture o all’interno di una maschera per aggiungere la fusione a tre planari.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Spazio globale normale:</b> | Utilizzare la mappa eseguita i baking World Space Normal. |
| <b>Posizione:</b> | Usa la mappa Posizione eseguita i baking. |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Proiezione:</b> | Selezionate gli assi lungo i quali proiettare le immagini. |
| <b>Metodo fusione:</b> | Selezionate il modo in cui le proiezioni degli assi si fondono tra loro. |
| <b>Fusione contrasto:</b> | Regolate il contrasto della fusione della proiezione. |
| <b>Affiancamento Texture:</b> | Regolate l&#39;Affiancamento della texture proiettata. |
| <b>Rotazione X:</b> | Regolate la rotazione della proiezione dell&#39;asse X. |
| <b>Scostamento X:</b> | Regolate lo scostamento della proiezione dell&#39;asse X. |
| <b>Rotazione Y:</b> | Regolate la rotazione della proiezione dell&#39;asse Y. |
| <b>Scostamento Y:</b> | Regolate lo scostamento della proiezione dell&#39;asse Y. |
| <b>Rotazione Z:</b> | Regolate la rotazione della proiezione dell&#39;asse Z. |
| <b>Scostamento Z:</b> | Regolate lo scostamento della proiezione dell&#39;asse Z. |

### Asse X

| Nome parametro | Descrizione |
| --- | --- |
| **Rotazione X:** | Regola la rotazione della proiezione della texture dell&#39;asse X. |
| **Scostamento X X:** | Regolate lo scostamento della proiezione dell&#39;asse X lungo l&#39;asse X. |
| **Scostamento X Y:** | Regolate lo scostamento della proiezione dell&#39;asse X lungo l&#39;asse Y. |

>[!NOTE]
>
> I parametri di offset contengono due assi nel titolo. Il primo definisce l&#39;asse di proiezione, mentre il secondo definisce l&#39;asse di offset. Quindi **Scostamento X Y** esamina in modo specifico la proiezione sull&#39;asse X e sposta tale proiezione lungo l&#39;asse Y locale delle proiezioni.
>
>Un altro modo di pensare è che **Offset X** compensa la proiezione X **orizzontalmente** e **Offset X Y** compensa la proiezione X **verticalmente**.

### Asse Y

| Nome parametro | Descrizione |
| --- | --- |
| **Rotazione X:** | Regolate la rotazione della proiezione della texture dell&#39;asse Y. |
| **Scostamento Y X:** | Regolate lo scostamento della proiezione dell&#39;asse Y lungo l&#39;asse X. |
| **Scostamento Y Y:** | Regolate lo scostamento della proiezione dell&#39;asse Y lungo l&#39;asse Y. |

>[!NOTE]
>
> I parametri di offset contengono due assi nel titolo. Il primo definisce l&#39;asse di proiezione, mentre il secondo definisce l&#39;asse di offset. Quindi **Scostamento Y X** esamina in modo specifico la proiezione sull&#39;asse Y e sposta tale proiezione lungo l&#39;asse X locale delle proiezioni.
>
>Un altro modo di pensare è che **Offset Y X** compensa la proiezione Y **in orizzontale** e **Offset Y** compensa la proiezione Y **in verticale**.

### Asse Z

| Nome parametro | Descrizione |
| --- | --- |
| **Rotazione X:** | Regolate la rotazione della proiezione della texture dell&#39;asse Z. |
| **Scostamento Z X:** | Regolate lo scostamento della proiezione dell&#39;asse Z lungo l&#39;asse X. |
| **Scostamento Z Y:** | Regolate lo scostamento della proiezione dell&#39;asse Z lungo l&#39;asse Y. |

>[!NOTE]
>
> I parametri di offset contengono due assi nel titolo. Il primo definisce l&#39;asse di proiezione, mentre il secondo definisce l&#39;asse di offset. Quindi **Scostamento Z Y** esamina in modo specifico la proiezione sull&#39;asse Z e sposta tale proiezione lungo l&#39;asse Y locale delle proiezioni.
>
>Un altro modo di pensare è che **Offset Z X** compensa la proiezione Z **orizzontalmente** e **Offset Z Y** compensa la proiezione Z **verticalmente**.
