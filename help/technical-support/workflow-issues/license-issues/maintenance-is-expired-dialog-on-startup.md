---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/workflow-issues/license-issues/maintenance-is-expired-dialog-on-startup.html"
breadcrumb-title: ''
description: Scopri come risolvere la finestra di dialogo Manutenzione scaduta che viene visualizzata all'avvio in Substance 3D Painter per la gestione delle licenze.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Workflow Issues > License Issues > Maintenance is expired dialog on startup
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Finestra di dialogo Manutenzione scaduta all'avvio
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '410'
ht-degree: 1%

---


# Finestra di dialogo Manutenzione scaduta all&#39;avvio

![](../../../assets/expired-mainteance-message.png)

Quando si avvia l’applicazione, potrebbe essere visualizzata una finestra di dialogo con il messaggio &quot;La manutenzione corrente è scaduta&quot;. In questa pagina sono elencate le soluzioni per evitare questa finestra di dialogo.

## Soluzione 1: aggiornare il file di licenza

Il messaggio di avviso viene visualizzato perché il file di licenza è troppo vecchio e deve essere aggiornato. A tale scopo, è sufficiente **riattivare il prodotto** tramite la procedura guidata dell&#39;applicazione. Il file di licenza può anche essere scaricato manualmente tramite il sito Web Substance 3D: <https://www.substance3d.com/>.

## Soluzione 2: modificare le impostazioni delle preferenze per nascondere la finestra di dialogo

>[!NOTE]
>
> Si consiglia di provare ad aggiornare il file di licenza prima di utilizzare questa soluzione alternativa.

Un’altra soluzione consiste nel nascondere il messaggio di avviso inserendo un’impostazione specifica.

Passare alla posizione delle preferenze dell&#39;applicazione:

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> </colgroup><tbody><tr><th>Sistema</th><th>Versione</th><th>Tracciato</th></tr><tr><td rowspan="2"><p><strong>Windows</strong></p><p>(Registro di sistema)</p></td><td><strong>7.2</strong> o versioni successive</td><td>HKEY_CURRENT_USER\Software\Adobe\Adobe Substance 3D Painter</td></tr><tr><td>Precedente</td><td>HKEY_CURRENT_USER\Software\Allegorithmic\Substance Painter</td></tr><tr><td rowspan="2"><p><strong>Mac</strong></p><p>(libreria)</p></td><td><strong>7.2</strong> o versioni successive</td><td>/Utenti/[nome utente]/Library/Preferences/com.adobe.Adobe Substance 3D Painter.plist</td></tr><tr><td>Precedente</td><td>/Utenti/[nome utente]/Library/Preferences/com.substance3d.Substance Painter.plist</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td><strong>7.2</strong> o versioni successive</td><td>/home/[nome utente]/.config/Adobe/Adobe Substance 3D Painter.conf</td></tr><tr><td>Precedente</td><td>/home/[nome utente]/.config/Allegorithmic/Substance Painter.conf</td></tr></tbody></table>

### Windows

Per impostare la variabile su Windows, effettuate le seguenti operazioni:

1. Aprire il menu Start.
1. Cerca **Regedit** per aprire l&#39;editor del Registro di sistema.
1. Accedi alla chiave del Registro di sistema elencata nella tabella precedente.
1. Fare clic sulla chiave del Registro di sistema denominata software nella struttura a sinistra.
1. Fai clic con il pulsante destro del mouse nell&#39;area vuota del pannello a destra e scegli **Nuovo > Valore stringa**.
1. Assegna al nuovo valore il nome **DisableLicenseWarningPopup** e premi Invio per la convalida.
1. Fai doppio clic sul valore appena creato.
1. Imposta il campo dati Valore su: **true**
1. Salva la modifica.
1. Avviare l&#39;applicazione.

### MacOS

1. Apri una nuova finestra **Finder**
1. Accedete al percorso elencato nella tabella precedente.
1. Fai clic con il pulsante destro del mouse sul file **plist** e scegli **Apri con > Xcode**.
1. Nella parte superiore dell&#39;elenco, aggiungi una nuova chiave denominata **DisableLicenseWarningPopup**
1. Imposta il tipo di chiave su **stringa**
1. Imposta il valore della chiave su **true**
1. Salvate e chiudete il file.
1. Avviare l&#39;applicazione.

### Linux

Per impostare la variabile su Linux, attenersi alla seguente procedura:

1. Passare all&#39;elenco dei percorsi nella tabella precedente.
1. Apri il file **.conf** presente nella cartella.
1. Aggiungere una nuova riga sotto la riga **[Generale]**
1. Nella nuova riga incollare il testo seguente: **DisableLicenseWarningPopup=true**
1. Salva il file.
1. Avviare l&#39;applicazione.
