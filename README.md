# Ex.07 Restaurant Website
## Date:13-12-2024

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
    <meta name="description" content="Welcome to One8 Restaurant - Delight in Exquisite Cuisines.">
    <title>Tempting kitchen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0eb0d8;
        }

        header {
            background-color: #1bb2d8;
            color: rgb(182, 217, 41);
            padding: 15px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #bcbec8;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: rgb(7, 7, 7);
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav ul li a:hover {
            background-color: #12cee3;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        footer {
            background-color: #0c0a0a;
            color: white;
            text-align: center;
            padding:1px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        h1 {
            color: #e1d7d7;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .menu-item {
            background-color: rgb(18, 155, 218);
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 0 10px rgba(19, 157, 221, 0.1);
        }

        .menu-item h3,h4{
            margin: 0 0 10px 0;
        }

        .menu-item p {
            color: #080808;
        }
    </style>
</head>
<body>

<header>
    <h1>AS RESTAURANT</h1>
    <p>EAT AND ENJOY!</p>
    <img src="WhatsApp Image 2024-12-11 at 21.23.31_6eef2006.jpg"width="15%">
 </header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#administration">Administration</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="home">
    <h2>AS RESTAURANT Welcomes you</h2>
    <p>We provide healthier food with fresh meat and vegetables. No artficial colours and flavours.</p>
</section>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <h3>Parotta</h3>
            <img src="image-923556-1671810387.jpg"height ="128" width="128">
            <p><strong>RS.30</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken biriyani</h3>
            <img src="Chicken-Biryani-Recipe.jpg"height ="128" width="128">
            <p><strong>RS.200</strong></p>
        
    </div>
        <div class="menu-item">
            <h3>Chicken full grill</h3>
            <img src="ai-generated-8542471_1280.jpg"height ="128" width="128">
            <p><strong>RS.300</strong></p>
        </div>
        <div class="menu-item">
            <h3>Hot chicken gravy</h3>
            <img src="Chicken-Chettinad-Curry-2-1.jpg"height ="128" width="128">
            <p><strong>RS.190</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken fried rice</h3>
            <img src="Gobi-Fried-Rice-5.jpg"height ="128" width="128">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken noodles</h3>
            <img src="chicken-chow-mein-TRR-1200-9-of-31.jpg"height ="128" width="128">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3>Malai chicken</h3>
            <img src="Malai-Chicken.jpg"height ="128" width="128">
            <p><strong>RS.250</strong></p>
        </div>
        <div class="menu-item">
            <h3>Fried Chicken</h3>
            <img src="buttermilk-fried-chicken-12-square.jpg"height ="128" width="128">
            <p><strong>RS.210</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken burger</h3>
            <img src="crispy-chicken-burger-WEB-01.jpg"height ="128" width="128">
            <p><strong>RS.210</strong></p>
        </div>
        <div class="menu-item">
            <h3>Chicken shawerma</h3>
            <img src="images.jpg"height ="128" width="128">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3>Mint mojito</h3>
            <img src="images (1).jpg"height ="128" width="128">
            <p><strong>RS.160</strong></p>
        </div>
        <div class="menu-item">
            <h3>Black current Ice Cream</h3>
            <img src="istockphoto-537317455-612x612.jpg" height ="128" width="128">
            <p><strong>RS.150</strong></p>
        </div>
    </div>
</section>
<section id="administration">
    <h2>Administration</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="WhatsApp Image 2024-12-11 at 21.28.13_dd998184.jpg"width="60%">
            <h3>FOUNDER</h3>
        </div>
        <div class="menu-item">
            <img src="WhatsApp Image 2024-12-11 at 21.32.10_df781ab8.jpg"width="50%">
            <h3>MANAGER</h3>
        </div>
        <div class="menu-item">
            <img src="WhatsApp Image 2024-12-11 at 21.35.41_db1b68f8.jpg"width="50%">
            <h3>BRAND AMBASSADOR</h3>
        </div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>At AS Restaurant, we believe that dining is more than just a meal—it's an experience. Established with the vision of bringing exceptional culinary delights to our guests, we pride ourselves on offering a perfect blend of flavors, ambiance, and hospitality.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Anna nagar, Chennai- 600001</p>
    <p>Phone: 6383882590</p>
    <p>Email:asrestaurant@gmail.com</p>
</section>
<footer>
    <p>@Owned by santa's</p>
</footer>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
