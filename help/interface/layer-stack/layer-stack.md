---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/layer-stack.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la Pila livelli in Substance 3D Painter per organizzare e gestire più livelli di pittura texture.
helpx_creative_field: ""
helpx_description: Painter > Interface > Layer stack
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Stack di livelli
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '615'
ht-degree: 5%

---


# Stack di livelli

![](../../assets/layer-stack.png)

La **Pila livelli** consente di manipolare i livelli di un set di texture. Un livello contiene il quadro e gli effetti che creeranno la texture sull’oggetto 3D nella scena. Potete nascondere e scoprire i livelli, inserirli in cartelle e modificarne l’opacità e il metodo di fusione.

Per ulteriori informazioni, vedere le pagine seguenti:

* [Creazione di livelli](creating-layers.md)
* [Gestione dei livelli](managing-layers.md)
* [Mascheratura ed effetti](masking-and-effects.md)
* [Metodi fusione](blending-modes.md)
* [Istanza dei livelli](layer-instancing.md)
* [Maschera Geometria](geometry-mask.md)

## Panoramica

La Pila livelli visualizza i livelli con una gerarchia specifica: il livello in basso verrà disegnato per primo sulla trama, il livello in alto seguirà. Di conseguenza, il livello in cima alla pila è l’ultimo elemento, mentre il livello in fondo è il primo. Lo stesso principio si applica alle cartelle, tuttavia il contenuto della cartella ha la priorità. Ciò significa che il contenuto di una cartella verrà elaborato prima dei livelli che si trovano allo stesso livello.

**Caratteristiche comuni:**

* Ogni livello è **multicanale**.
* Lo strumento pittura pittura **su tutti i rispettivi canali** a seconda delle impostazioni del materiale (il canale attualmente visualizzato nella Pila livelli non ha alcun impatto).
* Ogni livello ha un **metodo di fusione** e un **opacità** per canale (puoi passare da un canale all’altro tramite il menu a discesa in alto a sinistra).

**Tipi di livelli:**

* **Livello di pittura**: questo tipo di livello può essere colorato con pennelli e particelle
* **Livello di riempimento**: questo livello non può essere colorato, ma potete caricarvi un materiale per riempire i canali. Potete anche manipolare la trasformazione per ripetere il materiale, ad esempio.
* **Cartella**: questo tipo di livello ha solo lo scopo di contenere altri livelli, ma viene utilizzato principalmente per organizzare la Pila livelli

Su ogni livello puoi **aggiungere una maschera** che consente di applicare il contenuto solo a parti specifiche dei canali del set di texture corrente.\
Potete applicare manualmente le pitture alla maschera (in scala di grigio con un pennello) oppure usare filtri e sostanze per ottenere risultati più dinamici/procedurali.

## Modalità visualizzazione

![](../../assets/switch-viewmode-optim.gif)

Il menu a discesa superiore sinistro della Pila livelli controlla la modalità di visualizzazione della Pila livelli. Poiché un livello può coprire più canali, non è possibile visualizzare tutte queste proprietà contemporaneamente. La modalità visualizzazione può quindi essere utilizzata per definire il contesto di visualizzazione corrente. Quando si utilizza questo menu a discesa è possibile specificare quali canali devono essere utilizzati per visualizzare nelle miniature dei livelli, nonché controllare il metodo di fusione e l’opacità solo per questo canale.

L&#39;elenco in questo menu a discesa è basato sull&#39;elenco dei canali disponibili nelle [impostazioni del set di texture](../texture-set/texture-set-settings.md).

## Azioni

![](../../assets/image2020-9-30-12-2-13.png)

L&#39;elenco di icone in alto a destra contiene le azioni più comuni che è possibile eseguire nella Pila livelli:

| Azione | Descrizione |
| --- | --- |
| Aggiungi effetto <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-effect.png"/></div> | Crea un nuovo effetto e aggiungilo al livello selezionato. Per ulteriori informazioni sugli effetti, consultate[pagine dedicate](../../features/effects/effects.md). |
| Crea maschera <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-mask.png"/></div> | Apri il menu dell&#39;azione Maschera che contiene le seguenti voci:<ul data-preserve-html="true"><li data-preserve-html="true">Aggiungi maschera bianca</li><li data-preserve-html="true">Aggiungi maschera nera</li><li data-preserve-html="true">Aggiungi maschera bitmap</li><li data-preserve-html="true">Aggiungi maschera con selezione del colore</li><li data-preserve-html="true">Aggiungi maschera con combinazione di altezze</li></ul> |
| Crea nuovo Livello di pittura <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r3-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/image2020-9-30-11-52-41.png"/></div> | Crea un nuovo Livello di pittura sopra a quello attualmente selezionato. |
| Crea nuovo livello di riempimento <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r4-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/image2020-9-30-12-0-49.png"/></div> | Crea un nuovo [livello di riempimento](../../painting/fill-projections/fill-projections.md) sopra quello attualmente selezionato. |
| Aggiungi nuovi Materiali avanzati <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r5-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-smartmat.png"/></div> | Inserisce un nuovo Materiale avanzato sopra il livello attualmente selezionato.Facendo clic su questo pulsante si aprirà un mini-scaffale per sfogliare l&#39;elenco dei Materiali avanzati disponibili nelle [Risorse](../../interface/assets/assets.md) correnti. |
| Aggiungi nuova cartella <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r6-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/image2020-9-30-12-1-13.png"/></div> | Crea una nuova cartella vuota sopra il livello attualmente selezionato. |
| Elimina livello <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r7-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-trash.png"/></div> | Elimina l’elemento attualmente selezionato (livello, cartella o effetto). |
