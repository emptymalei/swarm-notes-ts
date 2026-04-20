---
# CSL-compatible fields
title: "MF-toolkit: A High-Performance Python Library for Multifractal Analysis with Automated Crossover Detection, Source Identification and Application to Gravitational Waves Data"
author:
  - literal: "Nahuel Mendez"
  - literal: "Maria Cristina Mariani Maria Pia Beccar-Varela"
  - literal: "Osei Tweneboah"
  - literal: "Sebastian Jaroszewicz"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16257"

# Custom fields
paper_id: "2604.16257"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-analysis"
  - "statistical-analysis"
  - "open-source-software"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mfdfa"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:08:07Z"
created_at: "2026-04-20T05:08:07Z"
---

# MF-toolkit: A High-Performance Python Library for Multifractal Analysis with Automated Crossover Detection, Source Identification and Application to Gravitational Waves Data

**Authors**: Nahuel Mendez, Maria Cristina Mariani Maria Pia Beccar-Varela, Osei Tweneboah, Sebastian Jaroszewicz
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16257](https://arxiv.org/abs/2604.16257)

## Summary

MF-toolkit is a parallelized Python library designed to streamline Multifractal Detrended Fluctuation Analysis (MFDFA) by automating previously manual components of the pipeline. The framework includes robust algorithms for automated crossover detection and provides tools for surrogate data generation to distinguish between genuine multifractal scaling and spurious correlations. Its utility is demonstrated through the analysis of non-stationary noise within LIGO gravitational wave datasets, offering a standardized approach for complex time series characterization.

## Key Contributions

- Introduces MF-toolkit, a high-performance Python library providing automated and parallelized Multifractal Detrended Fluctuation Analysis (MFDFA).
- Implements automated crossover detection algorithms (CDV-A and SPIC) to eliminate operator subjectivity and improve analysis reproducibility.
- Integrates Iterative Amplitude Adjusted Fourier Transform (IAAFT) surrogate generation to isolate the physical origins of multifractality in complex time series.

## Open Questions & Future Work

- [[isolating-transient-multifractal-signatures]]

## Key Concepts

- [[mfdfa]]: A statistical technique used for characterizing the scaling properties and long-range correlations of non-stationary complex time series.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 1 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Multifractal Detrended Fluctuation Analysis (MFDFA): It is a fundamental tool for analyzing non-stationary complex time series, and the paper provides a standardized, automated implementation for it.

### Approved Open Questions
- Isolating transient multifractal signatures: This is a core limitation in applying multifractal analysis to real-world transient-driven data like gravitational waves.

### Rejected Candidates
- [concept] MF-toolkit (`mf-toolkit`) - paper_local: This is a specific software library implementation rather than a standalone theoretical concept or mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.16257)
- [PDF](https://arxiv.org/pdf/2604.16257)

