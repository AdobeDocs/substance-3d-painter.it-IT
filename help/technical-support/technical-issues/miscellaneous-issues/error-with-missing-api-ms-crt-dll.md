---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/miscellaneous-issues/error-with-missing-api-ms-crt-dll.html"
breadcrumb-title: ''
description: Scoprite come correggere gli errori DLL api-ms-crt mancanti in Substance 3D Painter per il corretto supporto della libreria di runtime di Windows.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > Miscellaneous Issues > Error with missing api-ms-crt dll
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Errore con api-ms-crt dll mancante
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 0%

---


# Errore con api-ms-crt dll mancante

Impossibile avviare Substance 3D Painter. **api-ms-win-crt-runtime-l1-1-0.dll** non è presente nel computer.\
Questo problema si verifica probabilmente perché l&#39;aggiornamento KB2999226 che fa parte di **Visual C++ Redistributable** per Visual Studio 2015 non è stato installato.

## Come risolvere il problema?

### 1 - Verificare che Windows sia aggiornato

1. Aprire il menu Start
1. Seleziona Pannello di controllo
1. Fai clic su **Windows Update**
1. Fai clic su **Ricerca aggiornamenti**
1. **Installa** tutti gli aggiornamenti disponibili.
1. Dopo aver installato gli aggiornamenti, **riavvia** il computer.

Dopo il riavvio, ripeti i passaggi precedenti fino a quando non saranno più disponibili aggiornamenti.

### 2 - Installazione di Visual C++ Redistributable

1. Scarica Visual C++ Redistributable:
   1. Per [Windows a 64 bit](http://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x64.exe)
   1. Per [Windows a 32 bit](http://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x86.exe)
1. Esegui **vcredist\_x64.exe** (64 bit) o **vcredist\_x86.exe** (32 bit)
1. Seleziona Disinstalla e segui la procedura
1. Esegui nuovamente l&#39;eseguibile
1. Seleziona Installa
