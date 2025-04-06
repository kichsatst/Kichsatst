<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Final Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            padding: 14px 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        nav ul li a:hover {
            background-color: #ddd;
            color: black;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #4CAF50;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#images">Images</a></li>
            <li><a href="#favorites">Favorites</a></li>
            <li><a href="#resources">Resources</a></li>
        </ul>
    </nav>
    <main>
        <section id="about">
            <h2>About This Project</h2>
            <p>This is a simple HTML page created for my final project.</p>
        </section>
        
        <section id="images">
            <h2>My Favorite Images</h2>
            <img src="https://via.placeholder.com/300?text=Image+1" alt="A beautiful landscape">
            <img src="https://via.placeholder.com/300?text=Image+2" alt="A stunning sunset">
            <img src="https://via.placeholder.com/300?text=Image+3" alt="A serene beach">
        </section>
        
        <section id="favorites">
            <h2>My Favorite Things</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </section>
        
        <section id="resources">
            <h2>External Resources</h2>
            <p>Check out this awesome resource: <a href="https://www.example.com" target="_blank">Example Website</a></p>
        </section>
    </main>
</body>
</html>
