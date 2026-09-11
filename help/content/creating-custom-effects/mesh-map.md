---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/content/creating-custom-effects/mesh-map.html"
breadcrumb-title: ''
description: Scoprite come utilizzare le mappe trama negli effetti personalizzati in modo che Substance 3D Painter possa accedere alle informazioni sulla texture basata sulla geometria.
helpx_creative_field: ""
helpx_description: Painter > Content > Creating custom effects > Mesh Map
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mappa trama
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
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
| *occlusione ambiente* | **ambientOcclusionBase** | **ambiente\_occlusione** |
| *ID* | **id** | **id** |
| *Curvatura* | **curvatura** | **curvatura** |
| *Normale* | **normalBase** | **normale\_base** |
| *Normali dello spazio globale* | **normalWS** | **mondo\_spazio\_normali** |
| *Posizione* | **posizione** | **posizione** |
| *Thickness* | **thickness** | **thickness** |
| *Height* | **heightBase** | **height\_base** |
| *Normali incurvate* | **bentNormalsBase** | **piegato\_normali\_base** |
| *Opacità* | **opacityBase** | **opacità\_base** |
