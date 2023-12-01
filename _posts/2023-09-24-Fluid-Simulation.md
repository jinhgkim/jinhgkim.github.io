---
layout: post
title: Fluid Simulation
date: 2023-09-24 04:49:16
description: A tutorial to simulate fluid dynamics
tags: graphics physics
categories: personal-projects
---

Coming soon!

2D Fluid Simulation: <br />
First, construct a computational grids with the size of N+2. The additional layer plays a role as defining the boundary conditions. <br />
Each cell is a fluid object, which contains two information, velocity and density. <br />

Start from learning mesh generation

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/FluidGrid.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<br />
## References <br />

- [Real-Time Fluid Dynamics for Games](https://www.dgp.toronto.edu/public_user/stam/reality/Research/pdf/GDC03.pdf) by Jos Stam <br />
- [Fluid Simulation for Dummies](https://mikeash.com/pyblog/fluid-simulation-for-dummies.html) by Mike Ash <br />
