# # Held-Karp Method for Solving TSP

This repository contains a Jupyter Notebook implementing the **Held-Karp method**, a dynamic programming approach to solving the **Traveling Salesperson Problem (TSP)** optimally.

## 📌 Overview
The **Held-Karp algorithm** (also known as the Bellman-Held-Karp algorithm) is a dynamic programming solution for solving the TSP with **O(n² * 2ⁿ)** time complexity. It provides an optimal solution but is computationally expensive for large input sizes.

### 🔥 Demonstrating TSP as an NP-Hard Problem
- TSP is known to be **NP-hard**, meaning there is no known polynomial-time solution for all cases.
- The Held-Karp algorithm confirms this by showing:
  - **Time complexity:** O(n² * 2ⁿ), which grows exponentially.
  - **Memory complexity:** O(n * 2ⁿ), due to the need for storing subproblem results.
- As `n` increases, both **runtime** and **memory usage** grow exponentially, proving the computational difficulty.

## 📂 Files
- **`Held Karp method.ipynb`** – Jupyter Notebook implementing the Held-Karp algorithm for TSP.

## 🚀 Requirements
To run this notebook, install the following dependencies:

```bash
pip install numpy pandas matplotlib folium openstreetmap
