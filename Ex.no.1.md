# Ex01 Portfolio
## Date:

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
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gayathri | Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Gayathri</h1>
    <p>Third-year Learner | Aspiring Developer</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <div class="about-container">
      <img src="IMG-20240102-WA0002.jpg" alt="Gayathri's profile photo">
      <p>Hello! I'm Gayathri, a passionate Third-year college learner with a love for technology, problem-solving, and creativity. I enjoy learning new skills and working on projects that challenge me.</p>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">Java</div>
      <div class="card">Python</div>
      <div class="card">JavaScript</div>
      <div class="card">C Programming</div>
      <div class="card">Problem Solving</div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Student Grievance Portal</h3>
        <p>A web-based platform to register and track student grievances efficiently.</p>
      </div>
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>Personal portfolio to showcase my skills, projects, and achievements.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:gayathrimurugan006@gmail.com">gayathrimurugan006@gmail.com</a></p>
    <div class="contact-links">
      <a href="https://www.linkedin.com/in/gayathri-murugan-2aba16324/" target="_blank">LinkedIn</a>
      <a href="https://github.com/gayathrimurugan12" target="_blank">GitHub</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Gayathri M (212223220024)</p>
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
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: linear-gradient(135deg, #f0f0f0, #e8f5e9);
    color: #222;
}

header {
    background: linear-gradient(135deg, #6a11cb, #2575fc);
    color: white;
    text-align: center;
    padding: 2rem 0;
    border-bottom-left-radius: 40px;
    border-bottom-right-radius: 40px;
}

header h1 {
    font-size: 2.8rem;
    letter-spacing: 1px;
}

nav {
    background: white;
    padding: 0.8rem;
    text-align: center;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
}

nav a {
    color: #2575fc;
    margin: 0 15px;
    text-decoration: none;
    font-weight: 600;
}

nav a:hover {
    border-bottom: 2px solid #2575fc;
}

section {
    max-width: 1000px;
    margin: auto;
    padding: 2.5rem;
}

h2 {
    margin-bottom: 1rem;
    color: #2575fc;
    font-size: 2rem;
}

.about-container {
    display: flex;
    align-items: center;
    gap: 2rem;
    flex-wrap: wrap;
}

.about-container img {
    width: 220px;
    height: 220px;
    border-radius: 20px;
    object-fit: cover;
    box-shadow: 0 4px 15px rgba(0,0,0,0.15);
}

.skills, .projects {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
}

.card {
    background: white;
    padding: 1.5rem;
    flex: 1 1 calc(33% - 1rem);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    border-radius: 15px;
    transition: transform 0.2s ease;
}

.card:hover {
    transform: translateY(-5px);
}

.contact-links a {
    display: inline-block;
    margin: 0.5rem 1rem 0 0;
    padding: 0.6rem 1.2rem;
    background: linear-gradient(135deg, #6a11cb, #2575fc);
    color: white;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}

.contact-links a:hover {
    opacity: 0.9;
}

footer {
    background: #222;
    color: #ddd;
    text-align: center;
    padding: 1.2rem 0;
    margin-top: 2rem;
    border-top: 3px solid #2575fc;
}

```

## OUTPUT
<img width="1903" height="1013" alt="image" src="https://github.com/user-attachments/assets/2e8b71a2-0c08-4bf7-9eee-7762e4f5d15e" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
