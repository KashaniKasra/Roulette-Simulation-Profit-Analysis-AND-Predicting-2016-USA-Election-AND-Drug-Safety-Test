# Data Science Mini Projects

This project consists of three data science mini-projects focused on statistical simulation, inference, and data analysis, implemented using Python and Pandas.

---

## 1. Roulette Simulation and Profit Analysis

This task simulates the American roulette game with a focus on betting on black. The goals include:

- Simulating the game for various numbers of rounds (N = 10, 25, 100, 1000).
- Running Monte Carlo simulations (100,000 times) to estimate distributions of total and average winnings.
- Comparing theoretical expected values and standard errors with simulated outcomes.
- Using the Central Limit Theorem (CLT) to estimate the probability of casino loss.
- Analyzing why continued play benefits casinos.

---

## 2. 2016 US Presidential Election Prediction

Using polling data from the 2016 election, the tasks are:

- Estimating proportions and confidence intervals for Clinton and Trump support.
- Running Monte Carlo simulations to validate CI coverage.
- Cleaning and visualizing polling data over time.
- Aggregating observations and visualizing spread estimates using CLT.
- Performing hypothesis testing on the spread.

---

## 3. Drug Safety Statistical Testing

This section analyzes a drug trial dataset to evaluate side effects and lab measures:

- Comparing treatment (Drug) and control (Placebo) groups.
- Performing t-tests on WBC, RBC, number of adverse effects, and presence of adverse effects.
- Hypothesis formulation, p-value interpretation, and significance analysis at 0.05 and 0.1 levels.
- Use of statistical parameters like `equal_var` and `alternative` in hypothesis testing.

---

## Libraries Used

- `numpy`
- `pandas`
- `matplotlib`, `seaborn`
- `scipy.stats`

Each notebook section includes inline comments, visualizations, and statistical summaries to support interpretations.

## Files

- `CA0_notebook.ipynb`: Main notebook with implementations and plots.
- `drug_safety.csv`: Dataset for Task 3.
- `2016-general-election-trump-vs-clinton.csv`: Dataset for Task 2.

## Purpose

This assignment is a comprehensive introduction to core statistical concepts, real-world data analysis, and practical applications of probability and inference principles.