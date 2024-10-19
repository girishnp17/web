# web

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Girish - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #ffffff;
            font-weight: bold; /* Make all body text bold */
        }
        header {
            background: #1e1e1e;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: #ffffff;
            text-decoration: none;
            font-weight: bold; /* Make navigation links bold */
        }
        section {
            padding: 20px;
            background-color: #1e1e1e;
            border-radius: 8px;
            margin: 20px;
            box-shadow: 0 2px 5px rgba(255, 255, 255, 0.1);
        }
        h1, h2, h3 {
            font-family: 'Montserrat', sans-serif;
            margin-bottom: 10px;
            font-weight: bold; /* Make headings bold */
        }
        h2 {
            text-align: center;
        }
        p {
            text-align: justify;
            line-height: 1.6;
            font-weight: bold; /* Make paragraph text bold */
        }
        .project {
            background: #2a2a2a;
            margin: 20px 0;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(255, 255, 255, 0.1);
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #1e1e1e;
            color: #ffffff;
            font-weight: bold; /* Make footer text bold */
        }
        a {
            color: #1e90ff;
            font-weight: bold; /* Make links bold */
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>GIRISH NP</h1>
    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#certifications">Certifications</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Me</h2>
    <img src="C:\Users\urk23cs5015\Downloads\girish.jfif" alt="Girish's Picture" style="width: 250px; height: auto; border-radius: 80%; margin-bottom: 45px;">
    <p>Welcome to my portfolio! I'm a data analyst with a passion for transforming data into actionable insights. With a background in statistics and experience in tools like Python, R, SQL, and Tableau, I specialize in data visualization, statistical analysis, and data-driven decision-making.</p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>Data Analysis & Visualization</li>
        <li>Statistical Analysis (R, Python)</li>
        <li>SQL & Database Management</li>
        <li>Machine Learning & NLP</li>
        <li>Data Cleaning & Preparation</li>
        <li>Collaboration & Teamwork</li>
        <li>Problem-Solving & Critical Thinking</li>
    </ul>
</section>

<section id="certifications">
    <h2>Certifications</h2>
    <ul>
        <li>Google Data Analytics Certificate</li>
        <li>IBM Data Science Professional Certificate</li>
        <li>Tableau Desktop Specialist</li>
    </ul>
</section>



<section id="projects">
    <h2>Projects</h2>
    
    <div class="project">
        <h3>Stock Analysis</h3>
        <p>This project involves analyzing historical stock data to identify trends and forecast future performance.</p>
        <a href="#" target="_blank">View Project</a>
    </div>
    
    <div class="project">
        <h3>Fake News Detection</h3>
        <p>This project focuses on building a machine learning model to classify news articles as real or fake.</p>
        <a href="#" target="_blank">View Project</a>
    </div>
    
    <div class="project">
        <h3>Customer Segmentation</h3>
        <p>In this project, I analyzed customer data to identify distinct segments for targeted marketing strategies.</p>
        <a href="#" target="_blank">View Project</a>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>If you would like to connect or learn more about my work, feel free to reach out via email at <a href="mailto:girish@example.com">girish@example.com</a>.</p>
</section>

<footer>
    <p>&copy; 2024 Girish. All rights reserved.</p>
</footer>

</body>
</html>
