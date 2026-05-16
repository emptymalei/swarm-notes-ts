---
# CSL-compatible fields
title: "SciPaths: Forecasting Pathways to Scientific Discovery"
author:
  - literal: "Eric Chamoun"
  - literal: "Yizhou Chi"
  - literal: "Yulong Chen"
  - literal: "Rui Cao"
  - literal: "Zifeng Ding"
  - literal: "Michalis Korakakis"
  - literal: "Andreas Vlachos"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14600"

# Custom fields
paper_id: "2605.14600"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "forecasting"
  - "scientific-discovery"
  - "reasoning"
  - "benchmark"
architectures:
  []
datasets:
  - "scipaths"
concept_slugs:
  - "discovery-pathway-forecasting"
dataset_slugs:
  - "scipaths"
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:28Z"
created_at: "2026-05-16T05:12:28Z"
---

# SciPaths: Forecasting Pathways to Scientific Discovery

**Authors**: Eric Chamoun, Yizhou Chi, Yulong Chen, Rui Cao, Zifeng Ding, Michalis Korakakis, Andreas Vlachos
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14600](https://arxiv.org/abs/2605.14600)

## Summary

SciPaths introduces discovery pathway forecasting, a task that requires models to reverse-engineer scientific discoveries by identifying and grounding the necessary enabling contributions in prior literature. The authors release the SciPaths benchmark, which includes expert-annotated and silver-labeled pathways within ML and NLP research. Their evaluation reveals that current LLMs struggle with end-to-end pathway recovery, particularly in capturing core methodological dependencies, highlighting a critical gap in scientific forecasting capabilities.

## Key Contributions

- Introduced discovery pathway forecasting as a formal task for identifying the hierarchical dependencies and enabling contributions behind scientific discoveries.
- Released SciPaths, a benchmark consisting of 262 expert-annotated gold pathways and 2,444 silver pathways derived from the ML and NLP literature.
- Evaluated frontier and open-weight models, demonstrating that end-to-end pathway recovery is limited by decomposition performance, with core methodological dependencies presenting the greatest challenge.

## Open Questions & Future Work

- [[scientific-dependency-decomposition-bottleneck]]

## Key Concepts

- [[discovery-pathway-forecasting]]: A task-based framework for identifying and grounding the sequences of enabling contributions that lead to a specific scientific discovery.

## Archivist Review

The approved items establish a new task-based framework for scientific forecasting that moves beyond simple citation metrics. I have prioritized the definition of the 'discovery pathway forecasting' task and its primary performance bottleneck as they represent fundamental conceptual advances for future research in AI-driven scientific reasoning. Other candidates were rejected to maintain strict adherence to the scarcity guidelines and the focus on reusable, high-level structural contributions.

### Approved Concepts
- Discovery pathway forecasting: This task frames scientific discovery as a structural dependency problem rather than simple link prediction or retrieval, shifting how scientific progress can be evaluated.

### Approved Open Questions
- Scientific Dependency Decomposition Bottleneck: Addressing this bottleneck is essential for transitioning scientific AI from retrieval and link prediction tasks to systems capable of reasoning about the actual functional dependency structure of scientific advancement.

## Datasets

- [[scipaths]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14600)
- [PDF](https://arxiv.org/pdf/2605.14600)

