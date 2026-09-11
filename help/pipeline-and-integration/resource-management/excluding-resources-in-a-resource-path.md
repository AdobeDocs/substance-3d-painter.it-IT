---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/pipeline-and-integration/resource-management/excluding-resources-in-a-resource-path.html"
breadcrumb-title: ''
description: Scopri come escludere risorse specifiche dai percorsi delle risorse in Substance 3D Painter per una migliore organizzazione degli scaffali.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Resource management > Excluding resources in a resource path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Esclusione di risorse in un percorso di risorsa
user-guide-description: ''
user-guide-title: ''
source-git-commit: 22871eab2f25d09bd82f1292d8b3e5f8c4f1c2cf
workflow-type: tm+mt
source-wordcount: '451'
ht-degree: 0%

---


# Esclusione di risorse in un percorso di risorsa

In questa pagina viene illustrato come configurare un file Ignora per specificare le risorse e le cartelle che verranno ignorate durante la ricerca per indicizzazione della finestra [Risorse](../../interface/assets/assets.md). Consente di evitare la visualizzazione di risorse indesiderate.

>[!NOTE]
>
> Questa funzionalità è disponibile dalla versione 7.2.3.

## Creazione di un file Ignora

Passare alla posizione della cartella delle risorse in cui si desidera nascondere le risorse. Quindi crea un file con il nome seguente:

```
.ignore_assets_pt
```


>[!NOTE]
>
> Il nome del file deve iniziare con un punto.

Una volta creato, dovrebbe essere simile al seguente:

![](../../assets/ignore-file-location.png)

## Esempio

Il contenuto del file seguente eliminerà tutte le risorse e le cartelle diverse dalle cartelle di libreria predefinite:

```
## exclude all

* 

 

## re-include library directories

!alphas 

!colorluts 

!effects 

!emitters 

!environments 

!export-presets 

!generators 

!materials 

!presets 

!procedurals 

!receivers 

!shaders 

!smart-masks 

!smart-materials 

!templates 

!textures
```


## Regole e linee guida

Nella tabella seguente vengono illustrate le regole generali applicabili al file Ignora.

>[!NOTE]
>
> La corrispondenza dei pattern del file di ignora distingue tra maiuscole e minuscole, indipendentemente dal comportamento del sistema operativo.

| Regola | Descrizione | Esempio |
| --- | --- | --- |
| **Riga vuota** | Riga vuota che non corrisponde a nulla. Può essere usato come separatore per la leggibilità. |  |
| **Separatore di directory** | La barra viene utilizzata come separatore di directory. I separatori possono trovarsi all’inizio, al centro o alla fine di un pattern di ricerca.Se all&#39;inizio o al centro del pattern è presente un separatore (o entrambi), il pattern è relativo al livello di directory del file ignora stesso. In caso contrario, il pattern potrebbe anche corrispondere a qualsiasi livello al di sotto del livello di file ignora. Se alla fine del pattern è presente un separatore, questo verrà ignorato; il pattern continuerà a corrispondere sia ai file che alle directory. | `folder/filename.extension   folder/sub-folder` |
| **Riga commento** | Una riga che inizia con il simbolo di numero (o hash) funge da commento. | `# This is a comment` |
| **Asterisco** | Un asterisco corrisponde a tutto tranne una barra. | `# Match anything starting with Alpha   alpha*   # Match any file with given extension   *.jpg` |
| **Intervallo caratteri** | È possibile specificare un intervallo di caratteri compreso tra parentesi quadre in modo che corrisponda ai nomi di file e cartelle.<ul data-preserve-html="true"> <li data-preserve-html="true"><b>[abc]</b>: corrisponde a un carattere nell&#39;elenco specificato</li> <li data-preserve-html="true"><b>[a-c]</b>: corrisponde a un carattere nell&#39;intervallo specificato</li> <li data-preserve-html="true"><b>[!abc]</b>: trovare un carattere non nell&#39;elenco specificato</li> <li data-preserve-html="true"><b>[!a-c]</b>: trova un carattere non compreso nell&#39;intervallo specificato</li> </ul>L&#39;intervallo e l&#39;elenco possono essere anche numeri con il formato <b>[0-9]</b>. | `# Exclude any UDIM image in PNG   *_[0-9][0-9][0-9][0-9].png` |
| **Carattere di fuga** | Indicare caratteri letterali che verrebbero altrimenti ignorati o utilizzati come regole. | `# This is a comment   [#]This/Is/A/Path` |
| **Spazi finali** | Gli spazi finali vengono ignorati a meno che non siano preceduti da escape. | `# Match a subfolder with trailing space   folder/subfolder[ ]` |
| **Prefisso esclamativo** | La preimpostazione di un pattern con un punto esclamativo consente di annullarlo.Qualsiasi file corrispondente escluso da un criterio precedente verrà nuovamente incluso. Non è possibile includere nuovamente un file se una directory principale del file viene esclusa. La ricerca per indicizzazione non elenca le directory escluse per motivi legati alle prestazioni, pertanto i pattern sui file contenuti non hanno alcun effetto, indipendentemente dalla loro definizione. | `# Re-include specific file   !my_file_name.png` |
