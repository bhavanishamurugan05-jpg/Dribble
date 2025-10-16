# Project Responsive Web Design using Bootstrap
## Date:16-10-25

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header class="navbar">
    <div class="logo">Dribbble Clone</div>
    <nav>
      <ul>
        <li><a href="#">Inspiration</a></li>
        <li><a href="#">Find Work</a></li>
        <li><a href="#">Learn Design</a></li>
        <li><a href="#">Go Pro</a></li>
      </ul>
    </nav>
    <div class="actions">
      <input type="text" placeholder="Search..." class="search-bar" />
      <button class="btn">Sign up</button>
    </div>
  </header>

  
  <section class="hero">
    <h1>Explore the world’s leading<br>design portfolios</h1>
    <p>Millions of designers share their work, get feedback, and grow their careers on Dribbble.</p>
    <button class="btn primary">Get Started</button>
  </section>


  <section class="gallery">
    <div class="shot"><img src="Image.png 1.webp" alt="Design 1"></div>
    <div class="shot"><img src="Image .png 2.webp" alt="Design 2"></div>
    <div class="shot"><img src="image.png 3.webp" alt="Design 3"></div>
    <div class="shot"><img src="Image.png 4.webp" alt="Design 4"></div>
    <div class="shot"><img src="image.png 5.webp" alt="Design 5"></div>
  </section>

  
  <footer>
    <p>© 2025 Dribbble Clone. Built for learning purposes.</p>
  </footer>
</body>
</html>

style.css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background-color: #f9f9f9;
  color: #333;
}


.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #ea4c89;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  text-decoration: none;
  color: #555;
  font-weight: 500;
}

.actions {
  display: flex;
  align-items: center;
  gap: 10px;
}

.search-bar {
  padding: 8px 12px;
  border: 1px solid #ccc;
  border-radius: 20px;
}

.btn {
  padding: 8px 16px;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  background-color: #ea4c89;
  color: white;
  font-weight: 500;
  transition: 0.3s;
}

.btn:hover {
  background-color: #d63b76;
}


.hero {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(135deg, #fce3ec, #f9f0ff);
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
  color: #222;
}

.hero p {
  font-size: 1.1rem;
  margin-bottom: 30px;
  color: #555;
}

.primary {
  background-color: #ea4c89;
}


.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 40px;
}

.shot img {
  width: 100%;
  border-radius: 12px;
  transition: transform 0.3s ease;
}

.shot img:hover {
  transform: scale(1.05);
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #fff;
  font-size: 0.9rem;
  color: #666;
  border-top: 1px solid #eee;
}
```

## OUTPUT:
![pjt](https://github.com/user-attachments/assets/c03f7722-d0d6-42f3-b6d9-2dcbfac6c602)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
