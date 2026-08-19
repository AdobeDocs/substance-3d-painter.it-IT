---
helpx_url: 'https://helpx.adobe.com/it/substance-3d-painter/interface/viewport.html'
description: Scoprite come utilizzare la finestra della vista in Substance 3D Painter per visualizzare i modelli e le texture 3D durante il processo di pittura.
helpx_description: Painter > Interface > Viewport
title: Riquadro di visualizzazione
source-git-commit: 7b5f6e6c9623cb51253b6e49c8dbcbb22856418c
workflow-type: tm+mt
source-wordcount: '489'
ht-degree: 2%

---


# Riquadro di visualizzazione

![](../../assets/viewports-progress.jpg){width="600px"}

Nella finestra della vista vengono visualizzate la trama 3D e le relative texture. È anche possibile colorare sulla superficie della trama 3D.

## Panoramica

La finestra della vista è divisa in quattro parti:

* **Barra degli strumenti contestuale**: questa barra degli strumenti si trova nella parte superiore della finestra della vista e offre un collegamento a varie proprietà a seconda del contesto corrente (ad esempio, i parametri del pennello quando si disegna).
* **Vista 3D**: questa vista mostra la trama 3D da un angolo specifico, definito da una videocamera.
* **Vista 2D**: questa vista mostra lo srotolamento UV della trama 3D per il [set di texture](../texture-set/texture-set-list.md) attualmente selezionato.
* **Barra di avanzamento**: questa barra grigia/verde nella parte inferiore della finestra della vista viene visualizzata quando è in corso un calcolo, ad esempio quando il motore genera texture.

Per maggiori dettagli, consultate le pagine dedicate:

* [Vista 2D](2d-view.md)
* [Visualizzazione 3D](3d-view.md)
* [Gestione delle telecamere](camera-management.md)

Le viste 3D e 2D possono essere regolate per visualizzare informazioni aggiuntive o diverse tramite le [Impostazioni schermo](../../interface/display-settings/display-settings.md).

## Controlli di navigazione della finestra della vista

I controlli per lo spostamento nella finestra della vista sono simili sia nella vista 2D che in quella 3D.

<table>
  <tr>
    <th>Tipo di movimento</th>
    <th>Scelta rapida</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td>Rotazione/Rotazione<br></td>
    <td><strong>Alt + clic sinistro</strong></td>
    <td><ul><li>Vista 3D: orbita la videocamera attorno alla posizione del cursore.</li><li>Vista 2D: ruota lo spazio UV attorno alla posizione del cursore.</li></ul></td>
  </tr>
  <tr>
    <td>Panning</td>
    <td><strong>Alt + clic con il pulsante centrale del mouse</strong></td>
    <td>Sposta la fotocamera verso l’alto, il basso, a sinistra o a destra.</td>
  </tr>
  <tr>
    <td>Zoom/Carrello</td>
    <td><strong>Alt + clic con il pulsante destro</strong></td>
    <td>Ingrandisci avvicinandoti o allontanandoti dalla trama/UV.</td>
  </tr>
</table>

>[!NOTE]
> Nelle viste 2D e 3D, puoi agganciare ad angoli ortogonali quando orbiti/ruoti con **Alt + Maiusc + clic sinistro**.

## Modifica Del Layout

Il layout predefinito posiziona la vista 3D a sinistra e la vista 2D a destra. Nella **barra degli strumenti contestuale** sono disponibili alcuni parametri che consentono di modificare il layout:

<table>
  <tr>
    <th><em>Impostazione</em></th>
    <th><em>Descrizione</em></th>
  </tr>
  <tr>
    <td><strong>Modalità finestra di visualizzazione</strong><br>![](../../assets/viewport-viewmode.png)</td>
    <td>Queste impostazioni controllano il layout della finestra della vista:<br><ul><li><strong>3D/2D</strong> (impostazione predefinita): consente di visualizzare entrambe le viste 3D e 2D nella finestra della vista</li><li><strong>Solo 3D</strong>: ingrandisci la vista 3D e nascondi la vista 2D.</li><li><strong>Solo 2D</strong>: ingrandite la vista 2D e nascondete la vista 3D.</li><li><strong>Scambia 3D/2D</strong>: scambia l’ordine di visualizzazione delle visualizzazioni. Se la vista 3D era a sinistra, si troverà a destra dopo aver scelto questa azione.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Modalità prospettica</strong><br>![](../../assets/viewport-camera-projection.png)</td>
    <td>Queste impostazioni controllano l’aspetto della trama 3D nella vista 3D:<br><ul><li><strong>Vista prospettica</strong> (impostazione predefinita): visualizza la trama 3D come se fosse vista dall’occhio umano o da una videocamera.</li><li><strong>Vista ortogonale</strong>: visualizza la trama 3D in quanto ogni direzione misura la stessa lunghezza.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Modalità di rotazione fotocamera</strong><br>![](../../assets/viewport-camera-axis.png)</td>
    <td>Queste impostazioni determinano il numero di assi di rotazione della finestra della vista.<br><ul><li><strong>Rotazione libera</strong>: la fotocamera ruota sugli assi X, Y e Z.</li><li><strong>Rotazione vincolata</strong> (impostazione predefinita): la videocamera ruota solo sugli assi X e Y (senza rotazione).</li></ul></td>
  </tr>
  <tr>
    <td><strong>Modalità rendering</strong><br>![](../../assets/viewport-rendering.png)</td>
    <td>Passa alla <a href="../../features/iray-renderer/iray-renderer.md">modalità rendering</a>.</td>
  </tr>
</table>
