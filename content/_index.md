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
        **PhD Candidate, Purdue University — Electrical & Computer Engineering** (Aug 2023 — Present)  
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
  - block: collection
    id: papers
    content:
      title: Selected works
      archive:
        enable: false
      count: 10
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: liang
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
