---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/libraries-shader-api/lib-emissive-shader-api.html"
breadcrumb-title: ''
description: Accedete alla pagina di riferimento delle API shader Emissive Lib per Substance 3D Painter per creare materiali di emissione ed effetti luminosi.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Libraries - Shader API > Lib Emissive - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Lib Emissivo - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '54'
ht-degree: 0%

---


# Lib Emissivo - API shader

## lib-emissive.glsl

**Funzioni pubbliche:** *pbrComputeEmissive*

Importa da libreria

```
import lib-sparse.glsl
```


La texture del canale emissivo.

```
//: param auto channel_emissive 

uniform SamplerSparse emissive_tex;
```


Valore utilizzato per modificare l’intensità dell’emissivo.

```
//: param custom { 

//:   "default": 1.0, 

//:   "label": "Emissive Intensity", 

//:   "min": 0.0, 

//:   "max": 100.0, 

//:   "group": "Common Parameters" 

//: } 

uniform float emissive_intensity;
```


Calcolare la radianza emissivo per l&#39;occhio dell&#39;osservatore

```
vec3 pbrComputeEmissive(SamplerSparse emissive, SparseCoord coord) 

{ 

  return emissive_intensity * textureSparse(emissive, coord).rgb; 

} 

 
```
