---
# CSL-compatible fields
title: "Data-driven oscillator model for multi-frequency turbulent flows"
author:
  - literal: "Youngjae Kim"
  - literal: "Koichiro Yawata"
  - literal: "Hiroya Nakao"
  - literal: "Kunihiko Taira"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11745"

# Custom fields
paper_id: "2604.11745"
paper_source: "arxiv"
domain: "fluid-dynamics-ml"
tags:
  - "reduced-order-modeling"
  - "fluid-dynamics"
  - "oscillator-dynamics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "data-driven-oscillator-modeling"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-15T05:06:35Z"
created_at: "2026-04-15T05:06:35Z"
---

# Data-driven oscillator model for multi-frequency turbulent flows

**Authors**: Youngjae Kim, Koichiro Yawata, Hiroya Nakao, Kunihiko Taira
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11745](https://arxiv.org/abs/2604.11745)

## Summary

This paper addresses the difficulty of applying phase-reduction analysis to complex, multi-frequency turbulent flows. The authors propose a data-driven framework that extracts representative oscillators from flow data using specialized autoencoders and models their subsequent evolution with neural networks. Validated on supersonic cavity flows, the approach successfully captures large-scale flow features and provides accurate long-term forecasts of multi-frequency oscillatory dynamics.

## Key Contributions

- Introduced a data-driven framework that extends phase-reduction analysis to multi-frequency turbulent flows by modeling them as a system of oscillators.
- Utilized custom autoencoders to extract physically meaningful representative oscillators directly from high-dimensional flow field data.
- Demonstrated that the model accurately captures long-term oscillatory behavior in three-dimensional supersonic turbulent cavity flows.

## Open Questions & Future Work

- [[phase-reduction-for-multi-frequency-turbulence]]

## Key Concepts

- [[data-driven-oscillator-modeling]]: A framework that extracts representative oscillators from complex flow field data using autoencoders and models their temporal dynamics with neural networks.

## Archivist Review

I have approved the concept of 'Data-driven oscillator modeling' as it represents a robust architectural approach for spatio-temporal dimensionality reduction in dynamical systems, distinct from existing graph or flow-based methods in the vault. The open question regarding 'Phase reduction for multi-frequency turbulence' is approved as it addresses a fundamental mathematical challenge in non-periodic fluid dynamics that persists across current reduced-order modeling paradigms. Both entries are carefully scoped to reflect their specific domain utility while maintaining generalizability for future research.

### Approved Concepts
- Data-driven oscillator modeling: Provides a structured way to reduce high-dimensional turbulent flow dynamics into a manageable set of oscillators for multi-frequency scenarios, bridging phase-reduction analysis with data-driven neural modeling.

### Approved Open Questions
- Phase reduction for multi-frequency turbulence: This is a central bottleneck for using reduced-order oscillator models in complex turbulent engineering applications. Addressing it is necessary to move beyond current limitations that restrict phase-based control and analysis to simplified, quasi-periodic flows.

## Links

- [Abstract](https://arxiv.org/abs/2604.11745)
- [PDF](https://arxiv.org/pdf/2604.11745)

