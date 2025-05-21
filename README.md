# Ex.07 Restaurant Website
## Date:21/05/2025

NAME: S.Magesh

REG.NO: 212224040180

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
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>


    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FUSION FEAS</title>
</head>

<style>

    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #dee1bde2;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    background-color: rgb(152, 69, 116);
    border-radius: 10px;
}

.menu{
    background-color: rgb(118, 193, 173);
    align-items: center;
    color: rgb(146, 89, 114);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 80px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    font-family: 'Times New Roman', Times, serif;
    font-size: large;
    color: #0f1110;
    font-weight: bold;
}

.offer-txt{
    color: rgba(11, 22, 228, 0.47);
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background-image: url("Rest background.jpg");
    padding: 10px 40px;
    color: #4f9797;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(52, 179, 162);
}

.feature {
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    font-size: large;
    background-color: rgb(132, 171, 169);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgb(177, 98, 191);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: rgb(121, 173, 165);
}
    

</style>
<body>
    <header>
        <div class="logo">
            <img src="Fusion feast logo.jpg" alt="FUSION FEAST Logo">
            <h1 style="font-family: 'Times New Roman', Times, serif;"> FUSION FEAST </h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        
        <section class="banner" style="background-image: url(homepage.jpg)";>         
             <h2 class="offer-txt style="font-family: 'Times New Roman', Times, serif;">Better taste to make you better</h2>
            <h2 class="offer-txt" style="font-family: 'Times New Roman', Times, serif;"> WELCOMING YOU TO THE FUSION FEAST -THE INDIAN RESTAURANT! </h2>
            
            <p class = 'offer-txt' style="font-size: large ; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">The World's No. 1 high quality Indian Restaurant.As gentle as a mother's love...
            Food is better when we eat together...Come hungry leave happy...Because we care for your taste..A place to provide you with the best....</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Today's menu</h3>
                <img src="food items.jpg" alt="Our New Menu">
                <p> Today’s menu offers a variety of dishes made with fresh ingredients. Enjoy flavorful starters, delicious main courses, indulgent desserts, chef’s specials, and refreshing drinks. 
                    Every bite is crafted to delight your taste buds!</p>
                
            </div>
            <div class="feature">
                <h3>Book a table</h3>
                <img src="Book a table.jpg" alt="Book a table">
                <p>Reserve your table at Fusion feast for a memorable dining experience. Whether it’s a dinner, celebration, or casual gathering, enjoy our warm ambiance and delicious flavors.
                     Book now for the perfect meal!!</p>
                
            </div>
            <div class="feature">
                <h3>Opening timings</h3>
                <img src="Opening hours.jpg" class="hours" alt="Opening Hours">
                <p> Visit us during our convenient hours</p>
                <ul>
                    Monday - Friday: 07:00 AM - 02:00 AM <br>
                    Saturday: 07:00 AM - 11:00 PM <br>
                    Sunday: 07:00 AM - 10:00 PM <br>
                </ul>
                <p> A place for hungry people....!</p>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="Fusion feast logo.jpg" class="footer" alt="Fusion feast Logo">
            </div>
            
                <palign="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by G.Sindhu Priya Reddy</h3>
        </footer>
    </main>
</body>
</html>

home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME</title>
</head>
<div class="logo">
    <top left>
    <img src="Fusion feast logo.jpg" width="50" height="50"alt="FUSION FEAST Logo">
</top left>

</div>
    <div class="nav-list">
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact us</a>
    </div>


<style>
    header{
        font-size: 50px;
        font-style:initial;
        background-color: rgb(221, 172, 233);
    }
    .content{
        font-size: medium;
        padding: 10px;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
    }
</style>


<body bgcolor="lavender">
    <center>
        <header style="color: rgb(35, 62, 195);">
        FUSION FEAST
        </header>

        <img src="restaurant .jpg" width="500" height="400">
        
        <div class="content">
        <h2> Welcome to FUSION FEAST Restaurant- A place where taste meets your expectations!!</h2>
        <h2>A short note about fusion feast</h2>
        <p style="font-family:cursive; font-size: large;">
            As you step into FUSION FEAST, you’re greeted by a cozy and inviting atmosphere. Soft, golden light from elegant chandeliers fills the room, highlighting the warm 
            and plush furnishings.The air is filled with the irresistible aroma of freshly baked bread, exotic spices, and slow-cooked dishes, setting the stage for an 
            unforgettable dining experience.The menu offers a delightful mix of global flavors, expertly prepared by skilled chefs. Each dish is beautifully presented, 
            with a perfect blend of textures and flavors that will excite your taste buds. At FUSION FEAST, every meal is more than just food—it’s an experience that
            surprises and delights, leaving you wanting more.Come and enjoy a world of delicious flavors and spices that will make your visit truly special!
            Many traditional dishes are prepared with fresh, locally sourced ingredients that bring out the genuine flavors of the cuisine.This not only ensures 
            quality but also supports local farmers and producers.We are serving traditional dishes often by using age-old techniques, like slow cooking, wood-fire roasting,
             fermenting, or clay pot cooking,to achieve the original taste and texture.The experience of traditional dining extends to the ambiance, often featuring decor, music,
              and even tableware inspired by the culture being celebrated.We often feature dishes specific to festivals or seasons, such as Christmas roasts, Ramadan delicacies, 
              or spring harvest specials.
        </p>
        </div>

        <div class="content">
            
            <img src="Locally sourced ingredients.jpg" width="300" height="200">
            <img src="Traditional cooking tech.jpg" width="300" height="200">
            <img src="Ambiance n experience.jpg" width="300" height="200">
            <img src="seasonal fests.jpg" width="300" height="200">
            
        </div>
        <footer>
            
                <p align="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by G.Sindhu Priya Reddy</h3>
        </footer>
    </center>
    <div class="logo">
        <img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
    </div>
    

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <div class="logo">
        <img src="Fusion feast logo.jpg" width="50" height="50" alt="FUSION FEAST Logo">
    </div>
    <title>FUSION FEAST - Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #2c3e50;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .menu-container {
            padding: 40px 20px;
            background: #ffffff;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 30px;
            font-family: 'Playfair Display', serif;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 15px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: left;
        }

        .menu-item img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .menu-item:hover img {
            transform: scale(1.1);
        }

        .menu-details {
            padding: 15px;
        }

        .menu-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 10px;
            font-weight: 500;
        }

        .menu-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1.1rem;
            color: #e74c3c;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>FUSION FEAST</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact us</a>
            
        </nav>
    </header>

    <div class="menu-container">
        <h1>OUR MENU</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="Baby corn salt pepper.jpg" alt="Baby corn salt pepper">
                <div class="menu-details">
                    <h3>Baby corn salt pepper</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Veg momos.jpg" alt="Veg momos">
                <div class="menu-details">
                    <h3>Veg momos</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Aloo tikki.jpg" alt="Aloo tikki">
                <div class="menu-details">
                    <h3>Aloo tikki</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Prawn fry.jpg" alt="Prawn fry">
                <div class="menu-details">
                    <h3>Prawn fry</h3>
                    <p class="price">₹180/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Fish fry.jpg" alt="Fish fry">
                <div class="menu-details">
                    <h3>Fish fry</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Tandoori chicken.jpg" alt="Tandoori chicken">
                <div class="menu-details">
                    <h3>Tandoori chicken</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            
            <div class="menu-item">
                <img src="South indian meals.jpg" alt="South indian meals">
                <div class="menu-details">
                    <h3>South indian meals</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Avakai annam.jpg" alt="Avakai annam">
                <div class="menu-details">
                    <h3>Avakai annam</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="Veg biriyani.jpg" alt="Veg biriyani">
                <div class="menu-details">
                    <h3>Veg biriyani</h3>
                    <p class="price">₹200/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Curd rice.jpg" alt="Curd rice">
                <div class="menu-details">
                    <h3>Curd rice</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Avakai chicken biriyani.jpg" alt="Avakai chicken biriyani">
                <div class="menu-details">
                    <h3>Avakai chicken biriyani</h3>
                    <p class="price">₹250/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Mutton biriyani.jpg" alt="Mutton biriyani">
                <div class="menu-details">
                    <h3>Mutton biriyani</h3>
                    <p class="price">₹350/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Prawn biriyani.jpg" alt="Prawn biriyani">
                <div class="menu-details">
                    <h3>Prawn biriyani</h3>
                    <p class="price">₹350/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Ragi sangati-natukodi .jpg" alt="Ragi sangati-natukodi">
                <div class="menu-details">
                    <h3>Ragi sangati-natukodi</h3>
                    <p class="price">₹250/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Oreo milkshake.jpg" alt="Oreo milkshake">
                <div class="menu-details">
                    <h3>Oreo milkshake</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Chocolate milkshake.jpg" alt="Chocolate milkshake">
                <div class="menu-details">
                    <h3>Chocolate milkshake</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Ferrero rocher shake.jpg" alt="Ferrero rocher shake">
                <div class="menu-details">
                    <h3>Ferrero rocher shake</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Dry fruit shake.jpg" alt="Dry fruit shake">
                <div class="menu-details">
                    <h3>Dry fruit shake</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Mint cooler.jpg" alt="Mint cooler">
                <div class="menu-details">
                    <h3>Mint cooler</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Ultra lime.jpg" alt="Ultra lime">
                <div class="menu-details">
                    <h3>Ultra lime</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            
            <div class="menu-item">
                <img src="Hot chocolate.jpg" alt="Hot chocolate">
                <div class="menu-details">
                    <h3>Hot chocolate</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="cappuccino.jpg" alt="cappuccino">
                <div class="menu-details">
                    <h3>cappuccino</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Irani chai.jpg" alt="Irani chai">
                <div class="menu-details">
                    <h3>Irani chai</h3>
                    <p class="price">₹50/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Cold coffee.jpg" alt="Cold coffee">
                <div class="menu-details">
                    <h3>Cold coffee</h3>
                    <p class="price">₹90/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Falooda.jpg" alt="Falooda">
                <div class="menu-details">
                    <h3>Falooda</h3>
                    <p class="price">₹75/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Badam milk.jpg" alt="Badam milk">
                <div class="menu-details">
                    <h3>Badam milk</h3>
                    <p class="price">₹50/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Sizzling brownie.jpg" alt="Sizzling brownie">
                <div class="menu-details">
                    <h3>Sizzling brownie</h3>
                    <p class="price">₹150/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Rasmalai.jpg" alt="Rasmalai">
                <div class="menu-details">
                    <h3>Rasmalai</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Gulab jamun.jpg" alt="Gulab jamun">
                <div class="menu-details">
                    <h3>Gulab jamun</h3>
                    <p class="price">₹50/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Kheer.jpg" alt="Kheer">
                <div class="menu-details">
                    <h3>Kheer</h3>
                    <p class="price">₹85/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Junnu.jpg" alt="Junnu">
                <div class="menu-details">
                    <h3>Junnu</h3>
                    <p class="price">₹65/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="Ice cream .jpg" alt="Ice cream">
                <div class="menu-details">
                    <h3>Ice cream</h3>
                    <p class="price">₹70/-</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
            
        <p align="center" class="copy">&copy; Copyright Fusion feast</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by G.Sindhu Priya Reddy</h3>
</footer>
</center>
<div class="logo">
<img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
</div>


</body>
</html>

admin.html

<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #edafe1;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background-color: #000000;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: rgb(49, 140, 140);
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgb(222, 201, 222);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .team-section {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .team-member {
            text-align: center;
            background: #55aea8;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .team-member img {
            width: 100%;
            height: 80%;
            max-width: 150px;
            border-radius: 20%;
            margin-bottom: 10px;
        }
        .team-member h3 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .team-member p {
            font-size: 0.9em;
            padding-bottom: 15px;
            color: #0c0b0c;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
 </head>
 <body>
    <header>
        <top left>
        <div class="logo">
            <img src="Fusion feast logo.jpg" width="100" height="100" alt="FUSION FEAST Logo">
        <h1>Administration</h1>
    </top left>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <main>
        <div class="container">
            <center>
            <h2>OUR TEAM</h2>
        </center>
            <div class="team-section">
                <div class="team-member">
                    <img src="founder.jpg"alt="founder.jpg">
                    <h3>G Prasad Reddy-Founder</h3>
                    
                </div>
                <div class="team-member">
                    <img src="co-founder.jpg" alt="co-founder.jpg">
                    <h3>G.Sindhu Priya Reddy-co-founder</h3>
                
                </div>
                <div class="team-member">
                    <img src="Hari nayak.jpg" alt="Hari nayak.jpg">
                    <h3>Hari nayak-Marketing director</h3>
                   
                </div>
                <div class="team-member">
                    <img src="Ranveer brar.jpg" alt="Ranveer brar.jpg">
                    <h3>Ranveer brar-Manager</h3>

                </div>
                <div class="team-member">
                    <img src="Saransh goila.jpg" alt="Saransh goila.jpg">
                    <h3>Saransh goila-Master Chef</h3>
            
                </div>
                <div class="team-member">
                    <img src="Koushik S.jpg" alt="Koushik S.jpg">
                    <h3>Koushik S-Master chef</h3>
                    
                </div>
                <div class="team-member">
                    <img src="Harphal  singh sokhi.jpg" alt="Harphal singh sokhi.jpg">
                    <h3>Harphal singh sokhi-Chef</h3>
                    
                </div>
                <div class="team-member">
                    <img src="Vikas khanna.jpg" alt="Vikas khanna.jpg">
                    <h3>Vikas khanna-Chef</h3>
                    
                </div>
                <div class="team-member">
                    <img src="Vineet bhatia.jpg" alt="Vineet bhatia.jpg">
                    <h3>Vineet bhatia-Chef</h3>
                    
                </div>
            </div>
        </div>
        <footer>
            <div class="logo">
                <img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
            </div>
            
                <palign="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by G.Sindhu Priya Reddy</h3>
        </footer>
    </main>
 </body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Contact Us - Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
             <center>
            <div class="logo">
                <img src="Fusion feast logo.jpg" width="100" height="100" alt="FUSION FEAST Logo">
            </center>
            <h1>FUSION FEAST</h1>
        <div class="container">
            <h1>Contact us</h1>
            <nav>
                <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact us</a></li>
                </ul>
            </nav>
        </div>
    </header>
<style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #66c0ca;
    color: #1956cf;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #d8a2e6;
    padding: 20px 0;
    color: #fff;
}

header h1 {
    text-align: center;
    font-size: 2.5em;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-size: 1.2em;
}

nav ul li a:hover {
    text-decoration: underline;
}

.contact-us {
    background-color: #fff;
    padding: 40px 0;
    margin-top: 20px;
}

.contact-us h2 {
    text-align: center;
    font-size: 2.5em;
    margin-bottom: 20px;
}

.contact-us p {
    text-align: center;
    font-size: 1.2em;
    margin-bottom: 40px;
}

form {
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
    background-color: #ecf0f1;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    font-size: 1.1em;
    margin-bottom: 5px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    font-size: 1em;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin-top: 5px;
}

button {
    width: 100%;
    padding: 12px;
    background-color: #27dcd3;
    color: #fff;
    font-size: 1.2em;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #2775c4;
}

footer {
    background-color: #5b7fa2;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 40px;
}

</style>
    <section class="contact-us">
        <div class="container">
            <h2>Contact Us</h2>
            <p>"We'd love to hear from you! Need a reservation or have a query?"</p>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                </div>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
    <footer>
        <h1>Address-vkota,chittoor district</h1>
        <h1>email-fusionfeast@gmail.com</h1>
        <h1>Phone-+919390456730</h1>
          <h2>Food that not only satisfies your hunger but also your soul</h2>  
        <p align="center" class="copy">&copy; Copyright Fusion feast</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by s.Magesh</h3>
</footer>
    

</body>
</html>
```
## OUTPUT:
![Screenshot 2025-05-09 204951](https://github.com/user-attachments/assets/13bcaa5e-b5ee-4fe9-a031-c57b9afce6f0)
![Screenshot 2025-05-09 205159](https://github.com/user-attachments/assets/4e3e25f3-82b7-4ea8-ac1b-902efbbf1786)
![Screenshot 2025-05-09 211950](https://github.com/user-attachments/assets/732f9be9-4d52-4b96-b28a-4eac3558c8a0)
![Screenshot 2025-05-02 220847](https://github.com/user-attachments/assets/d079fab5-1cff-484e-b04b-7022e4b3c352)
![Screenshot 2025-05-02 220753](https://github.com/user-attachments/assets/a9344162-f2e6-4969-b15e-ededaa1692c3)
![Screenshot 2025-05-02 221753](https://github.com/user-attachments/assets/87de9567-f4ef-4d08-a569-bdac86980d7c)
![Screenshot 2025-05-02 221832](https://github.com/user-attachments/assets/4fdd35d9-fe91-4d05-b217-9412866132ae)
![Screenshot 2025-05-02 221906](https://github.com/user-attachments/assets/c59b4d9b-7422-4a42-845b-4dcc2b15daaf)
![Screenshot 2025-05-02 222041](https://github.com/user-attachments/assets/d9fca0b4-833a-4861-a5d1-769260965217)
![Screenshot 2025-05-02 222114](https://github.com/user-attachments/assets/04bd9597-566c-4fd2-b2ad-9964401d5c03)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
