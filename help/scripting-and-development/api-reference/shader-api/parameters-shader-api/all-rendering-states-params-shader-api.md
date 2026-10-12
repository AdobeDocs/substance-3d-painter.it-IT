---
breadcrumb-title: ""
description: Per controllare i parametri dello stato di rendering in Substance 3D Painter, accedete al riferimento di API shader Tutti gli stati di rendering per i parametri di stato di rendering.
title: Tutti gli stati di rendering Param - API shader
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
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


## Località di campionamento Shader

Per impostazione predefinita, i canali del documento vengono campionati utilizzando le coordinate delle texture non trasformate per ottimizzare il rendering durante il disegno.

Se vengono visualizzati elementi, impostare lo stato *non locale* su *on*.

```
//: state nonlocal on 

 
```
