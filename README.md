<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional video editing services to bring your vision to life. Transform your raw footage into polished, high-quality videos.">
    <title>Professional Video Editor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: url('hero-image.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }
        .hero h2 {
            font-size: 2em;
            max-width: 600px;
        }
        .section {
            padding: 40px 20px;
            text-align: center;
        }
        .section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        .services, .portfolio {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .service, .project {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 300px;
            text-align: left;
        }
        .service h3, .project h3 {
            margin-top: 0;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        footer p {
            margin: 5px 0;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #2c3e50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #34495e;
        }
    </style>
</head>
<body>
    <header>
        <h1>Professional Video Editing Services</h1>
        <nav>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h2>Transforming Raw Footage into Stunning Visual Stories</h2>
    </div>

    <section id="services" class="section">
        <h2>My Services</h2>
        <div class="services">
            <div class="service">
                <h3>Video Editing</h3>
                <p>Seamless edits for corporate videos, short films, or personal projects.</p>
            </div>
            <div class="service">
                <h3>Color Grading</h3>
                <p>Professional color correction and grading to enhance visual aesthetics.</p>
            </div>
            <div class="service">
                <h3>Motion Graphics</h3>
                <p>Custom animations and titles for a polished, professional look.</p>
            </div>
        </div>
    </section>

    <section id="portfolio" class="section">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="project">
                <h3>Project 1</h3>
                <p>A corporate video highlighting a brand's story.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>A cinematic short film showcasing dramatic editing and effects.</p>
            </div>
            <div class="project">
                <h3>Project 3</h3>
                <p>A vibrant social media ad with dynamic motion graphics.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Me</h2>
        <form class="contact-form" action="#" method="post">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Professional Video Editor. All rights reserved.</p>
        <p>Email: yourname@example.com | Phone: +123 456 7890</p>
    </footer>
</body>
</html>
