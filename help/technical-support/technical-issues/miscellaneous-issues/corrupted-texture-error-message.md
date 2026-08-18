---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/miscellaneous-issues/corrupted-texture-error-message.html"
breadcrumb-title: ''
description: Scoprite come correggere i messaggi di errore danneggiati relativi alle texture in Substance 3D Painter per ripristinare la funzionalità delle texture.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Miscellaneous Issues > Corrupted texture error message
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Messaggio di errore di texture danneggiata
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '385'
ht-degree: 0%

---


# Messaggio di errore di texture danneggiata

Le texture danneggiate in un progetto causano errori durante il processo di salvataggio e possono portare a progetti completamente danneggiati e non recuperabili. Tuttavia, questo problema può essere risolto manualmente.\
Una risorsa danneggiata si manifesta nel registro quando si apre un progetto con un messaggio di errore simile a questo nella finestra del registro:

![](../../../assets/corrupt1.png)

## Correzione di un riferimento a una risorsa danneggiata

### 1 - Ricerca della risorsa

Il primo passaggio in cui compare un errore consiste nel trovare e identificare la risorsa all&#39;origine del problema.\
Nella maggior parte dei casi, il colpevole proviene dalle **mappe trama** (texture cotte). Un modo rapido per verificarlo è osservare i generatori di maschere nella pila di livelli.

Le risorse danneggiate avranno il seguente aspetto:

![](../../../assets/corrupt2.png)

>[!NOTE]
>
> Ciò potrebbe anche significare che la risorsa è semplicemente mancante.\
> Per assicurarti, prova a cancellare lo slot e a modificare manualmente il forno. Se la miniatura della croce rossa è ancora presente, significa che la risorsa è danneggiata.

### 2 - Sostituzione della risorsa

Per sostituire una risorsa danneggiata, è necessario rimuovere prima tutti i relativi riferimenti. Se la corrente è relativamente piccola, può essere eseguita manualmente.\
Tuttavia, se il progetto si estende su più set di texture o su molti livelli, [Resource Updater](../../../features/plugins/resources-updater.md)può essere utile per individuare la risorsa danneggiata e sostituirla temporaneamente con un&#39;altra.

>[!NOTE]
>
> * Nel caso delle texture cotte, non dimenticate di eliminare anche gli slot Mappe trama nella finestra [Impostazioni set texture](../../../interface/texture-set/texture-set-settings.md).
> * Anche i dolci usati solo nelle impostazioni del set di texture, come la mappa normale, potrebbero essere danneggiati. Provare a rimuoverli se gli errori persistono.

### 3 - Pulizia

Una volta eliminati tutti i riferimenti alle risorse danneggiate, esegui una pulizia del progetto dal menu principale (**File** > **Pulisci**).\
In questo modo verranno rimosse dal progetto tutte le risorse danneggiate non utilizzate. È possibile eseguire la verifica navigando nella scheda Progetto nello scaffale per assicurarsi che tutte le risorse problematiche siano scomparse.

### 4 - Risparmia

Dopo la pulizia, prova a salvare il progetto:

* Se viene salvato senza errori, il progetto ora è libero da danneggiamenti (le mappe trama possono essere ripristinate e le risorse reimportate).
* Se gli errori persistono, significa che esiste ancora un riferimento a una risorsa danneggiata nel progetto.
