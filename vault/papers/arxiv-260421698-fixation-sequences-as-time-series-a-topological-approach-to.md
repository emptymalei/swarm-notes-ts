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
domain: "time-series"
tags:
  - "time-series"
  - "topological-data-analysis"
  - "eye-tracking"
  - "dyslexia-detection"
architectures:
  []
datasets:
  - "copenhagen-corpus"
concept_slugs:
  - "persistent-homology-for-eye-tracking-time-series"
dataset_slugs:
  - "copenhagen-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:54:10Z"
created_at: "2026-04-25T04:54:10Z"
---

# Fixation Sequences as Time Series: A Topological Approach to Dyslexia Detection

**Authors**: Marius Huber, David R. Reich, Lena A. Jäger
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21698](https://arxiv.org/abs/2604.21698)

## Summary

This paper presents a topological data analysis approach for detecting dyslexia by interpreting eye-tracking fixation sequences as time series. The authors develop novel filtrations within the persistent homology framework to capture robust, multi-scale structural information from scanpaths. By integrating these topological features into hybrid classification models, the method outperforms traditional statistical baselines on the Copenhagen Corpus. The results suggest that topological features provide significant diagnostic value beyond standard metrics in behavioral time series analysis.

## Key Contributions

- Introduces novel topological filtrations specifically designed for analyzing eye-tracking fixation sequences as time series data.
- Develops hybrid models that integrate topological features with traditional statistical features, improving classification accuracy for dyslexia detection compared to statistical baselines alone.
- Demonstrates that persistent homology captures complementary, multi-scale information from scanpaths that is otherwise missed by conventional feature engineering.

## Open Questions & Future Work

- [[interpreting-topological-features-dyslexia]]

## Key Concepts

- [[persistent-homology-for-eye-tracking-time-series]]: A topological data analysis approach using novel filtrations to extract multi-scale features from eye-tracking fixation sequences for diagnostic classification.

## Archivist Review

I approved the core topological method for eye-tracking as it offers a novel domain-specific application of persistent homology that is highly reusable for other behavioral time-series tasks. I also approved the open question regarding the interpretability of these topological signatures, as it highlights a fundamental bottleneck in applying complex topological tools to clinical domains. Other candidates were either too broad or served as routine dataset references.

### Approved Concepts
- Persistent Homology for Eye-Tracking Time Series: The paper introduces specific topological filtrations tailored to eye-tracking fixation sequences for classification tasks, moving beyond generic TDA applications.

### Approved Open Questions
- Interpretable Topological Dyslexia Features: Translating abstract topological features into clinically or cognitively meaningful insights is essential for the adoption of TDA-based diagnostic tools.

## Datasets

- [[copenhagen-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21698)
- [PDF](https://arxiv.org/pdf/2604.21698)

