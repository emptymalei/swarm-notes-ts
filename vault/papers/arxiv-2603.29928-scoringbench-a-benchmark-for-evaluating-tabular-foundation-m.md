---
# CSL-compatible fields
title: "ScoringBench: A Benchmark for Evaluating Tabular Foundation Models with Proper Scoring Rules"
author:
  - literal: "Jonas Landsgesell"
  - literal: "Pascal Knoll"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29928"

# Custom fields
paper_id: "2603.29928"
paper_source: "arxiv"
domain: "nlp"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:39:43Z"
created_at: "2026-04-02T05:39:43Z"
---

# ScoringBench: A Benchmark for Evaluating Tabular Foundation Models with Proper Scoring Rules

**Authors**: Jonas Landsgesell, Pascal Knoll
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29928](https://arxiv.org/abs/2603.29928)

## Summary

ScoringBench addresses the limitation of current tabular foundation model benchmarks, which rely primarily on point-estimate metrics that fail to characterize full predictive distributions. By incorporating a suite of proper scoring rules—including CRPS, CRLS, and Energy Score—the benchmark provides a more granular assessment of probabilistic forecast quality. The findings demonstrate that model performance rankings are highly sensitive to the chosen scoring rule, highlighting the necessity of aligning evaluation metrics with specific domain-dependent risk requirements.

## Key Contributions

- Introduces ScoringBench, a comprehensive benchmark for evaluating tabular foundation models using a suite of proper scoring rules (CRPS, CRLS, Interval Score, Energy Score, etc.).
- Demonstrates that model rankings shift significantly based on the chosen scoring rule, revealing that point-estimate metrics like RMSE/R2 are insufficient for high-stakes, asymmetric-risk domains.
- Provides empirical evidence that no single pretraining objective is universally optimal, underscoring that evaluation metrics must be tailored to specific domain risk profiles.

## Open Questions & Future Work

- [[ranking-normalization-methodology]]
- [[multivariate-target-evaluation]]

## Archivist Review

The submitted concepts (proper scoring rules) were rejected as they are standard statistical tools rather than novel research concepts. The open questions were approved as they address fundamental methodological challenges in benchmark design and evaluation for tabular foundation models that remain unresolved in the literature. No datasets were approved as none were cited as unique, novel contributions to the field.

### Approved Open Questions
- Robust Ranking Normalization Methods: Determining robust normalization methods is crucial for ensuring that leaderboard rankings accurately reflect model performance differences rather than artifacts of the ranking methodology.
- Multivariate Target Benchmarking: Many real-world tabular prediction tasks involve predicting multiple interrelated variables simultaneously; benchmarking these capabilities is essential for assessing the full utility of foundation models.

## Links

- [Abstract](https://arxiv.org/abs/2603.29928)
- [PDF](https://arxiv.org/pdf/2603.29928)

