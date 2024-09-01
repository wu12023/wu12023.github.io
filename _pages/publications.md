---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Recent Publication

**DiffLoRA: Generating Personalized Low-Rank Adaptation Weights with Diffusion**

*Yujia Wu, Yiming Shi, Jiwei Wei, Chengwei Sun, Yuyang Zhou, Yang Yang, Heng Tao Shen*

**Abstract:** Personalized text-to-image generation has gained significant attention for its capability to generate high-fidelity portraits of specific identities conditioned on user-defined prompts. Existing methods typically involve test-time fine-tuning or instead incorporating an additional pre-trained branch. However, these approaches struggle to simultaneously address the demands of efficiency, identity fidelity, and preserving the model's original generative capabilities. In this paper, we propose DiffLoRA, a novel approach that leverages diffusion models as a hypernetwork to predict personalized low-rank adaptation (LoRA) weights based on the reference images. By integrating these LoRA weights into the text-to-image model, DiffLoRA achieves personalization during inference without further training. Additionally, we propose an identity-oriented LoRA weight construction pipeline to facilitate the training of DiffLoRA. By utilizing the dataset produced by this pipeline, our DiffLoRA consistently generates high-performance and accurate LoRA weights. Extensive evaluations demonstrate the effectiveness of our method, achieving both time efficiency and maintaining identity fidelity throughout the personalization process.

[Read the full paper](https://arxiv.org/pdf/2408.06740)


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
