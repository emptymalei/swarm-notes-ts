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
  - "nlp"
architectures:
  []
datasets:
  - "scipaths"
concept_slugs:
  - "discovery-pathway-forecasting"
dataset_slugs:
  - "scipaths"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:10Z"
created_at: "2026-05-17T05:24:10Z"
---

# SciPaths: Forecasting Pathways to Scientific Discovery

**Authors**: Eric Chamoun, Yizhou Chi, Yulong Chen, Rui Cao, Zifeng Ding, Michalis Korakakis, Andreas Vlachos
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14600](https://arxiv.org/abs/2605.14600)

## Summary

SciPaths addresses the lack of benchmarks for reasoning about the causal dependencies behind scientific breakthroughs by introducing the discovery pathway forecasting task. This task requires models to identify the enabling contributions needed for a target scientific achievement and ground them in existing literature. Through the evaluation of several frontier language models, the authors demonstrate that current models struggle with complex methodological dependencies, establishing a new challenging benchmark for AI4Science.

## Key Contributions

- Introduces discovery pathway forecasting, a task focusing on identifying enabling contributions and prior-work dependencies for scientific research.
- Presents SciPaths, a benchmark consisting of 262 expert-annotated gold pathways and 2,444 silver pathways from ML and NLP literature.
- Evaluates frontier LLMs on the benchmark, showing that core methodological dependencies are a major bottleneck with current models achieving only 0.189 F1.

## Open Questions & Future Work

- [[methodological-dependency-inference]]

## Key Concepts

- [[discovery-pathway-forecasting]]: A task that requires reasoning backward from a scientific contribution to its required enabling contributions and prior work dependencies.

## Archivist Review

I approved the task definition and the associated dataset as they represent a novel, research-focused shift from traditional citation-based metrics to causal dependency chain modeling. The open question was approved for capturing the specific, non-trivial bottleneck identified by the authors in methodological dependency recovery. Other candidates were rejected to maintain the strict standard for scientific concept/question permanence.

### Approved Concepts
- Discovery Pathway Forecasting: Defines a new evaluation paradigm in AI4Science that focuses on causal dependency chains in scientific literature rather than simple citation prediction.

### Approved Open Questions
- Recovering Core Methodological Dependencies: The difficulty in recovering core methodological dependencies is a critical bottleneck in automated scientific forecasting.

## Datasets

- [[scipaths]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14600)
- [PDF](https://arxiv.org/pdf/2605.14600)

