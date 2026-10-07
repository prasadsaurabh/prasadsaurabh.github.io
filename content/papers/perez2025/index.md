---
title: >-
  Layer Optimized Spatial Spectral Masked Autoencoder for Semantic Segmentation of Hyperspectral Imagery
date: '2025-02-01'
featured: false   # has its own page (linked from Team) but is not listed on the Papers page
authors:
  - Aaron Perez
  - Saurabh Prasad
publication: >-
  IEEE/CVF Winter Conference on Applications of Computer Vision Workshops (GeoCV)
tags:
  - "Hyperspectral"
  - "Masked Autoencoders"
  - "GeoAI"
summary: >-
  We propose LO-SST, a Layer-Optimized Spatial-Spectral Transformer that combines structured layer pruning with self-supervised masked-autoencoder pretraining, achieving competitive hyperspectral segmentation accuracy while significantly reducing computational demands.
links:
  - name: CVF
    url: 'https://openaccess.thecvf.com/content/WACV2025W/GeoCV/html/Perez_Layer_Optimized_Spatial_Spectral_Masked_Autoencoder_for_Semantic_Segmentation_of_WACVW_2025_paper.html'
---

---

## Abstract {.label}

Hyperspectral imaging (HSI) captures detailed spectral data across numerous contiguous bands, offering critical insights for applications such as environmental monitoring, agriculture, and urban planning. However, the high dimensionality of HSI data poses significant challenges for traditional deep learning models, necessitating more efficient solutions. In this paper, we propose the Layer-Optimized Spatial-Spectral Transformer (LO-SST), a refined version of the Spatial-Spectral Transformer (SST) that incorporates structured layer pruning to reduce computational complexity while maintaining robust performance. LO-SST leverages self-supervised pretraining with a Masked Autoencoder (MAE) framework, enabling the model to effectively learn spatial and spectral dependencies even in scenarios with limited labeled data. The use of separate spatial and spectral positional embeddings further enhances the model's ability to capture intricate relationships within hyperspectral data. Our experiments show that LO-SST achieves competitive segmentation accuracy while significantly reducing computational demands compared to traditional models. The effectiveness of random masking over alternative strategies during pretraining is also demonstrated, underscoring its ability to preserve critical image features. These results highlight the potential of LO-SST as an efficient and scalable solution for hyperspectral image segmentation, particularly in resource-constrained applications.

---

## Citation {.label}

```BibTeX
@InProceedings{Perez_2025_WACV,
  author = {Perez, Aaron and Prasad, Saurabh},
  title = {Layer Optimized Spatial Spectral Masked Autoencoder for Semantic Segmentation of Hyperspectral Imagery},
  booktitle = {Proceedings of the Winter Conference on Applications of Computer Vision (WACV) Workshops},
  month = {February},
  year = {2025},
  pages = {599-607}
}
```
