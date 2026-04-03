---
# CSL-compatible fields
title: "Assessing the ability of a stretched-grid deep-learning weather prediction model to capture physical balances"
author:
  - literal: "Francesco Pasquini"
  - literal: "Michiel Baatsen"
  - literal: "Bastien François"
  - literal: "Natalie Theeuwes"
  - literal: "Maurice Schmeits"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01454"

# Custom fields
paper_id: "2604.01454"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:20:40Z"
created_at: "2026-04-03T05:20:40Z"
---

# Assessing the ability of a stretched-grid deep-learning weather prediction model to capture physical balances

**Authors**: Francesco Pasquini, Michiel Baatsen, Bastien François, Natalie Theeuwes, Maurice Schmeits
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01454](https://arxiv.org/abs/2604.01454)

## Summary

This paper investigates the physical reliability of the stretched-grid Deep Learning Weather Prediction (DLWP) model, Bris, by evaluating its performance against the operational MetCoOp Ensemble Prediction System (MEPS) during the severe extratropical cyclone Poly. Despite yielding comparable RMSE metrics, the study reveals that the DLWP model struggles to represent mesoscale atmospheric dynamics and systematically disrupts fundamental physical balances. The findings attribute these deficiencies to fine-scale noise in the predicted fields, which generates unrealistic spatial gradients and highlights significant challenges for the deployment of data-driven models in extreme weather forecasting.

## Key Contributions

- Provides a comparative physical consistency evaluation of a stretched-grid DLWP model (Bris) against an operational NWP ensemble (MEPS) for a severe extratropical cyclone event.
- Demonstrates that while the DLWP model achieves competitive RMSE, it fails to capture critical mesoscale dynamics and violates key atmospheric physical balances.
- Identifies that the failure to maintain physical consistency is primarily caused by fine-scale numerical noise, resulting in unrealistic spatial gradients in model output.

## Open Questions & Future Work

- [[origin-of-fine-scale-noise-in-ddm]]

## Archivist Review

I have approved one open question concerning the origin of fine-scale noise in deep learning weather prediction models. This is a critical, unresolved research question that impedes the deployment of high-resolution data-driven weather models. I rejected the model and ensemble system as they are local implementation/operational details rather than generalizable concepts or standard benchmarks.

### Approved Open Questions
- Origin of fine-scale noise in DLWP: This issue is fundamental to the viability of high-resolution data-driven weather prediction; without resolving the source of this noise, it is impossible to guarantee physical consistency or reliable forecasting performance for extreme events in operational settings.

### Rejected Candidates
- [concept] Bris model (`bris-model`) - paper_local: This is a specific model implementation rather than a general, reusable architecture or technique.
- [dataset] MetCoOp Ensemble Prediction System (MEPS) (`meps-ensemble`) - paper_local: This is a specific NWP operational product used for comparison, not a research dataset that serves as a general benchmarking target for future ML developments.

## Links

- [Abstract](https://arxiv.org/abs/2604.01454)
- [PDF](https://arxiv.org/pdf/2604.01454)

