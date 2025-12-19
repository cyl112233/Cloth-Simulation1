# Cloth-Simulation1
# Physics-Informed Neural Networks for High-Fidelity Dynamic Cloth Simulation: Parameter Estimation and Differentiable Simulation

## Overview

This repository provides an implementation of a **dual-driven physics-informed neural network (PINN)** framework for accurate dynamic cloth simulation. The approach integrates physical modeling with data-driven learning, achieving precise parameter estimation and high-fidelity simulations for cloth behavior. The framework consists of two key components:

1. **K-PINN**: A parameter estimation model that predicts mechanical parameters (tensile stiffness, shear stiffness, bending stiffness) from a single cloth image by incorporating physical constraints.
2. **DP-PINN**: A simulation framework that integrates a differentiable physics engine into the neural network, supporting dynamic cloth simulations with high physical consistency.

### Key Contributions:
- **K-PINN**: Reduces density estimation error from 1.8% to 1.2% compared to existing methods.
- **DP-PINN**: Outperforms traditional physics-based methods and data-driven models in simulation speed (6.1 ms for two-point fixed cloth) and physical consistency, providing stable and realistic dynamic cloth behaviors.

---

## Key Features

- **High-Fidelity Simulation**: Achieves real-time and accurate cloth simulation with complex deformations like stretching, bending, and wrinkling.
- **Dual-Driven Framework**: Combines physics-based modeling and data-driven learning, offering both simulation accuracy and computational efficiency.
- **Differentiable Physics Engine**: Enables seamless optimization of physical parameters and network weights through backpropagation.
- **Realistic Cloth Deformations**: Suitable for virtual reality, digital humans, and virtual try-on applications.

---

## Installation

To install the dependencies, run:

```bash
pip install -r requirements.txt
Here is a sample simulation result



