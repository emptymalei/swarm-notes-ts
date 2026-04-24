---
# CSL-compatible fields
title: "Fixation Sequences as Time Series: A Topological Approach to Dyslexia Detection"
author:
  - literal: "Marius Huber"
  - literal: "David R. Reich"
  - literal: "Lena A. Jäger"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21698"

# Custom fields
paper_id: "2604.21698"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "Copenhagen Corpus"
concept_slugs:
  - "persistent-homology-filtration-for-time-series"
dataset_slugs:
  - "copenhagen-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:07:25Z"
created_at: "2026-04-24T05:07:25Z"
---

# Fixation Sequences as Time Series: A Topological Approach to Dyslexia Detection

**Authors**: Marius Huber, David R. Reich, Lena A. Jäger
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21698](https://arxiv.org/abs/2604.21698)

## Summary

This paper explores the application of topological data analysis, specifically persistent homology, to detect dyslexia from eye-tracking fixation sequences. The authors propose novel filtration methods to transform fixation data into multi-scale topological features, which are then integrated into a hybrid classification model alongside traditional statistical metrics. Experimental results using the Copenhagen Corpus demonstrate that these topological features significantly improve diagnostic accuracy compared to models relying solely on standard scanpath features. The study highlights the effectiveness of persistent homology in capturing structural eye-movement patterns that are otherwise missed by conventional analysis.

## Key Contributions

- Develops novel persistent homology filtrations for eye-tracking fixation sequences that outperform standard topological approaches.
- Introduces hybrid models combining topological features with statistical metrics for clinical classification.
- Achieves state-of-the-art performance in dyslexia detection on the Copenhagen Corpus, demonstrating that topological features provide complementary information to traditional scanpath metrics.

## Open Questions & Future Work

- [[interpretability-of-topological-reading-features]]

## Key Concepts

- [[persistent-homology-filtration-for-time-series]]: A multi-scale topological feature extraction method that transforms time series into persistence diagrams through novel filtration techniques.

## Archivist Review

The paper presents a clear methodological contribution by applying persistent homology with custom filtrations to eye-tracking data. I approved the filtration concept as it offers a reusable topological representation framework for time series. I also approved one open question regarding interpretability, as it addresses a key bottleneck for clinical adoption. Other candidates were either too local to this specific study or redundant.

### Approved Concepts
- Persistent Homology Filtration for Time Series: Introduces a specialized topological data analysis technique adapted specifically for eye-tracking fixation sequences that captures structural patterns missed by point-wise metrics.

### Approved Open Questions
- Interpretability of topological reading features: Linking topological descriptors to cognitive theories is a prerequisite for clinical adoption of automated dyslexia screening tools.

## Datasets

- [[copenhagen-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21698)
- [PDF](https://arxiv.org/pdf/2604.21698)

