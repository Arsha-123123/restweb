# Ex.07 Restaurant Website
## Date:27/12/2024

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
index.html

<!DOCTYPE html>
 <html lang="en">
 <head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Icy Kingdom</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #12e9ed;
    }
    header {
      background-color:#e9e90b;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #ccc;
    }
    header img {
      height: 50px;
      vertical-align: middle;
    }
    header h1 {
      display: inline;
      margin-left: 10px;
      font-size: 24px;
      color: #333;
    }
    nav {
      background-color: #333;
      overflow: hidden;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;   
      display: block;
      float:left;
      
    }
    nav a:hover {
      background-color: #575757;
    }
    .content {
      display: flex;
      justify-content: space-around;
      padding: 20px;
    }
    .content div {
      background-color: #f8f8f8;
      padding: 20px;
      margin: 10px;
      flex: 1;
      text-align: center;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
  </style>
 </head>
 <body>
  <header>
    <img src="logo.jpg"height ="100" width = "70" alt="Icy Kingdom Logo">
    <br>
    <h1><font face="Goudy Oid Style Italic"size="7">Icy Kingdom </font
  </header>
  <nav>
    <a href="index.html" >Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="content">
    <div>
      <h3>Our New Menu</h3>
      <img src="menu image.jpg" alt="Menu img 1" height="200" width="200">
      <p>Discover our latest dishes with unique flavors!</p>
      <a href="menu.html">See our menu</a>
    </div>
    <div>
      <h3>Book a Table</h3>
      <img src="table.jpeg" alt="Menu img 1" height="200" width="200">
      <p>Reserve your spot to enjoy a delightful dining experience.</p>
      <a href="contact.html">Book now</a>
    </div>
    <div>
      <h3>Opening Hours</h3>
      <img src="service image.jpg" alt="Menu img 1" height="200" width="200">
      <p>Mon-Fri: 2pm-10pm<br>Sat: 2pm-11pm<br>Sun: 2pm-9pm</p>
    </div>
  </div>
  <footer>
    Designed and Developed by Arsha Jith S J
  </footer>
 </body>
 </html>

menu .html

<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Icy Kingdom</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #a10a5d;
    }
    header, nav, footer {
      background-color: #201e1e;
      color: white;
    }
    header {
      background-color:#728C69;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 20px;
    }
    .dish {
      background-color: #f8f8f8;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 20px;
      text-align: center;
      width: 30%;
    }
    .dish img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position:relative;
      bottom: 0;
      width: 100%;
    }
  </style>
 </head>
 <body>
  <header>
    <img src="logo.jpg" alt="Icy Kingdom Logo">
    <h1><font face="Goudy Oid Style Italic"size="6" color="#333">Icy Kingdom
    <h1><font face="Goudy Oid Style Italic" size="5" color="#333">Menu</font>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>

  </nav>
  <div class="menu">
    <div class="dish">
      <img src="Screenshot 2024-12-27 201633.png" height="200" width="300" alt="Chocolate Icecream">
      <h3>Chocolate Icecream</h3>
      <p>This simple recipe will make you rethink the store-bought tub.
    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 201753.png" height="200" width="300" alt="Masala">
      <h3>Masala Icecream</h3>
      <p>Fusion is the flavor of the season. Try this inventive ice-cream infused with the rustic flavor of masala tea. 
    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 202110.png" height="200" width="300" alt="Vegan Chocolate">
      <h3>Vegan Chocolate Icecream</h3>
      <p>A dairy-free version of your favourite chocolate ice cream, this recipe uses almonds and banana to replicate the creamy texture.
    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 202255.png" height="200" width="300" alt="Mango">
      <h3>Mango Icecream</h3>
      <p>Rich and creamy, this one is made with the goodness of mango pulp and milk. A lovely seasonal treat.
    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 202537.png" height="200" width="300" alt="Vannila">
      <h3>Vannila Icecream</h3>
      <p>The classic vanilla flavoured ice cream is sure to make you nostalgic. Go creative with toppings of your choice and create a perfect dessert.

    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 202740.png" height="200" width="300" alt="Apricot">
      <h3>Apricot Icecream</h3>
      <p>Enjoy the flavour of apricots like never before with these creamy scoops. Sprinkle almond pralines on top, and watch the magic unfold!
    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 202934.png" height="200" width="300" alt="Thandai">
      <h3>Thandai Icecream</h3>
      <p>A smooth and creamy ice cream, with the flavors of almonds, rose water, melon seeds and cardamom. Thandai ice cream is a heavenly dessert to serve at the next dinner party!
    </div>
    <div class="dish">
      <img src="Screenshot 2024-12-27 203215.png" height="200" width="300" alt="5 Mins Sundae">
      <h3>5 Mins Sundae</h3>
      <p> An all-time favourite ice cream sundae can now be made at home in just 5 minutes!
    </div>
    <footer>
      Designed and Developed Arsha Jith S J
    </footer>
 </body>
 </html>

 administration.html

 <!DOCTYPE html>
 <html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Administration - Icy Kingdom </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #0c31b7;
    }
    header, nav, footer {
      background-color: #1b010d;
      color: white;
    }
    header {
      background-color:#e912c9;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .administration {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 20px;
    }
    .chef {
      background-color: #f8f8f8;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 20px;
      text-align: center;
      width: 30%;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position:relative;
      bottom: 0;
      width: 100%;
    }
  </style>
 </head>
 <body>
  <header>
    <img src="logo.jpg" alt="Icy Kingdom Logo">
    <h1><font face="Goudy Oid Style Italic"size="6" color="#333">Icy Kingdom</font>
    <h1><font face="Goudy Oid Style Italic" size="5"color="#333">Administration</font>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="administration">
    <div class="chef">
      <h3>Chef Marco Romano</h3>
      <p>Specialty: Authentic Italian Cuisine
        With over 15 years of experience, Chef Marco brings the heart of Ita
    </div>
    <div class="chef">
      <h3>Chef Lisa Chen</h3>
      <p>Specialty: Pan-Asian Delights
        Expert in fusing flavors from across Asia, Chef Lisa’s signature di
    </div>
    <div class="chef">
      <h3>Chef Rajiv Mehta</h3>
      <p>Specialty: Modern Indian Cuisine
        Combining traditional spices with contemporary techniques, Chef Raji
    </div>
<div class="chef">
 <h3>Chef Amelia Torres</h3>
 <p>Specialty: Pastry and Desserts
 An award-winning pastry chef, Amelia’s creations, from macarons to m
 </div>
 <div class="chef">
 <h3>Chef David Miller</h3>
 <p>Specialty: Grill and Barbecue
 Known for his expertise in smoking and grilling, Chef David serves u
 </div>
 <div class="chef">
 <h3>Chef Sofia Hernandez</h3>
 <p>Specialty: Mediterranean Cuisine
 Chef Sofia’s dishes are inspired by the coasts of Greece and Spain, 
</div>
 </div>
 <footer>
 Designed and Developed by Arsha Jith S J
 </footer>
 </body>
 </html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Icy Kingdom</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #0fb890;
    }
    header, nav, footer {
      background-color: #2f0808;
      color: white;
    }
    header {
      background-color:#eff31b;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .contact {
      padding: 20px;
      text-align: center;
      color: white;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.jpg" alt="Icy Kingdom">

    <h1><font face="Goudy Oid Style Italic"size="6" color="#333">Icy Kingdom</font>
    <h1><font face="Goudy Oid Style Italic" size="5" color="#333">Contact Us</font></h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="contact">
    <h2>Get in Touch</h2>
    <p>Phone: 123-456-0040</p>
    <p>Email:contact@icykingdom.com</p>
    <p>Address: 456 street,cityvilla</p>
  </div>
  <footer>
    Designed and Developed by Arsha Jith SJ
  </footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-28 015110.png>) 
![alt text](<Screenshot 2024-12-28 014944.png>) 
![alt text](<Screenshot 2024-12-28 014959.png>)
![alt text](<Screenshot 2024-12-28 015008.png>) 
![alt text](<Screenshot 2024-12-28 015034.png>) 
![alt text](<Screenshot 2024-12-28 015101.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
