---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/getting-started/export.html"
breadcrumb-title: ''
description: Scopri come esportare texture da Substance 3D Painter in vari formati per utilizzarla in altre applicazioni e motori di gioco.
helpx_creative_field: ""
helpx_description: Painter > Getting Started > Export
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Esporta
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 1%

---


# Esporta

## Esportare texture

La texture viene esportata come una raccolta di bitmap. Painter offre molta flessibilità nell’esportazione di texture grazie ai Modelli di output. I modelli di output consentono di controllare aspetti quali la denominazione dei file esportati, il modo in cui le texture vengono compresse nei canali e il formato e la profondità di bit dei file esportati. Se il problema persiste, Painter include decine di Modelli di output predefiniti configurati per le applicazioni e i casi d&#39;uso 3D più comuni.

Aprite la <b>finestra Esportazione</b> e iniziate a esportare texture con <b>File > Esporta Texture</b> oppure usate la scelta rapida da tastiera da tastiera <b>CTRL + MAIUSC + E</b>. Utilizzate i seguenti collegamenti per ulteriori informazioni sull’esportazione di texture:

* [Finestra Esporta](../export/export-window/export-window.md)
* [Modelli di output](../export/export-presets/export-presets.md)
* [Modifica o creazione di Modelli di output](creating-export-presets.md)

### Esportare la trama

Painter può modificare la trama importata, ad esempio, generando automaticamente UV. Se hai apportato modifiche alla trama in Painter, puoi esportarla con <b>File > Esporta trama</b>.

Durante l’esportazione di una trama sono disponibili alcune opzioni:

* <b>Senza spostamento/tassellatura</b>: esporta la trama di base senza modificare la geometria in base ai materiali.
  * <b>Applica triangolazione</b>: se la trama importata è costituita da quadrupli o poligoni, puoi abilitare questa opzione per esportare la versione triangolata Painter della trama. In questo modo è possibile evitare bug basati sulla triangolazione visiva nel caso in cui altre applicazioni eseguano la triangolazione in modo diverso.
* <b>Con spostamento/tassellatura</b>: Painter tassella la trama, aggiungendovi altri poligoni, e utilizza spostamento o height per modificare la geometria di superficie della trama.
  * <b>Calcolare nuovamente le normali dei vertici</b>: la modifica della superficie della trama può causare una normalità errata dei vertici preesistenti. Abilitando questa opzione, Painter aggiorna automaticamente le normali dei vertici al valore corretto per la nuova superficie.

![](../assets/export-render.jpg){width="500px"}
