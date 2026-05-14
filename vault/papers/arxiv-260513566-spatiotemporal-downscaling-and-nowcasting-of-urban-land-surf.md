---
# CSL-compatible fields
title: "Spatiotemporal downscaling and nowcasting of urban land surface temperatures with deep neural networks"
author:
  - literal: "Solomiia Kurchaba"
  - literal: "Angela Meyer"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13566"

# Custom fields
paper_id: "2605.13566"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series"
  - "remote-sensing"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spatiotemporal-lst-downscaling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:23:35Z"
created_at: "2026-05-14T05:23:35Z"
---

# Spatiotemporal downscaling and nowcasting of urban land surface temperatures with deep neural networks

**Authors**: Solomiia Kurchaba, Angela Meyer
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13566](https://arxiv.org/abs/2605.13566)

## Summary

This paper addresses the resolution trade-off in satellite-derived Land Surface Temperature (LST) data by proposing a two-stage deep learning pipeline. First, a U-Net model downscales coarse, frequent SEVIRI/MSG observations to match fine, sparse MODIS data, providing 1 km/15-minute resolution LST fields. Second, a ConvLSTM model uses these downscaled fields to perform intraday LST nowcasting, achieving superior accuracy compared to standard statistical benchmarks. The approach is validated on large European cities and provides a robust foundation for operational urban climate monitoring.

## Key Contributions

- Proposes a U-Net-based spatiotemporal downscaling framework that fuses SEVIRI/MSG and MODIS data to achieve 1 km spatial and 15-minute temporal resolution for LST fields.
- Introduces a ConvLSTM-based nowcasting model for LST, yielding RMSEs of 0.57–1.15°C for 15–75 minute lead times.
- Demonstrates that the downscaled, high-resolution product significantly outperforms persistence and Climatological Rolling Median benchmarks across large European urban areas.

## Open Questions & Future Work

- [[year-round-lst-forecasting-generalization]]
- [[incorporating-physical-auxiliary-data]]

## Key Concepts

- [[spatiotemporal-lst-downscaling]]: A U-Net based framework for fusing geostationary and polar-orbiting satellite data to produce high-resolution spatiotemporal LST fields.

## Archivist Review

I approved the central downscaling framework concept and two open questions regarding seasonal generalization and physical auxiliary data integration. These items are sufficiently distinct, central to the paper's contribution, and represent non-trivial research directions in the context of remote sensing and urban forecasting. I rejected no candidates as I found the proposed items aligned well with the vault's standards.

### Approved Concepts
- Spatiotemporal LST Downscaling: Addresses the fundamental trade-off between spatial and temporal resolution in satellite-derived land surface temperature products.

### Approved Open Questions
- Year-round LST forecasting generalization: The limitation to warm-season training prevents models from being used for year-round climate applications or monitoring heat-related dynamics in non-summer periods.
- Incorporating physical auxiliary data: Explicitly modeling these factors could lead to more physically accurate and reliable urban climate forecasting compared to models relying solely on statistical inference from LST signals.

## Links

- [Abstract](https://arxiv.org/abs/2605.13566)
- [PDF](https://arxiv.org/pdf/2605.13566)

