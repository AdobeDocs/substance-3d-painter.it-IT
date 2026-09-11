---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/workflow-issues/project-issues/projects-are-really-big.html"
breadcrumb-title: ''
description: Scopri come ridurre le dimensioni dei file di progetto di Substance 3D Painter per ottimizzare le prestazioni e i requisiti di archiviazione.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > Project Issues > Projects are really big
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: I progetti sono davvero grandi
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '883'
ht-degree: 0%

---


# I progetti sono davvero grandi

Il progetto Substance 3D Painter può essere molto grande e utilizzare molto spazio su disco. Questa pagina spiega perché e come attenuarla.

## Che tipo di risorsa è memorizzata in un progetto?

Ogni risorsa o risorsa utilizzata durante la creazione della texture viene memorizzata nel file di progetto, tra cui:

* **Trama di origine** (non il file originale, ma uno elaborato)
* **Mappe trama Eseguite i baking**
* **Materiali** (come i materiali Substance)
* **Bitmap** o altre risorse utilizzate da qualsiasi livello, predefinito o tratto del pennello.

Le maglie ad alto poli non sono incluse nel progetto. Sono semplicemente collegati.

## Perché un progetto memorizza così tante risorse?

L&#39;archiviazione di tutte le risorse utilizzate rende un progetto completamente autonomo e facilmente spostabile da un computer all&#39;altro senza romperlo. L&#39;aspetto negativo principale è l&#39;ingombro potenzialmente elevato dei file sul disco.

La decisione di incorporare tutto nel file del progetto deriva dal fatto che tutto è non distruttivo. Significa che il progetto &quot;ricostruisce&quot; se stesso quando viene riaperto. Se manca un singolo pennello o materiale dallo scaffale, il progetto potrebbe rompersi e non essere in grado di rigenerarsi correttamente. L&#39;archiviazione di un duplicato della risorsa garantisce che il progetto possa essere ripristinato mentre è stato salvato.

## Esiste un modo per ridurre le dimensioni di un progetto?

Esistono alcuni modi per ridurre le dimensioni di un progetto:

### Pulisci risorse inutilizzate

Quando si utilizzano molte risorse in un progetto, Substance 3D Painter le copia. Ad esempio, se hai usato un canale alfa per dare una pittura a qualcosa. Se successivamente eliminate il livello quando è stato applicato il colore alfa, Substance 3D Painter non rimuove automaticamente la risorsa.

Per rimuovere la risorsa inutilizzata, utilizzare l&#39;azione **Pulisci** dal [menu File](https://substance3d.adobe.com/display/DRAFTPAINTER/File+menu). Quindi salva il progetto (questo attiverà la rimozione effettiva della risorsa).

Impossibile rimuovere la risorsa ancora utilizzata in un progetto. Ciò significa che il set di texture disabilitato fa ancora riferimento alle risorse e ne impedisce l’eliminazione. Per evitare ciò, rimuovere gli insiemi di texture disabilitati nella [finestra di riassegnazione degli insiemi di texture](../../../interface/texture-set/texture-set-reassignment.md).

### Ridurre la risoluzione del set di texture

Quando si salva un progetto, il risultato finale della Pila livelli di un set di texture viene salvato nel progetto. In questo modo è possibile mantenere un’anteprima nella finestra della vista quando il progetto viene riaperto senza dover ricalcolare il set di texture. Tuttavia, maggiore è la risoluzione del set di texture, maggiore sarà la cache di anteprima.

Per ridurre l&#39;ingombro della cache, basta cambiare la risoluzione su un numero più basso, come ad esempio 512. Poiché Substance 3D Painter non è distruttivo, questa risoluzione può essere ripristinata in un secondo momento senza perdere qualità.

### Comprimi il progetto

Il salvataggio incrementale di un progetto (tramite CTRL+S) può comportare la frammentazione dell&#39;archivio dei file di progetto. Anche se non è un problema critico, questo può introdurre uno spazio vuoto nel file di progetto che può aumentare le dimensioni.

Utilizzare la funzione &quot;Salva e compatta&quot; nel [Menu File](../../../interface/main-menu/file-menu.md) per salvare nuovamente il progetto e rimuovere lo spazio vuoto sprecato. Questa azione di salvataggio sarà più lunga di un salvataggio normale, ma può ridurre notevolmente l’ingombro del file.

### Riduci la dimensione delle mappe trama eseguite i baking

In generale, il principale colpevole e il motivo per cui un progetto occupa così tanto spazio sul disco è che le Mesh Maps eseguite i baking sono di per sé numerose e grandi.

Per ridurre le dimensioni delle Mesh Maps è possibile:

* *Utilizza una risoluzione di eseguita i baking inferiore.*\
  Anche se la Mappa normale può essere utile per essere eseguita i baking in 4K, questo potrebbe non essere il caso per la mappa di posizione, che di solito è solo intorno a sfumature colorate. Esegue i baking in due passaggi a due risoluzioni diverse per combinare diverse dimensioni di file.
* *Esportare la texture e ridurne manualmente l&#39;ingombro.*\
  Per impostazione predefinita, Substance 3D Painter esegue i baking tutte le texture come immagini RGBA a 16 bit, compresi i baker in scala di grigi come l’Occlusione ambientale.

  Per ridurre il eseguo i baking di impronta texture, segui questa procedura dettagliata:
  1. Disattivare l&#39;impostazione &quot;Applica diffusione&quot; nella finestra del Baker
  1. Imposta &quot;Dilatazione con&quot; su un valore ragionevole (ad esempio, 32 pixel per una risoluzione 2048)
  1. Esegue i baking tutte le tue Texture alla stessa risoluzione
  1. Esporta la texture eseguita i baking con il predefinito di esportazione &quot;Mesh Maps&quot; come PNG a 16 bit con il riempimento impostato su &quot;No padding (passthrough)&quot;
  1. Apri ogni mappa con un software di fotoritocco o Substance 3D Designer
  1. Riducete la risoluzione per le texture per le quali sembrano essere state adattate. Assicuratevi di cambiare l&#39;Occlusione ambientale, la curvatura e il Thickness da colore a scala di grigio.
  1. Salvate le nuove versioni delle texture come PNG a 16 bit.
  1. Reimportate le texture e sostituitele sulle texture di esegue i baking originali nelle impostazioni Set texture.
  1. Per rimuovere le vecchie mappe trama, usate l’azione Pulisci del menu File.
  1. Per comprimere il file di progetto, utilizzate l’azione Salva e compatta del menu File.\
     Dopo tutte queste fasi, l&#39;ingombro del progetto dovrebbe essere notevolmente ridotto.

È importante che le mappe della trama rimangano almeno texture a 16 bit. Anche se le texture a 8 bit possono avere un ingombro ridotto, introdurranno artefatti nei materiali avanzati e nei generatori di maschere. Si consiglia PNG perché è un formato di compressione senza perdita di dati, ovvero comprimerà comunque la texture senza introdurre artefatti e supporta anche 16 bit.
