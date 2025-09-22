---
layout: single
classes: homepage
title: ""
permalink: /
author_profile: false
entries_layout: list
---

<div class="profile-hero">
  <div class="profile-wrap">
    <div class="profile-left">
      <h1>Kwonsang Lee</h1>
      <div class="profile-title">Associate Professor</div>
      <div class="profile-links">
        <a href="https://stat.snu.ac.kr">Department of Statistics</a><br>
        <a href="https://en.snu.ac.kr">Seoul National University</a>
      </div>
      <div class="profile-email">kwonsanglee (at) snu (dot) ac (dot) kr</div>
      <p class="profile-p" style="margin-top: 1.8rem;">
        I am an Associate Professor of Statistics at Seoul National University, where I lead the SNU Causal Inference Lab.
      </p>
      <p class="profile-p">
        My research develops design- and algorithm-centric methods for causal inference, with a focus on matching, weighting, diagnostics, and randomization-based inference.
      </p>
      <p class="profile-more">
        <a href="{{ '/research/' | relative_url }}">More about my research →</a>
      </p>
      <p class="profile-p">
        From July 2025, I will be a visiting scholar at the University of Pennsylvania.
      </p>
      <div class="profile-cta">
        <!-- Google Scholar -->
        <a class="icon-link" href="https://scholar.google.com/citations?user=125S2iYAAAAJ&hl=en" target="_blank" aria-label="Google Scholar">
          <i class="fa-brands fa-google"></i>
          <span class="tooltip">Google Scholar</span>
        </a>
        <!-- CV -->
        <a class="icon-link" href="{{ '/assets/cv/kwonsang-lee-cv.pdf' | relative_url}}" target="_blank" aria-label="CV">
          <i class="fa-solid fa-file-lines"></i>
          <span class="tooltip">CV</span>
        </a>
      </div>
    </div>
    <div class="profile-right">
      <img src="{{ '/assets/images/kwonsang-lee.png' | relative_url }}" alt="Portrait of Kwonsang Lee">
    </div>
  </div>
</div>

<br>

<div class="prof-educ">
  <h2>Education</h2>
  <ul class="edu-list">
    <li class="edu-item">
      <div class="edu-dates">2017–2020</div>
      <div class="edu-body">
        <p class="edu-degree">
          Postdoctoral Fellow, Department of Biostatistics, Harvard T.H. Chan School of Public Health
        </p>
        <p class="edu-advisor">
          advised by <a href="https://hsph.harvard.edu/profile/francesca-dominici/" target="_blank" rel="noopener">Francesca Dominici</a>
        </p>
      </div>
    </li>
    <li class="edu-item">
      <div class="edu-dates">2012–2017</div>
      <div class="edu-body">
        <p class="edu-degree">
          Ph.D., Applied Mathematics and Computational Science (AMCS), University of Pennsylvania
        </p>
        <p class="edu-advisor">
          advised by <a href="https://statistics.wharton.upenn.edu/profile/dsmall/" target="_blank" rel="noopener">Dylan Small</a>
        </p>
      </div>
    </li>
    <li class="edu-item">
      <div class="edu-dates">2015–2016</div>
      <div class="edu-body">
        <p class="edu-degree">M.A., Statistics, University of Pennsylvania</p>
      </div>
    </li>
    <li class="edu-item">
      <div class="edu-dates">2006–2010</div>
      <div class="edu-body">
        <p class="edu-degree">B.S., Mathematics and Economics, Seoul National University</p>
      </div>
    </li>
  </ul>
</div>


<br>


<div class="prof-research">
  <h2>Research Interests</h2>
  <div class="topics-grid">
    <div class="topic-card">
      <div class="icon"><i class="fas fa-link"></i></div>
      <h4>Matching and Design</h4>
      <p>high-dimensional matching, matching with quantum computing, many-to-many</p>
    </div>
    <div class="topic-card">
      <div class="icon"><i class="fas fa-chart-line"></i></div>
      <h4>Inference</h4>
      <p>heterogeneous effect, causal interaction, sensitivity analysis</p>
    </div>
    <div class="topic-card">
      <div class="icon"><i class="fas fa-shield-alt"></i></div>
      <h4>Overlap &amp; Robustness</h4>
      <p>diagnostics, quantifying overlap</p>
    </div>
    <div class="topic-card">
      <div class="icon"><i class="fas fa-network-wired"></i></div>
      <h4>Complex Structure</h4>
      <p>multiple treatments, time-series data, mediation</p>
    </div>
  </div>
</div>


<br>


<div class="home-news">
  <div class="home-news-left">
    <h2>News</h2>
    <a class="home-news-more" href="{{ '/news/' | relative_url }}">View all →</a>
  </div>

  <div class="home-news-right">
    <ul class="news-list">
      {% assign recent_news = site.news | sort: 'date' | reverse | slice: 0, 5 %}
      {% for item in recent_news %}
        <li class="news-row">
          <span class="news-date">{{ item.date | date: "%b %d" }}</span>
          <span class="news-entry">{{ item.content | markdownify | strip }}</span>
        </li>
      {% endfor %}
    </ul>
  </div>
</div>



<br>

<br>



## To Do

* Home
  * Background colors?
* Research
  * More colors?
* Publications
  * Add DOI
* People
  * Better layout
    * Name card
    * Background color
* Seminar
  * Symposium -> to news
  * Under research?
* News
  * Add more news
* Misc.
  * Remove space at the bottom
  * Copyright messgae
  * Contact info at the footer? (causal email)
  * Remove unnecessary code and images and files
    * scss
    * head

