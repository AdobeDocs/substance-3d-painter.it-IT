---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/advanced-channel-painting/height-map-painting.html"
breadcrumb-title: ''
description: Scoprite come colorare le mappe dei height direttamente in Substance 3D Painter per creare effetti di spostamento e di elevazione delle superfici.
helpx_creative_field: ""
helpx_description: Painter > Painting > Advanced channel painting > Height Map Painting
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pittura mappa height
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 0%

---


# Pittura mappa height

## Idea generale

Lavorare su una mappa di altezza invece di lavorare direttamente su una normale offre diversi vantaggi, come una migliore qualità, un migliore controllo, flessibilità e una migliore coerenza tra le risorse.

La procedura è la seguente:

* Una mappa normale, cotta da una maglia poly alta, viene caricata sulla maglia poly bassa.
* Dipingerai ulteriori dettagli sul canale della mappa dell’altezza.
* Il Height che dipingete viene composto attraverso tutti i livelli e convertito in una mappa normale in tempo reale, e infine fuso con la normale dalla trama poli alta.

Tutto ciò di cui devi preoccuparti è dipingere quel height, tutto il resto viene fatto automaticamente.

### Formato HDR height

Il canale di Height utilizza un formato di colore **HDR**, che consente di colorare i valori positivi e negativi senza mai raggiungere un limite di luminosità, contrariamente alle tradizionali mappe di height che saturano tra 0 e 255.

* Quando colorate con una bitmap o una sostanza su un height, tale sorgente viene rimappata dal suo intervallo [0,255] originale a un intervallo [-1,1].

Un grigio medio verrà rimappato su 0. Di conseguenza, i valori inferiori a 127 **substrattano** dalla mappa di altezza, mentre i valori superiori a 127 **vi aggiungeranno** quando si utilizza il metodo di fusione predefinito impostato per le mappe height, **Scherma lineare (Aggiungi)**.

* Quando colorate con un colore normale, potete selezionare direttamente valori compresi tra -1 e 1.

### Visualizzazione height

Quando si visualizza la mappa del Height in modalità Solo, l’anteprima predefinita mostra solo valori positivi, con una forte saturazione del nero per valori negativi.

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
