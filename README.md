<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Your Name</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
        }
        nav {
            background: #444;
            text-align: center;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1rem;
        }
        nav a:hover {
            color: #f4f4f4;
            text-decoration: underline;
        }
        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 15px;
        }
        section {
            background: #fff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            margin-bottom: 15px;
            color: #333;
        }
        .about img {
            max-width: 150px;
            border-radius: 50%;
            margin: 10px 0;
        }
        .projects .project {
            margin-bottom: 15px;
        }
        .projects a {
            color: #007bff;
            text-decoration: none;
        }
        .projects a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
        }
        footer a {
            color: #007bff;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer | Open Source Enthusiast</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <div class="container">
        <section id="about" class="about">
            <h2>About Me</h2>
            <img src="your-photo.jpg" alt="Your Photo">
            <p>Hello! I'm <strong>Your Name</strong>, a passionate web developer specializing in creating beautiful, functional, and user-friendly websites. I enjoy solving problems and constantly learning new technologies to improve my craft.</p>
            <p>With experience in HTML, CSS, JavaScript, and various frameworks, I build responsive and efficient websites for businesses and individuals. Feel free to check out my projects below!</p>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects">
            <h2>My Projects</h2>
            <div class="project">
                <h3>Project 1: <a href="https://github.com/your-username/project1" target="_blank">Portfolio Website</a></h3>
                <p>A responsive portfolio website built using HTML, CSS, and JavaScript. This project showcases my design skills and coding ability.</p>
            </div>
            <div class="project">
                <h3>Project 2: <a href="https://github.com/your-username/project2" target="_blank">E-commerce Platform</a></h3>
                <p>An e-commerce web application built with React.js and Firebase. It includes features like user authentication and product search functionality.</p>
            </div>
            <div class="project">
                <h3>Project 3: <a href="https://github.com/your-username/project3" target="_blank">Weather App</a></h3>
                <p>A weather application that uses an API to fetch live weather data for any location. Built with HTML, CSS, and JavaScript.</p>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <p>If you'd like to work together, feel free to reach out!</p>
            <ul>
                <li>Email: your-email@example.com</li>
                <li>GitHub: <a href="https://github.com/your-username" target="_blank">your-username</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/your-linkedin" target="_blank">your-linkedin</a></li>
            </ul>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Your Name | <a href="https://github.com/your-username" target="_blank">GitHub</a></p>
    </footer>

</body>
</html>
