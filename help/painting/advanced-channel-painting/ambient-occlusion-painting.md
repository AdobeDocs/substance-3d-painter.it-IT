---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/advanced-channel-painting/ambient-occlusion-painting.html"
breadcrumb-title: ''
description: Scopri come pittura le mappe di occlusione ambientale direttamente in Substance 3D Painter per aggiungere ombre e profondità realistiche alle texture.
helpx_creative_field: ""
helpx_description: Painter > Painting > Advanced channel painting > Ambient Occlusion Painting
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Occlusione ambientale pittura
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '522'
ht-degree: 0%

---


# Occlusione ambientale pittura

Il canale di occlusione ambientale consente di pittura i dettagli nelle ombre ambientali di un oggetto. Può essere utilizzato per aggiungere dettagli AO provenienti da Materiali o semplicemente correggere manualmente gli errori di esegue i baking quando necessario.

&#x200B;>> 

Nella computergrafica, l’occlusione ambientale è una tecnica di ombreggiatura e rendering utilizzata per calcolare l’esposizione di ciascun punto di una scena all’illuminazione ambientale. L&#39;interno di un tubo è tipicamente più occluso (e quindi più scuro) rispetto alle superfici esterne esposte, e più si va all&#39;interno del tubo, più occlusa (e più scura) diventa l&#39;illuminazione. L’Occlusione ambientale può essere vista come un valore di accessibilità calcolato per ciascun punto della superficie.\
Fonte: &lt;https://en.wikipedia.org/wiki/Ambient_occlusion>

Il **risultato** di questo calcolo è archiviato in una bitmap denominata mappa &quot;Occlusione ambientale&quot;. Questa mappa può essere eseguita i baking direttamente nell&#39;applicazione. Vedere: [Esegue i baking](../../baking/baking.md).

## Occlusione ambientale pittura

Per pittura i dettagli dell’occlusione personalizzata, è necessario un canale di Occlusione ambientale. Può essere aggiunto tramite le [impostazioni del set di texture](../../interface/texture-set/texture-set-settings.md):

![](../../assets/add-ao-channel.png)

Una volta aggiunto il canale a un set di texture, potete usare qualsiasi livello per pittura nuove informazioni. Poiché il canale AO contiene solo informazioni in scala di grigio, i metodi di fusione consigliati sono **Normale** (pittura sopra) e **Moltiplica** (combina).

Per ulteriori informazioni su questi metodi e su come modificarli per canale, consultate: [Metodi di fusione](../../interface/layer-stack/blending-modes.md).

## Dipingere sulla mappa aggiuntiva dell&#39;Occlusione ambientale

In alcune situazioni, può essere utile sovrapporre le pitture all’Occlusione ambientale eseguita i baking per nascondere i dettagli o persino risolvere i problemi di esegue i baking.

La configurazione predefinita di un progetto in Substance 3D Painter combinerà l&#39;Occlusione ambientale **canale** con la mappa di Occlusione ambientale dalle **mappe aggiuntive**. Ciò significa che, per impostazione predefinita, non è possibile colorare sulla mappa aggiuntiva eseguita i baking; i risultati di ogni mappa (le mappe con baking e i canali) verranno moltiplicati insieme. Questa impostazione può tuttavia essere modificata con la seguente:

### 1 - Aggiungere un canale di Occlusione ambientale

Aggiungete un canale di occlusione ambientale nel set di texture corrente:\
![](../../assets/edit-ao-channel-optimized.gif)

Impostate la modalità di mixaggio su &quot; **replace** &quot; invece di &quot; **multiply** &quot;:\
![](../../assets/ao-mix-mode.gif)

### 2 - Impostazione di un livello di riempimento con l’occlusione ambientale eseguita i baking

Crea un nuovo livello di riempimento e inserisci l’occlusione ambientale eseguita i baking nello slot &quot;occlusione ambientale&quot;, tramite il pannello proprietà. Non dimenticare di modificare la lavorazione predefinita del livello di riempimento, se non è già impostata su 1.\
![](../../assets/ao-stack.png)

### 3 - Modificare il metodo di fusione del livello di riempimento

Per impostazione predefinita, il metodo di fusione del canale AO su qualsiasi nuovo livello è impostato su &quot; **Moltiplica** &quot;. Poiché è preferibile utilizzare il livello di riempimento come base, abbiamo scelto il metodo di fusione &quot;normale&quot;, in quanto la bitmap non ha alcun canale alfa, sostituirà tutto ciò che segue (incluso il colore predefinito dello shader).\
![](../../assets/ao-blend-mode.gif)

### 4 - Creazione di un livello di pittura sulla mappa di occlusione ambientale eseguita i baking

Create un nuovo livello (regolare o di riempimento) e impostatene il metodo di fusione su &quot;normale&quot; per il canale AO. Una volta completata questa configurazione, tutto ciò che viene dipinto sul canale AO assumerà il controllo della mappa dell’AO cotta che si trova sul livello sottostante.\
![](../../assets/paint-over-ao-optimized.gif)
