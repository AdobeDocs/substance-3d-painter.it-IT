---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/release-notes/old-versions/version-2-2.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Painter versione 2.2 per informazioni sulle nuove funzioni, i miglioramenti e le correzioni di bug.
helpx_creative_field: ""
helpx_description: Painter > Release notes > Old versions > Version 2.2
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 2.2
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '587'
ht-degree: 0%

---


# Versione 2.2

**Substance Painter 2.2** aggiunge un nuovo flusso di lavoro, ovvero la Stratificazione dinamica dei materiali.

Data di pubblicazione: *21 luglio 2016*

## Caratteristiche principali

### Nuovo flusso di lavoro Stratificazione dinamica dei materiali

![](../../assets/dynamic-material-blending-materials-preview.jpg)

Con questa nuova versione viene aggiunto un nuovo **flusso di lavoro** denominato **Livellamento dei materiali**. I flussi di lavoro tradizionali per la creazione di texture si basano sulla creazione di texture ad **alta risoluzione** per **mantenere i dettagli**, ma questo risulta **scomodo** per le esigenze specifiche. Un approccio più interessante consiste invece nel **creare materiale di lavorazione di piccole dimensioni** e **ripeterli all&#39;interno di uno shader**. Consente di mantenere una certa qualità e la possibilità di **ingrandire molto vicino** all&#39;oggetto utilizzando questo shader **senza perdere dettagli**. L&#39;unico problema è che per visualizzare in anteprima il risultato finale era in precedenza obbligatorio andare al motore di gioco/renderer che visualizza lo shader finale. Ciò non è più vero poiché in questa nuova versione è ora possibile utilizzare uno shader simile all&#39;interno di Substance Painter, che consente di **visualizzare il risultato finale e dipingere allo stesso tempo**.

È stato aggiunto un **nuovo progetto di esempio** denominato &quot;**FireHydrant**&quot; per presentare il nuovo flusso di lavoro.

![](../../assets/layer-stacks.png)

Questo nuovo flusso di lavoro consente due metodi di lavoro:

* I materiali sono definiti nello shader, puoi solo colorare le maschere per fonderle
* Materiali e maschere possono essere dipinti insieme

In ogni caso, è possibile definire una nuova pila di livelli ogni volta che offre maggiore libertà durante la creazione delle maschere e dei materiali. La gestione dei livelli è molto più semplice in questo modo e ogni pila può avere un proprio insieme di canali specifici che possono essere fusi nello shader finale.\
Abbiamo anche uno shader speciale per Unity 5 e Unreal Engine 4 disponibile su Share :

* [Unità 5](https://share.allegorithmic.com/libraries/2126)
* [Unreal Engine 4](https://share.allegorithmic.com/libraries/2125)

Per ulteriori informazioni, consulta la pagina dedicata della documentazione: [Stratificazione dinamica dei materiali](../../features/dynamic-material-layering.md)

### Nuovo campo di ricerca per scaffali

![](../../assets/mini-shelf-search.gif)

Abbiamo migliorato il **mini scaffale** che appare in varie posizioni dell&#39;applicazione con un campo di ricerca dedicato. Questo miglioramento rende la ricerca delle risorse molto più intuitiva e piacevole da usare. La ricerca personalizzata viene mantenuta durante la sessione corrente dell&#39;applicazione. Se, ad esempio, si utilizzano molti rumori di grunge, l&#39;utilizzo di questa parola chiave determinerà

## Esercitazione

L&#39;ultima esercitazione video illustra le nuove funzioni:

## Note sulla versione

### 2.2.0

(Pubblicato il 21 luglio 2016)

**Aggiunto:**

* [Shelf] Miglioramento del sistema di ricerca e delle query
* [Shelf] Aggiungi campo di ricerca per i mini-scaffali
* [Shader] Consente di definire la precisione dei passi per i cursori
* [Shader] Aggiungere un pulsante Annulla/Ripeti per i parametri dello shader
* [Shader] Il ricaricamento di uno shader non deve reimpostarne i parametri
* [MatLayering] Aggiungi il supporto per Stratificazioni dinamiche del materiale e sottopile
* [MatLayering] Consenti di importare un file json per configurare le impostazioni dello shader
* [MatLayering] Limite sblocca i campionatori texture (passa a texture senza binding)
* [Scripting] Consenti di impostare le impostazioni dei panettieri e avviare il loro calcolo
* [Substance] Utilizzare &quot;utilizzo&quot; per connessioni di input/output oltre agli identificatori
* [Tool] Consente di selezionare il canale di anteprima nella finestra della vista per lo strumento di proiezione

**Risolto:**

* Arresto anomalo all&#39;avvio se le sostanze si trovano in una cartella errata
* Il rapporto sugli arresti anomali a volte non funziona a causa di un file di registro errato
* [Iray] Gli effetti post non si aggiornano quando Iray è in pausa
* [Iray] La scelta rapida per l&#39;attivazione automatica non funziona più
* [Iray] Il comportamento del cursore Apertura varia a seconda delle dimensioni della risorsa
* [Livelli] Il primo canale di materiale non è attivato per impostazione predefinita se è disattivato
* [Shader] Se un &quot;param auto&quot; non è corretto, non vengono stampati errori

**Problema noto:**

* [Mac] Il limite di campioni di texture è bloccato su 16 (problema con il driver della GPU)
