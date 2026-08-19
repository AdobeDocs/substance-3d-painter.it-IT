---
title: Correzione dell'inclinazione
description: Scoprite come utilizzare la correzione dell’inclinazione per correggere gli artefatti di cottura quando si utilizza un flusso di lavoro di poli da alto a basso in Substance 3D Painter.
source-git-commit: db1c8daa33389f21699c53b0d6555c153fbc66d6
workflow-type: tm+mt
source-wordcount: '1027'
ht-degree: 0%

---


# Correzione dell&#39;inclinazione

<table>
  <tr style="border: 0;">
    <td style="border: 0; width: 35%" valign="top"><img src="../assets/baking/skew-correction-example.png" alt=""/></td>
    <td style="border: 0; width: 65%" valign="top">A volte, quando si cuoce a basso poli da un modello ad alto poli, è possibile che i dettagli appaiano deformati o distorti. Questo di solito accade quando le normali della gabbia e della superficie non si allineano bene. La cottura automatica proietta il poly alto sul poly basso in base a questi valori normali, quindi se non sono corretti, la cottura produce risultati mediocri.<br>Per fortuna, è disponibile la correzione dell'inclinazione (o mappatura dell'inclinazione) per correggere questo tipo di artefatto.<br>La correzione dell'inclinazione consente di colorare i valori direttamente sulla trama a basso poli per reindirizzare la proiezione utilizzata durante la cottura al forno senza dover creare una gabbia personalizzata.</td>
  </tr>
</table>

>[!NOTE]
>
> La correzione dell&#39;inclinazione viene colorata all&#39;interno della **modalità cottura** ed è memorizzata per set di texture.

## Correzioni inclinazione pittura

La funzione Correzione inclinazione consente di regolare manualmente le normali di superficie della trama in modo specifico per la cottura al forno. Anche se potete colorare le correzioni di inclinazione senza cuocere, può essere utile [cuocere prima le mappe di trama](how-to-bake-mesh-maps.md).

![](../assets/baking/mode_select_buttons.png)

*Passare alla modalità di cottura al forno per accedere alle impostazioni di correzione dell&#39;inclinazione.*

>[!IMPORTANT]
>
> La correzione dell’inclinazione richiede le seguenti impostazioni:
>
> * È necessario selezionare una scena High Poly. L&#39;opzione Inclina è disponibile solo quando si esegue la cottura da alta a bassa poli; se si seleziona **Usa trama bassa poli come trama alta poli**, l&#39;opzione Inclina correzione inclinazione **non** sarà disponibile.
> * **Cage** deve essere impostato su **Distance-based**.
> * È necessario controllare **valori normali medi**.

Con le impostazioni precedenti, potete fare clic su **Correzione inclinazione pittura** nel **pannello delle impostazioni comuni** per iniziare a disegnare. Quando si accede per la prima volta alla modalità di disegno della correzione dell&#39;inclinazione, **Ripeti automaticamente** verrà attivato automaticamente per il canale normale. Se preferisci, puoi disattivare **Auto-rebake** o cambiare il canale selezionato nel [**pannello dei panifici delle mappe trama**](../interface/baking-panels/mesh-map-bakers.md).

![](../assets/baking/skew-correction-menu.png)

### Strumenti di pittura

Quando disegnate le correzioni dell&#39;inclinazione, potete usare molti degli strumenti e delle scelte rapide che avete usato dalla modalità Pittura, inclusi gli strumenti **Gomma** e **Riempimento poligonale**.

* Potete passare dalla barra degli strumenti **Pennello**, **Gomma** e **Riempimento poligonale** oppure utilizzare la [scelta rapida da tastiera](../interface/settings/shortcuts.md) standard dalla modalità Pittura.
* Durante l&#39;utilizzo degli strumenti Pennello o Gomma, puoi regolare la dimensione, il flusso, l&#39;opacità e la spaziatura del pennello con i parametri nella parte superiore del **Riquadro di visualizzazione**. Puoi anche utilizzare la [scelta rapida da tastiera](../interface/settings/shortcuts.md) pertinente, se disponibile.

### Protezione bordo

La protezione del bordo ignora la correzione dell’inclinazione dipinta vicino ai bordi per mantenere una sfumatura uniforme delle normali della superficie. Puoi attivare/disattivare **Protezione Edge** nella sezione **Correzione inclinazione**. Quando è attivata l’opzione **Correzione bordo**, potete regolare la distanza del bordo e il contrasto del bordo per ottenere risultati ottimali.

* Distanza bordo: consente di controllare la distanza a cui ha effetto la protezione del bordo.
* Contrasto bordo: consente di controllare la sfumatura di protezione dei bordi. Un contrasto basso produce una sfumatura più uniforme.

>[!TIP]
>
> I valori per **Distanza bordo** e **Contrasto bordo** sono basati sulle dimensioni della trama. Per trame con dettagli molto piccoli rispetto alla dimensione di trama, potrebbe essere più facile immettere manualmente valori piccoli, piuttosto che utilizzare i cursori.

>[!NOTE]
>
> La protezione dei bordi si basa sulla mappa di trama **Bordi netti**, che è legata alla geometria della trama, non ai bordi UV.

### Visualizza inclina vettoriale

Per impostazione predefinita, quando iniziate a colorare le correzioni di inclinazione, le normali della superficie della trama vengono visualizzate nella **finestra della vista** come linee rosse, gialle e verdi. Potete modificare l&#39;aspetto di queste linee o disattivarle del tutto nella sezione **Inclina vettoriali** del **menu Visualizzazioni** che viene visualizzata nella **Finestra della vista.**

![](../assets/baking/visualizations_menu.png)

* **Lunghezza vettoriale**: regola la lunghezza delle linee nella finestra della vista. Linee più lunghe possono facilitare la comprensione della direzione del vettore.
* **Densità UV vettoriale**: modificate il numero di linee sulla superficie della trama. I vettori vengono posizionati nello spazio UV, quindi se la trama ha una densità di texel incoerente, il numero di vettori per unità di area della superficie varierà con la dimensione del poligono nella mappa UV.
* **Opacità vettoriale**: rendete i vettori più o meno trasparenti.

Il colore dei vettori indica l’entità della correzione dell’inclinazione applicata a ciascuna posizione del vettore.

* I vettori rossi non indicano correzioni dell’inclinazione: vengono utilizzate le normali di superficie di default.
* I vettori verdi indicano che le normali della superficie sono completamente corrette e direttamente perpendicolari alla superficie.

![](../assets/baking/skew-correction-painting.gif)*Colorare con un valore di flusso basso consente di controllare con precisione l&#39;intensità della correzione dell&#39;inclinazione.*

## Ottimizzazione delle prestazioni

### Organizza UV

**Rinnovo automatico** è ottimizzato per cercare di limitare il rebaking all&#39;area interessata da ogni tratto del pennello quando si disegnano correzioni dell&#39;inclinazione. Quando colori un tratto, **Auto-rebake** disegna un rettangolo di selezione attorno al tratto nello spazio UV e riattiva tutti gli elementi all&#39;interno del rettangolo. Ciò significa che se il tratto copre solo una piccola sezione dello spazio UV, solo una piccola area verrà rimbalzata, rendendo l&#39;operazione molto efficiente.

Tuttavia, se il tratto attraversa due Isole UV su lati opposti dello spazio UV, anche un piccolo tratto può richiedere la rigenerazione dell’intera texture, annullando l’ottimizzazione.

Di conseguenza, si consiglia di organizzare gli UV a trama in modo che le Isole UV vicine l&#39;una all&#39;altra nello spazio 3D siano anche vicine l&#39;una all&#39;altra nello spazio UV. Questo migliora le prestazioni di **Auto-rebake**.

### Imposta Allineamento a UV

In generale, è più efficace colorare le correzioni di inclinazione con **Proiezione > Allineamento** impostato su UV. Per modificare l&#39;**allineamento**:

1. Selezionate **Correzione inclinazione pittura** e attrezzate **Pennello** o **Gomma**.
1. Fate clic con il pulsante destro del mouse nel **Riquadro di visualizzazione** per aprire il **pannello delle impostazioni del pennello**.
1. Scorri fino a **Proiezione**.
1. Imposta **Allineamento** su **UV**.

Con **Allineamento** impostato su **UV**, è più difficile disegnare tratti uniformi tra le giunture di Isola UV. Tuttavia, ciò è generalmente meno importante quando si colorano le correzioni dell&#39;inclinazione rispetto alla creazione della trama.

>[!NOTE]
>
> I parametri per **Pennello** e **Gomma** sono memorizzati separatamente. Per ottimizzare le prestazioni di entrambi gli strumenti, dovrai impostare **Allineamento** per ciascuno di essi singolarmente.

## Inclinare le correzioni e annullare la sovrapposizione

Le operazioni di cottura al forno e pittura condividono una sola cronologia di annullamento. Il passaggio dalla modalità Baking a quella paint è di per sé un passaggio impraticabile, e anche l&#39;attivazione o la disattivazione della correzione dell&#39;inclinazione può essere annullata. Quando si annulla un’azione di cottura in modalità di disegno, la modalità di cottura in forno viene riaperta automaticamente prima che i passaggi vengano annullati; pertanto, un’azione non viene mai annullata all’esterno della modalità in cui si è verificata.