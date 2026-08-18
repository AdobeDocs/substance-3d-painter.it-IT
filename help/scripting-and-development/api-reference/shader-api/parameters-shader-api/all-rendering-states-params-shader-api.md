---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/scripting-and-development/api-reference/shader-api/parameters-shader-api/all-rendering-states-params-shader-api.html"
breadcrumb-title: ''
description: Per controllare i parametri dello stato di rendering in Substance 3D Painter, accedete al riferimento di API shader Tutti gli stati di rendering per i parametri di stato di rendering.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Parameters - Shader API > All Rendering States Params - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Tutti gli stati di rendering Param - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '107'
ht-degree: 2%

---


# Tutti gli stati di rendering Param - API shader

## Esempi di stati di rendering

## Culling faccia posteriore

Sfilacciare le facce posteriori:

```
//: state cull_face on
```


Disegnare facce anteriori e posteriori:

```
//: state cull_face off
```


## Fusione

Nessun oggetto con fusione e completamente opaco:

```
//: state blend none
```


Metodo di fusione standard per l&#39;ordine di disegno da dietro a davanti:

```
//: state blend over
```


Metodo di fusione standard per l&#39;ordine di disegno da dietro a davanti. Si supponga che il colore sia premoltiplicato per alfa:

```
//: state blend over_premult
```


Metodo fusione additivo:

```
//: state blend add
```


Metodo fusione moltiplicativo:

```
//: state blend multiply
```


## Località di campionamento shader

Per impostazione predefinita, i canali del documento vengono campionati utilizzando le coordinate della texture non trasformate per ottimizzare il rendering durante il disegno.

Se vengono visualizzati elementi, impostare lo stato *non locale* su *on*.

```
//: state nonlocal on 

 
```
