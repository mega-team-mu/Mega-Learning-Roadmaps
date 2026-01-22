# Week 2: Regression Techniques

## Focus: Advanced Regression Models

---

## Theory (3 hours)

### Theoretical Topics

- Regularization techniques (L1/L2)
- Overfitting vs Underfitting
- Bias-Variance tradeoff
- When to use different regression types

---

## Practice (4 hours)

### Practical Topics

- Polynomial Regression
- Ridge Regression (L2 regularization)
- Lasso Regression (L1 regularization)
- Elastic Net (L1 + L2 combined)

### Code Practice

```python
from sklearn.linear_model import Ridge, Lasso, ElasticNet
from sklearn.preprocessing import PolynomialFeatures
```

---

## Project (2 hours)

### Sales Forecasting with Regularized Regression

Build and compare different regression models for sales prediction.

**Deliverable:** Model performance comparison report

**Steps:**

1. Load sales dataset
2. Apply feature engineering
3. Train Ridge, Lasso, and Elastic Net models
4. Compare performance metrics
5. Analyze regularization effects

---

## Resources

- Scikit-learn regularization documentation
- Cross-validation techniques

---

## Checklist

- [ ] Understand regularization concepts
- [ ] Implement Polynomial Regression
- [ ] Implement Ridge and Lasso Regression
- [ ] Complete sales forecasting project
- [ ] Create model comparison report
