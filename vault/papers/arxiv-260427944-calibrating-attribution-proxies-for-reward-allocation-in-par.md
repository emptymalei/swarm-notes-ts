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
domain: "nlp"
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
processed_at: "2026-05-01T05:22:25Z"
created_at: "2026-05-01T05:22:25Z"
---

# Calibrating Attribution Proxies for Reward Allocation in Participatory Weather Sensing

**Authors**: Mark C. Ballandies, Michael T. C. Chiu, Claudio J. Tessone
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27944](https://arxiv.org/abs/2604.27944)

## Summary

This paper investigates incentive mechanisms for large-scale participatory weather sensing by using differentiable AI weather models to estimate the value of individual data contributions. The authors characterize gradient-based attribution on GFS analysis inputs as a scalable value signal, contrasting it with traditional, computationally intensive adjoint-based methods. Through an extensive evaluation of over 400 configurations, the study demonstrates that gradient attribution effectively aligns with sensor placement utility but requires mitigation strategies against adversarial gaming.

## Key Contributions

- Demonstrates that gradient-based attribution on differentiable AI weather models functions as a computationally efficient proxy for data contribution value, matching near-optimal sensor placement utility.
- Establishes that while attribution provides monotonic payments, it is vulnerable to adversarial inputs, necessitating external baseline data for robust validation.
- Provides a systematic evaluation of over 400 configurations assessing the trade-offs between fidelity, calibration, cost, and gaming susceptibility in weather data incentivization.

## Open Questions & Future Work

- [[bridging-station-to-grid-valuation-gap]]
- [[adversarial-spoofing-resilience]]

## Key Concepts

- [[gradient-based-attribution-for-weather-data-valuation]]: A method for assessing the utility of individual weather sensor data contributions by leveraging gradient information from differentiable AI weather models.

## Archivist Review

The paper introduces gradient-based attribution as a proxy for valuing data contributions in participatory sensing networks. I approved the core mechanism as a concept and the identified bottlenecks in valuation and security as open questions, as they represent fundamental challenges in deploying differentiable model-informed incentives. The GFS data was rejected as it is a standard meteorological product.

### Approved Concepts
- Gradient-based Attribution for Weather Data Valuation: Provides a computationally efficient proxy for data contribution value in participatory sensing where traditional adjoint methods are too costly.

### Approved Open Questions
- Station-to-Grid Valuation Gap: This is the core bottleneck to applying model-derived valuation in real-world infrastructure; without bridging this gap, the proxy may overstate or misinterpret the actual utility of sparse physical ground stations.
- Adversarial Spoofing Resilience: As attribution-based rewards become operational, they will inevitably become targets for strategic actors, necessitating a deeper understanding of adversarial spoofing resilience.

### Rejected Candidates
- [dataset] GFS analysis inputs (`gfs-analysis-inputs`) - not_novel: Standard gridded meteorological analysis product, not a distinct research dataset requiring a standalone entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.27944)
- [PDF](https://arxiv.org/pdf/2604.27944)

