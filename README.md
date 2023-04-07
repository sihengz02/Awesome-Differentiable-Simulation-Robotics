# Awesome-Differentiable-Simulation-Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Physics-based and Learning-based Differentiable Simulation papers relating to Robotics/Graphics domain**, inspired by [awesome-implicit-nerf-robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) <br>

#### Please feel free to send me [pull requests](https://github.com/Hilbert-Johnson/Awesome-Differentiable-Simulation-Robotics/blob/main/how-to-PR.md) or [email](mailto:zhaosh@smail.nju.edu.cn) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

---
## Overview

  - [Articulated Body Simulation](#articulated-body-simulation)
  - [Cloth Simulation](#cloth-simulation)
  - [Soft Body Simulation](#soft-body-simulation)
  - [Rigid Body and Cloth/Deformable Coupling](#rigid-body-and-clothdeformable-coupling)
  - [Learning for Simulation](#learning-for-simulation)
  - [Survey](#survey)
  - [Citation](#citation)

---
## Articulated Body Simulation

* End-to-end differentiable physics for learning and control, *Neurips, 2018*. [[Paper](https://proceedings.neurips.cc/paper/2018/hash/842424a1d0595b76ec4fa03c46e8d755-Abstract.html)]
* A differentiable physics engine for deep learning in robotics, *Front. Neurorobot, 2019*. [[Paper](https://www.frontiersin.org/articles/10.3389/fnbot.2019.00006/full?ref=https://githubhelp.com)]
* Efficient Differentiable Simulation of Articulated Bodies, *ICML, 2021*. [[Paper](https://arxiv.org/abs/2109.07719)]
* **Nimble**: Fast and feature-complete differentiable physics for articulated rigid bodies with contact, *RSS, 2021*. [[Paper](https://arxiv.org/pdf/2103.16021)]
* **Dojo**: A Differentiable Simulator for Robotics, *CoRL, 2022*. [[Paper](https://arxiv.org/abs/2203.00806)]
* **Brax**: A Differentiable Physics Engine for Large Scale Rigid Body Simulation, [[code](https://github.com/google/brax)]

---
## Cloth Simulation
* Differentiable Cloth Simulation for Inverse Problems, *Neurips, 2019*. [[Paper](https://proceedings.neurips.cc/paper/2019/hash/28f0b864598a1291557bed248a998d4e-Abstract.html)]
* DiffCloth: Differentiable Cloth Simulation with Dry Frictional Contact, *SIGGGRAPH, 2022*. [[Paper](https://people.csail.mit.edu/liyifei/publication/diffcloth/)]

---
## Soft Body Simulation

* **ChainQueen**: A Real-Time Differentiable Physical Simulator for Soft Robotics, *ICRA, 2019*. [[Paper](https://ieeexplore.ieee.org/abstract/document/8794333)]
* Differentiable Simulation of Soft Multi-body Systems, *Neurips, 2021*. [[Paper](https://arxiv.org/abs/2202.08227)]
* **DiffPD**: Differentiable projective dynamics, *TOG, 2021*. [[Paper](https://arxiv.org/abs/2101.05917)]
---
## Rigid Body and Cloth/Deformable Coupling

* Scalable Differentiable Physics for Learning and Control, *ICML, 2020*. [[Paper](https://arxiv.org/abs/2007.02168)]
* ADD: Analytically differentiable dynamics for multi-body systems with frictional contact, *TOG, 2020*.  [[Paper](https://arxiv.org/abs/2007.00987)]

---
## Learning for Simulation
* Learning particle dynamics for manipulating rigid bodies, deformable objects, and fluids, *ICLR, 2019*. [[Paper](https://arxiv.org/abs/1810.01566)]
* Learning to simulate complex physics with graph networks, *ICML, 2020*. [[Paper](https://proceedings.mlr.press/v119/sanchez-gonzalez20a.html)]
* Differentiable Physics Simulation of Dynamics-Augmented Neural Objects, *arXiv, 2022*. [[Paper](https://arxiv.org/abs/2210.09420)]
* Learning Multi-Object Dynamics with Compositional Neural Radiance Fields, *CoRL, 2022*. [[Paper](https://openreview.net/pdf?id=qUvTmyGpnm7)]

---
## Survey
* Differentiable Physics Simulation, *ICLR Workshop, 2020*. [[Paper](https://openreview.net/pdf?id=p-SG2KFY2)]
* Differentiable Physics Simulations with Contacts: Do They Have Correct Gradients w.r.t. Position, Velocity and Control, *ICML Workshop, 2022*. [[Paper](https://arxiv.org/abs/2207.05060)]

----
## Citation
If you find this repository useful, please consider citing this list:
```
@misc{zhao2023differentiablesimulationresources,
    title = {Awesome Differentiable Simulation - A curated list of resources on Physics-based and Learning-based Differentiable Simulation relating to robotics and graphics},
    author = {Siheng Zhao},
    journal = {GitHub repository},
    url = {https://github.com/Hilbert-Johnson/Awesome-Differentiable-Simulation-Robotics},
    year = {2023},
}
```
