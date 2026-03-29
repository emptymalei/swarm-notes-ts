---
# CSL-compatible fields
title: "The impact of machine learning forecasting on strategic decision-making for bike sharing systems"
author:
  - literal: "Enrico Angelelli"
  - literal: "Andrea Mor"
  - literal: "Carlotta Orsenigo"
  - literal: "M. Grazia Speranza"
  - literal: "Carlo Vercellis"
issued:
  date-parts:
    - [2026, 3, 27]
url: "https://arxiv.org/abs/2603.14901"

# Custom fields
paper_id: "2603.14901"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "logistics"
  - "simulation"
  - "optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "bike-sharing-net-flow-forecasting"
  - "simulation-augmented-decision-support-bike-sharing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:15:39Z"
created_at: "2026-03-29T20:15:39Z"
---

# The impact of machine learning forecasting on strategic decision-making for bike sharing systems

**Authors**: Enrico Angelelli, Andrea Mor, Carlotta Orsenigo, M. Grazia Speranza, Carlo Vercellis
**Date**: 2026-03-27
**Paper ID**: [openalex:2603.14901](https://arxiv.org/abs/2603.14901)

## Summary

This paper explores the use of machine learning models to forecast the net flow of bikes (returns minus withdrawals) at individual stations within a bike-sharing system. The generated forecasts are then incorporated into a dynamic simulation framework designed to support strategic, long-term decision-making, including the necessary daily relocation of bikes. The authors evaluate the utility of the ML forecasts through a two-pronged approach: comparing their accuracy against alternative prediction methods and quantifying the downstream impact on the overall quality of the simulation's operational output. The evaluation is validated using real-world operational data from the bike sharing system operating in Brescia, Italy.

## Key Contributions

- Application of machine learning techniques to forecast the net flow difference (returns minus withdrawals) at bike-sharing stations.
- Integration of these ML-based forecasts into a simulation framework to support long-term strategic decision-making and model daily operational dynamics.
- Evaluation methodology that assesses forecast quality both against alternative prediction methods and by analyzing its impact on the simulation framework's output quality.

## Limitations

The evaluation is based solely on the real-world data from the Brescia bike sharing system, which might limit generalizability to other systems.

## Open Questions & Future Work

- [[improving-bss-forecasting-detail-over-net-demand]]

## Key Concepts

- [[bike-sharing-net-flow-forecasting]]: Forecasting the net difference between bike returns and withdrawals (inflows minus outflows) at individual stations within a bike-sharing network.
- [[simulation-augmented-decision-support-bike-sharing]]: Utilizing machine learning forecasts within a simulation environment to model daily operational dynamics and inform strategic decisions, such as bike relocation policies.

## Archivist Review

Two concepts were approved as they represent reusable methodological patterns: the specific forecasting target (net flow) and the system architecture (forecasts integrated into a simulation for decision support). One open question was approved as it raises a specific, unresolved modeling issue regarding the necessary level of forecasting detail (net flow vs. origin-destination). No datasets were approved because the single named dataset is local and does not meet the standard for inclusion.

### Approved Concepts
- Bike Sharing Net Flow Forecasting: This is the specific forecasting target tailored for bike-sharing operations, modeling the net inventory change at a station.
- Simulation-Augmented Decision Support for Bike Sharing: It represents a specific methodology where ML forecasts directly inform a dynamic simulation environment for operational decision-making.

### Approved Open Questions
- Relationship between forecasting detail and simulation accuracy: Moving beyond net demand to Origin-Destination (OD) or trip-specific forecasting could significantly improve the realism of the simulation and the quality of the resulting strategic recommendations for fleet management and service reliability.

### Rejected Candidates
- [dataset] Brescia bike sharing system data (`brest-bike-sharing-system-data`) - low_impact: The dataset is a single, specific, named operational dataset, which does not warrant a standalone canonical note according to the scarcity policy for datasets.

## Links

- [Abstract](https://arxiv.org/abs/2603.14901)
- [PDF](https://arxiv.org/pdf/2603.14901)

