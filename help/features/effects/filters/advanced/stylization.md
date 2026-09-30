---

title: Stilizzazione
description: Scopri come utilizzare il filtro Stilizzazione di Substance 3D Painter.
source-git-commit: 644a36a1dde953c1d793821e104049ebb6ec3c19
workflow-type: tm+mt
source-wordcount: '1055'
ht-degree: 1%
---

# Stilizzazione

<table>
<tr style="border: 0;">
<td width="33.33%" style="border: 0;" valign="top">

![Icona Stilizzazione](./Resources/icon_stylization.png "Stilizzazione")

<b>Ingresso:</b> effetti/stilizzazione, stilizzazione, realistico, mano, dipinto, pennello

</td>
<td width="100.00%" style="border: 0;" valign="top">

## Descrizione

Il filtro Stilizzazione conferisce a un materiale un aspetto dipinto a mano e stilizzato.

Viene utilizzato su un livello texture per aggiungere pennellate pittoriche, variazione dello smoothness, modifica del colore ed effetti di luce eseguita i baking.

</td>
</tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| <b>Base Occlusione ambientale:</b> Colore |  |
| <b>Curvatura:</b> Colore |  |
| <b>Base normale:</b> colore |  |

<a name="parameters"></a>

## Parametri

| Nome parametro | Descrizione |
| --- | --- |
| <b>Stilizzazione:</b> | Regolate l’intensità globale del filtro. |
| <b>Tratti pennello:</b> | Regolate l’intensità complessiva dell’effetto tratto pennello. |
| <b>Smoothness:</b> | Regolate l’intensità complessiva dell’effetto smoothness. |
| <b>Colora:</b> | Regolate l’intensità complessiva dell’effetto Colora. |
| <b>Sfumatura:</b> | Regolate l’intensità complessiva dell’effetto sfumatura. |
| <b>Illuminazione Eseguita i baking:</b> | Regola l’intensità complessiva dell’effetto di luce eseguito i baking. |
| <b>Bordi e cavità:</b> | Regola l’intensità complessiva dell’effetto bordi e cavità. |

### Tratti pennello

| Nome parametro | Descrizione |
| --- | --- |
| <b>Quantità tratti:</b> | Regolate la quantità di tratti di pennello usati dal filtro. |
| <b>Modalità tratti:</b> | Selezionate il tipo di tratti di pennello usati dal filtro. |
| <b>Selezione tratti:</b> | Selezionate le forme dei tratti di pennello da proiettare quando utilizzate più tratti. |
| <b>Selezione tratti:</b> | Seleziona la forma del tratto pennello da proiettare quando utilizzi un singolo tratto. |
| <b>Scala tratti:</b> | Regolate la scala dei tratti del pennello. |
| <b>Dimensione non uniforme:</b> | Attiva/disattiva il ridimensionamento non uniforme per i tratti pennello proiettati. |
| <b>Dimensione tratti:</b> | Regola le proporzioni dei tratti di pennello proiettati. |
| <b>Scala tratti casuale:</b> | Regola la quantità di variazione casuale della scala applicata ai tratti del pennello. |
| <b>I Tratti Seguono La Superficie:</b> | Attiva/disattiva l’allineamento dei tratti del pennello all’orientamento della trama. |
| <b>Rotazione tratti:</b> | Regolate l’angolo di rotazione del tratto del pennello. |
| <b>Rotazione dei tratti casuale:</b> | Regola la quantità di rotazione casuale applicata ai tratti del pennello. |
| <b>Durezza proiezione:</b> | Regola la durezza della proiezione del timbro. |
| <b>Soglia normale:</b> | Regolate la soglia normale utilizzata per la proiezione del tratto. |

### Effetti Tratti pennello

| Nome parametro | Descrizione |
| --- | --- |
| <b>Colore personalizzato:</b> | Attiva/disattiva l’uso di un colore personale sui tratti del pennello. |
| <b>Variazione colore:</b> | Regola il grado di fusione dei tratti pennello con il colore di base. |
| <b>Opacità colore:</b> | Regola l’opacità del colore personale applicato ai tratti del pennello. |
| <b>Colore:</b> | Regolate il colore personale applicato ai tratti del pennello. |
| <b>Colore casuale:</b> | Regola la quantità di variazione casuale del colore applicata ai tratti del pennello. |
| <b>Rugosità personalizzata:</b> | Attiva/disattiva l’uso di un valore di rugosità personalizzato sui tratti del pennello. |
| <b>Variazione rugosità:</b> | Regolate la variazione di rugosità tra i tratti del pennello. |
| <b>Rugosità:</b> | Regolate il valore di rugosità dei tratti del pennello. |
| <b>Metallico personalizzato:</b> | Attiva/disattiva l’uso di un valore metallico personalizzato sui tratti del pennello. |
| <b>Variazione metallica:</b> | Regola la variazione metallica tra i tratti del pennello. |
| <b>Metallico:</b> | Regolate il valore metallico dei tratti del pennello. |
| <b>Personalizzato normale:</b> | Attivate/disattivate le opzioni aggiuntive di mappatura normale per i tratti pennello. |
| <b>Variazione normale:</b> | Regolate l’intensità dei tratti di pennello nel canale normale. |
| <b>Normale casuale:</b> | Regolate la quantità di variazione casuale della normale applicata ai tratti del pennello. |
| <b>Metodo fusione (normale):</b> | Selezionate il metodo di fusione normale usato per i tratti del pennello. |

### Uniformità

| Nome parametro | Descrizione |
| --- | --- |
| <b>Smoothness colore:</b> | Regola l’effetto di arrotondamento Kuwahara applicato al Colore di base. |
| <b>Smoothness rugosità:</b> | Regolate l’effetto di arrotondamento Kuwahara applicato alla rugosità. |
| <b>Smoothness metallico:</b> | Regolate l’effetto di arrotondamento Kuwahara applicato a Metallic. |
| <b>Smoothness Height:</b> | Regola l’effetto di arrotondamento Kuwahara applicato al Height. |
| <b>Smoothness normale:</b> | Regolate l’effetto di smussatura Kuwahara applicato a Normale. |
| <b>Smoothness Occlusione ambientale:</b> | Regola l’effetto di arrotondamento Kuwahara applicato all’Occlusione ambientale. |

### Colorazione

| Nome parametro | Descrizione |
| --- | --- |
| <b>Opacità colore:</b> | Regola l’opacità della selezione colore applicata al Colore di base. |
| <b>Colore:</b> | Selezionate il colore usato per sostituire il Colore di base. |
| <b>Variazione Grunge:</b> | Selezionate la forma del pattern utilizzata per la variazione di colore. |
| <b>Opacità Grunge:</b> | Regola la quantità di variazione del colore basata su pattern nel Colore di base. |
| <b>Colore Grunge:</b> | Regolate la tinta della variazione di colore basata su pattern in Colori di base. |
| <b>Importo di fatturazione:</b> | Regola il numero di pattern mappati nella variazione di colore. |
| <b>Scala motivo:</b> | Regola la scala dei pattern mappati nella variazione di colore. |

### Sfumatura

| Nome parametro | Descrizione |
| --- | --- |
| <b>Modalità sfumatura:</b> | Seleziona se la sfumatura utilizza uno o due colori. |
| <b>Colore:</b> | Regolate il primo colore sfumato. |
| <b>Opacità colore:</b> | Regolate l’opacità del primo colore sfumato. |
| <b>Metodo fusione colore:</b> | Selezionate il metodo di fusione del primo colore sfumato. |
| <b>Colore 2:</b> | Regolate il secondo colore della sfumatura. |
| <b>Opacità colore 2:</b> | Regolate l’opacità del secondo colore sfumato. |
| <b>Metodo di fusione Colore 2:</b> | Selezionate il metodo di fusione del secondo colore sfumato. |
| <b>Rotazione orizzontale:</b> | Regolate la rotazione orizzontale della sfumatura. |
| <b>Rotazione verticale:</b> | Regolate la rotazione verticale della sfumatura. |
| <b>Inversione sfumatura:</b> | Attivate/disattivate l’inversione della maschera sfumatura. |
| <b>Scostamento sfumatura:</b> | Regolate lo scostamento della maschera sfumatura. |
| <b>Contrasto sfumatura:</b> | Regolate il contrasto della maschera sfumatura. |

### Eseguita i baking illuminazione

| Nome parametro | Descrizione |
| --- | --- |
| <b>Tratti Del Pennello Nell&#39;Illuminazione:</b> | Regola il grado di variazione del tratto del pennello visualizzato nell’illuminazione eseguita i baking. |
| <b>Intensità Diffusa:</b> | Regolate l’intensità della luce diffusa. |
| <b>Colore Diffusa:</b> | Regolate il colore della luce diffusa. |
| <b>Raggio Diffusa:</b> | Regolate il raggio della luce diffusa. |
| <b>Contrasto Diffusa:</b> | Regolate il contrasto della luce diffusa. |
| <b>Intensità Specular:</b> | Regolate l’intensità della luce specular. |
| <b>Colore Specular:</b> | Regolate il colore della luce specular. |
| <b>Raggio Specular:</b> | Regolate il raggio della luce specular. |
| <b>Contrasto Specular:</b> | Regolate il contrasto della luce specular. |
| <b>Rotazione orizzontale:</b> | Regolate la rotazione orizzontale della sorgente luminosa. |
| <b>Rotazione verticale:</b> | Regolate la rotazione verticale della sorgente luminosa. |
| <b>Nitidezza colore:</b> | Regolate la nitidezza applicata al Colore di base. |
| <b>Nitidezza superficie:</b> | Regolate l&#39;effetto di dettaglio della superficie basato sulla trama sul Colore di base. |

### Bordi E Cavità

| Nome parametro | Descrizione |
| --- | --- |
| <b>Modalità:</b> | Selezionate se mappare cavità, bordi o entrambi sul Colore di base. |
| <b>Contrasto bordi e cavità:</b> | Regolate il contrasto della maschera per bordi e cavità. |
| <b>Opacità cavità:</b> | Regolate l&#39;intensità delle cavità fuse in Colore di base. |
| <b>Distribuzione cavità:</b> | Regolate l&#39;estensione delle cavità fuse in Colore di base. |
| <b>Tratti Pennello Nelle Cavità:</b> | Regolate il modo in cui i tratti del pennello mascherano la fusione delle cavità. |
| <b>Colore cavità personalizzate:</b> | Attivate/disattivate l’uso di un colore personale nelle cavità. |
| <b>Colore cavità:</b> | Regolate il colore personale mescolato nelle cavità. |
| <b>Opacità bordi:</b> | Regolate l&#39;intensità dei bordi fusi in Colore di base. |
| <b>Pagine affiancate ai bordi:</b> | Regolate la diffusione dei bordi fusi in Colore di base. |
| <b>Tratti Pennello Nei Bordi:</b> | Regola il modo in cui i tratti del pennello mascherano la fusione dei bordi. |
| <b>Colore bordi personalizzati:</b> | Attiva/disattiva l’uso di un colore personale sui bordi. |
| <b>Colore bordi:</b> | Regolate il colore personale mescolato ai bordi. |

#### Helper

| Nome parametro | Descrizione |
| --- | --- |
| <b>Helper visualizzazione:</b> | Seleziona la maschera di supporto o le informazioni di debug da visualizzare in Colori di base. |

