---
title: 'Federated Learning over Hierarchical Wireless Networks: Training Latency Minimization
  via Submodel Partitioning'
authors:
- Wenzhi Fang
- Dong-Jun Han
- Christopher G Brinton
date: '2024-02-01'
publishDate: '2025-02-03T20:19:27.321087Z'
publication_types:
- article-journal
publication: '*IEEEACM Transactions on Networking*'
abstract: Hierarchical federated learning (HFL) has demonstrated promising scalability advantages over the traditional “star-topology” architecture-based federated learning (FL). However, HFL still imposes significant computation, communication, and storage burdens on the edge, especially when training a large-scale model over resource-constrained wireless devices. In this paper, we propose hierarchical independent submodel training (HIST), a new FL methodology that aims to address these issues in hierarchical cloud-edge-client networks. The key idea behind HIST is to divide the global model into disjoint partitions (or submodels) per round so that each group of clients (i.e., cells) is responsible for training only one partition of the model, reducing client-side computational/storage costs and overall communication load. We characterize the convergence behavior of HIST under mild assumptions, showing the impacts of several key attributes (e.g., submodel sizes, number of cells, edge and global aggregation frequencies) on the rate and stationarity gap. Building upon the theoretical results, we propose a submodel partitioning strategy to minimize the training latency depending on network resource availability (e.g., computation powers, data rate) and a target learning performance guarantee (i.e., through the convergence bound). We then demonstrate how HIST can be augmented with over-the-air computation (AirComp) to further enhance the efficiency of the model aggregation over the edge cells. Through numerical evaluations, we verify that HIST is able to save training time and communication costs by wide margins while achieving comparable accuracy as conventional HFL. Moreover, our experiments demonstrate that AirComp-assisted HIST provides further improvements in training latency over different channel conditions and system parameters.
image:
  filename: neural_partition.png
links:
  - name: arXiv
    url: https://arxiv.org/pdf/2310.17890v2
  - name: Code
    url: https://github.com/wenzhifang/HIST
---
