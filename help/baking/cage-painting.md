---
title: Pittura a gabbia
description: Scoprite come evitare artefatti e personalizzare la gabbia durante il processo di esegue i baking con l’applicazione di pittura a gabbia in Substance 3D Painter.
hold: true
source-git-commit: a6741dd7c792608e886e0b04ee59ebf3fe4d3285
workflow-type: tm+mt
source-wordcount: '923'
ht-degree: 0%
---

# Pittura a gabbia

**La pittura a gabbia** consente di pittura le aree per allontanare la gabbia eseguente i baking o avvicinarla alla superficie a poli bassi. L’applicazione del colore in gabbia consente di prevenire gli artefatti durante la eseguita i baking, catturando al contempo tutti i dettagli ad alto livello della trama.

## Imposta pittura a gabbia

Affinché **Cage painting** sia disponibile, il progetto deve avere almeno un file di scena High-Poly da cui eseguire i baking e il tipo di gabbia deve essere impostato su **Distance-based**.

>[!NOTE]
>
> In una prossima versione verrà aggiunto il supporto per **Cage painting** per il **tipo di gabbia automatica**.

Si consiglia di impostare i valori **Distanza frontale massima** e **Rispetto al rettangolo di selezione** prima di iniziare a creare la pittura della gabbia, in quanto la modifica di questi valori dopo il disegno potrebbe richiedere ritocchi o addirittura la ricolorazione della gabbia da zero.

>[!TIP]
>
> Se desiderate ricominciare a disegnare sulle gabbie da zero, potete ripristinare i parametri di colorazione delle gabbie, i tratti di colorazione delle gabbie o tutte le impostazioni di esegue i baking.
>
> ![](../assets/baking/cage-painting/resetcage.png)

## Inizia pittura a gabbia

Per avviare il disegno con gabbia:

1. Passa alla [**modalità di Esegue i baking**](baking.md).
1. Assicurati di aver selezionato almeno un file **High-Poly scene** da cui eseguire i baking.
1. Nel **pannello delle impostazioni comuni** **pannello**, accedete alla **sezione Gabbia**.
1. Impostare il **tipo di gabbia** su **basato sulla distanza**.
1. Fai clic su **Gabbia Pittura**.

>[!NOTE]
>
> Per impostazione predefinita, **Auto-rebake** è attivato per il canale normale quando si immette per la prima volta **Cage painting**. Ciò significa che la mappa normale verrà automaticamente ricaricata ogni volta che si modifica la gabbia. Se preferisci, puoi disattivare **Auto-rebake** nel [**pannello baker mappa trama**](../interface/baking-panels/mesh-map-bakers.md).

Una volta attivata la modalità di disegno Gabbia, la visualizzazione predefinita nel **Riquadro di visualizzazione** mostra:

* La gabbia intorno alla trama in beige trasparente.
* Aree in cui il poli elevato interseca la gabbia in rosso brillante.
* Le aree dipinte con gabbia sono di colore verde (positivo) e blu (negativo) sulla superficie con trama a basso poli.

In modalità Disegno in gabbia, potete utilizzare il [**menu di visualizzazione Eseguito i baking**](baking-visualization-settings.md) nella **finestra della vista** per modificare il colore e l&#39;opacità della visualizzazione per ogni elemento oppure attivare o disattivare la visualizzazione per elementi specifici.

>[!NOTE]
>
> La visualizzazione in rosso brillante delle intersezioni di poli elevati con la gabbia è un’anteprima approssimativa e non corrisponde esattamente ai risultati finali della esegue i baking. Nella maggior parte dei casi, la visualizzazione è abbastanza accurata, ma per trame a basso poli con poligoni lunghi e sottili, può essere imprecisa ed è preferibile utilizzare **Esegue i baking rapida** o **Auto-Rebake** per verificare il risultato finale.

## Strumenti di pittura a gabbia

Quando colorate la gabbia, potete utilizzare molti degli strumenti e delle scelte rapide utilizzati nella **modalità Pittura**, inclusi gli strumenti **Pennello**, **Gomma** e **Riempimento poligonale**.

* Potete passare dalla modalità di disegno a **Pennello**, **Gomma** e **Riempimento poligonale** o utilizzare le [scelte rapide da tastiera](../interface/settings/shortcuts.md) standard.
* Durante l&#39;utilizzo degli strumenti **Pennello** o **Gomma**, è possibile regolare le dimensioni, il flusso, l&#39;opacità e la spaziatura dello strumento utilizzando i parametri nella parte superiore del **Riquadro di visualizzazione**. Puoi anche utilizzare le [scelte rapide da tastiera](../interface/settings/shortcuts.md) pertinenti, se disponibili.

### Pennello

L&#39;uso del **pennello** a piena **intensità**, **flusso** e **opacità** avrà un impatto enorme sulla superficie della gabbia. Si consiglia di impostare un valore **Intensità** molto basso e di utilizzare i parametri Flusso e Opacità per controllare l’intensità del pennello.

TODO: animazione/video che mostra la differenza nell’effetto intensità

### Gomma

Lo strumento Gomma consente di rimuovere la pittura dalla gabbia, ripristinando efficacemente le aree cancellate alle dimensioni predefinite della gabbia.

### Riempimento poligono

Nella **modalità di colorazione delle gabbie** **modalità**, lo **strumento di riempimento poligono** presenta una funzionalità aggiuntiva, mentre nella **finestra di visualizzazione** viene visualizzato un **cursore Intensità** quando si apportano modifiche che è possibile utilizzare per regolare il valore dell&#39;ultimo set di poligoni selezionati.

Questo è particolarmente utile per eseguire regolazioni per elemento utilizzando la **Modalità di riempimento trama** in scene con più trame separate.

>[!NOTE]
>
> Questa funzione funziona ripetendo l&#39;ultima operazione (applicazione del riempimento poligonale) con un valore di intensità diverso. Di conseguenza, se si esegue un’operazione diversa o si cambiano gli strumenti, il cursore scompare.

Spesso può essere utile applicare lo stesso valore **Riempimento poligonale** a più aree della trama. Per eseguire questa operazione:

1. Seleziona il primo gruppo di poligoni.
1. Utilizza il cursore **Intensità gabbia** per regolare l’intensità dell’effetto.
1. Copiare il valore **Intensità gabbia** dal cursore temporaneo nella **finestra della vista**.
1. Incollate il valore nel cursore **Intensità** nella parte superiore del **Riquadro di visualizzazione**.
1. Seleziona i successivi set di poligoni per applicare lo stesso valore di intensità.

Il video seguente mostra questo flusso di lavoro in azione, utilizzando lo **strumento Riempimento poligonale** **strumento** con **Riempimento trama** selezionato.

TODO: VIDEO

>[!NOTE]
>
> Quando si eseguono questi passaggi, può essere utile selezionare **Metodo fusione normale** in modo che lo strumento Riempimento poligono sovrascriva i valori colorati esistenti, anziché aggiungerli.

### Modalità Fusione

Per impostazione predefinita, sia lo strumento **Pennello** che lo strumento **Riempimento poligonale** utilizzano per impostazione predefinita il metodo di fusione **Scherma lineare (Aggiungi)**, ma potete anche utilizzare i metodi di fusione **Normale** e **Schiarisci (Massimo)**.

* **Scherma lineare (aggiungi)**
  * Ogni tratto/timbro aggiunge o sottrae il valore di intensità specificato dal valore esistente.
  * Questo metodo di fusione funziona in modo simile alle applicazioni di scultura 3D, in cui ogni tratto pittura viene aggiunto alla superficie della trama.
* **Normale**
  * Ogni tratto/timbro imposta il valore sull’intensità specificata, sovrascrivendo il valore esistente.
  * Questo metodo di fusione si comporta come il pennello predefinito in modalità pittura, consentendoti di coprire la superficie esistente con un valore diverso.
* **Schiarisci (massimo)**:
  * Per ogni tratto/timbro viene scelto il valore massimo tra l’intensità e il valore esistente.
  * Con questo metodo di fusione, i bordi del pennello impiegano più tempo per creare tratti successivi, contribuendo a creare una transizione più graduale.