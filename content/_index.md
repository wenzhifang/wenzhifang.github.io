---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within content/authors/)
      username: admin
      text: |-
        Hello and welcome! I am currently a third-year PhD student at Purdue University, majoring in Electrical and Computer Engineering, advised by [Prof. Christopher G. Brinton](https://scholar.google.com/citations?user=vWmHA5MAAAAJ&hl=en). Previous to that, I obtained my master’s degree in Electrical and Computer Engineering at ShanghaiTech University under the supervision of [Prof. Yong Zhou](https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=8bpAwKcAAAAJ&sortby=pubdate) and [Prof. Yuanming Shi](https://scholar.google.com/citations?user=362l5HAAAAAJ&hl=en). In addition, from Aug. 2022 to Feb. 2023, I served as a research intern in the Optimization for Machine Learning lab at KAUST led by [Prof. Peter Richtárik](https://richtarik.org/index.html).
      button:
        text: Download CV
        url: uploads/resume.pdf
  - block: markdown
    id: focus
    content:
      title: Research Pulse
      text: |-
        My work focuses on LLM post-training and Multi-agent LLM systems:
        - **RL-based Post Training**, developing reinforcement learning frameworks for adaptive control and collaboration of multi-agent LLM systems.
        - **Efficient On-deive LLM fine-tuning**, enabling distributed on-device LLM fine-tuning under computation, communication, and memory constraints.
        - **Federated learning and optimization**, designing efficient and convergent algroithm for distributed model training.
    design:
      columns: '1'
  - block: markdown
    id: experience
    content:
      title: Experience & training
      text: |-
        **PhD, Purdue University — Electrical & Computer Engineering** (Aug 2023 — Present)  
        Working on LLM post-training and reasoning, with an emphasis on RL-based alignment, agent collaboration, and communication-efficient fine-tuning for distributed on-device LLM systems.

        **Research Intern, Optimization for Machine Learning Lab, KAUST** (Aug 2022 — Feb 2023)  
        Working on optimization theory and its applications on machine learning, especially primal-dual algorithm. 

        **MS, ShanghaiTech University — Electrical & Computer Engineering** (2020 — 2023)  
        Working on optimization theory and its applications on communication system.
    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: News
      text: |-
        - **Feb 2026:** Ou work on DA-GRPO, a budget-aware reinforcement learning framework enabling continual learning in device–cloud LLM systems is now on ArXiv.
        - **Sept 2025:** Our work on device–cloud collaborative LLM reasoning, introducing an RL-based unified framework for adaptive routing and post-training is now on ArXiv.
        - **Jan 2025:** Our work on Federated Sketching LoRA (FSLoRA), a communication-efficient framework for collaborative on-device LLM fine-tuning under heterogeneous resource constraints is now on ArXiv.
        - **Sept 2024:** Our paper on hierarchical federated learning with multi-timescale gradient correction (MTGC) has been accepted to NeurIPS 2024.
        - **Aug 2023:** Joined Purdue as a PhD student after completing my MS at ShanghaiTech.
      subtitle: ''
    design:
      columns: '1'
  - block: markdown
    id: papers
    content:
      title: Selected works
      text: |-
        <div class="selected-works">

        <a class="selected-work-card" href="/publication/chen-2026-joint-continual/">
          <div class="selected-work-media">
            <img src="/publication/chen-2026-joint-continual/dagrpo-framework_hu_80a33ca626868d19.webp"
                 alt="Joint Continual Learning of Local Language Models and Cloud Offloading Decisions with Budget Constraints">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              Joint Continual Learning of Local Language Models and Cloud Offloading Decisions with Budget Constraints
            </h3>
            <p class="selected-work-summary">
              Continual post-training framework (DA-GRPO) that jointly learns on-device SLM policies and budget-aware cloud offloading decisions to reduce forgetting while respecting assistance constraints.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                Evan Chen*, <strong>Wenzhi Fang*</strong>, Shiqiang Wang, Christopher Brinton
              </div>
              <div class="selected-work-venue">
                <em>arXiv preprint</em> · January 2026
              </div>
            </div>
          </div>
        </a>

        <a class="selected-work-card" href="/publication/fang-2025-devicecloudcollaboration/">
          <div class="selected-work-media">
            <img src="/publication/fang-2025-devicecloudcollaboration/Overview_v5_hu_888c9a1f07e25b37.webp"
                 alt="Bridging On-Device and Cloud LLMs for Collaborative Reasoning: A Unified Methodology for Local Routing and Post-Training">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              Bridging On-Device and Cloud LLMs for Collaborative Reasoning: A Unified Methodology for Local Routing and Post-Training
            </h3>
            <p class="selected-work-summary">
              RL-based framework that enables on-device LLMs to decide when to invoke cloud models, jointly learning routing and post-training to balance accuracy and compute.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                <strong>Wenzhi Fang</strong>, Dong-Jun Han, Liangqi Yuan, Evan Chen, Christopher G. Brinton
              </div>
              <div class="selected-work-venue">
                <em>arXiv preprint</em> · September 2025
              </div>
            </div>
          </div>
        </a>

        <a class="selected-work-card" href="/publication/lee-2025-tap/">
          <div class="selected-work-media">
            <img src="/publication/lee-2025-tap/tap_hu_674d7ee1775d55d7.webp"
                 alt="TAP: Two-Stage Adaptive Personalization of Multi-task and Multi-Modal Foundation Models in Federated Learning">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              TAP: Two-Stage Adaptive Personalization of Multi-task and Multi-Modal Foundation Models in Federated Learning
            </h3>
            <p class="selected-work-summary">
              Personalization algorithm for multi-task, multi-modal foundation models that combines architecture-aware replacement with post-FL knowledge distillation.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                Seohyun Lee, <strong>Wenzhi Fang</strong>, Dong-Jun Han, Seyyedali Hosseinalipour, Christopher G. Brinton
              </div>
              <div class="selected-work-venue">
                <em>arXiv preprint</em> · September 2025
              </div>
            </div>
          </div>
        </a>

        <a class="selected-work-card" href="/publication/fang-2025-federatedsketchingloraondevice/">
          <div class="selected-work-media">
            <img src="/publication/fang-2025-federatedsketchingloraondevice/fslora_hu_8194dc94648cf45.webp"
                 alt="Federated Sketching LoRA: On-Device Collaborative Fine-Tuning of Large Language Models">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              Federated Sketching LoRA: On-Device Collaborative Fine-Tuning of Large Language Models
            </h3>
            <p class="selected-work-summary">
              Communication-efficient framework that uses sketching to adapt LoRA ranks per device, enabling collaborative on-device LLM fine-tuning under heterogeneous resources.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                <strong>Wenzhi Fang</strong>, Dong-Jun Han, Liangqi Yuan, Seyyedali Hosseinalipour, Christopher G. Brinton
              </div>
              <div class="selected-work-venue">
                <em>arXiv preprint</em> · January 2025
              </div>
            </div>
          </div>
        </a>

        <a class="selected-work-card" href="/publication/fang-2024-hierarchical/">
          <div class="selected-work-media">
            <img src="/publication/fang-2024-hierarchical/correction_dongjun_hu_e7f6e53c83253a93.webp"
                 alt="Hierarchical Federated Learning with Multi-Timescale Gradient Correction">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              Hierarchical Federated Learning with Multi-Timescale Gradient Correction
            </h3>
            <p class="selected-work-summary">
              Multi-timescale gradient correction method that stabilizes hierarchical FL across client and group levels, with convergence guarantees robust to data heterogeneity.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                <strong>Wenzhi Fang</strong>, Dong-Jun Han, Evan Chen, Shiqiang Wang, Christopher G. Brinton
              </div>
              <div class="selected-work-venue">
                <em>NeurIPS 2024</em> · September 2024
              </div>
            </div>
          </div>
        </a>

        <a class="selected-work-card" href="/publication/fang-2025-federated/">
          <div class="selected-work-media">
            <img src="/publication/fang-2025-federated/neural_partition_hu_77cb6237b1937f84.webp"
                 alt="Federated Learning over Hierarchical Wireless Networks: Training Latency Minimization via Submodel Partitioning">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              Federated Learning over Hierarchical Wireless Networks: Training Latency Minimization via Submodel Partitioning
            </h3>
            <p class="selected-work-summary">
              HIST framework that partitions large models into submodels across cells to reduce computation, storage, and communication while meeting convergence guarantees.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                <strong>Wenzhi Fang</strong>, Dong-Jun Han, Christopher G. Brinton
              </div>
              <div class="selected-work-venue">
                <em>IEEE/ACM Transactions on Networking</em> · February 2024
              </div>
            </div>
          </div>
        </a>

        <a class="selected-work-card" href="/publication/fang-2022-communication/">
          <div class="selected-work-media">
            <img src="/publication/fang-2022-communication/zeroth_order_hu_829e5fd3c7248efa.webp"
                 alt="Communication-efficient stochastic zeroth-order optimization for federated learning">
          </div>
          <div class="selected-work-body">
            <h3 class="selected-work-title">
              Communication-efficient stochastic zeroth-order optimization for federated learning
            </h3>
            <p class="selected-work-summary">
              FedZO algorithm for derivative-free federated optimization, with AirComp-assisted variant to preserve convergence under noisy wireless aggregation.
            </p>
            <div class="selected-work-meta">
              <div class="selected-work-authors">
                <strong>Wenzhi Fang</strong>, Ziyi Yu, Yuning Jiang, Yuanming Shi, Colin N. Jones, Yong Zhou
              </div>
              <div class="selected-work-venue">
                <em>IEEE Transactions on Signal Processing</em> · January 2022
              </div>
            </div>
          </div>
        </a>

        </div>
    design:
      columns: '1'
  - block: markdown
    id: service
    content:
      title: Academic Services
      text: |-
        ### Conference Reviewer
        - [Advances in Neural Information Processing Systems (NeurIPS)](https://neurips.cc/)
        - [International Conference on Machine Learning (ICML)](https://icml.cc/)
        - [International Conference on Learning Representations (ICLR)](https://iclr.cc/Conferences/2025)
        - [International Conference on Artificial Intelligence and Statistics (AISTATS)](https://aistats.org/aistats2025/)
        - [IEEE International Conference on Computer Communications (INFOCOM)](https://infocom2024.ieee-infocom.org/)

        ### Journal Reviewer
        - [Transactions on Machine Learning Research (TMLR)](https://jmlr.org/tmlr/)
        - [IEEE Transactions on Signal Processing (TSP)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=78)
        - [IEEE Transactions on Wireless Communications (TWC)](https://www.comsoc.org/publications/journals/ieee-twc)
        - [IEEE Transactions on Communications (TCOM)](https://www.comsoc.org/publications/journals/ieee-tcom)
        - [IEEE Transactions on Mobile Computing (TMC)](https://www.computer.org/csdl/journal/tm)
        - [IEEE Internet of Things Journal (IoT-J)](https://ieee-iotj.org/)
        - [IEEE Transactions on Machine Learning in Communications and Networking (TMLCN)](https://www.comsoc.org/publications/journals/ieee-tmlcn)
    design:
      columns: '1'
---
