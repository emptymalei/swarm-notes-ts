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
  - "ARFBench"
concept_slugs:
  - "tsqa"
dataset_slugs:
  - "arfbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:08:20Z"
created_at: "2026-04-24T05:08:20Z"
---

# ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response

**Authors**: Stephan Xie, Ben Cohen, Mononito Goswami, Junhong Shen, Emaad Khwaja, Chenghao Liu, David Asker, Othmane Abou-Amal, Ameet Talwalkar
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21199](https://arxiv.org/abs/2604.21199)

## Summary

ARFBench addresses the under-explored task of Time Series Question-Answering (TSQA) by evaluating multimodal foundation models on real-world software incident telemetry. The benchmark evaluates LLMs, VLMs, and specialized time series FMs, revealing that frontier VLMs currently lead performance. Additionally, a new hybrid TSFM-VLM architecture is introduced, and the potential for human-model collaboration is quantified through a high-performing oracle selector.

## Key Contributions

- Introduces ARFBench, a benchmark containing 750 questions over 142 time series from 63 production incidents for evaluating TSQA capabilities.
- Demonstrates that frontier VLMs significantly outperform existing baselines, with top models achieving 62.7% accuracy and 51.9% F1.
- Proposes a TSFM + VLM hybrid prototype that, after minimal post-training, matches the performance of frontier models.
- Establishes a superhuman performance baseline (82.8% F1 and 87.2% accuracy) using a model-expert oracle selector.

## Key Concepts

- [[tsqa]]: A task where natural language questions are used to infer and reason about properties of time series data.

## Archivist Review

I approved the TSQA concept as it formalizes an emerging intersection of time-series analysis and language reasoning. ARFBench was approved as a dataset, but rejected as a concept to avoid redundancy in the vault. No open questions were identified that met the criteria for a permanent research note.

### Approved Concepts
- Time Series Question-Answering (TSQA): TSQA defines the core research area of the paper, establishing a new task for multimodal foundation models.

### Rejected Candidates
- [concept] ARFBench (`arfbench`) - subcomponent_of_broader_mechanism: This is a dataset, not a methodological concept; it is already approved as a dataset.

## Datasets

- [[arfbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21199)
- [PDF](https://arxiv.org/pdf/2604.21199)

