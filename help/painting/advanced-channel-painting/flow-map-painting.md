---
breadcrumb-title: ""
description: Scoprite come pittura le mappe di flusso in Substance 3D Painter per controllare la direzione del flusso di materiale ed effetti anisotropi.
title: Pittura mappa di flusso
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%
---

# Pittura mappa di flusso

È previsto un canale dedicato, ma nel frattempo utilizzando il canale Normale e alcuni parametri del pennello è possibile pittura le mappe di flusso in Substance 3D Painter.

## Passaggio 1: creazione della mappa normale

Create una texture mappa normale di 16x16 pixel. Il colore deve essere 128, 255, 128, che dovrebbe dare il colore seguente: ![](../../assets/up-dx.png)\
(Questo colore equivale a un vettore che cerca verso l’alto, in DirectX)

## Passaggio 2: aggiungi canale normale

Nel progetto Substance 3D Painter, aggiungete un canale **Normale** tramite le **impostazioni del set di texture** se questo canale non esiste già.

## Passaggio 3: impostazione del pennello

Abilitate la funzione Segui tracciato nei parametri del pennello. Caricare la texture della mappa normale (punto 1) nello slot del canale normale. Disattivate gli altri canali.

![](../../assets/brush-settings-1.png){width="300px"}

## Passaggio 4: Pittura!

Dipingendo sulla trama con l’impostazione Segui tracciato attivata, i tratti del pennello disegneranno le direzioni nella mappa normale.

![](../../assets/painting-1.png){width="700px"}
