---
breadcrumb-title: ""
description: Scoprite come utilizzare gli input basati su trama negli effetti personalizzati per Substance 3D Painter per creare effetti di texture con riconoscimento della geometria.
title: Input basato su trama
user-guide-description: ""
user-guide-title: ""
source-git-commit: 4432887b652896f77fc3c99010436ef44aeb8a3e
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 1%
---

# Input basato su trama

L’input basato su trama è una texture fornita dal motore di Substance 3D Painter estratta dalla trama all’interno del progetto corrente. Queste texture possono essere utilizzate per creare effetti avanzati basati sulla topologia della trama.

>[!NOTE]
>
> Queste informazioni sulle trame si basano sulla topologia stessa e non tengono conto della mappa delle trame (texture eseguite i baking).
> 
> L&#39;input fornito dal motore è una texture a virgola mobile da 32 bit che verrà ridimensionata/bloccata al valore dell&#39;input nel grafico della Substance.

| Informazioni trama | Identificatore | Utilizzo | Descrizione |
| --- | --- | --- | --- |
| *Posizione (RGB)* | **trama\_posizione** | **posizioneTrama** | Recuperate una texture contenente la posizione del vertice. |
| *Spazio globale normale (RGB)* | **mesh\_world\_space\_normal** | **meshNormalWS** | Recuperate una texture contenente il vertice normale nello spazio mondo. |
| *Tangente spazio globale (RGB)* | **mesh\_world\_space\_tangent** | **meshTangentWS** | Recuperate una texture contenente il vertice tangente nello spazio mondo. |
| *World Space Bitangent (RGB)* | **mesh\_world\_space\_bitangent** | **meshBitangentWS** | Recuperate una texture contenente il vertice bi-tangente (bi-normale) nello spazio mondo. |
| *Dimensione Textel (Scala Di Grigi)* | **mesh\_texel\_size** | **meshTexelSize** | Recuperate una texture contenente la dimensione del testo (differenza tra la densità dei pixel e la trama UV). |
| *Maschera UV (scala di grigi)* | **trama\_uv\_mask** | **meshUVMask** | Recuperate una texture come maschera nera (esterna) e bianca (interna) delle Isole UV della trama. |
| *Vicina UV (RGB)* | **mesh\_uv\_next** | **meshUVNighbor** | Recuperare una texture con due informazioni. L&#39;interno delle Isole UV memorizza le coordinate UV regolari. La parte esterna delle Isole UV memorizza le coordinate UV del pixel sull&#39;altro lato delle giunture UV. Questa texture può essere utilizzata per creare effetti uniformi. |
