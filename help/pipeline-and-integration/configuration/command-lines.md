---
helpx_url: "https://helpx.adobe.com/it/substance-3d-painter/pipeline-and-integration/configuration/command-lines.html"
breadcrumb-title: ''
description: Scoprite come utilizzare gli argomenti della riga di comando con Substance 3D Painter per l'automazione, lo scripting e l'integrazione della pipeline.
helpx_creative_field: ""
helpx_description: Painter > Pipeline and integration > Configuration > Command lines
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Righe di comando
user-guide-description: ''
user-guide-title: ''
source-git-commit: 22871eab2f25d09bd82f1292d8b3e5f8c4f1c2cf
workflow-type: tm+mt
source-wordcount: '204'
ht-degree: 0%

---


# Righe di comando

In questa pagina sono elencate diverse righe di comando che è possibile utilizzare, ad esempio, all&#39;avvio dell&#39;applicazione per creare o aprire progetti.\
Queste righe di comando possono essere utilizzate come segue:

```
"Adobe Substance 3D Painter.exe" --command [option] 
```


## Elenco dei comandi

| Comando | Descrizione |
| --- | --- |
| **—help** **-?** **-h** | Visualizza informazioni sulla riga di comando disponibile e su come utilizzarla. |
| **—versione** **-v** | Visualizza la versione corrente di Substance 3D Painter. |
| **—mesh** | Trama da caricare in un progetto.Esempio: `// Create a new project with a specific mesh   "Adobe Substance 3D Painter.exe" --mesh "E:/MymeshFolder/MyMesh.obj"       // Update a mesh inside an existing project   "Adobe Substance 3D Painter.exe" --mesh "E:/MymeshFolder/MyMesh.obj" "E:/MyMeshFolder/Project.spp"` |
| **—mesh-map** | Mappe con baking associate alla trama (AO, Normale, Curvatura). Può essere specificato più volte. Nomenclatura : TextureSetName\_AdditionalMapSlot<ul data-preserve-html="true"> <li data-preserve-html="true">Occlusione ambientale = <strong> <em> occlusione </em> </strong></li> <li data-preserve-html="true">Curvatura = <strong> <em> curvatura </em> </strong></li> <li data-preserve-html="true">Normale = <strong> <em> base_normale </em> </strong></li> <li data-preserve-html="true">Spazio globale normale = <strong> <em> world_space_normals </em> </strong></li> <li data-preserve-html="true">Posizione = <strong> Posizione <em> </em> </strong></li> <li data-preserve-html="true">Thickness = <strong> <em> thickness </em> </strong></li> <li data-preserve-html="true">ID = <em> ID <strong> </strong> </em></li> </ul>Esempio: `"Adobe Substance 3D Painter.exe" --mesh "E:/MyMeshFolder/MyMesh.obj" --mesh-map " E:/MyMeshFolder/DefaultMaterial_ambient_occlusion.png"` |
| **—split-by-udim** | Create un set di texture per porzione UDIM. |
| **—export-path** | Percorso di esportazione predefinito in cui verranno esportati gli output del progetto. |
| **—vram-budget** | Sostituisci il budget della memoria video (VRAM) definito dal motore Substance 3D Painter. &quot;Quantità&quot; espressa in megabyte.    Esempio: `// Set the VRam budget to 2GB   "Adobe Substance 3D Painter.exe" --vram-budget 2048` |
| **—disable-version-check** | Non verificare la disponibilità di una nuova versione dell&#39;applicazione all&#39;avvio |
| **—enable-remote-scripting** | Consente di eseguire comandi di script dall&#39;esterno dell&#39;applicazione. Per ulteriori informazioni, vedere [Controllo remoto con script](../../scripting-and-development/scripts-and-plugins/remote-control-with-scripting.md). |
