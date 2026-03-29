---
# CSL-compatible fields
title: "MP-MoE: Matrix Profile-Guided Mixture of Experts for Precipitation Forecasting"
author:
  - literal: "Huyen Ngoc Tran"
  - literal: "Dung Trung Tran"
  - literal: "Hồng Phúc Nguyễn"
  - literal: "Xuan Vu Phan"
  - literal: "Nam-Phong Nguyen"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25046"

# Custom fields
paper_id: "2603.25046"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "ensemble methods"
  - "loss function design"
  - "meteorology"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mp-moe"
  - "matrix-profile-objective-function"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:16:45Z"
created_at: "2026-03-29T20:16:45Z"
---

# MP-MoE: Matrix Profile-Guided Mixture of Experts for Precipitation Forecasting

**Authors**: Huyen Ngoc Tran, Dung Trung Tran, Hồng Phúc Nguyễn, Xuan Vu Phan, Nam-Phong Nguyen
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25046](https://arxiv.org/abs/2603.25046)

## Summary

This paper introduces the Matrix Profile-guided Mixture of Experts (MP-MoE) framework to address the challenges of precipitation forecasting in tropical regions, particularly the penalty incurred by minor temporal shifts. MP-MoE integrates a conventional intensity loss with a novel, structural-aware Matrix Profile objective function, enabling expert selection based on subsequence similarity rather than only point-wise errors. Evaluations on Vietnamese river basin rainfall data show MP-MoE outperforms baselines in the Mean Critical Success Index (CSI-M) for heavy rainfall and reduces Dynamic Time Warping (DTW) values. This confirms the framework's ability to capture peak intensities while maintaining the morphological integrity of storm events across various forecasting horizons.

## Key Contributions

- Proposed MP-MoE, a framework integrating a structural-aware Matrix Profile objective with intensity loss to improve precipitation forecasting accuracy.
- The structural-aware loss mitigates the "double penalty" effect common in time series forecasting by emphasizing subsequence-level similarity over point-wise errors.
- Achieved superior performance over raw NWP and baseline learning methods in terms of Mean Critical Success Index (CSI-M) for heavy rainfall events.
- Demonstrated significant reduction in Dynamic Time Warping (DTW) values, indicating better preservation of the morphological integrity of storm events.

## Limitations

The evaluation is primarily focused on tropical river basins in Vietnam, suggesting the generalizability to regions with different meteorological regimes requires further testing.

## Open Questions & Future Work

- [[adaptive-loss-balancing-parameter-lambda]]
- [[online-learning-for-gating-network]]
- [[extending-1d-to-spatiotemporal-forecasting]]

## Key Concepts

- [[mp-moe]]: A forecasting framework that uses a structural-aware Matrix Profile objective to guide the selection within a Mixture of Experts model.
- [[matrix-profile-objective-function]]: A structural-aware loss function derived from the Matrix Profile concept, used to encourage morphological similarity in time series predictions.

## Archivist Review

The core contribution, the MP-MoE framework, and its novel structural component, the Matrix Profile Objective Function, were both approved as reusable concepts for sequence modeling. Two open questions concerning the adaptive tuning of loss parameters and extending the model to spatiotemporal dependency were deemed technically significant and retained. The specific local dataset was rejected as it lacks broad reusability.

### Approved Concepts
- Matrix Profile-Guided Mixture of Experts (MP-MoE): It is the core novel framework proposed, integrating a structural-aware loss with MoE for improved forecasting.
- Matrix Profile Objective Function: This is the novel loss component designed to mitigate the double penalty effect by focusing on subsequence similarity rather than point-wise errors.

### Approved Open Questions
- Adaptive tuning of loss-balancing hyperparameter: Adaptively tuning the loss balancing parameter $\\lambda$ is crucial for optimizing performance across highly variable meteorological conditions, moving beyond a fixed setting derived from initial empirical testing.
- Online learning for gating network adaptation: Implementing online learning addresses the limitation of a static expert pool by allowing the model to dynamically adjust its configuration in response to non-stationary climate patterns.
- Extension to spatiotemporal domain: Extending from 1D time-series to a spatiotemporal model using graph dependencies is necessary to capture the inherently spatial nature of weather systems and ensure consistency across neighboring forecast regions.

### Rejected Candidates
- [dataset] rainfall datasets from two major river basins in Vietnam (`rainfall-datasets-from-two-major-river-basins-in-vietnam`) - paper_local: The dataset is too specific and localized to warrant a permanent, reusable vault note, as it is primarily used for local evaluation.

## Links

- [Abstract](https://arxiv.org/abs/2603.25046)
- [PDF](https://arxiv.org/pdf/2603.25046)

