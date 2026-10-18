---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Can AI Forecast the Extremes? Evaluating Probabilistic Weather Models on Tropical Cyclones"
description: "This paper evaluates the performance of state-of-the-art probabilistic AI weather models (GenCast, FourCastNet 3, and FGN) against the traditional physics-based IFS-ENS ensemble, specifically focusing on tropical cyclones. The authors find that while AI models significantly excel in cyclone tracking—with FGN outperforming the baseline in 90% of cases—they continue to struggle with storm intensity bias and maintaining realistic ensemble spread. The study introduces specialized probabilistic metrics to diagnose these shortcomings, revealing that AI models can capture complex physical relationships like the wind-pressure curve but are still heavily influenced by the biases of their pretraining data."
resource: "https://arxiv.org/abs/2610.22077"
tags:
  - "weather-forecasting"
  - "probabilistic-forecasting"
  - "extreme-event-forecasting"
  - "benchmarking"
  - "time-series"
  - "tropical-cyclones"
  - "numerical-weather-prediction"
  - "uncertainty-quantification"
timestamp: "2026-10-18T00:17:05Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Nathan Chalumeau"
  - literal: "Xavier Renard"
  - literal: "Remi Meynadier"
  - literal: "Hugo Rakotoarimanga"
  - literal: "Marcin Detyniecki"
  - literal: "Emmanuel de Bezenac"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22077"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "gencast"
    description: "A probabilistic data-driven weather forecasting model designed to generate ensemble predictions that model the joint probability distribution of future atmospheric states."
  - name: "fgn-weather-model"
    description: "A graph-based neural network architecture optimized for weather forecasting that excels in spatial tracking of discrete atmospheric phenomena like tropical cyclones."
datasets:
  []
open_questions:
  - name: "ai-weather-intensity-bias"
    description: "How can architectural constraints or training objectives be modified to allow AI models to predict the extreme peak intensities of tropical cyclones (e.g., maximum wind speeds) without compromising global forecast stability or introducing excessive noise?"
  - name: "extreme-event-data-distribution-shift"
    description: "To what extent does the rarity of extreme events in pretraining data limit a model's ability to learn the physical laws governing them, and can specialized data augmentation or fine-tuning on synthetic extremes mitigate this bottleneck?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:17:05Z"
created_at: "2026-10-18T00:17:05Z"
---

# Can AI Forecast the Extremes? Evaluating Probabilistic Weather Models on Tropical Cyclones

**Authors**: Nathan Chalumeau, Xavier Renard, Remi Meynadier, Hugo Rakotoarimanga, Marcin Detyniecki, Emmanuel de Bezenac
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22077](https://arxiv.org/abs/2610.22077)

## Summary

This paper evaluates the performance of state-of-the-art probabilistic AI weather models (GenCast, FourCastNet 3, and FGN) against the traditional physics-based IFS-ENS ensemble, specifically focusing on tropical cyclones. The authors find that while AI models significantly excel in cyclone tracking—with FGN outperforming the baseline in 90% of cases—they continue to struggle with storm intensity bias and maintaining realistic ensemble spread. The study introduces specialized probabilistic metrics to diagnose these shortcomings, revealing that AI models can capture complex physical relationships like the wind-pressure curve but are still heavily influenced by the biases of their pretraining data.

## Key Contributions

- Conducted an extensive benchmark comparing probabilistic AI weather models (GenCast, FourCastNet 3, FGN) against the physics-based IFS-ENS for tropical cyclone forecasting.
- Demonstrated that leading AI models, specifically FGN, significantly outperform operational physics-based ensembles in cyclone tracking accuracy (90% better location scores).
- Developed a suite of diagnostic metrics for extreme weather, focusing on intensity biases, ensemble spread, and the wind-pressure relationship.
- Identified critical failure modes in current AI models, including systematic intensity underestimation and the influence of pretraining data on extreme event performance.

## Limitations

Leading AI models still struggle with accurately predicting storm intensity and maintaining sufficient ensemble spread compared to physics-based systems.

## Open Questions & Future Work

- [[ai-weather-intensity-bias]]
- [[extreme-event-data-distribution-shift]]

## Key Concepts

- [[gencast]]: A probabilistic data-driven weather forecasting model designed to generate ensemble predictions that model the joint probability distribution of future atmospheric states.
- [[fgn-weather-model]]: A graph-based neural network architecture optimized for weather forecasting that excels in spatial tracking of discrete atmospheric phenomena like tropical cyclones.

## Archivist Review

I approved the two primary AI models (GenCast and FGN) that represent the state-of-the-art in probabilistic and graph-based weather forecasting, as they are central to the paper's benchmarking contribution. I also approved two open questions that address the fundamental technical bottlenecks identified in the study: systematic intensity bias and the limitations imposed by training on data dominated by average conditions. These selections capture the essence of the paper's findings regarding the 'extremes gap' in AI weather prediction.

### Approved Concepts
- GenCast: GenCast represents a major shift toward probabilistic, generative ensemble weather forecasting, moving beyond the deterministic outputs of earlier AI weather models.
- FGN (Forecast Graph Network): This model demonstrates superior performance in spatial tracking of extreme events, highlighting the efficacy of graph-based neural architectures in capturing atmospheric dynamics.

### Approved Open Questions
- Addressing Intensity Bias in AI Weather Models: Accurately forecasting storm intensity is a critical safety requirement for operational weather prediction, where underestimation can lead to inadequate disaster response.
- Pretraining Data Influence on Extreme Generalization: Identifying whether the bottleneck for extreme weather forecasting is architectural or data-driven is essential for the next generation of atmospheric foundation models.

### Rejected Candidates
- [concept] FourCastNet 3 (`fourcastnet-3`) - subcomponent_of_broader_mechanism: FourCastNet 3 is an iterative update to an existing architecture (FourCastNet) rather than a fundamentally new mechanism deserving a separate note.
- [concept] IFS-ENS (`ifs-ens`) - not_novel: IFS-ENS is a standard physics-based operational baseline from ECMWF and not an AI concept introduced or defined by this research.

## Links

- [Abstract](https://arxiv.org/abs/2610.22077)
- [PDF](https://arxiv.org/pdf/2610.22077)

