---
layout: default
---

<div class="profile-header">
    <div class="profile-info">
        <h1>{{ site.author }}</h1>
        <p>I am a third year Ph.D. student in the Department of Civil and Environmental Engineering at the National University of Singapore, advised by <a href="https://scholar.google.com/citations?user=m9LF49sAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Prof. Justin Ker-Wei Yeoh</a>. My primary research focuses on spatial intelligence for BIM, exploring how geometric world models and joint-embedding approaches can train machines to reason about buildings in 3D space. Earlier on, I worked on leveraging and improving large language models and information retrieval techniques to automate code compliance for building regulations, with the goal of enhancing the design process in the architecture, engineering, and construction industry. I am always on the lookout for challenging opportunities that push the boundaries of knowledge and possibility. </p>
        <div class="profile-links">
            <a href="mailto:jackswl@u.nus.edu">Email</a> / 
            <a href="/assets/pdf/Jack_Resume_latest.pdf" target="_blank" rel="noopener noreferrer">CV</a> /
            <a href="https://scholar.google.com/citations?user=Pmr3ET4AAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a> / 
            <a href="https://github.com/jackswl" target="_blank" rel="noopener noreferrer">GitHub</a> /
            <a href="https://www.linkedin.com/in/jackswl/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        </div>
    </div>
    <div class="profile-picture">
        <img src="/assets/images/profile.jpg" alt="Jack Wei Lun Shi">
    </div>
</div>

<div class="research-section">
<h2>Research</h2>

<table class="research">
    <tr>
        <td class="research-thumb">
            <video src="/assets/images/thumb_honeycomb.mp4" poster="/assets/images/thumb_honeycomb.png" autoplay muted loop playsinline></video>
        </td>
        <td class="research-text">
            <a href="{{ '/honeycomb/' | relative_url }}"><span class="papertitle">Honeycomb: Constant-Size Scene Memory Representation for Video World Models</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Kaichen Zhou</span>, <span class="author">Haoyu Chen</span>, <span class="author">Yufeng Weng</span>, <span class="author">Keane Ong</span>, <span class="author">Ruojin Cai</span>, <span class="author">Hang Hua</span>, <span class="author">Justin Ker-Wei Yeoh</span>, <span class="author">Mengyu Wang</span>
            <br>
            <em>arXiv</em>, 2026
            <br>
            <a href="{{ '/honeycomb/' | relative_url }}">project page</a> /
            <a href="https://arxiv.org/abs/2609.37690" target="_blank" rel="noopener noreferrer">paper</a> /
            <a href="https://github.com/kaichen-z/honeycomb" target="_blank" rel="noopener noreferrer">code</a>
            <p>Honeycomb is a video world model whose HexMemory stores the scene in six fixed-size feature planes, keeping long-horizon generation consistent when revisiting regions while memory stays constant in size.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb">
            <video src="/assets/images/thumb_bimjepafm.mp4" poster="/assets/images/thumb_bimjepafm.png" autoplay muted loop playsinline></video>
        </td>
        <td class="research-text">
            <a href="{{ '/bim-jepa-fm/' | relative_url }}"><span class="papertitle">Toward generalizable foundation models for 3D BIM geometry using a joint embedding predictive architecture</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Wawan Solihin</span>, <span class="author">Yufeng Weng</span>, <span class="author">Houhao Liang</span>, <span class="author">Yimin Zhao</span>, <span class="author">Leong Hien Poh</span>, <span class="author">Justin Ker-Wei Yeoh</span>
            <br>
            <em>Automation in Construction</em>, 2026
            <br>
            <a href="{{ '/bim-jepa-fm/' | relative_url }}">project page</a> /
            <a href="https://doi.org/10.1016/j.autcon.2026.107169" target="_blank" rel="noopener noreferrer">paper</a>
            <p>A point cloud foundation model for 3D BIM geometry that generalizes across object classification, segmentation, and zero-shot tasks such as shape retrieval and anomaly detection.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb"><img src="/assets/images/thumb_bivqa.png" alt="BIVQA damage localization"></td>
        <td class="research-text">
            <a href="https://doi.org/10.1016/j.autcon.2026.107125" target="_blank" rel="noopener noreferrer"><span class="papertitle">Visual question answering for bridge damage inspection using a multi-modal large language model</span></a>
            <br>
            <span class="author">Minghao Dang</span>, <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Yapeng Guo</span>, <span class="author">Hongtao Cui</span>, <span class="author">Justin Ker-Wei Yeoh</span>, <span class="author">Shunlong Li</span>
            <br>
            <em>Automation in Construction</em>, 2026
            <br>
            <a href="https://doi.org/10.1016/j.autcon.2026.107125" target="_blank" rel="noopener noreferrer">paper</a>
            <p>BIVQA, built on a multi-modal large language model, answers natural-language questions about bridge inspection images while simultaneously localizing the damage.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb">
            <video src="/assets/images/thumb_bimjepa.mp4" poster="/assets/images/thumb_bimjepa.png" autoplay muted loop playsinline></video>
        </td>
        <td class="research-text">
            <a href="{{ '/bim-jepa/' | relative_url }}"><span class="papertitle">Self-supervised learning for BIM element classification using a joint embedding predictive architecture</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Wawan Solihin</span>, <span class="author">Yufeng Weng</span>, <span class="author">Yimin Zhao</span>, <span class="author">Leong Hien Poh</span>, <span class="author">Justin Ker-Wei Yeoh</span>
            <br>
            <em>Automation in Construction</em>, 2026
            <br>
            <a href="{{ '/bim-jepa/' | relative_url }}">project page</a> /
            <a href="https://doi.org/10.1016/j.autcon.2026.107075" target="_blank" rel="noopener noreferrer">paper</a>
            <p>By predicting the latent representations of masked regions of unlabeled BIM element point clouds, the pre-trained model outperforms supervised methods on element classification, especially when labeled data is scarce.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb"><img src="/assets/images/thumb_p4ir.png" alt="P4IR tree edit distance heatmap"></td>
        <td class="research-text">
            <a href="https://arxiv.org/abs/2606.22402" target="_blank" rel="noopener noreferrer"><span class="papertitle">Reinforcement learning to improve large language model-based automated code compliance systems</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Minghao Dang</span>, <span class="author">Wawan Solihin</span>, <span class="author">Leong Hien Poh</span>, <span class="author">Justin Ker-Wei Yeoh</span>
            <br>
            <em>arXiv</em>, 2026
            <br>
            <a href="https://arxiv.org/abs/2606.22402" target="_blank" rel="noopener noreferrer">paper</a>
            <p>P4IR combines supervised fine-tuning with GRPO reinforcement learning to generate more accurate code skeletons from building regulations, outperforming leading frontier LLMs in a zero-shot setting.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb"><img src="/assets/images/thumb_attribution.png" alt="Attribution maps for FFT, LoRA and QLoRA"></td>
        <td class="research-text">
            <a href="https://arxiv.org/abs/2604.15589" target="_blank" rel="noopener noreferrer"><span class="papertitle">LLM attribution analysis across different fine-tuning strategies and model scales for automated code compliance</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Minghao Dang</span>, <span class="author">Wawan Solihin</span>, <span class="author">Justin Ker-Wei Yeoh</span>
            <br>
            <em>International Conference on Computing in Civil and Building Engineering (ICCCBE)</em>, 2026
            <br>
            <a href="https://arxiv.org/abs/2604.15589" target="_blank" rel="noopener noreferrer">paper</a>
            <p>Perturbation-based attribution shows that full fine-tuning yields more focused attribution patterns over building regulation text than LoRA and QLoRA, and that larger LLMs learn to prioritize numerical constraints and rule identifiers.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb"><img src="/assets/images/thumb_buildthemis.png" alt="BuildThemis framework"></td>
        <td class="research-text">
            <a href="{{ '/buildthemis/' | relative_url }}"><span class="papertitle">Fine-tuning a large language model for automated code compliance of building regulations</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Wawan Solihin</span>, <span class="author">Justin Ker-Wei Yeoh</span>
            <br>
            <em>Advanced Engineering Informatics</em>, 2025
            <br>
            <a href="{{ '/buildthemis/' | relative_url }}">project page</a> /
            <a href="https://doi.org/10.1016/j.aei.2025.103676" target="_blank" rel="noopener noreferrer">paper</a>
            <p>BuildThemis combines a fine-tuned LLM with retrieval-augmented generation to turn building regulations into draft compliance-checking scripts that experts can readily refine.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb"><img src="/assets/images/thumb_hle.png" alt="Humanity's last exam"></td>
        <td class="research-text">
            <a href="https://agi.safe.ai/" target="_blank" rel="noopener noreferrer"><span class="papertitle">Humanity's last exam</span></a>
            <br>
            <span class="author">Long Phan</span>, <span class="author">Alice Gatti</span>, <span class="author">Ziwen Han</span>, <span class="author">Nathaniel Li</span>, ..., <span class="author"><strong>Jack Wei Lun Shi</strong></span>, ..., <span class="author">Alexandr Wang</span>, <span class="author">Dan Hendrycks</span>
            <br>
            <em>Nature</em>, 2026
            <br>
            <a href="https://agi.safe.ai/" target="_blank" rel="noopener noreferrer">project page</a> /
            <a href="https://doi.org/10.1038/s41586-025-09962-4" target="_blank" rel="noopener noreferrer">paper</a>
            <p>A benchmark of 2,500 expert-written questions at the frontier of human knowledge, on which state-of-the-art LLMs still score poorly.</p>
        </td>
    </tr>

    <tr>
        <td class="research-thumb"><img src="/assets/images/thumb_cbrom.png" alt="CBROM poster"></td>
        <td class="research-text">
            <a href="/assets/pdf/Poster_NUSIMS.pdf" target="_blank" rel="noopener noreferrer"><span class="papertitle">Component-based reduced order modeling for heat transfer in thermal fin and data server</span></a>
            <br>
            <span class="author"><strong>Jack Wei Lun Shi</strong></span>, <span class="author">Xiang Zhao</span>, <span class="author">My Ha Dao</span>
            <br>
            <em>International Workshop on Reduced Order Methods</em>, 2023 (poster)
            <br>
            <a href="/assets/pdf/Poster_NUSIMS.pdf" target="_blank" rel="noopener noreferrer">poster</a>
            <p>Decomposing a thermal fin and a data server into reusable components yields reduced order models that match high-fidelity FEA results while running 26 and 6.5 times faster.</p>
        </td>
    </tr>
</table>
</div>
