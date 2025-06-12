# Pet-Shop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paws & Whiskers</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Paws & Whiskers</h1>
        <nav>
            <a href="#products">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Your Pet's Happiness Starts Here 🐶🐱</h2>
        <p>Discover hand-picked toys, treats, and accessories for your furry friend.</p>
        <a href="#products" class="btn">Shop Now</a>
    </section>

    <section id="products" class="products">
        <h2>Featured Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/200x200?text=Dog+Toy" alt="Dog Toy">
                <h3>Squeaky Dog Toy</h3>
                <p>$9.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x200?text=Cat+Tunnel" alt="Cat Tunnel">
                <h3>Foldable Cat Tunnel</h3>
                <p>$14.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x200?text=Pet+Bed" alt="Pet Bed">
                <h3>Cozy Pet Bed</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>We're passionate pet lovers who want to bring the best products directly to your doorstep. Every item is hand-picked with love for comfort, safety, and fun!</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Have a question or just want to say hi? Email us at <a href="mailto:support@pawsandwhiskers.com">support@pawsandwhiskers.com</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Paws & Whiskers. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background-color: #fffaf4;
    color: #333;
}

header {
    background-color: #ffb347;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

header h1 {
    color: white;
    margin: 0;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 1rem;
    font-weight: bold;
}

.hero {
    background: url('https://images.unsplash.com/photo-1583337130417-3346a1a4ed5d?fit=crop&w=1500&q=80') no-repeat center center/cover;
    color: white;
    padding: 100px 20px;
    text-align: center;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
}

.btn {
    background-color: #ff7f50;
    color: white;
    padding: 0.7rem 1.5rem;
    border: none;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #ff6347;
}

.products {
    padding: 2rem;
    text-align: center;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    justify-content: center;
    margin-top: 1rem;
}

.product {
    background-color: white;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    padding: 1rem;
    width: 200px;
}

.product img {
    width: 100%;
    border-radius: 8px;
}

.product h3 {
    margin: 0.5rem 0;
}

.product button {
    background-color: #ffa07a;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.product button:hover {
    background-color: #ff8c66;
}

.about, .contact {
    padding: 2rem;
    text-align: center;
    background-color: #fff0e6;
}

footer {
    background-color: #ffd1a4;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
}
