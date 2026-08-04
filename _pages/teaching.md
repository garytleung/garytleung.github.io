---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 3
---

<style>
  .post-description:empty {
    display: none;
  }

  .teaching-intro {
    margin: 0.25rem 0 1.75rem;
    padding: 1rem 1.25rem;
    border-left: 4px solid var(--global-theme-color, #00356b);
    border-radius: 0 0.65rem 0.65rem 0;
    background: rgba(0, 53, 107, 0.055);
    font-size: 1.02rem;
    line-height: 1.65;
  }

  .teaching-intro p {
    margin: 0;
  }

  .teaching-courses {
    display: grid;
    gap: 1rem;
  }

  .teaching-course {
    position: relative;
    display: grid;
    grid-template-columns: 8.5rem minmax(0, 1fr);
    gap: 1.35rem;
    padding: 1.35rem 1.5rem;
    overflow: hidden;
    border: 1px solid rgba(0, 53, 107, 0.16);
    border-radius: 0.8rem;
    background: #fff;
    box-shadow: 0 0.3rem 1.1rem rgba(0, 36, 71, 0.06);
  }

  .teaching-course::before {
    position: absolute;
    inset: 0 auto 0 0;
    width: 4px;
    background: var(--global-theme-color, #00356b);
    content: "";
  }

  .teaching-term {
    padding-top: 0.15rem;
    color: var(--global-theme-color, #00356b);
    font-size: 0.92rem;
    font-weight: 700;
    line-height: 1.4;
  }

  .teaching-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.55rem;
    align-items: center;
    margin-bottom: 0.6rem;
  }

  .teaching-code,
  .teaching-level {
    display: inline-flex;
    align-items: center;
    border-radius: 999px;
    font-size: 0.76rem;
    font-weight: 700;
    line-height: 1;
  }

  .teaching-code {
    padding: 0.35rem 0.7rem;
    background: var(--global-theme-color, #00356b);
    color: #fff;
    letter-spacing: 0.075em;
  }

  .teaching-level {
    padding: 0.33rem 0.65rem;
    border: 1px solid #d7e2ec;
    background: #edf3f8;
    color: #29445e;
  }

  .teaching-title {
    margin: 0;
    color: var(--global-text-color, #222);
    font-size: 1.12rem;
    font-weight: 600;
    line-height: 1.45;
  }

  @media (max-width: 600px) {
    .teaching-intro {
      margin-bottom: 1.25rem;
    }

    .teaching-course {
      grid-template-columns: 1fr;
      gap: 0.65rem;
      padding: 1.2rem 1.25rem;
    }

    .teaching-term {
      padding-top: 0;
    }
  }
</style>

<div class="teaching-intro">
  <p>As a Teaching Fellow at <strong>Yale University</strong>, I have taught the following courses:</p>
</div>

<section class="teaching-courses" aria-label="Courses taught at Yale University" role="list">
  <article class="teaching-course" role="listitem">
    <div class="teaching-term">Spring 2025</div>
    <div>
      <div class="teaching-meta">
        <span class="teaching-code">PLSC 512</span>
        <span class="teaching-level">Ph.D.-level</span>
      </div>
      <h2 class="teaching-title">The Design and Analysis of Randomized Field Experiments in Political Science</h2>
    </div>
  </article>

  <article class="teaching-course" role="listitem">
    <div class="teaching-term">Fall 2024</div>
    <div>
      <div class="teaching-meta">
        <span class="teaching-code">PLSC 349</span>
        <span class="teaching-level">Undergraduate-level</span>
      </div>
      <h2 class="teaching-title">Visualization of Political and Social Data</h2>
    </div>
  </article>

  <article class="teaching-course" role="listitem">
    <div class="teaching-term">Spring 2024</div>
    <div>
      <div class="teaching-meta">
        <span class="teaching-code">PLSC 503</span>
        <span class="teaching-level">Causal Inference, Ph.D.-level</span>
      </div>
      <h2 class="teaching-title">Theory and Practice of Quantitative Methods</h2>
    </div>
  </article>

  <article class="teaching-course" role="listitem">
    <div class="teaching-term">Fall 2022</div>
    <div>
      <div class="teaching-meta">
        <span class="teaching-code">PLSC 344</span>
        <span class="teaching-level">Undergraduate-level</span>
      </div>
      <h2 class="teaching-title">Game Theory and Political Science</h2>
    </div>
  </article>
</section>
