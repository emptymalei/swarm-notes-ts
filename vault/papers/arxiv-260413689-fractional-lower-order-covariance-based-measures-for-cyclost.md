---
# CSL-compatible fields
title: "Fractional lower-order covariance-based measures for cyclostationary time series with heavy-tailed distributions: application to dependence testing and model order identification"
author:
  - literal: "Wojciech Żuławiński"
  - literal: "Agnieszka Wyłomańska"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13689"

# Custom fields
paper_id: "2604.13689"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "statistical-learning"
  - "cyclostationary-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "fractional-lower-order-covariance-floc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:06:31Z"
created_at: "2026-04-16T05:06:31Z"
---

# Fractional lower-order covariance-based measures for cyclostationary time series with heavy-tailed distributions: application to dependence testing and model order identification

**Authors**: Wojciech Żuławiński, Agnieszka Wyłomańska
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13689](https://arxiv.org/abs/2604.13689)

## Summary

This paper addresses the limitations of traditional covariance-based cyclostationary analysis when applied to heavy-tailed, infinite-variance time series. The authors propose a framework using the fractional lower-order covariance (FLOC) to derive new measures, namely the periodic fractional lower-order autocorrelation function (peFLOACF) and its partial counterpart (peFLOPACF). These tools facilitate robust dependence testing and model order identification for Periodic Autoregressive (PAR) and Periodic Moving Average (PMA) models. The methodology is validated through simulations and applied to real-world air pollution data, demonstrating its effectiveness in challenging statistical settings.

## Key Contributions

- Introduces periodic fractional lower-order autocorrelation and partial autocorrelation functions (peFLOACF and peFLOPACF) for heavy-tailed, infinite-variance cyclostationary processes.
- Develops a portmanteau test for dependence testing specifically designed for infinite-variance cyclostationary series.
- Proposes a robust method for order identification in Periodic Autoregressive (PAR) and Periodic Moving Average (PMA) models under non-Gaussian conditions.

## Open Questions & Future Work

- [[asymptotic-theory-floc-estimators]]

## Key Concepts

- [[fractional-lower-order-covariance-floc]]: A robust statistical alternative to traditional autocovariance for analyzing cyclostationary processes characterized by heavy-tailed, infinite-variance distributions.

## Archivist Review

I have approved the Fractional Lower-Order Covariance concept as it provides a critical, reusable mathematical tool for heavy-tailed time series analysis. The open question regarding asymptotic properties is approved as it addresses a fundamental theoretical bottleneck for moving beyond simulation-based validation of these estimators. No datasets were approved as none were presented as novel, reusable, or primary contributors.

### Approved Concepts
- Fractional Lower-Order Covariance (FLOC): It provides a robust mathematical foundation for analyzing cyclostationary time series where traditional second-order statistics (autocovariance) fail due to infinite variance and heavy tails.

### Approved Open Questions
- Asymptotic properties of FLOC estimators: Establishing the theoretical convergence of these estimators is crucial for developing reliable, non-heuristic tests in heavy-tailed cyclostationary modeling.

## Links

- [Abstract](https://arxiv.org/abs/2604.13689)
- [PDF](https://arxiv.org/pdf/2604.13689)

