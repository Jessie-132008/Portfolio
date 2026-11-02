# Ex01 Portfolio
## Date: 02/11/2026

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
</head>

<body bgcolor="#FFF8E7" text="#2B171B">

    <center>
        <h1><font color="#800020">ABOUT ME</font></h1>
        <p><i>Get to know me better</i></p>

        <hr color="#800020">

        <form>
            <button formaction="index.html">Home</button>
            <button formaction="about.html">About Me</button>
            <button formaction="skills.html">My Skills</button>
            <button formaction="projects.html">My Projects</button>
            <button formaction="contact.html">Contact</button>
        </form>

        <br>

        <img src="formal pic.jpg" alt="My Photo" width="160" height="180">
    </center>

    <h2><font color="#800020">Who Am I?</font></h2>

    <p>
        Hello! I am Jessie J, a Computer Science Engineering student
        at Saveetha Engineering College.
    </p>

    <p>
        I am interested in programming, web development, and learning
        new technologies. I enjoy exploring new concepts and improving
        my technical skills through practice and projects.
    </p>

    <h2><font color="#800020">Education</font></h2>

    <table border="1" cellpadding="10" cellspacing="0" width="100%">
        <tr bgcolor="#800020">
            <th><font color="#FFF8E7">Details</font></th>
            <th><font color="#FFF8E7">Information</font></th>
        </tr>

        <tr>
            <td>College</td>
            <td>Saveetha Engineering College</td>
        </tr>

        <tr>
            <td>Department</td>
            <td>Computer Science and Engineering</td>
        </tr>

        <tr>
            <td>Year</td>
            <td>Second Year</td>
        </tr>
    </table>

    <h2><font color="#800020">My Interests</font></h2>

    <ul>
        <li>Programming</li>
        <li>Web Development</li>
        <li>Technology and Innovation</li>
        <li>Learning new skills</li>
        <li>Working on team projects</li>
    </ul>

    <center>
        <hr color="#800020">
        <p><font color="#800020">© 2026 Jessie J</font></p>
    </center>

</body>
</html>
```

contact.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Me</title>
</head>

<body bgcolor="#FFF8E7" text="#2B171B">

    <center>
        <h1><font color="#800020">LET'S CONNECT</font></h1>
        <p><i>Have a question or want to get in touch?</i></p>

        <hr color="#800020">

        <form>
            <button formaction="index.html">Home</button>
            <button formaction="about.html">About Me</button>
            <button formaction="skills.html">My Skills</button>
            <button formaction="projects.html">My Projects</button>
            <button formaction="contact.html">Contact</button>
        </form>

        <h2><font color="#800020">Get In Touch</font></h2>

        <table border="1" cellpadding="18" cellspacing="10" width="85%">

            <tr>
                <td align="center">
                    <h2><font color="#800020">Email</font></h2>
                    <p>Feel free to send me an email.</p>
                    <a href="mailto:your-email@example.com">
                        Send Me an Email
                    </a>
                </td>

                <td align="center">
                    <h2><font color="#800020">LinkedIn</font></h2>
                    <p>Connect with me professionally.</p>
                    <a href="https://www.linkedin.com/" target="_blank">
                        Visit LinkedIn
                    </a>
                </td>
            </tr>

            <tr>
                <td align="center">
                    <h2><font color="#800020">GitHub</font></h2>
                    <p>Explore my coding projects.</p>
                    <a href="https://github.com/" target="_blank">
                        Visit GitHub
                    </a>
                </td>

                <td align="center">
                    <h2><font color="#800020">College</font></h2>
                    <p>Saveetha Engineering College</p>
                    <p>Computer Science and Engineering</p>
                </td>
            </tr>

        </table>

        <h2><font color="#800020">Thank You for Visiting!</font></h2>
        <p>I look forward to connecting and learning together.</p>
    </center>

    <hr color="#800020">

    <center>
        <p><font color="#800020">© 2026 Jessie J | Contact Page</font></p>
    </center>

</body>
</html>

```

index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
</head>

<body bgcolor="#FFF8E7" text="#2B171B">

    <center>
        <font color="#800020">
            <h1>MY PORTFOLIO</h1>
        </font>

        <h3>Welcome to My Personal Website</h3>

       <img src="formal pic.jpg"
     alt="Jessie's Profile Photo"
     width="180"
     height="180"
     style="border-radius:50%; border:5px solid #800020;">
        <h2><font color="#800020">Hello, I'm Jessie J</font></h2>
        <h3>Computer Science Engineering Student</h3>
        <p>Welcome to my personal portfolio!</p>

        <hr color="#800020">

        <h2><font color="#800020">Explore My Portfolio</font></h2>

        <form>
            <button formaction="index.html">Home</button>
            <button formaction="about.html">About Me</button>
            <button formaction="skills.html">My Skills</button>
            <button formaction="projects.html">My Projects</button>
            <button formaction="contact.html">Contact</button>
        </form>

        <hr color="#800020">

        <h2><font color="#800020">A Little About Me</font></h2>
        <p>
            I am a Computer Science Engineering student who enjoys
            programming, learning new technologies, and creating projects.
        </p>

        <p>
            <font color="#800020">
                <b>Learn • Create • Grow</b>
            </font>
        </p>

        <hr color="#800020">

        <p><font color="#800020">© 2026 Jessie J | My Portfolio</font></p>
    </center>

</body>
</html>

```

projects.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Projects</title>
</head>

<body bgcolor="#FFF8E7" text="#2B171B">

    <center>
        <h1><font color="#800020">MY PROJECTS</font></h1>
        <p><i>Things I have created and explored</i></p>

        <hr color="#800020">

        <form>
            <button formaction="index.html">Home</button>
            <button formaction="about.html">About Me</button>
            <button formaction="skills.html">My Skills</button>
            <button formaction="projects.html">My Projects</button>
            <button formaction="contact.html">Contact</button>
        </form>

        <h2><font color="#800020">Explore My Work</font></h2>

        <table border="1" cellpadding="15" cellspacing="10" width="90%">

            <tr>
                <td align="center">
                    <h2><font color="#800020">Personal Portfolio</font></h2>
                    <p>A personal website created using HTML.</p>
                    <p>Displays my profile, skills, projects, and contact details.</p>

                    <form action="index.html">
                        <button type="submit">View Project</button>
                    </form>
                </td>

                <td align="center">
                    <h2><font color="#800020">Smart Disaster Response System</font></h2>
                    <p>A college project for emergency response coordination.</p>
                    <p>Helps manage incidents, rescue teams, resources, and missions.</p>

                    <form action="about.html">
                        <button type="submit">Project Overview</button>
                    </form>
                </td>
            </tr>

            <tr>
                <td align="center">
                    <h2><font color="#800020">HTML Practice</font></h2>
                    <p>Simple webpages created while learning HTML.</p>
                    <p>Includes headings, tables, images, and hyperlinks.</p>

                    <form action="skills.html">
                        <button type="submit">View Skills</button>
                    </form>
                </td>

                <td align="center">
                    <h2><font color="#800020">Learning Journey</font></h2>
                    <p>Exploring programming and web development.</p>
                    <p>Practicing concepts through small tasks.</p>

                    <form action="about.html">
                        <button type="submit">About Me</button>
                    </form>
                </td>
            </tr>

        </table>
    </center>

    <hr color="#800020">

    <center>
        <p><font color="#800020">© 2026 Jessie J</font></p>
    </center>

</body>
</html>

```

skills.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Skills</title>
</head>

<body bgcolor="#FFF8E7" text="#2B171B">

    <center>
        <h1><font color="#800020">MY SKILL SHOWCASE</font></h1>
        <p><i>What I know and what I am learning</i></p>

        <hr color="#800020">

        <form>
            <button formaction="index.html">Home</button>
            <button formaction="about.html">About Me</button>
            <button formaction="skills.html">My Skills</button>
            <button formaction="projects.html">My Projects</button>
            <button formaction="contact.html">Contact</button>
        </form>
    </center>

    <center>
        <h2><font color="#800020">Programming Skills</font></h2>

        <table border="1" cellpadding="12" cellspacing="0" width="85%">
            <tr bgcolor="#800020">
                <th><font color="#FFF8E7">Skill</font></th>
                <th><font color="#FFF8E7">Level</font></th>
                <th><font color="#FFF8E7">My Progress</font></th>
            </tr>

            <tr>
                <td>C Programming</td>
                <td>Beginner</td>
                <td>Learning programming fundamentals</td>
            </tr>

            <tr>
                <td>Python</td>
                <td>Beginner</td>
                <td>Practicing basic programs</td>
            </tr>

            <tr>
                <td>HTML</td>
                <td>Beginner</td>
                <td>Creating webpages</td>
            </tr>
        </table>

        <h2><font color="#800020">Other Skills</font></h2>

        <table border="1" cellpadding="12" cellspacing="0" width="85%">
            <tr bgcolor="#800020">
                <th><font color="#FFF8E7">Skill</font></th>
                <th><font color="#FFF8E7">How I Use It</font></th>
            </tr>

            <tr>
                <td>Problem Solving</td>
                <td>Breaking problems into simple steps</td>
            </tr>

            <tr>
                <td>MS Office</td>
                <td>Creating documents and presentations</td>
            </tr>

            <tr>
                <td>Communication</td>
                <td>Sharing ideas clearly</td>
            </tr>

            <tr>
                <td>Teamwork</td>
                <td>Working together on group tasks</td>
            </tr>
        </table>

        <h2><font color="#800020">Currently Exploring</font></h2>

        <table border="1" cellpadding="12" cellspacing="0" width="85%">
            <tr>
                <td>Web Development</td>
                <td>Building webpages and portfolio projects</td>
            </tr>

            <tr>
                <td>Java</td>
                <td>Improving programming knowledge</td>
            </tr>

            <tr>
                <td>Database Concepts</td>
                <td>Learning how data is stored and managed</td>
            </tr>
        </table>

        <h3><font color="#800020">
            My Goal: Keep learning, practicing, and growing!
        </font></h3>
    </center>

    <hr color="#800020">

    <center>
        <p><font color="#800020">© 2026 Jessie J</font></p>
    </center>

</body>
</html>

```




## OUTPUT

<img width="1883" height="922" alt="image" src="https://github.com/user-attachments/assets/24f5f5ff-6f54-45fe-b3bf-f3c938039e67" />
<img width="1852" height="867" alt="image" src="https://github.com/user-attachments/assets/4511a725-462b-4008-b354-347ff03d173c" />
<img width="1810" height="900" alt="image" src="https://github.com/user-attachments/assets/c01333fa-0d7c-4431-a97e-036e22096d91" />
<img width="1891" height="847" alt="image" src="https://github.com/user-attachments/assets/15e71e03-b3e3-4e8b-a1e1-463f9bb908e9" />
<img width="1878" height="893" alt="image" src="https://github.com/user-attachments/assets/d92bb9fa-e0e8-46dc-9ab8-a93b33e66127" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
