---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/release-notes/old-versions/version-2-4.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Painter versione 2.4 per informazioni sulle nuove funzioni, i miglioramenti e le correzioni di bug.
helpx_creative_field: ""
helpx_description: Painter > Release notes > Old versions > Version 2.4
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 2.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '631'
ht-degree: 0%

---


# Versione 2.4

**Substance Painter 2.4** si concentra sul miglioramento della finestra scaffale e sulla gestione delle risorse.

Data di pubblicazione: *27 ottobre 2016*

## Funzioni principali

### Nuova finestra scaffale con filtro avanzato

![](../../assets/new-shelf-240.jpg)

La nuova finestra dello scaffale offre **una migliore organizzazione** delle risorse, oltre a **nuovi modi per filtrare i contenuti**. Abbiamo aggiunto la possibilità di creare **predefiniti personalizzati** in cui ogni predefinito ha un proprio filtro (per passare rapidamente tra le diverse query). Questi predefiniti possono anche essere i **isolati in una nuova finestra**, offrendo un modo per avere **più viste** dello scaffale e non solo una come prima. I filtri consentono inoltre di **sfogliare la gerarchia delle cartelle sul disco**, rendendo più utile il perfezionamento di una query più generale. È stato inoltre migliorato il **menu di scelta rapida** (quando si fa clic con il pulsante destro su una risorsa) per fornire **ulteriori informazioni utili**.

Per creare query avanzate, vedere la parte dedicata della documentazione: [Query di ricerca avanzate](../../interface/assets/advanced-search-queries.md)

### Finestra Nuova risorsa di importazione

![](../../assets/import-window-240.png)

Con la rielaborazione dello scaffale è stata **migliorata anche la finestra di importazione delle risorse**. La finestra è ora più coerente e può essere **chiamata in tre modi diversi**: tramite il menu File, tramite il pulsante nella finestra dello scaffale o come prima trascinando una risorsa nella finestra dello scaffale. La nuova finestra consente di **impostare rapidamente l&#39;utilizzo** per **più risorse** contemporaneamente, il che significa che non è più necessario trascinare e rilasciare le risorse nella posizione corretta. È stata inoltre aggiunta la possibilità di **specificare un percorso personalizzato** per creare sottocartelle per sfruttare la nuova visualizzazione della struttura.

Per ulteriori informazioni, vedere la parte dedicata della documentazione: [Aggiunta di risorse tramite la finestra di importazione](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/adding-content-via-the-import-window-151584824.html)

### Nuovi predefiniti particelle

![](../../assets/particle-240.png)

Abbiamo **rielaborato** il precedente **predefinito particelle** per renderlo più pronto all&#39;uso (in particolare il predefinito **Pioggia**). Abbiamo colto l&#39;occasione anche per **aggiungere nuovi predefiniti** con nuovi comportamenti: date un&#39;occhiata a **Electric Circuit, Electric Lines, Rococo e Veins Small**!

## Esercitazione

Le nuove funzioni e l’utilizzo dello scaffale sono descritti nell’ultima esercitazione:

## Note sulla versione

### 2.4.1

(Pubblicato il 28 ottobre 2016)

**Risolto:**

* Arresto anomalo durante la creazione di un progetto con un modello
* Arresto anomalo quando si chiude la finestra di dialogo di esportazione durante un’esportazione
* [Mac] Errori durante il salvataggio del progetto (impossibile salvare il predefinito di esportazione)
* [Shelf] Quando si crea un nuovo predefinito, questo viene visualizzato due volte
* [Shelf] I predefiniti non possono essere caricati in modalità di sola lettura senza diritti di amministratore

### 2.4.0

(Pubblicato il 27 ottobre 2016)

**Aggiunto:**

* [Shelf] Nuova interfaccia per sfogliare le risorse (vista struttura, filtri e così via)
* [Shelf] Consente di salvare una ricerca come predefinito
* [Shelf] Consente di creare una nuova finestra da un predefinito
* [Shelf] Nuova interfaccia per l&#39;importazione delle risorse
* [Shelf] Non copiare lo scaffale allegorico predefinito nella cartella Documenti
* [Shelf] Nuovi predefiniti particelle : Circuito elettrico, Linee elettriche, Rococò, Vene piccole
* [Shelf] Migliorati i vecchi predefiniti particelle per essere più facili da usare (come &quot;Rain&quot;)
* [Shelf] Aggiungi nuove informazioni nel menu contestuale della risorsa
* [Finestra di visualizzazione] Miglioramento delle prestazioni durante il caricamento delle mappe dell&#39;ambiente
* [Finestra vista] Aggiungi il supporto per mappe di ambiente che non sono alimentate da due

**Risolto:**

* Arresto anomalo durante la rimozione di una maschera
* Arresto anomalo quando si disegna dopo aver salvato un predefinito
* Arresto anomalo con sfocatura dell’ambiente su alcune GPU
* Arresto anomalo durante l’assegnazione di una risorsa errata al mini scaffale
* [Shelf] Pulisci e salva rimuovi tag e metadati per le risorse nel progetto
* [Shelf] l’importazione di un predefinito ne mostra le risorse nello shelf
* La Mappa normale [Esporta] generata dal canale del height ha un’intensità bassa
* [Esporta] Normale da trama non sempre presente nella mappa normale finale
* [Esportazione] Talvolta può verificarsi una dilatazione con trasparenza senza alcuna trasparenza
* [Scripting] &quot;alg.plugin\_root\_directory&quot; può restituire un percorso di rete troncato
* Il pulsante [TextureSet] Lock (Blocca texture) è attivato quando si riaprono progetti non quadrati
