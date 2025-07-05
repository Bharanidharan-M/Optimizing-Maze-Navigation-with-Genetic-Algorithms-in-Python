# 🧬 Maze Solver Using Genetic Algorithm (DEAP + Python)

This project demonstrates the use of a **Genetic Algorithm (GA)** to solve a 2D maze using the **DEAP (Distributed Evolutionary Algorithms in Python)** library. The algorithm evolves a population of movement paths to find an optimal or near-optimal solution from a defined start to an end point in the maze.

---

## 🚀 Features

- Uses Genetic Algorithms to evolve path solutions.
- Custom mutation, crossover, and fitness evaluation.
- Visualizes the best path across generations.
- Uses Manhattan Distance for fitness scoring.
- Prevents wall collisions and tracks progress.

---

## 🧩 Maze Structure

The maze is defined as a 2D list of 0s (free space) and 1s (walls).  
The goal is to move from the **top-left corner (0,0)** to the **bottom-right corner** using movement directions: `U` (Up), `D` (Down), `L` (Left), and `R` (Right).

---

