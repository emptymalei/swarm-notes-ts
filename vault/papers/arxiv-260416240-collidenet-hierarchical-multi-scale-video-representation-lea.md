---
# CSL-compatible fields
title: "CollideNet: Hierarchical Multi-scale Video Representation Learning with Disentanglement for Time-To-Collision Forecasting"
author:
  - literal: "Nishq Poorav Desai"
  - literal: "Ali Etemad"
  - literal: "Michael Greenspan"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16240"

# Custom fields
paper_id: "2604.16240"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "time-series-forecasting"
  - "video-analysis"
  - "transformer"
  - "spatiotemporal-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "collidenet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:08:14Z"
created_at: "2026-04-20T05:08:14Z"
---

# CollideNet: Hierarchical Multi-scale Video Representation Learning with Disentanglement for Time-To-Collision Forecasting

**Authors**: Nishq Poorav Desai, Ali Etemad, Michael Greenspan
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16240](https://arxiv.org/abs/2604.16240)

## Summary

CollideNet is a hierarchical transformer-based framework designed for effective time-to-collision (TTC) forecasting in video data. The architecture utilizes a dual-stream approach: a spatial stream for multi-resolution frame aggregation and a temporal stream that disentangles video features into non-stationary, trend, and seasonal components. By effectively modeling these diverse spatiotemporal patterns, CollideNet establishes new state-of-the-art performance across multiple public benchmarks and demonstrates superior generalization capabilities.

## Key Contributions

- Introduced CollideNet, a hierarchical spatiotemporal transformer architecture that processes video at multiple spatial resolutions and temporal scales.
- Implemented a temporal disentanglement mechanism within the temporal stream to isolate non-stationarity, trend, and seasonality components for improved TTC estimation.
- Achieved state-of-the-art results on three public video datasets, demonstrating significant improvements in forecasting accuracy and cross-dataset generalization.

## Open Questions & Future Work

- [[domain-shift-ttc-forecasting]]

## Key Concepts

- [[collidenet]]: A spatiotemporal hierarchical transformer architecture designed for multi-scale video representation and time-to-collision forecasting.

## Archivist Review

I approved the core architecture CollideNet because it provides a distinct, reusable methodology for hierarchical spatiotemporal disentanglement. I also approved the open question regarding TTC domain generalization, as it addresses a safety-critical bottleneck in real-world deployment that is explicitly highlighted by the performance variability observed in the paper. No datasets were approved as none were defined as central, novel, or unique contributions.

### Approved Concepts
- CollideNet: The hierarchical design and temporal disentanglement strategy are presented as a reusable framework for spatiotemporal video forecasting.

### Approved Open Questions
- TTC Forecasting Domain Generalization: TTC forecasting is safety-critical, and model degradation in new environments directly impacts the reliability of automated collision prevention systems.

### Rejected Candidates
- [concept] CollideNet sub-modules (`collidenet-architecture-subcomponents`) - subcomponent_of_broader_mechanism: The architecture is better represented as a single holistic concept; internal sub-modules do not warrant standalone notes.

## Links

- [Abstract](https://arxiv.org/abs/2604.16240)
- [PDF](https://arxiv.org/pdf/2604.16240)

