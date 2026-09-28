<template>
  <main class="portfolio-shell">
    <div class="sky-glow sky-glow-one"></div>
    <div class="sky-glow sky-glow-two"></div>

    <section class="bento-grid">
      <article class="card hero-card span-3">
        <div class="hero-topbar">
          <div class="avatar">k</div>
          <div class="status-pill">● Online</div>
        </div>

        <div class="hero-copy">
          <p class="eyebrow">Developer in training</p>
          <h1>Planet <span>.</span> Kosi</h1>
          <p class="role">Frontend developer with a taste for polished interfaces and cosmic systems.</p>
        </div>

        <div class="hero-meta">
          <span>Based in Lagos</span>
          <span>Available for projects</span>
        </div>
      </article>

      <article class="card about-card span-3">
        <div class="card-label">About me</div>
        <p>
          I build calm, useful interfaces for people who want software that feels intentional.
          I enjoy turning technical complexity into clear experiences and shipping products that look sharp while staying easy to use.
        </p>
      </article>

      <article class="card online-card span-1">
        <div class="card-label">Online accounts</div>
        <ul class="link-list">
          <li><a href="https://instagram.com/planetkosii">Instagram</a></li>
          <li><a href="https://twitter.com/planetkosi">X / Twitter</a></li>
          <li><a href="#">LinkedIn</a></li>
        </ul>
      </article>

      <article class="card lastfm-card span-1">
        <div class="card-label">Last.fm</div>
        <div class="stat-row">
          <strong>2,431</strong>
          <span>scrobbles this month</span>
        </div>
        <div class="mini-stack">
          <span>Lo-fi</span>
          <span>Alt R&amp;B</span>
          <span>Indie</span>
        </div>
      </article>

      <article class="card backloggd-card span-1">
        <div class="card-label">Backloggd</div>
        <div class="stat-row">
          <strong>84</strong>
          <span>games in progress</span>
        </div>
        <div class="mini-stack">
          <span>RPG</span>
          <span>Action</span>
          <span>Adventure</span>
        </div>
      </article>

      <article class="card github-card span-2">
        <div class="card-head">
          <div class="card-label">GitHub repo</div>
          <a href="#">View profile</a>
        </div>
        <div class="repo-box">
          <div>
            <span class="repo-name">planetkosi.github.io</span>
            <p>Portfolio and experiments in one place.</p>
          </div>
          <span class="badge">Public</span>
        </div>
      </article>

      <article class="card current-project-card span-1">
        <div class="card-label">Current project</div>
        <h3>Orbit Notes</h3>
        <p>A lightweight notes app for capturing ideas and turning them into focused action.</p>
      </article>

      <article class="card stack-card span-1">
        <div class="card-label">Coding stack</div>
        <div class="chip-grid">
          <span>Vue</span>
          <span>JavaScript</span>
          <span>CSS</span>
          <span>HTML</span>
          <span>Node</span>
          <span>Figma</span>
        </div>
      </article>

      <article class="card learning-card span-1">
        <div class="card-label">Currently learning</div>
        <ul class="list-plain">
          <li>TypeScript</li>
          <li>System design</li>
          <li>Motion design</li>
        </ul>
      </article>

      <article class="card skills-card span-1">
        <div class="card-label">Skills</div>
        <ul class="list-plain">
          <li>UI systems</li>
          <li>Web design</li>
          <li>Prototyping</li>
          <li>Frontend dev</li>
        </ul>
      </article>

      <article class="card featured-card span-3">
        <div class="card-head">
          <div class="card-label">Featured projects</div>
          <a href="#">See archive</a>
        </div>

        <div class="project-list">
          <div class="project-row">
            <div>
              <span class="project-tag">Product</span>
              <h3>Northstar CRM</h3>
            </div>
            <span>2025</span>
          </div>
          <div class="project-row">
            <div>
              <span class="project-tag">Brand</span>
              <h3>Monarch Studio</h3>
            </div>
            <span>2024</span>
          </div>
          <div class="project-row">
            <div>
              <span class="project-tag">Experience</span>
              <h3>Harbor Wallet</h3>
            </div>
            <span>2023</span>
          </div>
        </div>
      </article>
    </section>
  </main>
</template>