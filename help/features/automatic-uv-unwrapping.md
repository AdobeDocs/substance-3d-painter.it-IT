---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/automatic-uv-unwrapping.html"
breadcrumb-title: ''
description: Scopri come utilizzare lo srotolamento UV automatico in Substance 3D Painter per generare automaticamente layout UV per i modelli 3D.
helpx_creative_field: ""
helpx_description: Painter > Features > Automatic UV Unwrapping
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Srotolamento UV automatico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '482'
ht-degree: 0%

---


# Srotolamento UV automatico

![](../assets/auto-unwrap-update-810.jpg)\
Lo srotolamento UV automatico consente di generare automaticamente Isole UV durante l’importazione di un modello 3D. Può essere usato per dipingere su modelli 3D che non hanno UV esistenti.

## Attivazione dello srotolamento UV automatico

![](../assets/uv-new-project.png)

Quando crei un nuovo progetto o reimporti una trama in un progetto esistente, assicurati che l’opzione &quot;Scorrimento automatico&quot; sia selezionata. Se è disattivata, il processo verrà ignorato e gli UV con trama rimarranno invariati.

## Impostazioni di srotolamento UV

![](../assets/unwrap-settings.png)

Quando importate una trama e usate il processo di apertura, sono disponibili le seguenti impostazioni. Alcune impostazioni sono disponibili tramite il pulsante Opzioni nell’interfaccia.

| Sezione | ***Impostazione*** | ***Descrizione*** |
| --- | --- | --- |
| **Annulla il contornamento della sequenza** | **Cuciture** | Controlla se le giunture (bordi Isola UV) devono essere generate solo per le trame che non le contengono o che vengono sempre rigenerate.Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Genera dati mancanti </strong> (impostazione predefinita): le trame mancanti verranno generate.</li><li data-preserve-html="true"><strong> Ricalcola tutti i </strong>: verranno generate giunture per tutte le trame.</li></ul> |
| **Isole UV** | Controlla se lo srotolamento UV deve essere generato da trame senza UV o da qualsiasi trama. Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Genera dati mancanti </strong> (impostazione predefinita): verrà generato lo srotolamento UV per le trame mancanti di UV.</li><li data-preserve-html="true"><strong> Ricalcola tutti i </strong>: verrà generato lo srotolamento UV per tutte le trame.</li></ul> |  |
| **Impacchettamento** | Controlla l’impacchettamento o il layout delle Isole UV delle trame.Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Genera dati mancanti </strong> (impostazione predefinita): Isole UV del pacchetto per trame mancanti di UV.</li><li data-preserve-html="true"><strong> Ricalcola tutti i </strong>: comprimi tutte le Isole UV.</li></ul> |  |
|  |  |  |
| **Personalizzazione del layout** | **Dimensioni margine** | Definisce la spaziatura tra le Isole UV. Questa impostazione applica una percentuale generale indipendente dalla risoluzione.Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Nessun margine </strong>: 0%</li><li data-preserve-html="true"><strong> piccolo </strong> (impostazione predefinita): 0,2%</li><li data-preserve-html="true"><strong> Medio </strong>: 0,5%</li><li data-preserve-html="true"><strong> grande </strong>: 1%</li></ul> |
|  | **Isola UV orientamento** | Controllare l’orientamento delle Isole UV durante l’impacchettamento.Valori possibili:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Non vincolato</strong> (impostazione predefinita): nessun vincolo applicato per calcolare l&#39;orientamento.</li><li data-preserve-html="true"><strong>Allinea alla trama 3D</strong>: imposta l’orientamento dell’Isola UV verso la direzione della trama</li></ul> |
|  |  |  |
| **Riquadri UV** | **Numero massimo di porzioni UV** | Se il flusso di lavoro Porzioni UV è attivato, queste impostazioni determinano il numero massimo di porzioni da produrre per la distribuzione nelle Isole UV. |
|  |  |  |
| **Ottimizzazione** | **Evitare Isole UV allungate** | Se questa opzione è attivata, le Isole UV considerate troppo lunghe verranno divise per migliorare l’utilizzo dello spazio della texture.Esempio di prima (in alto) e dopo (in basso): <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r10-column-c2_dynamic_grid_items_grid-cell_position-par_image" src="../assets/uv-before-after.jpg" width="400px"/></div> |

## Limitazioni note

Di seguito è riportato un elenco di limitazioni relative al processo di annullamento del wrapping:

* L’elaborazione di maglie poly di alta qualità può richiedere molto tempo.
* I vertici alle stesse coordinate vengono uniti
* In alcuni rari casi, la generazione UV può non riuscire su alcune parti della trama
* Rapporto testel non uniforme o altamente distorto in una singola Isola UV in alcuni casi
* Proporzioni di testo non uniformi tra insiemi di texture
* Le Isole UV generate possono essere molto allungate e in alcuni casi non si adattano allo spazio UV
* Le facce degenerate o le facce con trama non triangolare con bordi piccoli o sovrapposti potrebbero non ottenere UV non avvolto
