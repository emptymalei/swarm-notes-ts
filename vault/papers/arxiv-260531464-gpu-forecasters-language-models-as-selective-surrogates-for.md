---
# CSL-compatible fields
title: "GPU Forecasters: Language Models as Selective Surrogates for Kernel Runtime Optimization"
author:
  - literal: "Zaid Khan"
  - literal: "Justin Chih-Yao Chen"
  - literal: "Jaemin Cho"
  - literal: "Elias Stengel-Eskin"
  - literal: "Mohit Bansal"
issued:
  date-parts:
    - [2026, 5, 29]
url: "https://arxiv.org/abs/2605.31464"

# Custom fields
paper_id: "2605.31464"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-01T05:44:17Z"
created_at: "2026-06-01T05:44:17Z"
---

# GPU Forecasters: Language Models as Selective Surrogates for Kernel Runtime Optimization

**Authors**: Zaid Khan, Justin Chih-Yao Chen, Jaemin Cho, Elias Stengel-Eskin, Mohit Bansal
**Date**: 2026-05-29
**Paper ID**: [arxiv:2605.31464](https://arxiv.org/abs/2605.31464)

## Summary

This paper investigates using LLMs as selective surrogate models to forecast GPU kernel performance, reducing the need for costly iterative hardware execution during optimization search. By predicting performance and selectively deferring uncertain cases to hardware, the model significantly expands the search space under constrained compute budgets. Experiments show that reinforcement learning further refines both the accuracy and calibration of these forecasts, resulting in improved kernel optimization outcomes compared to traditional direct-hardware search methods.

## Key Contributions

- Introduces the use of LLMs as selective GPU surrogates to predict kernel runtime performance, mitigating the bottleneck of costly hardware-based measurements.
- Develops a selective forecasting mechanism that allows the surrogate to defer uncertain performance predictions to actual GPU hardware.
- Demonstrates that integrating these LLM-based surrogates into kernel search processes enables exploring significantly larger candidate spaces and yields faster kernels within fixed GPU evaluation budgets.

## Links

- [Abstract](https://arxiv.org/abs/2605.31464)
- [PDF](https://arxiv.org/pdf/2605.31464)

