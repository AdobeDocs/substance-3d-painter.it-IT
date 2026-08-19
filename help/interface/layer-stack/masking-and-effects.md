---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/interface/layer-stack/masking-and-effects.html"
breadcrumb-title: ''
description: Scoprite come utilizzare la mascheratura e gli effetti nel gruppo di livelli di Substance 3D Painter per controllare la visibilità dei livelli e applicare gli effetti di livello.
helpx_creative_field: ""
helpx_description: Painter > Interface > Layer stack > Masking and effects
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mascheratura ed effetti
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '473'
ht-degree: 5%

---


# Mascheratura ed effetti

## Mascheratura

I livelli possono essere mascherati per visualizzare/applicare il loro contenuto solo su parti specifiche della texture. La maschera funziona come un parametro di intensità sul contenuto del livello. Una maschera su un livello è sempre in scala di grigio, indipendentemente dal contenuto usato per colorare su di essa (pertanto qualsiasi colore verrà convertito in un valore di scala di grigio prima di essere colorato).

È possibile aggiungere una maschera utilizzando il menu di scelta rapida o il pulsante dedicato:

![](../../assets/layer-mask.gif)

Possibili operazioni sulle maschere:

* Puoi visualizzare la maschera stessa facendo **ALT + clic sinistro del mouse** sulla sua miniatura. Passa dalla finestra della vista a una vista isolata della maschera da questo livello. Questa operazione è disponibile anche tramite le impostazioni del visualizzatore.
* Potete disattivare temporaneamente una maschera facendo **MAIUSC + clic sinistro del mouse** sulla sua miniatura. Ripeti la stessa operazione per riattivarla. Questa operazione è disponibile anche tramite il menu di scelta rapida (&quot;attiva/disattiva maschera&quot;).
* Potete copiare il contenuto di una maschera su un&#39;altra maschera facendo **clic con il pulsante destro del mouse > Copia contenuto maschera** sulla miniatura ed **clic con il pulsante destro del mouse > Incolla nella maschera** sulla miniatura della seconda maschera.
* Per invertire lo sfondo della maschera, **fai clic con il pulsante destro del mouse e scegli Inverti sfondo maschera**. Questa funzione è utile per evitare di distruggere gli effetti associati a una maschera.

>[!WARNING]
>
> Se aggiungete di nuovo una maschera o la rimuovete, la maschera e tutti gli effetti ad essa collegati verranno distrutti.

È possibile creare immediatamente una maschera durante la creazione di un livello di riempimento (tramite trascinamento) se si preme il tasto **CTRL**:

![](../../assets/mask-material-optimized.gif)

## Effetti

Gli effetti sono operazioni speciali che possono essere modificate in qualsiasi momento. Gli effetti possono essere posizionati su una maschera di sul contenuto di un livello.\
Tuttavia, gli effetti sono più appropriati per l’altro. Ad esempio, i &quot;generatori&quot; sono appropriati per le maschere.

La linea sotto ogni miniatura su un livello indica se sono presenti effetti. Grigio è uguale a nessun effetto, rosso è uguale ad almeno un effetto. Esiste una serie di effetti per maschera e per contenuto.

![](../../assets/effect.gif)

Per ulteriori informazioni, [vedere la pagina dedicata](../../features/effects/effects.md).

## Maschere avanzate

Le maschere avanzate consentono di salvare una maschera e il suo effetto di riutilizzarle facilmente su altri livelli o progetti. Per creare una maschera avanzata, fate clic con il pulsante destro del mouse su una maschera e scegliete &quot;**Crea maschera avanzata**&quot;.\
Quando trascini una maschera avanzata su un livello, se non esiste già viene creata una maschera nera; in caso contrario, l’elenco degli effetti viene unito a quello esistente. È possibile sovrascrivere completamente l&#39;elenco degli effetti tenendo premuto &quot;**CTRL**&quot; quando si rilascia la maschera avanzata.

![](../../assets/smart-mask-new-optimized.gif)

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/smart-mask-add-optimized.gif)

</td>
<td style="border: 0;" valign="top">

![](../../assets/smart-mask-overwrite-optimized.gif)

</td>
</tr>
</table>
