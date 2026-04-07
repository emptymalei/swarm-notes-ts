---
# CSL-compatible fields
title: "A Multi-Scale ResNet-augmented Fourier Neural Operator Framework for High-Frequency Sequence-to-Sequence Prediction of Magnetic Hysteresis"
author:
  - literal: "Ziqing Guo"
  - literal: "Xiaobing Shen"
  - literal: "Ruth V. Sabariego"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.04150"

# Custom fields
paper_id: "2604.04150"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "res-fno"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:54:28Z"
created_at: "2026-04-07T04:54:28Z"
---

# A Multi-Scale ResNet-augmented Fourier Neural Operator Framework for High-Frequency Sequence-to-Sequence Prediction of Magnetic Hysteresis

**Authors**: Ziqing Guo, Xiaobing Shen, Ruth V. Sabariego
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.04150](https://arxiv.org/abs/2604.04150)

## Summary

This paper introduces the Res-FNO framework, a novel approach for modeling high-frequency magnetic hysteresis in power electronics. The architecture leverages a parallel structure combining global spectral modeling through Fourier Neural Operators with a local multi-scale ResNet path for fine-grained temporal refinement. By incorporating physical features like the time derivative of magnetic flux density, the model effectively captures transient phenomena such as ringing effects and minor loops that are critical for accurate core loss estimation. Validation across various materials demonstrates the framework's robust generalization and performance in complex simulation tasks.

## Key Contributions

- Proposed Res-FNO, a hybrid framework integrating multi-scale ResNet with Fourier Neural Operators to capture multi-scale magnetic hysteresis dynamics.
- Incorporated magnetic flux density time derivatives as physical features to improve sensitivity to high-frequency transients, ringing effects, and minor loops.
- Demonstrated superior generalization and predictive accuracy across diverse magnetic materials compared to standard operator-based approaches.

## Open Questions & Future Work

- [[mitigating-fno-spectral-bias]]

## Key Concepts

- [[res-fno]]: A hybrid architecture that fuses global Fourier Neural Operator blocks with parallel multi-scale ResNet paths to address spectral bias and capture fine-grained temporal dynamics.

## Archivist Review

I approved the Res-FNO architectural pattern as a significant contribution to multi-scale physical modeling, as it provides a clear, reusable strategy for mitigating spectral bias in FNOs. I also approved the open question regarding FNO spectral bias because it represents a foundational limitation in the neural operator field that necessitates future research. I rejected the paper's specific material datasets as they are too specialized and lack the broader, independent utility required for vault storage.

### Approved Concepts
- Res-FNO (ResNet-augmented Fourier Neural Operator): It represents a reusable architectural paradigm for combining global spectral neural operators with localized residual refinement, useful for physical systems with multi-scale dynamics.

### Approved Open Questions
- Mitigating FNO Spectral Bias: Spectral bias is a fundamental limiting factor for neural operators in applications involving multiscale dynamics, making the development of strategies to balance global spectral modeling with localized precision essential for high-fidelity physical simulations.

## Links

- [Abstract](https://arxiv.org/abs/2604.04150)
- [PDF](https://arxiv.org/pdf/2604.04150)

