---
firstpage:
lastpage:
---

# Hammer

These datasets were generated with the [`AdroitHandHammer-v1`](https://robotics.farama.org/envs/adroit_hand/adroit_hammer/) environment, originally hosted in the [`hand_dapg`](https://github.com/aravindr93/hand_dapg) repository. The objective of the task is to introduce a nail in a board with a hammer tool using a 24-DoF robotic hand. This domain was selected to measure the effect of a narrow expert data distributions and human demonstrations on a sparse reward, high-dimensional robotic manipulation task.

There are three types of datasets, two from the original paper[1] (`human` and `expert`), and another one introduced in D4RL[2] (`cloned`).

```{toctree}
:hidden:
hammer/human.md
hammer/expert.md
hammer/cloned.md
```

## References

[1] Rajeswaran, Aravind, et al. ‘Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and Demonstrations’. CoRR, vol. abs/1709.10087, 2017, http://arxiv.org/abs/1709.10087.

[2] Fu, Justin, et al. ‘D4RL: Datasets for Deep Data-Driven Reinforcement Learning’. CoRR, vol. abs/2004.07219, 2020, https://arxiv.org/abs/2004.07219.

