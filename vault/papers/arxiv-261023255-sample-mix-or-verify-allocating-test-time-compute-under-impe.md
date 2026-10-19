---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Sample, Mix, or Verify? Allocating Test-Time Compute under Imperfect Verifiers"
description: "The paper addresses the challenge of allocating a fixed inference-time compute budget (sampling vs. verification) in LLM-based systems when verifiers are imperfect and prone to correlated errors. It proposes SPLIT, a framework that uses an exact success probability formula and empirical Bayes on pilot data to determine the optimal number of samples and verification strategy for unseen tasks. Across diverse benchmarks including math and software engineering, SPLIT achieves near-optimal budget allocation, significantly outperforming standard heuristic rules and providing insights into the precision-diminishing effects of correlated LLM judges."
resource: "https://arxiv.org/abs/2610.23255"
tags:
  - "large-language-models"
  - "llm-agents"
  - "inference-optimization"
  - "evaluation-benchmarks"
  - "software-engineering"
  - "inference-time-adaptation"
  - "empirical-study"
  - "decision-making"
timestamp: "2026-10-19T04:30:38Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Srinivasan Iyengar"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23255"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "split-framework"
    description: "A framework for optimizing inference-time compute allocation by modeling the joint probability of candidate correctness and imperfect verifier performance using empirical Bayes on pilot data."
datasets:
  []
open_questions:
  - name: "candidate-dependence-modeling"
    description: "Language models frequently generate near-duplicate or semantically redundant solutions, a form of intra-task candidate dependence. Failure to model these correlations can lead to biased forecasts of verified success, particularly at high sample counts where the actual diversity of the candidate pool is lower than independent models assume."
  - name: "optimal-sequential-test-time-allocation"
    description: "Existing online allocation policies for inference compute typically rely on greedy heuristics that ignore the cumulative risk of false positives from imperfect verifiers. Developing non-greedy policies that account for the expected value of information and the probability of verifier error remains an unresolved problem in test-time compute scaling."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T04:30:38Z"
created_at: "2026-10-19T04:30:38Z"
---

# Sample, Mix, or Verify? Allocating Test-Time Compute under Imperfect Verifiers

**Authors**: Srinivasan Iyengar
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23255](https://arxiv.org/abs/2610.23255)

## Summary

The paper addresses the challenge of allocating a fixed inference-time compute budget (sampling vs. verification) in LLM-based systems when verifiers are imperfect and prone to correlated errors. It proposes SPLIT, a framework that uses an exact success probability formula and empirical Bayes on pilot data to determine the optimal number of samples and verification strategy for unseen tasks. Across diverse benchmarks including math and software engineering, SPLIT achieves near-optimal budget allocation, significantly outperforming standard heuristic rules and providing insights into the precision-diminishing effects of correlated LLM judges.

## Key Contributions

- Derivation of an exact success probability formula for inference-time scaling that accounts for imperfect verifiers, varying task difficulty, and correlated mistakes.
- Introduction of the SPLIT framework, which utilizes empirical Bayes on a small pilot dataset to predict optimal compute allocation for unseen tasks.
- Comprehensive empirical evaluation across 7 benchmarks and 175 agent systems, demonstrating near-optimal (within 0.8% of hindsight best) allocation performance.
- Analytical explanation of counter-intuitive behaviors in multi-judge systems, such as when increasing the number of LLM judges leads to a decrease in precision.

## Limitations

The abstract notes that SPLIT loses performance in specific scenarios where it acts as a forecaster far beyond the pilot data, particularly compared to power-law fitting when verifiers cap success.

## Open Questions & Future Work

- [[candidate-dependence-modeling]]
- [[optimal-sequential-test-time-allocation]]

## Key Concepts

- [[split-framework]]: A framework for optimizing inference-time compute allocation by modeling the joint probability of candidate correctness and imperfect verifier performance using empirical Bayes on pilot data.

## Archivist Review

Approved the SPLIT framework as a timely contribution to the growing field of inference-time scaling (System 2 thinking), specifically addressing the role of fallible verifiers. Approved open questions regarding candidate dependence and sequential allocation as they target specific statistical and decision-theoretic gaps in current scaling theories. Rejected the agent rollout scaling question as it is essentially a request for more data/compute to confirm known patterns.

### Approved Concepts
- SPLIT Framework: Provides a principled method for 'inference-time scaling' that explicitly models verifier fallibility, a critical factor often overlooked in simpler scaling law formulations.

### Approved Open Questions
- Modeling Intra-Task Candidate Redundancy: Improving the accuracy of scaling laws for inference-time compute requires accounting for the diminishing returns caused by model output collapse or lack of sample diversity.
- Optimal Sequential Test-Time Allocation: Optimal sequential policies could maximize the reliability of language model-based systems by strategically balancing the costs of additional sampling against the risks of verifier-induced failure.

### Rejected Candidates
- [open_question] Long-horizon scaling of agent rollouts (`agent-rollout-long-horizon-scaling`) - not_novel: This candidate primarily calls for large-scale empirical validation of existing saturation hypotheses rather than identifying a novel conceptual or technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.23255)
- [PDF](https://arxiv.org/pdf/2610.23255)

