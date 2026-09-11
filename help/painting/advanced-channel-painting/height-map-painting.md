---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/advanced-channel-painting/height-map-painting.html"
breadcrumb-title: ''
description: Scoprite come pittura le mappe dell’altezza direttamente in Substance 3D Painter per creare effetti di spostamento e di elevazione delle superfici.
helpx_creative_field: ""
helpx_description: Painter > Painting > Advanced channel painting > Height Map Painting
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pittura mappa altezza
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 0%

---


# Pittura mappa altezza

## Idea generale

Lavorare su una mappa di altezza invece di lavorare direttamente su una normale offre diversi vantaggi, come una migliore qualità, un migliore controllo, flessibilità e una migliore coerenza tra le risorse.

La procedura è la seguente:

* Una mappa normale, eseguita i baking da una trama poly alta, viene caricata sulla trama poly bassa.
* Pittura ulteriori dettagli sul canale heightmap.
* Il Height pittura viene composto attraverso tutti i livelli e convertito in mappa normale in tempo reale, per poi essere fuso con la normale della trama poly più alta.

Tutto ciò di cui devi preoccuparti è dipingere quel height, tutto il resto viene fatto automaticamente.

### Formato height HDR

Il canale di Height utilizza un formato di colore **HDR**, che consente di colorare i valori positivi e negativi senza mai raggiungere un limite di luminosità, contrariamente alle tradizionali mappe di height che saturano tra 0 e 255.

* Quando colorate con una bitmap o una sostanza su un height, tale sorgente viene rimappata dal suo intervallo [0,255] originale a un intervallo [-1,1].

Un grigio medio verrà rimappato su 0. Di conseguenza, i valori inferiori a 127 **substrattano** dalla mappa di altezza, mentre i valori superiori a 127 **vi aggiungeranno** quando si utilizza il metodo di fusione predefinito impostato per le mappe height, **Scherma lineare (Aggiungi)**.

* Quando colorate con un colore normale, potete selezionare direttamente valori compresi tra -1 e 1.

### Visualizzazione height

Quando si visualizza la mappa dell’altezza in modalità Solo, l’anteprima predefinita mostra solo valori positivi, con una forte saturazione del nero per valori negativi.

L&#39;impostazione **+/- color** consente di visualizzare l&#39;intero intervallo utilizzando un colore diverso per i valori positivi e negativi.

L&#39;impostazione **Scala** consente di modificare l&#39;intervallo visibile di quella mappa HDR nel caso in cui abbiate aggiunto o sottratto più dell&#39;intervallo predefinito [-1,1].

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/height1.png)

</td>
<td style="border: 0;" valign="top">

![](../../assets/height2.png)

</td>
</tr>
</table>
