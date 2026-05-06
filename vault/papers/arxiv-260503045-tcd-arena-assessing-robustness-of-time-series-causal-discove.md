---
# CSL-compatible fields
title: "TCD-Arena: Assessing Robustness of Time Series Causal Discovery Methods Against Assumption Violations"
author:
  - literal: "Gideon Stein"
  - literal: "Niklas Penzel"
  - literal: "Tristan Piater"
  - literal: "Joachim Denzler"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.03045"

# Custom fields
paper_id: "2605.03045"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "tcd-arena"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:13:15Z"
created_at: "2026-05-06T05:13:15Z"
---

# TCD-Arena: Assessing Robustness of Time Series Causal Discovery Methods Against Assumption Violations

**Authors**: Gideon Stein, Niklas Penzel, Tristan Piater, Joachim Denzler
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.03045](https://arxiv.org/abs/2605.03045)

## Summary

TCD-Arena is introduced as a comprehensive, modular, and extendable benchmarking framework designed to evaluate the robustness of time series causal discovery (CD) algorithms against controlled assumption violations. Through an empirical study of 30 million CD attempts across 33 specific violation scenarios, the authors reveal critical performance profiles and limitations of existing methods. Furthermore, the paper highlights that employing ensemble strategies can mitigate robustness issues, offering a pathway toward more reliable causal discovery in complex, real-world data conditions.

## Key Contributions

- Introduces TCD-Arena, a modular and extendable testing framework for evaluating time series causal discovery robustness.
- Provides an extensive empirical analysis comprising 30 million causal discovery attempts across 33 distinct assumption violation scenarios.
- Demonstrates that causal discovery ensembles significantly improve general robustness to assumption violations compared to individual methods.

## Key Concepts

- [[tcd-arena]]: A modularized testing framework for evaluating the robustness of time series causal discovery algorithms against systematic assumption violations.

## Archivist Review

I approved the TCD-Arena framework as a central benchmarking tool for time series causal discovery, as it addresses the need for systematic robustness evaluation against assumption violations. I rejected 'Causal Discovery Ensembles' because ensembles are a ubiquitous ML strategy rather than a distinct, reusable concept unique to this domain. No datasets or open questions were proposed, so the approval list is kept intentionally lean.

### Approved Concepts
- TCD-Arena: It provides a systematic, modular framework for evaluating the robustness of time series causal discovery algorithms under controlled violations of key assumptions.

### Rejected Candidates
- [concept] Causal Discovery Ensembles (`causal-discovery-ensembles`) - not_novel: Ensemble techniques are a general ML strategy and not a novel concept specific enough to warrant a permanent entry in this time-series vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.03045)
- [PDF](https://arxiv.org/pdf/2605.03045)

