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
  - "causal-inference-derived-outcomes"
architectures:
  []
datasets:
  - "query2effect"
concept_slugs:
  - "query2effect"
dataset_slugs:
  - "query2effect"
skill: "TimeSeriesSkill"
processed_at: "2026-05-29T05:36:33Z"
created_at: "2026-05-29T05:36:33Z"
---

# Predicting Causal Effects from Natural Language Queries using Structured Representations

**Authors**: Giuliano Martinelli, Piriyakorn Piriyatamwong, Abelardo Carlos Martinez Lorenzo, Jasmin Baier, Riccardo Orlando, Satvik Garg, Sharif Kazemi, Linxi Wang, Arianna Legovini, Samuel Fraiberger
**Date**: 2026-05-28
**Paper ID**: [arxiv:2605.29631](https://arxiv.org/abs/2605.29631)

## Summary

This paper addresses the challenge of predicting causal effect sizes from natural language queries by leveraging LLMs and structured representations. The authors introduce Query2Effect, a large-scale benchmark of 72,000 queries based on experimental metadata, and propose a modular two-step framework for interpretation and estimation. Their results highlight the importance of separating semantic parsing from numerical prediction, showing that this approach improves out-of-domain generalization and prediction accuracy compared to direct prompting methods.

## Key Contributions

- Introduces Query2Effect, a benchmark of over 72,000 natural language questions designed to test causal effect estimation across varying levels of query ambiguity and abstraction.
- Proposes a two-step framework that decomposes the problem into semantic query interpretation (structured representation generation) followed by supervised effect size prediction.
- Demonstrates that fine-tuning significantly outperforms out-of-the-box LLM prompting, achieving 27% to 71% reductions in absolute prediction error.

## Key Concepts

- [[query2effect]]: A large-scale benchmark of over 72,000 natural language questions aligned with randomized controlled trial descriptions for causal effect size forecasting.

## Archivist Review

I approved the Query2Effect benchmark as a standalone note because it establishes a unique, large-scale resource for evaluating causal effect size forecasting from language, which is distinct from current vault entries. I rejected any internal sub-frameworks as they represent modular implementation choices rather than fundamentally novel techniques. My review followed the principle of scarcity, focusing only on the primary contribution that will serve as a foundational benchmark in future studies.

### Approved Concepts
- Query2Effect: It is the primary benchmark introduced to evaluate causal effect estimation from natural language queries, addressing the need for systematic testing of LLMs in experimental causal inference.

## Datasets

- [[query2effect]]

## Links

- [Abstract](https://arxiv.org/abs/2605.29631)
- [PDF](https://arxiv.org/pdf/2605.29631)

