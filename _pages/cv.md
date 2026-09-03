---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-pdf">
  <object data="{{ base_path }}/files/cvSamir.pdf" type="application/pdf">
    <iframe src="{{ base_path }}/files/cvSamir.pdf" title="CV"></iframe>
  </object>
  <p><a href="{{ base_path }}/files/cvSamir.pdf">Open CV as PDF</a></p>
</div>

<style>
  .cv-pdf object,
  .cv-pdf iframe {
    width: 100%;
    min-height: 85vh;
    border: 1px solid var(--global-border-color);
  }
</style>
