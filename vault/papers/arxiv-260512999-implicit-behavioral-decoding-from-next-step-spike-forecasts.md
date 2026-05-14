---
# CSL-compatible fields
title: "Implicit Behavioral Decoding from Next-Step Spike Forecasts at Population Scale"
author:
  - literal: "John R. Minnick"
  - literal: "Jesus Gonzalez-Ferrer"
  - literal: "Kamran Hussain"
  - literal: "Jinghui Geng"
  - literal: "Ash Robbins"
  - literal: "Mohammed A. Mostajo-Radji"
  - literal: "David Haussler"
  - literal: "Jason Eshraghian"
  - literal: "Mircea Teodorescu"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.12999"

# Custom fields
paper_id: "2605.12999"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "steinmetz-visual-discrimination-benchmark"
concept_slugs:
  - "implicit-behavioral-decoding"
dataset_slugs:
  - "steinmetz-visual-discrimination-benchmark"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:25:07Z"
created_at: "2026-05-14T05:25:07Z"
---

# Implicit Behavioral Decoding from Next-Step Spike Forecasts at Population Scale

**Authors**: John R. Minnick, Jesus Gonzalez-Ferrer, Kamran Hussain, Jinghui Geng, Ash Robbins, Mohammed A. Mostajo-Radji, David Haussler, Jason Eshraghian, Mircea Teodorescu
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.12999](https://arxiv.org/abs/2605.12999)

## Summary

This paper introduces a closed-loop BCI approach where a single Mamba forecaster is trained to predict future neural spike counts, simultaneously serving as a feature extractor for behavioral state decoding. By training only on population-scale spike data, the model's internal representation of predicted rates facilitates more accurate decoding of animal choice and stimulus side compared to raw spike counts. The method demonstrates robust performance on the Steinmetz dataset, with efficient calibration and latency profiles suitable for real-time neural interface applications.

## Key Contributions

- Demonstrates that a single Mamba model trained for next-step spike forecasting can perform downstream behavioral decoding in a single forward pass.
- Shows that linear decoding from Mamba-predicted rates outperforms direct decoding from raw spike counts by 4-6 pp in trial choice and stimulus side accuracy.
- Achieves near-asymptotic behavioral decoding performance with only 100-150 calibration trials and inference within a 50 ms latency constraint suitable for real-time BCI.

## Open Questions & Future Work

- [[closed-loop-bci-robustness]]

## Key Concepts

- [[implicit-behavioral-decoding]]: The use of neural population spike forecasting models to implicitly derive behavioral state representations for downstream tasks.

## Archivist Review

The paper proposes a novel use of neural forecasting models for implicit behavioral decoding. I approved this concept as it represents a significant shift from traditional task-specific decoding, and I approved the open question concerning the robustness of these closed-loop pipelines. I rejected 'Mamba' as it is a well-established architecture already represented in the field.

### Approved Concepts
- Implicit Behavioral Decoding: It defines a novel paradigm where neural forecasting models serve as feature extractors for downstream behavioral states without task-specific training.

### Approved Open Questions
- Closed-loop BCI Robustness: This addresses the gap between predictive performance in static benchmarks and real-world utility in autonomous closed-loop brain-computer interfaces.

### Rejected Candidates
- [concept] Mamba (`mamba`) - duplicate_existing: Mamba is a general-purpose architecture already widely known; its application here is a specific instantiation rather than a unique concept.

## Datasets

- [[steinmetz-visual-discrimination-benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2605.12999)
- [PDF](https://arxiv.org/pdf/2605.12999)

