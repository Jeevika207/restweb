# Ex.07 Restaurant Website
## Date: 12/05/2025

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie Hub - Home</title>
    <style>
        html, body {
            height: 100%;
            margin: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #9a9a9a;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 5px;
            font-size: 0.9em;
            margin-top: auto; 
        }
        footer a {
            color: rgb(208, 255, 0);
            text-decoration: none;
            font-weight: bold;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        header {
            text-align: center;
            padding: 20px;
        }
        header h1 {
            display: inline-block;
            margin: 0;
            font-size: 2em;
            vertical-align: middle;
        }
        .banner {
            background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        .banner h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }
        .section-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 40px 20px;
        }
        .card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .card img {
            width: 100%;
            max-width: 300px;
            max-height: 200px;
            height: auto;
            border-radius: 10px;
            object-fit: cover;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
        .card h3 {
            margin-top: 15px;
            color: #333;
        }
        .card p {
            font-size: 0.9em;
            color: #666;
            margin: 10px 0;
        }
        .card a {
            color: blue;
            text-decoration: underline;
            font-size: 0.9em;
        }
        @media (max-width: 600px) {
            .section-container {
                flex-direction: column;
                align-items: center;
            }
            .card {
                width: 90%;
                max-width: 350px;
            }
            .card img {
                max-width: 100%;
                max-height: 150px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>30% Off This Weekend</h2>
    <p>Don't miss out on our special weekend discount! Enjoy delicious meals at unbeatable prices.</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1642026465180-5e25255838e9" alt="Grilled Food">
        <h3>Our New Menu</h3>
        <p>Discover our latest culinary creations, crafted with passion and fresh ingredients.</p>
        <a href="menu.html">See our new menu</a>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1551183053-bf91a1d81141" alt="Salad">
        <h3>Book a Table</h3>
        <p>Reserve your spot for a delightful dining experience at Foodie Hub.</p>
        <a href="contact.html">Book your table now</a>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1651977560788-98792cd34da0" alt="Chef Cooking">
        <h3>Opening Hours</h3>
        <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Jeevika R</a>
    <p>&copy; 2025 Jeevika R. All Rights Reserved.</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie Hub - Menu</title>
    <style>
        html, body {
            height: 100%;
            margin: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #9a9a9a;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 5px;
            font-size: 0.9em;
            margin-top: auto; 
        }
        footer a {
            color: rgb(208, 255, 0);
            text-decoration: none;
            font-weight: bold;
        }
        nav {
            background-color: #333;
            padding: 8px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1em;
        }
        header {
            text-align: center;
            padding: 12px;
        }
        header h1 {
            display: inline-block;
            margin: 0;
            font-size: 1.5em;
            vertical-align: middle;
        }
        .banner {
            background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 24px 10px;
            text-align: center;
        }
        .banner h2 {
            font-size: 1.4em;
            margin-bottom: 5px;
        }
        .banner p {
            font-size: 1em;
            margin: 0;
        }
        .section-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 12px;
            margin: 18px 6px;
        }
        .card {
            background: white;
            border-radius: 8px;
            padding: 10px;
            width: 180px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.08);
            text-align: center;
        }
        .card img {
            width: 100%;
            max-width: 160px;
            max-height: 90px;
            height: auto;
            border-radius: 7px;
            object-fit: cover;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
        .card h3 {
            margin: 8px 0 5px 0;
            color: #333;
            font-size: 1.07em;
        }
        .card p {
            font-size: 0.85em;
            color: #666;
            margin: 6px 0;
        }
        @media (max-width: 700px) {
            .section-container {
                flex-direction: column;
                align-items: center;
            }
            .card {
                width: 95%;
                max-width: 240px;
            }
            .card img {
                max-width: 100%;
                max-height: 80px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Our Menu</h2>
    <p>Explore our delightful range of dishes!</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1661310019346-4cb563a19aec" alt="Grilled Chicken">
        <h3>Grilled Chicken</h3>
        <p>Juicy, perfectly seasoned grilled chicken.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1738486511470-471be341a1e3" alt="Caesar Salad">
        <h3>Caesar Salad</h3>
        <p>Romaine, parmesan, croutons, Caesar dressing.</p>
    </div>
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1705947846996-2887733378a3" alt="Spaghetti Carbonara">
        <h3>Spaghetti Carbonara</h3>
        <p>Classic pasta with creamy sauce and bacon.</p>
    </div>
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1661387558893-63d24776cf38" alt="Cheese Burger">
        <h3>Cheese Burger</h3>
        <p>Beef patty, cheddar, lettuce, tomato, sauce.</p>
    </div>
    <div class="card">
        <img src="https://plus.unsplash.com/premium_photo-1733306588881-0411931d4fed" alt="Margherita Pizza">
        <h3>Margherita Pizza</h3>
        <p>Wood-fired pizza with tomato, mozzarella, basil.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" alt="Fresh Sushi">
        <h3>Fresh Sushi</h3>
        <p>Assorted sushi rolls with fresh ingredients.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1519864600265-abb23847ef2c" alt="Tomato Soup">
        <h3>Tomato Soup</h3>
        <p>Creamy tomato soup with garlic bread.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1502741338009-cac2772e18bc" alt="Grilled Steak">
        <h3>Grilled Steak</h3>
        <p>Steak grilled to perfection, served with fries.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1464306076886-debca5e8a6b0" alt="Pancakes">
        <h3>Blueberry Pancakes</h3>
        <p>Pancakes with blueberries and maple syrup.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1516684669134-de6f27e8ea27" alt="Ice Cream">
        <h3>Ice Cream Sundae</h3>
        <p>Vanilla ice cream, chocolate sauce, nuts, cherry.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1467003909585-2f8a72700288" alt="Chocolate Lava Cake">
        <h3>Chocolate Lava Cake</h3>
        <p>Warm chocolate cake with molten center.</p>
    </div>
    <div class="card">
        <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" alt="Vegetarian Sushi">
        <h3>Vegetarian Sushi</h3>
        <p>Fresh veggie rolls with rice and seaweed.</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Jeevika R</a>
    <p>&copy; 2025 Jeevika R. All Rights Reserved.</p>
</footer>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie Hub - Administration</title>
    <style>
        html, body {
            height: 100%;
            margin: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #9a9a9a;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 5px;
            font-size: 0.9em;
            margin-top: auto; 
        }
        footer a {
            color: rgb(208, 255, 0);
            text-decoration: none;
            font-weight: bold;
        }
        nav {
            background-color: #333;
            padding: 8px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1em;
        }
        header {
            text-align: center;
            padding: 12px;
        }
        header h1 {
            display: inline-block;
            margin: 0;
            font-size: 1.5em;
            vertical-align: middle;
        }
        .banner {
            background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 24px 10px;
            text-align: center;
        }
        .banner h2 {
            font-size: 1.4em;
            margin-bottom: 5px;
        }
        .banner p {
            font-size: 1em;
            margin: 0;
        }
        .section-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 12px;
            margin: 18px 6px;
        }
        .card {
            background: white;
            border-radius: 8px;
            padding: 10px;
            width: 180px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.08);
            text-align: center;
        }
        .card img {
            width: 100%;
            max-width: 100px;
            max-height: 100px;
            height: auto;
            border-radius: 50%;
            object-fit: cover;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
        .card h3 {
            margin: 8px 0 2px 0;
            color: #333;
            font-size: 1.07em;
        }
        .card p {
            font-size: 0.85em;
            color: #666;
            margin: 4px 0;
        }
        .card .role {
            font-weight: bold;
            color: #208fff;
            margin-bottom: 3px;
        }
        @media (max-width: 700px) {
            .section-container {
                flex-direction: column;
                align-items: center;
            }
            .card {
                width: 95%;
                max-width: 240px;
            }
            .card img {
                max-width: 80px;
                max-height: 80px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Administration</h2>
    <p>Meet our talented management and kitchen team!</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="https://images.pexels.com/photos/614810/pexels-photo-614810.jpeg?auto=compress&w=100&h=100&fit=crop" alt="Rahul Sharma">
        <h3>Rahul Sharma</h3>
        <div class="role">General Manager</div>
        <p>Ensures smooth operations and top service.</p>
    </div>
    <div class="card">
        <img src="https://images.pexels.com/photos/1130626/pexels-photo-1130626.jpeg?auto=compress&w=100&h=100&fit=crop" alt="Ananya Singh">
        <h3>Ananya Singh</h3>
        <div class="role">Head Chef</div>
        <p>Leads the kitchen and creates new recipes.</p>
    </div>
    <div class="card">
        <img src="https://images.pexels.com/photos/91227/pexels-photo-91227.jpeg?auto=compress&w=100&h=100&fit=crop" alt="Vikram Patel">
        <h3>Vikram Patel</h3>
        <div class="role">Sous Chef</div>
        <p>Assists in menu and kitchen management.</p>
    </div>
    <div class="card">
        <img src="https://images.pexels.com/photos/733872/pexels-photo-733872.jpeg?auto=compress&w=100&h=100&fit=crop" alt="Priya Desai">
        <h3>Priya Desai</h3>
        <div class="role">Pastry Chef</div>
        <p>Makes all our desserts and baked goods.</p>
    </div>
    <div class="card">
        <img src="https://images.pexels.com/photos/91224/pexels-photo-91224.jpeg?auto=compress&w=100&h=100&fit=crop" alt="Arjun Mehra">
        <h3>Arjun Mehra</h3>
        <div class="role">Floor Manager</div>
        <p>Manages the dining area and customers.</p>
    </div>
    <div class="card">
        <img src="https://images.pexels.com/photos/774909/pexels-photo-774909.jpeg?auto=compress&w=100&h=100&fit=crop" alt="Sneha Iyer">
        <h3>Sneha Iyer</h3>
        <div class="role">Marketing Head</div>
        <p>Leads marketing and social media.</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Jeevika R</a>
    <p>&copy; 2025 Jeevika R. All Rights Reserved.</p>
</footer>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie Hub - Contact Us</title>
    <style>
        html, body {
            height: 100%;
            margin: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #9a9a9a;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        footer {
            background-color: #333;
            color: #ccc;
            text-align: center;
            padding: 5px;
            font-size: 0.9em;
            margin-top: auto; 
        }
        footer a {
            color: rgb(208, 255, 0);
            text-decoration: none;
            font-weight: bold;
        }
        nav {
            background-color: #333;
            padding: 8px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1em;
        }
        header {
            text-align: center;
            padding: 12px;
        }
        header h1 {
            display: inline-block;
            margin: 0;
            font-size: 1.5em;
            vertical-align: middle;
        }
        .banner {
            background-image: url('https://plus.unsplash.com/premium_photo-1661883237884-263e8de8869b');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 24px 10px;
            text-align: center;
        }
        .banner h2 {
            font-size: 1.4em;
            margin-bottom: 5px;
        }
        .banner p {
            font-size: 1em;
            margin: 0;
        }
        .section-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 12px;
            margin: 18px 6px;
        }
        .card {
            background: white;
            border-radius: 8px;
            padding: 10px;
            width: 180px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.08);
            text-align: center;
        }
        .card img {
            width: 100%;
            max-width: 100px;
            max-height: 100px;
            height: auto;
            border-radius: 50%;
            object-fit: cover;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
        .card h3 {
            margin: 8px 0 2px 0;
            color: #333;
            font-size: 1.07em;
        }
        .card p {
            font-size: 0.85em;
            color: #666;
            margin: 6px 0;
        }
        @media (max-width: 700px) {
            .section-container {
                flex-direction: column;
                align-items: center;
            }
            .card {
                width: 95%;
                max-width: 240px;
            }
            .card img {
                max-width: 80px;
                max-height: 80px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Foodie Hub</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Contact Us</h2>
    <p>Have any questions? Get in touch with us!</p>
</div>

<div class="section-container">
    <!-- Founder/Contact Person Card -->
    <div class="card">
        <img src="https://pplx-res.cloudinary.com/image/upload/v1747066938/user_uploads/66657936/e1ceee67-cbc6-4326-a665-6f8bae357952/Picsart_25-05-12_21-52-09-421.jpg" alt="Jeevika R">
        <h3>Jeevika R</h3>
        <p>Founder & Contact Person</p>
    </div>
    <div class="card">
        <h3>Email Us</h3>
        <p>
            <a href="mailto:info@foodiehub.com">info@foodiehub.com</a>
        </p>
    </div>
    <div class="card">
        <h3>Call Us</h3>
        <p>+123 456 7890</p>
    </div>
    <div class="card">
        <h3>Visit Us</h3>
        <p>123 Lemon Street,<br>Fruit City</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Jeevika R</a>
    <p>&copy; 2025 Jeevika R. All Rights Reserved.</p>
</footer>

</body>
</html>

```


## OUTPUT:
![image](https://github.com/user-attachments/assets/19bdeb69-9375-4e46-9e44-f5ec2030d815)
![image](https://github.com/user-attachments/assets/e361a8ea-038d-4b10-bc65-b0c08be3a459)
![image](https://github.com/user-attachments/assets/f7cdae57-9249-4a36-a93a-ba63dbdce11f)
![image](https://github.com/user-attachments/assets/fc311595-826b-4304-82ff-6c91ca829235)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
