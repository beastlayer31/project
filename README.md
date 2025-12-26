# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<html>
<head>
    <meta charset="UTF-8">
    <title>Sign In | Not Dribbble</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="navbar">
    <h1 class="logo">Not Dribbble</h1>
    <nav>
        <a href="web.html">Home</a>
        <a href="explore.html">Explore</a>
        <a href="desg.html">Designers</a>
    </nav>
</header>
<section class="signin">
    <h2>Sign In</h2>
    <form class="signin-form">
        <label>Email</label>
        <input type="email" placeholder="you@example.com" required>
        <label>Password</label>
        <input type="password" placeholder="••••••••" required>
        <button type="submit">Sign In</button>
        <p class="note">
            Don't have an account? <a href="singu.html">Sign up</a>
        </p>
    </form>
</section>
</body>
</html>
```
```
<html>
<head>
    <meta charset="UTF-8">
    <title>Designers | Not Dribbble</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="navbar">
    <h1 class="logo">Not Dribbble</h1>
    <nav>
        <a href="web.html">Home</a>
        <a href="explore.html">Explore</a>
        <a href="desg.html">Designers</a>
        <a href="sign.html" class="btn">Sign In</a>
    </nav>
</header>
<section class="designers">
    <h2>Top Designers</h2>

    <div class="designer-grid">
        <div class="designer-card">
            <div class="avatar">A</div>
            <h3>Arjun Kumar</h3>
            <p>UI / UX Designer</p>
        </div>
        <div class="designer-card">
            <div class="avatar">S</div>
            <h3>Sneha Rao</h3>
            <p>Web Designer</p>
        </div>
        <div class="designer-card">
            <div class="avatar">R</div>
            <h3>Rahul Mehta</h3>
            <p>Product Designer</p>
        </div>
        <div class="designer-card">
            <div class="avatar">P</div>
            <h3>Priya Sharma</h3>
            <p>Graphic Designer</p>
        </div>
        <div class="designer-card">
            <div class="avatar">K</div>
            <h3>Karthik V</h3>
            <p>Illustrator</p>
        </div>
        <div class="designer-card">
            <div class="avatar">N</div>
            <h3>Nisha Patel</h3>
            <p>Brand Designer</p>
        </div>
    </div>
</section>
</body>
</html>
```
```
<html>
<head>
    <meta charset="UTF-8">
    <title>Explore | Not Dribbble</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="navbar">
    <h1 class="logo">Not Dribbble</h1>
    <nav>
        <a href="web.html">Home</a>
        <a href="explore.html">Explore</a>
        <a href="desg.html">Designers</a>
        <a href="sign.html" class="btn">Sign In</a>
    </nav>
</header>
<section class="explore">
    <h2>Explore Creative Work</h2>
    <div class="categories">
        <span>UI Design</span>
        <span>Web Design</span>
        <span>Illustration</span>
        <span>Branding</span>
        <span>Logos</span>
        <span>Dashboards</span>
    </div>
    <h3>Trending Now</h3>
    <div class="explore-grid">
        <div class="explore-card">
            <img src="mob.jpg">
            <p>Mobile App UI</p>
        </div>
        <div class="explore-card">
            <img src="web.jpg">
            <p>Landing Page</p>
        </div>
        <div class="explore-card">
            <img src="dash.jpg">
            <p>Dashboard Design</p>
        </div>
    </div>
    <h3>Popular This Week</h3>
    <div class="explore-grid">
        <div class="explore-card">
            <img src="logo.jpg">
            <p>Logo Concept</p>
        </div>
        <div class="explore-card">
            <img src="ill.jpg">
            <p>Illustration</p>
        </div>
        <div class="explore-card">
            <img src="port.jpg">
            <p>Portfolio Design</p>
        </div>
    </div>
</section>
</body>
</html>
```
```
<html>
<head>
    <meta charset="UTF-8">
    <title>Not Dribbble</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="navbar">
        <h1 class="logo">Not Dribbble</h1>
        <nav>
            <a href="web.html">Home</a>
            <a href="explore.html">Explore</a>
            <a href="desg.html">Designers</a>
            <a href="sign.html" class="btn">Sign In</a>
        </nav>
    </header>
    <section class="hero">
        <h2>Discover the world's top designers</h2>
        <p>Explore creative work from designers around the globe</p>
    </section>
    <section class="gallery">
        <div class="card">
            <img src="mob.jpg" class="image">
            <p>Mobile App UI</p>
        </div>
        <div class="card">
            <img src="web.jpg" class="image">
            <p>Website Landing Page</p>
        </div>
        <div class="card">
            <img src="dash.jpg" class="image">
            <p>Dashboard Design</p>
        </div>
        <div class="card">
            <img src="logo.jpg" class="image">
            <p>Logo Concept</p>
        </div>
        <div class="card">
            <img src="ill.jpg" class="image">
            <p>Illustration</p>
        </div>
        <div class="card">
            <img src="port.jpg" class="image">
            <p>Portfolio Design</p>
        </div>
    </section>
    <footer>
        <p>© 2025 Not Dribbble. All rights reserved.</p>
    </footer>
</body>
</html>
```
```
<html>
<head>
    <meta charset="UTF-8">
    <title>Sign Up | Not Dribbble</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="navbar">
    <h1 class="logo">Not Dribbble</h1>
    <nav>
        <a href="web.html">Home</a>
        <a href="explore.html">Explore</a>
        <a href="desg.html">Designers</a>
        <a href="sign.html" class="btn">Sign In</a>
    </nav>
</header>
<section class="signin">
    <form class="signin-form">
        <h2>Create Account</h2>
        <label>Full Name</label>
        <input type="text" placeholder="Your name" required>
        <label>Email</label>
        <input type="email" placeholder="you@example.com" required>
        <label>Password</label>
        <input type="password" placeholder="Create a password" required>
        <label>Confirm Password</label>
        <input type="password" placeholder="Confirm password" required>
        <button type="submit">Sign Up</button>
        <p class="note">
            Already have an account?
            <a href="sign.html">Sign in</a>
        </p>
    </form>
</section>
</body>
</html>
```
```* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
    border-bottom: 1px solid #ddd;
}

.logo {
    color: #ea4c89;
}

nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #333;
    font-weight: 500;
}

.btn {
    padding: 6px 14px;
    border: 1px solid #ea4c89;
    border-radius: 20px;
    color: #ea4c89;
}

.hero {
    text-align: center;
    padding: 60px 20px;
    background: #f9f9f9;
}

.gallery,
.shots,
.explore-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    padding: 40px;
}

.card,
.shot,
.explore-card {
    width: 100%;
}

.image,
.shot img,
.explore-card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
    border-radius: 10px;
}

.card p,
.shot p,
.explore-card p {
    margin-top: 8px;
    font-weight: 600;
}

.explore {
    padding: 40px;
}

.categories {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin: 20px 0;
}

.categories span {
    padding: 10px 18px;
    background: #f1f1f1;
    border-radius: 20px;
    font-weight: 500;
}

footer {
    text-align: center;
    padding: 20px;
    background: #f1f1f1;
}
.designers {
    padding: 40px;
}
.designers h2 {
    margin-bottom: 20px;
}
.designer-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}
.designer-card {
    border: 1px solid #eee;
    border-radius: 12px;
    padding: 20px;
    text-align: center;
}
.avatar {
    width: 60px;
    height: 60px;
    margin: 0 auto 10px;
    background: #ea4c89;
    color: white;
    border-radius: 50%;
    font-size: 24px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.designer-card h3 {
    margin-bottom: 5px;
}
.designer-card p {
    color: #666;
    font-size: 14px;
}
.signin {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 60px 20px;
}
.signin-form {
    width: 100%;
    max-width: 360px;
    border: 1px solid #eee;
    border-radius: 12px;
    padding: 30px;
}
.signin-form h2 {
    text-align: center;
    margin-bottom: 20px;
}
.signin-form label {
    display: block;
    margin: 15px 0 5px;
    font-weight: 500;
}
.signin-form input {
    width: 100%;
    padding: 10px;
    border-radius: 6px;
    border: 1px solid #ccc;
}
.signin-form button {
    width: 100%;
    margin-top: 20px;
    padding: 10px;
    border: none;
    border-radius: 20px;
    background: #ea4c89;
    color: white;
    font-weight: 600;
    cursor: pointer;
}
.signin-form .note {
    text-align: center;
    margin-top: 15px;
    font-size: 14px;
}
.signin-form .note a {
    color: #ea4c89;
    text-decoration: none;
}
```
# OUTPUT:
<img width="1917" height="976" alt="image" src="https://github.com/user-attachments/assets/2dcc351f-3d9e-4e61-b892-dcf7b7d8a5d1" />
<img width="1919" height="962" alt="image" src="https://github.com/user-attachments/assets/418e41de-92e1-41c9-8c2a-5820747d69ca" />
<img width="1919" height="937" alt="image" src="https://github.com/user-attachments/assets/12aa8e47-0b50-48d6-96e9-82bfd40f0502" />
<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/ab0d67d4-41cb-4e28-a384-682dc8e0dbdc" />
<img width="1918" height="998" alt="image" src="https://github.com/user-attachments/assets/a05a1aa3-e98a-4afb-85ac-0d67c0803970" />




# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
