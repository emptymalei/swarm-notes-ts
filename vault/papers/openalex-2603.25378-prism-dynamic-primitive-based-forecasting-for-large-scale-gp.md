---
# CSL-compatible fields
title: "PRISM: Dynamic Primitive-Based Forecasting for Large-Scale GPU Cluster Workloads"
author:
  - literal: "Xin Wu"
  - literal: "Fei Teng"
  - literal: "Xingwang Li"
  - literal: "Bin Zheng"
  - literal: "Qiang Duan"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25378"

# Custom fields
paper_id: "2603.25378"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series decomposition"
  - "resource allocation"
  - "GPU workloads"
architectures:
  []
datasets:
  []
concept_slugs:
  - "prism-dynamic-primitive-forecasting"
  - "dictionary-driven-temporal-decomposition"
  - "adaptive-spectral-refinement"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:16:37Z"
created_at: "2026-03-29T20:16:37Z"
---

# PRISM: Dynamic Primitive-Based Forecasting for Large-Scale GPU Cluster Workloads

**Authors**: Xin Wu, Fei Teng, Xingwang Li, Bin Zheng, Qiang Duan
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25378](https://arxiv.org/abs/2603.25378)

## Summary

The paper introduces PRISM, a novel compositional forecasting framework designed to accurately predict highly volatile and multi-periodic GPU cluster workloads essential for efficient resource allocation in AI infrastructure. PRISM employs a dual representation strategy, utilizing dictionary-driven temporal decomposition alongside adaptive spectral refinement to extract stable and interpretable workload signatures. Evaluated on large-scale production traces, this method significantly outperforms existing predictors, especially by reducing errors during burst phases. The framework establishes a robust, architecture-aware foundation suitable for dynamic resource management in modern GPU-powered AI systems.

## Key Contributions

- Proposed PRISM, a primitive-based compositional forecasting framework for volatile GPU cluster workloads.
- Introduced a dual representation combining dictionary-driven temporal decomposition and adaptive spectral refinement to capture workload signatures.
- Achieved state-of-the-art forecasting results on large-scale production GPU traces, with significant reduction in burst-phase errors.
- Provided a robust, architecture-aware foundation for dynamic resource management in GPU-powered AI platforms.

## Limitations

The paper does not explicitly detail limitations, but the focus on GPU traces suggests potential generalization issues to non-GPU or non-AI infrastructure workloads.

## Open Questions & Future Work

- [[stability-of-learned-workload-primitives]]

## Key Concepts

- [[prism-dynamic-primitive-forecasting]]: A primitive-based compositional forecasting framework that combines dictionary-driven temporal decomposition with adaptive spectral refinement for complex workload prediction.
- [[dictionary-driven-temporal-decomposition]]: A time-series decomposition method that uses a dictionary approach to segment the input into stable, meaningful temporal signatures.
- [[adaptive-spectral-refinement]]: A mechanism used within PRISM to adjust and sharpen the frequency components extracted from the workload time series.

## Archivist Review

Three core technical components were approved: the overarching PRISM framework, its dictionary-driven decomposition technique, and the adaptive spectral refinement module. These are reusable concepts central to the paper's novelty in time-series modeling. One substantial open question regarding the long-term stability of the learned primitives was approved, as it represents a critical challenge for deploying compositional forecasting systems in dynamic production environments. Generic results and application summaries were rejected.

### Approved Concepts
- PRISM (Dynamic Primitive-Based Forecasting): PRISM is the proposed novel forecasting framework that addresses the volatility and multi-periodicity of GPU workloads using a compositional approach.
- Dictionary-Driven Temporal Decomposition: This technique for breaking down complex time series into stable, interpretable primitives forms the core novelty of the PRISM framework.
- Adaptive Spectral Refinement: This component complements the decomposition by providing a mechanism to refine the extracted temporal components, addressing noise or missing periodicity.

### Approved Open Questions
- Long-term stability of learned primitives: The robustness of the learned 'behavioral prototypes' (primitives) is essential for the practical deployment of the model in dynamic, evolving environments like production GPU clusters.

### Rejected Candidates
- [concept] Burst-Phase Error Reduction (`burst-phase-error-reduction`) - paper_local: This is a performance metric/result, not a reusable methodological concept.
- [concept] Architecture-Aware Foundation for Dynamic Resource Management (`GPU-workload-forecasting-foundation`) - paper_local: This describes the application/impact rather than a reusable technical mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2603.25378)
- [PDF](https://arxiv.org/pdf/2603.25378)

