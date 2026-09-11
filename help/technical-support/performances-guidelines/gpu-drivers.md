---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/performances-guidelines/gpu-drivers.html"
breadcrumb-title: ''
description: Scoprite i requisiti della GPU per l’VRAM e i driver per Substance 3D Painter per ottimizzare le prestazioni e la stabilità del rendering.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Performances guidelines > GPU Drivers
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: VRAM e driver GPU
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---


# Driver GPU

Non possiamo garantire prestazioni senza l&#39;uso di driver consigliati. È necessario evitare driver non WHQL.\
I driver GPU sono simili a quelli di qualsiasi software e ogni nuova versione può introdurre problemi di prestazioni. Se si verificano problemi dopo l&#39;aggiornamento a una versione del driver più recente, si consiglia di eseguire il downgrade dei driver a una versione precedente.

## Impostazioni driver NVIDIA

Alcune impostazioni NVIDIA predefinite possono influire sulle prestazioni. Si consiglia di creare un profilo e di disabilitare i seguenti parametri (impostarli su disattivato):

* Ottimizzazione concatenata
* Sincronizzazione verticale

## Come possono utilizzare la GPU altre applicazioni

Substance 3D Painter non è l’unico a lavorare con la GPU, anche altre applicazioni lo fanno. Quasi tutte le applicazioni 3D utilizzeranno la GPU e l&#39;VRAM per funzionare, comprese quelle comunemente utilizzate insieme a Painter, come Blender, Maya, Unreal Engine, Unity, C4D e altre. Una soluzione per garantire buone prestazioni mantenendo queste applicazioni aperte è assicurarsi che Substance 3D Painter venga lanciato per primo, al fine di richiedere la propria allocazione VRAM. Tuttavia, alcuni software possono acquisire dinamicamente alcune parti dell&#39;VRAM e possono ancora essere in conflitto con Substance 3D Painter anche se vengono lanciati dopo Painter.

In generale, maggiore è il numero di accessi al Painter VRAM, più veloce sarà l&#39;esecuzione, quindi cercare di ridurre al minimo la quantità di VRAM utilizzata da altre applicazioni in esecuzione contemporaneamente a Painter.

## Quantità e larghezza di banda VRAM della GPU

Substance 3D Painter si affida molto alla GPU per eseguire la maggior parte dei suoi calcoli. Ecco perché è importante disporre di una GPU che rispetti i [Requisiti di sistema](../../getting-started/system-requirements.md).

Painter agisce trasferendo la texture nella memoria GPU (VRAM) per eseguire i calcoli (come le operazioni di fusione per creare la texture finale). Tuttavia, se l&#39;VRAM inizia a riempirsi, le texture inutilizzate verranno trasferite nuovamente nella RAM del computer per liberare spazio VRAM. Substance 3D Painter scrive e legge i GB di dati mentre lavora. Ciò significa che sono importanti sia la capacità dell&#39;VRAM (quantità) che la velocità della banda larga quando si effettuano i trasferimenti. È possibile utilizzare strumenti quali [MSI AfterBurner](https://www.msi.com/page/afterburner) per monitorare questo comportamento.

>[!NOTE]
>
> Nvidia GTX 970</b> <b>presenta una progettazione problematica della memoria GPU che interessa Substance 3D Painter. Gli ultimi 500 MB dell&#39;intero disco da 4 GB funzionano a un ritmo inferiore rispetto ai restanti 3,5 GB. Se Substance 3D Painter utilizza gli ultimi 500 MB, le prestazioni possono essere ridotte fino a 10 volte (rispetto a quanto misurato). Per ulteriori dettagli tecnici, vedere: <https://www.pcper.com/news/Graphics-Cards/NVIDIA-Responds-GTX-970-35GB-Memory-Issue>
