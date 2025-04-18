---
title: Self-supervised OCT image denoising with slice-to-slice registration and reconstruction
authors:
- Shijie Li
- Guido Gerig
date: '2024-01-01'
doi: 10.1109/ISBI56570.2024.10635645
publishDate: '2025-04-10T19:27:13.177416Z'
publication_types:
- paper-conference
publication: '*2024 IEEE 21st International Symposium on Biomedical Imaging (ISBI)*'
url_pdf: 'https://arxiv.org/abs/2311.15167'
url_code: 'https://github.com/CJLee94/Slice2Slice.git'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://arxiv.org/abs/2308.09835'
# url_video: 'https://youtube.com'
abstract: Strong speckle noise is inherent to optical coherence tomography (OCT) imaging and represents a significant obstacle for accurate quantitative analysis of retinal structures which is key for advances in clinical diagnosis and monitoring of disease. Learning-based self-supervised methods for structure-preserving noise reduction have demonstrated superior performance over traditional methods but face unique challenges in OCT imaging. The high correlation of voxels generated by coherent A-scan beams undermines the efficacy of self-supervised learning methods as it violates the assumption of independent pixel noise. We conduct experiments demonstrating limitations of existing models due to this independence assumption. We then introduce a new end-to-end self-supervised learning framework specifically tailored for OCT image denoising, integrating slice-by-slice training and registration modules into one network. An extensive ablation study is conducted for the proposed approach. Comparison to previously published self-supervised denoising models demonstrates improved performance of the proposed framework, potentially serving as a preprocessing step towards superior segmentation performance and quantitative analysis.
tags:
  - Self Supervised Learning, Image Generative Model, Image Restoration, 3D Image Processing
image:
  caption: 'Image from Paper'
  focal_point: ''
  preview_only: false
featured: true

---
