---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/performances-guidelines/layer-management.html"
breadcrumb-title: ''
description: Scopri le best practice per la gestione dei livelli in Substance 3D Painter per ottimizzare le prestazioni e gestire i progetti organizzati.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Performances guidelines > Layer management
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Gestione dei livelli
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '677'
ht-degree: 0%

---


# Gestione dei livelli

Painter calcola la pila di livelli dal basso verso l’alto. Pertanto, se apporti modifiche al livello superiore della pila, Painter deve solo calcolare le modifiche di quel livello. Tuttavia, se apportate una modifica a un livello nella parte inferiore della pila, per calcolare il risultato finale Painter deve calcolare tutti i livelli al di sopra di tale livello.

Esistono diverse opzioni che potete utilizzare per ridurre il costo in termini di prestazioni quando si apportano modifiche ai livelli più bassi nella pila:

+++Usare le maschere di geometria
Le maschere di geometria sono lo strumento di ottimizzazione migliore. Ogni volta che puoi isolare una parte della trama su cui lavorare, esegui questa operazione mascherando i livelli o le cartelle. Le maschere di geometria funzionano isolando mediante UDIM o mediante una parte di trama, in modo che le aree che non si trovano nella maschera non vengano elaborate, migliorando le prestazioni. Per semplificare la creazione delle texture, potete anche isolare visivamente le parti nella finestra della vista.

Potete [ottenere ulteriori informazioni sulle maschere di geometria con questo tutorial](https://www.youtube.com/watch?v=TGASuIGSUns) o [facendo riferimento alla documentazione](../../interface/layer-stack/geometry-mask.md).

+++

+++Nascondi livelli
Per evitare rallentamenti quando si apportano modifiche a un livello inferiore nella pila dei livelli, potete nascondere i livelli sopra il livello modificato fino a quando non avete completato le regolazioni. Painter non elabora i livelli nascosti, quindi se tutti i livelli superiori sono nascosti, è come se steste modificando il livello superiore della pila. In questo modo, i livelli superiori verranno calcolati solo una volta, quando li scoprirai, anziché dopo ogni modifica apportata.

+++

+++Disabilita livelli
Proprio come per nascondere i livelli, il metodo di fusione Disattiva impedisce di calcolare i livelli. Può essere utile impostare i livelli a basso impatto sul metodo di fusione Disattiva durante la modifica delle aree in cui non sono importanti.

+++

+++Utilizzare le cartelle
Quando possibile, prova a raggruppare i livelli, in quanto le cartelle agiscono come un punto di memorizzazione invisibile nella cache. Se si apportano modifiche al di sotto o al di sopra di una determinata cartella, i livelli all&#39;interno della cartella non verranno ricalcolati singolarmente, ma il risultato del gruppo verrà ricalcolato.

+++

+++Limita l’uso di filtri nella parte superiore del gruppo di livelli
I filtri possono essere costosi. Se è necessario utilizzare un filtro vicino alla parte superiore dello stack di livelli, utilizzate le maschere di geometria per ridurre i costi di prestazioni.

+++

+++Limita l&#39;utilizzo del metodo di fusione passthrough
La passthrough viene spesso utilizzata con filtri o livelli di tratti pennello. Si tratta di un metodo di fusione costoso perché esamina tutti i livelli sottostanti e ne trasforma il risultato, invece di ignorare il risultato come se fosse un metodo di fusione normale. Ogni volta che si utilizza la passthrough, provare a combinarla con le maschere e le cartelle Geometry per ridurre al minimo l&#39;impatto sulle prestazioni.

+++

+++Profondità di proiezione ridotta
Con qualsiasi strumento o modalità che abbia un’impostazione profondità di proiezione (alterazione, planare, tracciato, ecc.), mantenete il valore della profondità di proiezione il più basso possibile. Più la profondità di proiezione si estende, meno performante risulta.

+++

+++Fai attenzione con i pennelli che hanno tratti dinamici
I pennelli e gli strumenti con un tag arancione hanno un parametro dinamico. Questo parametro dinamico può essere impostato su &quot;Illimitato&quot;, il che significa che ogni timbro in un tratto sarà univoco. Questo può avere un notevole impatto sulle prestazioni se si utilizzano centinaia o migliaia di tratti di pennello. Nella maggior parte dei casi, è difficile distinguere tra 16 e 32 variazioni, quindi in generale andare oltre è improbabile che abbia un impatto visivo maggiore.

[Ulteriori informazioni sui tratti dinamici nella documentazione.](../../painting/dynamic-strokes/dynamic-strokes.md)

+++

+++Lavora con una risoluzione della texture più bassa
La riduzione della risoluzione dei documenti è il modo più rapido per migliorare le prestazioni. Raddoppiare la risoluzione significa ottenere una mappa 4 volte più grande, quindi passare da 1k a 2k significa aumentare i costi delle prestazioni fino a 4 volte. Di conseguenza, è spesso utile lavorare ad una risoluzione più bassa il più a lungo possibile.

+++

+++Imposta le decalcomanie sulla modalità di proiezione planare
La modalità decalcomania predefinita è Altera, ma a meno che non si stia deformando la decalcomania spostandone i punti, il passaggio alla modalità Planare è molto meno costoso.

+++
