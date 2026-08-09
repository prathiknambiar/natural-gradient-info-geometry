# Natural Gradient & Information Geometry

An independent research project exploring the theoretical foundations of 
natural gradient descent through the lens of information geometry.

## Research Question
Why does natural gradient descent outperform vanilla gradient descent, 
and how does the geometry of the Fisher information matrix govern 
optimization behavior in statistical models and neural networks?

## Background
Standard gradient descent operates in parameter space, which has no 
natural geometric structure. Information geometry, pioneered by Amari (1998), 
treats families of probability distributions as Riemannian manifolds equipped 
with the Fisher information metric — revealing that the natural gradient 
is the true steepest descent direction in distribution space.

## Experiments
- `experiments/01_gaussian_1d.py` — Natural vs vanilla gradient descent 
  for 1D Gaussian mean estimation
- `experiments/02_gaussian_2d.py` — 2D case estimating μ and σ 
  simultaneously (in progress)

## References
- Amari, S. (1998). Natural Gradient Works Efficiently in Learning. 
  Neural Computation.
- Murray, I. (2019). A Gentle Introduction to Information Geometry.

## Status
Active — ongoing experiments and writeup in progress.
