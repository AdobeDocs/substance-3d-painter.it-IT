---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/pipeline-and-integration/resource-management/adding-saved-searches-manually.html"
breadcrumb-title: ''
description: Scopri come aggiungere manualmente ricerche salvate in Substance 3D Painter per accedere rapidamente ai filtri per le risorse utilizzati più di frequente.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Resource management > Adding saved searches manually
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Aggiunta manuale di ricerche salvate
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 2%

---


# Aggiunta manuale di ricerche salvate

Le query di ricerca delle risorse (o ricerche salvate) possono essere definite modificando un file di configurazione. Questa pagina spiega come.

## Posizione del file di configurazione

Per aggiungere query salvate personalizzate, passare alla cartella Documenti dell&#39;utente e aprire il file **Shelf.ini**.

<table data-preserve-html="true" style="width: 100.0%;"> <colgroup> <col style="width: 15.0%;"/> <col style="width: 15.0%;"/> <col style="width: 70.0%;"/> </colgroup> <tbody> <tr> <th>Piattaforma</th> <th>Versione</th> <th>Tracciato</th> </tr> <tr> <td rowspan="2"><strong>Windows</strong></td> <td><strong>7.2</strong> o versioni successive</td> <td colspan="1">C:\Users\username\Documents\Adobe\Adobe Substance 3D Painter</td> </tr> <tr> <td colspan="1">Precedente</td> <td colspan="1">C:\Users\username\Documents\Allegorithmic\Substance Painter</td> </tr> <tr> <td rowspan="2"><strong>Mac</strong></td> <td colspan="1"><strong>7.2</strong> o versioni successive</td> <td colspan="1">/Utenti/nome utente/Documenti/Adobe/Adobe Substance 3D Painter</td> </tr> <tr> <td colspan="1">Precedente</td> <td colspan="1">/Utenti/nomeutente/Documenti/Allegorithmic/Substance Painter</td> </tr> <tr> <td rowspan="2"><strong>Linux</strong></td> <td colspan="1"><strong>7.2</strong> o versioni successive</td> <td colspan="1">/home/nomeutente/Documenti/Adobe/Adobe Substance 3D Painter</td> </tr> <tr> <td>Precedente</td> <td colspan="1">/home/nomeutente/Documenti/Allegorithmic/Substance Painter</td> </tr> </tbody> </table>

## Esempio

Di seguito è riportato un esempio di contenuto che può essere inserito nel file di configurazione:

```
[filters] 

size=4 

1name=Grunge 

1query="u:basematerial=,smartmaterial=,smartmask=,texture=,procedural=,brush=,alpha= grunge" 

2name=Procedural 

2query="u:procedural=" 

3name=Environment 

3query="u:environment=" 

4name=Default Filters 

4query="p:/allegorithmic/^ u:filters="
```


Ecco come funziona la sintassi:

* **Dimensioni**: determina il numero di predefiniti personalizzati che l&#39;applicazione deve leggere e caricare.
* **Numero**: all&#39;inizio della riga definisce il predefinito corrente a cui è destinato (ad esempio: **1/**).
* **Query**: (dopo il numero) definisce i termini di ricerca effettivi utilizzati. Nell&#39;esempio viene utilizzato **u:** per gli usi, **p:** per i percorsi o una stringa per un termine di ricerca. Il contenuto della query deve essere racchiuso tra virgolette. Per ulteriori informazioni sui termini che è possibile utilizzare, [vedere questa pagina](../../interface/assets/advanced-search-queries.md).
* **Nome**: il nome del predefinito.
