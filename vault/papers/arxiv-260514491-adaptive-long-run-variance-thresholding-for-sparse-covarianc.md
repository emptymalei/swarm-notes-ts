---
# CSL-compatible fields
title: "Adaptive Long-Run Variance Thresholding for Sparse Covariance Estimation in High-Dimensional Time Series"
author:
  - literal: "Wenhao Zhang"
  - literal: "Zhaoxing Gao"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14491"

# Custom fields
paper_id: "2605.14491"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-long-run-variance-thresholding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:51Z"
created_at: "2026-05-16T05:12:51Z"
---

# Adaptive Long-Run Variance Thresholding for Sparse Covariance Estimation in High-Dimensional Time Series

**Authors**: Wenhao Zhang, Zhaoxing Gao
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14491](https://arxiv.org/abs/2605.14491)

## Summary

This paper addresses the limitations of standard covariance thresholding methods, which often assume independent data and fail when applied to high-dimensional time series. The authors propose an adaptive thresholding procedure that dynamically adjusts entry-specific thresholds based on estimated long-run variance to account for temporal dependence. The proposed estimator achieves optimal convergence rates under the spectral norm and ensures consistent support recovery, outperforming traditional approaches in both synthetic simulations and real-world applications involving gene expression and financial data.

## Key Contributions

- Introduced Adaptive Long-Run Variance Thresholding to enable consistent sparse covariance estimation in high-dimensional time series with weak temporal dependence.
- Proved spectral norm consistency and optimal convergence rates for the proposed estimator under regularity conditions.
- Established support recovery consistency and demonstrated that standard i.i.d.-based thresholding methods fail to accurately identify non-zero covariance entries in the presence of autocorrelation.

## Open Questions & Future Work

- [[theoretical-justification-block-cv]]
- [[adaptive-thresholding-complex-dependence]]

## Key Concepts

- [[adaptive-long-run-variance-thresholding]]: A thresholding procedure for sparse covariance estimation that adjusts entry-specific thresholds using estimated long-run variance to account for temporal autocorrelation.

## Archivist Review

The paper presents a significant improvement in high-dimensional covariance estimation by incorporating long-run variance into thresholding, directly addressing the limitations of i.i.d. assumptions. I have approved the proposed methodology as a core concept and the two identified research questions regarding theoretical gaps in tuning and dependence modeling, which are significant for high-dimensional time-series statistics. No datasets were approved as the applications (gene expression, stock returns) were standard domains rather than novel, specific datasets.

### Approved Concepts
- Adaptive Long-Run Variance Thresholding: It addresses the failure of standard thresholding methods when applied to high-dimensional time series with temporal dependence by replacing naive i.i.d. assumptions.

### Approved Open Questions
- Theoretical justification of block-CV: Tuning parameter selection is crucial for the practical performance of thresholding estimators. Understanding the theoretical validity of these selection methods is necessary to ensure the reliability of the resulting covariance estimates in applied settings.
- Adaptive thresholding for complex dependence: Real-world high-dimensional data frequently exhibit complex temporal dependencies. Proving the robustness of these estimators in more general settings is essential for their widespread applicability.

## Links

- [Abstract](https://arxiv.org/abs/2605.14491)
- [PDF](https://arxiv.org/pdf/2605.14491)

