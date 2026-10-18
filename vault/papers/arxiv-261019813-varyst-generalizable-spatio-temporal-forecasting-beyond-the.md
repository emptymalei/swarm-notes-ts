---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "VaryST: Generalizable Spatio-Temporal Forecasting Beyond the Closed-World Setting"
description: "VaryST is a spatio-temporal forecasting framework designed to handle the 'closed-world' limitations of traditional models, such as fixed graphs and consistent data availability. By dynamically constructing predictive context from long-term histories and identifying functionally relevant support nodes on-the-fly, it adapts to temporal evolution and spatial domain shifts. The model also employs a selective patch-masking training strategy to enhance robustness against missing data. Extensive evaluation shows that VaryST significantly improves zero-shot and few-shot generalization while maintaining high in-domain accuracy."
resource: "https://arxiv.org/abs/2610.19813"
tags:
  - "spatiotemporal-forecasting"
  - "time-series-forecasting"
  - "zero-shot-learning"
  - "few-shot-learning"
  - "distribution-shift"
  - "robustness"
  - "representation-learning"
  - "generalization"
timestamp: "2026-10-18T00:42:19Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Shengnan Guo"
  - literal: "Jinjun Cheng"
  - literal: "Xiaowei Mao"
  - literal: "Jianhao Zhang"
  - literal: "Haochen Lv"
  - literal: "Yang Jiang"
  - literal: "YiHeng Huang"
  - literal: "Yan Lin"
  - literal: "Youfang Lin"
  - literal: "Huaiyu Wan"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19813"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "varyst"
    description: "A generalizable spatio-temporal forecasting architecture that adapts to temporal and spatial changes by dynamically deriving node representations and selecting functional support nodes."
  - name: "selective-patch-masking"
    description: "A training strategy that adversarially masks highly-informative data patches to improve model robustness against sensor failure and observation unavailability."
datasets:
  []
open_questions:
  - name: "scaling-dynamic-st-selection"
    description: "How can dynamic support node selection be scaled to city-scale networks with hundreds of thousands of nodes while maintaining real-time inference capabilities?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:42:19Z"
created_at: "2026-10-18T00:42:19Z"
---

# VaryST: Generalizable Spatio-Temporal Forecasting Beyond the Closed-World Setting

**Authors**: Shengnan Guo, Jinjun Cheng, Xiaowei Mao, Jianhao Zhang, Haochen Lv, Yang Jiang, YiHeng Huang, Yan Lin, Youfang Lin, Huaiyu Wan
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19813](https://arxiv.org/abs/2610.19813)

## Summary

VaryST is a spatio-temporal forecasting framework designed to handle the 'closed-world' limitations of traditional models, such as fixed graphs and consistent data availability. By dynamically constructing predictive context from long-term histories and identifying functionally relevant support nodes on-the-fly, it adapts to temporal evolution and spatial domain shifts. The model also employs a selective patch-masking training strategy to enhance robustness against missing data. Extensive evaluation shows that VaryST significantly improves zero-shot and few-shot generalization while maintaining high in-domain accuracy.

## Key Contributions

- Introduces VaryST, a spatio-temporal forecasting model designed for generalization in 'open-world' environments with shifting spatial and temporal distributions.
- Develops a dynamic node representation mechanism that utilizes long-term historical context to adapt to evolving temporal patterns.
- Proposes a dynamic support node selection method that identifies functionally relevant nodes on-the-fly, allowing for zero-shot and few-shot generalization to new spatial domains.
- Implements an adversarial selective masking strategy during training to ensure robust performance even when primary sensor observations are missing.
- Demonstrates state-of-the-art performance across 17 baselines and 6 datasets, particularly in zero-shot and robustness scenarios.

## Limitations

The computational complexity of dynamically identifying and selecting functionally relevant support nodes from a large global context may pose scaling challenges in extremely large-scale networks.

## Open Questions & Future Work

- [[scaling-dynamic-st-selection]]

## Key Concepts

- [[varyst]]: A generalizable spatio-temporal forecasting architecture that adapts to temporal and spatial changes by dynamically deriving node representations and selecting functional support nodes.
- [[selective-patch-masking]]: A training strategy that adversarially masks highly-informative data patches to improve model robustness against sensor failure and observation unavailability.

## Archivist Review

The VaryST model and its associated Selective Patch Masking strategy are approved as they constitute the core technical contributions to the problem of generalizable spatio-temporal forecasting. The open question on scalability is included as it identifies a fundamental engineering bottleneck in applying dynamic graph selection to large-scale systems. Internal sub-modules and problem labels were rejected to maintain focus on standalone, reusable concepts.

### Approved Concepts
- VaryST: VaryST addresses the 'closed-world' limitation of traditional spatio-temporal models, which typically rely on static graph structures and fixed node sets, preventing deployment in dynamic real-world environments.
- Selective Patch Masking: This strategy explicitly addresses sensor failure and data unavailability by using an adversarial masking approach, forcing the model to learn redundant spatial and temporal dependencies.

### Approved Open Questions
- Scalability of Dynamic Spatial Selection: Scaling dynamic spatial dependencies is the primary bottleneck for deploying generalizable ST models in massive-scale urban or industrial monitoring systems where nodes are added or removed frequently.

### Rejected Candidates
- [concept] Closed-World Spatio-Temporal Forecasting (`closed-world-spatio-temporal-forecasting`) - paper_local: This term describes the limitation of existing work rather than a novel concept or mechanism introduced by the paper.
- [concept] Dynamic Support Node Selection (`dynamic-support-node-selection`) - subcomponent_of_broader_mechanism: This is a specific internal mechanism of the VaryST architecture and is better suited as part of the VaryST concept note.

## Links

- [Abstract](https://arxiv.org/abs/2610.19813)
- [PDF](https://arxiv.org/pdf/2610.19813)

