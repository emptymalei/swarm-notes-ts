---
created_at: '2026-05-06T05:11:11Z'
source_papers:
- '[[arxiv-260503997-uncertainty-quantification-in-forecast-comparisons]]'
title: Asymptotics for Growing Dimensions
---

**Background:** Simultaneous confidence bands for forecast evaluation metrics often rely on asymptotic theory that assumes the dimension of the evaluation space remains fixed as the sample size increases. Many modern forecasting applications involve evaluation vectors where the dimension potentially grows with or exceeds the available sample size.

**Question / Future Work:** There is a need to extend the existing asymptotic theory for simultaneous confidence bands—currently defined for a fixed dimension J as the sample size N goes to infinity—to cases where J grows with N (J → ∞ as N → ∞). Such an extension is critical for providing valid inference in high-dimensional settings where current theoretical guarantees do not formally apply.

**Why It Matters:** Without such a theoretical framework, uncertainty quantification in high-dimensional forecast comparisons remains heuristic and potentially invalid, limiting the reliability of model selection in large-scale applications.

**Evidence:** Extending the asymptotic theory to allow J → ∞ with N → ∞ would be of interest for applications involving large spatial grids, such as the weather forecasting case study, where the number of locations exceeds the sample size.