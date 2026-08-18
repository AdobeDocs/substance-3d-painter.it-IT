---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/configuring-pens-and-tablets.html"
breadcrumb-title: ''
description: Scoprite come configurare penne e tablet in Substance 3D Painter per una sensibilità alla pressione ottimale e un'esperienza di disegno ottimale.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Configuring Pens and Tablets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Configurazione di penne e tablet
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '877'
ht-degree: 0%

---


# Configurazione di penne e tablet

In questa pagina sono elencati più consigli per configurare una penna grafica su Windows per migliorarne la compatibilità con l&#39;applicazione.

## Che cos&#39;è Windows Ink?

Windows Ink è un software/servizio che gestisce Penne, ad esempio stilo o penne, da tablet grafici. Offre varie applicazioni come Sticky Notes e Sketchpad per interagire con una penna sul computer.

A partire dalla versione 2019.3, l’applicazione si basa su di essa per gestire le tavolette grafiche. Prima di questa versione era invece utilizzato Wintab (servizio precedente non supportato da tutti i modelli di tablet grafici).

## Attivazione di Windows Ink nelle impostazioni dei driver del Tablet PC

Per assicurarsi che la pressione della penna sia riconosciuta correttamente, è necessario attivare Windows Ink nelle impostazioni del driver della tavoletta grafica.

>[!NOTE]
>
> Windows Ink non è supportato sulle macchine virtuali, pertanto gli eventi della tavoletta grafica non verranno inoltrati all&#39;applicazione. La pressione della penna non è pertanto supportata in questa configurazione.

### Abilitazione di Windows Ink per le tavolette Wacom

1. Apri il menu **Inizio**.
1. Digitare **Proprietà tavoletta Wacom** e fare clic sul primo risultato della ricerca.
1. Nella finestra **Proprietà tavoletta Wacom**, fare clic sulla **Penna** nell&#39;elenco degli strumenti.\
   ![](../assets/wacom-tool-pen.png)
1. Fai clic sul pulsante più **&quot;+&quot;** per aggiungere un profilo di applicazione.\
   ![](../assets/wacom-profile-plus.png)
1. Fai clic sul pulsante **Sfoglia** nella nuova finestra per individuare l&#39;eseguibile di Substance 3D Painter.\
   ![](../assets/wacom-profile-browse.png)
1. Fare clic su **OK** per convalidare e creare il profilo.\
   ![](../assets/wacom-profile-sp.png)
1. Fare clic sulla scheda **Mappatura**.\
   ![](../assets/wacom-tab-mapping.png)
1. Nella parte inferiore sinistra della finestra, assicurati che **Usa Windows Ink** sia abilitato.\
   ![](../assets/wacom-use-windows-ink.png)

>[!NOTE]
>
> Dopo aver attivato Windows Ink, riavviate l’applicazione per verificare che le modifiche siano correttamente prese in considerazione.

### Abilitazione di Windows Ink per tablet Huion

1. Apri il menu **Inizio**.
1. Digita **Huion Tablet** e fai clic sul primo risultato della ricerca.
1. Nella finestra **Huion Tablet**, fare clic su **Digital Pen**.\
   ![](../assets/huion-pen-settings.png)
1. Nella parte inferiore sinistra della finestra, assicurati che **Abilita Windows Ink** sia abilitato.\
   ![](../assets/huion-pen-winink.png)

## Come accedere alle impostazioni di Windows Ink

È possibile accedere alle impostazioni di Windows Ink dalle impostazioni generali di Windows:

1. Apri il menu **Inizio**.
1. Fare clic sull&#39;icona **Impostazioni**.\
   ![](../assets/setting-menu-start.png)
1. Nella finestra Impostazioni, fare clic su **Dispositivi** .\
   ![](../assets/settings-device.png)
1. Nella finestra **Dispositivi**, fare clic su **Penna e Windows Ink** (disponibile solo se è collegata una tavoletta grafica).\
   ![](../assets/setting-pen-windows-ink.png)

## Impostazioni consigliate di Windows Ink

Di seguito sono riportate le impostazioni di Windows Ink e la configurazione consigliata per ciascuna di esse.

>[!NOTE]
>
> Anche dopo aver seguito questa guida, alcuni elementi visivi relativi a Windows Ink saranno ancora visibili. Purtroppo Microsoft non offre le impostazioni per disattivarle in Windows.
> 
> Gli elementi visivi rimanenti sono:
> 
> * **Cerchio** quando si fa clic con il pulsante destro del mouse.
> * **Descrizione comando** sotto il mouse quando si preme un modificatore di tasto (Ctrl, Alt o Maiusc).

### Impostazioni penna

![](../assets/ink-settings-main.png)

| ***Impostazione*** | ***Descrizione*** |
| --- | --- |
| **Scegliere la mano con cui scrivere** | Consigliati: **Mano destra** Queste impostazioni controllano il modo in cui viene riconosciuto l&#39;orientamento della penna. Se si imposta questa impostazione su Mano sinistra, l’interfaccia utente potrebbe bloccarsi durante l’elaborazione dei parametri. |
| **Mostra effetti visivi** | Consigliato: **Disabilitato** Questa impostazione controlla gli effetti visivi visualizzati durante varie interazioni con la penna. Disattivandolo, si può nascondere l’effetto cerchio increspato quando si fa clic: <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../assets/windows-pen-ripple-circle.jpg"/></div> |
| **Mostra cursori** | Consigliato: **Disabilitato** |
| **Consenti l&#39;utilizzo della penna come mouse in alcune app desktop** | Consigliato: **Abilitato** Queste impostazioni consentono alla penna grafica di inviare input regolari del mouse. Se è disabilitata, questa impostazione può causare problemi di interazione con i parametri dell&#39;interfaccia utente. |

### Impostazioni grafia

![](../assets/ink-settings-handwriting.png)

| ***Impostazione*** | ***Descrizione*** |
| --- | --- |
| **Dimensioni del carattere durante la scrittura direttamente nel campo di testo** | Consigliato: **Medio (predefinito)** |
| **Carattere durante l&#39;utilizzo della grafia** | Consigliato: **Segoe UI (impostazione predefinita)** |
| **Quando si tocca un campo di testo con la penna, utilizzare la grafia per immettere il testo** | Consigliati: **Solo in modalità tablet** Queste impostazioni controllano la modalità e la data di visualizzazione della finestra di immissione del testo scritto a mano. Se non impostata su &quot;solo in modalità tablet&quot;, la finestra verrà visualizzata ogni volta che viene selezionato un campo di testo nell&#39;interfaccia utente. Ad esempio quando si digita un valore specifico in un cursore. |
| **Consenti l&#39;utilizzo della penna come mouse in alcune app desktop** | Consigliato: **Abilitato** Queste impostazioni consentono alla penna grafica di inviare input regolari del mouse. Se è disabilitata, questa impostazione può causare problemi di interazione con i parametri dell&#39;interfaccia utente. |
| **Scrivi nel pannello della grafia con il dito** | Consigliato: **Disabilitato** |

### Impostazioni scelte rapide penna

![](../assets/ink-settings-pen.png)

| ***Impostazione*** | ***Descrizione*** |
| --- | --- |
| **Fai clic una volta** | Consigliato: **Niente** |
| **Doppio clic** | Consigliato: **Niente** |
| **Tenere premuto (supportato solo su alcune penne)** | Consigliato: **Niente** |
| **Consenti alle app di ignorare il comportamento del pulsante di scelta rapida** | Consigliato: **Abilitato** |
| **Se disponibile, mostra l&#39;area di lavoro inchiostri dopo la rimozione della penna dall&#39;archivio** | Consigliato: **Disabilitato** |

## Come accedere alle impostazioni Penna e Tocco

È possibile accedere alle impostazioni Penna e Tocco nel Pannello di controllo:

1. Apri il menu **Inizio**.
1. Digitare **Pannello di controllo** e fare clic sul primo risultato della ricerca.
1. Passare dalla **modalità di visualizzazione** del Pannello di controllo alla **icona piccola**.\
   ![](../assets/control-panel-display-mode.png)
1. Fare clic sulle impostazioni **Penna e tocco**.\
   ![](../assets/control-panel-pen-touch-settings.png)

## Impostazioni consigliate per penna e tocco

Per migliorare il comportamento di colorazione e la manipolazione della fotocamera, si consigliano le impostazioni seguenti.

Per accedere alle impostazioni, fare clic su una delle **azioni della penna** nella finestra, quindi fare clic sul pulsante **impostazioni**.

![](../assets/control-panel-settings.png)

| ***Impostazione*** | ***Descrizione*** |
| --- | --- |
| **Tocco singolo** | Nessun parametro. |
| **Doppio tocco** | Consigliati: **Valori predefiniti.** |
| **Tenere premuto** | Consigliato: **Disattivare l&#39;impostazione &quot;Abilita pressione prolungata per clic con il pulsante destro del mouse&quot;** Se si disabilita questa impostazione, sarà possibile trascinare qualsiasi elemento normalmente senza attivare il cerchio di trascinamento di Windows: <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table1_row-r3-column-c1_dynamic_grid_items_grid-cell_position-par_image" src="../assets/windows-pen-drag-circle.jpg"/></div> |
| **Utilizzare il pulsante della penna come equivalente del clic con il pulsante destro del mouse** | Consigliato: **Abilitato** |
| **Utilizzare la parte superiore della penna per cancellare l&#39;input penna (se disponibile)** | Consigliato: **Abilitato** |
