# Multi-Armed Bandit Simulation

## Description

A simple and extensible simulation environment for multi-armed bandit problems. The project provides a notebook for experimenting with exploration–exploitation strategies, visualizing reward trajectories, and comparing bandit policies in a controlled setting.

---

## Overview

The goal of this repository is to:

- Simulate **K-armed bandit** environments  
- Implement and test different **action-selection strategies**  
- Track cumulative reward / regret over time  
- Provide clear, reproducible experiments in a single Jupyter notebook

You can use it as a learning tool for reinforcement learning concepts, or as a base to prototype and compare custom bandit algorithms.

---

## Features

- Configurable number of arms and time horizon  
- Random or user-defined reward distributions for each arm  
- Step-by-step simulation logic inside a Jupyter notebook  
- Plots for:
  - Average reward over time  
  - Cumulative reward / regret  
  - Arm selection frequencies  
- Easy to extend with new strategies (e.g., ε-greedy variants, UCB-style rules, Bayesian / sampling-based methods)

---

## Project Structure

```text
.
├── BanditSimulation.ipynb   # Main notebook with simulation and analysis
└── README.md                # Project documentation
```
## Requirements

Make sure you have Python and Jupyter installed.

Typical dependencies (adjust based on your notebook):

```bash
pip install numpy matplotlib jupyter
```
