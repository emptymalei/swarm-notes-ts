---
# CSL-compatible fields
title: "Does Explanation Correctness Matter? Linking Computational XAI Evaluation to Human Understanding"
author:
  - literal: "Gregor Baer"
  - literal: "chao zhang"
  - literal: "Isel Grau"
  - literal: "Pieter Van Gorp"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25251"

# Custom fields
paper_id: "2603.25251"
paper_source: "openalex"
domain: "nlp"
tags:
  - "explainable-ai"
  - "human-subject-study"
  - "evaluation-metrics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "forward-simulation-xai-understanding"
  - "explanation-correctness-understanding-threshold"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:18:35Z"
created_at: "2026-03-29T20:18:35Z"
---

# Does Explanation Correctness Matter? Linking Computational XAI Evaluation to Human Understanding

**Authors**: Gregor Baer, chao zhang, Isel Grau, Pieter Van Gorp
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25251](https://arxiv.org/abs/2603.25251)

## Summary

This paper investigates the empirical link between computationally measured explanation correctness and actual human understanding in Explainable AI (XAI). The authors conducted a controlled user study ($N=200$) involving a time series classification task where participants predicted model outputs via forward simulation based on explanations with manipulated correctness levels (100%, 85%, 70%, 55%). Results indicate a non-linear relationship: performance dropped significantly when correctness fell below 70%, but further drops below this point caused no additional loss. Furthermore, achieving 100% correctness did not guarantee high understanding, underscoring that functional metrics must be validated against measurable human outcomes.

## Key Contributions

- Demonstrated experimentally that changes in computational explanation correctness do not linearly translate to changes in human understanding across all levels of correctness.
- Identified a critical correctness threshold (around 70%) below which further drops in computational fidelity yield no additional degradation in human performance for forward simulation tasks.
- Showed that high explanation correctness (100%) does not guarantee high human understanding, indicating model transparency is necessary but not sufficient for user insight.
- Established that lower explanation correctness disproportionately reduces the number of participants who successfully learn the underlying decision pattern of the AI model.

## Limitations

The study was conducted using only a time series classification task, and the specific correctness thresholds (70%, 55%) may vary across different domains or model types.

## Open Questions & Future Work

- [[correctness-human-understanding-granularity]]
- [[conditions-for-informative-self-reports]]
- [[generalizability-of-correctness-threshold]]
- [[localization-vs-perturbation-correctness-equivalence]]

## Key Concepts

- [[forward-simulation-xai-understanding]]: A user study paradigm where participants predict an AI's output based solely on its provided explanation, simulating the model's reasoning process.
- [[explanation-correctness-understanding-threshold]]: The empirical finding that human understanding, measured by performance, degrades significantly when explanation correctness drops below a specific threshold (e.g., 70%) but shows no further drop beyond that point.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 4 open question(s), and 0 dataset(s), with 0 rejected candidate note(s).

### Approved Concepts
- Forward Simulation in XAI Understanding: This describes the specific task used to measure human understanding by forcing participants to simulate the model's decision process based only on the explanation.
- Explanation Correctness Threshold for Understanding: This quantifies a specific, non-linear relationship between a computational metric (correctness) and human performance, identifying a critical threshold (70%).

### Approved Open Questions
- Fine-grained correctness-understanding link: Understanding the precise threshold where small functional correctness gains stop yielding human performance improvements is crucial for efficiently prioritizing XAI metric development.
- Systematic investigation of self-report informativeness: Establishing when subjective user feedback is a reliable proxy for objective understanding is vital for designing efficient human-centered evaluations, as current methods risk over-relying on uninformative subjective data.
- Generalizing functional property effects: Generalizability across different XAI evaluation metrics (like robustness or sparsity) and explanation formats is essential to validate if the threshold effect found for correctness is a universal principle in XAI human evaluation or specific to the tested metric/format.
- Correctness metric equivalence test: Resolving this impacts whether findings from human studies based on localization metrics can inform the validity of established, widely used perturbation-based functional metrics.

## Links

- [Abstract](https://arxiv.org/abs/2603.25251)
- [PDF](https://arxiv.org/pdf/2603.25251)

