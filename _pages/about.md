---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am an AI researcher. I develop efficient world models for autonomy, turn them into efficient world action models, and post-train world action models.

I received my Ph.D. in Computer Science from Vanderbilt University in 2026, advised by [Prof. Abhishek Dubey](https://scopelab.ai/) and closely collaborating with [Dr. Ayan Mukhopadhyay](https://www.ayanmukhopadhyay.com/). My dissertation, *Adaptive and Scalable AI-Driven Decision-Making for Cyber-Physical Systems*, developed decision-making methods that account for uncertainty, changing environments, and the limits of learned models, together with scalable planning over learned temporal abstractions. My research sits at the intersection of reinforcement learning, planning, and learned world models, with a focus on agents that act under uncertainty, adapt when the environment changes, and stay safe while doing so.

Prior to my doctoral studies, I earned my M.S. in Computer Engineering from Northwestern University, where I worked with [Prof. Qi Zhu](http://zhulab.ece.northwestern.edu/team.html) on securing connected and autonomous vehicles. My master's thesis on Sybil Attack Detection in VANET received the [Northwestern Best MS Computer Engineering Thesis Award](https://www.mccormick.northwestern.edu/electrical-computer/news-events/news/articles/2021/2021-ece-annual-awards-winners.html). I completed my B.S. in Computer Engineering with a dual degree in Computer Science from Rensselaer Polytechnic Institute. My research has been published at ICLR, NeurIPS, AAMAS, ICAPS, and ICCPS, and I have been honored with awards including the [Vanderbilt Provost's Pathbreaking Discovery Award](https://gradschool.vanderbilt.edu/student-resources/student-awards/) and the [Vanderbilt C.F. Chen Best Paper Runner-Up Award](https://www.linkedin.com/posts/institute-for-software-integrated-systems-vanderbilt-university_engineering-future-technology-activity-7194334972625784832-R1nS/).

Services
======
### Conference & Journal Reviewer
- International Conference on Learning Representations (ICLR 2026/2027)
- The ACM Web Conference (WWW 2026)
- Neural Information Processing Systems (NeurIPS 2025/2026)
- Knowledge Discovery and Data Mining (KDD 2025/2026/2027)
- International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2025)
- International Joint Conference on Neural Networks (IJCNN 2025/2026)
- International Conference on Neural Information Processing (ICONIP 2024)
- IEEE International Transportation Systems Conference (ITSC 2022)
- IEEE Transactions on Intelligent Vehicles
- ACM Transactions on Computing for Healthcare
- IEEE Internet of Things Journal

### Technical Program Committee
- Artifact Evaluation Committee, ACM/IEEE International Conference on Cyber-Physical Systems (ICCPS 2024/2025/2026)
- International Conference on Data Mining and Big Data (DMBD 2024)


Research
======
I build decision-making systems that stay reliable when the world doesn't hold still. My work combines reinforcement learning, planning, and learned world models, and spans the following areas:

### Planning with World Models and Learned Temporal Abstractions

- Latent Macro Action Planner (L-MAP): learns temporally extended macro-actions with a state-conditioned VQ-VAE and plans over them with Monte Carlo Tree Search, reaching state-of-the-art results on high-dimensional continuous control with low decision latency (ICLR 2025 Spotlight, top 5.1%).
- In-context planning with latent temporal abstractions: an agent trained offline that adapts online under stochastic, partially observable dynamics (under review).
- ARGO: a sample-efficient world action model that treats model uncertainty asymmetrically, optimistic for exploration and pessimistic for policy updates (developed during a research internship at Siemens; under review).

### Decision Making in Non-Stationary Environments

- Adaptive Monte Carlo Tree Search: safe exploration and online adaptation to changing dynamics in model-based reinforcement learning (AAMAS 2024; Vanderbilt C.F. Chen Best Paper Runner-Up).
- NS-Gym: open-source simulation environments and benchmarks for non-stationary Markov decision processes (NeurIPS 2025 Datasets & Benchmarks).

### Decision Making under Partial Observability

- Co-authored work on temporal belief representations and observation adaptation for POMDPs (NeurIPS 2025, ICAPS 2025) and on real-time UAV search and rescue with Shrinking POMCP (ICAA 2024).

### Runtime Safety Assurance of Autonomous Vehicles

- Dynamic Simplex: improves performance without compromising safety by planning with multiple generative models in dynamic environments (ICCPS 2023).
- Risk-aware scene sampling for high-risk scenario generation (ICAA 2022) and ANTI-CARLA, an adversarial testing framework for autonomous vehicles in CARLA (ITSC 2022).

### Securing Connected and Autonomous Vehicles

- A credibility-enhanced temporal graph convolutional network for Sybil attack detection in connected-vehicle networks, and a dual cyber-physical blockchain framework for large-scale vehicular networks (IEEE IV 2021).

[Find the publications for each of these projects.](publications)
