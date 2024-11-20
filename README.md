# Supply Chain Optimization: Outsourcing and Near-Sourcing in the Apparel Industry

This project focuses on analyzing and optimizing supply chain strategies in the apparel industry through simulation and regression modeling. Two sourcing scenarios were examined:

Scenario A: Complete outsourcing to a manufacturer in Ukraine.
Scenario B: A hybrid model combining outsourcing with near-sourcing for additional flexibility.
The study uses historical data, linear regression, and simulation to forecast demand, analyze profits, and assess risk for various order quantities.

## Introduction

The project explores insourcing, outsourcing, and near-sourcing in supply chain management for a company preparing to launch a new Limited Edition Collection (LEC) of shirts. The goal is to evaluate sourcing strategies by:

Forecasting demand using linear regression.
Simulating net profits for various order quantities.
Assessing the trade-offs between cost, risk, and profitability.

## Key Features

Demand Forecasting: Linear regression model to predict demand based on season duration and holiday periods.
Scenario Analysis:
Outsourcing: Fixed lead times and costs from a Ukrainian manufacturer.
Near-Sourcing: Flexible local sourcing for additional demand coverage.
Simulation Models: 1,000 iterations to calculate profit distributions for both scenarios.

Methodology

1. Linear Regression
Independent Variables:
Holiday periods (categorical).
Duration of the sales period (numeric).
Outcome:
A significant model with an adjusted r2 =0.85, predicting sales with high accuracy.
2. Simulation
Simulated demand errors using a normal distribution (μ=0,σ=112.09).
Calculated profits based on:
  Selling price.
  Refund value for unsold items.
  Fixed costs for outsourcing and near-sourcing.
Evaluated metrics:
  Average profit.
  Risk (standard deviation of profit).
  Minimum and maximum profit.

## Results

Scenario A: Complete Outsourcing
Optimal Order Quantity: ~290 units.
Characteristics:
Higher risk with a greater standard deviation of profit.
Maximum profitability at higher order sizes but diminishing returns.
Scenario B: Hybrid Model
Optimal Order Quantity: ~260 units.
Characteristics:
Steadier profit growth and reduced variability.
More efficient risk management.
 -- > Conclusion: Scenario B demonstrates a superior balance between profitability and risk, making it a more flexible and viable sourcing strategy.

## Assumptions

Demand errors follow a normal distribution (μ=0,σ=112.09).
Fixed costs:
Outsourcing: $65/unit.
Near-Sourcing: $95/unit.
Unsold units refunded at $15/unit.
Near-sourcing capacity limited to 156 units (12 units/day over 13 days).

## Limitations

Small dataset for regression analysis (23 LEC seasons).
Limited exploration of promotion effects on demand.
Simplistic assumptions about holiday impacts and near-sourcing capacities.

## License

This project is licensed under the MIT License.
