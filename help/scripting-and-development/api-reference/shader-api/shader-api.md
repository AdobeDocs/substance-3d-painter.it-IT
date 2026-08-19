---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api.html"
breadcrumb-title: ''
description: Accedete alla pagina di riferimento relativa alle API shader di Substance 3D Painter per creare shader personalizzati ed estendere le funzionalità di rendering.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: API Shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '702'
ht-degree: 0%

---


# API Shader

![](../../../assets/header-shader.jpg)

Substance Painter utilizza gli ombreggiatori per eseguire il rendering dei materiali nella relativa finestra di visualizzazione in tempo reale. È possibile scrivere ombreggiatori personalizzati per implementare nuovi comportamenti o semplicemente far corrispondere la finestra della vista ad altri moduli di rendering.

È possibile trovare altri shader per Substance Painter in [Substance share](https://share.allegorithmic.com/libraries?by_category_type_id=6).

>[!NOTE]
>
> L&#39;API shader è disponibile anche direttamente dall&#39;applicazione, accedendo al menu **Guida > Documentazione > API shader**.

## Riferimento shader

## Changelog

* [File di log delle modifiche completo](changelog-shader-api.md)

## Riscaldamento

In Substance Painter, puoi scrivere i tuoi shader in *GLSL*. È possibile scrivere solo una *parte* dello shader di frammento, che a volte viene definito *shader di superficie*. Senza ulteriori indugi, introduciamo lo shader di Substance Painter &quot;Hello world&quot;:

```
void shade(V2F inputs) { 

  diffuseShadingOutput(vec3(1.0, 0.0, 1.0)); 

}
```


Ora, se salvi questo frammento in un file *.glsl* e lo carichi in Substance Painter rilasciandolo nella scheda shader dello scaffale, ora puoi usarlo e vedere un bel colore rosa uniforme sulla trama.

## Shader di superficie

* [surface-shader.glsl](shaders-shader-api/surface-shader-shader-api.md)

## Dati forniti dal motore (o come si accede ai canali?)

In Substance Painter, potete accedere ai parametri del motore di rendering (canali del documento, texture aggiuntive, dati relativi alla fotocamera e così via). Ecco un elenco completo di tutti i parametri forniti dal motore:

* [all-engine-params.glsl](parameters-shader-api/all-engine-params-shader-api.md)

## Impostazioni del motore (o come si specificano gli stati di rendering?)

In alcuni casi può essere utile usare una specifica configurazione di rendering (taglio, fusione, località di campionamento e simili) per un effetto. Alcuni stati di rendering sono esposti e possono essere impostati nello shader. Di seguito è riportato un elenco completo di tutti gli stati di rendering esposti:

* [all-rendering-states-params.glsl](parameters-shader-api/all-rendering-states-params-shader-api.md)

## Modifiche personalizzate (o come posso modificare lo shader?)

Di solito si hanno modifiche personalizzate in uno shader. A tale scopo, nelle ombreggiature di Substance Painter, è stato introdotto un modo per specificare modifiche personalizzate. Di seguito è riportato un elenco completo di tutti i tipi di modifica dello shader personalizzati:

* [all-custom-params.glsl](parameters-shader-api/all-custom-params-shader-api.md)

## Librerie incorporate

Per evitare di scrivere molto codice standard in tutti i vostri shader, abbiamo creato una piccola ma pratica libreria di funzioni utili. **Al momento non è possibile modificarla né crearne una personalizzata.**

* [lib-alpha.glsl](libraries-shader-api/lib-alpha-shader-api.md): contiene helper correlati all&#39;opacità
* [lib-bayer.glsl](libraries-shader-api/lib-bayer-shader-api.md): contiene gli helper matrice bayer
* [lib-define.glsl](libraries-shader-api/lib-defines-shader-api.md): contiene utili costanti matematiche
* [lib-emissive.glsl](libraries-shader-api/lib-emissive-shader-api.md): contiene gli helper delle proprietà di emissione
* [lib-env.glsl](libraries-shader-api/lib-env-shader-api.md): contiene gli helper correlati alla mappa dell&#39;ambiente
* [lib-normal.glsl](libraries-shader-api/lib-normal-shader-api.md): contiene gli helper relativi alla mappa normale (e la mappa normale generata dal height)
* [lib-pbr.glsl](libraries-shader-api/lib-pbr-shader-api.md): contiene helper di rendering basati fisicamente
* [lib-pbr-aniso.glsl](libraries-shader-api/lib-pbr-aniso-shader-api.md): contiene helper di rendering anisotropi basati fisicamente
* [lib-pom.glsl](libraries-shader-api/lib-pom-shader-api.md): contiene helper mapping occlusioni parallax
* [lib-random.glsl](libraries-shader-api/lib-random-shader-api.md): contiene utilità casuali (sequenze a bassa discrepanza)
* [lib-sampler.glsl](libraries-shader-api/lib-sampler-shader-api.md): contiene gli helper di channel getters
* [lib-sparse.glsl](libraries-shader-api/lib-sparse-shader-api.md): contiene helper di campionamento delle texture sparse sicure
* [lib-sss.glsl](libraries-shader-api/lib-sss-shader-api.md): contiene helper di dispersione sottosuperficie
* [lib-utils.glsl](libraries-shader-api/lib-utils-shader-api.md): contiene funzioni dell&#39;utilità colore (conversioni sRGB, mappatura toni)
* [lib-vectors.glsl](libraries-shader-api/lib-vectors-shader-api.md): contiene helper vettoriali comuni

## Metadati

Potete dichiarare ulteriori informazioni non obbligatorie per dare un suggerimento al sistema di rendering. Di seguito è riportata la sintassi:

```
//: metadata { 

//:   "key1":"value1", 

//:   "key2":"value2" 

//: }
```


I tasti supportati sono:

* **custom-ui**: sostituire l&#39;interfaccia utente standard dei parametri dello shader con una vista personalizzata scritta come modulo QML (vedere la documentazione sullo scripting). Il percorso può essere assoluto o relativo a una cartella *custom-ui* dello scaffale.
* **mdl**: definire il materiale mdl di Iray da utilizzare con lo shader. La sintassi del percorso è la seguente: *mdl::folder1::folder2::mdl\_filename::material\_name* dove *cartella1::folder2::mdl\_filename* è il percorso all&#39;interno di una cartella dello scaffale *mdl* in un file mdl e *::material\_name* è il nome di un materiale dichiarato all&#39;interno di questo file mdl. (ad esempio: &quot;mdl&quot; : &quot;mdl::alg::materials::fisicamente\_metallico\_rugosità::fisicamente\_metallico\_rugosità&quot;)

## Ombreggiature di esempio (sì, finalmente!)

Per avere un&#39;idea di quello che sembra un vero shader, ecco alcuni shader campione, ordinati in base alla complessità crescente:

* [pixelated.glsl](shaders-shader-api/pixelated-shader-api.md) : shader con effetto pixel
* [toon.glsl](shaders-shader-api/toon-shader-api.md): shader toon
* [pbr-metal-rough.glsl](shaders-shader-api/pbr-metal-rough-shader-api.md): shader PBR predefinito incorporato nella Substance Painter

## Stratificazione dinamica dei materiali

La Stratificazione dinamica dei materiali è un flusso di lavoro specifico in cui i materiali vengono combinati all’interno di uno shader e consente all’utente di modificare dinamicamente le maschere di fusione in Substance Painter. Per attivare questo flusso di lavoro, sono disponibili due nuove funzionalità:

* dichiarare stack modificabili da una definizione di shader: [livelli\_dichiarano\_stacks.glsl](parameters-shader-api/layering-declare-stacks-shader-api.md)
* associa i materiali come parametri dello shader: [livelli\_bind\_materials.glsl](parameters-shader-api/layering-bind-materials-shader-api.md)
