---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/text-resource.html"
breadcrumb-title: ''
description: Scoprite come utilizzare le risorse di testo in Substance 3D Painter per aggiungere testo e composizione tipografica ai flussi di lavoro di pittura delle texture.
helpx_creative_field: ""
helpx_description: Substance 3D Painter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Risorsa testo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '521'
ht-degree: 0%

---


# Risorsa di testo

![](../assets/v10_text_resource_banner-1.jpg)

La <b>risorsa di testo</b> in può essere utilizzata per scrivere testo nelle texture con <b>file di font</b> specifici. Sono disponibili diversi parametri per regolare l’aspetto del testo finale disegnato.

## Esplorazione dei font

Per sfogliare i file dei font disponibili, è sufficiente fare clic sul filtro dei font (pulsante <b>T</b>) nella [finestra Risorse](../interface/assets/assets.md):

![](../assets/v10_text_assets.png)

I font possono anche essere filtrati in base ai percorsi, a seconda di dove si trovano sul sistema:

![](../assets/v10_font_path.png)

Le posizioni dei font disponibili dipendono dal sistema operativo corrente:

|  |  |
| --- | --- |
| Windows | <ul data-preserve-html="true"> <li data-preserve-html="true"><b>Sistema</b>: C:/Windows/Fonts</li> <li data-preserve-html="true"><b>Utente</b>: C:/Users/username/Appdata/Local/Microsoft/Windows/Fonts</li> </ul> |
| MacOS | <ul data-preserve-html="true"> <li data-preserve-html="true"><b>Sistema</b>: /Sistema/Libreria/Font</li> <li data-preserve-html="true"><b>Locale</b>: /Libreria/Font</li> <li data-preserve-html="true"><b>Utente</b>: /Utenti/nome utente/Libreria/Font</li> </ul> |
| Linux | <ul data-preserve-html="true"> <li data-preserve-html="true"><b>Sistema</b>: /usr/share/fonts/</li> <li data-preserve-html="true"><b>Locale</b>: /usr/local/share/fonts/</li> <li data-preserve-html="true"><b>Utente</b>: /home/nomeutente/.local/share/fonts/</li> </ul> |

### Importazione dei font

I font possono essere importati manualmente o inseriti in una libreria di Painter esistente come qualsiasi risorsa normale. Per farlo, consulta la [documentazione sull&#39;importazione](../content/importing-assets/import-drag-and-drop.md).

Painter supporta entrambi i formati di font <b>.ttf</b> e <b>.otf</b>.

>[!NOTE]
>
> Se una risorsa non viene caricata o importata con il messaggio di errore &quot;Impossibile importare a causa della restrizione di licenza del font&quot; significa che non può essere utilizzata da Painter. È possibile utilizzare solo font contrassegnati come <b>incorporabili</b> nei metadati.

### Utilizzo di un font come risorsa di testo

Una risorsa texture funziona come altre risorse (ad esempio immagini o materiali per Substance) e può essere utilizzata nei parametri del pennello, nelle proiezioni di riempimento o negli input dell’immagine Substance.

Per creare una risorsa di testo è sufficiente aggiungere un font in uno slot della risorsa. È anche possibile trascinare un font nella finestra della vista.

![](../assets/v10_text_drag_drop.gif)

### Parametri risorsa testo

Una risorsa di testo ha i seguenti parametri di base:

![](../assets/v10_text_params_base.png)

| <b>Parametro</b> | <b>Descrizione</b> |
| --- | --- |
| <b>Testo</b> | Testo da sottoporre a rendering.  **Nota:** il campo di testo nell&#39;interfaccia utilizza un carattere generico con un&#39;ampia gamma di caratteri che potrebbe creare discrepanza tra il testo digitato nel campo e il carattere selezionato che può essere riprodotto nella texture. |
| <b>Dimensione font</b> | Specificate la modalità utilizzata per calcolare la dimensione del font. Le modalità disponibili sono:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Automatico</b>: la dimensione viene calcolata automaticamente dal contenuto del testo e si adatta alla texture.</li> <li data-preserve-html="true"><b>Personalizzato</b>: la dimensione può essere controllata manualmente tramite l&#39;impostazione dedicata.</li> </ul> |
| <b>Allineamento</b> | Controlla l&#39;allineamento verticale e orizzontale. Usate i pulsanti per scegliere la modalità da usare. |
| <b>Colore</b> | Colore del testo di cui è stato eseguito il rendering. Questa impostazione può essere in scala di grigio se la risorsa di testo viene utilizzata in una maschera o in un canale in scala di grigio. |

Sono disponibili anche parametri più avanzati:

![](../assets/v10_text_params_advanced.png)

| <b>Parametro</b> | <b>Descrizione</b> |
| --- | --- |
| <b>Interlinea</b> | Distanza tra le righe di testo (&quot;interlinea&quot;) relativa alla dimensione del font. |
| <b>Spaziatura tra caratteri</b> | Quantità di spazio tra caratteri adiacenti in relazione alla dimensione del carattere. Può essere negativo per sottrarre la spaziatura. |
| <b>Scostamento</b> | Offset orizzontale e verticale del testo. Normalizzato in base alla dimensione del font. |
| <b>Riempimento sfondo</b> | Colore dello sfondo dietro il testo. |
| <b>Opacità sfondo</b> | Quanta parte del colore di sfondo è visibile. |
| <b>Risoluzione</b> | Specificate la modalità utilizzata per calcolare le dimensioni della texture utilizzata per eseguire il rendering del testo. Le modalità disponibili sono:<ul data-preserve-html="true"> <li data-preserve-html="true"><b>Automatico</b>: la risoluzione viene calcolata automaticamente.</li> <li data-preserve-html="true"><b>Personalizzato</b>: la risoluzione può essere definita manualmente tramite l&#39;impostazione dedicata.</li> </ul> |
