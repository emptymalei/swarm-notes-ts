---
# CSL-compatible fields
title: "Electricity price forecasting across Norway's five bidding zones in the post-crisis era"
author:
  - literal: "My Thi Diem Phan"
  - literal: "Trung Tuyen Truong"
  - literal: "Hoai Phuong Ha"
  - literal: "Dat Thanh Nguyen"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26634"

# Custom fields
paper_id: "2604.26634"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "electricity-price-forecasting"
  - "regime-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:13:17Z"
created_at: "2026-04-30T05:13:17Z"
---

# Electricity price forecasting across Norway's five bidding zones in the post-crisis era

**Authors**: My Thi Diem Phan, Trung Tuyen Truong, Hoai Phuong Ha, Dat Thanh Nguyen
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26634](https://arxiv.org/abs/2604.26634)

## Summary

This paper provides a systematic performance evaluation of electricity price forecasting across Norway's five bidding zones in the post-energy-crisis landscape. By constructing a 2019-2025 multimodal dataset and applying rigorous rolling-origin backtesting, the authors analyze the impact of various exogenous features and model architectures on forecast accuracy. The findings reveal that while gradient-boosted trees typically excel, simple statistical baselines remain robust, and that exogenous market data is essential for managing model reliability during volatile structural regimes.

## Key Contributions

- Evaluates eight forecasting model families across all five Norwegian Nord Pool bidding zones using a unified 2019-2025 multimodal dataset.
- Demonstrates that LightGBM consistently outperforms other architectures, while ridge ARX remains highly competitive in northern bidding zones.
- Finds that simple autoregressive and calendar-based models often match the performance of complex multimodal models, but external features like reservoir levels and gas prices are critical for reducing error during stressed market regimes.

## Open Questions & Future Work

- [[regime-aware-probabilistic-forecasting]]

## Archivist Review

I have approved the open question regarding regime-aware forecasting because it identifies a substantial and widely applicable limitation in current time-series forecasting research—specifically the trade-off between standard autoregressive performance and failure under structural shifts. I rejected all candidate concepts as they were descriptive of specific findings or standard practices rather than reusable methodologies or novel architectural paradigms. The review maintains the vault's high threshold for conceptual innovation and long-term utility.

### Approved Open Questions
- Regime-aware and probabilistic forecasting: Current models often perform well on average but fail systematically during extreme, identifiable market conditions, which significantly limits their utility for operational risk management.

### Rejected Candidates
- [open_question] Regime-aware and probabilistic forecasting (`regime-aware-probabilistic-forecasting`) - other: The candidate was accepted and moved to the approved_open_questions list.

## Links

- [Abstract](https://arxiv.org/abs/2604.26634)
- [PDF](https://arxiv.org/pdf/2604.26634)

