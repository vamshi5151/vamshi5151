<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Dr M VAMSHI KRISHNA</h1>
        <p>Professor | profvamshi@email.com | 9703818580</p>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>To work in a challenging environment demanding all my skills and efforts to explore and adapt myself in different fields and realize my potential where I get the opportunity for continuous learning..</p>
    </section>
    <section id="education">
        <h2>Education</h2>
        <p>
•	Doctoral Research in Applied Electromagnetics under the guidance of Prof G. S. N. Raju, Centurion University and awarded in 2017.
•	Master's Degree in Radar & Microwave Engineering in the Dept of ECE Andhra University (2007-2009), under the guidance of Prof G. S. N. Raju.
•	Bachelor's Degree in Electronics & Communication Engineering in J.I.T.M Paralakhemundi, under BPUT Odisha (2003-2007).
</p>
    </section>
    <section id="experience">
        <h2>Experience</h2>
        <p>EXPERIENCE:
11/2007 – 07/2009	Raghu Engineering College 02/2009 -07/2011	WIPRO Technologies 08/2011 – 10/2014	Centurion University 10/2014 – 08/2017	GITAM University 08/2017 – 10/2020	Centurion University
10/2020- Present	Dhanekula Institute of Engineering and Technology
</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HFSS,MATLAB</li>
            <li>Git & GitHub</li>
        </ul>
    </section>
    <footer>
        <p>Find me on <a href="https://github.com/username">GitHub</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f4f4f4;
}
header {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px;
}
h1 {
    margin: 0;
}
h2 {
    color: #333;
}
section {
    margin: 20px 0;
    padding: 15px;
    background-color: white;
    border-radius: 5px;
}
footer {
    text-align: center;
    margin-top: 20px;
}
a {
    color: #0078d4;
    text-decoration: none;
}
a:hover {
    text-decoration: underline;
}

// Simple alert for interactivity
document.addEventListener("DOMContentLoaded", function() {
    console.log("Resume page loaded!");
    alert("Welcome to my resume website!");
});
