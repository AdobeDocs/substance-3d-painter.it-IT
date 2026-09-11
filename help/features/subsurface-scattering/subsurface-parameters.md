---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/subsurface-scattering/subsurface-parameters.html"
breadcrumb-title: ''
description: Scoprite come configurare i parametri di dispersione del sottosuolo in Substance 3D Painter per creare materiali traslucidi realistici.
helpx_creative_field: ""
helpx_description: Painter > Features > Subsurface Scattering > Subsurface Parameters
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Parametri sottosuperficie
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 0%

---


# Parametri sottosuperficie

L&#39;implementazione del sottosuolo in tempo reale di Substance 3D Painter è un effetto di dispersione del sottosuolo dello spazio dello schermo. I parametri per controllarlo sono illustrati in questa pagina.\
L&#39;implementazione corrente si basa sul metodo &quot;Approssima profili di riflessione per dispersione efficiente sottosuperficie&quot; [pubblicato da PIXAR](http://graphics.pixar.com/library/ApproxBSSRDF/).

Per esempi di materiali basati su questi parametri, vedere: [Tipo di materiale sottosuperficie](subsurface-material-type.md).

## Parametri Shader/MDL

![](../../assets/shader-parameters.png)

Disponibile nella finestra [Impostazioni Shader](../../interface/shader-settings/shader-settings.md).

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Abilita** | Attivate o disattivate l&#39;effetto Dispersione sottosuperficie su questa istanza di shader/mdl.  Può essere utilizzato per disattivare l&#39;effetto SSS su materiale che non ne ha bisogno. |
| **Tipo di dispersione** | Definisce il comportamento dell&#39;assorbimento di luce nel materiale:<ul data-preserve-html="true"><li data-preserve-html="true"><strong> Traslucido</strong>: adatto per materiali generici come giada o marmo in cui la luce può penetrare profondamente in un oggetto.</li><li data-preserve-html="true"><strong> Incarnato</strong>: adatto per la pelle organica, in cui la luce viene assorbita rapidamente e dispersione solo vicino alla superficie.</li><li data-preserve-html="true"><strong>Red Shift/Rayleigh</strong>: più accurato dell’impostazione della pelle per simulare la pelle superficiale di esseri umani o creature.</li></ul> |
| **Scala** | Controlla il raggio/la profondità dell&#39;assorbimento luminoso nel materiale. Questo comportamento del parametro cambia a seconda della dimensione della trama nella scena.Confronto tra una scala di 0,0, 0,2 e 1,0 su una testa di dimensioni umane:   <div><img data-preserve-html="true" src="../../assets/scale-sss.jpg" width="650"/></div> |
| **Colore** | Il colore della luce quando viene assorbita dal materiale.Confronto tra tre colori:   <div><img data-preserve-html="true" src="../../assets/color-sss.jpg" width="650"/></div> |

### Parametri delle impostazioni di visualizzazione

![](../../assets/display-settings-1.png)

Disponibile nella finestra [Impostazioni schermo](../../interface/display-settings/display-settings.md).

>[!NOTE]
>
> Questo parametro **ha effetto solo** sulla versione **in tempo reale** dell&#39;effetto di dispersione della superficie.

| *Impostazione* | *Descrizione* |
| --- | --- |
| **Numero di campioni** | Controlla la quantità di campioni che verranno eseguiti per generare la sfocatura della sottosuperficie nello spazio dello schermo. Più campioni significa meno rumore, ma influirà sulle prestazioni.Confronto tra 8, 32 e 64 campioni quando si guarda vicino a una superficie :   <div><img data-preserve-html="true" src="../../assets/samples-sss-v2.jpg" width="650"/></div>  **Nota:** la quantità di disturbo può essere ridotta anche attivando [Impostazioni videocamera](../../interface/display-settings/camera-settings.md) senza aumentare la quantità di campioni. |
