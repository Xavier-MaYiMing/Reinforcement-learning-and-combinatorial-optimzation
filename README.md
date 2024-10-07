# Deep Learning and Reinforcement Learning in Combinatorial Optimization

**Regular updates on deep learning, reinforcement learning, and their applications to combinatorial optimization problems.**  
This repository provides insights into various reinforcement learning algorithms and their implementations, accompanied by clean and well-structured code.

## Covered Topics

### Reinforcement Learning Algorithms

- [x] **[Deep Q Network (DQN)](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/DQN.ipynb)**  
  Implementation of the foundational DQN algorithm, which uses Q-learning with deep neural networks for decision making.

- [x] **[Double DQN (DDQN)](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/DDQN.ipynb)**  
  A more stable version of DQN that reduces overestimation bias in the Q-value.

- [x] **[Dueling DQN](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/Dueling%20DQN.ipynb)**  
  An enhancement to DQN that separates value and advantage functions, improving the network's performance.

- [x] **[REINFORCE](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/REINFORCE.ipynb)**  
  A Monte Carlo policy gradient method for directly optimizing policy performance.

- [x] **[REINFORCE with Baseline](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/REINFORCE_with_baseline.ipynb)**  
  A variation of REINFORCE that reduces variance by subtracting a learned baseline value.

- [x] **[Actor-Critic](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/actor-critic.ipynb)**  
  Combines the benefits of value-based and policy-based methods by learning both the policy and value functions.

- [x] **[Advantage Actor-Critic (A2C)](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/A2C.ipynb)**  
  A synchronous version of Actor-Critic that uses the advantage function to optimize policy.

- [x] **[Proximal Policy Optimization (PPO)](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/PPO.ipynb)**  
  A state-of-the-art policy gradient method that ensures stable learning by limiting policy updates.

### Reinforcement Learning for Combinatorial Optimization Problems

- [] **[LSTM and Pointer Network, A2C, Greedy & Sampling for TSP]()**  
  **Reference:** Bello, I., Pham, H., Le, Q. V., et al. Neural combinatorial optimization with reinforcement learning. arXiv preprint arXiv:1611.09940, 2016.

- [x] **[Multi-Head Self-Attention, REINFORCE, Active Search for TSP](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/DRL4TSP%20(Attention%2C%20REINFORCE%2C%20active%20search).ipynb)**  
  **Reference:** Bello, I., Pham, H., Le, Q. V., et al. Neural combinatorial optimization with reinforcement learning. arXiv preprint arXiv:1611.09940, 2016.
Active search starts from scratch using DRL to solve individual problems by continuously learning and adjusting the model during inference.

- [x] **[Multi-Head Self-Attention, REINFORCE, Greedy & Sampling for TSP](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/DRL4TSP%20(Attention%2C%20REINFORCE).ipynb)**  
  **Reference:** Kool, W., Van Hoof, H., Welling, M. Attention, learn to solve routing problems! arXiv preprint arXiv:1803.08475, 2018.

- [x] **[Multi-Head Self-Attention, REINFORCE with Rollout Baseline, Greedy & Sampling for TSP](https://github.com/Xavier-MaYiMing/Reinforcement-learning-and-combinatorial-optimzation/blob/main/DRL4TSP%20(Attention%2C%20REINFORCE%20with%20Rollout%20Baseline).ipynb)**  
  **Reference:** Kool, W., Van Hoof, H., Welling, M. Attention, learn to solve routing problems! arXiv preprint arXiv:1803.08475, 2018.
The rollout baseline is a more effective strategy compared to the moving average baseline.


Stay tuned for more updates!
