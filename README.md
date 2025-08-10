# repo
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title> Jacob Chacko — Portfolio</title>
  <style>
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;color:#111}
    body{display:flex;flex-direction:column;min-height:100vh;background:#f7f7fb}
    .nav{
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:1rem;
      padding:1rem 2rem;
      background:linear-gradient(90deg,#ffffffd9,#f0f4ff);
      border-bottom:1px solid rgba(15,23,42,0.04);
      box-shadow:0 2px 8px rgba(16,24,40,0.03);
    }
    .brand{font-weight:700;font-size:1.1rem;color:#0f172a}
    .nav-links{display:flex;gap:1rem;align-items:center}
    .nav-links a{padding:.5rem .75rem;border-radius:8px;text-decoration:none;color:#0f172a}
    .nav-links a:hover{background:#eef2ff}
    main{flex:1;display:flex;flex-direction:column;gap:2rem;padding:2rem}
    .hero{display:flex;gap:2rem;align-items:center;justify-content:space-between;flex-wrap:wrap}
    .hero-text{flex:1;min-width:260px}
    .hero h1{font-size:2rem;margin-bottom:.5rem}
    .hero p{color:#334155;line-height:1.5;margin-bottom:1rem}
    .cta{display:inline-flex;gap:.5rem;align-items:center;padding:.6rem 1rem;border-radius:10px;background:#4f46e5;color:white;text-decoration:none;font-weight:600}
    .hero-img{flex-basis:320px;flex-shrink:0;display:flex;justify-content:center;align-items:center}
    .hero-img img{width:100%;max-width:360px;border-radius:12px;box-shadow:0 10px 30px rgba(2,6,23,0.08)}
    .projects{display:flex;gap:1.5rem;flex-wrap:wrap}
    .card{background:white;border-radius:12px;padding:1rem;flex:1;min-width:260px;box-shadow:0 8px 20px rgba(2,6,23,0.04)}
    .card h3{margin-bottom:.5rem}
    .card p{color:#475569}
    footer{padding:1rem 2rem;background:#0f172a;color:#fff;display:flex;justify-content:space-between;align-items:center;gap:1rem}
    footer a{color:#a5b4fc;text-decoration:underline}
    @media (max-width:720px){
      .nav{padding:1rem}
      .hero{flex-direction:column-reverse;align-items:flex-start}
      .hero-img img{max-width:100%}
    }
  </style>
</head>
<body>
  <nav class="nav">
    <div class="brand">Your Name</div>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
      <!-- Example hyperlink requirement: link to your GitHub or another site -->
      <a href="https://github.com/" target="_blank" rel="noopener">GitHub</a>
    </div>
  </nav>

  <main>
    <section class="hero" id="home">
      <div class="hero-text">
        <h1>Hi — I'm Your Name</h1>
        <p>Student • Developer • Creator. This is a simple, responsive personal website template built to satisfy a class project that requires HTML + CSS (Flexbox), a navigation bar, at least one image, and at least one hyperlink. Customize the copy and projects below to match your work.</p>
        <a class="cta" href="#projects">See Projects →</a>
      </div>
      <div class="hero-img">
        <!-- Example image requirement. Replace src with your own image file when ready. -->
        <img src="https://picsum.photos/600/400?random=8" alt="Example hero image">
      </div>
    </section>
    <section id="about" class="card" style="margin-top:1rem;">
      <h2>About</h2>
      <p>Hello! I'm a student working on a personal website project. This about section is a place to describe yourself, your interests, and what you're learning. Because Flexbox is used throughout, content will reflow nicely on small screens.</p>
    </section>
    <section id="projects" style="margin-top:1rem;">
      <h2 style="margin-bottom:.75rem;">Projects</h2>
      <div class="projects">
        <article class="card">
          <h3>Robotics Lesson Slides</h3>
          <p>Lesson plans and slides about drivetrain design, chassis, and gears.</p>
          <p><a href="#" aria-label="Open project">Open project</a></p>
        </article>
        <article class="card">
          <h3>Noodle Fan Pitch</h3>
          <p>A playful product idea: a small fan designed to cool noodles while eating. Includes a short pitch and prototype concept.</p>
          <p><a href="#" aria-label="View pitch">View pitch</a></p>
        </article>
      </div>
    </section>
    <section id="contact" class="card" style="margin-top:1rem;">
      <h2>Contact</h2>
      <p>If you'd like to collaborate or see more work, visit my <a href="https://github.com/" target="_blank" rel="noopener">GitHub profile</a> or email me at <a href="mailto:youremail@example.com">youremail@example.com</a>.</p>
      <!-- Example of an inline image in content -->
      <p style="margin-top:1rem">Here's another image (class requirement satisfied):</p>
      <img src="https://picsum.photos/seed/portfolio/400/220" alt="project snapshot" style="border-radius:8px;max-width:100%;margin-top:.5rem;">
    </section>
  </main>

  <footer>
    <div>© <span id="year"></span> Your Name</div>
    <div>Hosted with ❤️ — <a href="https://pages.github.com/" target="_blank" rel="noopener">GitHub Pages</a></div>
  </footer>

  <script>
    // Small JS to keep the copyright year current
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
