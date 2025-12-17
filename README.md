# Ex.07 Restaurant Website
## Date:17-12-2025

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
  <title>Home - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <!-- Banner Section -->
  <section class="banner" style="text-align: center; position: relative;">
    <img src="background.png" alt="Restaurant Banner" style="width:100%; height:auto; display:block;" >
    <div style="position: absolute; top: 40%; left: 50%; transform: translate(-50%, -50%); color: white; text-shadow: 2px 2px 5px black;">
      <h1>Welcome to Our Restaurant</h1>
      <p>Delicious food, made with love!</p>
    </div>
  </section>

  <!-- About Section -->
  <section style="padding: 40px; text-align: center;">
    <h2>About Us</h2>
    <p>
      We serve fresh, tasty, and hygienic food to satisfy your cravings.  
      From traditional Indian dishes to global flavors, we bring the best of both worlds.  
      Visit us and enjoy a wonderful dining experience with your friends and family.
    </p>
  </section>

  <!-- Highlights -->
  <section style="padding: 40px; background-color: #f9f9f9; text-align: center;">
    <h2>Why Choose Us?</h2>
    <div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap; margin-top: 20px;">
      <div style="max-width: 250px;">
        <h3>🍽️ Quality Food</h3>
        <p>We use only fresh ingredients to prepare mouth-watering dishes.</p>
      </div>
      <div style="max-width: 250px;">
        <h3>👨‍🍳 Expert Chefs</h3>
        <p>Our chefs bring authentic taste and creativity to every dish.</p>
      </div>
      <div style="max-width: 250px;">
        <h3>🏠 Cozy Ambience</h3>
        <p>Enjoy your meals in a comfortable and welcoming environment.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>Designed by Senash Ayisha F</p>
  </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <h2 style="text-align:center; margin-top:20px;">Our Menu</h2>

  <section class="menu-grid">
    <div class="item">
      <img src= "sawarma.png" alt="sawarma">
      <h3>sawarma</h3>
      <p>₹150</p>
    </div>
    <div class="item">
      <img src="french fries.png" alt="French fries">
      <h3>French fries</h3>
      <p>₹150</p>
    </div>
    <div class="item">
      <img src="Biriyani.png" alt="biriyani">
      <h3>Biriyani</h3>
      <p>₹250</p>
    </div>
    <div class="item">
      <img src="curd rice.png" alt="curd rice">
      <h3>urd rice</h3>
      <p>₹100</p>
    </div>
    <div class="item">
      <img src="dragon chicken.png" alt="dragon chicken">
      <h3>Dragon chicken</h3>
      <p>₹150</p>
    </div>
    <div class="item">
      <img src="tandoori.png" alt="tandoori">
      <h3>Tandoori</h3>
      <p>₹90</p>
    </div>
    
    <div class="item">
      <img src="chappathi.png" alt="chappathi">
      <h3>Chappathi</h3>
      <p>₹60</p>
    </div>
    <div class="item">
      <img src="dosa.png" alt="Dosa">
      <h3>Dosa</h3>
      <p>₹80</p>
    </div>
    <div class="item">
      <img src="ice cream.png" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>₹70</p>
    </div>
    <div class="item">
      <img src="juice.png" alt="Juice">
      <h3>Juice</h3>
      <p>₹50</p>
    </div>
    <div class="item">
      <img src="cake.png" alt="Cake">
      <h3>Cake</h3>
      <p>₹150</p>
    </div>
    <div class="item">
      <img src="pancake.png" alt="pancake">
      <h3>Pancake</h3>
      <p>₹220</p>
    </div>
  </section>

  <footer>
    <p>Designed by Senash Ayisha F</p>
  </footer>
</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Administration - Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body> 
  <header>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <h2>Administration Team</h2>
  <section class="admin-grid">
    <div class="person"><img src="manager.png" alt="Person 1"><p>Manager</p></div>
    <div class="person"><img src="chef.png" alt="Person 2"><p>Chef</p></div>
    <div class="person"><img src="assistant chef.png" alt="Person 3"><p>Assistant Chef</p></div>
    <div class="person"><img src="cashier.png" alt="Person 4"><p>Cashier</p></div>
    <div class="person"><img src="servent.png" alt="Person 5"><p>Waiter</p></div>
    <div class="person"><img src="cleaner.png" alt="Person 6"><p>Cleaner</p></div>
  </section>

  <footer>
    <p>Designed by Senash Ayisha F</p>
  </footer>
</body>
</html>

style.css

body {
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-color: #fff8f6;
color: #333;
}


header {
background-color: #c0392b;
padding: 10px;
text-align: center;
}


header nav a {
color: white;
margin: 0 15px;
text-decoration: none;
font-weight: bold;
}


header nav a:hover {
color: #f39c12;
}


.banner {
background: url('banner.jpg') no-repeat center/cover;
color: white;
text-align: center;
padding: 100px 20px;
}


.menu-grid, .admin-grid {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 20px;
padding: 20px;
}


.menu-grid .item, .admin-grid .person {
background: white;
border: 1px solid #ddd;
padding: 15px;
text-align: center;
border-radius: 8px;
box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}


.admin-grid img {
width: 100px;
height: 100px;
border-radius: 50%;
}


footer {
background-color: #c0392b;
color: white;
text-align: center;
padding: 10px;
margin-top: 20px;
}

```

## OUTPUT:
![alt text](<ayisha/restapp/static/Screenshot 2025-12-17 181912.png>)
![alt text](<ayisha/restapp/static/Screenshot 2025-12-17 181931.png>)
![alt text](<ayisha/restapp/static/Screenshot 2025-12-17 182012.png>)
![alt text](<ayisha/restapp/static/Screenshot 2025-12-17 182034.png>)
![alt text](<ayisha/restapp/static/Screenshot 2025-12-17 182042.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
