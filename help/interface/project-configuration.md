---
helpx_url: 'https://helpx.adobe.com/it/substance-3d-painter/interface/project-configuration.html'
breadcrumb-title: ''
description: Scoprite come configurare le impostazioni di progetto in Substance 3D Painter per impostare la risoluzione delle texture, i canali e le proprietà del progetto.
helpx_creative_field: ''
helpx_description: Painter > Interface > Project configuration
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Configurazione del progetto
user-guide-description: ''
user-guide-title: ''
source-git-commit: 3e4ef9bd5897f042b01d6c0819ec06cc21ba208a
workflow-type: tm+mt
source-wordcount: '839'
ht-degree: 3%

---


# Configurazione del progetto

![](../assets/project-configuration-full.png)

La finestra Configurazione progetto contiene i controlli per modificare le impostazioni del progetto. Le impostazioni del progetto vengono in genere impostate durante la creazione di un nuovo progetto, ma a volte può essere necessario modificarle successivamente nel progetto.

## Mesh 3D

Se sono state apportate modifiche alla trama 3D o al file mesh, potete reimportare la trama mantenendo gli altri dati del progetto. Controlla **Reimporta trama** e assicurati che sia stato importato il file corretto.

La reimportazione della trama è spesso utile quando è necessario:

* Aggiornare la topologia del modello 3D
* Aggiornare gli UV
* Aggiungi o rimuovi [set di texture](texture-set/texture-set.md)

| **Parametro** | **Descrizione** |
| --- | --- |
| **Trama 3D** | Indica il percorso del file del modello 3D. Utilizzare il **pulsante Seleziona** per modificare il file di origine per il progetto. |
| **Reimporta trama** | Se questa opzione è attivata, il file di trama viene reimportato quando si fa clic su OK nella parte inferiore dell’interfaccia. Questo parametro viene controllato automaticamente se il pulsante Seleziona (Select) viene utilizzato per specificare un file di trama diverso da quello originale. |

>[!NOTE]
>
> Se gli ID materiale cambiano o vengono rinominati durante la reimportazione della trama del progetto, i set di texture precedenti nel progetto possono diventare disattivati, dando l’aspetto di texture mancanti. Questo problema può essere risolto con la [finestra di riassegnazione](texture-set/texture-set-reassignment.md) dall&#39;**elenco set di texture**.

## Impostazioni progetto

Questa sezione controlla diverse impostazioni correlate al progetto:

<table>
  <tr>
    <th><em>Impostazione</em></th>
    <th><em>Descrizione</em></th>
  </tr>
  <tr>
    <td><strong>Formato mappa normale</strong></td>
    <td>Definisce il formato della mappa normale utilizzata per la trama nella finestra della vista. Questo parametro influisce solo sugli <a href="shader-settings/shader-settings.md">shader</a> nella finestra della vista e sulle mappe mesh nei <a href="../baking/baking.md">forni</a>. Il gruppo di livelli è indipendente. Valore consigliato per le applicazioni più comuni:<br><br><ul><li><strong>Unità</strong>: OpenGL</li><li><strong>Motore irreale</strong>: DirectX</li><li><strong>Maya</strong>: OpenGL</li><li><strong>3DS max</strong>: DirectX</li><li><strong>Blender</strong>: OpenGL</li></ul></td>
  </tr>
  <tr>
    <td><strong>Calcola lo spazio tangente per frammento</strong></td>
    <td>Determina come calcolare e visualizzare le mappe normali nella finestra della vista per l'ombreggiatura e l'illuminazione. Se questa opzione è attivata, la tangente e i binormali della trama verranno calcolati per pixel anziché per vertice.<br>Valore consigliato per le applicazioni comuni:<br><br><ul><li><strong>Unità</strong>: disattivata (abilitata se si utilizza HDRP)</li><li><strong>Motore Irreale</strong>: Abilitato</li></ul></td>
  </tr>
</table>

>[!NOTE]
>
> Per modificare il formato normale o il calcolo della tangente, è necessario eseguire nuovamente il baking delle mappe mesh per garantire che l&#39;aspetto nelle finestre sia corretto.

### Impostazioni specifiche per il tipo di file

Quando è selezionato un formato di trama USD, diventano disponibili altre impostazioni specifiche per il tipo di file.

![](../assets/image2023-1-30-11-16-6.png){width="473px"}

<table>
  <tr>
    <th><em>Parametro</em></th>
    <th><em>Descrizione</em></th>
  </tr>
  <tr>
    <td><strong>Ambito e varianti</strong></td>
    <td>Selezionare una parte specifica di un file USD. Per impostazione predefinita, è impostato su "Root", il che significa che l'intero file USD verrà utilizzato nel progetto Painter. <strong>Modifica...</strong> apre una nuova finestra che visualizza il contenuto dell'USD. Se vengono rilevate varianti, è possibile selezionare una variante specifica da caricare nel progetto.<br><br>Nota:<br><ul><li>Solo la selezione della variante di modellazione avrà un impatto.</li><li>Le varianti nidificate all'interno delle varianti non vengono attualmente rilevate.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Livello di suddivisione</strong></td>
    <td>Si applica alla geometria con suddivisione. Specificate l’entità di suddivisione della trama per la creazione di texture in Painter. Se la suddivisione è impostata in modo esplicito su 'none' all'interno del file USD, questa impostazione è disattivata. La suddivisione viene applicata dopo lo srotolamento UV, in modo che non alteri la forma degli UV della trama.</td>
  </tr>
  <tr>
    <td><strong>Cornice</strong></td>
    <td>Si applica agli USD in cui viene rilevata un’animazione. Seleziona il fotogramma che verrà caricato nel progetto Painter. Se nel file USD selezionato non è presente alcuna animazione, questa impostazione è disattivata.</td>
  </tr>
</table>

## Impostazioni porzioni UV

Questa sezione contiene i controlli per attivare/disattivare l’utilizzo di UDIM nel progetto. Non è possibile modificare queste impostazioni dopo la creazione del progetto, ma puoi visualizzare le impostazioni per il progetto qui. Per ulteriori informazioni, consultate la [documentazione sulle porzioni UV](../features/uv-tiles/uv-tiles.md).

## Impostazioni di importazione

Queste impostazioni controllano il modo in cui verrà importata la trama selezionata:

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Importa fotocamere** | Se questa opzione è attivata, anche le fotocamere presenti nel file con trama verranno importate e saranno disponibili nella finestra della vista 3D. |
| **Mantenere le posizioni dei tratti sulla trama** | Questa impostazione controlla il modo in cui i tratti del pennello verranno ricalcolati dopo l’importazione di una nuova trama 3D. Nella maggior parte dei casi si consiglia di mantenere attiva questa impostazione. Per ulteriori informazioni, consultate la documentazione sulla [riproiezione UV](../features/uv-reprojection.md). |
| **Annullamento automatico del wrapping** | Srotolamento UV automatico. Fare clic sul pulsante Opzione per configurare il processo. Per ulteriori informazioni, consulta la [documentazione per lo srotolamento automatico degli UV](../features/automatic-uv-unwrapping.md). |

### Dimensioni fisiche impostazioni

Regolate la [Dimensioni fisiche](../features/physical-size.md) della trama importata.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Usa scala unità interna del file mesh** | Se la trama è stata creata con misurazioni fisicamente accurate, lasciatela selezionata per mantenere la stessa dimensioni fisiche in Painter. |
| **Scala unità personalizzata** | Se la trama non è stata creata tenendo conto della dimensioni fisiche, utilizzate questa opzione per personalizzarne le dimensioni. Per determinare questo valore, dovete conoscere la dimensioni fisiche desiderata e la dimensione espressa in unità della trama importata. |
| **Imposta la scala del livello di riempimento su Dimensioni fisiche quando assegni i materiali** | Quando questa opzione è attivata, i livelli di riempimento e gli effetti passeranno automaticamente dal metodo di scala a Dimensioni fisiche quando si assegna un materiale con proprietà di Dimensioni fisiche. |

### Impostazioni per la gestione del colore

Questa sezione controlla le impostazioni relative alla conversione dei colori. Per ulteriori informazioni, consulta la documentazione [Gestione del colore](../features/color-management/color-management.md).
