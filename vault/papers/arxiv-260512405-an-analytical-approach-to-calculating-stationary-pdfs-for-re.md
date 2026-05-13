---
# CSL-compatible fields
title: "An analytical approach to calculating stationary PDFs for reflected random walks with an application to BESS-based ramp-rate control"
author:
  - literal: "Carlos Colchero"
  - literal: "Diego Jiménez-Arreguín"
  - literal: "Álvaro Herrera"
  - literal: "Jorge E. Pérez-García"
  - literal: "Oliver Probst"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12405"

# Custom fields
paper_id: "2605.12405"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "wiener-hopf-reflected-random-walk"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:22:51Z"
created_at: "2026-05-13T05:22:51Z"
---

# An analytical approach to calculating stationary PDFs for reflected random walks with an application to BESS-based ramp-rate control

**Authors**: Carlos Colchero, Diego Jiménez-Arreguín, Álvaro Herrera, Jorge E. Pérez-García, Oliver Probst
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12405](https://arxiv.org/abs/2605.12405)

## Summary

This paper introduces a rigorous analytical framework for deriving the stationary probability density function (PDF) of reflected random walks, utilizing a Wiener-Hopf-type integral equation. The methodology is applied to the sizing of power inverters for battery energy storage systems (BESS) managing the ramp-rate of variable renewable energy sources. By solving the derived Fredholm integral equation via a Neumann series, the authors provide closed-form insights that simplify design criteria for power systems practitioners, validated against numerical Nystrom methods and simulation data.

## Key Contributions

- Derives a rigorous Wiener-Hopf-type integral equation for the stationary PDF of a reflected random walk.
- Develops an analytical solution method for the BESS power PDF using a Neumann series expansion.
- Provides simplified design rules for inverter sizing in BESS-based ramp-rate control, verified against Nystrom-based numerical solutions and algorithmic simulations.

## Open Questions & Future Work

- [[finite-response-time-bess]]
- [[autocorrelation-heteroskedasticity-vrs]]

## Key Concepts

- [[wiener-hopf-reflected-random-walk]]: A rigorous mathematical framework for calculating stationary probability density functions of reflected random walks using Wiener-Hopf-type integral equations.

## Archivist Review

The paper provides a rigorous analytical approach for modeling constrained random processes in energy systems. I approved the Wiener-Hopf integral equation concept for its mathematical depth and reusability in physical time-series modeling, as well as two open questions addressing the gaps in the IID assumption and instantaneous response limits, which are common bottlenecks in real-world forecasting applications.

### Approved Concepts
- Wiener-Hopf-type integral equation for reflected random walk: Provides a formal analytical framework for determining stationary probability distributions in constrained stochastic systems, crucial for time-series forecasting in systems with physical boundaries.

### Approved Open Questions
- BESS Finite Response Time: Real-world BESS systems have non-zero ramp rates and communication/processing delays that could significantly impact the effectiveness of the control strategy and the validity of the stationary PDF derived under the assumption of instantaneous response.
- Autocorrelation and Heteroskedasticity Impacts: Ignoring temporal dependencies may lead to underestimation of BESS requirements, requiring a more robust framework for power system control.

## Links

- [Abstract](https://arxiv.org/abs/2605.12405)
- [PDF](https://arxiv.org/pdf/2605.12405)

