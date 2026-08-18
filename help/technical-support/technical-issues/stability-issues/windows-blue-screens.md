---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/stability-issues/windows-blue-screens.html"
breadcrumb-title: ''
description: Informazioni su come evitare errori di schermata blu di Windows quando si utilizza Substance 3D Painter per un funzionamento stabile del sistema.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Stability Issues > Windows Blue Screens
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Schermate blu di Windows
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '526'
ht-degree: 0%

---


# Schermate blu di Windows

In Windows [Blue Screens Of Death (BSOD)](https://en.wikipedia.org/wiki/Blue_screen_of_death) sono in genere correlati a driver o malfunzionamenti hardware. Substance 3D Painter stessa non è responsabile di questi BSOD, ma può mettere un po &#39;di luce su un problema con il computer stesso a causa di quanto intensa l&#39;applicazione è. Nel caso di Substance 3D Painter, un BSOD può essere causato dai seguenti problemi.

## Driver GPU instabili

Substance 3D Painter si affida molto alla GPU per eseguire i vari calcoli. I driver GPU a volte possono essere instabili o avere regressioni. Si consiglia di mantenere la GPU aggiornata per ottenere le correzioni più recenti e i miglioramenti delle prestazioni. Consultate: [La GPU contiene driver obsoleti](../gpu-issues/gpu-has-outdated-drivers.md).

### Installazione di Windows instabile

Windows stesso può essere instabile dopo alcuni aggiornamenti. Utilizzare gli strumenti di diagnostica forniti con Windows per rilevare potenziali errori nel sistema.

È consigliabile eseguire lo strumento **Gestione e manutenzione immagini distribuzione** (Gestione e manutenzione immagini distribuzione) e lo strumento **Controllo file di sistema** (SFC). Gestione e manutenzione immagini distribuzione è utile per recuperare i file di sostituzione necessari per SFC al fine di correggere i file di sistema danneggiati o mancanti.

Esecuzione di **Gestione e manutenzione immagini distribuzione**:

1. Apri il **menu Start**
1. Cerca **prompt dei comandi**
1. **Fare clic con il pulsante destro del mouse** sul risultato e scegliere &quot; **Esegui come amministratore** &quot;
1. Digitare il comando seguente: **DISM /Online /Cleanup-Image /RestoreHealth**
1. Premi **Invio**

Esecuzione di **SFC**:

1. Apri il **menu Start**
1. Cerca **prompt dei comandi**
1. **Fare clic con il pulsante destro del mouse** sul risultato e scegliere &quot; **Esegui come amministratore** &quot;
1. Digitare il comando seguente: **sfc /scannow**
1. Premi **Invio**

Riavvia il computer dopo entrambi i comandi per applicare gli aggiornamenti.

Per ulteriori informazioni su questo argomento, vedere: [Utilizzare lo strumento Controllo file di sistema per correggere i file di sistema mancanti o danneggiati](https://support.microsoft.com/en-us/help/929833/use-the-system-file-checker-tool-to-repair-missing-or-corrupted-system)

### Spazio su disco insufficiente

Dall&#39;introduzione delle [Texture virtuali sparse](../../../features/sparse-virtual-textures.md) in Substance 3D Painter, l&#39;applicazione ora utilizza il disco per memorizzare le texture nella cache mentre si lavora. Se lo spazio del sistema è esaurito, ciò può provocare instabilità.

Esistono due semplici soluzioni a questo problema:

* Liberate spazio sul disco per liberare spazio nel sistema di cache.
* Spostate la directory della cache in un&#39;altra unità con più spazio. È possibile modificare questa posizione accedendo alle impostazioni principali dell&#39;applicazione. Vedere l&#39;impostazione [&quot;File temporanei&quot;](https://docs.substance3d.com/display/SPDOC/General).

### Disco guasto (HDD o SSD)

Come accennato al punto precedente, il sistema di cache si basa fortemente sul disco. Se l&#39;unità disco è guasta, il sistema potrebbe essere instabile quando si tenta di scrivere o leggere dati.

Per rilevare se un disco è difettoso, è possibile eseguire CHKDSK su Windows:

1. Apri il **menu Stella**
1. Seleziona **Computer / Questo PC**
1. **Fate clic con il pulsante destro del mouse** sul disco rigido e scegliete **Proprietà.**
1. Passa alla scheda **Strumenti**.
1. Fai clic su **Controlla/Controlla ora** in **Controllo errori** .

### Memoria difettosa

La memoria difettosa (RAM) può causare instabilità di sistema se un programma non è in grado di leggere o scrivere in modo sicuro nella memoria. Per verificare l&#39;integrità della memoria, si consiglia di eseguire **MemTest**.

Consulta [questa guida](https://www.memtest86.com/technical.htm) su come installare e utilizzare MemTest.
