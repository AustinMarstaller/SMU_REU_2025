# Week 3





## Lecture 2: Intro to ROM

### Motivation

To understand a complex problem, first distill it into a simple problem. The context here are physical phenomena in the so-called real world: inverse imaging problems (e.g., using radar), computational fluid dynamics, etc.

Such problems can often be framed as systems of ordinary (resp. partial) differential equations (ODE). To perform simulations, the solutions to these systems of ODEs must be numerically approximated. This can require intense computing capabilities depending on the problem. Naturally, we arrive at our problem of interest: come up with a **surrogate model** for the full-scale model while maintaining low error. These models live in lower-dimensional spaces than their full-scale counterpart and therefore also take the name of a reduced order model. 

:::{important} Model Reduction
Real life problems require modeling increasingly complex physical phenomena. Model reduction techniques aim to provide a surrogate model while maintaining a degree of accuracy. Such problems are at the forefront of Applied Mathematics research.
:::

Generically, the following tools are what is required in the coming lectures:

- Mathematical tools
    * Numerical Linear Algebra: various matrix decompositions, inner products, norms, etc.
    * Laplace transform,
    * Control theory

