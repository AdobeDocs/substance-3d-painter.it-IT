---
breadcrumb-title: ""
description: Accedete alla pagina di riferimento per API shader Lib Bayer in Substance 3D Painter per creare pattern di dithering Bayer in ombreggiature personalizzate.
title: Lib Bayer - API shader
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '32'
ht-degree: 0%
---

# Lib Bayer - API shader

## lib-bayer.glsl

**Funzioni pubbliche:** *bayerMatrix8*

```
float bayerMatrix8(uvec2 coords) { 

  return (float(bayer(coords.x, coords.y)) + 0.5) / 64.0; 

} 

 
```
