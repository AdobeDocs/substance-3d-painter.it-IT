---
title: Edge Wear dettagliato MatFX
description: Scopri come utilizzare il filtro Edge Wear dettagli MatFX in Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '345'
ht-degree: 1%
---

# Edge Wear dettagliato MatFX

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="./Resources/icon_matfx_detail_edge_wear.png" alt="Icona Edge Wear dettagli MatFX" title="Edge Wear dettagliato MatFX"/><br><strong>Ingresso:</strong> Effetti/usura, bordo, materiale</td>
    <td style="border: 0;" valign="top">Descrizione<br>Il filtro Edge Wear dettagli MatFX consente di creare i dettagli del bordo usurato che possono essere fusi in un materiale.<br>Viene utilizzato su un livello di texture o una pila di materiali per aggiungere usura dei bordi, rottura delle grungi e regolazioni del materiale di supporto guidate da maschere e dati di curvatura.</td>
  </tr>
</table>

>[!NOTE]
>
> Affinché il filtro di Edge Wear Dettagli MatFX abbia un effetto visibile, è necessario che esistano informazioni normali variabili nella Pila livelli sotto il filtro. Se non ci sono dati o varietà nel canale normale, il filtro non sarà in grado di trovare i bordi da danneggiare e non avrà effetti visibili.

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| **Intensità sfocatura:** | Regolate l’intensità dell’effetto di sfocatura. |
| **Contorna con sfocatura:** | Attivate/disattivate l’opzione di ritorno a capo automatico. Quando è attivato, l’effetto campiona i pixel dal lato opposto della texture. |
| **Modalità di input:** | Selezionare la modalità di input utilizzata per attivare l&#39;effetto di usura. |
| **Livello di usura:** | Regolare il livello di usura complessivo. |
| **Contrasto usura:** | Regola il contrasto della maschera di usura. |
| **Smoothness bordi:** | Regolate lo smoothness dei bordi usurati. |
| **Quantità Grungi:** | Regolate la quantità di grunge aggiunta all&#39;usura. |
| **Scala Grungi:** | Regolate la scala del motivo della grunge. |

### Materiale

**Rugosità metallica PBR**

|  |  |
| --- | --- |
| **Colore di base:** | Regola il contributo del colore di base. |
| **Metallico:** | Regolate il valore metallico. |
| **Rugosità:** | Regolate il valore di rugosità. |

**Lucentezza Specular PBR**

|  |  |
| --- | --- |
| **Diffusa:** | Regolate il contributo diffusione. |
| **Colore Specular:** | Regolate il colore dello specular. |
| **Lucentezza:** | Regolate il valore della lucentezza. |

### Impostazioni

|  |  |
| --- | --- |
| **Controllo Maschera Generatore:** | Regolate l’influenza della maschera del generatore. |
| **Contrasto maschera generatore:** | Regolate il contrasto della maschera del generatore. |
| **Sfocatura maschera generatore:** | Regolate la sfocatura applicata alla maschera del generatore. |
| **Valore sfondo Alpha:** | Regolate il valore alfa dello sfondo. |
| **Intensità curvatura:** | Regolate l’intensità dell’input di curvatura. |
| **Inverti curvatura:** | Attiva/disattiva l’inversione dell’input di curvatura. |
| **Combina curvatura:** | Attiva/disattiva la combinazione dei dati di curvatura invertiti e non invertiti. |
| **Intensità normale:** | Regolate l’intensità normale. |
| **Distribuzione AO:** | Regolate la diffusione dell’effetto di occlusione ambientale. |
