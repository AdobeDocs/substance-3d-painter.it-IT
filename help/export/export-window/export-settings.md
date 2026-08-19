---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/getting-started/export/export-window/export-settings.html"
breadcrumb-title: ''
description: Scopri come configurare le impostazioni di esportazione in Substance 3D Painter per controllare la risoluzione, il formato e le opzioni di output delle texture.
helpx_creative_field: ""
helpx_description: Painter > Getting Started > Export > Export window > Export settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Impostazioni di esportazione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '958'
ht-degree: 1%

---


# Impostazioni di esportazione

![](../../assets/image2023-1-30-13-22-30.png){width="500px"}

La <b>scheda Impostazioni di esportazione</b> della <b>finestra Esporta texture</b> consente di configurare la composizione, le dimensioni e la posizione delle texture esportate.

## Configurazione generale e set di texture

![](../../assets/texture-set-list-1.png)

Il primo elemento della finestra è l&#39;elenco dei set di texture a sinistra. La sezione Impostazioni globali consente di accedere a parametri comuni a tutti gli insiemi di texture. In questo modo è più semplice regolare un singolo set di impostazioni da applicare a tutti i set di texture del progetto. Le modifiche apportate alle singole impostazioni dei set di texture hanno precedenza sulle impostazioni globali per quel set di texture. Ad esempio, impostando la risoluzione su 2048 nelle impostazioni globali e su 1024 come esclusione per un set di texture specifico, tutti i set di texture verranno esportati con una risoluzione di 2048, tranne quello su 1024.

La casella di controllo accanto al nome di ciascun set di texture indica se le texture associate verranno esportate o meno.

Il menu a discesa è utile per i progetti che dispongono di un numero elevato di set di texture, in quanto consente di modificare rapidamente la selezione con <b>Seleziona tutto</b>, <b>Deseleziona tutto</b> e <b>Inverti tutte le </b>azioni.

## Parametri generali di esportazione

![](../../assets/image2023-1-30-13-23-7.png)

Questa sezione contiene le impostazioni condivise per ogni texture che verrà generata:

| Impostazione | Descrizione |
| --- | --- |
| <b>Directory di output</b> | Salvate il percorso per le texture esportate. |
| <b>Modello di output</b> | Selezionate il modello di output usato per assegnare un nome ai canali e comporli in file di texture. Per ulteriori informazioni sui modelli, vedere l&#39;elenco [Modelli di output](../export-presets/export-presets.md). |
| <b>Tipo di file </b> | Il formato di file e la relativa profondità di bit. Se è selezionata l&#39;opzione <b>Basato sul modello di output</b>, il formato del file viene ereditato dal predefinito di esportazione (che consente di determinare il formato e la profondità di bit per texture anziché globalmente). La profondità di bit disponibile dipende dal tipo di file; per ulteriori informazioni, vedere la tabella seguente. |
| <b>Dimensione </b> | La risoluzione del file di texture esportato. Valori possibili:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>In base alle dimensioni di ciascun set di texture</b></li> <li data-preserve-html="true"><b>128</b></li> <li data-preserve-html="true"><b>256</b></li> <li data-preserve-html="true"><b>512</b></li> <li data-preserve-html="true"><b>1024</b></li> <li data-preserve-html="true"><b>2048</b></li> <li data-preserve-html="true"><b>4096</b></li> <li data-preserve-html="true"><b>8192</b> (disponibile solo con GPU con più di 1,5 GB di Vram)</li> </ul> |
| <b>Spaziatura interna </b> | Come riempire l’area al di fuori delle Isole UV all’interno della texture. I valori possibili sono:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Nessuna spaziatura interna (passthrough)</b>: utilizzare lo stato corrente della texture così com&#39;è.</li> <li data-preserve-html="true"><b>Dilatazione infinita</b>: allungare i bordi dell&#39;Isola UV fino a raggiungere i bordi adiacenti o la fine della texture.</li> <li data-preserve-html="true"><b>Dilatazione + trasparente</b>: allunga i bordi dell’Isola UV alla distanza specificata in pixel, il resto è trasparente.</li> <li data-preserve-html="true"><b>Dilatazione + colore di sfondo predefinito</b>: allunga i bordi dell’Isola UV fino alla distanza specificata in pixel; il resto viene riempito con il colore predefinito del canale del set di texture.</li> <li data-preserve-html="true"><b>Dilatazione + colore di sfondo predefinito</b>: allunga i bordi dell’Isola UV fino alla distanza specificata in pixel; il resto viene riempito con il colore predefinito del canale del set di texture.</li> <li data-preserve-html="true"><b>Dilatazione + diffusione</b>: allunga i bordi dell’Isola UV alla distanza specificata in pixel, il resto viene riempito con una versione sfocata dell’Isola UV (in base alle mappe mip).</li> </ul> |

>[!NOTE]
>
> Il formato di file **psd** è un contenitore. Ciò significa che le mappe di output verranno raccolte insieme all&#39;interno di un singolo file su disco.

### Dithering

L’esportazione di texture a 8 bit può causare bande nelle sfumature. Ciò è particolarmente evidente con le mappe Normale e Height. Esistono due modi per risolvere questo problema: utilizzando una precisione maggiore o compensando con il dithering.

Una maggiore precisione (16 o 32 bit) è ideale, ma potrebbe non essere compatibile con tutte le applicazioni. In particolare, i motori di gioco spesso si comprimono a 8 bit. Il dithering consente di ridurre i problemi di banding pur continuando a utilizzare 8 bit di informazioni.

![](../../assets/dither-1.jpg)

### Formati di file Texture

Di seguito è riportato un elenco di tutti i formati di file di esportazione supportati da Painter:

| Nome formato | Estensione formato | Profondità di bit supportata |
| --- | --- | --- |
| **Bitmap** | bmp | 8, 8 + dithering |
| **OpenEXR** | exr | 16 (galleggiante), 32 (galleggiante) |
| **Graphics Interchange Format** | gif | 8, 8 + dithering |
| **Radiance HDR** | hdr | 32 (fluttuante) |
| **Icona** | ico | 8, 8 + dithering |
| **Jpeg 2000** | j2k | 8, 8 + dithering, 16 |
| **Grafica Di Rete Jpeg** | jng | 8, 8 + dithering, 16 |
| **Jpeg 2000** | jp2 | 8, 8 + dithering, 16 |
| **Jpeg** | jpeg | 8, 8 + dithering |
| **Intervallo esteso JPEG** | jpeg-x | 8, 8 + dithering, 16, 32 (fluttuante) |
| **Portable Bit Map** | pbm | 8, 8 + dithering, 16 |
| **Mappa mobile portatile** | pfm | 32 (fluttuante) |
| **Mappa grigia portatile** | pgm | 8, 8 + dithering, 16 |
| **Portable Network Graphics** | png | 8, 8 + dithering, 16 |
| **Pixel Map Portatile** | ppm | 8, 8 + dithering, 16 |
| **Documento Photoshop** | psd | 8, 8 + dithering, 16 |
| **Truevision TGA** | targa | 8, 8 + dithering |
| **Formato file immagine tag** | tiff | 8, 8 + dithering, 16, 32 (fluttuante) |
| **Formato Bitmap protocollo applicazione wireless** | wbmp | 8, 8 + dithering |
| **WebP** | webp | 8, 8 + dithering |
| **X PixMap** | xpm | 8, 8 + dithering |

## Mappe di output

Quando è selezionato un set di texture specifico, per tale set è visibile la sezione Mappe di output.

![](../../assets/export-output-maps.png)

Questa sezione elenca tutte le texture che verranno generate in base al predefinito di esportazione corrente. Indica il modello di nome della texture, il formato di file, la profondità di bit e lo spazio colore se è abilitata la [Gestione colore](../../features/color-management/color-management.md).

Questa sezione consente di disabilitare l&#39;esportazione di file specifici o di ignorare il <b>formato file</b> e la <b>profondità di bit</b>.

![](../../assets/export-override.gif)

## Esporta risorsa USD

Seleziona questa casella per consentire l’esportazione in formato USD. A differenza del predefinito USDz (Apple AR) disponibile in <b>Modelli di output</b>, questa esportazione terrà in considerazione qualsiasi modello o parametro configurato per l&#39;esportazione. I seguenti file vengono esportati quando si seleziona la casella della risorsa USD:

* Cartella con mappe texture
* *.usda* che punta alla cartella delle mappe texture.
* Un file .usd opzionale che assembla i materiali con il file mesh originale. Può essere utilizzato direttamente in Omniverse per mostrare la tua trama con i materiali applicati automaticamente.
* Un file .usd opzionale, che include la trama utilizzata nel progetto. Viene esportato solo se il file di trama originale non è un file USD o se per generare gli UV è stato utilizzato lo scorrimento automatico di Painter.
