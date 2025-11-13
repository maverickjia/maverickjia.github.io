---
title: "Well Logs Interpolation and Uncertainty Analysis Using Attentive Neural Processes"
collection: talks
type: "Presentation"
permalink: /talks/2024-12-12-talk-AGU
venue: "SLB Summer Intern Project"
date: May - August, 2025
location: "Houston, TX"
---

**Abstract:** Mitigating methane emissions from the oil and gas (O&G) sector is pivotal for addressing global climate change quickly, as this sector contributes 22% of global anthropogenic methane emissions and 32% of such emissions in the United States. Continuous monitoring systems (CMS) are becoming increasingly vital for methane emission monitoring on O&G since they provide measurement of methane concentrations, and corresponding wind data, in near real-time, capable of capturing both highly fluctuating emissions and transient super emitters on O&G. However, existing localization and quantification approaches may not be the most effective for several reasons. First, most widely used forward models, such as Gaussian dispersion models, inadequately represent the complexities of atmospheric methane transport governed by the advection-diffusion partial differential equation (PDE), particularly in calm wind conditions. Second, these approaches struggle with multi-source emissions due to the increased complexity within the traditional inversion framework. Here, we propose to use physics-informed neural networks (PINN) to address the source localization and quantification problem. Specifically, a neural network is used to parameterize the solution to the advection diffusion PDE. Concurrently, the source term in the PDE is also treated as a trainable variable which is inverted from the data observed from CMS sensors. Importantly, we leverage the sparsity of potential emission sources to constrain the source term, achieving more accurate localization and quantification results. Finally, we implement a variety of techniques to enhance the performance of the PINN model such as embedding input coordinate variables, using adaptive weighting schemes in the loss function, and respecting causality in training the time-dependent PDE. We evaluate our model’s performance on controlled release data and also present initial results from a real O&G site.
[iPoster](https://agu24.ipostersessions.com/default.aspx?s=BA-99-09-91-AB-27-4E-93-78-D4-9C-F4-80-D6-56-35)
