---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/release-notes/old-versions/version-2017-2.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Painter versione 2017.2 per scoprire le nuove funzioni, i miglioramenti e le correzioni di bug.
helpx_creative_field: ""
helpx_description: Painter > Release notes > Old versions > Version 2017.2
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 2017.2
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '426'
ht-degree: 0%

---


# Versione 2017.2

**La versione di Substance Painter 2017.2** introduce una nuova e potente funzionalità tramite il sistema di punti di ancoraggio. Permette di realizzare configurazioni più avanzate nella Pila livelli, aprendo nuove opportunità.

Data di pubblicazione: *27 luglio 2017*

## Caratteristiche principali

### Nuovo effetto Punto di ancoraggio

![](../../assets/anchor-height-blend-optim.gif)

**Un nuovo tipo di effetto** è stato aggiunto a Substance Painter, accanto a quelli già esistenti, ad esempio **Filtro** e **Livello**, è ora possibile trovare il nuovo **Punto di ancoraggio**. Questo nuovo effetto consente di definire una **posizione** nella **Pila livelli** a cui è possibile fare riferimento **in tutti gli altri livelli del progetto.** Ciò consente, ad esempio, di utilizzare le informazioni del height da un livello nella maschera di un livello appena sopra questo, consentendo una fusione più naturale (come illustrato dal gif sopra).

Poiché l&#39;ancoraggio funziona come un effetto, può essere creato in **molte situazioni** : **contenuto** di un livello, **maschera** e anche come filtro **pass-through**. L’effetto funziona anche se il livello in cui si trova è disattivato. Tenete presente che l&#39;Ancoraggio definisce solo una posizione, non ciò che potete recuperare da essa. Queste informazioni vengono definite nel punto in cui viene creato il riferimento all&#39;ancoraggio.

Per ulteriori dettagli tecnici ed esempi, consultate la pagina dedicata: [Punto di ancoraggio](../../features/effects/anchor-point.md)

### Nuovi miglioramenti

Oltre al nuovo effetto Punto di ancoraggio, abbiamo lavorato anche su:

* Possibilità di rinominare alcuni effetti, ad esempio Riempimento e Pittura
* Nuove funzioni di scripting, che consentono di creare un collegamento dinamico con altre applicazioni come Unity

## Esercitazione

Le nuove funzioni sono descritte dettagliatamente nei nostri video più recenti:

## Note sulla versione

### 2017.2

(Pubblicato il 27 luglio 2017)

**Aggiunto:**

* [Effetto] Nuovo punto di ancoraggio che consente riferimenti a livelli e maschere
* [Livelli] Possibilità di rinominare gli effetti di riempimento e disegno
* [Plugin] Plug-in Substance Source aggiornato
* [Scripting] Consente di eseguire query sulla risoluzione del set di texture
* [Scripting] Consenti di ottenere lo stato del motore di pittura
* [Prestazioni] Ottimizzazione migliorata del caricamento del progetto e della timbratura del pennello

**Risolto:**

* [Tool] Problemi di prestazioni durante la modifica dei parametri del materiale
* [Motore] Scomparsa dei tratti di pennello durante la modifica della risoluzione (4K>2K)
* [Vista 3D] Lo spazio tangente non è sincronizzato con i forni
* [Shelf] Il percorso dello scaffale nei documenti utente non viene creato automaticamente
* [Shelf] Rendete i predefiniti compatibili con le versioni precedenti dopo un aggiornamento
* [Shader] Lo shader non PBR non funziona più
* [Bakers] La mappatura degli ID non riesce con l&#39;opzione Corrispondenza per nome abilitata
* [Sample] I nomi dei set di texture del progetto di esempio Meet Mat non sono corretti
* Il salvataggio di un progetto prima della creazione di un modello restituisce errori di autorizzazione di scrittura
