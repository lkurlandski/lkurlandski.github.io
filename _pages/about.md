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

- **Jul 2026** *Towards Moving Target Defense for IoT Malware Detection* appeared at SERP4IoT 2026.
- **Feb 2026** *Beyond Raw Bytes: Towards Large Malware Language Models* appeared at NDSS 2026.
- **Jun 2025** *Do Fear the REAPIR: Adversarial Malware from API Replacement* appeared at WoRMA 2025.
- **Apr 2025** Awarded [Provost's Outstanding Graduate Student Teaching Award](https://www.rit.edu/graduateschool/rit-provosts-outstanding-graduate-student-teaching-award).
- **Apr 2024** Awarded the [NSF Graduate Research Fellowship](https://www.nsf.gov/funding/initiatives/grfp).
- **Dec 2023** Awarded the [AI Seed Fund](https://www.rit.edu/srs/ai-seed-fund).
- **Jan 2022** *Impact of Stop Sets on Stopping Active Learning for Text Classification* appeared at ICSC 2022.
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
