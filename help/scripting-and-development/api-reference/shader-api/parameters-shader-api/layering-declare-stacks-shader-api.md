---
breadcrumb-title: ""
description: Accedete alla pagina di riferimento relativa alle API shader di dichiarazione dei livelli per Substance 3D Painter, con cui potete creare stack di livelli di materiale personalizzati.
title: Sovrapposizione delle pile di dichiarazione - API shader
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '101'
ht-degree: 0%
---

# Sovrapposizione delle pile di dichiarazione - API shader

## Livelli di materiale: dichiarare pile modificabili

Una serie modificabile è definita da un identificatore univoco e da un elenco di canali del documento. Gli ID di canale possibili sono: *ambientocclusione* *anisotropiangolo* *anisotropilivello* *basecolor* *blendingmask* *diffuso* *spostamento* *emissivo* *lucentezza* *height* *ior* *metallizzato* *normale* *opacità* *riflessione* *rugosità* *dispersione* *specular* *specularlevel* *trasmissivo* *utente0* *utente1* *utente2* *utente3* *utente4* *utente5* *utente6* *utente7*

Esempio:

```
//:  stacks [ 

//:    { 

//:      "id": "Mask1", 

//:      "channels": [ 

//:        {"id": "opacity"} 

//:      ] 

//:    }, { 

//:      "id": "Mask2", 

//:      "channels": [ 

//:        {"id": "opacity"}, 

//:        {"id": "user0"} 

//:      ] 

//:    } 

//:  ]
```


Per associare un canale da una pila a un parametro campionatore, anteporre il tag channel all’identificatore della pila:

```
//: param auto Mask1.channel_opacity 

uniform sampler2D mask_tex1; 

//: param auto Mask2.channel_opacity 

uniform sampler2D mask_tex2; 

 
```
