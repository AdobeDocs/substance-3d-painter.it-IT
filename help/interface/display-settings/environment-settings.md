---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/display-settings/environment-settings.html"
breadcrumb-title: ''
description: Scopri come configurare le impostazioni dell’ambiente in Substance 3D Painter per controllare l’illuminazione e lo sfondo per l’anteprima del materiale.
helpx_creative_field: ""
helpx_description: Painter > Interface > Display settings > Environment settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni ambiente
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 1%

---


# Impostazioni ambiente

Questa sezione delle **Impostazioni schermo** controlla l&#39;illuminazione nella finestra della vista.

## Ambiente

![](../../assets/env-settings.png)

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Mappa ambiente** | Texture mappa ambiente da utilizzare per illuminare la scena. È possibile trovare nella finestra [Risorse](../assets/assets.md) utilizzando il predefinito &quot;Ambiente&quot;.Fare clic sul pulsante per aprire un ripiano e scegliere una mappa dell&#39;ambiente diversa. |
| **Sovrascrivi spazio colore mappa ambiente** | Se il progetto corrente utilizza la [gestione colore](../../features/color-management/color-management.md), questa impostazione può essere abilitata per ignorare lo spazio colore della mappa dell&#39;ambiente. |
| **Opacità ambiente** | Controlla la visibilità/opacità delle texture di ambiente sullo sfondo della finestra della vista. Queste impostazioni non hanno alcun impatto sull’illuminazione della scena. |
| **Esposizione dell&#39;ambiente** | Il valore di esposizione (EV) è un numero che rappresenta una luminanza fissa della scena. Questa impostazione consente di scostare il valore di luminanza predefinito.Questa impostazione deve rimanere su 0 quando si utilizzano le mappe di ambiente fornite con l&#39;applicazione. La creazione di una texture di una risorsa con un valore di esposizione errato potrebbe causare problemi di calibrazione del colore in altre applicazioni. |
| **Rotazione ambiente** | Controlla la rotazione orizzontale della texture ambiente. Utile per ruotare la luce nella scena e cambiare il modo in cui reagisce l’oggetto. Può essere controllato con una [scelta rapida da tastiera](../settings/shortcuts.md). |
| **Sfocatura ambiente** | Controlla la nitidezza o la sfocatura della texture ambiente sullo sfondo della finestra della vista. Queste impostazioni non hanno alcun impatto sull’illuminazione. |
| **Allineamento ambiente** | Controlla il modo in cui la texture dell’ambiente ruota attorno alla modalità 3D all’interno della finestra della vista. Questa impostazione può essere utilizzata per illuminare le aree sotto il modello 3D quando è impostata su locale.Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Mondo</strong> (impostazione predefinita): l’ambiente è allineato alla scena e ruota attorno all’asse superiore del modello 3D.</li><li data-preserve-html="true"><strong>Locale</strong>: l&#39;ambiente è allineato alla fotocamera e ruota attorno all&#39;asse superiore della fotocamera.</li></ul> |

## Ombre

![](../../assets/shadow-2.png)

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Ombre** | Attiva o disattiva il rendering delle ombre nella finestra della vista. |
| **Modalità di calcolo** | Controlla la velocità di calcolo delle ombre.<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Intensivo </strong>: il calcolo è veloce ma il rendering della finestra della vista può essere bloccato.</li><li data-preserve-html="true"><strong> Media </strong>: media delle modalità Intensivo e Leggero.</li><li data-preserve-html="true"><strong> Leggero </strong>: (impostazione predefinita) Il calcolo delle ombre risulta lento in pochi secondi, ma non rallenta le prestazioni della finestra.</li></ul> |
| **Opacità ombre** | Controlla quante ombre saranno visibili nella scena. |
