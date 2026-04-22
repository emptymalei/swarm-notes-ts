---
# CSL-compatible fields
title: "State Forecasting in an Estimation Framework with Surrogate Sensor Modeling"
author:
  - literal: "Sriram Narayanan"
  - literal: "Mohamed Naveed Gul Mohamed"
  - literal: "Ishan Paranjape"
  - literal: "Indranil Nayak"
  - literal: "Suman Chakravorty"
  - literal: "Mrinal Kumar"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19442"

# Custom fields
paper_id: "2604.19442"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "surrogate-measurement-model-fusion"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:03:45Z"
created_at: "2026-04-22T05:03:45Z"
---

# State Forecasting in an Estimation Framework with Surrogate Sensor Modeling

**Authors**: Sriram Narayanan, Mohamed Naveed Gul Mohamed, Ishan Paranjape, Indranil Nayak, Suman Chakravorty, Mrinal Kumar
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19442](https://arxiv.org/abs/2604.19442)

## Summary

This paper introduces a hybrid framework designed to improve state estimation for complex physical systems under partial observability, with a specific focus on tracking resident space objects. The approach integrates a simplified physics-based dynamics model with a data-driven surrogate measurement model to compensate for limited observational data from radar and optical sensors. Numerical experiments validate that this fusion technique robustly reconstructs system dynamics, offering a significant advancement for aerospace state estimation tasks.

## Key Contributions

- Proposes a hybrid framework for state estimation that fuses simplified physics-based reference dynamics with a data-driven surrogate measurement model.
- Demonstrates effective reconstruction of system dynamics under conditions of partial observability specifically for resident space object (RSO) tracking.
- Provides a formal consistency analysis of the surrogate modeling approach to ensure robustness in space situational awareness applications.

## Open Questions & Future Work

- [[double-dipping-in-iterative-surrogate-training]]

## Key Concepts

- [[surrogate-measurement-model-fusion]]: A state estimation framework that fuses simplified physics-based dynamics with a data-driven surrogate model to enhance reconstruction from partial observations.

## Archivist Review

The paper proposes a hybrid estimation framework that effectively combines physics-based dynamics with learned measurement surrogates. I approved the overarching fusion concept as it is a reusable architectural pattern for state-space problems. The open question regarding 'double dipping' in iterative surrogate training is a significant, fundamental theoretical concern in filtering and estimation research that warrants its own note.

### Approved Concepts
- Surrogate Measurement Model Fusion: This hybrid approach of merging physical dynamics with learned measurement surrogates provides a robust solution to partial observability, a key challenge in state estimation.

### Approved Open Questions
- Bias in iterative surrogate training: This is a fundamental challenge in combining machine learning-based surrogate modeling with traditional state estimation (filtering), as it directly affects the validity and consistency of the resulting state estimates.

## Links

- [Abstract](https://arxiv.org/abs/2604.19442)
- [PDF](https://arxiv.org/pdf/2604.19442)

