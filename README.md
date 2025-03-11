<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glamour Wigs - Premium Quality Wigs</title>
    <style>
        :root {
            --primary-color: #FF69B4;
            --light-pink: #FFC0CB;
            --dark-pink: #FF1493;
            --white: #FFFFFF;
            --light-gray: #F5F5F5;
            --dark-gray: #333333;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--light-pink);
            color: var(--dark-gray);
        }
        
        header {
            background-color: var(--primary-color);
            padding: 15px 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: var(--white);
        }
        
        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        
        nav ul li {
            margin-left: 20px;
        }
        
        nav ul li a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--light-gray);
        }
        
        .search-bar {
            display: flex;
            margin: 10px 0;
        }
        
        .search-bar input {
            padding: 10px;
            width: 300px;
            border: none;
            border-radius: 4px 0 0 4px;
        }
        
        .search-bar button {
            padding: 10px 15px;
            background-color: var(--dark-pink);
            color: var(--white);
            border: none;
            border-radius: 0 4px 4px 0;
            cursor: pointer;
        }
        
        .hero {
            background-image: url('/api/placeholder/1200/400');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            text-align: center;
            margin-bottom: 40px;
        }
        
        .hero-content {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 30px;
            border-radius: 8px;
        }
        
        .hero h1 {
            font-size: 36px;
            margin-bottom: 15px;
        }
        
        .hero p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 24px;
            background-color: var(--primary-color);
            color: var(--white);
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: var(--dark-pink);
        }
        
        .featured-categories {
            margin-bottom: 40px;
        }
        
        h2 {
            text-align: center;
            margin-bottom: 20px;
            color: var(--dark-gray);
        }
        
        .category-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .category-card {
            background-color: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .category-card:hover {
            transform: translateY(-5px);
        }
        
        .category-img {
            height: 200px;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .category-info {
            padding: 15px;
            text-align: center;
        }
        
        .category-info h3 {
            margin-top: 0;
        }
        
        .products {
            margin-bottom: 40px;
        }
        
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .product-card {
            background-color: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
        }
        
        .product-img {
            height: 200px;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .product-info {
            padding: 15px;
        }
        
        .product-title {
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .product-price {
            color: var(--dark-pink);
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .product-rating {
            color: gold;
            margin-bottom: 10px;
        }
        
        .add-to-cart {
            background-color: var(--primary-color);
            color: var(--white);
            border: none;
            padding: 8px 15px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.3s;
        }
        
        .add-to-cart:hover {
            background-color: var(--dark-pink);
        }
        
        footer {
            background-color: var(--dark-gray);
            color: var(--white);
            padding: 40px 0;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }
        
        .footer-column h3 {
            margin-top: 0;
            margin-bottom: 15px;
            font-size: 18px;
        }
        
        .footer-column ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        .footer-column ul li {
            margin-bottom: 8px;
        }
        
        .footer-column ul li a {
            color: var(--light-gray);
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-column ul li a:hover {
            color: var(--primary-color);
        }
        
        .payment-methods {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }
        
        .payment-method {
            background-color: var(--white);
            color: var(--dark-gray);
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 14px;
        }
        
        .copyright {
            text-align: center;
            margin-top: 40px;
            color: var(--light-gray);
            font-size: 14px;
        }
        
        /* Responsive design */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                align-items: flex-start;
            }
            
            nav ul {
                margin-top: 15px;
            }
            
            .search-bar {
                width: 100%;
            }
            
            .search-bar input {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">Glamour Wigs</div>
                <nav>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Shop</a></li>
                        <li><a href="#">Categories</a></li>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Contact</a></li>
                        <li><a href="#">My Account</a></li>
                        <li><a href="#">Cart (0)</a></li>
                    </ul>
                </nav>
            </div>
            <div class="search-bar">
                <input type="text" placeholder="Search for wigs...">
                <button>Search</button>
            </div>
        </div>
    </header>

    <main>
        <section class="hero">
            <div class="hero-content">
                <h1>Glamorous Wigs for Every Style</h1>
                <p>Premium quality wigs that transform your look instantly</p>
                <a href="#" class="btn">Shop Now</a>
            </div>
        </section>

        <div class="container">
            <section class="featured-categories">
                <h2>Shop by Category</h2>
                <div class="category-grid">
                    <div class="category-card">
                        <div class="category-img">
                            <img src="/api/placeholder/250/200" alt="Long wigs">
                        </div>
                        <div class="category-info">
                            <h3>Long Wigs</h3>
                            <a href="#" class="btn">View All</a>
                        </div>
                    </div>
                    <div class="category-card">
                        <div class="category-img">
                            <img src="/api/placeholder/250/200" alt="Short wigs">
                        </div>
                        <div class="category-info">
                            <h3>Short Wigs</h3>
                            <a href="#" class="btn">View All</a>
                        </div>
                    </div>
                    <div class="category-card">
                        <div class="category-img">
                            <img src="/api/placeholder/250/200" alt="Curly wigs">
                        </div>
                        <div class="category-info">
                            <h3>Curly Wigs</h3>
                            <a href="#" class="btn">View All</a>
                        </div>
                    </div>
                    <div class="category-card">
                        <div class="category-img">
                            <img src="/api/placeholder/250/200" alt="Colored wigs">
                        </div>
                        <div class="category-info">
                            <h3>Colored Wigs</h3>
                            <a href="#" class="btn">View All</a>
                        </div>
                    </div>
                </div>
            </section>

            <section class="products">
                <h2>Bestselling Wigs</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Wavy blonde wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Wavy Blonde Wig</div>
                            <div class="product-price">$129.99</div>
                            <div class="product-rating">âââââ (42)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Short black bob">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Short Black Bob</div>
                            <div class="product-price">$99.99</div>
                            <div class="product-rating">âââââ (28)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Long brunette wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Long Brunette Wig</div>
                            <div class="product-price">$149.99</div>
                            <div class="product-rating">âââââ (56)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Curly red wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Curly Red Wig</div>
                            <div class="product-price">$119.99</div>
                            <div class="product-rating">âââââ (34)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </section>

            <section class="products">
                <h2>New Arrivals</h2>
                <div class="product-grid">
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Pastel pink wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Pastel Pink Wig</div>
                            <div class="product-price">$159.99</div>
                            <div class="product-rating">âââââ (12)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Ombre blue wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Ombre Blue Wig</div>
                            <div class="product-price">$179.99</div>
                            <div class="product-rating">âââââ (7)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Platinum blonde wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Platinum Blonde Wig</div>
                            <div class="product-price">$139.99</div>
                            <div class="product-rating">âââââ (19)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                    <div class="product-card">
                        <div class="product-img">
                            <img src="/api/placeholder/250/200" alt="Braided wig">
                        </div>
                        <div class="product-info">
                            <div class="product-title">Braided Wig</div>
                            <div class="product-price">$189.99</div>
                            <div class="product-rating">âââââ (23)</div>
                            <button class="add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Customer Service</h3>
                    <ul>
                        <li><a href="#">Contact Us</a></li>
                        <li><a href="#">FAQs</a></li>
                        <li><a href="#">Shipping & Delivery</a></li>
                        <li><a href="#">Returns & Exchanges</a></li>
                        <li><a href="#">Track Your Order</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Information</h3>
                    <ul>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Terms & Conditions</a></li>
                        <li><a href="#">Wig Care Guide</a></li>
                        <li><a href="#">Size Guide</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>My Account</h3>
                    <ul>
                        <li><a href="#">Sign In</a></li>
                        <li><a href="#">Register</a></li>
                        <li><a href="#">Order History</a></li>
                        <li><a href="#">Wishlist</a></li>
                        <li><a href="#">Newsletter</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Payment Methods</h3>
                    <p>We accept the following payment methods:</p>
                    <div class="payment-methods">
                        <div class="payment-method">MTN Mobile Money</div>
                        <div class="payment-method">Telecel Cash</div>
                        <div class="payment-method">AT Money</div>
                        <div class="payment-method">Credit/Debit Cards</div>
                    </div>
                </div>
            </div>
            <div class="copyright">
                &copy; 2025 Glamour Wigs. All Rights Reserved.
            </div>
        </div>
    </footer>
</body>
</html>

