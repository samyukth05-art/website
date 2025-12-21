# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>South Indian Delight</title>

    <style>
        body{
            margin:0;
            font-family: Arial, sans-serif;
            background:#fffaf0;
        }

        
        .header{
            background:#8b0000;
            color:#ffd700;
            text-align:center;
            padding:20px;
            font-size:36px;
            font-weight:bold;
        }

        
        nav{
            background:#1b5e20;
            text-align:center;
            padding:10px;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:0 20px;
            font-size:18px;
        }

        nav a:hover{
            color:#ffd700;
        }

        
        .hero{
            background:url("bg.jpg");
            background-size:cover;
            background-position:center;
            height: 250px;
            text-align:center;
            color:white;
            padding-top:70px;
        }

        .hero h1{
            font-size:40px;
            background:rgba(0,0,0,0.6);
            display:inline-block;
            padding:10px 20px;
        }

        .hero p{
            background:rgba(0,0,0,0.6);
            display:inline-block;
            padding:8px 15px;
            margin-top:10px;
        }

        .features{
            text-align:center;
            margin:40px 0;
        }

        .box{
            width:280px;
            display:inline-block;
            margin:15px;
        }

        .box img{
            width:100%;
            height:180px;
        }

        .box h3{
            color:#8b0000;
        }

        footer{
            background:#3e2723;
            color:white;
            text-align:center;
            padding:12px;
            margin-top:30px;
        }
    </style>
</head>

<body>

<div class="header">South Indian Delight</div>

<nav>
    <a href="home.html">HOME</a>
    <a href="menu.html">MENU</a>
    <a href="booking.html">BOOKING</a>
    <a href="contact.html">CONTACT</a>
</nav>

<div class="hero">
    <h1>Authentic South Indian Taste</h1><br>
    <p>Fresh • Traditional • Banana Leaf</p>
</div>

<div class="features">
    <div class="box">
        <img src="pv.jpg">
        <h3>Pure Vegetarian</h3>
        <p>Traditional veg recipes.</p>
    </div>

    <div class="box">
        <img src="fresh.jpg">
        <h3>Fresh Ingredients</h3>
        <p>Farm fresh spices.</p>
    </div>

    <div class="box">
        <img src="bf.jpg">
        <h3>Banana Leaf</h3>
        <p>Classic serving style.</p>
    </div>
</div>

<footer>
    © 2025 South Indian Delight
</footer>

</body>
</html>  

```
```
menu.html
<!DOCTYPE html>
<html>
<head>
<title>Menu | South Indian Delight</title>

<style>
body{
    margin:0;
    font-family:'Segoe UI', sans-serif;
    background:linear-gradient(to right, #fff8e1, #e8f5e9);
}

h1{
    text-align:center;
    color:#8b0000;
    margin:40px 0 10px;
    letter-spacing:2px;
}

.subtitle{
    text-align:center;
    color:#555;
    margin-bottom:35px;
    font-size:16px;
}

.menu{
    width:85%;
    margin:auto;
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:25px;
}

.item{
    background:white;
    width:260px;
    border-radius:16px;
    box-shadow:0 10px 20px rgba(0,0,0,0.15);
    border-top:6px solid #1b5e20;
    overflow:hidden;
    transition:transform 0.3s, box-shadow 0.3s;
}

.item:hover{
    transform:translateY(-8px);
    box-shadow:0 15px 25px rgba(0,0,0,0.25);
}


.item img{
    width:100%;
    height:160px;
    object-fit:cover;
}


.item-content{
    padding:18px;
}

.item-header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:8px;
}

.item h3{
    color:#8b0000;
    font-size:18px;
    margin:0;
}

.price{
    background:#1b5e20;
    color:white;
    padding:4px 10px;
    border-radius:20px;
    font-size:14px;
    font-weight:bold;
}

.item p{
    color:#444;
    font-size:15px;
    line-height:1.4;
}

.note{
    text-align:center;
    margin:40px 0;
    color:#555;
    font-style:italic;
}
</style>
</head>

<body>

<h1>Our Menu</h1>
<div class="subtitle">
    Authentic South Indian delicacies served fresh 🍃
</div>

<div class="menu">

    <div class="item">
        <img src="dosa.jpg" alt="Masala Dosa">
        <div class="item-content">
            <div class="item-header">
                <h3>Masala Dosa</h3>
                <span class="price">₹80</span>
            </div>
            <p>Crispy golden dosa filled with spiced potato masala.</p>
        </div>
    </div>

    <div class="item">
        <img src="is.jpg" alt="Idli Sambar">
        <div class="item-content">
            <div class="item-header">
                <h3>Idli & Sambar</h3>
                <span class="price">₹40</span>
            </div>
            <p>Soft steamed idlis served with hot sambar and chutney.</p>
        </div>
    </div>

    <div class="item">
        <img src="vp.jpg" alt="Ven Pongal">
        <div class="item-content">
            <div class="item-header">
                <h3>Ven Pongal</h3>
                <span class="price">₹60</span>
            </div>
            <p>Comforting rice & dal cooked with ghee and pepper.</p>
        </div>
    </div>

    <div class="item">
        <img src="mt.jpg" alt="Mini Tiffin">
        <div class="item-content">
            <div class="item-header">
                <h3>Mini Tiffin</h3>
                <span class="price">₹120</span>
            </div>
            <p>Idli, dosa, pongal, vada with sambar and chutneys.</p>
        </div>
    </div>

    <div class="item">
        <img src="si.jpg" alt="South Indian Meals">
        <div class="item-content">
            <div class="item-header">
                <h3>South Indian Meals</h3>
                <span class="price">₹150</span>
            </div>
            <p>Traditional full meals served on fresh banana leaf.</p>
        </div>
    </div>

    <div class="item">
        <img src="fk.jpg" alt="Filter Coffee">
        <div class="item-content">
            <div class="item-header">
                <h3>Filter Coffee</h3>
                <span class="price">₹20</span>
            </div>
            <p>Strong, aromatic traditional South Indian filter coffee.</p>
        </div>
    </div>

</div>

<div class="note">
    Prices inclusive of taxes • Pure vegetarian
</div>

</body>
</html>

```
```
booking.html
<!DOCTYPE html>
<html>
<head>
<title>Booking | South Indian Delight</title>

<style>
body{
    margin:0;
    font-family:'Segoe UI', sans-serif;
    background:linear-gradient(to right, #fff3e0, #f1f8e9);
}


.formbox{
    width:38%;
    margin:70px auto;
    background:#ffffff;
    padding:35px;
    border-radius:18px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
    border-top:10px solid #8b0000;
}

h2{
    text-align:center;
    color:#8b0000;
    letter-spacing:2px;
    margin-bottom:10px;
}

.subtitle{
    text-align:center;
    color:#555;
    margin-bottom:25px;
    font-size:15px;
}

input{
    width:100%;
    padding:12px;
    margin:12px 0;
    border-radius:8px;
    border:1px solid #ccc;
    font-size:15px;
}

input:focus{
    outline:none;
    border-color:#1b5e20;
    box-shadow:0 0 5px rgba(27,94,32,0.5);
}


button{
    width:100%;
    padding:14px;
    margin-top:15px;
    background:linear-gradient(to right, #1b5e20, #2e7d32);
    color:white;
    border:none;
    border-radius:30px;
    font-size:17px;
    font-weight:bold;
    cursor:pointer;
}

button:hover{
    background:linear-gradient(to right, #2e7d32, #1b5e20);
}


.note{
    text-align:center;
    margin-top:15px;
    font-size:14px;
    color:#444;
}
</style>
</head>

<body>

<div class="formbox">
    <h2>Book a Table</h2>
    <div class="subtitle">Experience authentic South Indian flavors 🍃</div>

    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="number" placeholder="Number of Guests" required>
        <input type="date" required>
        <input type="time" required>
        <button type="submit">Confirm Booking</button>
    </form>

    <div class="note">
        Banana leaf meals • Fresh ingredients • Traditional taste
    </div>
</div>

</body>
</html>

```
```
contact.html
<!DOCTYPE html>
<html>
<head>
<title>Contact | South Indian Delight</title>

<style>
body{
    margin:0;
    font-family:'Segoe UI', sans-serif;
    background:linear-gradient(to right, #fff8e1, #e8f5e9);
}

.contact{
    width:45%;
    margin:70px auto;
    background:white;
    padding:35px;
    border-radius:18px;
    box-shadow:0 12px 25px rgba(0,0,0,0.18);
    border-left:10px solid #8b0000;
    text-align:center;
}


.contact h1{
    color:#8b0000;
    letter-spacing:2px;
    margin-bottom:10px;
}


.subtitle{
    font-size:16px;
    color:#555;
    margin-bottom:25px;
}


.info{
    font-size:19px;
    margin:14px 0;
    color:#333;
}


.highlight{
    color:#1b5e20;
    font-weight:600;
}


.note{
    margin-top:25px;
    font-size:15px;
    color:#444;
    font-style:italic;
}
</style>
</head>

<body>

<div class="contact">
    <h1>Contact Us</h1>
    <div class="subtitle">
        We’d love to serve you authentic South Indian flavors 🍃
    </div>

    <div class="info">📍 <span class="highlight">24 Spice Street, Chennai</span></div>
    <div class="info">📞 <span class="highlight">+91 98765 43210</span></div>
    <div class="info">📧 <span class="highlight">southindiandelight@gmail.com</span></div>
    <div class="info">⏰ Open Daily: <span class="highlight">7:00 AM – 11:00 PM</span></div>

    <div class="note">
        Walk in for a hearty breakfast, lunch on banana leaf, or a peaceful dinner with family.
    </div>
</div>

</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-12-21 220431.png>)
![alt text](<Screenshot 2025-12-21 220448.png>)
![alt text](<Screenshot 2025-12-21 220502.png>)
![alt text](<Screenshot 2025-12-21 220513.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
