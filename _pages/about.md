---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm a Ph.D. candidate in Computing and Information Science at the Rochester Institute of Technology, advised by Matthew Wright and Yin Pan, and an NSF Graduate Research Fellow. I've spent most of the past four years researching how machine learning can applied in the malware domain. Moving forward, I am broadly interested in the intersection of security and artificial intelligence.

<div class="notice--info job-market" markdown="1">
I'm on the job market for research scientist positions starting mid-2027.
</div>

## Research interests

- **Malware Detection and Mitigation:** Malware analysis and threat mitigation.
- **Adversarial Learning and Robustness:** Robust and secure machine learning.
- **Large Language Models and Agentic AI:** Intelligent and autonomous AI systems.
- **Binary and Prrogram Analysis:** Software analysis and vulnerability discovery.

## News

<ul class="news">
  <li><span class="news__date">Jul 2026</span> <span><a href="https://dl.acm.org/doi/pdf/10.1145/3786159.3788477"><em>Towards Moving Target Defense for IoT Malware Detection</em></a> appeared at SERP4IoT 2026.</span></li>
  <li><span class="news__date">Feb 2026</span> <span><a href="https://ndss-symposium.org/wp-content/uploads/2026-s103-paper.pdf"><em>Beyond Raw Bytes: Towards Large Malware Language Models</em></a> appeared at NDSS 2026.</span></li>
  <li><span class="news__date">Jun 2025</span> <span><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11129592"><em>Do Fear the REAPIR: Adversarial Malware from API Replacement</em></a> appeared at WoRMA 2025.</span></li>
  <li><span class="news__date">Apr 2025</span> <span>Awarded the <a href="https://www.rit.edu/graduateschool/rit-provosts-outstanding-graduate-student-teaching-award">Provost's Outstanding Graduate Student Teaching Award</a>.</span></li>
  <li><span class="news__date">Apr 2024</span> <span>Awarded the <a href="https://www.nsf.gov/funding/initiatives/grfp">NSF Graduate Research Fellowship</a>.</span></li>
  <li><span class="news__date">Dec 2023</span> <span>Awarded the <a href="https://www.rit.edu/srs/ai-seed-fund">AI Seed Fund</a>.</span></li>
  <li><span class="news__date">Jan 2022</span> <span><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9736303"><em>Impact of Stop Sets on Stopping Active Learning for Text Classification</em></a> appeared at ICSC 2022.</span></li>
</ul>

## Selected publications

{% assign selected = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected %}
  {% include publication.html pub=post %}
{% endfor %}

[All publications &rarr;](/publications/)
