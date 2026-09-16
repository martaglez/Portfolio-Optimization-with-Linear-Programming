# Portfolio Optimization with Linear Programming

This project focuses on optimizing the allocation of **$100,000** between stocks, bonds and a savings account using **Linear Programming**.

The objective is to maximize expected return while satisfying diversification constraints:

* Maximum 50% invested in stocks
* Minimum 20% invested in savings
* Non-negative investments

## Results

The optimal allocation is:

| Asset               | Investment |
| ------------------- | ---------: |
| Stocks              |    $50,000 |
| Bonds               |    $30,000 |
| Savings             |    $20,000 |
| **Expected return** | **$5,900** |

## Sensitivity Analysis

The project also studies how the optimal portfolio changes when modifying:

* The maximum percentage invested in stocks
* The minimum percentage invested in savings
* The expected return of each asset

Shadow prices are also analysed to understand the effect of the constraints on the objective function.

## Simplex Method

A symbolic version of the **Simplex Method** was implemented using **SymPy**, including the construction of the tableau and pivot operations with parameters α and β.

## What I Learned

* Formulating optimization problems using mathematical constraints
* Solving Linear Programming problems with **PuLP**
* Performing sensitivity analysis and interpreting shadow prices
* Implementing Simplex operations with **SymPy**
* Understanding how changes in model parameters affect the optimal solution

## Technologies

**Python · PuLP · SymPy · Linear Programming · Simplex Method**
