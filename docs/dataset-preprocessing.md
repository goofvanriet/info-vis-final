# Datasets en Voorbewerking

Bij de start van dit project hebben we het onderwerp geselecteerd om gerichter te kunnen zoeken naar relevante datasets. Na het vaststellen van ons onderwerp hebben we een uitgebreide zoektocht uitgevoerd naar datasets die waardevolle gegevens bevatten voor onze analyse. Tijdens een teamvergadering hebben we deze datasets uitvoerig besproken en onderzocht op mogelijke correlaties tussen de verschillende databronnen. Dit proces hielp ons om het verhaal vanuit twee verschillende perspectieven steeds verder aan te scherpen. Uiteindelijk hebben we besloten om vijf datasets te gebruiken: vier afkomstig van [Our World in Data](https://ourworldindata.org/) en één van [Human Developments Reports](https://hdr.undp.org/). Door het combineren van deze data konden we interessante correlaties visualiseren die ondersteunend waren voor beide invalshoeken van ons verhaal. Na diverse overleggen en brainstormsessies hebben we ons verdiept in de relatie tussen de welvaart van landen en trends in CO2-uitstoot, waarbij we specifiek keken naar hoe de variabelen uit onze gekozen datasets beide verhaallijnen konden ondersteunen.

## Schoonmaak

In dit project hebben we een grondige data schoonmaak uitgevoerd om ervoor te zorgen dat onze visualisaties betrouwbaar zijn. Allereerst hebben we de relevante kolommen uit de verschillende datasets geselecteerd en deze samengevoegd in een nieuwe dataset. Dit was nodig om een duidelijk overzicht te krijgen van de belangrijkste informatie die we nodig hebben.

Daarnaast hebben we meerdere subsets van de relevante data gemaakt, elk met specifieke kolommen die relevant zijn voor bepaalde visualisaties. Dit hielp ons om gericht te werken aan specifieke visualisaties en zorgde ervoor dat de analyse efficiënter verliep.

Een belangrijk onderdeel van de data schoonmaak was het omgaan met missende waarden. We hebben zorgvuldig gekeken naar de relevantie van de rijen met missende waarden. Als een rij belangrijke informatie bevatte die niet genegeerd kon worden, zochten we naar manieren om de missende waarden op te vullen of gebruikten we alternatieve methoden voor de analyse.

Verder hebben we het percentage missende waarden in elke kolom geanalyseerd. Voor kolommen met een hoog percentage missende waarden overwogen we om deze kolommen te verwijderen, vooral als ze niet cruciaal waren. Voor kolommen met een laag percentage missende waarden gebruikten we technieken zoals het invullen van missende waarden met gemiddelde of mediaanwaarden.

Uiteindelijk zijn alle datasets die worden gebruikt voor de visualisaties van het type CSV. Dit komt deels doordat de meeste datasets die we van het internet hebben gedownload al in CSV-formaat waren. Daarnaast is het CSV-formaat gekozen vanwege de eenvoud en leesbaarheid. Het totaal van 107 kolommen over 5 datasets is gereduceerd naar een totaal van 25 kolommen over 8 datasets.


## Variabelen beschrijving

De variabelen die gebruikt worden in dit project zijn hieronder overzichtelijk weergeven met de bijbehorende variabeletype en meetniveau.

- Continue / Ratio variabelen: `Bioenergy levelized cost of energy`, `Geothermal levelized cost of energy`, `Offshore wind levelized cost of energy`, `Solar photovoltaic levelized cost of energy`, `Concentrated solar power levelized cost of energy`, `Hydropower levelized cost of energy`, `Onshore wind levelized cost of energy`, `Annual CO₂ emissions (per capita)`, `Population`, `CO2`, `CO2 per capita`, `GDP`, `GDP per capita`, `HDI`, `Life expectancy`, `Renewable Energy voor World`, `Annual CO₂ emissions from other industry`, `Annual CO₂ emissions from flaring`, `Annual CO₂ emissions from cement`, `Annual CO₂ emissions from gas`, `Annual CO₂ emissions from oil`, `Annual CO₂ emissions from coal`

- Discrete / Nominale variabelen: `Code`, `Country`

- Discrete / Interval variabelen: `Year`
