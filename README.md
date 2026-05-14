# Quantitative Portfolio Replication

Dynamic portfolio replication using Hierarchical Risk Parity, Elastic Net, GARCH and Kalman Filters.

## Overview

This project develops a quantitative framework for replicating a diversified benchmark portfolio using systematic allocation and risk-management techniques.

The workflow includes benchmark construction, volatility modeling, portfolio replication, rolling-window backtesting, transaction cost analysis and risk-adjusted performance evaluation.

## Methods

- Hierarchical Risk Parity for benchmark portfolio construction
- GARCH volatility forecasting
- Elastic Net regression for sparse portfolio replication
- Kalman Filter for dynamic allocation
- Value-at-Risk based risk scaling
- Rolling-window backtesting
- Transaction cost modeling
- Fama-French factor exposure analysis

## Key Results

- The log return-based Kalman Filter provided the best trade-off between tracking accuracy, portfolio stability and interpretability, outperforming standard return-based approaches in empirical replication tests.

- Hierarchical Risk Parity enabled the construction of a diversified and robust benchmark portfolio without relying on unstable covariance matrix inversion.

- Elastic Net regression achieved stable out-of-sample portfolio tracking while controlling model sparsity and turnover.

- Monthly Ridge regression reduced transaction costs and portfolio drift through lower-frequency rebalancing and simpler regularization.

- Volatility forecasting through GARCH models improved the understanding of market risk regimes and supported dynamic risk management.

- Dollar-Cost Averaging (DCA) analysis showed that the replication framework remains competitive under realistic retail investment behavior.

- The overall framework demonstrates that transparent and rule-based portfolio replication can provide low-cost access to alternative investment exposures using liquid instruments.

  
## Repository Structure

```text
.
├── quantitative-portfolio-replication.ipynb
├── Dataset3_PortfolioReplicaStrategy.xlsx
├── Dataset3_PortfolioReplicaStrategy2.xlsx
└── README.md
