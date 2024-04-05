The `classList` property in JavaScript is used to interact with the class attributes of an HTML element. It provides a set of functions for adding, removing, toggling, and checking the presence of CSS classes on an element. 

For example, you can toggle the class on an HTML element to add it if it is not present and remove if it is already present.

--- code ---
---
language: js
filename: script.js
line_numbers: false
line_highlights: 5
---
   
   // Light mode function 
  function changeLightMode(){
      var isLightMode = lightModeToggle.checked;

      document.body.classList.toggle("light-mode", isLightMode);

  }

--- /code ---


These are some of the functions and how the `classList` property works:

+ Accessing classList:
`element.classList` returns a list representing the class attribute of the specified element.

+ Adding a Class:
`classList.add("className")` adds the specified class to the element. If the class already exists, it is ignored.

+ Removing a Class:
`classList.remove("className")` removes the specified class from the element.

+ Toggling a Class:
`classList.toggle("className")` toggles the presence of the specified class. If the class is present, it is removed; otherwise, it is added.

+ Checking if a Class Exists:
`classList.contains("className")` returns a Boolean confirming whether the specified class is present on the element.

+ Replacing Classes:
`classList.replace("oldClass", "newClass")` replaces the specified old class with a new one.

+ Multiple Classes:
Multiple classes can be added or removed simultaneously by providing multiple arguments to add or remove methods.
