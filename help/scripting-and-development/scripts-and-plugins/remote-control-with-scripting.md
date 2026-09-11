---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/scripting-and-development/scripts-and-plugins/remote-control-with-scripting.html"
breadcrumb-title: ''
description: Scoprite come utilizzare lo scripting del controllo remoto in Substance 3D Painter per automatizzare i flussi di lavoro e controllare l'applicazione a livello di programmazione.
helpx_creative_field: ""
helpx_description: Painter > Scripting and development > Scripts and plugins > Remote control with scripting
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Controllo remoto con scripting
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '346'
ht-degree: 0%

---


# Controllo remoto con scripting

Questa pagina descrive come controllare l&#39;applicazione in remoto per eseguire i comandi Javascript o Python.\
Ciò richiede un argomento della riga di comando specifico, quindi un semplice script Python può eseguire qualsiasi comando disponibile dalle API Javascript e Python esistenti.

## Avvio dell’applicazione

Per controllare in remoto l’applicazione, è necessario avviare Substance 3D Painter con la riga di comando seguente:

```
"Adobe Substance 3D painter.exe" --enable-remote-scripting
```


>[!NOTE]
>
> Prima di eseguire gli script, verificare che l&#39;applicazione sia attiva e in esecuzione con questo comando. Se l’applicazione è ancora in fase di avvio o non è ancora pronta, gli script potrebbero non riuscire.

## Script di controllo remoto

Il seguente script Python può fungere da libreria per comunicare con l&#39;applicazione.

Salva lo script seguente in un file denominato **lib\_remote.py** per far funzionare correttamente gli esempi riportati di seguito.

```
import sys 

import json 

import base64 

import subprocess 

 

if sys.version_info >= (3, 0): 

 import http.client as http 

else: 

 import httplib as http 

 

class RemotePainter() : 

 def __init__(self, port=60041, host='localhost'): 

  self._host = host 

  self._port = port 

 

## Json server connection

  self._PAINTER_ROUTE = '/run.json' 

  self._HEADERS = {'Content-type': 'application/json', 'Accept': 'application/json'} 

 

## Execute a HTTP POST request to the Substance Painter server and send/receive JSON data

 def _jsonPostRequest( self, route, body, type ) : 

  connection = http.HTTPConnection(self._host, self._port, timeout=3600) 

  connection.request('POST', route, body, self._HEADERS) 

  response = connection.getresponse() 

 

  data = response.read() 

  connection.close() 

 

  if type == "js" : 

   data = json.loads( data.decode('utf-8') ) 

 

   if 'error' in data: 

    OutJson = json.loads( body.decode() ) 

    print( base64.b64decode( OutJson["js"] ) ) 

    raise ExecuteScriptError(data['error']) 

  else : 

## Python can return nothing, so decoding can fail

   try: 

    data = data.decode('utf-8').rstrip() 

   except: 

    pass 

 

  return data 

 

 def checkConnection(self): 

  connection = http.HTTPConnection(self._host, self._port) 

  connection.connect() 

 

## Execute a command

 def execScript( self, script, type ) : 

  Command = base64.b64encode( script.encode('utf-8') ) 

 

  if type == "js" : 

   Command = '{{"js":"{0}"}}'.format( Command.decode('utf-8') ) 

  else : 

   Command = '{{"python":"{0}"}}'.format( Command.decode('utf-8') ) 

 

  Command = Command.encode( "utf-8" ) 

 

  return self._jsonPostRequest( self._PAINTER_ROUTE, Command, type ) 

 

class PainterError(Exception): 

 def __init__(self, message): 

  super(PainterError, self).__init__(message) 

 

class ExecuteScriptError(PainterError): 

 def __init__(self, data): 

  super(PainterError, self).__init__('An error occured when executing script: {0}'.format(data)) 

 
```


## Esempi

Di seguito sono riportati due semplici esempi che mostrano come eseguire i comandi in entrambe le API supportate dall’applicazione:

### Esecuzione dei comandi JavaScript

La maggior parte delle funzioni Javascript nell’API restituisce dati String o Json che li rendono facili da manipolare all’interno dello script Python. L&#39;invio e la ricezione dei dati non dovrebbero comportare particolari problemi.

Crea un file di script python denominato **example\_js.py** e aggiungi il codice seguente:

```
import lib_remote 

 

Remote = lib_remote.RemotePainter() 

Remote.checkConnection() 

 

## Print the API version

Version = Remote.execScript( "alg.version.painter", "js" ) 

print( Version ) 

 

## Get a list of all the files in the default shelf/library:

Files = Remote.execScript( 'alg.resources.findResources("starter_assets", "*")', "js" ) 

 

for File in Files : 

 print( File )
```


Se l&#39;applicazione è in esecuzione con la riga di comando, l&#39;esecuzione di questo script consentirà l&#39;esecuzione dei comandi e il recupero dei relativi risultati.

### Esecuzione dei comandi Python

La maggior parte delle funzioni Python possono restituire oggetti che non possono essere passati nello script remoto, il che significa che per ricevere i dati devono essere esplicitamente convertiti in stringhe o dizionari Json.

Per semplificare le operazioni, è possibile creare uno script pitone personalizzato che viene caricato durante l&#39;avvio dell&#39;applicazione e chiamare le funzioni che gestiscono questo tipo di conversione senza dover fare affidamento sulle conversioni in linea.

Crea un file di script python denominato **example\_py.py** e aggiungi il codice seguente:

```
import lib_remote 

 

Remote = lib_remote.RemotePainter() 

Remote.checkConnection() 

 

## import the substance_painter module to make

## its API available to us

Remote.execScript( "import substance_painter", "python" ) 

 

## Print the API version

Version = Remote.execScript( "substance_painter.__version__", "python" ) 

print( Version ) 

 

## Get a list of all the files in the default shelf/library

## Because the search function return objects, we have to convert

## the information into a string within the same command (inline)

Command = 'substance_painter.resource.search( "p:starter_assets/" )' 

Command = '"|||".join( [ x.identifier().url() for x in {0}] )'.format( Command ) 

 

Files = Remote.execScript( Command, "python" ) 

Files = Files.split( "|||" ) 

 

for File in Files : 

 print( File )
```


Se l&#39;applicazione è in esecuzione con la riga di comando, l&#39;esecuzione di questo script consentirà l&#39;esecuzione dei comandi e il recupero dei relativi risultati.
