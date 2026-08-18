---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/scripting-and-development/api-reference/shader-api/libraries-shader-api/lib-utils-shader-api.html"
breadcrumb-title: ''
description: Accedete alla guida di riferimento per l’API shader Lib Utils in modo che Substance 3D Painter utilizzi le funzioni di utilità nello sviluppo di shader personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Libraries - Shader API > Lib Utils - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Utilità libbra - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '238'
ht-degree: 0%

---


# Utilità libbra - API shader

## Funzioni di utilità allegoritmiche

## Mappatura toni

Questi sono esempi di mappatura dei toni che puoi utilizzare nello shader. Painter non applica alcuna mappatura dei toni, ad eccezione di quella facoltativa applicata da Yebis. Se decidi di eseguire una mappatura dei toni nello shader, questa verrà applicata prima di Yebis.

Esegui la mappatura dei toni della curva a S in base ai parametri sigma e n.

```
vec3 tonemapSCurve(vec3 value, float sigma, float n) 

{ 

  vec3 pow_value = pow(value, vec3(n)); 

  return pow_value / (pow_value + pow(sigma, n)); 

}
```


## Conversioni sRGB

Queste sono le conversioni utilizzate in Painter. Puoi ignorare la conversione lineare -> sRGB automatica nella finestra della vista inserendo questa linea nello shader personalizzato:

*#define DISABLE\_FRAMEBUFFER\_SRGB\_CONVERSION*

e realizzare una conversione personalizzata.

sRGB per la conversione lineare dei colori. Versione scalare.

```
float sRGB2linear(float x) 

{ 

  return x <= 0.04045 ? 

    x * 0.0773993808 : // 1.0/12.92 

    pow((x + 0.055) / 1.055, 2.4); 

}
```


sRGB per la conversione lineare dei colori. Versione di RGB.

```
vec3 sRGB2linear(vec3 rgb) 

{ 

  return vec3( 

    sRGB2linear(rgb.r), 

    sRGB2linear(rgb.g), 

    sRGB2linear(rgb.b)); 

}
```


sRGB per la conversione lineare dei colori. Versione RGB + Alpha.

```
vec4 sRGB2linear(vec4 rgba) 

{ 

  return vec4(sRGB2linear(rgba.rgb), rgba.a); 

}
```


Conversione del colore da lineare a sRGB. Versione scalare.

```
float linear2sRGB(float x) 

{ 

  return x <= 0.0031308 ? 

      12.92 * x : 

      1.055 * pow(x, 0.41666) - 0.055; 

}
```


Conversione del colore da lineare a sRGB. Versione di RGB.

```
vec3 linear2sRGB(vec3 rgb) 

{ 

  return vec3( 

      linear2sRGB(rgb.r), 

      linear2sRGB(rgb.g), 

      linear2sRGB(rgb.b)); 

}
```


Conversione del colore da lineare a sRGB. Versione RGB + Alpha.

```
vec4 linear2sRGB(vec4 rgba) 

{ 

  return vec4(linear2sRGB(rgba.rgb), rgba.a); 

}
```


Conversione del colore da lineare a sRGB opzionale. Versione scalare.

```
//: param auto conversion_linear_to_srgb 

uniform bool convert_to_srgb_opt; 

float linear2sRGBOpt(float x) 

{ 

  return convert_to_srgb_opt ? linear2sRGB(x) : x; 

}
```


Conversione del colore da lineare a sRGB opzionale. Versione di RGB.

```
vec3 linear2sRGBOpt(vec3 rgb) 

{ 

  return convert_to_srgb_opt ? linear2sRGB(rgb) : rgb; 

}
```


Conversione del colore da lineare a sRGB opzionale. Versione RGB + Alpha.

```
vec4 linear2sRGBOpt(vec4 rgba) 

{ 

  return convert_to_srgb_opt ? linear2sRGB(rgba) : rgba; 

}
```


Conversione del colore. Versione scalare.

```
uniform int output_conversion_method; 

float convertOutput(float x) 

{ 

 if (output_conversion_method == 0) return x; 

 else if (output_conversion_method == 1) return linear2sRGB(x); 

 else return sRGB2linear(x); 

}
```


Conversione del colore. Versione di RGB.

```
vec3 convertOutput(vec3 rgb) 

{ 

 if (output_conversion_method == 0) return rgb; 

 else if (output_conversion_method == 1) return linear2sRGB(rgb); 

 else return sRGB2linear(rgb); 

}
```


Conversione del colore. Versione RGB + Alpha.

```
vec4 convertOutput(vec4 rgba) 

{ 

 if (output_conversion_method == 0) return rgba; 

 else if (output_conversion_method == 1) return linear2sRGB(rgba); 

 else return sRGB2linear(rgba); 

}
```


## Dithering

Ecco alcuni strumenti che consentono di aggiungere il dithering agli ombreggiatori.

Usa la matrice Bayer 8x8 per la modalità dithering

```
import lib-bayer.glsl 

 

float getDitherThreshold(uvec2 coords) 

{ 

  return bayerMatrix8(coords); 

} 

 

 

vec4 RGB2Gray(vec4 rgba) 

{ 

  float gray = 0.299 * rgba.r + 0.587 * rgba.g + 0.114 * rgba.b; 

  return vec4(vec3(gray), rgba.a); 

}
```


Rimuovi AO e ombre su superfici metalliche lucide (vicino agli specchi)

```
float specularOcclusionCorrection(float diffuseOcclusion, float metallic, float roughness) 

{ 

  return mix(diffuseOcclusion, 1.0, metallic * (1.0 - roughness) * (1.0 - roughness)); 

} 

 
```
