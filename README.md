# RL-Gridworld-Q-Learning
A beginner friendly Gridworld reinforcement learning game built from scratch using tabular Q-learning in Python

# GridWorld Q-Learning Game

This project is a beginner-friendly reinforcement learning implementation of a GridWorld game using **tabular Q-learning**. The goal is to train an agent to move from a starting position to a goal while avoiding traps and minimizing unnecessary steps.

The project was built from scratch in Python and designed to explain the core logic of reinforcement learning, including states, actions, rewards, exploration, exploitation, Q-values, and policy learning.

## Project Overview

In this game, the agent starts on a grid and must learn the best path to reach the goal. The agent receives rewards or penalties depending on its actions.

- Reaching the goal gives a positive reward.
- Falling into a trap gives a negative reward.
- Each normal movement gives a small penalty to encourage shorter paths.

The agent learns through repeated trial and error using Q-learning.

## Features

- GridWorld environment
- Agent movement logic
- Reward system
- Q-table creation
- Epsilon-greedy exploration
- Q-learning training loop
- Learned path visualization
- Reward history plot
- Smoothed training curve
- Learned policy display
- Text-based playable mode
- Automatic agent demo mode

## Reinforcement Learning Concepts Covered

This project demonstrates the following reinforcement learning concepts:

- Agent
- Environment
- State
- Action
- Reward
- Episode
- Policy
- Q-table
- Q-value update
- Exploration vs exploitation
- Epsilon decay
- Training reward analysis

## Technologies Used

- Python
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

## How the Game Works

The agent can move in four directions:

```text
up, down, left, right
