# First-Resume
This is my first resume developed by me and the name of this is "First-Resume".







HTML CODE OF THIS PORTFOLIO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - 1st Year B.Tech CSE Student</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>[MANVENDRA SINGH]</h1>
        <p>1st Year B.Tech Student | Computer Science Engineering</p>
    </header>

    <section class="contact-info">
        <h2>Contact Information</h2>
        <ul>
            <li>Phone: [7266008606]</li>
            <li>Email: [singhmanvendra2222@gmail.com]</li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/manvendra-singh-711520341/" target="_blank">[Manvendra Singh]</a></li>
            <li>GitHub: <a href="[GitHub Profile]" target="_blank">[ Singh_Manav001]</a></li>
        </ul>
    </section>

    <section class="objective">
        <h2>Objective</h2>
        <p>Motivated and enthusiastic 1st-year B.Tech student in Computer Science Engineering with a strong interest in programming, software development, and solving technical challenges. Seeking opportunities to contribute to software development and grow in a dynamic environment.</p>
    </section>

    <section class="education">
        <h2>Education</h2>
        <ul>
            <li><strong>B.Tech in Computer Science Engineering</strong> - [KIET GROUPE OF INSTITUTION], [GHAZIABAD, U.P.] <br> August 2024 –80 Present</li>
           
            <li>Relevant Coursework: Programming Fundamentals, Data Structures, Algorithms, Discrete Mathematics, Digital Logic, Electrical Circuits.</li>
        </ul>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li><strong>Programming Languages:</strong> C, Java (beginner level)</li>
            <li><strong>Web Development:</strong> HTML, CSS, JavaScript (basic knowledge)</li>
            <li><strong>Tools:</strong> Visual Studio Code, Eclipse, GitHub, Microsoft Office</li>
             
        </ul>
    </section>

    

    <section class="extracurricular">
        <h2>Extracurricular Activities</h2>
        <ul>
          
         
            <li>Active participant in language exchange groups to practice Japanese</li>
        </ul>
    </section>

    <section class="achievements">
        <h2>Achievements</h2>
        <ul>
            <li>Ranked in the top 20% in the first-semester exams</li>
             
            
        </ul>
    </section>

    <footer>
        <p>Developed by Manvendra Singh</p>
    </footer>

</body>
</html>

AND THE CSS CODE IS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

 
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
}

 
header {
    background-color: #2c3e50;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

 
section {
    margin: 20px;
    padding: 15px;
    background-color: #ffffff;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

 
section h2 {
    color: #34495e;
    font-size: 1.8em;
    margin-bottom: 10px;
}
 
a {
 
ul {
    list-style-type: none;
}

li {
    font-size: 1.2em;
    margin: 5px 0;
}


    color: #2980b9;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

 
footer {
    text-align: center;
    background-color: #2c3e50;
    color: white;
    padding: 10px;
    margin-top: 30px;
}

 
.contact-info ul {
    margin-left: 20px;
}

 
.projects ul {
    margin-left: 20px;
}

 
.skills ul {
    margin-left: 20px;
}

 
.extracurricular ul, .achievements ul {
    margin-left: 20px;
}
 
@media (max-width: 768px) {
    header h1 {
        font-size: 2em;
    }

    section {
        margin: 10px;
        padding: 10px;
    }

    section h2 {
        font-size: 1.5em;
    }

    li {
        font-size: 1em;
    }
}
