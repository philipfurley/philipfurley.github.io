---
layout: page
title: cv
permalink: /cv/
nav: true
nav_order: 3
cv_pdf: furley_cv.pdf
---

<div class="post">
  <!-- Download Button -->
  <div class="mb-4" style="text-align: right;">
    <a href="{{ '/assets/pdf/furley_cv.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" class="btn btn-sm z-depth-1 font-weight-bold" style="background-color: var(--global-theme-color); color: var(--global-bg-color);">
      <i class="fa-solid fa-file-pdf"></i> Download CV
    </a>
  </div>

  <!-- Embedded PDF Viewer -->
  <object data="{{ '/assets/pdf/furley_cv.pdf' | relative_url }}" type="application/pdf" width="100%" height="800px">
    <p>It appears your browser doesn't support embedded PDFs. 
       You can <a href="{{ '/assets/pdf/furley_cv.pdf' | relative_url }}">click here to download the PDF CV.</a></p>
  </object>
</div>
