---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Preprints

1. P. Clark Di Leoni, **L. Lu**, C. Meneveau, G. E. Karniadakis, & T. A. Zaki. [DeepONet prediction of linear instability waves in high-speed boundary layers](https://arxiv.org/abs/2105.08697). *arXiv preprint arXiv:2105.08697*, 2021.
1. B. Deng, Y. Shin, **L. Lu**, Z. Zhang, & G. E. Karniadakis. [Convergence rate of DeepONets for learning operators arising from advection-diffusion equations](https://arxiv.org/abs/2102.10621). *arXiv preprint arXiv:2102.10621*, 2021.
1. **L. Lu**, R. Pestourie, W. Yao, Z. Wang, F. Verdugo, & S. G. Johnson. [Physics-informed neural networks with hard constraints for inverse design](https://arxiv.org/abs/2102.04626). *arXiv preprint arXiv:2102.04626*, 2021.
