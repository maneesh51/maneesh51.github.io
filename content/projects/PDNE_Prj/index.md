---
title: Network structure-function relationship
date: 2025-10-26
# links:
#   - name: "Research Article"
#     url: "/publications/journal-article-2/"
#     icon: hero/academic-cap

featured: true

image:
  caption: Manish Yadav
  focal_point: ""
  preview_only: false

tags:
  - Complex Networks
  - Reservoir Computing
  - Machine Learning
---

This project has been started to understand emergent *structure-function* relationship of evolving networks. 


## Part-1: [Performance-Dependent Network Evolution (PDNE) framework](/publications/journal-article-2/).

I conceptualized a performance-driven evolutionary framework that grows reservoir networks from small initial seeds, while improving task performance. Key findings include:
- Evolution consistently outperforms random network generation.
- Evolved reservoirs become smaller, sparser, and more specialized, yet achieve higher accuracy.
- Network evolution follows identifiable **scaling laws** and **self-organization** in Nodes-Density parametric space, as well as **broken-symmetry** between input and readout nodes.
- As a bi-product, we discovered that task complexity can also be quantified using emerging structural signatures.

![Network Evolution Process](NARMA10_N-Density_fast.gif)
***Figure 1:** Network evolution over time showing performance improvement of the evoluving networks for different evolution models.*


This work demonstrated that RC benefits substantially from non-random, purposefully shaped architectures, challenging the long-standing reliance on large random reservoirs.

**Read full article here:** M. Yadav, S. Sinha, M. Stender, "Evolution beats random chance: Performance-dependent network evolution for enhanced computational capacity," [*Phys. Rev. E* **111**, 014320 (2025)](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.111.014320)

## Part-2: Performance-Dependent Node Pruning**. 

[Article published in *Chaos*](https://pubs.aip.org/aip/cha/article-abstract/35/8/083123/3358445/Task-specific-node-pruning-enhances-computational?redirectedFrom=fulltext)

In this complementary work, I introduced task-driven network pruning framework, starting from a large reservoir and iteratively removing nodes while optimizing performance. Results show:
- Pruned networks retain—often improve—accuracy
- Structural metrics such as spectral radius, out-degree, and **input–readout asymmetry** reorganize systematically
- Pruning reveals functionally critical subnetworks within Erdős-Rényi random networks.

**Read full article here:** M. Yadav and M. Stender, "Task-specific node pruning enhances computational efficiency of reservoir computing networks," [*Chaos* **35**, 083123 (2025)](https://doi.org/10.1063/5.0273535)

## Future directions

Furthermore, under the bigger theme of building a **comprehensive framework for performance-driven evolution of computational networks**. I further want to elucidate:

- How networks self-organize under **performance pressure**?
- What graph-theoretic measures (spectral radius, clustering, out-degree, motif distribution) emerge?
- How **structural adaptations** relate to task complexity and **generalizability**?
- **Scaling laws** governing optimal network 
- Node-level and macroscopic graph properties
- Incorporate **principles of biological evolution—mutation, adaptation, plasticity, co-evolution** and their computational analogs
- **Transfer learning** across tasks using evolving reservoirs

This line of research seeks to uncover why certain network structures are optimal for computation and how evolutionary mechanisms produce them.


<!--more-->
