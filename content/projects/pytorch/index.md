---
title: PyReCo Library
date: 2025-10-10
authors:
- admin
- Merten Stender
- Klara Disson
links:
  - type: site
    url: https://github.com/Cyber-Physical-Systems-in-Mech-Eng/pyReCo
  - name: "PyPI"
    url: https://pypi.org/project/pyreco/
    icon: brands/python

featured: true

image:
  caption: Manish Yadav
  focal_point: ""
  preview_only: false

tags:
  - Python Library
  - Reservoir computing

---

PyReCo is a Python based library built by researchers for researchers: we aim to develop new RC methods that allow for fast and efficient learning for sequential data. The main focus is time series prediction, mostly performed in an auto-regressive fashion based on learning discrete flow maps. Another core aspect that motivates the implementation of a new library is *structure-function-relationships* in functional networks.
<!--more-->

## Installation

```bash
pip install pyreco
```

PyReCo allows to implement novel ways to generate better reservoir networks than the classical random choice. Overview of the core capabilities of pyReCo:

- [x] **Classical reservoir computing**: using random reservoir layers and training readout-layer weights using Ridge regression
- [x] **Cross-validation**: built-in functions to k-fold cross-validate any ResPy model for performance evaluation
- [ ] **auto-regressive time stepping** through feeding the predictions into the input layer (closed-loop prediction system)
- [ ] **automated hyper-parameter tuning** for leakage rate, activation function, reservoir network properties, etc.

