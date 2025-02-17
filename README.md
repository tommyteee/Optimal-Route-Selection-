Route Optimization Using OR-Tools CP-SAT

![image](https://github.com/user-attachments/assets/ff0074b3-cc4f-4293-92fe-939262c0930c)

![image](https://github.com/user-attachments/assets/947bc317-7c6a-46c5-8b4d-1eca8d8bed94)

Overview

This project solves a route optimization problem using Constraint Programming (CP) with OR-Tools' CP-SAT solver. The goal is to find the shortest path from an origin to a destination while ensuring flow conservation at intermediate nodes. The model minimizes the total travel distance while enforcing constraints on valid paths.

Key Features

Implements shortest path optimization using constraint programming

Ensures flow conservation at all intermediate nodes

Uses binary decision variables to determine the optimal route

Employs OR-Tools' CP-SAT solver for fast and efficient optimization

Installation

1. Install Required Packages

Ensure you have the following dependencies installed:

pip install pandas numpy ortools openpyxl

How to Run the Project

Ensure your Excel input file (route_inputs.xlsx) is correctly formatted:

"nodes" sheet: node, description

"paths" sheet: node_from, node_to, distance

Run the Python script:

python route_optimization.py

View the results, which include:

Activated paths in the shortest route

Total minimized travel distance


License

This project is licensed under the MIT License.
