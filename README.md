📘 AI & Data Science Project Collection

This repository contains multiple tasks demonstrating concepts from Artificial Intelligence, Logic, Search Algorithms, and Machine Learning. Each task focuses on solving real-world problems using computational techniques and visualization.

📂 Project Structure
├── Task 1: Maze Escape using A* Algorithm
├── Task 2: Smart Traffic Signal System
├── Task 3: Sudoku Solver (Propositional vs First-Order Logic)
├── Task 4: House Price Prediction (ML Models)
🧩 Task 1: Maze Escape – A* Search Algorithm
📌 Description

A 15×15 maze is generated with:

Walls
Traps (high-cost paths)
Locks
Start & Exit points

The goal is to find the optimal path using the A* Search Algorithm.

⚙️ Features
Random maze generation (DFS-based)
Cost-based pathfinding
Manhattan distance heuristic
Performance evaluation (cost, steps, time)
Visualization of maze and path
🧠 Algorithm Used
A* Search

𝑓
(
𝑛
)
=
𝑔
(
𝑛
)
+
ℎ
(
𝑛
)
f(n)=g(n)+h(n)
📊 Output
Path found or not
Total cost
Steps taken
Execution time
Visual maze with highlighted path
🚦 Task 2: Smart Traffic Signal System
📌 Description

Simulation of a city-wide intelligent traffic control system on a 4×5 grid of intersections.

⚙️ Features
Adaptive traffic signals based on:
Traffic congestion
Vehicle density
Weather (rain)
Priority handling:
Emergency vehicles 🚑
Buses 🚌
Pedestrian crossing system
Vehicle movement simulation
Real-time traffic data updates
🧠 Advanced Concepts
Constraint Satisfaction
Soft constraints:
Fairness across districts
Green wave optimization
Congestion balancing
Fuel consumption tracking
Vehicle chain detection
📊 Output
Dynamic traffic simulation
Signal state changes (RED/YELLOW/GREEN)
Congestion levels
Adaptive timing adjustments
🔢 Task 3: Sudoku Solver
📌 Description

Solve a 9×9 Sudoku puzzle using:

Propositional Logic (CNF + SAT Solver)
First-Order Logic (Z3 Solver)
⚙️ Features
Grid visualization
Step-by-step solving display
Comparison of two logic approaches
🧠 Techniques Used
1. Propositional Logic
CNF encoding
Solved using pycosat
2. First-Order Logic
Constraint modeling using Z3
Uses:
Domain constraints (1–9)
Row/Column uniqueness
Subgrid constraints
📊 Output
Solved Sudoku board
Execution time comparison
Visual comparison of both approaches
📈 Task 4: House Price Prediction
📌 Description

Machine Learning model to predict house prices using the California Housing Dataset.

⚙️ Features
Data preprocessing & scaling
Statistical analysis
Visualization:
Histogram
Correlation heatmap
Model training & evaluation
🧠 Models Used
Linear Regression
K-Nearest Neighbors (k=3, 5, 7)
📊 Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
📉 Visualization
Actual vs Predicted values
Model comparison plots
🛠️ Technologies Used
Python 🐍
NumPy
Pandas
Matplotlib / Seaborn
Scikit-learn
Z3 Solver
PycoSAT
▶️ How to Run
Install dependencies:
pip install numpy pandas matplotlib seaborn scikit-learn z3-solver pycosat
Run each task separately:
python task1_maze.py
python task2_traffic.py
python task3_sudoku.py
python task4_ml.py
📌 Key Learnings
Application of A* in pathfinding problems
Real-world traffic optimization using AI
Difference between Propositional & First-Order Logic
Practical implementation of Machine Learning models
Importance of visualization and performance analysis
