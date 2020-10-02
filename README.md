# DQL-B-C-FrozenLake
<p>A new version of Deep Q-Learning designed for sparse reward environments and tested in a grid world.</p>
State-of-the-art methods for deep reinforcement learning have demonstrated the
ability to learn complex game strategies for Atari’s games, Chess, Go... Deep
Q-Learning was the first deep reinforcement learning method to outperform
the human level at some of Atari’s games, however, it performs poorly in
environments with sparse rewards or with the facility to die. In both cases, the
algorithm is not able to learn from low probability rewards.
In this project, a modified version of Deep-Q Learning which implements Deep
Q-Learning with Boltzmann Count-Based exploration (DQL-B-C) has been
developed. The algorithm has been tested and compared in a grid environment
with different grid sizes. The experiments demonstrate that DQL-B-C explores
better and learns more quickly.

