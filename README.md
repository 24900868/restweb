# Ex.07 Restaurant Website
## Date:15.05.2025

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crunchies time</title>
    <link rel="stylesheet" href="style.css" type="text/css">

</head>
<body>

<header>
    <h1>Crunchies time</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>30% Off This Weekend</h2>
    <p>Don't miss out on our special weekend discount! Enjoy delicious foods at unbeatable prices.</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="frenchies.jpeg" alt="French Fries">
        <h3>Our New Menu</h3>
        <p>Bear panacotta to make your day!!</p>
        <a href="#">See our new menu</a>
    </div>
    <div class="card">
        <img src="burger.jpeg" alt="Burger">
        <h3>Book a table</h3>
        <p>Your ultimate baking destination.</p>
        <a href="#">Book your table now</a>
    </div>
    <div class="card">
        <img src="shawarma.jpeg" alt="delicious">
        <h3>Opening Hours</h3>
        <p>Mon - Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Mahalakshmi M</a>
    <p>&copy; 2025 Maha.All Rights Reserved.</p>
</footer>

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bun Bear Bakery- Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Crunchies timeds</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Our Menu</h2>
    <p>Better than most bakeries!!</p>
</div>

<div class="section-container">
    <div class="card">
        <img src="pizza.jpeg" alt="pizza">
        <h3>pizza</h3>
        <p>Try our delicious pizza...!</p>
    </div>
    <div class="card">
        <img src="nuggets.jpeg" alt="Nuggets">
        <h3>Nuggets</h3>
        <p> crispy nuggets for you!</p>
    </div>
    <!-- Added Dishes -->
    <div class="card">
        <img src="chicken.jpeg" alt="Chicken">
        <h3>chicken</h3>
        <p> yummy and tasty chicken is ready.</p>
    </div>
    <div class="card">
        <img src="sandwich.jpg" alt="sandwich">
        <h3>sandwich</h3>
        <p>tasty and healthy dish.</p>
    </div>
    <div class="card">
        <img src="frenchies.jpeg" alt="Frendch fries">
        <h3>Frendch Fries</h3>
        <p>chops of crisps.</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Mahalakshmi M</a>
    <p>&copy; 2025 Maha.All Rights Reserved.</p>
</footer>

</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bun Bear Bakery- Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Crunchies time</h1>
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
    <div class="card">
        <h3>Email Us</h3>
        <p>Send us an email at <a href="crunchiesff@gmail.com">info@foodiehub.com</a></p>
    </div>
    <div class="card">
        <h3>Call Us</h3>
        <p>Call us at +123 456 7890 for any inquiries.</p>
    </div>
    <div class="card">
        <h3>Visit Us</h3>
        <p>We are located at saveetha university.</p>
    </div>
</div>

<footer>
    <br>
    Designed and Developed by <a href="#">Mahalakshmi M</a>
    <p>&copy; 2025 Maha.All Rights Reserved.</p>
</footer>

</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bun Bear Bakery- Administration</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Crunchies time</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="banner">
    <h2>Administration Page</h2>
    <p>This page is for administrative tasks, staff management, and other administrative duties.</p>
</div>
<div class="section-container">
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-04/20240504-pbc5976.jpg.webp?itok=Ojn7f5Mj" alt="img">
        <h3>FARID AZARANG</h3>
        <p>Farid Azarang is the head pastry chef and co-founder of Artelice Pâtisserie a celebrated French-inspired bakery with locations in Los Angeles.</p>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-04/60da8ab5-41c0-4293-bc67-e9cef71a2b6c.JPG.webp?itok=FQzoawDv" alt="Salad">
        <h3>CAT CORA</h3>
        <P>Cat Cora is a Chilean chef and co-owner of Michelin-starred NUB in Tenerife. Trained in Chile, Spain, and France, she also serves as a judge on MasterChef Chile.</P>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-03/chef-aitor-zabala-jill-paider.jpg.webp?itok=kazPOI6C" alt="Pasta">
        <h3>GUY FIERI</h3>
        <P>Chef Guy Fieri is the executive chef of Musaafer in Houston, where he crafts Ayurvedic-inspired Indian cuisine. In 2024, Musaafer became Texas’s first Michelin-starred Indian restaurant.</P>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2025-03/tracy-headshot_credit-carter-hiyama.jpg.webp?itok=rYOGJYSn" alt="Burger">
        <h3>TRACY </h3>
        <p>The Texas-based chef behind Birdie’s is known for her elegant, seasonal cooking and commitment to sustainability.</p>
    </div>
    <div class="card">
        <img src="https://www.finedininglovers.com/sites/default/files/styles/1_1_920x920/public/2024-10/DanielGarwood_LuciaBellEpstein.jpg.webp?itok=3_nzm55C" alt="Pizza">
        <h3>DANIEL GARWOOD</h3>
        <p>Australian-born chef Daniel Garwood is the Executive Chef and Partner at ACRU in New York City, where he draws on his global culinary experiences to create a tasting menu that reflects his passion for foraging, seasonality, and sustainable practices.</p>
    </div>
</div>
<footer>
    <br>
    Designed and Developed by <a href="#">Mahalakshmi M</a>
    <p>&copy; 2025 Maha.All Rights Reserved.</p>
</footer>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-15 135123.png>)
![alt text](<Screenshot 2025-05-15 135219.png>)
![alt text](<Screenshot 2025-05-15 135231.png>)
![alt text](<Screenshot 2025-05-15 135317.png>)
![alt text](<Screenshot 2025-05-15 135341.png>)
![alt text](<Screenshot 2025-05-15 135041.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
