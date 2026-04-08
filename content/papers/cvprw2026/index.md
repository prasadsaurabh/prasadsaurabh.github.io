---
title: >-
  DINO Soars: DINOv3 for Open-Vocabulary Semantic Segmentation of Remote Sensing Imagery
date: '2026-06-01'
authors:
  - Ryan Faulkenberry
  - Saurabh Prasad
publication: >-
  IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (MORSE)
tags:
  - "CVPRW MORSE 2026"
  - "Open-Vocabulary Segmentation"
  - "Foundation Models"
  - "GeoAI"
  - "DINOv3"
summary: >-
  **CVPRW MORSE 2026** · We present CAFe-DINO, an open-vocabulary semantic segmentation model for remote sensing imagery that requires zero RS-domain fine-tuning. Leveraging DINOv3's strong latent representations with cost aggregation and training-free upsampling, CAFe-DINO achieves state-of-the-art performance on key RS segmentation datasets, outperforming methods fine-tuned on RS data.
links:
  - name: Code
    url: 'https://github.com/rfaulk/DINO_Soars'
cover:
  image: "cover.png"
  alt: "DINO Soars paper figure"
  relative: true
  hiddenInList: false
---

---

##### Abstract

The remote sensing (RS) domain suffers from a lack of densely labeled datasets, which are costly to obtain. Models that can segment RS imagery without supervised fine-tuning are therefore highly valuable. Recently, DINOv3 surpassed state-of-the-art RS foundation models on the GEO-bench segmentation benchmark without pre-training on RS data. We leverage this to form an open-vocabulary semantic segmentation (OVSS) model for RS imagery, free of RS-domain fine-tuning. Our model, **CAFe-DINO** (Cost Aggregation + Feature Upsampling with DINO), exploits the strong OVSS performance of DINOv3 for RS imagery via cost aggregation and training-free upsampling of text-image similarity scores. The robust latent representations of the DINOv3 backbone eliminate the need for fine-tuning on RS imagery; we instead fine-tune on a RS-targeted subset of COCO-Stuff. CAFe-DINO achieves state-of-the-art performance on key RS segmentation datasets, outperforming OVSS methods fine-tuned on RS data.

---

##### Download

- [Code](https://github.com/rfaulk/DINO_Soars)

---

##### Citation

```BibTeX
@InProceedings{Faulkenberry2026DINOSoars,
  author = {Faulkenberry, Ryan and Prasad, Saurabh},
  title = {DINO Soars: DINOv3 for Open-Vocabulary Semantic Segmentation of Remote Sensing Imagery},
  booktitle = {Proceedings of the IEEE/CVF CVPR Workshops (MORSE)},
  year = {2026}
}
```
