---
layout: project
title: "Self-supervised learning for BIM element classification using a joint embedding predictive architecture"
badge: Automation in Construction 2026
teaser: /assets/projects/bim-jepa/teaser.png
permalink: /bim-jepa/

authors:
  - name: Jack Wei Lun Shi
    # url: https://jackswl.github.io
    aff: 1
  - name: Wawan Solihin
    aff: [1, 2]
  - name: Yufeng Weng
    aff: 1
  - name: Yimin Zhao
    aff: 1
  - name: Leong Hien Poh
    aff: 1
  - name: Justin Ker-Wei Yeoh
    aff: 1

affiliations:
  - id: 1
    name: Department of Civil and Environmental Engineering, National University of Singapore
  - id: 2
    name: Research and Innovation, NovaCITYNETS Pte.Ltd.


links:
  - text: Paper
    url: https://doi.org/10.1016/j.autcon.2026.107075
    icon: fa-regular fa-file
  - text: "Model Weight"
    url: https://github.com/jackswl/bim-jepa#pretrained-models
    icon: fa-solid fa-database   # or: fas fa-database (if using FA v5)
  - text: Training Code
    url: https://github.com/jackswl/bim-jepa
    icon: fab fa-github
  - text: Inference Demo
    url: https://github.com/jackswl/bim-jepa/blob/main/BIM_JEPA_demo_2.ipynb
    icon: fab fa-github
  # - text: BibTeX
  #   url: /assets/bibtex/fine-tuning.bib
  #   icon: fa-regular fa-file
---

<!-- lightweight release notice -->
<div class="row justify-content-center">
  <div class="col-md-10 col-lg-8">
    <div class="alert alert-info text-center" role="alert">
      The paper is published in Automation in Construction. Training code, model weights, and an inference demo are available via the links above. Thank you for your interest!
    </div>
  </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-12 mb-md-5">
    <h2 class="title text-center mt-md-4 mb-md-3">
      <span style="font-size: 0.8em;"><strong>Abstract</strong></span>
    </h2>
    <span style="font-size: 0.95em;">
      <!-- Write your abstract here (3–5 sentences). -->
    The development of scalable models for automated Building Information Modeling (BIM) element classification is hindered by the reliance on supervised learning, which requires expensive and laborious manual data annotation. This paper introduces a pre-trained model that leverages a Joint Embedding Predictive Architecture for self-supervised learning on unlabeled 3D point cloud representations of individual BIM elements. By predicting the latent representations of masked regions of element geometry, the proposed model learns rich geometric features that achieve competitive accuracy on a downstream classification task, outperforming existing supervised methods without heavy data augmentation, while excelling in data-scarce scenarios. This paper mitigates the data annotation bottleneck and establishes a path toward developing a foundation model for BIM geometry, enabling more scalable, data-efficient, and generalizable representation learning in the Architecture, Engineering, and Construction domain.
    </span>
  </div>
</div>

