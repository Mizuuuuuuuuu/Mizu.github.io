<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Christian Jake Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }
        header {
            padding: 20px;
            text-align: center;
            background-color: #4d2b20;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 50px 20px;
            background-color: #000;
        }
        .hero img {
            max-width: 400px;
            margin-right: 20px;
        }
        .hero h2 {
            font-size: 2.5rem;
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
        }
        .portfolio .projects {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .portfolio .project img {
            max-width: 200px;
            border: 2px solid #fff;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Christian Jake Portfolio</h1>
    </header>
    <section class="hero">
        <h2>Hello, I'm Christian Jake</h2>
    </section>
    <section class="portfolio">
        <h2>My Portfolio</h2>
        <p>Welcome to my portfolio. Here you'll find a selection of my work. Explore my projects to learn more about what I do.</p>
        <div class="projects">
            <div class="project">
                <img src="https://drive.google.com/drive/folders/1G-eseiuBmRsgKfZcrth4NenZLadmftU_">
            </div>
            <div class="project">
                <img src="https://drive.google.com/drive/folders/1HPB9NCZaSVZPbrTbWTcEcFM0y-d0Li3i">
            </div>
        </div>
    </section>
</body>
</html>
