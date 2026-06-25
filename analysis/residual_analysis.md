# Residual Analysis

## Objective
Residual analysis was carried out to evaluate how accurately the final Multiple Regression model predicts Monthly Sales. Residuals capture the gap between actual sales figures and the values predicted by the regression model.

---

## Residual Formula

```text
Residual = Actual Monthly Sales − Predicted Monthly Sales
```

---

## Model Used
The residual analysis was performed using the final Multiple Regression model, which includes the following predictors:

* Marketing Spend
* Footfall
* Inventory Availability
* Customer Rating
* Region (Dummy Variables)

This model achieved an R² value of 0.814, reflecting strong overall predictive performance.

---

## Largest Positive Residuals
Records with the largest positive residuals are stores where actual sales came in considerably higher than the model's predictions.

**Business Interpretation**
Possible contributing factors include:

* Stronger customer demand than the model anticipated
* Effective local marketing campaigns
* Seasonal purchasing patterns
* Store-specific operational advantages
* External influences not captured within the regression model

These stores delivered results that exceeded what the model projected.

---

## Largest Negative Residuals
Records with the largest negative residuals are stores where actual sales fell short of predicted values.

**Business Interpretation**
Possible contributing factors include:

* Short-term stock availability issues
* Heightened competition from local rivals
* Lower than expected customer demand
* Operational inefficiencies at store level
* Business conditions not reflected in the model's variables

These stores underdelivered relative to model expectations.

---

## Model Prediction Behaviour
The residual values include both positive and negative observations, indicating that the regression model does not display a consistent tendency to overestimate or underestimate Monthly Sales.

The majority of residuals sit close to zero, suggesting the model produces reliable predictions for most stores in the dataset.

---

## Overall Assessment
The residual analysis reinforces the decision to select the Multiple Regression model as the final predictive model. While a small number of stores exhibit larger prediction errors, the overall distribution of residuals points to solid model performance with no clear evidence of systematic prediction bias.

The model is well-suited for business forecasting and decision-making, with the understanding that certain external factors may still influence individual store outcomes beyond what the model can capture.
