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
  - "copenhagen-corpus"
concept_slugs:
  - "persistent-homology-for-eye-tracking-time-series"
dataset_slugs:
  - "copenhagen-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:08:43Z"
created_at: "2026-04-26T05:08:43Z"
---

# Fixation Sequences as Time Series: A Topological Approach to Dyslexia Detection

**Authors**: Marius Huber, David R. Reich, Lena A. Jäger
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21698](https://arxiv.org/abs/2604.21698)

## Summary

This paper introduces a topological approach to analyzing eye-tracking data by treating fixation sequences as time series processed through persistent homology. The authors develop novel filtrations to extract stable, multi-scale topological features, which are then integrated into hybrid models alongside traditional statistical measures. Empirical evaluation on the Copenhagen Corpus confirms that these topological features significantly enhance dyslexia detection, outperforming models that rely solely on conventional features.

## Key Contributions

- Introduces novel filtrations for time series that outperform existing methods in eye-tracking analysis.
- Develops hybrid models combining topological features with traditional statistical metrics to improve dyslexia detection performance.
- Demonstrates that persistent homology captures complementary, robust information from fixation sequences in the Copenhagen Corpus that standard features overlook.

## Open Questions & Future Work

- [[interpreting-topological-features-dyslexia]]

## Key Concepts

- [[persistent-homology-for-eye-tracking-time-series]]: A method for representing fixation sequences as time series using persistent homology to extract robust topological features for clinical and diagnostic tasks.

## Archivist Review

I have approved the core methodological approach (using persistent homology for eye tracking) and the dataset used for validation. The open question was refined to better fit the vault's standard of addressing substantial bottlenecks in interpretability rather than generic future work. Other candidates were rejected for being overly generic architectural patterns or subcomponents of the approved mechanism.

### Approved Concepts
- Persistent Homology for Eye Tracking Time Series: Provides a novel, robust way to extract multi-scale features from eye-tracking data for diagnostic tasks.

### Approved Open Questions
- Interpreting topological dyslexia features: Bridging the gap between high-level topological representations and lower-level cognitive processes is essential for gaining clinical trust and medical utility in screening tools.

### Rejected Candidates
- [concept] Hybrid Models for Dyslexia Detection (`hybrid-models-for-dyslexia-detection`) - generic: This is a generic architectural pattern of combining two feature sets rather than a specific, reusable methodological contribution.
- [concept] Novel Filtrations for Eye Tracking (`novel-filtrations-for-eye-tracking`) - subcomponent_of_broader_mechanism: The specific filtrations are subcomponents of the broader persistent homology framework and are not independently detailed as reusable primitives.

## Datasets

- [[copenhagen-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21698)
- [PDF](https://arxiv.org/pdf/2604.21698)

