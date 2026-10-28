# sadiqctr.github.io
Community Moderator Portfolio — Telegram Discord and Community Management
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#09090f">

  <title>Sadiqctr | Web3 Community Moderator</title>

  <meta name="description"
    content="Sadiqctr — Web3 community moderator specializing in Telegram, Discord, community safety, and member engagement. Open to full-time remote opportunities.">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #09090f;
      --panel: #11111c;
      --text: #f4f2ff;
      --muted: #a6a3bb;
      --purple: #a78bfa;
      --pink: #e879f9;
      --green: #a3ffcb;
      --border: rgba(255,255,255,0.10);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 90px;
    }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: "DM Sans", sans-serif;
      line-height: 1.7;
      overflow-x: hidden;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(1100px, 90%);
      margin: auto;
    }

    .glow {
      position: absolute;
      width: 300px;
      height: 300px;
      border-radius: 50%;
      filter: blur(110px);
      opacity: 0.16;
      pointer-events: none;
      z-index: -1;
      background: var(--purple);
    }

    .glow-one {
      top: 100px;
      left: -130px;
    }

    .glow-two {
      top: 500px;
      right: -150px;
      background: var(--pink);
    }

    /* Navigation */

    header {
      position: sticky;
      top: 0;
      z-index: 10;
      background: rgba(9,9,15,0.88);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
    }

    nav {
      min-height: 76px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      font-family: "Space Grotesk", sans-serif;
      font-size: 1.5rem;
      font-weight: 700;
      letter-spacing: -1px;
    }

    .logo span {
      color: var(--purple);
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 25px;
      font-size: 0.9rem;
      color: var(--muted);
    }

    .nav-links a:hover {
      color: var(--purple);
    }

    .nav-cta {
      border: 1px solid rgba(167,139,250,0.6);
      border-radius: 9px;
      padding: 9px 15px;
      color: var(--text) !important;
    }

    /* Hero */

    .hero {
      min-height: 660px;
      display: flex;
      align-items: center;
      padding: 100px 0 90px;
      position: relative;
    }

    .hero-content {
      max-width: 790px;
    }

    .availability {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      border: 1px solid var(--border);
      border-radius: 50px;
      padding: 8px 14px;
      color: var(--green);
      font-size: 0.83rem;
      margin-bottom: 28px;
      background: rgba(163,255,203,0.04);
    }

    .status-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: var(--green);
      box-shadow: 0 0 12px var(--green);
    }

    h1, h2, h3 {
      font-family: "Space Grotesk", sans-serif;
      line-height: 1.15;
    }

    h1 {
      font-size: clamp(3rem, 8vw, 6.2rem);
      letter-spacing: -5px;
      margin-bottom: 18px;
    }

    .gradient-text {
      background: linear-gradient(100deg, var(--purple), var(--pink));
      color: transparent;
      background-clip: text;
      -webkit-background-clip: text;
    }

    .hero h2 {
      font-size: clamp(1.15rem, 3vw, 1.65rem);
      font-weight: 500;
      color: #d9d4ef;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 640px;
      color: var(--muted);
      font-size: 1.05rem;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 13px 21px;
      border-radius: 10px;
      font-weight: 700;
      font-size: 0.94rem;
      transition: transform 0.2s, border-color 0.2s;
    }

    .btn:hover {
      transform: translateY(-3px);
    }

    .btn-primary {
      background: linear-gradient(110deg, #a78bfa, #d879f9);
      color: #100b1a;
    }

    .btn-secondary {
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.025);
    }

    /* Sections */

    section {
      padding: 85px 0;
    }

    .section-label {
      color: var(--purple);
      text-transform: uppercase;
      letter-spacing: 3px;
      font-size: 0.76rem;
      font-weight: 700;
      margin-bottom: 13px;
    }

    .section-title {
      font-size: clamp(2rem, 5vw, 3.1rem);
      letter-spacing: -1.5px;
      margin-bottom: 18px;
    }

    .section-intro {
      max-width: 650px;
      color: var(--muted);
      margin-bottom: 40px;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 18px;
    }

    .skill-card {
      background: linear-gradient(
        145deg,
        rgba(255,255,255,0.045),
        rgba(255,255,255,0.012)
      );
      border: 1px solid var(--border);
      border-radius: 17px;
      padding: 28px;
      transition: border-color 0.25s, transform 0.25s;
    }

    .skill-card:hover {
      border-color: rgba(167,139,250,0.55);
      transform: translateY(-4px);
    }

    .skill-icon {
      width: 48px;
      height: 48px;
      display: grid;
      place-items: center;
      border-radius: 13px;
      background: rgba(167,139,250,0.12);
      font-size: 1.45rem;
      margin-bottom: 20px;
    }

    .skill-card h3 {
      font-size: 1.25rem;
      margin-bottom: 10px;
    }

    .skill-card p {
      color: var(--muted);
      font-size: 0.94rem;
    }

    /* About */

    .about-box {
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: clamp(25px, 5vw, 50px);
      background:
        radial-gradient(
          circle at 100% 0%,
          rgba(167,139,250,0.10),
          transparent 45%
        ),
        var(--panel);
    }

    .about-box p {
      color: var(--muted);
      max-width: 780px;
      margin-bottom: 18px;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 25px;
    }

    .tag {
      border: 1px solid var(--border);
      border-radius: 50px;
      padding: 7px 13px;
      font-size: 0.83rem;
      color: #ddd5ff;
      background: rgba(167,139,250,0.06);
    }

    /* Work */

    .work-card {
      padding: 30px;
      border-radius: 16px;
      border: 1px dashed rgba(167,139,250,0.45);
      background: rgba(167,139,250,0.04);
    }

    .work-card h3 {
      margin-bottom: 12px;
    }

    .work-card p {
      color: var(--muted);
    }

    /* Contact */

    .contact-box {
      text-align: center;
      padding: clamp(30px, 7vw, 70px) 20px;
      border: 1px solid var(--border);
      border-radius: 22px;
      background:
        radial-gradient(
          ellipse at 50% 0%,
          rgba(167,139,250,0.13),
          transparent 60%
        ),
        var(--panel);
    }

    .contact-box .section-intro {
      margin: 0 auto 30px;
    }

    .contact-links {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 13px;
    }

    footer {
      border-top: 1px solid var(--border);
      padding: 25px 0;
      color: var(--muted);
      font-size: 0.85rem;
    }

    .footer-inner {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 12px;
    }

    /* Mobile */

    @media (max-width: 650px) {
      .nav-links {
        gap: 13px;
        font-size: 0.82rem;
      }

      .nav-links .nav-cta {
        padding: 7px 10px;
      }

      .hero {
        min-height: auto;
        padding: 100px 0 75px;
      }

      h1 {
        letter-spacing: -2.5px;
      }

      section {
        padding: 65px 0;
      }

      .skills-grid {
        grid-template-columns: 1fr;
      }

      .skill-card {
        padding: 23px;
      }
    }

    @media (max-width: 390px) {
      .logo {
        font-size: 1.2rem;
      }

      .nav-links {
        gap: 9px;
      }

      .nav-links a {
        font-size: 0.76rem;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after {
        scroll-behavior: auto !important;
        transition: none !important;
      }
    }
  </style>
</head>

<body>
  <div class="glow glow-one"></div>
  <div class="glow glow-two"></div>

  <header>
    <nav class="container" aria-label="Main navigation">
      <a class="logo" href="#home">Sadiq<span>ctr.</span></a>

      <div class="nav-links">
        <a href="#skills">Skills</a>
        <a href="#about">About</a>
        <a class="nav-cta" href="#contact">Contact ↗</a>
      </div>
    </nav>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero container" id="home">
      <div class="hero-content">

        <div class="availability">
          <span class="status-dot"></span>
          Open to full-time remote opportunities
        </div>

        <h1>
          Sadiq<span class="gradient-text">ctr</span>
        </h1>

        <h2>
          Web3 Community Moderator
          <span class="gradient-text"> & Community Support</span>
        </h2>

        <p>
          Helping build safer, more organized, and welcoming online
          communities. Focused on Telegram moderation, Discord support,
          community safety, and meaningful member engagement.
        </p>

        <div class="buttons">
          <a class="btn btn-primary"
             href="https://t.me/sadiqctr"
             target="_blank"
             rel="noopener noreferrer">
            Connect on Telegram ↗
          </a>

          <a class="btn btn-secondary" href="#skills">
            Explore My Skills ↓
          </a>
        </div>

      </div>
    </section>

    <!-- SKILLS -->
    <section id="skills">
      <div class="container">

        <div class="section-label">What I Focus On</div>
        <h2 class="section-title">
          Community first.<br>
          <span class="gradient-text">People always.</span>
        </h2>

        <p class="section-intro">
          Supporting healthy digital communities through clear
          communication, responsible moderation, and a welcoming
          environment for members.
        </p>

        <div class="skills-grid">

          <article class="skill-card">
            <div class="skill-icon" aria-hidden="true">💬</div>
            <h3>Telegram Moderation</h3>
            <p>
              Supporting community rules, identifying spam,
              assisting members, and helping keep discussions
              organized and respectful.
            </p>
          </article>

          <article class="skill-card">
            <div class="skill-icon" aria-hidden="true">🎮</div>
            <h3>Discord Communities</h3>
            <p>
              Helping maintain organized servers, supporting
              members, enforcing guidelines, and contributing
              to positive community experiences.
            </p>
          </article>

          <article class="skill-card">
            <div class="skill-icon" aria-hidden="true">🛡️</div>
            <h3>Community Safety</h3>
            <p>
              Staying alert to suspicious messages, potential
              scams, spam, and rule violations while helping
              members follow safe online practices.
            </p>
          </article>

          <article class="skill-card">
            <div class="skill-icon" aria-hidden="true">🌐</div>
            <h3>Web3 Community Support</h3>
            <p>
              Learning Web3 culture and supporting constructive
              conversations around blockchain projects,
              community guidelines, and member engagement.
            </p>
          </article>

        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about">
      <div class="container">

        <div class="section-label">A Little About Me</div>
        <h2 class="section-title">The person behind the username.</h2>

        <div class="about-box">
          <p>
            I'm Sadiqctr, an aspiring Web3 professional focused on
            Telegram and Discord community moderation. I'm interested
            in helping online communities become more organized,
            welcoming, and safe for their members.
          </p>

          <p>
            I'm continuing to develop my knowledge of Web3, community
            management, and the tools used by blockchain communities.
            I'm eager to learn, communicate professionally, and
            contribute to a team that values its community.
          </p>

          <p>
            My goal is to grow into a trusted community professional
            and contribute to a Web3 project in a full-time remote role.
          </p>

          <div class="tags">
            <span class="tag">Telegram</span>
            <span class="tag">Discord</span>
            <span class="tag">Community Support</span>
            <span class="tag">Moderation</span>
            <span class="tag">Web3 Learning</span>
            <span class="tag">Remote Opportunities</span>
          </div>
        </div>

      </div>
    </section>

    <!-- PORTFOLIO -->
    <section id="work">
      <div class="container">

        <div class="section-label">Portfolio</div>
        <h2 class="section-title">Work that speaks for itself.</h2>

        <p class="section-intro">
          This section can grow with your experience as you build
          moderation examples and document the work you're permitted
          to share.
        </p>

        <div class="work-card">
          <h3>Community Moderation Playbook</h3>
          <p>
            A future portfolio project: a sample set of community
            rules, spam-handling procedures, member-support guidelines,
            and escalation steps for a fictional Web3 community.
          </p>
        </div>

      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <div class="container">

        <div class="contact-box">
          <div class="section-label">Let's Connect</div>

          <h2 class="section-title">
            Let's build better<br>
            <span class="gradient-text">communities together.</span>
          </h2>

          <p class="section-intro">
            Interested in discussing a community moderation role
            or remote opportunity? Reach out to me.
          </p>

          <div class="contact-links">

            <a class="btn btn-primary"
               href="https://t.me/sadiqctr"
               target="_blank"
               rel="noopener noreferrer">
              Telegram ↗
            </a>

            <a class="btn btn-secondary"
               href="https://x.com/sadiqctr"
               target="_blank"
               rel="noopener noreferrer">
              Follow on X ↗
            </a>

          </div>
        </div>

      </div>
    </section>
  </main>

  <footer>
    <div class="container footer-inner">
      <span>© <span id="year">2026</span> Sadiqctr. All rights reserved.</span>
      <span>Built for community. Inspired by Web3.</span>
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>
</body>
</html>
