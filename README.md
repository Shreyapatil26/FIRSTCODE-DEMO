<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>kle College</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        scroll-behavior: smooth;
    }

    body {
        font-family: Arial, sans-serif;
        background-color: #f4f6f9;
    }

    /* Header */
    header {
        background-color: #2C2F7A;
        color: white;
        padding: 20px;
        text-align: center;
    }

    /* Navigation */
    nav {
        background-color: #4F7FFF;
        padding: 12px;
        text-align: center;
        position: sticky;
        top: 0;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin: 15px;
        font-weight: bold;
        transition: 0.3s;
    }

    nav a:hover {
        color: #2ED3B7;
    }

    /* Hero Section */
    .hero {
        position: relative;
        text-align: center;
        color: white;
    }

    .hero img {
        width: 100%;
        height: 350px;
        object-fit: cover;
        filter: brightness(60%);
    }

    .hero-text {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    .hero-text h1 {
        font-size: 40px;
    }

    /* Sections */
    section {
        padding: 50px;
        text-align: center;
    }

    .card {
        background: white;
        padding: 25px;
        margin: 20px auto;
        width: 80%;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        border-radius: 10px;
    }

    input, textarea {
        width: 80%;
        padding: 10px;
        margin: 10px 0;
        border-radius: 5px;
        border: 1px solid #ccc;
    }

    button {
        background-color: #2ED3B7;
        border: none;
        padding: 10px 20px;
        color: white;
        font-weight: bold;
        border-radius: 5px;
        cursor: pointer;
    }

    button:hover {
        background-color: #1bb79f;
    }

    footer {
        background-color: #2C2F7A;
        color: white;
        text-align: center;
        padding: 15px;
    }

    @media (max-width: 600px) {
        .card {
            width: 95%;
        }
        .hero-text h1 {
            font-size: 24px;
        }
    }
</style>
</head>

<body>

<header>
    <h2>kle College</h2>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#contact">Contact</a>
</nav>

<!-- Hero Section with College Image -->
<div class="hero" id="home">
    <img src="https://images.unsplash.com/photo-1580582932707-520aed937b7b" alt="College Image">
    <div class="hero-text">
        <h1>Welcome to kle College</h1>
        <p>Empowering Students for a Better Future</p>
    </div>
</div>

<section id="about">
    <div class="card">
        <h2>About Us</h2>
        <p>kle College was established in 2000. We provide high-quality education with modern infrastructure and experienced faculty members.</p>
    </div>
</section>

<section id="courses">
    <div class="card">
        <h2>Our Courses</h2>
        <p>
           • BCA <br>
           • BBA <br>
           • BCom <br>
           • BSc IT <br>
           • MBA
        </p>
    </div>
</section>

<section id="contact">
    <div class="card">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required><br>
            <input type="email" placeholder="Your Email" required><br>
            <textarea rows="4" placeholder="Your Message" required></textarea><br>
            <button type="submit">Send Message</button>
        </form>
    </div>
</section>

<footer>
    <p>© 2026 kle College | All Rights Reserved</p>
</footer>

</body>
</html>

