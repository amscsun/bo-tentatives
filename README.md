# bo-tentatives

## Introduction

The `bo-tentatives` repo is for writing a Python package on top of the `GPy` and `GPyOpt` package for the implementation of two ongoing papers:

  1. Lipschitz Bayesian Optimization with Gradient.
  2. Automatic Bayesian Optimization

The first requires computation of the gradient from a fitted GP regression model, with a new optimization routines that computes the parameters for ensuring a certain Lipschitz condition on the unknown function.

The second performs automatic data warping before performing BO, and aims at developing a variational inference technique for jointly sample the kernel parameters and transformation parameters from the estimated posterior.

### Lipschitz Bayesian Optimization with Gradients
