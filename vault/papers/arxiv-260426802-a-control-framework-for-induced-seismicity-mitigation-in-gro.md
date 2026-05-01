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
  - "control-oriented-induced-seismicity-mitigation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:24:33Z"
created_at: "2026-05-01T05:24:33Z"
---

# A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir

**Authors**: Diego Gutiérrez-Oribio, Ioannis Stefanou
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26802](https://arxiv.org/abs/2604.26802)

## Summary

This paper presents a control-theoretic framework for managing gas extraction in the Groningen reservoir to minimize induced seismicity while meeting production targets. The methodology employs a cascaded physical model linking pore-pressure diffusion to seismicity rate dynamics, augmented by a stochastic process for synthetic earthquake event generation. A robust feedback controller is then implemented to dynamically adjust production rates, accounting for operational constraints and actuator saturation. Experiments validate the effectiveness of this approach in regulating seismic activity under various operational and injection-reinjection scenarios.

## Key Contributions

- Proposed a control-oriented methodology for managing gas reservoir production under induced-seismicity constraints using a cascaded pore-pressure and seismicity rate model.
- Developed a stochastic event-generation procedure that maps continuous seismicity rate dynamics into discrete earthquake catalogs for robust controller feedback.
- Demonstrated that the proposed robust feedback controller successfully balances production maximization with seismicity reduction while respecting actuator saturation limits.

## Open Questions & Future Work

- [[estimation-of-unobservable-seismicity-rate]]

## Key Concepts

- [[control-oriented-induced-seismicity-mitigation]]: A control-theoretic approach to optimizing gas extraction rates while regulating seismic dynamics under induced seismicity constraints.

## Archivist Review

The paper proposes a novel framework for controlling industrial fluid extraction to mitigate seismicity. The concepts and open questions were selected based on their relevance to feedback control in complex physical time-series systems where the control variable is a latent construct derived from discrete event data. Other candidates were rejected as being overly tied to the specific Groningen reservoir implementation or generic research steps.

### Approved Concepts
- Control-oriented induced seismicity mitigation: Provides a foundational methodology for bridging physical reservoir modeling with industrial production control to mitigate environmental hazards.

### Approved Open Questions
- Estimating Unobservable Seismicity Rate: This represents a fundamental bottleneck for implementing feedback control systems in seismic mitigation, as the control law requires accurate feedback of the system's latent state.

## Links

- [Abstract](https://arxiv.org/abs/2604.26802)
- [PDF](https://arxiv.org/pdf/2604.26802)

