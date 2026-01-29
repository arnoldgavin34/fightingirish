# flghtingirish
athlete-site/
│── index.html
│── style.css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Athlete Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header class="hero">
        <h1>Gavin Arnold</h1>
        <p>Student-Athlete | Electrical Engineering | Leadership & Performance</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About</a>
        <a href="#stats">Athletic Stats</a>
        <a href="#highlights">Highlights</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a dedicated student-athlete pursuing Electrical Engineering at the University of Notre Dame.
            I bring discipline, leadership, and competitive drive both on and off the field.
        </p>
    </section>

    <!-- Stats Section -->
    <section id="stats">
        <h2>Athletic Stats</h2>
        <ul>
            <li>Height: 6'2"</li>
            <li>Position: Outside Hitter</li>
            <li>Vertical: 34"</li>
            <li>Team Captain</li>
        </ul>
    </section>

    <!-- Highlights Section -->
    <section id="highlights">
        <h2>Highlights</h2>
        <p>
            Game footage, awards, and accomplishments coming soon.
        </p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: gavinarnold@email.com</p>
        <p>LinkedIn: linkedin.com/in/gavinarnold</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Gavin Arnold</p>
    </footer>

</body>
</html>



body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.hero {
    background-color: #0a1f44;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

nav {
    background-color: #ffffff;
    padding: 10px;
    text-align: center;
    border-bottom: 2px solid #ddd;
}

nav a {
    margin: 0 15px;
    text-decoration: none;
    color: #0a1f44;
    font-weight: bold;
}

section {
    padding: 40px 20px;
    max-width: 800px;
    margin: auto;
}

h2 {
    color: #0a1f44;
}

ul {
    list-style-type: square;
    padding-left: 20px;
}

footer {
    background-color: #0a1f44;
    color: white;
    text-align: center;
    padding: 15px;
}
