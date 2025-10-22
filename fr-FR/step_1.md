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

- Accéder à classList :
  `element.classList` renvoie une liste des attributs de classe de l'élément.

- Ajouter une classe :
  `classList.add("className")` ajoute la classe spécifiée à l'élément. Si la classe existe déjà, elle est ignorée.

- Supprimer une classe :
  `classList.remove("className")` supprime la classe spécifiée de l'élément.

- Activer/désactiver une classe :
  `classList.toggle("className")` active/désactive la présence de la classe spécifiée. Si la classe est présente, elle est supprimée ; sinon, elle est ajoutée.

- Vérifier si une classe existe :
  `classList.contains("className")` renvoie un booléen (vrai/faux) indiquant si la classe spécifiée est présente sur l'élément.

- Remplacer des classes :
  `classList.replace("oldClass", "newClass")` remplace l'ancienne classe spécifiée par une nouvelle.
