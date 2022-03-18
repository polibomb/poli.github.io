<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading3</h1>
<p>This is a paragraph.</p>
<button type="button">Click Me!</button>

.button {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  background-color: white; 
  color: black; 
  border: 2px solid #4CAF50;
}

.button1:hover {
  background-color: #4CAF50;
  color: white;
}

.button2 {
  background-color: white; 
  color: black; 
  border: 2px solid #008CBA;
}

.button2:hover {
  background-color: #008CBA;
  color: white;
}

</style>
</head>
<body>

<h1>The button element - Styled with CSS</h1>

<p>Use the :hover selector to change the style of the button when you move the mouse over it.</p>
<p><strong>Tip:</strong> Use the transition-duration property to determine the speed of the "hover" effect:</p>

<button class="button button1">Green</button>
<button class="button button2">Blue</button>

</body>
</html>
