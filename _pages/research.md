---
permalink: /research/
title: "Research"
author_profile: true
---

My research sits at the intersection of machine learning and security. Most of it asks one question: what does it take for a model to *understand* executable code well enough to detect malicious behavior, and how does that understanding break under attack?

<!-- TODO: add one figure per project (e.g., an architecture or results figure from each paper) under images/research/ -->

## Large malware language models

Raw-binary malware classifiers read executables byte by byte, which lets them avoid hand-engineered features but leaves them limited in capability and struggling with very long sequences. Large language models suggest another path: pretrain on large amounts of unlabeled code, then finetune.

In [*Beyond Raw Bytes*](https://www.ndss-symposium.org/ndss-paper/beyond-raw-bytes-towards-large-malware-language-models/) (NDSS 2026), we take the first steps toward **large malware language models**, the malware analog to LLMs, covering data, model design, pretraining, and finetuning. Pretraining a malware classifier with language-modeling objectives improved downstream performance across diverse malware classification tasks by 1.1% on average and by up to 28.6%. Follow-up work (under review) argues that raw-binary classifiers need both *structure* and *scale* to work well.

[Paper](https://www.ndss-symposium.org/wp-content/uploads/2026-s103-paper.pdf) · [Slides](https://www.ndss-symposium.org/wp-content/uploads/s0103-kurlandski-slides.pdf) · [Talk](https://youtu.be/XjZozJdvbZo) · [USENIX Security 2024 poster](/publications/#posters)

## Adversarial malware

ML-based detectors are deployed against adversaries who adapt. In [*Do Fear the REAPIR*](/publications/#workshops) (WoRMA 2025), we generate adversarial malware through **API replacement**. Earlier, I explored an evasion attack that uses **machine translation** (AI@RIT Summit 2022).

## Detection that generalizes

Detectors trained on one platform or distribution often fail on another. With collaborators, I study **cross-platform malware detection through unsupervised domain alignment** (DAUGL, under review) and **moving target defense for IoT malware detection** (SERP4IoT 2026).

## Earlier work

As an undergraduate at TCNJ, I studied **label-efficient NLP**, showing how the choice of stop set affects methods for stopping active learning ([ICSC 2022](https://arxiv.org/abs/2201.05460)). I built a recommender system for finding under-appreciated research (NSF REU), detected deepfake audio as a research intern at CACI, and wrote the control software for optical microstructure fabrication in a photonics lab.

## Open-source software

- [**RawByteClf**](https://github.com/lkurlandski/RawByteClf): classifying malware from raw bytes with Transformers.
- [**EXTRACTOR**](https://github.com/lkurlandski/EXTRACTOR): extract, disassemble, and decompile code from PE files.
- [**MDALTH**](https://github.com/lkurlandski/MDALTH): modular deep active learning on PyTorch and Hugging Face.
