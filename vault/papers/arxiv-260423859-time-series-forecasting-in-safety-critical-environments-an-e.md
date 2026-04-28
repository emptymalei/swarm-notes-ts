---
# CSL-compatible fields
title: "Time-Series Forecasting in Safety-Critical Environments: An EU-AI-Act-Compliant Open-Source Package"
author:
  - literal: "Thomas Bartz-Beielstein"
  - literal: "Eva Bartz"
issued:
  date-parts:
    - [2026, 4, 26]
url: "https://arxiv.org/abs/2604.23859"

# Custom fields
paper_id: "2604.23859"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "compliance-by-design-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:16:40Z"
created_at: "2026-04-28T05:16:40Z"
---

# Time-Series Forecasting in Safety-Critical Environments: An EU-AI-Act-Compliant Open-Source Package

**Authors**: Thomas Bartz-Beielstein, Eva Bartz
**Date**: 2026-04-26
**Paper ID**: [arxiv:2604.23859](https://arxiv.org/abs/2604.23859)

## Summary

The paper introduces spotforecast2-safe, an open-source library for safety-critical time-series forecasting that prioritizes regulatory compliance over advanced features like AutoML or LLM integration. By embedding compliance directly into API contracts and CI/CD workflows, it ensures adherence to the EU AI Act and IEC safety standards. The library enforces strict development rules—such as zero dead code and deterministic processing—to minimize attack surfaces and ensure reproducibility in critical environments.

## Key Contributions

- Presents spotforecast2-safe, an open-source Python library for point forecasting that integrates EU AI Act and IEC safety standard requirements directly into its API and CI/CD pipelines.
- Implements a strict 'Compliance-by-Design' development methodology based on non-negotiable rules for determinism, minimal dependencies, and code safety.
- Provides a bidirectional traceability matrix mapping specific regulatory provisions to concrete code-level implementation mechanisms.

## Open Questions & Future Work

- [[formalizing-threat-models-forecasting]]

## Key Concepts

- [[compliance-by-design-forecasting]]: A methodology that integrates regulatory requirements directly into code-level API contracts, persistence, and CI pipelines for safety-critical forecasting.

## Archivist Review

The paper provides a unique perspective on integrating industrial and AI-specific regulatory compliance directly into the software architecture of a forecasting library. I approved the 'Compliance-by-Design' concept as it represents a shift from external compliance scanners to embedded API-contract-level design. The open question regarding threat model formalization was approved because it addresses a specific, critical bottleneck for safety-critical ML systems in industrial environments.

### Approved Concepts
- Compliance-by-Design Forecasting: Provides a rigorous framework for integrating regulatory compliance directly into the software architecture of forecasting tools.

### Approved Open Questions
- Formalizing Threat Models for Forecasting: Formalizing threat models is a prerequisite for advancing from Managed to Defined maturity levels under industrial cybersecurity standards, which is essential for auditability in critical infrastructure.

## Links

- [Abstract](https://arxiv.org/abs/2604.23859)
- [PDF](https://arxiv.org/pdf/2604.23859)

