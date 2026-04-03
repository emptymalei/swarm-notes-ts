---
# CSL-compatible fields
title: "Correlation analysis of the dispersion of SARS-CoV-2 in Mexico"
author:
  - literal: "Pablo Carlos López"
  - literal: "Marcos Flores"
  - literal: "Soham Biswas"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.01735"

# Custom fields
paper_id: "2604.01735"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "causal-insight"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:20:00Z"
created_at: "2026-04-03T05:20:00Z"
---

# Correlation analysis of the dispersion of SARS-CoV-2 in Mexico

**Authors**: Pablo Carlos López, Marcos Flores, Soham Biswas
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.01735](https://arxiv.org/abs/2604.01735)

## Summary

This paper introduces a post-pandemic analytical framework designed to evaluate the correlation of COVID-19 dispersion across different geographical regions in Mexico. The methodology specifically addresses the challenges of non-stationary time series, which are inherently characteristic of pandemic-related data. By focusing on societal interventions like mobility restrictions and vaccination campaigns, the approach offers a new lens for understanding the dynamics of epidemic spread and informing future public health strategy.

## Key Contributions

- Proposes a post-pandemic analytical framework to assess the impact of societal interventions on regional pandemic spread.
- Develops a methodology for analyzing correlations specifically tailored for non-stationary epidemiological time series.
- Provides insights into how mobility patterns and public health policies (lockdowns, vaccinations) manifest in long-term collective regional behaviors.

## Open Questions & Future Work

- [[generalization-of-spatial-correlation-epidemiology]]

## Archivist Review

The paper presents a domain-specific retrospective analysis of pandemic data. While the methodological approach for non-stationary time series correlations in a socio-epidemiological context is useful for public health researchers, it does not introduce a novel, broadly reusable temporal forecasting mechanism that meets the vault's high bar for core ML concepts. The open question was rejected because it frames a broad research program rather than a specific, well-defined technical bottleneck for time-series modeling.

### Approved Open Questions
- Generalizing spatial correlation analysis: Establishing a transferable framework allows for comparative epidemiological studies across different countries and diseases, which is currently limited by the reliance on compartmental models that prioritize biological parameters over collective regional behaviors.

### Rejected Candidates
- [open_question] Generalizing spatial correlation analysis (`generalization-of-spatial-correlation-epidemiology`) - low_impact: The proposed framework is a useful research direction but currently leans heavily on domain-specific public health goals rather than a fundamental temporal modeling limitation.

## Links

- [Abstract](https://arxiv.org/abs/2604.01735)
- [PDF](https://arxiv.org/pdf/2604.01735)

