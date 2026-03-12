# ⚽ Predictive Modeling & Player Valuation Engine (EA FC 24)

## 📌 Project Overview
This project focuses on sports analytics and predictive modeling using the EA FC 24 (FIFA) dataset. The goal is to build a valuation and recommendation engine capable of estimating a player's overall rating and market value based on over 100 in-game statistics (pace, dribbling, potential, etc.).

## ⚙️ Technical Stack
* **Language:** Python
* **Libraries:** Pandas, Scikit-Learn, Matplotlib
* **Techniques:** Principal Component Analysis (PCA), Predictive Regression, Missing Data Imputation.

## 🛠️ Pipeline & Architecture
1. **Data Preprocessing:** Handled missing values (NaNs) across a highly dimensional dataset containing goalkeeping, defending, and mentality attributes.
2. **Dimensionality Reduction (PCA):** Applied Principal Component Analysis (PCA) after standardizing the data (`StandardScaler`) to reduce the +100 feature space down to 10 principal components, retaining the maximum variance and optimizing computational efficiency.
3. **Predictive Modeling:** Deployed regression techniques to map the reduced feature space against the target variable (`overall` / `value_eur`), creating a system that can valuate newly generated players from scratch.

## 📈 Key Takeaways
This project demonstrates the ability to handle wide datasets, avoid the curse of dimensionality using PCA, and extract actionable insights from raw sports data to predict market values.

> **Note:** Code, visualizations, and explained variance charts can be found in the main Jupyter Notebook.
