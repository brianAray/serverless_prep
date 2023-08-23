# Imperial to Metric Converter

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
    <title>Imperial to Metric Converter</title>
</head>
<body>
    <!-- HTML Code -->
    <input type="number" id="value" placeholder="Enter value">
    <select id="unit">
        <option value="inches">Inches</option>
        <option value="feet">Feet</option>
        <!-- ... more units -->
    </select>
    <!-- This button, when clicked, will run the JS function named generateRandomNumber -->
    <button onclick="convert()">Convert</button>
    <p id="output"></p>

    <script>
        // JavaScript Code
        // This is the function that will be run when the button is clicked
        function convert() {
            /*
                Steps
                - Get the values from the input fields using DOM manipulation
                - Convert the value to a Number instead of a String
                - Based on the unit selected, convert it
                - Show the converted value onto the web page using DOM manipulation
            */
        }
    </script>
</body>
</html>
```

Using this starter code, complete the `<script>` section of the code in JavaScript.