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
    <div class="brand">Jacob Chacko</div>
    <div class="nav-links">
      <a href="#hobbies">Hobbies</a>
      <a href="#projects">Clubs</a>
      <a href="#contact">Contact</a>
      <a href="https://github.com/" target="_blank" rel="noopener">GitHub</a>
    </div>
  </nav>

  <main>
    <section class="hero" id="home">
      <div class="hero-text">
        <h1>Hi — I'm Jacob </h1>
        <p>I am currently attending Yonkers High School and am enrolled in the IB program. The IB (International Baccalaureate) is a rigorous, internationally recognized educational program for students aged 16–19 (for the Diploma Programme). It covers six subject groups — languages, sciences, math, humanities, and arts — along with core components like the Extended Essay (EE), Theory of Knowledge (TOK), and Creativity, Activity, Service (CAS). It’s designed to encourage critical thinking, global awareness, and independent learning, and is often seen as strong preparation for university.</p>
        <a class="cta" href="#projects">See Projects →</a>
      </div>
      <div class="hero-img">
        <img src="https://picsum.photos/600/400?random=8" alt="Example hero image">
      </div>
    </section>
    <section id="about" class="card" style="margin-top:1rem;">
      <h2>Hobbies</h2>
      <p>Some of my hobbies include traveling, driving, and swimming. I plan to one day travel to all 50 states of America, currently I have traveled to only 25 states. I love driving and have been practicing to obtain my licence. Finally swimming is my favorite sport.</p>
    </section>
    <section id="projects" style="margin-top:1rem;">
      <h2 style="margin-bottom:.75rem;">Clubs</h2>
      <div class="projects">
        <article class="card">
          <h3>Robotics (Design Director)</h3>
          <p>The Robotics club comepetes in the FRC competion for the chance to go to nationals. I am charge of "cading (3D modelling)" the robot. </p>
          <p><a href="#" aria-label="Open project">Open project</a></p>
        </article>
        <article class="card">
          <h3>Indian Gala</h3>
          <p>an annual performace that takes place every year at my school</p>
          <p><a href="#" aria-label="View pitch">View pitch</a></p>
        </article>
      </div>
    </section>
    <section id="contact" class="card" style="margin-top:1rem;">
      <h2>Contact</h2>
      <p>If you'd like to know more about the IB program, visit <a href="[(https://www.ibo.org/about-the-ib/what-it-means-to-be-an-ib-student/recognizing-student-achievement/about-assessment/dp-passing-criteria/)]" target="_blank" rel="noopener">GitHub profile</a> or email me at <a href="Thisis@fakeemail.com">Thisis@fakeemail.com</a>.</p>
      <p style="margin-top:1rem">Here's another image (class requirement satisfied):</p>
      <img src="https://picsum.photos/seed/portfolio/400/220" alt="project snapshot" style="border-radius:8px;max-width:100%;margin-top:.5rem;">
    </section>
  </main>

  <footer>
    <div>© <span id="year"></span> Jacob </div>
    <div>Link to Github — <a href="https://pages.github.com/" target="_blank" rel="noopener">GitHub Pages</a></div>
  </footer>
</body>
</html>
