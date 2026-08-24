---
layout: page
permalink: /software/
title: Software
description: Selected research software and reproducible implementations.
nav: true
nav_order: 3
---

Selected implementations accompanying my methodological research. For a full list of public repositories, see my [GitHub profile](https://github.com/ZiyiLiang).

<div class="software-grid">
  <article class="software-card">
    <h3>Structured Conformal Inference for Matrix Completion</h3>
    <p>
      Python package and experiment code for constructing joint prediction regions in matrix-completion and group-recommender settings.
    </p>
    <div class="software-tags"><span>Python</span><span>Jupyter</span><span>Conformal inference</span></div>
    <div class="software-links">
      <a href="https://github.com/ZiyiLiang/simultaneous-matrix-completion">GitHub</a>
      <a href="https://doi.org/10.1080/01621459.2026.2658287">Paper</a>
    </div>
  </article>

  <article class="software-card">
    <h3>Conformalized Early Stopping</h3>
    <p>
      Implementation of conformalized early stopping, which reuses an early-stopping holdout set for conformal calibration while retaining finite-sample guarantees.
    </p>
    <div class="software-tags"><span>Python</span><span>PyTorch</span><span>Uncertainty quantification</span></div>
    <div class="software-links">
      <a href="https://github.com/ZiyiLiang/Conformalized_early_stopping">GitHub</a>
      <a href="https://proceedings.mlr.press/v202/liang23i.html">Paper</a>
    </div>
  </article>

  <article class="software-card">
    <h3>LASLA</h3>
    <p>
      R implementation of locally adaptive structure learning for large-scale multiple testing with auxiliary or network information.
    </p>
    <div class="software-tags"><span>R</span><span>Multiple testing</span><span>Data integration</span></div>
    <div class="software-links">
      <a href="https://github.com/ZiyiLiang/r-lasla">GitHub</a>
      <a href="https://doi.org/10.5705/ss.202024.0002">Paper</a>
    </div>
  </article>

  <article class="software-card">
    <h3>Integrative Conformal Inference for Out-of-Distribution Testing</h3>
    <p>
      Python implementation of conformal out-of-distribution testing that incorporates labeled outliers and controls the false discovery rate.
    </p>
    <div class="software-tags"><span>Python</span><span>Out-of-distribution testing</span><span>FDR control</span></div>
    <div class="software-links">
      <a href="https://github.com/ZiyiLiang/weighted_conformal_pvalues">GitHub</a>
      <a href="https://doi.org/10.1093/jrsssb/qkad138">Paper</a>
    </div>
  </article>
</div>

<style>
  .software-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 1.4rem;
  }
  .software-card {
    border: 1px solid var(--global-divider-color);
    border-radius: 0.35rem;
    padding: 1.1rem 1.2rem;
    background: var(--global-card-bg-color);
  }
  .software-card h3 {
    font-size: 1.08rem;
    font-weight: 600;
    line-height: 1.35;
    margin: 0 0 0.65rem;
  }
  .software-card p {
    font-size: 0.96rem;
    margin-bottom: 0.85rem;
  }
  .software-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-bottom: 0.85rem;
  }
  .software-tags span {
    border: 1px solid var(--global-divider-color);
    border-radius: 999px;
    color: var(--global-text-color-light);
    font-size: 0.75rem;
    padding: 0.12rem 0.52rem;
  }
  .software-links {
    display: flex;
    gap: 1rem;
  }

  @media (max-width: 767.98px) {
    .post-title {
      margin-bottom: 0.8rem;
      font-size: 1.7rem;
      line-height: 1.25;
    }

    .software-grid {
      grid-template-columns: 1fr;
      gap: 0.85rem;
    }

    .software-card {
      padding: 1rem;
    }

    .software-card h3 {
      font-size: 1rem;
    }

    .software-card p {
      font-size: 0.92rem;
      line-height: 1.55;
    }
  }
</style>