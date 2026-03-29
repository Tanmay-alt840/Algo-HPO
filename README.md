# Multi-Algorithm Hyperparameter Optimization (HPO)
This repository presents a comprehensive comparative study of multiple Hyperparameter Optimization (HPO) techniques applied to Artificial Neural Networks (ANNs). The project explores both evolutionary and probabilistic optimization approaches to evaluate their effectiveness in improving model performance.

The algorithms implemented and analyzed include:

- Genetic Algorithm (GA)
- Particle Swarm Optimization (PSO)
- Differential Evolution (DE)
- PyHopper-based Optimization
- Bayesian Optimization with HyperBand (BOHB)

The objective is to benchmark these algorithms across common evaluation metrics such as convergence speed, solution quality, and computational efficiency.

---

# Project Overview
Hyperparameter tuning plays a critical role in machine learning model performance. This project systematically investigates how different optimization strategies behave under similar experimental settings.

Key highlights:

- Unified ANN-based evaluation framework across all algorithms
- Consistent search spaces for fair comparison
- Visualization of convergence trends and performance metrics
- Exploration of hybrid optimization strategies

---
# Repository Structure
- ANN_GA.ipynb → ANN optimized using Genetic Algorithm
- ANN_PSO.ipynb → ANN optimized using Particle Swarm Optimization
- ANN_DE.ipynb → ANN optimized using Differential Evolution
- DE_BO.ipynb → Hybrid Differential Evolution + Bayesian Optimization
- Additional notebooks → PyHopper and BOHB implementations

Each notebook is self-contained and includes:

- Model definition
- Search space configuration
- Optimization logic
- Evaluation and results

---
# Key Features
- Modular implementation of optimization algorithms
- Custom fitness evaluation using ANN performance
- Flexible hyperparameter search spaces
- Comparative analysis across multiple optimization strategies
- Hybrid optimization experimentation (DE + BO)

---
# Results & Insights
The project provides insights into:
- Trade-offs between exploration and exploitation
- Performance differences across evolutionary vs probabilistic methods
- Effectiveness of hybrid optimization approaches
Detailed results and comparisons are documented within the notebooks and accompanying analysis.

---
# Author
Tanmay Goel
