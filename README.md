# Control-FA-with-Reinforcement-learning
# Deep Reinforcement Learning Projects

Welcome to my Deep Reinforcement Learning Projects repository! This collection of projects explores various aspects of reinforcement learning, from policy evaluation to function approximation and control. Each project focuses on a specific reinforcement learning problem and provides practical insights and solutions. Below, you'll find an overview of each project:

## 1: Semi-gradient TD(0) with State Aggregation
In this project, we delve into implementing semi-gradient TD(0) with state aggregation in an environment with a large state space. The primary goal is policy evaluation, where we aim to accurately estimate state values under a given fixed policy. You'll learn how to:

- Implement semi-gradient TD(0) with function approximation using state aggregation.
- Use supervised learning approaches to approximate value functions.
- Compare the impact of different resolutions of state aggregation and witness how function approximation speeds up learning through generalization.

## 2: Semi-gradient TD with Neural Network
Building on the previous proejct, this project introduces semi-gradient TD with a simple neural network for policy evaluation in the 500-State Randomwalk environment. You'll implement:

- Stochastic gradient descent for state-value prediction.
- Semi-gradient TD with a neural network and the Adam algorithm.
- A comparison of performance between semi-gradient TD with a neural network and semi-gradient TD with tile-coding.

## 3: Sarsa Algorithm with Tile Coding
In this project , we transition to the control setting and implement the Sarsa algorithm using tile coding. You'll explore different settings for tile coding to see their effect on the agent's performance. The environment in focus is the Mountain Car task, where an underpowered car must reach the top of a hill.

## 4: Softmax Actor-Critic Agent
This project introduces the softmax actor-critic agent on a continuing task using the average reward formulation. You'll learn to parameterize the policy as a function and approximate the gradient of the objective for actor updates. Additionally, you'll update the critic using differential TD error. The task involves swinging up a pendulum and maintaining its upright position.


Feel free to explore each project folder to find detailed implementations, code, and explanations. These projects offer a comprehensive introduction to deep reinforcement learning concepts and applications. Happy learning and experimenting with the exciting world of reinforcement learning!
## Credits
All credits go to the "Prediction and Control with Function Approximation" course created by University of Alberta on Coursera.
