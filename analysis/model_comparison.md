# Model Comparison

## Purpose
The aim of this analysis is to compare the predictive performance of different regression models built to estimate Monthly Sales. Three models were assessed based on their R² values, statistical significance, and overall business utility.

---

## Models Evaluated

### 1. Marketing Spend Model

* **Independent Variable:** Marketing Spend
* **R²:** 0.167
* **Performance:** Moderate

This model shows a statistically significant association with Monthly Sales but accounts for only a small share of the variation in sales. As a standalone model, its predictive capability is limited.

---

### 2. Footfall Model

* **Independent Variable:** Footfall
* **R²:** 0.736
* **Performance:** Strong

The Footfall model explains a considerably larger portion of the variation in Monthly Sales. It reflects a strong positive relationship and outperforms the Marketing Spend model by a clear margin.

---

### 3. Multiple Regression Model

* **Independent Variables:**
  * Marketing Spend
  * Footfall
  * Inventory Availability
  * Customer Rating
  * Regional Dummy Variables
* **R²:** 0.814
* **Performance:** Very Strong

The Multiple Regression model delivered the highest predictive accuracy of all models tested. By combining several business variables, it explains Monthly Sales more comprehensively than any single-variable approach.

---

## Model Performance Summary

| Model               |    R² | Performance |
| ------------------- | ----: | ----------- |
| Marketing Spend     | 0.167 | Moderate    |
| Footfall            | 0.736 | Strong      |
| Multiple Regression | 0.814 | Very Strong |

---

## Final Observation
The Multiple Regression model was chosen as the final predictive model on account of its highest R² value (0.814). Incorporating multiple business variables strengthened the model's ability to explain Monthly Sales variation and produced the most dependable results for supporting business decision-making.
