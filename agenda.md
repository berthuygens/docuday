# **Intranet & Docu 2.0**

**Datum:** 13 januari 2025  
**Tijd:** 09:30 \- 16:30  
**Locatie:** \[Belpaire \- 05.N.09\]

---

## Table of Contents

- [Agenda](#agenda)
- [Evaluatie van huidige IT-documentatie](#evaluatie-van-huidige-it-documentatie)
- [Introductie tot markdown en versiebeheer](#introductie-tot-markdown-en-versiebeheer)
- [Hands-on: documentatie structureren](#hands-on-documentatie-structureren)
- [Intranet integratie](#intranet-integratie)

---

## Agenda

### Ontvangst en Korte Introductie (09:30 – 09:45)

* **Welkom** en introductie van de dag.  
* **Doelstellingen:**  
  * Verbeteren van de intranetstructuur en documentatie. 
  * Implementeren van een Markdown-structuur met versiebeheer.

### Evaluatie van huidige IT-documentatie (09:45 – 10:30)

* **Inventarisatie:** Huidige intranet pagina's , handleidingen en richtlijnen.  
* **Discussiepunten:**  
  * Wat werkt goed?  
  * Waar zijn verbeteringen nodig?  

###  Pauze (10:30 – 11:00)

###  Introductie tot markdown en versiebeheer (11:00 – 12:30)

* **Demonstratie:**  
  * Markdown-syntax   
  * Werken met Git: repositories, branches en commits.   
  * Demo materials MkDocs site   

###  Lunchpauze (12:30 – 13:30)

###  Hands-on: documentatie structureren (13:30 – 14:30)

* **Opzetten:** Een hiërarchie voor Markdown-documenten.  
* **Verdeling:** Wie doet wat?
* **Praktijkoefening:** Converteer een voorbeeldhandleiding naar Markdown.


###  Intranet integratie (14:45 – 16:15)

* **Toepassing:** Markdown-documenten in het intranet.  
* **Automatisering:** Demo CI/CD voor documentatie via GitHub.

###  Afsluiting (16:15 – 16:30)

* **Follow-up acties:**  
  * Implementatieplan.  
  * Toewijzen van beheerders voor de Markdown-structuur.  
* **Vragen:** Open discussie en afsluiting.


## Evaluatie van Huidige IT-Documentatie

### Discussiepunten

👎 Momenteel is het intranet een samenraapsel van google site pagina's en google drive documenten met vaak (heel) korte inhoud. Die al dan niet naar elkaar doorverwijzen , je bent al heel gauw het overzicht kwijt. Er is bovenaan wel een menu dat je kan gebruiken , maar niet echt user friendly.  

👎 De opmaak verschilt ook vaak van pagina tot pagina.

👎 Er is geen versiebeheer


## Introductie tot Markdown en Versiebeheer

### Waarom Markdown

1. **Eenvoudige en intuïtieve syntaxis:** Markdown is makkelijk te leren en te gebruiken. Het gebruikt eenvoudige, leesbare tekst voor opmaak, zoals:
    - `#` voor koppen
    - `*` voor opsommingen

    Hierdoor is het toegankelijk voor zowel beginners als gevorderden.


2. **Platformonafhankelijk:** Markdown-bestanden kunnen in vrijwel elke teksteditor worden gemaakt en bewerkt. Ze:
    - Zijn niet gebonden aan specifieke software.
    - Kunnen eenvoudig worden geëxporteerd naar andere formaten zoals HTML, PDF of Word.


3. **Ondersteuning door vele tools en platforms:**  Markdown wordt breed ondersteund door:
    - Blogs
    - Contentmanagementsystemen
    - Programmeertalen
    - Samenwerkingsplatformen zoals GitHub, Jupyter Notebooks, en Slack  

    Dit maakt het ideaal voor diverse toepassingen, van documentatie tot presentatie.


4. **Focus op inhoud, niet op opmaak**

    Omdat Markdown een eenvoudige tekstindeling is, kun je je concentreren op de inhoud, zonder afgeleid te worden door uitgebreide opmaakopties of complexe tekstverwerkers.
 

5. **Klein en lichtgewicht**
  Markdown-bestanden zijn:
    - Pure tekstbestanden
    - Klein van formaat
    - Snel te verwerken
  
6. **Ideaal voor versiebeheer**

    Al deze eigenschappen maakt markdown uiterst geschik voor het gebruik van versiebeheer (bv GIT) Het gebruik van `GIT` zorgt dat we onze documentatie en intranetpgaina's makkelijker samen kunnen beheren en zelfs (in de toekomst) beroep kunnen doen op alle collega's van het INBO. 
    
    Het is screwup-proof en kan van overal snel aangepast worden.  Er is ook een goede traceerbaarheid. Algemeen nodigt het uit tot een **actiever** beheer van documentatie.  


### Markdown syntax

Er zijn veel online cheat sheets https://www.markdownguide.org/cheat-sheet/ 

Meest basic syntax:

| Element         | Markdown Syntax                        |
|-----------------|----------------------------------------|
| Heading         | # H1                                   |
|                 | ## H2                                  |
|                 | ### H3                                 |
| Bold            |`**bold text**`                         |
| Italic          |`*italicized text*`                     |
| Blockquote      | > blockquote                           |
| Ordered List    | 1. First item                          |
|                 | 2. Second item                         |
|                 | 3. Third item                          |
| Unordered List  | - First item                           |
|                 | - Second item                          |
|                 | - Third item                           |
| Code            | ``` `code` ```                         |
| Horizontal Rule | ---                                    |
| Newline         | min 2 spaces at end of line            |
| Link            | [title](https://www.example.com)       |
| Image           | ![alt text](martijn.png)                 |

[Probeer zelf met deze tutorial ](https://tylingsoft.github.io/tutorial.md/#whats-markdown)

### Waarom GIT ?
Git is algemeen bekend als een krachtig hulpmiddel voor ontwikkelaars om code te beheren, wijzigingen bij te houden en samen te werken aan softwareprojecten. Niet-ontwikkelaars, kunnen ook aanzienlijk profiteren van het gebruik van Git. We denken dan in de eerste plaats aan het bijhouden van documentatie of het opvolgen van projecten.

VDoor Git te gebruiken voor documentatie, kunnen we als team een versiegeschiedenis van wijzigingen bijhouden, waardoor het eenvoudig is om te zien hoe documenten in de loop van de tijd zijn geëvolueerd en indien nodig terug te keren naar eerdere versies.

De collega's van BMK hebben enkele duideljke [tutorials]( https://tutorials.inbo.be/search/?q=git) gemaakt!  
Goede basis uitleg op [Youtube ](https://www.youtube.com/watch?v=eLmpKKaQL54)   
[Tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) Voor beginners  

---
### Nieuwe site op basis van markdown docs.

Er is een nieuwe [intranetsite](https://inbo.github.io/ict-intranet/) aangemaakt, die de kracht van markdown wil aantonen .  In combinatie met een statische html generator (Hugo, Mkdocs..)kunnen we heel snel met onze markdown documenten een intranet site opbouwen. Maar evengoed ook een chatbot , of een mobiele app. Daar zit net de kracht van markdown documenten.

## Hands-on: documentatie structureren

Een hiërarchie voor Markdown-documenten.
* **Verdeling:** Wie doet wat?


* **Praktijkoefening:** Converteer een voorbeeldhandleiding naar Markdown.

## Intranet integratie

 Continuous integration en continuous deployment (CI/CD) zijn onmisbare praktijken geworden om efficiënt software van hoge kwaliteit te leveren. Met CI/CD kunnen developers het proces van bouwen, testen en deployen van codewijzigingen automatiseren, het risico op menselijke fouten verkleinen en snellere iteraties mogelijk maken.  Maar we kunnen dit ook gebruiken om onze documentatie op een verstandige manier te gaan beheren en deployen.   

Een kleine demo...  