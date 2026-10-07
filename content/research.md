---
title: "Research"
description: "Research areas of the MLSP Laboratory at the University of Houston"
---

The MLSP Laboratory at the University of Houston develops machine learning and signal processing methods that make high-dimensional imaging more transferable, label-efficient, and scientifically useful. Across geospatial imaging (GeoAI) and biomedicine, we study how foundation models, multimodal representation learning, and human-guided AI can support robust analysis in data-scarce real-world settings. Our lab is supported by **NASA, NSF, NIH, DoD, and Amazon AWS**.

---

## GeoAI — Geospatial Image Analysis

<figure class="research-fig">
  <img src="/images/research/geoai.jpg" alt="Open-vocabulary segmentation maps of remote sensing scenes produced by CAFe-DINO" loading="lazy">
  <figcaption>Open-vocabulary segmentation of remote sensing imagery with DINOv3, from <a href="/papers/cvprw2026/">DINO Soars</a> (CVPRW MORSE 2026).</figcaption>
</figure>

Modern geospatial imaging through active and passive sensing modalities — including multispectral, hyperspectral, LiDAR, and SAR data acquired from satellites and aircraft — presents major opportunities and important challenges. High dimensionality, limited labeled data, and cross-sensor variability require machine learning methods that generalize across sensors, regions, resolutions, and environmental conditions rather than overfit to a single benchmark.

**Current research directions:**
- Foundation models and large vision models for geospatial semantic segmentation and scene understanding
- Efficient adaptation of foundation models to new sensors, spectral bands, and geographies
- Active learning and human-in-the-loop workflows for annotation efficiency
- Sensor-agnostic domain generalization across imaging conditions
- Multimodal learning across sensor, scale, and time

**Recent workshops chaired:**
- [GeoCV](https://sites.google.com/view/geocv/) at WACV — Computer Vision for Geospatial Image Analysis (2025, 2026)
- [MORSE](https://sites.google.com/view/cvpr-morse) at CVPR — Foundation Models in Remote Sensing (2025, 2026)

**Recent papers:**
- [DINO Soars: DINOv3 for Open-Vocabulary Semantic Segmentation of Remote Sensing Imagery](/papers/cvprw2026/) — CVPRW MORSE 2026
- [Gradient-Based Active Learning for Geospatial Semantic Segmentation with Large Vision Models](/papers/faulkenberry2026/) — WACVW GeoCV 2026
- [UniDiff: Parameter-Efficient Adaptation of Diffusion Models for Land Cover Classification](/papers/hu2025unidiff/) — WACV 2026
- [Advancing Efficient Vision Foundation Models for Analysis of Multispectral Imagery](/papers/liu2026/) — IEEE JSTARS 2026

**Sponsors:** NASA, NSF, DoD, Amazon AWS

---

## AI in Biomedicine

<figure class="research-fig">
  <img src="/images/research/biomed.jpg" alt="mViSE multiplex visual search engine pipeline and example brain-tissue retrievals" loading="lazy">
  <figcaption>Query-driven analysis of multiplex brain-tissue images, from <a href="/papers/huang2026mvise/">mViSE</a> (Scientific Reports 2026).</figcaption>
</figure>

Modern biomedical imaging systems — including FTIR microscopy and highly multiplexed immunofluorescence (IF) microscopy — generate high-resolution, high-dimensional measurements that capture rich biological structure across tissues. These data create new opportunities for understanding tissue organization, cellular phenotypes, and organ-level structure, while also demanding learning methods that can operate effectively with sparse annotations and heterogeneous imaging conditions.

**Current research directions:**
- Representation learning and phenotype discovery in multiplexed tissue imaging
- Visual prompting and incremental learning for biomedical segmentation
- Spatial proteomics and tissue atlas construction
- Deep learning for FTIR spectral microscopy analysis

**Recent papers:**
- [mViSE: A Visual Search Engine for Analyzing Multiplex IHC Brain Tissue Images](/papers/huang2026mvise/) — Scientific Reports 2026

**Sponsors:** NIH, NSF

---

## Datasets & Code

Some of the datasets we have released include:

- **IEEE GRSS IADF 2013 Data Fusion Contest** — hyperspectral imagery and a LiDAR-derived digital surface model over the University of Houston campus: [dataset page](https://machinelearning.ee.uh.edu/2013-ieee-grss-data-fusion-contest)
- **IEEE GRSS IADF 2018 Data Fusion Contest** — multispectral LiDAR and hyperspectral data over Houston: [IEEE DataPort](https://ieee-dataport.org/open-access/2018-ieee-grss-data-fusion-challenge-fusion-multispectral-lidar-and-hyperspectral-data)

Code:

- **DINO Soars / CAFe-DINO** — training and evaluation code for open-vocabulary segmentation of remote sensing imagery: [github.com/rfaulk/DINO_Soars](https://github.com/rfaulk/DINO_Soars)
- **mViSE** — open-source QuPath plug-in for query-driven analysis of multiplex brain-tissue images: see the [paper](/papers/huang2026mvise/)

---

## Open Positions

We are recruiting PhD students in foundation models, active learning, multi-sensor geospatial image analysis, and biomedical image analysis. See [Join the lab](/join/) for how to apply.
