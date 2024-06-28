# Datasets en Voorbewerking

Bij de start van dit project hebben we een specifiek onderwerp gekozen om gerichter te kunnen zoeken naar relevante datasets. Na het vaststellen van ons onderwerp voerden we een uitgebreide zoektocht uit naar datasets die waardevolle gegevens bevatten voor onze analyse. Tijdens een teamvergadering hebben we deze datasets grondig besproken en onderzocht op mogelijke correlaties. Dit proces stelde ons in staat het verhaal, dat vanuit twee verschillende perspectieven moet worden gepresenteerd, verder te verfijnen. Uiteindelijk besloten we vijf datasets te gebruiken: vier afkomstig van [Our World in Data](https://ourworldindata.org/) en één van de [Human Developments Reports](https://hdr.undp.org/). Door deze data te combineren, konden we interessante correlaties visualiseren die ondersteunend waren voor beide invalshoeken van ons verhaal. Na diverse overleggen en brainstormsessies verdiepten we ons in de relatie tussen de welvaart van landen en trends in CO2-uitstoot, waarbij we specifiek keken naar hoe de variabelen uit onze gekozen datasets beide verhaallijnen konden ondersteunen.

## Schoonmaak

In dit project hebben we een grondige data-schoonmaak uitgevoerd om de betrouwbaarheid van onze visualisaties te waarborgen. Allereerst selecteerden we de relevante kolommen uit verschillende datasets en voegden deze samen tot een nieuwe dataset. Dit was essentieel om een helder overzicht te krijgen van de cruciale informatie die nodig was. Daarnaast creëerden we meerdere subsets van de relevante data, elk toegespitst op specifieke kolommen die van belang zijn voor bepaalde visualisaties. Dit hielp ons om doelgericht te werken aan specifieke visualisaties en bevorderde de efficiëntie van onze analyses.

Een belangrijk aspect van de data-schoonmaak was het adresseren van ontbrekende waarden. Indien een rij cruciale informatie bevatte die niet over het hoofd kon worden gezien, zochten we naar manieren om deze ontbrekende waarden aan te vullen of pasten alternatieve analytische methoden toe. Verder analyseerden we het percentage ontbrekende waarden per kolom. Bij kolommen met een hoog percentage ontbrekende waarden overwogen we verwijdering, vooral als deze niet essentieel waren. Voor kolommen met een laag percentage ontbrekende waarden pasten we technieken toe zoals het invullen van waarden met het gemiddelde of de mediaan.

Voor de datasets hebben we voor het CSV-formaat gekozen vanwege de eenvoud en leesbaarheid. In totaal is het aantal kolommen van 107 uit vijf datasets gereduceerd naar 25 kolommen over acht datasets.


## Variabelen beschrijving

De variabelen die gebruikt worden in dit project zijn hieronder overzichtelijk weergeven met de bijbehorende variabeletype en meetniveau.

- Continue / Ratio variabelen: `Bioenergy levelized cost of energy`, `Geothermal levelized cost of energy`, `Offshore wind levelized cost of energy`, `Solar photovoltaic levelized cost of energy`, `Concentrated solar power levelized cost of energy`, `Hydropower levelized cost of energy`, `Onshore wind levelized cost of energy`, `Annual CO₂ emissions (per capita)`, `Population`, `CO2`, `CO2 per capita`, `GDP`, `GDP per capita`, `HDI`, `Life expectancy`, `Renewable Energy voor World`, `Annual CO₂ emissions from other industry`, `Annual CO₂ emissions from flaring`, `Annual CO₂ emissions from cement`, `Annual CO₂ emissions from gas`, `Annual CO₂ emissions from oil`, `Annual CO₂ emissions from coal`

- Discrete / Nominale variabelen: `Code`, `Country`

- Discrete / Interval variabelen: `Year`


## Aggregaties

Er zijn in het proces alleen nieuwe variabelen ontstaan uit berekeningen door bepaalde variabelen relatief te maken. Dit waren simpele berekeningen waarbij de oorsponkelijke waarden van variabelen gedeeld werden door de populatie van een land. De ontstane variabelen zorgden voor relevantere waarden die nodig waren voor het opstellen van de visualisaties.
