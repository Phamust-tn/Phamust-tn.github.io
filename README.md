<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Modern Responsive Web Page">
    <meta name="author" content="Phamust-tn">
    <title>Modern Web Page</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #6200ea;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            text-align: center;
            background: #3700b3;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: #bb86fc;
            color: white;
        }
        .hero h2 {
            font-size: 2rem;
            margin: 0;
        }
        .container {
            margin: 20px auto;
            max-width: 1200px;
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 10px;
            padding: 20px;
            text-align: center;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #3700b3;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Modern Web Page</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero" id="home">
        <h2>Build your dreams with us</h2>
        <p>Creating modern and responsive web pages for a better user experience.</p>
    </section>
    <section class="container">
        <h2>Our Services</h2>
        <div class="grid">
            <div class="card">
                <h3>Web Development</h3>
                <p>We create responsive and modern websites tailored to your needs.</p>
            </div>
            <div class="card">
                <h3>SEO Optimization</h3>
                <p>Improve your website's visibility in search engines.</p>
            </div>
            <div class="card">
                <h3>UI/UX Design</h3>
                <p>Enhance user experience with intuitive and aesthetic designs.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Phamust-tn. All rights reserved.</p>
    </footer>
</body>
</html>Test
