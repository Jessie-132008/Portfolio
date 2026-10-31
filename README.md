# Ex01 Portfolio
## Date: 31/10/2026

```
Name :  JESSIE J
Reg. No : 212225040153
```

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

about.html
```
<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html" class="active">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>About Me</h1>

    <p class="lead">
        Computer Science Engineering Student
    </p>

    <p>
        I am Jessie J, a Computer Science and Engineering
        student at Saveetha Engineering College.
    </p>

    <p>
        I enjoy learning programming languages,
        developing websites, and solving problems
        using technology.
    </p>

    <p>
        My goal is to improve my technical skills
        and become a skilled software developer.
    </p>

    <a href="port.html" class="btn">Back to Home</a>
</div>

</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Me</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html" class="active">Contact</a>
</div>

<div class="page">
    <h1>Contact Me</h1>

    <p>Email: jessiejohnson132008@gmail.com</p>
    <p>Phone: 9840506502</p>

    <p>
        LinkedIn:
        <a href="https://www.linkedin.com/"
           target="_blank">
            https://www.linkedin.com/in/jessie-j-25108637a
        </a>
    </p>

    <p>
        GitHub:
        <a href="https://github.com/"
           target="_blank">
            https://github.com/Jessie-132008
        </a>
    </p>
</div>

</body>
</html>
```

port.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Jessie | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="nav">
    <a href="port.html" class="active">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="home">
    <h1>Hello, I'm Jessie J</h1>
    <p>Computer Science Engineering Student</p>
    <p>
        I am passionate about programming,
        web development, and learning new technologies.
    </p>
    <a href="about.html" class="btn">Know More About Me</a>
</div>

</body>
</html>
```

projects.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Projects</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html" class="active">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>My Projects</h1>

    <div class="projects-container">

        <div class="project">
            <h3>Personal Portfolio</h3>
            <p>
                A personal website created using HTML
                and CSS to display my profile and skills.
            </p>
        </div>

        <div class="project">
            <h3>Smart Disaster Response System</h3>
            <p>
                An academic project designed to coordinate
                disaster incidents, rescue teams, resources,
                and emergency missions.
            </p>
        </div>

        <div class="project">
            <h3>Image to PDF Converter</h3>
            <p>
                A simple application idea for converting
                images into a PDF document.
            </p>
        </div>

    </div>
</div>

</body>
</html>
```

skills.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Skills</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html" class="active">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>My Skills</h1>

    <div class="skills-container">
        <div class="skill">C Programming</div>
        <div class="skill">Python</div>
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">Java</div>
        <div class="skill">Problem Solving</div>
        <div class="skill">MS Office</div>
    </div>
</div>

</body>
</html>
```

style.css
```
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: "Segoe UI", Arial, sans-serif;
    background: #080B12;
    color: #CBD5E1;
}

/* Navigation Bar */
.nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 12px;
    padding: 20px;
    background: #080B12;
    border-bottom: 1px solid #1E293B;
}

.nav a {
    color: #CBD5E1;
    text-decoration: none;
    padding: 10px 18px;
    border-radius: 6px;
    font-weight: 600;
    transition: 0.3s;
}

.nav a:hover,
.nav a.active {
    background: #0B1F3A;
    color: #60A5FA;
}

/* Home Page */
.home {
    text-align: center;
    padding: 130px 20px;
    margin: 25px;
    border-radius: 15px;
    background: linear-gradient(
        135deg,
        #080B12,
        #0B1F3A
    );
    border: 1px solid #1E3A5F;
}

.home h1 {
    font-size: 48px;
    color: #FFFFFF;
    margin-bottom: 15px;
}

.home p {
    font-size: 18px;
    line-height: 1.8;
    color: #CBD5E1;
}

/* Common Page Sections */
.page {
    max-width: 950px;
    margin: 45px auto;
    padding: 40px;
    background: #0D1421;
    border: 1px solid #1E293B;
    border-radius: 12px;
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.35);
    animation: fadeIn 0.5s ease;
}

.page h1 {
    color: #FFFFFF;
    font-size: 32px;
    border-bottom: 3px solid #3B82F6;
    display: inline-block;
    padding-bottom: 8px;
}

.page h2 {
    color: #E2E8F0;
}

.page p {
    line-height: 1.8;
}

/* Buttons */
.btn {
    display: inline-block;
    margin: 10px 8px 10px 0;
    padding: 12px 22px;
    background: #0B1F3A;
    color: #FFFFFF;
    text-decoration: none;
    border: 1px solid #3B82F6;
    border-radius: 6px;
    font-weight: 600;
    transition: 0.3s;
}

.btn:hover {
    background: #2563EB;
    transform: translateY(-2px);
}

/* Contact Links */
.page a:not(.btn) {
    color: #60A5FA;
    font-weight: 600;
    text-decoration: none;
}

.page a:not(.btn):hover {
    color: #FFFFFF;
    text-decoration: underline;
}

/* Skills */
.skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 25px;
}

.skill {
    padding: 12px 20px;
    background: #0B1F3A;
    color: #DBEAFE;
    border: 1px solid #1E3A5F;
    border-radius: 6px;
    font-weight: 600;
    transition: 0.3s;
}

.skill:hover {
    background: #1E3A5F;
    transform: translateY(-3px);
}

/* Projects */
.projects-container {
    display: grid;
    grid-template-columns: repeat(
        auto-fit,
        minmax(230px, 1fr)
    );
    gap: 25px;
    margin-top: 30px;
}

.project {
    padding: 25px;
    background: #080B12;
    border: 1px solid #1E293B;
    border-left: 4px solid #3B82F6;
    border-radius: 8px;
    transition: 0.3s;
}

.project:hover {
    transform: translateY(-5px);
    border-color: #3B82F6;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
}

.project h3 {
    color: #FFFFFF;
}

.project p {
    line-height: 1.7;
}

/* Responsive Design */
@media (max-width: 600px) {
    .home {
        margin: 15px;
        padding: 70px 15px;
    }

    .home h1 {
        font-size: 32px;
    }

    .page {
        margin: 20px;
        padding: 25px;
    }

    .nav {
        gap: 6px;
    }

    .nav a {
        padding: 8px 12px;
    }
}

/* Animation */
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(12px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

```

## OUTPUT
<img width="1907" height="992" alt="image" src="https://github.com/user-attachments/assets/e2dd3597-f12b-4e67-a0b5-9f929a95cca4" />
<img width="1910" height="962" alt="image" src="https://github.com/user-attachments/assets/cb500c69-9c4b-4b12-a12e-a4be0c9a16a7" />
<img width="1917" height="976" alt="image" src="https://github.com/user-attachments/assets/3dc6d7d2-aac6-46d0-9ee5-98576297c3f8" />
<img width="1905" height="956" alt="image" src="https://github.com/user-attachments/assets/f4ed65bd-28ae-4a8a-93ff-fe60a6038953" />
<img width="1907" height="955" alt="image" src="https://github.com/user-attachments/assets/7aa69a5f-7eac-4f31-9606-3352562e7c3c" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
