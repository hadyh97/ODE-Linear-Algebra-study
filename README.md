# Forward Euler Method — ODE Mini Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YourUsername/euler-method-mini-project/blob/main/ODE_Euler_MiniProject.ipynb)

This mini project studies the **accuracy and convergence of the Forward Euler method** for solving ordinary differential equations (ODEs).  
It combines mathematical analysis with a Python implementation to illustrate how numerical errors behave and how step size affects stability.

---

##  Overview

The notebook includes:
- A derivation of the **Forward Euler method** from the Taylor series,
- Implementation of the algorithm in Python,
- Comparison with the **exact analytical solution** \( y(t) = e^{-\lambda t} \),
- A **convergence test** confirming first-order global accuracy,
- Visualizations showing the effect of step size and stability.

---

##  How to Use

You can view the notebook directly on GitHub or open it interactively in Google Colab using the badge above.

If you want to experiment with the parameters:
- Run the notebook in **Colab** or **VS Code**.
- Modify the values of:
  ```python
  lam = 2.0   # λ (decay rate)
  h   = 0.2   # step size
  T   = 1.0   # final time
