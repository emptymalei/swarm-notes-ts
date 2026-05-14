---
# CSL-compatible fields
title: "SpikeProphecy: A Large-Scale Benchmark for Autoregressive Neural Population Forecasting"
author:
  - literal: "John R. Minnick"
  - literal: "Jinghui Geng"
  - literal: "Kamran Hussain"
  - literal: "Jesus Gonzalez-Ferrer"
  - literal: "Ash Robbins"
  - literal: "Mohammed A. Mostajo-Radji"
  - literal: "David Haussler"
  - literal: "Jason K. Eshraghian"
  - literal: "Mircea Teodorescu"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.12992"

# Custom fields
paper_id: "2605.12992"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "steinmetz-2019-ibl-dataset"
concept_slugs:
  - "population-metric-decomposition"
dataset_slugs:
  - "steinmetz-2019-ibl-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:25:15Z"
created_at: "2026-05-14T05:25:15Z"
---

# SpikeProphecy: A Large-Scale Benchmark for Autoregressive Neural Population Forecasting

**Authors**: John R. Minnick, Jinghui Geng, Kamran Hussain, Jesus Gonzalez-Ferrer, Ash Robbins, Mohammed A. Mostajo-Radji, David Haussler, Jason K. Eshraghian, Mircea Teodorescu
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.12992](https://arxiv.org/abs/2605.12992)

## Summary

SpikeProphecy is a large-scale benchmark for evaluating autoregressive neural population forecasting on high-density electrophysiology data. The authors address the inadequacy of aggregate Pearson correlation by introducing a population metric decomposition that isolates temporal fidelity, spatial pattern accuracy, and magnitude-invariant alignment. Applying this framework across seven model architectures, the study reveals robust regional predictability patterns and highlights significant biophysical constraints on spike-train forecasting.

## Key Contributions

- Introduces SpikeProphecy, the first large-scale benchmark for causal autoregressive spike-count forecasting on electrophysiology data.
- Proposes a population metric decomposition that separates aggregate forecasting performance into distinct temporal, spatial, and magnitude components.
- Demonstrates a consistent brain-region predictability ranking across diverse architectures, accounting for firing-statistics constraints.

## Open Questions & Future Work

- [[modeling-and-evaluating-sub-poisson-neurons]]

## Key Concepts

- [[population-metric-decomposition]]: A systematic evaluation framework that decomposes aggregate neural forecasting performance into independent temporal, spatial, and magnitude-invariant components.

## Archivist Review

Approved the population metric decomposition as it provides a valuable, reusable framework for multivariate sequence evaluation. The Steinmetz/IBL data was combined into a single, standard reference dataset note. The sub-Poisson neurons question was approved for its focus on a specific, theoretically grounded hurdle in time-series forecasting, while the distillation question was rejected as being too focused on local empirical findings.

### Approved Concepts
- Population metric decomposition: It addresses the critical limitation where single aggregate metrics (like Pearson correlation) mask important structural information in neural population forecasting.

### Approved Open Questions
- Modeling and evaluating sub-Poisson neurons: Standard aggregate metrics currently mask model improvements in regular-firing neurons, leading to misinterpretations of model performance and hindering the development of architectures capable of capturing precise intrinsic neural dynamics.

### Rejected Candidates
- [open_question] Distillation efficacy in neural forecasting (`distillation-efficacy-in-neural-forecasting`) - paper_local: The open question is too tied to the specific empirical negative result (KL-on-output-rates) in a single domain rather than a broad, actionable bottleneck in model design.

## Datasets

- [[steinmetz-2019-ibl-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.12992)
- [PDF](https://arxiv.org/pdf/2605.12992)

