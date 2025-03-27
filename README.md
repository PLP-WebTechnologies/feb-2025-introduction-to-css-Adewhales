# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file
- Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

-- Styles.css

/* Selector 1: Apply styling to all <h1> elements */

h1 {
    font-family: Arial, sans-serif;
    color: #4CAF50;
    text-align: center;
  }
  
  /* Selector 2: Style a class for the introduction paragraph */
  .introduction {
    font-size: 18px;
    line-height: 1.6;
    color:black
    margin: 20px;
  }
  
  /* Selector 3: Use a class to highlight specific list items */
  .highlight {
    background-color: #4CAF50
    padding: 5px;
    border: 2px solid #4CAF50;
    border-radius: 5px;
  }

  footer {
    text-align: center;
    font-style: italic;
    font-weight: bold;
    text-decoration: underline;
}
  
  /* Additional: Enhance overall body styling for readability */
  body {
    font-family: 'Verdana', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;

-- Answer.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Week_3 Assignment</title>
  <!-- Link to the external CSS file -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>
 
  <h1>Welcome to My Sport Page!</h1> <br>
  <p class="introduction">On 9 May 2017, two days before the 67th FIFA Congress, the FIFA Council approved the slot allocation in a meeting in Manama, Bahrain. This includes an intercontinental play-off tournament involving six teams to decide the last two FIFA World Cup spots.</p> <br>
  <ul>
    <li class="highlight">First Slot</li> <br>
    <li class="highlight">Second Slot</li> <br>
    <li class="highlight">Third Slot</li> <br>
    <li class="highlight">Forth Slot</li> <br>
  </ul>

  <footer><br><br><br><br><br><br><br><br><br>
    <p class="highlight">&copy; 2025. All rights reserved.</p>
</footer>
</body>
</html>
    

