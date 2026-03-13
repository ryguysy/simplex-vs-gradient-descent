# Simplex vs Gradient Descent

An empirical and conceptual study comparing the **Simplex algorithm** for linear programming with **gradient-based optimization methods**.

This project explores how two fundamentally different optimization paradigms behave in practice:  
- **Combinatorial optimization** through pivot operations on polyhedra (Simplex)  
- **Continuous optimization** using gradient-based search methods

The goal is to better understand how **problem structure influences algorithmic performance, convergence behavior, and solution paths**.

---

## Overview

Optimization is central to many areas of computer science, mathematics, and operations research. While both the **Simplex algorithm** and **gradient descent** are widely used optimization techniques, they operate under very different principles.

This project investigates:

- Structural differences between **linear programming** and **continuous optimization**
- How the **Simplex method navigates vertices of a feasible polytope**
- How **gradient descent follows local slope information**
- Performance and convergence behavior across different problem instances

---

## Paper

The full report can be found here:

**📄 [report.pdf](report.pdf)**

It includes:

- Background on the **Simplex algorithm**
- Overview of **gradient-based optimization**
- Conceptual and empirical comparisons
- Discussion of algorithmic trade-offs

---

## Key Topics

- Linear Programming
- Simplex Algorithm
- Gradient Descent
- Optimization Theory
- Algorithm Analysis
- Computational Experiments

---

## Motivation

Although both algorithms solve optimization problems, they belong to **different algorithmic worlds**:

| Simplex | Gradient Descent |
|--------|--------|
| Discrete pivot steps | Continuous updates |
| Moves along vertices of a polytope | Moves along gradient direction |
| Exact solution for LP | Iterative approximation |

Understanding these differences helps clarify when each approach is most effective.

---

## Author

**Ryan Saint-Yves**  
B.Sc. Joint Honours Mathematics & Computer Science  
University of Ottawa

LinkedIn: https://www.linkedin.com/in/ryan-saint-yves/

---

## License

This project is released for educational and research purposes.
