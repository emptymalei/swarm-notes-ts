---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "PathFM: Fast Generative Forecasting of Multivariate Trajectories"
description: "PathFM is a generative forecasting model designed to capture the dependence structure of multivariate trajectories, which standard marginal-quantile models often neglect. By utilizing flow matching and distilling the generation process into one or two steps, PathFM achieves high efficiency, enabling the generation of multiple trajectory paths in roughly the same time as a single query to a quantile model. The authors also introduce fps-bench (Forecast Path Score Bench) to evaluate trajectory-dependent metrics like energy and variogram scores. Experimental results show that PathFM outperforms baselines in path-based metrics and maintains long-term variability in chaotic systems where other strong baselines collapse."
resource: "https://arxiv.org/abs/2610.22358"
tags:
  - "time-series-forecasting"
  - "flow-matching"
  - "probabilistic-forecasting"
  - "multivariate-forecasting"
  - "foundation-models"
  - "distillation"
  - "benchmarking"
  - "generative-modeling"
timestamp: "2026-10-18T00:14:46Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jiachen Yao"
  - literal: "Xiyuan Zhang"
  - literal: "Annan Yu"
  - literal: "Boran Han"
  - literal: "Abdul Fatir Ansari"
  - literal: "Shuai Zhang"
  - literal: "Michael Bohlke-Schneider"
  - literal: "Bernie Wang"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22358"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "pathfm"
    description: "A generative time-series forecasting model using distilled flow matching to produce full multivariate trajectories efficiently."
  - name: "fps-bench"
    description: "An evaluation suite for time-series forecasting that assesses trajectory-level consistency through energy and variogram scores."
datasets:
  []
open_questions:
  - name: "scaling-generative-multivariate-forecasting-trajectories"
    description: "How can flow matching and distillation architectures like PathFM be scaled to extremely high-dimensional multivariate trajectories (e.g., thousands of sensors) without sacrificing joint coherence or sampling efficiency?"
  - name: "calibration-diversity-tradeoffs-in-distilled-forecasters"
    description: "What are the theoretical and empirical limits of using 1-step or 2-step distilled models for forecasting highly multi-modal futures, and how does this distillation affect the calibration of tail-risk estimates?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:14:46Z"
created_at: "2026-10-18T00:14:46Z"
---

# PathFM: Fast Generative Forecasting of Multivariate Trajectories

**Authors**: Jiachen Yao, Xiyuan Zhang, Annan Yu, Boran Han, Abdul Fatir Ansari, Shuai Zhang, Michael Bohlke-Schneider, Bernie Wang
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22358](https://arxiv.org/abs/2610.22358)

## Summary

PathFM is a generative forecasting model designed to capture the dependence structure of multivariate trajectories, which standard marginal-quantile models often neglect. By utilizing flow matching and distilling the generation process into one or two steps, PathFM achieves high efficiency, enabling the generation of multiple trajectory paths in roughly the same time as a single query to a quantile model. The authors also introduce fps-bench (Forecast Path Score Bench) to evaluate trajectory-dependent metrics like energy and variogram scores. Experimental results show that PathFM outperforms baselines in path-based metrics and maintains long-term variability in chaotic systems where other strong baselines collapse.

## Key Contributions

- Proposed PathFM, a generative forecasting model that uses flow matching to capture the full dependence structure of future trajectories.
- Developed an efficient inference strategy by distilling the flow model into 1-2 steps and implementing history attention cache sharing across draws.
- Achieved fast multi-path sampling speeds comparable to single-query marginal quantile models.
- Introduced fps-bench, a benchmarking framework that evaluates trajectory-level consistency using energy and variogram scores.

## Limitations

The paper does not explicitly detail the performance trade-offs when scaling the number of variables in the multivariate trajectories or the potential loss of diversity due to the extreme distillation to 1-2 steps.

## Open Questions & Future Work

- [[scaling-generative-multivariate-forecasting-trajectories]]
- [[calibration-diversity-tradeoffs-in-distilled-forecasters]]

## Key Concepts

- [[pathfm]]: A generative time-series forecasting model using distilled flow matching to produce full multivariate trajectories efficiently.
- [[fps-bench]]: An evaluation suite for time-series forecasting that assesses trajectory-level consistency through energy and variogram scores.

## Archivist Review

I approved PathFM and fps-bench as they represent the core architectural and evaluative contributions of the paper, respectively. I rejected the standard benchmarks (TIME, fev-bench) as they are established in the literature. The open questions were approved as they address fundamental bottlenecks in scaling and reliability for distilled generative forecasting.

### Approved Concepts
- PathFM: PathFM addresses a critical gap in time-series foundation models by shifting from marginal quantile predictions to modeling the full joint dependence structure of future trajectories.
- Forecast Path Score Bench (fps-bench): Existing time-series benchmarks often rely on marginal point or quantile metrics; fps-bench provides the necessary framework to evaluate the temporal and cross-variable consistency of generated paths.

### Approved Open Questions
- Scaling Generative Multivariate Trajectory Modeling: Real-world industrial and financial applications often involve high-dimensional data where joint trajectory dependence is critical for risk assessment.
- Calibration and Diversity in Distilled Forecasters: Forecasting requires high reliability in probabilistic coverage; understanding the trade-off between speed and calibration is essential for deployment in safety-critical systems.

### Rejected Candidates
- [concept] Direct Calibration Loss Optimization (`direct-calibration-loss-optimization`) - subcomponent_of_broader_mechanism: This is a specific training technique enabled by the model's architecture rather than a standalone novel concept or broad architectural paradigm.
- [dataset] TIME (`time`) - generic: This is an established, routine benchmark used for comparison rather than a novel contribution of this paper.
- [dataset] fev-bench (`fev-bench`) - generic: This is an existing forecasting benchmark that the authors build upon rather than a new dataset introduction.

## Links

- [Abstract](https://arxiv.org/abs/2610.22358)
- [PDF](https://arxiv.org/pdf/2610.22358)

