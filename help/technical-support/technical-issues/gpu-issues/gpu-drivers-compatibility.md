---
breadcrumb-title: ""
description: Scoprite i requisiti di compatibilità dei driver GPU per Substance 3D Painter per garantire la stabilità del rendering e delle prestazioni.
title: Compatibilità dei driver GPU
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 2%
---

# Compatibilità dei driver GPU

Questa pagina raggruppa le informazioni sui driver GPU che possono causare problemi con Substance 3D Painter.

## Nvidia

La tabella seguente elenca tutte le versioni dei driver che sono in grado di creare problemi per la GPU Nvidia (modelli GeForce o Quadro):

| *Versione driver* | *Descrizione del problema* |
| --- | --- |
| <b> 425.xx </b> | Raytracing GPU artefatti. |
| <b> 429.xx o precedente </b> | Artefatti del blocco di texture nera. |
| <b> 435.xx o precedente </b> | Problemi di colore sRGB durante il calcolo della texture. |
| <b> 439.xx </b> | Texture corruzione. |
| <b> 441.08 </b> | Problemi di Arresto anomalo o stabilità. |
| <b> 442.19 </b> | Problemi di Arresto anomalo o stabilità. |
| <b>528.09</b> | Blocco del sistema operativo. |
| Da <b>572.16 a 572.42</b> | Artefatti o arresti anomali quando si eseguono i baking texture. |

### AMD

| *Versione driver* | *Descrizione del problema* |
| --- | --- |
| Da **20.7.x** a **20.11.2** | Texture difetto o corruzione. |
| Da **20.11.3** a **21.2.1** | Texture difetti o corruzione più problemi di arresto anomalo o stabilità. |
| Da **21.2.3** a **21.6.1** | Problemi di Arresto anomalo o stabilità. |
