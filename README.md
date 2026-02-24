# Ex02 Commercial Website
## Date:24-02-2026

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
## HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar">
        <div class="logo">SubuTech</div>
        <ul class="nav-links">
            <li>Home</li>
            <li>Services</li>
            <li>About</li>
            <li>Contact</li>
        </ul>
    </nav>

    <section class="hero">
        <div class="hero-text">
            <h1>Grow Your Business With Us</h1>
            <p>We provide modern digital solutions for your business growth.</p>
            <button>Get Started</button>
        </div>
        <div class="hero-img">
            <img src="https://via.placeholder.com/400" alt="">
        </div>
    </section>

    <section class="services">
        <div class="card">Web Development</div>
        <div class="card">App Development</div>
        <div class="card">SEO Optimization</div>
        <div class="card">Marketing</div>
    </section>

    <footer class="footer">
        <p>© 2026 Subash. All rights reserved.</p>
    </footer>

</body>
</html>
```

## CSS
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #1e293b;
    color: white;
    padding: 15px 50px;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 30px;
}

.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
    flex-wrap: wrap;
}

.hero-text {
    flex: 1;
}

.hero-img {
    flex: 1;
}

.hero-img img {
    width: 100%;
}

button {
    padding: 10px 20px;
    margin-top: 15px;
    background: #2563eb;
    color: white;
    border: none;
}

.services {
    display: flex;
    justify-content: space-evenly;
    padding: 40px;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    background: #f1f5f9;
    padding: 40px;
    width: 200px;
    text-align: center;
}

.footer {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #1e293b;
    color: white;
    padding: 20px;
}
```


## OUTPUT
<img width="749" height="361" alt="image" src="https://github.com/user-attachments/assets/296c4282-3ff2-464f-93b2-1b66e8902d6e" />
<img width="1200" height="678" alt="image" src="https://github.com/user-attachments/assets/91ecc840-8f24-4bde-b822-4e09d69e3827" />




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
