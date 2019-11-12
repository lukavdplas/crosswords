# Joepieee Github Pages!

Todo:

### 1. Github Pages
Zet de Github Pages-feature aan voor deze pagina met [deze gids](https://pages.github.com/). Onderaan de gids staan tips over Jekyll blogs (ga je niet gebruiken maar is heel cool), CNAME (ga je gebruiken als je een domeinnaam hebt gekocht) en meer.

Het idee van Github Pages is dat er een webserver aan staat die precies jouw bestanden geeft. Normaal kan je naar `github.com/lukavplas/crossword-viewer/index.html` gaan, en dan krijg je een html-bestand waar de inhoud van `index.html` staat, maar ingepakt in de Github UI. Je kan dan op 'Raw view' klikken, en dan krijg je wel gewoon `index.html`, maar met wat truukjes om ervoor te zorgen dat het als tekstbestand wordt gezien door een browser, niet als html-webpagina.

Met github pages krijgt elk bestand ook een weblink: `lukavdplas.github.io/crossword-viewer/index.html`. Deze link geeft het originele bestand, en wordt dus door je webbrowser als een normale website beschouwd. 

### 2. Open source license
Open source software op de interwebs heeft een 'license' nodig: [link 1](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/licensing-a-repository) en [link 2](https://choosealicense.com/). Ik vind dat de MIT license goed bij mijn wereldbeeld en bij mijn projectjes past.

### 3. Website maken!
Open op je eigen computer `index.html` in chrome/firefox en in atom. Telkens als je iets verandert refresh je chrome om je nieuwe website te zien (dit kan ook automatisch). Superhandig zijn de developer tools van chrome, met oa de javascript console.

Er zit een gestripte versie van de printi homepage in `index.html` die een XML-bestand uit de `crosswords/` map inlaadt en print.
Ik heb css code soms in een element geschreven en soms bovenaan de pagina, dat is natuurlijk nogal vies. mi scusi

Voor javascript: denk eraan dat je vaak _event-driven_ werkt: je geeft bv een knop functionaliteit door een functie te schrijven die bij `button.onClick` ofzo wordt opgeroepen. Idem met XML bestanden opvragen. 