<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="hero">
            <h1>Welcome to My Portfolio</h1>
            <p>Discover my projects and skills</p>
            <a href="#projects" class="btn">View Projects</a>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="fade-in">
        <h2>About Me</h2>
        <p>Hello! My name is Manasa Vemuri, and I am currently pursuing my 3rd year of a BTech degree from SRM-AP University. I have a passion for coding and enjoy building projects using HTML, CSS, and JavaScript.</p>
    </section>

    <section id="projects" class="fade-in">
        <h2>My Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>Project 1</h3>
                <p>Address Handbook(C++).</p>
                <a href="https://your-project-link-1.com" target="_blank">View Project</a>
            </div>
            <div class="project-card">
                <h3>Project 2</h3>
                <p>Library Management(C).</p>
                <a href="https://your-project-link-2.com" target="_blank">View Project</a>
            </div>
            <div class="project-card">
                <h3>Project 3</h3>
                <p>Coupon Code Generatot(Data Structures).</p>
                <a href="https://your-project-link-3.com" target="_blank">View Project</a>
            </div>
            <div class="project-card">
                <h3>Project 4</h3>
                <p>Spotify Clone(HTML,CSS).</p>
                <a href="https://your-project-link-4.com" target="_blank">View Project</a>
            </div>
        </div>
    </section>

    <section id="contact" class="fade-in">
        <h2>Contact Me</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit" class="btn">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Manasa Vemuri. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
