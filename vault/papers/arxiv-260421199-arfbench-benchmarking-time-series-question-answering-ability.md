---
# CSL-compatible fields
title: "ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response"
author:
  - literal: "Stephan Xie"
  - literal: "Ben Cohen"
  - literal: "Mononito Goswami"
  - literal: "Junhong Shen"
  - literal: "Emaad Khwaja"
  - literal: "Chenghao Liu"
  - literal: "David Asker"
  - literal: "Othmane Abou-Amal"
  - literal: "Ameet Talwalkar"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21199"

# Custom fields
paper_id: "2604.21199"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "arfbench"
concept_slugs:
  []
dataset_slugs:
  - "arfbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:10:54Z"
created_at: "2026-04-26T05:10:54Z"
---

# ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response

**Authors**: Stephan Xie, Ben Cohen, Mononito Goswami, Junhong Shen, Emaad Khwaja, Chenghao Liu, David Asker, Othmane Abou-Amal, Ameet Talwalkar
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21199](https://arxiv.org/abs/2604.21199)

## Summary

This paper introduces ARFBench, a specialized benchmark designed to evaluate Time Series Question Answering (TSQA) capabilities of foundation models specifically for software incident response. Using 142 time series derived from production telemetry, the researchers assess various LLMs, VLMs, and time series models to characterize current limitations in anomaly reasoning. The study also presents a hybrid TSFM+VLM approach and demonstrates that human experts and foundation models exhibit complementary strengths, achieving near-expert performance when combined into a model-expert oracle.

## Key Contributions

- Introduces ARFBench, a novel TSQA benchmark containing 750 questions derived from 63 real-world software production incidents (5.38M data points).
- Evaluates performance of state-of-the-art LLMs, VLMs, and TSFMs, finding that frontier VLMs achieve a peak performance of 62.7% accuracy and 51.9% F1.
- Proposes a TSFM + VLM hybrid prototype that, after minimal post-training on synthetic and real data, achieves performance competitive with frontier models.
- Establishes a model-expert oracle selector, reaching 82.8% F1 and 87.2% accuracy, effectively defining a new superhuman performance ceiling for automated TSQA systems.

## Archivist Review

I approved the ARFBench dataset as it provides a valuable, standardized, and real-world-sourced benchmark for the emerging Time Series Question Answering (TSQA) field. I rejected the concept candidate for ARFBench because it is fundamentally a dataset-centric contribution, and creating a duplicate entry under 'concepts' would violate the instruction to be scarce and avoid duplicates.

### Rejected Candidates
- [concept] ARFBench (`arfbench`) - duplicate_existing: This is primarily a dataset/benchmark and is already approved under the approved_datasets list, making a duplicate concept entry unnecessary.

## Datasets

- [[arfbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21199)
- [PDF](https://arxiv.org/pdf/2604.21199)

