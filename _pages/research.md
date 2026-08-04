---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

<style>
  .research-page {
    max-width: 820px;
  }

  .research-jmp {
    margin: 0.35rem 0 3rem;
    padding-left: 1.35rem;
    border-left: 3px solid var(--global-theme-color, #00356b);
  }

  .research-kicker {
    margin: 0 0 0.55rem;
    color: var(--global-theme-color, #00356b);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.09em;
    text-transform: uppercase;
  }

  .research-title {
    margin: 0 0 1.1rem;
    color: var(--global-text-color);
    font-size: 1.5rem;
    font-weight: 700;
    line-height: 1.32;
  }

  .research-abstract {
    margin: 0;
    max-width: 47rem;
    font-size: 1rem;
    line-height: 1.75;
  }

  .research-working {
    padding-top: 2rem;
    border-top: 1px solid rgba(0, 53, 107, 0.18);
  }

  .research-working-header {
    display: flex;
    gap: 1rem;
    align-items: baseline;
    justify-content: space-between;
    margin-bottom: 0.85rem;
  }

  .research-working h2 {
    margin: 0;
    color: var(--global-theme-color, #00356b);
    font-size: 1.35rem;
    font-weight: 700;
  }

  .research-note {
    margin: 0;
    color: var(--global-text-color-light, #666);
    font-size: 0.88rem;
    font-style: italic;
  }

  .research-paper-list {
    margin: 0;
    padding: 0;
    list-style: none;
    border-bottom: 1px solid rgba(0, 53, 107, 0.13);
  }

  .research-paper {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    gap: 1rem;
    align-items: start;
    padding: 1rem 0;
    border-top: 1px solid rgba(0, 53, 107, 0.13);
  }

  .research-paper-title {
    font-weight: 600;
    line-height: 1.48;
  }

  .research-status {
    margin-top: 0.05rem;
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
    .research-jmp {
      padding-left: 1rem;
    }

    .research-title {
      font-size: 1.28rem;
    }

    .research-working-header {
      display: block;
    }

    .research-note {
      margin-top: 0.35rem;
    }

    .research-paper {
      grid-template-columns: 1fr;
      gap: 0.55rem;
    }

    .research-status {
      justify-self: start;
    }
  }
</style>

<div class="research-page">
  <section class="research-jmp" aria-labelledby="jmp-title">
    <p class="research-kicker">Job Market Paper</p>
    <h2 class="research-title" id="jmp-title">State versus Cultural Nationalism and the Legitimacy–Unity Trade-off: Evidence from China</h2>
    <p class="research-abstract">When does nationalism strengthen authoritarian rule, and at what cost? State nationalism defines the nation through political institutions and territorial boundaries rather than shared culture. I argue that it creates a legitimacy–unity trade-off: it increases perceived regime legitimacy and support for ethnic minority accommodation, but weakens national identification among regime opponents, for whom dissatisfaction with the regime spills over into disidentification from the nation. I test this argument through two online experiments alongside a large-scale laboratory experiment in mainland China and Hong Kong, using a novel compare-and-argue self-persuasion design that generates exogenous variation in conceptions of the nation. In mainland China, state nationalism raises regime legitimacy and, under external threat, support for minority accommodation. In Hong Kong, state nationalism amplified how repression-related news and government dissatisfaction weakened national identification. The findings suggest that nationalism in autocracies can secure loyalty to the regime at the expense of attachment to the nation.</p>
  </section>

  <section class="research-working" aria-labelledby="working-papers-title">
    <div class="research-working-header">
      <h2 id="working-papers-title">Working Papers</h2>
      <p class="research-note">Drafts available upon request.</p>
    </div>

    <ul class="research-paper-list">
      <li class="research-paper">
        <span class="research-paper-title">The Feedback Effects of Failed Nation-Building: Experimental Evidence from China</span>
        <span class="research-status">Under Review</span>
      </li>
      <li class="research-paper">
        <span class="research-paper-title">Victimhood Complements Victory</span>
        <span class="research-status">Under Review</span>
      </li>
      <li class="research-paper">
        <span class="research-paper-title">Self-Persuasion as Experimental Belief Manipulation: A Compare-and-Argue Method</span>
      </li>
      <li class="research-paper">
        <span class="research-paper-title">What Does It Mean to Be Chinese? Inclusive Nationalism in a Resilient Authoritarian Regime</span>
      </li>
    </ul>
  </section>
</div>
  
