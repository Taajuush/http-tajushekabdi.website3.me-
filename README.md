<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Taju Shekabdi Abdal — Portfolio</title>
  <meta name="description" content="Taju Shekabdi Abdal — Computer Science student at Jigjiga University. Web developer, designer and learner." />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="site-header">
    <nav class="nav">
      <a class="logo" href="#">Taju</a>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="https://github.com/tajushekabdiabdal" target="_blank" rel="noopener">GitHub</a></li>
      </ul>
      <button class="nav-toggle" aria-label="toggle navigation">☰</button>
    </nav>

    <div class="hero">
      <img class="profile" src="assets/profile.jpg" alt="Taju Shekabdi Abdal — profile photo" />
      <div class="hero-text">
        <h1>Hello — I'm <span class="accent">Taju Shekabdi Abdal</span></h1>
        <p class="lead">3rd-year Computer Science student at Jigjiga University • Web developer (HTML, CSS)</p>
        <div class="hero-cta">
          <a class="btn" href="#projects">View Projects</a>
          <a class="btn ghost" href="#contact">Contact Me</a>
        </div>
      </div>
    </div>
  </header>

  <main>
    <section id="about" class="section about">
      <div class="container">
        <h2>About Me</h2>
        <p>
          I am a Computer Science student at Jigjiga University (Oromia). I enjoy building clean, accessible websites using HTML, CSS, and basic JavaScript.
          I like to create personal websites and improve front-end skills through real projects.
        </p>
      </div>
    </section>

    <section id="skills" class="section skills">
      <div class="container">
        <h2>Skills</h2>
        <div class="skills-grid">
          <div class="skill-card">
            <h3>HTML</h3>
            <p>Semantic markup, accessibility basics</p>
          </div>
          <div class="skill-card">
            <h3>CSS</h3>
            <p>Responsive layout, Flexbox, Grid, animations</p>
          </div>
          <div class="skill-card">
            <h3>JavaScript</h3>
            <p>DOM, simple interactivity, form handling</p>
          </div>
          <div class="skill-card">
            <h3>Design</h3>
            <p>UI basics: typography, spacing, color</p>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="section projects">
      <div class="container">
        <h2>Portfolio</h2>
        <p class="muted">Example projects — replace these with your real projects and links.</p>

        <div class="project-grid">
          <article class="project-card">
            <div class="project-thumb">HTML/CSS</div>
            <h3>Personal Website (this site)</h3>
            <p>Responsive single-page website built with HTML &amp; CSS. Clean layout and smooth scroll.</p>
            <p class="meta">Tech: HTML • CSS</p>
            <a class="project-link" href="#" target="_blank">View demo</a>
          </article>

          <article class="project-card">
            <div class="project-thumb">Web</div>
            <h3>Landing Page</h3>
            <p>A modern landing page built for a mock product — responsive and mobile-first.</p>
            <p class="meta">Tech: HTML • CSS • JS</p>
            <a class="project-link" href="#" target="_blank">View demo</a>
          </article>

          <article class="project-card">
            <div class="project-thumb">Code</div>
            <h3>Simple JS App</h3>
            <p>Small JavaScript project demonstrating DOM manipulation and event handling.</p>
            <p class="meta">Tech: JavaScript</p>
            <a class="project-link" href="#" target="_blank">View demo</a>
          </article>
        </div>
      </div>
    </section>

    <section id="contact" class="section contact">
      <div class="container">
        <h2>Contact</h2>
        <p>Phone: +251953007845 • Email: <a href="mailto:abuuafham@gmail.com">abuuafham@gmail.com</a></p>

        <form id="contactForm" class="contact-form" action="#" onsubmit="handleContact(event)">
          <label>
            <span>Name</span>
            <input type="text" name="name" required placeholder="Your name" />
          </label>
          <label>
            <span>Email</span>
            <input type="email" name="email" required placeholder="you@example.com" />
          </label>
          <label>
            <span>Message</span>
            <textarea name="message" rows="5" required placeholder="Write your message..."></textarea>
          </label>
          <div class="form-actions">
            <button class="btn" type="submit">Send</button>
            <button class="btn ghost" type="reset">Reset</button>
          </div>
        </form>

      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> Taju Shekabdi Abdal — Jigjiga University • Oromia</p>
      <p class="muted">Made with ❤️ • Hosted on GitHub Pages</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

