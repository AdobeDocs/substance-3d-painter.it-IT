---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/advanced-channel-painting/normal-map-painting.html"
breadcrumb-title: ''
description: Scoprite come pittura la mappa normale direttamente in Substance 3D Painter per aggiungere dettagli della superficie e profondità alle texture.
helpx_creative_field: ""
helpx_description: Painter > Painting > Advanced channel painting > Normal Map Painting
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mappa normale pittura
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '553'
ht-degree: 0%

---


# Mappa normale pittura

I dettagli di pittura possono essere eseguiti colorando direttamente i dati della Mappa normale direttamente sulla trama. In questa pagina viene raggruppato un modo diverso per gestire la normale pittura di mappe.

## Dettagli mappa normale di pittura

Per pittura dettagli mappa normale:

1. Aggiungete un canale normale all’attuale set di texture (se non è già presente)
1. Attivate il canale normale nello strumento di pittura corrente
1. Caricate una risorsa Normale nello slot Normale della sezione Materiale dello strumento di pittura corrente.

Da lì, dipingere con una mappa normale è molto simile a [Pittura mappa Height](height-map-painting.md) , con la precisione aggiuntiva di una normale cotta.

![](../../assets/normal-painting.gif)

## Metodi di fusione normali

Le mappe normali hanno metodi di fusione propri nella Pila livelli:

* **Mappa normale dettagli** (impostazione predefinita)
* **Mappa normale dettagli inversa**
* **Mappa normale combinazione**

Per ulteriori informazioni, consultate la pagina [Metodi di fusione](../../interface/layer-stack/blending-modes.md).

## Spazio colore normale

Quando si carica una mappa normale nello slot di un materiale (proprietà dello strumento o livello di riempimento), è possibile modificare lo spazio colore predefinito.

Questa impostazione può essere utilizzata per specificare il Formato mappa normale poiché per impostazione predefinita è prevista una mappa normale di DirectX (Y-), che non è influenzata dall&#39;impostazione del progetto. Pertanto, quando si utilizza una mappa normale OpenGL (Y+), è necessario fare clic sulla piccola freccia per aprire il menu dello spazio colore e quindi modificare lo spazio colore della bitmap.

![](../../assets/normal-color-space.png)

## Dipingere su una mappa normale eseguita i baking

In alcune situazioni, può essere utile sovrapporre la pittura eseguita i baking per nascondere i dettagli (o anche risolvere problemi eseguiti i baking).\
L’impostazione predefinita di un progetto in Substance 3D Painter non lo consente, in quanto calcola separatamente il canale normale e la normale eseguita i baking. Questo comportamento può essere modificato tramite le [impostazioni del set di texture](../../interface/texture-set/texture-set-settings.md).

### 1 - Modifica del metodo di fusione del set di texture

Per impostazione predefinita viene creato un set di texture con l&#39;impostazione **mixaggio normale** impostata su **combina**.

Per eseguire l&#39;override o la pittura della mappa normale, è importante impostare questa impostazione su **replace**. La mappa normale scomparirà dalla finestra della vista, ma è previsto. La modifica di questa modalità in **replace** indica a Substance 3D Painter di tenere conto solo del canale normale e del canale di height durante la generazione della mappa normale finale.

![](../../assets/normal-mixing.png)

### 2 - Impostazione di un livello di riempimento con la mappa normale eseguita i baking

Crea un nuovo livello di riempimento e inserisci la normale eseguita i baking nello slot &quot;normale&quot;, tramite il pannello proprietà. Se il livello di riempimento non è impostato su 1, non dimenticate di modificare la fresatura predefinita.

![](../../assets/fill-layer_1.gif)

### 3 - Modificare il metodo di fusione del livello di riempimento

Per impostazione predefinita, il metodo di fusione del canale normale su qualsiasi nuovo livello è impostato su &quot;Mappa normale dettagli&quot;. Poiché è preferibile utilizzare il livello di riempimento come base, abbiamo scelto il metodo di fusione &quot;normale&quot;, in quanto la bitmap non ha canale alfa, sostituirà tutto ciò che segue (compreso il colore predefinito dello shader).

![](../../assets/blending-mode.gif)

### 4 - Creazione di un livello da far pittura sulla mappa normale eseguita i baking

Create un nuovo livello (regolare o di riempimento) e impostatene il metodo di fusione su &quot;normale&quot; per il canale normale. Una volta completata questa configurazione, tutto ciò che viene dipinto sul canale normale assumerà il controllo della mappa normale eseguita i baking che si trova sul livello sottostante.

![](../../assets/normal-painting-over.gif)
