---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/advanced-channel-painting/flow-map-painting.html"
breadcrumb-title: ''
description: Scoprite come colorare le mappe di flusso in Substance 3D Painter per controllare la direzione del flusso del materiale e gli effetti anisotropi.
helpx_creative_field: ""
helpx_description: Painter > Painting > Advanced channel painting > Flow Map Painting
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pittura mappa di flusso
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---


# Pittura mappa di flusso

È previsto un canale dedicato, ma nel frattempo utilizzando il canale Normale e alcuni parametri del pennello è possibile colorare le mappe di flusso in Substance 3D Painter.

## Passaggio 1: crea la mappa normale

Create una texture mappa normale di 16x16 pixel. Il colore deve essere 128, 255, 128, che dovrebbe dare il colore seguente: ![](../../assets/up-dx.png)\
(Questo colore equivale a un vettore che cerca verso l’alto, in DirectX)

## Passaggio 2: aggiungi canale normale

Nel progetto Substance 3D Painter, aggiungete un canale **Normale** tramite le **impostazioni del set di texture** se questo canale non esiste già.

## Passaggio 3: impostazione del pennello

Abilitate la funzione Segui tracciato nei parametri del pennello. Caricate la texture della mappa normale (punto 1) nello slot del canale normale. Disattivate gli altri canali.

![](../../assets/brush-settings-1.png){width="300px"}

## Passaggio 4 : Dipingi!

Dipingendo sulla trama con l’impostazione Segui tracciato attivata, i tratti del pennello disegneranno le direzioni nella mappa normale.

![](../../assets/painting-1.png){width="700px"}
