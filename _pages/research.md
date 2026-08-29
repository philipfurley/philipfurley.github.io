---
layout: page
title: research
permalink: /research/
description: Overview of primary research strands, theoretical frameworks, and core contributions.
nav: true
nav_order: 2
---

<style>
/* Grid Layout: Sidebar + Main Content */
.research-container {
  display: grid;
  grid-template-columns: 220px 1fr;
  gap: 3rem;
  align-items: start;
}

/* Sticky Left Navigation Sidebar */
.research-sidebar {
  position: sticky;
  top: 100px;
  background: var(--global-bg-color, #ffffff);
  padding: 1.25rem 1rem;
  border-left: 3px solid var(--global-theme-color, #007bff);
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}

.research-sidebar h4 {
  font-size: 0.85rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.8px;
  margin-bottom: 1rem;
  color: var(--global-text-color, #333);
}

.research-sidebar ul {
  list-style: none !important;
  padding: 0 !important;
  margin: 0 !important;
}

.research-sidebar li {
  margin-bottom: 0.65rem;
}

.research-sidebar a {
  display: block;
  font-size: 0.82rem;
  line-height: 1.35;
  color: var(--global-text-color-light, #666);
  text-decoration: none;
  transition: color 0.2s ease, font-weight 0.2s ease;
}

.research-sidebar a:hover {
  color: var(--global-theme-color, #007bff);
  font-weight: 600;
}

/* Section Card Framing for Research Strands */
.strand-card {
  background: var(--global-card-bg, #fcfcfc);
  border: 1px solid var(--global-divider-color, #e9ecef);
  border-radius: 8px;
  padding: 1.75rem;
  margin-bottom: 2.5rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.02);
}

.strand-card h3 {
  font-size: 1.35rem;
  font-weight: 700;
  letter-spacing: -0.3px;
  color: var(--global-theme-color, #007bff);
  margin-bottom: 1.25rem;
  line-height: 1.3;
}

.strand-card .strand-img {
  width: 100%;
  max-height: 380px;
  object-fit: cover;
  border-radius: 6px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
  margin-bottom: 1.25rem;
}

.strand-card .strand-lead {
  font-size: 0.95rem;
  line-height: 1.6;
  color: var(--global-text-color, #222);
  margin-bottom: 1.5rem;
}

.strand-card .section-divider {
  border: 0;
  height: 1px;
  background: var(--global-divider-color, #e0e0e0);
  margin: 1.5rem 0 1rem 0;
}

.strand-card h4.pub-heading {
  font-size: 0.78rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.8px;
  color: var(--global-text-color-light, #777);
  margin-bottom: 0.75rem;
}

/* Compact Publications Styles */
.compact-research h2.bibliography {
  display: none !important;
}

.compact-research ol.bibliography {
  list-style-type: none !important;
  padding-left: 0 !important;
  margin-left: 0 !important;
}

.compact-research ol.bibliography > li {
  list-style: none !important;
  padding-left: 0 !important;
  font-size: 0.78rem !important;
  line-height: 1.35 !important;
  margin-bottom: 0.6rem !important;
  padding-bottom: 0.5rem !important;
  border-bottom: 1px dashed var(--global-divider-color, #eee);
}

.compact-research ol.bibliography > li:last-child {
  border-bottom: none;
}

/* Collapsible Publications Styling */
.pub-wrapper ol.bibliography > li:nth-child(n+4) {
  display: none;
}

.pub-wrapper.expanded ol.bibliography > li {
  display: list-item !important;
}

.pub-toggle-btn {
  background: none;
  border: none;
  color: var(--global-theme-color, #007bff);
  font-size: 0.78rem;
  font-weight: 600;
  cursor: pointer;
  padding: 4px 0;
  margin-top: 0.25rem;
  display: inline-flex;
  align-items: center;
  gap: 4px;
}

.pub-toggle-btn:hover {
  text-decoration: underline;
}

/* Hide "Chapter" / Type Badges (.abbr) */
.compact-research .abbr {
  display: none !important;
}

/* Compact PDF Buttons */
.compact-research .links a.btn:not([href*=".pdf"]) {
  display: none !important;
}

.compact-research .links a.btn[href*=".pdf"] {
  font-size: 0.68rem !important;
  padding: 1px 6px !important;
  border-radius: 3px !important;
  text-transform: uppercase !important;
  letter-spacing: 0.5px !important;
}

.compact-research .title {
  font-size: 0.82rem !important;
  font-weight: 600 !important;
  color: var(--global-text-color, #222) !important;
}

.compact-research .author, 
.compact-research .periodical {
  font-size: 0.75rem !important;
  color: var(--global-text-color-light, #555) !important;
}

/* Responsive adjustment for small screens */
@media (max-width: 768px) {
  .research-container {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  .research-sidebar {
    position: relative;
    top: 0;
    border-left: none;
    border-bottom: 3px solid var(--global-theme-color, #007bff);
    margin-bottom: 1.5rem;
  }
}

/* Smooth Scrolling */
html {
  scroll-behavior: smooth;
}
</style>

<div class="research-container">

  <!-- Left Navigation Sidebar -->
  <nav class="research-sidebar">
    <h4>Research Strands</h4>
    <ul>
      <li><a href="#strand-1">1. Nonverbal Behavior</a></li>
      <li><a href="#strand-2">2. Executive Functions</a></li>
      <li><a href="#strand-3">3. Match Analysis</a></li>
      <li><a href="#strand-4">4. Metascience & Evolution</a></li>
      <li><a href="#strand-5">5. Surf Science</a></li>
    </ul>
  </nav>

  <!-- Main Content Area -->
  <div class="compact-research">

    <section id="strand-1" class="strand-card">
      <h3>1. Nonverbal Behavior, Emotion & Social Perception in Sport</h3>
      <img src="{{ '/assets/img/nvbresearch.jpg' | relative_url }}" alt="Nonverbal Behavior in Sport" class="strand-img">
      <div class="strand-lead">
        <p>This research strand investigates how human emotions and nonverbal signals are communicated, perceived, and utilized in high-pressure athletic environments. Utilizing thin-slice methodology, 3D pose analysis, and Facial Action Coding (FACS), this work explores how body language, facial expressions, and emotional displays influence expectancy of success, impression formation, and strategic interactions between opponents, teammates, and coaches.</p>
        <p>A key objective of this domain is to bridge basic social psychology and evolutionary theory with real-world application, demonstrating how nonverbal cues reveal underlying cognitive states (such as ego depletion or confidence) and directly shape athletic performance across sports like soccer, darts, basketball, and tennis.</p>
      </div>
      
      <hr class="section-divider">
      <h4 class="pub-heading">Selected Strand Publications</h4>
      <div class="pub-wrapper">
        {% bibliography --query @*[category=nonverbal]* %}
        <button class="pub-toggle-btn" onclick="togglePubs(this)">+ Show all publications</button>
      </div>
    </section>

    <section id="strand-2" class="strand-card">
      <h3>2. Executive Functions, Attention & Cognitive Load</h3>
      <img src="{{ '/assets/img/attentionresearch.jpg' | relative_url }}" alt="Executive Functions and Attention" class="strand-img">
      <div class="strand-lead">
        <p>This research line explores the cognitive architecture underlying elite human movement and tactical decision-making. Focusing on working memory capacity, visual attention, inattentional blindness, and dual-process models, the goal is to unravel how athletes process complex environmental stimuli while maintaining self-control under fatigue and cognitive load.</p>
        <p>Additionally, this strand examines the boundaries of cognitive transfer and ego-depletion, critically evaluating how executive control mechanisms function in high-pressure performance contexts and driving rigorous methodological standards for assessing executive function across sport science.</p>
      </div>

      <hr class="section-divider">
      <h4 class="pub-heading">Selected Strand Publications</h4>
      <div class="pub-wrapper">
        {% bibliography --query @*[category=cognitive]* %}
        <button class="pub-toggle-btn" onclick="togglePubs(this)">+ Show all publications</button>
      </div>
    </section>

    <section id="strand-3" class="strand-card">
      <h3>3. Sport Science, Match Analyses & Penalty Kicks</h3>
      <img src="{{ '/assets/img/penaltyresearch.jpg' | relative_url }}" alt="Match Analysis and Penalty Kicks" class="strand-img">
      <div class="strand-lead">
        <p>Focused on elite performance analysis, this research strand applies systematic video-notational methods, spatial analytics, and psychological profiling to understand decision-making under high stakes. Major areas of inquiry include the mechanical and psychological determinants of soccer penalty kicks, home advantage phenomena, and the objectivity of match analysis data used by elite coaching staff.</p>
        <p>By evaluating parameters such as visuomotor calibration, pressure, and perceptual strategies in sports like soccer, tennis, and darts, this work bridges match data analytics with actionable insights for talent development and opponent preparation.</p>
      </div>

      <hr class="section-divider">
      <h4 class="pub-heading">Selected Strand Publications</h4>
      <div class="pub-wrapper">
        {% bibliography --query @*[category=match_analysis]* %}
        <button class="pub-toggle-btn" onclick="togglePubs(this)">+ Show all publications</button>
      </div>
    </section>

    <section id="strand-4" class="strand-card">
      <h3>4. Evolutionary Perspectives, Biocultural Models & Metascience</h3>
      <img src="{{ '/assets/img/evolutionresearch.jpg' | relative_url }}" alt="Evolutionary Perspectives and Metascience" class="strand-img">
      <div class="strand-lead">
        <p>This interdisciplinary line uses evolutionary behavioral science to understand modern athletic competition as a window into human nature, physical play, and competitive signaling. Topics range from biocultural frameworks of play to evolutionary hypotheses explaining home ground territoriality and relative age effects in talent identification.</p>
        <p>Parallel to evolutionary theory, this strand emphasizes metascience and Open Science practices within sport psychology—critically examining replication validity (e.g., color effects and aggression), statistical power, sample sizes, and the relative utility of systematic versus narrative review formats.</p>
      </div>

      <hr class="section-divider">
      <h4 class="pub-heading">Selected Strand Publications</h4>
      <div class="pub-wrapper">
        {% bibliography --query @*[category=evolutionary]* %}
        <button class="pub-toggle-btn" onclick="togglePubs(this)">+ Show all publications</button>
      </div>
    </section>

    <section id="strand-5" class="strand-card">
      <h3>5. Surf Science & Action Sports Psychology</h3>
      <img src="{{ '/assets/img/surfresearch.jpg' | relative_url }}" alt="Surf Science and Action Sports" class="strand-img">
      <div class="strand-lead">
        <p>Investigating the psychological and physiological aspects of surfing and adaptive action sports, this strand explores perceptual-cognitive expertise, motor asymmetry, and performance judging. Specific topics include laterality effects (Goofy vs. Regular stance), the influence of post-performance expressions ("claiming") on wave scoring, and adaptation patterns in Para surfing.</p>
      </div>

      <hr class="section-divider">
      <h4 class="pub-heading">Selected Strand Publications</h4>
      <div class="pub-wrapper">
        {% bibliography --query @*[category=surf]* %}
        <button class="pub-toggle-btn" onclick="togglePubs(this)">+ Show all publications</button>
      </div>
    </section>

  </div>
</div>

<script>
function togglePubs(button) {
  const wrapper = button.parentElement;
  const isExpanded = wrapper.classList.toggle('expanded');
  button.textContent = isExpanded ? '– Show fewer publications' : '+ Show all publications';
}
</script>
