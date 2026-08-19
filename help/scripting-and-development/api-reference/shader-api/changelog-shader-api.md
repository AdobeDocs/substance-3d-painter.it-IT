---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/scripting-and-development/api-reference/shader-api/changelog-shader-api.html"
breadcrumb-title: ''
description: Esaminate il registro delle modifiche di Substance 3D Painter API shader per tenere traccia di aggiornamenti, nuove funzioni e modifiche nel tempo.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > API Reference > Shader API > Changelog - Shader API
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Changelog - API shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '837'
ht-degree: 3%

---


# Changelog - API shader

## Changelog

## 2018.3.2

* [lib-sparse.glsl](libraries-shader-api/lib-sparse-shader-api.md): le funzioni di campionamento utilizzano derivati di texture anziché un semplice livello mipmap. È un requisito fondamentale per il supporto del campionamento delle anisotropie. Funzioni di campionamento: le firme non vengono modificate.
* [lib-pom.glsl](libraries-shader-api/lib-pom-shader-api.md): la firma della funzione *getParallaxOffset* è stata modificata per utilizzare derivati delle texture

## 2018.3.0

* Aggiungi una nuova libreria [lib-pbr-aniso.glsl](libraries-shader-api/lib-pbr-aniso-shader-api.md) per visualizzare l&#39;evidenziazione degli specular anisotropi
* Aggiungi una nuova libreria [lib-sparse.glsl](libraries-shader-api/lib-sparse-shader-api.md) per facilitare il campionamento dei canali gestendo la disponibilità delle mipmap
* Aggiorna le interfacce delle librerie di shader per gestire questo campionamento sicuro
* **Dichiarazione di obsolescenza**: le funzioni precedenti basate sulle coordinate della texture vec2 e sul campionatore texture sono state dichiarate obsolete (utilizzare nuove firme)
* [lib-pom.glsl](libraries-shader-api/lib-pom-shader-api.md): aggiungi una funzione *applyParallaxOffset* per semplificare l&#39;uso dell&#39;effetto di occlusione parallax
* [lib-random.glsl](libraries-shader-api/lib-random-shader-api.md): aggiungete un generatore di valori casuali Blue Noise e alternative temporali
* [lib-sampler.glsl](libraries-shader-api/lib-sampler-shader-api.md): suddividere tutti gli helper di campionamento dei canali per avere sia gli helper di interpretazione dei valori che quelli di campionamento

## 2018.2.0

* **Modifica API shader di superficie**: la firma della funzione *ombra* è stata modificata. Vedere [surface-shader.glsl](shaders-shader-api/surface-shader-shader-api.md)
* La funzione *shadeShadow* non è più utilizzata e può essere rimossa in modo sicuro dagli shader di superficie personalizzati
* Aggiungere il supporto per la dispersione dei sottosuoli, vedere [surface-shader.glsl](shaders-shader-api/surface-shader-shader-api.md) e [lib-sss.glsl](libraries-shader-api/lib-sss-shader-api.md) per i dettagli
* [lib-pbr.glsl](libraries-shader-api/lib-pbr-shader-api.md): la funzione *pbrComputeBRDF* è stata rimossa. Consulta l&#39;esempio di [pbr-metal-rough.glsl](shaders-shader-api/pbr-metal-rough-shader-api.md) per sapere come utilizzare la libreria ora
* Sono stati aggiunti nuovi parametri del motore: *texture\_blue\_noise*, *aspetto\_rapporto*, *camera\_vp\_matrix\_inverse*, *ambiente\_esposizione*, *ambiente\_rotazione*, *fovy*, *principale\_luce* e *schermo\_dimensione*. Per ulteriori dettagli, vedere [all-engine-params.glsl](parameters-shader-api/all-engine-params-shader-api.md)
* Aggiungi i metadati *description* per fornire suggerimenti per i parametri dello shader personalizzati

## 2017.4.2

* Correggere gli shader mancanti negli esempi di documentazione (pixelati e toon shader)
* Correggere il dithering per un&#39;alta risoluzione
  * [lib-bayer.glsl](libraries-shader-api/lib-bayer-shader-api.md): **bayerMatrix8()** restituiscono valori validi per le coordinate > 4k

## 2017.4.1

* Correggere lo shader rivestito di pbr
  * [lib-vectors.glsl](libraries-shader-api/lib-vectors-shader-api.md): gli output **tangentSpaceToWorldSpace()** e **worldSpaceToTangentSpace()** sono ora normalizzati

## 2017.4.0

* Riflesso specular errato nella vista 2D per alcune trame

## 2017.3.1

* Dithering più economico

## 2017.2.0

* Rimuovere la normalizzazione della tabulazione interpolata per adeguarla al comportamento di Substance Designer e forni
* [Viewport] Sostituire il tavolo Hammersley con una spirale di Fibonacci

## 2.6.0

* Correggere i metodi di fusione e di taglio degli ombreggiatori
* Rielaborare il dithering. Se il rendering è lineare, lo applichiamo dopo il profilo colore.

## 2.5.0

* Aggiunta del supporto per i profili colore (LUT) nelle finestre delle viste (conversione sRGB opzionale)
* Aggiungere il dithering all’opacità negli shader
* Aggiungere la mappatura delle occlusioni parallasse agli shader PBR
* Aggiungere un modo per nascondere i parametri personalizzati dall’interfaccia utente dello shader predefinita
* Aggiungere un collegamento all’elenco dei tag di canale nella documentazione dello shader dei livelli
* Sostituire il tag &#39;channel\_ao&#39; con &#39;channel\_ambientocclusion&#39;
* [Riquadro di visualizzazione] Alcune mappe normali presentano valori bloccati che appaiono come artefatti
* Correggere i canali disponibili nel documento shader
* Consenti di definire un&#39;interfaccia utente shader personalizzata
* Aggiungere un’interfaccia utente shader personalizzata standard per gli shader di livelli di materiale
* La ricerca nei file personalizzati dell’interfaccia utente avviene ora in relazione a una cartella shader/custom-ui negli scaffali (come nel mdl)
* Usare il canale di specular level negli shader predefiniti
* Correggi esempio parametri shader vec3
* Aggiornare Painter al profilo principale OpenGL

## 2.4.0

* Correggere la differenza sulla mappa normale combinata esportata e visualizzata nella finestra della vista

## 2.2.0

* Aggiungere il supporto per le texture senza binding nel materiale generico per le texture non di documento
* Aggiornamento della documentazione dei cursori dello shader personalizzati
* Consenti di definire la precisione dei passi per i cursori
* Documentazione per stratificazione dinamica dei materiali

## 2.1.1

* Aggiungere una funzione &#39;RGB2Gray&#39; in lib-utils

## 2.1.0

* Consenti di definire gruppi per parametri shader e materiali/maschere
* Aggiungere i canali mancanti nella documentazione (&#39;ao&#39;, &#39;diffuso&#39;, &#39;specularlevel&#39;)

## 2.0.4

* Funzione di decompressione normale non corretta con valori alfa bassi
* Consenti di leggere i colori dei vertici della trama nello shader personalizzato
* [Viewport] Mapping di ambiente esteso in alcuni computer

## 2.0.0

* Consenti di sovrascrivere le mappe aggiuntive Normale/AO in base al canale dedicato
* Modificare la funzione Height2Normal per utilizzare il metodo Sobel
* Aggiungi la possibilità di definire un mdl per shader
* Aggiungi una nuova cartella mdl nello scaffale
* Aggiungere i predefiniti dei canali di diffusione e specular level
* Aggiornamento della documentazione per la mappatura dei toni
* Correggere i riflessi in modalità ortogonale
* È stato risolto il problema relativo al glitch bianco verticale che veniva visualizzato in una posizione specifica sull’envmap.
* Consenti di definire &#39;default\_color&#39; per i parametri di texture

## 1.7.0

* Consenti di campionare trame esterne (dallo scaffale)

## 1.6.0

* Funzione di esposizione gamma/tonalità per consentire la sovrascrittura
* Esporre più parole di testo

## 1.5.0

* Aggiungi numero di riga e nome file nel report degli errori dello shader

## 1.4.1

* Tutte le conversioni sRGB seguono lo standard sRGB, ad eccezione di quelle eseguite negli shader che hanno una stretta approssimazione
* Il canale di height nella mappa Normale viene convertito nello spazio colore errato

## 1.4.0

* Aggiungi canale di occlusione ambiente
* Aggiungi nuovo flusso di lavoro per edizione normale
* Aggiungere la sintassi dell’espressione &quot;o&quot; per i parametri automatici relativi alle texture
* Correzione dello shader pbr per la gpu Intel su OSX

## 1.3.4

* Consenti interpolazione binormali nello shader di frammento
* Correggi spazio tangente Mikkt

## 1.3.3

* Correggere le armoniche sferiche producendo un’intensità di luce negativa
* Il calcolo dell’esposizione è diverso da Substance Designer (e fissa il cursore dell’esposizione)
* Le ombre non devono essere visibili su una superficie metallica al 100%

## 1.3.0

* Aggiungi funzione ombra
* Aggiungi il supporto per l&#39;opacità (&#39;alpha\_test&#39; e &#39;alpha\_blend&#39;)

## 1.2.0

* Possibilità di impostare gli stati OpenGL richiesti in shader personalizzati
* Correggere le bitangenti invertite
* Aggiunta del supporto per il canale normale

## 1.0

* Aggiunta del supporto per shader personalizzati
