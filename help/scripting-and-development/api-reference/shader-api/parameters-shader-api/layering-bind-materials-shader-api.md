---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/parameters-shader-api/layering-bind-materials-shader-api.html"
breadcrumb-title: ''
description: Accedete alla pagina di riferimento relativa all’API shader Associazione di materiali livelli in cui Substance 3D Painter consente di associare i materiali nei flussi di lavoro con più livelli.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Parameters - Shader API > Layering Bind Materials - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Materiali di rilegatura livelli - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 0%

---


# Materiali di rilegatura livelli - API shader

## Livelli di materiale: associa i materiali come parametri di shader

Un materiale è definito da un identificatore univoco &#39;id&#39;. Parametri aggiuntivi:

* &#39;default&#39;: il nome predefinito della risorsa materiale da utilizzare.
* &#39;size&#39;: la dimensione della texture delle mappe del materiale.
* &#39;group&#39;: il gruppo dell&#39;interfaccia utente del widget di selezione del materiale.

Esempio:

```
//:  materials [ 

//:    { 

//:       "id": "Material1", 

//:       "default": "Concrete 044", 

//:       "size": 512, 

//:       "group": "Material 1" 

//:    }, { 

//:       "id": "Material2", 

//:       "default": "Leaves elm", 

//:       "size": 1024, 

//:       "group": "Material 2" 

//:    } 

//:  ]
```


Per associare un canale da un materiale a un campionatore, definisci un parametro automatico con l’ID del materiale seguito dal tag del canale (vedi i canali disponibili in [all-engine-params.glsl](all-engine-params-shader-api.md)):

```
//: param auto Material1.channel_basecolor 

uniform sampler2D basecolor_tex1; 

//: param auto Material1.channel_metallic 

uniform sampler2D metallic_tex1; 

//: param auto Material1.channel_roughness 

uniform sampler2D roughness_tex1; 

 

//: param auto Material2.channel_basecolor 

uniform sampler2D basecolor_tex2; 

//: param auto Material2.channel_metallic 

uniform sampler2D metallic_tex2; 

//: param auto Material2.channel_roughness 

uniform sampler2D roughness_tex2; 

 
```
