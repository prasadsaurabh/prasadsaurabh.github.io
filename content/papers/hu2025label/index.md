---
title: >-
  Label-Efficient Hyperspectral Image Classification via Spectral FiLM Modulation of Low-Level Pretrained Diffusion Features
date: '2025-07-01'
authors:
  - Yuzhen Hu
  - Biplab Banerjee
  - Saurabh Prasad
publication: >-
  ICML TerraBytes Workshop 2025 (Spotlight Paper)
tags:
  - "ICML TerraBytes 2025 (Spotlight)"
  - "Hyperspectral"
  - "Diffusion Models"
  - "Label-Efficient Learning"
  - "GeoAI"
summary: >-
  **ICML TerraBytes 2025 (Spotlight)** · We present a label-efficient framework for hyperspectral image classification that leverages spatial features from a frozen diffusion model pretrained on natural images. A lightweight FiLM-based fusion module adaptively integrates spectral cues into frozen spatial features, outperforming state-of-the-art approaches using only sparse training labels.
links:
  - name: Link
    url: 'https://openreview.net/forum?id=l9wTrSu9i9'
---

---

##### Abstract

Hyperspectral imaging (HSI) enables detailed land cover classification, but low spatial resolution and sparse annotations pose significant challenges. We present a label-efficient framework that leverages spatial features from a frozen diffusion model pretrained on natural images. Specifically, we extract low-level representations from high-resolution decoder layers at early denoising timesteps, which transfer well to the low-texture setting of HSI. To combine spectral and spatial information, we introduce a lightweight FiLM-based fusion module that adaptively integrates spectral cues into frozen spatial features, enabling effective multimodal learning under sparse supervision. Experiments on two recent hyperspectral datasets show that our method outperforms state-of-the-art approaches using only the sparse training labels provided.

---

##### Download

- [OpenReview](https://openreview.net/forum?id=l9wTrSu9i9)

---

##### Citation

```BibTeX
@inproceedings{Hu2025Label,
  author = {Hu, Yuzhen and Banerjee, Biplab and Prasad, Saurabh},
  title = {Label-Efficient Hyperspectral Image Classification via Spectral FiLM Modulation of Low-Level Pretrained Diffusion Features},
  booktitle = {ICML Workshop: TerraBytes: Towards global datasets and models for Earth Observation (Spotlight)},
  year = {2025}
}
```
