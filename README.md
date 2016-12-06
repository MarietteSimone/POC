# POC inleiding

Doel huidige app MisofoMe
De app MisofoMe heeft als doel het stimuleren van de uitwisseling van oefeningen door misofonie patiënten. Deze oefeningen helpen hen bij het leren omgaan met de misofonie.

Probleem
In de interviews die we hebben afgenomen met zowel patiënten als met een therapeut is naar voren gekomen dat de behandeling in het AMC niet voldoende is. Het is te vergelijken met het behalen van je rijbewijs, daarna begint het pas echt en doe je echt ervaring op. Na de therapie in het AMC zullen patiënten zelf hun behandeling moeten voortzetten. De hoofdvraag die wij naar aanleiding van dit probleem hebben opgesteld, luidt:
“Hoe kunnen we misofonie patiënten ondersteunen in het proces van zelfbehandeling na het afronden van hun therapie in het AMC?”

Wij creëren een platform waar misofonie patiënten oefeningen kunnen uitwisselen die voor hen goed werken. Hierdoor kunnen
Kies een geluid ervaren misofonie patiënten andere patiënten helpen. We maken verschillende formats voor de verschillende typen oefeningen, zodat het voor de gebruiker makkelijker wordt om bruikbare oefeningen toe te voegen. Doordat we de layout beter structureren, zijn de oefeningen prettiger te gebruiken.

<img src="https://trello-attachments.s3.amazonaws.com/583830811dba0b1a3139bbda/5846e835f79f80897744f493/c7b393ecadc609ab2dfc5be648e43814/Schermafbeelding_2016-12-06_om_17.18.42.png" alt="mijn afbeelding" title="Concept schets" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">
<img src="https://trello-attachments.s3.amazonaws.com/583830811dba0b1a3139bbda/5846e835f79f80897744f493/5ff29cb25bff1c518dcb8812be115036/Schermafbeelding_2016-12-06_om_17.18.36.png" alt="mijn afbeelding" title="Concept schets" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">

# Mijn technische uitdagingingen:
- Is het haalbaar om de hele app binnen de daarvoor beschikbare tijd te prototypen in Framer?
- Wat voor functies hebben we nodig om ons concept te kunnen maken?

# Aanpak
Ik ben eerst gaan kijken wat ik allemaal kon vinden over het werken met Framer, Het is interessant om te zien dat er al zoveel prototypes beschikbaar zijn. Over het algemeen lees en hoor ik veel positieve ervaringen over dit programma, je moet het even onder de knie krijgen maar daarna is het "super easy" zoals ze dat zeggen.

hieronder lees je een aantal ontdekkingen.

Sketch Import is daarbij heel belangrijk, daar kunnen we de gemaakte ontwerpen uit Sketch importeren.

voorbeeld van de code:
Import file "design" 
sketch = Framer.Importer.load("imported/design@1x")
 
Set the opacity of layerA 
sketch.layerA.opacity = 0.5

#  Screen-to-Screen Workflow code:
Dit is een belangrijke omdat we tussen verschillende pagina's moeten kunnen wisselen.

Create layers 
layerA = new Layer
    backgroundColor: "#00AAFF"
    size: Screen.size
 
layerB = new Layer
    backgroundColor: "#FFCC33"
    size: Screen.size
 
Set up FlowComponent 
flow = new FlowComponent
flow.showNext(layerA)

Transition to layerB on click 
layerA.onClick ->
    flow.showNext(layerB)
    
Go backwards 
flow.showPrevious()

# Functies voor ons concept
Ik heb op de portfolio pagina van Framer en een paar andere site's gekeken, en heb hieruit een aantal functies/interacties/voorbeelden kunnen halen die voor ons concept nodig zijn: 

- Bewegend beeld: https://share.framerjs.com/fjs6tr726vap/
- Chat Bubbles: https://share.framerjs.com/93x31t8weg1p/
- List Sorting: https://share.framerjs.com/exw00nylgvo3/
- Add project(oefening): https://material.uplabs.com/posts/add-project-animation
- Design Music Player: https://material.uplabs.com/posts/material-design-music-app-prototype
- Login: http://share.framerjs.com/b6qelo86ma45/
- Share: http://share.framerjs.com/1m7q7xefvn4d/


Deze bestanden kun je dan weer openen in Framer om te gebruiken in je eigen ontwerp.

# Nuttige video's/tutorials 
Op youtube heb je een aantal framer tutorials die je een stuk verder kunnen helpen, onderstaande video gaat vooral over interacties en transities.

https://www.youtube.com/watch?v=3zaxrXK7Nac

# bronnen
- https://material.uplabs.com/benjaminnathan
- https://framerjs.com/gallery/
- youtube.nl

# conclusie
Op de vraag of het mogelijk is voor ons om een prototype te maken in framer, denk ik dat het antwoord ja is er is genoeg informatie te vinden om het te kunnen leren. Een groter struikelblok zal de tijd zijn die we ervoor hebben. Verder heb ik erg handige functies gevonden die we in ons prototype kunnen gaan gebruiken.

# Extra 
Handige functies

Next & Previous — Go back and forth between two screens.<br>
Overlay — Show a new screen from the bottom.<br>
Modal — Show a modal dialog from the center.<br>
Scroll — Scrollable artboard with anchored layers.<br>
