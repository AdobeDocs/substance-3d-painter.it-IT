---
breadcrumb-title: ""
description: Scoprite come correggere gli arresti anomali di Substance 3D Painter quando si lavora con GPU con overclock per prestazioni stabili dell'applicazione.
title: Arresto anomalo quando si lavora con la GPU con overclock
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%
---

# Arresto anomalo quando si lavora con la GPU con overclock

Le GPU con overclock possono spesso essere più instabili perché eseguono frequenze che non sono state inizialmente progettate dal costruttore della GPU. Se la GPU è con overclock e si verificano problemi di stabilità, si consiglia di tornare per un po’ alle frequenze predefinite di fabbrica.

## GPU Nvidia

Nelle GPU Nvidia, a partire dai driver 355.82, è possibile disattivare temporaneamente l’overclock della GPU attivando una modalità di debug nelle impostazioni dei driver. Ciò consente di controllare e determinare i problemi relativi alle schede grafiche.

Per attivare la modalità di debug:

1. Apri il **Pannello di controllo Nvidia** (fai clic con il pulsante destro del mouse sul desktop).
1. Fare clic sul menu **Guida**.
1. Fare clic su **Modalità debug**.

>[!NOTE]
>
> La modalità di debug potrebbe non essere disponibile se la GPU è una scheda di riferimento. Sarà disponibile solo se la GPU viene eseguita con orologi non standard o con un BIOS modificato. In questo caso, si consiglia di disattivare manualmente l’overclock.
