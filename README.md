# Traveling Salesman Problem (TSP) Solver: Hill Climbing & Genetic Algorithm

This repository contains a comprehensive implementation and comparative analysis of two metaheuristic algorithms for solving the Traveling Salesman Problem (TSP):

- **Hill Climbing with Random Restarts**
- **Genetic Algorithm (GA)**

The notebook is designed to run in a Jupyter environment and provides detailed performance comparisons, visualizations, and statistical summaries for both algorithms across varying problem sizes.

---


## Features

- **Hill Climbing with Random Restarts**:
  - Uses random restart strategy to escape local optima
  - Implements neighbor generation via route swapping
  - Tracks convergence history for each restart

- **Genetic Algorithm**:
  - Uses tournament selection, order crossover (OX1), and swap mutation
  - Configurable population size, generations, and mutation rate
  - Tracks best fitness across generations

- **Experiments & Analysis**:
  - Runs both algorithms on TSP instances of sizes 10–50 cities
  - Compares solution quality (distance) and runtime
  - Generates box plots, line charts, and summary tables

- **Visualization**:
  - Plots routes for solution inspection
  - Comparative box plots for distance and runtime
  - Line plots showing scalability with problem size

---

## 🛠 Requirements

The notebook requires the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install dependencies via:

```bash
pip install numpy pandas matplotlib seaborn
