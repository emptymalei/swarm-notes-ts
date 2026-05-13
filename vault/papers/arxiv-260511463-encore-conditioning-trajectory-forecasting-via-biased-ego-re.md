---
# CSL-compatible fields
title: "Encore: Conditioning Trajectory Forecasting via Biased Ego Rehearsals"
author:
  - literal: "Conghao Wong"
  - literal: "Ziqian Zou"
  - literal: "Xinge You"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11463"

# Custom fields
paper_id: "2605.11463"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "trajectory-prediction"
  - "agent-interaction"
  - "interpretability"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "biased-ego-rehearsals"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:25:30Z"
created_at: "2026-05-13T05:25:30Z"
---

# Encore: Conditioning Trajectory Forecasting via Biased Ego Rehearsals

**Authors**: Conghao Wong, Ziqian Zou, Xinge You
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11463](https://arxiv.org/abs/2605.11463)

## Summary

This paper introduces Encore, a novel trajectory forecasting framework designed to explicitly account for individual agent subjectivities. The method operates in two phases: a rehearsal phase where an ego-predictor derives biased trajectories for all scene participants, and an encore phase where these trajectories condition the final motion predictions. By formalizing subjectivities as biased ego rehearsals, the model achieves superior predictive accuracy while providing interpretability into how ego-specific biases influence interaction dynamics.

## Key Contributions

- Introduces 'Encore', a trajectory prediction model that explicitly models agent subjectivities through biased rehearsals.
- Proposes a two-phase architecture: an ego-centric predictor to derive biased rehearsal trajectories followed by a conditioning network for final predictions.
- Demonstrates consistent performance improvements across standard trajectory forecasting datasets with improved interpretability of agent subjectivities.

## Open Questions & Future Work

- [[modeling-agent-subjectivity-modulation]]

## Key Concepts

- [[biased-ego-rehearsals]]: A trajectory conditioning technique that uses explicitly biased ego-centric rehearsal paths to modulate future participant motions.

## Archivist Review

I approved the core concept of Biased Ego Rehearsals because it represents a distinct and potentially reusable trajectory conditioning mechanism, rather than just a specific model architecture. I also approved the open question regarding agent subjectivity modulation, as it encapsulates a significant, well-defined limitation in current trajectory forecasting research. No datasets were approved as none were presented that were not already standard or better captured by existing benchmark notes.

### Approved Concepts
- Biased Ego Rehearsals: Provides a novel, interpretable mechanism for modulating trajectory predictions based on individual agent subjectivities.

### Approved Open Questions
- Modeling Agent Subjectivity Modulation: Addressing this is fundamental to improving the realism and interpretability of multi-agent trajectory prediction, particularly in complex social scenarios where individual behavior deviates from generic crowd dynamics.

## Links

- [Abstract](https://arxiv.org/abs/2605.11463)
- [PDF](https://arxiv.org/pdf/2605.11463)

