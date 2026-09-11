---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/scripting-and-development/api-reference/shader-api/shaders-shader-api/pixelated-shader-api.html"
breadcrumb-title: ''
description: Per Substance 3D Painter, accedi alla sezione API shader con effetto pixel per creare effetti di rendering con effetto pixel personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Shaders - Shader API > Pixelated - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Effetto pixel - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 0%

---


# Effetto pixel - API shader

## Shader con effetto pixel di base

Importa da librerie.

```
import lib-sampler.glsl
```


Definiamo la posizione della luce globale

```
const vec3 light_pos = vec3(10.0, 10.0, 10.0);
```


**associamo** l&#39;auto param world eye position alla nostra uniforme **fotocamera\_pos**.

```
//: param auto world_eye_position 

uniform vec3 camera_pos;
```


**Associamo** il canale del documento **colore di base** alla nostra uniforme **colore di base\_tex**.

```
//: param auto channel_basecolor 

uniform SamplerSparse basecolor_tex;
```


Definiamo una nuova regolazione personalizzata per questo shader, insieme al suo valore predefinito. Questo viene utilizzato per modificare il thickness di contorno, quando è ombreggiato.

```
//: param custom { 

//:  "default": 0.4, 

//:   "min": 0.0, 

//:   "max": 1.0, 

//:   "label": "Unlit outline thickness" 

//: } 

uniform float unlit_outline_thickness;
```


Definiamo una nuova regolazione personalizzata per questo shader, insieme al suo valore predefinito. Questo viene utilizzato per modificare il thickness di contorno, quando è illuminato.

```
//: param custom { 

//:   "default": 0.1, 

//:   "min": 0.0, 

//:   "max": 1.0, 

//:   "label": "Lit outline thickness" 

//: } 

uniform float lit_outline_thickness;
```


Punto di ingresso dello shader.

```
void shade(V2F inputs) 

{
```


Calcoliamo alcuni valori utili.

```
  vec3 V = normalize(camera_pos - inputs.position); 

  vec3 N = normalize(inputs.normal); 

  vec3 L = normalize(light_pos - inputs.position); 

  float NdV = dot(N, V); 

  float NdL = max(0.0, dot(N, L));
```


**Per priorità** è necessario eseguire il **rilevamento struttura**. Se la condizione di contorno è raggiunta, esci con il colore nero.

```
  if (NdV < mix(unlit_outline_thickness, lit_outline_thickness, NdL)) { 

    return; 

  } 

 

  vec3 baseColor = getBaseColor(basecolor_tex, inputs.sparse_coord);
```


Introdurre una certa variazione nelle dimensioni della maschera, in base alla luminanza del colore di base

```
  float maskRadiusJitter = pow(dot(baseColor, vec3(0.3333)), 0.1);
```


Calcolare un valore di maschera in base alla posizione del frammento nello spazio su schermo. In questo modo viene creata una griglia come pattern.

```
  float mask = pow(1.0 - length(fract(gl_FragCoord.xy / 7.0) - vec2(0.5)), maskRadiusJitter * 5.0) * 5.0;
```


Qui, campioniamo il colore di base e applichiamo una semplice attenuazione diffusa

```
  vec3 color = baseColor * NdL; 

 

  diffuseShadingOutput(mask * color); 

} 

 
```
