---
permalink: /software/
title: "Software"
author_profile: true
---
Open-source code from my research. Each project links to its repository and to the paper it accompanies.

NS-Gym
======
Simulation environments and benchmarks for non-stationary Markov decision processes: schedulers and update functions change environment parameters at runtime, with wrappers for Gymnasium environments and baseline decision-making algorithms. It is the basis of the AAMAS 2026 competition on evaluating adaptive decision agents under non-stationarity.

```bash
pip install ns-gym
```

[Repository](https://github.com/scope-lab-vu/ns_gym) · [Documentation](https://nsgym.io/) · [Paper (NeurIPS 2025 Datasets & Benchmarks)](https://arxiv.org/abs/2501.09646) · MIT license

L-MAP
======
Latent Macro Action Planner: offline reinforcement learning that learns temporally extended macro-actions with a state-conditioned VQ-VAE and plans over them with Monte Carlo Tree Search, with training and evaluation scripts for D4RL and MuJoCo tasks.

```bash
conda create -n lmap python=3.10 -y && conda activate lmap
git clone https://github.com/BaitingLuo/L-MAP.git && cd L-MAP
pip install -r requirements.txt && pip install -e .
```

MuJoCo is set up separately; the repository README has the steps.

[Repository](https://github.com/BaitingLuo/L-MAP) · [Paper (ICLR 2025 Spotlight)](https://openreview.net/forum?id=pQsllTesiE) · MIT license

ANTI-CARLA
======
An adversarial testing framework for autonomous driving pipelines in the CARLA simulator: it generates challenging scenes and conditions to search for failures of a controller under test, evaluated with the Learning by Cheating and TransFuser controllers.

```bash
git clone https://github.com/scope-lab-vu/ANTI-CARLA.git && cd ANTI-CARLA
conda create -n carla-sampling python=3.7 -y && conda activate carla-sampling
pip install -r requirements.txt
```

Requires CARLA 0.9.10 and the controller weights; a Docker setup is included in the repository.

[Repository](https://github.com/scope-lab-vu/ANTI-CARLA) · [Paper (ITSC 2022)](https://arxiv.org/abs/2208.06309)
