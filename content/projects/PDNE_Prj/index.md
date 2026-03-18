---
title: "Network structure-function relationship | New Preprint"
date: 2025-10-26
links:
  - name: "Part-1 Article (Phys. Rev. E)"
    url: "/publications/journal-article-2/"
    icon: hero/academic-cap
  - name: "New Preprint (Article Page)"
    url: "/publications/emergent-ei-structure-2026/"
    icon: hero/newspaper
  - name: "arXiv Preprint"
    url: "https://arxiv.org/abs/2603.13635"
    icon: hero/document-text
  - name: "PDNE-WilsonCowanNeuron Code"
    url: "https://github.com/maneesh51/PDNE-WilsonCowanNeuron"
    icon: hero/link

featured: true

content_meta:
  trending: false
  new: true
  preprint: true

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

## Part-2: Performance-Dependent Node Pruning.

[Article published in *Chaos*](https://pubs.aip.org/aip/cha/article-abstract/35/8/083123/3358445/Task-specific-node-pruning-enhances-computational?redirectedFrom=fulltext)

In this complementary work, I introduced task-driven network pruning framework, starting from a large reservoir and iteratively removing nodes while optimizing performance. Results show:
- Pruned networks retain—often improve—accuracy
- Structural metrics such as spectral radius, out-degree, and **input–readout asymmetry** reorganize systematically
- Pruning reveals functionally critical subnetworks within Erdős-Rényi random networks.

**Read full article here:** M. Yadav and M. Stender, "Task-specific node pruning enhances computational efficiency of reservoir computing networks," [*Chaos* **35**, 083123 (2025)](https://doi.org/10.1063/5.0273535)

## Part-3: Applications

### Building neuronal digital twins with directed evolution 🔥 🆕  📄 

This new direction applies PDNE to computational neuroscience, where the objective is to build compact and interpretable digital twins of neuronal population dynamics.

In our latest preprint, PDNE evolves reservoir structure directly from Wilson-Cowan dynamics and discovers functionally meaningful excitatory-inhibitory organization without imposing that structure by design.

- Accurate prediction of both excitatory and inhibitory activity across unseen stimulus amplitudes.
- Zero-shot generalization to new pulse configurations (number, position, and amplitude) without retraining.
- Emergent recovery of population-level E-I sign structure from dynamics-driven learning.

![PDNE applications to neuronal digital twins](/uploads/pdne-wc-fig1.png)
***Figure 2:** Performance-dependent network evolution framework for modeling Wilson-Cowan neuronal dynamics and extracting interpretable E-I structure.*

**Article page on this site:** [Emergent E-I Structure in Performance-Evolved Reservoir Networks of Neuronal Population Dynamics](/publications/emergent-ei-structure-2026/)

**Read preprint (arXiv):** [arXiv:2603.13635](https://arxiv.org/abs/2603.13635)

**Code repository:** [PDNE-WilsonCowanNeuron](https://github.com/maneesh51/PDNE-WilsonCowanNeuron)

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
