<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* ======= GENERAL STYLES ======= */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px 0;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 5px 0 20px 0;
            font-size: 1.2em;
        }

        header nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
        }

        section h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 2em;
        }

        .project {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #2c3e50;
            color: white;
        }

        /* ======= RESPONSIVE ======= */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2em;
            }
            header nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Imari Gueco</h1>
        <p>Web Developer & Designer</p>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am a computer technology student with skills in HTML, CSS, and basic web design. I love building simple and clean websites.</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of your first project.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of your second project.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
        <p>Phone: 09123456789</p>
    </section>

    <footer>
        <p>© 2026 Imari Gueco</p>
    </footer>
</body>
</html>
