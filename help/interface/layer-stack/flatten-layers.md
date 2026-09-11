---
title: Appiattisci livelli
description: ''
helpx_description: "Substance 3D Painter"
helpx_url: "https://helpx.adobe.com/substance-3d-painter/interface/layer-stack/flatten-layers.html"
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '883'
ht-degree: 1%

---


# Appiattisci livelli

![](../../assets/v12_banner_flatten.jpg)

## Appiattisci livelli

La conversione dei livelli consente di comprimere in un singolo livello i dati visibili della texture di un gruppo selezionato. In questo modo è possibile semplificare la Pila livelli, migliorare le prestazioni e semplificare la gestione dei progetti.

>[!NOTE]
>
> Quando si utilizza la funzione Appiattisci, viene creato un nuovo livello, ma il gruppo originale di livelli non viene eliminato. Il gruppo sorgente è invece disattivato, lasciando la scelta di eliminarlo o in alternativa salvarlo come Materiale avanzato per la modifica successiva.

## Come ridurre a livello singolo

Per ridurre a livello singolo una serie di livelli:

1. Seleziona i livelli desiderati.
1. Utilizzare <b>CTRL + G (CMD + G) </b> per raggruppare la selezione.
1. Utilizza <b>CTRL + M (CMD + M)</b> per unire la selezione.

Puoi anche accedere a queste opzioni dal menu di scelta rapida, invece di utilizzare le scelte rapide da tastiera.

![](../../assets/v12_flatten_menu.jpg)

Quando i livelli vengono convertiti, viene creato un nuovo livello di riempimento con texture convertite e il gruppo sorgente viene disattivato.

## Appiattisci canali specifici

* Su un livello di riempimento, usa il pannello Proprietà per disattivare i canali che non desideri unire. Le informazioni non vanno perse quando i canali sono disattivati. Una volta appiattito il livello, puoi riattivare i canali e i dati saranno ancora presenti.
* Per i gruppi o i livelli di pittura, puoi utilizzare i metodi di fusione per disabilitare i canali:
  * Nella parte superiore della Pila livelli, seleziona il canale da disattivare.
  * Modificate il metodo di fusione del livello desiderato su &quot;Disattivato&quot;.
  * Per applicare lo stesso metodo di fusione a tutti i canali di un livello, fate clic con il pulsante destro del mouse sul metodo di fusione e selezionate &quot;Applica a tutti i canali&quot;.

## Esportare le mappe appiattite dalla pila di livelli

Utilizza <b>Esporta gruppo con unico livello in file</b> dal menu di scelta rapida nella Pila livelli per esportare rapidamente texture. Questa opzione è disponibile quando è selezionato un livello o un gruppo. Quando sono selezionati più livelli o gruppi, questi verranno gestiti come batch, come se ciascuno di essi fosse stato esportato uno alla volta.

>[!NOTE]
>
> Come per la funzione <b>Appiattisci gruppo </b>, i canali e i livelli vuoti o disabilitati non verranno esportati. Se viene utilizzata una maschera di geometria, vengono esportate solo le porzioni UV abilitate all&#39;interno della maschera di geometria.

### Gestione dei file

Quando si seleziona <b>Esporta gruppo con unico livello in file</b>, sarà possibile selezionare una posizione per i file esportati.

I nomi dei file esportati seguono lo schema indicato nel campo del nome file. Il modello di default è:

* <b>$textureSet\_$layerName\_$srcMap(.$udim)</b>

Con questo pattern, le mappe avranno il nome del set di texture, il nome del livello, il nome del canale e, se si tratta di un progetto di porzioni UV, il numero UDIM.

Se si modifica il pattern, questo sarà nuovamente disponibile alla successiva apertura della finestra.

### Proprietà file esportate

Le proprietà dei file esportati si basano sui seguenti valori al momento dell’esportazione:

* La risoluzione si basa sulla risoluzione impostata per le texture.
* La profondità di bit si basa sulla profondità di bit del canale nelle impostazioni del set di texture.

Le seguenti proprietà sono hardcoded e non possono essere modificate:

* Il riempimento è bloccato a 1 px.
* Il formato del file dipende dal canale esportato. Le mappe come height e normale di solito richiedono più profondità di bit e vengono esportate come EXR, mentre gli altri canali vengono esportati come PNG.
* Se viene esportata solo una maschera, potete selezionare il formato di esportazione.

## Come viene generato il livello unito?

La funzione appiattisci crea una bitmap per canale abilitato all&#39;interno di un nuovo livello di riempimento. La risoluzione si basa sulla risoluzione impostata per l’insieme di texture e la profondità di bit è determinata dalle relative impostazioni.

L’opzione Unisci livello funziona quando sono presenti dati di texture all’interno di un determinato canale. La conversione non funzionerà su un livello di pittura vuoto e invierà un messaggio di errore al registro se nella selezione non sono presenti dati.

Solo i livelli visibili e gli effetti possono essere convertiti. Se alcuni livelli del gruppo vengono disattivati quando il gruppo viene unito, gli effetti di questi livelli non verranno inclusi nel risultato unito.

### Livelli disabilitati

Solo i livelli visibili e gli effetti possono essere convertiti. Se alcuni livelli del gruppo vengono disattivati quando il gruppo viene unito, gli effetti di questi livelli non verranno inclusi nel risultato unito.

### Maschere di livello e maschere di geometria

Le maschere vengono convertite separatamente dai dati della texture. Ciò significa che, se si appiattisce un gruppo con una maschera, verranno generati sia un riempimento appiattito che una maschera appiattita.

Quando si utilizza una maschera di geometria, se solo alcune porzioni UV sono selezionate all&#39;interno della maschera di geometria, il livello appiattito manterrà questa selezione. Le porzioni UV che non sono state selezionate nella maschera di geometria sono considerate vuote e pertanto la loro texture non viene mantenuta nel risultato appiattito.

## Gestire i contenuti convertiti

>[!NOTE]
>
> Le immagini con unico livello vengono memorizzate nel file di progetto (.SPP). Ciò significa che avranno un impatto sulle dimensioni del file di progetto.

Alle immagini con unico livello vengono automaticamente aggiunti i tag &quot;appiattite&quot;, per facilitarne la ricerca nel pannello Risorse. Vengono anche memorizzati automaticamente nella categoria Ricerche salvate &quot;Livelli convertiti&quot;.

### Pulisci le immagini inutilizzate

La rimozione di immagini inutilizzate dal file di progetto può contribuire a schiarire le dimensioni del progetto. Nel pannello Risorse, potete eliminare le immagini dal menu di scelta rapida. In alternativa, per rimuovere tutte le immagini inutilizzate, utilizzare <b>File > Rimuovi risorse inutilizzate</b>. Tenete presente che questa operazione non comporta solo l&#39;eliminazione delle immagini convertite, ma anche di tutte le risorse che non vengono utilizzate nella Pila livelli, negli slot delle mappe di backup o altrove nell&#39;interfaccia utente.
