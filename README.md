# POC

Doel huidige app MisofoMe
De app MisofoMe heeft als doel het stimuleren van de uitwisseling van oefeningen door misofonie patiënten. Deze oefeningen helpen hen bij het leren omgaan met de misofonie.

Probleem
In de interviews die we hebben afgenomen met zowel patiënten als met een therapeut is naar voren gekomen dat de behandeling in het AMC niet voldoende is. Het is te vergelijken met het behalen van je rijbewijs, daarna begint het pas echt en doe je echt ervaring op. Na de therapie in het AMC zullen patiënten zelf hun behandeling moeten voortzetten. De hoofdvraag die wij naar aanleiding van dit probleem hebben opgesteld, luidt:
“Hoe kunnen we misofonie patiënten ondersteunen in het proces van zelfbehandeling na het afronden van hun therapie in het AMC?”

Mijn technische uitdaging:
Is het haalbaar om de hele app binnen de daarvoor beschikbare tijd te prototypen in Framer?

Dingen die we allemaal van Framer kunnen leren voor ons prototype:

Next & Previous — Go back and forth between two screens.<br>
Overlay — Show a new screen from the bottom.<br>
Modal — Show a modal dialog from the center.<br>
Scroll — Scrollable artboard with anchored layers.<br>

Sketch Import is daarbij heel belangrijk, daar kunnen we de gemaakte ontwerpen uit importeren.

voorbeeld van de code:
# Import file "design" 
sketch = Framer.Importer.load("imported/design@1x")
 
# Set the opacity of layerA 
sketch.layerA.opacity = 0.5

Verder is een Screen-to-Screen Workflow tussen de gemaakte schermen belangrijk die code zal er ongeveer zo uitzien:

# Create layers 
layerA = new Layer
    backgroundColor: "#00AAFF"
    size: Screen.size
 
layerB = new Layer
    backgroundColor: "#FFCC33"
    size: Screen.size
 
# Set up FlowComponent 
flow = new FlowComponent
flow.showNext(layerA)

# Transition to layerB on click 
layerA.onClick ->
    flow.showNext(layerB)
    
# Go backwards 
flow.showPrevious()

Dan heb je nog video's op youtube die je een stuk verder kunnen helpen, onderstaande video gaat vooral over interacties en transities.

https://www.youtube.com/watch?v=3zaxrXK7Nac
