# Multi-City Epidemic Simulation using the SIR Model

## Overview

This project explores epidemic spread using the classical
SIR (Susceptible–Infected–Recovered) epidemiological model.

The model was extended to simulate disease transmission across
multiple cities connected by a mobility matrix.

The project was conducted at Coe College under the supervision
of Prof. Johnathan White.

---

## Model

The SIR model divides the population into three groups:

S – Susceptible  
I – Infected  
R – Recovered  

The simulation framework was extended to include **three cities
(total population ≈ 30,000)** connected through a daily mobility matrix.

Migration rates between cities ranged from **5–15%**.

---

## Implementation

The simulation was implemented in Python using:

- NumPy
- Pandas
- Matplotlib

Key parameters such as infection rate (β) and recovery rate (γ)
were calibrated to realistic epidemiological ranges.

---

## Results

The simulations produced visualizations including:

- Infection curves
- Heatmaps of infection spread
- Cross-city infection timing

The results demonstrate how inter-city mobility influences
infection peaks and disease spread.

This work was presented at the **MUMS Conference 2024**.

---

## Research Output

poster.pdf – conference poster describing the model and findings.

---

## Author

Shuyun (Esther) Chen  
Mathematics Student, Coe College
