# Portfolio-using-html-and-css
#HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Priyanka Kumari Pandey</h1>
        <p>B.Tech student in Electronics and Communication Engineering, graduating in 2025. Solid foundation in circuit design, signal processing, and telecommunications. Eager to apply my skills and knowledge in a dynamic work environment. Strong analytical abilities and a keen interest in cutting-edge technologies. Ready to contribute effectively to team projects and tackle challenging tasks.</p>
    </header>

    <section id="about">
        <img src="your-image.jpg" alt="Priyanka Kumari Pandey">
        <h2>About Me</h2>
        <p>B.Tech student in Electronics and Communication Engineering, set to graduate in 2025. I have developed a solid foundation in circuit design, signal processing, and telecommunications through rigorous coursework and hands-on projects. My technical skills include proficiency in Python, C, Java, AWS Cloud, full stack development, iOS development, and data engineering. I also have experience with microcontrollers, PCB design, and digital communication systems. Familiar with tools like MATLAB and Simulink, my strong analytical abilities and keen interest in cutting-edge technologies drive me to continuously learn and innovate. I am eager to contribute to team projects and excel in a dynamic work environment..</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>DATA ENGINEERING</li>
            <li>PYTHON</li>
            <li>JAVA</li>
            <li>AWS</li>
            <li>Full Stack Development</li>
            <!-- Add more skills as needed -->
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Arduino Flow Sensor</h3>
            <img src="project1-image.jpg" alt="Project 1">
            <p>Project description goes here.</p>
        </div>
        <div class="project">
            <h3>E- learning Webpage</h3>
            <img src="project2-image.jpg" alt="Project 2">
            <p>e learning educational webpage design using html and CSS.
Beyond Curriculum Training of FULL STACK WEB DEVELOPMENT</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:priyanka.p19122003@gmail.com">priyanka.p19122003@gmail.com</a></p>
        <p>Phone: 8240356365</p>
    </section>

    <footer>
        <p>&copy; 2024 Priyanka Kumari Pandey. All rights reserved.</p>
        <!-- Additional links or information can go here -->
    </footer>
</body>
</html>

#CSS
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5rem;
}

header p {
    font-size: 1.2rem;
}

section {
    padding: 2rem 1rem;
    max-width: 800px;
    margin: 0 auto;
    background: #fff;
    margin-bottom: 1rem;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section h2 {
    border-bottom: 2px solid #333;
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
}

#about img {
    max-width: 150px;
    border-radius: 50%;
    display: block;
    margin: 0 auto 1rem;
}

#skills ul {
    list-style-type: none;
    padding: 0;
}

#skills li {
    background: #333;
    color: #fff;
    display: inline-block;
    margin: 0.5rem;
    padding: 0.5rem 1rem;
    border-radius: 5px;
}

.project {
    margin-bottom: 1.5rem;
}

.project img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 1rem;
}

footer p {
    margin: 0;
}
