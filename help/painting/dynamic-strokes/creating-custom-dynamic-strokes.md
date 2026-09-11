---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/dynamic-strokes/creating-custom-dynamic-strokes.html"
breadcrumb-title: ''
description: Scoprite come creare tratti dinamici personalizzati in Substance 3D Painter per progettare comportamenti ed effetti unici per il tratto del pennello.
helpx_creative_field: ""
helpx_description: Painter > Painting > Dynamic strokes > Creating Custom Dynamic Strokes
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creazione di Tratti dinamici personalizzati
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---


# Creazione di Tratti dinamici personalizzati

Per creare Tratti dinamici personalizzati, sono disponibili due opzioni:

* Utilizzo di una risorsa Substance esistente per creare un nuovo pennello/strumento predefinito
* Crea una nuova risorsa Substance da zero (richiede [Substance 3D Designer](https://substance3d.adobe.com/display/SDDOC/Substance+Designer) ).

Si consiglia inoltre di leggere le [Prestazioni dinamiche del tratto](dynamic-stroke-performances.md) prima di creare file di Substance personalizzati per evitare eventuali colpevoli.

## Riutilizzo della risorsa esistente

La creazione di nuovi Tratti dinamici da zero può essere difficile. L’utilizzo di risorse esistenti, l’ottimizzazione e il salvataggio come nuovi predefiniti possono essere un punto di partenza sufficientemente valido.

Trovate risorse compatibili nello scaffale che possano soddisfare le vostre esigenze, quindi consultate la nostra pagina su [Predefiniti](../presets/presets.md).

## Creazione di file di Substance personalizzati per i Tratti dinamici

Di seguito è riportato un elenco dei parametri supportati per i Tratti dinamici nei grafici a Substance.

| Identificatore variabile | Descrizione |
| --- | --- |
| <b>Numero casuale</b> | Se un file di Substance viene cotto con il valore di Numero casuale visualizzato, sarà controllabile con la funzione Traccia dinamica. |
| <b>indiceTimbro</b> | <b>Intero1</b> verrà alimentato da Substance 3D Painter quando si disegna il tratto del pennello. I valori minimo e massimo non hanno alcun effetto; Substance 3D Painter li ignorerà. |
| <b>stampCycleCount</b> | <b>Intero1</b> Painter leggerà il valore predefinito del parametro, il valore minimo e il valore massimo per esporre il parametro Conteggio ciclo timbro. Questo parametro controlla il numero di varianti di Substance univoche che verranno create. |
| <b>$time</b> | <b>Virgola mobile1</b> verrà alimentato da Substance 3D Painter quando si disegna il tratto del pennello in base al tempo di disegno trascorso (per tratto). Questa proprietà può generare molte variazioni di Substance e quindi influire sulle prestazioni. |
| <b>strokeSpacing</b> | <b>float1</b> Valore di spaziatura corrente per l&#39;intero tratto colorato. |
| <b>strokeSize</b> | <b>float1</b> Valore della dimensione corrente per l&#39;intero tratto colorato. |
| <b>stampStrokePosition</b> | <b>numero intero1</b> Utilizzato per specificare l&#39;inizio di un tratto. Il valore finale è disponibile solo sul tratto del tracciato e non tramite la pittura manuale. Valore possibile:<ul data-preserve-html="true"> <li data-preserve-html="true">0 = centro</li> <li data-preserve-html="true">1 = inizio</li> <li data-preserve-html="true">2 = fine</li> </ul>Può essere disattivato utilizzando il tag utente isstrokepositionactive. |
| <b>distanceAlongCurve</b> | <b>float1</b> La distanza corrente al timbro specificato lungo un percorso. Questa proprietà può generare molte variazioni di Substance e quindi influire sulle prestazioni. Può essere disattivato con il tag utente <b>iscurvedistanceactive</b>. |
| <b>distanceMaxCurve</b> | <b>float1</b> Lunghezza totale di un tracciato creato con lo strumento tracciato. Può essere disattivato con il tag utente <b>iscurvedistanceactive</b>. |
| <b>pathCorner</b> | <b>numero intero1</b> Indicare il tipo di angolo utilizzato da una barra multifunzione. Valore possibile:<ul data-preserve-html="true"> <li data-preserve-html="true">0 = Nessun angolo</li> <li data-preserve-html="true">1 = Angolo sinistro</li> <li data-preserve-html="true">2 = Angolo destro</li> </ul> |
| <b>pathCornerAngle</b> | <b>mobile</b> Angolo (in radiante) dell&#39;angolo su un Percorso dei nastri. Può essere utilizzato per compensare o regolare l&#39;aspetto di un angolo in base a un valore di angolo preciso. |
| <b>patchLengthOnCurve</b> | <b>float</b> Dimensione di una sezione (patch) in un Percorso dei nastri. Combinato con <b>distanceAlongCurve</b> e <b>distanceMaxCurve</b>, può essere utilizzato, ad esempio, per normalizzare la dimensione di una patch. |
