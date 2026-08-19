---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/shaders-shader-api/surface-shader-shader-api.html"
breadcrumb-title: ''
description: Accedete al riferimento API shader superficie (Surface) per Substance 3D Painter per creare effetti e materiali di ombreggiatura personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Shaders - Shader API > Surface Shader - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Shader di superficie - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '114'
ht-degree: 0%

---


# Shader di superficie - API shader

## surface-shader.glsl

Per creare una risorsa shader utilizzabile in Substance Painter, è sufficiente creare un file glsl contenente una singola funzione denominata *shade* con il profilo seguente:

```
void shade(V2F inputs);
```


## Definizione del tipo di input V2F:

```
struct V2F { 

  vec3 normal;               // interpolated normal 

  vec3 tangent;              // interpolated tangent 

  vec3 bitangent;            // interpolated bitangent 

  vec3 position;             // interpolated position 

  vec4 color[1];             // interpolated vertex colors (color0) 

  vec2 tex_coord;            // interpolated texture coordinates (uv0) 

  SparseCoord sparse_coord;  // interpolated sparse texture coordinates used by textureSparse() sampling function 

  vec2 multi_tex_coord[8];   // interpolated texture coordinates (uv0-uv7) 

};
```


Nota: per ottenere un elemento SparseCoord per uv1-uv7, è necessario chiamare in modo esplicito *getSparseCoord(vec2)* definito in [lib-sparse.glsl](../libraries-shader-api/lib-sparse-shader-api.md)

## Uscite Surface Shader:

È possibile chiamare le seguenti funzioni dall&#39;interno della funzione *shade* per descrivere le proprietà dei frammenti:

```
// fragment opacity. default value: 1.0 

void alphaOutput(float); 

// diffuse lighting contribution. default value: vec3(0.0) 

void diffuseShadingOutput(vec3); 

// specular lighting contribution. default value: vec3(0.0) 

void specularShadingOutput(vec3); 

// color emitted by the fragment. default value: vec3(0.0) 

void emissiveColorOutput(vec3); 

// fragment color. default value: vec3(1.0) 

void albedoOutput(vec3); 

// subsurface scattering properties, see lib-sss.glsl for details. default value: vec4(0.0) 

void sssCoefficientsOutput(vec4);
```


Ad esempio, l’equazione di rendering di base per calcolare il colore del frammento è: *emissiveColor + albedo \* diffusaShading + specularShading*
