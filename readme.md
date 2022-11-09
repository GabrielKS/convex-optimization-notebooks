# Convex Optimization Notebooks

Gabriel Konar-Steenberg, fall 2022

## Overview

In fall 2022, I took *MATH306 Optimization*, a graduate-level course on convex optimization at Claremont Graduate University taught by Prof. Marina Chugunova. This repository contains some of my computational solutions to problems posed in that class, which I present as lightly edited Jupyter notebooks. Solutions are posted with the permission of the professor.

## Table of Contents

The files in order of writing are:

 1. `ellipsoid_method.ipynb`: implementation and graphical demonstrations of the [ellipsoid method](https://en.wikipedia.org/wiki/Ellipsoid_method)
 2. `conjugate_gradient_method.ipynb`: implementation of the [conjugate gradient method](https://en.wikipedia.org/wiki/Conjugate_gradient_method)
 3. `gradient_descent_step_regimes.ipynb`: implementation of a generic [gradient descent](https://en.wikipedia.org/wiki/Gradient_descent) algorithm and experimentation with several methods of choosing the step size
 4. `geometric_gradient_descent.ipynb`: implementation of the [geometric gradient descent](https://arxiv.org/abs/1506.08187) algorithm
 5. `damped_newton_method_variants.ipynb`: implementation of the [damped Newton's method](https://en.wikipedia.org/wiki/Newton%27s_method_in_optimization) and an investigation of ways to speed it up computationally

## Conventions and Other Notes

 * Each file is self-contained, so there is some repetition of common functions.
 * In files 1-4, the gradient and, where relevant, the Hessian are approximated numerically. In file 5, the gradient and Hessian are solved analytically ahead of time.

## Sources

 * My main textbook; all references to "Boyd" are to this source unless otherwise noted:

 > Boyd, S. P., & Vandenberghe, L. (2004). [Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf). Cambridge University Press.

 * Another frequently consulted source; all references to "Bubeck" are to this source unless otherwise noted:

 > Bubeck, S. (2015). [Convex Optimization: Algorithms and Complexity](https://doi.org/10.1561/2200000050). Foundations and Trends in Machine Learning, 8(3–4), 231–357.

 * From time to time, I reference a list of additional exercises associated with the Boyd textbook; this is typically notated with "Boyd 'Additional Exercises'":

 > Boyd, S. P., & Vandenberghe, L. (2016). [Additional Exercises for Convex Optimization](https://stanford.edu/~boyd/cvxbook/bv_cvxbook_extra_exercises.pdf).

