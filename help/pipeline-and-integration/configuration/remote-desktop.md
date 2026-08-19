---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/pipeline-and-integration/configuration/remote-desktop.html"
breadcrumb-title: ''
description: Scopri come configurare Substance 3D Painter per l’accesso desktop remoto per abilitare i flussi di lavoro e la collaborazione remoti.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Configuration > Remote Desktop
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Desktop remoto
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---


# Desktop remoto

In questa pagina vengono descritte soluzioni e alternative per consentire l&#39;esecuzione di Substance 3D Painter tramite Desktop remoto su Windows.

Per impostazione predefinita, in Windows RDP viene eseguito in un contesto OpenGL inesistente o troppo basso, il che rende l’applicazione incapace di funzionare correttamente o in caso di arresto anomalo. Substance 3D Painter richiede un contesto OpenGL 3.3. Di seguito sono riportate le soluzioni per attenuare il problema, ma non vi sono garanzie che funzioneranno poiché il problema iniziale dipende da Windows e da alcuni driver GPU.

>[!NOTE]
>
> Per impostazione predefinita, le GPU Nvidia Quadro possono eseguire l’applicazione in modalità RDP, mentre le GPU Nvidia GeForce forniscono solo un contesto OpenGL 1.4 (troppo basso per Substance 3D Painter). Per risolvere il problema, è possibile installare un eseguibile. Vedere: <https://developer.nvidia.com/designworks>

## Configurazione dei criteri di Windows

In Windows 10 potrebbe essere necessario modificare **Criteri di gruppo** per consentire l&#39;esecuzione della GPU in modalità RDP.

Per eseguire questa operazione:

1. Premi **Win + R** per aprire la finestra di esecuzione
1. Digita &quot; **gpedit.msc** &quot; quindi Invio
1. Passa a **Criteri computer locale\Configurazione computer\Modelli amministrativi\Componenti di Windows\Servizi Desktop remoto\Host sessione Desktop remoto\Ambiente sessione remota**
1. Abilita l&#39;opzione **Utilizza la scheda grafica predefinita hardware per tutte le sessioni di Servizi Desktop remoto**.

## Comando TSCON di Windows

Se la modifica dei criteri precedente non funziona, provare a utilizzare la riga di comando **tscon**. Questo comando consente di scollegare il computer remoto e collegarne uno nuovo all&#39;hardware fisico (mouse, tastiera e così via). Quindi, la semplice esecuzione dell’applicazione e il riconnesso in remoto dovrebbero consentire di lavorare con l’applicazione nella GPU.

1. Premi il tasto **Windows+R** per aprire la finestra **esegui**.
1. Digita **cmd** e premi **Invio**.
1. Nel tipo della riga di comando e nel comando seguente: **tscon 1 /dest:console**
1. Premi Invio
1. Nella riga di comando digitare il comando successivo: **start &quot;Path/To/Substance/Painter/Folder/Substance 3D Painter.exe&quot;** (assicurarsi di modificare il percorso in modo che corrisponda al computer)
1. Premi Invio

Dopo questi passaggi, attendere alcuni secondi per consentire l&#39;avvio dell&#39;applicazione e quindi riconnettersi alla sessione.

Se questa procedura non funziona, potrebbe essere necessario eseguire la riga di comando di Windows in modalità amministratore.

## Alternative

Se i suggerimenti precedenti non funzionano, si consiglia di utilizzare soluzioni alternative come VNC o Teamviewer, che supportano la GPU tramite connessioni remote.
