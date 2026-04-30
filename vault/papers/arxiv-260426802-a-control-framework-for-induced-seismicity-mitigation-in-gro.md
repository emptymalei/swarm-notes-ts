---
# CSL-compatible fields
title: "A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir"
author:
  - literal: "Diego Gutiérrez-Oribio"
  - literal: "Ioannis Stefanou"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26802"

# Custom fields
paper_id: "2604.26802"
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
processed_at: "2026-04-30T05:12:49Z"
created_at: "2026-04-30T05:12:49Z"
---

# A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir

**Authors**: Diego Gutiérrez-Oribio, Ioannis Stefanou
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26802](https://arxiv.org/abs/2604.26802)

## Summary

This paper addresses the inverse problem of managing gas field operations to mitigate induced seismicity without sacrificing production goals. The authors develop a framework that couples pore-pressure diffusion models with seismicity rate dynamics and a stochastic event-generation procedure to create synthetic earthquake catalogs. A robust feedback controller then uses these estimates to compute optimal, constrained well-rate commands, effectively regulating seismic activity while maintaining production targets. The framework is validated against data from the Groningen gas reservoir and demonstrates efficacy across various operational scenarios.

## Key Contributions

- Introduces a control-oriented methodology for gas production management that minimizes induced seismicity while meeting production quotas.
- Integrates a cascade model of pore-pressure diffusion with seismicity rate (SR) dynamics and a stochastic event-generation procedure for earthquake catalogs.
- Designs a robust feedback controller capable of regulating seismic rates via well-rate commands while accounting for actuator saturation (flux limits) and discrete-time updates.

## Open Questions & Future Work

- [[seismicity-rate-estimation-challenges-from-discrete-data]]

## Archivist Review

The paper provides a domain-specific engineering framework for seismic control rather than a general-purpose machine learning or time-series forecasting advancement. I have approved the open question regarding the estimation of latent seismicity rates, as this represents a fundamental bottleneck in the application of state-space or control-based approaches to stochastic point processes in temporal domains.

### Approved Open Questions
- Unobservable Seismicity Rate Estimation: Effective closed-loop control of seismic risks requires a reliable, real-time estimate of the state variable (seismicity rate). Without an accurate estimation method, feedback controllers cannot be effectively tuned or deployed in industrial settings.

### Rejected Candidates
- [concept] Control-Oriented Seismicity Mitigation Framework (`control-oriented-seismicity-mitigation-framework`) - not_reusable: This is a specific application of control theory rather than a general-purpose, reusable forecasting or ML concept.
- [concept] Pore-Pressure Seismicity Cascade Model (`pore-pressure-seismicity-cascade-model`) - not_reusable: This is a domain-specific physical model rather than a general-purpose ML concept or forecasting mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.26802)
- [PDF](https://arxiv.org/pdf/2604.26802)

