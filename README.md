# 🚀 AI & Intelligent Systems Project Suite

A collection of projects demonstrating practical applications of **Artificial Intelligence, Search Algorithms, Logical Reasoning, and Machine Learning**.

---

## 📌 Overview

This repository includes four major tasks:

| Task | Domain | Technique |
|------|--------|----------|
| 🧩 Task 1 | Pathfinding | A* Algorithm |
| 🚦 Task 2 | Smart Systems | Traffic Optimization |
| 🔢 Task 3 | Logic AI | SAT & First-Order Logic |
| 📈 Task 4 | Machine Learning | Regression |

---

## 🧩 Task 1: Maze Escape using A* Search

### 📝 Description
A **15×15 maze** with walls, traps, and locks. The goal is to find the optimal path from start to exit.

### ⚙️ Features
- Random maze generation (DFS)
- A* pathfinding
- Trap-based cost system
- Visualization of path

### 🧠 Formula
f(n) = g(n) + h(n)


### 📊 Output
- Optimal path
- Cost & steps
- Execution time
- Visual maze

---

## 🚦 Task 2: Smart Traffic Signal System

### 📝 Description
Simulation of an **adaptive traffic system** on a grid of intersections.

### ⚙️ Features
- Dynamic signal timing
- Emergency vehicle priority
- Bus lane prioritization
- Pedestrian crossings
- Weather-based adjustments

### 🧠 Concepts
- Constraint Satisfaction
- Green wave optimization
- Fairness across districts
- Congestion balancing

### 📊 Output
- Live traffic simulation
- Adaptive signals
- Improved traffic flow

---

## 🔢 Task 3: Sudoku Solver

### 📝 Description
Solves a **9×9 Sudoku** using two approaches.

### ⚙️ Methods

#### 1. Propositional Logic
- CNF encoding
- Solved using `pycosat`

#### 2. First-Order Logic
- Implemented using `Z3 Solver`
- Enforces:
  - Row/column uniqueness
  - Subgrid constraints

### 📊 Output
- Solved grid
- Time comparison
- Visual output

---

## 📈 Task 4: House Price Prediction

### 📝 Description
Predicts housing prices using the **California Housing Dataset**.

### ⚙️ Workflow
- Data preprocessing
- Visualization
- Model training

### 🧠 Models
- Linear Regression
- KNN (k = 3, 5, 7)

### 📊 Metrics
- R² Score
- MAE
- MSE

### 📉 Visuals
- Heatmaps
- Distribution plots
- Prediction graphs

---

## 🛠️ Tech Stack

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Z3 Solver
- PycoSAT

---

## ▶️ Getting Started

### 1. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn z3-solver pycosat
2. Run Tasks
python task1_maze.py
python task2_traffic.py
python task3_sudoku.py
python task4_ml.py

## 🎯 Learning Outcomes
A* Search implementation
Intelligent traffic systems
Logic-based problem solving
Machine learning fundamentals
Data visualization techniques
