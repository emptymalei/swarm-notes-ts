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
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "observation-native-atmospheric-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:10:36Z"
created_at: "2026-05-09T05:10:36Z"
---

# Earth-o1: A Grid-free Observation-native Atmospheric World Model

**Authors**: Junchao Gong, Kaiyi Xu, Wangxu Wei, Siwei Tu, Siwei Tu, Jingyi Xu, Zili Liu, Hang Fan, Zhiwang Zhou, Tao Han, Yi Xiao, Xinyu Gu, Zhangrui Li, Wenlong Zhang, Hao Chen, Xiaokang Yang, Yaqiang Wang, Lijing Cheng, Pierre Gentine, Wanli Ouyang, Feng Zhang, Zhe-Min Tan, Bowen Zhou, Fenghua Ling, Ben Fei, Lei Bai
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06337](https://arxiv.org/abs/2605.06337)

## Summary

Earth-o1 is a grid-free atmospheric world model that directly learns 3D physical dynamics from ungridded observational data, bypassing the constraints of traditional predefined spatial grids. By modeling the continuous evolution of atmospheric states, the system enables efficient real-time forecasting and cross-sensor inference. Evaluations show that this approach achieves surface forecast performance on par with the operational Integrated Forecasting System (IFS), demonstrating the viability of observation-native geophysical simulators.

## Key Contributions

- Introduces Earth-o1, a grid-free atmospheric world model that eliminates the computational overhead of traditional spatial grid interpolation.
- Enables direct, real-time forecasting and cross-sensor inference by learning continuous, three-dimensional physical evolution from ungridded data.
- Demonstrates surface forecast skill comparable to the operational Integrated Forecasting System (IFS) without relying on traditional numerical solvers.

## Open Questions & Future Work

- [[uncertainty-and-interpretability-in-observation-native-models]]

## Key Concepts

- [[observation-native-atmospheric-world-model]]: A grid-free atmospheric modeling framework that learns physical dynamics directly from raw, ungridded observational sensor data.

## Archivist Review

The paper introduces an important paradigm shift by replacing traditional fixed-grid numerical weather prediction with grid-free, observation-native world modeling. I approved the core concept of 'Observation-native Atmospheric World Model' and the open question regarding the fundamental challenges of uncertainty and interpretability in this new class of models. I applied strict criteria to ensure the note focuses on the architectural shift rather than the specific performance metrics or the implementation-specific 'Earth-o1' model.

### Approved Concepts
- Observation-native Atmospheric World Model: Proposes a paradigm shift from grid-based numerical weather prediction to direct, ungridded physical evolution modeling.

### Approved Open Questions
- Uncertainty and Interpretability in World Models: Defining a robust, probabilistic, and interpretable framework for observation-native latent spaces is essential for transitioning from empirical performance to scientific reliability in geophysical simulation.

## Links

- [Abstract](https://arxiv.org/abs/2605.06337)
- [PDF](https://arxiv.org/pdf/2605.06337)

