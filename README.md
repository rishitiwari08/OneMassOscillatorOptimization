# One-Mass Oscillator Optimization

## Overview
This project applies various optimization techniques to fit a one-mass oscillator model to real-world data. The goal is to determine optimal values for system parameters to minimize residuals between observed and predicted amplitudes.

## Optimization Methods Used
- Nelder-Mead
- Dual Annealing
- Differential Evolution
- Powell’s Method
- L-BFGS-B

## Repository Structure
- `data/` - Contains the datasets (`df1.pkl`, `df2.pkl`).
- `src/` - Contains the main optimization script.
- `notebook_result/` - Jupyter Notebook in pdf for visualization.

## Installation
Run the following to install dependencies:
```bash
pip install -r requirements.txt
