---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/shader-settings.html"
breadcrumb-title: ''
description: Scopri come configurare le impostazioni dello shader in Substance 3D Painter per personalizzare il rendering del materiale e l’aspetto visivo.
helpx_creative_field: ""
helpx_description: Painter > Interface > Shader settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni shader
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '633'
ht-degree: 5%

---


# Impostazioni shader

![](../../assets/shader-settings.png)

La finestra **Impostazioni shader** consente di controllare i parametri shader (e Iray mdl) e i parametri di spostamento della geometria.

Uno shader è una funzione che definisce l&#39;aspetto di un oggetto quando interagisce con luci e ombre nelle finestre delle viste. In questa applicazione gli shader vengono utilizzati per sapere come leggere i canali del set di texture ed eseguire il rendering della trama 3D nelle finestre delle viste.

## Annulla sovrapposizione e file shader

![](../../assets/shader-undo.png)

Questa sezione della finestra Impostazioni shader controlla i parametri principali durante la manipolazione degli shader.\
Lo stack Annulla/Ripeti per lo shader è indipendente dalla [Cronologia](https://substance3d.adobe.com/display/DRAFTPAINTER/History) principale per non creare conflitti durante il disegno.

Se il file shader è contrassegnato come &quot;Obsoleto&quot;, si consiglia di aggiornarlo quando possibile. Vedere: [Aggiornamento di uno shader](https://substance3d.adobe.com/display/DRAFTPAINTER/Updating+a+Shader)

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Annulla** | Annullare o ripristinare una modifica del file shader o qualsiasi modifica dei parametri shader |
| **Ripeti** | Applicate nuovamente una modifica annullata tramite Annulla. |
| **File shader** | Pulsante che mostra il file shader corrente utilizzato. Fate clic sul pulsante per aprire un ripiano e scegliete uno shader diverso. |
| **Nome istanza** | Nome dell&#39;istanza dello shader. |
| **Ripristina impostazioni predefinite** | Ripristinate tutti i parametri dello shader ai valori predefiniti (così come sono nel file dello shader). |

### Istanza dello shader

Un&#39;istanza di shader è uno shader basato su un file shader originale ma con parametri personalizzati. Un’istanza dello shader può essere condivisa tra più set di texture, e un set di texture può avere un’istanza dello shader univoca.

**Ad esempio:** un progetto può utilizzare uno shader di base, mentre un set di texture utilizza uno shader personalizzato per supportare l&#39;opacità.

Per creare e gestire le istanze dello shader, vedere la finestra [Elenco set di texture](../texture-set/texture-set-list.md).

## Parametri shader

![](../../assets/shader-parameters-1.png)

I parametri dello shader dipendono dal file dello shader caricato.

## Spostamento e tassellatura

![](../../assets/disp-parameters.png)

Lo Spostamento e la tassellatura sono due funzionalità che possono essere utilizzate per modificare la forma di un oggetto per aggiungere ulteriori dettagli.

* **Spostamento**: spingere o spostare la geometria in base a un canale di input.
* **Tasselazione**: suddividere la geometria per densificarla. Una maggiore densità significa che la spaziatura tra i poligoni è più corta, il che fornisce dettagli più fini.

Nello scaffale è disponibile un filtro denominato &quot;**Da Height a normale**&quot; che può essere utilizzato per ottenere la mappa normale finale (nel caso in cui la conversione nativa non sia sufficientemente forte).

### Spostamento

Di seguito sono riportate le impostazioni di Spostamento:

| *Impostazione* | *Descrizione* |
| --- | --- |
| Canale di origine <b> </b> | Canale da cui si basa la deformazione della trama. Il valore predefinito è Height, ma può essere impostato anche su Spostamento. |
| <b>Unità di scala</b> | Selezionare la modalità di definizione della scala di spostamento:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Normalizzata: </b>La scala di Spostamento è relativa alla dimensione del rettangolo di selezione della trama.</li> <li data-preserve-html="true"><b>Scena: </b>La scala di Spostamento è relativa alle unità del file di scena importato.</li> <li data-preserve-html="true"><b>Dimensioni fisiche (cm)</b>: la scala dello Spostamento viene misurata in cm in base alla dimensioni fisiche dell&#39;oggetto.</li> </ul> |
| <b> fattore scala</b> | Controlla la quantità di deformazione applicata alla trama nel progetto in base all’unità di scala selezionata. |

>[!NOTE]
>
> Sia le impostazioni <b>Scena</b> che <b>Dimensioni fisiche (cm) </b>Unità scala richiedono che il modello importato sia stato preparato per le misurazioni della dimensioni fisiche. Se le unità non sono impostate correttamente nel file importato o se le unità dimensioni fisiche non sono supportate dal tipo di file importato, lo spostamento funzionerà comunque, ma potrebbe non fornire risultati precisi per le esigenze.

### Tassellatura

Di seguito sono riportate le impostazioni di tassellatura:

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Modalità suddivisione** | Determina la modalità di calcolo della quantità di suddivisione. Le configurazioni disponibili sono:<ul data-preserve-html="true"><li data-preserve-html="true"> Uniforme (impostazione predefinita) </li><li data-preserve-html="true"> Lunghezza bordo </li></ul> |
| **Conteggio suddivisioni** | (Modalità uniforme)Da 1 a 32. Un valore elevato genera più poligoni, che forniscono maggiori dettagli ma possono introdurre problemi di prestazioni. |
| **Lunghezza massima** | (Modalità Lunghezza Bordo)1 / Valore. Ogni bordo del poligono viene diviso fino a quando ogni segmento è uguale o inferiore a questo numero, 1/1 è la dimensione della scena. |
