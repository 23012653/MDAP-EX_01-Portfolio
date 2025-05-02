# MDAP-EX_01-Portfolio
## Date: 02-05-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <div class="logo">MyPortfolio</div>
      <ul class="nav-links">
        <li><a href="#intro">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="intro" class="section intro">
    <div class="content">
      <h1>Hello, I'm <span>Anubharathi SS</span></h1>
      <p>I’m a front-end developer passionate about creating beautiful and functional web interfaces.</p>
    </div>
  </section>

  <section id="about" class="section about">
    <h2>About Me</h2>
    <p>I design and develop responsive websites using modern web technologies like HTML, CSS, and JavaScript.</p>
  </section>

  <section id="projects" class="section projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project">
        <h3>Responsive Website</h3>
        <p>A fully responsive website layout using Flexbox and Grid.</p>
      </div>
      <div class="project">
        <h3>To-Do Web App</h3>
        <p>An interactive JavaScript-based to-do list with filtering and persistence.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section contact">
    <h2>Contact Me</h2>
    <p>Email: anubharathi05@gamil.com</p>
    <p>GitHub: <a href="#">github.com/23012653</a></p>
  </section>

  <footer>
    <p>&copy; 2025 MyPortfolio. All rights reserved.</p>
  </footer>
</body>
</html>

```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    font-family: 'Segoe UI', sans-serif;
    background: #f7f9fc;
    color: #333;
    line-height: 1.6;
  }
  a {
    color: #16a833;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  
  header {
    background: #fff;
    padding: 20px 40px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .logo {
    font-size: 1.6rem;
    font-weight: bold;
    color: #4caf50;
  }
  .nav-links {
    display: flex;
    gap: 20px;
  }
  .nav-links li {
    list-style: none;
  }
  .nav-links a {
    padding: 8px 12px;
    border-radius: 6px;
    transition: background 0.3s;
  }
  .nav-links a:hover {
    background-color: #e8f5e9;
  }
  .section {
    padding: 60px 40px;
    text-align: center;
  }
  .intro {
    background: linear-gradient(to right, #4caf50, #81c784);
    color: white;
  }
  .intro h1 span {
    color: #ffe082;
  }
  .about, .projects, .contact {
    background: white;
  }
  .projects .project-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 30px;
  }
  .project {
    background: #f0f2f5;
    padding: 20px;
    border-radius: 12px;
    transition: transform 0.3s ease;
  }
  .project:hover {
    transform: translateY(-5px);
  }
  footer {
    background: #4caf50;
    color: white;
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
  }
  
```

## OUTPUT
![Screenshot 2025-05-02 215422](https://github.com/user-attachments/assets/0e29e928-16fc-453a-865a-4a9b6f3de289)

![Screenshot 2025-05-02 214942](https://github.com/user-attachments/assets/d68ee165-1333-4048-ba54-f42217f05989)




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
