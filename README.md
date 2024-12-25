# Ex.07 Restaurant Website
## Date:25-12-2024

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
    <title>Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Welcome to Alagappa Restaurant</h1>
    </header>

    <section>
        <div class="image-container">
            <img src="https://market-resized.envatousercontent.com/previews/files/225441304/preview.jpg?w=590&h=300&cf_fit=crop&crop=top&format=auto&q=85&s=a2e31550480d35ca5c0c0b9c0d2995f1211c2eb6b9ba2af324f8af5a4f2bafce" class="restaurant-img">
        </div>
    </section>

    <footer>
        <div class="container">
            <h2>Order Now</h2>
            <div class="menu-cards">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLvBSYpdrmjC6s63P5oWgTiU4gPl36dkdVfQ&s" alt="Burger">
                    <h3>BURGER</h3>
                </div>
                <div class="card">
                    <img src="https://content3.jdmagicbox.com/comp/def_content/pizza_outlets/default-pizza-outlets-13.jpg" alt="Pizza">
                    <h3>PIZZA</h3>
                </div>
                <div class="card">
                    <img src="https://www.yourhomemadehealthy.com/wp-content/uploads/2022/01/Featured-Pink-Sauce-Pasta.jpg" alt="Pasta">
                    <h3>PASTA</h3>
                </div>
            </div>
        </div>
        <div class="order-btn">
            <button>Order</button>
        </div>
    </footer>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu | Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Our Menu</h1>
    </header>

    <section class="menu-items">
        <div class="menu-card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLvBSYpdrmjC6s63P5oWgTiU4gPl36dkdVfQ&s" alt="Burger" class="menu-img">
            <h3>BURGER</h3>
        </div>
        <div class="menu-card">
            <img src="https://content3.jdmagicbox.com/comp/def_content/pizza_outlets/default-pizza-outlets-13.jpg" alt="Pizza" class="menu-img">
            <h3>PIZZA</h3>
        </div>
        <div class="menu-card">
            <img src="https://www.yourhomemadehealthy.com/wp-content/uploads/2022/01/Featured-Pink-Sauce-Pasta.jpg" alt="Pasta" class="menu-img">
            <h3>PASTA</h3>
        </div>
        <div class="menu-card">
            <img src="https://productimages.withfloats.com/actual/6240418b4918b30001de1a1e.jpg" alt="Fries" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>FRIES</h3>
        </div>
        <div class="menu-card">
            <img src="https://i2.wp.com/www.downshiftology.com/wp-content/uploads/2023/09/Vegetable-Soup-main.jpg" alt="Noodles" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>SOUP</h3>
        </div>
        <div class="menu-card">
            <img src="https://tildaricelive.s3.eu-central-1.amazonaws.com/wp-content/uploads/2023/05/09094743/INDONESIAN-TUNA-FRIED-RICE-min-scaled.webp" alt="Fried rice" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>FRIED RICE </h3>
        </div>
        <div class="menu-card">
            <img src="https://www.allrecipes.com/thmb/OJ28fIFte6Pyg93ML8IM-APbu1Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/AR-14554-sirloin-steak-with-garlic-butter-hero-4x3-d12fa79836754fcf850388e4677bbf55.jpg" alt="Steak" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>STEAK</h3>
        </div>
        <div class="menu-card">
            <img src="https://www.marthastewart.com/thmb/m6R1D2iuHvVxM8u7RJz7c-Us8Rg=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/MSL-865202-new-york-cheesecake-hero-horiz-0723-84e3c796119d408581d1ef4d02d801cd.jpg" alt="Barbique chicken" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>CHEESE CAKE</h3>
        </div>
        <div class="menu-card">
            <img src="https://pinchandswirl.com/wp-content/uploads/2024/10/Shoyu-Ramen-featured-image-500x500.jpg" alt="Fries" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>RAMEN</h3>
        </div>
        <div class="menu-card">
            <img src="https://www.sharmispassions.com/wp-content/uploads/2022/06/MangoPudding5-500x500.jpg" alt="Fries" class="menu-img"> <!-- Replace with correct Fries image URL -->
            <h3>PUDDING</h3>
        </div>
        
    </section>
</body>
</html>

login.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login | Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="login-page">
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Login to Your Account</h1>
    </header>

    <section class="login-container">
        <form>
            <div class="form-group">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" placeholder="Enter Your Email" required>
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter Your Password" required>
            </div>
            <button type="submit">Login</button>
        </form>
    </section>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | Alagappa Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="contact-page">
    <header>
        <div class="top-bar">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="login.html">Login</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
        <h1>Contact Us</h1>
    </header>

    <section class="contact-container">
        <div class="contact-info">
            <h2>Alagappa Restaurant</h2>
            <p>Cross Street, Chennai, Tamil Nadu</p>
            <p>Contact: 75275 28918</p>
            <p>Email: alagappa@email.com</p>
        </div>

        <div class="contact-form">
            <h2>Contact Form</h2>
            <form>
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Enter Your Message" required></textarea>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>
</body>
</html>

style.css

/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Global Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
}

/* Top Bar */
.top-bar {
    background-color: #000;
    padding: 10px 0;
    position: sticky;
    top: 0;
    z-index: 100;
}

.top-bar nav ul {
    list-style: none;
    text-align: center;
}

.top-bar nav ul li {
    display: inline;
    margin-right: 15px;
}

.top-bar nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.top-bar nav ul li a:hover {
    text-decoration: underline;
}

/* Home Page Header */
header h1 {
    color: #333;
    font-size: 3em;
    text-align: center;
    padding: 20px;
}

/* Image Styling */
.restaurant-img, .menu-img {
    width: 100%;
    height: auto;
}

/* Menu Page */
.menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin: 30px 0;
}

.menu-card {
    width: 250px;
    margin: 10px;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

.menu-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px 10px 0 0;
}

.menu-card h3 {
    font-size: 20px;
    padding: 15px;
    color: #333;
}

/* Contact Page */
.contact-page {
    background-color: #e8f7ff;
    padding: 40px 0;
}

.contact-container {
    display: flex;
    justify-content: space-between;
    padding: 0 10%;
}

.contact-info {
    width: 45%;
}

.contact-info h2 {
    font-size: 1.8em;
    color: #333;
    margin-bottom: 20px;
}

.contact-info p {
    font-size: 1.1em;
    margin: 10px 0;
}

.contact-form {
    width: 45%;
}

.contact-form form input, 
.contact-form form textarea {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact-form form textarea {
    resize: vertical;
    height: 150px;
}

.contact-form form button {
    background-color: #f04f44;
    color: white;
    padding: 12px;
    border: none;
    cursor: pointer;
    width: 100%;
    font-size: 1.2em;
    border-radius: 5px;
}

.contact-form form button:hover {
    background-color: #f1a1a1;
}

/* Login Page */
.login-page {
    background-color: #f4f4f4;
    padding: 40px 0;
}

.login-container {
    width: 50%;
    margin: 0 auto;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.login-container form input {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    font-size: 1em;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.login-container form button {
    background-color: #f04f44;
    color: white;
    padding: 12px;
    border: none;
    cursor: pointer;
    width: 100%;
    font-size: 1.2em;
    border-radius: 5px;
}

.login-container form button:hover {
    background-color: #f1a1a1;
}

/* Order Button */
.order-btn button {
    padding: 10px 20px;
    background-color: #f04f44;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 1.2em;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.order-btn button:hover {
    background-color: #f1a1a1;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

footer h2 {
    margin: 0;
}

footer .menu-cards {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
}

footer .menu-cards .card {
    width: 100px;
    text-align: center;
}

footer .menu-cards .card img {
    width: 80px;
    height: 80px;
}

footer .order-btn button {
    margin-top: 20px;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
    .contact-container, .login-container {
        width: 90%;
    }
    
    .menu-items {
        flex-direction: column;
        align-items: center;
    }

    .menu-card {
        width: 80%;
        margin: 15px 0;
    }
    
    header h1 {
        font-size: 2.5em;
    }
    
    .top-bar nav ul li {
        display: block;
        margin: 10px 0;
    }

    .top-bar nav ul li a {
        font-size: 16px;
    }
}

```

## OUTPUT:
![alt text](<Screenshot 2024-12-25 210840.png>)
![alt text](<Screenshot 2024-12-25 210902.png>)
![alt text](<Screenshot 2024-12-25 210942.png>)
![alt text](<Screenshot 2024-12-25 211021.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
