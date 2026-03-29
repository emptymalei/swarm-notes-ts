---
created_at: '2026-03-29T20:18:35Z'
source_papers:
- '[[openalex-2603.25251-does-explanation-correctness-matter-linking-computational-xa]]'
title: Generalizing functional property effects
---

**Background:** A limitation of the study is that it used synthetic data and a simple classification task to control explanation correctness precisely, which may not fully generalize to complex, real-world applications.

**Question / Future Work:** It is an open question whether the observed threshold relationship between correctness and understanding, derived from a simple time series classification task using temporally displaced feature errors, generalizes to real AI models, more complex decision boundaries, or other explanation formats (e.g., not heatmap-style feature attributions).

**Why It Matters:** Generalizability across different XAI evaluation metrics (like robustness or sparsity) and explanation formats is essential to validate if the threshold effect found for correctness is a universal principle in XAI human evaluation or specific to the tested metric/format.

**Evidence:** More broadly, the experimental approach we used here, manipulating a functional property at controlled levels and measuring human outcomes, could be applied to other widely used metrics such as robustness or sparsity to test whether they predict human performance.