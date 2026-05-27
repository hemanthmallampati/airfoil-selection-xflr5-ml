# Airfoil Selection for a General Aviation Trainer using XFLR5 & Machine Learning

## Overview
This project focuses on selecting the optimal airfoil for a General Aviation (GA) trainer aircraft by combining classical aerodynamic analysis in XFLR5 with a Machine Learning prediction model built in Python.

## Airfoils Analysed
- NACA 2412
- NACA 4412
- NACA 23012
- NACA 63215
- NACA 64A210

## Tools & Technologies
- **XFLR5** — Aerodynamic analysis and polar curve generation
- **Python** — ML model development
- **NumPy, Pandas** — Data processing
- **Scikit-learn** — Regression model for CL, CD, CM prediction
- **Matplotlib** — Visualisation of aerodynamic coefficients

## What Was Done
- Generated polar data (.plr) for each airfoil across a range of angles of attack
- Plotted CL vs α, CD vs α, CL/CD vs α, and CM vs α curves
- Built a supervised ML regression model to predict aerodynamic coefficients
- Selected the optimal airfoil based on best lift-to-drag ratio for low Reynolds number trainer conditions

## Results
Final airfoil selection showed approximately **15% improvement in L/D ratio** over the baseline configuration.

## Repository Structure
├── Airfoil_ML_DSU_v2.ipynb   # ML model and analysis notebook
├── naca 2412.txt / .plr      # XFLR5 polar data files
├── naca 4412.txt / .plr
├── naca 23012.txt / .plr
├── naca 63215.txt / .plr
├── naca 64a210.txt / .plr
└── graphs                    # Aerodynamic coefficient plots

---
*Part of undergraduate research in aerodynamics and data-driven aircraft design.*
