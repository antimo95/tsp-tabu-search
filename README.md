# 📦 TSP Optimization Project – Federico II 2024/2025

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![matplotlib](https://img.shields.io/badge/Matplotlib-3.x-green.svg)
![OR-Tools](https://img.shields.io/badge/Google_OR--Tools-9.x-red.svg)
![Colab](https://img.shields.io/badge/Colab-Compatible-yellow.svg)

## 🧭 Project: Traveling Salesman Problem with Tabu Search

This project tackles the classical **Traveling Salesman Problem (TSP)** using **metaheuristic and exact algorithms**, focusing on performance, accuracy, and gap analysis compared to optimal solutions.

---

📂 Dataset  
**Source**: TSPLIB benchmark files  
**Files used**:  
- `ch150.tsp` — Coordinates of 150 cities  
- `ch150.opt.tour` — Known optimal tour  
- `eil76.tsp` — Smaller instance for OR-Tools 


🛠 Tools & Technologies Used  
- 🧠 **Tabu Search** (classic and multi-start versions)  
- 🧩 **Google OR-Tools** (Row Generation solver)  
- 📊 **matplotlib** — tour visualization  
- 📐 **NumPy** — distance matrix computation  
- 🕸 **NetworkX** — graph analysis for subtours  
- ⚙️ **Google Colab** — development and testing

---

📊 Data Processing & Precomputation

🔍 **Input Handling**:  
- Parsing `.tsp` and `.tour` files to extract city coordinates and optimal solutions.

📏 **Distance Matrix**:  
- Computed using Euclidean distance between all city pairs.

🖼 **Visualization**:  
- Custom plot function for route display with city annotations.

---


🚀 Algorithms Implemented

1. ✅ **Tabu Search**:  
   - Local search with 2-opt neighborhood  
   - Tabu list with adaptive memory  
   - Early stopping based on stagnation

2. ✅ **Multi-Start Tabu Search**:  
   - Repeated Tabu Search from random seeds  
   - Best solution selected among all runs

3. ✅ **Exact Solver (OR-Tools)**:  
   - Row Generation to iteratively remove subtours  
   - Guarantees optimality on smaller instances

---

## 📌 Conclusion

Beyond the algorithms and their performance, this project provides a **practical learning experience** in operations research and algorithm design. Working with real benchmark datasets and implementing both heuristics and exact methods has offered the opportunity to:

- Understand the trade-offs between **efficiency and optimality**
- Gain hands-on experience with **metaheuristics**
- Appreciate the complexity of combinatorial problems in real scenarios

This type of problem-solving approach is highly transferable to many domains, including logistics, manufacturing, and bioinformatics, where finding "good enough" solutions quickly is often more valuable than perfection.

---
