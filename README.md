# Andes Virus Transmission & Control on Contact Networks

**Stochastic epidemiology · Network science · SEIR/SEIQR · Intervention simulation**

> Academic team project (Simulation and Modeling, Bocconi University). The simulated Italian coastal outbreak is **hypothetical** and the estimates are illustrative, not forecasts.

## Overview
We model a hypothetical introduction of Andes hantavirus (ANDV) into a structured coastal community, combining deterministic SEIR/SEIQR dynamics with stochastic transmission over a synthetic contact network. The analysis compares no intervention, symptomatic isolation, contact tracing and quarantine, and ring quarantine.

## Approach
- Synthetic population of **10,000** individuals, including household clustering and age-structured close contacts.
- Deterministic compartmental models for epidemic trajectories and intervention thresholds.
- Monte Carlo network simulations to capture stochastic extinction and outbreak variability.
- Sensitivity and robustness analyses across model parameters and contact structures.

## Selected findings (reported in the project report)
- **39%** of baseline stochastic introductions generated a major outbreak.
- Mean final attack rate across baseline simulations: **32.3%**.
- Symptomatic isolation reduced major-outbreak probability to **22%**; adding contact tracing reduced it to **18%**.
- Under the report's baseline assumptions, the analytical critical tracing-efficiency threshold was approximately **75%**.

These are model-specific results under stated assumptions, not estimates for an actual Italian outbreak.

## Files
- [`ANDV_Simulation.ipynb`](ANDV_Simulation.ipynb) — analysis and simulations.
- [`ANDV_Report.pdf`](ANDV_Report.pdf) — full methodology, results, limitations and references.

## Run locally
Install the packages in `requirements.txt`, then open the notebook in Jupyter. Some runs may be computationally intensive; execution has **not** been independently verified in this packaged version.

## Credits
Group project by **Alice Agazzi, Greta Dell'Amico, Marco Lazzeri and Michela Tomasoni**. This repository presents collaborative academic work; individual contributions are not separately attributed in the supplied report.

## Notes
Review co-author consent and university sharing rules before publishing the full report or notebook. No license is granted by default.
