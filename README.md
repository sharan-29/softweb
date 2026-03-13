# Ex.06 Restuarant Website
## Date:10-03-2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
Home.html
```python
<!DOCTYPE html>
<html>
<head>
<title>Restaurant - Home</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f2f2f2;
}

nav{
background:#333;
padding:15px;
text-align:right;
}

nav a{
color:white;
margin:20px;
text-decoration:none;
font-size:18px;
}

header{
height:400px;
background:url("https://images.unsplash.com/photo-1504674900247-0877df9cc836");
background-size:cover;
background-position:center;
}

.section{
padding:40px;
background:white;
}

</style>
</head>

<body>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="chef.html">Chef</a>
<a href="contact.html">Contact</a>
</nav>

<header></header>

<div class="section">
<h1>Welcome to Our Restaurant</h1>

<p>
Experience the best dining with delicious meals made from fresh ingredients.
Our chefs prepare magical dishes to give you the best taste experience.
</p>

<a href="menu.html">Explore Our Menu</a>

</div>

</body>
</html>
```

menu.html
```python
<!DOCTYPE html>
<html>
<head>
<title>Restaurant - Menu</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f2f2f2;
}

nav{
background:#333;
padding:15px;
text-align:right;
}

nav a{
color:white;
margin:20px;
text-decoration:none;
font-size:18px;
}

h1{
text-align:center;
margin-top:40px;
}

.menu{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:30px;
padding:40px;
}

.card{
background:white;
padding:15px;
text-align:center;
border-radius:10px;
}

.card img{
width:100%;
border-radius:10px;
}

</style>
</head>

<body>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="chef.html">Chef</a>
<a href="contact.html">Contact</a>
</nav>

<h1>Our Menu</h1>

<div class="menu">

<div class="card">
<img src="chicken-biryani-5.jpg">
<h3>Biryani</h3>
<p>Chicken Biryani</p>
</div>

<div class="card">
<img src="fried rice.jpg">
<h3>Fried Rice</h3>
<p>Chicken Fried Rice</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c">
<h3>Salad</h3>
<p>Good salad</p>
</div>

<div class="card">
<img src="maggi.jpg">
<h3>Maggi</h3>
<p>Nala dish</p>
</div>

</div>

</body>
</html>
```

chef.html
```python
<!DOCTYPE html>
<html>
<head>
<title>Restaurant - Chefs</title>

<style>

body{
margin:0;
font-family:Arial;
background:#111;
color:white;
}

nav{
background:#000;
padding:15px;
text-align:right;
}

nav a{
color:white;
margin:20px;
text-decoration:none;
font-size:18px;
}

h1{
text-align:center;
margin-top:40px;
}

.chefs{
display:flex;
justify-content:center;
gap:40px;
padding:50px;
}

.card{
background:#222;
padding:20px;
border-radius:10px;
width:220px;
text-align:center;
}

.card img{
width:100%;
border-radius:10px;
}

</style>
</head>

<body>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="chef.html">Chef</a>
<a href="contact.html">Contact</a>
</nav>

<h1>Our Magical Chefs</h1>

<div class="chefs">

<div class="card">
<img src="ishowspped chef.jpg">
<h3>IShowSpeed</h3>
<p>Biryani specialist</p>
</div>

<div class="card">
<img src="weeknd chef.jpg">
<h3>Weeknd</h3>
<p>Salad master</p>
</div>

<div class="card">
<img src="cat chef.jpg">
<h3>Chef Cat</h3>
<p>Fried Rice Master</p>
</div>

</div>

</body>
</html>
```

contact.html
```python
<!DOCTYPE html>
<html>
<head>
<title>Restaurant - Contact</title>

<style>

body{
margin:0;
font-family:Arial;
color:white;
}

nav{
background:#000;
padding:15px;
text-align:right;
}

nav a{
color:white;
margin:20px;
text-decoration:none;
font-size:18px;
}

.contact{
height:100vh;
background:url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4");
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
}

.box{
background:rgba(0,0,0,0.7);
padding:40px;
text-align:center;
border-radius:10px;
}

</style>
</head>

<body>

<nav>
<a href="home.html">Home</a>
<a href="menu.html">Menu</a>
<a href="chef.html">Chef</a>
<a href="contact.html">Contact</a>
</nav>

<div class="contact">

<div class="box">

<h1>Contact Us</h1>

<p>Address: Street:67 ,BAZOOKA PALACE,MARS</p>

<p>Phone: +91 6767676767</p>

<p>Email: BETTERLEAVEGOODREVIEW@email.com</p>

</div>

</div>

</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2026-03-13 091252.png>)

![alt text](<Screenshot 2026-03-13 091312.png>)

![alt text](<Screenshot 2026-03-13 091327.png>)

![alt text](<Screenshot 2026-03-13 091340.png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
