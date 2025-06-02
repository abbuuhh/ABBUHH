<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thunder Blog</title>
    <link href="https://fonts.googleapis.com/css?family=Montserrat:700,400&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background: #f4f8fb;
            margin: 0;
            padding: 0;
            color: #222;
        }
        header {
            background: linear-gradient(90deg, #3a7bd5 0%, #00d2ff 100%);
            color: #fff;
            padding: 40px 0 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            letter-spacing: 2px;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 700;
            transition: color 0.2s;
        }
        nav a:hover {
            color: #ffd700;
        }
        .container {
            max-width: 900px;
            margin: 40px auto;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 8px 32px rgba(60,60,120,0.08);
            padding: 32px;
        }
        .post {
            margin-bottom: 36px;
        }
        .post h2 {
            margin: 0 0 10px 0;
            color: #3a7bd5;
        }
        .post p {
            color: #555;
        }
        .readmore {
            color: #00d2ff;
            text-decoration: none;
            font-weight: 700;
        }
        footer {
            text-align: center;
            padding: 24px 0;
            background: #222;
            color: #fff;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Thunder</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Blog</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
        <p>Your daily dose of powerful stories, news & insights.</p>
    </header>
    <div class="container">
        <div class="post">
            <h2>Welcome to Thunder!</h2>
            <p>Discover the latest stories, tips, and insights that strike like thunder. Stay tuned for our powerful updates on tech, lifestyle, and more.</p>
            <a class="readmore" href="#">Read More</a>
        </div>
        <div class="post">
            <h2>The Science Behind Thunderstorms</h2>
            <p>Ever wondered what causes thunder and lightning? Dive into the fascinating science behind these powerful natural phenomena.</p>
            <a class="readmore" href="#">Read More</a>
        </div>
        <div class="post">
            <h2>Top 5 Gadgets to Track the Weather</h2>
            <p>Stay ahead of the storm with these must-have weather gadgets for your home and adventures.</p>
            <a class="readmore" href="#">Read More</a>
        </div>
    </div>
    <footer>
        &copy; 2025 Thunder Blog. All rights reserved.
    </footer>
</body>
</html>
