---
layout: about
title: about
permalink: /
subtitle: German Sport University Cologne · Institute of Exercise Training and Sport Informatics

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

selected_papers: false
social: false
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

<style>
.sidebar-contact {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  font-size: 0.8125rem;
  font-weight: 400;
  line-height: 1.45;
  letter-spacing: -0.01em;
  color: var(--global-text-color-light, #4a5568);
  margin-top: 1.25rem;
  padding-top: 1rem;
  border-top: 1px solid var(--global-divider-color, #e2e8f0);
}

.sidebar-contact .contact-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 0.65rem;
  width: 100%;
}

.sidebar-contact .contact-item:last-child {
  margin-bottom: 0;
}

.sidebar-contact i {
  width: 18px;
  min-width: 18px;
  margin-right: 10px;
  margin-top: 3px;
  color: var(--global-theme-color, #007bff);
  font-size: 0.85rem;
  text-align: center;
  opacity: 0.9;
}

.sidebar-contact span, 
.sidebar-contact a {
  color: inherit;
  word-break: break-word;
}

.sidebar-contact a {
  font-weight: 500;
  text-decoration: none;
  transition: color 0.15s ease-in-out;
}

.sidebar-contact a:hover {
  color: var(--global-theme-color, #007bff);
}

.about-highlights {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.25rem;
  margin: 2rem 0;
}

.highlight-card {
  background: var(--global-card-bg, #fcfcfc);
  border: 1px solid var(--global-divider-color, #e9ecef);
  border-left: 3px solid var(--global-theme-color, #007bff);
  border-radius: 6px;
  padding: 1rem 1.25rem;
  box-shadow: 0 2px 8px rgba(0,0,0,0.02);
}

.highlight-card h4 {
  font-size: 0.88rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  color: var(--global-theme-color, #007bff);
  margin-bottom: 0.4rem;
}

.highlight-card p {
  font-size: 0.85rem;
  line-height: 1.4;
  margin: 0;
  color: var(--global-text-color, #333);
}

html[data-theme='dark'] .highlight-card {
  background: #2c2c2e !important;
  border-color: #3a3a3c !important;
  border-left: 3px solid var(--global-theme-color, #007bff) !important;
}

html[data-theme='dark'] .highlight-card p {
  color: #ffffff !important;
}

.bio-lead {
  font-size: 1.05rem;
  line-height: 1.65;
  color: var(--global-text-color, #222);
}
</style>

<div class="bio-lead">
  <p>I am a professor (PD Dr.) at the <strong>German Sport University Cologne</strong>, where I serve as Deputy Head of the <strong>Institute of Exercise Training and Sport Informatics</strong>. My work has been recognized with the highest honor in German sport science—the <strong>DOSB Science Award</strong>—and is supported by major competitive grants, including funding from the German Research Foundation (DFG).</p>
</div>

<div class="about-highlights">
  <div class="highlight-card">
    <h4><i class="fa-solid fa-user-graduate"></i> Academic Rank</h4>
    <p>Privatdozent (PD Dr.) &amp; Senior Lecturer</p>
  </div>
  <div class="highlight-card">
    <h4><i class="fa-solid fa-trophy"></i> Recognition</h4>
    <p>DOSB Science Award Winner</p>
  </div>
  <div class="highlight-card">
    <h4><i class="fa-solid fa-flask"></i> Primary Funding</h4>
    <p>German Research Foundation (DFG)</p>
  </div>
</div>

<p>My research program advances our understanding of human emotion, nonverbal expressions, visual attention, and cognitive functioning under high pressure. A cornerstone of my work is the application of an <em>in situ</em> ethological approach within the rich, ecologically valid context of competitive sport.</p>

<p>By taking psychological inquiry out of artificial laboratory environments and examining high-stakes athletic scenarios, my lab leverages sports as a naturalistic lens to decode fundamental principles of human psychology, affective processes, nonverbal communication, and executive functioning. Ultimately, this research seeks to bridge the gap between basic cognitive-affective science and real-world human performance, offering novel insights into how individuals adapt, communicate, and excel when stakes are high.</p>

<script>
document.addEventListener("DOMContentLoaded", function () {
  var profile = document.querySelector(".profile");
  if (profile) {
    var contactDiv = document.createElement("div");
    contactDiv.className = "more-info sidebar-contact";
    contactDiv.innerHTML =
      '<div class="contact-item"><i class="fa-solid fa-envelope"></i><span><a href="mailto:p.furley@dshs-koeln.de">p.furley@dshs-koeln.de</a></span></div>' +
      '<div class="contact-item"><i class="fa-solid fa-phone"></i><span>+49 221 4982-4310</span></div>' +
      '<div class="contact-item"><i class="fa-solid fa-building-columns"></i><span>Inst. of Exercise Training &amp; Sport Informatics</span></div>' +
      '<div class="contact-item"><i class="fa-solid fa-location-dot"></i><span>Am Sportpark Müngersdorf 6<br>50933 Köln, Germany</span></div>';
    profile.appendChild(contactDiv);
  }
});
</script>
