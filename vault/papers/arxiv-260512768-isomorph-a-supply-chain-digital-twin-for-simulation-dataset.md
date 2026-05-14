---
# CSL-compatible fields
title: "ISOMORPH: A Supply Chain Digital Twin for Simulation, Dataset Generation, and Forecasting Benchmarks"
author:
  - literal: "Zhizhen Zhang"
  - literal: "Hyemin Gu"
  - literal: "Benjamin J. Zhang"
  - literal: "Daniel Elenius"
  - literal: "Michael Tyrrell"
  - literal: "Theo J. Bourdais"
  - literal: "Houman Owhadi"
  - literal: "Markos A. Katsoulakis"
  - literal: "Tuhin Sahai"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12768"

# Custom fields
paper_id: "2605.12768"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "benchmarking"
  - "time-series"
  - "uncertainty-quantification"
  - "simulation"
architectures:
  []
datasets:
  - "isomorph-dataset"
concept_slugs:
  - "isomorph-digital-twin"
dataset_slugs:
  - "isomorph-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:25:40Z"
created_at: "2026-05-14T05:25:40Z"
---

# ISOMORPH: A Supply Chain Digital Twin for Simulation, Dataset Generation, and Forecasting Benchmarks

**Authors**: Zhizhen Zhang, Hyemin Gu, Benjamin J. Zhang, Daniel Elenius, Michael Tyrrell, Theo J. Bourdais, Houman Owhadi, Markos A. Katsoulakis, Tuhin Sahai
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12768](https://arxiv.org/abs/2605.12768)

## Summary

ISOMORPH is a novel, public digital twin framework designed to address the scarcity of high-quality, interpretable benchmarks for multi-echelon supply chain logistics in time-series forecasting. The simulator models logistics as a Markov chain with tractable state space dynamics, enabling the generation of complex datasets that exhibit phenomena such as bullwhip effects and cascading bottlenecks. Evaluation on four major foundation models demonstrates that these models provide competitive forecast performance and can serve as fast, reliable surrogates for forward uncertainty quantification.

## Key Contributions

- Introduced ISOMORPH, a modular digital twin for multi-echelon supply chain logistics providing interpretable dynamics and conservation law verification.
- Released large-scale datasets (C=50 and C=200) exhibiting complex logistical phenomena such as bullwhip effects, variance amplification, and cascading bottlenecks.
- Demonstrated that foundation models like Chronos and TimesFM can serve as effective fast surrogates for forward uncertainty quantification within the digital twin.

## Open Questions & Future Work

- [[supply-chain-digital-twin-extensibility]]

## Key Concepts

- [[isomorph-digital-twin]]: A modular, interpretable multi-echelon supply chain digital twin for simulation, dataset generation, and forecasting benchmarks.

## Archivist Review

I approved the ISOMORPH framework and its associated dataset as they represent a significant step in addressing the lack of interpretable supply chain benchmarks in time-series forecasting. I also approved the open question on extending these digital twins to include more complex shock models and covariates, as this is a well-defined bottleneck for moving beyond current simplified supply chain simulators. The review was conducted with a focus on selecting only the most impactful, reusable contributions.

### Approved Concepts
- ISOMORPH: It addresses a significant gap in time-series forecasting benchmarks for supply chain logistics by providing a modular, interpretable simulator.

### Approved Open Questions
- Extending Supply Chain Digital Twin: This is a substantial bottleneck for evaluating the robustness of forecasting models against complex logistical phenomena like cascading bottlenecks and regime shifts.

## Datasets

- [[isomorph-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.12768)
- [PDF](https://arxiv.org/pdf/2605.12768)

