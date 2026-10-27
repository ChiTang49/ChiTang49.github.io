---
permalink: /
title: ""
excerpt: "About Wenchao Jia"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am currently a master's student in Computer Technology at East China Normal University.

My research interests include **embodied AI**, **vision-language-action (VLA) models**, **large language models**, and **reinforcement learning**. My recent work focuses on self-evolving post-training, outcome-value-guided planning, and agentic code repair.

<span class="anchor" id="news"></span>

# News

- *2026.09*: Began my M.S. studies in Computer Technology at East China Normal University.

<span class="anchor" id="projects"></span>

# Selected Projects

## QueST VLA: Self-Evolving Post-Training with Outcome-Value-Guided Planning and Experience Reuse

[[Code]](https://github.com/ChiTang49/SelfEvoVLA)

A self-evolving framework for long-horizon robot manipulation that integrates policy optimization during training, experience selection during inference, and successful trajectory reuse.

- **Policy Optimization**: Improved VLA policies using multi-trajectory rollouts, leave-one-out advantage estimation, and PPO. The macro-average success rate across three LIBERO-Long tasks increased from 61.3% to **74.7% (+13.3 percentage points)**.
- **Outcome Value Model**: Designed a trajectory-level value model that combines context, current observations, and action-token features to predict the success probability of candidate action chunks and guide planning.
- **Experience Reuse**: Fed successful trajectories back into the policy prior. Across one policy-training seed and two evaluation seeds, the mean success rate of experience reuse combined with planning increased from 66% to **72%**.
- **Tech Stack**: Python, PyTorch, QueST, RLOO, PPO, LIBERO-Long.

## Interactive Code Repair with Qwen3.5-9B: SEED Online Policy Distillation and GSPO Sequence-Level Reinforcement Learning

A post-training framework combining SFT, online RL, and policy distillation to address coarse terminal rewards and long-horizon credit assignment in agentic code repair.

- **Supervised Fine-Tuning**: Fine-tuned Qwen3.5-9B with LoRA, increasing the repair success rate from 37.50% to **55.08%** and the valid-action rate from 89.36% to **99.92%**.
- **Online Reinforcement Learning**: Built an end-to-end pipeline for data generation, trajectory sampling, policy training, and unified evaluation with veRL and vLLM, enabling a test-driven Repair Agent with multi-turn interaction.
- **Sequence-Level Optimization**: At comparable strict repair success rates during training, GSPO reduced the average cross-round fluctuation in policy loss by approximately **17%**.
- **Tech Stack**: PyTorch, Transformers, vLLM, veRL, LoRA, GRPO, GSPO, SEED.

<span class="anchor" id="learning"></span>
# Learning & Notes

- **[Embodied AI](https://github.com/ChiTang49/Embodied-AI)**: Course notes, experiments, learning resources, and reflections on embodied AI.
- **[Agent Learning](https://github.com/ChiTang49/Agent-Learning)**: Learning notes and reflections on AI agents, agentic reinforcement learning, and LLM fundamentals.

<span class="anchor" id="honors"></span>
# Honors and Awards

- *2025.05*: Bronze Medal, CCPC Jiangsu Provincial Collegiate Programming Contest.
- *2025.05*: Silver Medal, National Final of the China Collegiate Computing Contest's Group Programming Ladder Tournament.

<span class="anchor" id="education"></span>
# Educations

- *2026.09 - Present*, Master, East China Normal University, Shanghai.
- *2022.09 - 2026.06*, Undergraduate, Jiangsu University of Science and Technology, Zhenjiang.
