---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/technical-support/technical-issues/gpu-issues/gpu-drivers-crash-with-long-computations-tdr-crash.html"
breadcrumb-title: ''
description: Scoprite come correggere gli arresti anomali del driver GPU durante i calcoli lunghi in Substance 3D Painter per evitare errori di timeout TDR.
helpx_creative_field: ""
helpx_description: Painter > Technical support > Technical Issues > GPU Issues > GPU drivers crash with long computations (TDR crash)
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arresto anomalo dei driver GPU con calcoli lunghi (arresto anomalo TDR)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '859'
ht-degree: 0%

---


# Arresto anomalo dei driver GPU con calcoli lunghi (arresto anomalo TDR)

![Avviso TDR in Substance 3D Painter](../../../assets/tdr-window-v2.png "Avviso TDR in Substance 3D Painter"){zoomable="yes"}

In Windows, questa finestra viene visualizzata se Substance 3D Painter rileva che il valore TDR corrente è inferiore a un limite specifico (10 secondi).

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

## Perché il driver GPU si arresta in modo anomalo?

</td>
<td style="border: 0;" valign="top">

### Come modificare i valori di TDR

</td>
<td style="border: 0;" valign="top">

### Ripristina valori predefiniti TDR

</td>
</tr>
</table>

## Perché il driver GPU si arresta in modo anomalo?

Per evitare che il rendering o il calcolo della GPU possano **bloccare il sistema**, il sistema operativo Windows **annulla il driver della GPU** ogni volta che il rendering richiede più di qualche secondo. Quando il driver viene terminato, l&#39;applicazione che lo utilizza si arresto anomalo automaticamente. Non è possibile sapere quanto tempo può durare un’operazione di rendering o un calcolo (dipende dalla GPU, dai driver, dal sistema operativo, dalle dimensioni della trama, dalla dimensione della texture, ecc.), pertanto non è possibile stabilire un limite alla quantità di dati che il computer deve elaborare ed evitare l’arresto anomalo dal livello dell’applicazione.

In Windows è presente una **chiave** chiave **del Registro di sistema** che specifica il tempo di attesa del sistema operativo prima di uccidere il driver della GPU. L’applicazione non è autorizzata a modificare direttamente questa impostazione; questa procedura deve essere eseguita manualmente (vedi di seguito).

Per ulteriori informazioni, consultare la documentazione ufficiale: <https://docs.microsoft.com/en-us/windows-hardware/drivers/display/tdr-registry-keys>.

### Elenco di chiavi da modificare

Per regolare il TDR, aumenta semplicemente il ritardo: modifica **TdrDelay** e **TdrDdiDelay** con un valore più alto (ad esempio, 60 secondi).

![Chiavi TDR nell&#39;Editor del Registro di sistema di Windows](../../../assets/registry-example.png "Chiavi TDR nell&#39;Editor del Registro di sistema di Windows"){zoomable="yes"}

>[!NOTE]
>
> Tieni presente che questi tasti possono essere ripristinati al loro valore predefinito dagli aggiornamenti di Windows o dei driver GPU.

## Come modificare i valori di TDR

Seguire questa procedura per modificare il valore TDR.

***Si noti che dovranno essere create/modificate due chiavi diverse.***

>[!WARNING]
>
> La modifica del Registro di sistema può comportare conseguenze gravi e impreviste che possono impedire l&#39;avvio del sistema e, in caso di dubbi su come modificarlo, potrebbe essere necessario reinstallare l&#39;intero sistema operativo. Le chiavi di registro citate in questa pagina non dovrebbero tuttavia creare questo tipo di problemi.
> 
> Adobe non si assume alcuna responsabilità per eventuali danni causati al sistema modificando il registro di sistema.

### 1 - Aprire la finestra Esegui

Fare clic su **Inizio**, quindi su **Esegui** (oppure premere il tasto **Windows** e **R**). Verrà aperta la finestra **Esegui**.

![Finestra di dialogo Esegui di Windows](../../../assets/run-window.png "Finestra di dialogo Esegui di Windows"){zoomable="yes"}

### 2 - Avvia l’editor del Registro di sistema

Digita **regedit** nel campo di testo e premi **OK**.

![&#39;regedit&#39; nella finestra di dialogo Esegui di Windows](../../../assets/run-regedit-2.png "&#39;regedit&#39; nella finestra di dialogo Esegui di Windows"){zoomable="yes"}

### 3 - Accedere alla chiave del registro di sistema GraphicsDrivers

Verrà aperta la finestra del Registro di sistema.\
Nel riquadro a sinistra, passare nella struttura alla chiave **GraphicsDrivers** accedendo a:

```
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers
```


Assicurati di **rimanere** &quot;GraphicsDrivers&quot; e **di non fare clic** sul Registro di sistema **sulle chiavi seguenti** prima di procedere con i passaggi successivi.

+++&#39;GraphicsDrivers&#39; nella struttura del Registro di sistema di Windows
![&#39;GraphicsDrivers&#39; nella struttura del Registro di sistema di Windows](../../../assets/reg-left-pane.png "&#39;GraphicsDrivers&#39; nella struttura del Registro di sistema di Windows"){zoomable="yes"}



+++

### 4 - Aggiungere o modificare il valore TdrDelay

>[!NOTE]
>
> Se il valore <b>TdrDelay</b> di <b>non esiste ancora</b>, fare clic con il pulsante destro del mouse nel riquadro a destra e scegliere <b>Nuovo > Valore DWORD (32 bit)</b>. Assegnale il nome &quot;<b>TdrDelay</b>&quot;. Le maiuscole e le minuscole sono importanti, assicurati di seguirle (e controlla che non ci siano altri caratteri, ad esempio uno spazio finale).
> 
> ![](../../../assets/create-value.png)

Nel **riquadro destro**, fare doppio clic sul valore **TdrDelay**. Cambia l&#39;impostazione **Base** in **Decimal**. Impostate il valore su un valore diverso da quello predefinito **2** (consigliamo **60**).

Questo valore indica in secondi il tempo di attesa del sistema operativo prima di considerare che la GPU non risponde durante un calcolo.

Valore DWORD &#39;TdrDelay&#39; di ![&#x200B; nell&#39;editor del Registro di sistema di Windows](../../../assets/tdrdelay-edit.png " Valore DWORD &#39;TdrDelay&#39; nell&#39;editor del Registro di sistema di Windows"){zoomable="yes"}

### 5 - Aggiungere o modificare il valore TdrDdiDelay

>[!NOTE]
>
> Se il valore <b>TdrDdiDelay</b> di <b>TdrDdiDelay</b>, fare clic con il pulsante destro del mouse nel riquadro a destra e scegliere <b>Nuovo > Valore DWORD (32 bit)</b>. denominalo &quot; <b>TdrDdiDelay</b> &quot;. Se è importante, ricordati di seguirlo (e controlla che non ci siano altri caratteri, come gli spazi).
> 
> ![](../../../assets/create-value.png)

Nel **riquadro destro** , fare doppio clic sul valore **TdrDdiDelay** . Cambia l&#39;impostazione **Base** in **Decimal**. Impostate il valore su un valore diverso da quello predefinito **5** (consigliamo **60** ).

Questo valore indica in secondi il tempo di attesa del sistema operativo prima di considerare che un software ha impiegato troppo tempo per lasciare i driver della GPU.

**Esadecimale** è il valore predefinito. È sufficiente passare a **decimale** per visualizzare il valore corretto. **3C** (Esadecimale) equivale a **60** (Decimale).

### 6 - Fine e riavvio

Il riquadro destro dovrebbe ora essere simile al seguente:

![Chiavi TDR nell&#39;Editor del Registro di sistema di Windows - Chiavi TDR finali](../../../assets/registry-example.png "nell&#39;Editor del Registro di sistema di Windows - Finali"){zoomable="yes"}

**Chiudere** l&#39;editor del Registro di sistema. **Riavviare** il computer utilizzando **Start**, quindi **Riavvia**.

TdrValue viene considerato solo all&#39;avvio del computer, pertanto per forzare un aggiornamento è necessario riavviare il computer.

Se l’applicazione continua ad essere in arresto anomalo durante un calcolo lungo, prova ad esempio ad aumentare il ritardo (in secondi) da 60 a 120.

## Ripristina valori predefiniti TDR

Esistono due modi per ripristinare i valori predefiniti del TDR:

* Impostate **TdrDelay** su **2s** e **TdrDdiDelay** su **5s**, seguendo i passaggi descritti in precedenza.
* Oppure **Rimuovi** le chiavi **TdrDelay** e **TdrDdiDelay** dalla voce del Registro di sistema.
