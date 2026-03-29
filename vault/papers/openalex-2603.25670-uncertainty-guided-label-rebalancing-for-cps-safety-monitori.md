---
# CSL-compatible fields
title: "Uncertainty-Guided Label Rebalancing for CPS Safety Monitoring"
author:
  - literal: "John Ayotunde"
  - literal: "Qinghua Xu"
  - literal: "Guancheng Wang"
  - literal: "Lionel C. Briand"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25670"

# Custom fields
paper_id: "2603.25670"
paper_source: "openalex"
domain: "time-series"
tags:
  - "data imbalance"
  - "safety-critical systems"
  - "time-series forecasting"
architectures:
  []
datasets:
  - "UAV benchmark"
concept_slugs:
  - "u-balance-uncertainty-guided-rebalancing"
  - "uncertainty-guided-label-rebalancing-ulnr"
  - "gatedmlp-uncertainty-predictor"
dataset_slugs:
  - "uav-benchmark"
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:19:00Z"
created_at: "2026-03-29T20:19:00Z"
---

# Uncertainty-Guided Label Rebalancing for CPS Safety Monitoring

**Authors**: John Ayotunde, Qinghua Xu, Guancheng Wang, Lionel C. Briand
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25670](https://arxiv.org/abs/2603.25670)

## Summary

The paper addresses extreme class imbalance in Cyber-Physical Systems (CPS) safety monitoring, where unsafe events are rare. The proposed U-Balance framework leverages behavioral uncertainty by first training a GatedMLP to predict an uncertainty score from telemetry features. It then applies uncertainty-guided label rebalancing (uLNR) to probabilistically relabel uncertain 'safe' samples as 'unsafe', enriching the minority class informatively. Evaluated on a UAV benchmark with a 46:1 imbalance, U-Balance significantly improved performance, achieving an F1 score of 0.806, superior to baselines while maintaining inference efficiency.

## Key Contributions

- Proposed U-Balance, a novel supervised approach that integrates behavioral uncertainty to address extreme class imbalance in CPS safety monitoring.
- Introduced a GatedMLP-based uncertainty predictor to summarize telemetry into distributional kinematic features and an uncertainty score.
- Developed the uncertainty-guided label rebalancing (uLNR) mechanism, which probabilistically relabels uncertain 'safe' samples as 'unsafe' to enrich the minority class without synthesizing data.
- Achieved a 0.806 F1 score on a large-scale UAV benchmark (46:1 imbalance), outperforming the strongest baseline by 14.3 percentage points.

## Limitations

The paper relies on a moderate but significant correlation between behavioral uncertainty and safety outcomes, suggesting the uncertainty model may not perfectly capture all unsafe boundaries. The performance relies heavily on the quality of the GatedMLP-based uncertainty predictor.

## Open Questions & Future Work

- [[u-balance-generalizability-across-cps-domains]]
- [[alternative-uncertainty-estimation-for-ulnr]]

## Key Concepts

- [[u-balance-uncertainty-guided-rebalancing]]: A supervised framework that leverages behavioral uncertainty to rebalance imbalanced datasets for Cyber-Physical Systems safety monitoring.
- [[uncertainty-guided-label-rebalancing-ulnr]]: A mechanism that probabilistically relabels safe-labeled data points with high predicted uncertainty as unsafe to enrich the minority class in imbalanced datasets.
- [[gatedmlp-uncertainty-predictor]]: A GatedMLP model designed to predict a behavioral uncertainty score from kinematic features extracted from CPS telemetry windows.

## Archivist Review

Three central concepts were approved: the overall U-Balance framework, the novel uLNR rebalancing mechanism, and the GatedMLP used to generate the required uncertainty signal. The named UAV benchmark dataset was also approved for its role in evaluating the extreme class imbalance challenge. Two specific, mechanism-focused open questions regarding domain generalization and alternative uncertainty estimators were approved as valuable future work directions.

### Approved Concepts
- U-Balance: It is the main proposed framework that integrates uncertainty prediction with label rebalancing for improving safety monitoring on imbalanced CPS data.
- Uncertainty-Guided Label Rebalancing (uLNR): This is the specific core mechanism within U-Balance that modifies the training distribution based on uncertainty, addressing the minority class enrichment problem.
- GatedMLP-based Uncertainty Predictor: This is the specific architectural component used to quantify the novel concept of 'behavioral uncertainty' from time-series CPS telemetry.

### Approved Open Questions
- Evaluate U-Balance across CPS domains: Assessing generalizability beyond UAVs is crucial to determine if the uncertainty-guided rebalancing mechanism is a domain-agnostic solution for CPS safety prediction under imbalance.
- Investigate alternative uncertainty estimators: The effectiveness of the core concept (uncertainty-guided rebalancing) depends on the quality of the uncertainty signal; exploring more robust uncertainty estimators can lead to theoretically stronger guarantees.

### Rejected Candidates
- [concept] U-Balance (`u-balance-uncertainty-guided-rebalancing`) - generic: Approved. Candidate selected as a core mechanism.
- [concept] Uncertainty-Guided Label Rebalancing (uLNR) (`uncertainty-guided-label-rebalancing-ulnr`) - generic: Approved. Candidate selected as a core mechanism.
- [concept] GatedMLP-based Uncertainty Predictor (`gatedmlp-uncertainty-predictor`) - generic: Approved. Candidate selected as a core mechanism.
- [open_question] Evaluate U-Balance across CPS domains (`u-balance-generalizability-across-cps-domains`) - generic: Approved. Candidate is a specific, non-boilerplate future direction related to domain transfer.
- [open_question] Investigate alternative uncertainty estimators (`alternative-uncertainty-estimation-for-ulnr`) - generic: Approved. Candidate is a specific, non-boilerplate investigation into improving the uncertainty signal for the core method.

## Datasets

- [[uav-benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2603.25670)
- [PDF](https://arxiv.org/pdf/2603.25670)

