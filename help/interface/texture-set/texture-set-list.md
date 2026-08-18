---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/interface/texture-set/texture-set-list.html"
breadcrumb-title: ''
description: Scoprite come utilizzare l’elenco di set di texture in Substance 3D Painter per gestire e organizzare più set di texture nel progetto.
helpx_creative_field: ""
helpx_description: Painter > Interface > Texture Set > Texture Set list
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Elenco Set di texture
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '609'
ht-degree: 0%

---


# Elenco Set di texture

![](../../assets/texture-set-list.png)

Nella finestra **Elenco set di texture** vengono visualizzati tutti gli ID materiale del modello 3D corrente in un progetto. Consente di cambiare e visualizzare la pila di livelli associata a ciascun materiale sul modello, nonché le relative impostazioni dedicate.

L&#39;obiettivo principale della finestra Elenco set di texture è consentire il passaggio da un materiale all&#39;altro per accedere alla pila di livelli associata a ciascun materiale.\
Nel caso del flusso di lavoro [Livellamento dei materiali](../../features/dynamic-material-layering.md), i **sottostack** vengono visualizzati **sotto** il nome del set di texture.

>[!WARNING]
>
> È possibile modificare/colorare un solo set di texture alla volta.

## Stato set texture

Gli insiemi di texture possono avere più stati:

![](../../assets/txtset-status.png)

* **Selezionato**: il set di texture corrente è attualmente in fase di modifica. Se si seleziona un set di texture, vengono aggiornati di conseguenza lo [stack di livelli](../layer-stack/layer-stack.md) e la finestra [Impostazioni shader](../shader-settings/shader-settings.md).
* **Visibile/Nascosto**: per ulteriori dettagli, consulta la sezione sulla visibilità riportata di seguito.
* **Disabilitato**: i set di texture e lo stack di livelli associato non possono essere collegati a un materiale nella trama. Per ulteriori informazioni, vedere [Riassegnazione del set di texture](texture-set-reassignment.md).

## Visibilità

![](../../assets/texturesetlist.png)

La visualizzazione di un set di texture può essere gestita dalle icone dedicate:

| *Icona* | *Azione* | *Descrizione* |
| --- | --- | --- |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r1-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/txtsetlist-icon-menu.png"/></div> | Apri menu | Apri un nuovo menu con le seguenti azioni:<ul data-preserve-html="true"><li data-preserve-html="true"><strong>Mostra tutto</strong>: verranno visualizzati tutti i set di texture nella finestra della vista.</li><li data-preserve-html="true"><strong>Nascondi tutto</strong>: nasconderà tutti i set di texture nella finestra della vista.</li><li data-preserve-html="true"><strong>Inverti visualizzazione</strong>: gli insiemi di texture visibili diventeranno nascosti, quelli nascosti diventeranno visibili.</li></ul> |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r2-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/txtsetlist-icon-isolate.png"/></div> | Modalità di messa a fuoco | Isolate il set di texture attivo e nascondete tutti gli altri elementi mentre questa modalità è attiva. Fare di nuovo clic su questo pulsante per uscire dalla modalità. |
| <div><img class="" data-preserve-html="true" id="root_content_flex_items_position_position-par_dx_table_row-r3-column-c0_dynamic_grid_items_grid-cell_position-par_image" src="../../assets/txtsetlist-icon-visible.png"/></div> | Visibilità | Fate clic su questo pulsante accanto a un set di texture per nascondere o rendere visibile un set di texture nella finestra della vista. |

>[!NOTE]
>
> Per impostazione predefinita, quando **si disegna** viene visualizzato solo il set di texture selezionato. È possibile modificare questo comportamento in [Preferenze](../settings/settings.md) deselezionando &quot;**Mostra solo il materiale selezionato durante il disegno**&quot;.\
> Nota: nascondere altri set di texture durante il disegno **migliora le prestazioni**.

## Menu contestuale

![](../../assets/txtset-list-contextualmenu.png)

Facendo clic con il pulsante destro del mouse sul nome di un set di texture, viene aperto un menu contestuale con le seguenti azioni:

* **Mostra/Nascondi set di texture**: attiva/disattiva la visibilità del set di texture (come descritto nella sezione precedente)
* **Modifica nome**: consente di rinominare un set di texture. Questo nome verrà utilizzato anche durante il processo di esportazione delle texture. È inoltre possibile rinominare un set di texture facendo doppio clic sul relativo nome.
* **Reimposta il nome su \*nome originale\***: ripristina il nome del set di texture originale dal materiale mesh se è stato modificato.
* **Modifica descrizione**: consente di aggiungere/modificare la descrizione associata a un set di texture.

## Gestione shader

Per gestire l’assegnazione dello shader, potete usare il pulsante a destra del nome di ogni set di texture.\
Per impostazione predefinita, ogni set di texture condivide la stessa istanza dello shader. Tuttavia, può essere comodo avere a volte uno shader diverso solo per una parte specifica della trama. A tale scopo, fare clic sul pulsante e scegliere &quot;**Nuova istanza dello shader**&quot;. Da qui, nella finestra [Impostazioni shader](../shader-settings/shader-settings.md) è possibile modificare lo shader e i relativi parametri senza influire su altri set di texture.

![](../../assets/capture-d-e-cran-2018-07-12-a-15-45-32.png){width="500px"}

## Impostazioni

Il pulsante Impostazioni apre un nuovo menu che espone più azioni:

* **Nascondi descrizioni vuote** (impostazione predefinita): nasconde i campi descrizione se vuoti
* **Nascondi tutte le descrizioni**: nasconde i campi delle descrizioni anche se non vuoti
* **Mostra tutte le descrizioni**: mostra i campi delle descrizioni anche se vuoti
* **Importa parametri shader**: consente di importare un file json per configurare i parametri shader dei set di texture
* **Riassegna set di texture**: per ulteriori informazioni, vedere [Riassegnazione set di texture](texture-set-reassignment.md).
