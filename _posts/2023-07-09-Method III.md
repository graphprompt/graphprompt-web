---
title: Applying Meta-learning
categories:
- Method III

---
<div align="center">
<img src="/assets/alg.png" />
</div>

We introduce a meta-learning technique to learn more adaptive graph prompts for multi-task settings. Meta-learning is applied over multiple tasks to learn better prompts. This process involves constructing meta prompting tasks and updating the parameters of the tasks using a gradient descent method.

<!-- more -->To improve the learning stability,
we organize these tasks as multi-task episodes where each episode
contains batch tasks including node classification (“𝑛” for short),
edge classification (“ℓ” for short), and graph classification (“𝑔” for
short).

