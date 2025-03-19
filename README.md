# Personal-Protfolio-Website
<!DOCTYPE html>
<html lang="en">

<head>

    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f3f3f3;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
        }

        nav {
            text-align: center;
            margin: 1rem 0;
        }

        nav a {
            margin: 0 1rem;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            background: white;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .about {
            text-align: center;
        }

        .about img {
            border-radius: 150%;
            width: 150px;
            height: 150px;
        }

        .section-title {
            font-size: 1.5rem;
            margin: 1rem 0;
            color: #333;
        }

        .project {
            margin-bottom: 1.5rem;
        }

        footer {
            text-align: center;
            margin-top: 2rem;
            padding: 1rem;
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Crafting Engaging Digital Experiences</p>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="about">
            <h2 class="section-title">About Me</h2>
            <img src="1723378397654.jpg" alt="">
            <p>Hello! I'm a passionate web developer with expertise in HTML, CSS, JavaScript, and React.js. I love
                creating responsive and user-friendly websites. I have a background in [education details] and
                professional experience in [industry details].</p>
        </section>
        <section id="skills">
            <h2 class="section-title">My Skills</h2>
            <div class="skils">
                <h3> Soft Skill</h3>
                <ol>
                    <li>Communication Skills</li>
                    <li>Problem-Solving</li>
                </ol>
                </h3>
                <h3>Technical Skills</h3>
                <ol>
                    <li>HTML, CSS, and JavaScript</li>
                </ol>
            </div>
        </section>
        <section id="projects">
            <h2 class="section-title">My Projects</h2>
            <div class="project">
                <h3>Project 1: Portfolio Website</h3>
                <p>Description: A personal portfolio website showcasing my projects and skills.</p>
                <p>Technologies: HTML, CSS, JavaScript</p>
                <a href="#">Live Demo</a> | <a href="#">GitHub Repository</a>
            </div>
            <div class="project">
                <h3>Project 2: E-commerce Website</h3>
                <p>Description: A fully functional e-commerce platform with a payment gateway.</p>
                <p>Technologies: React.js,Node.js,MongoDB</p>
                <a href="#">Live Demo</a> | <a href="#">GitHub Repository</a>
            </div>
        </section>
        <section id="education">
            <h2>Education</h2>
            <div class="education-item">
                <h3>Bachelor of Science in Electrical and Communication Engineering </h3>
                <p><strong>Muthayammal Engineering College,Tamilnadu</strong></p>
                <p>August 2022 – May 2026</p>
                <ul>
                    <li>Graduated with Honors</li>
                    <li>Capstone Project: “Personal Portfolio Website”</li>
                </ul>
            </div>
            <div class="education-item">
                <h3>Higher Secondary Education</h3>
                <p><strong>Narayan Junior College,kurnool,Andhrapradesh </strong></p>
                <p>June 2020 – May 2021</p>
                <ul>
                    <li>Scored 97% in Board Examinations</li>

                </ul>
            </div>
        </section>
    </div>
    <footer>
        <p>Connect with me on <a href="https://linkedin.com/in/your-profile" style="color: white;">LinkedIn</a></p>
    </footer>
</body>

</html>
