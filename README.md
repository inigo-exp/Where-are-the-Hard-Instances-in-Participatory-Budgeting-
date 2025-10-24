# Hard Instances in Participatory Budgeting  
Optimization and Instance Generation Project

This project analyzes the computational complexity of participatory budgeting problems using optimization and statistical methods. The goal is to understand which instance characteristics make the problem harder to solve for Gurobi.

---

## Objectives
- Generate different types of participatory budgeting instances.  
- Study how distributions, correlations, and constraints affect solver difficulty.  
- Evaluate performance through runtime, feasibility, and statistical analysis.  

---

## Methodology
The problem is formulated as a binary optimization model similar to the knapsack problem, with additional neighborhood constraints.  
Different instance generation methods were implemented using varied parameter distributions, correlations, and bounds.  
Statistical tests and visualizations were used to compare methods and identify hard cases.

---

## Repository Structure
| File | Description |
|------|--------------|
| Code.ipynb | Jupyter Notebook with full implementation and analysis |
| Report.pdf | Final report with results, methodology, and discussion |
| README.md | Project overview and documentation |

---

## Tools
Language: Python  
Solver: Gurobi  
Libraries: numpy, pandas, matplotlib, scipy, seaborn  

---

## How to Run
1. Open Code.ipynb in Jupyter Notebook or JupyterLab.  
2. Run the cells in order to generate and evaluate the instances.  
3. Review visual outputs and performance metrics at the end of the notebook.  

