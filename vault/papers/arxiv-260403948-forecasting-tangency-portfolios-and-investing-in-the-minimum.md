---
# CSL-compatible fields
title: "Forecasting Tangency Portfolios and Investing in the Minimum Euclidean Distance Portfolio to Maximize Out-of-Sample Sharpe Ratios"
author:
  - literal: "Nolan Alexander"
  - literal: "William Scherer"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.03948"

# Custom fields
paper_id: "2604.03948"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-04-07T04:54:58Z"
created_at: "2026-04-07T04:54:58Z"
---

# Forecasting Tangency Portfolios and Investing in the Minimum Euclidean Distance Portfolio to Maximize Out-of-Sample Sharpe Ratios

**Authors**: Nolan Alexander, William Scherer
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.03948](https://arxiv.org/abs/2604.03948)

## Summary

This paper introduces a novel asset allocation framework that enhances out-of-sample Sharpe ratios by directly forecasting the tangency portfolio instead of the traditional return vector and covariance matrix. The method decomposes the efficient frontier into three interpretable coefficients, which are then forecasted using vector autoregressions. Finally, the strategy invests in the portfolio on the frontier that maintains the minimum Euclidean distance to this forecasted tangency position, effectively mitigating risks associated with the non-stationarity of returns and covariances in out-of-sample data.

## Key Contributions

- Introduces a two-component asset allocation framework that forecasts the tangency portfolio directly rather than estimating individual return vectors and covariance matrices.
- Utilizes functional decomposition of the efficient frontier (a square root second-order polynomial) to extract three interpretable coefficients for forecasting via vector autoregression.
- Implements a minimum Euclidean distance investment strategy to map forecasted tangency portfolios onto the efficient frontier, enhancing out-of-sample Sharpe ratio performance.

## Links

- [Abstract](https://arxiv.org/abs/2604.03948)
- [PDF](https://arxiv.org/pdf/2604.03948)

