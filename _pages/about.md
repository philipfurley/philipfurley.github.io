---
<style>
.sidebar-contact {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  font-size: 0.825rem;
  line-height: 1.4;
  color: var(--global-text-color-light, #4a4a4a);
  margin-top: 1.25rem;
  padding-top: 1rem;
  border-top: 1px solid var(--global-divider-color, #e5e5e5);
}

.sidebar-contact .contact-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 0.6rem;
  width: 100%;
}

.sidebar-contact .contact-item:last-child {
  margin-bottom: 0;
}

.sidebar-contact i {
  width: 18px;
  min-width: 18px;
  margin-right: 10px;
  margin-top: 2px;
  color: var(--global-theme-color, #007bff);
  font-size: 0.85rem;
  text-align: center;
}

.sidebar-contact span, 
.sidebar-contact a {
  color: inherit;
  word-break: break-word;
}

.sidebar-contact a {
  text-decoration: none;
  transition: color 0.2s ease;
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

/* Force dark card backgrounds in dark mode so light text stays legible */
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
