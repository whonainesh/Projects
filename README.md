<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Portfolio</title>

  <!-- Google Font for Video Game Theme -->
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
    }

    header {
      background: #333;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
      background-color: white;
      margin-top: 1rem;
      border-radius: 8px;
    }

    h1 {
      font-size: 2rem;
      margin: 0.5rem 0;
    }

    h2 {
      font-family: 'Press Start 2P', cursive;
      font-size: 24px;
      color: #ff0055;
      margin-bottom: 1rem;
      text-shadow: 2px 2px #000;
    }

    .projects .project {
      margin-bottom: 1.5rem;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .contact-form button {
      background-color: #333;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #555;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: #fff;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I I am Nikhil!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!.</p>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project One</h3>
      <p>Description of your first project. What technologies you used and what problem it solved.</p>
    </div>
    <div class="project">
      <h3>Project Two</h3>
      <p>Description of your second project. Highlight key features and functionality.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
