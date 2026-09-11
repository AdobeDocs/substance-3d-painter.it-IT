---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/gpu-issues/painter-doesn-t-start-on-the-right-gpu.html"
breadcrumb-title: ''
description: Scoprite come configurare Substance 3D Painter per l'avvio con la GPU corretta per prestazioni e compatibilità ottimali.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > GPU Issues > Painter doesnt start on the right GPU
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Painter non si avvia con la GPU corretta
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '624'
ht-degree: 0%

---


# Painter non si avvia con la GPU corretta

In Windows, l’applicazione potrebbe non utilizzare la GPU corretta all’avvio, il che potrebbe causare problemi di prestazioni e stabilità. Di seguito è riportato un elenco di problemi comuni e le relative soluzioni per garantire che il software funzioni con la GPU corretta.

Per sapere quale GPU è utilizzata, puoi controllare il [file di registro](../../exporting-the-log-file.md).

## Windows

### Monitoraggio della configurazione dei cavi

In Windows la GPU assegnata a un’applicazione dipende dal monitor su cui è in esecuzione l’applicazione. Questo perché i cavi del monitor sono collegati direttamente all&#39;output della GPU stessa. L’applicazione può iniziare con la GPU sbagliata, quindi se il monitor su cui si avvia è collegato all’output grafico della scheda madre anziché a quello della scheda grafica stessa. In tal caso, è probabile che Windows utilizzi la GPU integrata anziché la GPU dedicata.

<b>Per risolvere questo problema</b>: correggere la configurazione del cavo scollegando il monitor collegato alla scheda madre e collegandolo agli output della GPU.

### Installazione del driver GPU errata

Se i driver della GPU non sono installati correttamente, l&#39;applicazione non sarà in grado di raggiungere la GPU dedicata e dovrà invece eseguire il fallback sulla GPU integrata.

<b>Per risolvere il problema</b>: disinstallare i driver GPU correnti, eseguire una pulizia e reinstallare i driver GPU dopo il riavvio del computer.

### Impostazione profilo driver GPU Nvidia

In alcuni computer, ad esempio i laptop, l&#39;applicazione può essere eseguita sulla GPU integrata invece che sulla GPU Nvidia dedicata per impostazione predefinita. Con una GPU NVIDIA, il passaggio alla GPU corretta dipende dai profili dell’applicazione. Se un&#39;applicazione non dispone di tale profilo, è possibile assegnarne uno manualmente.

<b>Per risolvere il problema</b>:

1. Fai clic con il pulsante destro del mouse sul desktop e seleziona Pannello di controllo NVIDIA <b>o</b> Accedi al pannello di controllo e cerca il pannello di controllo NVIDIA
1. In <b>Impostazioni 3D</b>, accedi a <b>Gestisci impostazioni 3D</b>
1. Nella scheda <b>Impostazioni programma</b> aggiungi un nuovo profilo per <b>Substance 3D Painter</b>
1. Impostate come processore grafico preferito il processore NVIDIA ad alte prestazioni

### Impostazione prestazioni Windows

È possibile che Windows abbia impostato la GPU errata per l&#39;applicazione a causa delle impostazioni predefinite per le prestazioni e il consumo energetico.

<b>Per risolvere questo problema: </b>seguire la procedura dettagliata riportata di seguito per ignorare la configurazione predefinita della GPU.

1. Per aprire le impostazioni di visualizzazione, fare clic con il pulsante destro del mouse sul desktop:

   ![](../../../assets/settings-33.png)
1. Passare alla parte inferiore della finestra nella pagina Home e fare clic su &quot;Impostazioni grafica&quot;:

   ![](../../../assets/graphics-settings.png)
1. Fare clic sul pulsante &quot;Browse&quot; (Sfoglia) e individuare il file eseguibile di Substance 3D Painter:

   ![](../../../assets/browse-16.png)
1. Una volta aggiunta l&#39;applicazione, fai clic sul pulsante &quot;Opzioni&quot;:

   ![](../../../assets/options-19.png)
1. Scegliere l&#39;impostazione &quot;Prestazioni elevate&quot; e fare clic sul pulsante &quot;Salva&quot;

   ![](../../../assets/specs.png)

## Linux

### Disattiva &quot;Preferenze GPU non predefinite&quot;

Quando si esegue Painter da una scelta rapida da tastiera desktop o tramite Steam, assicurarsi che l&#39;impostazione <b>PrefersNonDefaultGPU</b> all&#39;interno del file <b>\*.desktop</b> sia impostata su <b>false</b>.

Questa impostazione può essere fuorviante e portare all’utilizzo/imposizione della GPU integrata al posto di quella discreta e più potente. Per ulteriori informazioni [vedere questa discussione](https://github.com/ValveSoftware/steam-for-linux/issues/9940).

### Forza la GPU specifica utilizzando la variabile di ambiente DRI\_PRIME

Per impostazione predefinita, Painter utilizzerà la prima GPU elencata dall’API grafica Vulkan, tuttavia questa GPU potrebbe essere errata (potrebbe essere la GPU integrata elencata per prima), con conseguenti prestazioni insoddisfacenti. La variabile di ambiente DRI\_PRIME può essere utilizzata per forzare la GPU desiderata. Per ulteriori informazioni [vedere la documentazione del wiki Arch](https://wiki.archlinux.org/title/PRIME#For_open_source_drivers%E2%80%94PRIME). Puoi anche fare riferimento alla [documentazione Mesa](https://docs.mesa3d.org/envvars.html#envvar-DRI_PRIME).
