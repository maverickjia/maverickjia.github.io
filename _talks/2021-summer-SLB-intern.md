---
title: "Well Logs Interpolation and Uncertainty Analysis Using Attentive Neural Processes"
collection: talks
type: "Presentation"
permalink: /talks/2024-12-12-talk-AGU
venue: "SLB Summer Intern Project"
date: 2021-07-30
location: "Houston, TX"
---

**Abstract:**  Accurate interpolation of well-log properties from sparse measurements is essential for subsurface characterization, yet traditional approaches struggle to integrate heterogeneous geophysical data and quantify predictive uncertainty. This project develops an end-to-end deep-learning framework based on Attentive Neural Processes (ANPs) to jointly interpolate well-log porosity and estimate uncertainty across a large 3D seismic volume. The method leverages a 700 × 327 × 397 seismic cube (~90 million samples) and 36 sparsely sampled well logs as input. ANPs combine the flexibility and speed of neural networks with the uncertainty-aware foundations of Gaussian Processes, while a cross-attention mechanism fuses local seismic patches with context points to improve spatial generalization and capture heterogeneity in the subsurface. The model is implemented in TensorFlow / TensorFlow Probability and trained on GPU-accelerated cloud infrastructure using a variational inference objective (ELBO). Experimental results demonstrate that ANPs produce accurate porosity predictions, yield uncertainty estimates strongly correlated with residual structure, and achieve high confidence-interval coverage across depth slices, crosslines, and inlines. This work highlights the potential of attention-based neural surrogates for scalable, uncertainty-aware geoscience modeling and provides a foundation for applying neural processes to broader subsurface inference tasks.
[Presentation](/files/SLB_final_presentation_MJ.pdf)
