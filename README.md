<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuickPickz - Online Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>QuickPickz</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Welcome to QuickPickz - Your One-Stop Shop for the Best Products!</h2>
        <p>Discover top-quality products at unbeatable prices. Shop now!</p>
    </section>

    <section id="products" class="product-section">
        <h2>Featured Products</h2>
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <h3>Product 1</h3>
            <p>$19.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <h3>Product 2</h3>
            <p>$29.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 3">
            <h3>Product 3</h3>
            <p>$39.99</p>
            <button>Add to Cart</button>
        </div>
    </section>

    <section id="about" class="about-section">
        <h2>About Us</h2>
        <p>QuickPickz is an online store dedicated to offering a wide range of high-quality products at affordable prices.</p>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to reach out!</p>
        <form action="#" method="POST">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 QuickPickz. All Rights Reserved.</p>
    </footer>
</body>
</html>
