---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/post-processing/tone-mapping.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la post-elaborazione della mappatura dei toni in Substance 3D Painter per regolare l'esposizione e la gradazione dei colori nella finestra della vista.
helpx_creative_field: ""
helpx_description: Painter > Features > Post Processing > Tone Mapping
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mappatura toni
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '690'
ht-degree: 0%

---


# Mappatura toni

![](../../assets/tone-mapping.png)

I parametri di Mappatura toni consentono di controllare in che modo i colori verranno ridimensionati per essere visualizzati sullo schermo. Queste impostazioni possono essere utili per ridistribuire i colori a causa della loro ampia gamma di valori (che possono superare quello che può essere visualizzato sullo schermo corrente).

>[!NOTE]
>
> Substance 3D Painter genera **HDR** colori (High dynamic range) (in uno spazio gamma lineare), ma la maggior parte delle schermate consente solo di visualizzare **colori LDR** (basso intervallo dinamico). Per mappare l’intervallo HDR all’intervallo LDR, è necessario eseguire una conversione. Questo è il principio della mappatura dei toni.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Esposizione** | Ridimensiona i risultati del rendering dello spazio HDR prima di applicare eventuali effetti di riflesso o della mappatura dei toni. |
| **Gamma** | Questo è il valore gamma per la correzione gamma. |
| **Funzione** | Funzione da utilizzare per mappare l&#39;intervallo HDR all&#39;intervallo LDR.  Le funzioni disponibili sono:<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Auto </strong>: la funzione della mappa di viraggio viene selezionata automaticamente. Il valore predefinito è <strong> Sensiometrico </strong>. </li><li data-preserve-html="true"><strong> Lineare </strong>: il colore di output non è bloccato su 0 a 1 solo per questo tipo. Questa opzione è ottimale per l’implementazione di un effetto nello spazio HDR sul lato dell’applicazione dopo l’applicazione degli effetti. <br/>Si consiglia di non utilizzarlo a meno che non si abbia un motivo specifico per utilizzarlo, perché i componenti di alta luminanza andranno completamente persi e si verificheranno luci soffuse se viene utilizzata la mappatura lineare come output finale dello schermo.</li><li data-preserve-html="true"><strong> LinearSat </strong>: è quasi uguale a <strong> Linear </strong>, con l&#39;eccezione che il colore di output è bloccato. Inoltre, la sintesi del riflesso è un po&#39; più fluida rispetto a <strong> lineare </strong>.</li><li data-preserve-html="true"><strong> Sensiometrico </strong>: funzione predefinita quando il rendering delle scene viene eseguito nello spazio HDR.</li><li data-preserve-html="true"><strong> Reinhard </strong>: il risultato è una mappatura più graduale rispetto a <strong> Sensitometric </strong> e un contrasto leggermente basso. Di conseguenza, fa sì che la risoluzione dei componenti di elevata luminanza diventi elevata e rafforza la riproduzione delle variazioni di luminanza nelle porzioni luminose.</li><li data-preserve-html="true"><strong> ReinhardLum </strong>: tipo per l&#39;implementazione della mappa di tono <strong> Reinhard </strong> con la luminanza come riferimento e mantenendo la saturazione originale (vivacità: rapporto RGB). Esegue il mapping solo delle informazioni di luminanza allo spazio LDR e quindi riproduce la saturazione originale. Anche la saturazione nello spazio HDR viene mantenuta dopo la mappatura dei toni.</li><li data-preserve-html="true">Registro <strong> </strong>: il mapping risulta ancora più graduale di <strong> Reinhard </strong> e il contrasto è basso. Ciò fa sì che la risoluzione dei componenti di elevata luminanza diventi elevata e che la riproduzione più intensa delle variazioni di luminanza nelle parti luminose.</li><li data-preserve-html="true"><strong> LogLum </strong>: tipo per l&#39;implementazione della mappa dei toni dello spazio logaritmico con la luminanza come riferimento e mantenendo la saturazione originale (vividezza: rapporto RGB). In questo modo vengono mappate solo le informazioni di luminanza allo spazio logaritmico e quindi viene riprodotta la saturazione originale. Anche la saturazione nello spazio HDR viene mantenuta dopo la mappatura dei toni.</li></ul> |
| **Fattore mapping** | Controlla il livello massimo di luminanza (luminosità) nello spazio HDR mappato allo spazio LDR finale nel processo di mappatura dei toni. I colori più luminosi della luminanza dello spazio HDR specificato non possono essere rappresentati nello spazio LDR, con conseguente sovraesposizione delle luci. Concretamente, questo valore è la luminanza (dopo il ridimensionamento dell’esposizione) nello spazio HDR che mappa al valore di luminanza massimo (1,0) nello spazio LDR. In modalità rendering HDR, più è basso questo valore, maggiore è il contrasto e maggiore è la probabilità che si verifichino fenomeni di luce in sovraimpressione. Viceversa, specificando valori più alti si ottiene un contrasto inferiore e si riduce la probabilità che le aree di luce risultino sovraesposte. In modalità rendering LDR, quando si esegue una riassociazione allo spazio HDR per applicare un effetto, l’intervallo di luminanza viene espanso fino al valore specificato in **Fattore di mappatura**. Al contrario, la luminanza **del fattore di mappatura** è mappata sulla luminanza massima LDR durante la mappatura dei toni.In altre parole, questo specifica il fattore di scala dell’intervallo dinamico applicato ai risultati del rendering LDR per l’applicazione degli effetti. Impostando questo valore su un valore alto si mettono in risalto le aree luminose negli effetti.  **Nota:** questa impostazione non avrà alcun effetto (verrà ignorata) se la **funzione** è impostata su una delle seguenti in modalità di rendering HDR: **Lineare** , **LineareSat** o **Sensitometrica**. |
