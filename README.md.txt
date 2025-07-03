# Klinkenberg Effect – Gas Permeability Analysis

This project demonstrates the analysis of gas permeability in porous media using the **Klinkenberg effect**. It includes:

✅ Linear regression to determine absolute permeability and slip factor  
✅ Newton-Raphson method with empirical slip factor to estimate permeability  
✅ Side-by-side comparison of predicted and actual permeability  
✅ Clear plots and summary tables  
✅ Beginner-friendly, well-commented code  

---

## 📊 Inputs

- Lab data: Measured gas permeability `k_g` and mean pressure `p_m`
- Data can be hardcoded or read from a `.csv`

---

## 📈 Outputs

- Linear regression plot of `k_g` vs `1/p_m`
- Comparison plot of measured vs predicted `k_g`
- Newton-Raphson iteration results
- Summary table with all computed values

---

## 🛠 How to Run

1. Install required packages:
```bash
pip install numpy pandas matplotlib scikit-learn
