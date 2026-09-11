---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/scripting-and-development/scripts-and-plugins/creating-a-javascript-plugin.html"
breadcrumb-title: ''
description: Scopri come creare plug-in JavaScript per Substance 3D Painter per estendere le funzionalità e automatizzare i flussi di lavoro personalizzati.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > Scripts and plugins > Creating a Javascript plugin
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creazione di un plug-in Javascript
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 1%

---


# Creazione di un plug-in Javascript

Questa guida dettagliata descrive come creare un plug-in semplice che consente di esportare la maschera del livello attualmente selezionato in un progetto.

L’obiettivo del plug-in in questa guida è esportare tutti i canali del set di texture corrente all’interno di un progetto come texture individuale.

## 1 - Passare alla cartella dei plug-in

Per aggiungere un nuovo plug-in Javascript, è necessario creare una cartella nella cartella dei plug-in di Substance 3D Painter.

Per accedere alla cartella **plugin**, accedi a:

<table data-preserve-html="true" style="width: 100.0%;"> <colgroup> <col style="width: 15.0%;"/> <col style="width: 15.0%;"/> <col style="width: 70.0%;"/> </colgroup> <tbody> <tr> <th>Piattaforma</th> <th>Versione</th> <th>Tracciato</th> </tr> <tr> <td rowspan="2"><strong>Windows</strong></td> <td><strong>7.2</strong> o versioni successive</td> <td colspan="1">C:\Users\username\Documents\Adobe\Adobe Substance 3D Painter</td> </tr> <tr> <td colspan="1">Precedente</td> <td colspan="1">C:\Users\username\Documents\Allegorithmic\Substance Painter</td> </tr> <tr> <td rowspan="2"><strong>Mac</strong></td> <td colspan="1"><strong>7.2</strong> o versioni successive</td> <td colspan="1">/Utenti/nome utente/Documenti/Adobe/Adobe Substance 3D Painter</td> </tr> <tr> <td colspan="1">Precedente</td> <td colspan="1">/Utenti/nomeutente/Documenti/Allegorithmic/Substance Painter</td> </tr> <tr> <td rowspan="2"><strong>Linux</strong></td> <td colspan="1"><strong>7.2</strong> o versioni successive</td> <td colspan="1">/home/nomeutente/Documenti/Adobe/Adobe Substance 3D Painter</td> </tr> <tr> <td>Precedente</td> <td colspan="1">/home/nomeutente/Documenti/Allegorithmic/Substance Painter</td> </tr> </tbody> </table>

### 2 - Creazione della cartella del plug-in

Il nome di un plug-in si basa sul nome della cartella principale.

Per questo esempio, è sufficiente creare una nuova cartella denominata **export-texture** all&#39;interno della cartella dei plug-in.

### 3 - Creazione dei file del plug-in

Apri la cartella appena creata e crea due file di testo vuoti (blocco note):

* **main.qml**
* **toolbar.qml**

L’estensione file qml è un’estensione Javascript per gli script creati per il linguaggio QML Qt. Consente di eseguire codice Javascript ma anche di creare interfacce utente personalizzate.

Il file **main.qml** è obbligatorio. Si tratta del primo file che verrà cercato dall&#39;applicazione per caricare il plug-in. È tuttavia possibile creare file aggiuntivi con qualsiasi nome, consentendo di dividere uno script in parti per una gestione più semplice. In questo caso, **toolbar.qml** verrà utilizzato per descrivere l&#39;aspetto di un pulsante che verrà aggiunto nell&#39;interfaccia dal plug-in.

### 4 - Contenuto dello script

Aprite i file script in un editor di testo come Blocco note++ e incollate i seguenti snippet di codice. Per ulteriori dettagli, vedere i commenti relativi al codice.

**toolbar.qml**

```
import QtQuick 2.7 

import AlgWidgets 2.0 

import AlgWidgets.Style 2.0 

 

AlgButton 

{ 

 tooltip: "" 

 iconName: "" 

 text: "Export Textures" 

}
```


**main.qml**

```
// Default includes, to acces Qt/QML 

// and Substance 3D Painter APIs 

import QtQuick 2.7 

import Painter 1.0 

 

// Root object for the plugin 

PainterPlugin 

{ 

 // Disable update and server settings 

 // since we don't need them 

 tickIntervalMS: -1 // Disabled Tick 

 jsonServerPort: -1 // Disabled JSON server 

 

 // Implement the OnCompleted function 

 // This event is used to build the UI 

 // once the plugin as been loaded by Substance 3D Painter 

 Component.onCompleted: 

 { 

  // Create a toolbar button 

  var InterfaceButton = alg.ui.addToolBarWidget("toolbar.qml"); 

 

  // Connect the function to the button 

  if( InterfaceButton ) 

  { 

   InterfaceButton.clicked.connect( exportTextures ); 

  } 

 } 

 

 // Custom function called by the Button, 

 // this is the core of the plugin 

 function exportTextures() 

 { 

  // Catch errors in the script during execution 

  try 

  { 

   // Verify if a project is open before  

   // trying to export something 

   if( !alg.project.isOpen() ) 

   { 

    return; 

   } 

 

   // Retrieve the currently selected Texture Set (and sub-stack if any) 

   var MaterialPath = alg.texturesets.getActiveTextureSet() 

   var UseMaterialLayering = MaterialPath.length > 1 

   var TextureSetName = MaterialPath[0] 

   var StackName = "" 

 

   if( UseMaterialLayering ) 

   { 

    StackName = MaterialPath[1] 

   } 

 

   // Retrieve the Texture Set information 

   var Documents = alg.mapexport.documentStructure() 

   var Resolution = alg.mapexport.textureSetResolution( TextureSetName ) 

   var Channels = null 

 

   for( var Index in Documents.materials ) 

   { 

    var Material = Documents.materials[Index] 

 

    if( TextureSetName == Material.name ) 

    { 

     for( var SubIndex in Material.stacks ) 

     { 

      if( StackName == Material.stacks[SubIndex].name ) 

      { 

       Channels = Material.stacks[SubIndex].channels 

       break 

      } 

     } 

    } 

   } 

 

   // Create the export settings 

   var Settings = { 

    "padding":"Infinite", 

    "dithering":"disbaled", // Hem, yes... 

    "resolution": Resolution, 

    "bitDepth": 16, 

    "keepAlpha": false 

   } 

 

   // Build the base of the export path 

   // Files will be located next to the project 

   var BasePath = alg.fileIO.urlToLocalFile( alg.project.url() ) 

   BasePath = BasePath.substring( 0, BasePath.lastIndexOf("/") ); 

 

   // Export the each channel 

   for( var Index in Channels ) 

   { 

    // Create the stack path, which defines the channel to export 

    var Path = Array.from( MaterialPath ) 

    Path.push( Channels[Index] ) 

 

    // Build the filename for the texture to export 

    var Filename = BasePath + "/" + TextureSetName 

 

    if( UseMaterialLayering ) 

    { 

     Filename += "_" + StackName 

    } 

 

    Filename += "_" + Channels[Index] + ".png" 

 

    // Perform the export 

    alg.mapexport.save( Path, Filename, Settings ) 

    alg.log.info( "Exported: " + Filename ) 

   } 

  } 

  catch( error ) 

  { 

   // Print errors in the log window 

   alg.log.exception( error ) 

  } 

 } 

} 
```


Al termine, salva e chiudi il file.

### 5 - Caricamento e attivazione del plug-in

Avviate Substance 3D Painter: per impostazione predefinita, i nuovi plug-in vengono caricati e attivati automaticamente.

Aprite un progetto, quindi fate clic sul pulsante dell’interfaccia utente creato dal plug-in per esportare i canali del set di texture attualmente selezionato:

![](../../assets/button-plugin.png)

Per attivare o disattivare un plug-in, usate il menu JavaScript nella parte superiore dell&#39;interfaccia:

![](../../assets/disable-plugin.png)
