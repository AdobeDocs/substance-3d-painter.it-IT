---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/uv-reprojection.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la riproiezione UV in Substance 3D Painter per trasferire texture tra layout UV diversi.
helpx_creative_field: ""
helpx_description: Painter > Features > UV Reprojection
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Riproiezione UV
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '378'
ht-degree: 0%

---


# Riproiezione UV

La riproiezione UV è un processo automatico che si verifica quando modificate la risoluzione della texture o importate una nuova trama.\
Se carichi una nuova trama nel documento (tramite la finestra [Configurazione progetto](https://substance3d.adobe.com/display/draftpainter/project%20configuration) ), tutte le tue azioni verranno riproiettate sulla nuova trama. Non importa se la topologia è cambiata (purché sia simile) o se gli UV sono cambiati. Poiché la riproiezione funziona ricalcolando tutti i livelli e i tratti pennello, può richiedere un po’ di tempo (soprattutto con risoluzioni texture elevate).

Colorare in vista 2D

Poiché ogni tratto creato nella vista 2D viene eseguito nello spazio UV, non è possibile riproiettarlo correttamente nel caso in cui l&#39;UV della trama cambi radicalmente dopo una reimportazione. Il modo migliore per fare in modo che il vostro progetto sia a prova di riproiezione è affidarsi alla mascheratura tramite una mappa ID e altro tipo di selezione e pittura invece della Vista 3D.

## Come funziona la riproiezione?

Substance 3D Painter salva i suoi dati in 3D nello spazio del mondo per mantenere tutto non distruttivo. Ciò significa che quando reimporta una trama, Substance 3D Painter tenta di colorare dove si trovava la trama prima della reimportazione, non ha modo di sapere dove alcuni pezzi avrebbero potuto spostarsi.

Inoltre, quando Substance 3D Painter importa una trama, ne calcola il rettangolo di selezione per registrare lo spazio e definire una scala relativa per gli strumenti (pennello, particelle e così via). Questo rettangolo di selezione ha una larghezza di 1 unità su ogni asse. Quando importate una nuova trama, se deselezionate l’opzione &quot;Mantieni traccia&quot;, il rettangolo di selezione viene normalizzato di nuovo sulla nuova trama. Pertanto, se le dimensioni della trama sono cambiate notevolmente, i tratti possono spostarsi. Se tuttavia selezionate &quot;Mantieni tratti&quot;, il rettangolo di selezione originale viene ridimensionato in base a quello nuovo per riproiettare correttamente i tratti del pennello.

>[!WARNING]
>
> La modifica delle unità della trama 3D può causare il mancato funzionamento della riproiezione UV; la trama vecchia e quella nuova, anche se la topologia non è cambiata, possono essere interpretate come scale molto diverse. Se possibile, si evita di cambiare la configurazione dell&#39;unità, perché potrebbe essere difficile correggerla.
