---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/libraries-shader-api/lib-alpha-shader-api.html"
breadcrumb-title: ''
description: Accedete alla pagina di riferimento API shader Alpha libreria affinché Substance 3D Painter possa lavorare con i canali alfa e la trasparenza negli ombreggiatori personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Libraries - Shader API > Lib Alpha - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Lib Alpha - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '72'
ht-degree: 0%

---


# Lib Alpha - API shader

## lib-alpha.glsl

**Funzioni pubbliche:** *alphaKill*

```
import lib-sampler.glsl 

import lib-random.glsl
```


Mappa dell&#39;opacità, fornita dal motore.

```
//: param auto channel_opacity 

uniform SamplerSparse opacity_tex;
```


Soglia di prova di Alpha.

```
//: param custom { 

//:   "default": 0.33, 

//:   "label": "Alpha threshold", 

//:   "min": 0.0, 

//:   "max": 1.0, 

//:   "group": "Common Parameters" 

//: } 

uniform float alpha_threshold;
```


dithering del test di Alpha.

```
//: param custom { 

//:   "default": false, 

//:   "label": "Alpha dithering", 

//:   "group": "Common Parameters" 

//: } 

uniform bool alpha_dither;
```


Emulazione test alfa: scartare il frammento corrente se l&#39;opacità è inferiore a una soglia definita dall&#39;utente. Deve essere chiamato richiami di campionamento delle texture AFTER: può rompere i derivati

```
void alphaKill(float alpha) 

{ 

  float threshold = alpha_dither ? getBlueNoiseThresholdTemporal() : alpha_threshold; 

  if (alpha < threshold) discard; 

} 

 

void alphaKill(SparseCoord coord) 

{ 

  alphaKill(getOpacity(opacity_tex, coord)); 

} 

 
```
