---
# CSL-compatible fields
title: "Using Large Language Models for Black-Box Testing of FMU-Based Simulations"
author:
  - literal: "Abdullah Mughees"
  - literal: "Gaadha Sudheerbabu"
  - literal: "Tanwir Ahmad"
  - literal: "Dragos Truscan"
  - literal: "Mikael Manngård"
  - literal: "Kristian Klemets"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25650"

# Custom fields
paper_id: "2604.25650"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:00Z"
created_at: "2026-04-29T05:11:00Z"
---

# Using Large Language Models for Black-Box Testing of FMU-Based Simulations

**Authors**: Abdullah Mughees, Gaadha Sudheerbabu, Tanwir Ahmad, Dragos Truscan, Mikael Manngård, Kristian Klemets
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25650](https://arxiv.org/abs/2604.25650)

## Summary

This paper introduces a human-in-the-loop framework for black-box testing of FMU-based simulation models by leveraging Large Language Models (LLMs). The system generates structured test scenarios—expressed as Given-When-Then goals—from FMU interface specifications, subsequently translating them into executable input time-series and assertion oracles. By automating scenario design and providing interpretable diagnostic reports, the approach streamlines the verification process for dynamic simulations. The effectiveness of this methodology is empirically validated using a Lube Oil Cooling system case study.

## Key Contributions

- Proposes an LLM-based black-box testing framework for Functional Mock-up Units (FMUs) that automates the generation of test scenarios from functional specifications.
- Implements a translation pipeline that converts LLM-generated Given-When-Then scenarios into concrete input time-series and assertion oracles for simulation verification.
- Demonstrates utility on a Lube Oil Cooling system, showing reduced manual effort in defining test scenarios and improved interpretability through automated visualization and logging.

## Open Questions & Future Work

- [[adaptive-oracle-calibration]]

## Archivist Review

The paper proposes a specific application of LLMs for software testing of simulations (FMUs). While the practical framework is well-described, it does not introduce a novel forecasting, representation, or calibration concept that would recur as a standard method in time-series research, so the framework itself was rejected. The open question regarding the adaptive calibration of qualitative oracles in simulation testing is highly relevant to ensuring reliability in automated temporal verification and was approved.

### Approved Open Questions
- Adaptive Calibration of Testing Oracles: Crucial for ensuring the reliability and trustworthiness of automated testing, as improperly configured oracles lead to inaccurate test verdicts.

### Rejected Candidates
- [concept] LLM-based FMU Testing Framework (`llm-based-fmu-testing-framework`) - paper_local: This is a paper-local application of LLMs to a specific testing task rather than a reusable forecasting mechanism or temporal representation.

## Links

- [Abstract](https://arxiv.org/abs/2604.25650)
- [PDF](https://arxiv.org/pdf/2604.25650)

