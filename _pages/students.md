---
layout: page
title: students
permalink: /students/
description: Information for prospective Bachelor's, Master's, and PhD students seeking research supervision.
nav: true
nav_order: 3
---

<style>
/* Page Layout Styling */
.students-container {
  max-width: 900px;
  margin: 0 auto;
}

/* Callout Lead Banner */
.students-lead-box {
  background: var(--global-card-bg, #fcfcfc);
  border-left: 4px solid var(--global-theme-color, #007bff);
  border-radius: 6px;
  padding: 1.5rem 1.75rem;
  margin-bottom: 2.5rem;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.03);
}

.students-lead-box p {
  font-size: 1rem;
  line-height: 1.65;
  color: var(--global-text-color, #222);
  margin: 0;
}

/* Feature Section Card */
.student-card {
  background: var(--global-card-bg, #fcfcfc);
  border: 1px solid var(--global-divider-color, #e9ecef);
  border-radius: 8px;
  padding: 2rem;
  margin-bottom: 2.5rem;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.02);
}

.student-card h3 {
  font-size: 1.35rem;
  font-weight: 700;
  color: var(--global-theme-color, #007bff);
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  gap: 10px;
}

/* Fully Displayed Image Frame */
.student-card .card-img-container {
  width: 100%;
  background: var(--global-hover-bg, #f8f9fa);
  border-radius: 6px;
  padding: 0.5rem;
  margin-bottom: 1.5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}

.student-card .card-img {
  width: 100%;
  height: auto;
  max-height: 480px;
  object-fit: contain; /* Ensures complete image is visible without cropping */
  border-radius: 4px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.06);
}

.student-card .card-text {
  font-size: 0.95rem;
  line-height: 1.65;
  color: var(--global-text-color, #222);
}

.student-card ul {
  margin-top: 0.75rem;
  margin-bottom: 1.25rem;
  padding-left: 1.25rem;
}

.student-card li {
  font-size: 0.92rem;
  line-height: 1.6;
  margin-bottom: 0.5rem;
  color: var(--global-text-color, #333);
}

/* Special Focus Box for PhD Candidates */
.phd-card {
  border: 2px dashed var(--global-theme-color, #007bff);
  background: var(--global-hover-bg, rgba(0, 123, 255, 0.02));
}

.contact-callout {
  background: var(--global-card-bg, #f1f5f9);
  border-radius: 6px;
  padding: 1.25rem;
  margin-top: 1.25rem;
  font-size: 0.9rem;
  line-height: 1.5;
}

/* Neat Contact Info Box */
.contact-details-box {
  background: var(--global-hover-bg, rgba(0, 123, 255, 0.04));
  border: 1px solid var(--global-divider-color, #e2e8f0);
  border-radius: 6px;
  padding: 1.25rem;
  margin-top: 1.5rem;
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}

.contact-detail-item {
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 0.95rem;
  font-weight: 500;
  color: var(--global-text-color, #222);
}

.contact-detail-item i {
  font-size: 1.1rem;
  color: var(--global-theme-color, #007bff);
  width: 20px;
  text-align: center;
}

.contact-detail-item a {
  color: var(--global-theme-color, #007bff);
  text-decoration: none;
  font-weight: 600;
}

.contact-detail-item a:hover {
  text-decoration: underline;
}

/* Dark Mode Overrides */
html[data-theme='dark'] .students-lead-box,
html[data-theme='dark'] .student-card,
html[data-theme='dark'] .contact-callout,
html[data-theme='dark'] .contact-details-box {
  background: #2c2c2e !important;
  border-color: #3a3a3c !important;
}

html[data-theme='dark'] .student-card .card-img-container {
  background: #1c1c1e !important;
}

html[data-theme='dark'] .students-lead-box {
  border-left: 4px solid var(--global-theme-color, #007bff) !important;
}

html[data-theme='dark'] .phd-card {
  border: 2px dashed var(--global-theme-color, #007bff) !important;
}

html[data-theme='dark'] .student-card h3,
html[data-theme='dark'] .card-text,
html[data-theme='dark'] li,
html[data-theme='dark'] .contact-detail-item,
html[data-theme='dark'] .students-lead-box p {
  color: #ffffff !important;
}
</style>

<div class="students-container">

  <!-- Intro Lead Banner -->
  <div class="students-lead-box">
    <p>
      Are you passionate about psychological science, human movement, and performance under pressure? I regularly supervise high-quality <strong>Bachelor's (BA)</strong>, <strong>Master's (MA)</strong>, and <strong>Doctoral (PhD)</strong> theses. Whether you want to collect empirical video data, conduct thin-slice experiments, or apply advanced behavioral analysis, explore the research pathways below.
    </p>
  </div>

  <!-- MAIN SUPERVISION FOCUS: STRAND 1 (BA & MA) -->
  <section class="student-card">
    <h3>
      <i class="fa-solid fa-fire"></i> Primary Thesis Topic: Nonverbal Behavior, Emotion &amp; Social Perception
    </h3>
    
    <div class="card-img-container">
      <img src="{{ '/assets/img/nvbresearch.jpg' | relative_url }}" alt="Nonverbal Behavior in Sport Research" class="card-img">
    </div>

    <div class="card-text">
      <p>
        The primary focus for student supervision revolves around <strong>Nonverbal Behavior, Emotion &amp; Social Perception in High-Pressure Sports</strong>. How do athletes communicate confidence or anxiety without saying a word? Can an opponent or referee decode hidden emotional states from a split-second movement?
      </p>
      <p>
        If you write your thesis in this strand, you will get hands-on experience with cutting-edge psychological and motion analysis techniques. Typical project areas include:
      </p>

      <ul>
        <li><strong>Thin-Slice Methodology:</strong> Testing how observers form rapid impressions of success, dominance, or ego depletion from brief video clips.</li>
        <li><strong>Facial Action Coding System (FACS):</strong> Analyzing micro-expressions of pride, shame, and emotional suppression in high-stakes competition.</li>
        <li><strong>3D Pose &amp; Motion Analysis:</strong> Decoding subtle postural indicators and biomechanical markers of performance anxiety.</li>
        <li><strong>Applied Decision-Making:</strong> Investigating nonverbal interactions between penalty takers and goalkeepers, players and referees, or coaches and athletes across sports like soccer, tennis, basketball, and darts.</li>
      </ul>

      <p>
        <em>Ideal candidates for this strand should have a keen interest in experimental design, quantitative statistical analysis, and behavioral observation.</em>
      </p>
    </div>
  </section>

  <!-- SECONDARY TOPICS: BA & MA -->
  <section class="student-card">
    <h3>
      <i class="fa-solid fa-lightbulb"></i> Alternative BA &amp; MA Thesis Options
    </h3>
    <div class="card-text">
      <p>
        While nonverbal behavior is our primary supervision line, I occasionally accept exceptional Bachelor's and Master's students for alternative project formats:
      </p>
      <ul>
        <li><strong>Broader Research Strands:</strong> Selected topics in executive functions, match analysis, evolutionary sports psychology, or surf science.</li>
        <li><strong>Self-Chosen Topics &amp; Applied PE Research:</strong> Have a specific idea? I welcome self-proposed projects—particularly applied empirical topics relevant to prospective Physical Education (PE / Lehramt) teachers and school sports.</li>
      </ul>
    </div>
  </section>

  <!-- PhD CANDIDATES SECTION -->
  <section class="student-card phd-card">
    <h3>
      <i class="fa-solid fa-graduation-cap"></i> Prospective PhD Candidates
    </h3>
    <div class="card-text">
      <p>
        I welcome inquiries from highly qualified prospective doctoral students looking to conduct cutting-edge PhD research. Doctoral projects are embedded exclusively within our primary research strand:
      </p>
      <p>
        <strong>Focus:</strong> <em>Nonverbal Behavior, Emotional Expression &amp; Social Perception in Competitive Environments.</em>
      </p>
      
      <div class="contact-callout">
        <strong>Important Note on Funding:</strong><br>
        Please note that fully funded internal PhD positions are limited. Prospective doctoral candidates must secure <strong>third-party or external funding</strong> (e.g., individual doctoral scholarships from the DFG, DAAD, national foundation grants, or international research fellowships). I am happy to support exceptional candidates with strong academic records in preparing scholarship applications or grant proposals.
      </div>
    </div>
  </section>

  <!-- HOW TO APPLY & CONTACT INFO -->
  <section class="student-card">
    <h3>
      <i class="fa-solid fa-paper-plane"></i> How to Inquire &amp; Apply
    </h3>
    <div class="card-text">
      <p>
        If you are interested in pursuing a thesis or PhD research under my supervision, please send a concise inquiry including your research interests, current transcript, and CV.
      </p>
      
      <div class="contact-details-box">
        <div class="contact-detail-item">
          <i class="fa-solid fa-envelope"></i>
          <span>Email: <a href="mailto:p.furley@dshs-koeln.de">p.furley@dshs-koeln.de</a></span>
        </div>
        <div class="contact-detail-item">
          <i class="fa-solid fa-phone"></i>
          <span>Phone: <a href="tel:+4922149824211">+49 (0)221 4982-4211</a></span>
        </div>
        <div class="contact-detail-item">
          <i class="fa-solid fa-building-columns"></i>
          <span>Institute of Exercise Training and Sport Informatics, German Sport University Cologne</span>
        </div>
      </div>
    </div>
  </section>

</div>
