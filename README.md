# Biosignatures
Global Sensitivity Analysis on Bayesian Inference for in situ Biosignatures

# Description

This R project computes the first and second order Sobol' indices for a Bayesian statistical model developed in my Master's thesis\
on the basis of `Catling et al. 2018` (full reference below).

The statistical model is based on the iterative Bayesian inference below:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;P(biogenic|signature,C)=\frac{P(signature|C, biogenic)\*\P(biogenic|C)}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />

The Sobol' method is an advanced variance-based sensitivity analysis technique to quantify the interactions between a model\
variables. For more information about the Sobol' method see `https://en.wikipedia.org/wiki/Variance-based_sensitivity_analysis`.

