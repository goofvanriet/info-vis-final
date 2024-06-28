![](./static/images/banner.png?)

[Klik hier om naar de data story te gaan](../notebooks/story.ipynb)

# Information Visualisation: Welvaart, Uitstoot en Duurzaamheid

Jupyter Book die verschillende correlaties mbt uitstoot welvaart en duurzaamheid.
[Dataset and preprocessing](./docs/dataset-preprocessing.md) page.

# Inhoudsopgave

- [Information Visualisation: Welvaart, Uitstoot & Verduurzaming](#information-visualisation-welvaart,-uitstoot-en-duurzaamheid)
- [Inhoudsopgave](#inhoudsopgave)
- [Aan de slag](#aan-de-slag)
- [Structuur](#structuur)
- [Gebruik](#gebruik)
- [Implementeren](#implementeren)
- [Dataset schoonmaakscripts](#dataset-schoonmaakscripts)
- [Auteurs](#auteurs)

# Aan de slag

```
git clone git@github.com:goofvanriet/info-vis-final.git
cd info-vis-final
pip3 install -r requirements.txt
```

Installeer daarnaast `conda` om een lokale omgeving op te zetten.
- [MacOS installation instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)
- [Windows installation instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html)
- [Linux installation instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)

Mocht je `jupyter` niet lokaal geïnstalleerd hebben, voer dan eenvoudigweg `pip3 install jupyter` uit.

# Structuur

```
.
├── LICENSE # Code licentie
├── README.md # Algemene projectinformatie en instructies
├── _build # Jupyter build die geïmplementeerd zal worden
├── _config.yml # Jupyter configuratiebestand
├── _toc.yml # Jupyter Inhoudsopgave configuratiebestand
├── data # Bevat dataset inclusief schoonmaakscripts
├── docs # Bestanden die gepubliceerd worden op GitHub Pages
├── notebooks # Bevat alle notebook grafieken die gebruikt worden voor de data story
├── requirements.txt # Projectafhankelijkheden
├── scripts # Aanvullende scripts gebruikt voor implementatie of schoonmaak
└── static # Afbeeldingen, css en js bestanden die gepubliceerd worden op GitHub Pages
```

# Gebruik

Voer 'jupyter notebook' uit in de hoofdmap van deze repository. Alle notebooks die bijdragen aan het verhaal moeten worden aangemaakt binnen de 'notebooks' directory. Om een onderhoudsarme en flexibele structuur te behouden, maak één notebook per grafiek.

Het hoofdnotebook voor het verhaal is './notebooks/story.ipynb'. Tussen de teksten kun je de resultaten van andere grafieken opnemen door simpelweg een nieuwe code-cel toe te voegen met de volgende inhoud '%run example_plot.ipynb'. Alleen het resultaat van de laatste cel binnen 'example_plot.ipynb' zal worden weergegeven.

# Deploy

Om naar GitHub Pages te implementeren, kunt u het volgende commando uitvoeren in een terminal: './scripts/deploy.sh'. Hiermee wordt het project gebouwd, worden de notebooks toegevoegd en wordt metadata toegevoegd aan 'story.ipynb' om de invoercellen te verbergen.

# Auteurs
- Anou Prins: 13427644
- Efehan Kuznek: 14012847
- Tom Kuin: 13186280
- Goof van Riet: 14715988
