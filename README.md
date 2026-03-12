# Empirical Analysis: Energy Poverty and the Fiscal Impact of the German Energy Transition (1995–2025)

## Executive Summary

While the expansion of renewable energy is recognized as a technological success (growing from 2% in 1995 to nearly 20% of total consumption by 2025), the fiscal implementation of the German "Energiewende" has produced a significant social imbalance.

Empirical evidence demonstrates that **Energy Poverty in Germany**, defined as spending more than 10% of net equivalent income on energy, has surged from 2% to 12% of the population. Analysis indicates that this is not primarily a market failure, but a state-induced crisis caused by high taxes, levies, and network charges, which disproportionately burden low-income households.

---

## Core Research Findings

- **The 12% Threshold:** Approximately 8 million people in Germany currently live in energy poverty.  
- **Fiscal Burden:** In the absence of state-imposed taxes and levies, the number of households in energy poverty would be reduced by approximately two-thirds. The disparity between net and gross electricity prices has been identified as the primary driver of social inequality.  
- **The Investment Trap:** Low-income tenants are affected by a "split incentive" problem. They are unable to invest in efficiency measures (PV, heat pumps), leaving them fully exposed to rising state-driven energy prices due to near-zero price elasticity.

---

## Methodology & Assumptions

To ensure academic rigor and comparability, a standardized model was developed based on Eurostat raw data and the follwoing assumptions:

- **Model Household:** 3 persons, 70 sqm living space.  
- **Energy Demand:** 120 kWh/sqm for heating + 4,000 kWh/year for electricity.  
- **Economic Metric:** The OECD Equivalence Scale was applied to simulate income distribution deciles from 1995 to 2025.  
- **Disparity Analysis:** Energy burdens were calculated both with and without taxes/levies to isolate the effect of government intervention.

---

## Policy Recommendations: A Market-Based Approach

Two solutions have been suggested to mitigate social hardship without compromising the ecological steering effect of prices:

### 1. Basic Contingent Levy Waiver (Rejected)

- **Concept:** Levies are waived for a baseline consumption amount.  
- **Critique:** High "deadweight loss" (Mitnahmeeffekte) arises, as high-income earners also benefit. A Rebound Effect may occur, weakening incentives for energy efficiency and technological innovation.

### 2. Targeted Fiscal Refund (Recommended)

- **Concept:** A "State Refund" system provides targeted tax rebates to households exceeding the 10% burden threshold.  
- **Advantage:** The method ensures the highest precision (Zielgenauigkeit) and preserves the market price signal for the majority of the economy, maintaining overall economic efficiency.  
- **Implementation:** Administration is feasible via the income tax declaration to minimize bureaucracy.  
- **Fiscal Impact:** Simulation results indicate that the total cost to the German state would be approximately €1.6 billion (2024). Compared to broad-based subsidies, this represents a highly cost-effective and fiscally responsible approach to securing social acceptance of the energy transition.

---

## Technical Implementation

The project relies on a robust Python-based data pipeline:

- **Data Integration:** Automated normalization handles Eurostat methodology shifts (e.g., the 2007 change).  
- **Statistical Modeling:** Monte Carlo-adjacent simulations of income distributions were performed.  
- **Visualization:** Matplotlib-based delta-plots illustrate the "Tax Gap" in energy affordability.

---

## Author

**Maximilian Starp**  
Dual Degree Student: B.Sc. Physics & B.Sc. Mathematics | University of Bonn  

---

**Disclaimer:** This analysis advocates for an energy transition that balances ecological necessity with fiscal discipline and the principles of a Social Market Economy.