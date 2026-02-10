---
title: 'TAP: Two-Stage Adaptive Personalization of Multi-task and Multi-Modal Foundation
  Models in Federated Learning'
featured: true
authors:
- Seohyun Lee
- Wenzhi Fang
- Dong-Jun Han
- Seyyedali Hosseinalipour
- Christopher G. Brinton
date: '2025-09-01'
publishDate: '2025-09-01'
publication_types:
- manuscript
publication_short: "ArXiv"
publication: '*arXiv preprint*'
abstract: Federated Learning (FL), despite demonstrating impressive capabilities in the training of multiple models in a decentralized manner, has been shown to produce a final model not necessarily well-suited to the needs of each client. While extensive work has been conducted on how to create tailored personalized models, called Personalized Federated Learning (PFL), less attention has been given to personalization via fine-tuning of foundation models with multi-task and multi-modal properties. To address this gap, we propose TAP (Two-Stage Adaptive Personalization), which (i) leverages mismatched model architectures between the clients and server to selectively conduct replacement operations when it benefits a client's local tasks and (ii) engages in post-FL knowledge distillation for capturing beneficial general knowledge without compromising personalization. We also introduce the first convergence analysis of the server model under its modality-task pair architecture. Through extensive experiments, we demonstrate the effectiveness of our proposed algorithm across a variety of datasets and tasks in comparison to a multitude of baselines.
image:
  filename: tap.png
links:
- name: arXiv
  url: https://arxiv.org/abs/2509.26524
- name: Code
  url: https://github.com/lee3296/TAP
---
