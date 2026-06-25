# Part 3 – Regression Insights

## Project Overview
This project applies regression analysis techniques to uncover the key business factors driving monthly retail sales. The work spans simple linear regression, multiple linear regression, model comparison, and residual analysis to assess predictive performance.

---

## Objective
The core objectives of this project are to:

* Understand how business variables relate to monthly sales outcomes.
* Compare the performance of simple and multiple regression models.
* Determine the most reliable model for prediction.
* Translate regression outputs into actionable business insights.

---

## Folder Structure

```
part3_regression_insights/
│
├── data/
│   └── business_regression_data.xlsx
│
├── analysis/
│   ├── regression_workbook.xlsx
│   ├── model_comparison.md
│   └── residual_analysis.md
│
├── outputs/
│   ├── regression_summary.xlsx
│   ├── model_equations.md
│   └── final_recommendation.md
│
├── screenshots/
│   ├── simple_regression_output.png
│   ├── multiple_regression_output.png
│   ├── residuals_preview.png
│   └── model_comparison_preview.png
│
└── README.md
```

---

## Analysis Performed

### 1. Simple Linear Regression

* Marketing Spend → Monthly Sales
* Footfall → Monthly Sales

### 2. Multiple Linear Regression
The final multiple regression model incorporated the following variables:

* Marketing Spend
* Footfall
* Inventory Availability
* Customer Rating
* Regional Dummy Variables

### 3. Residual Analysis
Residual values were reviewed to assess prediction errors and confirm the overall reliability of the regression model.

### 4. Model Comparison
All regression models were evaluated and ranked based on R² values, statistical significance, and predictive capability.

---

## Key Findings

* The Footfall model outperformed the Marketing Spend model by a considerable margin.
* The Multiple Regression model achieved the highest explanatory power with an R² of 0.814.
* Marketing Spend, Footfall, Inventory Availability, and Customer Rating all emerged as statistically significant predictors.
* Regional dummy variables did not reach statistical significance in the final model.

---

## Conclusion
Based on the regression analysis, the Multiple Regression model was selected as the final predictive model. It accounted for the largest share of variation in Monthly Sales and delivered the strongest overall predictive performance among all models evaluated.
