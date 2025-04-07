## SC3000 CartPole Assignment
In this project, we trained 3 different types of reinforcement learning agents to play the CartPole task and evaluated them.

**Breakdown:**

Isha: Monte Carlo Agent Training and Evaluation

Kwang Chen: Q-Learning Agent Training and Evaluation

Cherng Khai: Deep Q-Network (DQN) Agent Training and Evaluation
Our Process

Monte Carlo, Q-Learning and DQN are 3 different types of Reinforcement Learning algorithms covered in this course. Specifically, they are Model-Free RL algorithms, which means that they figure out the best actions without needing a model of the environment.

Monte Carlo is a model-free RL algorithm that learns by sampling experiences from the environment. Q-Learning, on the other hand, is an algorithm that learns by bootstrapping, which means it updates value estimates by leveraging both immediate and predicted future rewards. Q-Learning uses a Q-Table to store the expected cumulative reward for each state-action pair (Q-values), while DQN replaces the Q-table with a neural network that learns to approximate Q-values.

In this assignment, we compared the capabilities of the three algorithms.
