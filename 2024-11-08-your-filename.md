<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Personal Website</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm [Your Name], a [Your Profession]. I love [Your Interests/Hobbies].</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="posts">
            <!-- Example post -->
            <div class="post">
                <h3 class="post-title"><a href="project1.html">Project 1</a></h3>
                <span class="post-date">January 1, 2024</span>
                <p>This is a brief description of my first project.</p>
            </div>
            <!-- Add more posts as needed -->
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

