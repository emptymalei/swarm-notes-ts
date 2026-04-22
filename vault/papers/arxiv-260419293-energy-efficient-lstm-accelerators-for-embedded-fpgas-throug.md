---
# CSL-compatible fields
title: "Energy Efficient LSTM Accelerators for Embedded FPGAs through Parameterised Architecture Design"
author:
  - literal: "Chao Qian"
  - literal: "Tianheng Ling"
  - literal: "Gregor Schiele"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19293"

# Custom fields
paper_id: "2604.19293"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-04-22T05:04:06Z"
created_at: "2026-04-22T05:04:06Z"
---

# Energy Efficient LSTM Accelerators for Embedded FPGAs through Parameterised Architecture Design

**Authors**: Chao Qian, Tianheng Ling, Gregor Schiele
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19293](https://arxiv.org/abs/2604.19293)

## Summary

This paper introduces a parameterised accelerator architecture designed to improve the execution speed and energy efficiency of LSTM networks on resource-constrained embedded FPGAs. The design allows for flexible configuration of hardware resources, such as DSP usage and activation function implementation, to suit diverse deployment scenarios. Evaluated through real-time inference, the proposed accelerator achieves significant performance gains, demonstrating an energy efficiency of 11.89 GOP/s/W while processing 32873 samples per second.

## Key Contributions

- Proposes a parameterised hardware accelerator architecture for LSTMs tailored to resource-constrained embedded FPGAs.
- Enables flexible optimisation of resource usage, including DSP allocation and activation function implementation.
- Achieves an energy efficiency of 11.89 GOP/s/W during real-time inference on embedded FPGA hardware.

## Open Questions & Future Work

- [[automated-parameter-optimization-for-fpga-accelerators]]

## Archivist Review

The proposed concept of a parameterised FPGA accelerator is too specific to hardware engineering and falls outside the scope of reusable forecasting mechanisms or algorithms. However, the identified open question regarding the automation of hardware parameter selection represents a meaningful research challenge in deploying resource-constrained machine learning, which is a significant bottleneck in edge-based time series analysis.

### Approved Open Questions
- Automated Parameter Selection Framework: Currently, manual configuration of hardware accelerators for different deployment scenarios is time-consuming and non-optimal, which hinders the widespread adoption of customized FPGA-based acceleration in resource-limited embedded domains.

### Rejected Candidates
- [concept] Parameterised Hardware Accelerator Architecture (`parameterised-hardware-accelerator-architecture`) - paper_local: This is a specific architectural implementation for LSTMs on FPGAs and does not constitute a broadly reusable conceptual framework for time series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.19293)
- [PDF](https://arxiv.org/pdf/2604.19293)

