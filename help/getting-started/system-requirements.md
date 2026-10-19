---
breadcrumb-title: ""
description: Verifica i requisiti di sistema di Substance 3D Painter per verificare che il computer soddisfi le specifiche hardware e software.
title: Requisiti di sistema
user-guide-description: ""
user-guide-title: ""
source-git-commit: fbfe7e52b226b5a92f5b46ebbf82728f0ff9e3c5
workflow-type: tm+mt
source-wordcount: '814'
ht-degree: 1%
---

# Sistemi supportati

Di seguito è riportato un elenco di hardware e sistemi supportati dall&#39;applicazione:

## Windows

|  | Minimo | Consigliato | Ottimale |
| --- | --- | --- | --- |
| **SO** | Windows 11 64 bit versione 23H2 | Windows 11 64 bit versione 24H1 | Windows 11 64 bit versione 24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 Ada Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8 GB | 16 GB | 24 GB |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **Archiviazione** | SSD con 30 GB di spazio disponibile | SSD con 50 GB di spazio disponibile | SSD con 70 GB di spazio disponibile |

### macOS

|  | Minimo | Consigliato | Ottimale |
| --- | --- | --- | --- |
| **SO** | Sequoia di macOS 15 | macOS 27 Golden Gate | macOS 27 Golden Gate |
| **CPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **GPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **Archiviazione** | SSD con 30 GB di spazio disponibile | SSD con 50 GB di spazio disponibile | SSD con 70 GB di spazio disponibile |

>[!WARNING]
>
> Per le pipeline create tenendo presente la [piattaforma di riferimento VFX](https://vfxplatform.com/), è comunque possibile installare Substance 3D Painter su macOS 14 Sonoma. Tuttavia, Painter non viene più testato su versioni del sistema operativo che non soddisfano i requisiti minimi di sistema, pertanto la stabilità non è garantita.

### Linux

| Enterprise | Vapore |
| --- | --- |
| RHEL 8<br>RHEL 9 | Ubuntu 22,04 |

## Raccomandazioni generali

Per ottenere buone prestazioni durante l’utilizzo del flusso di lavoro Porzione UV consigliamo di utilizzare:

* 32 GB di RAM
* GPU con 8 GB di VRAM
* SSD per memorizzare sia la cache del progetto che quella dell&#39;applicazione.

Varie:

* Molte app Substance dipendono da OpenSSL 1.1.1 per la compatibilità con RHEL8/9. Per i sistemi con versioni OpenSSL più recenti, il cliente dovrà fornirlo manualmente
* Per lavorare in condizioni ottimali, consigliamo un monitor con una risoluzione verticale superiore a 1000 pixel e superiore a 1280 pixel.
* L&#39;esportazione a **8K** (8192\*8192 pixel) richiede una GPU con **più di** 2 GB di VRam.
* Solo le versioni 2019.x e successive sono state autenticate per essere eseguite su MacOS 10.15 (Catalina).
* Per utilizzare il software tramite RDP (Desktop remoto), vedere la [pagina della documentazione](../pipeline-and-integration/configuration/remote-desktop.md) dedicata.
* L&#39;Arresto anomalo sulla CPU Ryzen durante la esegue i baking può essere risolto aggiornando il BIOS.

## Configurazione non supportata

**Windows**

* Le macchine virtuali non sono supportate.
* Windows Server non è supportato.

**Mac**

* Sono supportate solo le configurazioni Apple ufficiali.
* Le eGPU non sono attualmente supportate e potrebbero presentare problemi di stabilità.

**Linux**

* I driver Mesa su Linux non sono supportati.

**Qualsiasi piattaforma**

* Le GPU integrate non sono supportate su CPU x86-64 (Intel, AMD).

## Versioni minime del driver GPU

Di seguito è riportato un elenco delle versioni minime dei driver della GPU necessarie per l&#39;esecuzione dell&#39;applicazione senza problemi. Questo elenco è soggetto a modifiche man mano che vengono rilasciate nuove versioni.

Per scaricare nuovi driver, consultate: [La GPU contiene driver obsoleti](../technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers.md).

| SO | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **Windows** | GeForce 442.50 Quadro 442.50 | Radeon 19.7.1 Radeon Pro/FirePro 18.Q4 | 15.33 |
| **Linux** | 535.171.04 o versioni successive | Radeon 22.40.6 | Non supportato |

>[!NOTE]
>
> In **Mac OS** il driver della GPU è fornito dal sistema operativo stesso. Esegui l’aggiornamento alla versione più recente del sistema operativo per accedere al driver più recente.

### Problemi di compatibilità dei driver

Per un elenco dettagliato dei problemi relativi ai driver GPU per costruttore, consultare la [pagina dedicata alla documentazione](../technical-support/technical-issues/gpu-issues/gpu-drivers-compatibility.md).

## Raytracing GPU per eseguire i baking

Per attivare il Raytracing GPU tramite Optix o DXR, è necessario installare i driver minimi sopra consigliati.

**DXR** richiede anche la seguente configurazione minima:

* **Windows 10** versione 1809; per ulteriori informazioni, vedere [questa pagina](https://experienceleague.adobe.com/it/docs/substance-3d/bakers/features/gpu-raytracing)
* **GPU con architettura Pascal** (Nvidia GeForce 10XX)

>[!TIP]
>
> Raytracing GPU funziona in modo ottimale su hardware di raytracing dedicato come le GPU NVIDIA GeForce RTX o NVIDIA Quadro RTX.

## Tablet grafici supportati

Di seguito è riportato un elenco di tavolette grafiche compatibili che sono state testate con la versione di Substance 3D Painter **7.4.2**:

+++Wacom

**Modelli:** Intuos Pro (dimensioni M), Intuos (dimensioni S)

| SO | Versione driver |
| --- | --- |
| Windows | 6.3.45-1 |
| macOS | 6.3.45-3 |

+++

+++XPen

**Modello:** Deco 01

| SO | Versione driver |
| --- | --- |
| Windows | XP-PENWin_3.2.2.211027 |
| macOS | XP-PENMac_3.2.3_211203 |
| Linux | XP-PEN-pentablet-3.2.1.211019-1 |

+++

+++Huion

**Modello:** Q11K

| SO | Versione driver |
| --- | --- |
| Windows | XP-PENWin_3.2.2.211027 |
| macOS | XP-PENMac_3.2.3_211203 |

+++

+++Xencelabs

**Modello:** Compressa A Penna Media

| SO | Versione driver |
| --- | --- |
| Windows | XencelabsWin_1.2.1-14 |
| macOS | XencelabsMac_1.2.1-18 |
| Linux | XencelabsLinux_1.1.0-2 |

+++

## Modelli supportati di SpaceMouse 3Dconnection

Di seguito è riportato un elenco delle versioni dei driver compatibili per [3Dconnection Space Mouse](https://3dconnexion.com/us/spacemouse/) che sono state testate con Substance 3D Painter versione **8.1.**

Le versioni dei driver sono valide per i modelli **Compact**, **Pro** e **Enterprise**.

| SO | Versione driver |
| --- | --- |
| Windows | 10.8.6.3431 |
| macOS | 10.7.2.3454 |

## Lingue

L&#39;interfaccia software è disponibile nelle seguenti lingue:

* Inglese (Stati Uniti)
* Tedesco
* Spagnolo
* Francese
* Italiano
* Giapponese
* Coreano
* Portoghese (Brasile)
* Cinese (semplificato)
