---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/features/physical-size.html"
breadcrumb-title: ''
description: Scoprite come impostare la dimensioni fisiche in Substance 3D Painter per definire le dimensioni reali per un ridimensionamento accurato della texture.
helpx_creative_field: ""
helpx_description: Painter > Features > Physical size
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Dimensione fisica
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 2%

---


# Dimensione fisica

![](../assets/banner-physicalsize-2.png)

La dimensioni fisiche è una proprietà all&#39;interno dei materiali della Substance che ne definisce le dimensioni reali. Può essere utilizzato per abbinare con precisione le dimensioni e l&#39;aspetto dei materiali sulle superfici 3D. Painter usa i centimetri come unità interna predefinita.

Per utilizzare la dimensioni fisiche, applicate un materiale che ha questa proprietà con un valore diverso da 0,0,0, quindi attivate la modalità dimensioni fisiche nel livello (o effetto) di riempimento in Trasformazione UV > Scala.

Per ulteriori informazioni, consulta:

* <b>Dimensioni fisiche</b> parametri in [Riempi proiezioni](../painting/fill-projections/fill-projections.md)
* <b>Parametri Griglia</b> in [Impostazioni viewport](../interface/display-settings/viewport-settings.md)
* <b>Spostamento basato sulla dimensioni fisiche</b> in [Impostazioni shader](../interface/shader-settings/shader-settings.md)

>[!NOTE]
>
> * Dalla versione 8.3 di Painter, dimensioni fisiche è disponibile per tutti i tipi di proiezioni.
> * La maggior parte dei formati di file di mesh specifica l&#39;unità utilizzata durante la creazione della trama; questa unità verrà convertita automaticamente in centimetri durante l&#39;importazione.
> * Alcuni formati, come .obj, non dispongono di informazioni sulle unità; pertanto, quando un progetto viene creato utilizzando una trama .obj, per impostazione predefinita viene misurato in centimetri senza alcuna conversione.
