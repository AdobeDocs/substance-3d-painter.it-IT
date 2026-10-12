---
breadcrumb-title: ""
description: Accedete alla pagina di riferimento relativa all’API shader di Alpha libreria in modo che Substance 3D Painter possa lavorare con i canali alfa e la trasparenza negli ombreggiatori personalizzati.
title: Lib Alpha - API shader
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
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


Emulazione test alfa: scartare il frammento corrente se l&#39;opacità è inferiore a una soglia definita dall&#39;utente. Dovrebbe essere chiamato dopo texture campionamenti chiamate: può rompere derivati

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
