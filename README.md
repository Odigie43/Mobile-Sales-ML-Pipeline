# Mobile Sales ML Pipeline

## Data-Driven Sales Performance Analysis and Predictive Forecasting for Business Decision-Making

A Python-based data analytics and machine learning research project investigating product sales performance, revenue estimation, predictive modelling and business decision support.

## Research Overview

This project analyses 50,000 sales observations involving mobile phones and laptops. It applies exploratory data analysis, data preprocessing, feature engineering, statistical visualisation and comparative machine learning techniques to investigate revenue patterns and evaluate regression model performance.

The research examines product categories, brands, regional performance, pricing, quantities sold and product specifications.

## Dataset

- **Total observations:** 50,000
- **Product categories:** Mobile Phones and Laptops
- **Key variables:** Product, Brand, Price, Quantity Sold, Region, Processor Specification, RAM, ROM, SSD, Delivery Days, Inward Month, Inward Year and Inward Quarter
- **Target variable:** Revenue
- **Revenue calculation:** Price × Quantity Sold

The dataset's source and redistribution permissions should be documented before public release.

## Machine Learning Models

Seven regression algorithms were evaluated.

| Model | R² | MAE | RMSE | MAPE |
|---|---|---|---|---|
| Random Forest | 1.0000 | 169.66 | 267.28 | 0.06% |
| XGBoost | 1.0000 | 227.79 | 346.57 | 0.08% |
| Gradient Boosting | 1.0000 | 469.48 | 698.30 | 0.16% |
| Decision Tree | 1.0000 | 507.96 | 850.91 | 0.18% |
| Ridge Regression | 0.9995 | 3,946.82 | 5,054.65 | 1.39% |
| Lasso Regression | 0.9995 | 3,948.33 | 5,055.38 | 1.39% |
| Linear Regression | 0.9995 | 3,946.82 | 5,054.65 | 1.39% |

*These metrics are reported from the project notebook and should be verified against the final saved results before publication.*

### Best Performing Model

Random Forest achieved the lowest reported prediction errors:

- R²: 1.0000 (rounded)
- MAE: 169.66
- RMSE: 267.28
- MAPE: 0.06%

Five-fold cross-validation produced an average MAE of approximately 174 and RMSE of 272.

## Methodological Limitation

Revenue is calculated directly from Price and Quantity Sold. Consequently, the exceptionally high model accuracy may primarily reflect reconstruction of this mathematical relationship rather than independent forecasting of future sales.

The current results should therefore be interpreted as revenue estimation rather than validated future sales forecasting. Future research will investigate chronological validation and prediction using information available before transactions occur.

## Research Methodology

1. Data loading and exploratory data analysis
2. Data cleaning and preprocessing
3. Feature engineering and categorical encoding
4. Training and testing dataset preparation
5. Comparative regression model training
6. Hyperparameter optimisation
7. Five-fold cross-validation
8. Performance evaluation using R², MAE, RMSE and MAPE
9. Revenue distribution and sales performance visualisation
10. Interpretation of findings and business implications

## Research Team and Contributions

**Engr. Emmanuel Odigie Okohe — Lead Researcher and Developer**

Responsible for research implementation, Python programming, exploratory data analysis, feature engineering, machine learning model development, visualisation, performance evaluation and interpretation of findings.

**Professor Frank Iwebuke Amadin — Academic Manuscript Reviewer**

Reviewed the research manuscript and assisted with identifying a suitable research dataset.

**Uwadi Emovon — Technical Code Reviewer**

Reviewed the Python implementation and assisted with identifying a suitable research dataset.

These contribution descriptions acknowledge the research team's involvement without implying independent journal peer review.

## Research Applications

The analytical workflow can support:

- Sales performance monitoring
- Product and regional performance analysis
- Pricing and revenue analysis
- Business intelligence reporting
- Machine learning model comparison
- Development of future demand forecasting systems

## Publication

**Research title:** Data-Driven Sales Performance Analysis and Predictive Forecasting for Business Decision-Making: A Comparative Machine Learning Approach

**Repository:** Zenodo

**DOI:** (https://doi.org/10.5281/zenodo.23698753)

The manuscript has undergone academic manuscript review and technical code review. It should not be described as formally journal peer-reviewed unless a separate qualifying peer-review process has been completed.

## Licence

The Python source code is released under the MIT License, subject to the repository's LICENSE file.

The research manuscript may be distributed separately under Creative Commons Attribution 4.0 International (CC BY 4.0).

Dataset and third-party material remain subject to their respective licences.

## Acknowledgements

Acknowledgement is given to Professor Frank Iwebuke Amadin for academic manuscript review and Uwadi Emovon for technical code review, as well as their assistance in identifying a suitable research dataset.

© 2026 Engr. Emmanuel Odigie Okohe. Code copyright subject to any applicable joint ownership arrangements.
