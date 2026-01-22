# Week 7: Model Evaluation & Selection

## Focus: Cross-validation & Hyperparameter Tuning

---

## Theory (3 hours)

### Theoretical Topics

- Bias-variance tradeoff
- Cross-validation strategies
- K-Fold Cross-Validation
- Stratified K-Fold
- Leave-One-Out Cross-Validation
- Hyperparameter tuning concepts

---

## Practice (4 hours)

### Practical Topics

- K-Fold Cross-Validation
- Grid Search CV
- Random Search CV
- ROC-AUC curves
- Learning curves

### Code Practice

```python
from sklearn.model_selection import cross_val_score, GridSearchCV, RandomizedSearchCV
from sklearn.metrics import roc_curve, auc
```

---

## Project (2 hours)

### Optimize Previous Projects

Revisit and optimize models from earlier weeks.

**Target:** 10%+ improvement in performance

**Steps:**

1. Select best performing project
2. Implement K-Fold cross-validation
3. Apply Grid Search for hyperparameters
4. Apply Random Search comparison
5. Analyze ROC-AUC curves
6. Document improvements

---

## Resources

- Scikit-learn model selection documentation
- Hyperparameter tuning guides

---

## Checklist

- [ ] Understand bias-variance tradeoff
- [ ] Implement K-Fold cross-validation
- [ ] Implement Grid Search CV
- [ ] Implement Random Search CV
- [ ] Master ROC-AUC analysis
- [ ] Achieve 10%+ model improvement
