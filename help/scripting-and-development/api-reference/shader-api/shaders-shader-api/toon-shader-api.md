---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/shaders-shader-api/toon-shader-api.html"
breadcrumb-title: ''
description: Accedete alla pagina di riferimento relativa alle API shader Toon in Substance 3D Painter per creare effetti di rendering personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Shaders - Shader API > Toon - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Toon - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---


# Toon - API shader

## Shader tonalità base

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


**associamo** la **curvatura della trama** alla nostra **curvatura\_tex** uniforme. Se non è disponibile alcuna curvatura, viene fornita una texture trasparente.

```
//: param auto texture_curvature 

uniform SamplerSparse curvature_tex;
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


Se preferiamo utilizzare la curvatura o meno.

```
//: param custom { 

//:   "default": false, 

//:   "label": "Use curvature" 

//: } 

uniform bool use_curvature;
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


**Per priorità** è necessario eseguire il **rilevamento struttura**. Consente all&#39;utente di scegliere se preferisce utilizzare o meno la mappa di curvatura per il rilevamento dei contorni.

```
  if (use_curvature) { 

    float curv = textureSparse(curvature_tex, inputs.sparse_coord).r; 

    NdV = 1.0 - curv; 

  }
```


Se la condizione di contorno è raggiunta, esci con il colore nero.

```
  if (NdV < mix(unlit_outline_thickness, lit_outline_thickness, NdL)) { 

    return; 

  }
```


Qui, eseguiamo una discretizzazione del colore in 4 passaggi.

```
  vec3 color = getBaseColor(basecolor_tex, inputs.sparse_coord); 

  if (NdL > 0.75) { 

    color = color; 

  } else if (NdL > 0.5) { 

    color = color * 0.5; 

  } else if (NdL > 0.1) { 

    color = color * 0.1; 

  } 

  else
```


Il fallback è nero.

```
    color = vec3(0.0); 

 

  diffuseShadingOutput(color); 

} 

 
```
