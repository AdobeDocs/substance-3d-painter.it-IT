---
breadcrumb-title: ''
description: Esamina tutte le modifiche e gli aggiornamenti nelle versioni di Substance 3D Painter per tenere traccia dell’evoluzione delle funzioni e dei miglioramenti nel tempo.
title: Da ZBrush a Painter Bridge
user-guide-description: ''
user-guide-title: ''
source-git-commit: c50b48e520277293b9ddef466baf8e27db4891ab
workflow-type: tm+mt
source-wordcount: '609'
ht-degree: 0%

---


# Da ZBrush a Painter Bridge

A partire da ZBrush 2026.2.0 (l&#39;aggiornamento Maxon One di aprile 2026) e Substance 3D Painter 12.0.2 (versione Steam e CC), è possibile inviare i modelli direttamente da ZBrush a Painter tramite un plug-in installato automaticamente con la versione più recente di ZBrush.

![Immagine promozionale che mostra una risorsa sottoposta a rendering durante la sovrapposizione dalla stessa risorsa in Zbrush e in Painter.](../../assets/zbrush_promotional.png)

Con il plug-in Substance Bridge, non è necessario sottoporsi al lungo processo di esportazione di file separati di tipo low-poly e high-poly, importazione in Painter, configurazione ed esecuzione di torte.

Per iniziare a utilizzare il bridge da Zbrush a Painter:

1. Assicurati che sia installata almeno la versione 2026.2.0 di ZBrush.
1. Abilita il plug-in in Painter verificando che **Python > zbrush_painter_plugin** sia selezionato.
1. Da ZBrush, **Invia a Painter** è disponibile in **Texture > Substance ponte**

![Immagine del plug-in Substance Bridge in ZBrush](../../assets/zbrush_painterSendTo.png)

## Configurazione

Puoi configurare le seguenti impostazioni per la creazione automatica dei progetti in Painter:

| Impostazione | Descrizione |
| --- | --- |
| Invia a Painter | Invia il modello a Substance 3D Painter con le impostazioni correnti applicate. A ogni clic viene creato un nuovo progetto Substance da zero. |
| **Sottostrumenti** | |
| Tutto | Invia ogni SubTool indipendentemente dalla visibilità. Che l&#39;occhio sia acceso o spento, tutto viene mandato. |
| Visibile | Invia solo gli strumenti secondari con l&#39;icona occhio attivata nell&#39;elenco Strumenti secondari. |
| Attivo | Invia solo lo strumento secondario selezionato. |
| Invia poliPaint | Converte PolyPaint in una mappa texture e la applica come livello di riempimento in Substance, dove è possibile colorare e fondersi con essa. |
| Normali uniformi | Smussa le normali tangenti durante l&#39;esportazione in modo che le trame sfaccettate appaiano uniformi nella Substance, in base a come vengono renderizzate dai motori di gioco. Disattivate questa opzione per visualizzare la sfaccettatura effettiva della geometria. |
| Mappe di esecuzione automatica | Esegue automaticamente gli algoritmi di cottura di Substance dopo l&#39;arrivo del modello, generando mappe normali, occlusione ambientale, curvatura e altre mappe di dettaglio dal confronto tra mesh alta e bassa. |
| Forza scorrimento automatico UV | Attiva l&#39;algoritmo di srotolamento UV di Substance su ogni SubTool che arriva. Se il modello presenta già UV soddisfacenti, disattivateli perché vengono sovrascritti. |
| Livello di suddivisioni | Controlla quali livelli di suddivisioni vengono inviati. Corrente invia solo il livello visualizzato. Bassa e Alta invia i livelli più bassi e più alti per la cottura al forno ed è l’opzione consigliata per la maggior parte dei flussi di lavoro. |
| Set di texture | Controlla la divisione dello spazio UV nella Substance: Per SubTool (un set di texture per SubTool) o Per PolyGroup (un set di texture per PolyGroup all&#39;interno di ogni SubTool). |

Quando Painter riceve il modello, se è abilitata l&#39;opzione Auto-bake, viene avviato il baking. La suddivisione più bassa del modello è quella importata come trama a basso poli, mentre la suddivisione più alta è usata come trama a alto poli per cuocere i dettagli. ZBrush è in grado di gestire un numero molto più elevato di poligoni rispetto a Painter, quindi assicurati che la trama poly bassa abbia dimensioni di lavoro ottimali (questo dipenderà dalla macchina, ma meno di 1 milione è meglio).

Gli insiemi di texture di Painter rappresentano assegnazioni di materiale. Un set di texture equivale a uno spazio UV.

* Per SubTool crea un set di texture per ogni SubTool (tutte le parti dei sottostrumenti condividerebbero lo stesso spazio UV), che è l&#39;opzione più semplice.
* Per PolyGroup crea un set di texture per PolyGroup all’interno di ciascun SubTool, per un controllo più preciso sulle assegnazioni di materiale.

>[!NOTE]
>
>Con la versione Steam di Painter, Painter deve essere aperto per ricevere il modello ZBrush.


## Risorse aggiuntive

[Guarda questo video](https://www.youtube.com/watch?v=fLkkwV4BzrU) per vedere Bridge in azione oppure accedi alla [documentazione di ZBrush](https://help.maxon.net/zbr/en-us/Default.htm#html/reference-guide/texture/substance-bridge/substance-bridge.html?Highlight=painter) per ulteriori informazioni.
