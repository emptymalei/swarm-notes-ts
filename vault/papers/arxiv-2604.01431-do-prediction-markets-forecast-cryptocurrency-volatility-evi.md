---
# CSL-compatible fields
title: "Do Prediction Markets Forecast Cryptocurrency Volatility? Evidence from Kalshi Macro Contracts"
author:
  - literal: "Hardhik Mohanty"
  - literal: "Bhaskar Krishnamachari"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01431"

# Custom fields
paper_id: "2604.01431"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-03T05:24:37Z"
created_at: "2026-04-03T05:24:37Z"
---

# Do Prediction Markets Forecast Cryptocurrency Volatility? Evidence from Kalshi Macro Contracts

**Authors**: Hardhik Mohanty, Bhaskar Krishnamachari
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01431](https://arxiv.org/abs/2604.01431)

## Summary

This paper investigates the utility of Kalshi event contracts as predictive signals for cryptocurrency realized volatility across Bitcoin and several altcoins. Using a dataset covering 2023-2026, the authors isolate distinct channels—monetary policy, recession risk, and inflation—that consistently outperform conventional benchmarks like Treasury yields and implied volatility indices. Results show that these event-driven markets contain unique information regarding volatility dynamics, with significant out-of-sample predictive gains confirmed through Clark-West and Benjamini-Hochberg tests.

## Key Contributions

- Establishes that Kalshi macro prediction markets provide incremental predictive power for cryptocurrency realized volatility beyond traditional financial indicators like Fed Funds futures and Treasury yields.
- Identifies distinct predictive channels: monetary policy repricing (KXFED) predicts Bitcoin volatility, while inflation repricing (KXCPI) predicts altcoin (ETH, SOL, ADA, LINK) volatility.
- Demonstrates robust out-of-sample performance for recession risk signals (KXRECSSNBER) with an MSFE ratio of 0.979.

## Open Questions & Future Work

- [[crypto-volatility-mechanism-ambiguity]]
- [[volatility-forecast-regime-dependence]]

## Archivist Review

The paper presents empirical evidence linking macro prediction markets to crypto-volatility. I have approved the two open questions because they identify significant limitations in interpreting these predictive signals—specifically the causal ambiguity of information flow and the temporal instability of predictive power across regimes. No new concepts or datasets were approved as the core findings are empirical applications rather than fundamental methodological innovations.

### Approved Open Questions
- Information Transmission Mechanism Ambiguity: Understanding the mechanism is critical for determining whether prediction markets offer genuine predictive alpha or if the signals merely reflect market noise or shared speculative activity. This distinction affects the robustness and policy implications of using such markets for financial forecasting.
- Volatility Forecast Regime Dependence: If a predictive signal is only valid in specific regimes, its utility for general-purpose risk management or options pricing is limited. Determining the scope and stability of these regimes is essential for practitioners.

## Links

- [Abstract](https://arxiv.org/abs/2604.01431)
- [PDF](https://arxiv.org/pdf/2604.01431)

