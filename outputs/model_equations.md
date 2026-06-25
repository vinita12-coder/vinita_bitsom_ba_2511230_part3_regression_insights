# Model Equations

## Overview
Three regression models were built to estimate **Monthly Sales**. Two simple linear regression models were developed using individual predictors, followed by a Multiple Linear Regression model that combines several business variables to achieve greater prediction accuracy.

---

# 1. Simple Linear Regression – Marketing Spend

### Equation

```text
Monthly Sales = 178,413.78 + 2.13 × (Marketing Spend)
```

### Interpretation
The coefficient indicates that for every one-unit rise in Marketing Spend, Monthly Sales are expected to increase by approximately **2.13 units**, assuming all other factors remain constant.

**Model Performance**

* R² = **0.167**
* Prediction Strength: **Moderate**

---

# 2. Simple Linear Regression – Footfall

### Equation

```text
Monthly Sales = 72,454.09 + 35.68 × (Footfall)
```

### Interpretation
The model suggests that each additional customer visit is associated with an increase of approximately **35.68 units** in Monthly Sales.

**Model Performance**

* R² = **0.736**
* Prediction Strength: **Strong**

---

# 3. Multiple Linear Regression (Final Model)

### Equation

```text
Monthly Sales =
89,639.79
+ 1.20 × Marketing Spend
+ 33.98 × Footfall
+ 2886.74 × Inventory Availability
+ 11024.99 × Customer Rating
+ 13305.30 × Region South
- 8667.13 × Region West
+ 8375.71 × Region East
```

> **Reference Category:** North Region

---

## Model Interpretation
The Multiple Linear Regression model estimates Monthly Sales by drawing on a combination of operational and customer-related variables. Positive coefficients indicate that an increase in a given predictor is associated with higher sales, while negative coefficients reflect a decline relative to the reference category.

Regional coefficients should be read in comparison with the **North** region, which serves as the baseline reference category.

---

## Final Model Selection
Among all three regression models, the **Multiple Linear Regression** model delivered the highest predictive performance with an **R² value of 0.814**.

This model was selected because it accounts for the combined effect of multiple business factors and provides the most accurate estimation of Monthly Sales.

---

## Summary

| Model                      |    R² | Selected |
| -------------------------- | ----: | :------: |
| Marketing Spend            | 0.167 |    No    |
| Footfall                   | 0.736 |    No    |
| Multiple Linear Regression | 0.814 |   ✅ Yes  |

The Multiple Linear Regression model is recommended for future forecasting and business decision-making given its superior explanatory power and predictive capability.
