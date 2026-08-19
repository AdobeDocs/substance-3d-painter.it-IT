---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/getting-started/activation-and-licenses.html"
breadcrumb-title: ''
description: Scoprite come attivare Substance 3D Painter e gestire le licenze per iniziare a utilizzare l'applicazione per la pittura di texture.
helpx_creative_field: ""
helpx_description: Painter > Getting Started > Activation and licenses
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Attivazione e licenze
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '482'
ht-degree: 1%

---


# Attivazione e licenze

Questa pagina contiene informazioni su come attivare e gestire le licenze per iniziare a utilizzare Painter.

## Processo di attivazione per tipo di applicazione

Il processo di attivazione dipende da dove hai acquistato o hai accesso a Painter:

| Tipo applicazione | Processo di attivazione |
| --- | --- |
| Creative Cloud desktop | Consulta la pagina dedicata nella [documentazione HelpX](https://helpx.adobe.com/it/download-install/using/download-creative-cloud-apps.html). In caso di problemi, la [documentazione di Creative Cloud](https://helpx.adobe.com/it/creative-cloud/user-guide.html) può fornire risposte aggiuntive. |
| Vapore | Avvia il prodotto direttamente dalla libreria Steam. |
| Substance 3D autonomo | Consulta il processo di attivazione descritto di seguito. |

## Passaggi di attivazione autonoma

### Attivazione guidata

L&#39;Attivazione guidata viene visualizzata in determinate versioni precedenti di Substance 3D Painter.

Se disponi di un file di licenza perpetua scaricato dal sito Web di Substance 3D prima del 30 settembre 2022, puoi comunque utilizzarlo per attivare le versioni idonee di Substance 3D Painter tramite l&#39;Attivazione guidata. [Ulteriori informazioni sulle licenze e gli account di Substance legacy sono disponibili qui.](https://substance3d.adobe.com/faq-end-of-life-accounts/)

![](../assets/activation-wizard.png){width="350px"}

L&#39;Attivazione guidata dispone di tre opzioni:

* <b>Valutazione del prodotto</b>: le versioni di prova precedenti non sono più disponibili. Puoi invece [avviare una versione di prova di 30 giorni per ogni applicazione Substance 3D qui](https://www.adobe.com/it/products/substance3d/free-trial-download.html?msockid=35568f9be2b964ec22d09c04e3eb65af) o con Creative Cloud Desktop.
* <b>Attivazione tramite un file di licenza</b>: attiva il prodotto con un file di licenza (<b>\*.key</b>) scaricato dalla pagina dell&#39;account nel sito Web di Substance 3D prima del 30 settembre 2022.
* <b>Attiva utilizzando il tuo account</b>: gli account Substance legacy non possono più essere utilizzati per l&#39;attivazione.

>[!WARNING]
>
> Per installare il file di licenza con l&#39;Attivazione guidata, assicurati di eseguire Painter come amministratore e di disattivare temporaneamente l&#39;antivirus.

### Attivazione manuale

È possibile attivare manualmente Substance Painter inserendo il file license.key nella seguente cartella:

>[!NOTE]
>
> Assicurati che il file sia denominato **license.key** altrimenti l&#39;applicazione non sarà in grado di trovarlo.

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>Piattaforma</th><th>Versione</th><th colspan="2">Tracciato</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>7.2</strong> o versioni successive</td><td colspan="1">Dati app (locale)</td><td colspan="1">C:\Users\[nome utente]\AppData\Local\Adobe\Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Dati app (roaming)</td><td colspan="1">C:\Users\[nome utente]\AppData\Roaming\Adobe\Adobe Substance 3D Painter</td></tr><tr><td rowspan="2">Precedente</td><td colspan="1">Dati app (locale)</td><td colspan="1">C:\Users\[nome utente]\AppData\Local\Allegorithmic\Substance Painter</td></tr><tr><td colspan="1">Dati app (roaming)</td><td colspan="1">C:\Users\[nome utente]\AppData\Roaming\Allegorithmic\Substance Painter</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="2">/Utenti/[nome utente]/Libreria/Application Support/Adobe/Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Precedente</td><td colspan="2">/Utenti/[nome utente]/Libreria/Application Support/Allegorithmic/Substance Painter</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="2">/home/[nome utente]/.local/share/Adobe/Adobe Substance 3D Painter</td></tr><tr><td>Precedente</td><td colspan="2">/home/[nome utente]/.local/share/Allegorithmic/Substance Painter</td></tr></tbody></table>

>[!NOTE]
>
> Alcune delle directory nei percorsi sopra menzionati potrebbero essere nascoste per impostazione predefinita. Digitate il percorso manualmente in Esplora file o visualizzate i file nascosti per visualizzarli.

### Variabile di ambiente

È possibile eseguire l&#39;override del percorso controllato da Painter per il file **license.key** con una [variabile di ambiente](../pipeline-and-integration/configuration/environment-variables.md).
