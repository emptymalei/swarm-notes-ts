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
  - "multimodal-learning"
  - "evaluation-benchmarks"
  - "large-language-models"
architectures:
  []
datasets:
  - "K-MetBench"
concept_slugs:
  - "k-metbench"
dataset_slugs:
  - "k-metbench"
skill: "GeneralMLSkill"
processed_at: "2026-04-29T05:13:16Z"
created_at: "2026-04-29T05:13:16Z"
---

# K-MetBench: A Multi-Dimensional Benchmark for Fine-Grained Evaluation of Expert Reasoning, Locality, and Multimodality in Meteorology

**Authors**: Soyeon Kim, Cheongwoong Kang, Myeongjin Lee, Eun-Chul Chang, Jaedeok Lee, Jaesik Choi
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24645](https://arxiv.org/abs/2604.24645)

## Summary

K-MetBench is a new multidimensional benchmark developed to evaluate the performance of multimodal large language models in the specialized domain of meteorology. By leveraging content from national qualification exams, the benchmark assesses model capabilities across visual reasoning, logical validity, and local geo-cultural comprehension. Evaluating 55 models, the study uncovers persistent gaps in specialized diagram interpretation and logical consistency, while highlighting that region-specific models are superior to large global models for local meteorological contexts.

## Key Contributions

- Introduces K-MetBench, a diagnostic benchmark designed for evaluating multimodal large language models in meteorology based on national qualification exams.
- Identifies a significant modality gap in interpreting specialized meteorological diagrams and a reasoning gap where models provide correct predictions with hallucinated logic.
- Demonstrates that smaller, region-specific models often outperform larger global models in local geo-cultural contexts, highlighting the insufficiency of parameter scaling alone.

## Open Questions & Future Work

- [[temporal-visual-reasoning-meteorology]]
- [[cross-region-generalizability-meteorological-benchmarks]]

## Key Concepts

- [[k-metbench]]: A multidimensional, expert-level diagnostic benchmark for evaluating multimodal models on meteorological tasks, including visual reasoning, logical validity, and local geo-cultural comprehension.

## Archivist Review

The benchmark and its associated dataset are approved as they represent a structured approach to expert-domain evaluation. The open questions highlight the fundamental tension between static benchmarking and the temporal requirements of meteorology, as well as the inherent difficulty of scaling geo-specific evaluation protocols.

### Approved Concepts
- K-MetBench: It provides a standardized, domain-specific benchmark for evaluating LLMs on expert-level meteorological reasoning and multimodality in a local context.

### Approved Open Questions
- Temporal Visual Reasoning in Meteorology: Temporal reasoning is fundamental to operational forecasting, yet most current benchmarks rely on static, single-frame interpretation which masks models' inability to track atmospheric dynamics.
- Cross-Region Generalizability of Benchmarks: Meteorological AI requires global utility, but geo-cultural sensitivities create significant barriers to zero-shot deployment; tracking benchmark generalizability is key to scalable, domain-aware AI.

## Datasets

- [[k-metbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.24645)
- [PDF](https://arxiv.org/pdf/2604.24645)

