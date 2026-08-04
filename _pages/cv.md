---
layout: page
permalink: /cv/
title: CV
description: Curriculum vitae.
nav: true
nav_order: 4
---

<style>
  .cv-page {
    max-width: 900px;
  }

  .cv-actions {
    margin: 0.25rem 0 1.5rem;
  }

  .cv-download {
    display: inline-block;
    padding: 0.58rem 0.95rem;
    border: 1px solid var(--global-theme-color, #00356b);
    border-radius: 0.35rem;
    background: var(--global-theme-color, #00356b);
    color: #fff !important;
    font-weight: 600;
    text-decoration: none;
  }

  .cv-download:hover {
    opacity: 0.88;
    text-decoration: none;
  }

  .cv-viewer {
    display: block;
    width: 100%;
    height: 1100px;
    border: 1px solid rgba(0, 53, 107, 0.18);
    border-radius: 0.35rem;
    background: #fff;
  }

  @media (max-width: 700px) {
    .cv-viewer {
      height: 760px;
    }
  }
</style>

<div class="cv-page">
  <p class="cv-actions">
    <a class="cv-download" href="{{ '/files/GaryLeung_CV_Jul31.pdf' | relative_url }}" target="_blank" rel="noopener">Open or download CV (PDF)</a>
  </p>

  <iframe class="cv-viewer" src="{{ '/files/GaryLeung_CV_Jul31.pdf' | relative_url }}" title="Gary Leung curriculum vitae"></iframe>
</div>
