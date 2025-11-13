---
layout: page
title: Home
id: home
permalink: /
---

<div class="home-hero">
  <div class="home-hero__eyebrow">
    <span class="dot"></span>
    Playing long-term games with small, sharp teams
  </div>

  <h1 class="home-hero__title">Hi, I’m CJ. I buy, build, and scale service businesses.</h1>

  <p class="home-hero__subtitle">
    I’m <strong>CJ Onyekwelu</strong>, a CFO and operator working at the intersection of
    <strong>healthcare, services, and software</strong>. I design systems, models, and teams that turn
    messy operations into durable, cash-generating companies.
  </p>

  <div class="home-hero__actions">
    <a class="btn btn-primary" href="/start-here">Start here</a>
    <a class="btn btn-ghost" href="/about">Learn more about me</a>
  </div>

  <div class="home-hero__meta">
    <span>Based in Alberta &amp; New York</span>
    <span>Operator-first, acquisition-minded</span>
  </div>
</div>

<div class="home-grid">
  <section class="home-card">
    <h2>What I work on</h2>
    <ul>
      <li><strong>Operating &amp; CFO work</strong> – building financial systems, budgets, and dashboards for healthcare and service businesses.</li>
      <li><strong>Ventures &amp; experiments</strong> – VR training concepts, skincare &amp; wellness (Piel Skincare), and small-business acquisitions.</li>
      <li><strong>Writing &amp; thinking</strong> – notes on systems, incentives, and compounding capital, skills, and reputation.</li>
    </ul>
    <p class="home-card__link">
      → See more in [[Work]] and [[Writing]]
    </p>
  </section>

  <section class="home-card">
    <div class="home-card__header">
      <h2>Current focus</h2>
      <span class="badge">Q4 2025</span>
    </div>
    <ul class="meta-list">
      <li>
        <span>Primary</span>
        <span>CFO work &amp; systems for healthcare and homecare.</span>
      </li>
      <li>
        <span>Building</span>
        <span>Exploring VR training &amp; small service-business acquisitions.</span>
      </li>
      <li>
        <span>Personal</span>
        <span>Strength &amp; conditioning; systematizing health like any other operation.</span>
      </li>
    </ul>
    <p class="home-card__link">
      → See [[Now]] for what I’m focused on right now
    </p>
  </section>

  <section class="home-card">
    <h2>Start your exploration</h2>
    <p>
      This site is a working notebook, not a polished magazine. If you’re new here, these are the best entry points:
    </p>
    <ul>
      <li>[[Start here]] – how this site is structured and where to go first.</li>
      <li>[[Operator notes]] – systems, processes, and how I think about running organizations.</li>
      <li>[[Investment & deal notes]] – theses, frameworks, and acquisition ideas.</li>
      <li>[[Health & training systems]] – treating fitness and body composition as a systems problem.</li>
    </ul>
  </section>
</div>

---

<style>
  .wrapper {
    max-width: 52rem;
  }

  .home-hero {
    padding: 2.5rem 2rem 2rem;
    margin-bottom: 2rem;
    border-radius: 1.25rem;
    background: radial-gradient(circle at 0% 0%, rgba(56,189,248,0.12), transparent 55%),
                radial-gradient(circle at 100% 0%, rgba(59,130,246,0.16), transparent 55%),
                #050816;
    color: #e5e7eb;
    border: 1px solid rgba(148,163,184,0.35);
  }

  .home-hero__eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.15rem 0.7rem;
    border-radius: 999px;
    font-size: 0.7rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    background: rgba(15,23,42,0.85);
    border: 1px solid rgba(148,163,184,0.6);
    color: #9ca3af;
    margin-bottom: 0.9rem;
  }

  .home-hero__eyebrow .dot {
    width: 0.4rem;
    height: 0.4rem;
    border-radius: 999px;
    background: #22c55e;
    box-shadow: 0 0 0 4px rgba(34,197,94,0.25);
  }

  .home-hero__title {
    margin: 0 0 0.5rem;
    font-size: 1.9rem;
    line-height: 1.2;
    letter-spacing: -0.03em;
  }

  @media (min-width: 768px) {
    .home-hero__title {
      font-size: 2.15rem;
    }
  }

  .home-hero__subtitle {
    margin: 0 0 1.25rem;
    font-size: 0.95rem;
    color: #cbd5f5;
  }

  .home-hero__actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin-bottom: 0.75rem;
  }

  .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.55rem 1.1rem;
    font-size: 0.85rem;
    border-radius: 999px;
    border: 1px solid transparent;
    text-decoration: none;
    cursor: pointer;
    white-space: nowrap;
    transition: background 0.15s ease, border-color 0.15s ease, transform 0.1s ease;
  }

  .btn-primary {
    background: radial-gradient(circle at 0% 0%, #38bdf8, #0ea5e9);
    color: #020617;
    box-shadow: 0 8px 22px rgba(56,189,248,0.55);
  }

  .btn-primary:hover {
    transform: translateY(-1px);
    box-shadow: 0 12px 28px rgba(56,189,248,0.65);
  }

  .btn-ghost {
    background: rgba(15,23,42,0.95);
    color: #e5e7eb;
    border-color: rgba(148,163,184,0.6);
  }

  .btn-ghost:hover {
    background: rgba(15,23,42,1);
    border-color: rgba(209,213,219,0.9);
    transform: translateY(-1px);
  }

  .home-hero__meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin-top: 0.25rem;
    font-size: 0.75rem;
    color: #9ca3af;
  }

  .home-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1.2rem;
  }

  @media (min-width: 900px) {
    .home-grid {
      grid-template-columns: 1.1fr 1fr;
    }
  }

  .home-card {
    background: #0b1120;
    border-radius: 0.85rem;
    padding: 1.1rem 1.2rem 1rem;
    border: 1px solid #111827;
  }

  .home-card h2 {
    margin-top: 0;
    margin-bottom: 0.5rem;
    font-size: 1rem;
  }

  .home-card p {
    margin-top: 0.2rem;
    margin-bottom: 0.6rem;
  }

  .home-card ul {
    padding-left: 1.1rem;
    margin-top: 0.1rem;
    margin-bottom: 0.4rem;
  }

  .home-card__header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 0.5rem;
    margin-bottom: 0.4rem;
  }

  .badge {
    font-size: 0.7rem;
    padding: 0.15rem 0.55rem;
    border-radius: 999px;
    border: 1px solid rgba(56,189,248,0.6);
    color: #bae6fd;
    background: rgba(15,23,42,0.9);
    white-space: nowrap;
  }

  .meta-list {
    list-style: none;
    padding-left: 0;
  }

  .meta-list li {
    display: flex;
    flex-direction: column;
    gap: 0.15rem;
    padding: 0.3rem 0;
    border-bottom: 1px dashed rgba(55,65,81,0.7);
    font-size: 0.85rem;
  }

  .meta-list li:last-child {
    border-bottom: none;
  }

  .meta-list li span:first-child {
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: #9ca3af;
  }

  .meta-list li span:last-child {
    color: #e5e7eb;
  }

  .home-card__link {
    font-size: 0.85rem;
    margin-top: 0.35rem;
    color: #93c5fd;
  }
</style>
