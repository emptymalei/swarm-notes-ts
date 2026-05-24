---
# CSL-compatible fields
title: "Forecasting Scientific Progress with Artificial Intelligence"
author:
  - literal: "Sean Wu"
  - literal: "Pan Lu"
  - literal: "Yupeng Chen"
  - literal: "Jonathan Bragg"
  - literal: "Yutaro Yamada"
  - literal: "Peter Clark"
  - literal: "David Clifton"
  - literal: "Philip Torr"
  - literal: "James Zou"
  - literal: "Junchi Yu"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22681"

# Custom fields
paper_id: "2605.22681"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "forecasting"
  - "evaluation-framework"
  - "scientific-discovery"
  - "uncertainty-estimation"
architectures:
  []
datasets:
  - "CUSP"
concept_slugs:
  - "cusp-benchmark"
dataset_slugs:
  - "cusp"
skill: "TimeSeriesSkill"
processed_at: "2026-05-24T05:25:14Z"
created_at: "2026-05-24T05:25:14Z"
---

# Forecasting Scientific Progress with Artificial Intelligence

**Authors**: Sean Wu, Pan Lu, Yupeng Chen, Jonathan Bragg, Yutaro Yamada, Peter Clark, David Clifton, Philip Torr, James Zou, Junchi Yu
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22681](https://arxiv.org/abs/2605.22681)

## Summary

This paper investigates the capacity of AI systems to forecast scientific progress using a new framework called CUSP (Cutoff-conditioned Unseen Scientific Progress). By evaluating frontier models across over 4,760 diverse scientific events, the study reveals significant deficiencies in predicting the realization and timing of research breakthroughs. The results show that while models can identify plausible research paths, they struggle with temporal accuracy, exhibit systematic overconfidence, and are limited by architectural constraints rather than just data availability. The findings suggest that current AI systems are not yet reliable tools for predictive scientific forecasting.

## Key Contributions

- Introduces the CUSP benchmark to evaluate AI forecasting of scientific progress across feasibility, reasoning, generation, and temporal prediction.
- Demonstrates that frontier AI models exhibit systematic failures in predicting the realization and timing of scientific breakthroughs across 4,760 events.
- Identifies domain-dependent predictive performance, with AI-related progress being more predictable than physics, chemistry, or biological advances.
- Reveals that model performance is largely insensitive to training cutoff dates, indicating that failure stems from inherent limitations rather than lack of data.

## Key Concepts

- [[cusp-benchmark]]: A multi-disciplinary benchmark designed to evaluate AI systems' ability to forecast scientific progress through feasibility, reasoning, and temporal prediction under controlled knowledge constraints.

## Archivist Review

The CUSP benchmark is approved as it introduces a novel evaluation protocol (cutoff-conditioned assessment) for measuring scientific progress forecasting, which is distinct from generic time-series benchmarks. Other candidates were rejected because they described model performance outcomes rather than reusable architectural or methodological concepts.

### Approved Concepts
- CUSP Benchmark: It establishes a standard for evaluating the ability of AI to forecast scientific breakthroughs under controlled knowledge constraints, disentangling training data effects from reasoning failures.

### Rejected Candidates
- [concept] Scientific Discovery Forecasting Limitations (`scientific-discovery-forecasting-limitations`) - not_reusable: The identified limitations are descriptive of current model performance and represent outcomes of the benchmark rather than a reusable architectural concept.

## Datasets

- [[cusp]]

## Links

- [Abstract](https://arxiv.org/abs/2605.22681)
- [PDF](https://arxiv.org/pdf/2605.22681)

