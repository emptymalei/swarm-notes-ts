---
# CSL-compatible fields
title: "Early-Warning Learner Satisfaction Forecasting in MOOCs via Temporal Event Transformers and LLM Text Embeddings"
author:
  - literal: "Anna Kowalczyk"
  - literal: "Jakub Kowalski"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.13241"

# Custom fields
paper_id: "2604.13241"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
  - "forecasting"
  - "multi-modal"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tet-llm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:07:18Z"
created_at: "2026-04-16T05:07:18Z"
---

# Early-Warning Learner Satisfaction Forecasting in MOOCs via Temporal Event Transformers and LLM Text Embeddings

**Authors**: Anna Kowalczyk, Jakub Kowalski
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.13241](https://arxiv.org/abs/2604.13241)

## Summary

This paper addresses the problem of early-warning learner satisfaction forecasting in MOOCs to enable timely interventions. The authors introduce TET-LLM, a multi-modal fusion framework that integrates temporal behavioral event sequences with contextual LLM-based text embeddings and topic distributions. The model utilizes a heteroscedastic regression head to provide both point predictions and uncertainty scores, ensuring reliable decision-making. Empirical results on large-scale MOOC datasets show significant performance improvements over traditional baselines across various early-stage forecasting horizons.

## Key Contributions

- Proposes TET-LLM, a multi-modal framework for early-warning satisfaction forecasting using behavioral event sequences and LLM text embeddings.
- Implements a heteroscedastic regression head for joint point estimate and predictive uncertainty quantification in learner satisfaction.
- Demonstrates superior performance on multi-platform MOOC data, achieving 0.82 RMSE and 0.77 AUC at the 7-day early horizon.

## Open Questions & Future Work

- [[late-breaking-satisfaction-forecasting]]
- [[causal-intervention-mooc-satisfaction]]

## Key Concepts

- [[tet-llm]]: A multi-modal forecasting framework that fuses temporal behavioral event sequences with LLM-derived textual embeddings and topic distributions.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 2 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- TET-LLM: The framework represents a systematic approach to fusing fine-grained sequential behavioral data with semantic textual embeddings for predictive forecasting, a common requirement in user-behavior modeling.

### Approved Open Questions
- Horizon-Adaptive Satisfaction Forecasting: This identifies a fundamental limitation in current early-warning paradigms that restrict predictions to fixed, narrow observation windows.
- Causal Intervention in Forecasting: Moving from predictive to causal models is critical for translating model outputs into actionable and ethically sound interventions in sensitive domains.

### Rejected Candidates
- [open_question] Late-Breaking MOOC Satisfaction Forecasting (`late-breaking-satisfaction-forecasting`) - other: The original title was slightly rephrased to be more descriptive of the technical challenge rather than the specific failure mode in MOOCs.

## Links

- [Abstract](https://arxiv.org/abs/2604.13241)
- [PDF](https://arxiv.org/pdf/2604.13241)

