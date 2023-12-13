<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #444;
            padding: 1em;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 1em;
            margin: 0 1em;
            display: inline-block;
        }

        section {
            padding: 2em;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <section>
        <h2>Welcome to Your Website</h2>
        <p>This is a simple example webpage. Feel free to customize and add more content.</p>
        <button onclick="showMessage()">Click me</button>
        <p id="demo"></p>
    </section>

    <script>
        function showMessage() {
            document.getElementById("demo").innerHTML = "Hello, welcome to your website!";
        }
    </script>

</body>
</html>
