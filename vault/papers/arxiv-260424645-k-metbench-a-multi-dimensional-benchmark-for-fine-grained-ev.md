---
# CSL-compatible fields
title: "K-MetBench: A Multi-Dimensional Benchmark for Fine-Grained Evaluation of Expert Reasoning, Locality, and Multimodality in Meteorology"
author:
  - literal: "Soyeon Kim"
  - literal: "Cheongwoong Kang"
  - literal: "Myeongjin Lee"
  - literal: "Eun-Chul Chang"
  - literal: "Jaedeok Lee"
  - literal: "Jaesik Choi"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24645"

# Custom fields
paper_id: "2604.24645"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "llm-as-a-judge-for-time-series-explanations"
  - "expert-decoupling-driving-vlas"
architectures:
  []
datasets:
  - "K-MetBench"
concept_slugs:
  - "k-metbench"
dataset_slugs:
  - "k-metbench"
skill: "GeneralMLSkill"
processed_at: "2026-04-28T05:13:41Z"
created_at: "2026-04-28T05:13:41Z"
---

# K-MetBench: A Multi-Dimensional Benchmark for Fine-Grained Evaluation of Expert Reasoning, Locality, and Multimodality in Meteorology

**Authors**: Soyeon Kim, Cheongwoong Kang, Myeongjin Lee, Eun-Chul Chang, Jaedeok Lee, Jaesik Choi
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24645](https://arxiv.org/abs/2604.24645)

## Summary

K-MetBench is a new diagnostic benchmark designed to evaluate multimodal large language models on meteorology-specific tasks, grounding its questions in official Korean national qualification exams. The benchmark assesses models across four critical dimensions: visual chart reasoning, logical consistency, Korean geo-cultural knowledge, and domain-specific accuracy. Evaluation of 55 models reveals that while models may predict weather outcomes correctly, they often rely on hallucinated logical rationales, and global models struggle significantly with local context compared to region-specific counterparts.

## Key Contributions

- Introduces K-MetBench, a multi-dimensional benchmark for meteorology that evaluates expert visual reasoning, logical validity, and geo-cultural comprehension.
- Reveals a pervasive modality gap in specialized diagram interpretation and a reasoning gap where models provide correct predictions based on hallucinated logic.
- Demonstrates that smaller, region-specific models outperform larger global models in local context, highlighting the insufficiency of parameter scaling for cultural dependencies.

## Open Questions & Future Work

- [[temporal-visual-reasoning-meteorology]]
- [[generalizability-geo-cultural-meteorology-benchmarks]]

## Key Concepts

- [[k-metbench]]: A diagnostic benchmark grounded in national meteorology qualification exams for evaluating expert-level multimodal reasoning.

## Archivist Review

I approved the K-MetBench benchmark and dataset as it represents a robust template for qualification-grounded evaluation in specialized domains. The open questions regarding temporal visual reasoning and cross-regional generalizability represent significant, reusable bottlenecks in the field of AI-driven meteorology.

### Approved Concepts
- K-MetBench: Provides a novel framework for evaluating expert reasoning, locality, and multimodality in meteorology.

### Approved Open Questions
- Temporal Visual Reasoning in Meteorology: Real-world weather forecasting is inherently dynamic; static analysis is insufficient for predictive modeling. Understanding how models handle temporal atmospheric data is crucial for their reliable deployment as forecasting assistants.
- Generalizing Meteorological Benchmarks Across Regions: Meteorological requirements vary drastically across regions due to unique topographical and climatic factors. A truly robust AI agent must demonstrate performance consistency across diverse global contexts, which requires scalable adaptation strategies.

## Datasets

- [[k-metbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.24645)
- [PDF](https://arxiv.org/pdf/2604.24645)

