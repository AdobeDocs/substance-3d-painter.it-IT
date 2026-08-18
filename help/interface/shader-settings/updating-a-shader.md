---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/interface/shader-settings/updating-a-shader.html"
breadcrumb-title: ''
description: Scopri come aggiornare gli shader personalizzati in Substance 3D Painter per applicare le modifiche dello shader e ricaricare i file shader.
helpx_creative_field: ""
helpx_description: Painter > Interface > Shader settings > Updating a shader
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Aggiornamento di uno shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '314'
ht-degree: 0%

---


# Aggiornamento di uno shader

A volte può essere necessario aggiornare lo shader utilizzato da un progetto per risolvere problemi o sfruttare le funzioni più recenti. In questa pagina viene descritto come eseguire questa operazione.

Di seguito sono riportati due passaggi per metodo su come aggiornare lo shader di un progetto:

* **Aggiornare uno shader tramite la finestra shader**
* **Aggiornare uno shader tramite il plug-in Resource Updater**

Se un progetto utilizza uno **shader personalizzato** (non fornito per impostazione predefinita con Substance 3D Painter), consulta la pagina [Shader personalizzato](https://substance3d.adobe.com/display/DRAFTPAINTER/Shader+API) per ottenere una guida su come aggiornarlo.

## Aggiornare uno shader mediante la finestra shader

### 1 - Aprire la finestra Impostazioni shader

La finestra **Impostazioni shader** è disponibile per impostazione predefinita a destra nella barra degli strumenti Dock.

![](../../assets/shader-settings-window.png)

### 2 - Fate clic sul pulsante shader e selezionate lo shader aggiornato

Fate clic sul pulsante shader (sotto il pulsante Annulla/Ripeti) e individuate lo shader corrispondente a quello già utilizzato.

![](../../assets/shader-mini-shelf.png)

### 3 - Lo shader viene aggiornato

Una volta caricato il nuovo shader, la menzione **obsoleta** deve essere rimossa e il modello 3D deve apparire normalmente nella finestra della vista.

![](../../assets/updated-shader.png)

## Aggiornare uno shader tramite il plug-in Resource Updater

### 1 - Aprire Resource Updater

Spostarsi a sinistra dell&#39;interfaccia per trovare la barra degli strumenti **Plug-in** e fare clic sull&#39;icona **Resource Updater**.

![](../../assets/resource-icon.png)

### 2 - Passare alla scheda Shader

Nella nuova finestra visualizzata, fai clic sulla scheda &quot;Shader&quot; per visualizzare lo shader presente nel progetto corrente.

![](../../assets/shader-tab.png)

### 3 - Trovare lo shader e aggiornarlo

Nella scheda Shader dovrebbe essere visualizzato un elenco di tutte le risorse Shader utilizzate dall&#39;utente dal progetto corrente. **Shader obsoleto** visibile con **sfondo rosso**. Fare clic sul pulsante &quot;Aggiorna&quot; accanto a una risorsa per aggiornarla.

![](../../assets/update-shader-click.gif)
