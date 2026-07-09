# Hierarchical Risk Parity with Nonlinear Latent Covariance Filtering

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21270553.svg)](https://doi.org/10.5281/zenodo.21270553)

This repository presents a reproducible implementation of **Hierarchical Risk Parity (HRP)** enhanced through **nonlinear latent covariance filtering** using deep Autoencoders.

The framework employs a rolling walk-forward optimization procedure to dynamically reconstruct covariance structures from nonlinear latent representations before portfolio allocation.

## Methodology

The implementation includes:
- Hierarchical Risk Parity (HRP)
- Deep Autoencoder covariance filtering
- Rolling walk-forward backtesting
- Out-of-sample empirical validation

## Performance Evaluation

The framework evaluates:
- Annualized Volatility
- Maximum Drawdown
- Annualized Sharpe Ratio
- Portfolio Turnover
- Effective Number of Assets (Neff)

## Repository Contents

- `Hierarchical Risk Parity with N...`: Main Jupyter Notebook with the full implementation.
- `df_stocks.xlsx`: Baseline asset dataset used for backtesting replication.
- `LICENSE`: MIT License.

## Citation

If you use this framework or dataset in your research, please cite it as:

```text
Ramírez-Carrillo, G. (2026). Hierarchical Risk Parity with Nonlinear Latent Covariance Filtering (Version v1.0.1). Zenodo. [https://doi.org/10.5281/zenodo.21270553](https://doi.org/10.5281/zenodo.21270553)
