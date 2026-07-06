---
layout: single
title: "WTM World Model Seminar"
permalink: /seminar/
author_profile: false
classes: wide
---

<style>
/* ── Width override (this page only) ── */
#main {
  width: min(100%, 1180px);
  max-width: calc(100% - 2rem);
}
.page {
  width: 100%;
  padding-right: 0 !important;
}
@media (min-width: 80em) {
  #main { max-width: 80%; }
}

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

/* ── Live calendar icon (next seminar date) ── */
.cal-icon {
  display: inline-block;
  width: 56px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 6px rgba(0,0,0,0.18);
  background: #fff;
  margin-bottom: 0.6rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  line-height: 1;
}
.cal-icon .cal-month {
  background: #c0392b;
  color: #fff;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  padding: 0.22rem 0;
}
.cal-icon .cal-day {
  color: #222;
  font-size: 1.7rem;
  font-weight: 700;
  padding: 0.28rem 0 0.32rem;
}
.cal-icon .cal-wday {
  color: #888;
  font-size: 0.62rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  padding-bottom: 0.3rem;
}
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
.sem-table td:nth-child(3) { min-width: 18rem; }

/* ── Presentation download link ── */
.presentation {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  margin-top: 0.4rem;
  padding: 0.2rem 0.6rem;
  background: #eef4f8;
  border: 1px solid #cfe0ec;
  border-radius: 4px;
  font-size: 0.85rem;
  font-weight: 600;
  color: #0b4f6c !important;
  text-decoration: none;
}
.presentation:hover { background: #0b4f6c; color: #fff !important; border-color: #0b4f6c; }
.presentation::before { content: "📄"; font-size: 0.95rem; }

/* ── Topic link row (Paper / Slides) ── */
.topic-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-top: 0.45rem;
}
.topic-links .presentation { margin-top: 0; }
.presentation.paper {
  background: #eef8f0;
  border-color: #cfe9d8;
  color: #0a6e5f !important;
}
.presentation.paper:hover { background: #0a6e5f; color: #fff !important; border-color: #0a6e5f; }
.presentation.paper::before { content: "🔗"; }

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
.sem-about p { margin: 0 0 1rem; }
.sem-about p:last-child { margin-bottom: 0; }

/* ── Feynman highlight callout ── */
.feynman-box {
  display: flex;
  gap: 1.1rem;
  align-items: flex-start;
  background: linear-gradient(135deg, #fffaf0 0%, #fff3da 100%);
  border: 1px solid #f0d9a8;
  border-left: 5px solid #e8a317;
  border-radius: 8px;
  padding: 1.3rem 1.6rem;
  margin: 1.4rem 0;
  line-height: 1.7;
  color: #4a3a16;
}
.feynman-box .fb-icon {
  font-size: 2rem;
  line-height: 1;
  flex-shrink: 0;
}
.feynman-box .fb-body { font-size: 1.05rem; }
.feynman-box .fb-title {
  font-weight: 700;
  font-size: 1.12rem;
  color: #9a6a00;
  margin: 0 0 0.35rem;
}
.feynman-box strong { color: #9a6a00; }
.feynman-box .fb-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-top: 0.7rem;
}
.feynman-box .fb-tag {
  background: #fff;
  border: 1px solid #ead9b0;
  border-radius: 20px;
  padding: 0.18rem 0.7rem;
  font-size: 0.85rem;
  font-weight: 600;
  color: #8a6400;
}

/* ── Clickable date chip (table) ── */
.date-chip {
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  width: 54px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 5px rgba(0,0,0,0.15);
  background: #fff;
  border: 1px solid #ddd;
  cursor: pointer;
  text-decoration: none !important;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  transition: transform 0.15s, box-shadow 0.15s;
  line-height: 1;
  vertical-align: top;
}
.date-chip:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 12px rgba(0,0,0,0.22);
}
.date-chip .dc-month {
  background: #c0392b;
  color: #fff;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  padding: 0.22rem 0;
  width: 100%;
  text-align: center;
}
.date-chip .dc-day {
  color: #222;
  font-size: 1.45rem;
  font-weight: 700;
  padding: 0.18rem 0 0;
  text-align: center;
  width: 100%;
}
.date-chip .dc-wday {
  color: #888;
  font-size: 0.58rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.04em;
  text-align: center;
  width: 100%;
  padding-bottom: 0.1rem;
}
.date-chip .dc-add {
  font-size: 0.6rem;
  color: #0b4f6c;
  font-weight: 700;
  padding: 0.2rem 0 0.22rem;
  text-align: center;
  background: #e4f0f8;
  width: 100%;
  letter-spacing: 0.03em;
}
.date-chip:hover .dc-add { background: #0b4f6c; color: #fff; }
.date-chip-past .dc-month { background: #999; }
.date-chip-past .dc-day   { color: #999; }
.date-chip-past .dc-wday  { color: #bbb; }
.date-chip-past .dc-add   { background: #f0f0f0; color: #aaa; }
.date-chip-past:hover .dc-add { background: #888; color: #fff; }

@media (max-width: 900px) {
  #main {
    max-width: 100%;
    padding-left: 0.9rem;
    padding-right: 0.9rem;
  }

  .page {
    padding-left: 0 !important;
    padding-right: 0 !important;
  }

  .sem-hero {
    padding: 2rem 1.1rem 1.8rem;
    border-radius: 8px;
    margin-bottom: 1.4rem;
  }

  .sem-hero img {
    width: min(58vw, 190px) !important;
    height: auto !important;
    padding: 10px !important;
    margin-bottom: 0.9rem !important;
  }

  .sem-hero .eyebrow {
    font-size: 0.74rem;
    line-height: 1.5;
    letter-spacing: 0.07em;
  }

  .sem-hero h1 {
    font-size: clamp(1.7rem, 9vw, 2.25rem);
    line-height: 1.08;
  }

  .sem-hero .tagline {
    font-size: 1rem;
    line-height: 1.55;
  }

  .sem-cards {
    grid-template-columns: 1fr;
    gap: 0.9rem;
    margin-bottom: 1.6rem;
  }

  .sem-card {
    padding: 1.2rem 1rem;
  }

  .sem-card .s-value {
    font-size: 1.03rem;
  }

  .sem-about,
  .sem-notice {
    padding: 1rem;
    font-size: 0.98rem;
  }

  .feynman-box {
    gap: 0.75rem;
    padding: 1rem;
  }

  .feynman-box .fb-icon {
    font-size: 1.45rem;
  }

  .feynman-box .fb-body {
    font-size: 0.98rem;
  }

  .sem-section-title {
    font-size: 1.25rem;
    margin-top: 1.7rem;
  }
}

@media (max-width: 640px) {
  .sem-table,
  .sem-table thead,
  .sem-table tbody,
  .sem-table tr,
  .sem-table th,
  .sem-table td {
    display: block;
    width: 100%;
  }

  .sem-table {
    border: 0;
    font-size: 0.98rem;
  }

  .sem-table thead {
    position: absolute;
    width: 1px;
    height: 1px;
    overflow: hidden;
    clip: rect(0 0 0 0);
    white-space: nowrap;
  }

  .sem-table tbody tr {
    margin: 0 0 1rem;
    border: 1px solid #dfe7ee;
    border-radius: 8px;
    overflow: hidden;
    background: #fff;
  }

  .sem-table tbody tr:nth-child(even) td,
  .sem-table tbody tr:hover td {
    background: transparent;
  }

  .sem-table tbody td {
    display: grid;
    grid-template-columns: 5.5rem minmax(0, 1fr);
    align-items: start;
    gap: 0.75rem;
    padding: 0.75rem 0.85rem;
    border-right: 0;
  }

  .sem-table tbody td::before {
    color: #66727d;
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    line-height: 1.4;
  }

  .sem-table tbody td:nth-child(1)::before { content: "Session"; }
  .sem-table tbody td:nth-child(2)::before { content: "Date"; }
  .sem-table tbody td:nth-child(3)::before { content: "Topic"; }
  .sem-table tbody td:nth-child(4)::before { content: "Presenter"; }
  .sem-table tbody td:nth-child(5)::before { content: "Room"; }

  .sem-table td:nth-child(3) {
    min-width: 0;
  }

  .sem-table .num {
    font-size: 1rem;
    font-weight: 700;
    color: #0b4f6c;
  }

  .topic-links {
    gap: 0.35rem;
  }

  .presentation {
    max-width: 100%;
    white-space: normal;
  }
}

@media (max-width: 420px) {
  #main {
    padding-left: 0.7rem;
    padding-right: 0.7rem;
  }

  .sem-hero {
    padding-left: 0.85rem;
    padding-right: 0.85rem;
  }

  .sem-table tbody td {
    grid-template-columns: 4.8rem minmax(0, 1fr);
    gap: 0.55rem;
    padding: 0.7rem;
  }

  .feynman-box {
    display: block;
  }

  .feynman-box .fb-icon {
    margin-bottom: 0.45rem;
  }
}
</style>

<script>
function downloadICS(el) {
  var date      = el.dataset.date;      /* YYYYMMDD */
  var num       = el.dataset.num  || '';
  var title     = el.dataset.title|| 'WTM World Model Seminar';
  var presenter = el.dataset.presenter || '';

  var dtStart = date + "T120000Z";  /* 14:00 CEST = 12:00 UTC */
  var dtEnd   = date + "T140000Z";  /* 16:00 CEST = 14:00 UTC */

  var summary = "WTM World Model Seminar #" + num +
                (title && title !== "TBA" ? " – " + title : "");
  var desc = (presenter ? "Presenter: " + presenter + "\\n" : "") +
             "Join Zoom: https://uni-hamburg.zoom.us/j/62688965566";

  var uid = "wtm-sem-" + num + "-" + date + "@kchu.github.io";

  var lines = [
    "BEGIN:VCALENDAR",
    "VERSION:2.0",
    "PRODID:-//WTM World Model Seminar//kchu.github.io//EN",
    "CALSCALE:GREGORIAN",
    "METHOD:PUBLISH",
    "BEGIN:VEVENT",
    "UID:" + uid,
    "DTSTART:" + dtStart,
    "DTEND:" + dtEnd,
    "SUMMARY:" + summary,
    "DESCRIPTION:" + desc,
    "LOCATION:House of Informatics\\, Bundesstr. 56b\\, 20146 Hamburg (Room 05-627)",
    "URL:https://uni-hamburg.zoom.us/j/62688965566",
    "END:VEVENT",
    "END:VCALENDAR"
  ];

  var blob = new Blob([lines.join("\r\n")], {type: "text/calendar;charset=utf-8"});
  var a = document.createElement("a");
  a.href = URL.createObjectURL(blob);
  a.download = "wtm-seminar-" + (num || "session") + ".ics";
  document.body.appendChild(a);
  a.click();
  document.body.removeChild(a);
}

/* Auto-gray past sessions + fill the "Next Session" card.
   Same date comparison drives both: chips before today are "past",
   the first chip on/after today is the next session.
   NOTE: use block comments only — the site HTML is minified on build
   (newlines stripped), which turns any // comment into a syntax error. */
document.addEventListener("DOMContentLoaded", function () {
  var months = ["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"];
  var wdays  = ["Sun","Mon","Tue","Wed","Thu","Fri","Sat"];

  var today = new Date();
  today.setHours(0, 0, 0, 0);

  var next = null;
  document.querySelectorAll(".date-chip").forEach(function (chip) {
    var d = chip.dataset.date; /* YYYYMMDD */
    if (!d) return;
    var dt = new Date(+d.slice(0,4), +d.slice(4,6) - 1, +d.slice(6,8));
    if (dt < today) {
      chip.classList.add("date-chip-past");
    } else {
      chip.classList.remove("date-chip-past");
      if (!next) next = dt;
    }
  });

  var cal = document.getElementById("cal-next");
  if (cal && next) {
    cal.querySelector(".cal-month").textContent = months[next.getMonth()];
    cal.querySelector(".cal-day").textContent   = next.getDate();
    cal.querySelector(".cal-wday").textContent  = wdays[next.getDay()];
  }
});
</script>

<!-- ═══ HERO ═══ -->
<div class="sem-hero">
  <img src="/images/WTM_WM_Seminar.png" alt="WTM World Model Seminar logo"
       style="width:240px; height:240px; object-fit:contain; border-radius:20px;
              background:rgba(255,255,255,0.12); padding:14px; margin-bottom:1.2rem;">
  <div class="eyebrow">University of Hamburg &nbsp;·&nbsp; Department of Informatics</div>
  <h1>WTM World Model Seminar</h1>
  <p class="tagline">
    A weekly reading and presentation seminar on world models, vision-language-action models, and embodied intelligence — bridging theory and robotics.
  </p>
  <a class="hero-btn" href="https://www.inf.uni-hamburg.de/en/inst/ab/wtm.html" target="_blank">
    Knowledge Technology Group (WTM) ↗
  </a>
</div>

<!-- ═══ INFO CARDS ═══ -->
<div class="sem-cards">

  <div class="sem-card">
    <div class="cal-icon" id="cal-next">
      <div class="cal-month">—</div>
      <div class="cal-day">–</div>
      <div class="cal-wday">Wed</div>
    </div>
    <div class="s-label">Next Session</div>
    <div class="s-value">
      Wednesday<br>
      <small>14:00 – 16:00 CEST</small>
    </div>
  </div>

  <div class="sem-card">
    <div class="s-icon">📍</div>
    <div class="s-label">Where (In-Person)</div>
    <div class="s-value">
      House of Informatics<br>
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
    The <strong>WTM World Model Seminar</strong> is an internal research seminar of the
    <a href="https://www.inf.uni-hamburg.de/en/inst/ab/wtm.html" target="_blank">Knowledge Technology (WTM) group</a>
    at the University of Hamburg. Each session presents and discusses recent advances in world models —
    spanning planning, perception, reinforcement learning, and robotic control. Open to all; join in
    person (Hamburg) or via Zoom.
  </p>
  <p>
    Both <strong>presenting and attending</strong> are encouraged — an open space to exchange ideas,
    discuss ongoing work, and learn from each other.
  </p>

  <div class="feynman-box">
    <div class="fb-icon">💡</div>
    <div class="fb-body">
      <div class="fb-title">In the spirit of the Feynman learning technique</div>
      Explaining a topic to others is one of the best ways to deepen your own understanding. No
      <strong>“perfect” or finished result</strong> needed — bring whatever you're working on:
      <div class="fb-tags">
        <span class="fb-tag">Work-in-progress</span>
        <span class="fb-tag">Preliminary results</span>
        <span class="fb-tag">Paper discussions</span>
        <span class="fb-tag">Technical questions</span>
        <span class="fb-tag">Research challenges</span>
      </div>
    </div>
  </div>

  <p>
    Let's think together, ask questions, and sharpen our ideas. Feel free to forward this invitation to
    anyone interested.
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
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="01" data-date="20260527"
            data-title="World Model for Robot Learning: A Comprehensive Survey"
            data-presenter="Parsa"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">May</div><div class="dc-day">27</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">World Model for Robot Learning: A Comprehensive Survey</div>
        <div class="topic-sub">Hou et al.</div>
        <div class="topic-links">
          <a class="presentation paper" href="https://arxiv.org/abs/2605.00080" target="_blank">Paper</a>
          <a class="presentation" href="/files/WTM_WM_Seminar_Presentation_1.pdf" target="_blank">Slides</a>
        </div>
      </td>
      <td class="Presenter">Parsa</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">02</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="02" data-date="20260603"
            data-title="Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation"
            data-presenter="Mostafa"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jun</div><div class="dc-day">3</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation</div>
        <div class="topic-sub">ByteDance Research</div>
        <div class="topic-links">
          <a class="presentation paper" href="https://gr1-manipulation.github.io/" target="_blank">Paper</a>
          <a class="presentation" href="/files/WTM_WM_Seminar_Presentation_2.pdf" target="_blank">Slides</a>
        </div>
      </td>
      <td class="Presenter">Mostafa</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">03</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="03" data-date="20260610"
            data-title="World Model as Simulator"
            data-presenter="Thomas"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jun</div><div class="dc-day">10</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">World Model as Simulator</div>
        <div class="topic-sub"></div>
        <div class="topic-links">
          <a class="presentation paper" href="https://openaccess.thecvf.com/content/CVPR2026/papers/Tang_DreamSAC_Learning_Hamiltonian_World_Models_via_Symmetry_Exploration_CVPR_2026_paper.pdf" target="_blank">Paper</a>
          <a class="presentation" href="/files/WTM_WM_Seminar_Presentation_3.pdf" target="_blank">Slides</a>
        </div>
      </td>
      <td class="Presenter">Thomas</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">04</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="04" data-date="20260617"
            data-title="Vision-Action Coupling in World Model Policies"
            data-presenter="Kun"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jun</div><div class="dc-day">17</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">Vision-Action Coupling in World Model Policies</div>
        <div class="topic-sub"></div>
        <div class="topic-links">
          <a class="presentation paper" href="https://arxiv.org/abs/2605.00080" target="_blank">Paper</a>
          <a class="presentation" href="/files/WTM_WM_Seminar_Presentation_4.pdf" target="_blank">Slides</a>
        </div>
      </td>
      <td class="Presenter">Kun</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">05</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="05" data-date="20260624"
            data-title="LAPA: Latent Action Pretraining from Videos"
            data-presenter="Parsa"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jun</div><div class="dc-day">24</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">LAPA: Latent Action Pretraining from Videos</div>
        <div class="topic-sub"></div>
        <div class="topic-links">
          <a class="presentation paper" href="https://latentactionpretraining.github.io/" target="_blank">Paper</a>
          <a class="presentation" href="/files/WTM_WM_Seminar_Presentation_5.pdf" target="_blank">Slides</a>
        </div>
      </td>
      <td class="Presenter">Parsa</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">06</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="06" data-date="20260701"
            data-title="Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation"
            data-presenter="Mostafa"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jul</div><div class="dc-day">1</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation</div>
        <div class="topic-sub"></div>
        <div class="topic-links">
          <a class="presentation paper" href="https://nimolty.github.io/Seer/" target="_blank">Paper</a>
          <a class="presentation" href="/files/WTM_WM_Seminar_Presentation_6.pdf" target="_blank">Slides</a>
        </div>
      </td>
      <td class="Presenter">Mostafa</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">07</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="07" data-date="20260708"
            data-title="TBA"
            data-presenter="TBA"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jul</div><div class="dc-day">8</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">TBA</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">Connor</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">08</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="08" data-date="20260715"
            data-title="TBA"
            data-presenter="TBA"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jul</div><div class="dc-day">15</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">TBA</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">Asihati</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">09</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="08" data-date="20260722"
            data-title="TBA"
            data-presenter="TBA"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jul</div><div class="dc-day">22</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">TBA</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">TBA</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <tr>
      <td class="num">10</td>
      <td><a class="date-chip" href="#" title="Add to calendar"
            data-num="08" data-date="20260729"
            data-title="TBA"
            data-presenter="TBA"
            onclick="downloadICS(this);return false;">
        <div class="dc-month">Jul</div><div class="dc-day">29</div>
        <div class="dc-wday">Wed</div><div class="dc-add">+ Cal</div>
      </a></td>
      <td>
        <div class="topic-title">TBA</div>
        <div class="topic-sub"></div>
      </td>
      <td class="Presenter">TBA</td>
      <td><span class="badge badge-room">05-627</span></td>
    </tr>

    <!-- ── Add more rows by copying the block above ── -->

  </tbody>
</table>

<div class="sem-notice">
  📬 <strong>Want to present?</strong> &nbsp;Please contact <a href="mailto:kun.chu@uni-hamburg.de">Kun</a> to sign up for a slot.<br>
</div>
