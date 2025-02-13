<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Katlego Bhotile | Engineering Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>Katlego Bhotile</h1>
        <p>Candidate Civil Technologist | Road Construction Specialist</p>
        <button id="theme-toggle">Toggle Dark/Light Mode</button>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="about">
        <h2>About Me</h2>
        <p>ECSA-accredited Candidate Civil Technologist with a Postgraduate Diploma in Project Management and extensive experience in road construction projects.</p>
    </section>
    
    <section id="experience">
        <h2>Experience</h2>
        <ul>
            <li><strong>Assistant Resident Engineer</strong> - Ikusaselihle Consultants (2024 - Present)</li>
            <li><strong>Route Manager</strong> - Q and A Engineers (2024)</li>
            <li><strong>Assistant Route Manager</strong> - Q and A Engineers (2022 - 2024)</li>
        </ul>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Resurfacing of National Route N12</h3>
            <p>Major road rehabilitation project for SANRAL.</p>
        </div>
        <div class="project">
            <h3>Routine Route Maintenance</h3>
            <p>Overseeing road maintenance compliance on SANRAL routes.</p>
        </div>
    </section>
    
    <section id="skills">
        <h2>Skills & Certifications</h2>
        <ul>
            <li>Road Construction Supervision</li>
            <li>Quality Control Management</li>
            <li>Project Management</li>
            <li>AutoCAD & Civil 3D</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:kbhotile@gmail.com">kbhotile@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/katlego-bhotile-1b360914b">View Profile</a></p>
        <p><a href="resume.pdf" download>Download CV</a></p>
    </section>
    
    <footer>
        <p>&copy; 2025 Katlego Bhotile. All Rights Reserved.</p>
    </footer>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
        }
        nav ul {
            list-style: none;
            padding: 0;
            background: #444;
        }
        nav ul li {
            display: inline;
            margin: 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background: #222;
            color: white;
            padding: 10px;
        }
    </style>
    
    <script>
        document.getElementById('theme-toggle').addEventListener('click', function() {
            document.body.classList.toggle('dark-mode');
        });
    </script>
</body>
</html>
