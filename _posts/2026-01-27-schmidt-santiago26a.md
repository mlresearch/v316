---
title: Uncertainty-Aware Ensemble Segmentation of Breast Cancer Tissue Microarrays
booktitle: Proceedings of the MICCAI Workshop on Computational Pathology
year: '2025'
month: 0
volume: '316'
series: Proceedings of Machine Learning Research
publisher: PMLR
abstract: "Breast cancer Tissue Microarrays (TMAs) offer a high-throughput platform
  for studying tumor morphology and biomarker expression. We present an automated
  deep learning pipeline for semantic segmentation of Hematoxylin and Eosin (H&E)-stained
  breast cancer TMAs, integrating ensemble U-Net architectures with ResNet encoders
  and Monte Carlo Dropout (MCDO) for uncertainty estimation. A robust pre-processing
  workflow addresses illumination artifacts, staining variability, and tissue detection.
  Multiple U-Net models were trained using distinct loss functions to address class
  imbal\x02ance and feature  iversity. Predictions were combined via soft voting,
  emulating consensus among pathologists. Uncertainty was quantified using MCDO across
  ensemble outputs, enhancing reliability and interpretability. Our pipeline outperforms
  similar methods such as WeGleNet (mIoU = 0.4368) and HistoSegNet (mIoU = 0.5505),
  achieving a mean IoU of 0.58 $\\pm$ 0.11 and Dice Score of 0.66 $\\pm$ 0.10. Calibration
  analysis shows superior alignment of standard deviation–based uncertainty estimates
  with actual prediction errors (UCE = 0.085 $\\pm$ 0.033). This pipeline effectively
  segments complex histopathological structures and flags ambiguous regions for review,
  supporting downstream biomarker discovery and clinical interpretation."
layout: inproceedings
issn: 2640-3498
id: schmidt-santiago26a
tex_title: Uncertainty-Aware Ensemble Segmentation of Breast Cancer Tissue Microarrays
firstpage: 39
lastpage: 51
page: 39-51
order: 39
cycles: false
bibtex_editor: Studer, Linda and Ciompi, Francesco and Khalili, Nadieh and Faryna,
  Khrystyna and Faryna, Khrystyna and Yeong, Joe and Lau, Mai Chan and Chen, Hao and
  Liu, Ziyi and Brattoli, Biagio
editor:
- given: Linda
  family: Studer
- given: Francesco
  family: Ciompi
- given: Nadieh
  family: Khalili
- given: Khrystyna
  family: Faryna
- given: Khrystyna
  family: Faryna
- given: Joe
  family: Yeong
- given: Mai Chan
  family: Lau
- given: Hao
  family: Chen
- given: Ziyi
  family: Liu
- given: Biagio
  family: Brattoli
bibtex_author: Schmidt-Santiago, Lucia and Kinakh, Roman and Carreras-Salinas, Sergio
  and Guerrero-Aspizcua, Sara and R\'{i}os-Mu\~{n}oz, Gonzalo R. and Mu\~{n}oz-Barrutia,
  Arrate
author:
- given: Lucia
  family: Schmidt-Santiago
- given: Roman
  family: Kinakh
- given: Sergio
  family: Carreras-Salinas
- given: Sara
  family: Guerrero-Aspizcua
- given: Gonzalo R.
  family: Ríos-Muñoz
- given: Arrate
  family: Muñoz-Barrutia
date: 2026-01-27
address:
container-title: Proceedings of the MICCAI Workshop on Computational Pathology
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 1
  - 27
pdf: https://raw.githubusercontent.com/mlresearch/v316/main/assets/schmidt-santiago26a/schmidt-santiago26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
