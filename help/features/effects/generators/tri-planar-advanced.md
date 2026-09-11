---
title: Tri-Planari Advanced
description: Scopri come utilizzare il generatore avanzato Tri-Planari di Substance 3D Painter.
source-git-commit: b7770a9497f0db047433aec32c31b57f8dc13ae7
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 2%

---


# Tri-Planari Advanced

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../../assets/generators/icon_tri_planar_advanced.png" alt=""/><br><strong>In:</strong> maschera, generatore</td>
    <td style="border: 0;" valign="top"><strong>Descrizione</strong><br>Il generatore Avanzato di Planari tridimensionali è una versione autonoma del metodo di fusione triplanare con controlli manuali per la proiezione completa, incluso il controllo di tutti i valori di rotazione e offset per ogni asse separato. Rispetto alla proiezione di riempimento nativa, il generatore avanzato Tri-Planari utilizza le normali dello spazio globale per fondere i tre assi di proiezione, mentre l'implementazione nativa si basa solo sulla geometria a basso polo. Ciò consente un maggiore controllo e risultati più accurati.<br><br>Il generatore avanzato Tri-Planari genera una texture monocromatica (bianco e nero). Di conseguenza, è utile per generare una fusione a tre planari di una maschera personalizzata o di un punto di ancoraggio da utilizzare come maschera.<br><br>Per l'input dell'immagine sono necessarie mappe normali di posizione Eseguita i baking e di spazio mondo. <a href="../../../baking/baking.md">Ulteriori informazioni sulla esegue i baking</a>.</td>
  </tr>
</table>

## Input

| Nome di input | Descrizione |
| --- | --- |
| Colore **Spazio globale normale** | Utilizzare la mappa eseguita i baking World Space Normals. |
| Colore **Posizione** | Utilizzate la mappa di posizione al forno. |
| **maschera** in scala di grigi | Usate una texture personalizzata o un punto di ancoraggio. |

## Parametri

<table>
  <tr>
    <th>Nome parametro</th>
    <th>Descrizione</th>
  </tr>
  <tr>
    <td><strong>Proiezione</strong></td>
    <td>Selezionare se proiettare tutti gli assi o solo un singolo asse.</td>
  </tr>
  <tr>
    <td><strong>Metodo fusione</strong></td>
    <td>Selezionate il metodo di fusione per la fusione tra gli assi.<br><ul><li><strong>Lineare</strong>: nella modalità di fusione lineare la linea di transizione di fusione è retta.</li><li><strong>Avanzate</strong>: in modalità di fusione avanzata, gli assi vengono fusi in base al valore massimo tra i 3 assi e l'angolo normale in una determinata posizione.</li></ul></td>
  </tr>
  <tr>
    <td><strong>Fusione del contrasto</strong></td>
    <td>Regola l’entità di sfocatura della linea di transizione di fusione.</td>
  </tr>
  <tr>
    <td><strong>Affiancamento texture</strong></td>
    <td>Regolate la suddivisione in porzioni della texture della maschera.</td>
  </tr>
</table>

### Asse X

| Nome parametro | Descrizione |
| --- | --- |
| **Rotazione X** | Ruotare la proiezione della texture dell&#39;asse X. |
| **Scostamento X X** | Spostate la proiezione della texture dell’asse X verso sinistra o verso destra. |
| **Scostamento X Y** | Spostate la proiezione della texture dell’asse X verso l’alto o il basso. |

### Asse Y

| Nome parametro | Descrizione |
| --- | --- |
| **Rotazione X** | Ruotare la proiezione della texture dell&#39;asse Y. |
| **Scostamento Y X** | Spostate la proiezione della texture dell&#39;asse Y verso sinistra o verso destra. |
| **Scostamento Y** | Spostate la proiezione della texture dell&#39;asse Y verso l&#39;alto o il basso. |

### Asse Z

| Nome parametro | Descrizione |
| --- | --- |
| **Rotazione X** | Ruotare la proiezione della texture dell&#39;asse Z. |
| **Scostamento Z X** | Spostate la proiezione della texture dell&#39;asse Z verso sinistra o verso destra. |
| **Scostamento Z Y** | Spostare la proiezione della texture dell&#39;asse Z verso l&#39;alto o verso il basso. |
