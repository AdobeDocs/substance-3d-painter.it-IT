---
title: Filtro
description: Scoprite come utilizzare gli effetti di filtro in Substance 3D Painter per applicare i filtri di elaborazione delle immagini e le regolazioni delle texture.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '584'
ht-degree: 3%
---

# Filtro

Gli effetti di filtro sono sostanze che Trasforma il contenuto di un livello o di una maschera. Con il metodo di fusione Passthrough, un livello può modificare i risultati della Pila livelli; l’uso di un filtro su un livello con il metodo di fusione Passthrough consente quindi di utilizzare i filtri per modificare la Pila livelli nel suo insieme.

## Come posso applicare un filtro?

A seconda del tipo di filtro, è necessario creare un effetto filtro sul contenuto o sulla maschera di un livello. È possibile applicare un filtro in due modi:

* L’approccio manuale richiede più passaggi per impostare il filtro, ma fornisce un controllo diretto su ogni passaggio del processo.
* La funzione di trascinamento consente di aggiungere rapidamente un filtro e imposta automaticamente il metodo di fusione su tutti i canali.

### Applicare manualmente un filtro

Nell’esempio seguente viene applicato un filtro di sfocatura al contenuto di un livello, ma questo viene utilizzato più comunemente per applicare filtri alle maschere:

**1. Aggiungi un effetto filtro**

Iniziate selezionando il contenuto di un livello o la maschera di livello, quindi fate clic sul **pulsante Effetto** (o fate clic con il pulsante destro del mouse per aprire il menu di scelta rapida). Selezionare l&#39;opzione &quot; **Aggiungi filtro** &quot; nell&#39;elenco.

![](../../assets/filters/filter-add-manually.gif)

**2. Selezionare il filtro nella finestra delle proprietà**

Nel **pannello Proprietà**, non è ancora stato selezionato alcun filtro. Fate clic sul pulsante di selezione Filtro per aprire il ripiano e selezionare il filtro desiderato. Qui è possibile scegliere il **filtro Sfocatura**.
![](../../assets/filters/filter-select.gif)

>[!NOTE]
>
> Quando applicate manualmente un filtro, ricordate che potrebbe essere necessario utilizzare il metodo di fusione pass-through se desiderate che il filtro influisca sul contenuto dei livelli sottostanti.

## Trascinare un filtro dallo scaffale

Questo metodo è destinato solo ai filtri che devono essere applicati all’intero gruppo di livelli. Verranno impostati automaticamente tutti i metodi di fusione di canale [](../../interface/layer-stack/blending-modes.md). Non funziona per applicare filtri a una maschera.

**1. Aprire l&#39;area Filtri dello scaffale**

Nel Ripiano, fai clic sulla sezione &quot;Filtri&quot; a sinistra.

![](../../assets/shelf-filters.gif)

**2. Trascina il filtro**

Seleziona il filtro da usare nello scaffale. Trascinalo nel gruppo di livelli, per assicurarti che si trovi nella posizione corretta (ad esempio, per evitare di trascinarlo in gruppi indesiderati).

![](../../assets/filter-dragdrop.gif)

Nell’esempio precedente, il filtro rilasciato ha già un metodo di fusione Passthrough. Questo vale per tutti i canali del documento.

## Aggiungi nuovi filtri

Tutti i filtri sono Substance e possono essere creati con Substance 3D Designer. Come avvio rapido, Substance 3D Designer fornisce modelli pronti all’uso per Substance 3D Painter.

Per ulteriori informazioni, consulta questa pagina: [Creazione di effetti personalizzati](../../content/creating-custom-effects/creating-custom-effects.md)

## Filtri disponibili

### Standard

* [Sfocatura](filters/standard/blur.md)
* [Sfocatura direzionale](filters/standard/blur-directional.md)
* [Pendenza sfocatura](filters/standard/blur-slope.md)
* [Fisso](filters/standard/clamp.md)
* [Bilanciamento colore](filters/standard/color-balance.md)
* [Correzione colore](filters/standard/color-correct.md)
* [Luminosità contrasto](filters/standard/contrast-luminosity.md)
* [Ombra esterna](filters/standard/drop-shadow.md)
* [Colore area di riempimento](filters/standard/fill-area-color.md)
* [Riempi area maschera](filters/standard/fill-area-mask.md)
* [FXAA (Anti-alias)](filters/standard/fxaa-anti-aliasing.md)
* [Bagliore](filters/standard/glow.md)
* [Sfumatura](filters/standard/gradient.md)
* [Sfumatura dinamica](filters/standard/gradient-dynamic.md)
* [Conversione in scala di grigi](filters/standard/grayscale-conversion.md)
* [Passa alte](filters/standard/highpass.md)
* [Scansione istogramma](filters/standard/histogram-scan.md)
* [Spostamento istogramma](filters/standard/histogram-shift.md)
* [Percettivo HSL](filters/standard/hsl-perceptive.md)
* [Inverti](filters/standard/invert.md)
* [Speculare](filters/standard/mirror.md)
* [Effetto pixel](filters/standard/pixelate.md)
* [Posterizza](filters/standard/posterize.md)
* [Nitidezza](filters/standard/sharpen.md)
* [Smoothstep](filters/standard/smoothstep.md)
* [Soglia](filters/standard/threshold.md)
* [Trasforma](filters/standard/transform.md)
* [Ordito](filters/standard/warp.md)

### Finiture

* [Finitura mascherino - Pennello lineare](filters/finishes/matfinish-brushed-linear.md)
* [MatFinish Galvanizzato](filters/finishes/matfinish-galvanized.md)
* [MatFinish Grainy](filters/finishes/matfinish-grainy.md)
* [MatFinish macinato](filters/finishes/matfinish-grinded.md)
* [MatFinish Hammered](filters/finishes/matfinish-hammered.md)
* [Cerchi perforati finitura mascherino](filters/finishes/matfinish-perforated-circles.md)
* [Rivestimento in polvere MatFinish](filters/finishes/matfinish-powder-coated.md)
* [MatFinish Raw](filters/finishes/matfinish-raw.md)
* [Ruvido finitura mascherino](filters/finishes/matfinish-rough.md)

### MatFX

* [Fumetto MatFX](filters/matfx/matfx-comic-book.md)
* [Edge Wear dettagliato MatFX](filters/matfx/matfx-detail-edge-wear.md)
* [Danni ai bordi di MatFX](filters/matfx/matfx-edge-damages.md)
* [MatFX HBAO](filters/matfx/matfx-hbao.md)
* [Pittura a olio MatFX](filters/matfx/matfx-oil-paint.md)
* [Pittura di peeling MatFX](filters/matfx/matfx-peeling-paint.md)
* [Meteorizzazione Ruggine MatFX](filters/matfx/matfx-rust-weathering.md)
* [Linea di chiusura MatFX](filters/matfx/matfx-shut-line.md)
* [Effetto acquerello MatFX](filters/matfx/matfx-watercolor.md)
* [Gocce d’acqua MatFX](filters/matfx/matfx-water-drops.md)

### Illuminazione

* [Baked lighting environment](filters/lighting/baked-lighting-environment.md)
* [Illuminazione eseguita i baking stilizzata](filters/lighting/baked-lighting-stylized.md)

### Avanzate

* [Kuwahara Anisotropo](filters/advanced/anisotropic-kuwahara.md)
* [Smusso](filters/advanced/bevel.md)
* [Smusso uniforme](filters/advanced/bevel-smooth.md)
* [Corrispondenza colori](filters/advanced/color-match.md)
* [Distanza direzionale](filters/advanced/directional-distance.md)
* [Curva sfumatura](filters/advanced/gradient-curve.md)
* [Regolazione height](filters/advanced/height-adjustments.md)
* [Height a normale](filters/advanced/height-to-normal.md)
* [Contorno maschera](filters/advanced/mask-outline.md)
* [PBR Validata](filters/advanced/pbr-validate.md)
* [Quantizza](filters/advanced/quantize.md)
* [Stilizzazione](filters/advanced/stylization.md)
* [Tri-Planari Advanced](filters/advanced/tri-planar-advanced-filter.md)
