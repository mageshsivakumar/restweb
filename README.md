# Ex.07 Restaurant Website
## Date:25/05/2025

## AIM:                
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```

home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Renolt Restaurant - Home</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }

        /* Body and Background */
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            font-size: 16px;
            padding: 0;
            margin: 0;
            background: #f5f5f5 url('watermark.png') no-repeat center center fixed; /* Add watermark image */
            background-size: 50%; /* Adjust size of watermark */
        }

        /* Header */
        header {
            background: linear-gradient(45deg, #9b1c1c, #d4af37); /* Gold and Red gradient */
            color: white;
            text-align: center;
            padding: 80px 20px;
            position: relative;
        }

        header h1 {
            font-size: 4em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.3em;
            margin-top: 10px;
        }

        /* Navigation Bar */
        nav {
            background-color: #9b1c1c; /* Red */
            padding: 12px 20px;
            text-align: center;
        }

        nav a {
            color: white;
            font-size: 1.2em;
            margin: 0 25px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            color: #d4af37; /* Gold */
            text-decoration: underline;
        }

        /* Hero Section */
        #hero {
            background: url('dragon-background.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 150px 20px;
            position: relative;
        }

        #hero h2 {
            font-size: 3em;
            font-weight: 600;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }

        #hero p {
            font-size: 1.5em;
            margin-bottom: 40px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }

        .cta-btn {
            background-color: #d4af37; /* Gold */
            padding: 15px 30px;
            color: white;
            text-transform: uppercase;
            font-size: 1.1em;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .cta-btn:hover {
            background-color: #9b1c1c; /* Red */
        }

        /* Featured Dishes Section */
        #featured-dishes {
            padding: 40px 20px;
            background-color: #ecf0f1;
            text-align: center;
        }

        #featured-dishes h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #9b1c1c; /* Red */
        }

        .dish-grid {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        .dish-card {
            background-color: white;
            width: 280px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            overflow: hidden;
            transition: transform 0.3s ease-in-out;
        }

        .dish-card:hover {
            transform: scale(1.05);
        }

        .dish-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .dish-card h3 {
            font-size: 1.7em;
            color: #2c3e50;
            margin-top: 20px;
        }

        .dish-card p {
            color: #7f8c8d;
            padding: 10px;
            font-size: 1.1em;
        }

        .dish-card .price {
            font-size: 1.3em;
            color: #d4af37; /* Gold */
            margin-top: 10px;
            padding: 15px;
            background-color: #f5f5f5;
            border-top: 1px solid #ccc;
        }

        /* Footer */
        footer {
            background-color: #9b1c1c; /* Red */
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 1em;
            margin-top: 40px;
        }

        footer p {
            margin: 10px 0;
        }

        /* Watermark in the Hero Section */
        #hero::after {
            content: "";
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: url('watermark.png') no-repeat center center;
            opacity: 0.1;  /* Make the watermark light and subtle */
            width: 200px;  /* Adjust size */
            height: 200px;
            z-index: -1;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            nav a {
                font-size: 1em;
                margin: 0 15px;
            }

            .dish-grid {
                flex-direction: column;
                align-items: center;
            }

            .dish-card {
                width: 100%;
                margin-bottom: 20px;
            }

            #hero h2 {
                font-size: 2.5em;
            }

            #hero p {
                font-size: 1.3em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Renolt Restaurant</h1>
    <p>Exceptional Dining Experience</p>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about us.html">About Us</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">administration</a>
</nav>

<section id="hero">
    <h2>Welcome to Renolt Restaurant</h2>
    <p>Where every meal is a masterpiece. Enjoy our delicious dishes crafted just for you.</p>
    <button class="cta-btn" onclick="window.location.href='menu.html'">Explore Our Menu</button>
</section>

<section id="featured-dishes">
    <h2>Featured Dishes</h2>
    <div class="dish-grid">
        <div class="dish-card">
            <img src="dish1.jpg" alt="Grilled Chicken">
            <h3>Grilled Chicken</h3>
            <p>Perfectly seasoned chicken with mashed potatoes and vegetables.</p>
            <div class="price">$12.99</div>
        </div>

        <div class="dish-card">
            <img src="a3.jpg" alt="Pasta Primavera">
            <h3>Pasta Primavera</h3>
            <p>Fresh pasta with seasonal veggies in olive oil and parmesan.</p>
            <div class="price">$10.99</div>
        </div>

        <div class="dish-card">
            <img src="dish3.jpg" alt="Margherita Pizza">
            <h3>Margherita Pizza</h3>
            <p>Classic pizza topped with fresh mozzarella, tomatoes, and basil pesto.</p>
            <div class="price">$9.99</div>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Renolt Restaurant | All Rights Reserved</p>
    <p>1234 Food Street, City, Country</p>
    <p>Design and Developed by aaron alex p</p>
</footer>

</body>
</html>
menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Renolt Restaurant</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }

        /* Body and Background */
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            font-size: 16px;
            padding: 0;
            margin: 0;
            background: #f5f5f5 url('watermark.png') no-repeat center center fixed; /* Add watermark image */
            background-size: 50%; /* Adjust size of watermark */
        }

        /* Header */
        header {
            background: linear-gradient(45deg, #9b1c1c, #d4af37); /* Gold and Red gradient */
            color: white;
            text-align: center;
            padding: 80px 20px;
            position: relative;
        }

        header h1 {
            font-size: 4em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.3em;
            margin-top: 10px;
        }

        /* Navigation Bar */
        nav {
            background-color: #9b1c1c; /* Red */
            padding: 12px 20px;
            text-align: center;
        }

        nav a {
            color: white;
            font-size: 1.2em;
            margin: 0 25px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            color: #d4af37; /* Gold */
            text-decoration: underline;
        }

        /* Menu Section */
        #menu {
            padding: 40px 20px;
            text-align: center;
        }

        #menu h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #9b1c1c; /* Red */
        }

        .dish-grid {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        .dish-card {
            background-color: white;
            width: 280px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            overflow: hidden;
            transition: transform 0.3s ease-in-out;
        }

        .dish-card:hover {
            transform: scale(1.05);
        }

        .dish-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .dish-card h3 {
            font-size: 1.7em;
            color: #2c3e50;
            margin-top: 20px;
        }

        .dish-card p {
            color: #7f8c8d;
            padding: 10px;
            font-size: 1.1em;
        }

        .dish-card .price {
            font-size: 1.3em;
            color: #f39c12;
            margin-top: 10px;
            padding: 15px;
            background-color: #f5f5f5;
            border-top: 1px solid #ccc;
        }

        /* Footer */
        footer {
            background-color: #9b1c1c; /* Red */
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 1em;
            margin-top: 40px;
        }

        footer p {
            margin: 10px 0;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            nav a {
                font-size: 1em;
                margin: 0 15px;
            }

            .dish-grid {
                flex-direction: column;
                align-items: center;
            }

            .dish-card {
                width: 100%;
                margin-bottom: 20px;
            }

            #menu h2 {
                font-size: 2em;
            }

            #menu p {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Renolt Restaurant</h1>
    <p>Exceptional Dining Experience</p>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
    <a herf="admin.html"> administration</a>
    
    
</nav>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="dish-grid">
        <!-- Dish 1 -->
        <div class="dish-card">
            <img src="a1.jpg" alt="Grilled Chicken">
            <h3>Grilled Chicken</h3>
            <p>Perfectly seasoned chicken with mashed potatoes and vegetables.</p>
            <div class="price">$12.99</div>
        </div>

        <!-- Dish 2 -->
        <div class="dish-card">
            <img src="a3.jpg" alt="Pasta Primavera">
            <h3>Pasta Primavera</h3>
            <p>Fresh pasta with seasonal veggies in olive oil and parmesan.</p>
            <div class="price">$10.99</div>
        </div>

        <!-- Dish 3 -->
        <div class="dish-card">
            <img src="a2.jpg" alt="Margherita Pizza">
            <h3>Margherita Pizza</h3>
            <p>Classic pizza topped with fresh mozzarella, tomatoes, and basil pesto.</p>
            <div class="price">$9.99</div>
        </div>

        <!-- Dish 4 -->
        <div class="dish-card">
            <img src="a4.jpg" alt="Grilled Salmon">
            <h3>Grilled Salmon</h3>
            <p>Juicy salmon fillet served with grilled vegetables and a lemon butter sauce.</p>
            <div class="price">$15.99</div>
        </div>

        <!-- Dish 5 -->
        <div class="dish-card">
            <img src="a5.jpg" alt="Caesar Salad">
            <h3>Caesar Salad</h3>
            <p>Classic Caesar salad with crunchy croutons and parmesan cheese.</p>
            <div class="price">$8.99</div>
        </div>

        <!-- Dish 6 -->
        <div class="dish-card">
            <img src="a6.jpg" alt="Steak Frites">
            <h3>Steak Frites</h3>
            <p>Tender steak served with crispy fries and béarnaise sauce.</p>
            <div class="price">$18.99</div>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Renolt Restaurant | All Rights Reserved</p>
    <p>1234 Food Street, City, Country</p>
    <p>Design and Developed by aaron alex</p>
</footer>

</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Renolt Restaurant</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }

        /* Body and Background */
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            font-size: 16px;
            padding: 0;
            margin: 0;
        }

        /* Header */
        header {
            background: linear-gradient(45deg, #9b1c1c, #d4af37); /* Gold and Red gradient */
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            font-size: 4em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.3em;
            margin-top: 10px;
        }

        /* Navigation Bar */
        nav {
            background-color: #9b1c1c; /* Red */
            padding: 12px 20px;
            text-align: center;
        }

        nav a {
            color: white;
            font-size: 1.2em;
            margin: 0 25px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            color: #d4af37; /* Gold */
            text-decoration: underline;
        }

        /* Contact Section */
        #contact {
            padding: 40px 20px;
            background-color: #ecf0f1;
            text-align: center;
        }

        #contact h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #9b1c1c; /* Red */
        }

        /* Contact Form */
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1.1em;
            background-color: #f5f5f5;
        }

        .contact-form button {
            background-color: #d4af37; /* Gold */
            padding: 15px 30px;
            color: white;
            font-size: 1.1em;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .contact-form button:hover {
            background-color: #9b1c1c; /* Red */
        }

        /* Contact Information */
        .contact-info {
            margin-top: 40px;
            font-size: 1.2em;
        }

        .contact-info p {
            margin: 10px 0;
        }

        /* Footer */
        footer {
            background-color: #9b1c1c; /* Red */
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 1em;
            margin-top: 40px;
        }

        footer p {
            margin: 10px 0;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            nav a {
                font-size: 1em;
                margin: 0 15px;
            }

            .contact-form {
                padding: 20px;
                margin: 0 10px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Renolt Restaurant</h1>
    <p>Exceptional Dining Experience</p>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">administration</a>
</nav>

<section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-form">
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

    <div class="contact-info">
        <p><strong>Address:</strong> 1234 Food Street, City, Country</p>
        <p><strong>Phone:</strong> (123) 456-7890</p>
        <p><strong>Email:</strong> info@renoltrestaurant.com</p>
    </div>
</section>

<footer>
    <p>&copy; 2024 Renolt Restaurant | All Rights Reserved</p>
    <p>1234 Food Street, City, Country</p>
    <p>Design and Developed by aaron alex</p>
</footer>

</body>
</html>
admin .html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Renolt Restaurant</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }

        /* Body and Background */
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            font-size: 16px;
            padding: 0;
            margin: 0;
        }

        /* Header */
        header {
            background: linear-gradient(45deg, #9b1c1c, #d4af37); /* Gold and Red gradient */
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            font-size: 4em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.3em;
            margin-top: 10px;
        }

        /* Navigation Bar */
        nav {
            background-color: #9b1c1c; /* Red */
            padding: 12px 20px;
            text-align: center;
        }

        nav a {
            color: white;
            font-size: 1.2em;
            margin: 0 25px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            color: #d4af37; /* Gold */
            text-decoration: underline;
        }

        /* Administration Section */
        #administration {
            padding: 40px 20px;
            background-color: #ecf0f1;
            text-align: center;
        }

        #administration h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: #9b1c1c; /* Red */
        }

        .team-members {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 40px;
            margin-top: 40px;
        }

        .team-member {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .team-member img {
            width: 100%;
            height: 200px; /* Adjust height as needed */
            object-fit: cover; /* Ensures the image maintains its aspect ratio and doesn't get distorted */
            margin-bottom: 20px;
        }

        .team-member h3 {
            font-size: 1.8em;
            color: #9b1c1c;
            margin-bottom: 10px;
        }

        .team-member p {
            font-size: 1.2em;
            color: #333;
        }

        /* Footer */
        footer {
            background-color: #9b1c1c; /* Red */
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 1em;
            margin-top: 40px;
        }

        footer p {
            margin: 10px 0;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            nav a {
                font-size: 1em;
                margin: 0 15px;
            }

            .team-members {
                grid-template-columns: repeat(2, 1fr);
                gap: 30px;
            }

            .team-member {
                padding: 15px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Renolt Restaurant</h1>
    <p>Exceptional Dining Experience</p>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
    <a href="administration.html">Administration</a>
</nav>

<section id="administration">
    <h2>Meet Our Team</h2>
    
    <div class="team-members">
        <!-- Team Member 1 -->
        <div class="team-member">
            <img src="b19.jpg" alt="Admin 1">
            <h3>John Doe</h3>
            <p>General Manager</p>
        </div>

        <!-- Team Member 2 -->
        <div class="team-member">
            <img src="b3.png" alt="Admin 2">
            <h3>Jane Smith</h3>
            <p>Operations Director</p>
        </div>

        <!-- Team Member 3 -->
        <div class="team-member">
            <img src="b4.png" alt="Admin 3">
            <h3>Mike Johnson</h3>
            <p>Head Chef</p>
        </div>

        <!-- Team Member 4 -->
        <div class="team-member">
            <img src="b12.jpg" alt="Admin 4">
            <h3>Emily Davis</h3>
            <p>Marketing Manager</p>
        </div>

        <!-- Team Member 5 -->
        <div class="team-member">
            <img src="b13.jpg" alt="Admin 5">
            <h3>Chris Williams</h3>
            <p>Customer Relations</p>
        </div>

        <!-- Team Member 6 -->
        <div class="team-member">
            <img src="b17.jpg" alt="Admin 6">
            <h3>Sarah Brown</h3>
            <p>Event Coordinator</p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Renolt Restaurant | All Rights Reserved</p>
    <p>1234 Food Street, City, Country</p>
    <p>design and developed by aaron alex</p>
</footer>

</body>
</html>
about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Renolt Restaurant</title>
    <style>
        /* Global Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }

        /* Body and Background */
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            font-size: 16px;
            padding: 0;
            margin: 0;
            background: #f5f5f5 url('watermark.png') no-repeat center center fixed; /* Add watermark image */
            background-size: 50%; /* Adjust size of watermark */
        }

        /* Header */
        header {
            background: linear-gradient(45deg, #9b1c1c, #d4af37); /* Gold and Red gradient */
            color: white;
            text-align: center;
            padding: 80px 20px;
            position: relative;
        }

        header h1 {
            font-size: 4em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.3em;
            margin-top: 10px;
        }

        /* Navigation Bar */
        nav {
            background-color: #9b1c1c; /* Red */
            padding: 12px 20px;
            text-align: center;
        }

        nav a {
            color: white;
            font-size: 1.2em;
            margin: 0 25px;
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            color: #d4af37; /* Gold */
            text-decoration: underline;
        }

        /* About Section */
        #about-us {
            padding: 80px 20px;
            text-align: center;
        }

        #about-us h2 {
            font-size: 2.5em;
            color: #9b1c1c; /* Red */
            margin-bottom: 30px;
        }

        #about-us p {
            font-size: 1.2em;
            line-height: 1.8;
            color: #555;
            margin-bottom: 30px;
            padding: 0 20px;
        }

        .about-img {
            width: 100%;
            height: 350px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 30px;
        }

        /* Footer */
        footer {
            background-color: #9b1c1c; /* Red */
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 1em;
            margin-top: 40px;
        }

        footer p {
            margin: 10px 0;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            nav a {
                font-size: 1em;
                margin: 0 15px;
            }

            #about-us h2 {
                font-size: 2em;
            }

            #about-us p {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Renolt Restaurant</h1>
    <p>Exceptional Dining Experience</p>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About Us</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">administration</a>
</nav>

<section id="about-us">
    <h2>About Renolt Restaurant</h2>
    <img src="a.jpg" alt="Restaurant Interior" class="about-img">
    <p>Welcome to Renolt Restaurant! We are a family-owned eatery known for serving the finest dishes made with love and the freshest ingredients. Our story began over a decade ago when we opened our doors with a single goal: to create a memorable dining experience for every guest.</p>
    <p>Our menu blends traditional recipes with modern techniques, and each dish is a reflection of our commitment to quality. Whether you're here for a casual meal or celebrating a special occasion, our team is dedicated to providing exceptional service and flavors that will leave you coming back for more.</p>
    <p>At Renolt Restaurant, we believe in not just serving food, but creating an experience that will linger long after the meal is over.</p>
</section>

<footer>
    <p>&copy; 2024 Renolt Restaurant | All Rights Reserved</p>
    <p>1234 Food Street, City, Country</p>
    <p>design and developed by aaron alex</p>
</footer>

</body>
</html>


```

## OUTPUT:
![Screenshot (68)](https://github.com/user-attachments/assets/884512a4-325a-441f-92af-b329ba40b00f)
![Screenshot (69)](https://github.com/user-attachments/assets/e00a38ce-e4ed-4a06-9b76-31ec49cbb069)
![Screenshot (70)](https://github.com/user-attachments/assets/5d68c199-9f27-4dfe-9b7f-e1ad4e31da1c)
![Screenshot (71)](https://github.com/user-attachments/assets/cb4055b5-426d-4c2d-af90-286f55542e6a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
