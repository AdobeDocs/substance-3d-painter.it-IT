---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/pipeline-and-integration/installation-and-preferences/preferences-and-application-data-location.html"
breadcrumb-title: ''
description: Informazioni sulle preferenze e sui percorsi dei dati dell'applicazione per Substance 3D Painter per gestire le impostazioni e i dati degli utenti.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Installation and preferences > Preferences and application data location
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Preferenze e posizione dei dati dell’applicazione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 4%

---


# Preferenze e posizione dei dati dell’applicazione

Questa pagina raggruppa le informazioni sulla posizione in cui sono memorizzate le preferenze dell’applicazione, per versione e piattaforma.\
Può essere utile sapere dove vengono memorizzate le preferenze nel caso in cui si desideri aggiungere **scaffali personalizzati** (per le installazioni di studi di produzione) o rimuovere queste preferenze per eseguire una **installazione pulita** dell&#39;applicazione.

## Preferenze

Questo percorso indica la posizione delle preferenze dell’applicazione (scelte rapide salvate, percorsi degli scaffali/delle risorse, layout dell’interfaccia, ecc.).

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> </colgroup><tbody><tr><th>Sistema</th><th>Versione</th><th>Tracciato</th></tr><tr><td rowspan="2"><p><strong>Windows</strong></p><p>(Registro di sistema)</p></td><td><strong>7.2</strong> o versioni successive</td><td>HKEY_CURRENT_USER\Software\Adobe\Adobe Substance 3D Painter</td></tr><tr><td>Precedente</td><td>HKEY_CURRENT_USER\Software\Allegorithmic\Substance Painter</td></tr><tr><td rowspan="2"><p><strong>Mac</strong></p><p>(libreria)</p></td><td><strong>7.2</strong> o versioni successive</td><td>/Utenti/[nome utente]/Library/Preferences/com.adobe.Adobe Substance 3D Painter.plist</td></tr><tr><td>Precedente</td><td>/Utenti/[nome utente]/Library/Preferences/com.substance3d.Substance Painter.plist</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td><strong>7.2</strong> o versioni successive</td><td>/home/[nome utente]/.config/Adobe/Adobe Substance 3D Painter.conf</td></tr><tr><td>Precedente</td><td>/home/[nome utente]/.config/Allegorithmic/Substance Painter.conf</td></tr></tbody></table>

## Dati applicazione

Questo percorso indica la posizione dei dati aggiuntivi dell&#39;applicazione (miniature di Assets, file di registro e così via).

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>Piattaforma</th><th>Versione</th><th colspan="2">Tracciato</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>7.2</strong> o versioni successive</td><td colspan="1">Dati app (locale)</td><td colspan="1">C:\Users\[nome utente]\AppData\Local\Adobe\Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Dati app (roaming)</td><td colspan="1">C:\Users\[nome utente]\AppData\Roaming\Adobe\Adobe Substance 3D Painter</td></tr><tr><td rowspan="2">Precedente</td><td colspan="1">Dati app (locale)</td><td colspan="1">C:\Users\[nome utente]\AppData\Local\Allegorithmic\Substance Painter</td></tr><tr><td colspan="1">Dati app (roaming)</td><td colspan="1">C:\Users\[nome utente]\AppData\Roaming\Allegorithmic\Substance Painter</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="2">/Utenti/[nome utente]/Libreria/Application Support/Adobe/Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Precedente</td><td colspan="2">/Utenti/[nome utente]/Libreria/Application Support/Allegorithmic/Substance Painter</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="2">/home/[nome utente]/.local/share/Adobe/Adobe Substance 3D Painter</td></tr><tr><td>Precedente</td><td colspan="2">/home/[nome utente]/.local/share/Allegorithmic/Substance Painter</td></tr></tbody></table>

>[!NOTE]
>
> Alcune delle directory nei percorsi sopra menzionati potrebbero essere nascoste per impostazione predefinita. Digitate il percorso manualmente in Esplora file o visualizzate i file nascosti per visualizzarli.
