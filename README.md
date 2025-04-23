# SOM_Reinforcement-Learning_PSO

**CS 451 - Computational Intelligence, Spring 2025, Habib University**  

---

## Overview
This assignment explores three core topics in computational intelligence:

1. **Self-Organizing Maps (SOM)** for clustering and visualizing death rate from natural disasters-related world data.
2. **Reinforcement Learning** with policy learning in the `Taxi-v3` Gym environment.
3. **Particle Swarm Optimization (PSO)** for minimizing continuous non-convex functions.

---

## Repository Structure

```
Assignment03/
│
├── Q1_SOM.ipynb                                               # SOM implementation with world map visualization
├── Q2_Taxi_RL.ipynb                                           # Value iteration-based agent for Taxi-v3 (to be created)
├── Q3_PSO.ipynb                                               # PSO for Rosenbrock & Greiwank functions (to be created)
├── ne_110m_admin_0_countries                                  # for geopandas to get world map shape
├── decadal-average-death-rates-from-natural-disasters-2020-1  # csv file for SOM dataset
└── README.md                                                  # Assignment summary and instructions
```

---

## Question Highlights

### Q1: SOM Clustering of COVID Data
- Apply SOM on a multi-attribute dataset.
- Use RGB mapping for visual cluster representation.
- Visualize clusters on a world map using GeoPandas.

### Q2: RL in Taxi-v3 Environment
- Implement value iteration for optimal taxi navigation.
- Learn and execute policies for pickup and drop-off tasks.

### Q3: PSO for Function Optimization
- Use PSO to minimize:
  - **Rosenbrock Function**
  - **Griewank Function**
- Plot best-so-far and average-so-far results per iteration.

---

## Requirements
- Python 3.8+
- Libraries: `numpy`, `matplotlib`, `geopandas`, `gym`, `seaborn`

Install dependencies:
```bash
pip install numpy matplotlib geopandas gym seaborn
```
