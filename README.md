# Proof of Concept (POC) en Reflectie

Maya App
Jouw steun bij het voorkomen van een terugval.

Probleem
In het huidige ontwerp van de app is het beheren van lijsten onnodig moeilijk gemaakt. Zo is het wijzigen en verwijderen van factoren vrijwel onmogelijk voor de gebruiker. 


# Technische deelvragen

- Is het haalbaar om de hele app binnen de daarvoor beschikbare tijd te prototypen in Adobe XD?
- Hoe kan ik het scenario "lijstjes beheer" interactief maken in Adobe XD, en het geheel zo structureren/opslaan zodat het goed overdraagbaar is naar toekomstige MAYA developers?
- Hoe kunnen we beginnende gebruikers helpen de app snel te leren begrijpen, zodat ze meteen weten wat er mogelijk is en hoe ze lijsten kunnen beheren in de app?
- Zijn er in Adobe XD genoeg opties om de interactie met de app juist weer te geven?
- Zijn er voldoende tutorials beschikbaar?

# Technische leerdoelen
- Goed en vloeiend werkend prototype maken in Adobe XD, voor zover dat haalbaar is binnen de beschikbare tijd.
- Basis van Adobe XD goed begrijpen en het leerproces gestructureerd aanpakken.
- De microinteracties op een goede manier weergeven in Adobe XD.

Mijn doelen zijn met succes behaald als ik een sterk en goed lopend prototype van mijn scenario heb ontwikkeld, die ik op een makkelijke manier kan overbrengen aan mijn teamgenoten en eventueel toekomstige deelnemers van dit project.

# Inleiding

De technische deelvraag die ik in mijn Proof of Concept ga onderzoeken is: "Hoe kan ik het scenario "lijstjes beheer" interactief maken in Adobe XD, en het geheel zo structureren/opslaan zodat het goed overdraagbaar is naar toekomstige MAYA developers?"
Na onderzoek gedaan te hebben naar verschillende prototyping tools, kwam ik uiteindelijk terecht bij Adobe Experience Design. Deze kwam naar voren in verschillende artikelen als één van de beste en nieuwste prototyping tools van dit jaar. Ook liep ik bij de andere programma opties aan tegen proefversies of hoge prijzen, waardoor de overdraagbaarheid aanzienlijk lastiger/onmogelijk zou worden.
Het plan is om de stappen om een activiteit aan te maken, te ontwerpen binnen deze tool (incl. microinteracties).
Ik heb allereerst pattern onderzoek gedaan, waaruit nu de eerste schetsen zijn ontstaan. Die ik weer verder ga uitwerken en testen om vervolgens het prototype te kunnen maken.

<img src="https://trello.com/c/vT6PwoSE/12-ruwe-scheten" alt="mijn afbeelding" title="Concept schets" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">
<img src="https://trello.com/c/vT6PwoSE/12-ruwe-scheten" alt="mijn afbeelding" title="Adobe XD" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">


# Aanpak videoprototype/productvideo
Ik ben begonnen met het leren van het programma: Adobe Character Animator, en hoewel ik hier veel vorderingen mee heb gemaakt ben ik nog niet in staat om een voledige video op te bouwen met dit programma. Door tijdsgebrek heb ik moeten switchen naar een videoprototype in Adobe Premiere Pro. 

Ik heb hiervoor eerst een kort script geschreven:
- beelden emoties: schaamte, schuld, haat, angst, walging en onbegrip.
- Wat kan ik hier zelf tegen doen?
- Maak kennis met de Share & CAre app.
- Functies: oefeningen, toevoegen, favorieten, meldingen.
- Afsluiting: Be your happy self again! + call to action

<img src="https://trello.com/c/vT6PwoSE/12-ruwe-scheten" alt="mijn afbeelding" title="Adobe XD Ontwerp" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">

# Leerdoelen videoprototype/productvideo

# Conclusie videoprototype/productvideo

# Reflectie videoprototype/productvideo

Hieronder nog een lijst met welke functies ik heb gebruikt/geleerd: 

- Materiaal importeren in premiere pro
- Volume harder en zachter instellen
- geknipt in beeldmateriaal
- beelden versneld/vertraagd laten afspelen 
- meerdere filmpjes op een pagina (naast elkaar) 
- muziek toegevoegd
- meerdere filmpjes op een pagina (naast elkaar) 
- muziek transitions
- geïmporteerd naar vimeo
- titels toegevoegd

LINK NAAR HET VIDEOPROTOTYPE:https://vimeo.com/200873191

# Bronnen videoprototype/productvideo

- vimeo tutorials
- Adobe Character Animator
- http://www.pacdv.com/sounds/voices-2.html
- http://events-en-marketing.nl/9-wetten-om-een-onverslaanbare-productvideo-te-maken
- https://www.premiumbeat.com/blog/15-premiere-pro-tutorials-every-video-editor-watch/


Eerste poging met Adobe Character Animator:
<img src="https://trello-attachments.s3.amazonaws.com/583830811dba0b1a3139bbda/585be7f80fc15f84f785111a/581182489b1045310753ba36e4e1c0bc/2.png" alt="mijn afbeelding" title="Adobe Character Animator" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">

Adobe Premiere Pro
<img src="https://trello-attachments.s3.amazonaws.com/583830811dba0b1a3139bbda/585be7f80fc15f84f785111a/f9a3bb8442b6769a7f96ee628a3bde5e/3.png" alt="mijn afbeelding" title="Adobe Premiere Pro" style="width: 125px; height: auto; max-width: 25%; float: right; margin: 4px 0 4px 4px; border: 2px solid red;">


------------------------------------------------------------------------------------------------------------------------------------------

# Aanpak Framer
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
Op Youtube heb je een aantal Framer tutorials die je een stuk verder kunnen helpen, onderstaande video gaat vooral over interacties en transities.

https://www.youtube.com/watch?v=3zaxrXK7Nac

# Conclusie Framer
Op de vraag of het mogelijk is voor ons om een prototype te maken in framer, denk ik dat het antwoord ja is er is genoeg informatie te vinden om het te kunnen leren. Een groter struikelblok zal de tijd zijn die we ervoor hebben. Verder heb ik erg handige functies gevonden die we in ons prototype kunnen gaan gebruiken.

# Extra 
Handige functies - Framerjs.com

Next & Previous — Go back and forth between two screens.<br>
Overlay — Show a new screen from the bottom.<br>
Modal — Show a modal dialog from the center.<br>
Scroll — Scrollable artboard with anchored layers.<br>

# Bronnen
Framer:
- https://material.uplabs.com/benjaminnathan
- https://framerjs.com/gallery/
- youtube.nl
