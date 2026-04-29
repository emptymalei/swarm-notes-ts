---
# CSL-compatible fields
title: "Universal Features in Atmospheric Particulate Matter Dynamics"
author:
  - literal: "Suchismita Banerjee"
  - literal: "Koyena Ghosh"
  - literal: "Urna Basu"
  - literal: "Banasri Basu"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25386"

# Custom fields
paper_id: "2604.25386"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "statistical-modeling"
  - "stochastic-processes"
architectures:
  []
datasets:
  []
concept_slugs:
  - "emg-residual-distribution"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:21Z"
created_at: "2026-04-29T05:11:21Z"
---

# Universal Features in Atmospheric Particulate Matter Dynamics

**Authors**: Suchismita Banerjee, Koyena Ghosh, Urna Basu, Banasri Basu
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25386](https://arxiv.org/abs/2604.25386)

## Summary

This paper investigates the statistical and dynamical properties of daily PM2.5 concentration fluctuations across 54 Indian cities over a six-year period. By de-trending and seasonalizing the data, the authors identify universal features in both the probability distribution and the spectral behavior of the residual time-series. Specifically, the fluctuations follow an exponentially modified Gaussian distribution and exhibit robust 1/f noise characteristics. A minimal stochastic model is introduced to explain these findings, providing a parsimonious framework for atmospheric particulate matter dynamics.

## Key Contributions

- Demonstrates that after seasonal de-trending, residual PM2.5 fluctuations across 54 Indian cities exhibit universal statistical properties.
- Shows that normalized residual fluctuations follow an exponentially modified Gaussian (EMG) distribution.
- Proposes a minimal stochastic model that reproduces observed universal features including stationary distributions, autocorrelation, and 1/f spectral scaling.

## Key Concepts

- [[emg-residual-distribution]]: The use of an exponentially modified Gaussian distribution to model the residual fluctuations of non-stationary physical processes after detrending.

## Archivist Review

I have approved the EMG-based residual distribution concept after generalizing its slug and title to reflect its broader potential as a statistical prior for physical time-series forecasting. The original candidate was rejected to prevent domain-specific clutter, as the underlying mechanism (modeling residuals of non-stationary physical processes via EMG) is the true contribution. No datasets or open questions met the high bar for permanent archival in this specific analysis.

### Approved Concepts
- Exponentally Modified Gaussian (EMG) Distribution for Residual Dynamics: Identifies a universal statistical characteristic for environmental time-series residuals that simplifies modeling across heterogeneous domains.

### Rejected Candidates
- [concept] Exponentally Modified Gaussian (EMG) Distribution for PM2.5 (`emg-pm25-distribution`) - other: The slug and title were overly domain-specific to PM2.5, whereas the mechanism is potentially applicable to a broader class of physical time-series residuals.

## Links

- [Abstract](https://arxiv.org/abs/2604.25386)
- [PDF](https://arxiv.org/pdf/2604.25386)

