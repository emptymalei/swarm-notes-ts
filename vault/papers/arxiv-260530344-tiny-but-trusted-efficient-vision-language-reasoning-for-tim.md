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
processed_at: "2026-05-29T05:33:39Z"
created_at: "2026-05-29T05:33:39Z"
---

# Tiny but Trusted: Efficient Vision-Language Reasoning for Time-Series Anomaly Detection

**Authors**: Xiaona Zhou, Muntasir Wahed, Tianjiao Yu, Constantin Brif, Ismini Lourentzou
**Date**: 2026-05-28
**Paper ID**: [arxiv:2605.30344](https://arxiv.org/abs/2605.30344)

## Summary

This paper addresses the interpretability and performance limitations of multimodal models in time-series anomaly detection by creating VisAnomBench, a new dataset featuring natural-language rationales for abnormal patterns. Using this benchmark, the authors develop VisAnomReasoner, a parameter-efficient vision-language model trained to provide grounded, interpretable detection decisions. Evaluations demonstrate that the model significantly outperforms existing methods on both the curated benchmark and the TSB-AD-U dataset, showing robust cross-benchmark generalization.

## Key Contributions

- Constructed VisAnomBench, a novel benchmark providing natural-language rationales for time-series anomaly detection.
- Developed VisAnomReasoner, which achieves 21.23 and 23.87 percentage point gains in precision and F1 over baselines on VisAnomBench.
- Demonstrated strong cross-benchmark generalization on TSB-AD-U with up to 13.39 percentage points improvement in F1.

## Key Concepts

- [[visanomreasoner]]: A parameter-efficient vision-language model architecture designed for grounded and interpretable time-series anomaly detection.

## Archivist Review

The paper introduces a novel approach to multimodal time-series anomaly detection using rationale-based fine-tuning. I have approved the model architecture (VisAnomReasoner) as a concept, as it represents a clear architectural shift for VLM-based temporal reasoning, and VisAnomBench as a standalone dataset given its specific contribution of natural-language anomaly rationales. TSB-AD-U was rejected as it is a well-known benchmark already in use.

### Approved Concepts
- VisAnomReasoner: Introduces a parameter-efficient architecture tailored for grounded VLM-based time-series anomaly detection, bridging the gap between natural language rationales and sequential data.

### Rejected Candidates
- [dataset] TSB-AD-U (`tsb-ad-u`) - duplicate_existing: TSB-AD-U is an existing, established collection of time-series anomaly detection benchmarks rather than a new core contribution of this work.

## Datasets

- [[visanombench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.30344)
- [PDF](https://arxiv.org/pdf/2605.30344)

