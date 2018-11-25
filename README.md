Onderwerp:
- Bodemdegradatie; door verandering in landgebruik.
  Specifiek kijkend naar wat ontbossing en een verandering in de landbouwmethode met de bodemkwaliteit doet. 
  Bodemdegradatie is het fenomeen waarin de kwaliteit van de bodem daalt door erosie, verdroging, verzilting of uitputting van nutrienten.
  Er bestaat een verschil tussen chemische en fysische bodemdegradatie. Chemische degradatie betekend een verslechtering in de chemische
  eigenschappen van de bodem, denk aan verzuring, verzilting en afname van nutrienten. Met fysische degradatie wordt de fysische staat van 
  de bodem aangetast, bijvoorbeeld structuur verlies wat leidt tot erosie.
    
 Doel:
 - Als gevolg van de ontwikkelingen in de landbouw en de voedselvoorziening komt het natuurlijk systeem onder steeds hogere druk te staan.
   Dit leidt tot een onbalans tussen de potenties van het natuurlijk systeem op het gebied van voedsel- en biomassaproductie en de mate 
   waarin dit systeem kan meeveren en zich nog kan herstellen. Voor het behoud en herstel van de balans tussen het natuurlijk systeem en 
   de vraag vanuit de maatschappij op gebied van landbouw en voedsel blijft nieuwe kennis over de bodem en de ondergrond nodig.
   Het doel van dit project is een stukje bewustwording creëeren over het belang van goede bodemkwaliteit en welke processen dit 
   aantasten. Een visualisatie maakt dit onderwerp ook toegankelijk voor mensen zonder voorkennis.   
  
Visualisatie:
- Een kaart dat de mate van bodemdegradatie laat zien aan de hand van kleuren, groen is weinig - rood is veel. Welk werelddeel het wordt 
  hangt nog een beetje af van de data. 
  Het idee is dat je kan klikken op een land, waarna een grafiek te voorschijn komt met daarin gegevens over de verandering in landgebruik.
  Door middel van deze gegevens wordt duidelijk hoe bepaalde landtypen (bossen, agrarisch, steden) zich hebben ontwikkeld over de jaren. 
  Om de visualisatie dynamischer te maken wordt er ook een tijdspan geimplementeerd bij de basis kaart over bodemdegradatie. Hierin wordt
  dan duidelijk dat bijvoorbeeld ontbossing meer degradatie veroorzaakt. 
  Eerst ga ik focussen op ontbossing en landbouw, daarna zou ik eventueel nog naar waterontrekking kunnen kijken.
- Main features (MVP): klik op een land en grafiek komt tevoorschijn, switchen tussen verschillende jaren, het jaar wordt dat gehighlight
  in de grafiek.
  Optional features: wateruitputting toevoegen.

Moeilijkheid:
De uitdaging in mijn project zit hem voornamelijk in het vinden van data. 
Waarom dit niet met GIS doen? Omdat ik per land een overzicht wil laten zien, wat de veranderingen zijn in landgebruik (dus afnamen/toename  van bossen, agrarisch land etc). En hoe dit de bodemkwaliteit beinvloed... DUNNO

Data sources: <br />
[https://data.oecd.org](https://data.oecd.org)
[https://data.worldbank.org/indicator/AG.LND.AGRI.ZS](https://data.worldbank.org/indicator/AG.LND.AGRI.ZS)
[http://www.fao.org/home/en/](http://www.fao.org/home/en/)
[https://ec.europa.eu/eurostat](https://ec.europa.eu/eurostat)
De data kan in CSV format gedownload worden, misschien dat het beter werkt met een JSON. Maar verder hoeft er niet veel veranderd 
te worden. 

External Components:
- D3-tip
- DataMap
- Topojson

Similar Visualisation:
[https://www.globalforestwatch.org/map](https://www.globalforestwatch.org/map)

