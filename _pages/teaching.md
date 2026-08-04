---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 3
---

<style>
  .teaching-page {
    max-width: 820px;
  }

  .teaching-intro {
    margin: 0.35rem 0 3rem;
    padding-left: 1.35rem;
    border-left: 3px solid var(--global-theme-color, #00356b);
  }

  .teaching-kicker {
    margin: 0 0 0.55rem;
    color: var(--global-theme-color, #00356b);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.09em;
    text-transform: uppercase;
  }

  .teaching-summary {
    margin: 0;
    max-width: 42rem;
    font-size: 1.15rem;
    font-weight: 500;
    line-height: 1.6;
  }

  .teaching-section {
    padding-top: 2rem;
    border-top: 1px solid rgba(0, 53, 107, 0.18);
  }

  .teaching-section h2 {
    margin: 0 0 0.85rem;
    color: var(--global-theme-color, #00356b);
    font-size: 1.35rem;
    font-weight: 700;
  }

  .teaching-course-list {
    margin: 0;
    padding: 0;
    list-style: none;
    border-bottom: 1px solid rgba(0, 53, 107, 0.13);
  }

  .teaching-course {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    gap: 1rem;
    align-items: start;
    padding: 1.1rem 0;
    border-top: 1px solid rgba(0, 53, 107, 0.13);
  }

  .teaching-course-meta {
    margin: 0 0 0.32rem;
    color: var(--global-theme-color, #00356b);
    font-size: 0.76rem;
    font-weight: 700;
    letter-spacing: 0.055em;
    text-transform: uppercase;
  }

  .teaching-course-title {
    margin: 0;
    color: var(--global-text-color);
    font-size: 1.05rem;
    font-weight: 600;
    line-height: 1.48;
  }

  .teaching-level {
    margin-top: 0.12rem;
    padding: 0.16rem 0.52rem;
    border: 1px solid rgba(0, 53, 107, 0.25);
    border-radius: 999px;
    background: rgba(0, 53, 107, 0.055);
    color: var(--global-theme-color, #00356b);
    font-size: 0.74rem;
    font-weight: 600;
    letter-spacing: 0.02em;
    white-space: nowrap;
  }

  @media (max-width: 600px) {
    .teaching-intro {
      padding-left: 1rem;
    }

    .teaching-summary {
      font-size: 1.05rem;
    }

    .teaching-course {
      grid-template-columns: 1fr;
      gap: 0.55rem;
    }

    .teaching-level {
      justify-self: start;
    }
  }
</style>

<div class="teaching-page">
  <section class="teaching-intro" aria-labelledby="teaching-summary">
    <p class="teaching-kicker">Yale University</p>
    <p class="teaching-summary" id="teaching-summary">As a Teaching Fellow, I have taught the following four courses.</p>
  </section>

  <section class="teaching-section" aria-labelledby="courses-title">
    <h2 id="courses-title">Courses</h2>

    <ul class="teaching-course-list">
      <li class="teaching-course">
        <div>
          <p class="teaching-course-meta">Spring 2025 · PLSC 512</p>
          <h3 class="teaching-course-title">The Design and Analysis of Randomized Field Experiments in Political Science</h3>
        </div>
        <span class="teaching-level">Ph.D.-level</span>
      </li>
      <li class="teaching-course">
        <div>
          <p class="teaching-course-meta">Fall 2024 · PLSC 349</p>
          <h3 class="teaching-course-title">Visualization of Political and Social Data</h3>
        </div>
        <span class="teaching-level">Undergraduate-level</span>
      </li>
      <li class="teaching-course">
        <div>
          <p class="teaching-course-meta">Spring 2024 · PLSC 503</p>
          <h3 class="teaching-course-title">Theory and Practice of Quantitative Methods (Causal Inference)</h3>
        </div>
        <span class="teaching-level">Ph.D.-level</span>
      </li>
      <li class="teaching-course">
        <div>
          <p class="teaching-course-meta">Fall 2022 · PLSC 344</p>
          <h3 class="teaching-course-title">Game Theory and Political Science</h3>
        </div>
        <span class="teaching-level">Undergraduate-level</span>
      </li>
    </ul>
  </section>
</div>
  
