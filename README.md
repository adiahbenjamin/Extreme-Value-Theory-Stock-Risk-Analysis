# Extreme Value Analysis of Stock Returns Using the Generalized Pareto Distribution

## Overview

This project applies Extreme Value Theory (EVT) to model extreme movements in stock returns and assess potential market risks. The analysis focuses on identifying extreme losses using the Peaks Over Threshold (POT) approach and fitting the Generalized Pareto Distribution (GPD) to exceedances beyond selected thresholds.

The study estimates tail risk measures including Value-at-Risk (VaR) and Expected Shortfall (ES), which are widely used in financial risk management.

## Objectives

* Identify extreme negative stock returns using EVT methods.
* Select appropriate thresholds using Mean Excess and parameter stability plots.
* Estimate GPD parameters (shape and scale).
* Evaluate the goodness-of-fit of the fitted distribution.
* Calculate VaR and Expected Shortfall at different confidence levels.

## Methodology

The analysis follows the Peaks Over Threshold (POT) framework:

1. Daily stock returns are calculated.
2. Negative returns are transformed into positive losses.
3. Extreme losses exceeding a chosen threshold are extracted.
4. A Generalized Pareto Distribution is fitted to model tail behaviour.
5. Risk measures are estimated using the fitted GPD model.

## Tools Used

* R Programming
* Extreme Value Theory
* Generalized Pareto Distribution (GPD)
* POT and evir packages
* Statistical modelling
* Risk measurement (VaR & ES)

## Key Findings

The results demonstrate how EVT can capture extreme market events beyond the assumptions of traditional risk models. The fitted GPD model provides estimates of potential extreme losses and tail risk exposure.

## Author

Benjamin Adiah
BSc Statistics Graduate | Data Analytics | Risk Modelling

