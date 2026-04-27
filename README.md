# Ex01 Portfolio
## Date: 27-04-2026

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
HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Viswa Prakaash | Resume</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

    <header>
        <h1>VISWA PRAKAASH N J</h1>
        <p>📞 +91 8610484780 | ✉️ viswaprakaash3@gmail.com</p>
        <p>
            <a href="https://github.com/ViswaPrakaashNJ">GitHub</a> |
            <a href="https://www.linkedin.com/in/viswa-prakaash-n-j-166b29357/">LinkedIn</a>
        </p>
    </header>

    <section>
        <h2>Career Objective</h2>
        <p>
            BE Computer Science Engineering student with strong programming and web development skills.
            Skilled in Python, Java, C, HTML, CSS, JavaScript, and basic React. Familiar with Git,
            AWS basics, Django, and MySQL.
        </p>
    </section>

    <section>
        <h2>Education</h2>
        <p><strong>B.E Computer Science Engineering</strong></p>
        <p>Saveetha Engineering College, Chennai (2023 – 2027) | CGPA: 7.7</p>

        <p><strong>HSC</strong></p>
        <p>Sri Krish International School CBSE, Chennai (2021 – 2023)</p>
    </section>

    <section>
        <h2>Internships & Training</h2>
        <ul>
            <li><strong>Cybersecurity Intern – Zybeak Technologies</strong> (Jan 2025)</li>
            <li><strong>Full Stack Training – RETECH Solutions</strong> (July 2024)</li>
        </ul>
    </section>

    <section>
        <h2>Projects</h2>
        <ul>
            <li><strong>AI-based Pneumonia Detection System</strong></li>
        </ul>
    </section>

    <section class="two-column">
        <div>
            <h2>Technical Skills</h2>
            <span class="tag">Python</span>
            <span class="tag">Java</span>
            <span class="tag">C</span>
            <span class="tag">SQL</span>
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
        </div>

        <div>
            <h2>Soft Skills</h2>
            <ul>
                <li>Communication</li>
                <li>Teamwork</li>
                <li>Leadership</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>Certifications</h2>
        <ul>
            <li>AWS Cloud Solution Architect – Coursera</li>
            <li>Natural Language Processing – Coursera</li>
        </ul>
    </section>

</div>

</body>
</html>
```

CSS
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f6f8;
    color: #333;
}

.container {
    width: 80%;
    margin: 30px auto;
    background: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

header {
    text-align: center;
    margin-bottom: 20px;
}

header h1 {
    color: #2c3e50;
}

header a {
    color: #3498db;
    text-decoration: none;
}

section {
    margin-bottom: 25px;
}

h2 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    margin-bottom: 10px;
    padding-bottom: 5px;
}

ul {
    margin-left: 20px;
}

.two-column {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.two-column div {
    width: 48%;
}

.tag {
    display: inline-block;
    background: #3498db;
    color: white;
    padding: 5px 10px;
    margin: 5px;
    border-radius: 5px;
    font-size: 14px;
}

@media (max-width: 768px) {
    .container {
        width: 95%;
    }

    .two-column div {
        width: 100%;
    }
}
```

## OUTPUT

<img width="1517" height="828" alt="image" src="https://github.com/user-attachments/assets/cad1ac63-8eec-4593-b584-d1927b77b79e" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
