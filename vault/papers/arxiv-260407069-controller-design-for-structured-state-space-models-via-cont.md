---
# CSL-compatible fields
title: "Controller Design for Structured State-space Models via Contraction Theory"
author:
  - literal: "Muhammad Zakwan"
  - literal: "Vaibhav Gupta"
  - literal: "Alireza Karimi"
  - literal: "Efe C. Balta"
  - literal: "Giancarlo Ferrari-Trecate"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07069"

# Custom fields
paper_id: "2604.07069"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "control-theory"
  - "state-space-models"
  - "nonlinear-systems"
  - "stability-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:54:23Z"
created_at: "2026-04-09T04:54:23Z"
---

# Controller Design for Structured State-space Models via Contraction Theory

**Authors**: Muhammad Zakwan, Vaibhav Gupta, Alireza Karimi, Efe C. Balta, Giancarlo Ferrari-Trecate
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07069](https://arxiv.org/abs/2604.07069)

## Summary

This paper introduces an indirect data-driven output feedback control framework for nonlinear systems using structured state-space models (SSMs) as surrogates. The authors address the challenges of control design in these models by establishing fundamental properties of controllability and observability, which facilitate scalable synthesis via linear matrix inequalities. Furthermore, the paper proves a separation principle for SSM-based control, enabling independent observer and controller design with guaranteed exponential stability. This approach provides a computationally efficient alternative to transformer-based control architectures for long-horizon dynamics.

## Key Contributions

- Establishes the first controllability and observability analysis for structured state-space models (SSMs) to enable rigorous control design.
- Develops a scalable output feedback controller synthesis framework using Linear Matrix Inequalities (LMIs) and contraction theory.
- Proves a separation principle for SSMs, allowing for the decoupled design of observers and state-feedback controllers while guaranteeing closed-loop exponential stability.

## Open Questions & Future Work

- [[ssm-internal-model-integration]]

## Archivist Review

The paper provides a theoretical foundation for SSM control, but the proposed concepts (controllability/observability/separation principle for SSMs) are extensions of classical control theory rather than novel ML mechanisms. I approved the open question regarding internal model integration as it identifies a clear, non-trivial gap in applying SSMs to robust control.

### Approved Open Questions
- Integrating Internal Model Principles: The internal model principle is critical for achieving robust tracking and disturbance rejection in practical control applications, representing a natural progression for this data-driven control framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.07069)
- [PDF](https://arxiv.org/pdf/2604.07069)

