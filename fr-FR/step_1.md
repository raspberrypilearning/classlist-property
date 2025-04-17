La propriété `classList` en JavaScript est utilisée pour ajouter, supprimer, activer/désactiver et vérifier la présence de classes CSS sur un élément.

## --- code ---

language: js
filename: script.js
line_numbers: false
line_highlights: 5
-------------------------------------------------------

// Fonction Light Mode
function changeLightMode(){
var isLightMode = lightModeSwitch.checked;
document.body.classList.toggle("light-mode");
}

\--- /code ---

Voici quelques-unes des méthodes qui peuvent être utilisées avec la propriété `classList`.

- Access classList:
  `element.classList` returns a list of the class attributes of the element.

- Add a class:
  `classList.add("className")` adds the specified class to the element. Si la classe existe déjà, elle est ignorée.

- Remove a class:
  `classList.remove("className")` removes the specified class from the element.

- Toggle a class:
  `classList.toggle("className")` toggles the presence of the specified class. Si la classe est présente, elle est supprimée ; sinon, elle est ajoutée.

- Check if a class exists:
  `classList.contains("className")` returns a Boolean (true/false) showing whether the specified class is present on the element.

- Replace classes:
  `classList.replace("oldClass", "newClass")` replaces the specified old class with a new one.
