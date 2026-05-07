---
# CSL-compatible fields
title: "Densification and forecasting of Sentinel-2 time series from multimodal SAR and Optical satellite data using deep generative models"
author:
  - literal: "Véronique Defonte"
  - literal: "Dawa Derksen"
  - literal: "Alexandre Constantin"
  - literal: "Bastien Nespoulous"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04239"

# Custom fields
paper_id: "2605.04239"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "multimodal"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:16:33Z"
created_at: "2026-05-07T05:16:33Z"
---

# Densification and forecasting of Sentinel-2 time series from multimodal SAR and Optical satellite data using deep generative models

**Authors**: Véronique Defonte, Dawa Derksen, Alexandre Constantin, Bastien Nespoulous
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04239](https://arxiv.org/abs/2605.04239)

## Summary

This paper introduces a probabilistic deep learning framework to address the temporal irregularity of optical satellite image time series caused by cloud cover. By integrating multimodal Sentinel-1 SAR and Sentinel-2 optical data, the model enables both the reconstruction of missing historical observations and the forecasting of future states at arbitrary timestamps. A key innovation of the framework is its focus on quantifying uncertainty in the generated imagery, providing more robust monitoring capabilities than traditional interpolation or reconstruction methods.

## Key Contributions

- Proposes a probabilistic deep generative framework for joint densification and forecasting of Sentinel-2 optical imagery.
- Leverages multimodal integration of Sentinel-1 SAR and Sentinel-2 optical data to overcome irregular temporal sampling and cloud obstruction.
- Demonstrates the capacity to generate optical imagery for arbitrary past and future timestamps while quantifying predictive uncertainty.

## Open Questions & Future Work

- [[snow-cloud-discrimination-robustness]]
- [[sar-utilization-rapid-change]]

## Archivist Review

The paper presents an interesting application of probabilistic generative models for satellite image densification. However, it does not propose a specific novel, reusable architecture or mechanism that qualifies for a standalone concept note under our strict selection criteria. The identified open questions regarding environmental robustness and multimodal signal utilization represent substantial challenges in Earth observation modeling and thus warrant permanent tracking.

### Approved Open Questions
- Discriminating snow from clouds: This is a fundamental failure mode in high-altitude or seasonal applications, and addressing it is crucial for robust, all-weather global satellite monitoring.
- SAR utilization for rapid changes: This addresses a potential bottleneck in the sensitivity of multimodal fusion models to fast-evolving environmental phenomena, which is critical for agricultural and disaster monitoring applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.04239)
- [PDF](https://arxiv.org/pdf/2605.04239)

