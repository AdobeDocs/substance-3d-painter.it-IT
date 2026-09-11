---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/startup-issues/crash-or-freeze-during-startup.html"
breadcrumb-title: ''
description: Scopri come correggere arresti anomali e blocchi durante l'avvio di Substance 3D Painter per un avvio stabile dell'applicazione.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Startup Issues > Crash or freeze during startup
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arresto anomalo o blocco durante l'avvio
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '618'
ht-degree: 0%

---


# Arresto anomalo o blocco durante l&#39;avvio

Questa pagina elenca i problemi noti e le relative soluzioni relative all’avvio non corretto dell’applicazione.

## Conflitti software

Per un elenco di tutti i software noti che possono creare conflitti, vedere la pagina seguente: [Conflitti software](software-conflicts.md).

## Esecuzione con la GPU errata

Se l&#39;applicazione non si avvia con la GPU corretta, potrebbero verificarsi problemi di stabilità. Per ulteriori informazioni, consulta questa pagina: [Painter non si avvia con la GPU corretta](../gpu-issues/painter-doesn-t-start-on-the-right-gpu.md).

## Driver GPU obsoleti

L’utilizzo di driver GPU datati può causare blocchi e/o arresti anomali. Si consiglia di utilizzare i driver più recenti della GPU, se disponibili. Consultate: [La GPU contiene driver obsoleti](../gpu-issues/gpu-has-outdated-drivers.md).

## Schermo bianco e non risponde

Se l&#39;applicazione si blocca durante l&#39;avvio su Windows (portando a una schermata bianca), può essere di alcuni motivi:

* Un&#39;applicazione esterna sta creando un conflitto. Vedere [Conflitti software](software-conflicts.md) per sapere quali.
* Alcune finestre dell’applicazione sono state aperte su un altro monitor. Ripristinando il layout predefinito dell&#39;interfaccia, è possibile avviare l&#39;applicazione normalmente:
  1. Apri l&#39;editor del Registro di sistema (**regedit** dal menu Start)
  1. Passare alle preferenze dell&#39;applicazione (vedere: [Preferenze e percorso dei dati dell&#39;applicazione](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/application-preferences-location-147095594.html))
  1. Espandi la chiave **Adobe Substance 3D Painter**
  1. Seleziona la chiave **Finestra principale 2018** ed eliminala
  1. Riavvia l’applicazione

## Arresto anomalo a causa di un percorso di sistema/percorso Python errato

L&#39;applicazione controlla il percorso di sistema per caricare i moduli Python e le impostazioni dell&#39;ambiente. Se il sistema ha una configurazione errata può provocare un arresto anomalo durante l&#39;avvio.

In Windows:

1. Apri il menu **Inizio**
1. Cerca e seleziona **Sistema (Pannello di controllo)**
1. Fai clic su **Impostazioni di sistema avanzate**
1. Fare clic su **Variabili di ambiente**
1. In **Variabili di sistema** trovare la variabile **PATH**

È quindi possibile modificare la variabile per verificarne il contenuto. Se ad esempio la variabile contiene questo tipo di caratteri, verrà generato un arresto anomalo

```
ï–›éŒ à €è¸€ì‡ì‡ç¿¹
```


## Aggiornamenti di Windows 10

Alcuni aggiornamenti di Windows 10 potrebbero creare instabilità. Utilizzare gli strumenti di diagnostica forniti con Windows per rilevare potenziali errori nel sistema.

È consigliabile eseguire lo strumento **Gestione e manutenzione immagini distribuzione** (Gestione e manutenzione immagini distribuzione) e lo strumento **Controllo file di sistema** (SFC). Gestione e manutenzione immagini distribuzione è utile per recuperare i file di sostituzione necessari per SFC al fine di correggere i file di sistema danneggiati o mancanti.

Esecuzione di **Gestione e manutenzione immagini distribuzione**:

1. Aprire il menu Start
1. Cerca prompt dei comandi
1. Fai clic con il pulsante destro del mouse sul risultato e scegli &quot;Esegui come amministratore&quot;
1. Digitare il comando seguente: **DISM /Online /Cleanup-Image /RestoreHealth**
1. Premi Invio

Esecuzione di **SFC**:

1. Aprire il menu Start
1. Cerca prompt dei comandi
1. Fai clic con il pulsante destro del mouse sul risultato e scegli &quot;Esegui come amministratore&quot;
1. Digitare il comando seguente: **sfc /scannow**
1. Premi Invio

Riavvia il computer dopo entrambi i comandi per applicare gli aggiornamenti.

Per ulteriori informazioni su questo argomento, vedere: [Utilizzare lo strumento Controllo file di sistema per correggere i file di sistema mancanti o danneggiati](https://support.microsoft.com/en-us/help/929833/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system).

## Arresto anomalo all’avvio con versioni precedenti

In Windows, è possibile che la versione 2018 (4.x) o precedente non si avvii perché uno dei file dll forniti con la cartella di installazione è troppo vecchio per il sistema operativo. Questo arresto anomalo può essere risolto sostituendo manualmente il file con una versione più recente.

Per eseguire questa operazione:

1. Passa alla cartella di installazione di Substance Painter.
1. Rinomina il file <b>libeay32.dll</b> in <b>backup\_libeay32.dll</b>.
1. Scarica il seguente file: [updated\_libeay32.zip](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/spdoc/files/182266673/225968681/1/1644000679697/updated-libeay32.zip).
1. Estrai il file dll dal file zip nella cartella di installazione (accanto al file Substance Painter.exe).
1. Avviare l&#39;applicazione.
