---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Shahin_CV.pdf" class="btn">Download PDF</a></p>

<object class="cv-pdf" data="{{ base_path }}/files/Shahin_CV.pdf" type="application/pdf">
  <p>Your browser can't display PDFs inline.
     <a href="{{ base_path }}/files/Shahin_CV.pdf">Download my CV</a> instead.</p>
</object>

<style>
  /* Viewer sized to the window rather than the PDF, so it scales with the page.
     Browsers that can't render PDFs inline (most mobile) fall back to the link. */
  .cv-pdf {
    width: 100%;
    height: 85vh;
    min-height: 500px;
    border: 1px solid var(--global-border-color);
  }
</style>
