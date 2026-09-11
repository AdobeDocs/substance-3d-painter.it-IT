---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/stability-issues/crash-while-baking.html"
breadcrumb-title: ''
description: Scopri come correggere gli arresti anomali di Substance 3D Painter durante le operazioni di esegue i baking per flussi di lavoro di esegue i baking texture affidabili.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Stability Issues > Crash while baking
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arresto anomalo durante la esegue i baking
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---


# Arresto anomalo durante la esegue i baking

Substance 3D Painter potrebbe subire arresti anomali durante la esegue i baking in alcune configurazioni. Questa pagina contiene un elenco di problemi noti e come ridurli.

## Arresto anomalo con anteprima Eseguita i baking

Per impostazione predefinita, Substance 3D Painter visualizza nella finestra della vista lo stato di eseguo i baking di una texture. Su alcuni computer questa funzione potrebbe causare instabilità.

Per disattivarlo:

1. Utilizza **Modifica > Impostazioni** per aprire le impostazioni principali
1. In **Generale** viene eseguito lo scorrimento verso il basso fino alla sezione denominata **Opzioni di Esegue i baking**.
1. Deseleziona o disabilita l&#39;opzione **Abilita processo di esegue i baking dell&#39;anteprima dal vivo**.

## Arresto anomalo con Raytracing GPU

Su alcune GPU con driver instabili, la procedura di esegue i baking può causare arresti anomali a causa della funzione Raytracing GPU.

Per disattivarlo:

1. Utilizza **Modifica > Impostazioni** per aprire le impostazioni principali
1. In **Generale** viene eseguito lo scorrimento verso il basso fino alla sezione denominata **Opzioni di Esegue i baking**.
1. Deseleziona o disabilita l&#39;opzione **Abilita Raytracing GPU**.

## Arresto anomalo con CPU Ryzen

L&#39;applicazione può subire un arresto anomalo durante il processo di esegue i baking su alcune configurazioni di computer in esecuzione con una CPU Ryzen. Un aggiornamento del BIOS in genere risolve il problema.

Questo problema è correlato ai calcoli multithread. Molti costruttori di schede madri hanno rilasciato nuovi aggiornamenti del BIOS per risolvere questo problema, pertanto si consiglia di applicare l&#39;aggiornamento. Per ulteriori informazioni, fare riferimento al manuale della scheda madre e al sito Web del costruttore.

## File assbin non compatibili

Per impostazione predefinita, durante la esegue i baking le trame con elevato poli vengono pre-elaborate in file **\*.assbin** per velocizzare il rebaking in un secondo momento. In alcuni rari casi, questi file possono causare l’arresto anomalo dell’applicazione se sono stati generati con una versione diversa. La semplice eliminazione dovrebbe risolvere il problema, in quanto verranno rigenerati.
