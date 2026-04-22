---
# CSL-compatible fields
title: "Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs"
author:
  - literal: "Kevin Murphy"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18576"

# Custom fields
paper_id: "2604.18576"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "forecastbench"
concept_slugs:
  - "linguistic-belief-state"
dataset_slugs:
  - "forecastbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:05:34Z"
created_at: "2026-04-22T05:05:34Z"
---

# Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs

**Authors**: Kevin Murphy
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18576](https://arxiv.org/abs/2604.18576)

## Summary

The Bayesian Linguistic Forecaster (BLF) is an agentic system designed for high-accuracy binary forecasting that replaces linear context-appending with an iterative, semi-structured 'linguistic belief state'. By combining numerical probability estimates with summarized natural-language evidence, the system maintains focused reasoning over extended tool-use loops. BLF achieves state-of-the-art results on the ForecastBench benchmark through additional innovations in hierarchical multi-trial logit-space shrinkage and hierarchical Platt calibration. Ablation studies confirm these components collectively outperform competitive benchmarks while maintaining low data leakage.

## Key Contributions

- Introduced the Bayesian Linguistic Forecaster (BLF), an agentic system that utilizes iterative linguistic belief updates to achieve SOTA performance on binary forecasting tasks.
- Demonstrated that a semi-structured linguistic belief state significantly improves forecasting accuracy by avoiding the context-window limitations associated with appending raw retrieved evidence.
- Developed a robust back-testing framework and hierarchical aggregation/calibration methods that outperform leading models like GPT-5 and Grok-4.20 on 400 ForecastBench questions.

## Open Questions & Future Work

- [[agentic-forecasting-scalability-and-generalization]]

## Key Concepts

- [[linguistic-belief-state]]: A semi-structured representation that merges probability estimates with natural-language evidence, updated iteratively to maintain core forecasting belief states.

## Archivist Review

The paper introduces the 'Linguistic Belief State' as a novel way to manage evidence in agentic loops, which I have approved. I also approved the ForecastBench dataset for reusability in forecasting research. Other methods mentioned (aggregation and calibration) were deemed standard statistical techniques or subcomponents of the primary agentic framework and were therefore rejected. The open question was refined to be more concise and focused on the identified research gaps.

### Approved Concepts
- Linguistic Belief State: Provides a novel alternative to context-window-limited evidence aggregation in agentic forecasting.

### Approved Open Questions
- Scalability of Agentic Forecasting: Binary forecasting is a limited scope; general-purpose forecasting agents must be able to handle continuous variables and multiclass categorization to be useful in real-world scenarios.

### Rejected Candidates
- [concept] Hierarchical Multi-Trial Aggregation (`hierarchical-multi-trial-aggregation`) - subcomponent_of_broader_mechanism: This is a specific ensemble heuristic that, while effective, lacks the architectural significance of the primary contribution (linguistic belief state) and is arguably a standard statistical post-processing step.
- [concept] Hierarchical Calibration (`hierarchical-calibration`) - not_novel: This is a standard application of Platt scaling with a hierarchical prior, which is a common statistical technique rather than a novel conceptual contribution.

## Datasets

- [[forecastbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.18576)
- [PDF](https://arxiv.org/pdf/2604.18576)

