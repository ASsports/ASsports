<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AS Esports</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav a {
            color: #fff;
            padding: 15px;
            text-decoration: none;
        }
        nav a:hover {
            background: #555;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin: 20px 0;
        }
        .section h2 {
            color: #333;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 15px;
            width: calc(25% - 40px);
            box-sizing: border-box;
        }
        .product img {
            max-width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>AOS Esports Equipment</h1>
    </header>
    <nav>
        <a href="#cricket">Cricket</a>
        <a href="#football">Football</a>
        <a href="#badminton">Badminton</a>
        <a href="#basketball">Basketball</a>
    </nav>
    <div class="container">
        <div id="cricket" class="section">
            <h2>Cricket Equipment</h2>
            <div class="products">
                <div class="product">
                    <img src="cricket_bat.jpg" alt="Cricket Bat">
                    <p>High-quality cricket bat.</p>
                </div>
                <div class="product">
                    <img src="cricket_ball.jpg" alt="Cricket Ball">
                    <p>Durable cricket ball.</p>
                </div>
                <!-- Add more cricket products here -->
            </div>
        </div>
        <div id="football" class="section">
            <h2>Football Equipment</h2>
            <div class="products">
                <div class="product">
                    <img src="football.jpg" alt="Football">
                    <p>Professional football.</p>
                </div>
                <div class="product">
                    <img src="football_boots.jpg" alt="Football Boots">
                    <p>Comfortable football boots.</p>
                </div>
                <!-- Add more football products here -->
            </div>
        </div>
        <div id="badminton" class="section">
            <h2>Badminton Equipment</h2>
            <div class="products">
                <div class="product">
                    <img src="badminton_racket.jpg" alt="Badminton Racket">
                    <p>Lightweight badminton racket.</p>
                </div>
                <div class="product">
                    <img src="shuttlecock.jpg" alt="Shuttlecock">
                    <p>High-speed shuttlecock.</p>
                </div>
                <!-- Add more badminton products here -->
            </div>
        </div>
        <div id="basketball" class="section">
            <h2>Basketball Equipment</h2>
            <div class="products">
                <div class="product">
                    <img src="basketball.jpg" alt="Basketball">
                    <p>Durable basketball.</p>
                </div>
                <div class="product">
                    <img src="basketball_hoop.jpg" alt="Basketball Hoop">
                    <p>Sturdy basketball hoop.</p>
                </div>
                <!-- Add more basketball products here -->
            </div>
        </div>
    </div>
</body>
</html>
