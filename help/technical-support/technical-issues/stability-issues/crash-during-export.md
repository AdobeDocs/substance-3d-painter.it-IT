---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/technical-support/technical-issues/stability-issues/crash-during-export.html"
breadcrumb-title: ''
description: Scoprite come correggere gli arresti anomali di Substance 3D Painter durante le operazioni di esportazione per flussi di lavoro di esportazione affidabili delle texture.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Stability Issues > Crash during export
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arresto anomalo durante l’esportazione
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 0%

---


# Arresto anomalo durante l’esportazione

Alcuni casi specifici possono causare arresti anomali di Substance 3D Painter durante l’esportazione, specialmente ad altissima risoluzione (come 4K o 8K). Di seguito è riportato un elenco delle fonti più comuni di questo problema.

## TDR (rilevamento e ripristino timeout)

Il rilevamento e ripristino del timeout (TDR) è un meccanismo di sicurezza di Microsoft Windows che impedisce alla GPU di bloccare il sistema con un calcolo infinito. Questo meccanismo è purtroppo troppo restrittivo per impostazione predefinita per Substance 3D Painter.

Per ulteriori informazioni, consulta: [Arresto anomalo dei driver GPU con calcoli lunghi (arresto anomalo TDR)](https://helpx.adobe.com/substance-3d/unlisted/documentation/spdoc/gpu-drivers-crash-with-long-computations-128745489.html).

## Memoria virtuale insufficiente

L’esportazione può richiedere una grande quantità di RAM (memoria del computer), nel qual caso il sistema tenterà di eseguire il fallback sulla memoria virtuale se la RAM del sistema è esaurita. La memoria virtuale è in genere una memoria aggiuntiva memorizzata sulle unità disco rigido. Se le dimensioni della memoria virtuale sono troppo piccole, Substance 3D Painter si arresta in modo anomalo perché la memoria totale è esaurita.

Per ulteriori informazioni, vedere: [Arresto anomalo con memoria virtuale insufficiente](crash-with-low-virtual-memory.md).

## Spazio su disco insufficiente

A partire dall&#39;introduzione del Substance 3D Painter Sparse Virtual Textures (SVT) è possibile eseguire lo streaming sul disco di alcune cache per bilanciare le prestazioni. Se lo spazio disponibile sul disco non è sufficiente, potrebbe verificarsi un arresto anomalo a causa dell&#39;impossibilità dell&#39;applicazione di trasferire e scrivere la cache.

Il percorso della cache può essere spostato dalla cartella dei file temporanei di sistema predefinita. Per ulteriori informazioni, vedere: [Texture virtuali sparse](../../../features/sparse-virtual-textures.md).

## Frequenza GPU con overclock

Le GPU con overclock possono spesso essere più instabili perché eseguono frequenze che non sono state inizialmente progettate dal costruttore della GPU. Potrebbe essere utile disattivare l’overclock per un certo periodo di tempo.

Per ulteriori informazioni, consulta: [Arresto anomalo quando si lavora con la GPU con overclock](../gpu-issues/crash-when-working-with-overclocked-gpu.md).
