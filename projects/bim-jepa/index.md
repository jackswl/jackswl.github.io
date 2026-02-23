---
layout: project
title: "BIM-JEPA: Self-supervised learning for BIM element classification using a joint embedding predictive architecture"
badge: "Automation in Construction (Under Review)"
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
    # url: https://doi.org/10.1016/j.aei.2025.103676
    icon: fa-regular fa-file
  - text: "Model Weight"
    url: "#"
    icon: fa-solid fa-database   # or: fas fa-database (if using FA v5)
  - text: Training Code
    url: https://github.com/jackswl/bim-jepa
    icon: fab fa-github
  - text: Inference Demo
    url: https://github.com/jackswl/bim-jepa
    icon: fab fa-github
  # - text: BibTeX
  #   url: /assets/bibtex/fine-tuning.bib
  #   icon: fa-regular fa-file
---

<!-- lightweight “more info soon” notice -->
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
      <!-- Write your abstract here (3–5 sentences). -->
    The development of scalable models for automated Building Information Modeling (BIM) element classification is hindered by the reliance on supervised learning, which requires expensive and laborious manual data annotation. This paper introduces BIM-JEPA, a foundation model that leverages a Joint Embedding Predictive Architecture for self-supervised pre-training on unlabeled 3D point cloud representations of individual BIM elements. By predicting the latent representations of masked regions of element geometry, BIM-JEPA learns semantically rich features that achieve competitive accuracy on a downstream classification task, outperforming existing supervised methods without heavy data augmentation, while excelling in data-scarce scenarios. This paper mitigates the data annotation bottleneck and establishes a path toward developing a foundation model for BIM geometry, enabling more scalable, data-efficient, and generalizable representation learning in the Architecture, Engineering, and Construction domain.
    </span>
  </div>
</div>

{% comment %}
<!--this is for table 1-->
<div class="row justify-content-center mt-md-1">
<div class="col-md-12 mb-md-5 bg-light rounded">
    <div class="row mt-md-3">
        <div class="col-md-12 mb-md-2 align-self-center">
        <h2 class="title">
            <span style="font-size: 0.8em;"><b>Addressing Qualitative Rules in Automated Code Compliance</b></span>
        </h2>
        <span style="font-size: 0.95em;">
            <!-- Summarize metrics and qualitative examples. -->
            Traditional NLP for ACC tends to rely on explicitly defined terms and NER-style extraction, which makes it ineffective for qualitative clauses with ambiguous interpretations; implicit assumptions (e.g., “shall be ventilated”, “overlooking”) often require expert knowledge, and cross-code context is hard to maintain without heavy manual pre-processing. To address this gap, we fine-tune an LLM on a domain-specific dataset spanning multiple Singapore codes of practice (Table 1), distinguishing quantitative rules that contain explicit numerical constraints from qualitative rules expressed descriptively. In the training set, 384/656 (58.54%) are quantitative and 272/656 (41.46%) are qualitative; the test set is similarly balanced.
        </span>
        </div>
        <div class="col-md-12 mb-md-3 align-self-center">
        <figure class="img-thumbnail mb-0">
            <img src="/assets/projects/fine-tuning/table1.png" alt="Results" class="img-fluid">
        </figure>
        </div>
    </div>
</div>
</div>


<!-- Method -->
<div class="row justify-content-center mt-md-1">
<div class="row mt-md-3">
    <div class="col-md-12 mb-md-2 align-self-center">
    <h2 class="title">
        <span style="font-size: 0.8em;"><b>Fine-tuning Mistral 7B Instruct Model</b></span>
    </h2>
    <span style="font-size: 0.95em;">
        <!-- Summarize metrics and qualitative examples. -->
        describe...
    </span>
    </div>
    <div class="col-md-12 mb-md-3 align-self-center">
    <figure class="img-thumbnail mb-0">
        <img src="/assets/projects/fine-tuning/method.png" alt="Results" class="img-fluid">
    </figure>
    </div>
</div>
</div>


<!-- Results -->
<div class="row justify-content-center mt-md-1">
  <div class="col-md-12 mb-md-5 bg-light rounded">
    <div class="row mt-md-3">
      <div class="col-md-12 mb-md-2 align-self-center">
        <h2 class="title">
          <span style="font-size: 0.8em;"><b>Results</b></span>
        </h2>
        <span style="font-size: 0.95em;">
          <!-- Summarize metrics and qualitative examples. -->
          describe....
        </span>
      </div>
      <div class="col-md-12 mb-md-3 align-self-center">
        <figure class="img-thumbnail mb-0">
          <img src="/assets/projects/fine-tuning/fig8.png" alt="Results" class="img-fluid">
        </figure>
      </div>
    </div>
  </div>
</div>

<div class="row justify-content-center mt-md-1">
<div class="row mb-md-4 mt-md-4">
    <div class="col-md-6 align-self-center">
    <figure class="img-thumbnail mb-0">
        <img src="/assets/projects/fine-tuning/fig9.png" alt="Overview" class="img-fluid">
    </figure>
    </div>
    <div class="col-md-6 align-self-center">
    <h2 class="title">
        <span style="font-size: 0.8em;"><b>Effect of RAG on low F3 scores</b></span>
    </h2>
    <span style="font-size: 0.95em;">
        <!-- Explain the problem and why it matters for AEC. -->
        This figure highlights the increase in F3 score achieved with the RAG prompt compared to the standard prompt at the 10th epoch, showing that the additional context in the RAG prompt significantly improves F3 scores, particularly for generated scripts with initially low F3 scores.
    </span>
    </div>
  </div>
</div>

<!--this is for table 2-->
<div class="row justify-content-center mt-md-1">
<div class="col-md-12 mb-md-5 bg-light rounded">
<div class="row mt-md-3">
    <div class="col-md-12 mb-md-2 align-self-center">
    <h2 class="title">
        <span style="font-size: 0.8em;"><b>Quantitative vs Qualitative Rule Types</b></span>
    </h2>
    <span style="font-size: 0.95em;">
        <!-- Summarize metrics and qualitative examples. -->
        Describe....
    </span>
    </div>
    <div class="col-md-12 mb-md-3 align-self-center">
    <figure class="img-thumbnail mb-0">
        <img src="/assets/projects/fine-tuning/table2.png" alt="Results" class="img-fluid">
    </figure>
    </div>
  </div>
</div>
</div>
{% endcomment %}