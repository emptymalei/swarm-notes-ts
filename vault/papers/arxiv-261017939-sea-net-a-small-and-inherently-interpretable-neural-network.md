---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Sea-Net: A Small and Inherently Interpretable Neural Network for Time Series Classification"
description: "SEA-Net is a lightweight, inherently interpretable neural network architecture designed for time series classification (TSC) in resource-constrained environments. By combining small multi-scale depthwise-separable convolutional encoders with Multiple Instance Learning (MIL) pooling heads, the model achieves high classification accuracy and superior temporal explanations compared to the MILLET baseline. Specifically, its bottleneck and gated variants reduce parameter counts to between 41K and 62K while improving explanation quality (NDCG@n) and classification performance, demonstrating that efficiency does not necessitate a loss in interpretability."
resource: "https://arxiv.org/abs/2610.17939"
tags:
  - "time-series-classification"
  - "explainable-ai"
  - "multiple-instance-learning"
  - "efficiency"
  - "edge-computing"
  - "interpretability"
  - "convolutional-neural-networks"
timestamp: "2026-10-18T01:01:01Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ubaid Ur Rehman"
  - literal: "Tanmoy Mondal"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.17939"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "sea-net"
    description: "A lightweight, inherently interpretable neural network for time series classification that uses multi-scale depthwise-separable convolutions and Multiple Instance Learning (MIL) pooling to provide temporal explanations."
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T01:01:01Z"
created_at: "2026-10-18T01:01:01Z"
---

# Sea-Net: A Small and Inherently Interpretable Neural Network for Time Series Classification

**Authors**: Ubaid Ur Rehman, Tanmoy Mondal
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.17939](https://arxiv.org/abs/2610.17939)

## Summary

SEA-Net is a lightweight, inherently interpretable neural network architecture designed for time series classification (TSC) in resource-constrained environments. By combining small multi-scale depthwise-separable convolutional encoders with Multiple Instance Learning (MIL) pooling heads, the model achieves high classification accuracy and superior temporal explanations compared to the MILLET baseline. Specifically, its bottleneck and gated variants reduce parameter counts to between 41K and 62K while improving explanation quality (NDCG@n) and classification performance, demonstrating that efficiency does not necessitate a loss in interpretability.

## Key Contributions

- Introduced SEA-Net, a lightweight neural network (41K-62K parameters) designed for interpretable time series classification on resource-constrained devices.
- Implemented a multi-scale depthwise-separable convolutional encoder that reduces parameter count by approximately 90% compared to InceptionTime-based models like MILLET.
- Demonstrated that replacing Conjunctive Pooling with Top-k or Gated MIL pooling strategies significantly improves temporal explanation quality (up to 0.765 NDCG@n).
- Achieved higher classification accuracy (0.955) than larger baselines while providing inherent transparency regarding which time intervals influence predictions.

## Limitations

The paper does not provide physical hardware benchmarks (e.g., latency or energy consumption) on micro-controllers despite the stated goal of edge deployment.

## Key Concepts

- [[sea-net]]: A lightweight, inherently interpretable neural network for time series classification that uses multi-scale depthwise-separable convolutions and Multiple Instance Learning (MIL) pooling to provide temporal explanations.

## Archivist Review

The review approves SEA-Net as the primary novelty, representing a specific advance in lightweight, interpretable time-series classification. Standard architectural components like Top-k pooling and existing baselines like MILLET were rejected to maintain focus on the paper's specific contributions. The proposed open question was rejected as it focused on general architectural trade-offs rather than a distinct, unresolved research challenge.

### Approved Concepts
- SEA-Net: It addresses the critical trade-off between model size, classification accuracy, and temporal interpretability for time-series data in resource-constrained environments.

### Rejected Candidates
- [concept] MILLET (`millet`) - not_novel: MILLET is an existing baseline model (Multiple Instance Learning with Temporal Explanation) and not the primary contribution of this paper.
- [concept] Top-k Pooling (`top-k-pooling`) - subcomponent_of_broader_mechanism: Top-k pooling is a standard architectural component and not a unique contribution of this paper.
- [open_question] Optimizing MIL Pooling for Diverse Temporal Patterns (`mil-pooling-strategy-tradeoffs`) - generic: This question describes a standard architectural trade-off and hyperparameter selection problem rather than a fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.17939)
- [PDF](https://arxiv.org/pdf/2610.17939)

