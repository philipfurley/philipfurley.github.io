---
layout: page
title: media coverage
permalink: /media/
nav: true
nav_order: 4
---

<style>
.media-section {
  margin-top: 2rem;
  margin-bottom: 2.5rem;
}

.media-section-title {
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--global-theme-color, #007bff);
  padding-bottom: 0.5rem;
  margin-bottom: 1.25rem;
  border-bottom: 2px solid var(--global-divider-color, #e2e8f0);
  display: flex;
  align-items: center;
  gap: 10px;
}

.media-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 1.25rem;
}

.media-card {
  background: var(--global-card-bg, #fcfcfc);
  border: 1px solid var(--global-divider-color, #e9ecef);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.03);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: flex;
  flex-direction: column;
  text-decoration: none !important;
  color: inherit !important;
}

.media-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
}

.media-thumb-container {
  width: 100%;
  height: 140px;
  background-color: #f1f5f9;
  position: relative;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

.media-thumb {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.media-thumb-placeholder {
  font-size: 2.5rem;
  color: var(--global-theme-color, #007bff);
  opacity: 0.4;
}

.media-body {
  padding: 1rem;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

.media-outlet {
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  color: var(--global-theme-color, #007bff);
  margin-bottom: 0.3rem;
}

.media-title {
  font-size: 0.95rem;
  font-weight: 600;
  line-height: 1.35;
  margin-bottom: 0.5rem;
  color: var(--global-text-color, #1a202c);
}

.media-description {
  font-size: 0.825rem;
  line-height: 1.45;
  color: var(--global-text-color-light, #4a5568);
  margin: 0;
  flex-grow: 1;
}

html[data-theme='dark'] .media-card {
  background: #2c2c2e !important;
  border-color: #3a3a3c !important;
}

html[data-theme='dark'] .media-thumb-container {
  background-color: #1c1c1e;
}

html[data-theme='dark'] .media-title {
  color: #f4f4f5 !important;
}

html[data-theme='dark'] .media-description {
  color: #a1a1aa !important;
}
</style>

<!-- SECTION 1: BODY LANGUAGE & NONVERBAL CUES -->
<div class="media-section">
  <div class="media-section-title">
    <i class="fa-solid fa-user-group"></i> Body Language &amp; Nonverbal Behavior
  </div>
  <div class="media-grid">

    <a href="https://www.theguardian.com" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-bullseye media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">The Guardian</div>
        <div class="media-title">Poker Faces in Darts &amp; Nonverbal Signals</div>
        <p class="media-description">Coverage of research examining body language, facial expressions, and nonverbal cues under high pressure.</p>
      </div>
    </a>

    <a href="https://www.spiegel.de" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-whistle media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">Der Spiegel</div>
        <div class="media-title">Referee Body Language &amp; Match Control</div>
        <p class="media-description">Analysis of empirical findings on how match officials' body language influences player perception.</p>
      </div>
    </a>

    <a href="https://www.dshs-koeln.de" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-podcast media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">DSHS Podcast • 2026</div>
        <div class="media-title">Performance Under Pressure</div>
        <p class="media-description">Podcast feature exploring executive control, emotional expression, and nonverbal behavior in sport.</p>
      </div>
    </a>

  </div>
</div>

<!-- SECTION 2: PENALTY SHOOTOUT PSYCHOLOGY -->
<div class="media-section">
  <div class="media-section-title">
    <i class="fa-solid fa-futbol"></i> Penalty Shootout Psychology
  </div>
  <div class="media-grid">

    <a href="https://www.huffpost.com" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-stopwatch media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">HuffPost</div>
        <div class="media-title">The Science of Penalty Kicks</div>
        <p class="media-description">Exploring gaze behavior, visual attention, and body posture during high-stakes penalty shootouts.</p>
      </div>
    </a>

  </div>
</div>

<!-- SECTION 3: COLOR PSYCHOLOGY IN SPORTS -->
<div class="media-section">
  <div class="media-section-title">
    <i class="fa-solid fa-palette"></i> Color Psychology in Sports
  </div>
  <div class="media-grid">

    <a href="https://www.theguardian.com" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-shirt media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">The Guardian</div>
        <div class="media-title">Color Effects on Performance &amp; Perception</div>
        <p class="media-description">Reporting on how uniform colors influence referee decisions, competitor dominance, and perceptual bias.</p>
      </div>
    </a>

  </div>
</div>

<!-- SECTION 4: AWARDS & RECOGNITION -->
<div class="media-section">
  <div class="media-section-title">
    <i class="fa-solid fa-trophy"></i> Awards &amp; Scientific Recognition
  </div>
  <div class="media-grid">

    <a href="https://www.sport1.de" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-award media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">SPORT1 • 2023</div>
        <div class="media-title">DOSB Science Award Winner</div>
        <p class="media-description">National sports reporting on receiving the top honor in German sport science.</p>
      </div>
    </a>

    <a href="https://www.jungewelt.de" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-newspaper media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">junge Welt • 2023</div>
        <div class="media-title">Excellence in Sport Psychology</div>
        <p class="media-description">Coverage highlighting award-winning research on decision-making and cognitive load.</p>
      </div>
    </a>

  </div>
</div>
