---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Multi-modal transmission forecasting for the Vera C. Rubin Observatory"
description: "The paper introduces a multimodal deep learning approach for forecasting atmospheric transmission at the Vera C. Rubin Observatory to optimize survey scheduling. By asynchronously fusing ground-based telemetry from the DREAM all-sky camera with regional satellite imagery, the model addresses the 'beyond-the-horizon' limitation of local sensors, enabling accurate predictions up to 30 minutes in advance. The strategy significantly outperforms traditional frozen-flow and persistence baselines, particularly for the 20-minute horizon required for 'pair mode' observations, reducing false-clear misses by over 20%."
resource: "https://arxiv.org/abs/2610.22725"
tags:
  - "astrophysics"
  - "time-series-forecasting"
  - "multimodal-learning"
  - "weather-forecasting"
  - "remote-sensing"
  - "spatiotemporal-modeling"
  - "ultra-short-term-forecasting"
timestamp: "2026-10-19T04:38:46Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Peter Xiangyuan Ma"
  - literal: "Joshua S. Bloom"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22725"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "short-horizon-nowcasting-precision-gap"
    description: "While deep learning models excel at capturing complex, non-linear dynamics over longer horizons, they often suffer from a performance gap at 'near-zero' lead times (e.g., 1-2 minutes). Research is needed to understand whether this is due to excessive smoothing in neural architectures, data resolution limits, or a lack of inductive biases for pure geometric advection that classical image-registration techniques naturally possess."
  - name: "multi-modal-horizon-interference"
    description: "Incorporating high-resolution local sensor data can be counterproductive for long-range forecasts once large-scale regional weather features become the primary drivers of atmospheric change. Identifying mechanisms for lead-time-dependent feature gating or adaptive weighting is required to prevent local telemetry from introducing noise that degrades the predictive power of regional data sources."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:38:46Z"
created_at: "2026-10-19T04:38:46Z"
---

# Multi-modal transmission forecasting for the Vera C. Rubin Observatory

**Authors**: Peter Xiangyuan Ma, Joshua S. Bloom
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22725](https://arxiv.org/abs/2610.22725)

## Summary

The paper introduces a multimodal deep learning approach for forecasting atmospheric transmission at the Vera C. Rubin Observatory to optimize survey scheduling. By asynchronously fusing ground-based telemetry from the DREAM all-sky camera with regional satellite imagery, the model addresses the 'beyond-the-horizon' limitation of local sensors, enabling accurate predictions up to 30 minutes in advance. The strategy significantly outperforms traditional frozen-flow and persistence baselines, particularly for the 20-minute horizon required for 'pair mode' observations, reducing false-clear misses by over 20%.

## Key Contributions

- Developed a monolithic multimodal model that fuses asynchronous data from ground-based all-sky cameras (DREAM) and weather satellites to bridge the gap between ultra-short and short-term atmospheric forecasting.
- Identified the 'beyond-the-horizon' problem in observatory scheduling, demonstrating that satellite imagery provides the necessary long-horizon predictive power (20-40 mins) that ground-based cameras lack.
- Achieved a 21% reduction in transmission error and a 22% reduction in false-clear misses at 20-minute horizons compared to the baseline frozen-flow tracker used by the Rubin Observatory.
- Quantified the estimated survey efficiency gain for the LSST (Legacy Survey of Space and Time) at 0.1% to 1% through improved dynamic scheduling.

## Limitations

The estimated gains in survey efficiency are optimistic order-of-magnitude estimates and require full integration into the Rubin scheduler to be validated.

## Open Questions & Future Work

- [[short-horizon-nowcasting-precision-gap]]
- [[multi-modal-horizon-interference]]

## Archivist Review

Approved two open questions focusing on the persistent performance gap between deep learning and classical baselines at very short horizons, and the negative transfer that can occur when fusing local and regional data for long-range forecasts. Concepts were rejected as they described specific observatory hardware or existing astronomical baseline methods rather than novel machine learning primitives.

### Approved Open Questions
- Short-Horizon Nowcasting Precision Gap: Closing this gap is critical for high-frequency operational systems where immediate queue management and safety-critical responses rely on ultra-short-term accuracy.
- Multi-Modal Horizon Interference: Understanding this negative transfer (interference) is essential for designing robust multimodal systems that maintain high performance across both short and long horizons without requiring separate, fragmented models.

### Rejected Candidates
- [concept] DREAM Camera (`dream-camera`) - paper_local: DREAM (Dutch Rubin Enhanced Atmospheric Monitor) is a specific hardware sensor system, not a novel machine learning architecture or reusable methodology.
- [concept] Frozen-Flow Tracker (`frozen-flow-tracker`) - not_novel: This is an existing physics-based baseline method, not a novel contribution of the paper.
- [concept] Pair Mode Scheduling (`pair-mode-scheduling`) - paper_local: This is a domain-specific operational mode for the Rubin Observatory, not a broadly reusable ML concept.
- [open_question] Continuous Weather Domain Adaptation (`weather-distribution-online-adaptation`) - duplicate_existing: The general problem of online adaptation to non-stationary distributions is already well-represented in the vault (e.g., unsupervised-online-adaptation).

## Links

- [Abstract](https://arxiv.org/abs/2610.22725)
- [PDF](https://arxiv.org/pdf/2610.22725)

