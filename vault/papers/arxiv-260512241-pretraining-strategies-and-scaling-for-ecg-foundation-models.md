---
# CSL-compatible fields
title: "Pretraining Strategies and Scaling for ECG Foundation Models: A Systematic Study"
author:
  - literal: "M A Al-Masud"
  - literal: "Nils Strodthoff"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12241"

# Custom fields
paper_id: "2605.12241"
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
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:23:22Z"
created_at: "2026-05-13T05:23:22Z"
---

# Pretraining Strategies and Scaling for ECG Foundation Models: A Systematic Study

**Authors**: M A Al-Masud, Nils Strodthoff
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12241](https://arxiv.org/abs/2605.12241)

## Summary

This study systematically evaluates pretraining methodologies and scaling laws for ECG foundation models using up to 11M publicly available physiological time-series samples. The authors compare five contrastive and non-contrastive self-supervised learning objectives, identifying contrastive predictive coding as the most robust for downstream task transfer. Furthermore, the paper provides evidence that structured state space models consistently outperform traditional transformer and CNN architectures, suggesting that strong inductive biases are critical for effective physiological signal modeling.

## Key Contributions

- Presents a systematic comparison of five self-supervised learning objectives for ECG foundation models, finding contrastive predictive coding to be the most effective.
- Demonstrates that scaling pretraining data up to 11M samples continues to provide performance gains across evaluated objectives.
- Establishes the empirical superiority of structured state space models over transformers and CNNs for ECG representation learning.

## Open Questions & Future Work

- [[ecg-fm-scaling-limits]]

## Archivist Review

This study provides a systematic evaluation of scaling laws for ECG foundation models, but does not introduce a novel, reusable architecture or technique that warrants a standalone conceptual entry. The open question was approved after being broadened to cover physiological foundation models, ensuring it remains relevant across future literature in time-series and medical signal processing. No datasets were approved as they were described only as an aggregate collection of public sources.

### Approved Open Questions
- Scaling Limits of Physiological FMs: Establishing whether performance gains continue beyond current scales is fundamental to defining universal scaling laws for physiological time series foundation models.

### Rejected Candidates
- [open_question] Scaling Limits of ECG FMs (`ecg-fm-scaling-limits`) - other: Renamed to be more general to physiological foundation models as requested by the review policy.

## Links

- [Abstract](https://arxiv.org/abs/2605.12241)
- [PDF](https://arxiv.org/pdf/2605.12241)

