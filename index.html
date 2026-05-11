<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Projects</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=VT323&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg:        #0d0d0d;
      --surface:   #141414;
      --border:    #2a2a2a;
      --accent:    #39ff14;
      --accent2:   #00c853;
      --text:      #f0ece4;
      --muted:     #888;
      --radius:    4px;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'VT323', monospace;
      font-weight: 400;
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* ── Noise texture overlay ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 0;
    }

    /* ── Header ── */
    header {
      position: relative;
      padding: 90px 8vw 60px;
      border-bottom: 1px solid var(--border);
      overflow: hidden;
    }

    header::after {
      content: 'PROJECTS';
      position: absolute;
      right: 6vw;
      top: 50%;
      transform: translateY(-50%);
      font-family: 'Playfair Display', serif;
      font-size: clamp(60px, 12vw, 160px);
      font-weight: 900;
      color: transparent;
      -webkit-text-stroke: 1px #2a2a2a;
      letter-spacing: -4px;
      user-select: none;
      pointer-events: none;
      white-space: nowrap;
    }

    .header-label {
      font-size: 11px;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 16px;
      font-weight: 500;
    }

    header h1 {
      font-family: 'Press Start 2P', monospace;
      font-size: clamp(22px, 3.5vw, 48px);
      font-weight: 700;
      line-height: 1.05;
      letter-spacing: -1px;
      max-width: 600px;
      position: relative;
      z-index: 1;
    }

    header h1 span {
      color: var(--accent);
      font-style: normal;
      text-shadow: 0 0 8px #39ff14, 0 0 20px #39ff1480;
    }

    .header-label {
      color: var(--accent);
      text-shadow: 0 0 6px #39ff1499;
    }

    .header-sub {
      margin-top: 20px;
      color: var(--muted);
      font-size: 15px;
      max-width: 400px;
      line-height: 1.6;
      position: relative;
      z-index: 1;
    }

    /* ── Main layout ── */
    main {
      padding: 80px 8vw;
      position: relative;
      z-index: 1;
    }

    /* ── Project card ── */
    .project {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0;
      border: 1px solid var(--border);
      margin-bottom: 60px;
      opacity: 0;
      transform: translateY(30px);
      animation: fadeUp 0.6s ease forwards;
    }

    .project:nth-child(1) { animation-delay: 0.1s; }
    .project:nth-child(2) { animation-delay: 0.25s; }
    .project:nth-child(3) { animation-delay: 0.4s; }

    @keyframes fadeUp {
      to { opacity: 1; transform: translateY(0); }
    }

    /* Flip layout for even cards */
    .project:nth-child(even) {
      direction: rtl;
    }
    .project:nth-child(even) > * {
      direction: ltr;
    }

    /* ── Media panel ── */
    .project-media {
      position: relative;
      background: var(--surface);
      border-right: 1px solid var(--border);
      /*min-height: 380px;*/
      margin: auto;
      overflow: hidden;
    }

    .project:nth-child(even) .project-media {
      border-right: none;
      border-left: 1px solid var(--border);
    }

    /* Placeholder shown when no media is added */
    .media-placeholder {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100%;
      min-height: 380px;
      gap: 12px;
      color: var(--border);
      font-size: 13px;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .media-placeholder svg {
      width: 48px;
      height: 48px;
      stroke: var(--border);
    }

    .project-media img,
    .project-media video,
    .project-media iframe {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .project-media video,
    .project-media iframe {
      min-height: 200px;
    }

    /* Hover shine effect on media */
    .project-media::after {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(135deg, rgba(255,255,255,0.04) 0%, transparent 60%);
      pointer-events: none;
      transition: opacity 0.3s;
    }

    .project:hover .project-media::after {
      opacity: 0;
    }

    /* ── Info panel ── */
    .project-info {
      padding: 48px 44px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      background: var(--surface);
    }

    .project-number {
      font-size: 11px;
      letter-spacing: 3px;
      color: var(--accent);
      text-transform: uppercase;
      font-weight: 500;
      margin-bottom: 20px;
      text-shadow: 0 0 6px #39ff1499;
    }

    .project-title {
      font-family: 'Press Start 2P', monospace;
      font-size: clamp(12px, 1.4vw, 18px);
      font-weight: 700;
      line-height: 1.15;
      letter-spacing: -0.5px;
      margin-bottom: 20px;


    }

    .project-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-bottom: 24px;
    }

    .tag {
      font-size: 11px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      color: var(--muted);
      border: 1px solid var(--border);
      padding: 4px 10px;
      border-radius: 2px;
      font-weight: 400;

    }

    .project-description {
      font-size: 15px;
      line-height: 1.75;
      color: rgba(240, 236, 228, 0.7);
      flex-grow: 1;
      margin-bottom: 36px;

    }

    .project-links {
      display: flex;
      gap: 14px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-family: 'VT323', monospace;
      font-size: 12px;
      letter-spacing: 2px;
      text-transform: uppercase;
      font-weight: 500;
      padding: 12px 22px;
      text-decoration: none;
      border: 1px solid;
      transition: background 0.2s, color 0.2s;
      cursor: pointer;
    }

    .btn-primary {
      background: var(--accent);
      color: #0d0d0d;
      border-color: var(--accent);
    }

    .btn-primary:hover {
      background: #57ff3a;
      border-color: #57ff3a;
      box-shadow: 0 0 12px #39ff1480;
    }

    .btn-ghost {
      background: transparent;
      color: var(--text);
      border-color: var(--border);
    }

    .btn-ghost:hover {
      border-color: var(--accent);
      color: var(--accent);
    }

    /* ── Divider between sections ── */
    .section-divider {
      display: flex;
      align-items: center;
      gap: 20px;
      margin: 80px 0 60px;
    }

    .section-divider span {
      font-size: 11px;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: var(--muted);
      white-space: nowrap;
    }

    .section-divider::before,
    .section-divider::after {
      content: '';
      flex: 1;
      height: 1px;
      background: var(--border);
    }

    /* ── Footer ── */
    footer {
      border-top: 1px solid var(--border);
      padding: 40px 8vw;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: var(--muted);
      font-size: 20px;
      position: relative;
      z-index: 1;
    }

    footer a {
      color: var(--accent);
      text-decoration: none;
    }

    /* ── Responsive ── */
    @media (max-width: 768px) {
      .project {
        grid-template-columns: 1fr;
        direction: ltr !important;
      }

      .project:nth-child(even) .project-media {
        border-left: none;
        border-right: none;
        border-bottom: 1px solid var(--border);
      }

      .project-media {
        border-right: none !important;
        border-bottom: 1px solid var(--border);
      }

      .project-info {
        padding: 32px 28px;
      }

      header::after { display: none; }
    }
  </style>
</head>
<body>

  <!-- ═══════════════════════════════════════════
       HEADER
  ════════════════════════════════════════════ -->
  <header>
    <p class="header-label">Portfolio</p>
    <h1>My <span>Projects</span></h1>
    <p class="header-sub">A collection of things I've built, designed, and shipped.</p>
  </header>

  <main>
    <article class="project">

      <div class="project-media">
        <img src="hotpotato.png" alt="Project 1 screenshot" width="200" height="300" />
      </div>

      <div class="project-info">
        <div>
          <p class="project-number">Project — 01</p>
          <h2 class="project-title">Personal Heat Monitor</h2>
          <div class="project-tags">
            <span class="tag">Web Dev</span>
            <span class="tag">Firmware</span>
            <span class="tag">Circuit Design</span>
          </div>
          <p style="font-size: 20px; "class="project-description">
            This is a personal heat monitor comprised of an ESP32-C3 and an SHT40 temperature and humidity sensor. It is designed to be clipped to a backpack and carried around the MIT campus to get temperature readings, which it then posts to a website so students can see how hot it is at different parts of the campus. This was a team project made for MIT's Engineering for Impact class (6.900). The project consisted of designing the PCB, creating the industrial design, programming the firmware, and creating the website. Check out the website below!
          </p>
        </div>
        <div class="project-links">
          <a href="https://efpi-11.mit.edu" class="btn btn-primary">Website →</a>
        </div>
      </div>

    </article>


    <!-- ═══════════════════════════════════════════
         PROJECT 2
    ════════════════════════════════════════════ -->

    <article class="project">

      <div class="project-media">
        <div class="project-media">
        <video controls><source src="lane_6.mp4" type="video/mp4" /></video>
      </div>
      </div>

      <div class="project-info">
        <div>
          <p class="project-number">Project — 02</p>
          <h2 class="project-title">Autonomous Racecar</h2>
          <div class="project-tags">
            <span class="tag">Robotics</span>
            <span class="tag">ROS2</span>
          </div>
          <p style="font-size: 20px;" class="project-description">
            This project was made for MIT's Robotics: Science and Systems class. It is a small car that was programmed to be able to stay in a track lane while maintaining high speeds to beat others in a race. Other parts of the challenge consisted of being able to localize itself in a known environment and navigate dynamic obstacles while attempting to identify certain objects with machine learning. Check out the rest of the project at the link below!
          </p>
        </div>
        <div class="project-links">
          <a href="https://rss2025-6.github.io/website/" class="btn btn-primary">Project Link</a>
        </div>
      </div>

    </article>

    <!-- ═══════════════════════════════════════════
         PROJECT 3
    ════════════════════════════════════════════ -->
    <article class="project">

      <div class="project-media">
        <video controls><source src="Lights.mp4" type="video/mp4" /></video>
      </div>

      <div class="project-info">
        <div>
          <p class="project-number">Project — 03</p>
          <h2 class="project-title">Sinusoidal Light and Sound Display</h2>
          <div class="project-tags">
            <span class="tag">Circuit Design</span>
            <span class="tag">Power Electronics</span>
          </div>
          <p style="font-size: 20px;" class="project-description">
            This project was made for MIT's Power Electronics class (6.2220). A voltage source of 1.5 V is put through a Boost Converter with a duty cycle of approximately 1/3 to bring it up to 5.54 V. This is then used to power a 555 timer to make a square wave which is smoothed by a simple Low Pass filter. The resulting wave is given to a set of LM3914s to power some bar displays and to a speaker made with wire and a neodymium magnet.
          </p>
        </div>
      </div>

    </article>


    <!-- ═══════════════════════════════════════════
         ADD MORE PROJECTS
    ════════════════════════════════════════════ -->

    <div class="section-divider"><span>More coming soon</span></div>

  </main>

  <!-- ═══════════════════════════════════════════
       FOOTER
  ════════════════════════════════════════════ -->
  <footer>
    <span>Willow Pickernell · 2026</span>
    <span>
      <a href="mailto:wrpicker25@gmail.com">wrpicker25@gmail.com</a>
    </span>
  </footer>

</body>
</html>
