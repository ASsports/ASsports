<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Equipment Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Sports Equipment Store</h1>
        <nav>
            <ul>
                <li><a href="#cricket">Cricket</a></li>
                <li><a href="#football">Football</a></li>
                <li><a href="#badminton">Badminton</a></li>
                <li><a href="#basketball">Basketball</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="cricket">
            <h2>Cricket Equipment</h2>
            <img src="images/cricket.jpg" alt="Cricket Equipment">
            <p>Explore our range of cricket bats, balls, pads, and more.</p>
        </section>
        <section id="football">
            <h2>Football Equipment</h2>
            <img src="images/football.jpg" alt="Football Equipment">
            <p>Find the best footballs, boots, and gear.</p>
        </section>
        <section id="badminton">
            <h2>Badminton Equipment</h2>
            <img src="images/badminton.jpg" alt="Badminton Equipment">
            <p>Discover our collection of badminton rackets, shuttlecocks, and more.</p>
        </section>
        <section id="basketball">
            <h2>Basketball Equipment</h2>
            <img src="images/basketball.jpg" alt="Basketball Equipment">
            <p>Check out our basketballs, hoops, and accessories.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Sports Equipment Store</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f9fa;
    color: #333;
}

header {
    background-color: #007bff;
    color: white;
    padding: 1em 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 1em;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 1em;
    max-width: 800px;
    margin: 0 auto;
}

section {
    margin-bottom: 2em;
}

section img {
    max-width: 100%;
    height: auto;
}

footer {
    text-align: center;
    padding: 1em 0;
    background-color: #007bff;
    color: white;
}
/your-website-folder
    /images
        cricket.jpg
        football.jpg
        badminton.jpg
        basketball.jpg
    index.html
    styles.css
