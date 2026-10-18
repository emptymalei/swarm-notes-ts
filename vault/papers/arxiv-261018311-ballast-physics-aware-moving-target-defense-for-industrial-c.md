---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "BALLAST: Physics-Aware Moving Target Defense for Industrial Control Systems Using a Digital Twin Safety Oracle"
description: "The paper proposes BALLAST, a physics-aware Moving Target Defense (MTD) for Industrial Control Systems (ICS). Unlike standard MTD which shuffles network addresses without regard for physical stability, BALLAST utilizes a physics-informed LSTM (PI-LSTM) acting as a Digital Twin 'safety oracle' to forecast the impact of network changes on control loops. A reinforcement learning agent manages the trade-off between security entropy and process stability, ensuring that any reconfiguration remains within safe operating envelopes. Evaluations on the SWaT water treatment testbed show that BALLAST eliminates safety violations while maintaining high reconnaissance deterrence, significantly outperforming existing RL-based MTD methods."
resource: "https://arxiv.org/abs/2610.18311"
tags:
  - "moving-target-defense"
  - "digital-twin"
  - "physics-informed-ml"
  - "safety-constrained-control"
  - "reinforcement-learning"
  - "industrial-control-systems"
  - "industrial-ai"
  - "cyber-physical-systems"
  - "swat-testbed"
timestamp: "2026-10-18T00:58:13Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Oscar Mogollon-Gutierrez"
  - literal: "Mohammadhossein Homaei"
  - literal: "Alberto Lopez-Trigo"
  - literal: "Andres Caro"
  - literal: "Mar Avila"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18311"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "physics-aware-moving-target-defense"
    description: "A security paradigm for cyber-physical systems where network reconfiguration strategies are constrained by the predicted physical stability and safety of the underlying controlled process."
datasets:
  - name: "SWaT Water Treatment Testbed"
    description: "A standard industrial control system security benchmark representing a six-stage water treatment facility, used for evaluating intrusion detection and active defense mechanisms."
open_questions:
  - name: "safety-oracle-robustness-in-cps"
    description: "How can the reliability and robustness of learned safety oracles be guaranteed against model drift, training data bias, or adversarial manipulation designed to trigger false safety violations?"
  - name: "multi-protocol-mtd-interoperability"
    description: "Can physics-aware MTD mechanisms and their associated handover protocols (like connection-draining) scale to support diverse, multi-protocol environments without introducing unacceptable latency or physical disruption?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:58:13Z"
created_at: "2026-10-18T00:58:13Z"
---

# BALLAST: Physics-Aware Moving Target Defense for Industrial Control Systems Using a Digital Twin Safety Oracle

**Authors**: Oscar Mogollon-Gutierrez, Mohammadhossein Homaei, Alberto Lopez-Trigo, Andres Caro, Mar Avila
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18311](https://arxiv.org/abs/2610.18311)

## Summary

The paper proposes BALLAST, a physics-aware Moving Target Defense (MTD) for Industrial Control Systems (ICS). Unlike standard MTD which shuffles network addresses without regard for physical stability, BALLAST utilizes a physics-informed LSTM (PI-LSTM) acting as a Digital Twin 'safety oracle' to forecast the impact of network changes on control loops. A reinforcement learning agent manages the trade-off between security entropy and process stability, ensuring that any reconfiguration remains within safe operating envelopes. Evaluations on the SWaT water treatment testbed show that BALLAST eliminates safety violations while maintaining high reconnaissance deterrence, significantly outperforming existing RL-based MTD methods.

## Key Contributions

- Developed BALLAST, a physics-aware Moving Target Defense (MTD) framework that uses a PI-LSTM Digital Twin to predict the physical impact of network address shuffling.
- Implemented a safety-constrained reinforcement learning agent that optimizes the trade-off between network security (entropy) and control loop stability.
- Introduced a connection-draining handover mechanism for the Modbus protocol to prevent 'in-flight' transaction failures during network reconfigurations.
- Demonstrated a 100% reduction in safety violations compared to traditional RL-MTD on the SWaT testbed while maintaining an 85% reconnaissance detection/deterrence rate.

## Limitations

The full decision-to-enforcement latency was measured only on workstation hardware; edge CPU performance is currently based on projections rather than empirical end-to-end measurements.

## Open Questions & Future Work

- [[safety-oracle-robustness-in-cps]]
- [[multi-protocol-mtd-interoperability]]

## Key Concepts

- [[physics-aware-moving-target-defense]]: A security paradigm for cyber-physical systems where network reconfiguration strategies are constrained by the predicted physical stability and safety of the underlying controlled process.

## Archivist Review

I approved Physics-Aware Moving Target Defense as a primary concept because it addresses a fundamental bottleneck in applying network security to physical processes. I rejected the system-specific name 'BALLAST' in favor of this generic category. The SWaT testbed was approved as a high-value reusable dataset in the ICS domain. Open questions were focused on the robustness of safety oracles and the practical challenge of protocol heterogeneity.

### Approved Concepts
- Physics-Aware Moving Target Defense: Traditional Moving Target Defense (MTD) often ignores the physical consequences of network-level reconfigurations, which can destabilize control loops or cause safety violations in cyber-physical systems.

### Approved Open Questions
- Robustness of Learned Safety Oracles: A flawed safety oracle can lead to a denial-of-service (if it blocks safe actions) or catastrophic failure (if it permits unsafe actions).
- Multi-Protocol MTD Interoperability: Real-world scalability of network defenses requires seamless operation across the complex protocol stacks found in heterogeneous industrial environments.

### Rejected Candidates
- [concept] BALLAST (`ballast-mtd`) - paper_local: This is the paper-local name for the specific framework; the broader and more reusable concept is Physics-Aware Moving Target Defense.
- [concept] Connection-Draining Handover (`connection-draining-handover`) - not_novel: This is a standard network engineering technique (graceful shutdown) applied to the Modbus protocol rather than a novel ML architectural concept.
- [concept] Physics-Informed LSTM Surrogate (`pi-lstm-surrogate`) - subcomponent_of_broader_mechanism: Physics-Informed LSTMs are an established model class; their specific use here is a subcomponent of the broader physics-aware defense framework.

## Datasets

- [[SWaT Water Treatment Testbed]]

## Links

- [Abstract](https://arxiv.org/abs/2610.18311)
- [PDF](https://arxiv.org/pdf/2610.18311)

