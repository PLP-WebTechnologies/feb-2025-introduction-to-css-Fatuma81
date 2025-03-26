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



style.css
* {
  margin: 0;
  box-sizing: border-box;
  padding: 0;
}

body {
  background: url(https://cdn.pixabay.com/photo/2017/04/29/05/24/mountains-2270056_960_720.jpg);
  background-repeat: no-repeat;
  background-size: 100vw 150vh;
  background-attachment: fixed;
}

h1 {
  color: #FFF;
  text-align: center;
  text-transform: uppercase;
  padding: 20px;
  font-family: 'Source Sans Pro', sans-serif;
}

p {
  color: #eee;
  text-align: center;
  font-family: 'Titillium Web', sans-serif;
  font-size: 17px;
}

div {
  width: 800px;
  height: 550px;
  background: rgba(0, 0, 0, .6);
  margin: 50px auto;
}

div p {
  font-size: 17px;
  padding: 30px;
}

input[name='go'] {
  margin-left: 60px;
  height: 15px;
  width: 15px;
  background-color: transparent;
}

span {
  color: #FFF;
  font-size: 16px;
  font-family: 'Source Sans Pro', sans-serif;
}

input[name='come'] {
  width: 80%;
  margin: 25px auto;
  display: block;
  padding: 10px;
  border-radius: 20px;
  border: none;
  outline: 0;
}

.cal {
  position: relative;
}

.cal:before {
  content: "\f073";
  position: absolute;
  font-family: 'FontAwesome';
  top: 11px;
  left: 349px;
  z-index: 1;
  color: #000;
  font-size: 14px;
}

select {
  height: 30px;
  width: 150px;
  border-radius: 10px;
  border: 0;
  outline: 0;
  margin: 20px 0 0 38px;
  padding: 5px;
}

input[type='submit'] {
  width: 80%;
  margin: 30px auto;
  display: block;
  border-radius: 10px;
  border: 0;
  outline: 0;
  height: 35px;
  background: #27aa9d;
  color: #FFF;
  transition: background-color 0.3s;
}

input[type='submit']:hover {
  background-color: #219a8c;
}

p:last-child {
  font-size: 16px;
  padding-bottom: 30px;
}

.opy {
  font-size: 20px;
  background: red;
}
