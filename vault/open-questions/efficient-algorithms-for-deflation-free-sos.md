---
created_at: '2026-04-29T05:10:54Z'
source_papers:
- '[[arxiv-260425664-deflation-free-optimal-scoring]]'
title: Efficient Algorithms for DFSOS
---

**Background:** Sparse discriminant analysis is commonly performed using deflation-based methods that compute discriminant vectors sequentially, which can propagate numerical and statistical errors. While deflation-free approaches have been developed to jointly estimate discriminant vectors under a global orthogonality constraint, existing heuristics for these constrained optimization problems remain computationally demanding.

**Question / Future Work:** There is a need to develop more efficient algorithms for solving the orthogonality-constrained optimization problem associated with deflation-free sparse optimal scoring (DFSOS). Current splitting methods for these problems incur significant computational costs, and further specialization of state-of-the-art manifold optimization algorithms could lead to improved efficiency.

**Why It Matters:** Computational efficiency is a primary barrier to the practical deployment of deflation-free sparse discriminant analysis in high-dimensional settings.

**Evidence:** The observed increase in computation used by DFSOS compared to the existing ASDA methods suggests an important avenue for potential research: the development of faster algorithms for solution of (8).