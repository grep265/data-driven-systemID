# Data driven system ID

This repository contains several examples of the data driven system identification techique called SINDy. SINDy (Sparse Identification of Nonlinear Dynamics) is a powerful data-driven method for discovering the governing equations of complex dynamical systems. It uses sparse regression techniques to identify a set of functions that best describe the system's behavior from time-series data.

Steps:
1. Data Collection: Time-series measurements of the system state are gathered
2. Library Construction: A library of candidate nonlinear functions is created
3. Sparse Regression: The algorithm identifies the most relevant terms from the library to describe the system dynamics
4. Model Formation: The selected terms are combined to form the governing equations

## List of examples

* [Example 1: Exponential & trigonometric](https://github.com/grep265/data-driven-systemID/blob/main/SINDy-example1.ipynb)
* [Example 2: Linear system](github.com/grep265/data-driven-systemID/blob/main/SINDy-example2.ipynb)
* [Example 3: Cubic](https://github.com/grep265/data-driven-systemID/blob/main/SINDy-example3.ipynb)
* [Example 4: Lorenz system](https://github.com/grep265/data-driven-systemID/blob/main/SINDy-example4.ipynb)

## References
[An introduction to Sparse Identification of Nonlinear Dynamical systems (SINDy)](https://pysindy.readthedocs.io/en/latest/examples/2_introduction_to_sindy/example.html)

[PYSINDy](https://github.com/dynamicslab/pysindy/blob/master/examples/3_original_paper.ipynb)

[Decoding Dynamics: A Quick Guide to SINDy](https://humaticlabs.com/blog/sindy-guide/)
