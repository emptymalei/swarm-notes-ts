---
# CSL-compatible fields
title: "GlucoFM-Bench: Benchmarking Time-Series Foundation Models for Blood Glucose Forecasting"
author:
  - literal: "Baiying Lu"
  - literal: "Zhaohui Liang"
  - literal: "Ryan Pontius"
  - literal: "Shengpu Tang"
  - literal: "Temiloluwa Prioleau"
issued:
  date-parts:
    - [2026, 6, 5]
url: "https://arxiv.org/abs/2606.06881"

# Custom fields
paper_id: "2606.06881"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series-inpainting-diffusion"
  - "healthformer"
  - "tsa-benchmark"
architectures:
  []
datasets:
  - "glucofm-bench"
concept_slugs:
  - "glucofm-bench"
dataset_slugs:
  - "glucofm-bench"
skill: "TimeSeriesSkill"
processed_at: "2026-06-08T05:48:42Z"
created_at: "2026-06-08T05:48:42Z"
---

# GlucoFM-Bench: Benchmarking Time-Series Foundation Models for Blood Glucose Forecasting

**Authors**: Baiying Lu, Zhaohui Liang, Ryan Pontius, Shengpu Tang, Temiloluwa Prioleau
**Date**: 2026-06-05
**Paper ID**: [arxiv:2606.06881](https://arxiv.org/abs/2606.06881)

## Summary

GlucoFM-Bench is a comprehensive benchmark designed to evaluate time-series foundation models (TSFMs) and supervised deep learning models for the critical task of blood glucose forecasting. The study evaluates eight architectures across 15 public datasets covering diverse diabetes populations and glycemic conditions. Results show that although TSFMs achieve competitive zero-shot and few-shot performance, lightweight LSTMs maintain superiority in full-shot, task-specific training scenarios. The findings highlight the specific limitations of current models in high-risk glycemic ranges and emphasize the need for evaluation protocols beyond aggregate performance.

## Key Contributions

- Introduces GlucoFM-Bench, a standardized benchmark comprising 15 diabetes-relevant datasets and 1,117 individuals for evaluating blood glucose forecasting models.
- Demonstrates that while pre-trained TSFMs like Chronos-2 and TimesFM excel in zero-shot and few-shot scenarios, lightweight LSTMs still outperform them in full-shot, data-abundant settings.
- Identifies persistent model failure modes in T1D cohorts and at glycemic extremes, advocating for metrics beyond simple aggregate error.

## Key Concepts

- [[glucofm-bench]]: A standardized benchmark for evaluating time-series foundation models on blood glucose forecasting across diverse patient populations.

## Archivist Review

I approved the benchmark as it provides a standardized, multi-dataset framework specifically addressing the critical application of foundation models to blood glucose forecasting. I rejected the other candidate concepts/questions as they were either captured by the primary benchmark or were routine performance observations. The selection maintains a high bar for reproducibility and domain-specific utility.

### Approved Concepts
- GlucoFM-Bench: It is the first comprehensive benchmark specifically tailored to evaluate foundation models on the critical task of blood glucose forecasting.

## Datasets

- [[glucofm-bench]]

## Links

- [Abstract](https://arxiv.org/abs/2606.06881)
- [PDF](https://arxiv.org/pdf/2606.06881)

