# Opgave: CSS responsive

Gegeven de Cowboy Henk pagina. We zullen deze stap voor stap responsive maken. Aan de HTML hoef je niks te wijzigen. Zet je media queries in responsive.css; je zult echter ook wel wijzigingen moeten doen in styles.css

## Flexibel maken

Maak het browservenster smaller; je merkt dat de pagina niet flexibel is. Er zijn twee schuldigen:

1. op de `body` is `width: 1200px` ingesteld; verander dit naar `max-width`
2. op de `main` zijn twee vaste kolommen gedefinieerd met `grid-template-columns: 760px 380px;`; verander dit naar twee flexibele kolommen met de `fr` eenheid

Controleer of de pagina nu wel flexibel is. 

## Responsive maken

We werken altijd van smal naar breed toe: gebruik enkel `min-width`, en sorteer breekpunten van klein naar groot

3. maak een eerste breekpunt op 500px; verberg de comments in de post footer, en toon het pas weer vanaf 500px
4. maak een tweede breekpunt op 700px; zet in de footer de buttons en de sociale media pas naast elkaar vanaf 700px
5. maak een derde breekpunt op 9000px; maak pas vanaf die breedte het hoofdmenu horizontaal, en de twee kolommen in de main 

## Uitbreidingen

Maak geen nieuwe breekpunten meer; drie is in bijna alle gevallen meer dan genoeg.

Experimenteer hier en daar met veranderende lettergroottes. Normaal zijn teksten iets groter op mobiel, iets kleiner op tablets en normaal op desktop.  