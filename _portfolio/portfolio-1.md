---
title: "Large-deviations theory of liquid crystal molecules"
excerpt: "The simplest phase transition that liquid crystals undergo is the isotropic -> nematic. Close to the nematic transition, the system forms domains that are very hard to quantify with molecular simulations. <br/><img src='/images/domains.png'>"
collection: portfolio
date: 2023-01-01
tags:
  - Molecular Dynamics
  - Liquid Crystals
  - Phase Transitions
  - Gay Berne potential
---

### Resources

- **Thesis** 📄: [Read Chapters 1, 4 and 6](https://www.proquest.com/docview/3060673874?fromopenview=true&pq-origsite=gscholar&sourcetype=Dissertations%20&%20Theses)
- **Published paper** 📄: [Read my paper in the Journal of Chemical Physics](https://pubs.aip.org/aip/jcp/article-abstract/162/2/024501/3329531/Exceptionally-large-fluctuations-in-orientational?redirectedFrom=fulltext)
- **Molecular Dynamics Code** 💻: [Link to GitHub repository](https://github.com/emainas/GayBerne_MolecularDynamics.git)
- **Large-deviations theory and Finite size scaling Code** 💻: [Link to GitHub repository](https://github.com/emainas/largedeviations-liquidcrystals.git)

---

### Overview

Describing the extent of order in isotropic liquid crystals can be done in terms of the probability distributions of collective molecular orientations. However, standard statistical mechanical methods for evaluating these distributions fail when large fluctuations become important, as they do close to the isotropic/nematic transition. Moreover, it is even difficult to extract quantitative details on large fluctuation behavior from simulations because of numerical noise. Using large-deviation theory, we described an approach to computing expressions for these probability distributions that can make use of simulation information to accurately compute even the large fluctuation limit of these distributions. Large-deviation theory can be shown to connect the applied field/orientational-order parameter equation of state to the desired probability distribution. The key is to think about the limiting extremes of the system’s response to an applied field. When the field is weak, the central-limit theorem applies, but in the presence of a strong field, individual rotors feel a mean-field from the rest of the system. We show that simple Pade’ interpolation between these limits generates a form for the equation of state that leads to a way of generating accurate orientational probability distributions from simulation.

---