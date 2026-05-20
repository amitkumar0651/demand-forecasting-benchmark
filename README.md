# Demand Forecasting Benchmark 🚀

A comprehensive end-to-end machine learning pipeline for time-series forecasting. This project benchmarks classical statistical methods against state-of-the-art Gradient Boosting frameworks to optimize demand prediction accuracy.

## 📌 Project Summary
This project addresses the challenge of accurate demand forecasting using historical transaction data. By implementing an end-to-end ML pipeline, I compared the effectiveness of traditional statistical time-series modeling with modern gradient-boosted decision trees. 

The focus was on rigorous feature engineering—specifically leveraging lag-based inputs—to transform a raw dataset into a predictive model capable of capturing complex temporal patterns.

## 🏆 Final Performance Results
After benchmarking four distinct models, **CatBoost** emerged as the champion, significantly outperforming both the statistical baseline and other ensemble methods.

| Rank | Model | RMSE |
| :--- | :--- | :--- |
| **1** | **CatBoost** | **2451.82** |
| 2 | XGBoost | 2483.17 |
| 3 | LightGBM | 2751.32 |
| 4 | SARIMA | 22662.95 |

## 🛠 Technical Highlights
*   **Pipeline Architecture:** Developed a modular pipeline covering data cleaning, feature engineering, and cross-validated model evaluation.
*   **Feature Engineering:** Engineered temporal lag features (Lag_1, Lag_7, Lag_30) to provide the models with context on historical sales trends.
*   **Optimization:** Achieved an **~89% reduction in RMSE** compared to the classical SARIMA baseline.
*   **Tech Stack:** Python, Pandas, Statsmodels, CatBoost, XGBoost, LightGBM, Scikit-Learn.

---
*Developed by Amit Kumar | AI & Data Science Specialist*
