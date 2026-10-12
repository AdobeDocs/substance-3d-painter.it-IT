---
breadcrumb-title: ""
description: Accedete alla pagina di riferimento Lib Emissivo API shader per Substance 3D Painter per creare materiali emissivi ed effetti luminosi.
title: Lib Emissivo - API shader
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '54'
ht-degree: 0%
---

# Lib Emissivo - API shader

## lib-emissivo.glsl

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
