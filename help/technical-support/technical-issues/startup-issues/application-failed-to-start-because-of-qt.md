---
breadcrumb-title: ""
description: Scoprite come correggere gli errori di avvio di Substance 3D Painter causati da problemi del framework Qt per un corretto avvio dell'applicazione.
title: Impossibile avviare l'applicazione a causa di Qt
user-guide-description: ""
user-guide-title: ""
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '130'
ht-degree: 0%
---

# Impossibile avviare l&#39;applicazione a causa di Qt

All&#39;avvio dell&#39;applicazione potrebbe essere visualizzato il seguente messaggio di errore:

&#x200B;>> 

Impossibile avviare l&#39;applicazione perché non è stato possibile inizializzare alcun plug-in della piattaforma Qt. La reinstallazione dell&#39;applicazione potrebbe risolvere il problema.

I plug-in delle piattaforme disponibili sono: minimal, fuori schermo, webgl, windows.

Questo errore può essere causato da un&#39;altra variabile di ambiente definita dal software in conflitto con l&#39;applicazione.

Assicurati di rimuovere le seguenti variabili dall&#39;ambiente corrente prima di avviare l&#39;applicazione:

```
QT_PLUGIN_PATH 

QML2_IMPORT_PATH
```


>[!NOTE]
>
> Queste variabili possono essere ereditate anche da un contesto Python, ad esempio con **pyinstaller**. Assicurati di rimuoverli dal contesto in cui viene avviata l&#39;applicazione.
