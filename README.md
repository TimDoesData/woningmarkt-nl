Case Study: Woningmarkt in Nederland
De Context
Dit project biedt een interactief inzicht in de dynamiek van de Nederlandse woningmarkt. Het dashboard is ontworpen om antwoord te geven op actuele ruimtelijke vraagstukken: Wat zijn de langetermijntrends in verkoopprijzen? Hoe verhoudt de huur- en koopmarkt zich tot elkaar? En in hoeverre zien we deze landelijke trends terug op provinciaal en gemeentelijk niveau, of is er sprake van sterke regionale spreiding?

De Aanpak
De basis van dit dashboard wordt gevormd door open data van CBS StatLine, specifiek gericht op gemiddelde verkoopprijzen, woningtypen en de actuele woningvoorraad. In de voorbereidende fase is SQL ingezet voor data-extractie, het opschonen van de ruwe data en het samenvoegen van de bestanden. Vervolgens is het datamodel in PowerBI opgebouwd. Om de data geografisch en in de tijd inzichtelijk te maken, heb ik de gemeentecodes gekoppeld aan regio-namen en diverse DAX-measures geschreven (zoals SUM, Last Year (LY) en Year-over-Year (YoY) %).

De Inzichten
Uit de analyse komen enkele duidelijke trends naar voren:

Aanbod vs. Prijs: Landelijk zien we een gestage groei van de woningvoorraad. Dit staat echter in schril contrast met de explosieve stijging van de gemiddelde verkoopprijzen sinds 2017, met een absolute piek in 2021 (een YoY stijging van maar liefst 15%).

Regionale Spreiding: Hoewel de prijsstijging over de hele linie zichtbaar is, liggen de absolute bedragen ver uit elkaar. In de Randstad overstijgt de gemiddelde verkoopprijs in 2024 de grens van €500.000, terwijl provincies als Limburg, Zeeland, Groningen en Friesland nog onder de €400.000 blijven.

Opvallende uitschieters: Waar de prijzen blijven stijgen, is de nieuwbouw de afgelopen twee jaar juist licht afgenomen. Een interessante afwijking is te zien op de geografische kaart bij Zuid-Holland: hoewel de provincie qua gemiddelde verkoopprijs in de landelijke middenmoot valt, behoort deze wel tot de absolute koplopers op het gebied van nieuwbouwprojecten.
