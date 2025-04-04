# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DOM Manipulation Example</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Welcome to DOM Manipulation!</h1>
  </header>

  <main>
    <section>
      <h2>Change the text content</h2>
      <p id="text">This is some static text.</p>
      <button id="changeTextBtn">Change Text</button>
    </section>

    <section>
      <h2>Modify CSS Styles</h2>
      <p id="styledText">This text will have its styles changed.</p>
      <button id="changeStyleBtn">Change Style</button>
    </section>

    <section>
      <h2>Add/Remove an Element</h2>
      <button id="addElementBtn">Add Element</button>
      <button id="removeElementBtn">Remove Element</button>
      <div id="newElementContainer"></div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 DOM Manipulation Example</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

Happy Coding! 💻✨
