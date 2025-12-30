# Ex.06 Restaurant Website
## Date:29-12-2025

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
admin.html
<html>
<head>
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="index.html">INDEX</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <h1 class="admin-title">ADMIN'S</h1>
    <div class="team-container">

        <div class="team-card">
            <img src="WhatsApp Image 2025-12-27 at 4.20.25 PM.jpeg">
            <h3>GAUTAM</h3>
            <p>CEO</p>
        </div>

        <div class="team-card">
            <img src="pic1.jpg">
            <h3>John</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="team-card">
            <img src="pic2.jpg">
            <h3>Thomas</h3>
            <p>Operations Manager</p>
        </div>

        <div class="team-card">
            <img src="pic3.jpg">
            <h3>scarlett</h3>
            <p>HR Manager</p>
        </div>

        <div class="team-card">
            <img src="pic4.jpg">
            <h3>alfie</h3>
            <p>Executive Chef</p>
        </div>

        <div class="team-card">
            <img src="pic5.jpg">
            <h3>Grace</h3>
            <p>Customer Service Manager</p>
        </div>

        <div class="team-card">
            <img src="pic6.jpg">
            <h3>Arthur</h3>
            <p>Managing Director</p>
        </div>

    </div>
</div>
<div class="footer">
    <p>&copy;GAUTAM(25009613)</p>
</body>
</html>

admin.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("bar.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.admin-title {
    font-size: 80px;
    color: lightslategray;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.team-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}
.team-card {
    background-color: blanchedalmond;
    width: 200px;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0,0,0,0.35);
}
.team-card img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}
.team-card h3 {
    font-size: 18px;
    margin-bottom: 5px;
}
.team-card p {
    font-size: 14px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

index.html

<html>
<head>
    <title>Restaurant WebPage</title>
    <link href="index.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="index.html">INDEX</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="main">
        <h1>Welcome to our Restaurant</h1>
        <h1 class="brand">PEAKY BLINDERS</h1>
        <h2>Experience the secret of british cuisine</h2>
        <p>
            British cuisine refers to the traditional foods and cooking styles of the United Kingdom. It is known for being simple, hearty, and filling, using locally available ingredients like meat, potatoes, vegetables, bread, and dairy products.
        </p>
    </div>
    <div class="images">
        <img src="entrance.jpg" alt="Image1">
        <img src="chairs.jpg" alt="Image2">
        <img src="bar.jpg" alt="Image3">
        <img src="image.png" alt="Image4">
    </div>
</div>
<div class="footer">
    <h4>GAUTAM.P(25009163)</h4>
</div>
</body>
</html>


index.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("bg1.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    text-decoration: underline;
    font-weight: bold;
    color: hotpink;
    font-size: 16px;
}
.main {
    text-align: center;
    color: white;
    margin-bottom: 40px;
}
.main h1 {
    font-size: 50px;
}
.main .brand {
    font-size: 70px;
    color: red;
    letter-spacing: 4px;
}
.main h2 {
    margin: 15px 0;
    font-weight: normal;
}
.main p {
    width: 70%;
    margin: 20px auto;
    font-size: 18px;
    line-height: 1.6;
}
.images {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
}
.images img {
    width: 220px;
    height: 160px;
    object-fit: cover;
    border: 5px solid white;
    border-radius: 10px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0;
}

menu.html

<html>
<head>
    <title>Menu Page</title>
    <link href="menu.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="index.html">INDEX</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="menu-container">
        <h1>MENU</h1>
        <div class="menu-items">

            <div class="menu-card">
                <img src="choco truffle.jpg">
                <h3>Choco-truffle</h3>
                <p>Rs. 150</p>
            </div>

            <div class="menu-card">
                <img src="fishnchips.jpg">
                <h3>Fish and chips</h3>
                <p>Rs. 130</p>
            </div>

            <div class="menu-card">
                <img src="Shepherd's Pie.jpg">
                <h3>Shepard's pie</h3>
                <p>Rs. 475</p>
            </div>

            <div class="menu-card">
                <img src="english breakfast.jpg">
                <h3>ENG-breakfast</h3>
                <p>Rs. 170</p>
            </div>

            <div class="menu-card">
                <img src="steak.jpg">
                <h3>Steak</h3>
                <p>Rs. 650</p>
            </div>

            <div class="menu-card">
                <img src="Sticky Toffee Pudding.jpg">
                <h3>Toffee pudding</h3>
                <p>Rs. 305</p>
            </div>

            <div class="menu-card">
                <img src="tart.jpg">
                <h3>Lemon tart</h3>
                <p>Rs. 450</p>
            </div>

            
        </div>
    </div>

</div>
<div class="footer">
    <h4>GAUTAM.P(25009613)</h4>
</div>

</body>
</html>

menu.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Georgia, serif;
}

.container {
    background: url("bg1.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}

.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}

.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}

.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
    font-size: 16px;
}

.menu-container {
    width: 100%;
}

.menu-container h1 {
    font-size: 80px;
    color: lightgrey;
    letter-spacing: 6px;
    margin-bottom: 35px;
    text-align: center;
    text-decoration: underline;
}

.menu-items {
    display: flex;
    gap: 20px;
    justify-content: center;   
    align-items: flex-start;
    flex-wrap: nowrap;
}

.menu-card {
    background-color: blanchedalmond;
    width: 180px;
    padding: 12px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.35);
}

.menu-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 12px;
    margin-bottom: 10px;
}

.menu-card h3 {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5px;
}

.menu-card p {
    font-size: 14px;
    color: black;
}
@media (max-width: 1200px) {
    .menu-items {
        flex-wrap: wrap;
        justify-content: center;
    }
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}


```


## OUTPUT:
![alt text](<Screenshot 2025-12-30 082444.png>)
![alt text](<Screenshot 2025-12-30 082454.png>)
![alt text](<Screenshot 2025-12-30 082503.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
