---
# CSL-compatible fields
title: "PDRS : A Linear O(N) Algorithm for Segmentation of High-Activity Regions in Irregularly Sampled Time Series"
author:
  - literal: "Atal Agrawal"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02843"

# Custom fields
paper_id: "2605.02843"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "segmentation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "peak-driven-region-segmentation-pdrs"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:13:35Z"
created_at: "2026-05-06T05:13:35Z"
---

# PDRS : A Linear O(N) Algorithm for Segmentation of High-Activity Regions in Irregularly Sampled Time Series

**Authors**: Atal Agrawal
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.02843](https://arxiv.org/abs/2605.02843)

## Summary

The paper introduces Peak-Driven Region Segmentation (PDRS), an O(N) algorithm designed for the rapid identification and segmentation of transient high-activity regions in irregularly sampled time series. By seeding regions at statistically significant local maxima and employing a gradient-aware, multi-source breadth-first search, PDRS avoids the O(N^2) computational overhead associated with traditional Bayesian Blocks. Empirical evaluations on SDSS Stripe 82 and ZTF DR23 astronomical datasets demonstrate that PDRS achieves segmentation results comparable to Bayesian Blocks at a fraction of the computational cost. The algorithm's domain-agnostic nature and interpretable parameters make it a scalable tool for various time-series analysis applications beyond astronomy.

## Key Contributions

- Introduces PDRS, a novel O(N) complexity algorithm for segmenting high-activity regions in irregularly sampled data.
- Demonstrates that PDRS provides performance comparable to computationally expensive O(N^2) Bayesian Blocks approaches while significantly reducing runtime.
- Validates PDRS effectiveness on large-scale astronomical light curves from SDSS Stripe 82 and ZTF DR23 datasets.

## Open Questions & Future Work

- [[automated-pdrs-parameter-optimization]]

## Key Concepts

- [[peak-driven-region-segmentation-pdrs]]: A linear-time segmentation algorithm that identifies high-activity regions in irregularly sampled time series by seeding from significant local maxima and performing gradient-aware multi-source breadth-first expansion.

## Archivist Review

I approved the PDRS algorithm for its significant contribution to O(N) time-series segmentation and the associated open question regarding automated parameter optimization. I rejected the astronomical datasets as they are routine in domain-specific research and not foundational for a general time-series vault. The review adhered to the guidelines by prioritizing a novel, reusable algorithmic mechanism over paper-specific datasets.

### Approved Concepts
- Peak-Driven Region Segmentation (PDRS): It offers a computationally scalable, O(N) alternative to O(N^2) Bayesian Blocks for identifying transient high-activity segments, which is critical for large-scale time-series pipelines.

### Approved Open Questions
- Automated Parameter Optimization for PDRS: Manual parameter tuning acts as a significant bottleneck for applying the algorithm to large-scale, diverse real-world time-series datasets.

### Rejected Candidates
- [dataset] SDSS Stripe 82 (`sdss-stripe-82`) - not_reusable: Routine astronomical dataset that does not warrant a dedicated note in the context of this time-series forecasting vault.
- [dataset] ZTF DR23 (`ztf-dr23`) - not_reusable: Routine astronomical dataset that does not warrant a dedicated note in the context of this time-series forecasting vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.02843)
- [PDF](https://arxiv.org/pdf/2605.02843)

