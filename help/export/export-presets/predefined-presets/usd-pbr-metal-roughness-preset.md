---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/getting-started/export/export-presets/predefined-presets/usd-pbr-metal-roughness-preset.html"
breadcrumb-title: ''
description: Scoprite come utilizzare il predefinito di esportazione USDz (Apple AR) in Substance 3D Painter per esportare le texture per i flussi di lavoro Apple AR.
helpx_creative_field: ""
helpx_description: Painter > Getting Started > Export > Export presets > Predefined Presets > USDz (Apple AR) Preset
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: USDz (Apple AR)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 0%

---


# Modello predefinito USDz (Apple AR)

>[!NOTE]
>
> Per esportare in USD con un Modello di output personalizzato, non utilizzare il modello USDz (Apple AR). Utilizza invece il Modello di output scelto e abilita <b>Esporta risorsa USD</b> nella parte inferiore della <b>scheda Impostazioni</b>.

Il modello di output predefinito USDz (Apple AR) esporta la risorsa configurata per l’uso con le applicazioni Apple AR.

Per utilizzare il modello USDz (Apple AR):

1. Aprite la finestra Esporta con <b>File > Esporta texture</b> o con la scelta rapida da tastiera <b>Ctrl + Maiusc + E</b>.
1. Nella <b>scheda Impostazioni</b>, apri il <b>menu a discesa dei Modelli di output</b> e seleziona <b>USDz (Apple AR)</b>.

![Immagine della finestra di esportazione che mostra il menu a discesa modello di output aperto e USDz (Apple AR) selezionato.](../../../assets/export-usd.png){zoomable="yes"}

Vengono creati e salvati cinque file di texture (colore di base, metallizzato, normale, occlusione e rugosità). Tutti i file vengono salvati come JPG, ad eccezione della mappa normale che viene salvata come PNG per evitare artefatti dovuti alla compressione con perdita di dati.

Inoltre, vengono creati altri due file con estensione usdc e usdz:

Ecco un esempio di JadeToad aperto direttamente in MacOS dal Finder:

![](../../../assets/usdz.png){width="400px"}

Di seguito è riportato un esempio del file USDZ inviato a un iPhone, utilizzando la modalità AR per inserire il modello JadeToad in un ambiente reale:

![](../../../assets/3d-usdz.jpg){width="500px"}
