JavaScript 中的 `classList` 属性用于添加、删除、切换和检查元素上 CSS 类的存在。

--- code ---
---
language: js
filename: script.js
line_numbers: false
line_highlights: 5
---

// 灯光模式函数
function changeLightMode(){
  var isLightMode = lightModeSwitch.checked;
  document.body.classList.toggle("light-mode");
}

--- /code ---

这些是可以与 `classList` 属性一起使用的一些方法。

- 访问 classList：
  `element.classList` 返回元素的类属性列表。

- 添加一个类：
  `classList.add("className")` 将指定的类添加到元素。 如果该类已经存在，则会被忽略。

- 删除一个类：
  `classList.remove("className")` 从元素中删除指定的类。

- 切换一个类：
  `classList.toggle("className")` 切换指定类的存在。 如果该类存在，则将其删除；否则，则添加。

- 检查类是否存在：
  `classList.contains("className")` 返回一个布尔值 (true/false)，显示元素上是否存在指定的类。

- 替换类：
  `classList.replace("oldClass", "newClass")` 用新类替换指定的旧类。
