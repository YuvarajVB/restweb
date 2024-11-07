# Ex.07 Restaurant Website
## Date:

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
    <title>Ocean’s Delight</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="v1033-bb-020.jpg" alt="Logo">
            <h1>Ocean's Delight</h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#book">Book</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner" >
            <h2 class="offer-txt" style="color: #fff;">30% Off This Weekend</h2>
            <p class = 'offer-txt' style="color: #fff;">At Ocean’s Delight, we pride ourselves on our farm-to-table approach, sourcing the freshest seafood directly from sustainable fisheries.</p>
        </section>
        <section class="features">
            <div class="feature1" style="color: #fff;">
                <h3>Our New Menu</h3>                
                <IMG SRC="1.png" >
                <a href="www.google.com">See our new menu</a>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
            </div>
            <div class="feature2" style="color: #fff;">
                <h3>Book a table</h3>
                <IMG SRC="2.png" >
                <a href="www.google.com">Book your table now</a>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
            </div>
            <div class="feature3" style="color: #970d0d;">
                <h3>Opening Hours</h3>
                <IMG SRC="3.png" >
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices.</p>
                <ul>
                    Monday - Friday: 11:00 AM - 10:00 PM <br>
                    Saturday: 10:00 AM - 11:00 PM <br>
                    Sunday: 10:00 AM - 9:00 PM <br>
                </ul>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="footer.png" class="footer" alt="Ocean's Delight">
                <p class="copy">&copy; Copyright Ocean's Delight</p>
            </div>
        </footer>
    </main>
</body>
</html>
```
```
main.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #b9fbe9;
}

header {
    display: flex;
    justify-content: space-between; /* Space between logo and menu */
    align-items: center;
    padding: 20px;
    background-color: rgb(161, 5, 245);
    border-radius: 10px;
}
.menu {
    background-color: rgb(213, 199, 199);
    color: white;
    padding: 15px 30px;
    border-radius: 30px;
    margin-left: auto; 
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
    justify-content: right;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 20px 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.offer-txt{
    color: black;
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background: url('Screenshot 2024-11-05 131723.png') no-repeat center center/cover;
    padding: 60px 20px;
    color: #fff;
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
    background-color: rgb(162, 211, 176);
}

.feature1,.feature2,.feature3 {
    text-align: center;
    background-color: rgb(240, 202, 133);
    
    padding: 10px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    flex: 1;
    margin: 0 10px;
}

.feature1,.feature2,.feature3 h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature1,.feature2,.feature3 img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}
.feature1 {
    background:  no-repeat center center/cover;
}

.feature2 {
    background:  no-repeat center center/cover;
}

.feature3 {
    background:  no-repeat center center/cover;
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
    color: blue;
}
```


## OUTPUT:
![Screenshot 2024-11-07 110825](https://github.com/user-attachments/assets/bfe46fb5-b5d8-439d-b796-ba5aea6b6093)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
