# Ex02 Commercial Website
## Date: 20/08/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<html>
<head>
    <title>Commercial Website </title>
    <link rel="stylesheet" href="web.css">
</head>

<body>

    <!-- Header -->
    <header>
        <h1>Spectrum</h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#account">Account</a>
        </nav>
    </header>

    <!-- Home -->
    <section id="home" class="box">
        <div>
            <h2>Welcome to Spectrum</h2>
            <p>We provide quality products at affordable prices.</p>
            <img src="stt.jpg" alt="Store">
        </div>
    </section>

    <!-- Products -->
    <section id="products">
        <h2>Our Products</h2>

        <div class="products">

            <div class="card">
                <img src="shoes.jpg" alt="Watch">
                <h3>Shoes</h3>
                <p>Price: ₹999</p>
            </div>

            <div class="card">
                <img src="watch.jpg" alt="Watch">
                <h3>Watch</h3>
                <p>Price: ₹1499</p>
            </div>

            <div class="card">
                <img src="bag.jpg" alt="Bag">
                <h3>Bag</h3>
                <p>Price: ₹799</p>
            </div>

        </div>
    </section>

    <!-- About -->
    <section id="about" class="box">
        <h2>About Us</h2>
        <p>
            ABC Store is a trusted online shopping platform offering
            quality products with excellent customer service.
        </p>
    </section>

    <!-- Contact -->
    <section id="contact" class="box">
        <h2>Contact Us</h2>

        <p>Email: abcstore@gmail.com</p>
        <p>Phone: +91 9876543210</p>
        <p>Address: Chennai, Tamil Nadu</p>
    </section>

    <!-- Account -->
    <section id="account" class="box">
        <h2>User Account</h2>

        <form>
            <input type="text" placeholder="Username"><br><br>

            <input type="password" placeholder="Password"><br><br>

            <button>Login</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>

        <p>
            Follow Us:
            <a href="#">Facebook</a> |
            <a href="#">Instagram</a> |
            <a href="#">Twitter</a>
        </p>
        <p>Dharshini K (212225240034)</p>
        <p>© 2026 ABC Store. All Rights Reserved.</p>

    </footer>

</body>
</html>
```
```
/* General */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, sans-serif;
    background:#fff0f5;
    color:#333;
}

/* Header */

header{
    background:linear-gradient(to right,#ff69b4,#ff1493);
    color:white;
    text-align:center;
    padding:25px;
}

header h1{
    margin-bottom:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-size:18px;
    transition:0.3s;
}

nav a:hover{
    color:#ffe4ec;
    text-decoration:underline;
}

/* Sections */

section{
    padding:40px 20px;
    text-align:center;
}

section h2{
    color:#d63384;
    margin-bottom:20px;
}

/* Home Image */

.box img{
    width:450px;
    max-width:90%;
    border-radius:15px;
    margin-top:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

/* Products */

.products{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:25px;
}

.card{
    background:white;
    width:230px;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,0.15);
    transition:0.3s;
}

.card img{
    width:100%;
    height:200px;
}

.card h3{
    margin:15px 0 10px;
    color:#d63384;
}

.card p{
    margin-bottom:15px;
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 10px 20px rgba(255,20,147,0.3);
}

/* About, Contact & Account */

.box{
    background:white;
    width:80%;
    margin:25px auto;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

/* Form */

input{
    width:250px;
    padding:10px;
    margin:10px;
    border:1px solid #ff69b4;
    border-radius:5px;
}

button{
    background:#ff1493;
    color:white;
    border:none;
    padding:10px 25px;
    border-radius:5px;
}
footer{
    background:#ff69b4;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:25px;
}
```
## OUTPUT
<img width="1600" height="900" alt="WhatsApp Image 2026-08-20 at 1 23 29 PM" src="https://github.com/user-attachments/assets/cc5c3e29-9988-48e4-8645-00b1ef314e56" />
<img width="1600" height="900" alt="WhatsApp Image 2026-08-20 at 1 23 30 PM" src="https://github.com/user-attachments/assets/96426454-283d-44fa-9b2c-66785b007bc5" />
<img width="1600" height="900" alt="WhatsApp Image 2026-08-20 at 1 23 30 PM (1)" src="https://github.com/user-attachments/assets/e755dd40-3e4b-47d9-a25b-80cd11390e1d" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
