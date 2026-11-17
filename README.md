# Monte Carlo Methods and Portfolio Simulation

**Theory, Convergence, and Applications to Risk Analysis**

Research article by Andrea Rostagno and Francesco Florio, published by Starting Finance Club PoliTo on 1 May 2026 as part of its Barrick Gold research series.

- [Published article](https://sfclubpolito.it/pdf-viewer.html?file=Pubblicazioni%2FMonte%20Carlo%20Methods%20and%20Portfolio%20Simulation.pdf&lang=it)
- [Official Python code, reproducibility instructions and outputs](https://github.com/StartingFinanceClubPoliTo/Research/tree/main/Barrick-Gold/Monte-Carlo-Risk)

## Research scope

The study applies Monte Carlo simulation to derivative pricing and portfolio risk. It covers geometric Brownian motion and jump-diffusion paths, European, Asian and barrier options, and variance reduction through antithetic variates, control variates, stratified sampling and importance sampling. The portfolio examples use simulated returns and terminal wealth to estimate value at risk (VaR) and conditional value at risk (CVaR).

## Reproducing the examples

Follow the setup in the official code companion. Its `requirements.txt` records the environment and `examples/run_reproducibility.py` regenerates the documented tables and figures. Consult the October 2026 corrections in the official README when comparing the regenerated outputs with the original article. The club repository is the source for the implementation and corrected results.
