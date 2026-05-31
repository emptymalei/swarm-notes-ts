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
  []
architectures:
  []
datasets:
  - "Query2Effect"
concept_slugs:
  []
dataset_slugs:
  - "query2effect"
skill: "TimeSeriesSkill"
processed_at: "2026-05-31T05:39:20Z"
created_at: "2026-05-31T05:39:20Z"
---

# Predicting Causal Effects from Natural Language Queries using Structured Representations

**Authors**: Giuliano Martinelli, Piriyakorn Piriyatamwong, Abelardo Carlos Martinez Lorenzo, Jasmin Baier, Riccardo Orlando, Satvik Garg, Sharif Kazemi, Linxi Wang, Arianna Legovini, Samuel Fraiberger
**Date**: 2026-05-28
**Paper ID**: [arxiv:2605.29631](https://arxiv.org/abs/2605.29631)

## Summary

This paper investigates the feasibility of using large language models to forecast causal effect sizes from natural language queries. The authors introduce Query2Effect, a benchmark of 72,000 queries designed to test model performance across varying levels of abstraction and ambiguity. They propose a two-step approach that synthesizes a structured query representation before employing a supervised encoder for estimation. Results indicate that decoupling semantic interpretation from numerical prediction significantly improves generalization, particularly when fine-tuned on the provided benchmark.

## Key Contributions

- Introduced Query2Effect, a large-scale benchmark of 72,000 natural language queries mapped to causal experiment descriptions.
- Proposed a two-step causal effect forecasting framework that decouples semantic query interpretation from numerical estimation.
- Demonstrated that fine-tuning on structured representations reduces absolute error by 27% to 71% compared to zero-shot LLM prompts.

## Archivist Review

I approved Query2Effect as a critical dataset for evaluating causal effect forecasting from natural language. I rejected the concept candidate because it was fundamentally a dataset artifact, which is already handled appropriately within the approved datasets list.

### Rejected Candidates
- [concept] Query2Effect (`query2effect`) - subcomponent_of_broader_mechanism: The benchmark Query2Effect is primarily a dataset, and its inclusion in the datasets category is sufficient.

## Datasets

- [[query2effect]]

## Links

- [Abstract](https://arxiv.org/abs/2605.29631)
- [PDF](https://arxiv.org/pdf/2605.29631)

