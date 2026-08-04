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

  .cv-mobile-note {
    display: none;
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
    .cv-actions {
      margin-bottom: 1rem;
    }

    .cv-download {
      display: block;
      width: 100%;
      text-align: center;
    }

    .cv-mobile-note {
      display: block;
      margin: 0;
      padding: 1rem;
      border-left: 3px solid var(--global-theme-color, #00356b);
      background: rgba(0, 53, 107, 0.055);
      line-height: 1.55;
    }

    .cv-viewer {
      display: none;
    }
  }
</style>

<div class="cv-page">
  <p class="cv-actions">
    <a class="cv-download" href="{{ '/files/GaryLeung_CV_Jul31.pdf' | relative_url }}" target="_blank" rel="noopener">Open CV in full screen (PDF)</a>
  </p>

  <p class="cv-mobile-note">For the best experience on a phone, use the button above to open the complete CV in your browser’s full-screen PDF viewer.</p>

  <iframe class="cv-viewer" src="{{ '/files/GaryLeung_CV_Jul31.pdf' | relative_url }}" title="Gary Leung curriculum vitae"></iframe>
</div>
