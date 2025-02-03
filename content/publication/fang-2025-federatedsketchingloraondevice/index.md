---
title: 'Federated Sketching LoRA: On-Device Collaborative Fine-Tuning of Large Language
  Models'
featured: true
authors:
- Wenzhi Fang
- Dong-Jun Han
- Liangqi Yuan
- Seyyedali Hosseinalipour
- Christopher G. Brinton
date: '2025-01-31'
publishDate: '2025-02-03T20:19:27.333711Z'
publication_types:
- manuscript
publication_short: ""
abstract: Fine-tuning large language models (LLMs) on devices is attracting increasing interest. Recent works have fused low-rank adaptation (LoRA) techniques with federated fine-tuning to mitigate challenges associated with device model sizes and data scarcity. Still, the heterogeneity of computational resources remains a critical bottleneck, while higher-rank modules generally enhance performance, varying device capabilities constrain LoRA's feasible rank range. Existing approaches attempting to resolve this issue either lack analytical justification or impose additional computational overhead, leaving a wide gap for an efficient and theoretically-grounded solution. To address these challenges, we propose federated sketching LoRA (FSLoRA), which leverages a sketching mechanism to enable devices to selectively update submatrices of global LoRA modules maintained by the server. By adjusting the sketching ratios, which determine the ranks of the submatrices on the devices, FSLoRA flexibly adapts to device-specific communication and computational constraints. We provide a rigorous convergence analysis of FSLoRA that characterizes how the sketching ratios affect the convergence rate. Through comprehensive experiments on multiple datasets and LLM models, we demonstrate FSLoRA's superior performance compared to various baselines.
image:
  filename: fslora.png
links:
- name: arXiv
  url: https://arxiv.org/abs/2501.19389
---