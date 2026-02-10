---
title: 'Joint Continual Learning of Local Language Models and Cloud Offloading Decisions with Budget Constraints'
featured: true
authors:
- Evan Chen*
- Wenzhi Fang*
- Shiqiang Wang
- Christopher Brinton
date: '2026-01-29'
publishDate: '2026-01-29T00:00:00Z'
publication_types:
- manuscript
publication_short: "ArXiv"
publication: '*arXiv preprint*'
abstract: Locally deployed Small Language Models (SLMs) must continually support diverse tasks under strict memory and computation constraints, making selective reliance on cloud Large Language Models (LLMs) unavoidable. Regulating cloud assistance during continual learning is challenging, as naive reward-based reinforcement learning often yields unstable offloading behavior and exacerbates catastrophic forgetting as task distributions shift. We propose DA-GRPO, a dual-advantage extension of Group Relative Policy Optimization that incorporates cloud-usage constraints directly into advantage computation, avoiding fixed reward shaping and external routing models. This design enables the local model to jointly learn task competence and collaboration behavior, allowing cloud requests to emerge naturally during post-training while respecting a prescribed assistance budget. Experiments on mathematical reasoning and code generation benchmarks show that DA-GRPO improves post-switch accuracy, substantially reduces forgetting, and maintains stable cloud usage compared to prior collaborative and routing-based approaches.
image:
  filename: dagrpo-framework.png
links:
- name: arXiv
  url: https://arxiv.org/abs/2602.00166
- name: PDF
  url: https://arxiv.org/pdf/2602.00166.pdf
---
