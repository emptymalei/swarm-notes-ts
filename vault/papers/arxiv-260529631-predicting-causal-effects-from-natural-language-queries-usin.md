---
# CSL-compatible fields
title: "Predicting Causal Effects from Natural Language Queries using Structured Representations"
author:
  - literal: "Giuliano Martinelli"
  - literal: "Piriyakorn Piriyatamwong"
  - literal: "Abelardo Carlos Martinez Lorenzo"
  - literal: "Jasmin Baier"
  - literal: "Riccardo Orlando"
  - literal: "Satvik Garg"
  - literal: "Sharif Kazemi"
  - literal: "Linxi Wang"
  - literal: "Arianna Legovini"
  - literal: "Samuel Fraiberger"
issued:
  date-parts:
    - [2026, 5, 28]
url: "https://arxiv.org/abs/2605.29631"

# Custom fields
paper_id: "2605.29631"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "causal-inference"
  - "large-language-models"
  - "benchmarking"
architectures:
  []
datasets:
  - "query2effect"
concept_slugs:
  - "query2effect"
dataset_slugs:
  - "query2effect"
skill: "TimeSeriesSkill"
processed_at: "2026-05-30T05:25:02Z"
created_at: "2026-05-30T05:25:02Z"
---

# Predicting Causal Effects from Natural Language Queries using Structured Representations

**Authors**: Giuliano Martinelli, Piriyakorn Piriyatamwong, Abelardo Carlos Martinez Lorenzo, Jasmin Baier, Riccardo Orlando, Satvik Garg, Sharif Kazemi, Linxi Wang, Arianna Legovini, Samuel Fraiberger
**Date**: 2026-05-28
**Paper ID**: [arxiv:2605.29631](https://arxiv.org/abs/2605.29631)

## Summary

This paper investigates the feasibility of using LLMs to forecast causal effect sizes from natural language queries. The authors introduce the Query2Effect benchmark, which challenges models to interpret diverse queries with varying degrees of implicitness, abstraction, and ambiguity. They propose a two-step framework that first converts natural language queries into structured representations before performing supervised effect size estimation. This separation of semantic interpretation and numerical prediction improves performance and enhances out-of-domain generalization.

## Key Contributions

- Introduced Query2Effect, a large-scale benchmark of over 72,000 natural language queries paired with experimental descriptions to evaluate causal effect estimation.
- Proposed a two-step causal effect forecasting framework that separates semantic query interpretation from numerical effect estimation using a structured representation.
- Demonstrated that finetuning significantly outperforms zero-shot LLM prompts, reducing absolute error by 27% to 71% across the evaluated tasks.

## Key Concepts

- [[query2effect]]: A large-scale benchmark containing over 72,000 natural language questions aligned with experiment descriptions for causal effect size forecasting.

## Archivist Review

I approved the Query2Effect benchmark as a standalone dataset and concept note, as it provides a standardized, large-scale resource for causal effect forecasting that is likely to be a recurring reference point in the literature. I rejected no other candidates, as none were proposed by the user, and the paper's primary contribution is the benchmark itself rather than a novel, reusable algorithmic mechanism.

### Approved Concepts
- Query2Effect: This is the primary benchmark introduced to standardize the task of predicting causal effect sizes from natural language queries.

## Datasets

- [[query2effect]]

## Links

- [Abstract](https://arxiv.org/abs/2605.29631)
- [PDF](https://arxiv.org/pdf/2605.29631)

