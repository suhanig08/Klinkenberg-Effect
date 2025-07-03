**Klinkenberg Effect** – Gas Permeability Analysis in Tight Formations

This project explores the **Klinkenberg effect**, which accounts for the increased permeability of gases in porous media due to slippage at low pressures. It's a key concept in petroleum engineering when dealing with gas flow through tight formations.

---

## Project Description

Using Python, this notebook demonstrates two methods for analyzing gas permeability data:

1. **Linear Regression** on measured gas permeability \(k_g\) vs inverse pressure \(1/p_m\) to estimate:
   - Absolute permeability \(k_L\)
   - Slip factor \(b\)

2. **Newton-Raphson Method** using an empirical model for \(b\) to solve for:
   - \(k_L\) at each data point
   - Predicted \(k_g\) using physics-based relationships

Both approaches are compared visually and numerically to show how theoretical and empirical models align with laboratory data.

---

##  Key Features

-  **Plots Measured vs Predicted \(k_g\)** for comparison
-  **Linear Regression Model** to extract \(k_L\) and \(b\)
-  **Newton-Raphson Solver** with empirical \(b = 6.9 \cdot k_L^{-0.36}\)
-  Supports lab data input via hardcoded arrays or CSV (optional)
-  Summary table comparing measured and predicted values

---
