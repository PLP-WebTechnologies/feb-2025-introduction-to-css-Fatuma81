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
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to TravelBuddy</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <h1>Your One Stop To Finding A Travel Companion</h1>
    <p>create profile</p>
        <div>
            <p>choose preferred mode of travel</p>
            <input type="radio" name="go"> <span>Flight</span>
            <input type="radio" name="go" checked> <span>Train</span>
            <input type="radio" name="go"> <span>Bus</span>
            <input type="text" placeholder="Your Name" name='come'>
            <span class='cal'>
                <input type="text" placeholder="Date" name='come'>
            </span>
            <select><option class='opy'>Destination City</option></select>
            <select><option>Select Class</option></select>
            <select><option>Adults</option></select>
            <select><option>Children</option></select>
            <input type='submit' value='Submit'>
        </div>
        </body>
</html>
