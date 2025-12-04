<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PixelTide - Freelance Services</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', sans-serif;
        }

        body {
            background-color: #f9f9f9;
            color: #333;
            scroll-behavior: smooth;
        }

        header {
            background-color: #1e3a8a;
            color: white;
            padding: 20px 0;
        }

        header nav {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(135deg, #3b82f6, #9333ea);
            color: white;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 40px;
        }

        .hero button {
            padding: 15px 30px;
            background-color: white;
            color: #3b82f6;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            font-weight: bold;
        }

        .hero button:hover {
            background-color: #f3f4f6;
        }

        .services, .portfolio {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
            color: #1e3a8a;
        }

        .service-card, .portfolio-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }

        .service-card:hover, .portfolio-card:hover {
            transform: translateY(-10px);
        }

        .service-card h3, .portfolio-card h3 {
            margin-bottom: 15px;
            color: #1e3a8a;
        }

        .service-card p, .portfolio-card p {
            color: #555;
        }

        .portfolio-card img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .portfolio-card button {
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #3b82f6;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }

        .portfolio-card button:hover {
            background-color: #2563eb;
        }

        footer {
            background-color: #1e3a8a;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
        }

        footer p {
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo"><h2>PixelTide</h2></div>
            <div class="menu">
                <a href="#services">Services</a>
                <a href="#portfolio">Portfolio</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to PixelTide</h1>
        <p>Your one-stop platform for freelance services</p>
        <button onclick="document.getElementById('portfolio').scrollIntoView({behavior:'smooth'})">Get Started</button>
    </section>

    <section class="services" id="services">
        <h2 class="section-title">Our Services</h2>
        <div class="service-card">
            <h3>Graphic Design</h3>
            <p>High-quality logos, banners, and visual content for your brand.</p>
        </div>
        <div class="service-card">
            <h3>Web Development</h3>
            <p>Modern websites built with responsive and clean design.</p>
        </div>
        <div class="service-card">
            <h3>Digital Marketing</h3>
            <p>Grow your online presence with SEO, social media, and ads.</p>
        </div>
        <div class="service-card">
            <h3>Writing & Translation</h3>
            <p>Professional content, copywriting, and language services.</p>
        </div>
    </section>

    <section class="portfolio" id="portfolio">
        <h2 class="section-title">Portfolio</h2>
        <div class="portfolio-card">
            <img src="PIXLETIDE3.PNG" alt="Project One">
            <h3>Project One</h3>
            <p>A creative logo design for a startup brand.</p>
            <button>View Project</button>
        </div>
        <div class="portfolio-card">
            <img src="PIXLETIDE2.PNG" alt="Project Two">
            <h3>Project Two</h3>
            <p>A responsive website built for an e-commerce business.</p>
            <button>View Project</button>
        </div>
        <div class="portfolio-card">
            <img src="PIXLETIDE6.PNG" alt="Project Three">
            <h3>Project Three</h3>
            <p>Social media campaign boosting engagement by 50%.</p>
            <button>View Project</button>
        </div>
        <div class="portfolio-card">
            <img src="PIXLE TIDE1.PNG" alt="Project Four">
            <h3>Project Four</h3>
            <p>Professional copywriting for a marketing campaign.</p>
            <button>View Project</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 PixelTide. All rights reserved.</p>
    </footer>
</body>
</html>

