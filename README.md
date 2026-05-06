# African Banking Crisis Analysis (1860–2014)

## Project Overview
This project provides a comprehensive data science analysis of economic, banking, and systemic crises in 13 African countries. Spanning over 150 years of data, the study identifies key economic indicators—such as inflation, sovereign debt default, and systemic stress—that serve as early warning signals for banking instability.

**Author:** Feven

## Key Objectives
- **Exploratory Data Analysis (EDA):** Visualize historical trends and the frequency of crises across nations like Egypt, Nigeria, and South Africa.
- **Statistical Hypothesis Testing:** Statistically validate the relationship between inflation, debt defaults, and systemic banking crises.
- **Predictive Modeling:** Develop a Logistic Regression model to predict the probability of a banking crisis based on real-time economic indicators.
- **Strategic Decision Support:** Provide actionable insights through a National Vulnerability Index and feature importance analysis.

## Core Findings
- **Inflation Thresholds:** Banking crises are significantly associated with high and volatile inflation rates.
- **Debt-Crisis Link:** Sovereign external debt defaults are a primary red flag for systemic banking instability.
- **High Accuracy Prediction:** The Logistic Regression model achieves high predictive performance (ROC-AUC > 0.98), making it a viable tool for early warning systems.

## Dataset
The analysis uses the "Africa Economic, Banking, and Systemic Crisis" dataset, which includes data for Algeria, Angola, Central African Republic, Ivory Coast, Egypt, Kenya, Mauritius, Morocco, Nigeria, South Africa, Tunisia, Zambia, and Zimbabwe.

## Technologies Used
- **Python** (Pandas, NumPy, Scipy)
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn

## How to Run
1. Clone this repository.
2. Ensure you have the required dependencies installed: `pip install pandas numpy matplotlib seaborn scikit-learn scipy`.
3. Open `Feven_Ethiopia_Final_project.ipynb` in a Jupyter environment.
4. Run all cells to reproduce the analysis.
