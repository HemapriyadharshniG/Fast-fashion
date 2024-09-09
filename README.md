HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Minimalist UI</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="logo">MySite</div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero-section">
        <h1>Welcome to My Minimalist UI</h1>
        <p>Simple, clean, and modern design</p>
        <a href="#" class="btn">Get Started</a>
    </header>

    <!-- Content Section -->
    <section class="content">
        <div class="card">
            <h2>Card Title</h2>
            <p>This is a simple card with a minimalist style. Add more content here to suit your needs.</p>
        </div>
        <div class="card">
            <h2>Card Title</h2>
            <p>This is another card. Minimalist design focuses on simplicity, usability, and elegance.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>© 2024 MySite. All rights reserved.</p>
    </footer>
</body>
</html>

CSS
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
}

/* Navigation Bar */
.navbar {
    display: flex;
    justify-content: space-between;
    padding: 1rem 2rem;
    background-color: #333;
}

.logo {
    color: #fff;
    font-size: 1.5rem;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-left: 1.5rem;
}

.nav-links li a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
}

.nav-links li a:hover {
    color: #f4f4f4;
    border-bottom: 2px solid #fff;
}

/* Hero Section */
.hero-section {
    text-align: center;
    padding: 5rem 1rem;
    background-color: #fff;
    margin-top: 1rem;
}

.hero-section h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero-section p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.hero-section .btn {
    background-color: #333;
    color: #fff;
    padding: 0.8rem 2rem;
    text-decoration: none;
    font-size: 1rem;
    border-radius: 3px;
}

.hero-section .btn:hover {
    background-color: #555;
}

/* Content Section */
.content {
    display: flex;
    justify-content: center;
    gap: 2rem;
    padding: 2rem;
}

.card {
    background-color: #fff;
    padding: 1.5rem;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    width: 250px;
    text-align: center;
}

.card h2 {
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

.card p {
    font-size: 1rem;
    color: #666;
}

/* Footer */
.footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: #fff;
    margin-top: 2rem;
}
