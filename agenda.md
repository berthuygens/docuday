# **Intranet & Docu 2.0**

**Datum:** 13 januari 2025  
**Tijd:** 09:30 \- 16:30  
**Locatie:** \[Belpaire \- 05.N.09\]


---

## Agenda

### Ontvangst en Korte Introductie (09:30 – 09:45)

* **Welkom** en introductie van de dag.  
* **Doelstellingen:**  
  * Verbeteren van de intranetstructuur en documentatie. 
  * Implementeren van een Markdown-structuur met versiebeheer.

### Evaluatie van Huidige IT-Documentatie (09:45 – 10:30)

* **Inventarisatie:** Huidige intranet pagina's , handleidingen en richtlijnen.  
* **Discussiepunten:**  
  * Wat werkt goed?  
  * Waar zijn verbeteringen nodig?  

###  Pauze (10:30 – 11:00)

###  Introductie tot Markdown en versiebeheer (11:00 – 12:30)

* **Demonstratie:**  
  * Markdown-syntax   
  * Werken met Git: repositories, branches en commits.   
  * Demo materials MkDocs site   
* **Praktijkoefening:**  
  Converteer een voorbeeldhandleiding naar Markdown.

###  Lunchpauze (12:30 – 13:30)

###  Hands-On: Documentatie structureren (13:30 – 14:30)

* **Opzetten:** Een hiërarchie voor Markdown-documenten.  
* **Verdeling:** Wie doet wat?


###  Intranet Integratie (14:45 – 16:15)

* **Toepassing:** Markdown-documenten in het intranet.  
* **Automatisering:** CI/CD voor documentatie via GitHub.

###  Afsluiting (16:15 – 16:30)

* **Follow-up acties:**  
  * Implementatieplan.  
  * Toewijzen van beheerders voor de Markdown-structuur.  
* **Vragen:** Open discussie en afsluiting.


## Evaluatie van Huidige IT-Documentatie

### Discussiepunten

👎 Momenteel is het intranet een samenraapsel van google site pagina's en google drive documenten met vaak (heel) korte inhoud. Die al dan niet naar elkaar doorverwijzen , je bent al heel gauw het overzicht kwijt. Er is bovenaan wel een menu dat je kan gebruiken , maar niet echt user friendly.  

👎 De opmaak verschilt ook vaak van pagina tot pagina.


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
| Link            | [title](https://www.example.com)       |
| Image           | ![alt text](image.jpg)                 |

[Probeer zelf met deze tutorial ](https://tylingsoft.github.io/tutorial.md/#whats-markdown)

### Werken met GIT