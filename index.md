---
title:
description: Personal website and selected work.
---

<section class="hero shell">
  <div class="hero-kicker"><span></span> Available for thoughtful work</div>
  <h1>Hello, I’m <em>Your Name.</em><br>I make useful things<br>for the web.</h1>
  <p class="hero-intro">A brief introduction goes here. Share what you do, what you’re interested in, and what kind of problems you like to solve.</p>
  <div class="hero-actions">
    <a class="button button-dark" href="{{ '/projects/' | relative_url }}">See my work <span>↗</span></a>
    <a class="text-link" href="{{ '/about/' | relative_url }}">More about me <span>→</span></a>
  </div>
</section>

<section class="section shell" aria-labelledby="featured-heading">
  <div class="section-heading">
    <div><p class="eyebrow">Selected work</p><h2 id="featured-heading">A few things I’ve made</h2></div>
    <a class="text-link desktop-link" href="{{ '/projects/' | relative_url }}">View all projects <span>→</span></a>
  </div>
  <div class="project-grid">
    <article class="project-card project-card--sage">
      <div class="project-visual"><span>01</span><div class="shape shape-one"></div></div>
      <div class="project-copy"><p class="project-type">Project type · Year</p><h3>Project name</h3><p>A concise description of the project, the problem it solves, and your contribution.</p><a href="#" aria-label="View Project name">View project <span>↗</span></a></div>
    </article>
    <article class="project-card project-card--blue">
      <div class="project-visual"><span>02</span><div class="shape shape-two"></div></div>
      <div class="project-copy"><p class="project-type">Project type · Year</p><h3>Another project</h3><p>Use this space to highlight an outcome, an interesting constraint, or something you learned.</p><a href="#" aria-label="View Another project">View project <span>↗</span></a></div>
    </article>
  </div>
</section>

<section class="section notes-preview shell" aria-labelledby="notes-heading">
  <div class="section-heading"><div><p class="eyebrow">From the notebook</p><h2 id="notes-heading">Recent notes</h2></div></div>
  <div class="empty-state"><p>Thoughts, field notes, and things worth remembering will appear here.</p><a class="text-link" href="{{ '/notes/' | relative_url }}">Browse the notebook <span>→</span></a></div>
</section>

<section class="contact-band">
  <div class="shell contact-inner"><p class="eyebrow">Start a conversation</p><h2>Have an interesting idea?<br><em>Let’s talk.</em></h2><a class="button button-light" href="mailto:{{ site.author.email }}">Get in touch <span>↗</span></a></div>
</section>
