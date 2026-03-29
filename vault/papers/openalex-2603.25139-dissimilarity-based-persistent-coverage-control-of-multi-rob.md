---
# CSL-compatible fields
title: "Dissimilarity-Based Persistent Coverage Control of Multi-Robot Systems for Improving Solar Irradiance Prediction Accuracy in Solar Thermal Power Plants"
author:
  - literal: "Haruki Kawase"
  - literal: "Taiga Sugawara"
  - literal: "A. Daniel Carnerero"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25139"

# Custom fields
paper_id: "2603.25139"
paper_source: "openalex"
domain: "time-series"
tags:
  - "spatial-temporal"
  - "optimization"
  - "robotics"
  - "geostatistics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dissimilarity-map-active-sensing"
  - "persistent-coverage-control-active-sensing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:17:06Z"
created_at: "2026-03-29T20:17:06Z"
---

# Dissimilarity-Based Persistent Coverage Control of Multi-Robot Systems for Improving Solar Irradiance Prediction Accuracy in Solar Thermal Power Plants

**Authors**: Haruki Kawase, Taiga Sugawara, A. Daniel Carnerero
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25139](https://arxiv.org/abs/2603.25139)

## Summary

This paper addresses the challenge of accurately forecasting solar irradiance for solar thermal power plants by introducing a dynamic sensor placement strategy. The authors leverage a kriging model to generate a dissimilarity map, which quantifies the regions where additional observations would most significantly reduce prediction uncertainty. Based on this map, a Persistent Coverage Control (PCC) algorithm is proposed to effectively guide mobile robots to collect data optimally. Experimental results show that this dissimilarity-guided active sensing approach achieves higher prediction accuracy compared to standard baselines under various simulated irradiance conditions.

## Key Contributions

- Developed a dissimilarity map based on a kriging model to quantify regions most needing new sensor observations.
- Proposed a novel Persistent Coverage Control (PCC) algorithm to dynamically position mobile sensors to optimize solar irradiance prediction accuracy.
- Demonstrated experimentally that the proposed approach yields more accurate irradiance predictions than baseline methods with a minimal number of mobile sensors.

## Limitations

The experimental validation relies on emulated irradiance fields, and practical deployment challenges for mobile robots in a live power plant setting are not detailed.

## Key Concepts

- [[dissimilarity-map-active-sensing]]: A spatial map derived from a Kriging model that quantifies the required improvement in observation data across a field.
- [[persistent-coverage-control-active-sensing]]: An algorithm that directs mobile agents to persistently cover areas where new observations will maximally improve the underlying spatial prediction model.

## Archivist Review

Two core technical contributions were identified and approved as reusable concepts: the method of deriving a 'Dissimilarity Map' from a Kriging model to quantify observation needs, and the 'Persistent Coverage Control' algorithm used to dynamically move agents based on this map. These mechanisms represent general patterns in active sensing and model-guided robotics that are likely to recur. No datasets or open questions were deemed substantial or novel enough for permanent vault inclusion.

### Approved Concepts
- Dissimilarity Map (Solar Prediction): This map is the core novelty used to drive the agent's movement for optimal data acquisition.
- Persistent Coverage Control (PCC): This is the main algorithmic contribution, linking uncertainty mapping directly to agent navigation for control.

### Rejected Candidates
- [concept] Dissimilarity Map (Solar Prediction) (`dissimilarity-map-active-sensing`) - generic: The concept is generalized from the specific application (solar prediction) to reflect a reusable pattern of using model-derived uncertainty to guide active sensing.
- [concept] Persistent Coverage Control (PCC) (`persistent-coverage-control-active-sensing`) - generic: The PCC algorithm is viewed as a reusable control paradigm for active sensing driven by model uncertainty, which warrants a note.

## Links

- [Abstract](https://arxiv.org/abs/2603.25139)
- [PDF](https://arxiv.org/pdf/2603.25139)

