---
helpx_url: "https://helpx.adobe.com/substance-3d-painter/painting/presets/creating-particles-presets/overview-of-the-particle-editor.html"
breadcrumb-title: ''
description: Scopri l’editor di particelle di Substance 3D Painter per creare pennelli particelle personalizzati per la pittura di texture.
helpx_creative_field: ""
helpx_description: Painter > Painting > Presets > Creating particles presets > Overview of the particle editor
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Panoramica dell'editor particelle
user-guide-description: ''
user-guide-title: ''
source-git-commit: 9f20406f682e0e6a2e9a423e81c5ecfc7430ecfd
workflow-type: tm+mt
source-wordcount: '1677'
ht-degree: 0%

---


# Panoramica dell&#39;editor particelle

Questa pagina descrive diversi aspetti dell’editor di particelle PopcornFX. Alcuni titoli e parametri delle finestre possono essere soggetti a modifiche a seconda della versione dell&#39;editor utilizzato.

## Impostazione finestra vista

### Come importare la propria trama

Copiate e incollate la trama nella cartella &quot;Trame&quot; del pacchetto. Quindi nell&#39;Editor apri la trama e fai clic su &quot;Genera&quot;.

Ora, nel sistema di particelle, andare a &quot;Sfondo&quot; nella vista albero, fare clic con il pulsante destro su &quot;3D Layers&quot;, &quot;New Backdrop&quot;, &quot;CNEdEditorBackdrop\_Model3D&quot;, e selezionare la trama in &quot;resource model&quot;.

In Substance 3D Painter, la trama viene ridimensionata in modo da trovarsi all’interno di una casella di dimensioni [-1;1] su ciascun asse. Per ottenere la scala corretta con Substance 3D Painter nell’Editor, devi importare una trama già ridimensionata per adattarsi a quella casella (modo facile) oppure giocare con le scale nell’Editor.

Nota: sono supportati solo i formati di trama FBX.

#### Come visualizzare la griglia

Ctrl+G. È possibile personalizzare il colore della griglia in &quot;Editor Properties&quot; &quot;GridColor&quot;.

## Emettitore

### Come creare eventi &quot;OnCollide&quot;

Il Physics Evolver gestisce la collisione con trame di sfondo nella scena. In Substance 3D Painter la scena sarà la vostra trama.

Prima nel Physics Evolver impostato &quot;WorldInteractionMode&quot; su &quot;OneWay&quot; per abilitare la collisione di particelle. Quindi crea un evento chiamato &quot;OnCollide&quot;, il Physics Evolver lo attiverà in caso di collisione con la scena.

In Substance 3D Painter, la scena è il modello su cui stai lavorando e tutti gli eventi chiamati &quot;OnCollide&quot; saranno sostituiti dal sistema di particelle Emitter del pennello corrente.

#### Come attivare le particelle dalla fotocamera

Nella parte superiore della finestra della vista, attivare il quarto pulsante &quot;Vincola le uova sul piano della fotocamera&quot;.

Per impostazione predefinita, Substance 3D Painter attiva gli emettitori dalla fotocamera.

#### Come emettere particelle in cima come la pioggia

Se abilitata, disattiva &quot;Vincola le uova sul piano della videocamera&quot;.

Create un Attributo Particella chiamato &quot;Globale&quot;, ora Substance 3D Painter genererà le vostre particelle all&#39;origine.

Per generare uova sulla parte superiore della trama, aggiungete una Shape Sampler BOX o CYLINDER, posizionatela sopra e campionatela nel vostro Script Spawner.

Ad esempio, con una Shape Sampler BOX chiamata &quot;Spawn&quot;, aggiungi questo allo script Spawner:

*Posizione = Spawn.samplePosition();*

## Ricevitore

### Come generare l’emettitore durante la creazione/modifica di un ricevitore

Per avvicinarti ancora di più al flusso di lavoro di Substance 3D Painter durante la modifica del ricevitore, puoi impostare l’editor in modo da ignorare il sistema di particelle generato.

Nella vista dell&#39;albero del ricevitore, selezionare &quot;Proprietà editor&quot;, quindi abilitare &quot;UserOverSpawn&quot; e selezionare l&#39;emettitore in &quot;OverSpawnEffect&quot;.

È comunque necessario aprire l&#39;emettitore per impostare gli eventi &quot;OnCollide&quot; per generare il ricevitore che si sta modificando.

#### Come impostare i campi particella

Ecco la descrizione del campo di particelle che deve avere nel ricevitore:

*&quot;Dimensione&quot; float*

Il moltiplicatore della dimensione del pennello in Substance 3D Painter.

*&quot;Opacità&quot; float*

Il moltiplicatore dell’opacità del pennello in Substance 3D Painter.

*float &quot;UV&quot;3*

Coordinata della texture sulla trama delle particelle.

In uno script Evolver, campionate la forma &quot;Trama&quot; di Sampler con la coordinata parametrica fornita dall&#39;Evolver proiezione:

UV = Mesh.sampleTexcoord(pCoords);

*&quot;Normale&quot; float3*

La normale della superficie della trama sotto le particelle.

In uno script Evolver, campionate la forma &quot;Trama&quot; di Sampler con la coordinata parametrica fornita dall&#39;Evolver proiezione:

Normale = normalizza(Mesh.sampleNormal(pCoords));

*&quot;Valore di inizializzazione&quot; int*

Solo un valore generato casualmente per Substance 3D Painter:

In uno script Evolver aggiungi:

Seme = int(rand(0,20000000));

*&quot;pCoords&quot; int3*

Non usato da Substance 3D Painter, ma indispensabile per fare la proiezione di particelle sulla trama e campionare altri campi.

#### Come proiettare particelle sulla trama

Aggiungete un modulo Evolver proiezione nello &quot;Stato\_0&quot; del ricevitore.

Ogni fotogramma, l&#39;Evolver proiezione proietterà le particelle sulla superficie più vicina di un Sampler di forma.

L&#39;Evolver della Proiezione può riempire la coordinata parametrica della proiezione nel campo di particelle specificato da &quot;OutputParametricCoordsField&quot; (vedi &quot;pCoords&quot; campo di particelle).

E può riproiettare un vettore sulla superficie della trama con &quot;ReprojectionsField&quot;.

Qui vogliamo proiettare le particelle sulla forma Sampler &quot;Mesh&quot;, compilare le coordinate parametriche nel campo di particelle int3 &quot;pCoords&quot; e proiettare anche la &quot;Velocità&quot; sulla superficie:

#### Come campionare la trama

In Substance 3D Painter, tutti i campionatori di forme denominati &quot;Mesh&quot; e &quot;ShapeType&quot; &quot;MESH&quot; verranno sostituiti con la trama utilizzata in Substance 3D Painter.<b>\
</b>

Nell’Editor, impostatela sulla stessa trama dello sfondo.

Per campionare elementi in uno script, è sufficiente scrivere &quot;Mesh.sample~Something~(pCoords)&quot; in uno script. Di seguito è riportata la documentazione:

<https://wiki.popcornfx.com/index.php/CParticleSamplerShape#Script_bindings>

Alcuni utili snippet di codice di cui avrai bisogno:

```
// UV is the texture coordinate of the particle on the mesh

// Must be after CParticleEvolver_Projection

UV = Mesh.sampleTexcoord(pCoords);

// Normal is the Normal of the surface on the mesh just below the particle

// Must be after CParticleEvolver_Projection

Normal = normalize(Mesh.sampleNormal(pCoords));
```


## Suggerimenti generali

### Come importare emettitore/ricevitore in Substance 3D Painter

In Substance 3D Painter, fai &quot;File&quot; > &quot;Importa particelle&quot; o Ctrl-Alt-R quindi scegli il tuo Emitter.pkfx o Receiver.pkfx nel tuo pacchetto.

Substance 3D Painter rileverà automaticamente i requisiti (campi di particelle, eventi OnCollide) per decidere se il pkfx è un emettitore, un ricevitore o nulla di compatibile.

Ora dovresti vedere l&#39;emettitore/ricevitore nello scaffale.

#### Come eseguire il debug di una particella con dimensioni di particella valide

Poiché il campo particella &quot;Dimensione&quot; deve essere compreso tra 0 e 1 per essere un moltiplicatore della dimensione del pennello in Substance 3D Painter, le particelle saranno di gran lunga troppo grandi nell’Editor. Quindi, aggiungi un campo personalizzato float &quot;BBSize&quot; impostato su 0.01 nello script Spawner, da utilizzare nel modulo di rendering delle particelle di Billboard come &quot;SizeField&quot; per visualizzare meglio la particella.

#### Come non rovinare con l&#39;ordine evolutivo

L&#39;ordine dell&#39;evolutore può essere molto importante.

Ad esempio, potreste voler sempre avere i vostri ultimi 2 evolutori per essere l&#39;Evolutore di proiezione e poi lo Script Evolver che campiona gli UV e i Normali con le pCoord generate dall&#39;Evolutore di proiezione.

Tenete presente che l&#39;ordine degli evolutori è letteralmente l&#39;ordine di esecuzione all&#39;interno di un fotogramma e che Substance 3D Painter raccoglierà i valori dei campi particella e la fine di ogni fotogramma.

#### Come campionare la mappa normale della trama

Substance 3D Painter sostituirà tutti i campionatori Texture denominati &quot;NormalMap&quot; con la mappa normale della trama (se importata).

Questa è l&#39;unica texture che puoi avere per ora, tutte le altre texture non saranno accessibili da Substance 3D Painter.

Una volta aggiunto il Sampler Texture &quot;NormalMap&quot;, è possibile campionarlo in uno script:

<http://www.popcornfx.com/wiki/index.php/CParticleSamplerTexture>

Alcuni snippet di codice utili:

```
// In Evolver Script convert the NormalMap texture in tangent space to world space normal

// /!\ the "Normal" particle field must always be the normal of the mesh not influenced by the normal map

// /!\ dont forget to initialize your particle fields in your Spawn Script

// otherwise pCoords and Normal will be invalid at the first update

float normalFactor = 1.0; // change the intensity of the normal map

float3 meshnormal = Normal;

float4 rawtangent = Mesh.sampleTangent(pCoords);

float3 binormal = normalize(cross(meshnormal, rawtangent.xyz) * rawtangent.w);

float3 tangent = normalize(cross(meshnormal, binormal));

float3 tsNormal = normalize(((NormalMap.sample(UV).xyz * 2.0 - 1.0).xyz) * float3(-normalFactor, normalFactor, 1));

float3 normal = normalize(tsNormal.x * tangent + tsNormal.y * binormal + tsNormal.z * meshnormal);
```


#### Come creare turbolenza

Nell’Editor, create un Sampler Turbulence.

<http://www.popcornfx.com/wiki/index.php/CParticleSamplerProceduralTurbulence>

Quindi ha 2 modi per campionare la turbolenza e agire sulle particelle:

##### Il modo più facile

Nel Physics Evolver del tuo livello, imposta &quot;VelocityFieldSampler&quot; sul tuo nome Turbulence Sampler e imposta &quot;Drag&quot; (Trascina) su un valore > 0.

##### La modalità con parametri

Potete regolare la turbolenza mediante attributi campionando il campo di velocità generato dal Sampler turbolenza in uno script Evolver:

Creare 2 Attributi Particella:

* float &quot;TurbulencePower&quot; minmax: [0;5]
* float &quot;TurbulenceScale&quot; minmax: [0,001; 5] (deve essere > 0)

Quindi crea 3 Campi Particella:

float &quot;TurbPower&quot; e float &quot;TurbScale&quot;

Per memorizzare gli attributi in essi contenuti nello script del generatore:

* TurbScale = 1,0 / TurbulenceScale;
* TurbPower = TurbulencePower;

float3 &quot;VelocityField&quot; in modalità di rotazione.

Sarà utilizzato come &quot;VelocityField&quot; nel Physics Evolver (già impostato per impostazione predefinita sul campo &quot;VelocityField&quot;).

Quindi prima del tuo Physics Evolver, in uno Script Evolver, campiona il tuo Turbulence Sampler chiamato &quot;Turb&quot;:

VelocityField = Turb.sample(Position \* TurbScale) \* TurbPower;

#### Come utilizzare correttamente il dt, il delta time

Il tempo delta è il tempo di simulazione in secondi tra gli aggiornamenti di ogni fotogramma. Nell&#39;editor il tempo delta viene aggiornato in base al tempo reale trascorso. In Substance 3D Painter il tempo delta è stato corretto e ogni aggiornamento viene avviato non appena terminato l’ultimo.

Un gioco in esecuzione a 60 FPS avrà un tempo delta di 1/60= 0,016 secondi, quindi prova a far funzionare i pennelli intorno a 0,016 di tempo delta.

* Tempo grandi delta > 0.016s
* Aggiornamento rapido PRO

Poiché l’intervallo tra gli aggiornamenti è molto lungo, il movimento delle particelle è maggiore e il Pennello viene eseguito più rapidamente in Substance 3D Painter.

* approssimazione CON

PopcornFX è una sorta di grande sistema di discrezionalità, quindi più grande è il dt, più grandi saranno le imprecisioni. Vedere l&#39;implicazione del tempo delta esteso sulle turbolenze: <http://www.popcornfx.com/wiki/index.php/CParticleEvolver_Physics#Dealing_with_turbulences_at_low_framerates>

* Schermate CON

Se il tempo delta è grande, anche il movimento delle particelle tra i fotogrammi è grande. Così, in Substance 3D Painter piccole macchie potrebbero apparire invece di linee rette.

Ciò accade perché Substance 3D Painter disegnerà un punto di tratto per ogni particella alla fine di ogni fotogramma e non disegnerà linee per ogni particella tra l’ultimo e il fotogramma corrente.

* Tempo delta ridotto &lt; 0,016 s
* Precisione PRO

Più piccolo è il tempo delta, più piccola sarà la distanza tra i tratti del pennello, quindi più nitido sarà il disegno. E anche la discrezionalità della simulazione sarà migliore.

* CON lenta

Più piccolo è il tempo delta, maggiore sarà il numero di aggiornamenti necessari per disegnare la stessa distanza.

Suggerimenti finali sui tempi delta : un buon modo per ottenere il dt corretto potrebbe essere iniziare con uno grande (0,1 s) poi diminuire passo dopo passo per ottenere il risultato desiderato.

#### Come esporre i parametri del sistema di particelle

Substance 3D Painter raccoglierà gli attributi delle particelle dei sistemi di particelle e li esporrà nei parametri del pennello fisico:

<http://www.popcornfx.com/wiki/index.php/Particle_effect_attributes>

In PopcornFX è disponibile la funzione denominata &quot;Attributi in Evolve&quot; che consente di accedere ad Attributo negli script Evolve: non fare così . Creare invece un campo particella e memorizzarvi l&#39;attributo nello script Spawner, quindi utilizzare tale campo particella negli script Evovler. (potrebbe essere risolto in futuro)

#### Come rilevare le particelle problematiche

Non dovresti mai avere particelle con strani valori di campo di particelle, quindi assicurati di rompere sui problemi di tanto in tanto:

<http://www.popcornfx.com/wiki/index.php/Particle_tips_BreakOnProblematicParticle>

#### Come risolvere i problemi dei sistemi di particelle in Substance 3D Painter

Nella directory di installazione di Substance 3D Painter è disponibile il file &quot;popcorn.htm&quot;. Questo file contiene tutti i registri di PopcornFX, dai un&#39;occhiata all&#39;interno per vedere cosa potrebbe succedere sbagliato.

#### Come inizializzare correttamente i campi particella

Per ottenere i valori validi per pCoords UV e Normal dal primo fotogramma, aggiungi questo elemento allo script per la generazione:

<b>  
</b>

```
// PostEval() will be called after particles have been translated to their respective spawn locations

// so, PostEval() is executed in world space

function void PostEval()

{

// we need to initialize correctly the values needed by Substance 3D Painter:

pCoords = Mesh.projectParametricCoords(Position);

UV = Mesh.sampleTexcoord(pCoords);

Normal = normalize(Mesh.sampleNormal(pCoords));

}
```
