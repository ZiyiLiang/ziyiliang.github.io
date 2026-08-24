---
layout: about
title: Home
permalink: /

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <nav class="profile-links" aria-label="Professional profiles">
      <a href="https://scholar.google.com/citations?user=jtcnL0UAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar"></i><span>Google Scholar</span></a>
      <a href="/assets/pdf/Ziyi_Liang_CV.pdf" target="_blank"><i class="fa-solid fa-file-lines"></i><span>Curriculum Vitae</span></a>
      <a href="mailto:ziyiliang@ucsb.edu"><i class="fa-solid fa-envelope"></i><span>Email</span></a>
      <a href="https://github.com/ZiyiLiang" target="_blank"><i class="fa-brands fa-github"></i><span>GitHub</span></a>
      <a href="https://www.linkedin.com/in/ziyi-liang-8b781b237/" target="_blank"><i class="fa-brands fa-linkedin"></i><span>LinkedIn</span></a>
    </nav>

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  .post article {
    font-size: 1.06rem;
    line-height: 1.72;
  }

  @media (min-width: 768px) {
    .profile.float-left {
      width: 24%;
      max-width: 220px;
      margin-right: 2rem;
    }
  }

  .profile img {
    aspect-ratio: 4 / 5;
    object-fit: cover;
    object-position: 50% 42%;
    border-radius: 3px !important;
    box-shadow: 0 10px 28px rgba(29, 47, 48, 0.12);
  }

  .profile-links {
    display: grid;
    gap: 0.42rem;
    margin-top: 0.9rem;
    font-size: 0.98rem;
  }

  .profile-links a {
    display: flex;
    align-items: center;
    gap: 0.55rem;
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .profile-links a:hover,
  .profile-links a:focus-visible {
    color: var(--global-hover-color);
    text-decoration: underline;
    text-underline-offset: 0.2em;
  }

  .profile-links i {
    width: 1.1rem;
    text-align: center;
  }


  .post a {
    color: var(--global-theme-color);
    text-decoration-color: color-mix(in srgb, var(--global-theme-color) 45%, transparent);
    text-underline-offset: 0.18em;
  }

  .post article > hr {
    clear: both;
    margin: 2rem 0 1.35rem;
  }

  .post article h3 {
    margin-bottom: 0.75rem;
    font-size: 1.35rem;
  }

  .research-keywords {
    margin-top: 1rem;
    color: var(--global-text-color-light);
    letter-spacing: 0.01em;
  }

  @media (max-width: 767.98px) {
    .post article {
      font-size: 0.94rem;
      line-height: 1.62;
    }

    .profile.float-left {
      float: none !important;
      clear: both;
      display: grid;
      grid-template-columns: 144px minmax(0, 1fr);
      align-items: center;
      column-gap: 1rem;
      width: 100%;
      max-width: none;
      margin: 0 0 1.5rem;
    }

    .profile figure {
      width: 144px;
      margin: 0;
    }

    .profile img {
      width: 144px;
      max-width: 144px;
      margin: 0;
    }

    .profile .more-info {
      width: 100%;
      margin: 0;
    }

    .profile-links {
      grid-template-columns: 1fr;
      gap: 0.12rem;
      margin-top: 0;
      font-size: 0.82rem;
    }

    .profile-links a {
      min-height: 1.65rem;
      gap: 0.45rem;
    }

    .post article > p:first-of-type {
      clear: both;
    }

    .post article h3 {
      font-size: 1.15rem;
    }
  }

  @media (max-width: 359.98px) {
    .profile.float-left {
      grid-template-columns: 124px minmax(0, 1fr);
      column-gap: 0.8rem;
    }

    .profile figure,
    .profile img {
      width: 124px;
      max-width: 124px;
    }

    .profile-links {
      font-size: 0.78rem;
    }
  }
</style>

I am a postdoctoral researcher in the [Department of Statistics and Applied Probability](https://www.pstat.ucsb.edu/) at the [University of California, Santa Barbara](https://www.ucsb.edu/). I work with [Annie Qu](https://qu.pstat.ucsb.edu/) and [Babak Shahbaba](https://ics.uci.edu/~babaks/) on statistical methodology for complex scientific data, with domain-science guidance from neuroscientist [Norbert Fortin](https://fortinlab.bio.uci.edu/).

I received my Ph.D. in [Applied Mathematics](https://dornsife.usc.edu/mathematics/short-guide-to-phd-program/) from the [University of Southern California](https://www.usc.edu/), where I was advised by [Matteo Sesia](https://msesia.github.io/) and [Larry Goldstein](https://dornsife.usc.edu/larry-goldstein/).

---

### Research Interests

My research interests include integrating heterogeneous data sources and quantifying uncertainty in modern predictive systems, with the broader goal of enabling reliable scientific discovery. Application areas span multimodal learning, mobile health, and computational neuroscience.

<p class="research-keywords"><strong>Keywords:</strong> Data integration &nbsp;&middot;&nbsp; Uncertainty quantification &nbsp;&middot;&nbsp; Data science for science</p>
