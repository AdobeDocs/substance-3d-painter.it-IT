---
breadcrumb-title: ""
description: Scoprite come utilizzare le mappe trama negli effetti personalizzati in modo che Substance 3D Painter possa accedere alle informazioni sulla texture basata sulla geometria.
title: Mappa trama
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 3%
---

# Mappa trama

Per collegare automaticamente le mappe trama (texture eseguite i baking) quando un effetto viene aggiunto su un livello, è necessario seguire una convenzione di denominazione specifica.

>[!NOTE]
>
> È possibile utilizzare **l&#39;utilizzo** o **l&#39;identificatore** in un nodo di input (l&#39;utilizzo ha la priorità).

Di seguito è riportata la convenzione di denominazione per ogni mappa mesh:

| Mappa di mesh | Utilizzo | Identificatore |
| --- | --- | --- |
| *Occlusione ambientale* | **ambientOcclusionBase** | **ambiente\_occlusione** |
| *ID* | **id** | **id** |
| *Curvatura* | **curvatura** | **curvatura** |
| *Normale* | **normalBase** | **normale\_base** |
| *Normali dello spazio globale* | **normalWS** | **mondo\_spazio\_normali** |
| *Posizione* | **posizione** | **posizione** |
| *Thickness* | **thickness** | **thickness** |
| *Height* | **heightBase** | **height\_base** |
| *Normali incurvate* | **bentNormalsBase** | **piegato\_normali\_base** |
| *Opacità* | **opacityBase** | **opacità\_base** |
