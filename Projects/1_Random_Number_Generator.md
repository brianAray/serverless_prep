# Random Number Generator

The project can be done completely on your own, but if you are not sure where to start then there is some starter code available.

You will need to be comfortable with DOM manipulation. If it is the first time you have heard about it, then check out these resources:

- https://www.w3schools.com/js/js_htmldom.asp
- https://www.freecodecamp.org/news/how-to-manipulate-the-dom-beginners-guide/
- [Cheat Sheet](https://dev.to/m0nm/javascript-dom-manipulation-cheatsheet-1jkb)

## Code Snippet

### HTML

The HTML will be what is shown visually on the web page. Make the name of the file 'index.html'.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Random Number Generator</title>
</head>
<body>
    <!-- HTML Code -->
    <input type="number" id="minValue" placeholder="Enter min value">
    <input type="number" id="maxValue" placeholder="Enter max value">
    <!-- This button, when clicked, will run the JS function named generateRandomNumber -->
    <button onclick="generateRandomNumber()">Generate</button>
    <p id="output"></p>

    <script>
        // JavaScript Code
        // This is the function that will be run when the button is clicked
        function generateRandomNumber() {
            /*
                Steps
                - Get the values from the input boxes using DOM manipulation
                - Use the Math.floor() function to calculate the random number
                - Set the number on the webpage using the <p> using DOM manipulation
            */
        }
    </script>
</body>
</html>
```

Using this starter code, complete the `<script>` section of the code in JavaScript.