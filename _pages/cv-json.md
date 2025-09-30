---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
# redirect_from:
#   - /resume-json
---
<!-- Uncomment this if use the cv-template.html -->
<!-- {% include base_path %}
{% include cv-template.html %} -->


<div class="cv-container">
  <h2>Curriculum Vitae</h2>

  <!-- PDF Embedded -->
  <div class="cv-embed" style="margin: 20px 0;">
    <iframe src="{{ base_path }}/files/cv.pdf" 
            width="100%" 
            height="800px" 
            style="border:1px solid #ccc;">
      This browser does not support PDFs. Please download the PDF to view it: 
      <a href="{{ base_path }}/files/cv.pdf">Download CV</a>
    </iframe>
  </div>

  <!-- Download Links -->
  <div class="cv-download-links">
    <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
    <a href="{{ base_path }}/files/cv.md" class="btn btn--inverse">View Markdown CV</a>
  </div>
</div>
