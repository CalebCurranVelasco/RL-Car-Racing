# Reinforcement Learning for Autonomous Car Racing

This repository contains a reinforcement learning (RL) project aimed at training an agent for autonomous car racing in the 'CarRacing-v0' environment. We implemented this project using PyTorch and the Stable Baselines3 library. The agent utilizes convolutional neural networks (CNN) as the policy architecture ('CnnPolicy') to process environment observations and make control decisions.

## Model Training and Evaluation

1. Trained the PPO (Proximal Policy Optimization) algorithm with 500,000 timesteps of interaction with the environment, achieving autonomous racing behavior.
2. Employed DummyVecEnv to interface the Gym environment with the model, allowing for efficient vectorized training and evaluation.
3. Conducted model evaluation by simulating 10 episodes, with the trained agent making driving decisions based on its learned policy, and visualized the results using the Gym rendering capabilities.

## Codebase Management and Model Persistence

1. Organized the project by creating a structured directory with a logging system ('Training/Logs') to monitor training progress using TensorBoard.
2. Saved the trained PPO model for future use and loaded it for evaluation, demonstrating the ability to persist and reuse trained reinforcement learning agents.
3. Developed a clear understanding of the environment through random exploration during training and applied the learned policy during testing for better control and performance.

## Video of the Car after training



https://github.com/CalebCurranVelasco/RL-Car-Racing/assets/118134327/353e517f-8ef7-4c80-9e78-a65d9ad81d57

