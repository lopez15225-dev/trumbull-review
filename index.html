<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Trumbull Review</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,300..900&family=Source+Serif+4:ital,wght@0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
<style>

  :root{
    --paper:#EDE4D3;
    --paper-dark:#E3D7BF;
    --walnut:#3D2B1F;
    --brass:#A9762F;
    --ink:#1F2937;
    --sepia:#8B7355;
    --rule: rgba(61,43,31,0.25);
  }

  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    margin:0;
    background:var(--paper);
    background-image:
      radial-gradient(ellipse at top left, rgba(169,118,47,0.06), transparent 50%),
      radial-gradient(ellipse at bottom right, rgba(61,43,31,0.05), transparent 50%);
    color:var(--ink);
    font-family:'Source Serif 4', serif;
    -webkit-font-smoothing:antialiased;
  }

  h1,h2,h3,.display{
    font-family:'Fraunces', serif;
    font-weight:600;
    color:var(--walnut);
    letter-spacing:-0.01em;
  }

  a{color:var(--walnut);}

  .eyebrow{
    font-family:'Source Serif 4', serif;
    font-style:italic;
    font-size:0.78rem;
    letter-spacing:0.14em;
    text-transform:uppercase;
    color:var(--sepia);
  }

  .rule{
    border:none;
    border-top:1px solid var(--rule);
    margin:0;
  }
  .rule.thick{ border-top-width:3px; border-top-color:var(--walnut); }
  .rule.double{
    border-top: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
    height:3px;
  }

  /* skip link */
  .skip-link{
    position:absolute; left:-999px; top:0;
    background:var(--walnut); color:var(--paper); padding:0.6rem 1rem; z-index:100;
  }
  .skip-link:focus{ left:0.5rem; top:0.5rem; }

  a:focus-visible, button:focus-visible, input:focus-visible, textarea:focus-visible{
    outline:2px solid var(--brass);
    outline-offset:3px;
  }

  /* ===== NAV ===== */
  header{
    position:sticky; top:0; z-index:50;
    background:rgba(237,228,211,0.92);
    backdrop-filter:blur(6px);
    border-bottom:1px solid var(--rule);
  }
  nav{
    max-width:1180px; margin:0 auto;
    display:flex; align-items:center; justify-content:space-between;
    padding:0.9rem 1.5rem;
  }
  .brand{
    display:flex; align-items:center; gap:0.65rem;
    font-family:'Fraunces', serif; font-weight:600; font-size:1.15rem;
    color:var(--walnut); text-decoration:none;
  }
  .brand svg{ width:30px; height:30px; flex-shrink:0; }
  .nav-links{ display:flex; gap:2rem; list-style:none; margin:0; padding:0; }
  .nav-links a{
    text-decoration:none; font-size:0.92rem; letter-spacing:0.03em;
    color:var(--ink); position:relative; padding-bottom:4px;
  }
  .nav-links a::after{
    content:''; position:absolute; left:0; bottom:0; width:0; height:1px;
    background:var(--brass); transition:width 0.25s ease;
  }
  .nav-links a:hover::after{ width:100%; }
  .nav-toggle{ display:none; background:none; border:none; cursor:pointer; padding:0.3rem; }
  .nav-toggle svg{ width:26px; height:26px; stroke:var(--walnut); }

  @media (max-width:760px){
    .nav-links{
      position:absolute; top:100%; left:0; right:0;
      flex-direction:column; background:var(--paper);
      border-bottom:1px solid var(--rule);
      padding:1rem 1.5rem; gap:1.1rem;
      display:none;
    }
    .nav-links.open{ display:flex; }
    .nav-toggle{ display:block; }
  }

  /* ===== HERO ===== */
  .hero{
    max-width:1180px; margin:0 auto;
    padding:5rem 1.5rem 4rem;
    display:grid; grid-template-columns:1.1fr 0.9fr; gap:3rem;
    align-items:center;
  }
  .hero h1{
    font-size:clamp(2.6rem, 5.5vw, 4.3rem);
    line-height:1.04;
    margin:0.5rem 0 1.2rem;
  }
  .hero p.lede{
    font-size:1.18rem; line-height:1.65; color:var(--ink);
    max-width:34rem; margin:0 0 2rem;
  }
  .hero-actions{ display:flex; gap:1rem; flex-wrap:wrap; }

  .btn{
    display:inline-block;
    font-family:'Source Serif 4', serif;
    font-size:0.92rem; letter-spacing:0.04em;
    padding:0.8rem 1.7rem;
    text-decoration:none;
    border:1px solid var(--walnut);
    transition:background 0.2s ease, color 0.2s ease;
  }
  .btn-primary{ background:var(--walnut); color:var(--paper); }
  .btn-primary:hover{ background:#2a1d14; }
  .btn-ghost{ color:var(--walnut); }
  .btn-ghost:hover{ background:rgba(61,43,31,0.06); }

  .globe-wrap{
    display:flex; justify-content:center; align-items:center;
    position:relative;
  }
  .globe-wrap svg{
    width:min(100%, 380px);
    animation:spin 90s linear infinite;
  }
  @media (prefers-reduced-motion: reduce){
    .globe-wrap svg{ animation:none; }
  }
  @keyframes spin{ from{transform:rotate(0deg);} to{transform:rotate(360deg);} }

  @media (max-width:850px){
    .hero{ grid-template-columns:1fr; text-align:center; padding-top:3rem;}
    .hero p.lede{ margin-inline:auto; }
    .hero-actions{ justify-content:center; }
    .globe-wrap{ order:-1; }
    .globe-wrap svg{ width:200px; }
  }

  /* ===== SECTION SHELL ===== */
  section{ max-width:1180px; margin:0 auto; padding:5rem 1.5rem; }
  section + section{ border-top:1px solid var(--rule); }
  .section-head{ max-width:42rem; margin-bottom:3rem; }
  .section-head h2{ font-size:clamp(1.9rem,3.2vw,2.6rem); margin:0.4rem 0 1rem; }
  .section-head p{ font-size:1.05rem; line-height:1.6; color:var(--sepia); margin:0; }

  /* ===== ABOUT ===== */
  .about-grid{
    display:grid; grid-template-columns:1fr 1fr; gap:3.5rem;
  }
  .about-grid p{ line-height:1.75; font-size:1.04rem; margin:0 0 1.2rem; }
  .masthead-fact{
    background:var(--paper-dark);
    border:1px solid var(--rule);
    padding:1.6rem 1.8rem;
    margin-bottom:1.2rem;
  }
  .masthead-fact dt{ font-family:'Fraunces',serif; font-weight:600; color:var(--walnut); font-size:0.95rem;}
  .masthead-fact dd{ margin:0.2rem 0 0; color:var(--sepia); font-size:0.92rem; line-height:1.5;}
  @media (max-width:760px){ .about-grid{ grid-template-columns:1fr; } }

  /* ===== SUBMISSIONS ===== */
  .sub-list{ list-style:none; margin:0; padding:0; }
  .sub-list li{
    display:grid; grid-template-columns:7rem 1fr;
    gap:1.5rem;
    padding:1.4rem 0;
    border-top:1px solid var(--rule);
  }
  .sub-list li:last-child{ border-bottom:1px solid var(--rule); }
  .sub-list .label{
    font-family:'Fraunces',serif; font-weight:600; color:var(--brass);
    font-size:0.85rem; letter-spacing:0.06em; text-transform:uppercase;
    padding-top:0.1rem;
  }
  .sub-list .detail h3{ margin:0 0 0.4rem; font-size:1.15rem; }
  .sub-list .detail p{ margin:0; color:var(--ink); line-height:1.6; }
  @media (max-width:600px){
    .sub-list li{ grid-template-columns:1fr; gap:0.3rem; }
  }

  .cta-box{
    margin-top:3rem; padding:2.4rem;
    border:1px solid var(--walnut);
    display:flex; justify-content:space-between; align-items:center; gap:2rem;
    flex-wrap:wrap;
  }
  .cta-box h3{ margin:0 0 0.3rem; font-size:1.3rem; }
  .cta-box p{ margin:0; color:var(--sepia); font-size:0.95rem; }

  /* ===== SHOWCASE ===== */
  .issue-strip{
    display:flex; gap:0.5rem; flex-wrap:wrap; margin-bottom:3rem;
  }
  .issue-pill{
    font-size:0.82rem; letter-spacing:0.04em;
    padding:0.45rem 1rem;
    border:1px solid var(--rule);
    color:var(--sepia);
  }
  .issue-pill.current{ border-color:var(--walnut); color:var(--walnut); background:var(--paper-dark); }

  /* ===== ISSUE ARCHIVE ===== */
  .archive-grid{
    display:grid; grid-template-columns:repeat(3,1fr); gap:2rem;
  }
  .issue-card{
    border:1px solid var(--rule);
    background:var(--paper-dark);
    display:flex; flex-direction:column;
    transition:border-color 0.2s ease, transform 0.2s ease;
  }
  .issue-card:hover{ border-color:var(--walnut); transform:translateY(-2px); }
  .issue-cover{
    aspect-ratio:3/4;
    border-bottom:1px solid var(--rule);
    display:flex; align-items:center; justify-content:center;
    position:relative;
    background:
      repeating-linear-gradient(135deg, rgba(61,43,31,0.04) 0px, rgba(61,43,31,0.04) 1px, transparent 1px, transparent 14px),
      var(--paper);
  }
  .issue-cover svg{ width:46%; opacity:0.85; }
  .issue-cover .issue-num{
    position:absolute; top:0.9rem; left:1rem;
    font-family:'Fraunces',serif; font-weight:600;
    font-size:0.78rem; letter-spacing:0.08em; text-transform:uppercase;
    color:var(--sepia);
  }
  .issue-body{ padding:1.4rem 1.5rem 1.6rem; display:flex; flex-direction:column; flex:1; }
  .issue-body h3{ font-size:1.15rem; margin:0 0 0.3rem; }
  .issue-body .issue-date{ font-size:0.82rem; color:var(--sepia); margin-bottom:0.8rem; }
  .issue-body p{ font-size:0.92rem; line-height:1.55; color:var(--ink); margin:0 0 1.2rem; flex:1; }
  .issue-body .btn{ align-self:flex-start; padding:0.55rem 1.1rem; font-size:0.82rem; }
  .issue-card.upcoming{ opacity:0.6; }
  .issue-card.upcoming .issue-cover{ background:repeating-linear-gradient(135deg, rgba(61,43,31,0.03) 0px, rgba(61,43,31,0.03) 1px, transparent 1px, transparent 14px), var(--paper); }
  .issue-card.upcoming .btn{ pointer-events:none; border-color:var(--rule); color:var(--sepia); }

  @media (max-width:900px){ .archive-grid{ grid-template-columns:repeat(2,1fr); } }
  @media (max-width:600px){ .archive-grid{ grid-template-columns:1fr; } }

  .piece-grid{
    display:grid; grid-template-columns:repeat(3,1fr); gap:0;
    border-top:1px solid var(--rule);
    border-left:1px solid var(--rule);
  }
  .piece{
    border-right:1px solid var(--rule);
    border-bottom:1px solid var(--rule);
    padding:2.2rem 1.8rem;
    transition:background 0.2s ease;
  }
  .piece:hover{ background:var(--paper-dark); }
  .piece .eyebrow{ display:block; margin-bottom:0.8rem; }
  .piece h3{ font-size:1.25rem; margin:0 0 0.6rem; line-height:1.25; }
  .piece p{ margin:0 0 1rem; color:var(--ink); font-size:0.95rem; line-height:1.6; }
  .piece .byline{ font-size:0.85rem; color:var(--sepia); font-style:italic; }

  @media (max-width:900px){ .piece-grid{ grid-template-columns:repeat(2,1fr); } }
  @media (max-width:600px){ .piece-grid{ grid-template-columns:1fr; } }

  /* ===== TEAM / CONTACT ===== */
  .team-contact{
    display:grid; grid-template-columns:1.1fr 0.9fr; gap:4rem;
  }
  .team-list{ display:grid; grid-template-columns:1fr 1fr; gap:2rem; }
  .team-member h3{ font-size:1.05rem; margin:0 0 0.15rem; }
  .team-member .role{ color:var(--brass); font-size:0.85rem; letter-spacing:0.03em; text-transform:uppercase; }
  .team-member p{ margin:0.5rem 0 0; font-size:0.92rem; color:var(--sepia); line-height:1.55; }

  .contact-card{
    background:var(--walnut); color:var(--paper);
    padding:2.4rem; align-self:start;
  }
  .contact-card h3{ color:var(--paper); margin:0 0 1.2rem; font-size:1.25rem; }
  .contact-card .field{ margin-bottom:1.1rem; }
  .contact-card label{ display:block; font-size:0.82rem; letter-spacing:0.04em; margin-bottom:0.4rem; color:var(--paper-dark); }
  .contact-card input, .contact-card textarea{
    width:100%; background:rgba(237,228,211,0.08);
    border:1px solid rgba(237,228,211,0.35);
    color:var(--paper); padding:0.7rem 0.8rem;
    font-family:'Source Serif 4', serif; font-size:0.95rem;
    border-radius:0;
  }
  .contact-card input::placeholder, .contact-card textarea::placeholder{ color:rgba(237,228,211,0.5); }
  .contact-card textarea{ resize:vertical; min-height:90px; }
  .contact-card .btn-primary{
    background:var(--brass); border-color:var(--brass); color:var(--walnut);
    width:100%; text-align:center; cursor:pointer; margin-top:0.4rem;
  }
  .contact-card .btn-primary:hover{ background:#bf8736; }
  .form-note{ font-size:0.8rem; color:rgba(237,228,211,0.6); margin-top:0.8rem; }

  @media (max-width:850px){
    .team-contact{ grid-template-columns:1fr; }
    .team-list{ grid-template-columns:1fr 1fr; }
  }
  @media (max-width:500px){ .team-list{ grid-template-columns:1fr; } }

  /* ===== FOOTER ===== */
  footer{
    border-top:3px solid var(--walnut);
    padding:2.5rem 1.5rem;
    text-align:center;
  }
  footer p{ margin:0.3rem 0; font-size:0.85rem; color:var(--sepia); }
  footer .brand{ justify-content:center; margin-bottom:0.8rem; }

</style>
</head>
<body>

<a href="#main" class="skip-link">Skip to content</a>

<header>
  <nav>
    <a href="#top" class="brand">
      <svg viewBox="0 0 100 100" fill="none" stroke="currentColor" aria-hidden="true">
        <circle cx="50" cy="50" r="42" stroke-width="2.4"/>
        <circle cx="50" cy="50" r="42" stroke-width="0.6" stroke-dasharray="0.8 2.2"/>
        <ellipse cx="50" cy="50" rx="42" ry="10" stroke-width="0.9"/>
        <ellipse cx="50" cy="50" rx="42" ry="24" stroke-width="0.9"/>
        <ellipse cx="50" cy="50" rx="42" ry="36" stroke-width="0.9"/>
        <ellipse cx="50" cy="50" rx="8" ry="42" stroke-width="0.9"/>
        <ellipse cx="50" cy="50" rx="20" ry="42" stroke-width="0.9"/>
        <ellipse cx="50" cy="50" rx="32" ry="42" stroke-width="0.9"/>
        <line x1="8" y1="50" x2="92" y2="50" stroke-width="1.6"/>
        <line x1="50" y1="8" x2="50" y2="92" stroke-width="1.6"/>
        <g stroke-width="0.8">
          <path d="M50 26 L52.5 47.5 L74 50 L52.5 52.5 L50 74 L47.5 52.5 L26 50 L47.5 47.5 Z"/>
        </g>
        <circle cx="50" cy="50" r="1.8" fill="currentColor" stroke="none"/>
      </svg>
      The Trumbull Review
    </a>
    <button class="nav-toggle" aria-label="Toggle menu" aria-expanded="false" id="navToggle">
      <svg viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round"><line x1="3" y1="6" x2="21" y2="6"/><line x1="3" y1="12" x2="21" y2="12"/><line x1="3" y1="18" x2="21" y2="18"/></svg>
    </button>
    <ul class="nav-links" id="navLinks">
      <li><a href="#about">About</a></li>
      <li><a href="#submissions">Submissions</a></li>
      <li><a href="#showcase">Latest Issue</a></li>
      <li><a href="#archive">Archive</a></li>
      <li><a href="#team">Masthead</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<main id="main">

  <!-- HERO -->
  <div class="hero" id="top">
    <div>
      <span class="eyebrow">A Journal of Letters &amp; Ideas — Est. 2026</span>
      <h1>Charting new<br>literary territory.</h1>
      <p class="lede">The Trumbull Review publishes fiction, poetry, and essays from student writers drawn to history, place, and the long view. We read closely. We publish twice a year.</p>
      <div class="hero-actions">
        <a href="#submissions" class="btn btn-primary">Submit your work</a>
        <a href="#showcase" class="btn btn-ghost">Read the latest issue</a>
      </div>
    </div>
    <div class="globe-wrap">
      <svg viewBox="0 0 200 200" fill="none" stroke="#3D2B1F" aria-hidden="true">
        <!-- outer ring with engraved tick marks -->
        <circle cx="100" cy="100" r="88" stroke-width="2.4"/>
        <circle cx="100" cy="100" r="92" stroke-width="0.6"/>
        <g stroke-width="0.7">
          <line x1="100" y1="8" x2="100" y2="14"/>
          <line x1="100" y1="186" x2="100" y2="192"/>
          <line x1="8" y1="100" x2="14" y2="100"/>
          <line x1="186" y1="100" x2="192" y2="100"/>
          <line x1="37" y1="37" x2="41" y2="41"/>
          <line x1="163" y1="37" x2="159" y2="41"/>
          <line x1="37" y1="163" x2="41" y2="159"/>
          <line x1="163" y1="163" x2="159" y2="159"/>
        </g>

        <!-- latitude lines (parallels) -->
        <g stroke-width="0.9" opacity="0.85">
          <ellipse cx="100" cy="100" rx="88" ry="14"/>
          <ellipse cx="100" cy="100" rx="88" ry="34"/>
          <ellipse cx="100" cy="100" rx="88" ry="52"/>
          <ellipse cx="100" cy="100" rx="88" ry="70"/>
        </g>

        <!-- longitude lines (meridians) -->
        <g stroke-width="0.9" opacity="0.85">
          <ellipse cx="100" cy="100" rx="14" ry="88"/>
          <ellipse cx="100" cy="100" rx="34" ry="88"/>
          <ellipse cx="100" cy="100" rx="52" ry="88"/>
          <ellipse cx="100" cy="100" rx="70" ry="88"/>
        </g>

        <line x1="12" y1="100" x2="188" y2="100" stroke-width="1.8"/>
        <line x1="100" y1="12" x2="100" y2="188" stroke-width="1.8"/>

        <!-- rough hand-drawn "coastline" hatching for an aged feel -->
        <g stroke-width="0.7" opacity="0.7">
          <path d="M50 55 Q66 70 58 92 Q48 112 64 132 Q72 144 60 158"/>
          <path d="M138 45 Q156 78 146 110 Q140 132 154 150"/>
          <path d="M95 35 Q110 50 100 68"/>
          <path d="M65 150 Q80 158 95 168"/>
        </g>
        <g stroke-width="0.4" opacity="0.5">
          <path d="M55 60 l3 -2 M60 64 l3 -2 M65 70 l2 -2 M58 100 l3 -1 M62 104 l3 -1"/>
          <path d="M142 60 l-3 -1 M146 66 l-3 -1 M140 100 l-3 0 M144 106 l-3 1"/>
        </g>

        <!-- compass rose, slightly worn -->
        <g transform="translate(100,100)">
          <path d="M0 -20 L4 0 L0 20 L-4 0 Z" stroke-width="0.8"/>
          <path d="M-20 0 L0 4 L20 0 L0 -4 Z" stroke-width="0.8"/>
          <path d="M0 -32 L2.2 0 L0 32 L-2.2 0 Z" stroke-width="0.5" opacity="0.55" transform="rotate(45)"/>
          <circle r="3.2" fill="#A9762F" stroke="#3D2B1F" stroke-width="0.8"/>
        </g>
      </svg>
    </div>
  </div>

  <!-- ABOUT -->
  <section id="about">
    <div class="section-head">
      <span class="eyebrow">About the Review</span>
      <h2>Where the past informs the page.</h2>
    </div>
    <div class="about-grid">
      <div>
        <p>The Trumbull Review began as a question: what happens when student writers are asked to think historically — to write as if the past were not behind us, but folded into the present? The answer, twice a year, is this journal.</p>
        <p>We publish fiction, poetry, and essays that take the long view: pieces concerned with memory, inheritance, place, and the slow accumulation of time. We are not interested in nostalgia for its own sake. We are interested in writing that understands history as a living argument.</p>
        <p>Every issue is read blind by our editorial board and assembled with the same care a cartographer gives a map: nothing included by accident, every line earning its place.</p>
      </div>
      <dl>
        <div class="masthead-fact">
          <dt>Founded</dt>
          <dd>2026, by a small group of students who missed the smell of library archives.</dd>
        </div>
        <div class="masthead-fact">
          <dt>Frequency</dt>
          <dd>Two print-style issues per academic year, plus occasional online folios.</dd>
        </div>
        <div class="masthead-fact">
          <dt>What we publish</dt>
          <dd>Fiction, poetry, and lyric essay.</dd>
        </div>
      </dl>
    </div>
  </section>

  <!-- SUBMISSIONS -->
  <section id="submissions">
    <div class="section-head">
      <span class="eyebrow">Call for Submissions</span>
      <h2>How to submit.</h2>
      <p>We read general submissions year-round and send decisions within eight weeks. There is no submission fee.</p>
    </div>

    <ul class="sub-list">
      <li>
        <span class="label">Fiction</span>
        <div class="detail">
          <h3>Up to 5,000 words</h3>
          <p>One story per submission. We're drawn to work with a strong sense of time and place, but all approaches are welcome.</p>
        </div>
      </li>
      <li>
        <span class="label">Poetry</span>
        <div class="detail">
          <h3>Up to 5 poems per submission</h3>
          <p>Send your strongest work as a single document. We read for precision of language above all.</p>
        </div>
      </li>
      <li>
        <span class="label">Essays</span>
        <div class="detail">
          <h3>Up to 3,500 words</h3>
          <p>Lyric essays, criticism, and researched nonfiction. Footnotes and citations welcome, not required.</p>
        </div>
      </li>
      <li>
        <span class="label">Format</span>
        <div class="detail">
          <h3>Standard manuscript format</h3>
          <p>12-point serif font, double-spaced, .docx or .pdf. Remove your name from the file for blind review.</p>
        </div>
      </li>
      <li>
        <span class="label">Rights</span>
        <div class="detail">
          <h3>First publication rights only</h3>
          <p>All rights revert to the author upon publication. We ask for the right to keep your piece in our online archive.</p>
        </div>
      </li>
    </ul>

    <div class="cta-box">
      <div>
        <h3>Ready to send something in?</h3>
        <p>Submissions open year-round. Simultaneous submissions are fine — just let us know if a piece is accepted elsewhere.</p>
      </div>
      <a href="#contact" class="btn btn-primary">Get submission details</a>
    </div>
  </section>

  <!-- LATEST ISSUE -->
  <section id="showcase">
    <div class="section-head">
      <span class="eyebrow" id="latestIssueEyebrow">Latest Issue</span>
      <h2>From the latest issue.</h2>
    </div>

    <!-- Pieces are loaded dynamically from /issues/*.json by js/issues.js -->
    <div class="piece-grid" id="pieceGrid">
      <p style="color:var(--sepia); font-style:italic;">Loading issue…</p>
    </div>
  </section>

  <!-- ISSUE ARCHIVE -->
  <section id="archive">
    <div class="section-head">
      <span class="eyebrow">The Archive</span>
      <h2>All issues.</h2>
      <p>Every issue of The Trumbull Review, gathered in one place.</p>
    </div>

    <!-- Issue cards are loaded dynamically from /issues/*.json by js/issues.js -->
    <div class="archive-grid" id="archiveGrid">
      <p style="color:var(--sepia); font-style:italic;">Loading issues…</p>
    </div>
  </section>

  <!-- TEAM + CONTACT -->
  <section id="team">
    <div class="team-contact">
      <div>
        <div class="section-head" style="margin-bottom:2.2rem;">
          <span class="eyebrow">The Masthead</span>
          <h2>Who's behind the Review.</h2>
        </div>
        <div class="team-list">
          <div class="team-member">
            <h3>Placeholder Name</h3>
            <div class="role">Editor-in-Chief</div>
            <p>Oversees editorial direction and final selections.</p>
          </div>
          <div class="team-member">
            <h3>Placeholder Name</h3>
            <div class="role">Poetry Editor</div>
            <p>Reads and curates the poetry section each issue.</p>
          </div>
          <div class="team-member">
            <h3>Placeholder Name</h3>
            <div class="role">Fiction Editor</div>
            <p>Leads the fiction reading committee.</p>
          </div>
          <div class="team-member">
            <h3>Placeholder Name</h3>
            <div class="role">Design &amp; Layout</div>
            <p>Builds each issue's print and web presentation.</p>
          </div>
        </div>
      </div>

      <div id="contact">
        <div class="contact-card">
          <h3>Get in touch</h3>
          <form onsubmit="event.preventDefault(); document.getElementById('formMsg').style.display='block';">
            <div class="field">
              <label for="name">Name</label>
              <input id="name" type="text" placeholder="Your name" required>
            </div>
            <div class="field">
              <label for="email">Email</label>
              <input id="email" type="email" placeholder="you@example.com" required>
            </div>
            <div class="field">
              <label for="msg">Message</label>
              <textarea id="msg" placeholder="Questions about submissions, partnerships, or anything else." required></textarea>
            </div>
            <button type="submit" class="btn-primary">Send message</button>
          </form>
          <p class="form-note" id="formMsg" style="display:none;">This is a placeholder form — connect it to an email service or form backend before launch.</p>
          <p class="form-note">Or write to us directly at <strong>editors@meridianreview.example</strong></p>
        </div>
      </div>
    </div>
  </section>

</main>

<footer>
  <div class="brand">
    <svg viewBox="0 0 100 100" fill="none" stroke="currentColor" aria-hidden="true" style="width:26px;height:26px;">
      <circle cx="50" cy="50" r="42" stroke-width="2.4"/>
      <circle cx="50" cy="50" r="42" stroke-width="0.6" stroke-dasharray="0.8 2.2"/>
      <ellipse cx="50" cy="50" rx="42" ry="10" stroke-width="0.9"/>
      <ellipse cx="50" cy="50" rx="42" ry="24" stroke-width="0.9"/>
      <ellipse cx="50" cy="50" rx="42" ry="36" stroke-width="0.9"/>
      <ellipse cx="50" cy="50" rx="8" ry="42" stroke-width="0.9"/>
      <ellipse cx="50" cy="50" rx="20" ry="42" stroke-width="0.9"/>
      <ellipse cx="50" cy="50" rx="32" ry="42" stroke-width="0.9"/>
      <line x1="8" y1="50" x2="92" y2="50" stroke-width="1.6"/>
      <line x1="50" y1="8" x2="50" y2="92" stroke-width="1.6"/>
      <g stroke-width="0.8">
        <path d="M50 26 L52.5 47.5 L74 50 L52.5 52.5 L50 74 L47.5 52.5 L26 50 L47.5 47.5 Z"/>
      </g>
      <circle cx="50" cy="50" r="1.8" fill="currentColor" stroke="none"/>
    </svg>
    The Trumbull Review
  </div>
  <p>A student literary magazine of fiction, poetry, and essays.</p>
  <p>&copy; 2026 The Trumbull Review. All rights revert to the authors.</p>
</footer>

<script>
  const toggle = document.getElementById('navToggle');
  const links = document.getElementById('navLinks');
  toggle.addEventListener('click', () => {
    const isOpen = links.classList.toggle('open');
    toggle.setAttribute('aria-expanded', isOpen);
  });
  links.querySelectorAll('a').forEach(a => a.addEventListener('click', () => {
    links.classList.remove('open');
    toggle.setAttribute('aria-expanded', 'false');
  }));

  /* ===== EDIT MODE =====
     Toggle button lets you click into any text on the page and retype it.
     Changes are saved to this browser only (localStorage) until you
     click "Save & Download" to get an updated HTML file. */
  (function(){
    const STORAGE_KEY = 'trumbull-review-edits';
    let editMode = false;

    const bar = document.createElement('div');
    bar.id = 'editBar';
    bar.style.cssText = `
      position:fixed; bottom:1.2rem; right:1.2rem; z-index:200;
      display:flex; gap:0.6rem; align-items:center;
      font-family:'Source Serif 4', serif;
    `;
    bar.innerHTML = `
      <button id="editToggleBtn" style="
        background:#3D2B1F; color:#EDE4D3; border:none;
        padding:0.7rem 1.2rem; font-size:0.88rem; letter-spacing:0.03em;
        cursor:pointer; box-shadow:0 2px 10px rgba(0,0,0,0.25);">
        ✎ Edit Text
      </button>
      <button id="downloadBtn" style="
        display:none; background:#A9762F; color:#3D2B1F; border:none;
        padding:0.7rem 1.2rem; font-size:0.88rem; letter-spacing:0.03em;
        cursor:pointer; box-shadow:0 2px 10px rgba(0,0,0,0.25);">
        ⬇ Save &amp; Download
      </button>
    `;
    document.body.appendChild(bar);

    const editBtn = document.getElementById('editToggleBtn');
    const downloadBtn = document.getElementById('downloadBtn');

    function getEditableElements(){
      const selector = 'h1, h2, h3, p, span.eyebrow, span.label, span.byline, dt, dd, .role, .issue-pill, .issue-date';
      return Array.from(document.querySelectorAll(selector)).filter(el => {
        if (el.closest('#editBar')) return false;
        if (el.closest('#pieceGrid') || el.closest('#archiveGrid')) return false; // these are CMS-managed, edit via /admin instead
        const hasBlockChild = Array.from(el.children).some(c =>
          getComputedStyle(c).display.includes('block') || c.tagName === 'svg' || c.tagName === 'DIV');
        if (hasBlockChild) return false;
        return el.textContent.trim().length > 0;
      });
    }

    function applyEditMode(on){
      editMode = on;
      editBtn.textContent = on ? '✓ Done Editing' : '✎ Edit Text';
      downloadBtn.style.display = on ? 'inline-block' : 'none';
      getEditableElements().forEach(el => {
        el.contentEditable = on;
        el.style.outline = on ? '1px dashed rgba(169,118,47,0.6)' : '';
        el.style.cursor = on ? 'text' : '';
        el.style.outlineOffset = on ? '2px' : '';
      });
    }

    editBtn.addEventListener('click', () => applyEditMode(!editMode));

    document.body.addEventListener('input', (e) => {
      if (!editMode) return;
      saveEdits();
    }, true);

    function saveEdits(){
      const data = {};
      getEditableElements().forEach((el, i) => {
        el.dataset.editId = el.dataset.editId || ('edit-' + i);
        data[el.dataset.editId] = el.innerHTML;
      });
      try{ localStorage.setItem(STORAGE_KEY, JSON.stringify(data)); }catch(e){}
    }

    function loadEdits(){
      let data;
      try{ data = JSON.parse(localStorage.getItem(STORAGE_KEY) || '{}'); }catch(e){ data = {}; }
      getEditableElements().forEach((el, i) => {
        const id = 'edit-' + i;
        el.dataset.editId = id;
        if (data[id] !== undefined) el.innerHTML = data[id];
      });
    }

    downloadBtn.addEventListener('click', () => {
      saveEdits();
      const clone = document.documentElement.cloneNode(true);
      const cloneBar = clone.querySelector('#editBar');
      if (cloneBar) cloneBar.remove();
      clone.querySelectorAll('[contenteditable]').forEach(el => {
        el.removeAttribute('contenteditable');
        el.style.outline = '';
        el.style.cursor = '';
        el.style.outlineOffset = '';
        el.removeAttribute('data-edit-id');
      });
      const html = '<!DOCTYPE html>\n' + clone.outerHTML;
      const blob = new Blob([html], {type:'text/html'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'trumbull-review.html';
      document.body.appendChild(a);
      a.click();
      a.remove();
      URL.revokeObjectURL(url);
    });

    window.addEventListener('DOMContentLoaded', loadEdits);
    if (document.readyState !== 'loading') loadEdits();
  })();
</script>

  <script src="js/issues.js"></script>
</body>
</html>
