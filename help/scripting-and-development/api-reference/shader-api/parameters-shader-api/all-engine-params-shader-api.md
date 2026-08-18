---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/scripting-and-development/api-reference/shader-api/parameters-shader-api/all-engine-params-shader-api.html"
breadcrumb-title: ''
description: Per controllare i parametri dello shader a livello di motore, accedere al riferimento di API shader Tutti i param motore (All Engine Params) in Substance 3D Painter.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Parameters - Shader API > All Engine Params - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Tutti i param motore - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '511'
ht-degree: 0%

---


# Tutti i param motore - API shader

## Esempi di parametri del motore

## Parametri texture

Substance Painter utilizza un sistema SVT (Sparse Virtual Texture) per visualizzare le texture nella finestra della vista.

Per ulteriori informazioni sul sistema, consultare la [documentazione online](../../../../features/sparse-virtual-textures.md).

Questo sistema ha ripercussioni sulla scrittura del codice dello shader. Stiamo fornendo degli assistenti per semplificarne l&#39;uso con le funzioni di ricerca della struttura e delle texture di *SamplerSparse* (vedi [lib-sparse.glsl](../libraries-shader-api/lib-sparse-shader-api.md)).

Utilizzo di base:

```
// Defines the SamplerSparse structure 

import lib-sparse.glsl 

 

//: param auto TEXTURE_TAG 

uniform SamplerSparse uniform_tex;   // Texture sampler and its information
```


I parametri della texture consentono di utilizzare l&#39;operatore &#39;or&#39; per definire un fallback:

```
//: param auto TEXTURE_TAG_1 or TEXTURE_TAG_2 

uniform SamplerSparse uniform_tex; // if TEXTURE_TAG_1 exists then TEXTURE_TAG_1 else TEXTURE_TAG_2
```


Dove *TEXTURE\_TAG* è uno dei tag descritti di seguito.

### Tag dei canali del documento

Tutte queste texture sono **premoltiplicate** e **dilatate** per evitare problemi di giuntura.

**Canali del set di texture**

*canale\_ambientocclusione* *canale\_anisotropiangolo* *canale\_anisotropilivello* *canale\_basecolor* *canale\_blendingmask* *canale\_diffuso* *canale\_spostamento* *canale\_emissivo* *canale\_lucidità* *canale\_height* *canale\_ior* *canale\_metallizzato* *canale\_normale* *canale\_opacità* *canale\_riflessione* *canale\_rugosità* *canale\_dispersione* *canale\_specular* *canale\_specularlevel* *canale\_trasmissivo*

**Canali utente**

*canale\_utente0* *canale\_utente1* *canale\_utente2* *canale\_utente3* *canale\_utente4* *canale\_utente5* *canale\_utente6* *canale\_utente7*

### Mappe delle mesh

*texture\_ambientocclusion*: mappa Occlusione ambiente\
*texture\_curvature*: mappa curvatura\
*texture\_id*: mappa ID\
*texture\_normal*: mappa normale dello spazio tangente\
*texture\_normal\_ws*: mappa normale spazio globale\
*texture\_position*: mappa posizione spazio mondo\
*texture\_thickness*: mappa Thickness

## Parametri di texture aggiuntivi

Utilizzo di base:

```
//: param auto TEXTURE_TAG 

uniform sampler2D uniform_tex;   // The texture itself 

 

//: param auto TEXTURE_TAG_size 

uniform vec4 uniform_tex_size;   // The size of the texture (width, height, 1/width, 1/height)
```


I parametri della texture consentono di utilizzare l&#39;operatore &#39;or&#39; per definire un fallback:

```
//: param auto TEXTURE_TAG_1 or TEXTURE_TAG_2 

uniform sampler2D uniform_tex; // if TEXTURE_TAG_1 exists then TEXTURE_TAG_1 else TEXTURE_TAG_2 

 

//: param auto TEX_TAG_1_size or TEX_TAG_2_size 

uniform vec4 uniform_tex_size; // if TEX_TAG_1 exists then TEX_TAG_1_size else TEX_TAG_2_size
```


Dove *TEXTURE\_TAG* è uno dei tag descritti di seguito.

*texture\_blue\_noise*: texture con disturbo blu\
*texture\_environment*: mappa dell&#39;ambiente, **mappata-mip**, utilizzare [lib-env.glsl](../libraries-shader-api/lib-env-shader-api.md) per utilizzare questa mappa

## Altri parametri

*aspect\_ratio*: un *float* contenente la finestra della vista *larghezza / height*

```
//: param auto aspect_ratio 

uniform float uniform_aspect_ratio;
```


*camera\_view\_matrix*: un *mat4* che rappresenta la trasformazione dallo spazio mondo allo spazio fotocamera

```
//: param auto camera_view_matrix 

uniform mat4 uniform_camera_view_matrix;
```


*camera\_view\_matrix\_it*: versione di trasposizione inversa di *camera\_view\_matrix*

```
//: param auto camera_view_matrix_it 

uniform mat4 uniform_camera_view_matrix_it;
```


*camera\_vp\_matrix\_inverse* : inversa della matrice *projection \* camera\_view\_matrix*

```
//: param auto camera_vp_matrix_inverse 

uniform mat4 uniform_camera_vp_matrix_inverse;
```


*ambiente\_esposizione*: un *float* che rappresenta l&#39;esposizione dell&#39;envmap

```
//: param auto environment_exposure 

uniform float uniform_environment_exposure;
```


*ambiente\_max\_lod*: un *float* che rappresenta la profondità della piramide mip-map dell&#39;envmap

```
//: param auto environment_max_lod 

uniform float uniform_max_lod;
```


*ambiente\_rotazione*: un *virgola mobile* che rappresenta la rotazione dell&#39;envmap attorno all&#39;asse superiore\
il valore è compreso nell&#39;intervallo [0,1] e deve essere mappato all&#39;intervallo [0, 2\*pi]

```
//: param auto environment_rotation 

uniform float uniform_environment_rotation;
```


*affiancati*: un *intero* che indica i volti sottoposti a rendering (-1: facce posteriori, 0: indefiniti, 1: facce anteriori)\
il valore 0 indica che è possibile fare affidamento sulla variabile incorporata *gl\_FrontFacing* di glsl

```
//: param auto facing 

uniform int uniform_facing;
```


*fovy* : un *float* che rappresenta il campo visivo della fotocamera lungo l&#39;asse Y

```
//: param auto fovy 

uniform float uniform_fovy;
```


*is\_2d\_view*: un *bool* che indica se il rendering viene eseguito per la vista 2D o meno

```
//: param auto is_2d_view 

uniform bool uniform_2d_view;
```


*is\_perspective\_projection*: un *bool* che indica se la proiezione è prospettica o ortogonale

```
//: param auto is_perspective_projection 

uniform bool uniform_perspective_projection;
```


*main\_light*: un *vec4* che indica la posizione della luce principale nell&#39;ambiente

```
//: param auto main_light 

uniform vec4 uniform_main_light;
```


*mvp\_matrix*: un *mat4* che rappresenta la matrice di proiezione della vista modello

```
//: param auto mvp_matrix 

uniform mat4 uniform_mvp_matrix;
```


*scena\_originale\_radius*: un *float* che rappresenta il raggio della sfera di delimitazione della scena prima della sua normalizzazione

```
//: param auto scene_original_radius 

uniform float uniform_scene_original_radius;
```


*schermo\_dimensione*: un *vec4* contenente i dati relativi alle dimensioni dello schermo *(larghezza, height, 1/larghezza, 1/height)*

```
//: param auto screen_size 

uniform vec4 uniform_screen_size;
```


*world\_camera\_direction*: un *vec3* che rappresenta l’orientamento della fotocamera mondiale

```
//: param auto world_camera_direction 

uniform vec3 uniform_world_camera_direction;
```


*world\_eye\_position* : un *vec3* che rappresenta la posizione dell&#39;occhio mondiale

```
//: param auto world_eye_position 

uniform vec3 uniform_world_eye_position; 

 
```
