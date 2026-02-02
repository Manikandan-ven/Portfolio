# Ex01 Portfolio
## Date:2/2/2026

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
  <title>Lokesh B | Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1 class="logo">Lokesh B</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#tech">Tech</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <img src="profile.jpg" alt="Profile Image">
    <h2>Hello, I'm <span>Lokesh B</span></h2>
    <p>Designer | Full Stack Developer</p>
    <p>2nd Year CSE Student</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
      I am a 2nd-year Computer Science student with a strong interest in full-stack development.
      I enjoy learning modern web technologies and building simple, user-friendly applications.
    </p>
  </section>

  <section id="skills" class="section light">
    <h2>Skills</h2>

    <div class="box">
      <h3>Design</h3>
      <div class="items">
        <span>UI/UX</span>
        <span>Canva</span>
        <span>Figma</span>
      </div>
    </div>

    <div class="box">
      <h3>Frontend</h3>
      <div class="items">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>React</span>
      </div>
    </div>

    <div class="box">
      <h3>Backend</h3>
      <div class="items">
        <span>Node.js</span>
        <span>Express</span>
        <span>REST API</span>
      </div>
    </div>
  </section>

  <section id="tech" class="section">
    <h2>Tech Stack</h2>
    <div class="items">
      <span>MongoDB</span>
      <span>SQL</span>
      <span>Git & GitHub</span>
      <span>DSA</span>
      <span>Cloud Basics</span>
    </div>
  </section>

  <section id="contact" class="section light">
    <h2>Contact</h2>
    <p>Email: lokesh@gmail.com</p>
    <p>Location: Chennai, India</p>
  </section>
  <footer>
    <p>© 2026 Lokesh B | Built with HTML & CSS</p>
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
  font-family: "Segoe UI", sans-serif;
}

body {
  background: #8e3b72;
  color: #ffffff;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 10%;
  background: #020332;
  position: sticky;
  top: 0;
}

.logo {
  font-size: 1.5rem;
}

nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #fff;
}

nav a:hover {
  color: #b9b6ff;
}

.hero {
  height: 85vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero img {
  width: 220px;
  height: 220px;
  border-radius: 20px;
  margin-bottom: 20px;
  object-fit: cover;
}

.hero h2 span {
  color: #ffd6f2;
}

.hero p {
  margin-top: 8px;
  opacity: 0.9;
}

.section {
  padding: 70px 10%;
  text-align: center;
}

.section h2 {
  margin-bottom: 20px;
  color: #ffd6f2;
}

.light {
  background: #9a9bbb;
}

.box {
  margin-bottom: 30px;
}

.items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 12px;
}

.items span {
  background: #020332;
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 0.9rem;
}

footer {
  background: #0f0f0f;
  padding: 15px;
  text-align: center;
  font-size: 0.85rem;
  opacity: 0.7;
}

```

## OUTPUT
![alt text](<Screenshot 2026-02-02 122033.png>)
![alt text](<Screenshot 2026-02-02 122116.png>)
## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
