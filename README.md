# Advanced Mathematics for Data Science (MASD)

This repository contains implementations of optimization methods studied in the "Advanced Mathematics for Data Science" (MASD) module. It includes various techniques for solving optimization problems, categorized by the type of methods and tasks.

## Table of Contents

- [Overview](#overview)
- [Structure](#structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Methods Implemented](#methods-implemented)
- [References](#references)

## Overview

The repository serves as a collection of implementations for optimization techniques, including:

1. Gradient descent methods (fixed step size, variable step size, Newton's method, Nesterov acceleration).
2. Non-differentiable optimization (subgradient and proximal methods).
3. Constrained optimization (projection methods).

These implementations were developed as part of hands-on sessions for the MASD module.

## Structure

The repository is organized into the following directories:

- **TP1: Gradient Descent**
  - Fixed step size gradient descent.
  - Variable step size gradient descent.
  - Newton's method.
  - Nesterov accelerated gradient.

- **TP2: Non-Differentiable Optimization**
  - Subgradient methods.
  - Proximal methods.

- **TP3: Constrained Optimization**
  - Projection methods for solving constrained optimization problems.

Each directory contains Python scripts with the corresponding implementations, along with examples and test cases.

## Methods Implemented

### TP1: Gradient Descent
- **Fixed Step Size:** Standard gradient descent with a fixed step size.
- **Variable Step Size:** Gradient descent with dynamically adjusted step sizes.
- **Newton's Method:** Second-order optimization using the Hessian.
- **Nesterov Accelerated Gradient:** Enhanced convergence using momentum.

### TP2: Non-Differentiable Optimization
- **Subgradient Methods:** Optimization for non-differentiable functions.
- **Proximal Methods:** Regularization techniques for optimization.

### TP3: Constrained Optimization
- **Projection Methods:** Optimization under constraints using projections onto feasible sets.

## References

- Lecture notes and materials from the MASD module.
