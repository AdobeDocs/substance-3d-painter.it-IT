---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/startup-issues/software-conflicts.html"
breadcrumb-title: ''
description: Scopri come risolvere i conflitti software che impediscono a Substance 3D Painter di avviarsi correttamente nel sistema.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Startup Issues > Software conflicts
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Conflitti software
user-guide-description: ''
user-guide-title: ''
source-git-commit: 22871eab2f25d09bd82f1292d8b3e5f8c4f1c2cf
workflow-type: tm+mt
source-wordcount: '681'
ht-degree: 0%

---


# Conflitti software

Questa pagina contiene un elenco di problemi noti di altri software che potrebbero impedire o impedire il corretto arresto anomalo di Substance 3D Painter.

| *Potenziale causa del conflitto* | *Problema* |
| --- | --- |
| **Antivirus/antispyware** | I software antivirus o antispyware possono causare alcuni dei seguenti problemi:<ul data-preserve-html="true"> <li data-preserve-html="true"><b> Falso positivo</b>: Painter è stato erroneamente contrassegnato come virus o malware.</li> <li data-preserve-html="true"><b> file bloccati</b>: Painter non è in grado di leggere o scrivere file (esportazione, creazione di predefiniti e così via).</li> <li data-preserve-html="true"><b> Eliminazione file</b>: Painter non può avviarsi o funzionare normalmente perché i file necessari sono stati rimossi.</li> </ul>Se si verifica una di queste situazioni, si consiglia di disattivare temporaneamente l&#39;antivirus per verificare se è utile o di aggiungere manualmente eccezioni per Painter. |
| **AMD CrossFire e NVIDIA SLI** | Painter non supporta più configurazioni GPU, con conseguenti arresti anomali. Si consiglia di disabilitare questa funzione. |
| <b> Assistente Autodesk </b> | L&#39;applicazione Autodesk Assistant può creare conflitti e rendere arresto anomalo l&#39;applicazione all&#39;avvio o all&#39;apertura di un file di progetto. Aggiornare l&#39;applicazione Autodesk per risolvere il problema. |
| <b> computer Alienware/Dell</b> | Per ulteriori informazioni, vedere questa pagina: [Arresto anomalo durante l&#39;apertura o il salvataggio di un file](../stability-issues/crash-when-opening-or-saving-a-file.md). |
| **APFS di Paragon Software** | È possibile che il software registri una posizione nella variabile di ambiente Percorso di Windows che può eseguire l&#39;arresto anomalo dell&#39;applicazione all&#39;avvio. La disinstallazione del software potrebbe non essere sufficiente e potrebbe essere necessario rimuovere manualmente la variabile di ambiente. Esempio di percorso problematico: `C:Program Files (x86)Paragon SoftwareAPFS for Windowsï–›éŒ à €è¸€ì‡ì‡ç¿¹` |
| **Avecto** | L’esecuzione di una versione precedente di Avecto può causare rallentamenti e arresti anomali. Assicurati di aggiornarlo alla versione più recente. |
| **Asus GPU Tweak** | Questo software può causare problemi durante la compilazione degli shader all&#39;interno di Substance 3D Painter o addirittura impedire l&#39;avvio della compilazione dello shader. Se si verifica questo problema, si consiglia di disinstallare il software per vedere se il problema viene risolto. |
| **Asus RAMCache** | Questo software potrebbe impedire il corretto avvio di Substance 3D Painter o renderlo instabile durante l&#39;esecuzione. Se riscontri problemi di stabilità, ti consigliamo di disabilitare o installare Asus RAMCache. |
| **Asus Sonic Suite** | Sui computer con una scheda madre ASUS, <b>Asus Sonic Suite</b> potrebbe essere installato per impostazione predefinita. La disinstallazione di questo software può risolvere alcuni problemi di visualizzazione/interfaccia in Substance 3D Painter. |
| **Software di backup cloud** **(** OneDrive,**GDrive,** **Dropbox,** **Filestream, ecc.)** | Il software di backup cloud può essere la fonte di numerosi arresti anomali durante il salvataggio di un progetto. In tal caso, si consiglia di lavorare sul file di progetto e di salvarlo in una cartella non sincronizzata, copiando invece i file di progetto nuovamente nell’unità cloud una volta che le modifiche non saranno più apportate. |
| **Chitubox** | Questo software può creare un conflitto e arresto anomalo l&#39;applicazione quando si apre una finestra di dialogo di file (come aprire o salvare un progetto). Per evitare questo problema, è possibile disattivare l&#39;impostazione <b>Abilita anteprima miniature del modello desktop</b> nelle preferenze di Chitubox. |
| **Visualizzazione Duetto** | <b>Duet Display</b> è noto per la creazione di problemi dei driver GPU che possono influire sul comportamento di Substance 3D Painter. Si consiglia di disinstallarlo. |
| **Google Chrome** | Google Chrome può causare alcuni arresti anomali quando viene eseguito insieme a Substance 3D Painter. Per migliorare la stabilità di Substance 3D Painter, si consiglia di aggiornare Google Chrome e i driver della GPU. Se gli arresti anomali si verificano ancora, disattiva Accelerazione hardware in Google Chrome (che interromperà l’utilizzo della GPU da parte di Chrome). |
| **Software audio Nahimic** | <b>Nahimic</b> può bloccare o eseguire l&#39;arresto anomalo del Painter. Può essere utile interromperlo e aggiornarlo può anche evitare problemi. Nahimic esegue anche servizi in background che possono interferire con l&#39;applicazione e che potrebbero dover essere arrestati o disabilitati. |
| **Software Openshot Video** | <b>Il software Openshot Video</b> può creare un conflitto con Substance 3D Painter con le anteprime dello scaffale. L’aggiornamento di Openshot dovrebbe risolvere il problema. |
| **Programma di installazione** | Questa applicazione può generare una configurazione dell&#39;ambiente errata che causa un errore all&#39;avvio. Per ulteriori informazioni, vedere [Impossibile avviare l&#39;applicazione a causa di Qt](application-failed-to-start-because-of-qt.md). |
| **Rptr / Plays.tv** | <b>Rptr</b> (o <b>[Plays.tv](http://plays.tv/) </b>) è installato per impostazione predefinita con alcuni driver GPU. Questo software può creare instabilità e arresto anomalo dell&#39;applicazione. Si consiglia di disinstallare l’applicazione. |
| **RGBFusion** | Questo software può creare conflitti con i driver della tavoletta grafica, l&#39;arresto del processo può risolvere temporaneamente il problema o disinstallare RGBFusion per una correzione permanente. |
