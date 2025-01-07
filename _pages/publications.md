---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

---

<!-- ## Publications-->

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="flex: 1; max-width: 300px; margin-right: 20px;">
    <img src="https://raw.githubusercontent.com/SKDDJ/picgoimgbed/main/202410181214510.jpg" alt="LoLDU Image Grid" style="width: 100%;">
  </div>
  <div style="flex: 2;">
    <h2 style="margin-top: 0;">LoLDU: Low-Rank Adaptation via Lower-Diag-Upper Decomposition for Parameter-Efficient Fine-Tuning</h2>
    <p><strong>Yujia Wu</strong>, Jiwei Wei, Yujia Wu, Ran Ran, Chengwei Sun, Shiyuan He, Yang Yang</p>
    <p><em>arXiv 2024</em></p>
    <div class="tldr-section">
      <details>
        <summary><strong>TL;DR</strong></summary>
        <div class="tldr-content">
          LoLDU introduces a novel Parameter-Efficient Fine-Tuning (PEFT) method that reduces trainable parameters by 2600 times compared to traditional methods, using Lower-Diag-Upper Decomposition for faster convergence and orthogonality, while maintaining performance across various datasets and models.
        </div>
      </details>
    </div>
    <p>[<a href="https://arxiv.org/abs/2410.13618">Paper</a>] [<a href="https://github.com/SKDDJ/LoLDU">Code</a>]</p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 20px;">
  <div style="flex: 1; max-width: 300px; margin-right: 20px;">
    <img src="https://raw.githubusercontent.com/SKDDJ/picgoimgbed/main/202409041312737.png" alt="DiffLoRA Image Grid" style="width: 100%;">
  </div>
  <div style="flex: 2;">
    <h2 style="margin-top: 0;">DiffLoRA: Generating Personalized Low-Rank Adaptation Weights with Diffusion</h2>
    <p>Yujia Wu, <strong>Yujia Wu</strong>, Jiwei Wei, Chengwei Sun, Yuyang Zhou, Yang Yang, Heng Tao Shen</p>
    <p><em>arXiv 2024</em></p>
    <div class="tldr-section">
      <details>
        <summary><strong>TL;DR</strong></summary>
        <div class="tldr-content">
          DiffLoRA leverages diffusion models to predict personalized low-rank adaptation weights, achieving efficient and identity-fidelity text-to-image generation without further training, by integrating these weights into the model during inference.
        </div>
      </details>
    </div>
    <p>[<a href="https://arxiv.org/pdf/2408.06740">Paper</a>] [<a href="https://github.com/SKDDJ/DiffLoRA_datasets">Code</a>]</p>
  </div>
</div>


<!-- {% include base_path %} -->

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
