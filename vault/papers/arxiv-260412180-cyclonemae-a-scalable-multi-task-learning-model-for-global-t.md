---
# CSL-compatible fields
title: "CycloneMAE: A Scalable Multi-Task Learning Model for Global Tropical Cyclone Probabilistic Forecasting"
author:
  - literal: "Renlong Hang"
  - literal: "Zihao Xu"
  - literal: "Jiuwei Zhao"
  - literal: "Runling Yu"
  - literal: "Leye Cheng"
  - literal: "Qingshan Liu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12180"

# Custom fields
paper_id: "2604.12180"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "structure-aware-masked-autoencoder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:04:53Z"
created_at: "2026-04-15T05:04:53Z"
---

# CycloneMAE: A Scalable Multi-Task Learning Model for Global Tropical Cyclone Probabilistic Forecasting

**Authors**: Renlong Hang, Zihao Xu, Jiuwei Zhao, Runling Yu, Leye Cheng, Qingshan Liu
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12180](https://arxiv.org/abs/2604.12180)

## Summary

CycloneMAE is a multi-task, structure-aware masked autoencoder designed to address the limitations of traditional NWP and deterministic DL models in tropical cyclone forecasting. By leveraging a discrete probabilistic gridding mechanism and a pre-train/fine-tune paradigm, the model generates both deterministic and probabilistic forecasts from multi-modal data. The framework achieves superior performance across five ocean basins compared to leading NWP systems, with significant improvements in track, pressure, and wind speed accuracy. Attribution analysis confirms the model effectively learns physically interpretable representations, transitioning from core structural analysis to environmental context over longer forecasting horizons.

## Key Contributions

- Introduces CycloneMAE, a multi-task masked autoencoder model that enables scalable, joint deterministic and probabilistic tropical cyclone forecasting.
- Outperforms state-of-the-art NWP models in pressure and wind speed prediction up to 120 hours and track forecasting up to 24 hours across five global ocean basins.
- Demonstrates via integrated gradients that the model shifts focus from internal convective structures to external environmental factors as the forecast horizon increases.

## Open Questions & Future Work

- [[local-global-atmospheric-context-integration]]

## Key Concepts

- [[structure-aware-masked-autoencoder]]: A masked autoencoder variant that explicitly incorporates spatial structural constraints of physical entities into the representation learning process.

## Archivist Review

The approved concept defines a generalizable approach for integrating physical object structure into masked autoencoder training, which is a significant advancement for atmospheric modeling. The approved open question addresses the fundamental tension between localized high-resolution prediction and global-scale context integration, which is a major bottleneck in weather forecasting literature. Other candidates were rejected to prioritize clarity and broader utility within the vault.

### Approved Concepts
- Structure-Aware Masked Autoencoder: Introduces an inductive bias for modeling localized extreme weather phenomena by explicitly structuring the masked autoencoder process around feature geometries.

### Approved Open Questions
- Local-global atmospheric context integration: Identifying how to effectively bridge localized structural representation learning with global-scale atmospheric context is essential for scaling data-driven weather models to long-range forecasting.

### Rejected Candidates
- [concept] TC structure-aware masked autoencoder (`tc-structure-aware-masked-autoencoder`) - other: Renamed to a more general term for wider reusability in the vault.
- [open_question] Integrating global meteorological context (`integrating-global-context-for-tc-tracking`) - other: Renamed to a more standard technical slug for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.12180)
- [PDF](https://arxiv.org/pdf/2604.12180)

