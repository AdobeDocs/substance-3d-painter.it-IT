---
breadcrumb-title: ""
description: Scopri come correggere le finestre di visualizzazione e la texture sfocate in Substance 3D Painter per garantire una qualità visiva nitida e chiara.
title: Le finestre di visualizzazione e la texture sono sfocate o poco nitide
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 1%
---

# Le finestre di visualizzazione e la texture sono sfocate o poco nitide

Le finestre delle viste possono apparire sfocate per motivi diversi.

## Impostazioni per schermi ad alto DPI (Retina)

Per impostazione predefinita, Substance 3D Painter riduce la risoluzione del viewport sullo schermo High-DPI/Retina per migliorare le prestazioni.

Questo comportamento può essere modificato nelle [impostazioni principali](https://helpx.adobe.com/it/substance-3d/unlisted/documentation/spdoc/general-71008262.html) modificando il parametro **Ridimensionamento finestra vista**.

## Filtro Texture

Le finestre delle viste utilizzano mipmap e filtri delle texture per consentire lo streaming in entrata e in uscita di [Texture virtuali sparse](../../../features/sparse-virtual-textures.md) al fine di migliorare le prestazioni. In alcuni casi questo può portare a texture sfocate.

Il filtro texture può essere regolato tramite la finestra Impostazioni schermo sotto i parametri [Impostazioni finestra vista](../../../interface/display-settings/viewport-settings.md).
