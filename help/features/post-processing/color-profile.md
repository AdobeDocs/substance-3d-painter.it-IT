---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/features/post-processing/color-profile.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la post-elaborazione del profilo colore in Substance 3D Painter per applicare la correzione del colore e le trasformazioni LUT.
helpx_creative_field: ""
helpx_description: Painter > Features > Post Processing > Color Profile
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Profilo colore
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '622'
ht-degree: 0%

---


# Profilo colore

![](../../assets/doc-lut-example.jpg){width="700px"}

Substance 3D Painter consente di assegnare **Profili colore** alle **viewports** caricando **LUT** texture.\
Un profilo colore può essere utilizzato per calibrare il colore finale dello schermo in modo che corrisponda a una destinazione, ad esempio una videocamera specifica. Spesso un profilo manipola i colori modificando la luminosità, il gamma, il contrasto o persino il bilanciamento del colore.

>[!NOTE]
>
> **LUT** è l&#39;acronimo di &quot;**Look Up Table**&quot;. Si tratta di un metodo ottimizzato per l’esecuzione di Color Grading come effetto post. Una LUT viene utilizzata per compensare la differenza tra una sorgente e un risultato.\
>  Substance 3D Painter utilizza **LUT 3D** archiviati come **texture 2D** (in virgola mobile) di qualsiasi risoluzione possibile (l&#39;impostazione predefinita è **2048x128 pixel** ). Ciò significa che il cubo che memorizza le operazioni di colore è separato in sezioni che vengono visualizzate l’una accanto all’altra. Per ulteriori dettagli tecnici, consulta l&#39;articolo **GPU**: <http://http.developer.nvidia.com/GPUGems2/gpugems2_chapter24.html>

## Utilizzo di un profilo colore

Un profilo colore può essere caricato tramite la finestra Impostazioni schermo.\
Selezionate la casella di controllo &quot; **Attiva profilo colore** &quot; per modificare la finestra della vista e attivare un profilo colore.

![](../../assets/color-profile-ui.png)

* Quando &quot;Attiva profilo colore&quot; è **disabilitato**, il rendering della finestra della vista viene eseguito in **sRGB** per la vista Materiale (e lineare per alcuni canali specifici)
* Quando &quot;Attiva profilo colore&quot; è **abilitato**, il rendering della finestra della vista viene eseguito in **Lineare/Raw** per ogni vista (inclusi i canali singoli)

Se una texture LUT viene caricata nello slot della risorsa, verrà utilizzata per modificare il rendering della finestra della vista in **modalità Materiale**.\
In caso contrario, il rendering verrà visualizzato come Lineare/Raw (ad esempio con le viste dei canali singoli).

L&#39;impostazione **punto bianco** può essere utilizzata per modificare la mappatura dei toni dell&#39;immagine di input (prima che la LUT abbia effetto).\
Se, ad esempio, state osservando il sole, il valore dovrebbe essere maggiore di 1 (impostazione predefinita). Per un&#39;esposizione perfetta, il punto bianco deve essere impostato sul valore alto dell&#39;immagine.

La formula di punto bianco è la seguente:

```
float Value = 1.0f / WhitePoint; // Value from the user interface 

float3 Output = clamp( HDR.rgb * Value, 0.0f, 1.0f );
```


È possibile applicare una mappatura tonale specifica prima di utilizzare un profilo colore. Consultate le funzioni disponibili in [Mappatura toni](tone-mapping.md).\
Substance 3D Painter elabora il colore di input solo tramite l’impostazione punto bianco. Ad esempio, non è stata applicata alcuna LUT Shaper.

## Creazione di profili colore

Substance 3D Painter sposterà la finestra della vista sul rendering **Lineare** quando l’opzione &quot; **Attiva profilo colore**&quot; è abilitata. Ciò significa che quando viene applicata una LUT, deve convertire il colore da un profilo lineare alla destinazione desiderata.

### Metodo 1: modifica della LUT identità

La modifica della LUT dell&#39;identità può essere eseguita in un software che supporta <b>32bit mobili</b> texture, ad esempio <b>Substance 3D Designer</b>. Scarica il LUT dell’identità come punto di partenza per creare un nuovo profilo:

[Scarica colore\_profilo\_linear.exr](https://github.com/AdobeDocs/painter-python-api/raw/refs/heads/main/static/misc/color_profile_linear.exr)

### Metodo 2: utilizzo di OpenColor IO per generare una texture LUT

Installa gli strumenti **OpenColor IO**. Scarica quindi la configurazione OCIO di esempio, disponibile qui: <http://opencolorio.org/downloads.html>\
Eseguire quindi il programma **ociolutimage** con gli argomenti seguenti:

```
ociolutimage --generate --cubesize 64 --config nuke-default/config.ocio --colorconvert linear srgb --output lutLinearToSRGB.exr
```


**Nota**: è anche possibile modificare il LUT identità con **OpenColor IO** utilizzando il programma **ocioconvert** per applicare la conversione colore a questo LUT.

### Importazione di un nuovo profilo colore

È sufficiente aprire la finestra di importazione (o trascinare e rilasciare il LUT nello scaffale). Quando importate la texture LUT in Substance 3D Painter, assicuratevi di assegnare il **utilizzo** &quot; **colorlut** &quot; alla nuova risorsa. In caso contrario, la risorsa non sarà visibile correttamente nello scaffale.

Per ulteriori informazioni, vedere la documentazione sull&#39;importazione di nuove risorse: [Aggiunta di risorse tramite la finestra di importazione](https://helpx.adobe.com/it/substance-3d/unlisted/documentation/spdoc/adding-content-via-the-import-window-151584824.html)
