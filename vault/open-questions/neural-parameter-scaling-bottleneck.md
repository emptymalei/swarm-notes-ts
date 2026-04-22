---
created_at: '2026-04-22T05:04:58Z'
source_papers:
- '[[arxiv-260418827-omnimouse-scaling-properties-of-multi-modal-multi-task-brain]]'
title: Scaling bottleneck of neuron embeddings
---

**Background:** Neural foundation models often rely on per-neuron identity embeddings to handle heterogeneous, multi-session datasets. This approach scales linearly with the number of neurons, which poses significant computational challenges for scaling to larger, more diverse datasets.

**Question / Future Work:** The current architecture relies on per-neuron identity embeddings, creating a computational bottleneck where the number of parameters grows linearly with the neuron count. Developing parameter-efficient architectures that decouple model capacity from the number of recorded units remains an essential challenge for achieving broader neuro-scientific scaling.

**Why It Matters:** This architectural bottleneck represents a fundamental barrier to scaling neural foundation models as high-density recording technologies continue to increase the number of monitored neurons.

**Evidence:** OmniMouse parameters scale linearly with the number of neurons, as it learns per-neuron embeddings. This makes training computationally expensive and may limit scaling to larger datasets.