<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 0.5em 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0 1em;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background-color: #fff;
            overflow: hidden;
        }
        article {
            float: left;
            width: 70%;
        }
        aside {
            float: right;
            width: 30%;
            background-color: #f4f4f4;
            padding: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Awesome Website</h1>
    </header>

    <nav>
        <a href="#">Home</a> |
        <a href="#">About</a> |
        <a href="#">Services</a> |
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <article>
            <h2>Welcome to My Website</h2>
            <p>This is a basic HTML template for creating websites. You can customize it as needed.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, diam id tincidunt tincidunt, elit mauris dictum quam, id aliquam lorem ipsum et.</p>
        </article>

        <aside>
            <h3>Sidebar</h3>
            <p>This is a sidebar with additional information.</p>
        </aside>
    </div>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

</body>
</html>
