# Traveling Salesman Problem Solver using Genetic Algorithm

## Introduction

This project presents an implementation of a solver for the **Traveling Salesman Problem (TSP)** using a **Genetic Algorithm (GA)**.  
The system includes a graphical user interface built with **PyQt5** and **Matplotlib**, enabling users to observe how the genetic algorithm evolves over time and gradually improves the solution.

The Traveling Salesman Problem aims to find the shortest possible route that visits each city exactly once and returns to the starting city. Since TSP is an NP-hard optimization problem, heuristic and evolutionary approaches such as Genetic Algorithms are suitable for finding near-optimal solutions in a reasonable amount of time.

---

## Artificial Intelligence Method

- Algorithm: Genetic Algorithm
- Key concepts applied:
  - Population initialization
  - Fitness evaluation based on total travel distance
  - Selection mechanism
  - Crossover operation
  - Mutation operation
  - Elitism strategy
- Optimization goal: Minimize the total distance of the tour

---

## Main Features

- Random generation of city coordinates
- Calculation of distance matrix using Euclidean distance
- Genetic Algorithm-based optimization process
- Visualization of:
  - City positions
  - Best tour found during evolution
- Graphical user interface for interaction and result display
- Real-time updates using timers

---

## Technologies Used

- Programming Language: Python
- Libraries and Frameworks:
  - PyQt5
  - Matplotlib
  - NumPy
  - Math
  - Random

---

## Installation and Requirements

Ensure that Python version 3.8 or higher is installed on your system.

Install the required dependencies using the following command:

```bash
pip install pyqt5 matplotlib numpy
```

## How to Run

1. Open the project folder in **Visual Studio Code**.
2. Ensure that all required libraries are installed.
3. Run the Jupyter Notebook directly or convert it into a Python script.
4. Execute the program using the following command:
   ```bash
   python FinalTermAI.py
   ```
5. A graphical window will appear, displaying the cities, the current best tour, and distance-related information.

---

## Output Description

- Cities are displayed as points on a two-dimensional coordinate plane.
- The best tour found by the genetic algorithm is visualized using connecting lines between cities.
- The interface displays the total travel distance and distance matrix information.

---

## Learning Outcomes

Through this project, the team was able to:

- Apply Genetic Algorithms to solve a classical optimization problem in Artificial Intelligence.
- Understand evolutionary computation concepts through practical implementation.
- Develop a GUI-based Artificial Intelligence application.
- Visualize and analyze heuristic optimization processes.
