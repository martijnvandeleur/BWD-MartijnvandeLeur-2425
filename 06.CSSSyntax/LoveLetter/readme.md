# Love Letter

Tip: druk **Ctrl+Shift+V** in VS Code om deze tekst opgemaakt weer te geven.

Tip: de VS Code preview geeft geen achtergrond afbeeldingen weer. Het is voor deze oefening dan ook minder nuttig; je opent de pagina best in de browser.

## A. start CSS

Dit onderdeel gaat over volgende theorie:
* **CSS Course > 01 syntax**: [extern gelinkte stijlen](https://rogiervdl.github.io/CSS-course/01_syntax.html#/extern-gelinkte-stijlen) 
* **CSS Course > 01 syntax**: hoofdstuk [Selectors](https://rogiervdl.github.io/CSS-course/01_syntax.html#/selectors) 
* **CSS Course > 01 syntax**: hoofdstuk [Properties](https://rogiervdl.github.io/CSS-course/01_syntax.html#/properties) 

Opdrachten:
1. maak een submap css aan
1. maak hierin een bestand styles.css aan
2. link het aan de HTML pagina
3. kopieer deze start css:

```
/* deel 1: start CSS */

* {
   margin: 0;
   padding: 0;
}

html {
   background-color: #fff;
}

body {
   border: 10px solid white;
   height: 600px;
   margin: 20px auto;
   max-width: 300px;
   padding: 40px 100px;
}

h1 {
   margin-top: 30px;
}

main {
   padding-top: 30px;
}

mark {
   background-color: transparent;
}

footer {
   margin-top: 35px;
}

/* deel 2: achtergronden */


/* deel 3: lettertypes */


/* deel 4: tekstopmaak */


/* deel 5: schaduwen */


```

## B. achtergronden

Dit onderdeel gaat over volgende theorie:
* **CSS Course > 02 design**: [achtergronden](https://rogiervdl.github.io/CSS-course/02_design.html#/background-images) 

Opdrachten (in styles.css):

1. stel tile.png in als achtergrond van de `html`.
2. stel bg.png in als achtergrond van de `body` en gebruik `background-size` om het over hoogte en breedte uit te rekken

## C. lettertypes

Dit onderdeel gaat over volgende theorie:
* **CSS Course > 02 design**: [gratis fonts](https://rogiervdl.github.io/CSS-course/02_design.html#/gratis-fonts) 
* **CSS Course > 02 design**: [font properties](https://rogiervdl.github.io/CSS-course/02_design.html#/font-family) 

Opdrachten:

1. stel eerst Arial als `font-family` in voor de `body`
2. stel dan een speciaal lettertype in voor de titel in `h1`:
   * surf naar [Google fonts](https://fonts.google.com/)
   * filter linksonder op categorie "Handwriting"
   * scroll door tot het "Caveat" lettertype, en selecteer de medium 500 versie
   * je krijgt rechts een stukje code van volgende vorm: `<link href="https://fonts.googleapis.com/css2?family=xxx:wght@yyy&display=swap" rel="stylesheet">`; kopieer dit naar de `<head>` in index.html
   * je vindt er ook een codefragement over hoe je het moet gebruiken; stel dit lettertype in styles.css in voor de `h1`
3. stel nu met dezelfde methode het lettertype "Indie Flower" in voor de tekst in het midden

## D. tekstopmaak

Dit onderdeel gaat over volgende theorie:
* **CSS Course > 02 design**: [font properties](https://rogiervdl.github.io/CSS-course/02_design.html#/font-family) 

Opdrachten:

1. pas de kleuren (blauwe tekst en rode hartjes), regelhoogtes, hoofdletters, uitlijning, lettergrootte enz... aan tot het er precies uitziet zoals op de screenshot

## E. schaduwen

Dit onderdeel gaat over volgende theorie:
* **CSS Course > 02 design**: [font properties](https://rogiervdl.github.io/CSS-course/02_design.html#/font-family) 
* **CSS Course > 02 design**: [box shadow](https://rogiervdl.github.io/CSS-course/02_design.html#/box-shadow-radius) 

Opdrachten:

1. stel de schaduw in van de "You" teksten
2. stel de schaduw in rondom de brief



