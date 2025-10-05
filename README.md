# Ex.07 Restaurant Website
## Date:05.10.2025

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
  <title>RESTAURANT</title>
  <link rel="stylesheet" href="styleh.css">
</head>
<body>
  <header>
    <h1>5 STAR RESTAURANT</h1>
    
    <nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    
    <h2></color>"Where every dish tells a story--flavors crafted with tradition and love</h2>
    <p>Step into 5 Star and let your senses celebrate! From fiery stir-fries to golden spring rolls,we bring you flavors that warm the heart and excite the soul.Every dish is crafted with passion--chopsticks optional,enjoyment guaranteed</p>
    <img src="home1.jpg">
  </section>

  <footer>
    <p>© 2025 5 STAR RESTAURANT| Designed by <strong>Sridharan B(25016127)</strong></p>
  </footer>
</body>
</html>

styleh.css

body {
  background-image: url('home.jpeg');
  font-family: Arial, sans-serif;
  background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
  padding: 20px;
  border-bottom: 3px solid red;
}

h1 {
    position:relative;
  color: red;
  right:30%;
  top:20%;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: black;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: red;
  position: relative;
  left:30%;
}


.home {
  padding: 40px;
  color: black;
}

.home img {
  width: 500px;
  border-radius: 10px;
  margin-top: 20px;
  border: 3px solid red;
}

footer {
  background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
  color: black;
  padding: 15px;
  border-top: 2px solid red;
}

menu.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="stylem.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            
            <div class="food1">
                <img src="prawnfry.jpg"alt="pic">
                <b>Prawn Fry -$20</b>
            </div>
            <div class="food2">
                <img src="fish.jpg" alt="pic">
                <b>Fish Fry-$15</b>
            </div>
            <div class="food3">
                <img src="tunamusset.jpg" alt="pic">
                <b>Tuna Masset-$50</b>
            </div>
            <div class="food4">
                <img src="shell.jpg" alt="pic">
                <b>Shell Soup-$60</b>
            </div>
            <div class="food5">
                <img src="octopus.jpg" alt="pic">
                <b>Ocutopus-$30</b>
            </div>
            <div class="food6">
                <img src="chicken tikka.jpg" alt="pic">
                <b>Chicken Tikka-$40</b>
            </div>
            <div class="food7">
                <img src="friedriceballs.jpg" alt="pic">
                <b>FriedRiceBalls-$30</b>
            </div>
            <div class="food8">
                <img src="vegetablesalad.jpg" alt="pic">
                <b>VegetableSalad-$40</b>
            </div>
            <div class="food9">
                <img src="friedbanana.jpg" alt="pic">
                <b>FriedBananaFritters-$50</b>
            </div>
            <div class="food10">
                <img src="pierogi.jpg" alt="pic">
                <b>Pierogi-$40</b>
            </div>
            <div class="food11">
                <img src="pancake.jpg" alt="pic">
                <b>PanCake-$50</b>
            </div>
            <div class="food12">
                <img src="roastmeat.jpg" alt="pic">
                <b>Roast Meat-$60</b>
            </div>
        </div><br><br><br>
        <footer>
            <p class="bottom">&copy; 2025 5 STAR RESTAURANT | Designed by <strong>Sridharan B(25016127)</strong></p>

        </footer>
    </body>
</html>

stylem.css

body{
    
    background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgb(227, 226, 224);
    position: relative;
    left: 1200px;
}
.food1{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food11{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    top: 10px;
    
}
.food12{
    padding: 10px;
    background-color:violet;
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    top: 10px;
}
img{
    width: 150px;
    height: 100px;
    border: solid rgb(87, 85, 85) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
   
    color: rgb(247, 6, 6);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 50px;
    background-color: black;
    color: white;
}
nav a {
  list-style: none;
  padding: 0;
  margin-top: 10px;
  color: black;
  position: relative;
  top: 20px;
}

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration Team</title>
    <link rel="stylesheet" href="stylea.css">
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html" class="active">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Meet Our Team</h2>

        <div class="team">
            <div class="member">
                <img src="IMG_20250815_081336_169.webp" alt="Sridharan B">
                <h3>Sridharan B</h3>
                <p>CEO</p>
            </div>

            <div class="member">
                <img src="cr7.jpeg" alt="Ronaldo">
                <h3>Ronaldo</h3>
                <p>Manager</p>
            </div>

            <div class="member">
                <img src="dhoni.jpeg" alt="M.S.Dhoni">
                <h3>M.S.Dhoni</h3>
                <p>Account Manager</p>
            </div>

            <div class="member">
                <img src="meta.jpeg" alt="Mark zuckerberg">
                <h3>Mark zuckerberg</h3>
                <p>Service Manager</p>
            </div>

            <div class="member">
                <img src="elon.jpeg" alt="Elon musk">
                <h3>Elon musk</h3>
                <p>Maintenance Manager</p>
            </div>

            <div class="member">
                <img src="bill.jpeg" alt="Bill gates">
                <h3>Bill gates</h3>
                <p>Reception</p>
            </div>
        </div>
    </main>
    <br><br>
    <footer>
        <p>© 2025 5 STAR RESTAURANT | Designed by <strong>Sridharan B(25016127)</strong></p>
    </footer>
</body>
</html>

stylea.css

body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: yellow;
}

/* Header */
header {
    background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
    color: red;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: black;
    font-size: 1.8em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.member {
    background-color: #222;
    color: white;
    border-radius: 12px;
    width: 150px;
    padding: 20px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 80%;
    height: 230px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid orange;
}

.member h3 {
    margin-top: 15px;
    color: blck;
    font-size: 1.2em;
}

.member p {
    color: #FFD500;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 0.9em;
}

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | The Six Tastes Restaurant</title>
  <link rel="stylesheet" href="stylesheet.css">
</head>
<body>
  <header>
    <h1>CONTACT US</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>Contact Us</h2>
    <p>📍 1234 marina beach,chennai,tamilnadu</p>
    <p>📞  8248******</p>
    <p>✉  abc@gmail.com</p>
  </section>
  <footer>
    <p>© 2025 5 STAR RESTAURANT | Designed by <strong>Sridharan B(25016127)</strong></p>
  </footer>
</body>
</html>

stylesheet.css

body {
  font-family: Arial, sans-serif;
  background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
  color: black;
  margin: 0;
  text-align: center;
}

header {
  background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
  padding: 20px;
  border-bottom: 3px solid blue;
}

h1 {
  color: red;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
  color: black;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: blue;
}

.contact {
  padding: 200px;
}

footer {
  background:linear-gradient(120deg,#ff0080,#7928ca,#2afadf,#4c83ff);
  color: black;
  padding: 15px;
  border-top: 2px solid black;
}
```
## OUTPUT:
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
