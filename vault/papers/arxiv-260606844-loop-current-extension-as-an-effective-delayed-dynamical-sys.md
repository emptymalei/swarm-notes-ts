---
# CSL-compatible fields
title: "Loop Current Extension as an Effective Delayed Dynamical System"
author:
  - literal: "Francisco J. Beron-Vera"
  - literal: "María J. Olascoaga"
  - literal: "Philippe Miron"
issued:
  date-parts:
    - [2026, 6, 5]
url: "https://arxiv.org/abs/2606.06844"

# Custom fields
paper_id: "2606.06844"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "dynamical-systems"
  - "oceanography"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "delayed-coordinate-representations"
  - "delayed-sindy"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-08T05:48:46Z"
created_at: "2026-06-08T05:48:46Z"
---

# Loop Current Extension as an Effective Delayed Dynamical System

**Authors**: Francisco J. Beron-Vera, María J. Olascoaga, Philippe Miron
**Date**: 2026-06-05
**Paper ID**: [arxiv:2606.06844](https://arxiv.org/abs/2606.06844)

## Summary

This paper characterizes the Loop Current extension in the Gulf of Mexico as a low-dimensional delayed dynamical system by applying delayed-coordinate reconstruction to satellite altimetry. By utilizing ridge regression, multilayer perceptron forecasting, and Sparse Identification of Nonlinear Dynamics (SINDy), the authors identify compact, stable evolution maps that capture predictable variability. The results demonstrate that these delayed-coordinate representations achieve superior forecasting performance compared to persistence at lead times of 30-90 days, while rendering external physical diagnostic variables redundant.

## Key Contributions

- Demonstrated that Loop Current extension dynamics can be effectively modeled as a low-dimensional delayed dynamical system.
- Showed that delayed-coordinate representations outperform persistence in 30–90 day forecasting horizons using sparse evolution maps.
- Established that physical diagnostic variables provide no additional predictive power once the delayed-state representation of the Loop Current is accounted for.

## Key Concepts

- [[delayed-coordinate-representations]]: A method for reconstructing the state space of a dynamical system using lagged observations of a single variable.
- [[delayed-sindy]]: An adaptation of SINDy that operates on delayed-coordinate state spaces to discover parsimonious governing equations.

## Archivist Review

The paper introduces a compelling application of delayed-state space reconstruction to complex climate phenomena. The approved concepts are fundamental methods for discovering parsimonious dynamics in time-series data with latent memory effects, which are likely to recur in scientific forecasting tasks. I have rejected no candidates as none were proposed for datasets or open questions.

### Approved Concepts
- Delayed-Coordinate Representations: Central technique for constructing the reduced-order dynamical system from time-series observations.
- Delayed SINDy: The paper highlights the use of Sparse Identification of Nonlinear Dynamics (SINDy) on delayed coordinates as a key finding for stability and interpretability.

## Links

- [Abstract](https://arxiv.org/abs/2606.06844)
- [PDF](https://arxiv.org/pdf/2606.06844)

