# Aviation Accident Analysis

## Overview

This lab simulated the analysis of U.S. aviation accident data. In this assignment, we assessed the safety performance of small (≤20 passengers) and large (>20 passengers) aircrafts using constraints and guidelines provided by our simulated client.

### Goal

Identify manufacturers (makes) and models associated with lower rates of aircraft destruction and lower fractions of fatal/serious passenger injuries.

#### Tools Used

- Jupyter Notebook
- Python
- Pandas
- NumPy
- Matplotlib

## Objectives

- Clean and prepare aviation accident data (1983–2023 filter applied).
- Separate aircraft into small and large passenger categories.

### Calculate Safety Metrics

- Mean fraction of fatal/serious injuries
- Mean aircraft destruction rate
- Compare manufacturers in each category
- Visualize injury rate distributions and identify top-performing makes
- Provide data-driven safety recommendations.

## Key Metrics

**Frac.Fatal.Serious**: Fraction of passengers fatally or seriously injured per accident
**Destroyed**: Binary indicator of total aircraft destruction

## Methods

- Grouped analysis by aircraft make
- Summary statistics (means, sorting, filtering top 10/15)

### Visualization

- Bar plots (mean comparisons)
- Violin plots (small aircraft distributions)
- Strip plots (large aircraft distributions)

## Results Summary

- Most accidents across top-performing makes result in **low serious/fatal injury fractions**.
- Large commercial manufacturers generally show very **low destruction rates**.
- Safety distributions are right-skewed, with ((most observations concentrated at zero injury)).