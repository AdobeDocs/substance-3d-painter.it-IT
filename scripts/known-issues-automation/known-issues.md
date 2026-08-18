---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/release-notes/know-issues.html"
breadcrumb-title: ''
description: Esamina i problemi noti per Substance 3D Painter per ricevere informazioni sulle limitazioni e sulle soluzioni alternative attuali nell'ultima versione.
helpx_creative_field: ""
helpx_description: Substance 3D Painter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Problemi noti
user-guide-description: ''
user-guide-title: ''
source-git-commit: 99ba6e8d891dab9cebbf6035a6850bab331e7472
workflow-type: tm+mt
source-wordcount: '905'
ht-degree: 0%

---


# Problemi noti

Questa pagina elenca tutti i problemi noti attivi presenti nella versione 12.1.0 di Substance 3D Painter:

* `[Engine]` Errore durante l&#39;utilizzo di Smart Materials se il set di texture non include la porzione 1001
* `[Engine]` Colorazione con lo strumento Clona in canali normali non corretta
* La maschera Geometria `[Engine]` mostra artefatti ai bordi UV con livelli istanziati
* La modalità &quot;Vicina spazio 3D&quot; del riempimento UV `[Engine]` non funziona correttamente su triangoli sottili
* Il risultato del punto di ancoraggio `[Engine]` non viene visualizzato tra una maschera e un canale di colore

* `[Baking]` AO errato su cubi semplici
* L&#39;interpretazione del suffisso `[Baking]` corrispondente per nome è errata
* Le cuciture Uv di `[Baking]` non vengono visualizzate dopo la reimportazione di mes
* `[Baking]` artefatti di tipo griglia con alcune impostazioni

* `[Substance]` Diversi errori ortografici nelle risorse
* `[Substance]` condizione di spazio vuoto interrotto per visibilità
* Il caricamento di `[Substance]` predefiniti per alcuni materiali richiede troppo tempo
* `[Substance]`: impossibile importare la risorsa con utilizzi misti

* `[Color Management]` Associazioni incompatibili con il generatore non utilizzate nella maschera
* L&#39;output del filtro `[Color Management]` non viene considerato correttamente
* `[Color Management]` conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

* Le risorse `[Shelf]` ottengono l&#39;utilizzo errato se inserite in una cartella con un nome specifico
* `[Shelf]` `[Substance]` Dati utente non considerati per la generazione della miniatura di shelf

* `[Shader]` parametro &quot;camera_vp_matrix_inverse&quot; non riconosciuto
* Impossibile leggere sempre il canale utente 0 `[Shader]` come sRGB con uno shader specifico

* `[Scripting]` `[Javascript]` Errore di battitura &quot;disabilitato&quot; durante la specifica del parametro di dithering nelle funzioni di esportazione
* `[Scripting]` `[Python]` Vari errori di battitura nel modulo substance_painter.project

* Il progetto `[Single Channel View]` salvato nella visualizzazione a colori di base sembra più scuro dopo l&#39;aggiornamento della versione di Painter
* Il progetto `[Single Channel View]` salvato nella visualizzazione a colori di base sembra più scuro dopo l&#39;aggiornamento della versione di Painter

* `[gltf]` Impossibile aprire i file esportati tramite Babylon Exporter
* `[Displacement]` difetto durante il disegno
* `[Polygon Fill Tool]` Selezione errata con simmetria
* A volte `[2D view]` tratti non vengono visualizzati quando si disegna
* Impossibile scrivere `[Console]` simboli associati al collegamento
* `[LOG]` Messaggio di errore non corretto durante l&#39;esportazione non riuscita
* Lo stencil `[3D View]` non funziona con oggetti duplicati
* `[Resource updater]` Risorse diverse nello scaffale con lo stesso nome vengono lette come un&#39;unica risorsa
* `[Sample]` videocamera danneggiata nell&#39;esempio di anteprima
* `[Instancing]` `[Projection]` Quando si seleziona un&#39;istanza in un proj planare, viene selezionato un altro proj planare in un altro set di texture
* `[Slider]` Input numerici deselezionati quando il cursore esce dalla finestra
* `[Anchor point]` Riferimenti interrotti durante la copia e l&#39;incolla del contenuto della maschera
* `[Mesh export]` Non prendere in considerazione i nuovi nomi dei set di texture
* `[Anchor Points]` Colore errato quando utilizzato in Generator
* Il baker di mappe ID `[Bakers]` non prende in considerazione il materiale fisico 3ds Max 2021
* `[UV Tiles]` Nessun messaggio di errore sugli spazi UV sovrapposti con una trama specifica
* `[GLTF]` `[Crash]` La creazione di un progetto con file gltf compresso causa un arresto anomalo
* `[UV Tile sequence]` mappe posizione non importate correttamente
* La maschera di combinazione per `[UVTiles]` Height non viene aggiornata con la maschera di porzione UV
* `[Import]` Impossibile importare il file obj con valori &quot;nan&quot;
* `[Export]` esportazioni GLTF con dimensioni errate
* Il nome `[Texture Set]` può essere vuoto
* `[Layer stack]` Copia nella maschera passa alla modalità materiale
* `[UI]` Errore di battitura nelle impostazioni del creatore pennelli
* `[Texture Set Settings]` Nome istanza dello shader errato dopo una ridenominazione
* Il metodo di fusione Colore e Saturazione di `[Blending]` cambia anche la luminosità
* `[Librairies]` La larghezza delle ricerche salvate e le finestre di filtro in base al percorso non vengono salvate se modificate
* `[Geometry mask]` Problema durante la reimportazione della trama e del livello istanza
* Spazio colore `[Color management]` non trovato quando manca il riquadro 1001
* spostamento `[Export mesh]` non esportato con porzioni UV specifiche impostate
* `[RedHat]` Problemi con il selettore colore
* Il menu di scelta rapida di `[Regression]` `[UI]` è troppo piccolo sullo schermo hd
* `[Resources]` Mappe mesh importate ignorate dall&#39;aggiornamento automatico
* L&#39;anteprima dello spazio per il mixaggio dei colori `[User Channels]` non è corretta
* La selezione della geometria `[Mask]` è ancora attiva dopo il passaggio alla modalità di cottura in forno
* `[Sonoma]` icone non visualizzate nei menu
* La fusione di `[Path]` Height di più percorsi può causare artefatti
* `[USD]` Assegnazione usda errata in alcuni casi
* `[Polygon Fill]` La modifica dello spazio colore di base non aggiorna il selettore colore
* `[Paint Skew]` lo strumento selezionato in inclinazione colore rimane selezionato dopo il passaggio alla modalità Pittura
* Il selettore `[Color Picker]` rimane aperto dopo la modifica dello strumento
* `[UV Padding]` artefatti durante l&#39;upscaling della texture da 4k a 8k all&#39;esportazione
* Le impostazioni di `[Baking Common Settings]` Cage Distance non aggiornano la visualizzazione di cage wireframe e shader
* `[Send to Photoshop]` non riesce a esportare la maschera di livello
* `[Skew Baking]` La correzione dell&#39;inclinazione si interrompe quando si disegna e si annulla
* L&#39;interazione del riquadro di visualizzazione `[Projection Tool]` è bloccata dallo strumento di proiezione
* Le risorse non quadrate vengono dilatate quando vengono utilizzate negli slot del canale del pennello
* Impossibile decodificare la sostanza
* Gli UV non perfettamente sovrapposti possono creare artefatti
* Normali mesh non valide con alcuni fbx
* La visualizzazione non viene aggiornata quando si cambia il canale interessato da un livello
* Il progetto con un set di texture viene riaperto in modalità Solo colore base
* L&#39;interfaccia utente del pulsante del canale nelle proprietà Materiale/pittura può essere interrotta
* L’ordine dei canali nelle Proprietà può essere interrotto
* I tratti creati in L16F e RBG16F possono mostrare artefatti
* Il comportamento del pulsante Ripristina non interagisce con il tasto di blocco nelle impostazioni della fotocamera
* L’esportazione di Photoshop ignora la selezione della maschera di geometria
* La Pendenza della sfocatura e il filtro Altera dipendono dalla risoluzione impostata della texture
* Le mappe senza nomi vengono create all’esterno della cartella di esportazione
* Lo stencil non viene aggiornato quando si modifica il pennello predefinito
* Problema di trasparenza nei file PSD
* Le modifiche dei parametri del pennello dalla barra degli strumenti contestuale non vengono visualizzate nella cronologia
* Impossibile rinominare o eliminare i predefiniti di esportazione se li hai già eliminati e ricreati in questa sessione
* La mappatura dei canali in alcuni casi non funziona per l’anteprima dello strumento di proiezione
* L’apertura e il salvataggio di alcuni progetti può richiedere più tempo del solito

## Stabilità

* `[Crash]` Se si fa clic sull&#39;elenco Set di texture dopo una creazione del progetto non riuscita, si verifica un arresto anomalo
* `[Crash]` Errore critico: arresto anomalo quando lo stesso progetto viene aperto due volte
* `[Crash]` Selezionare &quot;Esporta trama&quot; quando il caricamento della trama non è riuscito
* `[Crash]` Fare clic su &quot;Inizia a disegnare&quot; dopo aver provato ad aprire un vecchio progetto
* `[Crash]` La creazione di testi molto lunghi nella barra multifunzione può arrestarsi in modo anomalo
* `[Crash]` Ripristino della modalità di disegno dopo la perdita del dispositivo durante la cottura al forno
* `[Crash]` Esci da Painter dopo aver annullato l’esportazione delle mappe
* `[Crash]` Esportazione della trama con alcuni simboli speciali nel nome della fotocamera
* `[Crash]` L&#39;eliminazione di un canale in modalità di visualizzazione Maschera causa un arresto anomalo
* `[Crash]` Alcune Substance possono causare un arresto anomalo durante il rendering
* `[Crash]` reimporta trama in modalità cottura al forno
* `[Crash]` Il ricaricamento di più trame può causare un arresto anomalo
