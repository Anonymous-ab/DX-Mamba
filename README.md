<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Info Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            text-align: center;
        }
        nav {
            margin: 1rem 0;
            text-align: center;
        }
        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            margin: 2rem 0;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Info Page</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="about">
            <h2>About</h2>
            <p>This page is a simple example of a GitHub Pages website. It serves as an info page where you can share details about yourself, your work, or anything else you find interesting.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Project 1:</strong> <a href="#">Link to Project 1</a></li>
                <li><strong>Project 2:</strong> <a href="#">Link to Project 2</a></li>
                <li><strong>Project 3:</strong> <a href="#">Link to Project 3</a></li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>You can reach me at:</p>
            <ul>
                <li>Email: <a href="mailto:example@example.com">example@example.com</a></li>
                <li>GitHub: <a href="https://github.com/anonymous-user-2711" target="_blank">github.com/anonymous-user-2711</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Anonymous User 2711. All rights reserved.</p>
    </footer>
</body>
</html>
