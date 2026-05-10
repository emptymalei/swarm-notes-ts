---
# CSL-compatible fields
title: "Earth-o1: A Grid-free Observation-native Atmospheric World Model"
author:
  - literal: "Junchao Gong"
  - literal: "Kaiyi Xu"
  - literal: "Wangxu Wei"
  - literal: "Siwei Tu"
  - literal: "Siwei Tu"
  - literal: "Jingyi Xu"
  - literal: "Zili Liu"
  - literal: "Hang Fan"
  - literal: "Zhiwang Zhou"
  - literal: "Tao Han"
  - literal: "Yi Xiao"
  - literal: "Xinyu Gu"
  - literal: "Zhangrui Li"
  - literal: "Wenlong Zhang"
  - literal: "Hao Chen"
  - literal: "Xiaokang Yang"
  - literal: "Yaqiang Wang"
  - literal: "Lijing Cheng"
  - literal: "Pierre Gentine"
  - literal: "Wanli Ouyang"
  - literal: "Feng Zhang"
  - literal: "Zhe-Min Tan"
  - literal: "Bowen Zhou"
  - literal: "Fenghua Ling"
  - literal: "Ben Fei"
  - literal: "Lei Bai"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06337"

# Custom fields
paper_id: "2605.06337"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "observation-native-atmospheric-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:18:45Z"
created_at: "2026-05-10T05:18:45Z"
---

# Earth-o1: A Grid-free Observation-native Atmospheric World Model

**Authors**: Junchao Gong, Kaiyi Xu, Wangxu Wei, Siwei Tu, Siwei Tu, Jingyi Xu, Zili Liu, Hang Fan, Zhiwang Zhou, Tao Han, Yi Xiao, Xinyu Gu, Zhangrui Li, Wenlong Zhang, Hao Chen, Xiaokang Yang, Yaqiang Wang, Lijing Cheng, Pierre Gentine, Wanli Ouyang, Feng Zhang, Zhe-Min Tan, Bowen Zhou, Fenghua Ling, Ben Fei, Lei Bai
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06337](https://arxiv.org/abs/2605.06337)

## Summary

Earth-o1 is an observation-native atmospheric world model that eliminates the need for predefined spatial grids by directly learning continuous, three-dimensional physical dynamics from raw, ungridded observational data. Unlike traditional frameworks that rely on explicit numerical solvers or complex data assimilation, this grid-free paradigm autonomously advances the atmospheric state in space and time. Evaluation shows the model achieves surface forecasting performance competitive with the operational Integrated Forecasting System (IFS), demonstrating the potential of fully observation-driven simulators for digital twin applications.

## Key Contributions

- Introduces Earth-o1, a grid-free world model that bypasses traditional atmospheric spatial gridding and numerical solvers.
- Demonstrates that direct learning from raw, ungridded observational data enables real-time forecasting and cross-sensor inference.
- Achieves surface forecast performance comparable to the operational Integrated Forecasting System (IFS) in hindcast evaluations.

## Open Questions & Future Work

- [[advancing-observation-native-earth-models]]

## Key Concepts

- [[observation-native-atmospheric-world-model]]: A grid-free modeling framework that learns 3D physical atmospheric evolution directly from ungridded, heterogeneous sensor data.

## Archivist Review

I approved the primary contribution concept and the identified bottleneck question regarding observation-native world models. I applied a strict filter to ensure only the core paradigm shift was captured, rejecting minor sub-modules or general future work. No datasets were approved as none were highlighted as specific, reusable, and novel benchmarking contributions.

### Approved Concepts
- Observation-native atmospheric world model: Defines a new paradigm of grid-free, sensor-native modeling that circumvents traditional grid-based computational bottlenecks in geophysics.

### Approved Open Questions
- Advancing Observation-native Earth Models: Identifies specific technical bottlenecks regarding uncertainty, modal generalization, and scientific interpretability essential for evolving these simulators into foundational scientific discovery tools.

## Links

- [Abstract](https://arxiv.org/abs/2605.06337)
- [PDF](https://arxiv.org/pdf/2605.06337)

