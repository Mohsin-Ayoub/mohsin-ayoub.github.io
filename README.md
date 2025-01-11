<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohsin Ayoub's Resume</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 30px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .contact-info, .social-links {
            list-style: none;
            padding: 0;
            text-align: center;
        }
        .contact-info li, .social-links li {
            margin: 10px 0;
        }
        .contact-info li a, .social-links li a {
            color: #333;
            text-decoration: none;
            font-size: 1.2em;
        }
        .contact-info li a:hover, .social-links li a:hover {
            color: #00aaff;
        }
        .section {
            margin: 40px 0;
        }
        .section h2 {
            background-color: #333;
            color: #fff;
            padding: 10px;
            font-size: 1.5em;
        }
        .experience, .education, .skills, .achievements {
            margin: 20px 0;
        }
        .experience-item, .education-item, .skill-item, .achievement-item {
            margin-bottom: 20px;
        }
        .time-period, .degree, .skill-icon, .achievement-icon {
            display: inline-block;
            margin-right: 10px;
        }
        .button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #00aaff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mohsin Ayoub</h1>
        <ul class="contact-info">
            <li><a href="mailto:mohsinabbasi009@gmail.com"><i class="fas fa-envelope"></i> mohsinabbasi009@gmail.com</a></li>
            <li><a href="tel:+4915211448247"><i class="fas fa-phone-alt"></i> (+49) 15211448247</a></li>
            <li><a href="https://linkedin.com/in/mohsin-ayoub" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a></li>
            <li><a href="https://github.com/Mohsin-Ayoub/mohsin-ayoub.github.io" target="_blank"><i class="fab fa-github"></i> GitHub</a></li>
            <li><a href="https://wa.me/923421544632" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a></li>
        </ul>
    </header>

    <div class="container">
        <section class="about section">
            <h2>About Me</h2>
            <p>Enthusiastic and detail-oriented software developer with extensive experience in backend and full-stack development using technologies like .NET Core, C#, SQL Server, and JavaScript frameworks. Skilled in building scalable and reliable software solutions, leading teams, and ensuring project success through agile methodologies. Passionate about contributing to innovative development projects in areas like AI, cloud computing, or enterprise software, and excelling in roles that combine technical expertise with team leadership.</p>
        </section>

        <section class="work-experience section">
            <h2>Work Experience</h2>
            <div class="experience">
                <div class="experience-item">
                    <div class="time-period"><i class="fas fa-calendar-alt"></i> <strong>01/04/2023 – 31/10/2024</strong></div>
                    <h3>Asp.Net Core Developer, Panda Tech</h3>
                    <p>Developed backend solutions using .NET Core, C#, and SQL Server, and frontend with ASP.NET MVC, Knockout.js, HTML, CSS, JavaScript, and jQuery. Managed version control with GitLab and Source Tree. Led a team of 3 developers, overseeing task assignments, code reviews, and project decisions. Ensured project timelines and milestones were met through effective sprint management.</p>
                </div>
                <div class="experience-item">
                    <div class="time-period"><i class="fas fa-calendar-alt"></i> <strong>01/08/2021 – 31/03/2023</strong></div>
                    <h3>Asp.Net MVC Developer, ISLO Technologies (Pvt.) Ltd</h3>
                    <p>Developed overall application from scratch. Added new features to the application. Solved complex problems and fixed bugs to ensure application reliability.</p>
                </div>
            </div>
        </section>

        <section class="education section">
            <h2>Education</h2>
            <div class="education-item">
                <div class="degree"><i class="fas fa-graduation-cap"></i></div>
                <h3>M.Sc High Integrity Systems, Frankfurt University of Applied Sciences</h3>
                <p><strong>01/10/2024 – Current</strong>, Frankfurt am Main, Germany</p>
            </div>
            <div class="education-item">
                <div class="degree"><i class="fas fa-graduation-cap"></i></div>
                <h3>B.S (Computer Science), Federal Urdu University</h3>
                <p><strong>10/09/2019 – 11/08/2023</strong>, Islamabad, Pakistan, CGPA: 3.71/4.0 (Equivalent to 1.5 in the German grading system)</p>
            </div>
        </section>

        <section class="skills section">
            <h2>Skills</h2>
            <div class="skill-item">
                <div class="skill-icon"><i class="fab fa-java"></i></div>
                <span>Java</span>
            </div>
            <div class="skill-item">
                <div class="skill-icon"><i class="fab fa-cuttlefish"></i></div>
                <span>C#</span>
            </div>
            <div class="skill-item">
                <div class="skill-icon"><i class="fas fa-database"></i></div>
                <span>SQL Server</span>
            </div>
            <div class="skill-item">
                <div class="skill-icon"><i class="fab fa-html5"></i></div>
                <span>HTML</span>
            </div>
            <div class="skill-item">
                <div class="skill-icon"><i class="fab fa-css3-alt"></i></div>
                <span>CSS</span>
            </div>
            <div class="skill-item">
                <div class="skill-icon"><i class="fab fa-js"></i></div>
                <span>JavaScript</span>
            </div>
            <div class="skill-item">
                <div class="skill-icon"><i class="fas fa-code"></i></div>
                <span>Git, GitLab</span>
            </div>
        </section>

        <section class="achievements section">
            <h2>Achievements</h2>
            <div class="achievement-item">
                <div class="achievement-icon"><i class="fas fa-trophy"></i></div>
                <span>Machine Learning – GPA: 1.0</span>
            </div>
            <div class="achievement-item">
                <div class="achievement-icon"><i class="fas fa-trophy"></i></div>
                <span>Artificial Intelligence – GPA: 1.6</span>
            </div>
            <div class="achievement-item">
                <div class="achievement-icon"><i class="fas fa-trophy"></i></div>
                <span>Data Science – GPA: 1.0</span>
            </div>
        </section>
    </div>
</body>
</html>
