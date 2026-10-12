---
breadcrumb-title: ""
description: Scoprite come correggere le anteprime di risorse vuote e ripiani in Substance 3D Painter per ripristinare la funzionalità di visualizzazione delle miniature.
title: Le anteprime delle risorse (o degli scaffali) sono vuote
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 0%
---

# Le anteprime delle risorse (o degli scaffali) sono vuote

Questo problema può essere causato da altro software, vedere: [Conflitti software](../startup-issues/software-conflicts.md).

Se non è possibile determinare quale aggiornamento/disinstallazione del software, cercare una variabile di ambiente denominata &quot;QT\_PLUGIN\_PATH&quot; e rimuoverla.

**In Windows:**

1. Apri **Sistema** nel Pannello di controllo.
1. Nella scheda Avanzate fare clic su **Variabili di ambiente**
1. Cerca la variabile denominata **&quot;QT\_PLUGIN\_PATH&quot;**
1. **Rimuovi**
1. **Riavvia** il computer
