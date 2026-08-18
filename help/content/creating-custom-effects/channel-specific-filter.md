---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/content/creating-custom-effects/channel-specific-filter.html"
breadcrumb-title: ''
description: Scoprite come creare effetti di filtro specifici per i canali in modo che Substance 3D Painter elabori i singoli canali delle texture.
helpx_creative_field: ""
helpx_description: Painter > Content > Creating custom effects > Channel specific filter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Filtro specifico per il canale
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 0%

---


# Filtro specifico per il canale

Un effetto può essere specifico di un determinato canale. In tal caso, se si desidera modificare un canale specifico, è necessario creare un input E un output che identifichi questo canale. Come regola generale, la struttura di input/output deve sempre rispettare una regola 1:1. Se desideri inserire un canale specifico, devi generare lo stesso canale.

Esempio di un filtro che influisce solo sul canale **basecolor**:

![](../../assets/specific-filter-basecolor.png)

>[!NOTE]
>
> Non è possibile combinare una configurazione generica (nodi di input/output) e canali specifici (colore base/colore base).

## Gestione dei componenti di Alpha

I canali memorizzati come RGBA supportano il formato alfa (basecolor, ad esempio). Per questi canali, l&#39;ingresso/uscita alfa può essere memorizzato direttamente nell&#39;uscita colore della Substance. Tuttavia, il motore di Substance non supporta l’Alpha per le immagini in scala di grigio: deve essere gestito utilizzando una mappa secondaria. Per ottenere la componente alfa di un canale specifico in un grafico della sostanza, create un input in scala di grigio denominato &#39;**nomecanale\_Alpha**&#39;, ad esempio: **colore di base\_Alpha**, **rugosità\_Alpha** e così via.\
Per generare l&#39;output di questo componente alfa, creare un nodo di output con la stessa convenzione di nome.

>[!NOTE]
>
> L&#39;output &quot;**\_Alpha**&quot; specifico per canale non funziona con **materiali** normali. Per nascondere un canale con una maschera, è necessario creare un output specifico con la seguente convenzione di denominazione:
> 
> * Identificatore: **canali\_Alpha**
> * Sintassi: **canali\_Alpha**

## Elenco di utilizzi e identificatori di input/output

>[!NOTE]
>
> È possibile utilizzare **l&#39;utilizzo** o **l&#39;identificatore** in un nodo di input (l&#39;utilizzo ha la priorità).

| Nome canale | Utilizzo | Alpha identificatore/identificatore |
| --- | --- | --- |
| *Occlusione ambiente* | **occlusioneAmbientale** | **ambientOcclusion/ambientOcclusion\_Alpha** |
| *Angolo Anisotropia* | **anisotropiangolo** | **anisotropiaAngolo/anisotropiaAngolo\_Alpha** |
| *Livello Anisotropia* | **anisotropilivello** | **anisotropiaLivello/anisotropiaLivello\_Alpha** |
| *Colore di base* | **colore base** | **baseColor / baseColor\_Alpha** |
| *Maschera di fusione* | **maschera di fusione** | **maschera di fusione/maschera di fusione\_Alpha** |
| *Diffusione* | **diffusione** | **diffusione/diffusione\_Alpha** |
| *Spostamento* | **spostamento** | **spostamento/spostamento\_Alpha** |
| *Emissivo* | **emissivo** | **emissivo/emissivo\_Alpha** |
| *Lucentezza* | **lucidità** | **lucidità/lucidità\_Alpha** |
| *Height* | **height** | **height/height\_Alpha** |
| *IOR* | **ior** | **ior / ior\_Alpha** |
| *Metallico* | **metallico** | **metallizzato/metallizzato\_Alpha** |
| *Normale* | **normale** | **normale/normale\_Alpha** |
| *Opacità* | **opacità** | **opacità/opacità\_Alpha** |
| *Riflessione* | **reflection** | **riflesso/riflessione\_Alpha** |
| *Rugosità* | **rugosità** | **rugosità/rugosità\_Alpha** |
| *Dispersione* | **dispersione** | **dispersione/dispersione\_Alpha** |
| *Specular* | **specular** | **specular/specular\_Alpha** |
| *Specular level* | **specularlevel** | **specularLevel/specularLevel\_Alpha** |
| *Trasmissivo* | **trasmissivo** | **trasmissivo/trasmissivo\_Alpha** |
| *Utente 0* | **utente0** | **utente0 / utente0\_Alpha** |
| *Utente 1* | **utente1** | **utente1 / utente1\_Alpha** |
| *Utente 2* | **utente2** | **utente2 / utente2\_Alpha** |
| *Utente 3* | **utente3** | **utente3 / utente3\_Alpha** |
| *Utente 4* | **utente4** | **utente4 / utente4\_Alpha** |
| *Utente 5* | **utente5** | **utente5 / utente5\_Alpha** |
| *Utente 6* | **utente6** | **utente6 / utente6\_Alpha** |
| *Utente 7* | **utente7** | **utente7 / utente7\_Alpha** |

## Esempi

![](../../assets/single-channel.png){width="650px"}

In questo esempio il canale alfa del colore di base viene estratto tramite un nodo in scala di grigio per sovrascrivere il canale **Rugosità**.

![](../../assets/mix-channel.png){width="650px"}

In questo esempio il canale **Rugosità** viene moltiplicato sul **Colore di base**.
