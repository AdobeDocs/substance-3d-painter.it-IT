---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/painting/presets/photoshop-brush-presets-abr/photoshop-brush-parameters-compatibility.html"
breadcrumb-title: ''
description: Informazioni sulla compatibilità dei parametri dei pennelli di Photoshop in Substance 3D Painter durante l’importazione dei predefiniti dei pennelli ABR.
helpx_creative_field: ""
helpx_description: Painter > Painting > Presets > Photoshop Brush Presets (ABR) > Photoshop Brush Parameters Compatibility
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Compatibilità dei parametri dei pennelli Photoshop
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '645'
ht-degree: 1%

---


# Compatibilità dei parametri dei pennelli Photoshop

In questa pagina sono elencati tutti i parametri dei pennelli di Photoshop e la loro compatibilità con il motore dei pennelli di Substance 3D Painter.

## Compatibilità generale

Quando si osserva all’interno del file ABR, Substance 3D Painter recupera solo pennelli/strumenti predefiniti specifici:

| *Tipo predefinito* | *Supporto* | *Descrizione* |
| --- | --- | --- |
| **Pennello (bitmap)** | Importato | I pennelli predefiniti basati sulle bitmap verranno importati come alfa. |
| **Pennello (procedurale)** | Ignorato | I pennelli predefiniti basati su forme procedurali (come un cerchio) non vengono importati. |
| **Pennello (Aerografo)** | Ignorato | I predefiniti dei pennelli con le impostazioni Aerografo non vengono importati. |
| **Pennello (setole)** | Ignorato | I predefiniti per i pennelli con impostazioni Setole non vengono importati. |
| **Pennello (Commestibile)** | Ignorato | I pennelli predefiniti con le impostazioni Pennello modificabile non vengono importati. |
| **Matita** | Ignorato | I predefiniti Matita non vengono importati. |
| **Pennello miscela colori** | Ignorato | I predefiniti per i pennelli miscela colori non vengono importati. |
| **Timbro clone** | Ignorato | I predefiniti di Timbro clone non vengono importati. |
| **Sfumino** | Ignorato | I predefiniti Sfumino non vengono importati. |

## Parametri

Per ulteriori informazioni sulle funzionalità di questi parametri, consultare la [documentazione ufficiale di Photoshop](https://helpx.adobe.com/it/photoshop/using/creating-modifying-brushes.html) .

Non tutti i parametri dei pennelli di Photoshop sono supportati. Fare riferimento alla legenda per conoscere lo stato di ogni parametro descritto di seguito:

* **Quadrato (■)**: indica che il parametro è supportato. Per informazioni sull&#39;accesso, vedere la descrizione.
* **Crocetta (✖)**: indica che il parametro non è supportato.

>[!NOTE]
>
> Mentre i parametri di controllo nei predefiniti del pennello possono essere controllati con vari metodi, ad esempio Inclinazione penna, Dissolvenza e Pressione penna, attualmente è supportata solo la **Pressione penna**.

| *Gruppo* | *Parametro* | *Supporto* | *Descrizione* |
| --- | --- | --- | --- |
| Forma punta pennello | **Dimensioni** | ■ | Corrispondente al parametro Dimensione strumento di disegno.  **Nota:** Photoshop definisce la dimensione in pixel, mentre la dimensione di Substance 3D Painter si basa sul Rettangolo di selezione del progetto. Una corrispondenza esatta non è quindi possibile e sarà solo relativa. |
| **Rifletti X** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Rifletti Y** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Angolo** | ■ | Corrispondente al parametro Angolo dello strumento di disegno. |  |
| **Rotondità** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Durezza** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Spaziatura** | ■ | Corrispondente al parametro Spaziatura dello strumento di disegno. |  |
|  |  |  |  |
| Dinamica forme | **Variazione dimensioni** | ■ | Corrisponde al parametro Variazione dimensione strumento di disegno. |
| **Controllo (per dimensione)** | ■ | Corrispondente all&#39;impostazione Pressione dello strumento di disegno per il parametro Dimensione . |  |
| **Diametro Minimo** | ■ | Corrispondente al parametro Dimensione minima dello strumento di pittura. |  |
| **Scala inclinazione** | ✖ |  |  |
| **Variazione angolo** | ■ | Corrisponde al parametro Variazione angolo dello strumento di disegno. |  |
| **Controllo (per Angolo)** | ✖ |  |  |
| **Variazione rotondità** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Rotondità minima** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Variazione rifl. X** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Variazione rifl. Y** | ■ | Gestito tramite il file di Substance &quot;Brush Maker Photoshop&quot;. |  |
| **Proiezione pennello** | ✖ |  |  |
|  |  |  |  |
| Dispersione | **Dispersione** | ■ | Corrisponde al parametro Variazione posizione dello strumento di disegno. |
| **Entrambi gli assi** | ■ | Corrispondenza con il parametro Variazione posizione asse dello strumento di disegno. |  |
| **Controllo (per Dispersione)** | ✖ |  |  |
| **Conteggio** | ■ | Compensata tramite il parametro Spaziatura dello strumento di pittura. |  |
| **Variazione conteggio** | ✖ |  |  |
| **Controllo (per variazione conteggio)** | ✖ |  |  |
|  |  |  |  |
| Texture | **Motivo texture** | ✖ |  |
| **Inverti** | ✖ |  |  |
| **Scala** | ✖ |  |  |
| **Luminosità** | ✖ |  |  |
| **Contrasto** | ✖ |  |  |
| **Texture Ogni Punta** | ✖ |  |  |
| **Modalità** | ✖ |  |  |
| **Profondità** | ✖ |  |  |
| **Profondità minima** | ✖ |  |  |
| **Variazione Profondità** | ✖ |  |  |
| **Controllo (per variazione Profondità)** | ✖ |  |  |
|  |  |  |  |
| Pennello doppio | **Modalità** | ✖ |  |
| **Dimensioni** | ✖ |  |  |
| **Spaziatura** | ✖ |  |  |
| **Dispersione** | ✖ |  |  |
| **Entrambi gli assi** | ✖ |  |  |
| **Conteggio** | ✖ |  |  |
|  |  |  |  |
| Dinamica del colore | **Applica Per Suggerimento** | ✖ |  |
| **Variazione primo piano/sfondo** | ✖ |  |  |
| **Controllo (per variazione F/B)** | ✖ |  |  |
| **Variazione tonalità** | ✖ |  |  |
| **Variazione saturazione** | ✖ |  |  |
| **Variazione luminosità** | ✖ |  |  |
| **Purezza** | ✖ |  |  |
|  |  |  |  |
| Transfert | **Variazione opacità** | ■ | Corrispondente con i timbri dello strumento di pittura Il parametro di fusione è impostato su &quot;Schiarisci&quot;. |
| **Controllo (per opacità)** | ■ | Corrispondente all&#39;impostazione Pressione dello strumento di disegno per il parametro Flusso. |  |
| **Minimo (per il controllo dell&#39;opacità)** | ■ | Corrispondente al parametro Flusso minimo dello strumento di pittura. |  |
| **Variazione flusso** | ■ | Corrispondente al parametro Variazione flusso dello strumento di disegno. |  |
| **Controllo (per Flusso)** | ■ | Corrispondenza con l&#39;impostazione Pressione dello strumento di pittura per il parametro Flusso (se minore di Opacità). |  |
| **Minimo (per il controllo di flusso)** | ■ | Corrispondenza con il parametro Flusso minimo dello strumento di pittura (se inferiore a Opacità). |  |
| **Variazione umidità** | ✖ |  |  |
| **Controllo (per variazione umidità)** | ✖ |  |  |
| **Minimo (per controllo umidità)** | ✖ |  |  |
| **Variazione mix** | ✖ |  |  |
| **Controllo (per Mix)** | ✖ |  |  |
| **Minimo (per il controllo Mix)** | ✖ |  |  |
|  |  |  |  |
| Posa pennello | **Inclinazione X** | ✖ |  |
| **Ignora inclinazione X** | ✖ |  |  |
| **Inclinazione Y** | ✖ |  |  |
| **Sovrascrivi inclinazione Y** | ✖ |  |  |
| **Rotazione** | ✖ |  |  |
| **Ignora rotazione** | ✖ |  |  |
| **Pressione** | ✖ |  |  |
| **Sovrascrivi pressione** | ✖ |  |  |
|  |  |  |  |
| Altro | **Disturbo** | ✖ |  |
| **Bordi bagnati** | ✖ |  |  |
| **Build-up** | ✖ |  |  |
| **Arrotondamento** | ■ | Non corrisponde direttamente, ma può essere gestito tramite l&#39;impostazione [Lazy Mouse](../../lazy-mouse.md). |  |
| **Texture Protect** | ✖ |  |  |
