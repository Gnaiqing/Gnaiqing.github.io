---
title: "Tenet: A framework for modeling tensor dataflow based on relation-centric notation"
collection: publications
category: conferences
permalink: /publication/2021-tenet
date: 2021-06-14
venue: 'the 2021 ACM/IEEE 48th Annual International Symposium on Computer Architecture (ISCA)'
paperurl: 'https://arxiv.org/pdf/2105.01892'
---
**Modeling tensor dataflow in spatial architectures with a novel relation-centric notation.**

Accelerating tensor applications on spatial architectures provides high performance and energy-efficiency, but requires accurate performance models for evaluating various dataflow alternatives. Such modeling relies on the notation of tensor dataflow and the formulation of performance metrics. Recent proposed compute-centric and data-centric notations describe the dataflow using imperative directives. However, these two notations are less expressive and thus lead to limited optimization opportunities and inaccurate performance models.

In this paper, we propose a framework TENET that models hardware dataflow of tensor applications. We start by introducing a relation-centric notation, which formally describes the hardware dataflow for tensor computation. The relation-centric notation specifies the hardware dataflow, PE interconnection, and data assignment in a uniform manner using relations. The relation-centric notation is more expressive than the compute-centric and data-centric notations by using more sophisticated affine transformations. Another advantage of relation-centric notation is that it inherently supports accurate metrics estimation, including data reuse, bandwidth, latency, and energy. TENET computes each performance metric by counting the relations using integer set structures and operators. Overall, TENET achieves 37.4% and 51.4% latency reduction for CONV and GEMM kernels compared with the state-of-the-art data-centric notation by identifying more sophisticated hardware dataflows.