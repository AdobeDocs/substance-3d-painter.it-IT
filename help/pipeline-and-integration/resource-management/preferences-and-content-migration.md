---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/pipeline-and-integration/resource-management/preferences-and-content-migration.html"
breadcrumb-title: ''
description: Scopri come migrare le preferenze e i contenuti in Substance 3D Painter durante l'aggiornamento o il passaggio a un nuovo sistema.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Resource management > Preferences and content migration
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Migrazione di preferenze e contenuti
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '484'
ht-degree: 1%

---


# Migrazione di preferenze e contenuti

Questa pagina descrive come migrare i dati dalle preferenze e da Shelf/Assets per utilizzarli nelle nuove versioni.

Dopo il rilascio della versione 7.2, le preferenze e la posizione dello scaffale sono state modificate per renderle comuni a più versioni dell’applicazione (Substance 3D standalone, Steam e Creative Cloud Desktop). Questa modifica indica che le preferenze precedenti e le risorse personalizzate **sono state ignorate** per impostazione predefinita (**ma non perse**). Poiché lo **scaffale** è stato rinominato **Risorse**, la migrazione richiede alcuni passaggi descritti di seguito.

## Migrazione delle risorse di shelf e asset

Il percorso delle risorse dell&#39;utente predefinito è stato modificato, il che significa che qualsiasi contenuto inserito nella cartella Documenti viene ora ignorato dalle nuove versioni dell&#39;applicazione. Per ripristinare questo contenuto basta spostare i file da una posizione all&#39;altra.

### Dove trovare il contenuto

Il percorso Shelf o Assets si trova nei seguenti percorsi:

<table data-preserve-html="true" style="width: 100.0%;"><colgroup> <col style="width: 15.0%;"/> <col style="width: 15.0%;"/> <col style="width: 70.0%;"/> </colgroup><tbody><tr><th>Piattaforma</th><th>Versione</th><th>Tracciato</th></tr><tr><td rowspan="2"><strong>Windows</strong></td><td><strong>7.2</strong> o versioni successive</td><td colspan="1">C:\Users\username\Documents\Adobe\Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Precedente</td><td colspan="1">C:\Users\username\Documents\Allegorithmic\Substance Painter</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="1">/Utenti/nome utente/Documenti/Adobe/Adobe Substance 3D Painter</td></tr><tr><td colspan="1">Precedente</td><td colspan="1">/Utenti/nomeutente/Documenti/Allegorithmic/Substance Painter</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>7.2</strong> o versioni successive</td><td colspan="1">/home/nomeutente/Documenti/Adobe/Adobe Substance 3D Painter</td></tr><tr><td>Precedente</td><td colspan="1">/home/nomeutente/Documenti/Allegorithmic/Substance Painter</td></tr></tbody></table>

### Come migrare il contenuto dello scaffale

Il vecchio contenuto dello scaffale è costituito solo da file sul disco, quindi la loro migrazione consiste solo nel posizionare questi file nel posto giusto.

1. Chiudi l’applicazione
1. Passa alla cartella Scaffale precedente
1. Copia o taglia le sottocartelle (alfa, procedure, materiali, ecc.)
1. Passa alla nuova cartella Risorse
1. Incolla le sottocartelle copiate in precedenza all&#39;interno della cartella Risorse. Se richiesto, sovrascrivi.

Ora riavvia l’applicazione: il contenuto dovrebbe essere visualizzato nella finestra Risorse.

>[!NOTE]
>
> Assicurarsi di copiare le sottocartelle e non solo la cartella principale delle risorse. La cartella principale è stata rinominata da **scaffale** a **risorse**, pertanto la copia solo della cartella principale non renderà le risorse visibili all&#39;applicazione.

### Come migrare i predefiniti di shelf

I predefiniti di shelf vengono salvati all&#39;interno di un file di configurazione. Per migrare questi predefiniti:

1. Chiudi l’applicazione
1. Passa alla cartella Scaffale precedente
1. Copiare o tagliare il file Shelf.ini
1. Passa alla nuova cartella Risorse
1. Incolla il file e sovrascrivi quello esistente

Ora riavvia l’applicazione, le ricerche salvate vengono visualizzate nella sezione dedicata o nella finestra Risorse.

## Migrazione delle preferenze

Si consiglia di regolare manualmente le impostazioni dell’applicazione dall’interfaccia. Questo è il modo più sicuro per migrare le informazioni senza introdurre problemi di compatibilità.

Altrimenti consulta la pagina seguente per sapere dove si trovano le preferenze: [Preferenze e percorso dei dati dell&#39;applicazione](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/application-preferences-location-147095594.html).
