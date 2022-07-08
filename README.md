# Soft Actor-Critic (SAC)
This repository contains a clean and minimal implementation of Soft Actor-Critic (SAC) algorithm in Pytorch, for continuous action spaces.

SAC is a state-of-the-art model-free deep RL algorithm for continuous action spaces. It adopts an off-policy actor-critic approach and uses stochastic policies. SAC uses the maximum entropy formulation to achieve exploration.

You can find more details about how SAC works in my blog post [here](https://adi3e08.github.io/posts/2021/12/soft-actor-critic/).

## References
* "Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor", Haarnoja et al. [Link](https://arxiv.org/abs/1801.01290).
* "Soft Actor-Critic Algorithms and Applications", Haarnoja et al. [Link](https://arxiv.org/abs/1812.05905).

## Tested on

* Cartpole Swingup ([Deepmind Control Suite](https://github.com/deepmind/dm_control/tree/master/dm_control/suite)) - Swing up and balance an unactuated pole by applying forces to a cart at its base.

<p align="center">
<img src=".media/sac_cartpole_swingup.png" width="50%" height="50%">
</p>

<p align="center">
<img src=".media/sac_cartpole_swingup.gif" width="50%" height="50%">
</p>

* Reacher Hard ([Deepmind Control Suite](https://github.com/deepmind/dm_control/tree/master/dm_control/suite)) - Control a two-link robotic arm to reach a randomized target location.

<p align="center">
<img src=".media/sac_reacher_hard.png" width="50%" height="50%">
</p>

<p align="center">
<img src=".media/sac_reacher_hard.gif" width="50%" height="50%">
</p>

* [Bipedal Walker](https://gym.openai.com/envs/BipedalWalker-v2/) (OpenAI Gym) - Train a bipedal robot to walk.

<p align="center">
<img src=".media/sac_bipedal_walker.png" width="50%" height="50%">
</p>

<p align="center">
<img src=".media/sac_bipedal_walker.gif" width="50%" height="50%">
</p>
 
