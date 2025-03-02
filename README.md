<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first website using HTML, CSS, and JavaScript!</p>
    <button onclick="alert('Hello World!')">Click Me</button>
    <script src="script.js"></script>
</body>
</html>
/* Reset some default styles */
body, h1, p, button {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

/* Basic page styles */
body {
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
    font-size: 16px;
}

/* Header styles */
header {
    text-align: center;
    padding: 50px;
    background-color: #4CAF50;
    color: white;
}

/* Button styles */
button {
    padding: 10px 20px;
    background-color: #007BFF;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #0056b3;
}

/* Footer styles */
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}
// You can add JavaScript here for more interactivity
console.log('Hello from JavaScript!');
