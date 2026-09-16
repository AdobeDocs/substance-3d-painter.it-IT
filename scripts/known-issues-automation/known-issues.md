---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/release-notes/know-issues.html"
breadcrumb-title: ""
description: Esamina i problemi noti per Substance 3D Painter per ricevere informazioni sulle limitazioni e sulle soluzioni alternative attuali nell'ultima versione.
helpx_creative_field: ""
helpx_description: Substance 3D Painter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Problemi noti
user-guide-description: ""
user-guide-title: ""
source-git-commit: a652271a4b12d9c27513ebc4d5974fa87da29580
workflow-type: tm+mt
source-wordcount: '855'
ht-degree: 0%
---

# Problemi noti

Questa pagina elenca tutti i problemi noti attivi presenti nella versione 12.1.5 di Substance 3D Painter:

* `[Baking]` AO errato su cubi semplici
* L&#39;interpretazione del suffisso `[Baking]` corrispondente per nome è errata
* Le cuciture Uv di `[Baking]` non vengono visualizzate dopo la reimportazione di mes
* `[Baking]` artefatti di tipo griglia con alcune impostazioni
* `[Baking]` Occlusione ambiente Ignora backface per nome trama non funziona
* `[Baking]` `[AMD]` Dispositivo perso durante la cottura al forno con trame poly alte e pesanti

* `[Substance]` Diversi errori ortografici nelle risorse
* `[Substance]` condizione di spazio vuoto interrotto per visibilità
* Il caricamento di `[Substance]` predefiniti per alcuni materiali richiede troppo tempo
* `[Substance]`: impossibile importare la risorsa con utilizzi misti

* `[Engine]` Errore durante l&#39;utilizzo di Smart Materials se il set di texture non include la porzione 1001
* `[Engine]` Colorazione con lo strumento Clona in canali normali non corretta
* La maschera Geometria `[Engine]` mostra artefatti ai bordi UV con livelli istanziati

* `[Color Management]` Associazioni incompatibili con il generatore non utilizzate nella maschera
* L&#39;output del filtro `[Color Management]` non viene considerato correttamente
* `[Color Management]` conversioni dello spazio cromatico HDR con ACE su Linux producono colori bloccati

* `[USD]` Assegnazione usda errata in alcuni casi
* `[USD]` La geometria USD esportata è scivolata lungo i bordi UV
* `[USD]` Blocco durante il caricamento di USDz non validi

* Le risorse `[Shelf]` ottengono l&#39;utilizzo errato se inserite in una cartella con un nome specifico
* `[Shelf]` `[Substance]` Dati utente non considerati per la generazione della miniatura di shelf

* `[Shader]` parametro &quot;camera_vp_matrix_inverse&quot; non riconosciuto
* Il canale utente 0 `[Shader]` non può sempre essere letto come sRGB con shader specifico

* `[Scripting]` `[Javascript]` Errore di battitura &quot;disabilitato&quot; durante la specifica del parametro di dithering nelle funzioni di esportazione
* `[Scripting]` `[Python]` Vari errori di battitura nel modulo substance_painter.project

* La fusione di `[Path]` Height di più percorsi può causare artefatti
* `[Path]` problema di visibilità della selezione quadrata blu

* Il progetto `[Single Channel View]` salvato nella visualizzazione colore di base appare più scuro dopo l&#39;aggiornamento della versione di Painter
* Il progetto `[Single Channel View]` salvato nella visualizzazione colore di base appare più scuro dopo l&#39;aggiornamento della versione di Painter

* `[gltf]`: impossibile aprire i file esportati tramite l&#39;Esportazione di Babilonia
* `[Displacement]` difetto durante il disegno
* `[Polygon Fill Tool]` Selezione errata con simmetria
* A volte `[2D view]` tratti non vengono visualizzati quando si disegna
* Impossibile scrivere `[Console]` simboli associati alla scelta rapida da tastiera
* `[LOG]` Messaggio di errore non corretto durante l&#39;esportazione non riuscita
* Lo stencil `[3D View]` non funziona con oggetti duplicati
* `[Resource updater]` Risorse diverse nello scaffale con lo stesso nome vengono lette come un&#39;unica risorsa
* `[Sample]` videocamera danneggiata nell&#39;esempio di anteprima
* `[Instancing]` `[Projection]` Quando si seleziona un&#39;istanza nel proj planare, viene selezionato un altro proj planare in un altro set di texture
* `[Slider]` Input numerici deselezionati quando il cursore esce dalla finestra
* `[Anchor point]` Riferimenti interrotti durante la copia e l&#39;incolla del contenuto della maschera
* `[Mesh export]` Non prendere in considerazione i nuovi nomi dei set di texture
* `[Anchor Points]` Colore errato quando utilizzato in Generator
* Il baker di mappe ID `[Bakers]` non prende in considerazione il materiale fisico 3ds Max 2021
* `[UV Tiles]` Nessun messaggio di errore sugli spazi UV sovrapposti con una trama specifica
* `[GLTF]` `[Crash]` La creazione di un progetto con file gltf compresso provoca un arresto anomalo
* `[UV Tile sequence]` mappe posizione non importate correttamente
* La maschera di combinazione per `[UVTiles]` Height non viene aggiornata con la maschera Porzione UV
* `[Import]` Impossibile importare il file obj con valori &quot;nan&quot;
* `[Export]` esportazioni GLTF con dimensioni errate
* Il nome `[Texture Set]` può essere vuoto
* `[Layer stack]` Copia nella maschera passa alla modalità materiale
* `[UI]` Errore di battitura nelle impostazioni del creatore pennelli
* `[Texture Set Settings]` Nome istanza shader errato dopo una ridenominazione
* Il metodo di fusione Colore e Saturazione di `[Blending]` cambia anche la luminosità
* `[Librairies]` La larghezza delle ricerche salvate e le finestre di filtro in base al percorso non vengono salvate se modificate
* `[Geometry mask]` Problema durante la reimportazione della trama e del livello istanza
* Spazio colore `[Color management]` non trovato quando manca il riquadro 1001
* spostamento `[Export mesh]` non esportato con porzioni UV specifiche impostate
* `[RedHat]` Problemi con il selettore colore
* Il menu di scelta rapida di `[Regression]` `[UI]` è troppo piccolo sullo schermo hd
* `[Resources]` Mappe mesh importate ignorate dall&#39;aggiornamento automatico
* L&#39;anteprima dello spazio per il mixaggio dei colori `[User Channels]` non è corretta
* La selezione della geometria `[Mask]` è ancora attiva dopo il passaggio alla modalità di esegue i baking
* `[Sonoma]` icone non visualizzate nei menu
* `[Polygon Fill]` La modifica dello spazio colore del colore di base non aggiorna il selettore colore
* `[UV Padding]` artefatti durante l&#39;aumento di texture da 4k a 8k all&#39;esportazione
* `[Performances]` Painter nasconde l&#39;utilizzo dell&#39;VRAM
* `[FBX]` problemi di scala
* È possibile selezionare `[Texture set list]` Porzioni UV contemporaneamente a un set di texture
* `[Viewport]` Ritardo del cursore nella parte inferiore della finestra della vista della modalità di esegue i baking
* Le risorse non quadrate vengono allungamento quando vengono utilizzate negli slot del canale del pennello
* Impossibile decodificare la sostanza
* Gli UV non perfettamente sovrapposti possono creare artefatti
* Normali mesh non valide con alcuni fbx
* La visualizzazione non viene aggiornata quando si cambia il canale interessato da un livello
* I progetti con un set di texture vengono riaperti in modalità Solo Colore di base
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

## Stabilità

* `[Crash]` Se si fa clic sull&#39;elenco Set di texture dopo la creazione del progetto non riuscita, viene generato un arresto anomalo
* `[Crash]` arresto anomalo di errore critico quando lo stesso progetto viene aperto due volte
* `[Crash]` Selezionare &quot;Esporta trama&quot; quando il caricamento della trama non è riuscito
* `[Crash]` Fare clic su &quot;Inizia a disegnare&quot; dopo aver provato ad aprire un vecchio progetto
* `[Crash]` La creazione di testi molto lunghi nella barra multifunzione può arresto anomalo
* `[Crash]` Ripristino della modalità di disegno dopo la perdita del dispositivo durante la esegue i baking
* `[Crash]` Esci da Painter dopo aver annullato l’esportazione delle mappe
* `[Crash]` Esportazione della trama con alcuni simboli speciali nel nome della fotocamera
