# Week 5: Support Vector Machines & KNN

## Focus: SVM and K-Nearest Neighbors

---

## Theory (3 hours)

### Theoretical Topics

- SVM kernels (Linear, RBF, Polynomial)
- Margin optimization
- Kernel trick
- Distance metrics (Euclidean, Manhattan)
- KNN algorithm

---

## Practice (4 hours)

### Practical Topics

- Linear SVM
- Kernel SVM (RBF, Polynomial)
- K-Nearest Neighbors
- Hyperparameter tuning for SVM and KNN

### Code Practice

```python
from sklearn.svm import SVC
from sklearn.neighbors import KNeighborsClassifier
from sklearn.model_selection import GridSearchCV
```

---

## Project (2 hours)

### Image Classification (Digit Recognition)

Build SVM and KNN models for digit classification.

**Dataset:** MNIST or similar

**Steps:**

1. Load MNIST dataset
2. Preprocess images (flatten, normalize)
3. Train Linear SVM
4. Train Kernel SVM
5. Train KNN classifier
6. Compare model performances
7. Tune hyperparameters

---

## Resources

- MNIST dataset
- Scikit-learn SVM documentation

---

## Checklist

- [ ] Understand SVM concepts and kernels
- [ ] Understand KNN algorithm
- [ ] Implement Linear and Kernel SVM
- [ ] Implement KNN classifier
- [ ] Complete digit recognition project
