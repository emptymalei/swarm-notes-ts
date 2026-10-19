---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "ASE: Attribution-Guided Semantic Evolution for Time Series Forecasting"
description: "ASE is a modular framework designed to enhance time series forecasting by incorporating external textual information alongside numerical histories. It utilizes a process called Attribution-guided Semantic Evolution to construct, evaluate, and refine textual factors based on their conditional contribution to predictive accuracy. The framework employs feedback loops via conditional refitting diagnostics to guide the evolution of semantic primitives into task-specific event or state factors. Experimental results on the TESS benchmarks and the CSI 300 stock ranking task demonstrate that ASE consistently outperforms numerical-only experts and outperforms existing multimodal baselines."
resource: "https://arxiv.org/abs/2610.23027"
tags:
  - "time-series-forecasting"
  - "multimodal-learning"
  - "financial-forecasting"
  - "representation-learning"
  - "interpretability"
  - "forecasting-accuracy"
timestamp: "2026-10-19T04:35:11Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yuxuan Zheng"
  - literal: "Zhaoyang Li"
  - literal: "Purui Liu"
  - literal: "Hengbo Xiao"
  - literal: "Guannan He"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23027"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "attribution-guided-semantic-evolution"
    description: "A modular framework that evolves textual semantic factors using attribution feedback to enhance numerical time series forecasting."
  - name: "conditional-refitting-diagnostics"
    description: "A diagnostic method that uses iterative model refitting to evaluate the marginal predictive contribution of individual semantic or numerical factors."
datasets:
  - name: "TESS Benchmark"
    description: "A benchmark suite of four datasets (often incorporating text and numerical time series) specifically designed to evaluate how textual information enhances forecasting performance."
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:35:11Z"
created_at: "2026-10-19T04:35:11Z"
---

# ASE: Attribution-Guided Semantic Evolution for Time Series Forecasting

**Authors**: Yuxuan Zheng, Zhaoyang Li, Purui Liu, Hengbo Xiao, Guannan He
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23027](https://arxiv.org/abs/2610.23027)

## Summary

ASE is a modular framework designed to enhance time series forecasting by incorporating external textual information alongside numerical histories. It utilizes a process called Attribution-guided Semantic Evolution to construct, evaluate, and refine textual factors based on their conditional contribution to predictive accuracy. The framework employs feedback loops via conditional refitting diagnostics to guide the evolution of semantic primitives into task-specific event or state factors. Experimental results on the TESS benchmarks and the CSI 300 stock ranking task demonstrate that ASE consistently outperforms numerical-only experts and outperforms existing multimodal baselines.

## Key Contributions

- Proposed the ASE framework, which modularly integrates textual and numerical data for time series forecasting through evolution and attribution.
- Developed conditional refitting diagnostics to provide a feedback loop for the iterative refinement of textual factors.
- Achieved new state-of-the-art results on all four TESS benchmark datasets, significantly reducing MSE compared to previously published scores.
- Demonstrated a measurable improvement in RankIC on the CSI 300 financial ranking task, confirming that semantic factors provide predictive value beyond numerical histories.

## Limitations

The abstract does not explicitly state computational costs or the scalability of the 'evolution' process when dealing with extremely large-scale text corpora.

## Key Concepts

- [[attribution-guided-semantic-evolution]]: A modular framework that evolves textual semantic factors using attribution feedback to enhance numerical time series forecasting.
- [[conditional-refitting-diagnostics]]: A diagnostic method that uses iterative model refitting to evaluate the marginal predictive contribution of individual semantic or numerical factors.

## Archivist Review

I have approved the ASE framework and its core Conditional Refitting Diagnostics mechanism as they represent a distinct, reusable methodology for multimodal time series integration. The TESS benchmark is approved as the primary evaluation suite. The CSI 300 index was rejected as it is a routine financial dataset rather than a novel ML benchmark. No open questions were explicitly identified in the analysis or abstract.

### Approved Concepts
- Attribution-guided Semantic Evolution: ASE provides a structured, feedback-driven methodology for bridging unstructured textual information with structured numerical time series, addressing a key challenge in multimodal forecasting.
- Conditional Refitting Diagnostics: This diagnostic provides an objective feedback mechanism to measure the marginal utility of specific factors (e.g., textual semantic primitives) relative to a numerical baseline, ensuring factor retention only when they add predictive value.

### Rejected Candidates
- [dataset] CSI 300 (`csi-300`) - generic: The CSI 300 is a standard financial market index and does not represent a novel dataset contribution or a specific machine learning benchmark suite introduced by this paper.

## Datasets

- [[TESS Benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2610.23027)
- [PDF](https://arxiv.org/pdf/2610.23027)

