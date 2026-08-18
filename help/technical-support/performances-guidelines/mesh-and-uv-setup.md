---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/performances-guidelines/mesh-and-uv-setup.html"
breadcrumb-title: ''
description: Scoprite le best practice per la configurazione di trame e UV in Substance 3D Painter per ottimizzare le prestazioni e la qualità delle texture.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Performances guidelines > Mesh and UV setup
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Configurazione Trama e UV
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '432'
ht-degree: 0%

---


# Configurazione Trama e UV

Prendervi qualche minuto per preparare la trama per Painter può rendere il processo di creazione delle texture più semplice e veloce.

+++Modelli con elevato numero di poligoni
Non esiste un benchmark specifico per il conteggio multiplo che Painter è in grado di gestire, in quanto dipende in gran parte dalle specifiche della macchina, dall&#39;assegnazione del set di texture e dalle proprietà dello stack di livelli, ma meno di 10 milioni di poly devono essere gestiti correttamente se si tiene conto delle ottimizzazioni dello stack di livelli.

+++

+++Modelli con basso numero di poligoni
C&#39;è una cosa come il poly troppo basso. Questo perché il motore delle texture usa i Poligoni per sapere quale parte della trama deve essere sottoposta a rendering per calcolare i tratti del pennello. Le trame con un numero di poligoni molto basso possono essere riprodotte completamente anche con tratti di pennello piccoli che possono sovraccaricare inutilmente la GPU.

Ad esempio, se create una texture su un singolo piano quadruplo, è meglio suddividere la trama, specialmente quando si dipinge a mano con molti tratti, poiché le informazioni vengono distribuite su più vertici.

+++

+++Dividere le texture su più set di texture
È preferibile dividere trame più grandi con assegnazioni di materiale più complesse in diversi insiemi di texture. I set di texture consentono di assegnare diverse impostazioni per set di texture, come la risoluzione e le proprietà dello shader. Ad esempio, se solo una parte della trama utilizza la traslucidità o l’SSS, è preferibile assegnare un altro insieme di texture e una diversa istanza dello shader alla parte. In questo modo, non è necessario calcolare queste proprietà più complesse dove non vengono utilizzate.

+++

+++Mantieni le Isole UV vicine
Provate a mantenere vicine Isole UV vicine in uno spazio 3D. Questo vale sia per il layout UDIM che per il layout dello spazio UV classico. Se hanno condiviso tratti pennello o texture, è più facile calcolarli quando sono raggruppati nella stessa area dello spazio UV, piuttosto che se si trovano a estremità opposte.

Il motore delle texture divide una texture in blocchi più piccoli per velocizzare il calcolo. Ciò significa che ogni tratto aggiorna solo i pezzi che devono essere modificati, invece di aggiornare l’intera texture con ogni tratto. Mantenendo le Isole UV adiacenti vicine l&#39;una all&#39;altra, riduce al minimo il numero di blocchi interessati da un singolo tratto.

+++

+++Evitare troppi oggetti
Le prestazioni devono rimanere ottimali quando si importa una trama con meno di 8000 sottooggetti. Il superamento di questo limite può influire sulle prestazioni della finestra della vista e del disegno. Se viene raggiunto questo limite, si consiglia di unire gli oggetti per ridurre il sovraccarico di rendering.

+++
