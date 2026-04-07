---
# CSL-compatible fields
title: "Solar-VLM: Multimodal Vision-Language Models for Augmented Solar Power Forecasting"
author:
  - literal: "Hang Fan"
  - literal: "Haoran Pei"
  - literal: "Runze Liang"
  - literal: "Weican Liu"
  - literal: "Long Cheng"
  - literal: "Wei Wei"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.04145"

# Custom fields
paper_id: "2604.04145"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-04-07T04:54:35Z"
created_at: "2026-04-07T04:54:35Z"
---

# Solar-VLM: Multimodal Vision-Language Models for Augmented Solar Power Forecasting

**Authors**: Hang Fan, Haoran Pei, Runze Liang, Weican Liu, Long Cheng, Wei Wei
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.04145](https://arxiv.org/abs/2604.04145)

## Summary

Solar-VLM is a multimodal framework that integrates temporal, visual, and textual data to improve photovoltaic power forecasting accuracy. The model uses specialized encoders for each modality and employs a graph-based attention mechanism to capture complex spatial relationships between geographically distributed PV sites. By effectively fusing these heterogeneous inputs, Solar-VLM addresses the limitations of unimodal forecasting approaches in modeling highly dynamic solar power generation.

## Key Contributions

- Introduced Solar-VLM, a unified multimodal framework for photovoltaic (PV) power forecasting integrating temporal observations, satellite imagery, and textual weather reports.
- Developed modality-specific encoders and a cross-site feature fusion mechanism combining Graph Attention Networks (GATs) with cross-site attention to model spatiotemporal interdependencies.
- Demonstrated superior performance over existing models using a dataset of eight geographically distributed PV stations in Northern China.

## Open Questions & Future Work

- [[few-shot-multimodal-pv-forecasting-limits]]

## Archivist Review

I have rejected all concept candidates as they represent standard architectural implementations (e.g., combining encoders or using GATs for spatial dependencies) rather than novel, reusable theoretical mechanisms. The open question was refined for consistency with existing nomenclature while keeping its core focus on the data-efficiency bottleneck of multimodal forecasting models.

### Approved Open Questions
- Few-shot Multimodal Forecasting Limits: This addresses the practical bottleneck of deploying large, data-hungry models in real-world scenarios where high-quality, large-scale training data for specific PV sites may not be readily available.

### Rejected Candidates
- [open_question] Few-shot PV forecasting with VLMs (`vlm-few-shot-pv-forecasting`) - other: Renamed to align with standard vault naming conventions for open questions.

## Links

- [Abstract](https://arxiv.org/abs/2604.04145)
- [PDF](https://arxiv.org/pdf/2604.04145)

