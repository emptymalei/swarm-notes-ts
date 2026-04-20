---
# CSL-compatible fields
title: "EVIL: Evolving Interpretable Algorithms for Zero-Shot Inference on Event Sequences and Time Series with LLMs"
author:
  - literal: "David Berghaus"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.15787"

# Custom fields
paper_id: "2604.15787"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "interpretability"
  - "zero-shot-learning"
  - "llm"
architectures:
  []
datasets:
  []
concept_slugs:
  - "llm-guided-program-evolution"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:10:28Z"
created_at: "2026-04-20T05:10:28Z"
---

# EVIL: Evolving Interpretable Algorithms for Zero-Shot Inference on Event Sequences and Time Series with LLMs

**Authors**: David Berghaus
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.15787](https://arxiv.org/abs/2604.15787)

## Summary

EVIL is an evolutionary search framework that utilizes LLMs to generate simple, interpretable Python algorithms for dynamical systems inference. By evolving programs rather than training neural networks, the approach enables zero-shot, in-context inference across multiple event sequence and time-series tasks. The discovered algorithms are shown to be highly compact and computationally efficient, outperforming complex deep learning baselines while maintaining complete transparency in their decision-making logic.

## Key Contributions

- Introduces EVIL, a method for discovering interpretable inference algorithms via LLM-guided evolutionary search of Python/NumPy programs.
- Achieves zero-shot inference capability across diverse dynamical systems, including temporal point processes, Markov jump processes, and time series imputation without per-dataset training.
- Demonstrates that evolved compact algorithms match or exceed state-of-the-art deep learning performance while providing full interpretability and superior computational efficiency.

## Open Questions & Future Work

- [[symbolic-vs-neural-inference-scalability]]

## Key Concepts

- [[llm-guided-program-evolution]]: The use of LLM-based search and mutation to discover compact, interpretable Python/NumPy code for zero-shot inference on dynamical systems.

## Archivist Review

I approved the concept of LLM-Guided Program Evolution as a novel, recurring methodology for symbolic discovery. I renamed the open question to focus on the fundamental tension between symbolic and neural approaches for complex dynamical systems, rather than the limitations of a specific framework. All branded names were discarded in favor of generalizable descriptive titles.

### Approved Concepts
- LLM-Guided Program Evolution: It shifts the paradigm from training opaque neural networks to discovering transparent, symbolic algorithms for dynamical systems using LLMs as search engines.

### Approved Open Questions
- Symbolic vs. Neural Inference Scalability: Bridging the gap between the transparency of evolved symbolic code and the predictive power/uncertainty quantification of neural models is essential for practical deployment in safety-critical systems.

### Rejected Candidates
- [concept] EVIL (Evolving Interpretable Algorithms with LLMs) (`evil-evolving-interpretable-algorithms-with-llms`) - other: The concept is renamed to 'LLM-Guided Program Evolution' to focus on the technical mechanism rather than the specific paper-branded acronym.
- [open_question] Limitations of Evolved Algorithms (`limitations-of-evolved-algorithms-for-dynamical-systems`) - other: Renamed to 'Symbolic vs. Neural Inference Scalability' for better encyclopedic clarity and alignment with long-term research tracking.

## Links

- [Abstract](https://arxiv.org/abs/2604.15787)
- [PDF](https://arxiv.org/pdf/2604.15787)

