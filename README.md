# Monte Carlo Simulation of OLS Estimators

This project uses Monte Carlo simulations to study the statistical properties of OLS estimators under different data-generating processes.

## Overview
The notebook investigates how OLS performs in finite samples under:
- Standard exogenous regressors
- Endogeneity
- Time-series dependence (AR(1) errors)

Monte Carlo methods are used to evaluate bias and RMSE across repeated simulations.

## Experiments
1. **Baseline OLS (Exogenous Regressors)**  
   - Simulated data with independent regressors  
   - OLS estimates are shown to be unbiased and consistent

2. **OLS with Endogeneity**  
   - Introduces correlation between regressors and error terms  
   - Demonstrates persistent bias that does not vanish with more simulations

3. **Time-Series Case: AR(1) Errors**  
   - Simulates serially correlated errors  
   - Examines the distribution of OLS coefficient estimates

## Methods
- Monte Carlo simulation
- OLS with robust standard erro
