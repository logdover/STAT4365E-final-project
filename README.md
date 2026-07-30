# Exit Velocity to Expected Value: Predicting 2023 Offensive Production

A data science project analyzing MLB Statcast data to predict hitter performance (OPS) using physical contact profile metrics.

---

## Project Overview
This project evaluates how well raw physical contact characteristics explain overall hitting success. Using 2023 Statcast data (N = 133 qualified hitters), we built and evaluated regression models to identify the impact of exit velocity, launch angle, and whiff rates on On-Base Plus Slugging (OPS).

---

### Visualizations

#### Correlation Heatmap
![Correlation Heatmap](correlation_heatmap.png)

#### OLS Test Set Residual Plot
![Residual Plot](ols_residual_plot.png)

---

## Tech & Dependencies
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `statsmodels`, `scikit-learn`, `matplotlib`, `seaborn`

To install dependencies locally:
```bash
pip install -r requirements.txt
