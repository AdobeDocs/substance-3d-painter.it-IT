---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/presets/creating-particles-presets/creating-a-new-particle-script.html"
breadcrumb-title: ''
description: Scoprite come creare un nuovo script per particelle in Substance 3D Painter per definire il comportamento e gli effetti personalizzati del pennello per particelle.
helpx_creative_field: ""
helpx_description: Painter > Painting > Presets > Creating particles presets > Creating A New Particle Script
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creazione Di Un Nuovo Script Particelle
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '728'
ht-degree: 0%

---


# Creazione Di Un Nuovo Script Particelle

Scarica il pacchetto PopcornFX preimpostato: [Modelli\_EmitterReceiver.pkkg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/spdoc/files/67403778/68419585/1/1411557944000/templates-emitterreceiver.pkkg)

Questo pacchetto è un &quot;kit di avvio&quot; che contiene un emettitore e un ricevitore che modificheremo e importeremo in Substance 3D Painter.

## Installazione di Popcorn Fx

Avvia l’editor PopcornFX, crea un nuovo progetto e aprilo.

Nel tuo progetto, fai clic con il pulsante destro del mouse su un&#39;area vuota e seleziona &quot;Importa pacchetto Popcorn&quot;. Quindi scegli &quot;Modelli\_EmitterReceiver.pkkg&quot;.

Ora dovresti avere:

* Un sistema di particelle &quot;\_Emitter&quot; che è un modello base di un emettitore.
* Un sistema di particelle &quot;\_Receiver&quot; che è un modello di base di un ricevitore.
* Una trama sferica usata come sfondo predefinito della scena

&quot;\_Emitter&quot; e &quot;\_Receiver&quot; sono già &quot;Painter ready&quot;. Sono già stati configurati con i necessari evolutori, campi, sfondi, ecc...

## Importare la trama

PopcornFX supporta solo **FBX**, assicurati di esportare la trama in questo formato. Durante la fase di esportazione, controllate le dimensioni della trama per provare a inserirle nelle unità corrette in &quot;mondo reale&quot;.

Copiatelo e incollatelo nella cartella &quot;trame&quot; del vostro progetto (in PopcornFX, potete fare clic con il pulsante destro del mouse sulla cartella &quot;trame&quot; e selezionare &quot;Apri percorso file&quot;).

Torna all&#39;editor, apri la trama (fai doppio clic su di essa) e fai clic su &quot; **Build** &quot;. Chiudere la finestra e salvare le modifiche.

## Editing di emettitori/ricevitori

Duplicheremo i sistemi di particelle esistenti e li adatteremo per tenere correttamente conto della nuova trama.

Fate clic con il pulsante destro del mouse sul sistema di particelle &quot;\_Emitter&quot; (nella cartella &quot;Particelle&quot;), quindi selezionate &quot;Clona&quot; (o &quot;Duplica&quot;) per creare il vostro emettitore.

Apritelo e, nella finestra &quot;Vista albero particelle&quot; (in basso a sinistra), selezionate &quot; **Livello\_Modello**&quot; che dovrebbe trovarsi in: &quot;Proprietà editor => Sfondo => Livelli 3D&quot;.

Quindi, nella finestra &quot;Proprietà nodo&quot; sostituire &quot;dummymesh.fbx&quot; con il modello. Salvate la modifica (File => Salva) e chiudete la finestra emettitore.

Ora **clona &quot;\_Receiver** **&quot;** (nella cartella &quot;Particelle&quot;) per creare un ricevitore personalizzato da questo.

Apritela e, come per l&#39;emittente, sostituite la trama fittizia con il modello in &quot;Layer\_Model&quot;. Abbiamo **modificato la trama** **visualizzata sullo schermo** , ma dobbiamo anche modificare **la trama** **utilizzata dalle particelle**.

A tale scopo, nella finestra &quot;Vista albero particelle&quot;, fare clic su &quot; **Forma** &quot; che dovrebbe trovarsi in: &quot;Effetto particelle => Spawner => Livello\_1 => Campionatori => Trama&quot;.

Sostituire quindi &quot;MeshResource&quot; con il modello.

Una volta fatto, c&#39;è un&#39;ultima cosa da fare: dobbiamo &quot;collegare&quot; l&#39;emettitore e il ricevitore con quello che abbiamo appena creato.

Nell&#39;albero del ricevitore, selezionare &quot;Proprietà editor&quot;, quindi selezionare l&#39;emettitore in &quot;OverSpawnEffect&quot;. Salvare il ricevitore.

Aprire l&#39;emettitore (quello precedentemente duplicato) e nella finestra &quot;Vista albero particelle&quot;, fare clic su &quot;Eventi&quot; che dovrebbe trovarsi in: &quot;Effetto particelle => Spawner&quot;. Quindi sostituire il ricevitore con il ricevitore facendo clic su &quot;Extern&quot;.\
Operazione completata. Ora, se selezioni la vista 3D (del tuo emettitore o ricevitore), puoi creare particelle premendo il pulsante &quot;space&quot;.

## Facoltativo: modificare il comportamento del ricevitore

Aprite il ricevitore e nella finestra &quot;Vista albero particelle&quot; selezionate &quot; CParticleEvolver\_Script &quot; (il primo dedicato a voi :)) che dovrebbe trovarsi in : &quot;Particle Effect => Layer\_1 => State\_0&quot;.

Nella finestra &quot;Editor nodo specializzato&quot;, nella funzione, aggiungere &quot;Life = 0.5;&quot; per modificare la durata delle particelle. Quindi usa la scelta rapida &quot;Ctrl+s&quot; per salvare lo script. Dovresti essere in grado di notare la differenza nella vista 3D.

Per ulteriori informazioni sul suo funzionamento, visita il seguente collegamento:

<http://wiki.popcornfx.com/index.php/Main_Page>

## Importazione di emettitore/ricevitore in Substance 3D Painter

In Substance 3D Painter, fai &quot;File&quot; > &quot;Importa particelle&quot; oppure Ctrl-Alt-R, quindi scegli l’emettitore e il ricevitore (entrambi in formato .pkfx) nel tuo pacchetto.

Substance 3D Painter rileverà automaticamente i requisiti (campi di particelle, eventi OnCollide) per decidere se il pkfx è un emettitore, un ricevitore o nulla di compatibile.

Ora dovresti vedere l&#39;emettitore/ricevitore nello scaffale (nelle schede &quot;Emettitori&quot; e &quot;Ricevitori&quot;).

Per usarli, è necessario prima fare clic sul pulsante &quot;Attiva/disattiva particelle&quot;.

Quindi, nella finestra &quot;Strumento&quot;, in &quot;Fisica&quot; avrete la possibilità di selezionare l&#39;emettitore (per sostituire &quot;predefinito\_emettitore&quot;) e il ricevitore (per sostituire predefinito\_ricevitore).

Ora è possibile fare clic con il pulsante destro del mouse nella finestra &quot;Strumento&quot; e salvare lo strumento.
