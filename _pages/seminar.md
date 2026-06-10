---
layout: single
title: "WTM World Model Seminar"
permalink: /seminar/
author_profile: false
classes: wide
---

<style>
/* ── Hero ── */
.sem-hero {
  background: linear-gradient(135deg, #0d2b45 0%, #0b4f6c 55%, #0a6e5f 100%);
  color: #fff;
  padding: 3rem 2.5rem 2.5rem;
  border-radius: 10px;
  margin-bottom: 2.2rem;
  text-align: center;
}
.sem-hero .eyebrow {
  font-size: 0.92rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  opacity: 0.7;
  margin-bottom: 0.7rem;
}
.sem-hero h1 {
  font-size: 2.6rem;
  font-weight: 700;
  color: #fff;
  margin: 0 0 0.6rem;
  border: none;
}
.sem-hero .tagline {
  font-size: 1.2rem;
  opacity: 0.85;
  max-width: 560px;
  margin: 0 auto 1.3rem;
  line-height: 1.6;
}
.sem-hero .hero-btn {
  display: inline-block;
  background: rgba(255,255,255,0.12);
  border: 1px solid rgba(255,255,255,0.35);
  color: #fff;
  padding: 0.45rem 1.3rem;
  border-radius: 20px;
  font-size: 0.98rem;
  text-decoration: none;
  transition: background 0.2s;
}
.sem-hero .hero-btn:hover { background: rgba(255,255,255,0.24); color: #fff; }

/* ── Info cards ── */
.sem-cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.25rem;
  margin-bottom: 2.5rem;
}
.sem-card {
  background: #f8f9fa;
  border: 1px solid #e2e6ea;
  border-radius: 10px;
  padding: 2rem 1.5rem;
  text-align: center;
}
.sem-card .s-icon { font-size: 2.4rem; margin-bottom: 0.6rem; }
.sem-card .s-label {
  font-size: 0.88rem;
  text-transform: uppercase;
  letter-spacing: 0.07em;
  color: #888;
  margin-bottom: 0.4rem;
}
.sem-card .s-value {
  font-size: 1.15rem;
  font-weight: 600;
  color: #222;
  line-height: 1.5;
}
.sem-card .s-value small { font-weight: 400; color: #555; font-size: 1rem; }
.sem-card .s-btn {
  display: inline-block;
  margin-top: 0.8rem;
  padding: 0.45rem 1.2rem;
  background: #0b4f6c;
  color: #fff !important;
  border-radius: 4px;
  font-size: 1rem;
  text-decoration: none;
}
.sem-card .s-btn:hover { background: #0d2b45; }

/* ── Section headings ── */
.sem-section-title {
  font-size: 1.4rem;
  font-weight: 700;
  color: #0b4f6c;
  border-bottom: 2px solid #0b4f6c;
  padding-bottom: 0.35rem;
  margin: 2.2rem 0 1.1rem;
}

/* ── Schedule table ── */
.sem-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 1rem;
  margin-bottom: 0.5rem;
}
.sem-table thead th {
  background: #0b4f6c;
  color: #fff;
  padding: 0.7rem 0.9rem;
  text-align: left;
  font-weight: 600;
  white-space: nowrap;
}
.sem-table tbody td {
  padding: 0.7rem 0.9rem;
  border-bottom: 1px solid #e9ecef;
  vertical-align: top;
}
.sem-table tbody tr:nth-child(even) td { background: #f6f8fa; }
.sem-table tbody tr:hover td { background: #e3f0f8; }
.sem-table .num { color: #888; font-size: 0.92rem; }
.sem-table .tba { color: #aaa; font-style: italic; }
.sem-table .topic-title { font-weight: 600; color: #1a1a1a; font-size: 1rem; }
.sem-table .topic-title a { color: #0b4f6c; text-decoration: underline; }
.sem-table .topic-title a:hover { color: #0a6e5f; }
.sem-table .topic-sub  { font-size: 0.9rem; color: #555; margin-top: 0.2rem; }

/* ── Badges ── */
.badge {
  display: inline-block;
  border-radius: 3px;
  font-size: 0.84rem;
  padding: 0.15rem 0.5rem;
  font-weight: 600;
}
.badge-room    { background:#e3f2fd; color:#1565c0; border:1px solid #90caf9; }
.badge-online  { background:#e8f5e9; color:#2e7d32; border:1px solid #a5d6a7; }
.badge-hybrid  { background:#f3e5f5; color:#6a1b9a; border:1px solid #ce93d8; }
.badge-past    { background:#f5f5f5; color:#888;    border:1px solid #ddd; }

/* ── Notice box ── */
.sem-notice {
  background: #fffbe6;
  border-left: 4px solid #f0b429;
  border-radius: 0 6px 6px 0;
  padding: 0.95rem 1.2rem;
  font-size: 1rem;
  color: #554400;
  margin-top: 1.5rem;
}
.sem-notice a { color: #0b4f6c; }

/* ── About section ── */
.sem-about {
  background: #f0f7ff;
  border: 1px solid #cce0f5;
  border-radius: 8px;
  padding: 1.4rem 1.6rem;
  font-size: 1.05rem;
  line-height: 1.75;
  color: #333;
}
.sem-about p { margin: 0; }
</style>

<!-- ═══ HERO ═══ -->
<div class="sem-hero">
  <img src="/images/WTM_WM_Seminar.png" alt="WTM World Model Seminar logo"
       style="width:240px; height:240px; object-fit:contain; border-radius:20px;
              background:rgba(255,255,255,0.12); padding:14px; margin-bottom:1.2rem;">
  <div class="eyebrow">University of Hamburg &nbsp;·&nbsp; Department of Informatics</div>
  <h1>WTM World Model Seminar</h1>
  <p class="tagline">
    A weekly reading and presentation seminar on world models, vision-language action models, and embodied intelligence — bridging theory and robotics.
  </p>
  <a class="hero-btn" href="https://www.inf.uni-hamburg.de/en/inst/ab/wtm.html" target="_blank">
    Knowledge Technology Group (WTM) ↗
  </a>
</div>

<!-- ═══ INFO CARDS ═══ -->
<div class="sem-cards">

  <div class="sem-card">
    <div class="s-icon">📅</div>
    <div class="s-label">When</div>
    <div class="s-value">
      Every Wednesday<br>
      <small>[14:00 – 16:00 CET]</small>
    </div>
  </div>

  <div class="sem-card">
    <div class="s-icon">📍</div>
    <div class="s-label">Where (In-Person)</div>
    <div class="s-value">
      [House of Informatics]<br>
      <small>Bundesstr. 56b, 20146 Hamburg</small>
    </div>
  </div>

  <div class="sem-card">
    <div class="s-icon">💻</div>
    <div class="s-label">Join Online</div>
    <div class="s-value">Zoom</div>
    <a class="s-btn" href="https://uni-hamburg.zoom.us/j/62688965566?pwd=gZWbwaI1g6ba1lhvu3L98LuDzvEvdw.1" target="_blank">Join Zoom ↗</a>
  </div>

</div>

<!-- ═══ ABOUT ═══ -->
<div class="sem-section-title">About the Seminar</div>
<div class="sem-about">
  <p>
    The <strong>WTM World Model Seminar</strong> is an internal research seminar organized by the
    <a href="https://www.inf.uni-hamburg.de/en/inst/ab/wtm.html" target="_blank">Knowledge Technology (WTM) group</a>
    at the University of Hamburg. Each session features a presentation and discussion on recent advances
    in world models — including their applications to planning, perception, reinforcement learning,
    and robotic control. The seminar is open to all members of the WTM group and interested researchers.
    Both in-person attendance (Hamburg) and remote participation via Zoom are welcome.
  </p>
</div>

<!-- ═══ SCHEDULE ═══ -->
<div class="sem-section-title">Schedule</div>

<table class="sem-table">
  <thead>
    <tr>
      <th>#</th>
      <th>Date</th>
      <th>Topic</th>
      <th>Presenter</th>
      <th>Location/Room</th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <td class="num">01</td>
      <td>[May 27, 2026]</td>
      <td>
        <div class="topic-title"><a href="https://arxiv.org/abs/2605.00080" target="_blank">World Model for Robot Learning: A Comprehensive Survey</a></div>
        <div class="topic-sub">Hou et al.</div>
      </td>
      <td class="Presenter">Parsa</td>
      <td><span class="badge badge-room">[07-627]</span></td>
    </tr>

    <tr>
      <td class="num">02</td>
      <td>[June 3, 2026]</td>
      <td>
        <div class="topic-title"><a href="https://gr1-manipulation.github.io/" target="_blank">Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation</a></div>
        <div class="topic-sub">ByteDance Research</div>
      </td>
      <td class="Presenter">Mostafa</td>
      <td><span class="badge badge-room">[07-627]</span></td>
    </tr>

    <tr>
      <td class="num">03</td>
      <td>[June 10, 2026]</td>
      <td>
        <div class="topic-title">World Model as Simulator</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">Thomas</td>
      <td><span class="badge badge-room">[07-627]</span></td>
    </tr>

    <tr>
      <td class="num">04</td>
      <td>[June 17, 2026]</td>
      <td>
        <div class="topic-title">TBA</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">Kun</td>
      <td><span class="badge badge-room">[07-627]</span></td>
    </tr>

    <tr>
      <td class="num">05</td>
      <td>[June 24, 2026]</td>
      <td>
        <div class="topic-title">TBA</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">TBA</td>
      <td><span class="badge badge-room">[07-627]</span></td>
    </tr>

    <!-- ── Add more rows by copying the block above ── -->

  </tbody>
</table>

<div class="sem-notice">
  📬 <strong>Want to present?</strong> &nbsp;Please contact <a href="mailto:kun.chu@uni-hamburg.de">Kun</a> to sign up for a slot.<br>
</div>
