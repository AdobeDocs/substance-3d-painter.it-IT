---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/content/creating-custom-effects/user-data.html"
breadcrumb-title: ''
description: Scopri come utilizzare i dati utente negli effetti personalizzati per consentire a Substance 3D Painter di passare informazioni personalizzate agli effetti shader.
helpx_creative_field: ""
helpx_description: Painter > Content > Creating custom effects > User data
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Dati utente
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '1175'
ht-degree: 1%

---


# Dati utente

Questa pagina descrive le proprietà personalizzate (dati utente) che possono essere aggiunte al grafico a Substance per eseguire comportamenti specifici.\
Le impostazioni dei dati utente vengono in genere applicate ai nodi di input o output di un grafico per indicare come devono essere interpretate dall’applicazione. Ciò consente di richiedere l’input di un grafico in modo tale da applicare gli effetti in un contesto noto (ad esempio, richiedere uno spazio cromatico specifico) o per indicare come è stato realizzato un output nel caso in cui l’applicazione debba applicare conversioni aggiuntive in seguito.

* Le impostazioni dei dati di utilizzo sono definite come **chiave = valore**
* Più impostazioni sono separate da un punto e virgola ( **;** )

## Spazio cromatico

L&#39;impostazione **spazio colore** può essere utilizzata per richiedere input del grafico Substance con uno spazio cromatico specifico o per definire un output configurato in un determinato modo. Ad esempio specificando il formato dell&#39;output della mappa normale.

Esempio di sintassi: **colorspace=$working**

Panoramica dei contesti:

* **Pulsante colore**: un widget del pulsante colore nelle proprietà di un grafico a Substance.
* **Input/output grafico**: nodo di input o output di un grafico connesso a un canale (ad esempio: BaseColor).
* **Input immagine**: input generico di un grafico, non correlato a canali specifici.

>[!NOTE]
>
> Con l’introduzione della gestione colore, sono stati modificati diversi comportamenti relativi all’impostazione degli spazi colore:
> 
> * La tabella seguente elenca prima le impostazioni dello spazio colore compatibili con le versioni precedenti alla 8.1. La seconda sezione è esclusiva della versione 8.1 e successive.
> * Per quanto riguarda i contesti in cui è possibile utilizzare l&#39;impostazione dello spazio colore, solo dal momento che la versione 8.1 può pulsante colore definire uno spazio colore. Nelle versioni precedenti si presume che siano nello spazio di visualizzazione (sRGB).
> 
> Le trasformazioni/spazi cromatici **snorm** e **unorm** non devono essere combinati con i formati di texture della GPU, il loro scopo è diverso.

| SpazioColore | Disponibilità contesto | Descrizione |
| --- | --- | --- |
| **auto** | Pulsante colore Input/output grafico Input immagine | Impostazione predefinita. L’applicazione decide la conversione dello spazio colore da eseguire a seconda delle proprietà del nodo di input e dell’immagine inserita nell’input. |
| **lineare** | Pulsante colore Input/output grafico Input immagine | Spazio cromatico standard sRGB IEC 61966-2-1:1999 con una curva gamma/tonalità lineare. Disponibile solo con la modalità di gestione colore **Legacy**. |
| **srgb** | Pulsante colore Input/output grafico Input immagine | Spazio colore standard sRGB IEC 61966-2-1:1999. Disponibile solo con la modalità di gestione colore **Legacy**. |
| **passthru** | Pulsante colore Input/output grafico Input immagine | Obsoleto. Interpretato come **lineare** in modalità di gestione colore legacy e **raw** con OCIO/ACE. Dovrebbe invece essere sostituito da **raw**. |
| **snorm** | Input/output grafico Input immagine | Firmato normalizzato. Richiedi che l&#39;immagine di input sia nell&#39;intervallo [0, 1]. Per le immagini di input a 8 bit questo significa che il valore medio è 127. Per gli input di immagini mobili, il centro è 0,5 e non esegue alcun bloccaggio. |
| **normalxyzright** | Input/output grafico Input immagine | Formato mappa normale OpenGL. |
| **normalxyzleft** | Input/output grafico Input immagine | formato mappa normale DirectX. |
|  |  |  |
| **unorm** | Input/output grafico Input immagine | Ingresso fluttuante, senza intervallo/bloccaggio. |
| **dati** | Pulsante colore Input/output grafico Input immagine | Normalizzato o float senza segno. Informazioni non colore. |
| **raw** | Pulsante colore Input/output grafico Input immagine | Quando questa impostazione viene utilizzata, non viene applicata alcuna trasformazione del colore. |
| **$standardsrgb** | Pulsante colore Input/output grafico Input immagine | Spazio colore standard sRGB IEC 61966-2-1:1999. |
| **$working** | Pulsante colore Input/output grafico Input immagine | Lo spazio colore di lavoro dipende dalle impostazioni di gestione del colore. Saranno identici ai dati per i canali gestiti senza colore e i canali mono (stencil, alfa, mask) |
| **$raw** | Pulsante colore Input/output grafico Input immagine | Alias per **raw**. |
| **$auto** | Pulsante colore Input/output grafico Input immagine | Alias per **auto**. |

## Modalità Alpha

È possibile utilizzare l&#39;impostazione **alfa** per specificare la modalità di combinazione dell&#39;alfa di un input o output di colore (RGBA).

Esempio di sintassi: **alpha=premoltiplicato**

| Impostazione | Descrizione |
| --- | --- |
| semplice | Richiedete o definite l&#39;alfa come retta. |
| premoltiplicato | Richiedi o definisci il canale alfa come premoltiplicato. |
| nessuno | Passthrough, utilizzare l&#39;alfa specificato così com&#39;è. |

>[!NOTE]
>
> Per impostazione predefinita, il canale **Opacità** è considerato **diritto**.

## Colore predefinito di input immagine

Il colore predefinito dell’immagine di un grafico a Substance è il nero, con il valore alfa impostato su 0. L&#39;impostazione **defaultcolor** consente di definire un valore diverso quando l&#39;input immagine di un grafico è vuoto

Per specificare il colore è possibile utilizzare valori mobili (intervallo [0, 1]) o interi (intervallo [0, 255]). Ogni valore del componente è separato da una virgola, mentre il valore a virgola mobile utilizza un punto come separatore decimale. Se un elemento mobile non ha un punto, verrà considerato come un numero intero.

Esempio di sintassi:

* **colore predefinito=(1.0,0.5,0.0)**
* **colore predefinito=(0,128,255)**

## Riempimento di input immagine

Per impostazione predefinita, l’input dell’immagine di un grafico a Substance non ha alcuna spaziatura interna, e l’area esterna all’Isola UV viene solitamente riempita con un colore uniforme per motivi legati alle prestazioni. L&#39;impostazione di riempimento può essere utilizzata per richiedere invece una dilatazione infinita, che può essere utilizzata per i filtri per evitare, ad esempio, la creazione di giunture.

Esempio di sintassi: **p**&#x200B;**adding=extend**

## Disabilitare un output per impostazione predefinita

Quando si aggiunge una sostanza in uno slot (come lo slot di materiale dello strumento di un livello di riempimento), è possibile specificare tramite il campo di testo metadati di non abilitare un canale specifico:

* In un nodo di output specifico (come un materiale): **disable=(true)**
* In un nodo di output generico (come un filtro): **disable=(height,diffusione,specular)**

Quando si carica la sostanza, questo canale non sarà attivato nell’interfaccia utente e quindi non avrà alcun effetto nel gruppo di livelli. L&#39;utente può comunque riattivare il canale.

## Designare un output come maschera/alfa comune

L’output di un grafico a Substance può essere utilizzato come canale/maschera alfa condivisa sugli altri output.

Questa operazione può essere eseguita in due modi:

* Creare un nodo di output con l&#39;identificatore **canali\_Alpha**
* Oppure aggiungi i seguenti dati utente in un nodo di output specifico: **IsChannelsAlpha=true**

Possono essere presenti alcune condizioni:

* Se esiste un nodo di output con l&#39;identificatore **canali\_Alpha** e altri output non dispongono dei dati utente, questo nodo verrà utilizzato come maschera dei canali.
* Se un output contiene i dati utente, verrà utilizzato come maschera dei canali finché non esiste alcun nodo **canali\_Alpha**.
* Se esistono sia un nodo **canali\_Alpha** che un nodo con i dati utente, verrà utilizzato per primo il nodo di output **canali\_Alpha**.
* Se più nodi dispongono dei dati utente, il primo nodo trovato dall&#39;applicazione verrà utilizzato come maschera dei canali. L’ordine in cui vengono trovati gli output non è garantito allo stesso modo definito dal grafico della Substance.

>[!NOTE]
>
> Queste impostazioni si applicano solo al grafico della Substance utilizzato in **modalità materiale**. Non si applica a filtri, generatori, ecc.

## Imposta il metodo di fusione predefinito per gli output di materiale

È possibile definire quale deve essere il metodo di fusione di un output specifico in un grafico a Substance quando si trascinano i materiali dallo scaffale nella finestra della vista o nella pila di livelli.

* In un nodo di output specifico: **blendingmode=normal**

Elenco dei metodi di fusione supportati:

* normale
* passthrough
* disattiva
* sostituire
* moltiplicare
* dividere
* inversedividi
* scurire
* schiarisci
* lineardodge
* sottrarre
* inversesubtract
* differenza
* esclusione
* signedadd
* sovrapponi
* schermo
* linearburn
* colorburn
* colordodge
* softlight
* luce intensa
* vividlight
* riflesso
* tinta
* saturazione
* colore
* valore
* normalcombine
* dettaglio normale
* normalinversedetail
