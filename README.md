# Hello World Assignment

## Objective: This assignment will demonstrate how HTML, CSS, and JavaScript work together.

## Instructions: Type the code into the indicated files.

### Link: [Hello World](https://mrowenha.github.io/coding1-hello-world/)

### The following is the code for the "index.html" file:
```
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Hello World</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  <h1>Hello World</h1>
  <img src="helloWorldAstronaut.jpg">
  <h3 id="dateLocation"></h3>
  <script src="script.js"></script> 
</body>

</html>
```
### The following is the code for the "style.css" file:
```
html, body {
  height: 100%;
  width: 100%;
}

body {
  background-color: black;
  text-align: center;
}

h1 {
  font-size: 48pt;
  color: white;
}

h3 {
  font-size: 24pt;
  color: white;
}

img {
  max-width: 100%;
  height: auto;
}
```
### The following is the code for the "script.js" file:
```
const date = new Date();
document.getElementById("dateLocation").innerHTML = date;
```
