---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/subsurface-scattering/enabling-subsurface-in-a-project.html"
breadcrumb-title: ''
description: Scoprite come attivare la dispersione sottosuperficiale nei progetti Substance 3D Painter per creare realistici effetti di materiale traslucido.
helpx_creative_field: ""
helpx_description: Painter > Features > Subsurface Scattering > Enabling Subsurface in a Project
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Abilitazione della sottosuperficie in un progetto
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '267'
ht-degree: 0%

---


# Abilitazione della sottosuperficie in un progetto

Per attivare correttamente la dispersione di sottosuperficie in Substance 3D Painter, è necessario impostare prima alcuni parametri.\
In questa pagina viene fornita una guida sui parametri da attivare.

## 1 - Impostazioni set texture

Nel [set di texture](../../interface/texture-set/texture-set.md) aggiungi un canale **diffusione** se non è già presente:

![](../../assets/add-channel.png)

>[!NOTE]
>
> Il canale di dispersione funziona come una **maschera** sopra la **superficie surreale**: se il canale è nero non vi è alcuna superficie subsuperficiale, mentre se è bianco l&#39;intensità della superficie subsuperficiale sarà massima. Questo canale è un valore in scala di grigi che per impostazione predefinita è **nero**. Aggiungete un livello di riempimento nella Pila livelli per controllare il colore predefinito o utilizzate un livello di pittura per controllare manualmente l’intensità.

## 2 - Impostazione globale sottosuperficie

Abilita l&#39;impostazione di dispersione Subsurface principale nelle [Impostazioni schermo](../../interface/display-settings/display-settings.md) (sotto le impostazioni Post-Effects):

![](../../assets/enable-subsurface.png)

>[!NOTE]
>
> L’attivazione/disattivazione dell’effetto Sottosuperficie influisce sull’intero progetto. Può essere utile utilizzare questo parametro globale se è troppo pesante in termini di prestazioni.

## 3 - Impostazioni Shader

![](../../assets/shader-parameters.png)

Nella finestra [Impostazioni Shader](../../interface/shader-settings/shader-settings.md) con shader predefiniti è possibile trovare un gruppo &quot; **Parametri SSS**&quot; con due impostazioni.\
Modificate la scala e il colore per adattarli al materiale di destinazione. Per ulteriori informazioni su queste impostazioni, vedere: [Parametri sottosuperficie](subsurface-parameters.md)

## Bonus: attivazione delle ombre

L’effetto di dispersione Sottosuperficie funziona bene ma può sembrare strano se è solo.\
L&#39;attivazione delle ombre può aiutare l&#39;aspetto finale nella finestra della vista e migliorare il realismo del materiale finale.

Nella finestra [Impostazioni ambiente](../../interface/display-settings/environment-settings.md), attiva l&#39;impostazione &quot; **Ombre**&quot;:

![](../../assets/shadow-2.png)
