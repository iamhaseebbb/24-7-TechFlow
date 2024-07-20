<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>24/7 TechFlow</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>24/7 TechFlow</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#support">Support</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Seamless IT Solutions Anytime, Anywhere</h2>
            <a href="#services" class="btn">Get Started</a>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service">
                <h3>IMAC Services</h3>
                <p>Installation, Move, and Change of IT equipment and infrastructure within organizations.</p>
            </div>
            <div class="service">
                <h3>Windows Installation</h3>
                <p>Professional installation and configuration of Windows operating systems.</p>
            </div>
            <div class="service">
                <h3>Data Entry Services</h3>
                <p>Accurate and efficient data entry, management, and processing solutions.</p>
            </div>
            <div class="service">
                <h3>24/7 Support</h3>
                <p>Around-the-clock availability to ensure clients receive timely and effective assistance.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Our mission at 24/7 TechFlow is to provide unparalleled support in IT equipment setup, relocation, modification, Windows installation, and data entry services. We aim to deliver seamless, reliable, and efficient solutions around the clock, ensuring our clients' technology infrastructure and data management needs are met with precision and excellence.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit" class="btn">Send</button>
            </form>
        </div>
    </section>

    <section id="support">
        <div class="container">
            <h2>Support</h2>
            <p>Need help? Contact our support team 24/7.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 24/7 TechFlow. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #003366;
    color: #FFFFFF;
}

header {
    background-color: #003366;
    padding: 10px 0;
    border-bottom: 2px solid #FFCC00;
}

.container {
    width: 80%;
    margin: 0 auto;
    text-align: center;
}

.logo h1 {
    margin: 0;
    font-size: 2em;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #FFFFFF;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background-color: #004080;
    padding: 100px 0;
}

.hero h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.btn {
    background-color: #FFCC00;
    color: #003366;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

section {
    padding: 50px 0;
}

.service {
    margin-bottom: 30px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin-top: 10px;
}

form input, form textarea {
    width: 100%;
    max-width: 400px;
    padding: 10px;
    margin-top: 5px;
    border: none;
    border-radius: 5px;
}

form button {
    margin-top: 20px;
}

footer {
    background-color: #002244;
    padding: 20px 0;
    text-align: center;
}
