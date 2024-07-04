# Taxi-V3

This repository contains solutions to OpenAI Gym's Taxi-v3 problem using two different approaches: brute force and Q-learning. The Taxi-v3 problem is a classic reinforcement learning task where the goal is to drive a taxi to pick up and drop off passengers at designated locations on a grid.

## Brute Force Solution
The `brute_force.ipynb` notebook demonstrates a brute force method which involves exploring all possible actions and states to find an optimal solution. While this approach can be informative, it is computationally expensive and impractical for larger or more complex problems.

## Q-Learning Solution
The `q_learning.ipynb` notebook demonstrates a Q-learning approach to solving the Taxi-v3 problem. Q-learning is a type of reinforcement learning algorithm that learns an optimal policy by interacting with the environment and updating value estimates based on received rewards.

## Results
Both notebooks include detailed explanations and visualizations to help you understand the problem-solving process. The Q-learning solution, in particular, demonstrates how the learned policy improves over time and eventually converges to an optimal strategy.