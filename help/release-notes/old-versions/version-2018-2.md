---
breadcrumb-title: ""
description: Consulta le note sulla versione per Substance 3D Painter versione 2018.2 per scoprire le nuove funzioni, i miglioramenti e le correzioni di bug.
title: Versione 2018.2
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '2346'
ht-degree: 0%
---

# Versione 2018.2

**Substance Painter 2018.2** aggiunge funzionalità attese da molto tempo, come la pittura a dispersione sottosuolo, che semplificano ulteriormente la creazione di texture.

Data di pubblicazione: *2 agosto 2018*

## Caratteristiche principali

### Dispersione sotto la superficie

![](../../assets/changelog-sss.jpg)

**La dispersione sottosuperficiale** è ora supportata nella finestra della vista **in tempo reale** e con il **modulo di rendering Iray**.\
La dispersione sotto la superficie è un meccanismo di luce quando penetra un oggetto o una superficie. Invece di essere riflessa, come con le superfici metalliche, una parte della luce viene assorbita dal materiale e poi **dispersa all&#39;interno**. Molti materiali nella vita reale hanno dispersione sottosuperficiale come pelle o cera.

L’implementazione dell’effetto Subsurface di Adobe è molto simile a quella delle implementazioni in tempo reale di altri motori di gioco e di altri moduli di rendering offline. Semplificazione della creazione di texture di dispersione da utilizzare in altre applicazioni.

![](../../assets/comparison-1.jpg){width="650px"}

Sopra è riportato un esempio con la ben nota risorsa Digital Emily 2. Grazie all&#39;USC Institute for Creative Technologies e ai membri del progetto Wikihuman per averci permesso di dimostrare i nostri rendering con le risorse Digital Emily 2.\
(Si noti che questo confronto è stato fatto in condizioni di illuminazione simili ma non precise, il che potrebbe spiegare le differenze visive).

Per aggiungere la dispersione dei sottofondi in un progetto, effettuate le seguenti operazioni:

1. Passate alla finestra **Impostazioni schermo** e **attivate** l&#39;impostazione **Dispersione sottosuperficie**.
1. Aggiungi un canale &quot;**Dispersione**&quot; nel set di texture corrente
1. Usa un livello di riempimento o **una pittura in bianco** nel nuovo canale per **rivelare** l&#39;effetto della superficie inferiore nella finestra della vista.

Una procedura più dettagliata è disponibile nella [documentazione sulla dispersione sottosuperficie](../../features/subsurface-scattering/subsurface-scattering.md).

>[!NOTE]
>
> Per supportare la dispersione dei sottofondi nella finestra della vista in tempo reale, gli **shader** nei progetti devono essere **aggiornati**.\
> Per gli shader personalizzati, consultare la documentazione disponibile nel **menu della guida** per sapere cosa è cambiato nell&#39;**API shader**.

### Manipolatori per livelli di riempimento

![](../../assets/changelog-manipulator.png)

I controlli dei livelli di riempimento sono stati migliorati per offrire manipolatori. Ora è più facile posizionare e controllare con precisione le proiezioni di riempimento.

Quando si utilizza la **Proiezione UV**, nella **vista 2D** verrà visualizzato un manipolatore:

* Facendo clic su **fuori**, il manipolatore **lo ruoterà**.
* Facendo clic sul **quadrato** alle **cornici**, verrà **ridimensionato**.
* Facendo clic su **all&#39;interno**, il manipolatore **tradurrà**.
* Utilizza **CTRL** per modificare più angoli nella **simmetria**.
* Usate **MAIUSC** per **vincolare** una trasformazione (traslazione, rotazione o scala).\
  ![](../../assets/manipulator-uv.gif)

Quando si utilizza la **proiezione tripla Planare**, nella **vista 3D** verrà visualizzato un manipolatore:

* Il cubo tratteggiato rappresenta la proiezione globale
* Utilizza la scelta rapida da tastiera da tastiera **W**, **E** o **R** per passare dalla modalità **Traduci**, **Ruota** e **Scala**.
* Utilizza la scelta rapida da tastiera da tastiera **T** per passare dall&#39;orientamento locale a quello globale per il manipolatore.
* Utilizzate **MAIUSC** per **vincolare** la trasformazione.
* La proiezione del cubo trivalente può essere modificata anche nelle proprietà avanzate del livello di riempimento:\
  ![](../../assets/fill-properties-triplanar.png)\
  ![](../../assets/manipulator-3d-optim.gif)

Anche la barra degli strumenti contestuale nella parte superiore della finestra della vista verrà adattata in base alla modalità di proiezione corrente, offrendo strumenti e controlli aggiuntivi:

![](../../assets/contextual-toolbar-manipulator.png)

Per ulteriori informazioni, consulta la [documentazione del livello di riempimento](../../painting/fill-projections/fill-projections.md).

### Supporto non quadrato e non di fresatura per lo strumento Stencil e Proiezione

![](../../assets/non-square-stencil.jpg)

Il parametro dello stencil e lo strumento di proiezione sono stati migliorati per supportare risoluzioni non quadrate e comportamenti non di fresatura.\
Per impostazione predefinita, il parametro predefinito è ora impostato su non fatturazione. Questo parametro può essere modificato nelle proprietà dello strumento:

![](../../assets/tilling-parameter-stencil.png)

La modalità di fatturazione può essere impostata come segue:

* **Nessun Affiancamento** (impostazione predefinita)
* **Affiancamento orizzontale**
* **Affiancamento verticale**
* **Affiancamento H e V** (comportamento precedente)

Questo nuovo parametro può essere salvato in uno strumento o in un pennello predefinito, per facilitarne la condivisione con contenuti personalizzati.

>[!NOTE]
>
> * Il rapporto di proiezione si adatterà anche con i file di Substance che producono risoluzioni non quadrate. Il rapporto verrà calcolato direttamente dal nodo di output.
> * Con lo strumento proiezione, se più canali hanno rapporti diversi, il primo rapporto trovato verrà applicato a tutti gli altri canali.

### Importazione e gestione delle telecamere

![](../../assets/camera-import.png)

Ora è possibile **importare fotocamere personalizzate** all&#39;interno di Substance Painter insieme all&#39;importazione della trama.\
Le videocamere possono essere selezionate **per esaminarle** nella **finestra della vista 3D** e utilizzate **per eseguire il rendering in Iray**.

Per ulteriori informazioni, consultare la [documentazione sulla gestione della fotocamera](../../interface/viewport/camera-management.md).

Per **importare le fotocamere** in un progetto:

1. Esporta la trama per il progetto con le fotocamere nello stesso file (con un formato supportato come FBX, Alembic o glTF)
1. Selezionare le impostazioni &quot;Importa fotocamere&quot; nella [finestra nuovo progetto](../../getting-started/project-creation.md) (o nella [configurazione progetto](../../interface/project-configuration.md)).\
   ![](../../assets/new-project-cameras.png)
1. Passare alla fotocamera desiderata con il menu a discesa nella finestra della vista o utilizzando le impostazioni in [Impostazioni schermo](../../interface/display-settings/camera-settings.md).\
   ![](../../assets/cmaera-select-viewport.png)

Le impostazioni della fotocamera nella finestra Impostazioni schermo sono state estese per controllare le proprietà della fotocamera.\
È possibile **passare** da una videocamera all&#39;altra, visualizzarne le **proporzioni** e **bloccare** le proprietà per evitare di modificarle. È possibile utilizzare un pulsante di ripristino per ripristinare i valori iniziali della fotocamera.

![](../../assets/camera-properties-2.png)

Si prende in considerazione anche il fotogramma della fotocamera (e il suo cancello), rendendo possibile la visualizzazione e la pittura attraverso un punto di vista molto specifico. Il fotogramma e il gate vengono visualizzati nel riquadro di visualizzazione 3D e la relativa opacità può essere controllata nelle **Impostazioni del riquadro di visualizzazione** dalla finestra [Impostazioni schermo](../../interface/display-settings/camera-settings.md):

![](../../assets/camera-gate.png)

### Pila livelli miglioramenti comportamento

* **Trascina materiali e Materiali avanzati sulla mappa ID:**\
  È stato migliorato il trascinamento del contenuto dallo scaffale alla finestra della vista. Premendo **CTRL** durante il trascinamento di un materiale, è ora possibile scegliere il colore ID da utilizzare come maschera.\
  Una maschera nera con un effetto di selezione colore verrà aggiunta al nuovo livello creato nella Pila livelli. Se lo stesso materiale viene trascinato su un altro colore ID, il livello esistente viene aggiornato e i colori ID vengono combinati.\
  ![](../../assets/id-drop.gif)
* **Pila livelli scorrimento trascinamento :**\
  Trascinare i livelli intorno alla Pila livelli ora ha una piccola finestra.\
  Quando una risorsa o un livello viene trascinato vicino ai bordi della finestra della Pila livelli, inizierà automaticamente a scorrere il relativo contenuto.\
  ![](../../assets/layer-drag.gif)

### Importazione mesh glTF e Alembic

![](../../assets/logo-mesh-import.png)

Ora sono supportati nuovi formati di file per l’importazione di trame e la creazione di nuovi progetti:

* **glTF**: questo formato era già disponibile durante l&#39;esportazione di texture e può essere utilizzato durante l&#39;importazione. Se un file glTF contiene texture, queste verranno importate e inserite nella Pila livelli (per il flusso di lavoro metallizzato/rugosità).
* **Alembic**: questo formato è ampiamente utilizzato nel settore VFX / Animazione per trasferire le trame.

>[!NOTE]
>
> Substance Painter non consente di controllare quale fotogramma di animazione importare al momento.\
> Ciò significa che quando si esporta un file Alembic, il fotogramma di riferimento da utilizzare per la pittura sulla risorsa deve essere già impostato.

### Miglioramenti dell’integrazione Substance

![](../../assets/integration.png)

L&#39;integrazione di Substance in Substance Painter è stata migliorata con richieste attese da tempo:

* <b>Visibile Se:</b>\
  &quot;Visible if&quot; è un&#39;ottima funzione del formato di file di Substance che permette di nascondere i parametri in base alle condizioni.\
  Questa funzione fornisce un elenco più chiaro di parametri e impostazioni contestuali, fornendo in generale materiali e filtri più facili da usare.\
  Per ulteriori informazioni, consulta la [documentazione del Substance Designer](https://experienceleague.adobe.com/en/docs/substance-3d-designer/home).\
  ![](../../assets/visible-if.gif)
* I **predefiniti di Substance** predefiniti di Substance rappresentano un modo semplice per fornire modifiche avanzate e variazioni dei materiali. Molti materiali in [Substance Source](https://source.allegorithmic.com) sono predefiniti, quindi prova!\
  Se un file di Substance contiene uno o più predefiniti, sarà disponibile un nuovo menu a discesa nell’elenco dei parametri. Seleziona il predefinito da applicare per aggiornare i parametri.\
  ![](../../assets/presets.png)
* **Substance attributi**\
  Gli attributi di Substance vengono ora visualizzati nell’interfaccia, per facilitare il recupero delle informazioni su un file specifico.\
  Gli attributi possono essere visualizzati in due posizioni diverse: sopra i parametri nella finestra delle proprietà o facendo clic con il pulsante destro del mouse su una risorsa nello scaffale.\
  ![](../../assets/attributes.png) ![](../../assets/attributes-shelf.png)

### Nuovo progetto di esempio &quot;Jade Toad&quot;

![](../../assets/toad-samle.jpg)

Un nuovo progetto di esempio denominato &quot;**JadeToad**&quot; è ora incluso in Substance Painter. Per impostazione predefinita, in questo progetto di esempio è attivato l&#39;effetto **Dispersione sottosuperficie**.\
Per trovare il progetto, utilizza la voce di menu **File** > **Apri campione...**.

## Note sulla versione

### 2018.2.3

(Pubblicato il 25 settembre 2018)

**&#x200B;**&#x200B;Corretto:**&#x200B;**

* [vista 2D] Il vista 2D è interrotto con alcune trame durante la creazione di un nuovo progetto
* [Arresto anomalo] Il passaggio da Proiezione UV a proiezione triplanari porta a un arresto anomalo
* [RayCollider] Più arresti anomali dovuti a &quot;RayCollider&quot;
* [Strumento] Quando si cambia livello, le proprietà del pennello modificate vengono perse
* Le impostazioni del pennello vengono ripristinate quando si passa alla gomma

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 2018.2.2

(Pubblicato l&#39;11 settembre 2018)

**Aggiunto:**

* Riepilogo: correzione rapida con aggiornamento dei contenuti, nuove funzionalità di scripting e possibilità di disattivare l&#39;aggiornamento automatico
* [Content]&#x200B;[Shelf] Aggiungi un predefinito Ripiano incarnato
* [Content]&#x200B;[shelf] Conversione di 19 normali cutanee in materiali per la dispersione sottosuperficiale
* [Scripting] Crea un modello di progetto da un progetto aperto
* [Scripting] Ottenere/impostare le impostazioni di esportazione di un progetto aperto
* [Updates] Consente di disattivare la finestra a comparsa Aggiornamento automatico da impostazioni e variabile di ambiente
* [Aggiornamenti] Non visualizzare fino alla versione successiva nella finestra a comparsa con aggiornamenti per la manutenzione

**Corretto:**

* [Fotocamera] Zoom errato passando da ortografica a Prospettiva
* [Display] Alcune mappe vengono visualizzate in modalità lineare anziché sRGB
* [Finestre di visualizzazione] Lo stato attivo della trama non funziona correttamente
* [vista 2D] Il progetto con la fotocamera rotta ha sparito i proiettili UV
* [SSS]&#x200B;[Tooltip] nel registro vengono visualizzate le descrizioni degli strumenti per la dispersione delle superfici
* Alcuni progetti non possono essere aperti in 2018.2 e il messaggio di errore non può salvare un pacchetto substance null
* [Maschera] Il colore dello strumento Pittura può bloccarsi in alcuni casi quando si lavora su una maschera
* [Materiale] Mappe non visualizzate in situazioni specifiche
* manipolatore [Proj]&#x200B;[Tools] attivo con un generatore
* [Substance] Gruppi di parametri Substance mancanti
* [Scripting] Nome software errato nella documentazione
* [UDIM] Nessuna informazione nel registro sulle conchiglie UV su più porzioni UV

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 2018.2.1

(Pubblicato il 3 agosto 2018)

**Corretto:**

* Parametri shader di dispersione sottosuperficie mancanti da progetti di aggiornamento

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows

### 2018.2

(Pubblicato il 2 agosto 2018)

**Aggiunto:**

* Riepilogo: Versione estate, Supporto per la dispersione sotto la superficie, miglioramenti a livello di proiezione e riempimento, importazione e selezione della fotocamera, supporto di Alembic/glTF, trascinamento sulla mappa ID, supporto migliorato del formato di Substance e nuovi contenuti
* [SSS]&#x200B;[Viewport]&#x200B;[Iray] Dispersione sottosuperficie generica
* [SSS] Sincronizza i parametri di dispersione MDL e subsuperficiale
* [SSS] È stato aggiunto un nuovo canale in scala di grigi denominato &quot;Scattering&quot;
* [SSS]&#x200B;[Impostazioni Shader] Parametro del tipo di dispersione per la dispersione del sottosuolo (incarnato o traslucido)
* [SSS]&#x200B;[Impostazioni Shader] Parametro della scala di dispersione per la dispersione del sottosuolo
* [SSS]&#x200B;[Impostazioni Shader] Parametro colore di dispersione per la dispersione del sottosuolo
* [SSS]&#x200B;[Impostazioni schermo] Conteggio dei campioni di dispersione per la dispersione sotto la superficie
* [Shader]&#x200B;[Iray] Integra MDL di dispersione sottosuperficiale per Iray
* [Shader] Aggiornamento di Shader tramite il programma di aggiornamento delle risorse
* [Shader] Aggiornamento dell&#39;API del log delle modifiche e della documentazione
* [Proprietà utensile]&#x200B;[Proj] Nuovi parametri per la proiezione triplanare
* [Finestra vista]&#x200B;[Proj] Controlla le proprietà del livello di riempimento nella vista 3D direttamente con i manipolatori (proiezione triplanare)
* [Shortcuts]&#x200B;[Proj] Nuove scelte rapide Q, W, E, R, T per manipolatori di proiezione triplanari
* [Riquadro di visualizzazione]&#x200B;[Proj] Controlla le proprietà del livello di riempimento direttamente nei Vista 2D con i manipolatori (Proiezione UV)
* [Shortcuts]&#x200B;[Proj] Nuova scelta rapida da tastiera Q per manipolatori Proiezione UV
* [Barra degli strumenti contestuale]&#x200B;[Proj] Controlla manipolatori di proiezione triplanari
* [Barra degli strumenti contestuale]&#x200B;[Proj] manipolatori di Proiezioni UV di controllo
* [Proprietà strumento] Disattiva Affiancamento texture con lo strumento proiezione e stencil
* [Stencil] Utilizzare immagini non quadrate con lo strumento di proiezione/stencil
* [Stencil] Consenti il controllo della modalità Affiancamento nella finestra Proprietà
* [Stencil] Lo zoom non è centrato su uno stencil non Affiancamento
* [Fotocamere] Importa fotocamere da Maya, Max, Blender, Modo, DAE
* [Fotocamere]&#x200B;[Finestra vista] Selezionare e controllare le videocamere importate nella finestra della vista
* [Fotocamere]&#x200B;[Iray] Seleziona e controlla le videocamere importate in Iray
* [Fotocamere]&#x200B;[UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] &quot;Importa fotocamere&quot; è selezionato per impostazione predefinita
* [Videocamere]&#x200B;[Scelte rapide] Aggiungete le scelte rapide &quot;&lt;&quot; e &quot;>&quot; per passare da una videocamera all’altra
* [Fotocamere]&#x200B;[Finestra vista] Aggiungere un fotogramma nella finestra della vista
* [Fotocamere]&#x200B;[Impostazioni finestra vista] Controllo dell&#39;opacità del fotogramma
* [Fotocamere]&#x200B;[Impostazioni fotocamera] lunghezza focale massima a 500 mm
* [Fotocamere]&#x200B;[Impostazioni videocamera] Rapporto di esposizione
* [Fotocamere]&#x200B;[Impostazioni fotocamera] Aggiungi un&#39;opzione di blocco
* [Fotocamere]&#x200B;[Impostazioni fotocamera] Aggiungi un&#39;opzione di ripristino
* [Cameras]&#x200B;[Impostazioni fotocamera] Aggiungi attributo distanza focale
* [glTF] Importazione di un file glTF
* [glTF] Importa mapping occlusione ambientale
* [Alembic] Importa fotogramma Alembic 1 con geometria statica
* [Ripiano] Trascina i materiali direttamente sulla trama utilizzando mappe ID con un modificatore (CTRL/Comando)
* [Pila livelli] Creazione automatica della maschera ID con trascinamento dei materiali sulla trama con mappe ID
* [Pila livelli] Scorrimento automatico dei livelli con trascinamento sulla Pila livelli
* [UI]&#x200B;[Proprietà strumento] Predefinito di Esposizione Substance
* [UI]&#x200B;[Menu?] Miglioramento del menu?
* [UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] Riorganizzazione della finestra
* [UI]&#x200B;[Nuovo progetto]&#x200B;[Configurazione progetto] Sostituisci il termine &quot;Trama&quot; con &quot;File&quot;
* [UI]&#x200B;[Substance] Visualizza gli attributi della Substance nell&#39;interfaccia utente
* [Scelte rapide] &quot;F4&quot; alterna la vista 2D e 3D
* [Scelte rapide] Nuove scelte rapide per Attiva/Disattiva stencil &quot;N&quot; e maschera veloce &quot;U&quot;
* [Integrazione Substance] Considera le istruzioni &#39;visible if&#39; nei parametri di Substance
* [Riquadro di visualizzazione] Le ombre non vengono calcolate dopo lo spostamento della videocamera
* [Content] Aggiorna MeetMat con le fotocamere importate
* [Content] Aggiungi un campione con la dispersione sottosuperficiale attivata - JadeToad
* [Content] Aggiungi un nuovo modello di progetto PBR con la dispersione sottosuperficie attivata
* [Content] Predefiniti di esportazione aggiornati per aggiungere un nuovo canale di diffusione
* [Content]&#x200B;[Shelf] Aggiunto supporto per la dispersione sottosuperficiale per: pbr-metal-rough, pbr-metal-rough-alpha-test, pbr-coated, pbr-spec-gloss
* [Content]&#x200B;[Shelf] Aggiunto canale di dispersione a 5 materiali avanzati (marmi e pelli)
* [Content]&#x200B;[Shelf] 1 nuovo materiale giada
* [Content]&#x200B;[Shelf] 1 nuovo materiale cera

**Corretto:**

* [CMD] Risultati diversi utilizzando la stessa riga di comando con versioni diverse
* [TDR] Se TdrLevel è impostato, non ci sono errori nel registro
* [Baker] La mappa di Occlusione ambientale è capovolta
* [ID Map] Arresto anomalo durante il prelievo al di fuori dell’intervallo 0-1
* [Iray] Arresto anomalo quando si cambia set di texture e si torna alla modalità Pittura
* [Finestra vista] Sincronizza le aree di rilascio tra le finestre della vista per il trascinamento
* [Engine] Artefatto moire quando si Affiancamento i livelli di riempimento o si disegna un piccolo pennello
* [Licenza] Verifica versione software non valida del servizio di licenza
* [Licenza] Rielabora il modo in cui gestiamo l&#39;autenticazione
* [API] Chiama l&#39;evento API di scripting `onNewProjectCreated` anche durante la creazione con un modello
* [Shader] Lo shader compilato non viene caricato dalla cache se non viene compilato dal file di shader
* [Shelf] L’esportazione del file HDR dallo shelf genera un file con valori bloccati
* [Esporta] L’esportazione EXR blocca i valori di colore RGB tra 0 e 1
* [Content] Il disturbo Procedurale &quot;Rumore di Perlin 3D frattale&quot; è pixelato

**Problemi noti:**

* Blocco del calcolo sulle GPU AMD VEGA
* Problema relativo al tablet Huion con scelte rapide nel sistema operativo Windows
