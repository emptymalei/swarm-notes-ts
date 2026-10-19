---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Energy-Aware Earth System Science: A Community Roadmap"
description: "This paper presents a community roadmap for integrating energy awareness into Earth system science by analyzing the computational efficiency of models from the Coupled Model Intercomparison Project (CMIP) over three decades. The authors derive a scaling law showing that model error decreases by 13.5% for every doubling of compute, while highlighting that some variables like precipitation have seen minimal improvement. The study critiques the lack of energy reporting in modern machine-learning weather models and introduces a 'skill-energy framework' designed to rank models based on an empirical Pareto front of performance versus power consumption."
resource: "https://arxiv.org/abs/2610.23216"
tags:
  - "climate-science"
  - "earth-system-modeling"
  - "energy-efficiency"
  - "benchmarking"
  - "model-evaluation"
  - "weather-forecasting"
  - "energy-policy"
  - "sustainability"
timestamp: "2026-10-19T04:32:13Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ioana Colfescu"
  - literal: "Annalisa Bracco"
  - literal: "Kara Moraw"
  - literal: "Chen Lu"
  - literal: "Michael Bareford"
  - literal: "Tom Beucler"
  - literal: "Massimo Bollasina"
  - literal: "Juan Carlos Bilbao-Ludena"
  - literal: "Hannah Christensen"
  - literal: "Serafina DiGioia"
  - literal: "Gregory J. Hakim"
  - literal: "Thomas Hauser"
  - literal: "Adrian Jackson"
  - literal: "Phong Le"
  - literal: "Ilenia Manco"
  - literal: "Stephen Mobbs"
  - literal: "Amirpasha Mozaffari"
  - literal: "Antonio Navarra"
  - literal: "Mark Parsons"
  - literal: "James W. B. Rae"
  - literal: "Thomas Reichler"
  - literal: "Carlos Rodriguez-Pardo"
  - literal: "Graham Stacey"
  - literal: "Michèle Weiland"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23216"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "skill-energy-framework"
    description: "An evaluation methodology for Earth system models that uses an empirical Pareto front and ranking score to integrate energy consumption with predictive performance."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-19T04:32:13Z"
created_at: "2026-10-19T04:32:13Z"
---

# Energy-Aware Earth System Science: A Community Roadmap

**Authors**: Ioana Colfescu, Annalisa Bracco, Kara Moraw, Chen Lu, Michael Bareford, Tom Beucler, Massimo Bollasina, Juan Carlos Bilbao-Ludena, Hannah Christensen, Serafina DiGioia, Gregory J. Hakim, Thomas Hauser, Adrian Jackson, Phong Le, Ilenia Manco, Stephen Mobbs, Amirpasha Mozaffari, Antonio Navarra, Mark Parsons, James W. B. Rae, Thomas Reichler, Carlos Rodriguez-Pardo, Graham Stacey, Michèle Weiland
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23216](https://arxiv.org/abs/2610.23216)

## Summary

This paper presents a community roadmap for integrating energy awareness into Earth system science by analyzing the computational efficiency of models from the Coupled Model Intercomparison Project (CMIP) over three decades. The authors derive a scaling law showing that model error decreases by 13.5% for every doubling of compute, while highlighting that some variables like precipitation have seen minimal improvement. The study critiques the lack of energy reporting in modern machine-learning weather models and introduces a 'skill-energy framework' designed to rank models based on an empirical Pareto front of performance versus power consumption.

## Key Contributions

- Quantified the relationship between model error and compute across 5 CMIP generations, finding a 13.5% error reduction per doubling of compute power.
- Demonstrated the diminishing returns of scaling, showing that halving CMIP6 error would require a 28-fold increase in computational resources.
- Identified significant stagnation in precipitation error reduction (only 7% since CMIP1) compared to sea-level pressure and temperature.
- Proposed a skill-energy framework to standardize the reporting of energy use alongside predictive performance for future model intercomparisons.

## Limitations

The study relies on archived output and historical estimates of compute, which may not capture the nuances of the latest specialized AI hardware or undisclosed proprietary model energy data.

## Key Concepts

- [[skill-energy-framework]]: An evaluation methodology for Earth system models that uses an empirical Pareto front and ranking score to integrate energy consumption with predictive performance.

## Archivist Review

The analysis identifies the 'Skill-Energy Framework' as a significant methodological contribution for standardizing energy-aware evaluations in climate science and potentially other compute-intensive fields. I have approved this concept due to its high reusability and relevance to sustainable AI. Scaling laws were rejected as a concept because they are an established phenomenon being applied here rather than a new discovery of the mechanism itself. The CMIP dataset was rejected because specific versions are already well-documented in the knowledge vault.

### Approved Concepts
- Skill-Energy Framework: It addresses the critical need to balance computational cost and energy consumption against predictive skill in Earth system modeling, moving beyond pure performance metrics.

### Rejected Candidates
- [concept] ESM Scaling Laws (`esm-scaling-laws`) - not_novel: Scaling laws are a well-established phenomenon in machine learning; the specific coefficients found for ESMs in this study are empirical results rather than a novel, reusable methodological concept.
- [dataset] CMIP Datasets (`cmip-datasets`) - duplicate_existing: The Coupled Model Intercomparison Project (CMIP) is a long-standing project with specific versions (CMIP5, CMIP6) already represented in the vault; this is a duplicate of existing institutional knowledge.

## Links

- [Abstract](https://arxiv.org/abs/2610.23216)
- [PDF](https://arxiv.org/pdf/2610.23216)

