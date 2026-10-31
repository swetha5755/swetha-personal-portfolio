# Ex01 Portfolio
## Date:27.10.2026

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
    <title>Swetha S | Personal Portfolio</title>
</head>

<body bgcolor="#FFF5FA">

    <!-- NAVIGATION BAR -->

    <table width="100%" bgcolor="#F1DDF5" cellpadding="18">
        <tr>
            <td width="35%">
                <font face="Georgia" color="#512B55" size="6">
                    <b><i>Swetha S ✦</i></b>
                </font>
            </td>

            <td align="right">
                <font face="Arial" size="3" color="#512B55">
                    <a href="#home">Home</a> &nbsp;&nbsp;
                    <a href="#about">About</a> &nbsp;&nbsp;
                    <a href="#education">Education</a> &nbsp;&nbsp;
                    <a href="#skills">Skills</a> &nbsp;&nbsp;
                    <a href="#projects">Projects</a> &nbsp;&nbsp;
                    <a href="#contact">Contact</a>
                </font>
            </td>
        </tr>
    </table>

    <br><br>

    <!-- HOME / HERO SECTION -->

    <table width="90%" align="center" cellpadding="20">
        <tr>

            <!-- LEFT SIDE: INTRODUCTION -->

            <td width="58%" valign="middle">

                <font face="Arial" color="#96558B" size="4">
                    <b>H E L L O , &nbsp; I ' M</b>
                </font>

                <br><br>

                <font face="Georgia" color="#291B35" size="7">
                    <b><i>Swetha S</i></b>
                </font>

                <br><br>

                <table bgcolor="#EBDCF5" cellpadding="12">
                    <tr>
                        <td>
                            <font face="Arial" color="#512B55" size="3">
                                &lt;/&gt; Computer Science Engineering Student
                            </font>
                        </td>
                    </tr>
                </table>

                <br>

                <font face="Arial" color="#392B40" size="4">
                    A curious and motivated Computer Science Engineering
                    student passionate about
                    <b><font color="#854477">Artificial Intelligence,
                    Machine Learning, Data Science</font></b>
                    and
                    <b><font color="#854477">Web Development.</font></b>
                </font>

                <br><br>

                <font face="Arial" color="#392B40" size="4">
                    I enjoy learning new technologies, solving real-world
                    problems and building creative, impactful solutions.
                </font>

                <br><br><br>

                <table cellpadding="12">
                    <tr>
                        <td bgcolor="#965C91">
                            <a href="#projects">
                                <font face="Arial" color="white" size="3">
                                    <b>View My Projects</b>
                                </font>
                            </a>
                        </td>

                        <td width="15"></td>

                        <td bgcolor="#EBDCF5">
                            <a href="#contact">
                                <font face="Arial" color="#512B55" size="3">
                                    <b>Contact Me</b>
                                </font>
                            </a>
                        </td>
                    </tr>
                </table>

                <br><br>

                <font face="Arial" color="#965C91" size="4">
                    <a href="YOUR_GITHUB_URL">GitHub</a>
                    &nbsp;&nbsp; | &nbsp;&nbsp;
                    <a href="YOUR_LINKEDIN_URL">LinkedIn</a>
                    &nbsp;&nbsp; | &nbsp;&nbsp;
                    <a href="mailto:YOUR_EMAIL@gmail.com">Email</a>
                </font>

            </td>

            <!-- RIGHT SIDE: PROFILE PHOTOGRAPH -->

            <td width="42%" align="center" valign="middle">

                <table bgcolor="#E8D5EF" cellpadding="15">
                    <tr>
                        <td align="center">
                            <img src="expt1/profile.jpeg"
                                 alt="Swetha S Profile Photograph"
                                 width="300">
                        </td>
                    </tr>
                </table>

            </td>

        </tr>
    </table>

    <br><br>

    <!-- ABOUT SECTION -->

    <table width="100%" bgcolor="#F0E2F5" cellpadding="30">
        <tr>
            <td align="center">

                <font face="Georgia" color="#70416F" size="6">
                    <b>About Me</b>
                </font>

                <br><br>

                <font face="Arial" color="#392B40" size="4">
                    I am pursuing a Bachelor of Engineering in Computer
                    Science and Engineering at Saveetha Engineering College,
                    Chennai.
                    <br><br>
                    I am passionate about technology, innovation and
                    continuous learning. My interests include Artificial
                    Intelligence, Machine Learning, Generative AI and
                    Web Development.
                </font>

                <br><br>

                <font face="Georgia" color="#854477" size="4">
                    <b>My Interests</b>
                </font>

                <br><br>

                <font face="Arial" color="#392B40" size="3">
                    Artificial Intelligence &nbsp; | &nbsp;
                    Machine Learning &nbsp; | &nbsp;
                    Generative AI &nbsp; | &nbsp;
                    Web Development &nbsp; | &nbsp;
                    Data Science
                </font>

            </td>
        </tr>
    </table>

    <br>

    <!-- EDUCATION SECTION -->

    <table width="90%" align="center" cellpadding="15">
        <tr>
            <td align="center">

                <font face="Georgia" color="#70416F" size="6">
                    <b>Education & Certifications</b>
                </font>

                <br><br>

                <table width="85%" align="center"
                       bgcolor="#F8EAF3" border="1"
                       bordercolor="#D7B8D9" cellpadding="15">

                    <tr bgcolor="#EBDCF5">
                        <th>
                            <font face="Arial" color="#512B55">
                                Qualification
                            </font>
                        </th>

                        <th>
                            <font face="Arial" color="#512B55">
                                Institution
                            </font>
                        </th>

                        <th>
                            <font face="Arial" color="#512B55">
                                Status
                            </font>
                        </th>
                    </tr>

                    <tr>
                        <td>BE Computer Science and Engineering</td>
                        <td>Saveetha Engineering College</td>
                        <td>Currently Pursuing</td>
                    </tr>

                </table>

                <br>

                <font face="Georgia" color="#854477" size="4">
                    <b>Certifications</b>
                </font>

                <ul>
                    <li>AWS Academy - AWS Fundamentals</li>
                    <li>Simplilearn - DBMS</li>
                    <li>Scaler Topics - Fundamentals of Machine Learning</li>
                </ul>

            </td>
        </tr>
    </table>

    <br>

    <!-- SKILLS SECTION -->

    <table width="100%" bgcolor="#F1DDF5" cellpadding="25">
        <tr>
            <td align="center">

                <font face="Georgia" color="#70416F" size="6">
                    <b>My Skills</b>
                </font>

                <br><br>

                <table width="90%" align="center" cellpadding="15">
                    <tr>

                        <td width="25%" bgcolor="#FFF5FA" align="center">
                            <font face="Georgia" color="#854477" size="4">
                                <b>Programming</b>
                            </font>
                            <p>C Programming</p>
                            <p>Python</p>
                            <p>Java</p>
                        </td>

                        <td width="25%" bgcolor="#FFF5FA" align="center">
                            <font face="Georgia" color="#854477" size="4">
                                <b>Web Development</b>
                            </font>
                            <p>HTML</p>
                            <p>CSS</p>
                            <p>JavaScript</p>
                            <p>React</p>
                        </td>

                        <td width="25%" bgcolor="#FFF5FA" align="center">
                            <font face="Georgia" color="#854477" size="4">
                                <b>AI & Data</b>
                            </font>
                            <p>Artificial Intelligence</p>
                            <p>Machine Learning</p>
                            <p>Generative AI</p>
                            <p>Data Science</p>
                        </td>

                        <td width="25%" bgcolor="#FFF5FA" align="center">
                            <font face="Georgia" color="#854477" size="4">
                                <b>Other Skills</b>
                            </font>
                            <p>UI/UX Design</p>
                            <p>Problem Solving</p>
                            <p>Creative Thinking</p>
                        </td>

                    </tr>
                </table>

            </td>
        </tr>
    </table>

    <br>

    <!-- PROJECTS SECTION -->

    <table width="90%" align="center" cellpadding="20">
        <tr>
            <td align="center">

                <font face="Georgia" color="#70416F" size="6">
                    <b>My Projects</b>
                </font>

            </td>
        </tr>

        <tr>
            <td bgcolor="#F8EAF3">

                <font face="Georgia" color="#854477" size="4">
                    <b>01. AI Study Assistant</b>
                </font>

                <p>
                    An AI-powered study assistant concept designed to
                    help students understand topics, organize learning
                    materials and improve productivity.
                </p>

                <b>Technologies:</b> Python, AI, Web Development

            </td>
        </tr>

        <tr>
            <td bgcolor="#F0E2F5">

                <font face="Georgia" color="#854477" size="4">
                    <b>02. AI-Powered Urban Air Quality Intelligence Platform</b>
                </font>

                <p>
                    A project concept focused on analyzing urban air
                    quality using environmental data and machine learning
                    to support environmental monitoring.
                </p>

                <b>Technologies:</b> Python, Machine Learning,
                GeoPandas, PostgreSQL and PostGIS

            </td>
        </tr>

        <tr>
            <td bgcolor="#F8EAF3">

                <font face="Georgia" color="#854477" size="4">
                    <b>03. Internship Management System</b>
                </font>

                <p>
                    A web application concept for managing internship
                    activities, student details, applications and progress.
                </p>

                <b>Technologies:</b> React, Node.js and MongoDB

            </td>
        </tr>
    </table>

    <br>

    <!-- CONTACT SECTION -->

    <table width="100%" bgcolor="#EBDCF5" cellpadding="30">
        <tr>
            <td align="center">

                <font face="Georgia" color="#70416F" size="6">
                    <b>Let's Connect!</b>
                </font>

                <br><br>

                <font face="Arial" color="#392B40" size="4">
                    I would love to connect, collaborate and explore
                    new opportunities.
                </font>

                <br><br>

                <font face="Arial" color="#512B55" size="4">
                    <b>Email:</b>
                    <a href="mailto:YOUR_EMAIL@gmail.com">
                        YOUR_EMAIL@gmail.com
                    </a>

                    <br><br>

                    <b>LinkedIn:</b>
                    <a href="YOUR_LINKEDIN_URL">
                        Visit My LinkedIn Profile
                    </a>

                    <br><br>

                    <b>GitHub:</b>
                    <a href="YOUR_GITHUB_URL">
                        Visit My GitHub Profile
                    </a>
                </font>

            </td>
        </tr>
    </table>

    <!-- FOOTER -->

    <table width="100%" bgcolor="#70416F" cellpadding="18">
        <tr>
            <td align="center">

                <font face="Arial" color="white" size="3">
                    &copy; 2026 Swetha S. All Rights Reserved.
                    <br><br>
                    Created with HTML and creativity.
                    <br><br>
                    <a href="#home">
                        <font color="white">Back to Top</font>
                    </a>
                </font>

            </td>
        </tr>
    </table>

</body>
</html>
```

## OUTPUT
<img width="1877" height="883" alt="image" src="https://github.com/user-attachments/assets/18dff879-228e-457b-9561-222d979f3348" />
<img width="1876" height="752" alt="image" src="https://github.com/user-attachments/assets/4cfe8877-6ed2-4735-87dd-1e6ae7c1e51d" />
<img width="1852" height="1001" alt="image" src="https://github.com/user-attachments/assets/fc14fa9a-d015-469a-b2ba-cb06bf3b9f05" />
<img width="1877" height="475" alt="image" src="https://github.com/user-attachments/assets/0c87680a-ace8-42c8-9b80-4abdfcbef253" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
