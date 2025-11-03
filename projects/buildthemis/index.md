---
layout: project
title: Fine-tuning a large language model for automated code compliance of building regulations
badge: Advanced Engineering Informatics 2025
teaser: /assets/projects/fine-tuning/teaser.png
permalink: /buildthemis/

authors:
  - name: Jack Wei Lun Shi
    # url: https://jackswl.github.io
    aff: 1
  - name: Wawan Solihin
    aff: [1, 2]
  - name: Justin Ker-Wei Yeoh
    aff: 1

affiliations:
  - id: 1
    name: Department of Civil and Environmental Engineering, National University of Singapore
  - id: 2
    name: Research and Innovation, NovaCITYNETS Pte.Ltd.


links:
  - text: Paper
    url: https://doi.org/10.1016/j.aei.2025.103676
    icon: fa-regular fa-file
  # - text: Code
  #   url: https://github.com/your/repo
  #   icon: fab fa-github
  # - text: BibTeX
  #   url: /assets/bibtex/fine-tuning.bib
  #   icon: fa-regular fa-file
---

<div class="row justify-content-center">
  <div class="col-md-12 mb-md-5">
    <h2 class="title text-center mt-md-4 mb-md-3">
      <span style="font-size: 0.8em;"><strong>Abstract</strong></span>
    </h2>
    <span style="font-size: 0.95em;">
      <!-- Write your abstract here (3–5 sentences). -->
      In the Architecture, Engineering, and Construction (AEC) industry, the interpretation and conversion of building rules into a computer-processable format for automated compliance checking systems are crucial for improving the design process. Yet, current systems and research on rule interpretation either demand extensive and timeconsuming expert-induced intervention, or rely on hard-coded pattern matching with limited applicability. To address these limitations, this paper introduces BuildThemis, a framework integrating a large language model fine-tuned on a real-world rule interpretation dataset with a Retrieval-Augmented Generation (RAG) mechanism. BuildThemis serves as a code-assistance tool that delivers structured draft scripts that experts can readily refine. The RAG technique grounds the fine-tuned LLM using an external code knowledge base, achieving a higher CodeBERTScore compared to non-RAG code generation approaches. Results demonstrate that the BuildThemis framework enhances the rule interpretation process by capturing latent concepts within rule-script pairs across various codes of practice and generating semantically similar scripts compared to the reference scripts. This approach to automating rule interpretation emphasizes generalization and reusability of rules, enabling the efficient conversion of textual regulatory documents into computable formats.
    </span>
  </div>
</div>


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