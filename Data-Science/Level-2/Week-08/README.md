# Week 8: Feature Engineering & Dimensionality Reduction

## Focus: PCA & Feature Selection

---

## Theory (3 hours)

### Theoretical Topics

- Feature importance techniques
- PCA mathematics and intuition
- Variance explained
- Feature scaling and normalization
- Handling imbalanced datasets

---

## Practice (4 hours)

### Practical Topics

- Principal Component Analysis (PCA)
- Feature scaling (StandardScaler, MinMaxScaler)
- Feature normalization
- Handling imbalanced data (SMOTE, undersampling)
- Feature selection methods

### Code Practice

```python
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler, MinMaxScaler
from imblearn.over_sampling import SMOTE
```

---

## Project (2 hours)

### End-to-End ML Pipeline

Build a complete ML pipeline incorporating all techniques.

**Steps:**

1. Data loading and exploration
2. Feature engineering
3. Apply PCA for dimensionality reduction
4. Handle imbalanced data
5. Model training with pipeline
6. Evaluation and optimization
7. Save pipeline for deployment

---

## Resources

- Scikit-learn Pipeline documentation
- Imbalanced-learn library

---

## Checklist

- [ ] Understand PCA mathematics
- [ ] Implement feature scaling
- [ ] Implement PCA
- [ ] Handle imbalanced datasets
- [ ] Build complete ML pipeline
- [ ] Complete end-to-end project
