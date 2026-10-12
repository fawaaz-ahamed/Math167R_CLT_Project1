# Math167R Project 1: Central Limit Theorem and Monte Carlo Simulation

This project investigates the sampling distribution of the mean using Monte Carlo simulation.

For each population, I generated 10,000 repeated samples using sample sizes of 5, 10, 20, 30, 50, and 100. I compared histograms, normal Q–Q plots, simulated means, standard errors, skewness, and excess kurtosis.

## Required Distributions

- Standard normal
- Six-sided die
- Exponential
- Small binomial
- Cauchy

## Extra-Credit Distributions

- Dependent machine failure
- Non-identical basketball shots
- Custom age-at-death distribution

## Files

Each numbered Quarto file contains the population description, simulation design, R functions, graphs, numerical evidence, interpretation, and conclusion.

The project uses student-ID seed `6424` for reproducibility.

## Main Conclusion

The Central Limit Theorem generally worked more quickly for symmetric populations and required larger sample sizes for skewed populations. The Cauchy and dependent processes demonstrated important limitations of the usual assumptions.