---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/baking/how-to-bake-mesh-maps.html"
breadcrumb-title: ''
description: Scoprite come eseguire il baking delle mappe di trama in Substance 3D Painter per generare occlusione ambientale, curvatura e altre texture basate su geometria.
helpx_creative_field: ""
helpx_description: Painter > Baking > How to bake mesh maps
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Come eseguire i baking le mappe trama
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '520'
ht-degree: 0%

---


# Come eseguire i baking le mappe trama

La modalità di esegue i baking dedicata di Substance 3D Painter semplifica la esegue i baking di mappe trama che possono alimentare materiali avanzati straordinari e altri strumenti. Continua a leggere o guarda il video seguente per scoprire come iniziare a eseguire i baking con Substance 3D Painter.

## 1 - Passare alla modalità di esegue i baking

Per impostazione predefinita, Painter viene avviato in modalità Disegno durante la creazione o l’apertura di un progetto. Per poter eseguire i baking le mappe trama, è necessario passare alla modalità di Esegue i baking. Per passare alla modalità di Esegue i baking, utilizzate una delle seguenti opzioni:

* Utilizza il <b>pulsante della modalità di Esegue i baking</b> (<b>icona Croissant</b>) nella barra degli strumenti contestuale in alto a destra nella finestra della vista

  ![](../assets/croissant-icon.png)

  >[!NOTE]
  >
  > A volte il <b>pulsante della modalità di Esegue i baking</b> può essere nascosto dietro altri pannelli, a seconda del layout dell&#39;area di lavoro.
* Usa il menu Metodo e seleziona <b>Esegue i baking mappe trama.\
  </b>
* Utilizza la scelta rapida da tastiera della tastiera <b>F8</b>.

### 2 - Selezionare set di texture e Porzioni UV

All&#39;interno dell&#39;<b>elenco Set di texture</b>, utilizzate la casella di controllo accanto a ogni set di texture (e al numero di Porzione UV, se presente) per selezionare le parti da eseguire i baking:

![](../assets/texture-set-list-baking-selection.png)

### 3 - Seleziona baker

All&#39;interno della finestra Baker mappe trama, utilizzare le caselle di controllo per selezionare le mappe che si desidera eseguire i baking:

![](../assets/mesh-map-bakers-selection.png)

### 4 - Modificare le impostazioni comuni

Nel pannello baker mappe trama, fate clic sulle impostazioni comuni per modificare le impostazioni quali risoluzione mappa con baking, larghezza dilatazione e alti parametri poli, condivise su tutte le mappe:

![](../assets/common-settings.png)

Nelle impostazioni comuni, potete definire quali file usare come trame ad alta definizione. La selezione di trame ad alta definizione consente di definire il modo in cui la gabbia viene generata per le trame:

* Basato sulla distanza: gonfiate i vertici lontano dalla trama a una distanza uniforme attraverso il modello per creare una gabbia.
* Automatico (sperimentale): Painter analizza la trama e genera automaticamente una gabbia, cercando di mantenere la gabbia vicina alla superficie senza creare intersezioni per risultati ottimali.
* File personalizzato: importa un file creato per utilizzarlo come gabbia. I file importati devono avere lo stesso numero di vertici della trama di base per funzionare correttamente.

Se non ti esegue i baking da una trama di poli elevato, attiva la casella di controllo <b>Usa trama di poli bassa come trama di poli alta</b>.

### 5 - Regolare la gabbia

Sono disponibili diverse opzioni per regolare la gabbia in base al metodo utilizzato. Con una gabbia basata sulla distanza, è possibile regolare le distanze frontale e posteriore per ridurre al minimo l&#39;intersezione tra la gabbia e la rete.

![](../assets/cage-distance.gif)

>[!NOTE]
>
> Quando la gabbia interseca la geometria del modello, vengono visualizzati dei punti rossi. Una gabbia intersecante generalmente porta ad artefatti e problemi nell&#39;area intersecante.

### 6 - Avviare la esegue i baking

Nella parte inferiore della finestra della vista fare clic sul pulsante Esegue i baking per avviare la esegue i baking.

![](../assets/bake-button.png)

### 7 - Inspect per la Esegue i baking degli errori

Una volta completata la esegue i baking, puoi controllare se sono stati segnalati errori nella finestra Registro Esegue i baking.

Se presenti, utilizzare la freccia accanto al messaggio di errore per visualizzare le relative impostazioni di baker:

![](../assets/bake-failed.png)
