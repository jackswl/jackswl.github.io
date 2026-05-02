---
layout: project
title: "Generalizable foundation models for 3D BIM geometry with a joint embedding predictive architecture"
badge: "Under Review"
teaser: /assets/projects/bim-jepa-fm/teaser.png
permalink: /bim-jepa-fm/

authors:
  - name: Jack Wei Lun Shi
    # url: https://jackswl.github.io
    aff: 1
  - name: Wawan Solihin
    aff: [1, 2]
  - name: Yufeng Weng
    aff: 1
  - name: Houhao Liang
    aff: 3
  - name: Yimin Zhao
    aff: 1
  - name: Leong Hien Poh
    aff: 1
    break: true
  - name: Justin Ker-Wei Yeoh
    aff: 1

affiliations:
  - id: 1
    name: Department of Civil and Environmental Engineering, National University of Singapore
  - id: 2
    name: Research and Innovation, NovaCITYNETS Pte.Ltd.
  - id: 3
    name: CNRS@CREATE, 1 Create Way, CREATE Tower, Singapore

links:
  - text: Paper
    # url:
    icon: fa-regular fa-file
  - text: "Model Weight"
    url: "#"
    icon: fa-solid fa-database
  - text: Training Code
    url: "https://github.com/jackswl/bim-jepa-fm"
    icon: fab fa-github
  - text: Inference Demo
    url: "#"
    icon: fab fa-github
---

<!-- lightweight "more info soon" notice -->
<div class="row justify-content-center">
  <div class="col-md-10 col-lg-8">
    <div class="alert alert-info text-center" role="alert">
      More details, including all training code and model weights, will be released upon acceptance of the paper. Thank you for your interest!
    </div>
  </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-12 mb-md-5">
    <h2 class="title text-center mt-md-4 mb-md-3">
      <span style="font-size: 0.8em;"><strong>Abstract</strong></span>
    </h2>
    <span style="font-size: 0.95em;">
      <!-- Write your abstract here. -->
      The adoption of artificial intelligence in the Architecture, Engineering, and Construction domain is hindered by a reliance on task-specific models that fail to generalize across diverse geometric applications. To address this limitation, this paper introduces a point cloud-based foundation model for 3D Building Information Modeling (BIM) geometry, pre-trained via a Latent-Euclidean Joint Embedding Predictive Architecture on individual BIM objects. By enforcing predictive consistency between global object context and local topological details within a regularized latent space, the proposed model extracts robust semantic features while suppressing low-level geometric noise. Extensive evaluations demonstrate the generalizability of the learned representations across multiple downstream tasks, achieving competitive performance in standard and fine-grained object classification, semantic segmentation via transfer learning, out-of-distribution part segmentation of computer-aided design objects, and zero-shot tasks including shape retrieval and clash detection. These results establish BIM-JEPA++ as a foundation model that facilitates diverse applications for 3D BIM geometry.
    </span>
  </div>
</div>
