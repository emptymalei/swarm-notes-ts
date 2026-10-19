---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "RTSM: Adapting Recursive Models to Multivariate Time-Series Classification"
description: "The paper introduces the Recursive Time-Series Model (RTSM), a novel architecture designed for multivariate time-series classification that prioritizes parameter efficiency through weight-tied refinement. RTSM utilizes a learned convolutional temporal tokenizer to extract initial features, followed by an iterative refinement process on a single latent state and a pooled readout for classification. Evaluated on the 30-dataset UEA archive, RTSM achieves a mean accuracy of 72.81%, surpassing existing deep learning models like MambaSL by 1.6 percentage points. The study highlights that the choice of temporal encoding and the organization of the latent state are critical factors for successfully adapting recursive architectures to time-series data."
resource: "https://arxiv.org/abs/2610.23353"
tags:
  - "multivariate-time-series"
  - "time-series-classification"
  - "deep-learning"
  - "representation-learning"
  - "computational-efficiency"
  - "temporal-modeling"
  - "model-evaluation"
timestamp: "2026-10-19T04:29:09Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Georg Tenzing"
  - literal: "Anna Tegon"
  - literal: "Luca Benini"
  - literal: "Thorir Mar Ingolfsson"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23353"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "rtsm"
    description: "A multivariate time-series classification model that uses a convolutional tokenizer and iterative weight-tied refinement on a single latent state to achieve high accuracy with a constant parameter footprint."
datasets:
  []
open_questions:
  - name: "inference-time-scaling-for-recursive-tsc"
    description: "Does the integration of randomized initialization (RI) and noise injection (NI) during the training of recursive time-series models enable them to scale performance effectively when computational depth is increased at inference time? Current results suggest that standard deterministic training may not fully unlock the scaling potential of these models in the time-series domain."
  - name: "hardware-aware-weight-shared-inference-efficiency"
    description: "What are the actual throughput and energy gains of weight-tied recursive time-series models when implemented on specialized hardware like edge AI accelerators or GPUs, considering the trade-offs between activation data movement, execution scheduling, and the limited memory footprint of weights?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:29:09Z"
created_at: "2026-10-19T04:29:09Z"
---

# RTSM: Adapting Recursive Models to Multivariate Time-Series Classification

**Authors**: Georg Tenzing, Anna Tegon, Luca Benini, Thorir Mar Ingolfsson
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23353](https://arxiv.org/abs/2610.23353)

## Summary

The paper introduces the Recursive Time-Series Model (RTSM), a novel architecture designed for multivariate time-series classification that prioritizes parameter efficiency through weight-tied refinement. RTSM utilizes a learned convolutional temporal tokenizer to extract initial features, followed by an iterative refinement process on a single latent state and a pooled readout for classification. Evaluated on the 30-dataset UEA archive, RTSM achieves a mean accuracy of 72.81%, surpassing existing deep learning models like MambaSL by 1.6 percentage points. The study highlights that the choice of temporal encoding and the organization of the latent state are critical factors for successfully adapting recursive architectures to time-series data.

## Key Contributions

- Introduced the Recursive Time-Series Model (RTSM), leveraging weight-tied refinement for parameter-efficient multivariate time-series classification.
- Achieved a state-of-the-art mean accuracy of 72.81% across 30 UEA datasets, outperforming 17 deep-learning baselines including MambaSL.
- Demonstrated that a single-state latent organization and a learned convolutional temporal tokenizer are superior architectural choices for recursive time-series modeling.
- Proposed a classifier design where the refinement module's parameter count remains independent of its computational depth, facilitating flexible inference.

## Limitations

The paper focuses on classification, and the abstract does not discuss the model's performance or adaptation for forecasting or anomaly detection tasks.

## Open Questions & Future Work

- [[inference-time-scaling-for-recursive-tsc]]
- [[hardware-aware-weight-shared-inference-efficiency]]

## Key Concepts

- [[rtsm]]: A multivariate time-series classification model that uses a convolutional tokenizer and iterative weight-tied refinement on a single latent state to achieve high accuracy with a constant parameter footprint.

## Archivist Review

Approved RTSM as a significant model contribution that sets a new performance bar for recursive architectures in the time-series domain. Two open questions were approved focusing on the critical unresolved challenges of scaling inference compute and realizing hardware-level energy benefits. Rejected the general weight-tied refinement concept as it is a pre-existing ML technique and the UEA archive as it is already documented in the vault.

### Approved Concepts
- Recursive Time-Series Model (RTSM): RTSM establishes a high-performance baseline for multivariate time-series classification using recursive architectures, outperforming strong alternatives like MambaSL while maintaining parameter efficiency.

### Approved Open Questions
- Inference Scaling via Stochastic Training in RTSM: If training regimes can induce better inference scaling, recursive models could adaptively trade off latency for accuracy on a per-sample basis, which is a critical capability for edge deployment.
- Hardware Efficiency of Weight-Shared Temporal Refinement: The primary motivation for weight-sharing is parameter efficiency, but its practical advantage in terms of energy and speed requires verification on real-world hardware architectures.

### Rejected Candidates
- [concept] Weight-tied Refinement (`weight-tied-refinement`) - not_novel: Weight-tied refinement is a broad, well-established architectural pattern used in models like ALBERT and Deep Equilibrium Models; it is not a novel concept unique to this paper.
- [dataset] UEA multivariate time-series classification archive (`uea-dataset-multivariate-classification`) - duplicate_existing: This dataset already exists in the knowledge vault under the canonical name 'uea-dataset'.

## Links

- [Abstract](https://arxiv.org/abs/2610.23353)
- [PDF](https://arxiv.org/pdf/2610.23353)

