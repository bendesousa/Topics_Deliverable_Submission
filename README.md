# Topics Deliverable Submission

This repository contains the Python implementation of the **Topics in Applied Operational Research** timetable optimization problem using **Gurobi**.

## Overview

The project focuses on constructing a university timetable that:

- Avoids overlaps for compulsory courses.
- Minimizes clashes for optional courses.
- Ensures students have feasible course options.
- Accounts for room capacities and time constraints.
- Provides optional extensions such as lunch breaks and consecutive lecture slots.

The **mathematical formulation** of the problem is detailed in the accompanying LaTeX document in the submission package.

## Structure

- `base_model.py`: Python script implementing the mathematical model using Gurobi.
- `README.md`: This file explaining the repository.

## Requirements

- Python 3.8+  
- [Gurobi Optimizer](https://www.gurobi.com/) with a valid license  
- `numpy` library  

Install Python dependencies:

```bash
pip install numpy gurobipy
