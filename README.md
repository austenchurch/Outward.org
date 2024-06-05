# Outward.org
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outward</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#mission">Mission Statement</a></li>
                <li><a href="#volunteer">Volunteer</a></li>
                <li><a href="#giving">Giving</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#events">Events</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <div class="slideshow-container">
                <div class="mySlides fade">
                    <img src="image1.jpg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="image2.jpg" style="width:100%">
                </div>
                <div class="mySlides fade">
                    <img src="image3.jpg" style="width:100%">
                </div>
            </div>
        </section>
        <section class="info">
            <h1>Welcome to Outward</h1>
            <p>Outward is dedicated to helping families stay together while receiving the support they need. Learn more about our mission and how you can get involved.</p>
        </section>
    </main>
    <footer>
        <div class="footer-section">
            <h3>Our Mission</h3>
            <p>We strive to rehabilitate families together, rather than splitting them up to seek separate help.</p>
        </div>
        <div class="footer-section">
            <h3>Connect With Us</h3>
            <ul>
                <li><a href="#facebook">Facebook</a></li>
                <li><a href="#twitter">Twitter</a></li>
                <li><a href="#instagram">Instagram</a></li>
            </ul>
        </div>
        <div class="footer-section">
            <h3>Give a Gift Today</h3>
            <button>Donate</button>
        </div>
        <div class="footer-section">
            <h3>Contact Us</h3>
            <p>Email: contact@outward.org</p>
            <p>Phone: (123) 456-7890</p>
        </div>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #006400;
    color: white;
    padding: 10px 0;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
    padding: 0;
}

header nav ul li {
    display: inline;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
}

header nav ul li a:hover {
    background-color: #004d00;
}

.hero {
    position: relative;
    max-width: 100%;
    margin: auto;
}

.mySlides {
    display: none;
}

.mySlides img {
    width: 100%;
}

.info {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    display: flex;
    justify-content: space-around;
    padding: 20px 0;
}

.footer-section {
    width: 25%;
}

.footer-section h3 {
    border-bottom: 2px solid #006400;
    padding-bottom: 10px;
}

.footer-section ul {
    list-style: none;
    padding: 0;
}

.footer-section ul li {
    margin: 10px 0;
}

.footer-section ul li a {
    color: white;
    text-decoration: none;
}

.footer-section ul li a:hover {
    text-decoration: underline;
}

footer button {
    background-color: #006400;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

footer button:hover {
    background-color: #004d00;
}
