# HTML-CSS-assignment

!DOCTYPE HTML>
<html>
<head>
    <html lang = "en">
    <meta name="width=device-width, initial-scale=1.0">
    <meta content="width=device-width, initial-scale=1.0">
    <title>Junior Software Engineer Studio</title>
    <link rel="stylesheet" href="assigno.css">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
    </style>

</head>

<body>
    <h1>Week 3 PLP Class Schedule</h1>
    <p style="color: blue;">
        We have had an amazing week, we got to engage with languages such as CSS for styling, Python for Backend and MySQL for database.
    </p>

    <div class = "list-group">
        <h2>By the End of these Course We will Have Build Tech Skills In:-</h2>
        <ul>
            <li>Frontend - HTML, CSS, & Javascript</li>
            <li>Backend - Python</li>
            <li>Mobile Dev - Dart(Flutter)</li>
            <li>Database - MySQL</li>
        </ul>
    </div>

</body>
</html>




/* General Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

/* Element Selectors */
h1, h2, h3 {
    font-size: 24px;
    font-weight: bold;
}

/* Class Selectors */
.list-group {
    background-color: #f5f5f5;
    padding: 20px;
    border: 1px solid #ccc;
}

/* ID Selectors */
#unique-element {
    border: 2px solid blue;
}

/* Link Styles */
a {
    color: blue;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Card Component */
.card {
    background-color: #fff;
    border: 1px solid #ccc;
    padding: 20px;
    margin: 20px;
}

.card-title {
    font-size: 20px;
    font-weight: bold;
}

.card-description {
    font-size: 16px;
    color: #666;
}
