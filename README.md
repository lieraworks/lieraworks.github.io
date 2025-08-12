<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Name | Portfolio</title>
  <style>
    /* Reset some default styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f0f2f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #4a90e2;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.3rem;
    }

    header p {
      font-size: 1.2rem;
      font-weight: 300;
    }

    nav {
      margin-top: 0.8rem;
    }

    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #d1e6fc;
    }

    main {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      margin-bottom: 3rem;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-bottom: 3px solid #4a90e2;
      padding-bottom: 0.5rem;
      display: inline-block;
    }

    .about p {
      max-width: 700px;
      font-size: 1.1rem;
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }

    .project-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgb(0 0 0 / 0.1);
      padding: 1rem;
      display: flex;
      flex-direction: column;
    }

    .project-card img {
      width: 100%;
      border-radius: 6px;
      object-fit: cover;
      height: 160px;
      margin-bottom: 1rem;
    }

    .project-card h3 {
      margin-bottom: 0.5rem;
      color: #4a90e2;
    }

    .project-card p {
      flex-grow: 1;
      font-size: 1rem;
      margin-bottom: 1rem;
    }

    .project-card a {
      text-align: right;
      font-weight: 600;
      color: #4a90e2;
      text-decoration: none;
    }

    .project-card a:hover {
      text-decoration: underline;
    }

    .contact {
      background: #4a90e2;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
      border-radius: 8px;
      max-width: 400px;
      margin: 0 auto 3rem;
    }

    .contact a {
      color: white;
      font-weight: 700;
      text-decoration: none;
      border-bottom: 2px solid white;
    }

    .contact a:hover {
      color: #d1e6fc;
      border-color: #d1e6fc;
    }

    footer {
      text-align: center;
      padding: 1rem;
      color: #777;
      font-size: 0.9rem;
    }

    @media (max-width: 500px) {
      header h1 {
        font-size: 2rem;
      }
      section h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Web Developer | Designer | Creator</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>

    <section id="about" class="about">
      <h2>About Me</h2>
      <p>
        Hello! I'm a passionate web developer specialized in building responsive and accessible websites.
        I love creating clean and efficient code and bringing ideas to life on the web.
      </p>
    </section>

    <section id="projects" class="projects">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <img src="https://via.placeholder.com/300x160" alt="Project 1 Screenshot" />
          <h3>Project One</h3>
          <p>A brief description of the project, technologies used, and what it solves.</p>
          <a href="#">View Project</a>
        </div>

        <div class="project-card">
          <img src="https://via.placeholder.com/300x160" alt="Project 2 Screenshot" />
          <h3>Project Two</h3>
          <p>A brief description of the project, technologies used, and what it solves.</p>
          <a href="#">View Project</a>
        </div>

        <div class="project-card">
          <img src="https://via.placeholder.com/300x160" alt="Project 3 Screenshot" />
          <h3>Project Three</h3>
          <p>A brief description of the project, technologies used, and what it solves.</p>
          <a href="#">View Project</a>
        </div>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2>Contact Me</h2>
      <p>You can reach me at <a href="mailto:lieraworks@gmail.com">lieraworks@gmail.com</a></p>
      <p>Or follow me on 
        <a href="#" target="_blank" rel="noopener noreferrer">LinkedIn</a> | 
        <a href="#" target="_blank" rel="noopener noreferrer">GitHub</a>
      </p>
    </section>

  </main>

  <footer>
    &copy; 2025 Liera Jane C. All rights reserved.
  </footer>

</body>
</html>
