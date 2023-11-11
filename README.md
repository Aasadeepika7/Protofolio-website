index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Portfolio</title>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Introduce yourself and highlight your skills and experiences.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Name 1</h3>
            <p>Description of the project.</p>
        </div>
        <div class="project">
            <h3>Project Name 2</h3>
            <p>Description of the project.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your.email@example.com</p>
        <p>LinkedIn: linkedin.com/in/your-profile</p>
        <!-- Add more contact information as needed -->
    </section>
</body>
</html>







style.css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

section {
    margin: 20px;
}

h2 {
    color: #333;
}

ul {
    list-style-type: none;
}

.project {
    margin-bottom: 15px;
}
