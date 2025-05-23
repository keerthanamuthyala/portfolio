<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Muthyala Keerthana | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      scroll-behavior: smooth;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #1f2937;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #f4f4f4;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }
    section {
      padding: 4rem 2rem;
      max-width: 900px;
      margin: auto;
      background: white;
      margin-top: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    }
    h1, h2 {
      color: #1f2937;
    }
    .skills ul, .projects ul, .certifications ul {
      list-style-type: square;
      padding-left: 1.5rem;
    }
    .hero {
      background: linear-gradient(to right, #667eea, #764ba2);
      color: white;
      padding: 5rem 2rem;
      text-align: center;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: auto;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #1f2937;
      color: white;
    }
    a {
      color: #1f2937;
    }
  </style>
</head>
<body>
  <header>
    <h1>Keerthana</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#certifications">Certifications</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Welcome to My Portfolio!</h2>
    <p>I'm <strong>Muthyala Keerthana</strong>, an aspiring software developer passionate about coding, learning, and building impactful solutions.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a recent B.Tech (CSE) graduate from Trinity College of Engineering and Technology (JNTUH). I'm skilled in Java, basic Python, SQL, and web development. I'm passionate about continuous learning and ready to contribute effectively as a software developer.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <ul>
        <li>Programming: Java, Python (Basics)</li>
        <li>Web: HTML, CSS</li>
        <li>Database: MySQL, Oracle, SQL</li>
        <li>Tools: MS Office, Windows OS</li>
        <li>Soft Skills: Communication, Problem-solving, Teamwork, Adaptability</li>
      </ul>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <ul>
        <li><strong>Hot Events Prediction using Bayesian Model:</strong> Predicting trending events in social networks using statistical models.</li>
        <li><strong>Employee Management System:</strong> A basic CRUD application to manage employee data.</li>
      </ul>
    </div>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <div class="certifications">
      <ul>
        <li>Full Stack Java Developer Course</li>
        <li>Common Internship Test - Participation</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p><strong>Email:</strong> <a href="mailto:keerthanam989@gmail.com">keerthanam989@gmail.com</a></p>
    <p><strong>Phone:</strong> <a href="tel:+919618981337">+91-9618981337</a></p>
    <p><strong>Location:</strong> Ameerpet, Hyderabad, Telangana</p>
  </section>

  <footer>
    <p>&copy; 2025 Muthyala Keerthana. All rights reserved.</p>
  </footer>
</body>
</html>
