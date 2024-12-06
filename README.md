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
            background-color: #000;
            color: #fff;
        }
        header {
            padding: 20px;
            text-align: center;
            background-color: #4d2b20;
            font-size: 1.5rem;
        }
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 50px 20px;
            text-align: center;
        }
        .hero img {
            max-width: 400px;
            margin-bottom: 20px;
            border-radius: 10px;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin: 0;
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
        }
        .portfolio .project img {
            max-width: 100%;
            border-radius: 5px;
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
        ChristianJakePortfolio
    </header>
    <section class="hero">
        <h2>Hello, I'm Christian Jake</h2>
    <section class="portfolio">
    <h2>My Portfolio</h2>
    <p>Welcome to my portfolio. Here you'll find a selection of my work. Explore my projects to learn more about what I do.</p>
    <div class="projects">
        <div class="project">
            <a href="https://drive.google.com/drive/folders/1G-eseiuBmRsgKfZcrth4NenZLadmftU_">
                <button>View More</button>
            </a>
        </div>
        <div class="project">
            <a href="https://drive.google.com/drive/folders/1HPB9NCZaSVZPbrTbWTcEcFM0y-d0Li3i">
                <button>View More</button>
            </a>
        </div>
    </div>
</section>
