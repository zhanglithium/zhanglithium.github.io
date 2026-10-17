---
layout: page-full-width
title: Sixuan Zhang — Seeing the Atmosphere
permalink: /
---

<div class="szp-home">
  <div class="szp-topline">
    <span class="szp-overline">ATMOSPHERIC SCIENCE <span aria-hidden="true">/</span> DIGITAL HUMANITIES</span>
    <nav class="szp-shortcuts" aria-label="Homepage sections">
      <a href="#about">About</a>
      <a href="#research">Research</a>
      <a href="#dh-practice">DH Practice</a>
      <a href="{{ '/coursework/' | relative_url }}">Coursework ↗</a>
    </nav>
  </div>

  <section class="szp-hero" aria-labelledby="szp-hero-title">
    <div class="szp-hero-copy">
      <p class="szp-kicker">RESEARCH · MAPPING · DIGITAL METHODS</p>
      <h1 id="szp-hero-title">Sixuan Zhang <span>— Seeing the Atmosphere</span></h1>
      <p class="szp-lead">Satellite observations, machine learning, and the spatial stories of air pollution.</p>
      <p class="szp-description">I explore how digital methods can reconstruct and visualize historical patterns of atmospheric nitrogen dioxide (NO₂), and how those maps can inform questions about environmental inequality.</p>
      <div class="szp-actions">
        <a class="szp-button" href="#research">Explore my research <span aria-hidden="true">↗</span></a>
        <a class="szp-link" href="{{ '/coursework/' | relative_url }}">View DH coursework <span aria-hidden="true">→</span></a>
      </div>
    </div>
    <figure class="szp-hero-figure">
      <div class="szp-hero-visual">
        <img src="{{ '/assets/img/la_triptych_omi_eon_tropomi.png' | relative_url }}" alt="Triptych comparing OMI, EON, and TROPOMI NO2 over Los Angeles" loading="eager">
      </div>
      <figcaption>OMI · EON · TROPOMI · Los Angeles, July 2, 2025</figcaption>
    </figure>
  </section>

  <section class="szp-section szp-about" id="about" aria-labelledby="szp-about-heading">
    <div class="szp-section-meta">01 / ABOUT</div>
    <div>
      <h2 id="szp-about-heading">Understanding the atmosphere across scales.</h2>
      <p>My research connects satellite remote sensing and machine learning to study the spatial and historical patterns of air pollution. I am particularly interested in how observations at different resolutions shape the questions we can ask about cities and communities.</p>
      <a class="szp-inline-link" href="{{ '/about.html' | relative_url }}">More about my work <span aria-hidden="true">↗</span></a>
    </div>
  </section>

  <section class="szp-section szp-work" id="research" aria-labelledby="szp-research-heading">
    <div class="szp-section-meta">02 / RESEARCH</div>
    <div>
      <h2 id="szp-research-heading">Seeing NO₂ over Los Angeles</h2>
      <p class="szp-research-intro">My current project uses EON to reconstruct finer-scale NO₂ over Los Angeles and examine how pollution inequality changes across time. The figures below move from satellite observation and reconstruction to long-term inequality analysis.</p>

      <article class="szp-feature-block">
        <figure class="szp-research-figure szp-research-figure-large">
          <img src="{{ '/assets/img/la_triptych_omi_eon_tropomi.png' | relative_url }}" alt="Triptych showing OMI observation, EON reconstruction, and TROPOMI observation over Los Angeles">
          <figcaption><strong>OMI, EON, and TROPOMI over Los Angeles.</strong> This triptych shows how EON reconstructs finer spatial detail between coarse OMI observations and high-resolution TROPOMI observations.</figcaption>
        </figure>
      </article>

      <div class="szp-figure-grid">
        <figure class="szp-research-figure">
          <img src="{{ '/assets/img/la_relative_inequality_2004_2025.png' | relative_url }}" alt="Relative NO2 inequality over Los Angeles from 2004 to 2025 for poverty and income-race inequality">
          <figcaption><strong>Relative NO₂ inequality, 2004–2025.</strong> Relative poverty inequality and income-race inequality both increase over time, while annual mean NO₂ declines.</figcaption>
        </figure>
        <figure class="szp-research-figure">
          <img src="{{ '/assets/img/la_race_ethnicity_relative_inequality_2004_2025.png' | relative_url }}" alt="Race and ethnicity relative NO2 inequality over Los Angeles from 2004 to 2025">
          <figcaption><strong>Race and ethnicity relative NO₂ inequality, 2004–2025.</strong> Relative inequality remains positive for all four groups compared with non-Hispanic White residents.</figcaption>
        </figure>
      </div>

      <div class="szp-grid szp-grid-research-notes">
        <article class="szp-tile">
          <span class="szp-tile-index">01</span>
          <h3>Historical NO₂ Reconstruction</h3>
          <p>EON learns from OMI and TROPOMI to reconstruct finer-scale NO₂ patterns for earlier years when only coarser observations were available.</p>
        </article>
        <article class="szp-tile">
          <span class="szp-tile-index">02</span>
          <h3>Urban Air Pollution</h3>
          <p>The Los Angeles case study highlights strong within-city variability, especially in central and eastern parts of the basin.</p>
        </article>
        <article class="szp-tile">
          <span class="szp-tile-index">03</span>
          <h3>Environmental Inequality</h3>
          <p>Using fixed 2020 tract boundaries and demographics, I compare long-term NO₂ inequality across poverty, income-race, and race/ethnicity groupings.</p>
        </article>
      </div>

      <p class="szp-small szp-method-note">Method note: 2004 covers October–December only. The long-term inequality figures use fixed 2020 tract boundaries and demographics. The dashed line in the inequality plots shows annual mean EON NO₂ TVCD, not population-weighted NO₂.</p>
    </div>
  </section>

  <section class="szp-section" id="dh-practice" aria-labelledby="szp-dh-heading">
    <div class="szp-section-meta">03 / DIGITAL HUMANITIES</div>
    <div>
      <h2 id="szp-dh-heading">Digital methods and critical making</h2>
      <p>My digital humanities practice asks not only what a tool can produce, but also how its data, assumptions, and interfaces shape what becomes visible.</p>
      <div class="szp-pill-list" aria-label="Digital humanities areas">
        <span>Digital Mapping</span><span>Text Analysis</span><span>Critical Making</span><span>Data &amp; Archives</span>
      </div>
      <p class="szp-small">Selected class exercises and reflections are collected in the coursework section of this site.</p>
    </div>
  </section>

  <section class="szp-coursework-banner" id="coursework" aria-labelledby="szp-coursework-heading">
    <div>
      <span class="szp-banner-label">DH 8991 · INTRODUCTION TO DIGITAL HUMANITIES</span>
      <h2 id="szp-coursework-heading">Coursework &amp; reflections</h2>
      <p>Blog posts, critical readings, an annotated bibliography, and practical experiments from the course are collected in a separate space.</p>
    </div>
    <a class="szp-button szp-button-light" href="{{ '/coursework/' | relative_url }}">Open coursework <span aria-hidden="true">↗</span></a>
  </section>

  <footer class="szp-footer">
    <span>Sixuan Zhang · Seeing the Atmosphere</span>
    <span>Built with CB-Essay and GitHub Pages</span>
  </footer>
</div>
