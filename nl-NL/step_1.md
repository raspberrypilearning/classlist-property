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

- Access classList:
  `element.classList` returns a list of the class attributes of the element.

- Add a class:
  `classList.add("className")` adds the specified class to the element. Als de klasse al bestaat, wordt deze genegeerd.

- Remove a class:
  `classList.remove("className")` removes the specified class from the element.

- Toggle a class:
  `classList.toggle("className")` toggles the presence of the specified class. Als de klasse aanwezig is, wordt deze verwijderd; anders wordt deze toegevoegd.

- Check if a class exists:
  `classList.contains("className")` returns a Boolean (true/false) showing whether the specified class is present on the element.

- Replace classes:
  `classList.replace("oldClass", "newClass")` replaces the specified old class with a new one.
