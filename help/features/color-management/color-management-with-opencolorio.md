---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/features/color-management/color-management-with-opencolorio.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la gestione colore OpenColorIO in Substance 3D Painter per flussi di lavoro di colore coerenti tra le pipeline.
helpx_creative_field: ""
helpx_description: Painter > Features > Color management > Color management with OpenColorIO
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Gestione del colore con OpenColorIO
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '675'
ht-degree: 8%

---


# Gestione del colore con OpenColorIO

Questa pagina elenca le impostazioni di gestione del colore relative a OpenColorIO (OCIO).

## Impostazioni progetto

![](../../assets/project-settings-3.png)

Le impostazioni del progetto possono essere impostate durante la creazione di un nuovo progetto tramite la finestra [nuovo progetto](../../getting-started/project-creation.md) o la finestra [configurazione del progetto](../../interface/project-configuration.md).

>[!NOTE]
>
> Se la variabile di ambiente **OCIO** è presente e specifica un file di configurazione valido, le impostazioni nell&#39;interfaccia utente verranno ignorate e disabilitate.

Le impostazioni disponibili sono:

<table data-preserve-html="true" style="width: 99.9039%;"><colgroup><col style="width: 12.512%;"/><col style="width: 21.1742%;"/><col style="width: 66.3122%;"/></colgroup><tbody><tr><th style="width: 12.5%;">Sezione</th><th style="width: 21.1538%;">Impostazione</th><th style="width: 66.25%;">Descrizione</th></tr><tr><td rowspan="3" style="width: 12.5%;"><strong>Configurazione</strong></td><td style="width: 21.1538%;"><strong>Gestione del colore</strong></td><td style="width: 66.25%;"><p>Definite il motore da utilizzare per gestire i colori.</p><p>Valori possibili:</p><ul><li><strong>Precedente</strong> (impostazione predefinita): utilizza la correzione del colore gamma sRGB/Linear sRGB predefinita.</li><li><strong>OpenColorIO</strong>: utilizza l'integrazione OCIO.</li><li><strong>Adobe ACE</strong>: Adobe Color Engine per il supporto dei profili ICC.</li></ul></td></tr><tr><td style="width: 21.1538%;"><strong>Configurazione OpenColorIO</strong></td><td style="width: 66.25%;"><p>File di configurazione da utilizzare per le impostazioni di gestione del colore.</p><p>Valori possibili:</p><ul><li><strong>Substance</strong> (impostazione predefinita): utilizza la gamma lineare come spazio di lavoro.</li><li><strong>ACES 1.0.3</strong>: utilizzare ACEScg come spazio di lavoro.</li><li><strong>ACES 1.2</strong>: utilizzare ACEScg come spazio di lavoro.</li><li><strong>Personalizzato</strong>: utilizza un file di configurazione personalizzato.</li></ul></td></tr><tr><td style="width: 21.1538%;"><strong>File di configurazione</strong></td><td style="width: 66.25%;">Percorso del file di configurazione OCIO. Disabilitato se la modalità di configurazione non è impostata su <strong>Personalizzato</strong>.</td></tr><tr><th style="width: 12.5%;"><br/></th><th style="width: 21.1538%;"><br/></th><th style="width: 66.25%;"><br/></th></tr><tr><td rowspan="2" style="width: 12.5%;"><strong>Impostazioni del colore</strong></td><td style="width: 21.1538%;"><strong>Spazio cromatico di lavoro</strong></td><td style="width: 66.25%;">Spazio cromatico utilizzato dal motore per lavorare all'interno dell'applicazione. Spazio colore da cui è possibile convertire le texture in (importazione) o da (esportazione).</td></tr><tr><td colspan="1"><strong>Spazio cromatico sRGB standard</strong></td><td colspan="1"><p>Spazio colore corrispondente allo spazio colore [standard sRGB](https://en.wikipedia.org/wiki/SRGB) (IEC 61966-2-1:1999).</p><p>Questo spazio colore viene utilizzato in diversi punti all’interno dell’applicazione:</p><ul><li>Per convertire il set di colori nel campo esadecimale del selettore colore.</li><li>Per salvare e caricare i campioni di colore nel selettore colore.</li><li>Da elencare come visualizzazione nell'elenco del selettore colore.</li></ul></td></tr><tr><th style="width: 12.5%;"><br/></th><th style="width: 21.1538%;"><br/></th><th style="width: 66.25%;"><br/></th></tr><tr><td rowspan="4" style="width: 12.5%;"><strong>Impostazioni predefinite dello spazio cromatico per l'importazione bitmap</strong></td><td style="width: 21.1538%;"><strong>Immagini a 8 bit</strong></td><td style="width: 66.25%;">Spazio colore da usare per impostazione predefinita durante l’importazione di file di immagine a 8 bit.</td></tr><tr><td style="width: 21.1538%;"><strong>Immagini a 16 bit</strong></td><td style="width: 66.25%;">Spazio colore da usare per impostazione predefinita durante l’importazione di file di immagine a 16 bit.</td></tr><tr><td style="width: 21.1538%;"><strong>Immagini a virgola mobile</strong></td><td style="width: 66.25%;">Spazio colore da usare per impostazione predefinita durante l’importazione di file di immagine HDR/EXR.</td></tr><tr><td style="width: 21.1538%;"><strong>Rilevamento automatico degli spazi cromatici</strong></td><td style="width: 66.25%;"><p>Consente di definire lo spazio colore dalle risorse in base a impostazioni specifiche.</p><p>Valori possibili:</p><ul><li><strong>Disabilitato</strong>: utilizzare l'impostazione di colore predefinita e ignorare la configurazione della risorsa.</li><li><strong>Analizza nome file</strong> (impostazione predefinita): utilizzare OCIO [convenzione di denominazione](https://opencolorio.readthedocs.io/en/latest/guides/authoring/rules.html?highlight=filename#strictparsing) per estrarre il nome dello spazio colore utilizzato dalla risorsa.</li><li><strong>Utilizza regole file di configurazione</strong>: utilizza la configurazione OCIO per determinare come assegnare gli spazi colore. Questo parametro ha la priorità sulle impostazioni dello spazio colore del file di immagine precedente.</li></ul></td></tr><tr><th style="width: 12.5%;"><br/></th><th style="width: 21.1538%;"><br/></th><th style="width: 66.25%;"><br/></th></tr><tr><td style="width: 12.5%;"><strong>Substance materiale</strong></td><td style="width: 21.1538%;"><strong>Spazio cromatico del materiale predefinito</strong></td><td style="width: 66.25%;"><p>Definisci lo spazio colore da usare per i materiali Substance per l’input/output con gestione del colore (vedi di seguito per l’elenco dei canali).</p></td></tr><tr><th style="width: 12.5%;"><br/></th><th style="width: 21.1538%;"><br/></th><th style="width: 66.25%;"><br/></th></tr><tr><td rowspan="3" style="width: 12.5%;"><strong>Esporta gli spazi cromatici</strong><br/><br/><br/></td><td style="width: 21.1538%;"><strong>Immagini a 8 bit</strong></td><td style="width: 66.25%;">Spazio colore da usare per impostazione predefinita durante l’esportazione di file di immagini a 8 bit.</td></tr><tr><td style="width: 21.1538%;"><strong>Immagini a 16 bit</strong></td><td style="width: 66.25%;">Spazio colore da usare per impostazione predefinita durante l’esportazione di file di immagine a 16 bit.</td></tr><tr><td style="width: 21.1538%;"><strong>Immagini a virgola mobile</strong></td><td style="width: 66.25%;">Spazio colore da usare per impostazione predefinita durante l’esportazione di file di immagine HDR/EXR.</td></tr></tbody></table>

### Ruoli OpenColorIO

I seguenti ruoli sono supportati e consentono di modificare la selezione predefinita degli spazi colore:

| Nome ruolo | Descrizione |
| --- | --- |
| **substance\_3d\_painter\_standard\_srgb** | Ruolo per specificare lo spazio colore corrispondente allo standard [sRGB](https://en.wikipedia.org/wiki/SRGB) (IEC 61966-2-1:1999). |
| **substance\_3d\_painter\_bitmap\_import\_8bit** | Ruolo per specificare lo spazio colore utilizzato per importare immagini a 8 bit. |
| **substance\_3d\_painter\_bitmap\_import\_16bit** | Ruolo per specificare lo spazio colore utilizzato per importare immagini a 16 bit. |
| **substance\_3d\_painter\_bitmap\_import\_floating** | Ruolo per specificare lo spazio colore utilizzato per importare le immagini HDR. |
| **substance\_3d\_painter\_substance\_material** | Ruolo per specificare lo spazio cromatico utilizzato per i canali con gestione del colore nei materiali per Substance. |
| **substance\_3d\_painter\_bitmap\_export\_8bit** | Ruolo per specificare lo spazio colore utilizzato durante l’esportazione di texture a 8 bit. |
| **substance\_3d\_painter\_bitmap\_export\_16bit** | Ruolo per specificare lo spazio colore utilizzato per esportare le texture a 16 bit. |
| **substance\_3d\_painter\_bitmap\_export\_floating** | Ruolo per specificare lo spazio colore utilizzato durante l’esportazione delle texture HDR. |

>[!NOTE]
>
> Le configurazioni OCIO fornite con l&#39;applicazione possono essere utilizzate come esempi su come utilizzare questi ruoli specifici.
