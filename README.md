# MDAP-EX_01-Portfolio
## Date: 30-04-2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
    
         {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f5f5f5;
            color: #333;
            align: center
        }

        header {
            background-color: #212223;
            color: white;
            padding: 15px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
        }
        nav ul li a:hover {
            color: #636261;
        }

        section {
            padding: 60px 20px;
            margin: 80px 20px 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
        }

        .project {
            background-color: #e6f2ff;
            padding: 15px;
            border-radius: 8px;
            margin: 10px 0;
        }

        #contact a {
            color: #5f6061;
            text-decoration: none;
            font-weight: bold;
        }
        #contact a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #7a7b7c;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }
            section {
                padding: 40px 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Anubharathi SS</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internship">Internship</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello!I am a front developer passionate about to create a visual aspects of webpage and application.This role excites me because it combine creativity with technology.I like to make a websites not only good but also function smoothly over different devices.</p>
</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Mobile App UI</h3>
                <p>A sleek mobile-first user interface prototype for a task management app, focusing on intuitive navigation and user experience.</p>
            </div>
            <div class="project">
                <h3>E-Commerce Template</h3>
                <p>An e-commerce product page with interactive filtering, responsive layout, and a simple cart system built using vanilla JavaScript.</p>
            </div>
        </section>

        <section id="internship">
            <h2>Internship</h2>
            <h3>Design-Oriented:<h3></h3>
            <p>"Collaborated on UI/UX during my internship by creating a mobile-friendly portfolio website with a modern aesthetic.</p>
        </section>


        <section id="skills">
            <h2>Skills</h2>
            <ul>
              <li><strong>Frontend:</strong> HTML5, CSS3, JavaScript, Bootstrap, Tailwind CSS</li>
              <li><strong>Frameworks:</strong> React.js (basics)</li>
              <li><strong>Tools:</strong> Git, GitHub, VS Code, Chrome DevTools</li>
              <li><strong>Design:</strong> Responsive Web Design, UI/UX Principles, Figma (basic)</li>
              <li><strong>Soft Skills:</strong> Problem-solving, Teamwork, Communication, Time Management</li>
            </ul>
          </section>
          

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: anubharathi05@gmail.com</p>
        </section>
    </main>

    <footer>
        <p>&copy;2025 portfolio. All Rights Reserved.</p>
    </footer>

</body>
</html>
```


## OUTPUT
![Screenshot 2025-04-30 090957](https://github.com/user-attachments/assets/b286247c-05ce-4b5c-ab05-87036d207eb7)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
