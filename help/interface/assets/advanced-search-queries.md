---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/assets/advanced-search-queries.html"
breadcrumb-title: ''
description: Scopri come creare query di ricerca avanzate in Substance 3D Painter per trovare risorse specifiche utilizzando criteri di ricerca complessi.
helpx_creative_field: ""
helpx_description: Painter > Interface > Assets > Advanced search queries
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Query di ricerca avanzate
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---


# Query di ricerca avanzate

Le query di ricerca avanzate consentono di creare ricerche complesse e riutilizzarle come [ricerche salvate](saved-searches.md).

Le query avanzate possono essere utilizzate nella barra di ricerca e contenere:

1. **Percorso**: consente di perfezionare il risultato di una ricerca in base a una struttura di cartelle/cartelle.
1. **Utilizzo**: elenca tutti i possibili utilizzi disponibili nell&#39;applicazione
1. **Query di testo**: consente di aggiungere liberamente qualsiasi altro tipo di query (come le parole chiave personalizzate)

Quando si definisce una nuova query di ricerca, sono consentite più selezioni.

## Tracciato

La query con percorso consente di rifinire una query basata su un percorso. Nel pannello **Filtra per percorso** sono elencate tutte le librerie disponibili (che puoi aggiungere autonomamente tramite Modifica > Impostazioni > Librerie).\
È possibile utilizzare la definizione del percorso per filtrare in base al percorso di libreria personalizzato o a specifiche sottocartelle nella gerarchia.

## Utilizzo

Utilizzo: definizione di risorsa e utilizzo in Substance 3D Painter. Alcuni possono essere definiti dal tipo di file della risorsa.\
Ad esempio:

* **pbr.glsl**: file shader che può essere utilizzato solo come shader e nient&#39;altro.
* **effetto.sbsar**: un file substance: può essere un generatore, un filtro o anche un materiale, pertanto se il suo utilizzo non è impostato nel grafico originale (in Designer), dovrà essere indicato dall&#39;utente in Painter al momento dell&#39;importazione.

## Testo

La query di testo supporta diversi tipi di filtro, alcuni dei quali sono più avanzati dell&#39;interfaccia normale.\
Possono essere attivati digitando le parole chiave corrette.

* **Tipi di ricerca disponibili**:
  * &quot; **n:** &quot;: nome
  * &quot; **s:** &quot;: shelf/library (include &quot;session&quot; e &quot;project&quot;)
  * &quot; **p:** &quot;: percorso
  * &quot; **u:** &quot;: utilizzo
* **Escaping**: è possibile utilizzare &quot; **\** &quot; prima del carattere di cui è necessario eseguire l&#39;escape oppure utilizzare le virgolette, ad esempio:
  * **a\ nome\ con\ spazi**
  * **&quot;un nome con spazi&quot;**
* **Attributi (o gruppo) specifici**: per eseguire ricerche in attributi specifici, anteporre &#39;or group&#39; a un identificatore di tipo. Esempio:
  * **n:a,b,c,d**: il nome è a oppure b oppure c oppure d
* **Comportamento ricerca**:
  * Per filtrare utilizzi specifici, aggiungi la **parola chiave** specifica alla ricerca, ad esempio: &quot; **immagini** ambiente&quot;
  * Per aggiungere più richieste, utilizzare una virgola &quot; **,** &quot;, ad esempio: &quot;cobalto **,** oro&quot; (se si utilizza una virgola, la ricerca mostrerà solo una risorsa che corrisponde a entrambe le parole chiave contemporaneamente)
  * Per cercare un nome esatto, utilizzare un punto esclamativo &quot;!&quot; alla fine, esempio: **di!**  (restituirà **dirt** ma non **gocce** , questa parola chiave disabiliterà la corrispondenza fuzzy)
  * Per escludere un motivo da una ricerca, utilizzare un trattino &quot; **-** &quot;, ad esempio: **u:image n:-normal** (restituirà immagini che non contengono &quot;normal&quot;)
* **Funzioni corrispondenti (suffisso pattern):**
  * **impostazione predefinita**: corrispondenza approssimativa (approssimativa)
  * **contiene** : !
  * **regex**: #
  * **uguale** : =
  * **inizia con**: ^
  * **termina con** : &amp;
