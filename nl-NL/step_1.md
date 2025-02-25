Een functie is een herbruikbaar blok code dat een specifieke taak uitvoert.

Functies verdelen je code in bepaalde taken zodat deze makkelijker te begrijpen is.

Vooral als je taken hebt die meerdere keren moeten worden uitgevoerd. Het zijn een soort hulpmiddelen die je steeds opnieuw kunt gebruiken in verschillende delen van je code.

### Een functie schrijven:

- Begin met het trefwoord `function` om aan te geven dat er een functie wordt aangemaakt.
- Geef je functie een naam (bijv. `optellenGetallen`).
- Plaats haakjes `()` na de functienaam. Dit kunnen parameters (invoer) zijn die jouw functie nodig heeft.
- Gebruik open accolades `{` om het codeblok te definiëren dat de functie zal uitvoeren.
- Sluit de accolades `}` om het einde van de functie aan te geven.

Hier is een voorbeeld:

--- code ---
---
language: js
filename:
line_numbers:
line_number_start:
line_highlights:
---

function optellenGetallen(a, b) {
  return a + b;
}
    
--- /code ---

`optellenGetallen` is hier een functie die twee invoeren `a` en `b` neemt en hun som retourneert.

### Een functie gebruiken:

Je gebruikt een functie door deze **aan te roepen**.

Hier wordt de functie `optellenGetallen()` aangeroepen met de waarden 5 en 8.

Het retourneert de som van de getallen, die je vervolgens kunt gebruiken. In dit voorbeeld wordt de som van 5 en 8 toegewezen aan de variabele `resultaat` en vervolgens wordt `resultaat` weergegeven in de console.

--- code ---
---
language: js
filename:
line_numbers: 
line_number_start:
line_highlights:
---

let resultaat = optellenGetallen(5, 8);
console.log(resultaat); // Uitvoer: 13
    
--- /code ---
