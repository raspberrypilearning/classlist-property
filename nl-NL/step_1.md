De eigenschap `classList` in JavaScript wordt gebruikt om CSS-klassen aan een element toe te voegen, te verwijderen, in of uit te schakelen en de aanwezigheid ervan te controleren.

## --- code ---

language: js
filename: script.js
line_numbers: false
line_highlights: 5
-------------------------------------------------------

// Light mode functie
function changeLightMode(){
var isLightMode = lightModeSwitch.checked;
document.body.classList.toggle("light-mode");
}

\--- /code ---

Dit zijn enkele methoden die kunnen worden gebruikt met de eigenschap `classList`.

- Toegang tot classList:
  `element.classList` retourneert een lijst met de klassen kenmerken van het element.

- Een klasse toevoegen:
  `classList.add("className")` voegt de opgegeven klasse toe aan het element. Als de klasse al bestaat, wordt deze genegeerd.

- Een klasse verwijderen:
  `classList.remove("className")` verwijdert de opgegeven klasse uit het element.

- Een klasse in- of uitschakelen:
  `classList.toggle("className")` schakelt de aanwezigheid van de opgegeven klasse in of uit. Als de klasse aanwezig is, wordt deze verwijderd; anders wordt deze toegevoegd.

- Controleren of een klasse bestaat:
  `classList.contains("className")` retourneert een Booleaanse waarde (true/false) die aangeeft of de opgegeven klasse aanwezig is in het element.

- Een klasse vervangen: `element.classList.replace("oldClass", "newClass")` vervangt de opgegeven oude klasse door een nieuwe.