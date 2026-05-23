---
# CSL-compatible fields
title: "Forecasting Scientific Progress with Artificial Intelligence"
author:
  - literal: "Sean Wu"
  - literal: "Pan Lu"
  - literal: "Yupeng Chen"
  - literal: "Jonathan Bragg"
  - literal: "Yutaro Yamada"
  - literal: "Peter Clark"
  - literal: "David Clifton"
  - literal: "Philip Torr"
  - literal: "James Zou"
  - literal: "Junchi Yu"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22681"

# Custom fields
paper_id: "2605.22681"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "benchmarking"
  - "forecasting"
  - "reasoning"
  - "scientific-discovery"
architectures:
  []
datasets:
  - "cusp-benchmark-dataset"
concept_slugs:
  - "cusp-benchmark"
dataset_slugs:
  - "cusp-benchmark-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-23T05:20:11Z"
created_at: "2026-05-23T05:20:11Z"
---

# Forecasting Scientific Progress with Artificial Intelligence

**Authors**: Sean Wu, Pan Lu, Yupeng Chen, Jonathan Bragg, Yutaro Yamada, Peter Clark, David Clifton, Philip Torr, James Zou, Junchi Yu
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22681](https://arxiv.org/abs/2605.22681)

## Summary

The paper introduces CUSP (Cutoff-conditioned Unseen Scientific Progress), a novel benchmark for evaluating the ability of AI models to forecast scientific developments across multiple domains. Through testing 4,760 events, the authors demonstrate that while models can identify research directions, they consistently fail to predict whether scientific milestones will be achieved or when they will occur. The findings reveal that these forecasting failures are not solely due to lack of training data, but rather fundamental limitations in model reasoning, uncertainty estimation, and predictive foresight.

## Key Contributions

- Introduced CUSP, a benchmark of 4,760 scientific events for evaluating AI models on scientific forecasting tasks.
- Demonstrated that current frontier models reliably identify plausible research directions but fail to predict the realization or timing of scientific advances.
- Revealed that scientific forecasting limitations persist regardless of training cutoff dates and are exacerbated by systematic model overconfidence.

## Key Concepts

- [[cusp-benchmark]]: A multi-disciplinary benchmark designed to evaluate AI systems' ability to forecast scientific progress through feasibility, reasoning, and temporal prediction tasks.

## Archivist Review

I have approved the CUSP benchmark and its corresponding dataset as they introduce a standardized evaluation paradigm for scientific forecasting. This benchmark effectively isolates the challenge of predicting scientific breakthroughs by controlling knowledge access relative to time-based cutoffs, which is a novel contribution to time-series forecasting in scientific domains. I have rejected no candidates as none were provided other than the central contributions.

### Approved Concepts
- CUSP (Cutoff-conditioned Unseen Scientific Progress): It is the first systematic, temporally-grounded benchmark specifically designed to test the ability of LLMs to forecast scientific breakthroughs under controlled information constraints.

## Datasets

- [[cusp-benchmark-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.22681)
- [PDF](https://arxiv.org/pdf/2605.22681)

