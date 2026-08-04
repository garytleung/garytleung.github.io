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
    max-width: 980px;
  }

  .cv-actions {
    margin: 0.25rem 0 1.25rem;
  }

  .cv-action {
    display: inline-block;
    padding: 0.58rem 0.95rem;
    border: 1px solid var(--global-theme-color, #00356b);
    border-radius: 0.35rem;
    font-weight: 600;
    text-align: center;
    text-decoration: none;
  }

  .cv-action:hover {
    opacity: 0.88;
    text-decoration: none;
  }


  .cv-download {
    background: transparent;
    color: var(--global-theme-color, #00356b) !important;
  }

  .cv-viewer {
    display: block;
    width: 100%;
    height: 1100px;
    border: 1px solid rgba(0, 53, 107, 0.18);
    border-radius: 0.35rem;
    background: #f5f6f7;
  }

  @media (max-width: 1024px) {
    .cv-viewer {
      height: 78vh;
      height: 78svh;
      min-height: 620px;
    }
  }

  @media (max-width: 520px) {
    .cv-action {
      display: block;
      width: 100%;
    }
  }

  @media (max-height: 600px) and (orientation: landscape) {
    .cv-viewer {
      height: 520px;
      min-height: 520px;
    }
  }
</style>

<div class="cv-page">
  <div class="cv-actions">
    <a class="cv-action cv-download" href="{{ '/files/GaryLeung_CV_Jul31.pdf' | relative_url }}" download="GaryLeung_CV.pdf">Download PDF</a>
  </div>

  <iframe
    class="cv-viewer"
    src="https://mozilla.github.io/pdf.js/web/viewer.html?file=https%3A%2F%2Fgarytleung.github.io%2Ffiles%2FGaryLeung_CV_Jul31.pdf#zoom=page-width&amp;pagemode=none"
    title="Gary Leung curriculum vitae"
    loading="eager"
    allow="fullscreen"
  ></iframe>
</div>
