---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/dynamic-strokes/enabling-dynamic-stroke-feature.html"
breadcrumb-title: ''
description: Scoprite come attivare la funzione tratto dinamico in Substance 3D Painter per creare tratti di pennello reattivi con effetti variabili.
helpx_creative_field: ""
helpx_description: Painter > Painting > Dynamic strokes > Enabling Dynamic Stroke Feature
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Abilitazione della funzione Tratto dinamico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '448'
ht-degree: 2%

---


# Abilitazione della funzione Tratto dinamico

Per abilitare la funzione Tratti dinamici è necessaria prima una risorsa specifica.

## Ricerca di risorse compatibili con i Tratti dinamici

Durante l&#39;esplorazione della finestra [Risorse](../../interface/assets/assets.md), un&#39;icona dedicata in basso a destra di una miniatura indica il tipo di compatibilità della risorsa. Se non è visibile alcuna icona significa che la risorsa non può sfruttare la funzione.

| *Icona* | *Descrizione* |
| --- | --- |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-dyn.png"/></div> | Questa risorsa può utilizzare uno o più dei seguenti comportamenti:<ul data-preserve-html="true"><li data-preserve-html="true">Indice timbro</li><li data-preserve-html="true">Ora</li><li data-preserve-html="true">Random Seed</li></ul> |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/icon-random.png"/></div> | Questa risorsa espone solo il parametro Numero casuale. |

È anche possibile cercare le risorse utilizzando il campo di ricerca nello scaffale con le seguenti parole chiave:

* tratto dinamico
* casuale

## Parametri tratti dinamici

![](../../assets/dynamic-strokes-settings.png)

Quando una risorsa Traccia dinamica è stata caricata, viene aggiunto un nuovo elenco di parametri prima del gruppo di parametri Substance.

| *Parametro* | *Descrizione* |
| --- | --- |
| **Controlli dinamici** | Elencare i parametri disponibili con il file di Substance attualmente utilizzato. |
| **Inizio timbro** | Disponibile solo se la risorsa dispone del controllo dinamico Indice timbro. Indica il valore a partire dal quale deve iniziare l’indice dei timbri all’interno del tratto del pennello:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Dall&#39;inizio (0)</strong>: impostazione predefinita. L’indice inizia da zero a ogni nuovo tratto.</li> <li data-preserve-html="true"><strong>Da indice casuale</strong>: l&#39;indice inizia da un valore casuale (con il massimo definito dal conteggio ciclo timbro). Si noti che i seguenti valori saranno ancora in sequenza e non completamente casuali.</li> </ul> |
| **Conteggio cicli timbro** | Disponibile solo se la risorsa dispone del controllo dinamico Indice timbro. Questi parametri controllano quando Substance 3D Painter deve interrompere la generazione di nuove variazioni di Substance e iniziare a riciclare quelle esistenti. Questo parametro ha un grande impatto sulle prestazioni, che potete leggere per saperne di più sulle [prestazioni dinamiche del tratto](dynamic-stroke-performances.md). |
| **Tipo di valore di inizializzazione casuale** | Disponibile solo se la risorsa ha il controllo dinamico &quot;Numero casuale&quot;. Controlla la modifica del valore di Numero casuale:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Singolo</strong>: impostazione predefinita. Usate un singolo valore di Numero casuale che può essere impostato manualmente tramite i parametri della Substance.</li> <li data-preserve-html="true"><strong>Casuale per tratto</strong>: genera un nuovo valore di Numero casuale per ogni nuovo tratto del pennello.</li> <li data-preserve-html="true"><strong>Casuale per timbro</strong>: genera un nuovo valore di numero casuale per ogni timbro all’interno di un tratto del pennello. <em><strong>Prestare attenzione ai parametri, in quanto possono essere molto costosi</strong>.</em></li> </ul> |
| **Ora** | Il controllo dinamico del tempo non dispone di alcun parametro. Il tempo dipende dalla durata del disegno di un tratto pennello. |

## Elenco degli strumenti compatibili

Le impostazioni di Traccia dinamica sono disponibili solo con gli strumenti e i contesti seguenti:

| *Tipo di strumento* | *Slot di risorse compatibile* |
| --- | --- |
| **Pittura** | <ul data-preserve-html="true"><li data-preserve-html="true">Alfa</li><li data-preserve-html="true">Materiale</li></ul> |
| **Gomma** | <ul data-preserve-html="true"><li data-preserve-html="true">Alfa</li><li data-preserve-html="true">Materiale</li></ul> |
| **Proiezione** | <ul data-preserve-html="true"><li data-preserve-html="true">Alfa</li></ul> |
| **Sfumino** | <ul data-preserve-html="true"><li data-preserve-html="true">Alfa</li></ul> |
| **Clona** | <ul data-preserve-html="true"><li data-preserve-html="true">Alfa</li></ul> |

>[!NOTE]
>
> I tratti dinamici non sono compatibili con **Particelle**, motivo per cui la funzione è disabilitata quando si utilizza uno strumento in modalità Fisica.
