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
**I'm on the job market** for research scientist positions starting mid-2027. Reach me at [luke.kurlandski@gmail.com](mailto:luke.kurlandski@gmail.com) or see my [CV](https://lkurlandski.github.io/CurriculumVitae/cv.pdf).
</div>

## Research interests

- **Language models for code and binaries:** pretraining, tokenization, and long-context modeling of executables
- **Adversarial robustness:** attacks on and defenses for ML-based security systems
- **LLM security:** the robustness of large language models and their use in defensive security
- **Generalization:** detectors that transfer across platforms and data distributions

## News

<ul class="news">
  <li><span class="news__date">Feb 2026</span> <span>Presented <a href="https://www.ndss-symposium.org/ndss-paper/beyond-raw-bytes-towards-large-malware-language-models/"><em>Beyond Raw Bytes: Towards Large Malware Language Models</em></a> at NDSS 2026 in San Diego (<a href="https://youtu.be/XjZozJdvbZo">talk video</a>).</span></li>
  <li><span class="news__date">2026</span> <span><em>Towards Moving Target Defense for IoT Malware Detection</em> accepted at SERP4IoT 2026.</span></li>
  <li><span class="news__date">Jun 2025</span> <span><em>Do Fear the REAPIR: Adversarial Malware from API Replacement</em> appeared at WoRMA 2025, co-located with IEEE EuroS&amp;P.</span></li>
  <li><span class="news__date">Apr 2025</span> <span>Received RIT's Provost's Outstanding Graduate Student Teaching Award.</span></li>
  <li><span class="news__date">Aug 2024</span> <span>Presented a poster on pretrained executable language models at USENIX Security 2024.</span></li>
  <li><span class="news__date">Apr 2024</span> <span>Awarded the NSF Graduate Research Fellowship (also offered the NDSEG Fellowship, which I declined).</span></li>
</ul>

## Selected publications

{% assign selected = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected %}
  {% include publication.html pub=post %}
{% endfor %}

[All publications &rarr;](/publications/)

## Teaching and mentoring

- **Instructor**, Advanced Malware Forensics (graduate seminar, RIT, Spring 2024). Sole instructor; overhauled the course materials.
- **Mentor** to 19 B.S. and M.S. students across 7 independent studies and 3 capstone projects (2023–present).
- **Provost's Outstanding Graduate Student Teaching Award**, RIT (2025).
