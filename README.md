
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Noir coffee Co. - Restaurant & Cafe</title>
       <style>
        /* Reset and basic styling */
        body {
            margin: 0;
            font-family: Avantgarde, TeX Gyre Adventor, URW Gothic L, sans-serif;
            color: #333;
        }

        /* Header */
        header {
            background-color: #112c52;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #feb47b;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(to right, #426a99,#2b3e54), url('https://source.unsplash.com/1920x1080/?restaurant,cafe') no-repeat center center/cover;
            height: 100vh;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
        }

        .hero p {
            font-size: 1.5rem;
            margin: 10px 0;
        }

        .hero a {
            background-color: #ff5500;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: bold;
        }

        .hero a:hover {
            background-color: #2b3e54;
        }

        /* Sections */
        section {
            padding: 50px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #333;
        }

        section p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            color: #aaabad;
        }

        /* Menu Section */
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .menu-item {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 15px;
            width: 250px;
            text-align: left;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-item h3 {
            margin: 10px;
            font-size: 1.5rem;
        }

        .menu-item p {
            margin: 10px;
            font-size: 1rem;
            color: #777;
        }

        .menu-item .price {
            font-weight: bold;
            margin: 10px;
            color: #333;
        }

        /* Reservation Form */
        .reservation form {
            max-width: 500px;
            margin: 0 auto;
        }

        .reservation input, .reservation textarea, .reservation button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .reservation button {
            background-color: #feb47b;
            color: white;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }

        .reservation button:hover {
            background-color: #ff7e5f;
        }

        /* Testimonials Section */
        .testimonials {
            background-color: #f4f4f4;
            padding: 50px 20px;
        }

        .testimonial {
            max-width: 600px;
            margin: 20px auto;
            text-align: left;
            font-style: italic;
        }

        .testimonial p {
            margin-bottom: 10px;
        }

        .testimonial span {
            font-weight: bold;
            color: #333;
        }

        /* Google Maps Section */
        .map {
            width: 100%;
            height: 400px;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
        }

        footer a {
            color: #feb47b;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Noir coffee Co.</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#reservation">Reservation</a></li>
                <li><a href="#location">Location</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Welcome to Noir Coffee Co.</h1>
        <p>Serving delicious food since 1995</p>
        <a href="#menu">Explore Our Menu</a>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Our best's</h2>
        <p>Explore our variety of delicious dishes made with love and the finest ingredients.</p>
        <div class="menu">
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSaK4IrHSidPT9_3gz4MThq_cCsG7Tl_nM6Hg&s" alt="Burger">
                <h3>Classic Burger</h3>
                <p>Juicy grilled burger with fresh toppings.</p>
                <p class="price">$9.99</p>
            </div>
            <div class="menu-item">
                <img src="https://www.onceuponachef.com/images/2020/04/Bolognese-1200x944.jpg" alt="Pasta">
                <h3>Italian Pasta</h3>
                <p>Authentic pasta in creamy Alfredo sauce.</p>
                <p class="price">$12.99</p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPaZYHyMK7AuxUQPZKANaMa00Z5DcdbaS1Pg&s">
                <h3>Margherita Pizza</h3>
                <p>Wood-fired pizza with fresh mozzarella and basil.</p>
                <p class="price">$14.99</p>
            </div>
        </div>
    </section>

    <!-- Reservation Form -->
    <section id="reservation" class="reservation">
        <h2>Make a Reservation</h2>
        <p>Book your table in advance to enjoy a hassle-free dining experience.</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="tel" placeholder="Your Phone" required>
            <input type="date" required>
            <textarea placeholder="Special Requests (optional)" rows="4"></textarea>
            <button type="submit">Reserve Now</button>
        </form>
    </section>

    <!-- Location with Google Maps -->
    <section id="location">
        <h2>Our Location</h2>
        <p>Find us at the heart of the city. We can’t wait to serve you!</p>
        <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.8354345094227!2d-122.41941608468074!3d37.77492927975916!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80858064f6b3e533%3A0xfaf9f0c53f116d63!2sSan%20Francisco%2C%20CA%2C%20USA!5e0!3m2!1sen!2sin!4v1616522219945!5m2!1sen!2sin" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="testimonials">
        <h2>Customer Testimonials</h2>
        <div class="testimonial">
            <p>"The food here is amazing! The staff is incredibly friendly, and the ambiance is perfect."</p>
            <span>- John Doe</span>
        </div>
        <div class="testimonial">
            <p>"I loved their pasta! Definitely coming back again. Highly recommended for food lovers."</p>
            <span>- Jane Smith</span>
        </div>
        <div class="testimonial">
            <p>"Perfect spot for family dinners. Their menu has something for everyone."</p>
            <span>- Emily Johnson</span>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Noir coffee Co. All rights reserved. | <a href="#home">Back to top</a></p>
    </footer>
</body>
</html>
