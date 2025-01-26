---
title: "Angular momentum fluctuations in molecular simulations"
excerpt: "Phase transition diagnostic tool. <br/><img src='/images/T10traj.png'>"
collection: portfolio
tags:
  - Molecular Dynamics
  - Angular Momentum
  - Phase Transitions
---

### Overview

In Molecular Dynamics simulations, it is computationally impossible to calculate the interactions between $$\(10^{23}\)$$ particles (the order of Avogadro’s number). Modern computers can simulate systems up to the order of $$\(10^6\)$$ particles. 

To simulate large systems, a small part is selected (the "unit cell"), and **periodic boundary conditions** are employed. This means that when a particle reaches the edge of the unit cell, it reappears from the other side with the same velocity. However, when periodic boundary conditions are employed, the total angular momentum of the unit cell is not conserved.

---

### Problem Statement

If the unit cell is considered an open system rather than a closed one, a balance equation instead of a conservation equation can be constructed for the angular momentum. In this case:
- The rate of change of angular momentum is the balance between the torque exerted by particles outside the unit cell and the angular momentum flux through the boundaries.
- As a result, angular momentum oscillates around zero due to this interplay.

This study explores the relationship between angular momentum fluctuations and the physical characteristics of the system (system size, temperature, and density). Key points include:
- Fitting angular momentum distributions to a Gaussian function.
- Measuring the variance for different system sizes, temperatures, and densities.
- Investigating a potential connection between variances and finite-size effects.

---

### Research Goals

The study aims to address the following question:

> Suppose we have a two-dimensional tetragonal-shaped unit cell with \(N\) interacting particles. How are the fluctuations of angular momentum related to the physical characteristics of the system, and how can we exploit these relationships to diagnose finite-size system effects?

---

### Resources

- **White paper** 📄: [Download the PDF](/files/portfolio_1_file.pdf)
- **Molecular Dynamics code** 💻: [Link to code repository](https://github.com/emainas/LennardJones_MolecularDynamics.git)

---

### Summary of Findings

The findings of this research suggest that angular momentum fluctuations can serve as a diagnostic tool for identifying finite-size effects in molecular simulations. Future work will focus on expanding this approach to three-dimensional systems and incorporating additional physical parameters.

---
