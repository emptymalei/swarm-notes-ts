---
# CSL-compatible fields
title: "Calibrating Attribution Proxies for Reward Allocation in Participatory Weather Sensing"
author:
  - literal: "Mark C. Ballandies"
  - literal: "Michael T. C. Chiu"
  - literal: "Claudio J. Tessone"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27944"

# Custom fields
paper_id: "2604.27944"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "gradient-based-attribution-for-weather-data-valuation"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-02T05:07:42Z"
created_at: "2026-05-02T05:07:42Z"
---

# Calibrating Attribution Proxies for Reward Allocation in Participatory Weather Sensing

**Authors**: Mark C. Ballandies, Michael T. C. Chiu, Claudio J. Tessone
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27944](https://arxiv.org/abs/2604.27944)

## Summary

This paper investigates the use of differentiable AI weather models to calculate the value of data contributions in participatory IoT weather networks. By characterizing gradient-based attribution on gridded GFS analysis inputs, the authors establish a computationally efficient proxy for reward allocation. Extensive evaluation reveals that while these attribution methods are faithful to sensor placement utility, they are susceptible to adversarial manipulation that requires baseline-based mitigation.

## Key Contributions

- Introduces gradient-based attribution using differentiable AI weather models as a scalable proxy for data contribution value in IoT sensing networks.
- Validates that attribution signals correlate with sensor placement utility and provide monotonically faithful payment structures.
- Demonstrates vulnerability to adversarial inputs, necessitating external baseline data for robust, gaming-resistant reward allocation.

## Open Questions & Future Work

- [[bridging-station-to-grid-valuation-gap]]

## Key Concepts

- [[gradient-based-attribution-for-weather-data-valuation]]: A method using gradients from differentiable AI weather models to estimate the marginal utility of local weather data contributions.

## Archivist Review

The paper contributes a novel, scalable approach for quantifying the value of data in participatory sensing networks using differentiable AI models. The gradient-based attribution concept is approved as a reusable method. The open question regarding the gap between model-level simulated sensitivity and actual sensor impact is approved as a critical, research-worthy bottleneck for field deployment. An architectural stability question was rejected as it is less fundamental than the core valuation infrastructure challenge.

### Approved Concepts
- gradient-based attribution for weather data valuation: Provides a scalable computational method for quantifying data contribution value that circumvents the high overhead of full data assimilation infrastructures.

### Approved Open Questions
- Bridging station to grid valuation gap: Necessary for transitioning from simulated theoretical reward models to reliable, operational incentive systems.

### Rejected Candidates
- [open_question] Stability of Architectural Complementarity (`architectural-complementarity-stability`) - not_novel: The stability of architectural behavior across future model generations is a generic performance characteristic of emerging architectures rather than a foundational bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.27944)
- [PDF](https://arxiv.org/pdf/2604.27944)

