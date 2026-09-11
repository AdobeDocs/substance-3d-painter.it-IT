---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/features/sparse-virtual-textures.html"
breadcrumb-title: ''
description: Scoprite come utilizzare le texture virtuali sparse in Substance 3D Painter per lavorare con texture ad altissima risoluzione in modo efficiente.
helpx_creative_field: ""
helpx_description: Painter > Features > Sparse Virtual Textures
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Texture virtuali sparse
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '748'
ht-degree: 0%

---


# Texture virtuali sparse

![](../assets/svt-header.jpg)

A partire dalla versione **2018.3** Substance 3D Painter utilizza **Texture virtuali sparse** ( **SVT** ) nella relativa finestra della vista in tempo reale per gestire grandi quantità di texture. Questa tecnologia consente lo streaming in/out di texture che sono necessarie solo da un determinato punto di vista al fine di mantenere un impatto specifico sulla memoria GPU. Migliora le prestazioni sui progetti con una grande quantità di set di texture (o UDIM).

## Piattaforme supportate

![](../assets/sparse-settings.png)

Le texture sparse si basano su una configurazione hardware specifica per garantire prestazioni ottimali. Se la configurazione corrente non la supporta correttamente, Substance 3D Painter **eseguirà il fallback** a un&#39;implementazione software (meno precisa e meno efficiente).

È possibile forzare Substance 3D Painter a utilizzare il fallback software invece dell&#39;accelerazione hardware selezionando [Impostazioni](../interface/settings/settings.md).

Di seguito è riportata la configurazione che supporta le texture virtuali sparse con accelerazione hardware:

| Piattaforma | Supportato (con accelerazione hardware) | Non supportato (fallback software) |
| --- | --- | --- |
| **Windows** | <ul data-preserve-html="true"><li data-preserve-html="true">Nvidia GeForce (driver 411.63 o superiori)</li><li data-preserve-html="true">Nvidia Quadro (Driver 411.63 o superiori)</li><li data-preserve-html="true">AMD FirePro e Radeon Pro (driver 18.9.3 o superiori) <strong> &#42; </strong></li><li data-preserve-html="true">AMD Radeon (driver 18.9.3 o superiori)&#42;</li></ul> | <ul data-preserve-html="true"><li data-preserve-html="true"> Nvidia Quadro M2000 </li><li data-preserve-html="true">  Nvidia Geforce GTX 970 </li><li data-preserve-html="true"> GPU Intel </li></ul> |
| **SO Mac** | <ul data-preserve-html="true"><li data-preserve-html="true"> Funzionalità hardware non supportata dal sistema operativo </li></ul> | <ul data-preserve-html="true"><li data-preserve-html="true">Qualsiasi modello GPU</li></ul> |
| **Linux** | <ul data-preserve-html="true"><li data-preserve-html="true">Nvidia GeForce (driver 410.73 o superiori)</li><li data-preserve-html="true">Nvidia Quadro (Driver 410.73 o superiori)</li><li data-preserve-html="true">AMD FirePro e Radeon Pro (driver 18.9.3 o superiori) <strong> &#42; </strong></li><li data-preserve-html="true">AMD Radeon (driver 18.9.3 o superiori)&#42;</li></ul> | <ul data-preserve-html="true"><li data-preserve-html="true">GPU Intel</li></ul> |


* **\***: l&#39;accelerazione hardware è disabilitata per impostazione predefinita e può essere abilitata manualmente in [Impostazioni](../interface/settings/settings.md).

## Perché Substance 3D Painter utilizza Texture virtuali sparse?

Substance 3D Painter utilizza il suo motore principale per il calcolo delle texture che vengono quindi visualizzate nelle finestre delle viste. Ciò significa che il motore e la finestra della vista devono condividere la memoria GPU (VRam) per elaborare e visualizzare queste texture. Più **set di texture** (o Porzione UV) contiene un progetto, maggiore sarà la quantità di memoria necessaria per la finestra della vista. Se la finestra della vista occupa troppa memoria nella GPU, il motore principale non dispone di spazio sufficiente per il calcolo della texture e dovrà svuotare la texture nella memoria di sistema (Ram). Ciò si tradurrà in prestazioni mediocri e calcoli lenti.

L&#39;obiettivo del SVT è quello di calcolare quanto può utilizzare il viewport sulla memoria GPU, lasciando il maggior spazio possibile al motore principale per effettuare i calcoli. Il vantaggio del sistema è che sblocca anche la possibilità di caricare progetti molto più grandi in Substance 3D Painter pur continuando a funzionare normalmente.

## Come funziona la Texture sparsa?

Le texture virtuali sparse sono un tipo di texture non completa. Ciò significa che l’applicazione carica solo parti di texture in memoria. Viene caricato solo ciò che è necessario e il resto viene inserito nella memoria di sistema o sul disco (cache). Se necessario, le texture vengono recuperate dalla cache e reinserite nella finestra della vista. Per velocizzare i trasferimenti, il sistema utilizza **mipmap** e passa rapidamente da una risoluzione all&#39;altra della texture. Per questo motivo, se si passa rapidamente alla finestra della vista, all&#39;inizio si possono verificare texture sfocate, che aumentano di qualità dopo pochi secondi.

Per ulteriori informazioni tecniche, vedere: [Texture virtuali sparse](https://silverspaceship.com/src/svt/) .

## Posizione cache

![](../assets/settings-temp.png)

Quando la memoria di sistema (Ram) non è sufficiente per memorizzare la cache SVT, Substance 3D Painter passa al disco rigido del computer per memorizzare la cache.\
Per impostazione predefinita, la posizione di questa cache si trova nella cartella dei file temporanei del sistema operativo. È possibile modificare questa posizione accedendo alle impostazioni principali dell&#39;applicazione, vedere [Preferenze generali](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/general-71008262.html) .

## Compatibilità con Shader

Per sfruttare appieno la SVT, gli Ombreggiatori devono richiedere e leggere texture dal sistema Sparse. Pertanto le funzioni precedenti basate sulle **coordinate di texture vec2** e **campionatori** sono state dichiarate obsolete. Vengono ora fornite le funzioni di supporto per utilizzare le texture sparse.

Per aggiornare gli shader:

* Per **Substance 3D Painter shader predefinito**: seguire la procedura dettagliata dalla pagina [Aggiornamento di uno shader](../interface/shader-settings/updating-a-shader.md).
* Per **shader personalizzato**: esaminare i messaggi di errore nel registro e nella pagina [API shader](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/custom-shader-api-89686018.html).

>[!WARNING]
>
> I progetti precedenti possono mostrare lampi bianchi se i loro shader non sono aggiornati. Per ulteriori informazioni, consulta questa pagina: [Applicare la trama al bianco quando si sposta la fotocamera](../technical-support/technical-issues/rendering-issues/mesh-flash-to-white-when-moving-camera.md).
