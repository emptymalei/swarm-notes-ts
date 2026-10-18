---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DST-Net: Decomposed Spatio-Temporal Network for Time Series Forecasting"
description: "DST-Net is a novel time series forecasting architecture that leverages series decomposition through a disentangled modeling strategy. Recognizing that trend and seasonal components possess different inductive biases, the model employs a Latent Graph Block for the trend component to capture spatial dependencies and a Gaussian Multi-scale Attention mechanism for the seasonal component to focus on local temporal patterns. This targeted approach addresses the limitations of homogeneous modeling, where global noise often distracts from local evolutionary phases. Results indicate that aligning component-specific properties with specialized architectures significantly improves forecasting accuracy on diverse real-world datasets."
resource: "https://arxiv.org/abs/2610.21123"
tags:
  - "time-series-forecasting"
  - "series-decomposition"
  - "spatio-temporal-modeling"
  - "attention-mechanisms"
  - "graph-neural-networks"
  - "trend-seasonal-decomposition"
  - "multivariate-time-series"
timestamp: "2026-10-18T00:24:31Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yaohua Zha"
  - literal: "Hai Wu"
  - literal: "Shu-Tao Xia"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21123"
paper_source: "arxiv"
architectures:
  - "transformer"
  - "graph-neural-networks"
concepts:
  - name: "gaussian-multi-scale-attention"
    description: "An attention mechanism that incorporates learnable Gaussian priors to enforce multi-scale local focus and filter out global noise in seasonal time series components."
datasets:
  []
open_questions:
  - name: "adaptive-series-decomposition-optimization"
    description: "How can the decomposition process itself be made adaptive or learnable to ensure that the trend and seasonal components optimally align with the specialized inductive biases of downstream modeling branches?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:24:31Z"
created_at: "2026-10-18T00:24:31Z"
---

# DST-Net: Decomposed Spatio-Temporal Network for Time Series Forecasting

**Authors**: Yaohua Zha, Hai Wu, Shu-Tao Xia
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21123](https://arxiv.org/abs/2610.21123)

## Summary

DST-Net is a novel time series forecasting architecture that leverages series decomposition through a disentangled modeling strategy. Recognizing that trend and seasonal components possess different inductive biases, the model employs a Latent Graph Block for the trend component to capture spatial dependencies and a Gaussian Multi-scale Attention mechanism for the seasonal component to focus on local temporal patterns. This targeted approach addresses the limitations of homogeneous modeling, where global noise often distracts from local evolutionary phases. Results indicate that aligning component-specific properties with specialized architectures significantly improves forecasting accuracy on diverse real-world datasets.

## Key Contributions

- Proposed DST-Net, a disentangled architecture that applies specialized modeling strategies for trend and seasonal components rather than the common homogeneous approach.
- Developed the Latent Graph Block to capture global topological dependencies and spatial co-movements specifically within the trend component.
- Introduced Gaussian Multi-scale Attention, which uses learnable Gaussian priors to focus on local evolutionary phases in seasonal components and mitigate global noise.
- Demonstrated state-of-the-art performance across multiple real-world time series benchmarks by aligning model inductive biases with component-specific properties.

## Limitations

The paper does not explicitly discuss the computational overhead associated with maintaining two distinct modeling branches or the complexity of learnable Gaussian priors.

## Open Questions & Future Work

- [[adaptive-series-decomposition-optimization]]

## Key Concepts

- [[gaussian-multi-scale-attention]]: An attention mechanism that incorporates learnable Gaussian priors to enforce multi-scale local focus and filter out global noise in seasonal time series components.

## Archivist Review

I approved the Gaussian Multi-scale Attention as a specific and reusable architectural contribution that addresses the noise sensitivity of Transformers in seasonal time series forecasting. I also approved the open question regarding adaptive decomposition, as the paper's move toward heterogeneous modeling highlights the critical dependency on the quality of the initial component split. The Latent Graph Block was rejected because latent graph learning is an established GNN paradigm, and its application to a specific signal component is an implementation detail rather than a fundamental conceptual shift.

### Approved Concepts
- Gaussian Multi-scale Attention: It addresses the 'attention distraction' problem in Transformers for time series by biasing the model toward local temporal evolution, which is critical for seasonal components.

### Approved Open Questions
- Adaptive Series Decomposition Optimization: If the initial decomposition is suboptimal or fails to adapt to distribution shifts, specialized modeling branches (like GNNs for trend or local attention for seasonality) will receive misaligned inputs, degrading performance.

### Rejected Candidates
- [concept] Latent Graph Block (`latent-graph-block`) - subcomponent_of_broader_mechanism: The use of latent graph discovery for multivariate time series is a well-established technique (e.g., MTGNN); its application to the trend component specifically is a paper-local implementation detail rather than a novel standalone concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.21123)
- [PDF](https://arxiv.org/pdf/2610.21123)

