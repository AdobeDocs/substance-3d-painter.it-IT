---
helpx_url: 'https://helpx.adobe.com/it/substance-3d-painter/baking/mesh-map-settings.html'
breadcrumb-title: ''
description: Scoprite come configurare le impostazioni della mappa trama in Substance 3D Painter per controllare i parametri di cottura e la qualità dell'output.
helpx_creative_field: ''
helpx_description: Substance 3D Painter
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Impostazioni della mappa della trama
user-guide-description: ''
user-guide-title: ''
source-git-commit: 7b5f6e6c9623cb51253b6e49c8dbcbb22856418c
workflow-type: tm+mt
source-wordcount: '1348'
ht-degree: 10%

---


# Impostazioni della mappa della trama

<b>Il pannello delle impostazioni della mappa trama</b> è disponibile in modalità Baking e dispone dei controlli per preparare la trama per la cottura in forno. Per regolare le impostazioni della mappa della trama per una determinata mappa, selezionate la mappa nel <b>pannello dei panifici della mappa della trama</b>. Ogni mappa trama può avere diverse impostazioni disponibili. Nella parte superiore del pannello Pannelli mappe trama è disponibile una raccolta di <b>impostazioni comuni </b>condivise da tutte le mappe trama.

Tutte le impostazioni condivise tra le mappe trama verranno visualizzate nella pagina Impostazioni comuni, anziché in ogni singola mappa trama.

## Impostazioni comuni

La pagina delle impostazioni comuni contiene i controlli che influiscono sul modo in cui tutte le mappe trama vengono salvate.

### Impostazioni di output

| Impostazione | Funzione |
| --- | --- |
| Dimensione di output | Definite la risoluzione X e Y delle mappe mesh generate. Fai clic sul blocco per consentire risoluzioni non quadrate. |
| Larghezza dilatazione | Regolate la distanza di estensione delle informazioni al forno oltre i limiti delle Isole UV. |
| Applica diffusione | Selezionate questa casella per applicare la diffusione ai bordi delle informazioni generate. |

### Parametri high poly

| Impostazione | Funzione |
| --- | --- |
| Usa trama poly bassa come trama poly alta | Abilita questa impostazione per eseguire il bake delle mappe in base alla trama del progetto. |
| Trame ad alta definizione | Aggiungi trame poly alte al tuo progetto per creare da una trama poly alta alla trama poly bassa nel tuo progetto. È possibile importare più trame. |
| Gabbia | Determinate come viene generata la gabbia di cottura.<ul data-preserve-html="true"> <li data-preserve-html="true">Basato sulla distanza: gonfiate i vertici lontano dalla trama a una distanza uniforme attraverso il modello per creare una gabbia.</li> <li data-preserve-html="true">Automatico (sperimentale): Painter analizza la trama e genera automaticamente una gabbia, cercando di mantenere la gabbia vicina alla superficie senza creare intersezioni per risultati ottimali.</li> <li data-preserve-html="true">File personalizzato: importa un file creato per utilizzarlo come gabbia. I file importati devono avere lo stesso numero di vertici della trama di base per funzionare correttamente.</li> </ul> |
| Ignora backface | Attivate/disattivate se le facce posteriori vengono ignorate durante la cottura al forno. Questo può aiutare a ridurre gli artefatti, ma può anche causare errori in alcuni casi limite. |
| Corrispondenza | Modificate il modo in cui il fornaio determina se includere gli oggetti durante la cottura al forno:<ul data-preserve-html="true"> <li data-preserve-html="true">Sempre: includi tutte le trame di poli alte che vengono colpite all&#39;interno della gabbia durante la cottura.</li> <li data-preserve-html="true">Per nome mesh: per ogni gabbia, cuocere solo mesh con il suffisso mesh corrispondente.</li> </ul> |
| Suffisso della trama low poly | Quando utilizzate Corrispondenza per nome trama, utilizzate questo suffisso per definire trame poly basse. |
| Suffisso trama high poly | Quando utilizzate Corrispondenza per nome trama, utilizzate questo suffisso per definire le trame poli alte e farle corrispondere alla trama poli bassa corrispondente. |
| Anti-alias | Regola la quantità di antialiasing nelle mappe generate. |

#### Correzione dell&#39;inclinazione

| Impostazione | Descrizione |
| --- | --- |
| **Correzione inclinazione pittura** | Accedete alla modalità di disegno della correzione dell&#39;inclinazione. |
| **Protezione di Edge** | Attivate/disattivate la protezione dei bordi per mascherare i valori di correzione dell’inclinazione dipinti vicini ai bordi netti. |
| **Distanza bordo** | Controlla la distanza di estensione della protezione dei bordi dai bordi netti |
| **Contrasto bordo** | Consente di controllare la nitidezza con cui la sfumatura di protezione dei bordi passa dalla protezione completa alla mancata protezione. |

## Impostazioni mappa ID

| Impostazione | Funzione |
| --- | --- |
| Origine colore | Cambia il modo in cui vengono determinati i colori al forno della mappa ID:<ul data-preserve-html="true"> <li data-preserve-html="true">Colore vertice</li> <li data-preserve-html="true">Colore materiale</li> <li data-preserve-html="true">ID file</li> <li data-preserve-html="true">ID trama/Poligruppo</li> </ul> |
| Generatore colore | Quando utilizzate ID file o ID trama/Poligruppo come sorgente colore, determinate come vengono generati i colori:<ul data-preserve-html="true"> <li data-preserve-html="true">Casuale</li> <li data-preserve-html="true">Scostamento tonalità</li> <li data-preserve-html="true">Scala di grigio</li> </ul> |

## Impostazioni mappa occlusione ambiente

| Impostazione | Funzione |
| --- | --- |
| Raggi secondari | Modifica il numero di raggi secondari. Più raggi possono produrre risultati migliori a costo di tempi di elaborazione più lunghi. |
| Distanza minima occlusione | Regolate la distanza minima per i raggi da percorrere in modo da colpire la geometria poly elevata e influire sulla mappa AO risultante. |
| Distanza massima occlusore | I raggi che si estendono oltre questa distanza senza toccare la trama di poli superiore sono considerati come non occlusi e non influiscono sulla mappa di AO. |
| Relativo al rettangolo di selezione | Quando questa casella è selezionata, altre impostazioni che fanno riferimento alla distanza sono basate sul rettangolo di selezione della trama del progetto. Quindi una distanza di 1 è uguale alla dimensione del rettangolo di selezione. |
| Angolo di diffusione | Regolate l’intervallo angular dei raggi generati. Un angolo di estensione più elevato consente di occludere più facilmente una superficie mediante una geometria che non è posizionata perpendicolarmente alla superficie. |
| Distribuzione | Seleziona la modalità di distribuzione dei raggi. |
| Ignora backface | Consente di specificare se le superfici posteriori devono essere considerate oggetti occlusi. |
| Occlusione autonoma | Seleziona le trame che devono influire sull’occlusione dell’ambiente per la trama corrente. |
| Attenuazione | Modificate la modalità di attenuazione dell’occlusione in base alla distanza dell’occluder. |
| Piano terreno | Abilitate questa opzione per creare un piano terreno che funga da occluder. |
| Offset piano terreno | Modificate la posizione del piano terreno. |

## Impostazioni mappa curvatura

| Impostazione | Funzione |
| --- | --- |
| Metodo | Scegliete come generare la mappa di curvatura. |
| Raggi secondari | Regolate il numero di raggi secondari utilizzati per generare la mappa di curvatura. Più raggi secondari possono produrre risultati migliori a scapito di tempi di elaborazione più lunghi. |
| Raggio di campionamento | Regolate la distanza di ricerca del fornaio per calcolare la curvatura del punto corrente. |
| Rispetto al rettangolo di selezione | Quando questa opzione è selezionata, tutte le distanze sono basate sulle dimensioni del rettangolo di selezione della trama. |
| Intersezione autonoma | Scegliete gli oggetti da considerare per la determinazione della curvatura. |
| Mappatura automatica dei toni (per porzione UV) | Lasciare selezionata questa opzione per regolare automaticamente le mappe di curvatura della tonemap in base ai singoli riquadri UV. |
| Mappatura toni min | Se la mappatura automatica dei toni è disattivata, regolate il valore minimo per la mappatura dei toni. |
| Mappatura toni max | Se l’opzione mappatura automatica toni è disattivata, regola il valore massimo per la mappatura toni. |

## Impostazioni mappa posizione

| Impostazione | Funzione |
| --- | --- |
| Modalità | Selezionare se generare una mappa di posizione di tutti gli assi o solo calcolare la posizione per un asse selezionato. |
| Asse | Se è selezionata la modalità Asse singolo, utilizzare questa impostazione per scegliere l&#39;asse da calcolare. |
| Tipo di normalizzazione | Modificate il modo in cui i valori delle posizioni vengono normalizzati, utilizzando un Rettangolo di selezione o una sfera di selezione oppure disattivate la normalizzazione. |
| Scala di normalizzazione | Modifica i limiti massimi dello spazio posizione. |

## Impostazioni mappa thickness

| Impostazione | Funzione |
| --- | --- |
| Raggi secondari | Modifica il numero di raggi secondari. Più raggi possono produrre risultati migliori a costo di tempi di elaborazione più lunghi. |
| Distanza minima occlusione | Regolate la distanza minima per i raggi da percorrere in modo da colpire la geometria poly elevata e influire sulla mappa di thickness risultante. |
| Distanza massima occlusione | I raggi che si estendono oltre questa distanza senza toccare la maglia di poli superiore sono considerati come non occlusi e non influiscono sulla mappa del thickness. |
| Relativo al rettangolo di selezione | Quando questa casella è selezionata, altre impostazioni che fanno riferimento alla distanza sono basate sul rettangolo di selezione della trama del progetto. Quindi una distanza di 1 è uguale alla dimensione del rettangolo di selezione. |
| Angolo di diffusione | Regolate l’intervallo angular dei raggi generati. Un angolo di estensione più elevato consente di occludere più facilmente una superficie mediante una geometria che non è posizionata perpendicolarmente alla superficie. |
| Distribuzione | Seleziona la modalità di distribuzione dei raggi. |
| Occlusione autonoma | Selezionate le trame che devono influire sul thickness della trama corrente. |
| Normalizzazione | Modificare la modalità di normalizzazione dei valori dei thickness. |

## Impostazioni mappa height

| Impostazione | Funzione |
| --- | --- |
| Normalizzazione | Modificare la modalità di normalizzazione dei valori dei height. |
| Divisore di scala | Se Normalizzazione è impostata su Manuale, utilizzare questo cursore per regolare il divisore di ridimensionamento e la normalizzazione della mappa dei height. |

## Impostazioni mappa delle normali di piegatura

| Impostazione | Funzione |
| --- | --- |
| Raggi secondari | Modifica il numero di raggi secondari. Più raggi possono produrre risultati migliori a costo di tempi di elaborazione più lunghi. |
| Distanza minima occlusione | Regolate la distanza minima per i raggi da percorrere in modo da colpire la geometria polare elevata e influire sulla mappa delle normali di piegatura risultante. |
| Distanza massima occlusione | I raggi che si estendono oltre questa distanza senza toccare la trama polare alta non sono considerati occlusi e non influenzano la mappa delle normali curve. |
| Relativo al rettangolo di selezione | Quando questa casella è selezionata, le altre impostazioni che fanno riferimento alla distanza si basano sul rettangolo di selezione della trama del progetto. Quindi una distanza di 1 è uguale alla dimensione del rettangolo di selezione. |
| Angolo di diffusione | Regolate l’intervallo angular dei raggi generati. Un angolo di estensione più elevato consente di occludere più facilmente una superficie mediante una geometria che non è posizionata perpendicolarmente alla superficie. |
| Distribuzione | Seleziona la modalità di distribuzione dei raggi. |
| Ignora backface | Scegliete se trattare le superfici posteriori come occlusioni. |
| Occlusione autonoma | Selezionate le trame che devono influire sulle normali di piegatura per la trama corrente. |
