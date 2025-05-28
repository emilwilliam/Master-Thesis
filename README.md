# Beyond Single Factors: Multifactor Volatility-Timing in Norway

This is the replication code for the master thesis "Beyond Single Factors: Multifactor Volatility-Timing in Norway", as part of an MSc in Finance at BI Norwegian Business School, with credits transferred to an MSc in Financial Engineering at EDHEC Business School as well. Supervised by Tong Zhang, the thesis was completed in 2025.

## Thesis Overview

We study whether volatility-timing strategies applied to well-known asset pricing factors improve risk-adjusted returns in the Norwegian stock market. We do it by constructing individual-factors, individual-factor portfolios and mean-variance multifactor portfolios, applying volatility management techniques based on factor and market volatility, and evaluating their out-of-sample performance. We find that individual volatility-managed factors and individual volatility-managed factor portfolios generally fail to deliver statistically significant improvements, whereas a volatility-managed multifactor portfolio based on market volatility achieves a modestly significant Sharpe ratio increase. We conclude that while volatility-timing may enhance performance under specific conditions, the results lack robustness when accounting for time periods, factor dependencies, and real-world frictions, questioning their practical applicability.

## Repository Structure

Beyond-Single-Factors_Multifactor-Volatility-Timing-in-Norway/: The thesis. 

Code/: Contains scripts for replicating the analysis, including volatility-managed factor construction, portfolio optimization, and performance evaluation using Python. Key methodologies follow Moreira and Muir (2017) and DeMiguel et al. (2024).

Code/Plots: Output figures (e.g., risk-return trade-offs, portfolio weights) as presented in the thesis.

Code/Tables: Output tables (e.g., performance metrics, Sharpe ratios) as presented in the thesis.