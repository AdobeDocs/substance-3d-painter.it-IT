---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/libraries-shader-api/lib-random-shader-api.html"
breadcrumb-title: ''
description: Accedete al riferimento Lib Random API shader per Substance 3D Painter per generare valori casuali nello sviluppo di shader personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Libraries - Shader API > Lib Random - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Lib Random - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '128'
ht-degree: 0%

---


# Lib Random - API shader

## lib-random.glsl

**Funzioni pubbliche:** *getBlueNoiseThreshold* *getBlueNoiseThresholdTemporal* *fibonacci1D* *fibonacci2D* *fibonacci2DDitheredTemporal*

Importa da libreria

```
import lib-defines.glsl
```


Una texture di disturbo blu 2D contenente valori scalari

```
//: param auto texture_blue_noise 

uniform sampler2D texture_blue_noise;
```


Risoluzione texture disturbo blu

```
const ivec2 texture_blue_noise_size = ivec2(256);
```


Numero casuale fotogramma corrente

```
//: param auto random_seed 

uniform int alg_random_seed;
```


Ottieni un valore casuale uniforme basato sulle coordinate dei pixel.

```
float getBlueNoiseThreshold() 

{ 

  return texture(texture_blue_noise, gl_FragCoord.xy / vec2(texture_blue_noise_size)).x + 0.5 / 65536.0; 

}
```


Ottieni un valore casuale uniforme basato sulle coordinate dei pixel e sull’ID fotogramma.

```
float getBlueNoiseThresholdTemporal() 

{ 

  return fract(getBlueNoiseThreshold() + M_GOLDEN_RATIO * alg_random_seed); 

}
```


Restituire il numero i *th* dalla sequenza di fibonacci.

```
float fibonacci1D(int i) 

{ 

  return fract((float(i) + 1.0) * M_GOLDEN_RATIO); 

}
```


Restituire la coppia i *th* dalla sequenza di fibonacci. nbSample è necessario per ottenere una distribuzione uniforme.

```
vec2 fibonacci2D(int i, int nbSamples) 

{ 

  return vec2( 

    (float(i)+0.5) / float(nbSamples), 

    fibonacci1D(i) 

  ); 

}
```


Restituire la coppia i *th* dalla sequenza di fibonacci. nbSample è necessario per ottenere una distribuzione uniforme. Questa versione ha una rotazione pseudo-casuale per fotogramma e per pixel applicata.

```
vec2 fibonacci2DDitheredTemporal(int i, int nbSamples) 

{ 

  vec2 s = fibonacci2D(i, nbSamples); 

  s.x += getBlueNoiseThresholdTemporal(); 

  return s; 

} 

 
```
