# -CSC-333-OR-Linear-Programming-Solution
Linear Programming Project
Project Description
This project addresses a series of Linear Programming (LP) problems, each representing real-world scenarios involving optimization. These problems include maximizing profit, minimizing cost, and allocating limited resources effectively. Using Python and its libraries such as SciPy, matplotlib, and NumPy, the solutions are implemented programmatically and visualized graphically.

The project demonstrates:

Formulating optimization problems as mathematical models.
Solving them using Python's scipy.optimize.linprog method.
Visualizing constraints, feasible regions, and optimal solutions.
Objectives of the LP Problems
1. Maximizing Profit for a Factory
Goal: Maximize the profit from producing two products (A and B) while adhering to resource constraints such as machine time and raw materials.

2. Minimizing Cost for a Manufacturer
Goal: Minimize the production cost of two products (X and Y) given limited labor and material resources.

3. Other Problems
Similarly, other problems deal with maximizing revenue, minimizing costs, and optimal resource allocation for different scenarios. The objectives are clearly stated in each respective code section.

How the Problems Were Solved
Mathematical Formulation:

Define decision variables (e.g., 
x
,
y
x,y for the number of products or resources).
Create an objective function (e.g., profit = 
3
x
+
4
y
3x+4y).
Establish constraints (e.g., 
2
x
+
3
y
≤
12
2x+3y≤12).
Implementation in Python:

Use scipy.optimize.linprog for solving LP problems.
Plot constraints and feasible regions using matplotlib.
Graphical Solution:

The constraints are plotted to visualize the feasible region.
The optimal solution is marked on the graph for clarity.
Files in This Project
maximize_profit.py - Code for Maximizing Profit for a Factory.
minimize_cost.py - Code for Minimizing Cost for a Manufacturer.
additional_problems.py - Other LP problems such as resource allocation, advertising budget, etc.
README.md - Project documentation.
requirements.txt - Python dependencies.
How to Run the Code
Prerequisites
Install Anaconda or ensure Python (3.8+) is installed.
Install required libraries:
pip install -r requirements.txt
The file contains:
scipy
matplotlib
numpy
Steps to Run
Clone or download the repository:

git clone https://github.com/your-repo/linear-programming-project.git
cd linear-programming-project
Open Jupyter Notebook (recommended for interactive exploration):

jupyter notebook
Open and execute the respective .ipynb files or .py scripts:

For Maximizing Profit:
python maximize_profit.py
For Minimizing Cost:
python minimize_cost.py
View the results in the terminal (optimal solutions) and plots (graphical visualization).

Detailed Example: Maximize Profit
Problem Setup
A factory produces two products, A and B, with resource constraints:

Machine time: 
2
x
+
3
y
≤
12
2x+3y≤12
Raw materials: 
x
+
2
y
≤
8
x+2y≤8
Solution
Code solves using scipy.optimize.linprog.
Constraints are plotted to show the feasible region.
The optimal solution is identified both programmatically and graphically.
Output
The script outputs:

The optimal number of products 
x
x and 
y
y.
The maximum profit value.
A graph showing the feasible region and optimal solution.
Instructions for Extending the Project
Add new LP problems:
Define objective function coefficients and constraints in a similar format.
Use the existing code as a template.
Modify the visualization:
Adjust axis limits and labels for different scales.
Customize colors and styles for clearer representation.












