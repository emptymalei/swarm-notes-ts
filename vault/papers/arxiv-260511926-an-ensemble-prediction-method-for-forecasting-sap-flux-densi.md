---
# CSL-compatible fields
title: "An ensemble prediction method for forecasting sap flux density and water-use in temperate trees"
author:
  - literal: "Mengyi Gong"
  - literal: "Rebecca Killick"
  - literal: "Andrew Hirons"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11926"

# Custom fields
paper_id: "2605.11926"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-05-13T05:24:21Z"
created_at: "2026-05-13T05:24:21Z"
---

# An ensemble prediction method for forecasting sap flux density and water-use in temperate trees

**Authors**: Mengyi Gong, Rebecca Killick, Andrew Hirons
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11926](https://arxiv.org/abs/2605.11926)

## Summary

This paper introduces an ensemble prediction framework designed for real-time monitoring and forecasting of daily tree sap flux density and water-use. By integrating IoT sensor data with additive models, the method effectively captures complex, non-linear relationships between physiological tree responses and dynamic environmental drivers. The approach is validated on multi-season field data across nine tree species, demonstrating robust performance for irrigation decision support even under extreme conditions like heatwaves.

## Key Contributions

- Proposed an ensemble prediction pipeline utilizing additive models to forecast daily sap flux density and tree water-use.
- Developed a framework that accounts for non-linear interactions between sap flux density and environmental drivers, alongside inter-tree variability across growing seasons.
- Demonstrated the model's reliability in irrigation management and climate-stressed conditions using a three-year dataset across nine distinct tree species.

## Open Questions & Future Work

- [[predicting-tree-water-use-under-heatwaves]]
- [[tree-size-scaling-water-use]]

## Archivist Review

I have reviewed the submission and decided to approve the two open questions as they represent significant, non-boilerplate research challenges in hydrological forecasting. The proposed ensemble concept was rejected because it is a generic implementation detail specific to the authors' pipeline and does not offer a novel or distinct enough conceptual advancement to warrant a permanent vault note. No datasets were approved as the field data was not named or provided as a standardized, reusable public benchmark.

### Approved Open Questions
- Predicting tree water-use during heatwaves: Improving the robustness of water-use forecasts during climate extremes is essential for sustainable irrigation management and ecosystem conservation under changing climate scenarios.
- Impact of tree size on scaling: Addressing the scaling bottleneck is critical for applying individual-tree sensor data to large-scale forestry and agricultural irrigation planning.

### Rejected Candidates
- [concept] Ensemble prediction pipeline (`ensemble-prediction-pipeline`) - paper_local: This is a descriptive term for the author's specific model implementation rather than a distinct, widely reusable methodology.

## Links

- [Abstract](https://arxiv.org/abs/2605.11926)
- [PDF](https://arxiv.org/pdf/2605.11926)

