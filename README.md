# Portfolio
Project: Portfolio
Cursus: DSFB2
Docenten: Bas van Gestel, Chris van Oevelen, René van der Ploeg en Michael Liem

PROJECTSTRUCTUUR

De projectmap is als volgt georganiseerd (zie ook 04-data-management.Rmd):

bookdown_portfolio/
│
├── 01-CV.Rmd
├── 02-future-goals.Rmd
├── 03-vrijeopdr.Rmd
├── 04-data-management.Rmd
├── 05-reproducible-science.Rmd
├── 06-R-package.Rmd
├── 07-bronvermelding.Rmd
│
├── images/
│   ├── dir_tree_opdr3a.png
│   ├── portfolio_dirtree2.png
│   ├── profielfoto.jpg
│   └── README_screenshot_opdr3a.png
│
├── index.Rmd
├── packages.bib
├── bookdown.Rproj
├── _bookdown.yml
├── _output.yml
└── _book/

INHOUD VAN HET PORTFOLIO

Het portfolio bestaat uit de volgende onderdelen:

01-CV.Rmd -)                   Curriculum vitae
02-future-goals.Rmd -)         toekomstige doelen en ambities
03-vrijeopdr.Rmd -)            Vrije opdracht
04-data-management.Rmd -)      Opdracht over datamanagement
05-reproducible-science.Rmd -) Opdracht over reproduceerbare wetenschap
06-R-package.Rmd -)            Opdracht over R-packages
07-bronvermelding.Rmd -)       Bronnen en literatuur

BESTANDSBESCHRIJVINGEN

R Markdown-bestanden (.Rmd): bevatten de hoofdstukken en inhoud van het portfolio.
index.Rmd: bevat de introductie en vormt het startpunt van het Bookdown-project.
images/: bevat afbeeldingen die in het portfolio worden gebruikt.
packages.bib: bevat bibliografische referenties.
_bookdown.yml: bevat de configuratie en volgorde van de hoofdstukken.
_output.yml: bevat de instellingen voor de uitvoer van het boek.
bookdown.Rproj: het RStudio-projectbestand.
_book/: bevat de gegenereerde HTML-versie van het portfolio.

HET PORTFOLIO RENDEREN

Het project kan worden geopend in RStudio door bookdown.Rproj te openen.
Om het volledige portfolio opnieuw te genereren, gebruik je in de R-console: bookdown::render_book()
Bookdown genereert vervolgens de HTML-bestanden in de map _book/.

GEBRUIKTE TECHNOLOGIEN

- R
- RStudio
- R Markdown
- Bookdown
- Git (voor versiebeheer)
- Auteur

Dit portfolio is gemaakt als onderdeel van de cursus Biology 2.

