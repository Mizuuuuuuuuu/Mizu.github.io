<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="GitHub Portfolio">
    <title>Your GitHub Portfolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to an external CSS file -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #24292f;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        section {
            margin: 40px 0;
        }
        .about, .projects, .contact {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .about img {
            max-width: 200px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        .projects .project {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        .projects .project img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        footer {
            background-color: #24292f;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer a {
            color: #58a6ff;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Chistian Jake Perandos</h1>
        <p>Web Developer | Open Source Contributor | GitHub Enthusiast</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        <!-- About Section -->
        <section id="about" class="about">
            <h2>About Me</h2>
            <div style="display: flex; align-items: center;">
                <img src="your-photo.jpg" alt="Your photo">
                <p>Hello! I'm a passionate web developer and an open-source contributor. I specialize in creating web applications using HTML, CSS, JavaScript, and various modern technologies. Explore my GitHub projects to see what I've built so far!</p>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects">
            <h2>GitHub Projects</h2>
            <div class="project">
                <div style="width: 45%;">
                    <h3>Project 1: <a href="https://github.com/your-username/project1" target="_blank">Project Name</a></h3>
                    <p>A brief description of what the project is about. This could include the technologies used and its purpose. For example: "A to-do list app built with React.js that allows users to manage tasks efficiently."</p>
                </div>
                <div style="width: 45%;">
                    <h3>Project 2: <a href="https://github.com/your-username/project2" target="_blank">Project Name</a></h3>
                    <p>A brief description of the second project. "A weather app that pulls live data from an API and displays weather information for any city worldwide."</p>
                </div>
            </div>
            <div class="project">
                <div style="width: 45%;">
                    <h3>Project 3: <a href="https://github.com/your-username/project3" target="_blank">Project Name</a></h3>
                    <p>Description of the project. "A simple personal blog site built with Node.js and Express, where users can write and share articles."</p>
                </div>
                <div style="width: 45%;">
                    <h3>Project 4: <a href="https://github.com/your-username/project4" target="_blank">Project Name</a></h3>
                    <p>Description of another project. "An e-commerce platform built with Vue.js and Firebase, enabling users to browse and purchase items online."</p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <p>If you'd like to collaborate or ask any questions, feel free to reach out!</p>
            <ul>
                <li>Email: your-email@example.com</li>
                <li>GitHub: <a href="https://github.com/your-username" target="_blank">your-username</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/your-linkedin" target="_blank">your-linkedin</a></li>
            </ul>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Your Name | Check out my repositories on <a href="https://github.com/your-username" target="_blank">GitHub</a></p>
    </footer>

</body>
</html>
