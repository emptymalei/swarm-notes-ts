---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "OrderFlowDiT: Transport-Regularized Diffusion Transformer for Probabilistic Limit-Order Supply Forecasting"
description: "This paper introduces OrderFlowDiT, a conditional Diffusion Transformer designed to forecast the probabilistic distribution of limit-order volume across multiple price levels. Standard diffusion models often fail in this domain because coordinate-wise losses do not capture the geometric displacement of price or the fluctuations in total volume mass. To address this, the authors incorporate an unbalanced optimal-transport (UOT) auxiliary loss, which regularizes the model's predictions to better align with the spatial distribution of order flow. Evaluation on a benchmark of 30 U.S. equities shows that this approach significantly improves both the transport-based accuracy and the calibration of predictive uncertainty compared to traditional mean-squared error diffusion training."
resource: "https://arxiv.org/abs/2610.22727"
tags:
  - "probabilistic-forecasting"
  - "financial-forecasting"
  - "diffusion-transformers"
  - "optimal-transport"
  - "uncertainty-quantification"
  - "time-series-forecasting"
  - "generative-models"
  - "limit-order-book"
  - "financial-time-series"
timestamp: "2026-10-19T04:38:03Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jung Hun Phee"
  - literal: "Tucker Balch"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22727"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "orderflowdit"
    description: "A conditional Diffusion Transformer architecture specifically designed to model the joint distribution of unnormalized limit-order volume-at-price fields."
  - name: "unbalanced-optimal-transport-regularization"
    description: "A regularization technique for generative models that penalizes spatial misalignment and total mass discrepancy in predicted fields using unbalanced optimal transport theory."
datasets:
  []
open_questions:
  - name: "financial-world-model-integration"
    description: "Developing comprehensive financial world models requires the integration of order submission generators with impact models that determine subsequent book states based on the interaction between liquidity, incoming flow, and specific trading actions. Identifying and validating the link between these aggregated components remains an unresolved step toward multi-step simulation and policy evaluation."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:38:03Z"
created_at: "2026-10-19T04:38:03Z"
---

# OrderFlowDiT: Transport-Regularized Diffusion Transformer for Probabilistic Limit-Order Supply Forecasting

**Authors**: Jung Hun Phee, Tucker Balch
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22727](https://arxiv.org/abs/2610.22727)

## Summary

This paper introduces OrderFlowDiT, a conditional Diffusion Transformer designed to forecast the probabilistic distribution of limit-order volume across multiple price levels. Standard diffusion models often fail in this domain because coordinate-wise losses do not capture the geometric displacement of price or the fluctuations in total volume mass. To address this, the authors incorporate an unbalanced optimal-transport (UOT) auxiliary loss, which regularizes the model's predictions to better align with the spatial distribution of order flow. Evaluation on a benchmark of 30 U.S. equities shows that this approach significantly improves both the transport-based accuracy and the calibration of predictive uncertainty compared to traditional mean-squared error diffusion training.

## Key Contributions

- Developed OrderFlowDiT, the first conditional Diffusion Transformer architecture tailored for modeling unnormalized limit-order book (LOB) volume-at-price fields.
- Introduced an unbalanced optimal-transport (UOT) auxiliary loss that improves the spatial fidelity of probabilistic forecasts by explicitly accounting for price displacement and mass fluctuations.
- Established a comprehensive 'full-field' evaluation protocol for LOB forecasting that integrates transport costs with proper scoring rules and calibration diagnostics.
- Empirically demonstrated that UOT-regularized training reduces transport cost by 45.8% and transport energy score by 26.1% across 30 U.S. equities compared to standard MSE diffusion.

## Limitations

The study focuses on a five-minute forecasting horizon, and the computational overhead of the UOT loss during training may limit scalability for extremely high-frequency tick-by-tick updates.

## Open Questions & Future Work

- [[financial-world-model-integration]]

## Key Concepts

- [[orderflowdit]]: A conditional Diffusion Transformer architecture specifically designed to model the joint distribution of unnormalized limit-order volume-at-price fields.
- [[unbalanced-optimal-transport-regularization]]: A regularization technique for generative models that penalizes spatial misalignment and total mass discrepancy in predicted fields using unbalanced optimal transport theory.

## Archivist Review

I approved OrderFlowDiT as a significant adaptation of DiTs to financial fields and Unbalanced Optimal-Transport Regularization as a highly reusable loss mechanism for non-mass-conserving field forecasting. I rejected the 'full-field evaluation framework' as it is a paper-local assembly of standard statistical tools. No specific named dataset was provided, so the dataset candidates were rejected. One open question regarding the integration of flow models into comprehensive financial world models was approved due to its high technical importance for market simulation research.

### Approved Concepts
- OrderFlowDiT: It is a pioneer in applying Diffusion Transformer (DiT) architectures to the high-dimensional, unnormalized spatial fields found in financial limit order books, moving beyond traditional vector-based forecasting.
- Unbalanced Optimal-Transport Regularization: Unlike standard coordinate-wise losses (MSE) that ignore spatial relationships, UOT provides a differentiable penalty for geometric displacement and mass fluctuations in predicted fields.

### Approved Open Questions
- Financial World Model Integration: This integration is essential for creating autonomous market simulators capable of evaluating complex trading strategies and their long-term effects on market liquidity and stability.

### Rejected Candidates
- [concept] Full-Field Evaluation Framework (`full-field-evaluation-framework`) - subcomponent_of_broader_mechanism: This is a composite methodology combining existing metrics (OT, Energy Score, calibration) for a specific task rather than a novel, reusable standalone mechanism.
- [dataset] 30 U.S. Equities Dataset (`30-us-equities-dataset`) - other: The paper refers to a generic collection of equity data from a standard source (likely LOBSTER) without providing a unique name or public repository for a specific benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2610.22727)
- [PDF](https://arxiv.org/pdf/2610.22727)

