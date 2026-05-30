---
# CSL-compatible fields
title: "Tiny but Trusted: Efficient Vision-Language Reasoning for Time-Series Anomaly Detection"
author:
  - literal: "Xiaona Zhou"
  - literal: "Muntasir Wahed"
  - literal: "Tianjiao Yu"
  - literal: "Constantin Brif"
  - literal: "Ismini Lourentzou"
issued:
  date-parts:
    - [2026, 5, 28]
url: "https://arxiv.org/abs/2605.30344"

# Custom fields
paper_id: "2605.30344"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "VisAnomBench"
concept_slugs:
  - "visanomreasoner"
  - "visanombench"
dataset_slugs:
  - "visanombench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-30T05:22:18Z"
created_at: "2026-05-30T05:22:18Z"
---

# Tiny but Trusted: Efficient Vision-Language Reasoning for Time-Series Anomaly Detection

**Authors**: Xiaona Zhou, Muntasir Wahed, Tianjiao Yu, Constantin Brif, Ismini Lourentzou
**Date**: 2026-05-28
**Paper ID**: [arxiv:2605.30344](https://arxiv.org/abs/2605.30344)

## Summary

This paper introduces VisAnomReasoner, an efficient vision-language model tailored for time-series anomaly detection. To address the lack of grounded explanations in existing sequential data benchmarks, the authors curate VisAnomBench, which incorporates high-quality, VLM-derived anomaly rationales. Fine-tuning on this benchmark enables the model to produce interpretable, grounded decisions, significantly outperforming existing baseline methods in both anomaly localization and classification tasks. Furthermore, the approach demonstrates strong generalization performance across different benchmark datasets.

## Key Contributions

- Introduced VisAnomBench, a novel dataset for time-series anomaly detection augmented with high-quality, VLM-generated natural-language rationales.
- Developed VisAnomReasoner, a parameter-efficient VLM that achieves significant performance gains in anomaly localization, improving precision by 21.23% and F1 by 23.87% on VisAnomBench.
- Demonstrated superior cross-benchmark generalization capability, with VisAnomReasoner improving precision by 9.57% and F1 by 13.39% on the TSB-AD-U benchmark.

## Key Concepts

- [[visanomreasoner]]: A parameter-efficient Vision-Language Model specifically fine-tuned for grounded and interpretable time-series anomaly detection.
- [[visanombench]]: A curated benchmark for time-series anomaly detection augmented with high-quality anomaly explanations derived from multiple large VLMs.

## Archivist Review

I approved the proposed model architecture and the accompanying benchmark because they collectively establish a novel pipeline for grounding time-series anomaly detection in natural-language rationales. These contributions provide a reusable framework for future research on interpretable anomaly detection, moving beyond simple classification tasks. Other candidates were not submitted as open questions, and I have strictly limited the dataset approvals to the primary benchmark.

### Approved Concepts
- VisAnomReasoner: It represents a specific architecture-training methodology for bridging VLM reasoning capabilities with sequential data anomaly tasks using natural-language explanations.
- VisAnomBench: This is a foundational dataset resource that addresses the structural lack of natural-language rationales in existing anomaly detection benchmarks.

## Datasets

- [[visanombench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.30344)
- [PDF](https://arxiv.org/pdf/2605.30344)

