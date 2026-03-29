🚀 AI & Intelligent Systems Project Suite

A comprehensive collection of projects demonstrating practical applications of Artificial Intelligence, Search Algorithms, Logical Reasoning, and Machine Learning.

This repository showcases how different AI techniques can be applied to solve real-world problems such as pathfinding, traffic optimization, constraint solving, and predictive modeling.

📌 Overview

This project is divided into four major tasks:

Task	Domain	Key Technique
🧩 Task 1	Pathfinding	A* Search Algorithm
🚦 Task 2	Smart Systems	Adaptive Traffic Control
🔢 Task 3	Logic AI	SAT & First-Order Logic
📈 Task 4	Machine Learning	Regression Models
🧩 Task 1: Maze Escape using A* Search
📝 Description

A randomly generated 15×15 maze simulates a high-security environment with obstacles like walls, traps, and locked areas. The objective is to guide an agent from start to exit using an optimal path.

⚙️ Key Features
Dynamic maze generation (DFS-based)
Intelligent pathfinding using A*
Trap-aware cost system
Heuristic: Manhattan Distance
Visual representation of maze and solution path
🧠 Core Idea

The A* algorithm ensures optimality using:

f(n) = g(n) + h(n)
📊 Output
Path found with minimum cost
Total steps & execution time
Visualized maze with highlighted path
🚦 Task 2: Smart Traffic Signal System
📝 Description

A simulation of an intelligent traffic control system over a grid of intersections that adapts dynamically to real-time conditions.

⚙️ Key Features
Adaptive signal timing based on:
Traffic density
Congestion levels
Weather conditions (rain)
Priority handling:
Emergency vehicles
Public transport (buses)
Pedestrian crossing system
Real-time vehicle simulation
🧠 Advanced Concepts
Constraint Satisfaction (Hard + Soft Constraints)
Green wave optimization (vehicle flow continuity)
District-based fairness system
Fuel consumption tracking
Congestion balancing
📊 Output
Live traffic simulation
Dynamic signal updates
Improved traffic flow efficiency
🔢 Task 3: Sudoku Solver using Logic
📝 Description

Solves a standard 9×9 Sudoku puzzle using two different AI reasoning approaches.

⚙️ Approaches Used
1️⃣ Propositional Logic
CNF encoding of Sudoku constraints
Solved using a SAT solver (pycosat)
2️⃣ First-Order Logic
Constraint modeling using Z3 Solver
Ensures:
Unique rows, columns, and subgrids
Valid number domain (1–9)
📊 Output
Solved Sudoku grid
Execution time comparison
Visualization of solutions
💡 Insight

This task highlights the difference between:

Boolean constraint solving (SAT)
Symbolic reasoning (FOL)
📈 Task 4: House Price Prediction
📝 Description

A machine learning project that predicts housing prices using the California Housing Dataset.

⚙️ Workflow
Data preprocessing & normalization
Exploratory Data Analysis (EDA)
Model training & evaluation
🧠 Models Implemented
Linear Regression
K-Nearest Neighbors (k = 3, 5, 7)
📊 Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
📉 Visualizations
Feature correlations (heatmap)
Data distribution plots
Actual vs Predicted comparison
🛠️ Tech Stack
Language: Python
Libraries:
NumPy, Pandas
Matplotlib, Seaborn
Scikit-learn
Z3 Solver
PycoSAT
▶️ Getting Started
1️⃣ Install Dependencies
pip install numpy pandas matplotlib seaborn scikit-learn z3-solver pycosat
2️⃣ Run the Tasks
python task1_maze.py
python task2_traffic.py
python task3_sudoku.py
python task4_ml.py
🎯 Key Learning Outcomes
Practical implementation of A* Search in complex environments
Design of adaptive, real-time intelligent systems
Understanding Propositional vs First-Order Logic
Application of Machine Learning for prediction tasks
Importance of data visualization and performance evaluation
