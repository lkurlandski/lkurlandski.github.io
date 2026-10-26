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

- **Malware Detection and Mitigation:** Malware analysis and threat mitigation.
- **Adversarial Learning and Robustness:** Robust and secure machine learning.
- **Large Language Models and Agentic AI:** Intelligent and autonomous AI systems.
- **Binary and Prrogram Analysis:** Software analysis and vulnerability discovery.

## News

- **Feb 2026** Presented [*Beyond Raw Bytes: Towards Large Malware Language Models*](https://www.ndss-symposium.org/ndss-paper/beyond-raw-bytes-towards-large-malware-language-models/) at NDSS 2026 in San Diego ([talk video](https://youtu.be/XjZozJdvbZo)).
- **2026** *Towards Moving Target Defense for IoT Malware Detection* accepted at SERP4IoT 2026.
- **Jun 2025** *Do Fear the REAPIR: Adversarial Malware from API Replacement* appeared at WoRMA 2025, co-located with IEEE EuroS&P.
- **Apr 2025** Received RIT's Provost's Outstanding Graduate Student Teaching Award.
- **Aug 2024** Presented a poster on pretrained executable language models at USENIX Security 2024.
- **Apr 2024** Awarded the NSF Graduate Research Fellowship (also offered the NDSEG Fellowship, which I declined).
{: .news}

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
