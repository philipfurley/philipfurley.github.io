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

<!-- SECTION 1: BODY LANGUAGE & NONVERBAL BEHAVIOR -->
<div class="media-section">
  <div class="media-section-title">
    <i class="fa-solid fa-user-group"></i> Body Language &amp; Nonverbal Behavior
  </div>
  <div class="media-grid">

    <a href="https://www.theguardian.com/sport/2025/oct/13/luke-littler-poker-face-key-to-dominance-darts" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <img src="https://img.logo.dev/theguardian.com?token=pk_X1-Y3111T-29_7-1111111" alt="The Guardian" class="media-thumb" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
        <i class="fa-solid fa-bullseye media-thumb-placeholder" style="display:none;"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">The Guardian</div>
        <div class="media-title">Luke Littler's Poker Face May Be the Key to His Dominance in Darts</div>
        <p class="media-description">Feature on empirical research using the Facial Action Coding System (FACS) to analyze nonverbal cues and tension prior to high-stakes throws.</p>
      </div>
    </a>

    <a href="https://www.youtube.com/watch?v=1Cf2xoYlSCY" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <img src="https://img.youtube.com/vi/1Cf2xoYlSCY/hqdefault.jpg" alt="DSHS Podcast" class="media-thumb" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
        <i class="fa-solid fa-podcast media-thumb-placeholder" style="display:none;"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">DSHS Wissenschaftspodcast</div>
        <div class="media-title">#54 Game Gestures &amp; Nonverbal Communication in Sport</div>
        <p class="media-description">In-depth podcast episode on post-error gestures, emotion regulation, and executive control under high pressure.</p>
      </div>
    </a>

    <a href="https://scf33298fe03e3221.jimcontent.com/download/version/1627393823/module/12781310199/name/Pr%C3%A4sentation%20Pers%C3%B6nlichkeit%20Kommunikation.pdf" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-whistle media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">Sports Science Press</div>
        <div class="media-title">Referee Body Language and Nonverbal Signals</div>
        <p class="media-description">Coverage examining how referee body language and nonverbal cues shape player perception and match authority.</p>
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

    <a href="https://fis.dshs-koeln.de/de/clippings/warum-machen-das-so-wenige-ein-elfmeter-in-diese-ecke-geht-fast-i/" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-stopwatch media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">Media Feature</div>
        <div class="media-title">Penaltys sind Kopfsache: Körpersignale vor dem Schuss</div>
        <p class="media-description">Analysis of visual attention, hastening and hiding behavior, and pressure coping mechanisms in penalty shootouts.</p>
      </div>
    </a>

    <a href="https://idw-online.de/de/news746969" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <img src="https://img.logo.dev/idw-online.de?token=pk_X1-Y3111T-29_7-1111111" alt="idw-online" class="media-thumb" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
        <i class="fa-solid fa-newspaper media-thumb-placeholder" style="display:none;"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">idw Nachrichten</div>
        <div class="media-title">Der Mythos vom englischen Elfmeterfluch</div>
        <p class="media-description">Scientific press feature analyzing data across European leagues, World Cups, and European Championships.</p>
      </div>
    </a>

    <a href="https://www.nature.com/articles/s41598-020-63889-6" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <img src="https://img.logo.dev/nature.com?token=pk_X1-Y3111T-29_7-1111111" alt="Nature" class="media-thumb" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
        <i class="fa-solid fa-flask media-thumb-placeholder" style="display:none;"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">Scientific Reports (Nature)</div>
        <div class="media-title">English Football Players Are Not as Bad at Kicking Penalties as Assumed</div>
        <p class="media-description">Empirical evaluation of penalty kick performance metrics across major international tournaments.</p>
      </div>
    </a>

  </div>
</div>

<!-- SECTION 3: AWARDS & RECOGNITION -->
<div class="media-section">
  <div class="media-section-title">
    <i class="fa-solid fa-trophy"></i> Awards &amp; Scientific Recognition
  </div>
  <div class="media-grid">

    <a href="https://www.sport1.de/news/olympia/2023/02/dosb-wissenschaftspreis-an-philip-furley-verliehen" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <img src="https://img.logo.dev/sport1.de?token=pk_X1-Y3111T-29_7-1111111" alt="SPORT1" class="media-thumb" onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
        <i class="fa-solid fa-award media-thumb-placeholder" style="display:none;"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">SPORT1 • 2023</div>
        <div class="media-title">DOSB-Wissenschaftspreis an Philip Furley verliehen</div>
        <p class="media-description">National reporting on winning 1st place in the DOSB Science Award for outstanding research in sport science.</p>
      </div>
    </a>

    <a href="https://fis.dshs-koeln.de/de/persons/philip-furley/" target="_blank" rel="noopener noreferrer" class="media-card">
      <div class="media-thumb-container">
        <i class="fa-solid fa-graduation-cap media-thumb-placeholder"></i>
      </div>
      <div class="media-body">
        <div class="media-outlet">DSHS Academic Profile</div>
        <div class="media-title">Toyota &amp; DOSB Science Awards Distinction</div>
        <p class="media-description">Official summary of honors, DFG grants, and nonverbal behavior research projects at German Sport University Cologne.</p>
      </div>
    </a>

  </div>
</div>
