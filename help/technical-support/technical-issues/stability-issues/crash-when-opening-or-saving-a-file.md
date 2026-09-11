---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/stability-issues/crash-when-opening-or-saving-a-file.html"
breadcrumb-title: ''
description: Scopri come correggere gli arresti anomali di Substance 3D Painter all’apertura o al salvataggio dei file per una gestione affidabile del progetto.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Stability Issues > Crash when opening or saving a file
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arresto anomalo di apertura o salvataggio di un file
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 0%

---


# Arresto anomalo di apertura o salvataggio di un file

Ci sono alcuni motivi per cui Substance 3D Painter dovrebbe arresto anomalo su Windows quando si apre una finestra di dialogo di file. In questa pagina vengono raggruppati i motivi e le soluzioni a questo problema.

## Conflitti software

Alcuni programmi possono aggiungere estensioni di shell personalizzate che possono causare instabilità o arresti anomali. Per ulteriori informazioni, esaminare l&#39;elenco [Conflitti software](../startup-issues/software-conflicts.md).

## Estensioni della shell/Temi personalizzati

I temi personalizzati non sono supportati dal nostro framework GUI, pertanto si consiglia vivamente di disinstallare il tema corrente prima di utilizzare Substance 3D Painter.

Per impostazione predefinita, i computer **Alienware** / **Dell** integrano alcune estensioni della shell che risultano incompatibili con Substance 3D Painter. Si consiglia di disinstallarli. Anche se non conosciamo esattamente tutte le estensioni che sono incompatibili, la maggior parte delle volte corrispondono a:

* Classe DBROverlayIconBackuped.DBROverlayIconBackuped
* Classe DBROverlayIconNotBackuped.DBROverlayIconNotBackuped

Puoi visualizzare le estensioni installate nel computer utilizzando lo strumento seguente. Ecco una procedura approssimativa su come procedere:

1. Scarica e installa ShellExView da NirSoft: <http://www.nirsoft.net/utils/shexview.html>
1. Eseguire il programma
1. Fai clic su **Opzione** e scegli **Filtra per tipo di estensione**
1. Seleziona **Gestore sovrapposizione icone**
1. Dovresti visualizzare le due voci per **Alien Respawn**.
1. Seleziona **entrambi** e fai clic sul pulsante rosso per disattivarli.
