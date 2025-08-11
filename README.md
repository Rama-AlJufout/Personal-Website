<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rama's Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #ffe6f0;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #f0768b;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-top: 1rem;
      border: 3px solid white;
    }

    nav {
      background-color: #f0768b;
      text-align: center;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    nav ul li {
      display: inline-block;
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 2rem;
      background-color: white;
      margin: 1rem;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #f0768b;
      color: white;
    }

    /* Projects tabs styled as links */
    .tabs {
      display: flex;
      gap: 15px;
      justify-content: center;
      flex-wrap: wrap;
      margin-bottom: 1rem;
    }

    .tab {
      background-color: #f0768b;
      color: white;
      padding: 10px 20px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: 600;
      transition: background-color 0.3s ease;
      user-select: none;
      cursor: pointer;
    }

    .tab:hover {
      background-color: #d95f6c;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, I'm Rama 👋</h1>
    <p>Aspiring AI Engineer | Web Enthusiast</p>
    <img src="Rama.jpg" alt="Rama's Photo">
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a passionate and driven engineer, proudly holding a degree in Intelligent Systems Engineering from Tafila Technical University. 
      With a strong foundation in problem-solving, creativity, and cutting-edge technologies, I am committed to building innovative solutions that make a real impact. 
      My journey in technology is fueled by curiosity, continuous learning, and the ambition to excel as an AI engineer who delivers excellence in every project.
    </p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="tabs">
      <a href="Responsive Blog Theme.html" target="_blank" class="tab">Spain Trip Blog</a>
      <a href="Small Business Website.html" target="_blank" class="tab">Spanish Food Menu</a>
      <a href="Traffic Light Exercise.html" target="_blank" class="tab">Traffic Light JS</a>
    </div>
    <p style="text-align:center; color:#7a2a3d;">Click on a project above to open it in a new tab.</p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>📧 Email: <a href="mailto:aljufoutrama@gmail.com">aljufoutrama@gmail.com</a></p>
    <p>📱 Phone: <a href="tel:+962798033160">+962 7 9803 3160</a></p>
    <p>💼 LinkedIn: <a href="http://linkedin.com/in/rama-al-jufout-a93a74322" target="_blank">View my LinkedIn</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Rama Ahmad</p>
  </footer>
</body>
</html>
