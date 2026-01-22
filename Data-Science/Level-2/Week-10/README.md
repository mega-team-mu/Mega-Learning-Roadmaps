# Week 10: Deep Neural Networks

## Focus: Multi-layer Networks & Optimization

---

## Theory (3 hours)

### Theoretical Topics

- Deep architectures design
- Vanishing/exploding gradients problem
- Optimizers:
  - SGD
  - Adam
  - RMSprop
- Learning rate scheduling

---

## Practice (4 hours)

### Practical Topics

- Build 3+ layer networks
- Batch normalization
- Dropout regularization
- Different optimizers
- Early stopping

### Code Practice

```python
from keras.layers import Dense, Dropout, BatchNormalization
from keras.callbacks import EarlyStopping
from keras.optimizers import Adam, RMSprop
```

---

## Project (2 hours)

### Multi-class Classification

Build a deep neural network for Fashion MNIST.

**Dataset:** Fashion MNIST

**Steps:**

1. Load Fashion MNIST dataset
2. Preprocess images
3. Build deep network (3+ layers)
4. Apply batch normalization
5. Apply dropout
6. Train with Adam optimizer
7. Evaluate on test set

---

## Resources

- Fashion MNIST dataset
- Keras optimizers documentation

---

## Checklist

- [ ] Understand deep architecture design
- [ ] Understand gradient problems and solutions
- [ ] Implement batch normalization
- [ ] Implement dropout
- [ ] Use different optimizers
- [ ] Complete Fashion MNIST project
