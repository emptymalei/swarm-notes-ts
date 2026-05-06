---
# CSL-compatible fields
title: "Can Transformers predict system collapse in dynamical systems?"
author:
  - literal: "Zheng-Meng Zhai"
  - literal: "Celso Grebogi"
  - literal: "Ying-Cheng Lai"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04024"

# Custom fields
paper_id: "2605.04024"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "parameter-space-extrapolation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:11:03Z"
created_at: "2026-05-06T05:11:03Z"
---

# Can Transformers predict system collapse in dynamical systems?

**Authors**: Zheng-Meng Zhai, Celso Grebogi, Ying-Cheng Lai
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04024](https://arxiv.org/abs/2605.04024)

## Summary

This paper investigates whether Transformer-based foundation models can serve as reliable digital twins for nonlinear dynamical systems, specifically regarding their ability to generalize to unseen parameter regimes. By comparing Transformers against reservoir computing on a benchmark task involving the prediction of catastrophic collapse at critical bifurcation thresholds, the study finds that Transformers fail to capture these transitions. The findings indicate that, unlike reservoir computing, standard Transformer architectures may lack the necessary temporal structural induction to handle parameter-space extrapolation in physical systems.

## Key Contributions

- Establishes that standard Transformer architectures struggle to generalize to unseen parameter regimes in nonlinear dynamical systems compared to reservoir computing.
- Demonstrates that Transformers consistently fail to predict catastrophic collapse in dynamical systems when trained only on normal parameter regimes.
- Provides a rigorous benchmark for evaluating the out-of-distribution generalization of foundation models for physical dynamics.

## Open Questions & Future Work

- [[transformer-extrapolation-failure-dynamical-systems]]

## Key Concepts

- [[parameter-space-extrapolation]]: The capacity of a model to generalize its dynamics predictions to parameter regimes unseen during training, specifically involving bifurcations or state transitions.

## Archivist Review

I approved one concept and one open question. The concept 'Parameter-Space Extrapolation' is a vital distinction for the field of scientific machine learning, moving beyond standard interpolation metrics. The open question formalizes the fundamental architectural limitation identified by the authors, distinguishing between sequence-based learners and physical dynamical system models.

### Approved Concepts
- Parameter-Space Extrapolation: The paper distinguishes between standard time-series forecasting and the ability to generalize across different dynamical system regimes, a critical requirement for digital twins.

### Approved Open Questions
- Transformer Extrapolation Failure: This question addresses a fundamental limitation of current foundation models for physical dynamics and scientific discovery, highlighting the trade-off between architectural flexibility and inductive physical priors.

## Links

- [Abstract](https://arxiv.org/abs/2605.04024)
- [PDF](https://arxiv.org/pdf/2605.04024)

