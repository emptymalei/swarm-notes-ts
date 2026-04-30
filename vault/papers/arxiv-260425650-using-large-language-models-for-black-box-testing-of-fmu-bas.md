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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "llm-assisted-fmu-testing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:15:34Z"
created_at: "2026-04-30T05:15:34Z"
---

# Using Large Language Models for Black-Box Testing of FMU-Based Simulations

**Authors**: Abdullah Mughees, Gaadha Sudheerbabu, Tanwir Ahmad, Dragos Truscan, Mikael Manngård, Kristian Klemets
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25650](https://arxiv.org/abs/2604.25650)

## Summary

This paper introduces a framework that utilizes Large Language Models to automate the black-box testing of Functional Mock-up Units (FMUs) in dynamic simulations. By ingesting interface specifications, the LLM generates structured Given-When-Then scenario goals and corresponding assertion oracles. The system executes these scenarios against the FMU, validates outputs, and produces comprehensive logs and visual statistics to improve test interpretability. The approach is validated on a Lube Oil Cooling system, demonstrating its potential to reduce manual test design efforts for dynamic models.

## Key Contributions

- Develops a human-in-the-loop framework for generating test scenarios for Functional Mock-up Units (FMUs) using Large Language Models.
- Automates the generation of Given-When-Then structured scenario goals and assertion oracles from functional interface specifications.
- Demonstrates the practicality of the approach through testing a Lube Oil Cooling system, providing human-readable logs and performance metrics for verification.

## Open Questions & Future Work

- [[adaptive-oracle-calibration-dynamic-simulation]]

## Key Concepts

- [[llm-assisted-fmu-testing]]: A framework that uses LLMs to translate interface specifications of functional mock-up units into structured test scenarios and assertion oracles.

## Archivist Review

I have approved the concept for LLM-assisted FMU testing as it represents a novel and reusable framework for simulation-based verification. I also approved the open question regarding adaptive oracle calibration, as it identifies a substantive research bottleneck in automated software testing for dynamic systems. Other candidates were rejected based on the requirement that only standalone, reusable contributions be admitted to the vault.

### Approved Concepts
- LLM-assisted FMU testing: Introduces a paradigm for automating the generation of test scenarios and oracles for black-box dynamic system simulations, which is a significant challenge in cyber-physical verification.

### Approved Open Questions
- Adaptive Oracle Calibration: This is a fundamental bottleneck in automated black-box testing; without reliable automated calibration, the approach remains dependent on intensive expert tuning, limiting scalability and trustworthiness.

### Rejected Candidates
- [dataset] Lube Oil Cooling system (`lube-oil-cooling-system`) - paper_local: This is a single case study application rather than a reusable benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.25650)
- [PDF](https://arxiv.org/pdf/2604.25650)

