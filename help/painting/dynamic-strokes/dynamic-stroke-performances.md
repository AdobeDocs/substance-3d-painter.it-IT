---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/dynamic-strokes/dynamic-stroke-performances.html"
breadcrumb-title: ''
description: Scoprite le considerazioni sulle prestazioni del tratto dinamico in Substance 3D Painter per ottimizzare il rendering e la reattività del tratto del pennello.
helpx_creative_field: ""
helpx_description: Painter > Painting > Dynamic strokes > Dynamic Stroke Performances
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Prestazioni del tratto dinamico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '995'
ht-degree: 0%

---


# Prestazioni del tratto dinamico

Per i Tratti dinamici le prestazioni del grafico della Substance contano molto perché la Substance può essere rigenerata molto tempo in un periodo molto breve. Se un calcolo Substance è troppo pesante, può creare latenza e quindi balbetta e si blocca quando si dipinge. Tutto questo può finire per creare una cattiva esperienza di pittura. Questa pagina contiene informazioni e consigli sull’uso della funzione Traccia dinamica.

## Il calcolo dei tratti dinamici può essere pesante

È anche importante sapere che il calcolo può avere un impatto in contesti diversi :

* **Durante il disegno**: il tratto dinamico viene generato (a seconda delle impostazioni) durante il disegno. Una configurazione errata può rallentare o rallentare il disegno.
* **Alla riapertura di un progetto**: anche se il processo di pittura è andato bene, esiste comunque la possibilità che il calcolo si arresti quando si apre un progetto, rendendo i progetti molto più lunghi del solito. Questo perché il processo di pittura iniziale è andato bene perché il calcolo è stato distribuito nel tempo, tuttavia succede quasi tutto in una volta quando si apre un progetto. Ciò significa che un progetto potrebbe richiedere migliaia di Substance univoche da generare se il tratto dinamico non era configurato correttamente.
* **Consumo di memoria**: la generazione di molte variazioni per un grafico a Substance potrebbe richiedere molta memoria (perché queste generazioni sono volatili al volo).

## Utilizzo delle impostazioni di variazione e spaziatura

Anche se è facile implementare effetti straordinari o avanzati all&#39;interno della Substance stessa, talvolta può essere più utile mantenerla semplice e utilizzare invece le impostazioni native dei parametri degli strumenti di Substance 3D Painter. Queste impostazioni sono molto più veloci da calcolare per il motore di pittura:

* **Variazione**: questi parametri consentono di creare casualità a un costo molto contenuto modificando alcuni attributi senza ricalcolare la Substance (ad esempio l&#39;angolo, la posizione e l&#39;opacità).
* **Spaziatura**: minore è la spaziatura, maggiore sarà il numero di timbri creati durante il disegno di un tratto. A volte non è necessario un tratto di pennello continuo e l’uso di una spaziatura ampia può anche aiutare a visualizzare meglio l’alfa/il materiale utilizzato.

## Quando e quale tipo di casuale utilizzare

Il Numero Casuale è un ottimo modo per generare unicità. Il problema è che la generazione può essere costosa e nel caso della funzione Traccia dinamica può accadere molto spesso se non viene modificata correttamente. È importante capire quando usare il Numero casuale e quando evitarlo, preferendo piuttosto un metodo alternativo per ottenere il miglior compromesso tra immagini e prestazioni:

* **Numero casuale per timbro**: in questo caso, per ogni timbro verrà generata una nuova Substance univoca. Questo è perfetto per la creazione di unghie uniche su una tavoletta di legno, ad esempio, ma non se si stanno creando tracce di inchiostro/pittura.
* **Numero casuale per tratto**: viene creato un numero casuale univoco per il tratto corrente del pennello. Ciò è utile quando sono presenti pochi timbri ma è necessario un nuovo set di variazioni per ogni tratto (come un effetto spray).
* **Numero casuale statico**: la Substance viene generata una volta e non cambierà mai. Ottimale per le prestazioni ma forse troppo restrittivo a seconda delle vostre esigenze.

Che ne dici di **ora** ($time)?\
Il tempo può essere utile per la creazione di aspetti molto specifici, ma in realtà è una delle variabili più costose da utilizzare in un grafico a Substance. Il motivo è che è molto difficile ottenere valori simili da un tratto di pennello all&#39;altro, quindi il motore del pennello genererà probabilmente nuove variazioni in ogni momento. Evitalo se è possibile, utilizza la spaziatura e l’Indice timbro invece che la combinazione può portare a risultati simili.

## Utilizzo di StampIndex e StampCycleCount

**StampIndex** è l&#39;ID di un singolo timbro all&#39;interno di un tratto del pennello. Per impostazione predefinita, inizia da 0 e aumenta di 1 per ogni nuovo timbro. **StampCycleCount** consente di limitare la quantità di indici univoci e indica a Substance 3D Painter di riciclare/riutilizzare i grafici a Substance già generati. Quando l’ID corrente raggiunge il limite, Substance 3D Painter ricomincia da 0, creando un ciclo continuo.

La soluzione migliore per mantenere la casualità senza compromettere le buone prestazioni consiste pertanto nel sfruttare la conta ciclica con i seguenti elementi:

* **IndiceTimbro come NumeroCasuale**: durante la creazione di un grafico a Substance è possibile impostare il NumeroCasuale come Assoluto. In questo modo è possibile inserirvi un valore personalizzato che può essere Indice timbro. In questo modo viene creata una versione univoca del grafico Substance per ogni timbro all’interno del tratto.
* **In combinazione con StampCycleCount**: è possibile creare un set limitato di nuove varianti e quindi riutilizzarle.
* **Inizio casuale**: se il conteggio dei cicli è impostato per iniziare da un valore casuale anziché da 0, verrà utilizzata una versione di Substance diversa all&#39;inizio per ogni tratto all&#39;interno del pool di grafici già generati.

## Disabilitazione del calcolo in base ai valori dei parametri

Substance 3D Painter non è in grado di determinare quando si modifica un parametro che può produrre lo stesso output, semplicemente perché il calcolo è nascosto all’interno del grafico della Substance. Questa è una scatola nera.

Per migliorare le prestazioni durante l’ottimizzazione dei parametri e l’uso dei Tratti dinamici, è possibile specificare quando devono essere generate nuove istanze del grafico utilizzando i valori condizionali nei campi userdata del grafico Substance.

I valori possibili sono:

| *Variabile* | *Utilizzo* |
| --- | --- |
| **IsStampIndexActive** | Utilizzato per determinare se l&#39;indice del timbro deve cambiare durante il disegno. |
| **IsRandomSeedActive** | Utilizzato per determinare se il valore di Numero casuale deve cambiare durante il disegno. |
| **IsTimeActive** | Utilizzato per determinare se l&#39;ora ($time) deve aumentare durante il disegno. |

Ad esempio:

```
IsRandomSeedActive=input.roundness_jitter>0 || input.flip_x_jitter || input.flip_y_jitter
```


In questo caso, il valore di inizializzazione casuale verrà modificato solo se il parametro del grafico (identificatore) **rotondità\_jitter** è maggiore di 0 o se il valore booleano **capovolgi\_x\_jitter** o **capovolgi\_y\_jitter** è abilitato. Se la condizione non viene soddisfatta, il grafico non verrà rigenerato. I parametri del grafico devono essere preceduti da &quot; **input.**  &quot; per essere riconosciuto.
