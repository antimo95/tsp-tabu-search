# 📦 TSP Optimization Project – Federico II 2024/2025

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![matplotlib](https://img.shields.io/badge/Matplotlib-3.x-green.svg)
![OR-Tools](https://img.shields.io/badge/Google_OR--Tools-9.x-red.svg)
![Colab](https://img.shields.io/badge/Colab-Compatible-yellow.svg)

## 🧭 Project: Traveling Salesman Problem with Tabu Search

This project tackles the classical **Traveling Salesman Problem (TSP)** using **metaheuristic and exact algorithms**, focusing on performance, accuracy, and gap analysis compared to optimal solutions.

---

## 🔧 Algorithms Implemented

1. **Tabu Search**  
   Classic metaheuristic for TSP using 2-opt neighborhood and memory-based move exclusion.

2. **Multi-Start Tabu Search**  
   Repeated Tabu Search from different random seeds to enhance global exploration and avoid local minima.

3. **Exact Solver with Google OR-Tools**  
   Solves TSP using **Row Generation** to handle subtour elimination constraints iteratively.

---

## 📁 File Structure

- `ch150.tsp`, `ch150.opt.tour`, `eil76.tsp` → Dataset files in TSPLIB format.
- `RO_TabuSearch_TSP.ipynb` → Main notebook with all implementations.
- `plot_tour()` → Visualizes the generated routes.
- `compute_distance_matrix()` → Builds the full distance matrix.

---

## 🧮 Features

- Visual comparison between **Tabu Search** and **Optimal Tour**
- Gap computation between heuristic and exact solutions
- Early stopping with counter on non-improving moves
- Pretty distance matrix printing
- Fully modular design


