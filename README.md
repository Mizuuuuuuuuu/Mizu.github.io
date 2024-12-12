<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christian Jake Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #000, #4d2b20);
            color: #fff;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #4d2b20;
            color: #fff;
        }
        header .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        header nav {
            display: flex;
            gap: 20px;
        }
        header nav a {
            color: #fff;
            text-decoration: none;
            font-size: 1rem;
        }
        header nav a:hover {
            text-decoration: underline;
        }
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            height: 100vh;
            background: url('Bubble-Float.jpg') no-repeat center center/cover;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }
        .hero p {
            font-size: 1.2rem;
            margin-top: 10px;
        }
        .portfolio {
            padding: 50px 20px;
            text-align: center;
        }
        .portfolio h2 {
            margin-bottom: 20px;
            font-size: 2rem;
        }
        .portfolio p {
            margin-bottom: 30px;
            font-size: 1rem;
        }
        .portfolio .projects {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .portfolio .project {
            background-color: #222;
            border: 1px solid #444;
            border-radius: 10px;
            padding: 15px;
            width: 200px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        .portfolio .project img {
            max-width: 100%;
            border-radius: 5px;
        }
        .portfolio .project p {
            margin: 10px 0;
            font-size: 1rem;
        }
        .portfolio .project button {
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #4d2b20;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
        }
        .portfolio .project button:hover {
            background-color: #6e3c2e;
        }
        footer {
            padding: 20px;
            text-align: center;
            background-color: #111;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Christian Jake Portfolio</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact Me</a>
        </nav>
    </header>
    <section id="home" class="hero">
        <h1>Hello, I'm Christian Jake</h1>
        <p>A College Student in Quezon City University</p>
    </section>
    <section id="portfolio" class="portfolio">
        <h2>My Portfolio</h2>
        <p>Welcome to my portfolio. Here you'll find a selection of my work. Explore my projects to learn more about what I do.</p>
        <div class="projects">
            <div class="project">
                <img src="https://via.placeholder.com/200x150" alt="My Project Design">
                <p>My Project Design</p>
                <a href="https://drive.google.com/drive/folders/1G-eseiuBmRsgKfZcrth4NenZLadmftU_">
                    <button>View More</button>
                </a>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/200x150" alt="My Project Design">
                <p>My Project Design</p>
                <a href="https://drive.google.com/drive/folders/1HPB9NCZaSVZPbrTbWTcEcFM0y-d0Li3i">
                    <button>View More</button>
                </a>
            </div>
        </div>
    </section>
    <footer>
        &copy; 2024 Christian Jake Portfolio. All rights reserved.
    </footer>
</body>
</html>
