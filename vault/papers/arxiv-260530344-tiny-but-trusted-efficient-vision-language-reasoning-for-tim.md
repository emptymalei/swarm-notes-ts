---
# CSL-compatible fields
title: "Tiny but Trusted: Efficient Vision-Language Reasoning for Time-Series Anomaly Detection"
author:
  - literal: "Xiaona Zhou"
  - literal: "Muntasir Wahed"
  - literal: "Tianjiao Yu"
  - literal: "Constantin Brif, Ismini Lourentzou"
issued:
  date-parts:
    - [2026, 5, 28]
url: "https://arxiv.org/abs/2605.30344"

# Custom fields
paper_id: "2605.30344"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "visanombench"
concept_slugs:
  - "visanomreasoner"
dataset_slugs:
  - "visanombench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-31T05:36:28Z"
created_at: "2026-05-31T05:36:28Z"
---

# Tiny but Trusted: Efficient Vision-Language Reasoning for Time-Series Anomaly Detection

**Authors**: Xiaona Zhou, Muntasir Wahed, Tianjiao Yu, Constantin Brif, Ismini Lourentzou
**Date**: 2026-05-28
**Paper ID**: [arxiv:2605.30344](https://arxiv.org/abs/2605.30344)

## Summary

The authors introduce VisAnomBench, a novel benchmark that addresses the scarcity of natural-language rationales in existing time-series anomaly detection tasks by augmenting data with expert-quality explanations. They leverage this to train VisAnomReasoner, a parameter-efficient vision-language model designed for interpretable anomaly localization. Experimental validation shows substantial performance gains over existing baselines on both the new benchmark and the TSB-AD-U dataset, confirming the model's effectiveness and generalization capability.

## Key Contributions

- Introduced VisAnomBench, a new benchmark for time-series anomaly detection that includes high-quality natural language rationales.
- Developed VisAnomReasoner, a parameter-efficient VLM that achieves significant performance gains in anomaly localization, improving precision by 21.23% and F1 by 23.87% on VisAnomBench.
- Demonstrated strong cross-benchmark generalization on the TSB-AD-U benchmark, yielding 9.57% and 13.39% improvements in precision and F1 respectively.

## Key Concepts

- [[visanomreasoner]]: A parameter-efficient Vision-Language Model specifically fine-tuned for grounded time-series anomaly detection.

## Archivist Review

The paper's primary methodological contribution is the VisAnomReasoner model, which demonstrates a successful paradigm for adapting vision-language models to sequential anomaly detection using rationale-based fine-tuning. The dataset, VisAnomBench, is approved as a standalone resource for benchmarking these models, but the concept candidate for the same was rejected to maintain a clear distinction between data and methodology. No significant open questions were proposed that transcend the paper's specific evaluation setup.

### Approved Concepts
- VisAnomReasoner: It represents a specialized, parameter-efficient VLM architecture for time-series anomaly localization that outperforms generic baselines.

### Rejected Candidates
- [concept] VisAnomBench (`visanombench`) - other: This is a dataset, not a methodological concept, and should be categorized as a dataset note instead.

## Datasets

- [[visanombench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.30344)
- [PDF](https://arxiv.org/pdf/2605.30344)

