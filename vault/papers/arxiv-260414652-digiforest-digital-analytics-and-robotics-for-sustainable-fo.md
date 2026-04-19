---
# CSL-compatible fields
title: "DigiForest: Digital Analytics and Robotics for Sustainable Forestry"
author:
  - literal: "Marco Camurri"
  - literal: "Enrico Tomelleri"
  - literal: "Matías Mattamala"
  - literal: "Sebastián Barbas Laina"
  - literal: "Martin Jacquet"
  - literal: "Jens Behley"
  - literal: "Sunni Kanta Prasad Kushwaha"
  - literal: "Fang Nan"
  - literal: "Nived Chebrolu"
  - literal: "Leonard Freißmuth"
  - literal: "Marvin Chayton Harms"
  - literal: "Meher V. R. Malladi"
  - literal: "Fan Yang"
  - literal: "Jonas Frey"
  - literal: "Cesar Cadena"
  - literal: "Marco Hutter"
  - literal: "Janine Schweier"
  - literal: "Kostas Alexis"
  - literal: "Cyrill Stachniss"
  - literal: "Maurice Fallon"
  - literal: "Stefan Leutenegger"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14652"

# Custom fields
paper_id: "2604.14652"
paper_source: "arxiv"
domain: "robotics"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "digiforest"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:05:59Z"
created_at: "2026-04-19T05:05:59Z"
---

# DigiForest: Digital Analytics and Robotics for Sustainable Forestry

**Authors**: Marco Camurri, Enrico Tomelleri, Matías Mattamala, Sebastián Barbas Laina, Martin Jacquet, Jens Behley, Sunni Kanta Prasad Kushwaha, Fang Nan, Nived Chebrolu, Leonard Freißmuth, Marvin Chayton Harms, Meher V. R. Malladi, Fan Yang, Jonas Frey, Cesar Cadena, Marco Hutter, Janine Schweier, Kostas Alexis, Cyrill Stachniss, Maurice Fallon, Stefan Leutenegger
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14652](https://arxiv.org/abs/2604.14652)

## Summary

DigiForest is a comprehensive framework for sustainable forestry that combines autonomous robotics with digital analytics for precise forest management. The system utilizes a fleet of aerial, legged, and marsupial robots to collect granular tree-level data, which is processed to generate automated forest inventories. Additionally, it incorporates a Decision Support System for growth forecasting and autonomous harvesters designed for low-impact logging, validated across diverse European forest environments.

## Key Contributions

- Introduces DigiForest, a large-scale precision forestry framework integrating autonomous robotics and digital analytics.
- Develops a heterogeneous robotic system (aerial, legged, marsupial) for high-fidelity tree-level data collection.
- Provides a forest inventory automation pipeline that extracts tree traits for growth forecasting and sustainable decision support.

## Open Questions & Future Work

- [[collaborative-marsupial-forestry-exploration]]
- [[online-panoptic-segmentation-robotics]]

## Key Concepts

- [[digiforest]]: A comprehensive precision forestry framework integrating heterogeneous autonomous robotics, automated tree trait extraction, and decision support systems.

## Archivist Review

I approved the DigiForest framework as a novel, integrated approach to precision forestry. I also approved two research questions focused on the technical bottlenecks of marsupial robotic coordination and real-time panoptic segmentation for mobile platforms, as these are significant, unresolved challenges in robotics and environmental sensing. I rejected the mentioned dataset because it is described as a collection of field validation locations rather than a unified, canonical benchmark dataset suitable for vault archival.

### Approved Concepts
- DigiForest: It is the core framework introduced in the paper, defining a multi-modal robotic and digital ecosystem for precision forestry.

### Approved Open Questions
- Collaborative Marsupial Forestry Exploration: Marsupial systems are critical for overcoming the limited endurance of drones and the limited traversability of legged robots in dense forestry; establishing robust collaborative frameworks is essential for scaling these deployments.
- Online Panoptic Segmentation for Robotics: Onboard semantic and instance-aware mapping is necessary for robots to perform intelligent, site-specific decision-making in real-time, such as identifying specific tree species or health conditions during navigation.

### Rejected Candidates
- [dataset] DigiForest-Finland-UK-Switzerland-dataset (`DigiForest-Finland-UK-Switzerland-dataset`) - low_impact: This is a loosely defined collection of field data rather than a standardized, named benchmark dataset intended for broad reuse.

## Links

- [Abstract](https://arxiv.org/abs/2604.14652)
- [PDF](https://arxiv.org/pdf/2604.14652)

