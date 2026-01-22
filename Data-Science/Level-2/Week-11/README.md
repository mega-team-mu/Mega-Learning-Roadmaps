# Week 11: Convolutional Neural Networks (CNN) - Part 1

## Focus: CNN Architecture & Image Processing

---

## Theory (3 hours)

### Theoretical Topics

- Convolution operation
- Feature maps
- Pooling layers (Max, Average)
- CNN layer types
- Image preprocessing

---

## Practice (4 hours)

### Practical Topics

- Conv2D layers
- MaxPooling layers
- Flatten and Dense layers
- Data augmentation
- Image data generators

### Code Practice

```python
from keras.layers import Conv2D, MaxPooling2D, Flatten
from keras.preprocessing.image import ImageDataGenerator
```

---

## Project (2 hours)

### Image Classification (CIFAR-10)

Build a CNN for CIFAR-10 classification.

**Dataset:** CIFAR-10 (10 classes)

**Steps:**

1. Load CIFAR-10 dataset
2. Preprocess images
3. Apply data augmentation
4. Build CNN architecture
5. Train model
6. Evaluate accuracy

---

## Resources

- CIFAR-10 dataset
- Keras Conv2D documentation

---

## Checklist

- [ ] Understand convolution operation
- [ ] Understand pooling layers
- [ ] Implement Conv2D layers
- [ ] Implement data augmentation
- [ ] Complete CIFAR-10 project
