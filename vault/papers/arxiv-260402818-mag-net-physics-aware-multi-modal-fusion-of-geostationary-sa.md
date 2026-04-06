---
# CSL-compatible fields
title: "MAG-Net: Physics-Aware Multi-Modal Fusion of Geostationary Satellite and Radar for Severe Convective Precipitation Nowcasting"
author:
  - literal: "Dandan Chen"
  - literal: "Yaqiang Wang"
  - literal: "Anyuan Xiong"
  - literal: "Enda Zhu"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02818"

# Custom fields
paper_id: "2604.02818"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "multi-modal-learning"
  - "spatiotemporal-forecasting"
  - "nowcasting"
  - "generative-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gradient-preserving-fusion-gpf"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-06T05:03:05Z"
created_at: "2026-04-06T05:03:05Z"
---

# MAG-Net: Physics-Aware Multi-Modal Fusion of Geostationary Satellite and Radar for Severe Convective Precipitation Nowcasting

**Authors**: Dandan Chen, Yaqiang Wang, Anyuan Xiong, Enda Zhu
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02818](https://arxiv.org/abs/2604.02818)

## Summary

MAG-Net is a physics-aware multi-modal generative network designed to improve convective precipitation nowcasting by fusing radar dynamics with geostationary satellite data. By incorporating thermodynamic and microphysical precursors, the model addresses performance degradation at longer lead times and reduces common generative blurring effects. Its performance is further enhanced by an inference-time Gradient-Preserving Fusion (GPF) strategy, which balances probabilistic constraints with regression accuracy. Experiments over southeastern China confirm the model's superior capability in detecting intense convective events compared to existing deterministic and generative baselines.

## Key Contributions

- Introduces MAG-Net, a physics-aware fusion architecture integrating radar data with geostationary satellite imagery to capture thermodynamic precursors for severe weather.
- Proposes an inference-time Gradient-Preserving Fusion (GPF) strategy that mitigates blurring artifacts by combining probabilistic event constraints with regression outputs.
- Demonstrates significant improvements over state-of-the-art baselines like CPrecNet and DGMR, achieving a 0.083 increase in CSI40 for intense convective echo detection.

## Open Questions & Future Work

- [[cross-climate-generalization-convective-nowcasting]]

## Key Concepts

- [[gradient-preserving-fusion-gpf]]: An inference-time fusion strategy that balances probabilistic constraints and regression details to preserve high-frequency textures in generative forecasting.

## Archivist Review

I approved the Gradient-Preserving Fusion concept as it provides a reusable strategy for mitigating generative blurring in spatiotemporal tasks. I also approved an open question regarding cross-climate generalization, as it addresses a fundamental bottleneck in the robustness of physics-informed forecasting models. I rejected the model name itself to maintain focus on reusable methodological contributions.

### Approved Concepts
- Gradient-Preserving Fusion (GPF): GPF is the central mechanism introduced to address the blurring effects commonly found in generative precipitation nowcasting.

### Approved Open Questions
- Cross-Climate Nowcasting Generalization: Understanding the limits of cross-climate generalization is crucial for the deployment of machine learning-based weather forecasting tools in global operational environments.

### Rejected Candidates
- [concept] MAG-Net (`mag-net`) - paper_local: This is a paper-specific model architecture rather than a general method or pattern.

## Links

- [Abstract](https://arxiv.org/abs/2604.02818)
- [PDF](https://arxiv.org/pdf/2604.02818)

