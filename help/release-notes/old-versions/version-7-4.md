---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/release-notes/old-versions/version-7-4.html"
breadcrumb-title: ''
description: Consulta le note sulla versione per Substance 3D Painter versione 7.4 per informazioni sulle nuove funzioni, i miglioramenti e le correzioni di bug.
helpx_creative_field: ""
helpx_description: Painter > Release notes > Old versions > Version 7.4
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versione 7.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '1910'
ht-degree: 0%

---


# Versione 7.4

**Substance 3D Painter 7.4** aggiunge il supporto per OpenColorIO con l&#39;introduzione del nuovo flusso di lavoro Gestione colore.

Data di pubblicazione: *24 novembre 2021*

## Funzioni principali

### Nuova gestione colore

![](../../assets/banner-cm.jpg)

Questa versione introduce la gestione del colore con il supporto di [OpenColorIO](https://opencolorio.org/) (OCIO in breve) versione 2.

Questo nuovo flusso di lavoro consente di gestire e calibrare i colori dall’importazione all’esportazione e anche all’interno della finestra della vista, in modo da adattare più facilmente qualsiasi contenuto in diverse applicazioni.

* **Impostazioni progetto**\
  Quando si crea un nuovo progetto, è ora possibile attivare la gestione del colore. Un progetto esistente può anche abilitare la gestione del colore tramite le impostazioni del progetto.\
  Per abilitare la gestione del colore, passa da **Legacy** (impostazione predefinita) a **OpenColorIO** e utilizza una delle configurazioni predefinite o una personalizzata.

  ![](../../assets/cm-settings.png){width="400px"}

* **Impostazioni di visualizzazione del riquadro di visualizzazione**\
  Nella parte superiore delle viste 2D e 3D sono presenti due controlli per la gestione del colore:\
  **Pulsante Colore**: attiva o disattiva la trasformazione del colore nella finestra della vista.\
  **Menu a discesa Trasformazione visualizzazione**: seleziona la trasformazione di visualizzazione da utilizzare per la conversione dei colori.

  ![](../../assets/cm-viewport.jpg){width="500px"}

* **Impostazioni selettore colore**\
  Quando la gestione del colore è attivata, i selettori colore offrono nuovi controlli. I colori vengono modificati nello spazio colore di lavoro specificato dalla configurazione.\
  Sotto i cursori HSV/RGB viene visualizzato il valore del colore finale, trasformato dallo spazio di lavoro allo spazio colore di visualizzazione.

  ![](../../assets/color-picker-demo.png)

  ![](../../assets/cm-picker-display-value.png)

* **Importare bitmap e materiali di Substance con uno spazio colore personalizzato**\
  Sono disponibili impostazioni dedicate per specificare come devono essere gestite le risorse, inclusa la modalità di interpretazione dell&#39;output dei materiali Substance.\
  È inoltre possibile sapere quale spazio colore viene utilizzato da una risorsa analizzandone il nome file.

  ![](../../assets/auto-color-space.png)

* **Esporta impostazioni**\
  Quando esporti le texture, nei nomi dei file dei canali con gestione del colore viene visualizzato il nome dello spazio colore utilizzato con l’aiuto della nuova parola chiave **$colorSpace**.

  ![](../../assets/export-list-1.png){width="250px"}

  ![](../../assets/export-list-2_1.png)

>[!NOTE]
>
> Per ulteriori informazioni sul funzionamento della gestione del colore nell&#39;applicazione, consulta la [pagina dedicata](../../features/color-management/color-management.md).

### Nuovo disancoraggio della finestra della vista 2D e 3D

![](../../assets/banner-undock.jpg)

La vista 2D e 3D può ora essere disancorata per essere spostata altrove. Ad esempio, se la vista 3D si trova su una schermata principale mentre la vista 2D si trova su un&#39;altra schermata.

Lavorare con una vista non ancorata è più semplice per organizzare il layout dell’applicazione e tenere d’occhio le cose senza perdere troppa area di pittura.

* **Disancorare una visualizzazione**\
  Per disancorare una vista, aprite il menu Visualizza e scegliete una delle due opzioni. Ogni opzione apre una nuova finestra con la vista all&#39;interno, mentre l&#39;altra vista rimane ancorata all&#39;interno dell&#39;interfaccia principale.

  ![](../../assets/undock-menu.png)

* **Scambia anche con una vista non ancorata**\
  Quando una vista è disancorata, è possibile scambiarla con l’azione di scambio del menu Visualizza.

  ![](../../assets/swap-undock.gif){width="500px"}

* **Compatibile con la gestione del colore**\
  La vista non ancorata dispone di una propria trasformazione della visualizzazione per la gestione del colore, che rende più facile la gestione in diversi monitor.

  ![](../../assets/false-colors-undock.jpg){width="500px"}

### Nuovo supporto per SpaceMouse® di 3Dconnection

![](../../assets/spacemouse-banner.jpg)

**SpaceMouse®** è un dispositivo tramite 3Dconnection che consente di manipolare la videocamera della finestra della vista 3D in modo più intuitivo e semplice. Ora è supportato in modalità nativa e direttamente plug and play con Painter.

Per ulteriori informazioni, consulta la [pagina della documentazione](../../features/spacemouse-by-3dconnexion.md) dedicata.

>[!NOTE]
>
> * Disponibile con la versione 7.4.2 e successive.
> * Assicurarsi di installare i driver più recenti di SpaceMouse® per trarre vantaggio dallo schema di controllo Painter.

### Nuovo contenuto

![](../../assets/banner-content-4.jpg)

Un nuovo set di risorse è stato aggiunto al contenuto predefinito disponibile con l&#39;applicazione:

* Nuove decalcomanie, strumenti predefiniti e filtri (di **Käy Vriend**):
  * **Decalcomanie**
    * Scar Plain Straight
    * Patch tasca regolare
  * **Predefiniti**
    * Nastro Zipper Advanced
    * Arresto avanzato zip
    * Cursore avanzato zip
    * Pizzi per cavo di serraggio
    * Serrare l&#39;occhiello del cavo
    * Stelle scintillanti dorate
    * Glitter Party
    * Glitter Dots Pastello
  * **Generatore**
    * Gonfiamento Riduzione/Avvolgimento

* Nuove bitmap per grungi (di **Emiel Sleegers**):
  * Vernice intonaco grunge
  * Intonaco Di grunge Sbiadito
  * Vernice grunge sfogliata
  * Umidità grunge
  * Polpa di grunge
  * Grunge Cobweb
  * Grunge Bush
  * Legno di grunge morbido
  * Carta di grunge strappata
  * Grunge crepata profonda
  * Dust spazzolato grunge

### Srotolamento UV automatico migliorato

![](../../assets/banner-uv-1.jpg)

Lo srotolamento UV automatico è stato aggiornato con una nuova opzione che migliora il supporto dei modelli 3D con superfici estese.

Questa nuova impostazione denominata **Evitare Isole UV allungate** consente di sfruttare meglio lo spazio UV dividendo le Isole UV che potrebbero essere troppo lunghe.

Di seguito è riportato un esempio di queste nuove impostazioni senza utilizzarle rispetto a quando le si utilizza:

![](../../assets/uv-before-after.jpg){width="500px"}

### Script Python migliorati

![](../../assets/banner-python-1.jpg)

L’API Python dispone di un nuovo metodo che consente di chiamare l’API Javascript.

Questo nuovo metodo consente di migrare più facilmente i vecchi plug-in alla nuova API Python. Sblocca anche alcune funzioni come la gestione di **Baking** e **Shader** che non sono ancora state esposte in Python.

Per eseguire un comando Javascript da Python, utilizzare la funzione **assessment()** dal nuovo sottomodulo **js**. Ulteriori informazioni sono disponibili nella documentazione delle API (disponibile tramite il menu Aiuto dell’applicazione).

## Note sulla versione

### 7.4.2

*(Rilasciato il 8 marzo 2022)*

**Aggiunto:**

* [SpaceMouse]&#x200B;[Windows] Supporto di 3Dconnection SpaceMouse nel riquadro di visualizzazione 3D per la navigazione
* [SpaceMouse]&#x200B;[Windows] Scelte rapide/tasti di base per i modelli Pro ed Enterprise di SpaceMouse nella finestra della vista 3D
* [SpaceMouse]&#x200B;[Windows] Icona del centro di rotazione dedicato nella finestra della vista 3D
* [Gestione colore] Utilizzare i ruoli dalla configurazione OCIO per modificare le impostazioni predefinite
* [Gestione colore] Gestione colore gestisce la finestra delle proprietà per i widget colore
* [Gestione colore] Gestione colore gestisce la finestra delle proprietà per l’anteprima del materiale
* [Gestione colore] Campioni di gestione colore nel selettore colore
* [Gestione colore] Aggiungi un’impostazione per definire lo spazio colore sRGB standard
* [Gestione colore] Aggiungi lo spazio cromatico sRGB standard dalla configurazione OCIO nel selettore colore. Elenco selettori visualizzazione
* [Gestione colore] Miglioramenti per il menu di esclusione dello spazio colore
* [Gestione colore] Consente di ignorare lo spazio colore della mappa dell&#39;ambiente in Impostazioni schermo
* [Gestione colore] Disegna sfumature selettore colore in base alla visualizzazione corrente
* [Gestione colore] Blocca valori HDR per impostazione predefinita nell&#39;editor colori
* [Gestione colore] Usa passthrough (senza spazio colore) per i filtri in modalità Legacy
* [Gestione colore] Limita la visualizzazione delle sfumature nell&#39;editor colori in base all&#39;intervallo [0-1]
* [Gestione colore] Nascondi selettore visualizzazione nel selettore colore in modalità Legacy
* [Gestione colore] Rendi il selettore colore un campo esadecimale sempre nello spazio colore sRGB
* [Gestione colore] Disattiva il selettore colore Visualizza il menu a discesa per i canali dati
* [Ottimizzazione] La griglia di alterazione ricalcola solo le porzioni UV coperte
* [Esportazione] Consente di esportare i progetti di porzioni UV per Sketchfab, USD e glTF
* [Scripting]&#x200B;[Python] Consente di modificare la funzione di mappatura tonale

**Corretto:**

* [Sketchfab] L&#39;aggiornamento del modello esistente comporta la creazione di un nuovo modello
* [Sketchfab] Arresto anomalo durante la ricerca di un modello aggiornato in precedenza
* Arresto anomalo durante l’esportazione in USD
* Arresto anomalo durante la creazione di una nuova istanza dello shader nella maschera di geometria o quando la geometria è nascosta
* [Finestra Importa risorsa] Arresto anomalo quando si modifica il tipo di risorse importate
* Le mappe mesh normali vengono invertite quando vengono utilizzate nella pila di livelli
* [Substance] Metodo di fusione dei dati utente non preso in considerazione
* [Gestione colore] Le bitmap con spazio colore nel nome del file vengono importate come sequenze di porzioni UV
* [Gestione colore] Gli output con gestione del colore del grafico a Substance si trovano in uno spazio colore errato
* [Gestione colore] Lo strumento Riempimento poligonale visualizza il colore errato
* [Gestione colore] Il tonemapper ACES viene applicato ai canali in modalità Solo
* [Gestione colore] L’illuminazione della sfera di anteprima dello strumento non è gestita dal colore
* [Gestione colore]&#x200B;[Esporta] Le mappe convertite applicano una conversione errata
* [Scripting]&#x200B;[Python]&#x200B;[Gestione colore] I progetti creati con la variabile di ambiente template e OCIO sono in modalità Legacy
* [Scripting]&#x200B;[Python] Impossibile utilizzare la funzione di valutazione JavaScript all&#39;avvio
* [Offerta Adobe 3D] Impossibile avviare Painter quando si utilizzano impostazioni internazionali con lingue non supportate per impostazione predefinita

**Problemi noti:**

* 3Dconnection SpaceMouse non supportato su MacOS
* [UI] Barra di scorrimento orizzontale con la gestione del colore visualizzata in alcuni casi nella nuova finestra del progetto
* [Panettieri] L&#39;impostazione &quot;Normali medi&quot; non ha effetto nei progetti per le porzioni UV
* [Mac M1] I materiali avanzati non vengono visualizzati correttamente
* [Gestione colore] Le risorse utilizzate in modalità di proiezione non sono sottoposte alla gestione del colore nella sovrapposizione

### 7.4.1

*(Rilasciato il 14 dicembre 2021)*

**Aggiunto:**

* [Gestione colore] Usa ruolo dati nei nomi file esportati
* [Gestione colore] Per impostazione predefinita, espandi la sezione Gestione colore quando OCIO è selezionato nelle finestre Nuovo progetto e Impostazioni progetto
* [Gestione colore] Aggiungere il tonemapper ACES in modalità legacy
* [Gestione colore] Regolare le impostazioni di configurazione predefinite
* [Gestione colore]&#x200B;[Esporta] Riempi $colorSpace nei nomi dei file per i canali dati
* [Esporta] Esporta progetto porzione UV in Stager
* [Interoperabilità] Non disponibile per le edizioni Steam e Substance
* [Interoperabilità] Consente di inviare un progetto UV Tile a Stager

**Corretto:**

* [MacOS]&#x200B;[Arresto anomalo] Painter non inizia con Catalina
* [Gestione colore]&#x200B;[Arresto anomalo] Arresto anomalo casuale durante la riproduzione con tipo di dati/gestione colore sul canale utente
* [Gestione colore] Le risorse utilizzate come scala di grigio nello spazio colore della maschera visualizzano il nuovo menu
* [Gestione colore] Il canale utente è più scuro nella finestra della vista in modalità legacy + visualizzazione solo
* [Gestione colore] La mappa Env è sempre lineare quando utilizzata in iRay
* [Gestione colore] Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* [Gestione colore] Il selettore colore non funziona all’interno di una Substance in modalità legacy
* [Gestione colore] Il passaggio tra le viste dei singoli canali nella finestra della vista viene visualizzato con lo spazio cromatico corretto quando si utilizza il menu a discesa
* [Gestione colore] L’esportazione applica la conversione errata ai canali utente con gestione del colore in modalità legacy
* I tratti creati nella maschera di visualizzazione Solo non vengono visualizzati quando si ritorna alla vista Materiale
* [Esportazione] Le mappe convertite non vengono esportate come canali con gestione del colore
* [Set di texture] Descrizione comando con nome originale mancante nei canali utente rinominati
* [Steam] File mancanti durante la verifica dell&#39;integrità del file con Steam

**Problemi noti:**

* [Mac M1] I materiali avanzati non vengono visualizzati correttamente

### 7.4.0

*(Rilasciato il 24 novembre 2021)*

**Aggiunto:**

* [Gestione colore] Supporto della gestione colore OpenColorIO versione 2
* [Gestione colore] Aggiungere impostazioni di gestione del colore alle impostazioni del progetto
* [Gestione colore] Finestra di avvertenza sulle modifiche alla configurazione di Gestione colore all’apertura di un progetto
* [Gestione colore] Visualizza un messaggio di errore se è selezionato un file di configurazione OCIO non valido
* [Gestione colore] Consente di ignorare la configurazione con la variabile di ambiente OCIO
* [Gestione colore] Più configurazioni OCIO integrate per impostazione predefinita con l&#39;applicazione
* [Gestione colore] Estrai il nome dello spazio colore dal nome del file bitmap importato
* [Gestione colore] Consente di ignorare lo spazio colore con uno spazio colore dalla configurazione nella finestra Proprietà
* [Gestione colore] Aggiungere opzioni di gestione del colore nelle impostazioni del set di texture
* [Gestione colore]&#x200B;[Finestra vista] Consente di gestire separatamente i colori delle viste 2D e 3D
* [Gestione colore] Caricare e convertire la mappa dell&#39;ambiente nello spazio colore di lavoro
* [Gestione colore] Regola il selettore colore e l&#39;editor con lo spazio colore corrente
* [Gestione colore] Consente di selezionare lo spazio colore di trasformazione della visualizzazione nella finestra della vista con un nuovo menu a discesa
* [Gestione colore] Applicare la trasformazione della visualizzazione con i risultati del rendering dei raggi
* [Gestione colore] Esportare texture con diversi spazi colore
* [Gestione colore]&#x200B;[Python] Applicazione delle impostazioni di gestione del colore dalla variabile di ambiente (OCIO) ai nuovi progetti
* [Finestra vista] Consente di disancorare la finestra della vista 2D o 3D
* [Annullamento automatico] Nuova opzione per evitare isole allungate
* [Scripting Python] Chiama funzioni JavaScript dall’API Python
* [Finestra Nuovo progetto] Rende comprimibile la sezione delle mappe importate
* [Proiezione]&#x200B;[Altera] Consenti di nascondere le normali come opzione nelle impostazioni di Altera
* [Content] 11 nuove mappe grungi
* [Content] 8 nuovi strumenti predefiniti (cerniera, cavo di serraggio, scintillio)
* [Contenuto] 8 nuovi materiali (cicatrice, tasca, ...)
* [Contenuto] 1 nuovo generatore (gonfia shrinkwarp)

**Problemi noti:**

* [Mac M1] I materiali avanzati non vengono visualizzati correttamente
* [Gestione colore]&#x200B;[Arresto anomalo] Arresto anomalo casuale durante la riproduzione con tipo di dati/gestione colore sul canale utente
* [Gestione colore] Il selettore colore non seleziona il valore corretto per il canale dati in modalità legacy
* [Gestione colore]&#x200B;[Iray] Il salvataggio del rendering in EXR o TIFF durante l’attivazione della Gestione colore nella finestra della vista consente di salvare sempre in modalità lineare
* [Gestione colore] Le risorse utilizzate come scala di grigio nella maschera visualizzano il menu Spazio colore errato
* [Color Management]&#x200B;[Iray] La mappa Env è sempre lineare se utilizzata in Iray
* [Gestione colore]&#x200B;[Esporta] Le mappe convertite non vengono esportate come canali di gestione del colore
* [Gestione colore]&#x200B;[Esporta] L&#39;esportazione ignora se il canale utente è sottoposto alla gestione del colore o meno in modalità legacy
