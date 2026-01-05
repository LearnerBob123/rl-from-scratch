# RL-from-Scratch

This repository contains my step-by-step implementations of reinforcement learning algorithms, from basic tabular methods to deep RL, as part of my self-driven experiments to understand how RL algorithms learn and where they can fail.

## Overview

I started by re-implementing existing papers to understand the mechanics of RL algorithms, iteratively improving and testing them in various environments. The goal is to see **where each method succeeds, where it fails, and how new updates affect learning stability**.

## Implemented Algorithms

- **Tabular Q-Learning** – tested on basic Gymnasium environments  
- **Deep Q-Networks (DQN)** – including convolutional variants for Atari games  
- **Actor-Critic methods (AC, A2C, A3C)** – tested on classical control environments and small custom environments  
- **Policy Gradient methods** – experimentation with advantage estimation and reward shaping  

## Key Focus

- Understanding the impact of **hyperparameters** on learning  
- Observing **policy stability and convergence**  
- Iteratively testing updates to see **how learning improves or breaks**  
- Step-by-step experiments to deepen intuition about RL mechanics  

## Environments

- Classic control (CartPole, MountainCar, LunarLander)  
- Basic Gymnasium environments  
- Selected Atari environments for DQN experiments  

## Usage

- Each folder contains a self-contained script or notebook demonstrating a specific algorithm  
- Run scripts sequentially to follow the learning progression from tabular methods to deep RL  

---

**Note:** This repo is focused on **learning and experimentation**, not production pipelines. It’s a personal exploration of RL algorithms and their behavior.
